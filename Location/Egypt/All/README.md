Linux in Egypt - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Egypt.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Egypt/Desktop/README.md) and [notebooks](/Location/Egypt/Notebook/README.md).

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

Total: 1301

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Pavilion dv6                | Notebook    | [f5588fa17c](https://linux-hardware.org/?probe=f5588fa17c) | Jan 03, 2026 |
| Toshiba       | Satellite C660              | Notebook    | [050e673661](https://linux-hardware.org/?probe=050e673661) | Jan 02, 2026 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [86fd33cc78](https://linux-hardware.org/?probe=86fd33cc78) | Dec 29, 2025 |
| Dell          | Precision 3510              | Notebook    | [bc2b9346a8](https://linux-hardware.org/?probe=bc2b9346a8) | Dec 26, 2025 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | Notebook    | [1ab8fce0d9](https://linux-hardware.org/?probe=1ab8fce0d9) | Dec 23, 2025 |
| HP            | 3032h                       | Desktop     | [2677e76ffa](https://linux-hardware.org/?probe=2677e76ffa) | Dec 23, 2025 |
| Dell          | 0WWJRX A00                  | Desktop     | [c495486733](https://linux-hardware.org/?probe=c495486733) | Dec 22, 2025 |
| Cherry        | ZE03                        | Tablet      | [c57675791a](https://linux-hardware.org/?probe=c57675791a) | Dec 21, 2025 |
| HP            | 8265                        | Desktop     | [bc9655d1c7](https://linux-hardware.org/?probe=bc9655d1c7) | Dec 18, 2025 |
| Dell          | Inspiron 5520               | Notebook    | [308195cc57](https://linux-hardware.org/?probe=308195cc57) | Dec 15, 2025 |
| HP            | 3031h                       | Desktop     | [68b5d8293b](https://linux-hardware.org/?probe=68b5d8293b) | Dec 13, 2025 |
| HP            | 3031h                       | Desktop     | [a8df00a12c](https://linux-hardware.org/?probe=a8df00a12c) | Dec 13, 2025 |
| Acer          | TravelMate P648-M           | Notebook    | [c0a98b9939](https://linux-hardware.org/?probe=c0a98b9939) | Dec 13, 2025 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [0526edbed2](https://linux-hardware.org/?probe=0526edbed2) | Dec 07, 2025 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [5ece52a259](https://linux-hardware.org/?probe=5ece52a259) | Dec 06, 2025 |
| HP            | ProBook 6475b               | Notebook    | [00eb32da0d](https://linux-hardware.org/?probe=00eb32da0d) | Nov 30, 2025 |
| Dell          | Inspiron 3593               | Notebook    | [4d6848cbbe](https://linux-hardware.org/?probe=4d6848cbbe) | Nov 28, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [9693ca4d23](https://linux-hardware.org/?probe=9693ca4d23) | Nov 25, 2025 |
| Dell          | Inspiron 3420               | Notebook    | [e7b9c0a99c](https://linux-hardware.org/?probe=e7b9c0a99c) | Nov 22, 2025 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [697d0f6a95](https://linux-hardware.org/?probe=697d0f6a95) | Nov 18, 2025 |
| Lenovo        | NOK                         | Desktop     | [422ad35193](https://linux-hardware.org/?probe=422ad35193) | Nov 11, 2025 |
| Dell          | Inspiron 3593               | Notebook    | [d081ec10ae](https://linux-hardware.org/?probe=d081ec10ae) | Nov 08, 2025 |
| HP            | ZBook 15u G6                | Notebook    | [83a6b26777](https://linux-hardware.org/?probe=83a6b26777) | Nov 07, 2025 |
| HP            | ZBook 15u G6                | Notebook    | [ec2aa9a549](https://linux-hardware.org/?probe=ec2aa9a549) | Nov 07, 2025 |
| Dell          | Precision 5550              | Notebook    | [ca3bf54288](https://linux-hardware.org/?probe=ca3bf54288) | Nov 06, 2025 |
| HP            | 18E7                        | Desktop     | [8a7fccab07](https://linux-hardware.org/?probe=8a7fccab07) | Nov 06, 2025 |
| Fujitsu Si... | D2594-A1 S26361-D2594-A1    | Desktop     | [fbba371855](https://linux-hardware.org/?probe=fbba371855) | Nov 05, 2025 |
| Toshiba       | Satellite C660              | Notebook    | [90b7822ac3](https://linux-hardware.org/?probe=90b7822ac3) | Nov 02, 2025 |
| Acer          | TravelMate P633-M           | Notebook    | [b180598624](https://linux-hardware.org/?probe=b180598624) | Nov 01, 2025 |
| Acer          | TravelMate P633-M           | Notebook    | [df99fc55f8](https://linux-hardware.org/?probe=df99fc55f8) | Nov 01, 2025 |
| MSI           | Cyborg 15 A13VE             | Notebook    | [e2e5290bd7](https://linux-hardware.org/?probe=e2e5290bd7) | Nov 01, 2025 |
| HP            | Pavilion x360 Convertibl... | Convertible | [042a9aa4ac](https://linux-hardware.org/?probe=042a9aa4ac) | Oct 31, 2025 |
| Acer          | Aspire A315-56              | Notebook    | [fe5af2a1d9](https://linux-hardware.org/?probe=fe5af2a1d9) | Oct 31, 2025 |
| Google        | Fleex                       | Notebook    | [93c6ddedb8](https://linux-hardware.org/?probe=93c6ddedb8) | Oct 26, 2025 |
| Dell          | 0Y9655                      | Desktop     | [2a5fa0d0ff](https://linux-hardware.org/?probe=2a5fa0d0ff) | Oct 24, 2025 |
| ASUSTek       | ASUS Vivobook Pro 15 N65... | Notebook    | [bd284e6d3a](https://linux-hardware.org/?probe=bd284e6d3a) | Oct 23, 2025 |
| ASUSTek       | ASUS Vivobook Pro 15 N65... | Notebook    | [858e18bde6](https://linux-hardware.org/?probe=858e18bde6) | Oct 23, 2025 |
| Dell          | Inspiron 3521               | Notebook    | [7e5b0f53eb](https://linux-hardware.org/?probe=7e5b0f53eb) | Oct 23, 2025 |
| HP            | EliteBook 745 G6            | Notebook    | [83a1710405](https://linux-hardware.org/?probe=83a1710405) | Oct 21, 2025 |
| ASUSTek       | ProArt PX13 HN7306WI_HN7... | Convertible | [3fecb6fffe](https://linux-hardware.org/?probe=3fecb6fffe) | Oct 21, 2025 |
| Gigabyte      | H61M-S2P                    | Desktop     | [cd25fdddc2](https://linux-hardware.org/?probe=cd25fdddc2) | Oct 21, 2025 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [4e8bab0faa](https://linux-hardware.org/?probe=4e8bab0faa) | Oct 18, 2025 |
| Samsung       | RV409/RV509/RV709           | Notebook    | [bf2212cc1e](https://linux-hardware.org/?probe=bf2212cc1e) | Oct 16, 2025 |
| ASUSTek       | PRIME H610M-D D4            | Desktop     | [d3e41e3f05](https://linux-hardware.org/?probe=d3e41e3f05) | Oct 16, 2025 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a9fca8f1ec](https://linux-hardware.org/?probe=a9fca8f1ec) | Oct 13, 2025 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [e642ef7f74](https://linux-hardware.org/?probe=e642ef7f74) | Oct 13, 2025 |
| Dell          | G15 5515                    | Notebook    | [13add03f14](https://linux-hardware.org/?probe=13add03f14) | Oct 05, 2025 |
| HP            | ElitePad 1000 G2            | Notebook    | [3cb789f09c](https://linux-hardware.org/?probe=3cb789f09c) | Oct 05, 2025 |
| Dell          | G15 5511                    | Notebook    | [64922e9eee](https://linux-hardware.org/?probe=64922e9eee) | Oct 04, 2025 |
| Dell          | Inspiron 3593               | Notebook    | [0e580b8d29](https://linux-hardware.org/?probe=0e580b8d29) | Oct 03, 2025 |
| Lenovo        | G510 20238                  | Notebook    | [19292b0e4c](https://linux-hardware.org/?probe=19292b0e4c) | Sep 30, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [f5e8a4bdf7](https://linux-hardware.org/?probe=f5e8a4bdf7) | Sep 23, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [a364f89143](https://linux-hardware.org/?probe=a364f89143) | Sep 22, 2025 |
| HP            | 8455                        | Desktop     | [77fa51097c](https://linux-hardware.org/?probe=77fa51097c) | Sep 21, 2025 |
| Dell          | Inspiron 3593               | Notebook    | [9c7d57832e](https://linux-hardware.org/?probe=9c7d57832e) | Sep 20, 2025 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [410536c62e](https://linux-hardware.org/?probe=410536c62e) | Sep 20, 2025 |
| Dell          | Precision M4800             | Notebook    | [b560fc1daf](https://linux-hardware.org/?probe=b560fc1daf) | Sep 18, 2025 |
| Acer          | Aspire A315-58G             | Notebook    | [a49941ec3d](https://linux-hardware.org/?probe=a49941ec3d) | Sep 17, 2025 |
| Lenovo        | ThinkPad X200s 7470DH5      | Notebook    | [7a45dc0d70](https://linux-hardware.org/?probe=7a45dc0d70) | Sep 16, 2025 |
| Dell          | Inspiron N5110              | Notebook    | [128da64491](https://linux-hardware.org/?probe=128da64491) | Sep 16, 2025 |
| Lenovo        | ThinkPad X200s 7470DH5      | Notebook    | [424467e9f2](https://linux-hardware.org/?probe=424467e9f2) | Sep 10, 2025 |
| HP            | Notebook                    | Notebook    | [8b6c254f73](https://linux-hardware.org/?probe=8b6c254f73) | Sep 10, 2025 |
| HP            | 158B                        | Desktop     | [ca916ef5b2](https://linux-hardware.org/?probe=ca916ef5b2) | Sep 07, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [da744d8835](https://linux-hardware.org/?probe=da744d8835) | Sep 05, 2025 |
| HP            | Pavilion dv6                | Notebook    | [83ad06d612](https://linux-hardware.org/?probe=83ad06d612) | Aug 24, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [528ee01d6f](https://linux-hardware.org/?probe=528ee01d6f) | Aug 23, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [b4b0bb1b9a](https://linux-hardware.org/?probe=b4b0bb1b9a) | Aug 23, 2025 |
| HP            | 158B                        | Desktop     | [b330c07f12](https://linux-hardware.org/?probe=b330c07f12) | Aug 21, 2025 |
| HP            | 18E7                        | Desktop     | [42e6b96722](https://linux-hardware.org/?probe=42e6b96722) | Aug 18, 2025 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [61c9468332](https://linux-hardware.org/?probe=61c9468332) | Aug 14, 2025 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [c15d2ef43e](https://linux-hardware.org/?probe=c15d2ef43e) | Aug 13, 2025 |
| HP            | 3047h                       | Desktop     | [4330166a7a](https://linux-hardware.org/?probe=4330166a7a) | Aug 11, 2025 |
| Gigabyte      | H310M S2                    | Desktop     | [c3ec54ad8b](https://linux-hardware.org/?probe=c3ec54ad8b) | Aug 07, 2025 |
| Dell          | Latitude E7450              | Notebook    | [5c7fdef9c4](https://linux-hardware.org/?probe=5c7fdef9c4) | Aug 06, 2025 |
| Toshiba       | T20                         | Notebook    | [7a0cf89b6e](https://linux-hardware.org/?probe=7a0cf89b6e) | Aug 01, 2025 |
| Toshiba       | Satellite C850D-B541        | Notebook    | [a6ac7b9903](https://linux-hardware.org/?probe=a6ac7b9903) | Jul 28, 2025 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [99c1c89581](https://linux-hardware.org/?probe=99c1c89581) | Jul 28, 2025 |
| Acer          | Veriton M4630G V:1.0        | Desktop     | [03dc58eed4](https://linux-hardware.org/?probe=03dc58eed4) | Jul 27, 2025 |
| Gigabyte      | H310M S2                    | Desktop     | [c02c9e1263](https://linux-hardware.org/?probe=c02c9e1263) | Jul 22, 2025 |
| Dell          | Latitude E5440              | Notebook    | [5815a288c4](https://linux-hardware.org/?probe=5815a288c4) | Jul 21, 2025 |
| Toshiba       | Satellite C660              | Notebook    | [6ffd323933](https://linux-hardware.org/?probe=6ffd323933) | Jul 21, 2025 |
| HP            | 8265                        | Desktop     | [d33e774855](https://linux-hardware.org/?probe=d33e774855) | Jul 20, 2025 |
| Dell          | Inspiron 7405 2n1           | Convertible | [c4b2ddc6c3](https://linux-hardware.org/?probe=c4b2ddc6c3) | Jul 19, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [a085f23042](https://linux-hardware.org/?probe=a085f23042) | Jul 17, 2025 |
| Dell          | Latitude E5470              | Notebook    | [2775415c7e](https://linux-hardware.org/?probe=2775415c7e) | Jul 15, 2025 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [e2254ece26](https://linux-hardware.org/?probe=e2254ece26) | Jul 15, 2025 |
| Dell          | Latitude E5420              | Notebook    | [53a3a12e68](https://linux-hardware.org/?probe=53a3a12e68) | Jul 10, 2025 |
| Dell          | Latitude E5420              | Notebook    | [7b5452450c](https://linux-hardware.org/?probe=7b5452450c) | Jul 10, 2025 |
| Dell          | G15 5515                    | Notebook    | [2f6024a6c5](https://linux-hardware.org/?probe=2f6024a6c5) | Jul 05, 2025 |
| HP            | EliteBook 2540p             | Notebook    | [f9b77e1f7f](https://linux-hardware.org/?probe=f9b77e1f7f) | Jul 05, 2025 |
| HP            | Notebook                    | Notebook    | [621cac5cef](https://linux-hardware.org/?probe=621cac5cef) | Jul 03, 2025 |
| HP            | 215 G1                      | Notebook    | [797f49da63](https://linux-hardware.org/?probe=797f49da63) | Jun 29, 2025 |
| HP            | Unknown                     | Notebook    | [bad4801691](https://linux-hardware.org/?probe=bad4801691) | Jun 28, 2025 |
| Dell          | 0VHWTR A01                  | Desktop     | [5f23434d5d](https://linux-hardware.org/?probe=5f23434d5d) | Jun 27, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | Notebook    | [1797f5b3a6](https://linux-hardware.org/?probe=1797f5b3a6) | Jun 27, 2025 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0c07f0bed4](https://linux-hardware.org/?probe=0c07f0bed4) | Jun 26, 2025 |
| Dell          | 06D7TR A00                  | Desktop     | [015d2cf526](https://linux-hardware.org/?probe=015d2cf526) | Jun 23, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | Notebook    | [67f8325fda](https://linux-hardware.org/?probe=67f8325fda) | Jun 21, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | Notebook    | [3e43a4f20d](https://linux-hardware.org/?probe=3e43a4f20d) | Jun 21, 2025 |
| HP            | 2215                        | Desktop     | [5efb489e32](https://linux-hardware.org/?probe=5efb489e32) | Jun 20, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [a63035a575](https://linux-hardware.org/?probe=a63035a575) | Jun 20, 2025 |
| Lenovo        | G50-70 20351                | Notebook    | [4484fb3a90](https://linux-hardware.org/?probe=4484fb3a90) | Jun 18, 2025 |
| Lenovo        | G50-70 20351                | Notebook    | [125d269f18](https://linux-hardware.org/?probe=125d269f18) | Jun 17, 2025 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [d7dcc77ef4](https://linux-hardware.org/?probe=d7dcc77ef4) | Jun 10, 2025 |
| Dell          | 09KPNV A00                  | Desktop     | [18576eca95](https://linux-hardware.org/?probe=18576eca95) | Jun 07, 2025 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [c107b5993c](https://linux-hardware.org/?probe=c107b5993c) | Jun 05, 2025 |
| HP            | 1850                        | Desktop     | [8b4b91570c](https://linux-hardware.org/?probe=8b4b91570c) | Jun 03, 2025 |
| HP            | 1850                        | Desktop     | [9237575fda](https://linux-hardware.org/?probe=9237575fda) | Jun 03, 2025 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4e5c695e1a](https://linux-hardware.org/?probe=4e5c695e1a) | May 31, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2fe3106c34](https://linux-hardware.org/?probe=2fe3106c34) | May 31, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [01649c1e77](https://linux-hardware.org/?probe=01649c1e77) | May 31, 2025 |
| HP            | 158B                        | Desktop     | [2bfaadf6f1](https://linux-hardware.org/?probe=2bfaadf6f1) | May 29, 2025 |
| ASUSTek       | UX360UAK                    | Convertible | [ef99f952d6](https://linux-hardware.org/?probe=ef99f952d6) | May 28, 2025 |
| Clevo         | W150HNM/W170HN              | Notebook    | [16efffe0c8](https://linux-hardware.org/?probe=16efffe0c8) | May 27, 2025 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [a220a11c8b](https://linux-hardware.org/?probe=a220a11c8b) | May 24, 2025 |
| Dell          | 0M5WNK A00                  | Desktop     | [969276d51a](https://linux-hardware.org/?probe=969276d51a) | May 23, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [de6813611a](https://linux-hardware.org/?probe=de6813611a) | May 23, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [e40233b293](https://linux-hardware.org/?probe=e40233b293) | May 23, 2025 |
| Dell          | Inspiron 3521               | Notebook    | [8382441b90](https://linux-hardware.org/?probe=8382441b90) | May 22, 2025 |
| Acer          | Aspire 5741G                | Notebook    | [42ed2de824](https://linux-hardware.org/?probe=42ed2de824) | May 21, 2025 |
| Fujitsu       | FMVS75MWP                   | Notebook    | [91ff517514](https://linux-hardware.org/?probe=91ff517514) | May 21, 2025 |
| HP            | x2 210 G2                   | Tablet      | [3b69455bad](https://linux-hardware.org/?probe=3b69455bad) | May 18, 2025 |
| Foxconn       | 17A0                        | Desktop     | [60ebdf150e](https://linux-hardware.org/?probe=60ebdf150e) | May 18, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M640... | Notebook    | [681c2b2a5b](https://linux-hardware.org/?probe=681c2b2a5b) | May 18, 2025 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [7f727e7b41](https://linux-hardware.org/?probe=7f727e7b41) | May 17, 2025 |
| Dell          | Inspiron 5521               | Notebook    | [d2352cf808](https://linux-hardware.org/?probe=d2352cf808) | May 15, 2025 |
| Dell          | Inspiron 5521               | Notebook    | [28cc25da02](https://linux-hardware.org/?probe=28cc25da02) | May 15, 2025 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [8b15d2ba3e](https://linux-hardware.org/?probe=8b15d2ba3e) | May 14, 2025 |
| Dell          | Latitude E6440              | Notebook    | [e8b6a014ef](https://linux-hardware.org/?probe=e8b6a014ef) | May 14, 2025 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [7811ee9979](https://linux-hardware.org/?probe=7811ee9979) | May 13, 2025 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [8874c904b3](https://linux-hardware.org/?probe=8874c904b3) | May 12, 2025 |
| Apple         | MacBookPro11,5              | Notebook    | [a47ea20a83](https://linux-hardware.org/?probe=a47ea20a83) | May 12, 2025 |
| Apple         | MacBookPro11,5              | Notebook    | [455bbfdfb5](https://linux-hardware.org/?probe=455bbfdfb5) | May 12, 2025 |
| HP            | EliteBook 840 G1            | Notebook    | [164fd32025](https://linux-hardware.org/?probe=164fd32025) | May 11, 2025 |
| Dell          | Latitude E5570              | Notebook    | [59a9bc5d6e](https://linux-hardware.org/?probe=59a9bc5d6e) | May 10, 2025 |
| Dell          | Latitude E5570              | Notebook    | [25d9722587](https://linux-hardware.org/?probe=25d9722587) | May 10, 2025 |
| MSI           | Sword 16 HX B13VFKG         | Notebook    | [b4a4f3d64e](https://linux-hardware.org/?probe=b4a4f3d64e) | May 10, 2025 |
| Foxconn       | 17A0                        | Desktop     | [f41834b4d3](https://linux-hardware.org/?probe=f41834b4d3) | May 08, 2025 |
| Dell          | 0XHGV1 A01                  | Desktop     | [ef61650adc](https://linux-hardware.org/?probe=ef61650adc) | May 08, 2025 |
| Dell          | Latitude E5570              | Notebook    | [39d284edef](https://linux-hardware.org/?probe=39d284edef) | May 02, 2025 |
| ASUSTek       | PRIME H610M-D D4            | Desktop     | [744ddeb617](https://linux-hardware.org/?probe=744ddeb617) | May 02, 2025 |
| Dell          | Inspiron 3537               | Notebook    | [0210cf011f](https://linux-hardware.org/?probe=0210cf011f) | May 01, 2025 |
| Dell          | Latitude E5470              | Notebook    | [df83165e0d](https://linux-hardware.org/?probe=df83165e0d) | Apr 29, 2025 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [4daf2a4b57](https://linux-hardware.org/?probe=4daf2a4b57) | Apr 28, 2025 |
| HUAWEI        | MRC-WX0                     | Notebook    | [82e5622af9](https://linux-hardware.org/?probe=82e5622af9) | Apr 27, 2025 |
| Acer          | Aspire A315-56              | Notebook    | [5f5150ad43](https://linux-hardware.org/?probe=5f5150ad43) | Apr 26, 2025 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [9431b95e78](https://linux-hardware.org/?probe=9431b95e78) | Apr 25, 2025 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [f3e8946a13](https://linux-hardware.org/?probe=f3e8946a13) | Apr 24, 2025 |
| HP            | 212B                        | Desktop     | [246c9eef2a](https://linux-hardware.org/?probe=246c9eef2a) | Apr 24, 2025 |
| HP            | 212B                        | Desktop     | [eb1cb3632a](https://linux-hardware.org/?probe=eb1cb3632a) | Apr 24, 2025 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [444b3440d2](https://linux-hardware.org/?probe=444b3440d2) | Apr 23, 2025 |
| HP            | Laptop 15-da1xxx            | Notebook    | [0177d4e74d](https://linux-hardware.org/?probe=0177d4e74d) | Apr 18, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [1a24e3ac70](https://linux-hardware.org/?probe=1a24e3ac70) | Apr 17, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | Notebook    | [6bc29b1f8a](https://linux-hardware.org/?probe=6bc29b1f8a) | Apr 16, 2025 |
| ASUSTek       | ASUS Zenbook S 14 UX5406... | Notebook    | [76745d3d9c](https://linux-hardware.org/?probe=76745d3d9c) | Apr 15, 2025 |
| HP            | Pavilion g6                 | Notebook    | [2e517fc65b](https://linux-hardware.org/?probe=2e517fc65b) | Apr 12, 2025 |
| HP            | Pavilion g6                 | Notebook    | [4012a698b0](https://linux-hardware.org/?probe=4012a698b0) | Apr 12, 2025 |
| Dell          | Precision M6800             | Notebook    | [aeb8b2056c](https://linux-hardware.org/?probe=aeb8b2056c) | Apr 11, 2025 |
| HP            | ProBook 450 G4              | Notebook    | [a45fe36a21](https://linux-hardware.org/?probe=a45fe36a21) | Apr 11, 2025 |
| Dell          | Precision 7510              | Notebook    | [c5b7c67bfa](https://linux-hardware.org/?probe=c5b7c67bfa) | Apr 10, 2025 |
| Dell          | Latitude E5570              | Notebook    | [064369ed71](https://linux-hardware.org/?probe=064369ed71) | Apr 08, 2025 |
| Dell          | Latitude E5570              | Notebook    | [adc6699f22](https://linux-hardware.org/?probe=adc6699f22) | Apr 07, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [19e67fff37](https://linux-hardware.org/?probe=19e67fff37) | Apr 07, 2025 |
| HP            | Elite x2 1012 G2            | Tablet      | [54a28ef3e5](https://linux-hardware.org/?probe=54a28ef3e5) | Apr 07, 2025 |
| Apple         | MacBook7,1                  | Notebook    | [1fd031c7b3](https://linux-hardware.org/?probe=1fd031c7b3) | Apr 03, 2025 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [da40950441](https://linux-hardware.org/?probe=da40950441) | Mar 27, 2025 |
| Dell          | Inspiron 5537               | Notebook    | [4c739ad54c](https://linux-hardware.org/?probe=4c739ad54c) | Mar 23, 2025 |
| Dell          | Latitude 3490               | Notebook    | [ef1a04b57c](https://linux-hardware.org/?probe=ef1a04b57c) | Mar 21, 2025 |
| Dell          | Latitude 3490               | Notebook    | [0e12d08f5d](https://linux-hardware.org/?probe=0e12d08f5d) | Mar 21, 2025 |
| Dell          | 0PC5F7 A03                  | Desktop     | [47ce3b377f](https://linux-hardware.org/?probe=47ce3b377f) | Mar 21, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [532e9b11f1](https://linux-hardware.org/?probe=532e9b11f1) | Mar 18, 2025 |
| Dell          | Latitude E5570              | Notebook    | [8499b7c3fe](https://linux-hardware.org/?probe=8499b7c3fe) | Mar 18, 2025 |
| Dell          | Latitude E5570              | Notebook    | [3e6c06c6d5](https://linux-hardware.org/?probe=3e6c06c6d5) | Mar 18, 2025 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7d9943a8ee](https://linux-hardware.org/?probe=7d9943a8ee) | Mar 18, 2025 |
| HP            | Laptop 15-bs1xx             | Notebook    | [be44fa9bb9](https://linux-hardware.org/?probe=be44fa9bb9) | Mar 17, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [23f3fc5f7a](https://linux-hardware.org/?probe=23f3fc5f7a) | Mar 17, 2025 |
| I-Life Dig... | ZED NOTE                    | Notebook    | [fe3fdc611d](https://linux-hardware.org/?probe=fe3fdc611d) | Mar 15, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [2a685b647c](https://linux-hardware.org/?probe=2a685b647c) | Mar 15, 2025 |
| Dell          | G15 5510                    | Notebook    | [9b426d41c8](https://linux-hardware.org/?probe=9b426d41c8) | Mar 08, 2025 |
| HP            | 158B                        | Desktop     | [b9e8156dd2](https://linux-hardware.org/?probe=b9e8156dd2) | Mar 08, 2025 |
| Pegatron      | IPMSB-H61A                  | Desktop     | [6c2ccf42d6](https://linux-hardware.org/?probe=6c2ccf42d6) | Mar 05, 2025 |
| ASUSTek       | X550LC                      | Notebook    | [3e24558a3f](https://linux-hardware.org/?probe=3e24558a3f) | Mar 04, 2025 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ea8ecb147c](https://linux-hardware.org/?probe=ea8ecb147c) | Mar 04, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [74b75a7bcd](https://linux-hardware.org/?probe=74b75a7bcd) | Mar 02, 2025 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [46f120cff4](https://linux-hardware.org/?probe=46f120cff4) | Mar 01, 2025 |
| Toshiba       | Satellite C55D-B            | Notebook    | [23dc9bb800](https://linux-hardware.org/?probe=23dc9bb800) | Feb 28, 2025 |
| Toshiba       | Satellite C55D-B            | Notebook    | [c237029310](https://linux-hardware.org/?probe=c237029310) | Feb 22, 2025 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6d8695ea36](https://linux-hardware.org/?probe=6d8695ea36) | Feb 19, 2025 |
| HP            | EliteDesk 800 G1 TWR        | Notebook    | [0b59ac1ae0](https://linux-hardware.org/?probe=0b59ac1ae0) | Feb 19, 2025 |
| HP            | ProBook 650 G4              | Notebook    | [4a5951f69c](https://linux-hardware.org/?probe=4a5951f69c) | Feb 13, 2025 |
| HP            | ProBook 645 G1              | Notebook    | [b5eec97184](https://linux-hardware.org/?probe=b5eec97184) | Feb 12, 2025 |
| HP            | ProBook 645 G1              | Notebook    | [3788447439](https://linux-hardware.org/?probe=3788447439) | Feb 12, 2025 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [9b17c34065](https://linux-hardware.org/?probe=9b17c34065) | Feb 09, 2025 |
| Lenovo        | 317C NOK                    | Desktop     | [5143f71cfe](https://linux-hardware.org/?probe=5143f71cfe) | Feb 06, 2025 |
| HP            | Laptop 15-da1xxx            | Notebook    | [6916691766](https://linux-hardware.org/?probe=6916691766) | Feb 05, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [e3df6fbe82](https://linux-hardware.org/?probe=e3df6fbe82) | Feb 01, 2025 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [af249aa284](https://linux-hardware.org/?probe=af249aa284) | Feb 01, 2025 |
| HP            | Pavilion dv6                | Notebook    | [d7225984fb](https://linux-hardware.org/?probe=d7225984fb) | Jan 31, 2025 |
| Dell          | Inspiron 7405 2n1           | Convertible | [bb2c02e996](https://linux-hardware.org/?probe=bb2c02e996) | Jan 31, 2025 |
| HP            | EliteBook 725 G2            | Notebook    | [12895d228b](https://linux-hardware.org/?probe=12895d228b) | Jan 31, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [607c59f622](https://linux-hardware.org/?probe=607c59f622) | Jan 31, 2025 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [e88ce8e3a0](https://linux-hardware.org/?probe=e88ce8e3a0) | Jan 27, 2025 |
| HP            | Pavilion Notebook           | Notebook    | [ff03629e03](https://linux-hardware.org/?probe=ff03629e03) | Jan 24, 2025 |
| Dell          | Vostro 3500                 | Notebook    | [8c26a17e9e](https://linux-hardware.org/?probe=8c26a17e9e) | Jan 21, 2025 |
| MSI           | B365M PRO-VH                | Desktop     | [d334da5c12](https://linux-hardware.org/?probe=d334da5c12) | Jan 19, 2025 |
| Lenovo        | G510 20238                  | Notebook    | [44c16909d6](https://linux-hardware.org/?probe=44c16909d6) | Jan 13, 2025 |
| HP            | 3047h                       | Desktop     | [dfe665e491](https://linux-hardware.org/?probe=dfe665e491) | Jan 12, 2025 |
| HP            | EliteBook 850 G2            | Notebook    | [70b90777fc](https://linux-hardware.org/?probe=70b90777fc) | Jan 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [b626c2eb32](https://linux-hardware.org/?probe=b626c2eb32) | Jan 11, 2025 |
| Dell          | Inspiron 5520               | Notebook    | [d07eadfcad](https://linux-hardware.org/?probe=d07eadfcad) | Jan 08, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [d778466d49](https://linux-hardware.org/?probe=d778466d49) | Jan 07, 2025 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [a56f47a26f](https://linux-hardware.org/?probe=a56f47a26f) | Jan 06, 2025 |
| Intel         | H61M-DS2                    | Desktop     | [2ef34839f4](https://linux-hardware.org/?probe=2ef34839f4) | Jan 06, 2025 |
| Panasonic     | CF-31SBLEB1M                | Notebook    | [c01282e1c8](https://linux-hardware.org/?probe=c01282e1c8) | Dec 27, 2024 |
| Panasonic     | CF-31SBLEB1M                | Notebook    | [b1be038c76](https://linux-hardware.org/?probe=b1be038c76) | Dec 27, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [985a70079c](https://linux-hardware.org/?probe=985a70079c) | Dec 26, 2024 |
| Dell          | XPS 15 9500                 | Notebook    | [6beec071ad](https://linux-hardware.org/?probe=6beec071ad) | Dec 25, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [729549a358](https://linux-hardware.org/?probe=729549a358) | Dec 25, 2024 |
| HP            | 3646h                       | Desktop     | [dccac4d763](https://linux-hardware.org/?probe=dccac4d763) | Dec 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [fe9e479afd](https://linux-hardware.org/?probe=fe9e479afd) | Dec 21, 2024 |
| HP            | 18E7                        | Desktop     | [d0b93f0461](https://linux-hardware.org/?probe=d0b93f0461) | Dec 21, 2024 |
| HP            | 18E7                        | Desktop     | [5a4b0dfd19](https://linux-hardware.org/?probe=5a4b0dfd19) | Dec 19, 2024 |
| Toshiba       | Satellite L50-B             | Notebook    | [44d23fe380](https://linux-hardware.org/?probe=44d23fe380) | Dec 14, 2024 |
| Dell          | Inspiron 5405               | Notebook    | [3bbbe8e729](https://linux-hardware.org/?probe=3bbbe8e729) | Dec 13, 2024 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [6b8ce5850b](https://linux-hardware.org/?probe=6b8ce5850b) | Dec 12, 2024 |
| Dell          | 0Y9655                      | Desktop     | [02dddf8f3b](https://linux-hardware.org/?probe=02dddf8f3b) | Dec 10, 2024 |
| Dell          | 0Y9655                      | Desktop     | [b5f13b6611](https://linux-hardware.org/?probe=b5f13b6611) | Dec 07, 2024 |
| Dell          | Latitude 5430               | Notebook    | [da4238a565](https://linux-hardware.org/?probe=da4238a565) | Dec 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [b83929cc27](https://linux-hardware.org/?probe=b83929cc27) | Dec 02, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [2f6d2fe7e2](https://linux-hardware.org/?probe=2f6d2fe7e2) | Dec 01, 2024 |
| Alienware     | 17                          | Notebook    | [feba90fb9d](https://linux-hardware.org/?probe=feba90fb9d) | Nov 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [82cdcbb4ca](https://linux-hardware.org/?probe=82cdcbb4ca) | Nov 29, 2024 |
| Dell          | Precision M4800             | Notebook    | [c97548d58c](https://linux-hardware.org/?probe=c97548d58c) | Nov 28, 2024 |
| Dell          | Precision M4800             | Notebook    | [8cddfc2c38](https://linux-hardware.org/?probe=8cddfc2c38) | Nov 28, 2024 |
| Dell          | Precision M4800             | Notebook    | [932bc22167](https://linux-hardware.org/?probe=932bc22167) | Nov 28, 2024 |
| HP            | 1850                        | Desktop     | [371b052cf9](https://linux-hardware.org/?probe=371b052cf9) | Nov 28, 2024 |
| HP            | 82B4                        | Desktop     | [6d6647f3e4](https://linux-hardware.org/?probe=6d6647f3e4) | Nov 27, 2024 |
| HP            | 82B4                        | Desktop     | [fbe90d8967](https://linux-hardware.org/?probe=fbe90d8967) | Nov 27, 2024 |
| Unknown       | Unknown                     | Phone       | [f0f007efa8](https://linux-hardware.org/?probe=f0f007efa8) | Nov 23, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [68441310db](https://linux-hardware.org/?probe=68441310db) | Nov 20, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [43952ac7ef](https://linux-hardware.org/?probe=43952ac7ef) | Nov 20, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [7c3fb96c09](https://linux-hardware.org/?probe=7c3fb96c09) | Nov 18, 2024 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [e0c753b463](https://linux-hardware.org/?probe=e0c753b463) | Nov 17, 2024 |
| HP            | 829D                        | Desktop     | [e50b3cd963](https://linux-hardware.org/?probe=e50b3cd963) | Nov 16, 2024 |
| HP            | 829D                        | Desktop     | [414970c712](https://linux-hardware.org/?probe=414970c712) | Nov 14, 2024 |
| HP            | 18E7                        | Desktop     | [e6421394f6](https://linux-hardware.org/?probe=e6421394f6) | Nov 13, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [cbaa46528f](https://linux-hardware.org/?probe=cbaa46528f) | Nov 10, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [765457bf04](https://linux-hardware.org/?probe=765457bf04) | Nov 09, 2024 |
| Lenovo        | 3176 NOK                    | Desktop     | [5e69593bff](https://linux-hardware.org/?probe=5e69593bff) | Nov 06, 2024 |
| HP            | ProBook 450 G4              | Notebook    | [bbe42e4f22](https://linux-hardware.org/?probe=bbe42e4f22) | Nov 04, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [dde9b2b53c](https://linux-hardware.org/?probe=dde9b2b53c) | Nov 04, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a3e0d131dc](https://linux-hardware.org/?probe=a3e0d131dc) | Nov 01, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | Notebook    | [02bcf148cc](https://linux-hardware.org/?probe=02bcf148cc) | Oct 31, 2024 |
| Apple         | MacBookPro13,1              | Notebook    | [a4cea0834a](https://linux-hardware.org/?probe=a4cea0834a) | Oct 29, 2024 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3cf2d45223](https://linux-hardware.org/?probe=3cf2d45223) | Oct 28, 2024 |
| Dell          | G15 5515                    | Notebook    | [e1bfa90d78](https://linux-hardware.org/?probe=e1bfa90d78) | Oct 28, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [4c16301925](https://linux-hardware.org/?probe=4c16301925) | Oct 27, 2024 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [1d8bed869f](https://linux-hardware.org/?probe=1d8bed869f) | Oct 23, 2024 |
| Biostar       | A320MH PRO                  | Desktop     | [714325c3c9](https://linux-hardware.org/?probe=714325c3c9) | Oct 20, 2024 |
| HP            | ProBook 450 G4              | Notebook    | [e519e7e92e](https://linux-hardware.org/?probe=e519e7e92e) | Oct 15, 2024 |
| HP            | EliteBook 2730p             | Notebook    | [d19cdc0aa3](https://linux-hardware.org/?probe=d19cdc0aa3) | Oct 14, 2024 |
| HP            | EliteBook 2730p             | Notebook    | [77f96f6424](https://linux-hardware.org/?probe=77f96f6424) | Oct 14, 2024 |
| Dell          | G15 5515                    | Notebook    | [13906ffd4a](https://linux-hardware.org/?probe=13906ffd4a) | Oct 13, 2024 |
| Dell          | G15 5515                    | Notebook    | [876d624fba](https://linux-hardware.org/?probe=876d624fba) | Oct 13, 2024 |
| Dell          | Precision 7530              | Notebook    | [ca12dbc1be](https://linux-hardware.org/?probe=ca12dbc1be) | Oct 11, 2024 |
| Dell          | G15 5520                    | Notebook    | [0d6ad139c2](https://linux-hardware.org/?probe=0d6ad139c2) | Oct 11, 2024 |
| Dell          | Precision 7530              | Notebook    | [c386366ce5](https://linux-hardware.org/?probe=c386366ce5) | Oct 10, 2024 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [5188f7bee3](https://linux-hardware.org/?probe=5188f7bee3) | Oct 09, 2024 |
| Dell          | Precision M4800             | Notebook    | [87e17e0353](https://linux-hardware.org/?probe=87e17e0353) | Oct 09, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [70445ed733](https://linux-hardware.org/?probe=70445ed733) | Oct 09, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [267a889e66](https://linux-hardware.org/?probe=267a889e66) | Oct 07, 2024 |
| HP            | EliteBook 745 G6            | Notebook    | [00186bd746](https://linux-hardware.org/?probe=00186bd746) | Oct 04, 2024 |
| Dell          | 06D7TR A00                  | Desktop     | [489410fb9f](https://linux-hardware.org/?probe=489410fb9f) | Oct 03, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [ae376b3f78](https://linux-hardware.org/?probe=ae376b3f78) | Oct 02, 2024 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [5fca760834](https://linux-hardware.org/?probe=5fca760834) | Oct 02, 2024 |
| Lenovo        | LOQ 15IAX9 83GS             | Notebook    | [c05357e589](https://linux-hardware.org/?probe=c05357e589) | Oct 02, 2024 |
| HP            | ProBook 450 G4              | Notebook    | [74d843a3ff](https://linux-hardware.org/?probe=74d843a3ff) | Oct 01, 2024 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [451563b4fb](https://linux-hardware.org/?probe=451563b4fb) | Oct 01, 2024 |
| HP            | ProBook 450 G4              | Notebook    | [15151ed93a](https://linux-hardware.org/?probe=15151ed93a) | Sep 28, 2024 |
| Sony          | SVE15126CAB                 | Notebook    | [f60413658c](https://linux-hardware.org/?probe=f60413658c) | Sep 28, 2024 |
| Micro Comp... | V3                          | Tablet      | [ff1521c6b1](https://linux-hardware.org/?probe=ff1521c6b1) | Sep 28, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [f8be1ee994](https://linux-hardware.org/?probe=f8be1ee994) | Sep 22, 2024 |
| HP            | 158A                        | Desktop     | [6d925337a1](https://linux-hardware.org/?probe=6d925337a1) | Sep 20, 2024 |
| HP            | ZBook 15 G6                 | Notebook    | [edda518320](https://linux-hardware.org/?probe=edda518320) | Sep 17, 2024 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [75f181c794](https://linux-hardware.org/?probe=75f181c794) | Sep 17, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [e9442ac0ef](https://linux-hardware.org/?probe=e9442ac0ef) | Sep 13, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | Notebook    | [cbd5c6f4d1](https://linux-hardware.org/?probe=cbd5c6f4d1) | Sep 11, 2024 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [addda32455](https://linux-hardware.org/?probe=addda32455) | Sep 10, 2024 |
| Dell          | Precision M6500             | Notebook    | [f33e0f389f](https://linux-hardware.org/?probe=f33e0f389f) | Sep 10, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f12c5f1a0e](https://linux-hardware.org/?probe=f12c5f1a0e) | Sep 07, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [558e2441f3](https://linux-hardware.org/?probe=558e2441f3) | Sep 07, 2024 |
| Dell          | Precision M6500             | Notebook    | [d38f4f3a0d](https://linux-hardware.org/?probe=d38f4f3a0d) | Sep 04, 2024 |
| HP            | 1850                        | Desktop     | [29a0446b30](https://linux-hardware.org/?probe=29a0446b30) | Sep 04, 2024 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [c191463e94](https://linux-hardware.org/?probe=c191463e94) | Sep 03, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7fd01bbf58](https://linux-hardware.org/?probe=7fd01bbf58) | Sep 03, 2024 |
| Lenovo        | ThinkPad T460s 20F9001DU... | Notebook    | [9fbc883284](https://linux-hardware.org/?probe=9fbc883284) | Sep 03, 2024 |
| HP            | 18E4                        | Desktop     | [c35e92df21](https://linux-hardware.org/?probe=c35e92df21) | Sep 03, 2024 |
| MiTAC         | 9525                        | Notebook    | [dae6039353](https://linux-hardware.org/?probe=dae6039353) | Sep 01, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [70206460b9](https://linux-hardware.org/?probe=70206460b9) | Aug 31, 2024 |
| HP            | 1850                        | Desktop     | [497427a54f](https://linux-hardware.org/?probe=497427a54f) | Aug 31, 2024 |
| HP            | ZBook 14 G2                 | Notebook    | [7f0dc8a5ee](https://linux-hardware.org/?probe=7f0dc8a5ee) | Aug 30, 2024 |
| HP            | ZBook 14 G2                 | Notebook    | [0afb138cf7](https://linux-hardware.org/?probe=0afb138cf7) | Aug 30, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [4a96c956a3](https://linux-hardware.org/?probe=4a96c956a3) | Aug 25, 2024 |
| Lenovo        | B550 20053                  | Notebook    | [d7a362e8ae](https://linux-hardware.org/?probe=d7a362e8ae) | Aug 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [8ef075cdc6](https://linux-hardware.org/?probe=8ef075cdc6) | Aug 24, 2024 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [5c65c772a0](https://linux-hardware.org/?probe=5c65c772a0) | Aug 23, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [7e292e87db](https://linux-hardware.org/?probe=7e292e87db) | Aug 21, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [e06d0034c0](https://linux-hardware.org/?probe=e06d0034c0) | Aug 20, 2024 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [5af8f48189](https://linux-hardware.org/?probe=5af8f48189) | Aug 19, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [18c286a7b5](https://linux-hardware.org/?probe=18c286a7b5) | Aug 18, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [52ae72249a](https://linux-hardware.org/?probe=52ae72249a) | Aug 18, 2024 |
| Dell          | 0VG93V A00                  | Desktop     | [b81443c816](https://linux-hardware.org/?probe=b81443c816) | Aug 18, 2024 |
| Dell          | 0VG93V A00                  | Desktop     | [c6be5f6727](https://linux-hardware.org/?probe=c6be5f6727) | Aug 17, 2024 |
| MiTAC         | 9525                        | Notebook    | [1c218ead51](https://linux-hardware.org/?probe=1c218ead51) | Aug 17, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [625bb8784e](https://linux-hardware.org/?probe=625bb8784e) | Aug 15, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [19095098a9](https://linux-hardware.org/?probe=19095098a9) | Aug 15, 2024 |
| HP            | 1850                        | Desktop     | [d54e50f3b1](https://linux-hardware.org/?probe=d54e50f3b1) | Aug 14, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [abeade75bf](https://linux-hardware.org/?probe=abeade75bf) | Aug 07, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [32fc2acd15](https://linux-hardware.org/?probe=32fc2acd15) | Aug 06, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [2b509a59ee](https://linux-hardware.org/?probe=2b509a59ee) | Aug 05, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [694cfee657](https://linux-hardware.org/?probe=694cfee657) | Aug 03, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [f9c0a1fd98](https://linux-hardware.org/?probe=f9c0a1fd98) | Aug 03, 2024 |
| Dell          | Inspiron 5520               | Notebook    | [96341f34a7](https://linux-hardware.org/?probe=96341f34a7) | Aug 03, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [15d899f5d6](https://linux-hardware.org/?probe=15d899f5d6) | Aug 01, 2024 |
| Gigabyte      | H67MA-D2H-B3                | Desktop     | [dcd172f513](https://linux-hardware.org/?probe=dcd172f513) | Aug 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3070972064](https://linux-hardware.org/?probe=3070972064) | Jul 30, 2024 |
| Toshiba       | Satellite C655D             | Notebook    | [e81fee8a6c](https://linux-hardware.org/?probe=e81fee8a6c) | Jul 29, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [3141d6b0c5](https://linux-hardware.org/?probe=3141d6b0c5) | Jul 28, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [e3fc443c3c](https://linux-hardware.org/?probe=e3fc443c3c) | Jul 28, 2024 |
| HP            | Pavilion 17                 | Notebook    | [059579abe8](https://linux-hardware.org/?probe=059579abe8) | Jul 25, 2024 |
| HP            | Notebook                    | Notebook    | [a1f1e83afe](https://linux-hardware.org/?probe=a1f1e83afe) | Jul 23, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [154385f06a](https://linux-hardware.org/?probe=154385f06a) | Jul 23, 2024 |
| HP            | Notebook                    | Notebook    | [1df59c0265](https://linux-hardware.org/?probe=1df59c0265) | Jul 23, 2024 |
| HP            | 158B                        | Desktop     | [8968fc3701](https://linux-hardware.org/?probe=8968fc3701) | Jul 22, 2024 |
| HP            | ProBook 450 G3              | Notebook    | [2bac99deff](https://linux-hardware.org/?probe=2bac99deff) | Jul 21, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [414b4921b3](https://linux-hardware.org/?probe=414b4921b3) | Jul 21, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [5cc826a584](https://linux-hardware.org/?probe=5cc826a584) | Jul 21, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [1757077236](https://linux-hardware.org/?probe=1757077236) | Jul 21, 2024 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [000b9c52ac](https://linux-hardware.org/?probe=000b9c52ac) | Jul 20, 2024 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [15d7334bb1](https://linux-hardware.org/?probe=15d7334bb1) | Jul 20, 2024 |
| HP            | 1850                        | Desktop     | [41ee740278](https://linux-hardware.org/?probe=41ee740278) | Jul 20, 2024 |
| Toshiba       | Satellite C850-C010         | Notebook    | [903cf22463](https://linux-hardware.org/?probe=903cf22463) | Jul 20, 2024 |
| Toshiba       | Satellite C850-C010         | Notebook    | [94ab3f5efb](https://linux-hardware.org/?probe=94ab3f5efb) | Jul 20, 2024 |
| Dell          | Latitude E6230              | Notebook    | [49a877be66](https://linux-hardware.org/?probe=49a877be66) | Jul 17, 2024 |
| Dell          | Latitude E6230              | Notebook    | [804f26874d](https://linux-hardware.org/?probe=804f26874d) | Jul 17, 2024 |
| Dell          | Latitude 9520               | Convertible | [492747d61c](https://linux-hardware.org/?probe=492747d61c) | Jul 15, 2024 |
| Dell          | Latitude 9520               | Convertible | [1dc165b627](https://linux-hardware.org/?probe=1dc165b627) | Jul 15, 2024 |
| Toshiba       | Satellite C870-D7K          | Notebook    | [448a44a1ec](https://linux-hardware.org/?probe=448a44a1ec) | Jul 14, 2024 |
| HP            | 158B                        | Desktop     | [fd2a4a4a87](https://linux-hardware.org/?probe=fd2a4a4a87) | Jul 13, 2024 |
| Lenovo        | 3098 NOK                    | Desktop     | [bebed79fcb](https://linux-hardware.org/?probe=bebed79fcb) | Jul 11, 2024 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [38b32e8ac2](https://linux-hardware.org/?probe=38b32e8ac2) | Jul 07, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [38b439c526](https://linux-hardware.org/?probe=38b439c526) | Jul 06, 2024 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [d9c9dbd8c1](https://linux-hardware.org/?probe=d9c9dbd8c1) | Jul 04, 2024 |
| Dell          | Latitude E5520              | Notebook    | [c9c6c2b869](https://linux-hardware.org/?probe=c9c6c2b869) | Jul 04, 2024 |
| Dell          | Latitude 7480               | Notebook    | [b496b8fd50](https://linux-hardware.org/?probe=b496b8fd50) | Jul 02, 2024 |
| Dell          | Latitude 7480               | Notebook    | [a3c6aac33a](https://linux-hardware.org/?probe=a3c6aac33a) | Jul 02, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4a6c68bf6a](https://linux-hardware.org/?probe=4a6c68bf6a) | Jun 28, 2024 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [09efd74667](https://linux-hardware.org/?probe=09efd74667) | Jun 27, 2024 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [09ef0acf45](https://linux-hardware.org/?probe=09ef0acf45) | Jun 23, 2024 |
| GPD           | G1618-04                    | Tablet      | [665c71f6b0](https://linux-hardware.org/?probe=665c71f6b0) | Jun 22, 2024 |
| GPD           | G1618-04                    | Tablet      | [e5cdfd42b9](https://linux-hardware.org/?probe=e5cdfd42b9) | Jun 22, 2024 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [25f65c8ddd](https://linux-hardware.org/?probe=25f65c8ddd) | Jun 20, 2024 |
| HP            | 350 G1                      | Notebook    | [26da241c3b](https://linux-hardware.org/?probe=26da241c3b) | Jun 15, 2024 |
| Dell          | 0F5C5X A00                  | Desktop     | [8db1dee6a9](https://linux-hardware.org/?probe=8db1dee6a9) | Jun 13, 2024 |
| HP            | 802F                        | Desktop     | [d61162e434](https://linux-hardware.org/?probe=d61162e434) | Jun 05, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [3ece85e84e](https://linux-hardware.org/?probe=3ece85e84e) | Jun 04, 2024 |
| Dell          | Latitude E6410              | Notebook    | [ab1f6d2cd0](https://linux-hardware.org/?probe=ab1f6d2cd0) | Jun 03, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [e611c9b374](https://linux-hardware.org/?probe=e611c9b374) | Jun 02, 2024 |
| Dell          | Latitude 5495               | Notebook    | [4af3b4124d](https://linux-hardware.org/?probe=4af3b4124d) | Jun 02, 2024 |
| Dell          | Latitude 5495               | Notebook    | [ce25c22ac7](https://linux-hardware.org/?probe=ce25c22ac7) | Jun 02, 2024 |
| Dell          | Latitude 3520               | Notebook    | [63f78aa5ba](https://linux-hardware.org/?probe=63f78aa5ba) | May 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [ea24258471](https://linux-hardware.org/?probe=ea24258471) | May 22, 2024 |
| Acer          | Aspire A515-45G             | Notebook    | [2e3cf7fe5c](https://linux-hardware.org/?probe=2e3cf7fe5c) | May 18, 2024 |
| Lenovo        | ThinkPad P50 20EQS3B327     | Notebook    | [1d0eb1521b](https://linux-hardware.org/?probe=1d0eb1521b) | May 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [77f3080542](https://linux-hardware.org/?probe=77f3080542) | May 15, 2024 |
| Sony          | SVE1512D1RB                 | Notebook    | [07bdd1d315](https://linux-hardware.org/?probe=07bdd1d315) | May 12, 2024 |
| HP            | EliteBook 8560p             | Notebook    | [9f23553e6a](https://linux-hardware.org/?probe=9f23553e6a) | May 12, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [916a3269bb](https://linux-hardware.org/?probe=916a3269bb) | May 11, 2024 |
| Dell          | Latitude E5520              | Notebook    | [1c27a2760d](https://linux-hardware.org/?probe=1c27a2760d) | May 08, 2024 |
| HP            | ZBook 15 G3                 | Notebook    | [8fbd2e21a7](https://linux-hardware.org/?probe=8fbd2e21a7) | May 08, 2024 |
| HP            | EliteBook 745 G3            | Notebook    | [7eae46245c](https://linux-hardware.org/?probe=7eae46245c) | May 06, 2024 |
| Gigabyte      | H61M-S2P                    | Desktop     | [157cc8b4cc](https://linux-hardware.org/?probe=157cc8b4cc) | May 04, 2024 |
| Dell          | G15 5511                    | Notebook    | [8bb70e4a24](https://linux-hardware.org/?probe=8bb70e4a24) | May 04, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0839696375](https://linux-hardware.org/?probe=0839696375) | May 04, 2024 |
| Dell          | Latitude E5520              | Notebook    | [0c2c1716be](https://linux-hardware.org/?probe=0c2c1716be) | May 04, 2024 |
| MSI           | MS-7309                     | Desktop     | [0683637148](https://linux-hardware.org/?probe=0683637148) | May 03, 2024 |
| HP            | 805A                        | Desktop     | [1c688de61d](https://linux-hardware.org/?probe=1c688de61d) | May 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [06046f8679](https://linux-hardware.org/?probe=06046f8679) | Apr 30, 2024 |
| HP            | ZBook 15                    | Notebook    | [b5181afe2b](https://linux-hardware.org/?probe=b5181afe2b) | Apr 25, 2024 |
| HP            | Pavilion Notebook           | Notebook    | [0ed4e3a757](https://linux-hardware.org/?probe=0ed4e3a757) | Apr 24, 2024 |
| HP            | ProBook 645 G4              | Notebook    | [5e0b981c4f](https://linux-hardware.org/?probe=5e0b981c4f) | Apr 20, 2024 |
| HP            | 1632                        | Desktop     | [1a23bb9aba](https://linux-hardware.org/?probe=1a23bb9aba) | Apr 19, 2024 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8f4cd3f89d](https://linux-hardware.org/?probe=8f4cd3f89d) | Apr 19, 2024 |
| HP            | 1632                        | Desktop     | [2d11bc974f](https://linux-hardware.org/?probe=2d11bc974f) | Apr 18, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [0d2ecb9207](https://linux-hardware.org/?probe=0d2ecb9207) | Apr 17, 2024 |
| Lenovo        | B590 20206                  | Notebook    | [e99c52e2f5](https://linux-hardware.org/?probe=e99c52e2f5) | Apr 16, 2024 |
| HP            | Pavilion 15                 | Notebook    | [e7d5a8c55a](https://linux-hardware.org/?probe=e7d5a8c55a) | Apr 14, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [e820d6337a](https://linux-hardware.org/?probe=e820d6337a) | Apr 11, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [d8a1d4fd64](https://linux-hardware.org/?probe=d8a1d4fd64) | Apr 10, 2024 |
| Dell          | Inspiron N5010              | Notebook    | [7fe3c3fa19](https://linux-hardware.org/?probe=7fe3c3fa19) | Apr 09, 2024 |
| Dell          | G15 5511                    | Notebook    | [3493d65893](https://linux-hardware.org/?probe=3493d65893) | Apr 06, 2024 |
| Dell          | G15 5511                    | Notebook    | [98ba745e2f](https://linux-hardware.org/?probe=98ba745e2f) | Apr 06, 2024 |
| MSI           | Modern 14 B5M               | Notebook    | [0862e9e806](https://linux-hardware.org/?probe=0862e9e806) | Apr 05, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [4b0127a449](https://linux-hardware.org/?probe=4b0127a449) | Apr 04, 2024 |
| HP            | 8434 11                     | Desktop     | [a1a62e20a4](https://linux-hardware.org/?probe=a1a62e20a4) | Apr 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [21c028b980](https://linux-hardware.org/?probe=21c028b980) | Apr 02, 2024 |
| Apple         | MacBook10,1                 | Notebook    | [2da6005f10](https://linux-hardware.org/?probe=2da6005f10) | Apr 01, 2024 |
| Apple         | MacBook10,1                 | Notebook    | [36d6f74236](https://linux-hardware.org/?probe=36d6f74236) | Apr 01, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [900e722a10](https://linux-hardware.org/?probe=900e722a10) | Apr 01, 2024 |
| HP            | 1998                        | Desktop     | [4c2971ed76](https://linux-hardware.org/?probe=4c2971ed76) | Mar 27, 2024 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [18b1b5d0e9](https://linux-hardware.org/?probe=18b1b5d0e9) | Mar 26, 2024 |
| Dell          | Latitude E6540              | Notebook    | [cb66e3c3d1](https://linux-hardware.org/?probe=cb66e3c3d1) | Mar 26, 2024 |
| Lenovo        | ThinkPad E480 20KN0082AD    | Notebook    | [db9cb980a5](https://linux-hardware.org/?probe=db9cb980a5) | Mar 25, 2024 |
| HP            | 1998                        | Desktop     | [d8865ee940](https://linux-hardware.org/?probe=d8865ee940) | Mar 24, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [f341009f68](https://linux-hardware.org/?probe=f341009f68) | Mar 19, 2024 |
| HP            | Laptop 15-bs1xx             | Notebook    | [585d283a71](https://linux-hardware.org/?probe=585d283a71) | Mar 15, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7a99f5e6bc](https://linux-hardware.org/?probe=7a99f5e6bc) | Mar 13, 2024 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [13aa71b72d](https://linux-hardware.org/?probe=13aa71b72d) | Mar 07, 2024 |
| HP            | ZBook 17 G3                 | Notebook    | [e69ebcea87](https://linux-hardware.org/?probe=e69ebcea87) | Mar 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1446f9eae8](https://linux-hardware.org/?probe=1446f9eae8) | Mar 05, 2024 |
| Apple         | MacBookPro5,3               | Notebook    | [20e198611e](https://linux-hardware.org/?probe=20e198611e) | Mar 02, 2024 |
| HP            | 1998                        | Desktop     | [de124e0aad](https://linux-hardware.org/?probe=de124e0aad) | Feb 29, 2024 |
| HP            | ProBook 640 G2              | Notebook    | [70cfce9afd](https://linux-hardware.org/?probe=70cfce9afd) | Feb 28, 2024 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [a3e7bc047a](https://linux-hardware.org/?probe=a3e7bc047a) | Feb 27, 2024 |
| HP            | 1998                        | Desktop     | [6629121159](https://linux-hardware.org/?probe=6629121159) | Feb 24, 2024 |
| HP            | 1998                        | Desktop     | [c36364061e](https://linux-hardware.org/?probe=c36364061e) | Feb 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [e0a46a8c21](https://linux-hardware.org/?probe=e0a46a8c21) | Feb 23, 2024 |
| HP            | ZBook 17 G3                 | Notebook    | [9b0019e8dd](https://linux-hardware.org/?probe=9b0019e8dd) | Feb 23, 2024 |
| HP            | 2215                        | Desktop     | [eef0673d86](https://linux-hardware.org/?probe=eef0673d86) | Feb 21, 2024 |
| HP            | 2215                        | Desktop     | [3333f97016](https://linux-hardware.org/?probe=3333f97016) | Feb 21, 2024 |
| HP            | 2215                        | Desktop     | [d23162f59f](https://linux-hardware.org/?probe=d23162f59f) | Feb 20, 2024 |
| Acer          | Veriton X4110G              | Desktop     | [85c69e6034](https://linux-hardware.org/?probe=85c69e6034) | Feb 20, 2024 |
| HP            | 2215                        | Desktop     | [8fec3e792a](https://linux-hardware.org/?probe=8fec3e792a) | Feb 19, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7ed42ddb2a](https://linux-hardware.org/?probe=7ed42ddb2a) | Feb 19, 2024 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6e7ac3ec7e](https://linux-hardware.org/?probe=6e7ac3ec7e) | Feb 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [4bfbb106d2](https://linux-hardware.org/?probe=4bfbb106d2) | Feb 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [96859b01b7](https://linux-hardware.org/?probe=96859b01b7) | Feb 17, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [6e9a9b6226](https://linux-hardware.org/?probe=6e9a9b6226) | Feb 17, 2024 |
| Toshiba       | Satellite C660              | Notebook    | [336464e94f](https://linux-hardware.org/?probe=336464e94f) | Feb 16, 2024 |
| HP            | 3047h                       | Desktop     | [05f8efc7c6](https://linux-hardware.org/?probe=05f8efc7c6) | Feb 15, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c1504decd1](https://linux-hardware.org/?probe=c1504decd1) | Feb 15, 2024 |
| HP            | ProBook 450 G4              | Notebook    | [25a3c438a1](https://linux-hardware.org/?probe=25a3c438a1) | Feb 13, 2024 |
| HP            | 1998                        | Desktop     | [de3c15346c](https://linux-hardware.org/?probe=de3c15346c) | Feb 10, 2024 |
| HP            | 215 G1                      | Notebook    | [52df684d4c](https://linux-hardware.org/?probe=52df684d4c) | Feb 05, 2024 |
| HP            | 215 G1                      | Notebook    | [c992749b63](https://linux-hardware.org/?probe=c992749b63) | Feb 05, 2024 |
| HP            | 1998                        | Desktop     | [5e85b19897](https://linux-hardware.org/?probe=5e85b19897) | Feb 05, 2024 |
| Acer          | Aspire A515-45G             | Notebook    | [4012edd9e1](https://linux-hardware.org/?probe=4012edd9e1) | Feb 04, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8de0a1db50](https://linux-hardware.org/?probe=8de0a1db50) | Feb 04, 2024 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [e58ba87da3](https://linux-hardware.org/?probe=e58ba87da3) | Feb 04, 2024 |
| Dell          | 0G214D A00                  | Desktop     | [1a1b425da2](https://linux-hardware.org/?probe=1a1b425da2) | Feb 04, 2024 |
| HP            | ZBook 15 G2                 | Notebook    | [2fe30cca38](https://linux-hardware.org/?probe=2fe30cca38) | Feb 03, 2024 |
| Dell          | Latitude 3420               | Notebook    | [15de060676](https://linux-hardware.org/?probe=15de060676) | Feb 02, 2024 |
| Dell          | Latitude E6420              | Notebook    | [ff73a45b61](https://linux-hardware.org/?probe=ff73a45b61) | Feb 01, 2024 |
| HP            | 1998                        | Desktop     | [8ab7c171c3](https://linux-hardware.org/?probe=8ab7c171c3) | Jan 31, 2024 |
| HP            | 1998                        | Desktop     | [92ff4b3ecd](https://linux-hardware.org/?probe=92ff4b3ecd) | Jan 30, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [fc77fc72a5](https://linux-hardware.org/?probe=fc77fc72a5) | Jan 29, 2024 |
| Dell          | 03NVJ6 A03                  | Desktop     | [2ad42e2ce5](https://linux-hardware.org/?probe=2ad42e2ce5) | Jan 29, 2024 |
| Dell          | Inspiron 5521               | Notebook    | [e9f2d87f0f](https://linux-hardware.org/?probe=e9f2d87f0f) | Jan 26, 2024 |
| Dell          | Inspiron 5521               | Notebook    | [1c9b6b485d](https://linux-hardware.org/?probe=1c9b6b485d) | Jan 26, 2024 |
| HP            | ProBook 645 G4              | Notebook    | [af6ac91f2a](https://linux-hardware.org/?probe=af6ac91f2a) | Jan 25, 2024 |
| Dell          | 040DDP A01                  | Desktop     | [521a18e93d](https://linux-hardware.org/?probe=521a18e93d) | Jan 20, 2024 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [c2522bf7b3](https://linux-hardware.org/?probe=c2522bf7b3) | Jan 19, 2024 |
| Dell          | 040DDP A01                  | Desktop     | [c332d169ee](https://linux-hardware.org/?probe=c332d169ee) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [d5e4257979](https://linux-hardware.org/?probe=d5e4257979) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [4f35e40b86](https://linux-hardware.org/?probe=4f35e40b86) | Jan 16, 2024 |
| HP            | Laptop 14-cf1xxx            | Notebook    | [b26a65cafd](https://linux-hardware.org/?probe=b26a65cafd) | Jan 16, 2024 |
| Acer          | Predator G9-592             | Notebook    | [67dd34e639](https://linux-hardware.org/?probe=67dd34e639) | Jan 16, 2024 |
| Gigabyte      | H61M-S2P                    | Desktop     | [b9dd6cbf20](https://linux-hardware.org/?probe=b9dd6cbf20) | Jan 15, 2024 |
| Acer          | Aspire A515-45G             | Notebook    | [9f83faffad](https://linux-hardware.org/?probe=9f83faffad) | Jan 14, 2024 |
| HP            | 3647h                       | Desktop     | [e9767a4e96](https://linux-hardware.org/?probe=e9767a4e96) | Jan 12, 2024 |
| HP            | 3647h                       | Desktop     | [39414040e7](https://linux-hardware.org/?probe=39414040e7) | Jan 12, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [feaf3edd58](https://linux-hardware.org/?probe=feaf3edd58) | Jan 10, 2024 |
| Dell          | Inspiron 3593               | Notebook    | [e82da0cd29](https://linux-hardware.org/?probe=e82da0cd29) | Jan 05, 2024 |
| HP            | ZBook 15 G5                 | Notebook    | [7d1279f3ef](https://linux-hardware.org/?probe=7d1279f3ef) | Jan 04, 2024 |
| Dell          | 06FW8P A01                  | Desktop     | [64eb36d553](https://linux-hardware.org/?probe=64eb36d553) | Jan 04, 2024 |
| Dell          | 06FW8P A01                  | Desktop     | [4a93269eb2](https://linux-hardware.org/?probe=4a93269eb2) | Jan 04, 2024 |
| Dell          | 03NVJ6 A03                  | Desktop     | [a87a530d24](https://linux-hardware.org/?probe=a87a530d24) | Dec 30, 2023 |
| Dell          | 02VCFF A00                  | Desktop     | [902c7a4466](https://linux-hardware.org/?probe=902c7a4466) | Dec 27, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [7378a1bdb4](https://linux-hardware.org/?probe=7378a1bdb4) | Dec 27, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [b6056625fc](https://linux-hardware.org/?probe=b6056625fc) | Dec 26, 2023 |
| HP            | G62                         | Notebook    | [434b8aa389](https://linux-hardware.org/?probe=434b8aa389) | Dec 25, 2023 |
| Acer          | Predator PH317-53           | Notebook    | [fcc1b4896e](https://linux-hardware.org/?probe=fcc1b4896e) | Dec 25, 2023 |
| Acer          | Extensa 2519                | Notebook    | [29bc812d6d](https://linux-hardware.org/?probe=29bc812d6d) | Dec 23, 2023 |
| HP            | 18E7                        | Desktop     | [71f34bba13](https://linux-hardware.org/?probe=71f34bba13) | Dec 21, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [1fff6e8409](https://linux-hardware.org/?probe=1fff6e8409) | Dec 20, 2023 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [5574b0048b](https://linux-hardware.org/?probe=5574b0048b) | Dec 16, 2023 |
| Dell          | Precision 5540              | Notebook    | [ff22e47089](https://linux-hardware.org/?probe=ff22e47089) | Dec 16, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [f33ae0cc45](https://linux-hardware.org/?probe=f33ae0cc45) | Dec 14, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [15f1f8f029](https://linux-hardware.org/?probe=15f1f8f029) | Dec 13, 2023 |
| ASUSTek       | H61M-K                      | Desktop     | [d7a660dbef](https://linux-hardware.org/?probe=d7a660dbef) | Dec 13, 2023 |
| HP            | 1850                        | Desktop     | [903e4b5eb1](https://linux-hardware.org/?probe=903e4b5eb1) | Dec 11, 2023 |
| HP            | 3029h                       | Desktop     | [f7d6a9e2d4](https://linux-hardware.org/?probe=f7d6a9e2d4) | Dec 10, 2023 |
| Dell          | Latitude 5430               | Notebook    | [c105b5162b](https://linux-hardware.org/?probe=c105b5162b) | Dec 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [ed7195f601](https://linux-hardware.org/?probe=ed7195f601) | Dec 05, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | Notebook    | [fe13325e26](https://linux-hardware.org/?probe=fe13325e26) | Dec 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [a63677b9e1](https://linux-hardware.org/?probe=a63677b9e1) | Dec 03, 2023 |
| HP            | 2215                        | Desktop     | [f29d88c563](https://linux-hardware.org/?probe=f29d88c563) | Dec 03, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [f7bf7a5dcc](https://linux-hardware.org/?probe=f7bf7a5dcc) | Dec 02, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [cd95525dd4](https://linux-hardware.org/?probe=cd95525dd4) | Dec 01, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [eb52097d1b](https://linux-hardware.org/?probe=eb52097d1b) | Nov 29, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [beba27b952](https://linux-hardware.org/?probe=beba27b952) | Nov 28, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [ce1806eec5](https://linux-hardware.org/?probe=ce1806eec5) | Nov 26, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [e9bfd98ad2](https://linux-hardware.org/?probe=e9bfd98ad2) | Nov 26, 2023 |
| HP            | Unknown                     | Notebook    | [74afdb551a](https://linux-hardware.org/?probe=74afdb551a) | Nov 26, 2023 |
| HP            | Unknown                     | Notebook    | [6d4bc0aed6](https://linux-hardware.org/?probe=6d4bc0aed6) | Nov 26, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [6e903b92f6](https://linux-hardware.org/?probe=6e903b92f6) | Nov 26, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [ea362b85cf](https://linux-hardware.org/?probe=ea362b85cf) | Nov 25, 2023 |
| HP            | ProBook 450 G7              | Notebook    | [30edbbd6f0](https://linux-hardware.org/?probe=30edbbd6f0) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [193588412a](https://linux-hardware.org/?probe=193588412a) | Nov 23, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [d277e32193](https://linux-hardware.org/?probe=d277e32193) | Nov 20, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [72e5f7b707](https://linux-hardware.org/?probe=72e5f7b707) | Nov 19, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [29dc31d4de](https://linux-hardware.org/?probe=29dc31d4de) | Nov 16, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [b612f7a489](https://linux-hardware.org/?probe=b612f7a489) | Nov 16, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3843b68ba8](https://linux-hardware.org/?probe=3843b68ba8) | Nov 15, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [2158fdddd7](https://linux-hardware.org/?probe=2158fdddd7) | Nov 14, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [a3eb4c9d76](https://linux-hardware.org/?probe=a3eb4c9d76) | Nov 04, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [476a922e2f](https://linux-hardware.org/?probe=476a922e2f) | Nov 02, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [6efacfa5c8](https://linux-hardware.org/?probe=6efacfa5c8) | Nov 01, 2023 |
| Sony          | SVS15116GAB                 | Notebook    | [03634a7731](https://linux-hardware.org/?probe=03634a7731) | Oct 30, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [eebc7d0d72](https://linux-hardware.org/?probe=eebc7d0d72) | Oct 28, 2023 |
| Dell          | Latitude 5530               | Notebook    | [70ffc0b609](https://linux-hardware.org/?probe=70ffc0b609) | Oct 23, 2023 |
| Dell          | Latitude E5570              | Notebook    | [3c4a0eb291](https://linux-hardware.org/?probe=3c4a0eb291) | Oct 23, 2023 |
| Dell          | Precision M4800             | Notebook    | [1538f5153d](https://linux-hardware.org/?probe=1538f5153d) | Oct 19, 2023 |
| Dell          | Precision M4800             | Notebook    | [03012f2d54](https://linux-hardware.org/?probe=03012f2d54) | Oct 19, 2023 |
| Dell          | 0TY915                      | Desktop     | [8ebe2fefc1](https://linux-hardware.org/?probe=8ebe2fefc1) | Oct 15, 2023 |
| Dell          | 0TY915                      | Desktop     | [736f520474](https://linux-hardware.org/?probe=736f520474) | Oct 15, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6ec1b6d812](https://linux-hardware.org/?probe=6ec1b6d812) | Oct 13, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [25433b6adb](https://linux-hardware.org/?probe=25433b6adb) | Oct 13, 2023 |
| Dell          | Precision 5530              | Notebook    | [2c19c2e063](https://linux-hardware.org/?probe=2c19c2e063) | Oct 12, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | Notebook    | [b18b8f45a4](https://linux-hardware.org/?probe=b18b8f45a4) | Oct 11, 2023 |
| Dell          | Latitude 7210 2-in-1        | Tablet      | [e223a799bc](https://linux-hardware.org/?probe=e223a799bc) | Oct 07, 2023 |
| Dell          | 0WWJRX A00                  | Desktop     | [331ecd3ee8](https://linux-hardware.org/?probe=331ecd3ee8) | Oct 06, 2023 |
| Dell          | Latitude E6520              | Notebook    | [cb7181f79f](https://linux-hardware.org/?probe=cb7181f79f) | Oct 05, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [a9e2c9b64e](https://linux-hardware.org/?probe=a9e2c9b64e) | Oct 03, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cd70d42de1](https://linux-hardware.org/?probe=cd70d42de1) | Oct 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [21a71fe352](https://linux-hardware.org/?probe=21a71fe352) | Oct 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [4fc3b1e588](https://linux-hardware.org/?probe=4fc3b1e588) | Oct 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [01d6d4f3c4](https://linux-hardware.org/?probe=01d6d4f3c4) | Oct 01, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [fe6b9d4c65](https://linux-hardware.org/?probe=fe6b9d4c65) | Oct 01, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [5cae9ddf98](https://linux-hardware.org/?probe=5cae9ddf98) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [700c901144](https://linux-hardware.org/?probe=700c901144) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [16f4068970](https://linux-hardware.org/?probe=16f4068970) | Sep 30, 2023 |
| Dell          | Latitude E6530              | Notebook    | [5fc5673815](https://linux-hardware.org/?probe=5fc5673815) | Sep 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BT      | Notebook    | [ba269d8c4a](https://linux-hardware.org/?probe=ba269d8c4a) | Sep 29, 2023 |
| HP            | ZBook Studio x360 G5        | Convertible | [dd0d8dda44](https://linux-hardware.org/?probe=dd0d8dda44) | Sep 26, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c62002acdf](https://linux-hardware.org/?probe=c62002acdf) | Sep 25, 2023 |
| Sary          | Tab2                        | Tablet      | [7078e2b899](https://linux-hardware.org/?probe=7078e2b899) | Sep 23, 2023 |
| Sary          | Tab2                        | Tablet      | [913ec00764](https://linux-hardware.org/?probe=913ec00764) | Sep 23, 2023 |
| Dell          | Latitude E6520              | Notebook    | [734076d709](https://linux-hardware.org/?probe=734076d709) | Sep 23, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [966f802eb6](https://linux-hardware.org/?probe=966f802eb6) | Sep 21, 2023 |
| Toshiba       | PORTEGE M750                | Notebook    | [1c3442d87f](https://linux-hardware.org/?probe=1c3442d87f) | Sep 14, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [d1e95788fd](https://linux-hardware.org/?probe=d1e95788fd) | Sep 13, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [ced1631b20](https://linux-hardware.org/?probe=ced1631b20) | Sep 11, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [e78c297114](https://linux-hardware.org/?probe=e78c297114) | Sep 10, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [75eb2afaca](https://linux-hardware.org/?probe=75eb2afaca) | Sep 09, 2023 |
| ASUSTek       | TP500LN                     | Notebook    | [d90f472bcf](https://linux-hardware.org/?probe=d90f472bcf) | Sep 09, 2023 |
| Unknown       | Unknown                     | Soc         | [55b8727f3f](https://linux-hardware.org/?probe=55b8727f3f) | Sep 06, 2023 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [a28ca9b2fb](https://linux-hardware.org/?probe=a28ca9b2fb) | Sep 04, 2023 |
| MSI           | Modern 14 B11MOU            | Notebook    | [239c2bbc02](https://linux-hardware.org/?probe=239c2bbc02) | Sep 02, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [ad844f1a8c](https://linux-hardware.org/?probe=ad844f1a8c) | Aug 30, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [0c279f8cf0](https://linux-hardware.org/?probe=0c279f8cf0) | Aug 30, 2023 |
| HP            | 350 G1                      | Notebook    | [1e317e5a51](https://linux-hardware.org/?probe=1e317e5a51) | Aug 30, 2023 |
| HP            | 8061                        | Desktop     | [31a0fa50a3](https://linux-hardware.org/?probe=31a0fa50a3) | Aug 29, 2023 |
| HP            | 350 G1                      | Notebook    | [d800790bce](https://linux-hardware.org/?probe=d800790bce) | Aug 28, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [89e74082d8](https://linux-hardware.org/?probe=89e74082d8) | Aug 23, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [205a407b60](https://linux-hardware.org/?probe=205a407b60) | Aug 21, 2023 |
| HP            | G62                         | Notebook    | [778c1c04b9](https://linux-hardware.org/?probe=778c1c04b9) | Aug 19, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [8735b5577b](https://linux-hardware.org/?probe=8735b5577b) | Aug 18, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [3771669b84](https://linux-hardware.org/?probe=3771669b84) | Aug 10, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [32c2f39f3a](https://linux-hardware.org/?probe=32c2f39f3a) | Aug 06, 2023 |
| Dell          | Inspiron 3558               | Notebook    | [5331913f13](https://linux-hardware.org/?probe=5331913f13) | Aug 04, 2023 |
| Toshiba       | Satellite C855D             | Notebook    | [4835e837bd](https://linux-hardware.org/?probe=4835e837bd) | Aug 03, 2023 |
| HP            | ProBook 6475b               | Notebook    | [c3cfc235fe](https://linux-hardware.org/?probe=c3cfc235fe) | Aug 01, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [ad721ddbad](https://linux-hardware.org/?probe=ad721ddbad) | Jul 31, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [08990a8da3](https://linux-hardware.org/?probe=08990a8da3) | Jul 28, 2023 |
| HP            | 3047h                       | Desktop     | [07de35877b](https://linux-hardware.org/?probe=07de35877b) | Jul 21, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [42ddc0425b](https://linux-hardware.org/?probe=42ddc0425b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [0093aba5fd](https://linux-hardware.org/?probe=0093aba5fd) | Jul 16, 2023 |
| HP            | Unknown                     | Notebook    | [e36ee407e4](https://linux-hardware.org/?probe=e36ee407e4) | Jul 12, 2023 |
| HP            | 18E4                        | Desktop     | [6d3964fd1b](https://linux-hardware.org/?probe=6d3964fd1b) | Jul 05, 2023 |
| HP            | 18E4                        | Desktop     | [8a382f8911](https://linux-hardware.org/?probe=8a382f8911) | Jul 05, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [5d4cb4e73a](https://linux-hardware.org/?probe=5d4cb4e73a) | Jul 03, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [3fe182f682](https://linux-hardware.org/?probe=3fe182f682) | Jul 02, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [587f8b6b83](https://linux-hardware.org/?probe=587f8b6b83) | Jul 01, 2023 |
| HP            | 18E7                        | Desktop     | [1ae4c92b7f](https://linux-hardware.org/?probe=1ae4c92b7f) | Jun 26, 2023 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [9f1f9757a2](https://linux-hardware.org/?probe=9f1f9757a2) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | Notebook    | [7d8f0212e9](https://linux-hardware.org/?probe=7d8f0212e9) | Jun 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [0f64e88f33](https://linux-hardware.org/?probe=0f64e88f33) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [6d8c00ff02](https://linux-hardware.org/?probe=6d8c00ff02) | Jun 23, 2023 |
| HP            | EliteBook 8540w             | Notebook    | [1c1a2724f4](https://linux-hardware.org/?probe=1c1a2724f4) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [8df9a683cb](https://linux-hardware.org/?probe=8df9a683cb) | Jun 23, 2023 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [4d419c5b63](https://linux-hardware.org/?probe=4d419c5b63) | Jun 23, 2023 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [44f21e0f7e](https://linux-hardware.org/?probe=44f21e0f7e) | Jun 17, 2023 |
| Dell          | 0HMX8D A01                  | Desktop     | [e96dd04034](https://linux-hardware.org/?probe=e96dd04034) | Jun 15, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [d4da1625e2](https://linux-hardware.org/?probe=d4da1625e2) | Jun 12, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | Notebook    | [ac48eeb92c](https://linux-hardware.org/?probe=ac48eeb92c) | Jun 10, 2023 |
| Lenovo        | G580 ChiefRiver Platform    | Notebook    | [ade15528d8](https://linux-hardware.org/?probe=ade15528d8) | Jun 10, 2023 |
| HP            | 1494                        | Desktop     | [7e431c0351](https://linux-hardware.org/?probe=7e431c0351) | Jun 08, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [2b1a1d3e39](https://linux-hardware.org/?probe=2b1a1d3e39) | Jun 07, 2023 |
| HP            | 1494                        | Desktop     | [0f032c101b](https://linux-hardware.org/?probe=0f032c101b) | Jun 07, 2023 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [3308d91565](https://linux-hardware.org/?probe=3308d91565) | Jun 07, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [8a69d6c123](https://linux-hardware.org/?probe=8a69d6c123) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [ecfe7565f4](https://linux-hardware.org/?probe=ecfe7565f4) | Jun 01, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [183ee8e37a](https://linux-hardware.org/?probe=183ee8e37a) | May 27, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [2fadb86df4](https://linux-hardware.org/?probe=2fadb86df4) | May 27, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [cbcea9cc58](https://linux-hardware.org/?probe=cbcea9cc58) | May 27, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [b17003f11e](https://linux-hardware.org/?probe=b17003f11e) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [dedcc1bb3f](https://linux-hardware.org/?probe=dedcc1bb3f) | May 22, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [ec1357e74e](https://linux-hardware.org/?probe=ec1357e74e) | May 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7ab850285a](https://linux-hardware.org/?probe=7ab850285a) | May 14, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [6a031fd8a6](https://linux-hardware.org/?probe=6a031fd8a6) | May 13, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [25c4b5fe60](https://linux-hardware.org/?probe=25c4b5fe60) | May 07, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [3ff6a3dac0](https://linux-hardware.org/?probe=3ff6a3dac0) | May 06, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [483415e8cb](https://linux-hardware.org/?probe=483415e8cb) | May 05, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [fa074ed7c9](https://linux-hardware.org/?probe=fa074ed7c9) | May 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [640e50acf8](https://linux-hardware.org/?probe=640e50acf8) | May 04, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [a2f3590a6a](https://linux-hardware.org/?probe=a2f3590a6a) | May 04, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [3ab78594e3](https://linux-hardware.org/?probe=3ab78594e3) | May 02, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [bf317c9241](https://linux-hardware.org/?probe=bf317c9241) | May 01, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0db7cac0f4](https://linux-hardware.org/?probe=0db7cac0f4) | May 01, 2023 |
| HP            | Unknown                     | Notebook    | [475eb33956](https://linux-hardware.org/?probe=475eb33956) | May 01, 2023 |
| Lenovo        | ThinkPad X220 429044U       | Notebook    | [1bf66ba9be](https://linux-hardware.org/?probe=1bf66ba9be) | Apr 26, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [e97953e840](https://linux-hardware.org/?probe=e97953e840) | Apr 26, 2023 |
| HP            | EliteBook 2730p             | Notebook    | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [40cf2f15c2](https://linux-hardware.org/?probe=40cf2f15c2) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [7d3b6ba1a3](https://linux-hardware.org/?probe=7d3b6ba1a3) | Apr 25, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [ed8414c493](https://linux-hardware.org/?probe=ed8414c493) | Apr 24, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [695220be38](https://linux-hardware.org/?probe=695220be38) | Apr 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [43aae4850b](https://linux-hardware.org/?probe=43aae4850b) | Apr 23, 2023 |
| HP            | Notebook                    | Notebook    | [36788985ec](https://linux-hardware.org/?probe=36788985ec) | Apr 20, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [b1c04430cc](https://linux-hardware.org/?probe=b1c04430cc) | Apr 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [b2873d15a0](https://linux-hardware.org/?probe=b2873d15a0) | Apr 19, 2023 |
| HP            | Notebook                    | Notebook    | [072fc2bf12](https://linux-hardware.org/?probe=072fc2bf12) | Apr 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6fae9a24fb](https://linux-hardware.org/?probe=6fae9a24fb) | Apr 19, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [fb3d31599f](https://linux-hardware.org/?probe=fb3d31599f) | Apr 18, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [3d5c848955](https://linux-hardware.org/?probe=3d5c848955) | Apr 18, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [c33ef2ceeb](https://linux-hardware.org/?probe=c33ef2ceeb) | Apr 11, 2023 |
| Nvidia        | Tegra                       | Soc         | [1378d303e3](https://linux-hardware.org/?probe=1378d303e3) | Apr 08, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [c73108de7b](https://linux-hardware.org/?probe=c73108de7b) | Apr 06, 2023 |
| Dell          | Latitude 7350               | Notebook    | [9bdfad0684](https://linux-hardware.org/?probe=9bdfad0684) | Apr 06, 2023 |
| Nvidia        | Tegra                       | Soc         | [d57318f254](https://linux-hardware.org/?probe=d57318f254) | Apr 02, 2023 |
| Lenovo        | ThinkPad T530 23594LU       | Notebook    | [9de89fee19](https://linux-hardware.org/?probe=9de89fee19) | Apr 01, 2023 |
| Dell          | Vostro 15 3515              | Notebook    | [7b4a51d5e3](https://linux-hardware.org/?probe=7b4a51d5e3) | Mar 29, 2023 |
| Dell          | Latitude 7350               | Notebook    | [de44a7d43c](https://linux-hardware.org/?probe=de44a7d43c) | Mar 28, 2023 |
| HP            | Compaq 610                  | Notebook    | [dc9383200e](https://linux-hardware.org/?probe=dc9383200e) | Mar 28, 2023 |
| Dell          | Latitude 7350               | Notebook    | [8ef24a8281](https://linux-hardware.org/?probe=8ef24a8281) | Mar 28, 2023 |
| Dell          | Latitude E6430              | Notebook    | [912e5e8577](https://linux-hardware.org/?probe=912e5e8577) | Mar 26, 2023 |
| Dell          | Latitude E6430              | Notebook    | [237dabb566](https://linux-hardware.org/?probe=237dabb566) | Mar 26, 2023 |
| HP            | 250 G4                      | Notebook    | [e0ff721413](https://linux-hardware.org/?probe=e0ff721413) | Mar 23, 2023 |
| Lenovo        | S20-30 20421                | Notebook    | [3c1dd3564d](https://linux-hardware.org/?probe=3c1dd3564d) | Mar 19, 2023 |
| Dell          | G5 5500                     | Notebook    | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [211a71ed78](https://linux-hardware.org/?probe=211a71ed78) | Mar 18, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [abb09d2f8e](https://linux-hardware.org/?probe=abb09d2f8e) | Mar 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [e548fa074e](https://linux-hardware.org/?probe=e548fa074e) | Mar 14, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [3b1827fe4f](https://linux-hardware.org/?probe=3b1827fe4f) | Mar 13, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [74452c1274](https://linux-hardware.org/?probe=74452c1274) | Mar 13, 2023 |
| Dell          | Latitude 5420               | Notebook    | [948cbeda59](https://linux-hardware.org/?probe=948cbeda59) | Feb 23, 2023 |
| Dell          | 073MMW A02                  | Desktop     | [aa198228bc](https://linux-hardware.org/?probe=aa198228bc) | Feb 19, 2023 |
| Gigabyte      | H87M-HD3                    | Desktop     | [778b7898e3](https://linux-hardware.org/?probe=778b7898e3) | Feb 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [9d060a9cc6](https://linux-hardware.org/?probe=9d060a9cc6) | Feb 15, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [0cbe95253a](https://linux-hardware.org/?probe=0cbe95253a) | Feb 15, 2023 |
| Dell          | G3 3579                     | Notebook    | [4721b18608](https://linux-hardware.org/?probe=4721b18608) | Feb 09, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [df4d59acd5](https://linux-hardware.org/?probe=df4d59acd5) | Feb 07, 2023 |
| Dell          | Inspiron 7405 2n1           | Convertible | [fa32fd369b](https://linux-hardware.org/?probe=fa32fd369b) | Feb 07, 2023 |
| Dell          | Inspiron 7405 2n1           | Convertible | [fe5eeacae5](https://linux-hardware.org/?probe=fe5eeacae5) | Feb 07, 2023 |
| HP            | 2B34                        | Desktop     | [3376fc38b3](https://linux-hardware.org/?probe=3376fc38b3) | Feb 05, 2023 |
| HP            | 802F                        | Desktop     | [b36a46a944](https://linux-hardware.org/?probe=b36a46a944) | Feb 03, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [bc685693a6](https://linux-hardware.org/?probe=bc685693a6) | Jan 30, 2023 |
| Dell          | Inspiron 3580               | Notebook    | [e049beb54a](https://linux-hardware.org/?probe=e049beb54a) | Jan 28, 2023 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [9a1bab8f2c](https://linux-hardware.org/?probe=9a1bab8f2c) | Jan 26, 2023 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [8bc1c22b23](https://linux-hardware.org/?probe=8bc1c22b23) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Dell          | G15 5511                    | Notebook    | [cea8996d31](https://linux-hardware.org/?probe=cea8996d31) | Jan 23, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [fc8a27e6c5](https://linux-hardware.org/?probe=fc8a27e6c5) | Jan 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b36d7e8eb](https://linux-hardware.org/?probe=7b36d7e8eb) | Jan 17, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [93380bb1f5](https://linux-hardware.org/?probe=93380bb1f5) | Jan 17, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [58db914ce7](https://linux-hardware.org/?probe=58db914ce7) | Jan 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [482cc76bce](https://linux-hardware.org/?probe=482cc76bce) | Jan 14, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [662223c5f6](https://linux-hardware.org/?probe=662223c5f6) | Jan 14, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [85969e813b](https://linux-hardware.org/?probe=85969e813b) | Jan 13, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3cd650450c](https://linux-hardware.org/?probe=3cd650450c) | Jan 12, 2023 |
| HP            | 3047h                       | Desktop     | [0dd7c7c08f](https://linux-hardware.org/?probe=0dd7c7c08f) | Jan 11, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [9464593531](https://linux-hardware.org/?probe=9464593531) | Jan 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [cedf3a8ef8](https://linux-hardware.org/?probe=cedf3a8ef8) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [eab4c8b296](https://linux-hardware.org/?probe=eab4c8b296) | Jan 06, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| HP            | Pavilion 15                 | Notebook    | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3d50b74a6b](https://linux-hardware.org/?probe=3d50b74a6b) | Dec 23, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [00e62a7231](https://linux-hardware.org/?probe=00e62a7231) | Dec 23, 2022 |
| Gigabyte      | GA-990FXA-D3                | Desktop     | [30822e6e18](https://linux-hardware.org/?probe=30822e6e18) | Dec 22, 2022 |
| Dell          | Latitude E7470              | Notebook    | [2894205731](https://linux-hardware.org/?probe=2894205731) | Dec 19, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c8b402d4df](https://linux-hardware.org/?probe=c8b402d4df) | Dec 18, 2022 |
| Dell          | Latitude 5580               | Notebook    | [b45e1798cc](https://linux-hardware.org/?probe=b45e1798cc) | Dec 18, 2022 |
| HP            | 15                          | Notebook    | [95f40991cc](https://linux-hardware.org/?probe=95f40991cc) | Dec 18, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [2c57417bdf](https://linux-hardware.org/?probe=2c57417bdf) | Dec 16, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1613228bb2](https://linux-hardware.org/?probe=1613228bb2) | Dec 08, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [04a09baf04](https://linux-hardware.org/?probe=04a09baf04) | Dec 08, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| ASUSTek       | P6T                         | Desktop     | [8268d853c9](https://linux-hardware.org/?probe=8268d853c9) | Dec 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| HP            | 1850                        | Desktop     | [1d0a3a4461](https://linux-hardware.org/?probe=1d0a3a4461) | Nov 29, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [6c7a9e7fe5](https://linux-hardware.org/?probe=6c7a9e7fe5) | Nov 25, 2022 |
| HP            | ENVY m6                     | Notebook    | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [d4ed3112e5](https://linux-hardware.org/?probe=d4ed3112e5) | Nov 21, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [c565a2d0fc](https://linux-hardware.org/?probe=c565a2d0fc) | Nov 21, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Pegatron      | 2A94h                       | Desktop     | [be99475703](https://linux-hardware.org/?probe=be99475703) | Nov 19, 2022 |
| Dell          | Inspiron 3593               | Notebook    | [f5c9f5e8e1](https://linux-hardware.org/?probe=f5c9f5e8e1) | Nov 19, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [bc0980a6df](https://linux-hardware.org/?probe=bc0980a6df) | Nov 16, 2022 |
| Hampoo        | Cherry Trail CR             | Notebook    | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [ef49631a3c](https://linux-hardware.org/?probe=ef49631a3c) | Nov 12, 2022 |
| Samsung       | 275E4E/275E5E               | Notebook    | [0eba8cf68e](https://linux-hardware.org/?probe=0eba8cf68e) | Nov 09, 2022 |
| Dell          | Precision 5520              | Notebook    | [a96e7097e1](https://linux-hardware.org/?probe=a96e7097e1) | Nov 03, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [8575548418](https://linux-hardware.org/?probe=8575548418) | Oct 28, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [38c23f070a](https://linux-hardware.org/?probe=38c23f070a) | Oct 27, 2022 |
| Dell          | Latitude E7270              | Notebook    | [7c249e55c8](https://linux-hardware.org/?probe=7c249e55c8) | Oct 27, 2022 |
| HP            | Notebook                    | Notebook    | [d713217453](https://linux-hardware.org/?probe=d713217453) | Oct 23, 2022 |
| HP            | Notebook                    | Notebook    | [ef9adb0e8a](https://linux-hardware.org/?probe=ef9adb0e8a) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| Acer          | Predator PO3-630            | Desktop     | [aae61f30c7](https://linux-hardware.org/?probe=aae61f30c7) | Oct 20, 2022 |
| Dell          | G15 5510                    | Notebook    | [1286ecf9dd](https://linux-hardware.org/?probe=1286ecf9dd) | Oct 18, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a360479032](https://linux-hardware.org/?probe=a360479032) | Oct 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [72e2c65863](https://linux-hardware.org/?probe=72e2c65863) | Oct 13, 2022 |
| HP            | 18E7                        | Desktop     | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | Desktop     | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Sony          | VPCEH3LFX                   | Notebook    | [fbb59e09fc](https://linux-hardware.org/?probe=fbb59e09fc) | Oct 07, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [6f0af51d33](https://linux-hardware.org/?probe=6f0af51d33) | Oct 06, 2022 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [843cabf6e6](https://linux-hardware.org/?probe=843cabf6e6) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| HP            | ENVY m6                     | Notebook    | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| HP            | 1850                        | Desktop     | [f111f19884](https://linux-hardware.org/?probe=f111f19884) | Oct 04, 2022 |
| HP            | Notebook                    | Notebook    | [a30c1af9a5](https://linux-hardware.org/?probe=a30c1af9a5) | Sep 30, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [c83049a0f6](https://linux-hardware.org/?probe=c83049a0f6) | Sep 29, 2022 |
| HP            | 843C                        | Desktop     | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [113f7431d5](https://linux-hardware.org/?probe=113f7431d5) | Sep 28, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [cf8fefa8b5](https://linux-hardware.org/?probe=cf8fefa8b5) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [d0f2ed977a](https://linux-hardware.org/?probe=d0f2ed977a) | Sep 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [3f9e2bb677](https://linux-hardware.org/?probe=3f9e2bb677) | Sep 23, 2022 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [10103bf87f](https://linux-hardware.org/?probe=10103bf87f) | Sep 23, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [56bff32d34](https://linux-hardware.org/?probe=56bff32d34) | Sep 21, 2022 |
| Dell          | Latitude 3540               | Notebook    | [7e56d744b7](https://linux-hardware.org/?probe=7e56d744b7) | Sep 21, 2022 |
| Dell          | Latitude 3540               | Notebook    | [0216f52b36](https://linux-hardware.org/?probe=0216f52b36) | Sep 21, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | Notebook    | [fef4bc54eb](https://linux-hardware.org/?probe=fef4bc54eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad Edge 0578JJG       | Notebook    | [db6bdb0dbd](https://linux-hardware.org/?probe=db6bdb0dbd) | Sep 20, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [e91328a3c2](https://linux-hardware.org/?probe=e91328a3c2) | Sep 20, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [085558878e](https://linux-hardware.org/?probe=085558878e) | Sep 20, 2022 |
| Samsung       | Lumpy                       | Notebook    | [9c1fd4f253](https://linux-hardware.org/?probe=9c1fd4f253) | Sep 18, 2022 |
| Samsung       | Lumpy                       | Notebook    | [1ea9c40a42](https://linux-hardware.org/?probe=1ea9c40a42) | Sep 15, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [12d6e02796](https://linux-hardware.org/?probe=12d6e02796) | Sep 15, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| HP            | ZBook Studio x360 G5        | Convertible | [5fe757d559](https://linux-hardware.org/?probe=5fe757d559) | Sep 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0356a8d7a1](https://linux-hardware.org/?probe=0356a8d7a1) | Sep 05, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [91001df765](https://linux-hardware.org/?probe=91001df765) | Sep 04, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [9281a357e0](https://linux-hardware.org/?probe=9281a357e0) | Sep 04, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [ac5ecfc107](https://linux-hardware.org/?probe=ac5ecfc107) | Sep 04, 2022 |
| HP            | Pavilion 15                 | Notebook    | [ed8a48954e](https://linux-hardware.org/?probe=ed8a48954e) | Sep 04, 2022 |
| Dell          | G15 5510                    | Notebook    | [fbcdd4d274](https://linux-hardware.org/?probe=fbcdd4d274) | Sep 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [93980a32fc](https://linux-hardware.org/?probe=93980a32fc) | Sep 02, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e5545fc36a](https://linux-hardware.org/?probe=e5545fc36a) | Aug 30, 2022 |
| HP            | EliteBook 8560w             | Notebook    | [0ea43b9010](https://linux-hardware.org/?probe=0ea43b9010) | Aug 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [750425c2c2](https://linux-hardware.org/?probe=750425c2c2) | Aug 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [77a2156c5a](https://linux-hardware.org/?probe=77a2156c5a) | Aug 21, 2022 |
| HP            | ProBook 655 G1              | Notebook    | [e37e59a165](https://linux-hardware.org/?probe=e37e59a165) | Aug 20, 2022 |
| Gigabyte      | H61M-S2P                    | Desktop     | [49aedf1cf8](https://linux-hardware.org/?probe=49aedf1cf8) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [78ff8418f9](https://linux-hardware.org/?probe=78ff8418f9) | Aug 17, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [c62eb0135b](https://linux-hardware.org/?probe=c62eb0135b) | Aug 15, 2022 |
| HP            | EliteBook 8560w             | Notebook    | [86b3f33331](https://linux-hardware.org/?probe=86b3f33331) | Aug 14, 2022 |
| HP            | EliteBook 8560w             | Notebook    | [4ea7538e24](https://linux-hardware.org/?probe=4ea7538e24) | Aug 14, 2022 |
| HP            | 18E7                        | Desktop     | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| HP            | 1850                        | Desktop     | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e97781a7cc](https://linux-hardware.org/?probe=e97781a7cc) | Aug 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [abe7afa30f](https://linux-hardware.org/?probe=abe7afa30f) | Aug 09, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e0403fe18f](https://linux-hardware.org/?probe=e0403fe18f) | Aug 08, 2022 |
| Toshiba       | NB250                       | Notebook    | [e320782bcf](https://linux-hardware.org/?probe=e320782bcf) | Jul 30, 2022 |
| HP            | 18E4                        | Desktop     | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| HP            | G62                         | Notebook    | [dd114592c4](https://linux-hardware.org/?probe=dd114592c4) | Jul 27, 2022 |
| HP            | 3647h                       | Desktop     | [ed98e07a47](https://linux-hardware.org/?probe=ed98e07a47) | Jul 26, 2022 |
| MSI           | MS-14Y1                     | Notebook    | [782beac866](https://linux-hardware.org/?probe=782beac866) | Jul 18, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [5510f2d904](https://linux-hardware.org/?probe=5510f2d904) | Jul 18, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [99eacb5700](https://linux-hardware.org/?probe=99eacb5700) | Jul 11, 2022 |
| Panasonic     | FZG1-3                      | Notebook    | [753cc1d311](https://linux-hardware.org/?probe=753cc1d311) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | Notebook    | [01d4651376](https://linux-hardware.org/?probe=01d4651376) | Jul 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1f42376321](https://linux-hardware.org/?probe=1f42376321) | Jul 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [977cf239f9](https://linux-hardware.org/?probe=977cf239f9) | Jul 08, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [b1d77e2a01](https://linux-hardware.org/?probe=b1d77e2a01) | Jul 05, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [8e2249c595](https://linux-hardware.org/?probe=8e2249c595) | Jul 05, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [342facf96e](https://linux-hardware.org/?probe=342facf96e) | Jul 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [21dd020507](https://linux-hardware.org/?probe=21dd020507) | Jul 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [e35e3b2e52](https://linux-hardware.org/?probe=e35e3b2e52) | Jul 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f76f8dff7a](https://linux-hardware.org/?probe=f76f8dff7a) | Jun 30, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [1157ee7e3a](https://linux-hardware.org/?probe=1157ee7e3a) | Jun 21, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [ee2a9b3c87](https://linux-hardware.org/?probe=ee2a9b3c87) | Jun 20, 2022 |
| Dell          | G5 5587                     | Notebook    | [9f2ca6b48b](https://linux-hardware.org/?probe=9f2ca6b48b) | Jun 18, 2022 |
| Lenovo        | B40-80 80F6                 | Notebook    | [7449f0f8d2](https://linux-hardware.org/?probe=7449f0f8d2) | Jun 13, 2022 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [428eebd42f](https://linux-hardware.org/?probe=428eebd42f) | Jun 13, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [1794b92b61](https://linux-hardware.org/?probe=1794b92b61) | Jun 12, 2022 |
| Dell          | Latitude E6410              | Notebook    | [184348232a](https://linux-hardware.org/?probe=184348232a) | Jun 11, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [4668e3772e](https://linux-hardware.org/?probe=4668e3772e) | Jun 05, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [208a2ee137](https://linux-hardware.org/?probe=208a2ee137) | Jun 02, 2022 |
| HP            | 0A80h                       | Desktop     | [7e5c6cf61e](https://linux-hardware.org/?probe=7e5c6cf61e) | May 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9a3948a7e8](https://linux-hardware.org/?probe=9a3948a7e8) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [2e520c1e13](https://linux-hardware.org/?probe=2e520c1e13) | May 23, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9be915450d](https://linux-hardware.org/?probe=9be915450d) | May 23, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [4058369652](https://linux-hardware.org/?probe=4058369652) | May 21, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [bd33528d52](https://linux-hardware.org/?probe=bd33528d52) | May 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a18593bb5b](https://linux-hardware.org/?probe=a18593bb5b) | May 07, 2022 |
| Dell          | 03NVJ6 A04                  | Desktop     | [ebacf887d7](https://linux-hardware.org/?probe=ebacf887d7) | May 04, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [6d8f615203](https://linux-hardware.org/?probe=6d8f615203) | Apr 30, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [fb1248d6be](https://linux-hardware.org/?probe=fb1248d6be) | Apr 29, 2022 |
| HP            | Pavilion 15                 | Notebook    | [fee7e96d70](https://linux-hardware.org/?probe=fee7e96d70) | Apr 28, 2022 |
| Fujitsu       | FMVA06004                   | Notebook    | [4c63e1bcc2](https://linux-hardware.org/?probe=4c63e1bcc2) | Apr 25, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [e6ef37e2a0](https://linux-hardware.org/?probe=e6ef37e2a0) | Apr 24, 2022 |
| Dell          | Latitude 3440               | Notebook    | [a0c0358f78](https://linux-hardware.org/?probe=a0c0358f78) | Apr 24, 2022 |
| HP            | 8053                        | Desktop     | [f214dbdf74](https://linux-hardware.org/?probe=f214dbdf74) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [a1636896d9](https://linux-hardware.org/?probe=a1636896d9) | Apr 22, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [03481a94b3](https://linux-hardware.org/?probe=03481a94b3) | Apr 22, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b84eab559e](https://linux-hardware.org/?probe=b84eab559e) | Apr 21, 2022 |
| HP            | 15                          | Notebook    | [3253e0fc56](https://linux-hardware.org/?probe=3253e0fc56) | Apr 21, 2022 |
| Sony          | SVT1121B2EW                 | Notebook    | [dd43f45353](https://linux-hardware.org/?probe=dd43f45353) | Apr 21, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [6843f2bcfe](https://linux-hardware.org/?probe=6843f2bcfe) | Apr 20, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| HP            | 8265                        | Desktop     | [6a7abd0db8](https://linux-hardware.org/?probe=6a7abd0db8) | Apr 19, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [f3afe20dae](https://linux-hardware.org/?probe=f3afe20dae) | Apr 16, 2022 |
| Alienware     | 17                          | Notebook    | [b9b420077c](https://linux-hardware.org/?probe=b9b420077c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [fecdd237a4](https://linux-hardware.org/?probe=fecdd237a4) | Apr 11, 2022 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [4368114931](https://linux-hardware.org/?probe=4368114931) | Apr 04, 2022 |
| Dell          | 0WK833                      | Desktop     | [efee7c0ec6](https://linux-hardware.org/?probe=efee7c0ec6) | Apr 02, 2022 |
| Dell          | 0WK833                      | Desktop     | [a8703c7598](https://linux-hardware.org/?probe=a8703c7598) | Apr 02, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f93e8f46c2](https://linux-hardware.org/?probe=f93e8f46c2) | Apr 01, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [2da8f96ad8](https://linux-hardware.org/?probe=2da8f96ad8) | Mar 29, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [bd875807ce](https://linux-hardware.org/?probe=bd875807ce) | Mar 26, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [96f9ba743f](https://linux-hardware.org/?probe=96f9ba743f) | Mar 25, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [55a2911462](https://linux-hardware.org/?probe=55a2911462) | Mar 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Notebook                    | Notebook    | [4cc8a23994](https://linux-hardware.org/?probe=4cc8a23994) | Mar 22, 2022 |
| HP            | Notebook                    | Notebook    | [cb2c910f05](https://linux-hardware.org/?probe=cb2c910f05) | Mar 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [99dc5cde41](https://linux-hardware.org/?probe=99dc5cde41) | Mar 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d74cd69ff9](https://linux-hardware.org/?probe=d74cd69ff9) | Mar 20, 2022 |
| HP            | Pavilion 15                 | Notebook    | [0f3cb22c3d](https://linux-hardware.org/?probe=0f3cb22c3d) | Mar 20, 2022 |
| HP            | G62                         | Notebook    | [5a5a9ce935](https://linux-hardware.org/?probe=5a5a9ce935) | Mar 20, 2022 |
| Dell          | 0804P1 A05                  | Server      | [97777b0db4](https://linux-hardware.org/?probe=97777b0db4) | Mar 17, 2022 |
| HP            | ENVY dv6                    | Notebook    | [39ff0aa86d](https://linux-hardware.org/?probe=39ff0aa86d) | Mar 17, 2022 |
| Dell          | Latitude 3410               | Notebook    | [d21a10beb4](https://linux-hardware.org/?probe=d21a10beb4) | Mar 10, 2022 |
| Gigabyte      | H110M-S2PT-CF               | Desktop     | [506afdf9c7](https://linux-hardware.org/?probe=506afdf9c7) | Mar 09, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [b3ba67d085](https://linux-hardware.org/?probe=b3ba67d085) | Mar 08, 2022 |
| Intel         | DQ965MT AAD36265-505        | Desktop     | [93758c64fa](https://linux-hardware.org/?probe=93758c64fa) | Mar 07, 2022 |
| Acer          | Aspire ES1-331              | Notebook    | [cbba045d50](https://linux-hardware.org/?probe=cbba045d50) | Mar 05, 2022 |
| Dell          | 0XG309                      | Desktop     | [535c8e4e2e](https://linux-hardware.org/?probe=535c8e4e2e) | Feb 28, 2022 |
| Dell          | 0XG309                      | Desktop     | [d9f753df89](https://linux-hardware.org/?probe=d9f753df89) | Feb 28, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [57bb50b654](https://linux-hardware.org/?probe=57bb50b654) | Feb 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f0692aebbe](https://linux-hardware.org/?probe=f0692aebbe) | Feb 25, 2022 |
| Dell          | Venue 10 Pro 5056           | Notebook    | [faf162367f](https://linux-hardware.org/?probe=faf162367f) | Feb 25, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [732784f9ec](https://linux-hardware.org/?probe=732784f9ec) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [2c3ac58820](https://linux-hardware.org/?probe=2c3ac58820) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [d1fd917c74](https://linux-hardware.org/?probe=d1fd917c74) | Feb 24, 2022 |
| HP            | 3397                        | Desktop     | [de499e61b9](https://linux-hardware.org/?probe=de499e61b9) | Feb 22, 2022 |
| HP            | ENVY dv6                    | Notebook    | [6d07aead9f](https://linux-hardware.org/?probe=6d07aead9f) | Feb 21, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [2ddf4948c9](https://linux-hardware.org/?probe=2ddf4948c9) | Feb 19, 2022 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [d799c9b2f2](https://linux-hardware.org/?probe=d799c9b2f2) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [5760b6c177](https://linux-hardware.org/?probe=5760b6c177) | Feb 14, 2022 |
| HP            | 3397                        | Desktop     | [06f2eef752](https://linux-hardware.org/?probe=06f2eef752) | Feb 13, 2022 |
| Dell          | G3 3500                     | Notebook    | [0010596573](https://linux-hardware.org/?probe=0010596573) | Feb 10, 2022 |
| HP            | 1906                        | Desktop     | [c2107ad290](https://linux-hardware.org/?probe=c2107ad290) | Feb 08, 2022 |
| HP            | 1906                        | Desktop     | [9f08673e43](https://linux-hardware.org/?probe=9f08673e43) | Feb 08, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9129341c42](https://linux-hardware.org/?probe=9129341c42) | Jan 24, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| Sony          | SVF15328CXB                 | Notebook    | [d55d8f394d](https://linux-hardware.org/?probe=d55d8f394d) | Jan 21, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [dfbb7c034f](https://linux-hardware.org/?probe=dfbb7c034f) | Jan 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [4edc707b67](https://linux-hardware.org/?probe=4edc707b67) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [71a9fb4409](https://linux-hardware.org/?probe=71a9fb4409) | Jan 13, 2022 |
| Lenovo        | ThinkPad X1 Yoga 1st 20F... | Convertible | [9087ece92b](https://linux-hardware.org/?probe=9087ece92b) | Jan 13, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [b70942532f](https://linux-hardware.org/?probe=b70942532f) | Jan 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [bda1b240c9](https://linux-hardware.org/?probe=bda1b240c9) | Dec 28, 2021 |
| Lenovo        | BRASWELL NOK                | Desktop     | [0b12f54345](https://linux-hardware.org/?probe=0b12f54345) | Dec 26, 2021 |
| HP            | 3047h                       | Desktop     | [71b6f0abea](https://linux-hardware.org/?probe=71b6f0abea) | Dec 25, 2021 |
| Dell          | G15 5510                    | Notebook    | [1209f0844f](https://linux-hardware.org/?probe=1209f0844f) | Dec 20, 2021 |
| Dell          | G15 5510                    | Notebook    | [e5039b3b7d](https://linux-hardware.org/?probe=e5039b3b7d) | Dec 18, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7326d20e8a](https://linux-hardware.org/?probe=7326d20e8a) | Dec 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [357bfe0849](https://linux-hardware.org/?probe=357bfe0849) | Dec 11, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [f8dc028352](https://linux-hardware.org/?probe=f8dc028352) | Dec 08, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [dd578dae69](https://linux-hardware.org/?probe=dd578dae69) | Dec 05, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [d15350584d](https://linux-hardware.org/?probe=d15350584d) | Dec 05, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [d6acd43784](https://linux-hardware.org/?probe=d6acd43784) | Nov 25, 2021 |
| ASUSTek       | VivoBook E14 E402YA_E402... | Notebook    | [e820cb3456](https://linux-hardware.org/?probe=e820cb3456) | Nov 25, 2021 |
| HP            | 83DD                        | Mini pc     | [9ec6f2e5fe](https://linux-hardware.org/?probe=9ec6f2e5fe) | Nov 16, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [49f973804a](https://linux-hardware.org/?probe=49f973804a) | Nov 13, 2021 |
| Dell          | Latitude 5420               | Notebook    | [973018da2b](https://linux-hardware.org/?probe=973018da2b) | Nov 08, 2021 |
| Dell          | Precision WorkStation 49... | Desktop     | [b40b65db05](https://linux-hardware.org/?probe=b40b65db05) | Nov 07, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [eacb69d71e](https://linux-hardware.org/?probe=eacb69d71e) | Nov 05, 2021 |
| Lenovo        | ThinkPad E14 20RAS0CM00     | Notebook    | [a35aaaeb6d](https://linux-hardware.org/?probe=a35aaaeb6d) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e8781db5ab](https://linux-hardware.org/?probe=e8781db5ab) | Oct 31, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e1978d5164](https://linux-hardware.org/?probe=e1978d5164) | Oct 31, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [08d287d2e2](https://linux-hardware.org/?probe=08d287d2e2) | Oct 30, 2021 |
| Dell          | 0CRH6C A01                  | Desktop     | [ff796824d2](https://linux-hardware.org/?probe=ff796824d2) | Oct 30, 2021 |
| HP            | 1850                        | Desktop     | [b155e888a5](https://linux-hardware.org/?probe=b155e888a5) | Oct 24, 2021 |
| HP            | ProBook 6460b               | Notebook    | [317c62df4b](https://linux-hardware.org/?probe=317c62df4b) | Oct 23, 2021 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [e66a1ae149](https://linux-hardware.org/?probe=e66a1ae149) | Oct 21, 2021 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [7339dc6e79](https://linux-hardware.org/?probe=7339dc6e79) | Oct 21, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [85036968bb](https://linux-hardware.org/?probe=85036968bb) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [2db5d6dc7c](https://linux-hardware.org/?probe=2db5d6dc7c) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [1faf3f28e5](https://linux-hardware.org/?probe=1faf3f28e5) | Oct 20, 2021 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [8c1989ae75](https://linux-hardware.org/?probe=8c1989ae75) | Oct 16, 2021 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [6c2357c3a8](https://linux-hardware.org/?probe=6c2357c3a8) | Oct 16, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [831fff897a](https://linux-hardware.org/?probe=831fff897a) | Oct 15, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d69772c626](https://linux-hardware.org/?probe=d69772c626) | Oct 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0086ED     | Notebook    | [2db7f4be45](https://linux-hardware.org/?probe=2db7f4be45) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e8ae6d00a2](https://linux-hardware.org/?probe=e8ae6d00a2) | Oct 12, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d0fb953c7e](https://linux-hardware.org/?probe=d0fb953c7e) | Oct 11, 2021 |
| Alienware     | 0P0JWX A00                  | Desktop     | [bc2b8a4fa5](https://linux-hardware.org/?probe=bc2b8a4fa5) | Oct 11, 2021 |
| Alienware     | 0P0JWX A00                  | Desktop     | [879496302d](https://linux-hardware.org/?probe=879496302d) | Oct 11, 2021 |
| Alienware     | 0P0JWX A00                  | Desktop     | [bbe7dc3f56](https://linux-hardware.org/?probe=bbe7dc3f56) | Oct 11, 2021 |
| HP            | ProBook 645 G1              | Notebook    | [102902cf2b](https://linux-hardware.org/?probe=102902cf2b) | Oct 10, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [51d51a675d](https://linux-hardware.org/?probe=51d51a675d) | Oct 10, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [f8d957d29f](https://linux-hardware.org/?probe=f8d957d29f) | Oct 09, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [6c5495590b](https://linux-hardware.org/?probe=6c5495590b) | Oct 08, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [b95391e679](https://linux-hardware.org/?probe=b95391e679) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [61c4dc2ac2](https://linux-hardware.org/?probe=61c4dc2ac2) | Oct 03, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6df5eb55f0](https://linux-hardware.org/?probe=6df5eb55f0) | Oct 03, 2021 |
| ASUSTek       | N501JW                      | Notebook    | [0e37d3409d](https://linux-hardware.org/?probe=0e37d3409d) | Oct 01, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [48b4af3338](https://linux-hardware.org/?probe=48b4af3338) | Sep 01, 2021 |
| HP            | 1632                        | Desktop     | [269b4ad58e](https://linux-hardware.org/?probe=269b4ad58e) | Aug 22, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [3eb5c512ad](https://linux-hardware.org/?probe=3eb5c512ad) | Aug 19, 2021 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [26cae4bb7a](https://linux-hardware.org/?probe=26cae4bb7a) | Aug 16, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [d2e64a8d57](https://linux-hardware.org/?probe=d2e64a8d57) | Aug 08, 2021 |
| HP            | Compaq 2510p                | Notebook    | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | Notebook    | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Packard Be... | EasyNote LX                 | Notebook    | [125ad979fe](https://linux-hardware.org/?probe=125ad979fe) | Aug 06, 2021 |
| Intel         | DG31PR AAD97573-205         | Desktop     | [9bda168dc6](https://linux-hardware.org/?probe=9bda168dc6) | Aug 04, 2021 |
| Dell          | 0DR845                      | Desktop     | [1714388038](https://linux-hardware.org/?probe=1714388038) | Aug 03, 2021 |
| Dell          | G3 3579                     | Notebook    | [4f7539c771](https://linux-hardware.org/?probe=4f7539c771) | Jul 30, 2021 |
| Dell          | Inspiron 1564               | Notebook    | [08fc5f3b99](https://linux-hardware.org/?probe=08fc5f3b99) | Jul 27, 2021 |
| HP            | 3047h                       | Desktop     | [58b480757e](https://linux-hardware.org/?probe=58b480757e) | Jul 18, 2021 |
| HP            | 3047h                       | Desktop     | [40a25f223c](https://linux-hardware.org/?probe=40a25f223c) | Jul 18, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b07887acc1](https://linux-hardware.org/?probe=b07887acc1) | Jul 18, 2021 |
| HP            | 0AE8h C                     | Desktop     | [b8b861a13d](https://linux-hardware.org/?probe=b8b861a13d) | Jul 13, 2021 |
| MSI           | MS-7507                     | Desktop     | [ede4b6fc34](https://linux-hardware.org/?probe=ede4b6fc34) | Jul 11, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [428dcd6503](https://linux-hardware.org/?probe=428dcd6503) | Jul 07, 2021 |
| Dell          | G3 3579                     | Notebook    | [97c520db01](https://linux-hardware.org/?probe=97c520db01) | Jul 04, 2021 |
| HP            | 0A54h                       | Desktop     | [c8d8757784](https://linux-hardware.org/?probe=c8d8757784) | Jul 02, 2021 |
| ASUSTek       | X200MA                      | Notebook    | [c9edeec38a](https://linux-hardware.org/?probe=c9edeec38a) | Jun 26, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [8c7ef2bc15](https://linux-hardware.org/?probe=8c7ef2bc15) | Jun 20, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [4c397b8b70](https://linux-hardware.org/?probe=4c397b8b70) | Jun 20, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [05dbeca379](https://linux-hardware.org/?probe=05dbeca379) | Jun 17, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [f685842bb1](https://linux-hardware.org/?probe=f685842bb1) | Jun 16, 2021 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [696a1c9564](https://linux-hardware.org/?probe=696a1c9564) | Jun 13, 2021 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [c432c046f1](https://linux-hardware.org/?probe=c432c046f1) | Jun 04, 2021 |
| HP            | 158B                        | Desktop     | [cc2472f216](https://linux-hardware.org/?probe=cc2472f216) | Jun 03, 2021 |
| HP            | 83E1                        | Desktop     | [a10433a3cb](https://linux-hardware.org/?probe=a10433a3cb) | Jun 03, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [ace51e66cb](https://linux-hardware.org/?probe=ace51e66cb) | May 31, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [e57c2fb16d](https://linux-hardware.org/?probe=e57c2fb16d) | May 30, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [976e39384a](https://linux-hardware.org/?probe=976e39384a) | May 30, 2021 |
| HP            | ProBook 645 G1              | Notebook    | [a92458c2db](https://linux-hardware.org/?probe=a92458c2db) | May 26, 2021 |
| HP            | 2129                        | Desktop     | [3991895525](https://linux-hardware.org/?probe=3991895525) | May 23, 2021 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [6ae217a5a8](https://linux-hardware.org/?probe=6ae217a5a8) | May 21, 2021 |
| Dell          | G5 5587                     | Notebook    | [fae808ae7d](https://linux-hardware.org/?probe=fae808ae7d) | May 02, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [b902c359da](https://linux-hardware.org/?probe=b902c359da) | Apr 30, 2021 |
| Unknown       | Unknown                     | Phone       | [da645fe697](https://linux-hardware.org/?probe=da645fe697) | Apr 25, 2021 |
| Gigabyte      | H55M-S2V                    | Desktop     | [9170ec8194](https://linux-hardware.org/?probe=9170ec8194) | Apr 20, 2021 |
| HP            | Notebook                    | Notebook    | [872a5f9112](https://linux-hardware.org/?probe=872a5f9112) | Apr 18, 2021 |
| HP            | 3397                        | Desktop     | [bb31fb43b4](https://linux-hardware.org/?probe=bb31fb43b4) | Apr 17, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [b7fe68e060](https://linux-hardware.org/?probe=b7fe68e060) | Apr 17, 2021 |
| Hampoo        | Cherry Trail CR             | Notebook    | [101c47c9a2](https://linux-hardware.org/?probe=101c47c9a2) | Apr 17, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [3200f41cf0](https://linux-hardware.org/?probe=3200f41cf0) | Apr 13, 2021 |
| HP            | 3397                        | Desktop     | [aa5cc70dda](https://linux-hardware.org/?probe=aa5cc70dda) | Apr 12, 2021 |
| HP            | 15                          | Notebook    | [27bcfc6f15](https://linux-hardware.org/?probe=27bcfc6f15) | Apr 10, 2021 |
| HP            | 15                          | Notebook    | [aebfb75282](https://linux-hardware.org/?probe=aebfb75282) | Apr 10, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2c17afdb0a](https://linux-hardware.org/?probe=2c17afdb0a) | Apr 08, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [820db16b30](https://linux-hardware.org/?probe=820db16b30) | Apr 08, 2021 |
| Dell          | Inspiron 3580               | Notebook    | [fcb5ccbc6c](https://linux-hardware.org/?probe=fcb5ccbc6c) | Apr 08, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [a3ecba2a79](https://linux-hardware.org/?probe=a3ecba2a79) | Apr 06, 2021 |
| Dell          | 0F5C5X A00                  | Desktop     | [7eda600c97](https://linux-hardware.org/?probe=7eda600c97) | Apr 05, 2021 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [bb1ef328b0](https://linux-hardware.org/?probe=bb1ef328b0) | Mar 30, 2021 |
| HP            | Unknown                     | Notebook    | [984ec41c5f](https://linux-hardware.org/?probe=984ec41c5f) | Mar 28, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [10aaa9110b](https://linux-hardware.org/?probe=10aaa9110b) | Mar 23, 2021 |
| Gigabyte      | H61M-S2P                    | Desktop     | [280d47279c](https://linux-hardware.org/?probe=280d47279c) | Mar 23, 2021 |
| Gigabyte      | H61M-S2P                    | Desktop     | [a33947d95c](https://linux-hardware.org/?probe=a33947d95c) | Mar 23, 2021 |
| HP            | 2215                        | Desktop     | [baefda0ada](https://linux-hardware.org/?probe=baefda0ada) | Mar 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ecb76b364b](https://linux-hardware.org/?probe=ecb76b364b) | Mar 20, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Egypt/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 87        | 9.24%   |
| Ubuntu 22.04       | 71        | 7.54%   |
| Ubuntu 18.04       | 45        | 4.78%   |
| Arch Rolling       | 36        | 3.82%   |
| Zorin 17           | 33        | 3.5%    |
| Zorin 16           | 24        | 2.55%   |
| Ubuntu 24.04       | 22        | 2.34%   |
| OpenMandriva 4.3   | 21        | 2.23%   |
| Fedora 40          | 21        | 2.23%   |
| Pop!_OS 22.04      | 19        | 2.02%   |
| ArcoLinux Rolling  | 18        | 1.91%   |
| Linux Mint 22.1    | 17        | 1.8%    |
| Fedora 39          | 16        | 1.7%    |
| Fedora 41          | 15        | 1.59%   |
| Debian 12          | 15        | 1.59%   |
| Linux Mint 22.2    | 12        | 1.27%   |
| Fedora 38          | 12        | 1.27%   |
| Fedora 42          | 11        | 1.17%   |
| OpenMandriva 4.2   | 10        | 1.06%   |
| Manjaro            | 10        | 1.06%   |
| Zorin 15           | 9         | 0.96%   |
| Ubuntu 19.10       | 9         | 0.96%   |
| Ubuntu 20.10       | 8         | 0.85%   |
| OpenMandriva 23.01 | 8         | 0.85%   |
| Ubuntu 22.10       | 7         | 0.74%   |
| Ubuntu 21.10       | 7         | 0.74%   |
| Pop!_OS 20.10      | 7         | 0.74%   |
| OpenMandriva 25.90 | 7         | 0.74%   |
| Arch               | 7         | 0.74%   |
| Ubuntu 23.10       | 6         | 0.64%   |
| Linux Mint 20.3    | 6         | 0.64%   |
| Kali 2023.3        | 6         | 0.64%   |
| Fedora 36          | 6         | 0.64%   |
| Zorin 18           | 5         | 0.53%   |
| OpenMandriva 23.03 | 5         | 0.53%   |
| Linux Mint 21.2    | 5         | 0.53%   |
| Linux Mint 19.3    | 5         | 0.53%   |
| KDE neon 20.04     | 5         | 0.53%   |
| Fedora 37          | 5         | 0.53%   |
| Fedora 35          | 5         | 0.53%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 281       | 31.02%  |
| Fedora        | 106       | 11.7%   |
| Zorin         | 71        | 7.84%   |
| Linux Mint    | 71        | 7.84%   |
| OpenMandriva  | 70        | 7.73%   |
| Arch          | 43        | 4.75%   |
| Pop!_OS       | 34        | 3.75%   |
| Kali          | 31        | 3.42%   |
| Debian        | 26        | 2.87%   |
| Manjaro       | 23        | 2.54%   |
| ArcoLinux     | 19        | 2.1%    |
| Kubuntu       | 13        | 1.43%   |
| ROSA          | 12        | 1.32%   |
| KDE neon      | 10        | 1.1%    |
| Endless       | 10        | 1.1%    |
| Elementary    | 9         | 0.99%   |
| Xubuntu       | 6         | 0.66%   |
| Parrot        | 6         | 0.66%   |
| MX            | 6         | 0.66%   |
| Nobara        | 5         | 0.55%   |
| EndeavourOS   | 4         | 0.44%   |
| BlackPanther  | 4         | 0.44%   |
| Ubuntu Unity  | 3         | 0.33%   |
| Ubuntu Budgie | 3         | 0.33%   |
| RHEL          | 3         | 0.33%   |
| Garuda Linux  | 3         | 0.33%   |
| Xero          | 2         | 0.22%   |
| Rocky Linux   | 2         | 0.22%   |
| openSUSE      | 2         | 0.22%   |
| Neptune OS    | 2         | 0.22%   |
| Lubuntu       | 2         | 0.22%   |
| LMDE          | 2         | 0.22%   |
| Gentoo        | 2         | 0.22%   |
| Clear Linux   | 2         | 0.22%   |
| CachyOS       | 2         | 0.22%   |
| Android       | 2         | 0.22%   |
| ALT Linux     | 2         | 0.22%   |
| Ultramarine   | 1         | 0.11%   |
| Ultimate      | 1         | 0.11%   |
| TUXEDO OS     | 1         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 18        | 1.8%    |
| 5.4.0-42-generic         | 17        | 1.7%    |
| 6.14.2-desktop-3omv2590  | 12        | 1.2%    |
| 5.10.14-desktop-1omv4002 | 10        | 1%      |
| 6.8.0-52-generic         | 8         | 0.8%    |
| 5.4.0-58-generic         | 8         | 0.8%    |
| 6.8.0-51-generic         | 6         | 0.6%    |
| 6.8.0-49-generic         | 6         | 0.6%    |
| 6.8.0-45-generic         | 6         | 0.6%    |
| 6.2.6-desktop-1omv2390   | 6         | 0.6%    |
| 6.14.0-37-generic        | 6         | 0.6%    |
| 6.1.1-desktop-1omv2290   | 6         | 0.6%    |
| 5.4.0-48-generic         | 6         | 0.6%    |
| 5.15.0-48-generic        | 6         | 0.6%    |
| 5.15.0-47-generic        | 6         | 0.6%    |
| 5.11.0-37-generic        | 6         | 0.6%    |
| 6.5.0-kali3-amd64        | 5         | 0.5%    |
| 6.5.0-35-generic         | 5         | 0.5%    |
| 6.5.0-28-generic         | 5         | 0.5%    |
| 6.5.0-18-generic         | 5         | 0.5%    |
| 6.2.0-39-generic         | 5         | 0.5%    |
| 6.14.0-33-generic        | 5         | 0.5%    |
| 6.14.0-15-generic        | 5         | 0.5%    |
| 5.8.0-7630-generic       | 5         | 0.5%    |
| 5.3.0-51-generic         | 5         | 0.5%    |
| 5.19.0-76051900-generic  | 5         | 0.5%    |
| 5.15.0-56-generic        | 5         | 0.5%    |
| 5.15.0-50-generic        | 5         | 0.5%    |
| 5.13.0-30-generic        | 5         | 0.5%    |
| 6.9.3-76060903-generic   | 4         | 0.4%    |
| 6.8.5-301.fc40.x86_64    | 4         | 0.4%    |
| 6.8.0-60-generic         | 4         | 0.4%    |
| 6.8.0-41-generic         | 4         | 0.4%    |
| 6.8.0-40-generic         | 4         | 0.4%    |
| 6.6.2-desktop-1omv2390   | 4         | 0.4%    |
| 6.2.0-26-generic         | 4         | 0.4%    |
| 6.12.10-76061203-generic | 4         | 0.4%    |
| 6.12.1-desktop-1omv2490  | 4         | 0.4%    |
| 6.1.0-23-amd64           | 4         | 0.4%    |
| 5.8.0-48-generic         | 4         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 85        | 8.82%   |
| 5.15.0  | 71        | 7.37%   |
| 6.8.0   | 62        | 6.43%   |
| 6.5.0   | 53        | 5.5%    |
| 5.3.0   | 30        | 3.11%   |
| 4.15.0  | 30        | 3.11%   |
| 6.14.0  | 27        | 2.8%    |
| 5.8.0   | 27        | 2.8%    |
| 5.19.0  | 25        | 2.59%   |
| 5.13.0  | 24        | 2.49%   |
| 5.11.0  | 21        | 2.18%   |
| 6.2.0   | 20        | 2.07%   |
| 6.1.0   | 20        | 2.07%   |
| 5.16.7  | 18        | 1.87%   |
| 5.0.0   | 18        | 1.87%   |
| 6.14.2  | 13        | 1.35%   |
| 6.11.0  | 13        | 1.35%   |
| 5.10.0  | 11        | 1.14%   |
| 4.18.0  | 11        | 1.14%   |
| 5.10.14 | 10        | 1.04%   |
| 6.6.2   | 7         | 0.73%   |
| 6.2.6   | 7         | 0.73%   |
| 6.1.1   | 6         | 0.62%   |
| 6.9.3   | 5         | 0.52%   |
| 6.6.9   | 5         | 0.52%   |
| 6.12.1  | 5         | 0.52%   |
| 6.8.9   | 4         | 0.41%   |
| 6.8.5   | 4         | 0.41%   |
| 6.4.11  | 4         | 0.41%   |
| 6.17.9  | 4         | 0.41%   |
| 6.12.10 | 4         | 0.41%   |
| 6.10.11 | 4         | 0.41%   |
| 5.16.0  | 4         | 0.41%   |
| 5.14.0  | 4         | 0.41%   |
| 4.19.0  | 4         | 0.41%   |
| 6.9.10  | 3         | 0.31%   |
| 6.8.11  | 3         | 0.31%   |
| 6.7.0   | 3         | 0.31%   |
| 6.6.16  | 3         | 0.31%   |
| 6.5.5   | 3         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 92        | 9.67%   |
| 5.15    | 81        | 8.52%   |
| 6.8     | 80        | 8.41%   |
| 6.5     | 60        | 6.31%   |
| 6.14    | 48        | 5.05%   |
| 6.1     | 36        | 3.79%   |
| 6.2     | 35        | 3.68%   |
| 5.3     | 33        | 3.47%   |
| 5.10    | 33        | 3.47%   |
| 6.6     | 32        | 3.36%   |
| 5.16    | 32        | 3.36%   |
| 5.8     | 31        | 3.26%   |
| 5.19    | 31        | 3.26%   |
| 4.15    | 30        | 3.15%   |
| 6.12    | 27        | 2.84%   |
| 6.11    | 27        | 2.84%   |
| 5.13    | 26        | 2.73%   |
| 5.11    | 24        | 2.52%   |
| 5.0     | 18        | 1.89%   |
| 6.4     | 16        | 1.68%   |
| 6.10    | 14        | 1.47%   |
| 4.18    | 14        | 1.47%   |
| 6.9     | 13        | 1.37%   |
| 6.17    | 12        | 1.26%   |
| 6.7     | 10        | 1.05%   |
| 6.13    | 10        | 1.05%   |
| 4.9     | 10        | 1.05%   |
| 6.3     | 9         | 0.95%   |
| 6.0     | 9         | 0.95%   |
| 5.18    | 8         | 0.84%   |
| 5.17    | 8         | 0.84%   |
| 6.16    | 7         | 0.74%   |
| 6.15    | 6         | 0.63%   |
| 5.14    | 5         | 0.53%   |
| 5.9     | 4         | 0.42%   |
| 5.6     | 4         | 0.42%   |
| 4.19    | 4         | 0.42%   |
| 5.12    | 3         | 0.32%   |
| 5.7     | 2         | 0.21%   |
| 5.5     | 2         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 842       | 97.91%  |
| i686    | 11        | 1.28%   |
| aarch64 | 7         | 0.81%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 485       | 53.77%  |
| KDE5            | 110       | 12.2%   |
| XFCE            | 69        | 7.65%   |
| Unknown         | 62        | 6.87%   |
| KDE6            | 57        | 6.32%   |
| X-Cinnamon      | 54        | 5.99%   |
| MATE            | 10        | 1.11%   |
| KDE             | 8         | 0.89%   |
| Pantheon        | 7         | 0.78%   |
| KDE4            | 6         | 0.67%   |
| Cinnamon        | 5         | 0.55%   |
| Budgie          | 5         | 0.55%   |
| Unity           | 3         | 0.33%   |
| i3              | 3         | 0.33%   |
| qtile           | 2         | 0.22%   |
| LXQt            | 2         | 0.22%   |
| LXDE            | 2         | 0.22%   |
| Hyprland        | 2         | 0.22%   |
| GNOME Flashback | 2         | 0.22%   |
| GNOME Classic   | 2         | 0.22%   |
| sway:wlroots    | 1         | 0.11%   |
| Sway            | 1         | 0.11%   |
| Enlightenment   | 1         | 0.11%   |
| Endless:GNOME   | 1         | 0.11%   |
| COSMIC          | 1         | 0.11%   |
| awesome         | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 553       | 62.07%  |
| Wayland | 293       | 32.88%  |
| Unknown | 34        | 3.82%   |
| Tty     | 11        | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 431       | 48.37%  |
| GDM3    | 139       | 15.6%   |
| SDDM    | 137       | 15.38%  |
| GDM     | 82        | 9.2%    |
| LightDM | 78        | 8.75%   |
| TDM     | 11        | 1.23%   |
| KDM     | 6         | 0.67%   |
| GREETD  | 3         | 0.34%   |
| LY-DM   | 2         | 0.22%   |
| XDM     | 1         | 0.11%   |
| Ly      | 1         | 0.11%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 710       | 80.96%  |
| Unknown     | 58        | 6.61%   |
| en_GB       | 34        | 3.88%   |
| ar_EG       | 34        | 3.88%   |
| C           | 26        | 2.96%   |
| en_ZA       | 3         | 0.34%   |
| de_DE       | 3         | 0.34%   |
| ru_RU       | 2         | 0.23%   |
| POSIX       | 1         | 0.11%   |
| fr_FR       | 1         | 0.11%   |
| en_US.UFT-8 | 1         | 0.11%   |
| en_CA       | 1         | 0.11%   |
| C.UTF8      | 1         | 0.11%   |
| ar_SA       | 1         | 0.11%   |
| ar_AE       | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 521       | 59.41%  |
| EFI  | 356       | 40.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 604       | 67.41%  |
| Btrfs   | 123       | 13.73%  |
| Tmpfs   | 71        | 7.92%   |
| Overlay | 57        | 6.36%   |
| Unknown | 19        | 2.12%   |
| Xfs     | 13        | 1.45%   |
| Zfs     | 4         | 0.45%   |
| Ext2    | 3         | 0.33%   |
| Ext3    | 2         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 448       | 51.03%  |
| GPT     | 333       | 37.93%  |
| MBR     | 97        | 11.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 766       | 87.14%  |
| Yes       | 113       | 12.86%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 529       | 60.32%  |
| Yes       | 348       | 39.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Hewlett-Packard                      | 264       | 30.73%  |
| Dell                                 | 202       | 23.52%  |
| Lenovo                               | 131       | 15.25%  |
| ASUSTek Computer                     | 77        | 8.96%   |
| Gigabyte Technology                  | 49        | 5.7%    |
| Acer                                 | 26        | 3.03%   |
| Toshiba                              | 18        | 2.1%    |
| MSI                                  | 17        | 1.98%   |
| Apple                                | 8         | 0.93%   |
| Sony                                 | 6         | 0.7%    |
| Samsung Electronics                  | 6         | 0.7%    |
| HUAWEI                               | 6         | 0.7%    |
| Fujitsu                              | 5         | 0.58%   |
| Hampoo                               | 4         | 0.47%   |
| Alienware                            | 4         | 0.47%   |
| Intel                                | 3         | 0.35%   |
| Fujitsu Siemens                      | 3         | 0.35%   |
| Unknown                              | 3         | 0.35%   |
| Raspberry Pi Foundation              | 2         | 0.23%   |
| Pegatron                             | 2         | 0.23%   |
| Panasonic                            | 2         | 0.23%   |
| Packard Bell                         | 2         | 0.23%   |
| Nvidia                               | 2         | 0.23%   |
| I-Life Digital Technologies          | 2         | 0.23%   |
| TECNO                                | 1         | 0.12%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.12%   |
| Sary                                 | 1         | 0.12%   |
| Razer                                | 1         | 0.12%   |
| MiTAC                                | 1         | 0.12%   |
| Micro Computer (HK) Tech Limited     | 1         | 0.12%   |
| IBM                                  | 1         | 0.12%   |
| GPD                                  | 1         | 0.12%   |
| Google                               | 1         | 0.12%   |
| Foxconn                              | 1         | 0.12%   |
| ECS                                  | 1         | 0.12%   |
| Clevo                                | 1         | 0.12%   |
| Cherry                               | 1         | 0.12%   |
| Biostar                              | 1         | 0.12%   |
| ASRock                               | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Gigabyte G41MT-S2PT                      | 8         | 0.93%   |
| Lenovo IdeaPad 520-15IKB 81BF            | 7         | 0.81%   |
| HP Notebook                              | 7         | 0.81%   |
| Unknown                                  | 7         | 0.81%   |
| HP ProDesk 600 G1 TWR                    | 6         | 0.7%    |
| HP Pavilion dv6                          | 6         | 0.7%    |
| HP EliteBook 745 G3                      | 6         | 0.7%    |
| HP Compaq Pro 6305 SFF                   | 6         | 0.7%    |
| Gigabyte H61M-S2P                        | 6         | 0.7%    |
| Dell Latitude E5570                      | 6         | 0.7%    |
| Dell Inspiron 5570                       | 6         | 0.7%    |
| HP ProBook 645 G1                        | 5         | 0.58%   |
| HP ProBook 450 G7                        | 5         | 0.58%   |
| HP Laptop 15-da1xxx                      | 5         | 0.58%   |
| Dell OptiPlex 780                        | 5         | 0.58%   |
| Dell Inspiron 7577                       | 5         | 0.58%   |
| Dell Inspiron 3593                       | 5         | 0.58%   |
| Dell Inspiron 3521                       | 5         | 0.58%   |
| Dell G3 3579                             | 5         | 0.58%   |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 5         | 0.58%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 4         | 0.47%   |
| Lenovo IdeaPad 330-15IKB 81DE            | 4         | 0.47%   |
| Lenovo IdeaPad 330-15AST 81D6            | 4         | 0.47%   |
| HP Z820 Workstation                      | 4         | 0.47%   |
| HP Pavilion 15                           | 4         | 0.47%   |
| HP Compaq 6005 Pro SFF PC                | 4         | 0.47%   |
| Dell Precision M4800                     | 4         | 0.47%   |
| Dell OptiPlex 760                        | 4         | 0.47%   |
| Dell OptiPlex 7020                       | 4         | 0.47%   |
| Dell Inspiron N5110                      | 4         | 0.47%   |
| Dell Inspiron N5010                      | 4         | 0.47%   |
| Dell Inspiron 5520                       | 4         | 0.47%   |
| Dell G5 5587                             | 4         | 0.47%   |
| Dell G15 5511                            | 4         | 0.47%   |
| Dell G15 5510                            | 4         | 0.47%   |
| Toshiba Satellite C660                   | 3         | 0.35%   |
| MSI MS-7C02                              | 3         | 0.35%   |
| Lenovo V14-IIL 82C4                      | 3         | 0.35%   |
| Lenovo Legion Y540-15IRH 81SX            | 3         | 0.35%   |
| Lenovo Legion 5 15IMH05H 81Y6            | 3         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell Inspiron       | 64        | 7.45%   |
| Dell Latitude       | 52        | 6.05%   |
| Lenovo IdeaPad      | 49        | 5.7%    |
| HP EliteBook        | 38        | 4.42%   |
| Dell OptiPlex       | 35        | 4.07%   |
| HP Compaq           | 34        | 3.96%   |
| HP Pavilion         | 32        | 3.73%   |
| HP ProBook          | 31        | 3.61%   |
| Lenovo ThinkPad     | 25        | 2.91%   |
| Dell Precision      | 22        | 2.56%   |
| ASUS VivoBook       | 21        | 2.44%   |
| HP EliteDesk        | 18        | 2.1%    |
| HP Laptop           | 16        | 1.86%   |
| Toshiba Satellite   | 15        | 1.75%   |
| HP ZBook            | 15        | 1.75%   |
| ASUS ASUS           | 15        | 1.75%   |
| Lenovo Legion       | 14        | 1.63%   |
| HP ProDesk          | 12        | 1.4%    |
| Acer Aspire         | 12        | 1.4%    |
| Dell G15            | 11        | 1.28%   |
| Lenovo ThinkCentre  | 9         | 1.05%   |
| Gigabyte G41MT-S2PT | 8         | 0.93%   |
| Dell G3             | 8         | 0.93%   |
| HP Notebook         | 7         | 0.81%   |
| ASUS ROG            | 7         | 0.81%   |
| Unknown             | 7         | 0.81%   |
| HP 250              | 6         | 0.7%    |
| Gigabyte H61M-S2P   | 6         | 0.7%    |
| Dell G5             | 5         | 0.58%   |
| ASUS TUF            | 5         | 0.58%   |
| ASUS PRIME          | 5         | 0.58%   |
| HP Z820             | 4         | 0.47%   |
| HP ENVY             | 4         | 0.47%   |
| Acer Veriton        | 4         | 0.47%   |
| Acer Predator       | 4         | 0.47%   |
| MSI MS-7C02         | 3         | 0.35%   |
| Lenovo Yoga         | 3         | 0.35%   |
| Lenovo V14-IIL      | 3         | 0.35%   |
| Lenovo G510         | 3         | 0.35%   |
| HP Victus           | 3         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 81        | 9.43%   |
| 2018    | 78        | 9.08%   |
| 2012    | 76        | 8.85%   |
| 2017    | 62        | 7.22%   |
| 2014    | 62        | 7.22%   |
| 2021    | 60        | 6.98%   |
| 2019    | 59        | 6.87%   |
| 2011    | 57        | 6.64%   |
| 2020    | 46        | 5.36%   |
| 2016    | 45        | 5.24%   |
| 2015    | 45        | 5.24%   |
| 2010    | 38        | 4.42%   |
| 2009    | 34        | 3.96%   |
| 2008    | 32        | 3.73%   |
| 2022    | 30        | 3.49%   |
| 2023    | 15        | 1.75%   |
| 2007    | 15        | 1.75%   |
| 2024    | 8         | 0.93%   |
| Unknown | 6         | 0.7%    |
| 2006    | 4         | 0.47%   |
| 2005    | 4         | 0.47%   |
| 2025    | 2         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 585       | 68.1%   |
| Desktop        | 232       | 27.01%  |
| Convertible    | 20        | 2.33%   |
| Tablet         | 11        | 1.28%   |
| System on chip | 5         | 0.58%   |
| Mini pc        | 3         | 0.35%   |
| Phone          | 2         | 0.23%   |
| Server         | 1         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 818       | 94.9%   |
| Enabled  | 44        | 5.1%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 857       | 99.77%  |
| Yes  | 2         | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 267       | 30.65%  |
| 16.01-24.0  | 172       | 19.75%  |
| 3.01-4.0    | 154       | 17.68%  |
| 8.01-16.0   | 154       | 17.68%  |
| 32.01-64.0  | 45        | 5.17%   |
| 1.01-2.0    | 27        | 3.1%    |
| 24.01-32.0  | 22        | 2.53%   |
| 2.01-3.0    | 19        | 2.18%   |
| 64.01-256.0 | 8         | 0.92%   |
| 0.51-1.0    | 2         | 0.23%   |
| 0.01-0.5    | 1         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 2.01-3.0    | 292       | 30.83%  |
| 1.01-2.0    | 253       | 26.72%  |
| 4.01-8.0    | 175       | 18.48%  |
| 3.01-4.0    | 147       | 15.52%  |
| 8.01-16.0   | 33        | 3.48%   |
| 0.51-1.0    | 28        | 2.96%   |
| 0.01-0.5    | 10        | 1.06%   |
| 16.01-24.0  | 6         | 0.63%   |
| 32.01-64.0  | 2         | 0.21%   |
| 64.01-256.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 497       | 56.35%  |
| 2       | 312       | 35.37%  |
| 3       | 46        | 5.22%   |
| 4       | 14        | 1.59%   |
| 0       | 6         | 0.68%   |
| 5       | 3         | 0.34%   |
| 9       | 2         | 0.23%   |
| 6       | 1         | 0.11%   |
| Unknown | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 556       | 64.06%  |
| Yes       | 312       | 35.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 753       | 87.66%  |
| No        | 106       | 12.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 683       | 79.14%  |
| No        | 180       | 20.86%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 563       | 64.71%  |
| No        | 307       | 35.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Egypt   | 859       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Cairo                 | 443       | 47.23%  |
| Alexandria            | 122       | 13.01%  |
| Giza                  | 82        | 8.74%   |
| Al Mansurah           | 29        | 3.09%   |
| Tanta                 | 27        | 2.88%   |
| Zagazig               | 12        | 1.28%   |
| Qina                  | 10        | 1.07%   |
| Ismailia              | 9         | 0.96%   |
| Aswan                 | 9         | 0.96%   |
| Assiut                | 9         | 0.96%   |
| Port Said             | 8         | 0.85%   |
| Bani Suwayf           | 8         | 0.85%   |
| Al Ma`adi             | 8         | 0.85%   |
| Kafr ash Shaykh       | 7         | 0.75%   |
| Hurghada              | 7         | 0.75%   |
| Al Qahirah al Jadidah | 7         | 0.75%   |
| Suez                  | 6         | 0.64%   |
| Minya                 | 6         | 0.64%   |
| Damietta              | 6         | 0.64%   |
| Banha                 | 6         | 0.64%   |
| Madinat an Nasr       | 5         | 0.53%   |
| Helwan                | 5         | 0.53%   |
| Talkha                | 4         | 0.43%   |
| Sohag                 | 4         | 0.43%   |
| New Cairo             | 4         | 0.43%   |
| Damanhur              | 4         | 0.43%   |
| Awsim                 | 4         | 0.43%   |
| Al Mahallah al Kubra  | 4         | 0.43%   |
| Al Fayyum             | 4         | 0.43%   |
| Al 'Ashir min Ramadan | 4         | 0.43%   |
| Zefta                 | 3         | 0.32%   |
| Shubra al Khaymah     | 3         | 0.32%   |
| Sharqia               | 3         | 0.32%   |
| Ibshaway              | 3         | 0.32%   |
| Gharbia               | 3         | 0.32%   |
| Tukh                  | 2         | 0.21%   |
| Tala                  | 2         | 0.21%   |
| Rosetta               | 2         | 0.21%   |
| Qalyubia              | 2         | 0.21%   |
| Munuf                 | 2         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 246       | 359    | 20.07%  |
| Seagate                        | 214       | 269    | 17.46%  |
| Samsung Electronics            | 131       | 169    | 10.69%  |
| Toshiba                        | 111       | 143    | 9.05%   |
| Kingston                       | 63        | 85     | 5.14%   |
| SanDisk                        | 44        | 47     | 3.59%   |
| Unknown                        | 42        | 51     | 3.43%   |
| Crucial                        | 41        | 49     | 3.34%   |
| Micron Technology              | 37        | 44     | 3.02%   |
| SK hynix                       | 35        | 43     | 2.85%   |
| Hitachi                        | 35        | 41     | 2.85%   |
| Intel                          | 28        | 28     | 2.28%   |
| HGST                           | 24        | 29     | 1.96%   |
| HS-SSD-C100                    | 18        | 22     | 1.47%   |
| Micron/Crucial Technology      | 14        | 16     | 1.14%   |
| LITEON                         | 11        | 16     | 0.9%    |
| LITEONIT                       | 10        | 13     | 0.82%   |
| HS-SSD-E100                    | 10        | 11     | 0.82%   |
| KIOXIA                         | 9         | 12     | 0.73%   |
| Kingston Technology Company    | 8         | 9      | 0.65%   |
| JMicron Technology             | 7         | 8      | 0.57%   |
| Apple                          | 7         | 10     | 0.57%   |
| TwinMOS                        | 6         | 8      | 0.49%   |
| A-DATA Technology              | 6         | 6      | 0.49%   |
| MAXIO Technology (Hangzhou)    | 5         | 6      | 0.41%   |
| KingSpec                       | 5         | 6      | 0.41%   |
| Shenzhen Longsys Electronics   | 4         | 4      | 0.33%   |
| Fujitsu                        | 4         | 5      | 0.33%   |
| Transcend                      | 3         | 3      | 0.24%   |
| Silicon Motion                 | 3         | 3      | 0.24%   |
| Lexar                          | 3         | 3      | 0.24%   |
| Hewlett-Packard                | 3         | 3      | 0.24%   |
| UMIS                           | 2         | 2      | 0.16%   |
| Solid State Storage Technology | 2         | 2      | 0.16%   |
| Phison Electronics             | 2         | 3      | 0.16%   |
| Phison                         | 2         | 2      | 0.16%   |
| Maxtor                         | 2         | 3      | 0.16%   |
| Hikvision                      | 2         | 2      | 0.16%   |
| China                          | 2         | 2      | 0.16%   |
| Unknown                        | 2         | 2      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 52        | 4.02%   |
| Toshiba MQ04ABF100 1TB                            | 22        | 1.7%    |
| Kingston SA400S37240G 240GB SSD                   | 17        | 1.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 16        | 1.24%   |
| Toshiba MQ01ABD100 1TB                            | 14        | 1.08%   |
| Seagate ST500DM002-1BD142 500GB                   | 14        | 1.08%   |
| Kingston SA400S37480G 480GB SSD                   | 14        | 1.08%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB               | 11        | 0.85%   |
| Kingston SA400S37120G 120GB SSD                   | 11        | 0.85%   |
| Unknown MMC Card  32GB                            | 10        | 0.77%   |
| Seagate ST2000LM007-1R8174 2TB                    | 10        | 0.77%   |
| Intel SSDPEKNU512GZ 512GB                         | 10        | 0.77%   |
| Crucial CT240BX500SSD1 240GB                      | 10        | 0.77%   |
| Unknown MMC Card  64GB                            | 9         | 0.7%    |
| Seagate ST500LT012-1DG142 500GB                   | 9         | 0.7%    |
| Seagate ST3500312CS 500GB                         | 9         | 0.7%    |
| Crucial CT480BX500SSD1 480GB                      | 9         | 0.7%    |
| Toshiba MQ01ABF050 500GB                          | 8         | 0.62%   |
| Toshiba DT01ACA050 500GB                          | 8         | 0.62%   |
| WDC WD10SPZX-24Z10 1TB                            | 7         | 0.54%   |
| Seagate ST3500414CS 500GB                         | 7         | 0.54%   |
| HS-SSD-E100 128G                                  | 7         | 0.54%   |
| HS-SSD-C100 120G                                  | 7         | 0.54%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                  | 6         | 0.46%   |
| WDC WD5000AAKX-001CA0 500GB                       | 6         | 0.46%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 6         | 0.46%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 6         | 0.46%   |
| Seagate ST1000LM049-2GH172 1TB                    | 6         | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB                    | 6         | 0.46%   |
| Samsung SSD 860 EVO 500GB                         | 6         | 0.46%   |
| Samsung NVMe SSD Drive 256GB                      | 6         | 0.46%   |
| WDC WD5000AAKX-75U6AA0 500GB                      | 5         | 0.39%   |
| WDC WD5000AADS-00S9B0 500GB                       | 5         | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 5         | 0.39%   |
| Unknown MMC Card  128GB                           | 5         | 0.39%   |
| Seagate ST750LM022 HN-M750MBB 752GB               | 5         | 0.39%   |
| Seagate ST500LT012-9WS142 500GB                   | 5         | 0.39%   |
| Seagate ST3250318AS 250GB                         | 5         | 0.39%   |
| Seagate ST1000LM048-2E7172 1TB                    | 5         | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 5         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 226       | 334    | 36.16%  |
| Seagate             | 214       | 268    | 34.24%  |
| Toshiba             | 95        | 122    | 15.2%   |
| Hitachi             | 35        | 41     | 5.6%    |
| HGST                | 24        | 29     | 3.84%   |
| Samsung Electronics | 13        | 17     | 2.08%   |
| Unknown             | 4         | 4      | 0.64%   |
| JMicron Technology  | 4         | 4      | 0.64%   |
| Fujitsu             | 4         | 5      | 0.64%   |
| Apple               | 3         | 4      | 0.48%   |
| Maxtor              | 1         | 2      | 0.16%   |
| Hewlett-Packard     | 1         | 1      | 0.16%   |
| ASMT                | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 62        | 69     | 21.09%  |
| Kingston            | 56        | 77     | 19.05%  |
| Crucial             | 37        | 45     | 12.59%  |
| SanDisk             | 18        | 20     | 6.12%   |
| WDC                 | 17        | 19     | 5.78%   |
| Micron Technology   | 13        | 17     | 4.42%   |
| Intel               | 12        | 12     | 4.08%   |
| LITEON              | 11        | 16     | 3.74%   |
| LITEONIT            | 10        | 13     | 3.4%    |
| SK hynix            | 9         | 9      | 3.06%   |
| HS-SSD-C100         | 8         | 10     | 2.72%   |
| TwinMOS             | 6         | 8      | 2.04%   |
| Toshiba             | 6         | 8      | 2.04%   |
| KingSpec            | 5         | 6      | 1.7%    |
| Transcend           | 3         | 3      | 1.02%   |
| Lexar               | 2         | 2      | 0.68%   |
| China               | 2         | 2      | 0.68%   |
| Apple               | 2         | 2      | 0.68%   |
| A-DATA Technology   | 2         | 2      | 0.68%   |
| ZOTAC               | 1         | 1      | 0.34%   |
| Verbatim            | 1         | 1      | 0.34%   |
| Value               | 1         | 1      | 0.34%   |
| Team                | 1         | 1      | 0.34%   |
| Maxtor              | 1         | 1      | 0.34%   |
| KingFast            | 1         | 1      | 0.34%   |
| HS-SSD-E100         | 1         | 1      | 0.34%   |
| Hikvision           | 1         | 1      | 0.34%   |
| HEYGATE             | 1         | 1      | 0.34%   |
| Hewlett-Packard     | 1         | 1      | 0.34%   |
| Dahua               | 1         | 1      | 0.34%   |
| CT250MX5            | 1         | 1      | 0.34%   |
| CARLSTEIN           | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 563       | 832    | 49.78%  |
| SSD     | 270       | 353    | 23.87%  |
| NVMe    | 234       | 303    | 20.69%  |
| MMC     | 35        | 43     | 3.09%   |
| Unknown | 29        | 35     | 2.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 679       | 1192   | 69.93%  |
| NVMe | 234       | 303    | 24.1%   |
| MMC  | 35        | 43     | 3.6%    |
| SAS  | 23        | 28     | 2.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 487       | 774    | 60.8%   |
| 0.51-1.0   | 268       | 351    | 33.46%  |
| 1.01-2.0   | 37        | 44     | 4.62%   |
| 3.01-4.0   | 4         | 6      | 0.5%    |
| 4.01-10.0  | 3         | 8      | 0.37%   |
| 2.01-3.0   | 2         | 2      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 237       | 25.76%  |
| 251-500        | 204       | 22.17%  |
| 501-1000       | 145       | 15.76%  |
| 51-100         | 95        | 10.33%  |
| 1001-2000      | 73        | 7.93%   |
| 21-50          | 64        | 6.96%   |
| 1-20           | 51        | 5.54%   |
| Unknown        | 22        | 2.39%   |
| 2001-3000      | 17        | 1.85%   |
| More than 3000 | 12        | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 312       | 33.19%  |
| 21-50          | 188       | 20%     |
| 101-250        | 141       | 15%     |
| 51-100         | 112       | 11.91%  |
| 251-500        | 83        | 8.83%   |
| 501-1000       | 56        | 5.96%   |
| Unknown        | 22        | 2.34%   |
| 1001-2000      | 15        | 1.6%    |
| 2001-3000      | 7         | 0.74%   |
| More than 3000 | 4         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD5000AAKX-00ERMA0 500GB          | 4         | 6      | 2.99%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 5      | 2.99%   |
| WDC WD5000AVDS-63U7B1 500GB           | 3         | 3      | 2.24%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 2.24%   |
| Seagate ST3500312CS 500GB             | 3         | 6      | 2.24%   |
| WDC WD5000AVVS-63H0B1 500GB           | 2         | 2      | 1.49%   |
| WDC WD5000AADS-00S9B0 500GB           | 2         | 3      | 1.49%   |
| WDC WD1600AABS-00H4A0 160GB           | 2         | 2      | 1.49%   |
| WDC WD10SPZX-60Z10T0 1TB              | 2         | 3      | 1.49%   |
| Toshiba MQ01ABF050 500GB              | 2         | 4      | 1.49%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 2         | 2      | 1.49%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 4      | 1.49%   |
| Seagate ST380815AS 80GB               | 2         | 2      | 1.49%   |
| Seagate ST3500413AS 500GB             | 2         | 3      | 1.49%   |
| Samsung Electronics SSD 870 EVO 500GB | 2         | 2      | 1.49%   |
| WDC WD800JD-60LSA5 80GB               | 1         | 1      | 0.75%   |
| WDC WD800BD-22MRA1 80GB               | 1         | 3      | 0.75%   |
| WDC WD5000LPVX-75V0TT0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000LPVX-60V0TT0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000BPVT-24HXZT3 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 2      | 0.75%   |
| WDC WD5000AAVS-22G9B1 500GB           | 1         | 1      | 0.75%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 2      | 0.75%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000AAKX-08U6AA0 500GB          | 1         | 2      | 0.75%   |
| WDC WD5000AAKX-08ANVA0 500GB          | 1         | 1      | 0.75%   |
| WDC WD5000AAKX-009FA0 500GB           | 1         | 1      | 0.75%   |
| WDC WD5000AAKS-00V6A0 500GB           | 1         | 1      | 0.75%   |
| WDC WD5000AADS-00M2B0 500GB           | 1         | 1      | 0.75%   |
| WDC WD3200BUDT-63DPZY0 320GB          | 1         | 1      | 0.75%   |
| WDC WD3200BEKT-60V5T1 320GB           | 1         | 3      | 0.75%   |
| WDC WD3200AAJS-56M0A0 320GB           | 1         | 1      | 0.75%   |
| WDC WD3200AAJS-56B4A0 320GB           | 1         | 2      | 0.75%   |
| WDC WD3200AAJS-22B4A0 320GB           | 1         | 1      | 0.75%   |
| WDC WD3200AAJS-00L7A0 320GB           | 1         | 1      | 0.75%   |
| WDC WD3200AAJS-00B4A0 320GB           | 1         | 1      | 0.75%   |
| WDC WD3200A 320GB                     | 1         | 1      | 0.75%   |
| WDC WD2500AAJS-00VTA0 250GB           | 1         | 1      | 0.75%   |
| WDC WD20SPZX-75UA7T0 2TB              | 1         | 1      | 0.75%   |
| WDC WD1600AVVS-63L2B0 160GB           | 1         | 1      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 46        | 62     | 35.94%  |
| Seagate                     | 35        | 50     | 27.34%  |
| Hitachi                     | 9         | 9      | 7.03%   |
| Toshiba                     | 7         | 10     | 5.47%   |
| Samsung Electronics         | 6         | 6      | 4.69%   |
| HGST                        | 5         | 9      | 3.91%   |
| SK hynix                    | 4         | 4      | 3.13%   |
| Micron Technology           | 4         | 5      | 3.13%   |
| Intel                       | 3         | 3      | 2.34%   |
| A-DATA Technology           | 2         | 2      | 1.56%   |
| TwinMOS                     | 1         | 1      | 0.78%   |
| LITEONIT                    | 1         | 1      | 0.78%   |
| Kingston Technology Company | 1         | 1      | 0.78%   |
| Kingston                    | 1         | 2      | 0.78%   |
| Hewlett-Packard             | 1         | 1      | 0.78%   |
| Fujitsu                     | 1         | 2      | 0.78%   |
| Apple                       | 1         | 1      | 0.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 46        | 62     | 43.4%   |
| Seagate             | 35        | 50     | 33.02%  |
| Hitachi             | 9         | 9      | 8.49%   |
| Toshiba             | 6         | 9      | 5.66%   |
| HGST                | 5         | 9      | 4.72%   |
| Samsung Electronics | 2         | 2      | 1.89%   |
| Hewlett-Packard     | 1         | 1      | 0.94%   |
| Fujitsu             | 1         | 2      | 0.94%   |
| Apple               | 1         | 1      | 0.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 101       | 145    | 82.11%  |
| SSD  | 17        | 19     | 13.82%  |
| NVMe | 5         | 5      | 4.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD3200AAJS-00L7A0 320GB                      | 1         | 2      | 20%     |
| Toshiba MK5061GSYN 500GB                         | 1         | 1      | 20%     |
| Toshiba MK3265GSXV 320GB                         | 1         | 1      | 20%     |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 20%     |
| Samsung Electronics MZ7PC128HAFU-000H1 128GB SSD | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 2         | 2      | 40%     |
| Samsung Electronics | 2         | 2      | 40%     |
| WDC                 | 1         | 2      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 544       | 954    | 58.31%  |
| Works    | 264       | 437    | 28.3%   |
| Malfunc  | 120       | 169    | 12.86%  |
| Failed   | 5         | 6      | 0.54%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 641       | 63.09%  |
| AMD                            | 117       | 11.52%  |
| Samsung Electronics            | 67        | 6.59%   |
| SanDisk                        | 32        | 3.15%   |
| SK hynix                       | 26        | 2.56%   |
| Micron Technology              | 24        | 2.36%   |
| Micron/Crucial Technology      | 18        | 1.77%   |
| Kingston Technology Company    | 16        | 1.57%   |
| Toshiba America Info Systems   | 13        | 1.28%   |
| KIOXIA                         | 8         | 0.79%   |
| Shenzhen Longsys Electronics   | 6         | 0.59%   |
| Phison Electronics             | 5         | 0.49%   |
| MAXIO Technology (Hangzhou)    | 5         | 0.49%   |
| Broadcom / LSI                 | 5         | 0.49%   |
| ADATA Technology               | 5         | 0.49%   |
| Union Memory (Shenzhen)        | 4         | 0.39%   |
| Nvidia                         | 4         | 0.39%   |
| Solid State Storage Technology | 3         | 0.3%    |
| Silicon Motion                 | 3         | 0.3%    |
| Yangtze Memory Technologies    | 2         | 0.2%    |
| Marvell Technology Group       | 2         | 0.2%    |
| LSI Logic / Symbios Logic      | 2         | 0.2%    |
| Apple                          | 2         | 0.2%    |
| VIA Technologies               | 1         | 0.1%    |
| Seagate Technology             | 1         | 0.1%    |
| Lite-On Technology             | 1         | 0.1%    |
| JMicron Technology             | 1         | 0.1%    |
| INNOGRIT                       | 1         | 0.1%    |
| Biwin Storage Technology       | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 84        | 7.32%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 66        | 5.75%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 52        | 4.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 43        | 3.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 35        | 3.05%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 35        | 3.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 33        | 2.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 30        | 2.62%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 29        | 2.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 23        | 2.01%   |
| Intel SATA Controller [RAID mode]                                                       | 23        | 2.01%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 21        | 1.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 19        | 1.66%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 18        | 1.57%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 15        | 1.31%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 15        | 1.31%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 15        | 1.31%   |
| Intel SSD 670p Series [Keystone Harbor]                                                 | 14        | 1.22%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 14        | 1.22%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 13        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 13        | 1.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 12        | 1.05%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 12        | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 11        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 11        | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 11        | 0.96%   |
| Intel RST Volume Management Device Controller                                           | 10        | 0.87%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 10        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 10        | 0.87%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 9         | 0.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 9         | 0.78%   |
| Micron 2210 NVMe SSD [Cobain]                                                           | 9         | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 9         | 0.78%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                           | 8         | 0.7%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 8         | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 0.7%    |
| AMD 400 Series Chipset SATA Controller                                                  | 8         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                                   | 7         | 0.61%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                        | 7         | 0.61%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 7         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 590       | 56.35%  |
| NVMe | 236       | 22.54%  |
| RAID | 110       | 10.51%  |
| IDE  | 101       | 9.65%   |
| SAS  | 8         | 0.76%   |
| SCSI | 2         | 0.19%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 700       | 81.49%  |
| AMD      | 152       | 17.69%  |
| ARM      | 6         | 0.7%    |
| Qualcomm | 1         | 0.12%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz       | 18        | 2.09%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 1.74%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 11        | 1.28%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 11        | 1.28%   |
| Intel Core i5-4570 CPU @ 3.20GHz        | 10        | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 9         | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 9         | 1.05%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 9         | 1.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 9         | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 9         | 1.05%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 9         | 1.05%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 8         | 0.93%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 8         | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 8         | 0.93%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 7         | 0.81%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 7         | 0.81%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 7         | 0.81%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 7         | 0.81%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 7         | 0.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 7         | 0.81%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 6         | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz       | 6         | 0.7%    |
| Intel Core i5-2400 CPU @ 3.10GHz        | 6         | 0.7%    |
| Intel Core i3-3217U CPU @ 1.80GHz       | 6         | 0.7%    |
| Intel 12th Gen Core i7-12700H           | 6         | 0.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 0.7%    |
| AMD Ryzen 7 5700U with Radeon Graphics  | 6         | 0.7%    |
| AMD Ryzen 7 4800H with Radeon Graphics  | 6         | 0.7%    |
| AMD Ryzen 5 5600H with Radeon Graphics  | 6         | 0.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz       | 5         | 0.58%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz      | 5         | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 5         | 0.58%   |
| Intel Core i7-4510U CPU @ 2.00GHz       | 5         | 0.58%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 5         | 0.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 5         | 0.58%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 5         | 0.58%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 5         | 0.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 5         | 0.58%   |
| Intel Core i3-2120 CPU @ 3.30GHz        | 5         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 209       | 24.3%   |
| Intel Core i5           | 204       | 23.72%  |
| Other                   | 78        | 9.07%   |
| Intel Core i3           | 67        | 7.79%   |
| Intel Core 2 Duo        | 48        | 5.58%   |
| AMD Ryzen 7             | 32        | 3.72%   |
| Intel Xeon              | 22        | 2.56%   |
| AMD Ryzen 5             | 21        | 2.44%   |
| Intel Celeron           | 17        | 1.98%   |
| Intel Pentium           | 16        | 1.86%   |
| Intel Atom              | 13        | 1.51%   |
| AMD A6                  | 11        | 1.28%   |
| AMD A4                  | 11        | 1.28%   |
| AMD Ryzen 9             | 8         | 0.93%   |
| AMD PRO A10             | 8         | 0.93%   |
| AMD A8                  | 7         | 0.81%   |
| Intel Core 2            | 6         | 0.7%    |
| AMD E2                  | 6         | 0.7%    |
| Intel Core 2 Quad       | 5         | 0.58%   |
| AMD Ryzen 7 PRO         | 5         | 0.58%   |
| AMD Ryzen 5 PRO         | 5         | 0.58%   |
| AMD A10                 | 5         | 0.58%   |
| Intel Pentium Dual-Core | 4         | 0.47%   |
| Intel Pentium 4         | 4         | 0.47%   |
| Intel Core              | 4         | 0.47%   |
| AMD E1                  | 4         | 0.47%   |
| Intel Pentium D         | 3         | 0.35%   |
| AMD PRO A8              | 3         | 0.35%   |
| AMD Phenom II X4        | 3         | 0.35%   |
| AMD Athlon II X2        | 3         | 0.35%   |
| Intel Pentium Silver    | 2         | 0.23%   |
| Intel Celeron D         | 2         | 0.23%   |
| AMD Ryzen 3             | 2         | 0.23%   |
| AMD Phenom              | 2         | 0.23%   |
| AMD FX                  | 2         | 0.23%   |
| AMD Athlon II Dual-Core | 2         | 0.23%   |
| AMD Athlon 64 X2        | 2         | 0.23%   |
| Intel Xeon Silver       | 1         | 0.12%   |
| Intel Pentium Dual      | 1         | 0.12%   |
| Intel Genuine           | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 379       | 43.97%  |
| 4      | 273       | 31.67%  |
| 6      | 84        | 9.74%   |
| 8      | 54        | 6.26%   |
| 1      | 21        | 2.44%   |
| 14     | 13        | 1.51%   |
| 12     | 12        | 1.39%   |
| 10     | 11        | 1.28%   |
| 16     | 6         | 0.7%    |
| 24     | 4         | 0.46%   |
| 3      | 3         | 0.35%   |
| 20     | 2         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 845       | 98.26%  |
| 2      | 15        | 1.74%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 608       | 70.37%  |
| 1      | 256       | 29.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 848       | 98.49%  |
| Unknown        | 10        | 1.16%   |
| 32-bit         | 3         | 0.35%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 486       | 54.67%  |
| 0x206a7    | 30        | 3.37%   |
| 0x306c3    | 29        | 3.26%   |
| 0x1067a    | 26        | 2.92%   |
| 0x306a9    | 24        | 2.7%    |
| 0x906ea    | 19        | 2.14%   |
| 0x40651    | 19        | 2.14%   |
| 0x806ea    | 17        | 1.91%   |
| 0x806e9    | 16        | 1.8%    |
| 0x306d4    | 15        | 1.69%   |
| 0x906e9    | 11        | 1.24%   |
| 0x806ec    | 11        | 1.24%   |
| 0x406e3    | 11        | 1.24%   |
| 0x6fd      | 8         | 0.9%    |
| 0x06001119 | 8         | 0.9%    |
| 0x20655    | 7         | 0.79%   |
| 0xa0652    | 6         | 0.67%   |
| 0x806c1    | 6         | 0.67%   |
| 0x30678    | 6         | 0.67%   |
| 0x706e5    | 5         | 0.56%   |
| 0x6fb      | 5         | 0.56%   |
| 0x506e3    | 5         | 0.56%   |
| 0x20652    | 5         | 0.56%   |
| 0x0600111f | 5         | 0.56%   |
| 0xf65      | 4         | 0.45%   |
| 0x806eb    | 4         | 0.45%   |
| 0x406c4    | 4         | 0.45%   |
| 0x406c3    | 4         | 0.45%   |
| 0x10676    | 4         | 0.45%   |
| 0x06006705 | 4         | 0.45%   |
| 0x06006704 | 4         | 0.45%   |
| 0xa0671    | 3         | 0.34%   |
| 0x206c2    | 3         | 0.34%   |
| 0x106e5    | 3         | 0.34%   |
| 0x106a5    | 3         | 0.34%   |
| 0x0a50000c | 3         | 0.34%   |
| 0x0800820d | 3         | 0.34%   |
| 0x0600611a | 3         | 0.34%   |
| 0x010000c8 | 3         | 0.34%   |
| 0x010000b6 | 3         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| KabyLake           | 149       | 17.31%  |
| Haswell            | 99        | 11.5%   |
| SandyBridge        | 63        | 7.32%   |
| IvyBridge          | 57        | 6.62%   |
| Skylake            | 49        | 5.69%   |
| Unknown            | 43        | 4.99%   |
| Penryn             | 42        | 4.88%   |
| Westmere           | 30        | 3.48%   |
| Broadwell          | 26        | 3.02%   |
| Icelake            | 25        | 2.9%    |
| Core               | 24        | 2.79%   |
| CometLake          | 24        | 2.79%   |
| Alderlake Hybrid   | 24        | 2.79%   |
| Zen 3              | 22        | 2.56%   |
| TigerLake          | 22        | 2.56%   |
| Silvermont         | 22        | 2.56%   |
| Piledriver         | 21        | 2.44%   |
| Excavator          | 19        | 2.21%   |
| Zen 2              | 15        | 1.74%   |
| K10                | 13        | 1.51%   |
| Zen+               | 12        | 1.39%   |
| NetBurst           | 12        | 1.39%   |
| Zen                | 7         | 0.81%   |
| Steamroller        | 7         | 0.81%   |
| Nehalem            | 7         | 0.81%   |
| Goldmont plus      | 5         | 0.58%   |
| Bobcat             | 5         | 0.58%   |
| K8 Hammer          | 4         | 0.46%   |
| Puma               | 3         | 0.35%   |
| Jaguar             | 3         | 0.35%   |
| Goldmont           | 2         | 0.23%   |
| P6                 | 1         | 0.12%   |
| Lunarlake Hybrid   | 1         | 0.12%   |
| Bulldozer          | 1         | 0.12%   |
| Bonnell            | 1         | 0.12%   |
| ArrowLake-H Hybrid | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 586       | 50.96%  |
| Nvidia           | 296       | 25.74%  |
| AMD              | 267       | 23.22%  |
| VIA Technologies | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 36        | 3.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 33        | 2.83%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 31        | 2.65%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 31        | 2.65%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 29        | 2.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 27        | 2.31%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 24        | 2.05%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 23        | 1.97%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 22        | 1.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 22        | 1.88%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 19        | 1.63%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 1.54%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 1.37%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 1.37%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 16        | 1.37%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 16        | 1.37%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 1.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 14        | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 13        | 1.11%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 1.11%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 1.03%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 12        | 1.03%   |
| Nvidia GM108M [GeForce MX130]                                                            | 11        | 0.94%   |
| Nvidia GT218 [GeForce 210]                                                               | 10        | 0.86%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.86%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 10        | 0.86%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 10        | 0.86%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.86%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 10        | 0.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 10        | 0.86%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 0.77%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 8         | 0.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 0.68%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 0.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 318       | 36.47%  |
| Intel + Nvidia         | 178       | 20.41%  |
| 1 x AMD                | 148       | 16.97%  |
| 1 x Nvidia             | 91        | 10.44%  |
| Intel + AMD            | 85        | 9.75%   |
| AMD + Nvidia           | 25        | 2.87%   |
| Other                  | 7         | 0.8%    |
| 2 x Intel              | 7         | 0.8%    |
| 2 x AMD                | 7         | 0.8%    |
| 2 x Nvidia             | 2         | 0.23%   |
| 3 x AMD                | 1         | 0.11%   |
| 1 x VIA                | 1         | 0.11%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.11%   |
| AMD + 2 x Nvidia       | 1         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 701       | 79.75%  |
| Proprietary | 134       | 15.24%  |
| Unknown     | 44        | 5.01%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 573       | 64.75%  |
| 1.01-2.0   | 86        | 9.72%   |
| 0.01-0.5   | 70        | 7.91%   |
| 3.01-4.0   | 61        | 6.89%   |
| 0.51-1.0   | 59        | 6.67%   |
| 7.01-8.0   | 15        | 1.69%   |
| 5.01-6.0   | 12        | 1.36%   |
| 8.01-16.0  | 8         | 0.9%    |
| 2.01-3.0   | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 116       | 13.91%  |
| AU Optronics            | 116       | 13.91%  |
| Samsung Electronics     | 111       | 13.31%  |
| BOE                     | 110       | 13.19%  |
| Chimei Innolux          | 103       | 12.35%  |
| Dell                    | 52        | 6.24%   |
| Hewlett-Packard         | 33        | 3.96%   |
| Chi Mei Optoelectronics | 22        | 2.64%   |
| Lenovo                  | 19        | 2.28%   |
| Goldstar                | 16        | 1.92%   |
| Sharp                   | 15        | 1.8%    |
| PANDA                   | 12        | 1.44%   |
| InfoVision              | 12        | 1.44%   |
| Apple                   | 7         | 0.84%   |
| Unknown                 | 6         | 0.72%   |
| NEC Computers           | 6         | 0.72%   |
| Fujitsu Siemens         | 6         | 0.72%   |
| BenQ                    | 6         | 0.72%   |
| ASUSTek Computer        | 6         | 0.72%   |
| Acer                    | 6         | 0.72%   |
| Philips                 | 5         | 0.6%    |
| AOC                     | 5         | 0.6%    |
| ViewSonic               | 4         | 0.48%   |
| HKC                     | 3         | 0.36%   |
| Panasonic               | 2         | 0.24%   |
| MStar                   | 2         | 0.24%   |
| LG Philips              | 2         | 0.24%   |
| InnoLux Display         | 2         | 0.24%   |
| Eizo                    | 2         | 0.24%   |
| CSO                     | 2         | 0.24%   |
| Unknown                 | 2         | 0.24%   |
| Toshiba                 | 1         | 0.12%   |
| TMX                     | 1         | 0.12%   |
| Sun                     | 1         | 0.12%   |
| Sony                    | 1         | 0.12%   |
| RGT                     | 1         | 0.12%   |
| QCM                     | 1         | 0.12%   |
| Planar                  | 1         | 0.12%   |
| NCS                     | 1         | 0.12%   |
| MSI                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 10        | 1.18%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch          | 8         | 0.95%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 8         | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch      | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 6         | 0.71%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 5         | 0.59%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch           | 5         | 0.59%   |
| Dell E170S DELA04A 1280x1024 340x270mm 17.1-inch                      | 5         | 0.59%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                 | 5         | 0.59%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 5         | 0.59%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 5         | 0.59%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.59%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 5         | 0.59%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 4         | 0.47%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 4         | 0.47%   |
| Lenovo LEN T2454pA LEN60C9 1920x1080 518x324mm 24.1-inch              | 4         | 0.47%   |
| Lenovo LCD Monitor LEN40A0 1366x768 309x173mm 13.9-inch               | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch      | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch       | 4         | 0.47%   |
| BOE LCD Monitor BOE07B0 1920x1080 344x194mm 15.5-inch                 | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch         | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 4         | 0.47%   |
| Samsung Electronics SyncMaster SAM0350 1440x900 428x255mm 19.6-inch   | 3         | 0.36%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch     | 3         | 0.36%   |
| Samsung Electronics S19B150 SAM08A2 1366x768 410x230mm 18.5-inch      | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch  | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch  | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch  | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch  | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SDC419D 2880x1800 302x189mm 14.0-inch | 3         | 0.36%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.36%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 3         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 342       | 41.76%  |
| 1366x768 (WXGA)    | 266       | 32.48%  |
| 1280x1024 (SXGA)   | 34        | 4.15%   |
| 1600x900 (HD+)     | 25        | 3.05%   |
| 1920x1200 (WUXGA)  | 23        | 2.81%   |
| 1440x900 (WXGA+)   | 23        | 2.81%   |
| 1680x1050 (WSXGA+) | 16        | 1.95%   |
| 2560x1440 (QHD)    | 15        | 1.83%   |
| 1280x800 (WXGA)    | 15        | 1.83%   |
| 3840x2160 (4K)     | 14        | 1.71%   |
| 2880x1800          | 9         | 1.1%    |
| 2560x1600          | 5         | 0.61%   |
| 2288x1287          | 4         | 0.49%   |
| 3840x2400          | 3         | 0.37%   |
| 3440x1440          | 2         | 0.24%   |
| 2880x1620          | 2         | 0.24%   |
| 2736x1824          | 2         | 0.24%   |
| 1920x540           | 2         | 0.24%   |
| 1920x1280          | 2         | 0.24%   |
| 1600x1200          | 2         | 0.24%   |
| Unknown            | 2         | 0.24%   |
| 5760x1080          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 3000x2120          | 1         | 0.12%   |
| 2304x1440          | 1         | 0.12%   |
| 2160x1440          | 1         | 0.12%   |
| 1400x1050          | 1         | 0.12%   |
| 1360x768           | 1         | 0.12%   |
| 1280x960           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |
| 1024x768 (XGA)     | 1         | 0.12%   |
| 1024x600           | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 386       | 46.34%  |
| 14      | 84        | 10.08%  |
| 13      | 52        | 6.24%   |
| 17      | 37        | 4.44%   |
| 24      | 31        | 3.72%   |
| 23      | 29        | 3.48%   |
| 19      | 26        | 3.12%   |
| 18      | 25        | 3%      |
| 12      | 23        | 2.76%   |
| 21      | 21        | 2.52%   |
| Unknown | 19        | 2.28%   |
| 27      | 17        | 2.04%   |
| 16      | 16        | 1.92%   |
| 22      | 15        | 1.8%    |
| 20      | 11        | 1.32%   |
| 11      | 9         | 1.08%   |
| 31      | 7         | 0.84%   |
| 142     | 4         | 0.48%   |
| 32      | 3         | 0.36%   |
| 10      | 3         | 0.36%   |
| 54      | 2         | 0.24%   |
| 40      | 2         | 0.24%   |
| 37      | 2         | 0.24%   |
| 34      | 2         | 0.24%   |
| 25      | 2         | 0.24%   |
| 67      | 1         | 0.12%   |
| 58      | 1         | 0.12%   |
| 46      | 1         | 0.12%   |
| 42      | 1         | 0.12%   |
| 29      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 531       | 64.21%  |
| 401-500        | 85        | 10.28%  |
| 501-600        | 74        | 8.95%   |
| 201-300        | 55        | 6.65%   |
| 351-400        | 34        | 4.11%   |
| Unknown        | 19        | 2.3%    |
| 601-700        | 10        | 1.21%   |
| 701-800        | 6         | 0.73%   |
| More than 2000 | 4         | 0.48%   |
| 801-900        | 4         | 0.48%   |
| 1001-1500      | 4         | 0.48%   |
| 901-1000       | 1         | 0.12%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 636       | 79.7%   |
| 16/10   | 94        | 11.78%  |
| 5/4     | 31        | 3.88%   |
| Unknown | 17        | 2.13%   |
| 4/3     | 9         | 1.13%   |
| 3/2     | 4         | 0.5%    |
| 1.00    | 4         | 0.5%    |
| 21/9    | 2         | 0.25%   |
| 0.45    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 383       | 46.03%  |
| 81-90          | 117       | 14.06%  |
| 201-250        | 79        | 9.5%    |
| 151-200        | 47        | 5.65%   |
| 141-150        | 39        | 4.69%   |
| 61-70          | 20        | 2.4%    |
| 71-80          | 19        | 2.28%   |
| Unknown        | 19        | 2.28%   |
| 301-350        | 17        | 2.04%   |
| 111-120        | 16        | 1.92%   |
| 251-300        | 14        | 1.68%   |
| 351-500        | 13        | 1.56%   |
| 121-130        | 12        | 1.44%   |
| 51-60          | 9         | 1.08%   |
| More than 1000 | 8         | 0.96%   |
| 131-140        | 6         | 0.72%   |
| 501-1000       | 6         | 0.72%   |
| 91-100         | 5         | 0.6%    |
| 41-50          | 3         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 286       | 34.84%  |
| 101-120       | 260       | 31.67%  |
| 51-100        | 200       | 24.36%  |
| 161-240       | 29        | 3.53%   |
| Unknown       | 19        | 2.31%   |
| More than 240 | 17        | 2.07%   |
| 1-50          | 10        | 1.22%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 751       | 85.15%  |
| 2     | 71        | 8.05%   |
| 0     | 56        | 6.35%   |
| 3     | 4         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 479       | 35.53%  |
| Intel                             | 416       | 30.86%  |
| Qualcomm Atheros                  | 136       | 10.09%  |
| Broadcom                          | 108       | 8.01%   |
| Ralink Technology                 | 39        | 2.89%   |
| MediaTek                          | 31        | 2.3%    |
| Broadcom Limited                  | 24        | 1.78%   |
| Shenzhen Goodix Technology        | 23        | 1.71%   |
| Ralink                            | 15        | 1.11%   |
| TP-Link                           | 13        | 0.96%   |
| Samsung Electronics               | 8         | 0.59%   |
| Qualcomm Atheros Communications   | 6         | 0.45%   |
| Huawei Technologies               | 6         | 0.45%   |
| Xiaomi                            | 4         | 0.3%    |
| Nvidia                            | 4         | 0.3%    |
| Marvell Technology Group          | 4         | 0.3%    |
| Qualcomm                          | 3         | 0.22%   |
| Edimax Technology                 | 3         | 0.22%   |
| ASIX Electronics                  | 3         | 0.22%   |
| Sierra Wireless                   | 2         | 0.15%   |
| JMicron Technology                | 2         | 0.15%   |
| Ericsson Business Mobile Networks | 2         | 0.15%   |
| Dell                              | 2         | 0.15%   |
| D-Link                            | 2         | 0.15%   |
| ZyDAS                             | 1         | 0.07%   |
| vivo                              | 1         | 0.07%   |
| VIA Technologies                  | 1         | 0.07%   |
| U-Blox                            | 1         | 0.07%   |
| Sundance Technology Inc / IC Plus | 1         | 0.07%   |
| OPPO Electronics                  | 1         | 0.07%   |
| Motorola                          | 1         | 0.07%   |
| Mercucys                          | 1         | 0.07%   |
| Linux Foundation                  | 1         | 0.07%   |
| Lenovo                            | 1         | 0.07%   |
| Hewlett-Packard                   | 1         | 0.07%   |
| Belkin Components                 | 1         | 0.07%   |
| 3Com                              | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 290       | 18.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 119       | 7.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 39        | 2.51%   |
| Intel Ethernet Connection I217-LM                                      | 37        | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 36        | 2.32%   |
| Intel Wireless 8265 / 8275                                             | 26        | 1.67%   |
| Intel Wireless 8260                                                    | 26        | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                          | 26        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 24        | 1.54%   |
| Shenzhen Goodix Fingerprint Reader                                     | 23        | 1.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 20        | 1.29%   |
| Intel Wireless 7265                                                    | 20        | 1.29%   |
| Ralink RT5370 Wireless Adapter                                         | 19        | 1.22%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 19        | 1.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 18        | 1.16%   |
| Intel Wireless 7260                                                    | 18        | 1.16%   |
| Ralink MT7601U Wireless Adapter                                        | 17        | 1.09%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 16        | 1.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 16        | 1.03%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 16        | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 16        | 1.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 15        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 15        | 0.96%   |
| Intel Wi-Fi 6 AX200                                                    | 15        | 0.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 15        | 0.96%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 15        | 0.96%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 14        | 0.9%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 14        | 0.9%    |
| Intel Wi-Fi 6 AX201                                                    | 14        | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 0.84%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                                  | 12        | 0.77%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 11        | 0.71%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 11        | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 0.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10        | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 10        | 0.64%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 9         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 9         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 298       | 41.16%  |
| Realtek Semiconductor           | 129       | 17.82%  |
| Qualcomm Atheros                | 106       | 14.64%  |
| Broadcom                        | 67        | 9.25%   |
| Ralink Technology               | 39        | 5.39%   |
| MediaTek                        | 29        | 4.01%   |
| Ralink                          | 15        | 2.07%   |
| TP-Link                         | 12        | 1.66%   |
| Broadcom Limited                | 10        | 1.38%   |
| Qualcomm Atheros Communications | 6         | 0.83%   |
| Edimax Technology               | 3         | 0.41%   |
| Sierra Wireless                 | 2         | 0.28%   |
| Dell                            | 2         | 0.28%   |
| D-Link                          | 2         | 0.28%   |
| ZyDAS                           | 1         | 0.14%   |
| Qualcomm                        | 1         | 0.14%   |
| Mercucys                        | 1         | 0.14%   |
| Belkin Components               | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 39        | 5.36%   |
| Intel Wireless 8265 / 8275                                           | 26        | 3.57%   |
| Intel Wireless 8260                                                  | 26        | 3.57%   |
| Broadcom BCM43142 802.11b/g/n                                        | 26        | 3.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 24        | 3.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 20        | 2.75%   |
| Intel Wireless 7265                                                  | 20        | 2.75%   |
| Ralink RT5370 Wireless Adapter                                       | 19        | 2.61%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 19        | 2.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 18        | 2.47%   |
| Intel Wireless 7260                                                  | 18        | 2.47%   |
| Ralink MT7601U Wireless Adapter                                      | 17        | 2.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 16        | 2.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 16        | 2.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 16        | 2.2%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 15        | 2.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 15        | 2.06%   |
| Intel Wi-Fi 6 AX200                                                  | 15        | 2.06%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 14        | 1.92%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 14        | 1.92%   |
| Intel Wi-Fi 6 AX201                                                  | 14        | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 13        | 1.79%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 11        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 10        | 1.37%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                      | 10        | 1.37%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                            | 9         | 1.24%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 9         | 1.24%   |
| Intel Wireless 3160                                                  | 9         | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                      | 8         | 1.1%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 8         | 1.1%    |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310] | 7         | 0.96%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 7         | 0.96%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                        | 7         | 0.96%   |
| Intel Centrino Advanced-N 6235                                       | 7         | 0.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 7         | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 6         | 0.82%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter             | 6         | 0.82%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]              | 6         | 0.82%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 5         | 0.69%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                      | 5         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 431       | 55.47%  |
| Intel                             | 209       | 26.9%   |
| Broadcom                          | 46        | 5.92%   |
| Qualcomm Atheros                  | 38        | 4.89%   |
| Broadcom Limited                  | 14        | 1.8%    |
| Samsung Electronics               | 8         | 1.03%   |
| Xiaomi                            | 4         | 0.51%   |
| Nvidia                            | 4         | 0.51%   |
| Marvell Technology Group          | 4         | 0.51%   |
| Huawei Technologies               | 3         | 0.39%   |
| ASIX Electronics                  | 3         | 0.39%   |
| Qualcomm                          | 2         | 0.26%   |
| MediaTek                          | 2         | 0.26%   |
| JMicron Technology                | 2         | 0.26%   |
| vivo                              | 1         | 0.13%   |
| VIA Technologies                  | 1         | 0.13%   |
| TP-Link                           | 1         | 0.13%   |
| Sundance Technology Inc / IC Plus | 1         | 0.13%   |
| OPPO Electronics                  | 1         | 0.13%   |
| Lenovo                            | 1         | 0.13%   |
| 3Com                              | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 290       | 36.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 119       | 14.97%  |
| Intel Ethernet Connection I217-LM                                      | 37        | 4.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 36        | 4.53%   |
| Broadcom NetXtreme BCM5762 Gigabit Ethernet PCIe                       | 16        | 2.01%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 15        | 1.89%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 13        | 1.64%   |
| Intel Ethernet Connection I219-LM                                      | 12        | 1.51%   |
| Intel Ethernet Connection (2) I219-LM                                  | 12        | 1.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 11        | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                      | 10        | 1.26%   |
| Intel 82577LM Gigabit Network Connection                               | 9         | 1.13%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe               | 9         | 1.13%   |
| Intel Ethernet Connection (7) I219-LM                                  | 8         | 1.01%   |
| Intel Ethernet Connection (16) I219-LM                                 | 7         | 0.88%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 0.88%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 6         | 0.75%   |
| Intel Ethernet Connection I218-LM                                      | 6         | 0.75%   |
| Intel Ethernet Connection (4) I219-LM                                  | 6         | 0.75%   |
| Intel Ethernet Connection (3) I218-LM                                  | 6         | 0.75%   |
| Intel 82574L Gigabit Network Connection                                | 6         | 0.75%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.63%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.63%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 4         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.5%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                          | 4         | 0.5%    |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.5%    |
| Intel Ethernet Connection (5) I219-LM                                  | 4         | 0.5%    |
| Intel 82566DM-2 Gigabit Network Connection                             | 4         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 3         | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 3         | 0.38%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.38%   |
| Intel 82566DM Gigabit Network Connection                               | 3         | 0.38%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 0.38%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 3         | 0.38%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.25%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 2         | 0.25%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.25%   |
| Qualcomm Nokia X30 5G                                                  | 2         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 752       | 51.33%  |
| WiFi     | 682       | 46.55%  |
| Modem    | 31        | 2.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 568       | 65.59%  |
| Ethernet | 298       | 34.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 528       | 61.47%  |
| 1     | 309       | 35.97%  |
| 0     | 17        | 1.98%   |
| 3     | 5         | 0.58%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 849       | 98.61%  |
| Yes  | 12        | 1.39%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 253       | 44.62%  |
| Realtek Semiconductor           | 69        | 12.17%  |
| Qualcomm Atheros Communications | 63        | 11.11%  |
| Broadcom                        | 40        | 7.05%   |
| IMC Networks                    | 28        | 4.94%   |
| Cambridge Silicon Radio         | 26        | 4.59%   |
| Foxconn / Hon Hai               | 17        | 3%      |
| Toshiba                         | 12        | 2.12%   |
| Lite-On Technology              | 12        | 2.12%   |
| Hewlett-Packard                 | 12        | 2.12%   |
| Ralink                          | 9         | 1.59%   |
| Dell                            | 7         | 1.23%   |
| Apple                           | 5         | 0.88%   |
| TP-Link                         | 3         | 0.53%   |
| MediaTek                        | 3         | 0.53%   |
| Foxconn International           | 3         | 0.53%   |
| Taiyo Yuden                     | 1         | 0.18%   |
| Realtek                         | 1         | 0.18%   |
| Ralink Technology               | 1         | 0.18%   |
| Fujitsu                         | 1         | 0.18%   |
| Edimax Technology               | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 102       | 17.99%  |
| Intel AX201 Bluetooth                               | 55        | 9.7%    |
| Realtek Bluetooth Radio                             | 43        | 7.58%   |
| Qualcomm Atheros  Bluetooth Device                  | 43        | 7.58%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 39        | 6.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 4.59%   |
| IMC Networks Wireless_Device                        | 19        | 3.35%   |
| Intel Bluetooth Device                              | 16        | 2.82%   |
| Intel AX200 Bluetooth                               | 14        | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                      | 12        | 2.12%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 12        | 2.12%   |
| Ralink RT3290 Bluetooth                             | 9         | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 1.59%   |
| Broadcom HP Portable Bumble Bee                     | 8         | 1.41%   |
| Realtek RTL8821A Bluetooth                          | 7         | 1.23%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 1.23%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.88%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 5         | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                    | 5         | 0.88%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 5         | 0.88%   |
| IMC Networks Bluetooth Radio                        | 5         | 0.88%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.88%   |
| Toshiba RT Bluetooth Radio                          | 4         | 0.71%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 0.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 0.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.71%   |
| Intel AX210 Bluetooth                               | 4         | 0.71%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.71%   |
| Dell Wireless 365 Bluetooth                         | 4         | 0.71%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.71%   |
| Apple Bluetooth Host Controller                     | 4         | 0.71%   |
| TP-Link TP-T@- UB500 Adapter                        | 3         | 0.53%   |
| Lite-On Bluetooth Device                            | 3         | 0.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.53%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.53%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.53%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.53%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Intel                  | 681       | 61.46%  |
| AMD                    | 198       | 17.87%  |
| Nvidia                 | 195       | 17.6%   |
| Generalplus Technology | 6         | 0.54%   |
| JMTek                  | 4         | 0.36%   |
| C-Media Electronics    | 4         | 0.36%   |
| ASUSTek Computer       | 4         | 0.36%   |
| Conexant Systems       | 3         | 0.27%   |
| Logitech               | 2         | 0.18%   |
| Yamaha                 | 1         | 0.09%   |
| Weltrend Semiconductor | 1         | 0.09%   |
| VIA Technologies       | 1         | 0.09%   |
| Thermaltake            | 1         | 0.09%   |
| Texas Instruments      | 1         | 0.09%   |
| Tenx Technology        | 1         | 0.09%   |
| Kingston Technology    | 1         | 0.09%   |
| Hewlett-Packard        | 1         | 0.09%   |
| ELMCU                  | 1         | 0.09%   |
| Barco Display Systems  | 1         | 0.09%   |
| Astro Gaming           | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 88        | 6.56%   |
| AMD Ryzen HD Audio Controller                                              | 62        | 4.62%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 61        | 4.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 61        | 4.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 52        | 3.88%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 51        | 3.8%    |
| Intel Cannon Lake PCH cAVS                                                 | 42        | 3.13%   |
| AMD FCH Azalia Controller                                                  | 37        | 2.76%   |
| Intel 8 Series HD Audio Controller                                         | 35        | 2.61%   |
| Intel Haswell-ULT HD Audio Controller                                      | 33        | 2.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 29        | 2.16%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 28        | 2.09%   |
| Intel Broadwell-U Audio Controller                                         | 25        | 1.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 24        | 1.79%   |
| Nvidia GA107 High Definition Audio Controller                              | 22        | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 22        | 1.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 21        | 1.57%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 20        | 1.49%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 20        | 1.49%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 1.42%   |
| AMD Trinity HDMI Audio Controller                                          | 19        | 1.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 19        | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 18        | 1.34%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 18        | 1.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 17        | 1.27%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 16        | 1.19%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 16        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 1.19%   |
| AMD Kabini HDMI/DP Audio                                                   | 16        | 1.19%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 15        | 1.12%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.04%   |
| Nvidia High Definition Audio Controller                                    | 13        | 0.97%   |
| Nvidia GF119 HDMI Audio Controller                                         | 13        | 0.97%   |
| Intel Comet Lake PCH-LP cAVS                                               | 13        | 0.97%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 13        | 0.97%   |
| Intel CM238 HD Audio Controller                                            | 12        | 0.89%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 12        | 0.89%   |
| AMD Radeon High Definition Audio Controller                                | 11        | 0.82%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 11        | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                              | 10        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 148       | 27.56%  |
| SK hynix                     | 120       | 22.35%  |
| Micron Technology            | 75        | 13.97%  |
| Crucial                      | 42        | 7.82%   |
| Kingston                     | 41        | 7.64%   |
| Unknown                      | 37        | 6.89%   |
| Ramaxel Technology           | 24        | 4.47%   |
| Elpida                       | 10        | 1.86%   |
| Nanya Technology             | 9         | 1.68%   |
| Corsair                      | 7         | 1.3%    |
| Team                         | 3         | 0.56%   |
| M                            | 3         | 0.56%   |
| A-DATA Technology            | 3         | 0.56%   |
| Unknown                      | 3         | 0.56%   |
| MINPO                        | 2         | 0.37%   |
| G.Skill                      | 2         | 0.37%   |
| Unknown (E)                  | 1         | 0.19%   |
| Unknown (ABCD)               | 1         | 0.19%   |
| Unknown (0x7F7FB5FFFFFFFFFF) | 1         | 0.19%   |
| S                            | 1         | 0.19%   |
| Lexar Co Limited             | 1         | 0.19%   |
| Kingmax                      | 1         | 0.19%   |
| H                            | 1         | 0.19%   |
| Axiom                        | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s | 9         | 1.55%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s    | 8         | 1.38%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s | 7         | 1.21%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s  | 6         | 1.03%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s  | 6         | 1.03%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s | 5         | 0.86%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s | 5         | 0.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s  | 5         | 0.86%   |
| Samsung RAM M378B5173DB0-CK0 4096MB DIMM DDR3 1600MT/s | 5         | 0.86%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s | 4         | 0.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s | 4         | 0.69%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s  | 4         | 0.69%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s  | 4         | 0.69%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s  | 4         | 0.69%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s  | 4         | 0.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s  | 4         | 0.69%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s  | 4         | 0.69%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 4         | 0.69%   |
| Samsung RAM M378B5273CH0-CH9 4GB DIMM DDR3 1867MT/s    | 4         | 0.69%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s   | 4         | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s   | 4         | 0.69%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s | 4         | 0.69%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 3         | 0.52%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s   | 3         | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s | 3         | 0.52%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s | 3         | 0.52%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s | 3         | 0.52%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s           | 3         | 0.52%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s  | 3         | 0.52%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s  | 3         | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s  | 3         | 0.52%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s | 3         | 0.52%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s | 3         | 0.52%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s  | 3         | 0.52%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s  | 3         | 0.52%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s  | 3         | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s | 3         | 0.52%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3             | 3         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s  | 3         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s  | 3         | 0.52%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 193       | 45.95%  |
| DDR3    | 144       | 34.29%  |
| SDRAM   | 20        | 4.76%   |
| Unknown | 18        | 4.29%   |
| DDR5    | 13        | 3.1%    |
| DDR2    | 13        | 3.1%    |
| LPDDR5  | 6         | 1.43%   |
| LPDDR3  | 6         | 1.43%   |
| LPDDR4  | 5         | 1.19%   |
| DDR     | 2         | 0.48%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 277       | 68.06%  |
| DIMM         | 115       | 28.26%  |
| Row Of Chips | 12        | 2.95%   |
| Chip         | 3         | 0.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 162       | 33.96%  |
| 4096  | 140       | 29.35%  |
| 16384 | 81        | 16.98%  |
| 2048  | 65        | 13.63%  |
| 1024  | 15        | 3.14%   |
| 32768 | 9         | 1.89%   |
| 512   | 4         | 0.84%   |
| 12288 | 1         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 101       | 21.09%  |
| 2667    | 95        | 19.83%  |
| 3200    | 73        | 15.24%  |
| 1333    | 26        | 5.43%   |
| 2400    | 19        | 3.97%   |
| 2133    | 19        | 3.97%   |
| 1334    | 16        | 3.34%   |
| 1867    | 11        | 2.3%    |
| 800     | 11        | 2.3%    |
| 667     | 11        | 2.3%    |
| 8400    | 8         | 1.67%   |
| 400     | 8         | 1.67%   |
| 4800    | 7         | 1.46%   |
| 3600    | 7         | 1.46%   |
| 1866    | 7         | 1.46%   |
| Unknown | 6         | 1.25%   |
| 5600    | 5         | 1.04%   |
| 1066    | 5         | 1.04%   |
| 4199    | 4         | 0.84%   |
| 6400    | 3         | 0.63%   |
| 3467    | 3         | 0.63%   |
| 2048    | 3         | 0.63%   |
| 2000    | 3         | 0.63%   |
| 1800    | 3         | 0.63%   |
| 1648    | 3         | 0.63%   |
| 1067    | 3         | 0.63%   |
| 3266    | 2         | 0.42%   |
| 3000    | 2         | 0.42%   |
| 1331    | 2         | 0.42%   |
| 533     | 2         | 0.42%   |
| 49926   | 1         | 0.21%   |
| 8533    | 1         | 0.21%   |
| 7500    | 1         | 0.21%   |
| 7467    | 1         | 0.21%   |
| 5200    | 1         | 0.21%   |
| 4266    | 1         | 0.21%   |
| 3800    | 1         | 0.21%   |
| 3733    | 1         | 0.21%   |
| 3500    | 1         | 0.21%   |
| 2666    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 8         | 57.14%  |
| Seiko Epson     | 3         | 21.43%  |
| Ricoh           | 1         | 7.14%   |
| Kyocera         | 1         | 7.14%   |
| Canon           | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                           | 2         | 14.29%  |
| Seiko Epson Printer                                        | 1         | 7.14%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 7.14%   |
| Seiko Epson ET-2710 Series                                 | 1         | 7.14%   |
| Ricoh Printing Support                                     | 1         | 7.14%   |
| Kyocera UTAX_TA LP 3240_LP 4240                            | 1         | 7.14%   |
| HP LaserJet P3005                                          | 1         | 7.14%   |
| HP LaserJet 1020                                           | 1         | 7.14%   |
| HP HP LaserJet M402dw                                      | 1         | 7.14%   |
| HP DeskJet F2492 All-in-One                                | 1         | 7.14%   |
| HP Deskjet 2510 series                                     | 1         | 7.14%   |
| HP Deskjet 1510                                            | 1         | 7.14%   |
| Canon LBP3010/LBP3018/LBP3050                              | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 126       | 21.76%  |
| Microdia                               | 76        | 13.13%  |
| IMC Networks                           | 47        | 8.12%   |
| Realtek Semiconductor                  | 46        | 7.94%   |
| Cheng Uei Precision Industry (Foxlink) | 40        | 6.91%   |
| Sunplus Innovation Technology          | 37        | 6.39%   |
| Bison Electronics                      | 34        | 5.87%   |
| Quanta                                 | 28        | 4.84%   |
| Lite-On Technology                     | 26        | 4.49%   |
| Suyin                                  | 17        | 2.94%   |
| Syntek                                 | 12        | 2.07%   |
| Silicon Motion                         | 11        | 1.9%    |
| Luxvisions Innotech Limited            | 10        | 1.73%   |
| Sonix Technology                       | 9         | 1.55%   |
| Shinetech                              | 8         | 1.38%   |
| Samsung Electronics                    | 8         | 1.38%   |
| Apple                                  | 8         | 1.38%   |
| Logitech                               | 5         | 0.86%   |
| MacroSilicon                           | 3         | 0.52%   |
| Lenovo                                 | 3         | 0.52%   |
| Z-Star Microelectronics                | 2         | 0.35%   |
| eMPIA Technology                       | 2         | 0.35%   |
| Cubeternet                             | 2         | 0.35%   |
| Aveo Technology                        | 2         | 0.35%   |
| Acer                                   | 2         | 0.35%   |
| Xiaomi                                 | 1         | 0.17%   |
| vivo                                   | 1         | 0.17%   |
| Primax Electronics                     | 1         | 0.17%   |
| OPPO Electronics                       | 1         | 0.17%   |
| OmniVision Technologies                | 1         | 0.17%   |
| Microsoft                              | 1         | 0.17%   |
| kingcome                               | 1         | 0.17%   |
| Jieli Technology                       | 1         | 0.17%   |
| Intel                                  | 1         | 0.17%   |
| Genesys Logic                          | 1         | 0.17%   |
| Foxconn / Hon Hai                      | 1         | 0.17%   |
| Arkmicro Technologies                  | 1         | 0.17%   |
| ALi                                    | 1         | 0.17%   |
| Alcor Micro                            | 1         | 0.17%   |
| Unknown                                | 1         | 0.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 42        | 7.2%    |
| Realtek Integrated_Webcam_HD                                               | 17        | 2.92%   |
| Chicony Integrated Camera                                                  | 16        | 2.74%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 15        | 2.57%   |
| Chicony EasyCamera                                                         | 14        | 2.4%    |
| Sunplus Integrated_Webcam_HD                                               | 13        | 2.23%   |
| IMC Networks Integrated Camera                                             | 13        | 2.23%   |
| Chicony HP HD Camera                                                       | 13        | 2.23%   |
| Microdia Laptop_Integrated_Webcam_HD                                       | 12        | 2.06%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                        | 9         | 1.54%   |
| Bison Lenovo EasyCamera                                                    | 9         | 1.54%   |
| Syntek Integrated Camera                                                   | 8         | 1.37%   |
| Suyin HP Truevision HD                                                     | 8         | 1.37%   |
| Realtek Integrated Webcam HD                                               | 8         | 1.37%   |
| Lite-On HP HD Webcam                                                       | 8         | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 8         | 1.37%   |
| Chicony HP TrueVision HD Camera                                            | 8         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 8         | 1.37%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 7         | 1.2%    |
| Samsung Galaxy series, misc. (MTP mode)                                    | 7         | 1.2%    |
| Lite-On HP HD Camera                                                       | 7         | 1.2%    |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 7         | 1.2%    |
| Microdia Dell Laptop Integrated Webcam HD                                  | 6         | 1.03%   |
| Chicony HP HD Webcam                                                       | 6         | 1.03%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 6         | 1.03%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 6         | 1.03%   |
| Realtek Integrated Webcam                                                  | 5         | 0.86%   |
| Quanta HP HD Camera                                                        | 5         | 0.86%   |
| Lite-On Integrated Camera                                                  | 5         | 0.86%   |
| Chicony TOSHIBA Web Camera - HD                                            | 5         | 0.86%   |
| Bison HP TrueVision HD Webcam                                              | 5         | 0.86%   |
| Bison EasyCamera                                                           | 5         | 0.86%   |
| Shinetech ASUS FHD webcam                                                  | 4         | 0.69%   |
| Quanta HD User Facing                                                      | 4         | 0.69%   |
| Microdia 1.3 MPixel Integrated Webcam                                      | 4         | 0.69%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 4         | 0.69%   |
| IMC Networks EasyCamera                                                    | 4         | 0.69%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 4         | 0.69%   |
| Chicony HP Webcam [2 MP Macro]                                             | 4         | 0.69%   |
| Chicony HP TrueVision HD                                                   | 4         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 57        | 51.35%  |
| Synaptics                          | 22        | 19.82%  |
| Shenzhen Goodix Technology         | 11        | 9.91%   |
| AuthenTec                          | 7         | 6.31%   |
| Upek                               | 6         | 5.41%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.7%    |
| LighTuning Technology              | 2         | 1.8%    |
| Elan Microelectronics              | 2         | 1.8%    |
| Focal-systems.Corp                 | 1         | 0.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 22.52%  |
| Validity Sensors Fingerprint scanner                                       | 8         | 7.21%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 5.41%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 5.41%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 4.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 4.5%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 3.6%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.6%    |
| Synaptics  WBDI                                                            | 4         | 3.6%    |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 3.6%    |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.6%    |
| AuthenTec AES2810                                                          | 4         | 3.6%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.7%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.7%    |
| Validity Sensors VFS491                                                    | 2         | 1.8%    |
| Upek TCS5B Fingerprint sensor                                              | 2         | 1.8%    |
| Synaptics UWP WBDI                                                         | 2         | 1.8%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 2         | 1.8%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.8%    |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.8%    |
| Elan ELAN:ARM-M4                                                           | 2         | 1.8%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.9%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 1         | 0.9%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.9%    |
| Synaptics UWP WBDI Device                                                  | 1         | 0.9%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.9%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.9%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.9%    |
| AuthenTec AES1600                                                          | 1         | 0.9%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 37        | 77.08%  |
| Alcor Micro         | 5         | 10.42%  |
| O2 Micro            | 3         | 6.25%   |
| Lenovo              | 1         | 2.08%   |
| Hewlett-Packard     | 1         | 2.08%   |
| Chicony Electronics | 1         | 2.08%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 29.17%  |
| Broadcom 5880                                                                | 14        | 29.17%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 5         | 10.42%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 10.42%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.25%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 2.08%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 2.08%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 2.08%   |
| Broadcom 58200                                                               | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 563       | 63.33%  |
| 1     | 264       | 29.7%   |
| 2     | 55        | 6.19%   |
| 3     | 4         | 0.45%   |
| 5     | 2         | 0.22%   |
| 4     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 111       | 29.21%  |
| Fingerprint reader       | 110       | 28.95%  |
| Net/wireless             | 40        | 10.53%  |
| Chipcard                 | 39        | 10.26%  |
| Multimedia controller    | 21        | 5.53%   |
| Bluetooth                | 14        | 3.68%   |
| Communication controller | 10        | 2.63%   |
| Storage                  | 6         | 1.58%   |
| Net/ethernet             | 6         | 1.58%   |
| Camera                   | 6         | 1.58%   |
| Sound                    | 5         | 1.32%   |
| Unassigned class         | 4         | 1.05%   |
| Storage/ide              | 2         | 0.53%   |
| Firewire controller      | 2         | 0.53%   |
| Wireless                 | 1         | 0.26%   |
| Network                  | 1         | 0.26%   |
| Modem                    | 1         | 0.26%   |
| Card reader              | 1         | 0.26%   |

