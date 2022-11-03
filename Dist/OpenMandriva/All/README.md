OpenMandriva - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for OpenMandriva.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva/Desktop/README.md) and [notebooks](/Dist/OpenMandriva/Notebook/README.md).

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

Total: 9467

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY m6                     | Notebook    | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [83a1fc191a](https://linux-hardware.org/?probe=83a1fc191a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 710S-13IKB 80VQ     | Notebook    | [dbacfbd3b0](https://linux-hardware.org/?probe=dbacfbd3b0) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a9f10f8922](https://linux-hardware.org/?probe=a9f10f8922) | Nov 02, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [3773260366](https://linux-hardware.org/?probe=3773260366) | Nov 02, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [22214c7851](https://linux-hardware.org/?probe=22214c7851) | Nov 02, 2022 |
| Panasonic     | CF-C1BWFBZ1M                | Notebook    | [18a81d5db2](https://linux-hardware.org/?probe=18a81d5db2) | Nov 02, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [22f68458d4](https://linux-hardware.org/?probe=22f68458d4) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| VS Company    | G31T-M                      | Desktop     | [75eb6866e0](https://linux-hardware.org/?probe=75eb6866e0) | Nov 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [06ea8207dc](https://linux-hardware.org/?probe=06ea8207dc) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [a85aef0a90](https://linux-hardware.org/?probe=a85aef0a90) | Oct 31, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [67e15a659d](https://linux-hardware.org/?probe=67e15a659d) | Oct 31, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [8b208b8383](https://linux-hardware.org/?probe=8b208b8383) | Oct 31, 2022 |
| Acer          | Extensa 5635Z               | Notebook    | [35ce596e08](https://linux-hardware.org/?probe=35ce596e08) | Oct 31, 2022 |
| ASUSTek       | M4A78 PLUS                  | Desktop     | [bac044cd22](https://linux-hardware.org/?probe=bac044cd22) | Oct 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [c64399793c](https://linux-hardware.org/?probe=c64399793c) | Oct 31, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c23efa8caa](https://linux-hardware.org/?probe=c23efa8caa) | Oct 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [598d815c17](https://linux-hardware.org/?probe=598d815c17) | Oct 31, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [acfa0d90d6](https://linux-hardware.org/?probe=acfa0d90d6) | Oct 31, 2022 |
| Pegatron      | IPPCR-SS                    | Desktop     | [9427da0212](https://linux-hardware.org/?probe=9427da0212) | Oct 31, 2022 |
| HP            | G72                         | Notebook    | [08a732911d](https://linux-hardware.org/?probe=08a732911d) | Oct 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| HP            | 18E7                        | Desktop     | [6393aa1211](https://linux-hardware.org/?probe=6393aa1211) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [dca18dced0](https://linux-hardware.org/?probe=dca18dced0) | Oct 30, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [bf8945db85](https://linux-hardware.org/?probe=bf8945db85) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Prestigio     | PSB133S01ZFP                | Notebook    | [e10becbd35](https://linux-hardware.org/?probe=e10becbd35) | Oct 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7605a5bf1c](https://linux-hardware.org/?probe=7605a5bf1c) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [b7760774ca](https://linux-hardware.org/?probe=b7760774ca) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| Dell          | Studio 1737                 | Notebook    | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| HP            | Compaq 615                  | Notebook    | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [048348c6ba](https://linux-hardware.org/?probe=048348c6ba) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [ffb4369f83](https://linux-hardware.org/?probe=ffb4369f83) | Oct 29, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [1d3ff229c6](https://linux-hardware.org/?probe=1d3ff229c6) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Samsung       | 670Z5E                      | Notebook    | [159f89858c](https://linux-hardware.org/?probe=159f89858c) | Oct 28, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [6d87562df6](https://linux-hardware.org/?probe=6d87562df6) | Oct 28, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [2ca56cb740](https://linux-hardware.org/?probe=2ca56cb740) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6b57390808](https://linux-hardware.org/?probe=6b57390808) | Oct 28, 2022 |
| Lenovo        | B560                        | Notebook    | [73a6da1bdc](https://linux-hardware.org/?probe=73a6da1bdc) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [0ca2ea7180](https://linux-hardware.org/?probe=0ca2ea7180) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| Intel         | DG965OT AAD63733-203        | Desktop     | [28ad26edff](https://linux-hardware.org/?probe=28ad26edff) | Oct 28, 2022 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [1627ad94ef](https://linux-hardware.org/?probe=1627ad94ef) | Oct 27, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [6b01f2f498](https://linux-hardware.org/?probe=6b01f2f498) | Oct 27, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [5748274da1](https://linux-hardware.org/?probe=5748274da1) | Oct 27, 2022 |
| Acer          | Aspire 8730                 | Notebook    | [86bffd9523](https://linux-hardware.org/?probe=86bffd9523) | Oct 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [22dedf6886](https://linux-hardware.org/?probe=22dedf6886) | Oct 27, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [033d6281bd](https://linux-hardware.org/?probe=033d6281bd) | Oct 27, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [fd34f66305](https://linux-hardware.org/?probe=fd34f66305) | Oct 26, 2022 |
| Acer          | Veriton M275                | Desktop     | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d8343e2db5](https://linux-hardware.org/?probe=d8343e2db5) | Oct 26, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| Dell          | Precision 7560              | Notebook    | [c82d6a32a5](https://linux-hardware.org/?probe=c82d6a32a5) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [2dd0f7f115](https://linux-hardware.org/?probe=2dd0f7f115) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [622aa11277](https://linux-hardware.org/?probe=622aa11277) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [eca0e58bd8](https://linux-hardware.org/?probe=eca0e58bd8) | Oct 25, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ec46b18fd5](https://linux-hardware.org/?probe=ec46b18fd5) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [1c68e176b6](https://linux-hardware.org/?probe=1c68e176b6) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| ASRock        | B660M Pro RS                | Desktop     | [e3b389cb66](https://linux-hardware.org/?probe=e3b389cb66) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | Notebook    | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bfa28dd791](https://linux-hardware.org/?probe=bfa28dd791) | Oct 24, 2022 |
| Lenovo        | B560                        | Notebook    | [82125c56a3](https://linux-hardware.org/?probe=82125c56a3) | Oct 24, 2022 |
| Dell          | 0GX297                      | Desktop     | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Medion        | P8612                       | Notebook    | [a5c437d5f8](https://linux-hardware.org/?probe=a5c437d5f8) | Oct 24, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | A7U                         | Notebook    | [867f26dde1](https://linux-hardware.org/?probe=867f26dde1) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a995e58f10](https://linux-hardware.org/?probe=a995e58f10) | Oct 24, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d178c463df](https://linux-hardware.org/?probe=d178c463df) | Oct 24, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [69327d2615](https://linux-hardware.org/?probe=69327d2615) | Oct 24, 2022 |
| HP            | 8767 A                      | Desktop     | [7ecf583dab](https://linux-hardware.org/?probe=7ecf583dab) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | Notebook    | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [683ac39f80](https://linux-hardware.org/?probe=683ac39f80) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [5ff7cf2e42](https://linux-hardware.org/?probe=5ff7cf2e42) | Oct 23, 2022 |
| ASUSTek       | PB62                        | Desktop     | [ddec39293d](https://linux-hardware.org/?probe=ddec39293d) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | Desktop     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [edfb470814](https://linux-hardware.org/?probe=edfb470814) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | Notebook    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| ASUSTek       | F2A85-V PRO                 | Desktop     | [ff4b30eab7](https://linux-hardware.org/?probe=ff4b30eab7) | Oct 23, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [3d217d0a43](https://linux-hardware.org/?probe=3d217d0a43) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Dell          | 0HX555                      | Desktop     | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | Desktop     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Sony          | VPCEB1S1R                   | Notebook    | [1e64f5427a](https://linux-hardware.org/?probe=1e64f5427a) | Oct 21, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [7bd1ee25b3](https://linux-hardware.org/?probe=7bd1ee25b3) | Oct 21, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| MSI           | H310M PRO-VD                | Desktop     | [9ce99513bc](https://linux-hardware.org/?probe=9ce99513bc) | Oct 21, 2022 |
| Lenovo        | ThinkPad R61 8935AC7        | Notebook    | [94d73589fc](https://linux-hardware.org/?probe=94d73589fc) | Oct 21, 2022 |
| Microboard    | Cantiga & ICH9M Chipset     | Notebook    | [1fffce3846](https://linux-hardware.org/?probe=1fffce3846) | Oct 21, 2022 |
| Dell          | Precision M6800             | Notebook    | [9b909039ee](https://linux-hardware.org/?probe=9b909039ee) | Oct 21, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [612f0f6e06](https://linux-hardware.org/?probe=612f0f6e06) | Oct 21, 2022 |
| MSI           | H61M-P20                    | Desktop     | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| Lenovo        | ThinkPad T520 42434WU       | Notebook    | [d118d39c58](https://linux-hardware.org/?probe=d118d39c58) | Oct 21, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [1ad0ed065f](https://linux-hardware.org/?probe=1ad0ed065f) | Oct 21, 2022 |
| MSI           | GT70 0NC/GT70 0NC           | Notebook    | [592b788d62](https://linux-hardware.org/?probe=592b788d62) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| ASUSTek       | P7P55-M                     | Desktop     | [3ff254b938](https://linux-hardware.org/?probe=3ff254b938) | Oct 20, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7a1b569725](https://linux-hardware.org/?probe=7a1b569725) | Oct 20, 2022 |
| Dell          | Latitude E5410              | Notebook    | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| Gigabyte      | AERO 17 XD                  | Notebook    | [ca3dd06f6b](https://linux-hardware.org/?probe=ca3dd06f6b) | Oct 20, 2022 |
| Sony          | SVE1513B1EW                 | Notebook    | [77ef0b542b](https://linux-hardware.org/?probe=77ef0b542b) | Oct 20, 2022 |
| Dell          | 0V52N7 A01                  | Server      | [c3990d0066](https://linux-hardware.org/?probe=c3990d0066) | Oct 19, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| HP            | 1825                        | Desktop     | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [de13cd2a09](https://linux-hardware.org/?probe=de13cd2a09) | Oct 19, 2022 |
| HP            | ProBook 4330s               | Notebook    | [088c42cbc9](https://linux-hardware.org/?probe=088c42cbc9) | Oct 19, 2022 |
| HP            | 805D                        | Desktop     | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [d65e0cfe7a](https://linux-hardware.org/?probe=d65e0cfe7a) | Oct 18, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [e4c3a71575](https://linux-hardware.org/?probe=e4c3a71575) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | Desktop     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| Lenovo        | G480                        | Notebook    | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| HP            | Unknown                     | Notebook    | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| ASUSTek       | F9S                         | Notebook    | [c8df776935](https://linux-hardware.org/?probe=c8df776935) | Oct 17, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [e77cad05c2](https://linux-hardware.org/?probe=e77cad05c2) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [a1e9be5323](https://linux-hardware.org/?probe=a1e9be5323) | Oct 17, 2022 |
| HP            | Pavilion dv8                | Notebook    | [d290113849](https://linux-hardware.org/?probe=d290113849) | Oct 17, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [29f6ba9612](https://linux-hardware.org/?probe=29f6ba9612) | Oct 17, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c5beaeaf05](https://linux-hardware.org/?probe=c5beaeaf05) | Oct 17, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a45675d222](https://linux-hardware.org/?probe=a45675d222) | Oct 16, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Dell          | Latitude 3490               | Notebook    | [a739a29b72](https://linux-hardware.org/?probe=a739a29b72) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [76f457f2aa](https://linux-hardware.org/?probe=76f457f2aa) | Oct 16, 2022 |
| Dell          | Latitude E6420              | Notebook    | [913e2b1acd](https://linux-hardware.org/?probe=913e2b1acd) | Oct 15, 2022 |
| HP            | 1850                        | Desktop     | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | Notebook    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [a19fc69283](https://linux-hardware.org/?probe=a19fc69283) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | Desktop     | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| Dell          | 0J3C2F A01                  | Desktop     | [b30840548a](https://linux-hardware.org/?probe=b30840548a) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| HP            | 3648h                       | Desktop     | [ce5e78d7e3](https://linux-hardware.org/?probe=ce5e78d7e3) | Oct 14, 2022 |
| Dell          | Latitude 3340               | Notebook    | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | Notebook    | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [60e6bd1280](https://linux-hardware.org/?probe=60e6bd1280) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| Dell          | Latitude E5440              | Notebook    | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [b040c6de83](https://linux-hardware.org/?probe=b040c6de83) | Oct 14, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [a9f67e3f57](https://linux-hardware.org/?probe=a9f67e3f57) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | Notebook    | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [4cadd86832](https://linux-hardware.org/?probe=4cadd86832) | Oct 13, 2022 |
| Dell          | Studio 1555                 | Notebook    | [52104abe69](https://linux-hardware.org/?probe=52104abe69) | Oct 13, 2022 |
| HP            | ENVY 15                     | Notebook    | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Lenovo        | ThinkCentre M71e 3167B28    | Desktop     | [0cfbd3c2fc](https://linux-hardware.org/?probe=0cfbd3c2fc) | Oct 13, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [37b9e0d491](https://linux-hardware.org/?probe=37b9e0d491) | Oct 13, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [814a533c23](https://linux-hardware.org/?probe=814a533c23) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| HP            | 3648h                       | Desktop     | [5b495e41ff](https://linux-hardware.org/?probe=5b495e41ff) | Oct 13, 2022 |
| Dell          | Vostro 3446                 | Notebook    | [da79693286](https://linux-hardware.org/?probe=da79693286) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [65e0a41b8d](https://linux-hardware.org/?probe=65e0a41b8d) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | G42                         | Notebook    | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [a122b26729](https://linux-hardware.org/?probe=a122b26729) | Oct 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7fda9973db](https://linux-hardware.org/?probe=7fda9973db) | Oct 12, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ccdcc89519](https://linux-hardware.org/?probe=ccdcc89519) | Oct 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [88385d207c](https://linux-hardware.org/?probe=88385d207c) | Oct 12, 2022 |
| Star Labs     | StarLite                    | Notebook    | [627ad33197](https://linux-hardware.org/?probe=627ad33197) | Oct 12, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [8eaf391b08](https://linux-hardware.org/?probe=8eaf391b08) | Oct 12, 2022 |
| HP            | 1497                        | Desktop     | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| AMD           | A88                         | Desktop     | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [40adf0a5d8](https://linux-hardware.org/?probe=40adf0a5d8) | Oct 11, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | Desktop     | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [33c86327c4](https://linux-hardware.org/?probe=33c86327c4) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | Desktop     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| Lenovo        | ThinkPad X220 42873LJ       | Notebook    | [b96b26c09b](https://linux-hardware.org/?probe=b96b26c09b) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [f263785a18](https://linux-hardware.org/?probe=f263785a18) | Oct 11, 2022 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | Notebook    | [1680df8cd8](https://linux-hardware.org/?probe=1680df8cd8) | Oct 11, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [e5720c01a5](https://linux-hardware.org/?probe=e5720c01a5) | Oct 10, 2022 |
| ASRock        | B365M Pro4                  | Desktop     | [669c570a2e](https://linux-hardware.org/?probe=669c570a2e) | Oct 10, 2022 |
| HP            | Presario CQ57               | Notebook    | [b67f538b81](https://linux-hardware.org/?probe=b67f538b81) | Oct 10, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [f3a23a25c6](https://linux-hardware.org/?probe=f3a23a25c6) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| HP            | Notebook                    | Notebook    | [2fd3bd5ee0](https://linux-hardware.org/?probe=2fd3bd5ee0) | Oct 10, 2022 |
| HP            | 829E                        | Mini pc     | [465ec7a2fe](https://linux-hardware.org/?probe=465ec7a2fe) | Oct 10, 2022 |
| MSI           | P67A-GD65                   | Desktop     | [009f3853bf](https://linux-hardware.org/?probe=009f3853bf) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | Desktop     | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | Desktop     | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | Notebook    | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| ASUSTek       | P7P55D-E LX                 | Desktop     | [d6231f581c](https://linux-hardware.org/?probe=d6231f581c) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [1d59ae6f4a](https://linux-hardware.org/?probe=1d59ae6f4a) | Oct 08, 2022 |
| Dell          | Latitude 5580               | Notebook    | [77173e171f](https://linux-hardware.org/?probe=77173e171f) | Oct 08, 2022 |
| MSI           | A55M-P33                    | Desktop     | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0a30c048b8](https://linux-hardware.org/?probe=0a30c048b8) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9d44a35e48](https://linux-hardware.org/?probe=9d44a35e48) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | Desktop     | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [3e7cc2c14a](https://linux-hardware.org/?probe=3e7cc2c14a) | Oct 07, 2022 |
| HP            | 872E                        | Mini pc     | [651563d698](https://linux-hardware.org/?probe=651563d698) | Oct 07, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [29de9dfa4a](https://linux-hardware.org/?probe=29de9dfa4a) | Oct 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [509deb10b3](https://linux-hardware.org/?probe=509deb10b3) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8901403de4](https://linux-hardware.org/?probe=8901403de4) | Oct 07, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [60c519a7dd](https://linux-hardware.org/?probe=60c519a7dd) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f19e278e43](https://linux-hardware.org/?probe=f19e278e43) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [d5f7a80d34](https://linux-hardware.org/?probe=d5f7a80d34) | Oct 06, 2022 |
| Gigabyte      | Z270X-Gaming 5              | Desktop     | [9ad9a1c969](https://linux-hardware.org/?probe=9ad9a1c969) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | Desktop     | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [69db41a0b6](https://linux-hardware.org/?probe=69db41a0b6) | Oct 06, 2022 |
| Lenovo        | 1031 SDK0E50510 WIN 2625... | Desktop     | [771e19629c](https://linux-hardware.org/?probe=771e19629c) | Oct 05, 2022 |
| HP            | 18E4                        | Desktop     | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Gigabyte      | TRX40 AORUS PRO WIFI        | Desktop     | [85f2638273](https://linux-hardware.org/?probe=85f2638273) | Oct 05, 2022 |
| Positivo      | C14CR01                     | Notebook    | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f9224c972e](https://linux-hardware.org/?probe=f9224c972e) | Oct 05, 2022 |
| Lenovo        | ThinkPad L430 24641J9       | Notebook    | [4f4932300b](https://linux-hardware.org/?probe=4f4932300b) | Oct 05, 2022 |
| Lenovo        | Yoga 510-14IKB 80VB         | Convertible | [e328286003](https://linux-hardware.org/?probe=e328286003) | Oct 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [14423cc638](https://linux-hardware.org/?probe=14423cc638) | Oct 05, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Dell          | XPS 9320                    | Notebook    | [c4888023c3](https://linux-hardware.org/?probe=c4888023c3) | Oct 04, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b151ce6353](https://linux-hardware.org/?probe=b151ce6353) | Oct 04, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [1923c04bfc](https://linux-hardware.org/?probe=1923c04bfc) | Oct 04, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1cceb45dea](https://linux-hardware.org/?probe=1cceb45dea) | Oct 04, 2022 |
| Acer          | Aspire 4736                 | Notebook    | [48b8af7bcf](https://linux-hardware.org/?probe=48b8af7bcf) | Oct 04, 2022 |
| Wortmann      | 1220676_1470204             | Tablet      | [09cdce1807](https://linux-hardware.org/?probe=09cdce1807) | Oct 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [60de9a1977](https://linux-hardware.org/?probe=60de9a1977) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [adde8098e4](https://linux-hardware.org/?probe=adde8098e4) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [4994764371](https://linux-hardware.org/?probe=4994764371) | Oct 04, 2022 |
| HP            | 213D A01                    | Desktop     | [e81fd5fea5](https://linux-hardware.org/?probe=e81fd5fea5) | Oct 04, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [1348c5b5eb](https://linux-hardware.org/?probe=1348c5b5eb) | Oct 03, 2022 |
| HP            | 2AED                        | All in one  | [9092720ed6](https://linux-hardware.org/?probe=9092720ed6) | Oct 03, 2022 |
| Intel         | H55                         | Desktop     | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| MSI           | H110M GAMING                | Desktop     | [379aaceaab](https://linux-hardware.org/?probe=379aaceaab) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a055ed4d2c](https://linux-hardware.org/?probe=a055ed4d2c) | Oct 03, 2022 |
| Acer          | TravelMate 5744             | Notebook    | [4817d4810d](https://linux-hardware.org/?probe=4817d4810d) | Oct 03, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [80a70e8f6e](https://linux-hardware.org/?probe=80a70e8f6e) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [9bf3a4a735](https://linux-hardware.org/?probe=9bf3a4a735) | Oct 03, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [36b32fe8c0](https://linux-hardware.org/?probe=36b32fe8c0) | Oct 03, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [c6e6708366](https://linux-hardware.org/?probe=c6e6708366) | Oct 03, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [019702e62b](https://linux-hardware.org/?probe=019702e62b) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M58p 6234FB9    | Desktop     | [3c772e3e1d](https://linux-hardware.org/?probe=3c772e3e1d) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [47a7282318](https://linux-hardware.org/?probe=47a7282318) | Oct 02, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [43694e5952](https://linux-hardware.org/?probe=43694e5952) | Oct 02, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [bfd8dc3c18](https://linux-hardware.org/?probe=bfd8dc3c18) | Oct 02, 2022 |
| MSI           | A75A-G35                    | Desktop     | [66b1d71092](https://linux-hardware.org/?probe=66b1d71092) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| Biostar       | A75MG                       | Desktop     | [ba1785b4b6](https://linux-hardware.org/?probe=ba1785b4b6) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [be11beaedd](https://linux-hardware.org/?probe=be11beaedd) | Oct 02, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| ASRock        | Z97 Pro4                    | Desktop     | [d0465080bf](https://linux-hardware.org/?probe=d0465080bf) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| ASRock        | J5005-ITX                   | Desktop     | [783c72d32e](https://linux-hardware.org/?probe=783c72d32e) | Oct 01, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| MSI           | MS-7235                     | Desktop     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | Notebook    | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| Itautec       | Infoway a7420               | Notebook    | [bb52fe66cf](https://linux-hardware.org/?probe=bb52fe66cf) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [f05f33fa9b](https://linux-hardware.org/?probe=f05f33fa9b) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| HP            | Pavilion dv2700             | Notebook    | [0da9fb0afd](https://linux-hardware.org/?probe=0da9fb0afd) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [aee33639b9](https://linux-hardware.org/?probe=aee33639b9) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [24aefc4138](https://linux-hardware.org/?probe=24aefc4138) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | Notebook    | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| Intel         | H61                         | Desktop     | [37af3b0cdb](https://linux-hardware.org/?probe=37af3b0cdb) | Sep 30, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [f0eae50061](https://linux-hardware.org/?probe=f0eae50061) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Dell          | Latitude E6520              | Notebook    | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [11e4602764](https://linux-hardware.org/?probe=11e4602764) | Sep 30, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [3e91e2bfaf](https://linux-hardware.org/?probe=3e91e2bfaf) | Sep 29, 2022 |
| Dell          | Latitude D531               | Notebook    | [331cad8b98](https://linux-hardware.org/?probe=331cad8b98) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
| HP            | 3398                        | Desktop     | [c2190a0657](https://linux-hardware.org/?probe=c2190a0657) | Sep 29, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [f9efac58da](https://linux-hardware.org/?probe=f9efac58da) | Sep 29, 2022 |
| HP            | Compaq 6720s                | Notebook    | [ddb5163310](https://linux-hardware.org/?probe=ddb5163310) | Sep 29, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [88d57c6319](https://linux-hardware.org/?probe=88d57c6319) | Sep 29, 2022 |
| Huanan        | X79 (INTEL Xeon E5/Corei... | Desktop     | [a40d59533c](https://linux-hardware.org/?probe=a40d59533c) | Sep 29, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [9414d73ae0](https://linux-hardware.org/?probe=9414d73ae0) | Sep 29, 2022 |
| Acer          | Veriton M275                | Desktop     | [f871926a8e](https://linux-hardware.org/?probe=f871926a8e) | Sep 29, 2022 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [235930defb](https://linux-hardware.org/?probe=235930defb) | Sep 28, 2022 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [5a7ad7dba9](https://linux-hardware.org/?probe=5a7ad7dba9) | Sep 28, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6f1ecca2f0](https://linux-hardware.org/?probe=6f1ecca2f0) | Sep 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [372cdc3726](https://linux-hardware.org/?probe=372cdc3726) | Sep 28, 2022 |
| Dell          | Latitude 3310               | Notebook    | [c21a321dce](https://linux-hardware.org/?probe=c21a321dce) | Sep 28, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [a42a4722f7](https://linux-hardware.org/?probe=a42a4722f7) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [2e9902fee0](https://linux-hardware.org/?probe=2e9902fee0) | Sep 28, 2022 |
| Dell          | Vostro 5391                 | Notebook    | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| Dell          | Latitude 3120               | Convertible | [932a938506](https://linux-hardware.org/?probe=932a938506) | Sep 28, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [c3041b210f](https://linux-hardware.org/?probe=c3041b210f) | Sep 28, 2022 |
| HP            | 18E7                        | Desktop     | [132a87f746](https://linux-hardware.org/?probe=132a87f746) | Sep 28, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [9a613eaf66](https://linux-hardware.org/?probe=9a613eaf66) | Sep 28, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ada186ce05](https://linux-hardware.org/?probe=ada186ce05) | Sep 27, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d27bf09dc8](https://linux-hardware.org/?probe=d27bf09dc8) | Sep 27, 2022 |
| Sony          | VPCEH1S1R                   | Notebook    | [5214bb023f](https://linux-hardware.org/?probe=5214bb023f) | Sep 27, 2022 |
| Dell          | Latitude 3300               | Notebook    | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [af23e43e99](https://linux-hardware.org/?probe=af23e43e99) | Sep 27, 2022 |
| Dell          | Latitude 3310               | Notebook    | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| HP            | 844C                        | Desktop     | [51cb0bca57](https://linux-hardware.org/?probe=51cb0bca57) | Sep 27, 2022 |
| HP            | 0A60h                       | Desktop     | [ccb90a4b31](https://linux-hardware.org/?probe=ccb90a4b31) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d46d96565b](https://linux-hardware.org/?probe=d46d96565b) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f5f99a7234](https://linux-hardware.org/?probe=f5f99a7234) | Sep 27, 2022 |
| Toshiba       | Satellite C850-1LK          | Notebook    | [f0240dcb2d](https://linux-hardware.org/?probe=f0240dcb2d) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7cea84adb2](https://linux-hardware.org/?probe=7cea84adb2) | Sep 27, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [a33ab40c8b](https://linux-hardware.org/?probe=a33ab40c8b) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [bc34bf4d73](https://linux-hardware.org/?probe=bc34bf4d73) | Sep 27, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Positivo      | SW6H                        | Notebook    | [4cfa6665bb](https://linux-hardware.org/?probe=4cfa6665bb) | Sep 27, 2022 |
| Packard Be... | EasyNote LS44SB             | Notebook    | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [56ac60a3dc](https://linux-hardware.org/?probe=56ac60a3dc) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [898f9bf963](https://linux-hardware.org/?probe=898f9bf963) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [8736347f60](https://linux-hardware.org/?probe=8736347f60) | Sep 26, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9d1392e945](https://linux-hardware.org/?probe=9d1392e945) | Sep 26, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a213c6d22a](https://linux-hardware.org/?probe=a213c6d22a) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [6ce0a09785](https://linux-hardware.org/?probe=6ce0a09785) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [9458cffde8](https://linux-hardware.org/?probe=9458cffde8) | Sep 26, 2022 |
| Dell          | Latitude E5250              | Notebook    | [e4ffe3583d](https://linux-hardware.org/?probe=e4ffe3583d) | Sep 26, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [8d3b235d4c](https://linux-hardware.org/?probe=8d3b235d4c) | Sep 25, 2022 |
| CCE           | Capella & IbexPeak-M Chi... | Notebook    | [07554a7a2b](https://linux-hardware.org/?probe=07554a7a2b) | Sep 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [a7aadaeed0](https://linux-hardware.org/?probe=a7aadaeed0) | Sep 25, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [41db205ec7](https://linux-hardware.org/?probe=41db205ec7) | Sep 25, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [21121aa007](https://linux-hardware.org/?probe=21121aa007) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | Desktop     | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6c6ae30eba](https://linux-hardware.org/?probe=6c6ae30eba) | Sep 24, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [8442ff18ca](https://linux-hardware.org/?probe=8442ff18ca) | Sep 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| HP            | 198E                        | Desktop     | [ffa9a79cc0](https://linux-hardware.org/?probe=ffa9a79cc0) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Acidanther... | Mac-A369DDC4E67F1C45 iMa... | All in one  | [0e9b82f312](https://linux-hardware.org/?probe=0e9b82f312) | Sep 24, 2022 |
| Unknown       | WZBTDT1 R110                | Desktop     | [8b6b5af31a](https://linux-hardware.org/?probe=8b6b5af31a) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [815fe42722](https://linux-hardware.org/?probe=815fe42722) | Sep 23, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| HP            | 0AA8h                       | Desktop     | [9c02e3fc31](https://linux-hardware.org/?probe=9c02e3fc31) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Lenovo        | ThinkCentre M58p 6137CR4    | Desktop     | [72e0bfca3b](https://linux-hardware.org/?probe=72e0bfca3b) | Sep 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [5281ee08e1](https://linux-hardware.org/?probe=5281ee08e1) | Sep 23, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9c4d48864b](https://linux-hardware.org/?probe=9c4d48864b) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | Desktop     | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [443df1ca5c](https://linux-hardware.org/?probe=443df1ca5c) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [061ef6f153](https://linux-hardware.org/?probe=061ef6f153) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [69a66aefdd](https://linux-hardware.org/?probe=69a66aefdd) | Sep 23, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2b37d81d4c](https://linux-hardware.org/?probe=2b37d81d4c) | Sep 22, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [2527dc6ea0](https://linux-hardware.org/?probe=2527dc6ea0) | Sep 22, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [9b451feb14](https://linux-hardware.org/?probe=9b451feb14) | Sep 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Lenovo        | ThinkPad X200s 7470WWD      | Notebook    | [268aa65de3](https://linux-hardware.org/?probe=268aa65de3) | Sep 22, 2022 |
| HP            | 1998                        | Desktop     | [f8399e0d3a](https://linux-hardware.org/?probe=f8399e0d3a) | Sep 22, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [07477a078f](https://linux-hardware.org/?probe=07477a078f) | Sep 22, 2022 |
| ASUSTek       | K70AD                       | Notebook    | [49dff3ffb5](https://linux-hardware.org/?probe=49dff3ffb5) | Sep 22, 2022 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | Notebook    | [c1edc96aa7](https://linux-hardware.org/?probe=c1edc96aa7) | Sep 21, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [989f23b214](https://linux-hardware.org/?probe=989f23b214) | Sep 21, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | Desktop     | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [ee93820bdf](https://linux-hardware.org/?probe=ee93820bdf) | Sep 21, 2022 |
| Dell          | G5 5505                     | Notebook    | [82017aa2ae](https://linux-hardware.org/?probe=82017aa2ae) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [2165b4b046](https://linux-hardware.org/?probe=2165b4b046) | Sep 20, 2022 |
| Dell          | XPS 9320                    | Notebook    | [cd57903024](https://linux-hardware.org/?probe=cd57903024) | Sep 20, 2022 |
| Dell          | Precision M3800             | Notebook    | [2d5d8707dd](https://linux-hardware.org/?probe=2d5d8707dd) | Sep 20, 2022 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [3e0939e549](https://linux-hardware.org/?probe=3e0939e549) | Sep 20, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [4d5fc6b39f](https://linux-hardware.org/?probe=4d5fc6b39f) | Sep 20, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9c483616f6](https://linux-hardware.org/?probe=9c483616f6) | Sep 20, 2022 |
| Acer          | Aspire V3-471               | Notebook    | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| Lenovo        | 3728 SDK0R32862 WIN 3258... | Desktop     | [d78d85bde3](https://linux-hardware.org/?probe=d78d85bde3) | Sep 20, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8003baae8c](https://linux-hardware.org/?probe=8003baae8c) | Sep 19, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [a2d230d217](https://linux-hardware.org/?probe=a2d230d217) | Sep 19, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [33e582251a](https://linux-hardware.org/?probe=33e582251a) | Sep 19, 2022 |
| Lenovo        | G50-80 80R0                 | Notebook    | [f04ed15344](https://linux-hardware.org/?probe=f04ed15344) | Sep 19, 2022 |
| Samsung       | R530/R730                   | Notebook    | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0e1784b38d](https://linux-hardware.org/?probe=0e1784b38d) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [983266d6ba](https://linux-hardware.org/?probe=983266d6ba) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [374de3c13c](https://linux-hardware.org/?probe=374de3c13c) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [bc2dd8505b](https://linux-hardware.org/?probe=bc2dd8505b) | Sep 19, 2022 |
| HP            | 2B34                        | Desktop     | [a9e82bbb40](https://linux-hardware.org/?probe=a9e82bbb40) | Sep 19, 2022 |
| Dell          | Latitude 3310               | Notebook    | [55332651e0](https://linux-hardware.org/?probe=55332651e0) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Convertible | [e6b9b405e8](https://linux-hardware.org/?probe=e6b9b405e8) | Sep 19, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [448ba707f6](https://linux-hardware.org/?probe=448ba707f6) | Sep 19, 2022 |
| Dell          | Latitude 3120               | Notebook    | [558e95141d](https://linux-hardware.org/?probe=558e95141d) | Sep 19, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [419bf72e22](https://linux-hardware.org/?probe=419bf72e22) | Sep 19, 2022 |
| Dell          | Latitude 3300               | Notebook    | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| ECS           | A55F2-M4                    | Desktop     | [335d28e72c](https://linux-hardware.org/?probe=335d28e72c) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| Positivo      | C14CR21                     | Notebook    | [e72ef2677b](https://linux-hardware.org/?probe=e72ef2677b) | Sep 19, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [892c3fb361](https://linux-hardware.org/?probe=892c3fb361) | Sep 18, 2022 |
| HP            | EliteBook 2740p             | Notebook    | [6643773237](https://linux-hardware.org/?probe=6643773237) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | Notebook    | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [eb619ed1c5](https://linux-hardware.org/?probe=eb619ed1c5) | Sep 18, 2022 |
| HP            | 2B29                        | Desktop     | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [08bd4157a3](https://linux-hardware.org/?probe=08bd4157a3) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | Desktop     | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [65c4f113d8](https://linux-hardware.org/?probe=65c4f113d8) | Sep 18, 2022 |
| HP            | ProBook 6470b               | Notebook    | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Acer          | Switch SA5-271P             | Tablet      | [c9900a8e2f](https://linux-hardware.org/?probe=c9900a8e2f) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [d55d9fad24](https://linux-hardware.org/?probe=d55d9fad24) | Sep 17, 2022 |
| Lenovo        | ThinkPad E570 20H5009NUS    | Notebook    | [c64258edc0](https://linux-hardware.org/?probe=c64258edc0) | Sep 17, 2022 |
| Dell          | Latitude 7390               | Notebook    | [64c9b13553](https://linux-hardware.org/?probe=64c9b13553) | Sep 17, 2022 |
| Toshiba       | TECRA S10                   | Notebook    | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| NEC Comput... | PC-VY21AEZ75                | Notebook    | [a24d79ffc2](https://linux-hardware.org/?probe=a24d79ffc2) | Sep 17, 2022 |
| Toshiba       | Satellite P845T             | Notebook    | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [a790b35cc1](https://linux-hardware.org/?probe=a790b35cc1) | Sep 17, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e55484acd4](https://linux-hardware.org/?probe=e55484acd4) | Sep 17, 2022 |
| Dell          | Precision 7720              | Notebook    | [9658507a0b](https://linux-hardware.org/?probe=9658507a0b) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [7f9cf09305](https://linux-hardware.org/?probe=7f9cf09305) | Sep 17, 2022 |
| Intel         | H61                         | Desktop     | [d1b17183d7](https://linux-hardware.org/?probe=d1b17183d7) | Sep 16, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [21620af2bb](https://linux-hardware.org/?probe=21620af2bb) | Sep 16, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [d5464b13f9](https://linux-hardware.org/?probe=d5464b13f9) | Sep 16, 2022 |
| HP            | 82F2 A01                    | Desktop     | [f97faeff54](https://linux-hardware.org/?probe=f97faeff54) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e472e7fdde](https://linux-hardware.org/?probe=e472e7fdde) | Sep 16, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1ccce4a76a](https://linux-hardware.org/?probe=1ccce4a76a) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e04ec1834f](https://linux-hardware.org/?probe=e04ec1834f) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| HP            | Compaq Presario CQ50        | Notebook    | [41dcd9ffc4](https://linux-hardware.org/?probe=41dcd9ffc4) | Sep 16, 2022 |
| Sony          | VAIO                        | All in one  | [71ae1045da](https://linux-hardware.org/?probe=71ae1045da) | Sep 15, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [fcdfa43a37](https://linux-hardware.org/?probe=fcdfa43a37) | Sep 15, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | Notebook    | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0a91582802](https://linux-hardware.org/?probe=0a91582802) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [8366bd494c](https://linux-hardware.org/?probe=8366bd494c) | Sep 14, 2022 |
| Dell          | Inspiron 14-3467            | Notebook    | [e92b56817a](https://linux-hardware.org/?probe=e92b56817a) | Sep 14, 2022 |
| BESSTAR Te... | HM50                        | Desktop     | [a2632415a2](https://linux-hardware.org/?probe=a2632415a2) | Sep 14, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| HP            | 1495                        | Desktop     | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| HP            | 1496                        | Desktop     | [cb6033fc21](https://linux-hardware.org/?probe=cb6033fc21) | Sep 14, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Timi          | TM1612                      | Notebook    | [536fc04dcb](https://linux-hardware.org/?probe=536fc04dcb) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 2324GA1       | Notebook    | [c4e6cc1489](https://linux-hardware.org/?probe=c4e6cc1489) | Sep 14, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | Desktop     | [d88e0026dc](https://linux-hardware.org/?probe=d88e0026dc) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| Dell          | Latitude 3120               | Convertible | [a8315e1147](https://linux-hardware.org/?probe=a8315e1147) | Sep 13, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ea845ec5ea](https://linux-hardware.org/?probe=ea845ec5ea) | Sep 13, 2022 |
| Dell          | Inspiron 3451               | Notebook    | [f06aa45765](https://linux-hardware.org/?probe=f06aa45765) | Sep 13, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [bfd4a6b00a](https://linux-hardware.org/?probe=bfd4a6b00a) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | Notebook    | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| MSI           | Z97 MPOWER                  | Desktop     | [a98aedda05](https://linux-hardware.org/?probe=a98aedda05) | Sep 13, 2022 |
| Compal        | NCL60/61                    | Notebook    | [f1f5499af8](https://linux-hardware.org/?probe=f1f5499af8) | Sep 12, 2022 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [0937dcb89c](https://linux-hardware.org/?probe=0937dcb89c) | Sep 12, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [2eb979e980](https://linux-hardware.org/?probe=2eb979e980) | Sep 12, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [16a4aa3cd8](https://linux-hardware.org/?probe=16a4aa3cd8) | Sep 12, 2022 |
| Dell          | 0H8052                      | Desktop     | [1ade497706](https://linux-hardware.org/?probe=1ade497706) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Gigabyte      | EX58-UD3R                   | Desktop     | [e482e214bd](https://linux-hardware.org/?probe=e482e214bd) | Sep 12, 2022 |
| Shuttle       | XH310V2                     | Desktop     | [c99efae947](https://linux-hardware.org/?probe=c99efae947) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| MSI           | GP73 Leopard 8RE            | Notebook    | [21744558cb](https://linux-hardware.org/?probe=21744558cb) | Sep 12, 2022 |
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [58b48039ce](https://linux-hardware.org/?probe=58b48039ce) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| Intel         | D945GCNL AAD97184-106       | Desktop     | [a2bdc2d18c](https://linux-hardware.org/?probe=a2bdc2d18c) | Sep 11, 2022 |
| HP            | 304Bh                       | Desktop     | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5523f4050c](https://linux-hardware.org/?probe=5523f4050c) | Sep 11, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [b76fc41706](https://linux-hardware.org/?probe=b76fc41706) | Sep 11, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [5d0092ffc1](https://linux-hardware.org/?probe=5d0092ffc1) | Sep 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| HP            | Notebook                    | Notebook    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| Lenovo        | 3708 SDK0J40700 WIN 3258... | Desktop     | [4db3f9151e](https://linux-hardware.org/?probe=4db3f9151e) | Sep 11, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0225ec89d7](https://linux-hardware.org/?probe=0225ec89d7) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [6168b7089f](https://linux-hardware.org/?probe=6168b7089f) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| MSI           | 0A48                        | Desktop     | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [eff4400b7d](https://linux-hardware.org/?probe=eff4400b7d) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
| HP            | 3396                        | Desktop     | [964f32cccf](https://linux-hardware.org/?probe=964f32cccf) | Sep 10, 2022 |
| Dell          | 03NVJ6 A00                  | Desktop     | [ef8c1a9dee](https://linux-hardware.org/?probe=ef8c1a9dee) | Sep 10, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| ASRock        | G41M-VS3                    | Desktop     | [021bcda428](https://linux-hardware.org/?probe=021bcda428) | Sep 10, 2022 |
| Lenovo        | ThinkPad L420 7829H86       | Notebook    | [406535e915](https://linux-hardware.org/?probe=406535e915) | Sep 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Gigabyte      | Z68AP-D3                    | Desktop     | [1ac8cbcc47](https://linux-hardware.org/?probe=1ac8cbcc47) | Sep 10, 2022 |
| LG Electro... | U560-G.BG31P1               | Notebook    | [741c3eddbe](https://linux-hardware.org/?probe=741c3eddbe) | Sep 10, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [40c43aff10](https://linux-hardware.org/?probe=40c43aff10) | Sep 10, 2022 |
| Samsung       | SX60P                       | Notebook    | [1e0ea8e787](https://linux-hardware.org/?probe=1e0ea8e787) | Sep 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| Acer          | Aspire E1-572               | Notebook    | [1cfbfd9b91](https://linux-hardware.org/?probe=1cfbfd9b91) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| Dell          | 04075X A00                  | All in one  | [e2ff438b3c](https://linux-hardware.org/?probe=e2ff438b3c) | Sep 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Dell          | Latitude E4300              | Notebook    | [634c1467f8](https://linux-hardware.org/?probe=634c1467f8) | Sep 09, 2022 |
| Dell          | Latitude 3120               | Convertible | [6b2b6b7aa9](https://linux-hardware.org/?probe=6b2b6b7aa9) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [5c21c2acc6](https://linux-hardware.org/?probe=5c21c2acc6) | Sep 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [628d805267](https://linux-hardware.org/?probe=628d805267) | Sep 09, 2022 |
| Positivo      | H14BT58                     | Notebook    | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [2154b21ff3](https://linux-hardware.org/?probe=2154b21ff3) | Sep 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [ee7071f4e7](https://linux-hardware.org/?probe=ee7071f4e7) | Sep 08, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d13ff70895](https://linux-hardware.org/?probe=d13ff70895) | Sep 08, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [e3976254ee](https://linux-hardware.org/?probe=e3976254ee) | Sep 08, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [c9d50b8db9](https://linux-hardware.org/?probe=c9d50b8db9) | Sep 08, 2022 |
| Dell          | G5 5505                     | Notebook    | [e26e58afac](https://linux-hardware.org/?probe=e26e58afac) | Sep 08, 2022 |
| Intel         | D33217CK G76541-301         | Desktop     | [1f1e6e67ab](https://linux-hardware.org/?probe=1f1e6e67ab) | Sep 07, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Lenovo        | G580                        | Notebook    | [922ede2a50](https://linux-hardware.org/?probe=922ede2a50) | Sep 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [a6b07acfe5](https://linux-hardware.org/?probe=a6b07acfe5) | Sep 07, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [cf398ae303](https://linux-hardware.org/?probe=cf398ae303) | Sep 07, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [cca59cbb3c](https://linux-hardware.org/?probe=cca59cbb3c) | Sep 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E531 68856... | Notebook    | [498682ac13](https://linux-hardware.org/?probe=498682ac13) | Sep 06, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [01ab1f5015](https://linux-hardware.org/?probe=01ab1f5015) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| Sony          | VPCSB3X9E                   | Notebook    | [03bd901e4f](https://linux-hardware.org/?probe=03bd901e4f) | Sep 06, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [614d44ff70](https://linux-hardware.org/?probe=614d44ff70) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | Notebook    | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [78e0cb1ca2](https://linux-hardware.org/?probe=78e0cb1ca2) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Dell          | Latitude E4300              | Notebook    | [4589ef4489](https://linux-hardware.org/?probe=4589ef4489) | Sep 06, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [51b15f6d34](https://linux-hardware.org/?probe=51b15f6d34) | Sep 06, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | Notebook    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| ASUSTek       | ET2040I                     | Desktop     | [44ab433428](https://linux-hardware.org/?probe=44ab433428) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | Notebook    | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5263a99ed8](https://linux-hardware.org/?probe=5263a99ed8) | Sep 05, 2022 |
| HP            | 18E4                        | Desktop     | [2c113164fd](https://linux-hardware.org/?probe=2c113164fd) | Sep 05, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [b5e07ae97b](https://linux-hardware.org/?probe=b5e07ae97b) | Sep 05, 2022 |
| MSI           | B85M-E43 DASH               | Desktop     | [f52a53f4a7](https://linux-hardware.org/?probe=f52a53f4a7) | Sep 05, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [6098d39f63](https://linux-hardware.org/?probe=6098d39f63) | Sep 05, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a132b449e4](https://linux-hardware.org/?probe=a132b449e4) | Sep 05, 2022 |
| Dell          | Latitude E6220              | Notebook    | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Lenovo        | ThinkPad T530 2429W4Y       | Notebook    | [572b46f025](https://linux-hardware.org/?probe=572b46f025) | Sep 05, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [49bd6dbb99](https://linux-hardware.org/?probe=49bd6dbb99) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 20HD005GUS    | Notebook    | [af984a6d00](https://linux-hardware.org/?probe=af984a6d00) | Sep 05, 2022 |
| ASUSTek       | K53BY                       | Notebook    | [efbc2be1a7](https://linux-hardware.org/?probe=efbc2be1a7) | Sep 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [0e44b5b729](https://linux-hardware.org/?probe=0e44b5b729) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | Notebook    | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| HP            | 8076                        | Desktop     | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| HP            | OMEN by Laptop 17-cb1xxx    | Notebook    | [f0a6826f9d](https://linux-hardware.org/?probe=f0a6826f9d) | Sep 05, 2022 |
| Acer          | Aspire S5-371               | Notebook    | [ed31a97b57](https://linux-hardware.org/?probe=ed31a97b57) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| ASUSTek       | X45C                        | Notebook    | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [739d82814f](https://linux-hardware.org/?probe=739d82814f) | Sep 04, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [b36d7be7c1](https://linux-hardware.org/?probe=b36d7be7c1) | Sep 04, 2022 |
| HP            | 304Bh                       | Desktop     | [d395dd6c91](https://linux-hardware.org/?probe=d395dd6c91) | Sep 04, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dcfbebc2dd](https://linux-hardware.org/?probe=dcfbebc2dd) | Sep 04, 2022 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [fb64be85f1](https://linux-hardware.org/?probe=fb64be85f1) | Sep 04, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [113f737135](https://linux-hardware.org/?probe=113f737135) | Sep 04, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [96d17dc188](https://linux-hardware.org/?probe=96d17dc188) | Sep 04, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b5cc00787f](https://linux-hardware.org/?probe=b5cc00787f) | Sep 04, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [792cbc3418](https://linux-hardware.org/?probe=792cbc3418) | Sep 04, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [3ba0635033](https://linux-hardware.org/?probe=3ba0635033) | Sep 04, 2022 |
| MSI           | MS-168B                     | Notebook    | [a0a6645eef](https://linux-hardware.org/?probe=a0a6645eef) | Sep 04, 2022 |
| Jumper        | EZbook                      | Notebook    | [d67fae436c](https://linux-hardware.org/?probe=d67fae436c) | Sep 04, 2022 |
| HP            | 8767 A                      | Desktop     | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| Gigabyte      | B560 AORUS PRO AX           | Desktop     | [fbd2e39516](https://linux-hardware.org/?probe=fbd2e39516) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [adfeeb4193](https://linux-hardware.org/?probe=adfeeb4193) | Sep 04, 2022 |
| ECS           | H61H-G11/7.0                | Desktop     | [790b93cbee](https://linux-hardware.org/?probe=790b93cbee) | Sep 03, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [3d542c8484](https://linux-hardware.org/?probe=3d542c8484) | Sep 03, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [c2251f33ef](https://linux-hardware.org/?probe=c2251f33ef) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [34002dc814](https://linux-hardware.org/?probe=34002dc814) | Sep 02, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9e666e1530](https://linux-hardware.org/?probe=9e666e1530) | Sep 02, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [21183dcf00](https://linux-hardware.org/?probe=21183dcf00) | Sep 02, 2022 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Getac         | B300-X                      | Notebook    | [927b99c2e0](https://linux-hardware.org/?probe=927b99c2e0) | Sep 02, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [448c7a24e2](https://linux-hardware.org/?probe=448c7a24e2) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Notebook    | [8716f564d8](https://linux-hardware.org/?probe=8716f564d8) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [44a711d7ce](https://linux-hardware.org/?probe=44a711d7ce) | Sep 02, 2022 |
| Intel         | DH61WW AAG23116-204         | Desktop     | [3310a4c592](https://linux-hardware.org/?probe=3310a4c592) | Sep 02, 2022 |
| Dell          | Latitude 3120               | Convertible | [cb976a52d2](https://linux-hardware.org/?probe=cb976a52d2) | Sep 02, 2022 |
| HP            | 8053                        | Desktop     | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [b9502cc4a9](https://linux-hardware.org/?probe=b9502cc4a9) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d27c20dcf9](https://linux-hardware.org/?probe=d27c20dcf9) | Sep 01, 2022 |
| Packard Be... | DOT S                       | Notebook    | [b5b03f1cf7](https://linux-hardware.org/?probe=b5b03f1cf7) | Sep 01, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5ba20eb04b](https://linux-hardware.org/?probe=5ba20eb04b) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [b84d0acafb](https://linux-hardware.org/?probe=b84d0acafb) | Sep 01, 2022 |
| Acer          | Aspire 5715Z                | Notebook    | [82086ce1c6](https://linux-hardware.org/?probe=82086ce1c6) | Sep 01, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [c83430605e](https://linux-hardware.org/?probe=c83430605e) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| Lenovo        | ThinkCentre M58e 7408BA5    | Desktop     | [4384314f98](https://linux-hardware.org/?probe=4384314f98) | Sep 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [c9a801a4d2](https://linux-hardware.org/?probe=c9a801a4d2) | Sep 01, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7140822520](https://linux-hardware.org/?probe=7140822520) | Sep 01, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [d48b9efca4](https://linux-hardware.org/?probe=d48b9efca4) | Sep 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6566bc7d09](https://linux-hardware.org/?probe=6566bc7d09) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [ad6c7ea5ab](https://linux-hardware.org/?probe=ad6c7ea5ab) | Aug 31, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [710d1e9a9b](https://linux-hardware.org/?probe=710d1e9a9b) | Aug 31, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [120400698e](https://linux-hardware.org/?probe=120400698e) | Aug 31, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [b895a2ae7c](https://linux-hardware.org/?probe=b895a2ae7c) | Aug 31, 2022 |
| HP            | Notebook                    | Notebook    | [2ca7fbbfa9](https://linux-hardware.org/?probe=2ca7fbbfa9) | Aug 31, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [09ffe165d3](https://linux-hardware.org/?probe=09ffe165d3) | Aug 30, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| Dell          | Precision M6400             | Notebook    | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [a2940c76f5](https://linux-hardware.org/?probe=a2940c76f5) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [33aaa7baf4](https://linux-hardware.org/?probe=33aaa7baf4) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [0099ab3432](https://linux-hardware.org/?probe=0099ab3432) | Aug 29, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [536742931b](https://linux-hardware.org/?probe=536742931b) | Aug 29, 2022 |
| Dell          | Latitude 3300               | Notebook    | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | Desktop     | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [9336d821f8](https://linux-hardware.org/?probe=9336d821f8) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [99f7df96c2](https://linux-hardware.org/?probe=99f7df96c2) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| Dell          | Studio 1735                 | Notebook    | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [d8a4e4d954](https://linux-hardware.org/?probe=d8a4e4d954) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| HP            | 620                         | Notebook    | [b16c60f4cf](https://linux-hardware.org/?probe=b16c60f4cf) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Acer          | AO722                       | Notebook    | [377ad8686f](https://linux-hardware.org/?probe=377ad8686f) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [a18db0fafd](https://linux-hardware.org/?probe=a18db0fafd) | Aug 27, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [d6c013a669](https://linux-hardware.org/?probe=d6c013a669) | Aug 27, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [67712f11d9](https://linux-hardware.org/?probe=67712f11d9) | Aug 27, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [b97366daa0](https://linux-hardware.org/?probe=b97366daa0) | Aug 27, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [7bea18122c](https://linux-hardware.org/?probe=7bea18122c) | Aug 27, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [cf0bc232f5](https://linux-hardware.org/?probe=cf0bc232f5) | Aug 26, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [1b562e8768](https://linux-hardware.org/?probe=1b562e8768) | Aug 26, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [7e45cde899](https://linux-hardware.org/?probe=7e45cde899) | Aug 26, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| HP            | 8509                        | Desktop     | [0656e40cba](https://linux-hardware.org/?probe=0656e40cba) | Aug 26, 2022 |
| HP            | 15                          | Notebook    | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| Dell          | 06MC09 A00                  | Mini pc     | [71402e3c39](https://linux-hardware.org/?probe=71402e3c39) | Aug 26, 2022 |
| NCR           | Pocono                      | Desktop     | [c209b1443a](https://linux-hardware.org/?probe=c209b1443a) | Aug 25, 2022 |
| Dell          | 0RJ290                      | Desktop     | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [26572efe76](https://linux-hardware.org/?probe=26572efe76) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [82da7782ec](https://linux-hardware.org/?probe=82da7782ec) | Aug 25, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [bcd578a016](https://linux-hardware.org/?probe=bcd578a016) | Aug 25, 2022 |
| HP            | 829A                        | Mini pc     | [76cb57e98d](https://linux-hardware.org/?probe=76cb57e98d) | Aug 25, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | Notebook    | [a7c9d17455](https://linux-hardware.org/?probe=a7c9d17455) | Aug 25, 2022 |
| OEM           | A320                        | Desktop     | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
| HP            | Notebook                    | Notebook    | [0d4422145a](https://linux-hardware.org/?probe=0d4422145a) | Aug 25, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [b201192ebb](https://linux-hardware.org/?probe=b201192ebb) | Aug 25, 2022 |
| Dell          | Latitude E5510              | Notebook    | [c237161d31](https://linux-hardware.org/?probe=c237161d31) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d1cae6aca8](https://linux-hardware.org/?probe=d1cae6aca8) | Aug 24, 2022 |
| HP            | 21D0                        | Desktop     | [1bd58d519c](https://linux-hardware.org/?probe=1bd58d519c) | Aug 24, 2022 |
| Lenovo        | ThinkPad T420 4180F75       | Notebook    | [f4a6e9705d](https://linux-hardware.org/?probe=f4a6e9705d) | Aug 24, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [f20e68e820](https://linux-hardware.org/?probe=f20e68e820) | Aug 24, 2022 |
| Gigabyte      | Z68A-D3H-B3                 | Desktop     | [e75751c55b](https://linux-hardware.org/?probe=e75751c55b) | Aug 24, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [c824203d0a](https://linux-hardware.org/?probe=c824203d0a) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IAP 81A3      | Notebook    | [81b42d221d](https://linux-hardware.org/?probe=81b42d221d) | Aug 24, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d609bf3253](https://linux-hardware.org/?probe=d609bf3253) | Aug 24, 2022 |
| Dell          | 08HPGT A01                  | Desktop     | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| Supermicro    | X10SDV-8C+-LN2F             | Server      | [a4ec1f93e5](https://linux-hardware.org/?probe=a4ec1f93e5) | Aug 23, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| ICP / iEi     | B217 V1.0                   | Desktop     | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [5754d37860](https://linux-hardware.org/?probe=5754d37860) | Aug 23, 2022 |
| Dell          | Latitude E5470              | Notebook    | [4cf5f4680f](https://linux-hardware.org/?probe=4cf5f4680f) | Aug 23, 2022 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [1528da74f6](https://linux-hardware.org/?probe=1528da74f6) | Aug 22, 2022 |
| HP            | 8158 A01                    | Mini pc     | [443d203df8](https://linux-hardware.org/?probe=443d203df8) | Aug 22, 2022 |
| Google        | Galtic                      | Notebook    | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [53a4b425d3](https://linux-hardware.org/?probe=53a4b425d3) | Aug 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| Intel         | NUC11ATBC4 M53051-202       | Mini pc     | [6568854eef](https://linux-hardware.org/?probe=6568854eef) | Aug 22, 2022 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| HP            | 82B4                        | Desktop     | [e3200ae579](https://linux-hardware.org/?probe=e3200ae579) | Aug 22, 2022 |
| Dell          | Latitude 3300               | Notebook    | [e8b139ecad](https://linux-hardware.org/?probe=e8b139ecad) | Aug 22, 2022 |
| Dell          | Latitude 3310               | Notebook    | [dedda1b96c](https://linux-hardware.org/?probe=dedda1b96c) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [fa5f1121d5](https://linux-hardware.org/?probe=fa5f1121d5) | Aug 22, 2022 |
| Lenovo        | 36FB SDK0L77769 WIN 3423... | All in one  | [c65b675fc8](https://linux-hardware.org/?probe=c65b675fc8) | Aug 22, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [8c7493d7d1](https://linux-hardware.org/?probe=8c7493d7d1) | Aug 22, 2022 |
| Intel         | H61                         | Desktop     | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e064c453da](https://linux-hardware.org/?probe=e064c453da) | Aug 21, 2022 |
| Fujitsu       | LIFEBOOK UH552              | Notebook    | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | Notebook    | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [8de83c544f](https://linux-hardware.org/?probe=8de83c544f) | Aug 21, 2022 |
| HP            | 1998                        | Desktop     | [69b6b04268](https://linux-hardware.org/?probe=69b6b04268) | Aug 21, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | Notebook    | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| Acer          | Predator G9-791             | Notebook    | [782f581f0b](https://linux-hardware.org/?probe=782f581f0b) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [142e25352d](https://linux-hardware.org/?probe=142e25352d) | Aug 20, 2022 |
| Packard Be... | PT890-8237A                 | Desktop     | [36a4120390](https://linux-hardware.org/?probe=36a4120390) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| AZW           | MII-V                       | Desktop     | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| OEM           | Intel H81                   | Desktop     | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [84ed4c9d73](https://linux-hardware.org/?probe=84ed4c9d73) | Aug 20, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [ee75702cd5](https://linux-hardware.org/?probe=ee75702cd5) | Aug 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0aae35eb95](https://linux-hardware.org/?probe=0aae35eb95) | Aug 19, 2022 |
| Dell          | 0XHGV1 A01                  | Desktop     | [b05fac6451](https://linux-hardware.org/?probe=b05fac6451) | Aug 19, 2022 |
| HP            | 15                          | Notebook    | [d519e672ca](https://linux-hardware.org/?probe=d519e672ca) | Aug 19, 2022 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [803031cd3b](https://linux-hardware.org/?probe=803031cd3b) | Aug 19, 2022 |
| HP            | Pavilion dm4                | Notebook    | [46bb1c7064](https://linux-hardware.org/?probe=46bb1c7064) | Aug 19, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [74b0bedd54](https://linux-hardware.org/?probe=74b0bedd54) | Aug 19, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ac7fb69037](https://linux-hardware.org/?probe=ac7fb69037) | Aug 19, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [eb86fd2237](https://linux-hardware.org/?probe=eb86fd2237) | Aug 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c954da96ad](https://linux-hardware.org/?probe=c954da96ad) | Aug 18, 2022 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [d9f1c174b3](https://linux-hardware.org/?probe=d9f1c174b3) | Aug 18, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [870fcf0f3c](https://linux-hardware.org/?probe=870fcf0f3c) | Aug 18, 2022 |
| Acer          | Aspire 7750G                | Notebook    | [6110ab7d79](https://linux-hardware.org/?probe=6110ab7d79) | Aug 18, 2022 |
| Dell          | Latitude E5510              | Notebook    | [c7defb71d5](https://linux-hardware.org/?probe=c7defb71d5) | Aug 18, 2022 |
| Medion        | Akoya E6418 MD99620         | Notebook    | [6817b38103](https://linux-hardware.org/?probe=6817b38103) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a0a7a845e3](https://linux-hardware.org/?probe=a0a7a845e3) | Aug 18, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Toshiba       | dynabook T653/46JR          | Notebook    | [decfecaa20](https://linux-hardware.org/?probe=decfecaa20) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | Notebook    | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Acer          | MRS600M                     | Desktop     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [870d7102f5](https://linux-hardware.org/?probe=870d7102f5) | Aug 17, 2022 |
| Packard Be... | EasyNote TK37               | Notebook    | [996a14d9f4](https://linux-hardware.org/?probe=996a14d9f4) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [93b2d066d6](https://linux-hardware.org/?probe=93b2d066d6) | Aug 17, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [471659ffff](https://linux-hardware.org/?probe=471659ffff) | Aug 17, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [3ab7d6393c](https://linux-hardware.org/?probe=3ab7d6393c) | Aug 17, 2022 |
| Dell          | Latitude 3380               | Notebook    | [a99b3cef26](https://linux-hardware.org/?probe=a99b3cef26) | Aug 17, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [9bdceca056](https://linux-hardware.org/?probe=9bdceca056) | Aug 17, 2022 |
| ASUSTek       | N75SF                       | Notebook    | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| NEC Comput... | PC-LJ730MG6W                | Notebook    | [c0e6c7edb7](https://linux-hardware.org/?probe=c0e6c7edb7) | Aug 17, 2022 |
| Dell          | Latitude 3310               | Notebook    | [92f66bf3aa](https://linux-hardware.org/?probe=92f66bf3aa) | Aug 17, 2022 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [59080cc039](https://linux-hardware.org/?probe=59080cc039) | Aug 17, 2022 |
| ASUSTek       | Z550SA                      | Notebook    | [03ef043fd9](https://linux-hardware.org/?probe=03ef043fd9) | Aug 17, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [2b97e09efa](https://linux-hardware.org/?probe=2b97e09efa) | Aug 17, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [92c0a6fe2a](https://linux-hardware.org/?probe=92c0a6fe2a) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a880d764be](https://linux-hardware.org/?probe=a880d764be) | Aug 16, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [7b3d6b544c](https://linux-hardware.org/?probe=7b3d6b544c) | Aug 16, 2022 |
| Lenovo        | ThinkPad L412 0585A84       | Notebook    | [637fa23dca](https://linux-hardware.org/?probe=637fa23dca) | Aug 16, 2022 |
| Dell          | Latitude 3310               | Notebook    | [1694bfcea7](https://linux-hardware.org/?probe=1694bfcea7) | Aug 16, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [ec4014a549](https://linux-hardware.org/?probe=ec4014a549) | Aug 16, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [2a8e801b4e](https://linux-hardware.org/?probe=2a8e801b4e) | Aug 16, 2022 |
| Dell          | 0GM819                      | Desktop     | [f7745d3d3a](https://linux-hardware.org/?probe=f7745d3d3a) | Aug 16, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [b4757c5ff7](https://linux-hardware.org/?probe=b4757c5ff7) | Aug 16, 2022 |
| TUXEDO        | Book BA1510                 | Notebook    | [6d8040e80b](https://linux-hardware.org/?probe=6d8040e80b) | Aug 15, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [79f5c08bff](https://linux-hardware.org/?probe=79f5c08bff) | Aug 15, 2022 |
| Acer          | Aspire ES1-532G             | Notebook    | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6c31827147](https://linux-hardware.org/?probe=6c31827147) | Aug 15, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| HP            | 2AE2                        | Desktop     | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| HP            | Notebook                    | Notebook    | [975f3e38e3](https://linux-hardware.org/?probe=975f3e38e3) | Aug 15, 2022 |
| Dell          | 0C27VV A01                  | Desktop     | [04f75d45cb](https://linux-hardware.org/?probe=04f75d45cb) | Aug 15, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [4ba26713bc](https://linux-hardware.org/?probe=4ba26713bc) | Aug 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| HP            | Laptop 14-bs1xx             | Notebook    | [4b603b6b08](https://linux-hardware.org/?probe=4b603b6b08) | Aug 15, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [170b178361](https://linux-hardware.org/?probe=170b178361) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4b1440875b](https://linux-hardware.org/?probe=4b1440875b) | Aug 14, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [15ffff65c0](https://linux-hardware.org/?probe=15ffff65c0) | Aug 14, 2022 |
| HP            | ProBook 4330s               | Notebook    | [62ff6ffc08](https://linux-hardware.org/?probe=62ff6ffc08) | Aug 14, 2022 |
| HP            | 18E7                        | Desktop     | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [7c37c2a6d7](https://linux-hardware.org/?probe=7c37c2a6d7) | Aug 14, 2022 |
| Acer          | Aspire M5-581T              | Notebook    | [7efdb0e467](https://linux-hardware.org/?probe=7efdb0e467) | Aug 14, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [30146876c6](https://linux-hardware.org/?probe=30146876c6) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
| Acer          | Aspire 5680                 | Notebook    | [20c2c97a69](https://linux-hardware.org/?probe=20c2c97a69) | Aug 14, 2022 |
| Unknown       | 1.0                         | Desktop     | [35d076bae0](https://linux-hardware.org/?probe=35d076bae0) | Aug 14, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [4386fccad1](https://linux-hardware.org/?probe=4386fccad1) | Aug 14, 2022 |
| Acer          | Aspire VN7-571G             | Notebook    | [0d6dfdd6e0](https://linux-hardware.org/?probe=0d6dfdd6e0) | Aug 14, 2022 |
| HP            | Pavilion dv9500             | Notebook    | [fd3bd18049](https://linux-hardware.org/?probe=fd3bd18049) | Aug 14, 2022 |
| HP            | 829A                        | Mini pc     | [0e36f81a7b](https://linux-hardware.org/?probe=0e36f81a7b) | Aug 13, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ee169e47b3](https://linux-hardware.org/?probe=ee169e47b3) | Aug 13, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [83fcabac55](https://linux-hardware.org/?probe=83fcabac55) | Aug 13, 2022 |
| Dell          | Vostro 1520                 | Notebook    | [9dab88f3ee](https://linux-hardware.org/?probe=9dab88f3ee) | Aug 13, 2022 |
| Positivo      | EC10IS1                     | Notebook    | [b66cd42f99](https://linux-hardware.org/?probe=b66cd42f99) | Aug 13, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [4e57c20454](https://linux-hardware.org/?probe=4e57c20454) | Aug 13, 2022 |
| Lenovo        | ThinkCentre XXXX 739527G    | Desktop     | [ca5fe11e2c](https://linux-hardware.org/?probe=ca5fe11e2c) | Aug 13, 2022 |
| ASUSTek       | ROG STRIX B365-F GAMING     | Desktop     | [1ae946a847](https://linux-hardware.org/?probe=1ae946a847) | Aug 13, 2022 |
| HP            | Unknown                     | Notebook    | [7375604d06](https://linux-hardware.org/?probe=7375604d06) | Aug 13, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [32bf5bd8b8](https://linux-hardware.org/?probe=32bf5bd8b8) | Aug 13, 2022 |
| HP            | 1850                        | Desktop     | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [50b7221c5a](https://linux-hardware.org/?probe=50b7221c5a) | Aug 12, 2022 |
| Positivo      | Mobile                      | Notebook    | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Fujitsu       | LIFEBOOK S904               | Notebook    | [0e3107a650](https://linux-hardware.org/?probe=0e3107a650) | Aug 12, 2022 |
| ASUSTek       | K73BR                       | Notebook    | [67f5d3f176](https://linux-hardware.org/?probe=67f5d3f176) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | Notebook    | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| Dell          | Latitude 7420               | Notebook    | [26cd6bbb87](https://linux-hardware.org/?probe=26cd6bbb87) | Aug 12, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| Lenovo        | Unknown                     | Notebook    | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| ASRock        | Z97M Pro4                   | Desktop     | [245d189a61](https://linux-hardware.org/?probe=245d189a61) | Aug 11, 2022 |
| Gateway       | MT6723                      | Notebook    | [368de1c083](https://linux-hardware.org/?probe=368de1c083) | Aug 11, 2022 |
| Dell          | G5 5505                     | Notebook    | [cbbcb7c9a2](https://linux-hardware.org/?probe=cbbcb7c9a2) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [73bf30c596](https://linux-hardware.org/?probe=73bf30c596) | Aug 11, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c765f5b81c](https://linux-hardware.org/?probe=c765f5b81c) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| HP            | Pavilion dm3                | Notebook    | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| OpenMandriva 4.2    | 4557      | 49.15%  |
| OpenMandriva 4.3    | 3684      | 39.74%  |
| OpenMandriva 4.50   | 703       | 7.58%   |
| OpenMandriva 4.90   | 304       | 3.28%   |
| OpenMandriva 4.1    | 14        | 0.15%   |
| OpenMandriva 2014.0 | 4         | 0.04%   |
| OpenMandriva 4.0    | 2         | 0.02%   |
| OpenMandriva 3.0    | 2         | 0.02%   |
| OpenMandriva 4.0.1  | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| OpenMandriva | 9245      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002       | 4388      | 47.06%  |
| 5.16.7-desktop-1omv4003        | 3558      | 38.16%  |
| 5.12.4-desktop-1omv4050        | 367       | 3.94%   |
| 5.18.12-desktop-3omv4090       | 271       | 2.91%   |
| 5.11.12-desktop-1omv4002       | 188       | 2.02%   |
| 5.19.5-desktop-1omv4090        | 118       | 1.27%   |
| 5.14.7-desktop-1omv4050        | 103       | 1.1%    |
| 5.16.13-desktop-1omv4003       | 97        | 1.04%   |
| 5.19.12-desktop-2omv4090       | 24        | 0.26%   |
| 5.14.14-desktop-1omv4050       | 24        | 0.26%   |
| 5.12.7-desktop-1omv4003        | 22        | 0.24%   |
| 5.17.1-desktop-2omv4050        | 17        | 0.18%   |
| 5.5.12-desktop-1omv4001        | 12        | 0.13%   |
| 5.11.0-desktop-clang-1omv4002  | 10        | 0.11%   |
| 5.19.11-desktop-2omv4090       | 8         | 0.09%   |
| 5.19.1-desktop-1omv4090        | 6         | 0.06%   |
| 5.16.3-desktop-2omv4050        | 6         | 0.06%   |
| 5.18.13-desktop-1omv4090       | 5         | 0.05%   |
| 5.10.13-desktop-1omv4002       | 5         | 0.05%   |
| 5.18.9-desktop-gcc-1omv4090    | 4         | 0.04%   |
| 6.0.2-desktop-1omv4050         | 3         | 0.03%   |
| 5.19.0-desktop-1omv4090        | 3         | 0.03%   |
| 5.16.9-desktop-1omv4003        | 3         | 0.03%   |
| 5.16.5-desktop-2omv4003        | 3         | 0.03%   |
| 5.12.7-desktop-clang-1omv4003  | 3         | 0.03%   |
| 5.9.12-desktop-1omv4002        | 2         | 0.02%   |
| 5.5.0-desktop-1omv4001         | 2         | 0.02%   |
| 5.19.8-desktop-2omv4090        | 2         | 0.02%   |
| 5.19.3-desktop-1omv4090        | 2         | 0.02%   |
| 5.17.7-desktop-1omv4090        | 2         | 0.02%   |
| 5.17.1-desktop-clang-2omv4050  | 2         | 0.02%   |
| 5.16.0-desktop-1omv4050        | 2         | 0.02%   |
| 5.13.2-desktop-clang-1omv4050  | 2         | 0.02%   |
| 5.11.13-desktop-clang-1omv4050 | 2         | 0.02%   |
| 5.11.11-desktop-clang-1omv4050 | 2         | 0.02%   |
| 4.1.12-nrj-server-1omv         | 2         | 0.02%   |
| 6.0.2-desktop-1omv4090         | 1         | 0.01%   |
| 6.0.0-desktop-gcc-1omv4050     | 1         | 0.01%   |
| 6.0.0-desktop-1omv4090         | 1         | 0.01%   |
| 6.0.0-desktop-1omv4050         | 1         | 0.01%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.14 | 4388      | 47.06%  |
| 5.16.7  | 3560      | 38.18%  |
| 5.12.4  | 367       | 3.94%   |
| 5.18.12 | 271       | 2.91%   |
| 5.11.12 | 188       | 2.02%   |
| 5.19.5  | 118       | 1.27%   |
| 5.14.7  | 103       | 1.1%    |
| 5.16.13 | 98        | 1.05%   |
| 5.19.12 | 25        | 0.27%   |
| 5.12.7  | 25        | 0.27%   |
| 5.14.14 | 24        | 0.26%   |
| 5.17.1  | 19        | 0.2%    |
| 5.5.12  | 12        | 0.13%   |
| 5.11.0  | 12        | 0.13%   |
| 5.19.11 | 9         | 0.1%    |
| 5.19.1  | 6         | 0.06%   |
| 5.16.3  | 6         | 0.06%   |
| 5.18.13 | 5         | 0.05%   |
| 5.10.13 | 5         | 0.05%   |
| 6.0.2   | 4         | 0.04%   |
| 6.0.0   | 4         | 0.04%   |
| 5.18.9  | 4         | 0.04%   |
| 5.16.9  | 4         | 0.04%   |
| 5.16.5  | 4         | 0.04%   |
| 5.13.2  | 4         | 0.04%   |
| 5.19.0  | 3         | 0.03%   |
| 5.11.11 | 3         | 0.03%   |
| 5.9.12  | 2         | 0.02%   |
| 5.8.13  | 2         | 0.02%   |
| 5.5.0   | 2         | 0.02%   |
| 5.19.8  | 2         | 0.02%   |
| 5.19.3  | 2         | 0.02%   |
| 5.18.11 | 2         | 0.02%   |
| 5.17.7  | 2         | 0.02%   |
| 5.16.0  | 2         | 0.02%   |
| 5.12.12 | 2         | 0.02%   |
| 5.12.1  | 2         | 0.02%   |
| 5.11.13 | 2         | 0.02%   |
| 4.1.15  | 2         | 0.02%   |
| 4.1.12  | 2         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4399      | 47.19%  |
| 5.16    | 3675      | 39.43%  |
| 5.12    | 397       | 4.26%   |
| 5.18    | 283       | 3.04%   |
| 5.11    | 208       | 2.23%   |
| 5.19    | 166       | 1.78%   |
| 5.14    | 128       | 1.37%   |
| 5.17    | 21        | 0.23%   |
| 5.5     | 14        | 0.15%   |
| 6.0     | 8         | 0.09%   |
| 5.13    | 5         | 0.05%   |
| 4.1     | 4         | 0.04%   |
| 5.15    | 3         | 0.03%   |
| 5.9     | 2         | 0.02%   |
| 5.8     | 2         | 0.02%   |
| 5.1     | 2         | 0.02%   |
| 4.19    | 2         | 0.02%   |
| 5.3     | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 9243      | 99.98%  |
| aarch64 | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 9205      | 99.52%  |
| Unknown  | 17        | 0.18%   |
| LXQt     | 13        | 0.14%   |
| GNOME    | 6         | 0.06%   |
| KDE4     | 2         | 0.02%   |
| KDE      | 2         | 0.02%   |
| Cinnamon | 2         | 0.02%   |
| XFCE     | 1         | 0.01%   |
| Budgie   | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 9190      | 99.38%  |
| Wayland | 54        | 0.58%   |
| Unknown | 2         | 0.02%   |
| Tty     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 9233      | 99.86%  |
| Unknown | 5         | 0.05%   |
| GDM     | 4         | 0.04%   |
| LightDM | 2         | 0.02%   |
| KDM     | 2         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 5036      | 54.3%   |
| de_DE   | 765       | 8.25%   |
| ru_RU   | 522       | 5.63%   |
| fr_FR   | 497       | 5.36%   |
| pt_BR   | 381       | 4.11%   |
| pl_PL   | 336       | 3.62%   |
| it_IT   | 247       | 2.66%   |
| es_ES   | 213       | 2.3%    |
| cs_CZ   | 187       | 2.02%   |
| en_GB   | 173       | 1.87%   |
| es_AR   | 80        | 0.86%   |
| es_MX   | 75        | 0.81%   |
| de_AT   | 71        | 0.77%   |
| hu_HU   | 65        | 0.7%    |
| nl_NL   | 39        | 0.42%   |
| en_AU   | 38        | 0.41%   |
| fr_CA   | 34        | 0.37%   |
| en_IN   | 34        | 0.37%   |
| en_CA   | 33        | 0.36%   |
| es_CO   | 30        | 0.32%   |
| de_CH   | 29        | 0.31%   |
| pt_PT   | 28        | 0.3%    |
| fr_BE   | 28        | 0.3%    |
| ru_UA   | 26        | 0.28%   |
| es_CL   | 24        | 0.26%   |
| Unknown | 23        | 0.25%   |
| da_DK   | 21        | 0.23%   |
| tr_TR   | 20        | 0.22%   |
| nl_BE   | 19        | 0.2%    |
| ro_RO   | 18        | 0.19%   |
| es_VE   | 15        | 0.16%   |
| es_PE   | 14        | 0.15%   |
| fr_CH   | 12        | 0.13%   |
| nb_NO   | 11        | 0.12%   |
| uk_UA   | 9         | 0.1%    |
| en_ZA   | 9         | 0.1%    |
| en_HK   | 9         | 0.1%    |
| es_CR   | 8         | 0.09%   |
| it_CH   | 7         | 0.08%   |
| es_UY   | 7         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 4988      | 53.92%  |
| EFI  | 4263      | 46.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 7540      | 81.01%  |
| Ext4     | 1674      | 17.98%  |
| Btrfs    | 39        | 0.42%   |
| F2fs     | 18        | 0.19%   |
| Xfs      | 11        | 0.12%   |
| Unknown  | 8         | 0.09%   |
| Ext2     | 7         | 0.08%   |
| Ext3     | 6         | 0.06%   |
| Jfs      | 3         | 0.03%   |
| Reiserfs | 2         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 5696      | 61.49%  |
| MBR     | 3538      | 38.19%  |
| Unknown | 30        | 0.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5259      | 56.69%  |
| No        | 4018      | 43.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4760      | 51.43%  |
| Yes       | 4496      | 48.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 1657      | 17.92%  |
| Hewlett-Packard     | 1189      | 12.86%  |
| Dell                | 1120      | 12.11%  |
| Lenovo              | 1051      | 11.37%  |
| Gigabyte Technology | 814       | 8.8%    |
| Acer                | 601       | 6.5%    |
| MSI                 | 545       | 5.9%    |
| ASRock              | 422       | 4.56%   |
| Toshiba             | 220       | 2.38%   |
| Intel               | 185       | 2%      |
| Apple               | 124       | 1.34%   |
| Sony                | 120       | 1.3%    |
| Fujitsu             | 115       | 1.24%   |
| Samsung Electronics | 101       | 1.09%   |
| Medion              | 82        | 0.89%   |
| Biostar             | 58        | 0.63%   |
| Positivo            | 57        | 0.62%   |
| Foxconn             | 54        | 0.58%   |
| Pegatron            | 52        | 0.56%   |
| Unknown             | 52        | 0.56%   |
| Packard Bell        | 51        | 0.55%   |
| ECS                 | 33        | 0.36%   |
| HUAWEI              | 23        | 0.25%   |
| eMachines           | 23        | 0.25%   |
| Fujitsu Siemens     | 22        | 0.24%   |
| Philco              | 21        | 0.23%   |
| Notebook            | 19        | 0.21%   |
| TUXEDO              | 18        | 0.19%   |
| BESSTAR Tech        | 17        | 0.18%   |
| LG Electronics      | 16        | 0.17%   |
| Chuwi               | 16        | 0.17%   |
| Gateway             | 15        | 0.16%   |
| Alienware           | 14        | 0.15%   |
| Supermicro          | 13        | 0.14%   |
| Microsoft           | 13        | 0.14%   |
| Shuttle             | 12        | 0.13%   |
| AZW                 | 12        | 0.13%   |
| PCWare              | 11        | 0.12%   |
| ZOTAC               | 8         | 0.09%   |
| NEC Computers       | 8         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| ASUS UX31E                  | 101       | 1.09%   |
| ASUS All Series             | 93        | 1.01%   |
| Unknown                     | 84        | 0.91%   |
| Dell Latitude 3120          | 48        | 0.52%   |
| HP Notebook                 | 42        | 0.45%   |
| Dell OptiPlex 780           | 34        | 0.37%   |
| Dell Latitude 3190 2-in-1   | 34        | 0.37%   |
| Dell OptiPlex 7010          | 31        | 0.34%   |
| Dell Inspiron 3451          | 30        | 0.32%   |
| Dell Latitude 3310          | 29        | 0.31%   |
| Gigabyte H410M H V3         | 27        | 0.29%   |
| HP Pavilion g6              | 23        | 0.25%   |
| HP Pavilion dv6             | 20        | 0.22%   |
| ASUS SABERTOOTH Z77         | 20        | 0.22%   |
| ASUS PRIME A320M-K          | 20        | 0.22%   |
| Sony VGN-FZ31Z              | 19        | 0.21%   |
| Gigabyte 970A-DS3P          | 19        | 0.21%   |
| Dell Latitude E6430         | 19        | 0.21%   |
| MSI MS-7C37                 | 17        | 0.18%   |
| Intel H61                   | 17        | 0.18%   |
| HP EliteDesk 800 G1 SFF     | 17        | 0.18%   |
| HP Compaq Pro 6300 SFF      | 17        | 0.18%   |
| Gigabyte B450M DS3H         | 17        | 0.18%   |
| Dell OptiPlex 9020          | 17        | 0.18%   |
| MSI MS-7817                 | 16        | 0.17%   |
| MSI MS-7721                 | 16        | 0.17%   |
| Dell OptiPlex 790           | 16        | 0.17%   |
| HP Pavilion 15              | 15        | 0.16%   |
| Gigabyte A320M-S2H          | 15        | 0.16%   |
| Dell OptiPlex 3020          | 15        | 0.16%   |
| ASUS M5A78L-M/USB3          | 15        | 0.16%   |
| HP Compaq 8200 Elite SFF PC | 14        | 0.15%   |
| Dell Latitude E6410         | 14        | 0.15%   |
| Dell Latitude D630          | 14        | 0.15%   |
| ASUS TUF Gaming X570-PLUS   | 14        | 0.15%   |
| ASUS PRIME B450M-A          | 14        | 0.15%   |
| Medion E2292                | 13        | 0.14%   |
| Dell Latitude E6420         | 13        | 0.14%   |
| ASUS PRIME B450M-A II       | 13        | 0.14%   |
| Positivo Mobile             | 12        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 432       | 4.67%   |
| Dell Latitude         | 427       | 4.62%   |
| Lenovo ThinkPad       | 333       | 3.6%    |
| Lenovo IdeaPad        | 267       | 2.89%   |
| Dell OptiPlex         | 245       | 2.65%   |
| Dell Inspiron         | 231       | 2.5%    |
| HP Pavilion           | 205       | 2.22%   |
| HP Compaq             | 202       | 2.18%   |
| ASUS PRIME            | 180       | 1.95%   |
| Toshiba Satellite     | 174       | 1.88%   |
| HP Laptop             | 124       | 1.34%   |
| Lenovo ThinkCentre    | 115       | 1.24%   |
| ASUS UX31E            | 101       | 1.09%   |
| ASUS All              | 93        | 1.01%   |
| HP ProBook            | 91        | 0.98%   |
| HP EliteBook          | 86        | 0.93%   |
| ASUS VivoBook         | 86        | 0.93%   |
| ASUS ROG              | 86        | 0.93%   |
| Unknown               | 84        | 0.91%   |
| ASUS TUF              | 68        | 0.74%   |
| HP EliteDesk          | 59        | 0.64%   |
| Dell Vostro           | 59        | 0.64%   |
| Dell Precision        | 58        | 0.63%   |
| ASUS M5A78L-M         | 49        | 0.53%   |
| Fujitsu LIFEBOOK      | 48        | 0.52%   |
| Fujitsu ESPRIMO       | 48        | 0.52%   |
| HP ProDesk            | 47        | 0.51%   |
| Lenovo IdeaCentre     | 45        | 0.49%   |
| HP Notebook           | 42        | 0.45%   |
| Dell XPS              | 42        | 0.45%   |
| ASUS SABERTOOTH       | 35        | 0.38%   |
| Packard Bell EasyNote | 34        | 0.37%   |
| Gigabyte B450M        | 34        | 0.37%   |
| Gigabyte H410M        | 32        | 0.35%   |
| Acer Extensa          | 30        | 0.32%   |
| ASUS P8H61-M          | 29        | 0.31%   |
| Acer TravelMate       | 29        | 0.31%   |
| Gigabyte X570         | 28        | 0.3%    |
| Gigabyte B450         | 28        | 0.3%    |
| HP ENVY               | 25        | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 954       | 10.32%  |
| 2012    | 934       | 10.1%   |
| 2013    | 770       | 8.33%   |
| 2019    | 697       | 7.54%   |
| 2014    | 666       | 7.2%    |
| 2010    | 652       | 7.05%   |
| 2018    | 651       | 7.04%   |
| 2020    | 590       | 6.38%   |
| 2017    | 503       | 5.44%   |
| 2009    | 488       | 5.28%   |
| 2008    | 486       | 5.26%   |
| 2016    | 471       | 5.09%   |
| 2015    | 467       | 5.05%   |
| 2021    | 414       | 4.48%   |
| 2007    | 309       | 3.34%   |
| 2006    | 125       | 1.35%   |
| 2022    | 36        | 0.39%   |
| 2005    | 20        | 0.22%   |
| 2004    | 6         | 0.06%   |
| Unknown | 6         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 4395      | 47.54%  |
| Notebook       | 4367      | 47.24%  |
| Convertible    | 168       | 1.82%   |
| All in one     | 147       | 1.59%   |
| Mini pc        | 123       | 1.33%   |
| Tablet         | 27        | 0.29%   |
| Server         | 17        | 0.18%   |
| System on chip | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 9245      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 9235      | 99.89%  |
| Yes  | 10        | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 2683      | 28.99%  |
| 4.01-8.0        | 2444      | 26.41%  |
| 8.01-16.0       | 1685      | 18.21%  |
| 16.01-24.0      | 1294      | 13.98%  |
| 32.01-64.0      | 464       | 5.01%   |
| 1.01-2.0        | 351       | 3.79%   |
| 2.01-3.0        | 133       | 1.44%   |
| 24.01-32.0      | 94        | 1.02%   |
| 64.01-256.0     | 84        | 0.91%   |
| 0.51-1.0        | 18        | 0.19%   |
| More than 256.0 | 4         | 0.04%   |
| Unknown         | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 7102      | 76.42%  |
| 0.51-1.0   | 1268      | 13.64%  |
| 2.01-3.0   | 642       | 6.91%   |
| 0.01-0.5   | 176       | 1.89%   |
| 3.01-4.0   | 61        | 0.66%   |
| 4.01-8.0   | 30        | 0.32%   |
| 8.01-16.0  | 12        | 0.13%   |
| 16.01-24.0 | 1         | 0.01%   |
| Unknown    | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 5551      | 59.97%  |
| 2      | 2211      | 23.89%  |
| 3      | 748       | 8.08%   |
| 4      | 347       | 3.75%   |
| 0      | 161       | 1.74%   |
| 5      | 128       | 1.38%   |
| 6      | 53        | 0.57%   |
| 7      | 25        | 0.27%   |
| 8      | 17        | 0.18%   |
| 9      | 6         | 0.06%   |
| 12     | 4         | 0.04%   |
| 15     | 2         | 0.02%   |
| 18     | 1         | 0.01%   |
| 11     | 1         | 0.01%   |
| 10     | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5138      | 55.54%  |
| No        | 4113      | 44.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8517      | 92.13%  |
| No        | 728       | 7.87%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6225      | 67.33%  |
| No        | 3021      | 32.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4857      | 52.53%  |
| Yes       | 4389      | 47.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 1104      | 11.94%  |
| USA          | 1055      | 11.41%  |
| Russia       | 670       | 7.25%   |
| France       | 650       | 7.03%   |
| Brazil       | 631       | 6.82%   |
| Poland       | 519       | 5.61%   |
| Italy        | 404       | 4.37%   |
| Spain        | 306       | 3.31%   |
| UK           | 283       | 3.06%   |
| Netherlands  | 251       | 2.71%   |
| Canada       | 242       | 2.62%   |
| Czechia      | 226       | 2.44%   |
| Mexico       | 159       | 1.72%   |
| Australia    | 143       | 1.55%   |
| India        | 141       | 1.52%   |
| Ukraine      | 122       | 1.32%   |
| Argentina    | 109       | 1.18%   |
| Austria      | 107       | 1.16%   |
| Japan        | 104       | 1.12%   |
| Hungary      | 102       | 1.1%    |
| Portugal     | 96        | 1.04%   |
| Romania      | 85        | 0.92%   |
| Indonesia    | 84        | 0.91%   |
| Sweden       | 83        | 0.9%    |
| Belgium      | 81        | 0.88%   |
| Switzerland  | 79        | 0.85%   |
| Greece       | 62        | 0.67%   |
| Finland      | 58        | 0.63%   |
| Slovakia     | 54        | 0.58%   |
| Bulgaria     | 53        | 0.57%   |
| Turkey       | 50        | 0.54%   |
| Serbia       | 50        | 0.54%   |
| Colombia     | 49        | 0.53%   |
| China        | 49        | 0.53%   |
| Norway       | 40        | 0.43%   |
| Chile        | 37        | 0.4%    |
| Denmark      | 36        | 0.39%   |
| Belarus      | 35        | 0.38%   |
| South Africa | 34        | 0.37%   |
| Peru         | 33        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Schagen        | 137       | 1.48%   |
| Moscow         | 124       | 1.34%   |
| Prague         | 116       | 1.25%   |
| Paris          | 79        | 0.85%   |
| Warsaw         | 73        | 0.79%   |
| Sao Paulo      | 72        | 0.78%   |
| Berlin         | 71        | 0.77%   |
| St Petersburg  | 58        | 0.63%   |
| Vienna         | 53        | 0.57%   |
| Milan          | 53        | 0.57%   |
| Krakow         | 49        | 0.53%   |
| Munich         | 46        | 0.5%    |
| Mexico City    | 45        | 0.49%   |
| Rio de Janeiro | 42        | 0.45%   |
| Rome           | 41        | 0.44%   |
| Hamburg        | 34        | 0.37%   |
| Sydney         | 33        | 0.36%   |
| Madrid         | 30        | 0.32%   |
| Helsinki       | 30        | 0.32%   |
| Yekaterinburg  | 27        | 0.29%   |
| Wroclaw        | 25        | 0.27%   |
| Buenos Aires   | 25        | 0.27%   |
| Belgrade       | 25        | 0.27%   |
| Athens         | 25        | 0.27%   |
| Melbourne      | 24        | 0.26%   |
| Barcelona      | 24        | 0.26%   |
| Stuttgart      | 23        | 0.25%   |
| Porto Alegre   | 23        | 0.25%   |
| Lima           | 23        | 0.25%   |
| Kyiv           | 23        | 0.25%   |
| Krasnodar      | 23        | 0.25%   |
| Gonikoppal     | 22        | 0.24%   |
| Budapest       | 22        | 0.24%   |
| Montreal       | 21        | 0.23%   |
| Jakarta        | 21        | 0.23%   |
| Istanbul       | 20        | 0.22%   |
| Funchal        | 20        | 0.22%   |
| Dortmund       | 20        | 0.22%   |
| Brisbane       | 20        | 0.22%   |
| Poznan         | 19        | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2462      | 2950   | 18.78%  |
| Seagate             | 2223      | 2622   | 16.96%  |
| Samsung Electronics | 1599      | 1938   | 12.2%   |
| Toshiba             | 954       | 1025   | 7.28%   |
| Kingston            | 780       | 841    | 5.95%   |
| SanDisk             | 569       | 613    | 4.34%   |
| Hitachi             | 553       | 581    | 4.22%   |
| Crucial             | 545       | 628    | 4.16%   |
| Unknown             | 345       | 378    | 2.63%   |
| A-DATA Technology   | 286       | 306    | 2.18%   |
| HGST                | 218       | 238    | 1.66%   |
| SK hynix            | 210       | 215    | 1.6%    |
| Intel               | 178       | 197    | 1.36%   |
| China               | 134       | 143    | 1.02%   |
| Micron Technology   | 91        | 93     | 0.69%   |
| GOODRAM             | 90        | 97     | 0.69%   |
| PNY                 | 89        | 98     | 0.68%   |
| Intenso             | 87        | 92     | 0.66%   |
| Maxtor              | 76        | 86     | 0.58%   |
| SPCC                | 74        | 77     | 0.56%   |
| Patriot             | 74        | 78     | 0.56%   |
| Fujitsu             | 61        | 61     | 0.47%   |
| OCZ                 | 59        | 60     | 0.45%   |
| Apacer              | 59        | 63     | 0.45%   |
| Transcend           | 57        | 59     | 0.43%   |
| JMicron Technology  | 57        | 58     | 0.43%   |
| Phison              | 56        | 67     | 0.43%   |
| Apple               | 53        | 58     | 0.4%    |
| Unknown             | 53        | 54     | 0.4%    |
| LITEON              | 52        | 52     | 0.4%    |
| Corsair             | 49        | 51     | 0.37%   |
| KIOXIA              | 41        | 43     | 0.31%   |
| ASMT                | 41        | 44     | 0.31%   |
| Hewlett-Packard     | 38        | 43     | 0.29%   |
| Gigabyte Technology | 38        | 40     | 0.29%   |
| Netac               | 31        | 32     | 0.24%   |
| KingSpec            | 31        | 31     | 0.24%   |
| Silicon Motion      | 28        | 31     | 0.21%   |
| Team                | 26        | 28     | 0.2%    |
| Plextor             | 26        | 28     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 163       | 1.14%   |
| Seagate ST500DM002-1BD142 500GB     | 148       | 1.04%   |
| Seagate ST1000DM010-2EP102 1TB      | 115       | 0.8%    |
| Seagate ST500LT012-1DG142 500GB     | 111       | 0.78%   |
| SanDisk SSD U100 256GB              | 101       | 0.71%   |
| Samsung SSD 860 EVO 500GB           | 98        | 0.69%   |
| Kingston SA400S37120G 120GB SSD     | 95        | 0.66%   |
| Toshiba MQ01ABF050 500GB            | 93        | 0.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 91        | 0.64%   |
| Kingston SV300S37A120G 120GB SSD    | 85        | 0.59%   |
| Toshiba DT01ACA100 1TB              | 84        | 0.59%   |
| Kingston SA400S37480G 480GB SSD     | 82        | 0.57%   |
| Unknown SD/MMC/MS PRO 1TB           | 80        | 0.56%   |
| Seagate ST1000LM035-1RK172 1TB      | 80        | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB            | 78        | 0.55%   |
| Toshiba MQ01ABD100 1TB              | 77        | 0.54%   |
| Crucial CT240BX500SSD1 240GB        | 77        | 0.54%   |
| Samsung SSD 850 EVO 250GB           | 75        | 0.52%   |
| Crucial CT500MX500SSD1 500GB        | 72        | 0.5%    |
| Seagate ST2000DM008-2FR102 2TB      | 71        | 0.5%    |
| Samsung SSD 860 EVO 250GB           | 71        | 0.5%    |
| Toshiba DT01ACA050 500GB            | 68        | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 61        | 0.43%   |
| Samsung SSD 850 EVO 500GB           | 61        | 0.43%   |
| Seagate ST3500418AS 500GB           | 60        | 0.42%   |
| Seagate ST1000DM003-1ER162 1TB      | 57        | 0.4%    |
| Toshiba MQ04ABF100 1TB              | 55        | 0.38%   |
| Seagate ST9500325AS 500GB           | 55        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB         | 55        | 0.38%   |
| Unknown                             | 53        | 0.37%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 51        | 0.36%   |
| Toshiba HDWD110 1TB                 | 49        | 0.34%   |
| Samsung SSD 970 EVO Plus 500GB      | 49        | 0.34%   |
| HGST HTS721010A9E630 1TB            | 49        | 0.34%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 47        | 0.33%   |
| Crucial CT480BX500SSD1 480GB        | 47        | 0.33%   |
| Seagate ST1000DM003-1SB102 1TB      | 42        | 0.29%   |
| Seagate ST1000DM003-1CH162 1TB      | 42        | 0.29%   |
| Seagate ST3500413AS 500GB           | 41        | 0.29%   |
| Seagate Expansion 2TB               | 39        | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2195      | 2580   | 33.36%  |
| WDC                 | 2040      | 2397   | 31%     |
| Toshiba             | 843       | 903    | 12.81%  |
| Hitachi             | 553       | 581    | 8.4%    |
| Samsung Electronics | 374       | 414    | 5.68%   |
| HGST                | 218       | 238    | 3.31%   |
| Unknown             | 83        | 83     | 1.26%   |
| Maxtor              | 73        | 83     | 1.11%   |
| Fujitsu             | 60        | 60     | 0.91%   |
| Apple               | 29        | 29     | 0.44%   |
| SABRENT             | 17        | 20     | 0.26%   |
| WD MediaMax         | 8         | 9      | 0.12%   |
| Hewlett-Packard     | 7         | 7      | 0.11%   |
| ASMT                | 7         | 10     | 0.11%   |
| ASMedia             | 7         | 7      | 0.11%   |
| Intenso             | 6         | 6      | 0.09%   |
| IBM/Hitachi         | 6         | 6      | 0.09%   |
| USB3.0              | 4         | 4      | 0.06%   |
| Quantum             | 4         | 4      | 0.06%   |
| HPE                 | 4         | 4      | 0.06%   |
| Magnetic Data       | 3         | 3      | 0.05%   |
| JMicron Technology  | 3         | 3      | 0.05%   |
| ExcelStor           | 3         | 3      | 0.05%   |
| China               | 3         | 3      | 0.05%   |
| USB                 | 2         | 2      | 0.03%   |
| SAGE                | 2         | 2      | 0.03%   |
| MDT                 | 2         | 2      | 0.03%   |
| KESU                | 2         | 2      | 0.03%   |
| Inateck             | 2         | 2      | 0.03%   |
| HGST HTS            | 2         | 2      | 0.03%   |
| Unknown             | 2         | 2      | 0.03%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| TPH00800640GB       | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| SATAFIRM            | 1         | 1      | 0.02%   |
| RSH-339             | 1         | 1      | 0.02%   |
| RSH-319             | 1         | 1      | 0.02%   |
| QC-FT-D             | 1         | 1      | 0.02%   |
| Promise             | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 878       | 1012   | 18.46%  |
| Kingston            | 669       | 717    | 14.06%  |
| SanDisk             | 526       | 562    | 11.06%  |
| Crucial             | 474       | 542    | 9.96%   |
| WDC                 | 293       | 310    | 6.16%   |
| A-DATA Technology   | 236       | 248    | 4.96%   |
| China               | 131       | 140    | 2.75%   |
| GOODRAM             | 87        | 92     | 1.83%   |
| Intel               | 84        | 89     | 1.77%   |
| PNY                 | 80        | 87     | 1.68%   |
| Toshiba             | 79        | 82     | 1.66%   |
| Intenso             | 77        | 82     | 1.62%   |
| SK hynix            | 72        | 74     | 1.51%   |
| Patriot             | 67        | 71     | 1.41%   |
| Micron Technology   | 67        | 69     | 1.41%   |
| OCZ                 | 59        | 60     | 1.24%   |
| SPCC                | 57        | 59     | 1.2%    |
| Apacer              | 54        | 57     | 1.14%   |
| Transcend           | 50        | 51     | 1.05%   |
| LITEON              | 47        | 47     | 0.99%   |
| Unknown             | 33        | 33     | 0.69%   |
| KingSpec            | 31        | 31     | 0.65%   |
| ASMT                | 31        | 31     | 0.65%   |
| Netac               | 28        | 29     | 0.59%   |
| Corsair             | 28        | 29     | 0.59%   |
| Unknown             | 26        | 27     | 0.55%   |
| Team                | 24        | 25     | 0.5%    |
| Hewlett-Packard     | 23        | 25     | 0.48%   |
| LITEONIT            | 22        | 23     | 0.46%   |
| Plextor             | 21        | 23     | 0.44%   |
| Gigabyte Technology | 21        | 21     | 0.44%   |
| Apple               | 19        | 19     | 0.4%    |
| KingDian            | 16        | 17     | 0.34%   |
| Seagate             | 12        | 12     | 0.25%   |
| KingFast            | 12        | 13     | 0.25%   |
| Lexar               | 11        | 11     | 0.23%   |
| Leven               | 11        | 11     | 0.23%   |
| KIOXIA-EXCERIA      | 11        | 11     | 0.23%   |
| Colorful            | 11        | 11     | 0.23%   |
| Verbatim            | 9         | 9      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 5598      | 7489   | 48.29%  |
| SSD     | 4109      | 5136   | 35.44%  |
| NVMe    | 1506      | 1788   | 12.99%  |
| MMC     | 265       | 286    | 2.29%   |
| Unknown | 115       | 138    | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 8139      | 12168  | 78.15%  |
| NVMe | 1467      | 1730   | 14.09%  |
| SAS  | 544       | 653    | 5.22%   |
| MMC  | 265       | 286    | 2.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 6443      | 8266   | 64.15%  |
| 0.51-1.0   | 2580      | 3113   | 25.69%  |
| 1.01-2.0   | 650       | 778    | 6.47%   |
| 3.01-4.0   | 134       | 176    | 1.33%   |
| 2.01-3.0   | 129       | 157    | 1.28%   |
| 4.01-10.0  | 91        | 118    | 0.91%   |
| 10.01-20.0 | 17        | 17     | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 4996      | 53.67%  |
| 101-250        | 1234      | 13.26%  |
| Unknown        | 981       | 10.54%  |
| 251-500        | 820       | 8.81%   |
| 501-1000       | 409       | 4.39%   |
| 51-100         | 370       | 3.97%   |
| 21-50          | 316       | 3.39%   |
| 1001-2000      | 120       | 1.29%   |
| 2001-3000      | 35        | 0.38%   |
| More than 3000 | 28        | 0.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 7580      | 81.53%  |
| Unknown        | 981       | 10.55%  |
| 21-50          | 187       | 2.01%   |
| 101-250        | 179       | 1.93%   |
| 51-100         | 150       | 1.61%   |
| 251-500        | 105       | 1.13%   |
| 501-1000       | 66        | 0.71%   |
| 1001-2000      | 33        | 0.35%   |
| More than 3000 | 9         | 0.1%    |
| 2001-3000      | 6         | 0.06%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB              | 101       | 101    | 3.55%   |
| Seagate ST500DM002-1BD142 500GB     | 63        | 65     | 2.22%   |
| Seagate ST9500325AS 500GB           | 41        | 43     | 1.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 35        | 36     | 1.23%   |
| Seagate ST500LT012-1DG142 500GB     | 33        | 33     | 1.16%   |
| Seagate ST3500418AS 500GB           | 27        | 28     | 0.95%   |
| Toshiba MQ01ABF050 500GB            | 26        | 26     | 0.91%   |
| Seagate ST500LT012-9WS142 500GB     | 26        | 27     | 0.91%   |
| HGST HTS545050A7E680 500GB          | 25        | 25     | 0.88%   |
| Kingston SV300S37A120G 120GB SSD    | 24        | 24     | 0.84%   |
| Seagate ST9320325AS 320GB           | 21        | 21     | 0.74%   |
| HGST HTS541010A9E680 1TB            | 21        | 21     | 0.74%   |
| Hitachi HTS543232A7A384 320GB       | 17        | 17     | 0.6%    |
| WDC WD5000AAKX-001CA0 500GB         | 16        | 17     | 0.56%   |
| Toshiba MQ01ABD075 752GB            | 15        | 15     | 0.53%   |
| Toshiba DT01ACA100 1TB              | 15        | 15     | 0.53%   |
| Seagate ST1000LM035-1RK172 1TB      | 15        | 15     | 0.53%   |
| Hitachi HTS545050A7E380 500GB       | 15        | 15     | 0.53%   |
| Toshiba MQ01ABD100 1TB              | 14        | 14     | 0.49%   |
| HGST HTS721010A9E630 1TB            | 14        | 15     | 0.49%   |
| Crucial CT240M500SSD1 240GB         | 14        | 14     | 0.49%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 13        | 13     | 0.46%   |
| WDC WD10JPVX-22JC3T0 1TB            | 13        | 13     | 0.46%   |
| Toshiba MQ01ABD050 500GB            | 13        | 13     | 0.46%   |
| Toshiba DT01ACA050 500GB            | 13        | 13     | 0.46%   |
| Samsung Electronics HD322HJ 320GB   | 13        | 13     | 0.46%   |
| HGST HTS545050A7E380 500GB          | 13        | 13     | 0.46%   |
| Seagate ST500LM021-1KJ152 500GB     | 12        | 12     | 0.42%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 12        | 12     | 0.42%   |
| Seagate ST3500413AS 500GB           | 12        | 12     | 0.42%   |
| Seagate ST31000528AS 1TB            | 12        | 12     | 0.42%   |
| Seagate ST31000524AS 1TB            | 12        | 12     | 0.42%   |
| Hitachi HTS547550A9E384 500GB       | 12        | 13     | 0.42%   |
| Seagate ST1000DM010-2EP102 1TB      | 11        | 11     | 0.39%   |
| Seagate ST1000DM003-9YN162 1TB      | 11        | 11     | 0.39%   |
| Samsung Electronics HD161HJ 160GB   | 11        | 11     | 0.39%   |
| Hitachi HDS721050CLA362 500GB       | 11        | 12     | 0.39%   |
| HGST HTS725050A7E630 500GB          | 11        | 11     | 0.39%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 10        | 10     | 0.35%   |
| Seagate ST9250315AS 250GB           | 10        | 10     | 0.35%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 741       | 788    | 26.84%  |
| WDC                 | 647       | 708    | 23.43%  |
| Hitachi             | 277       | 289    | 10.03%  |
| Toshiba             | 235       | 237    | 8.51%   |
| Samsung Electronics | 223       | 235    | 8.08%   |
| SanDisk             | 147       | 147    | 5.32%   |
| HGST                | 103       | 104    | 3.73%   |
| Kingston            | 69        | 71     | 2.5%    |
| Maxtor              | 45        | 46     | 1.63%   |
| Crucial             | 42        | 43     | 1.52%   |
| A-DATA Technology   | 26        | 27     | 0.94%   |
| Intel               | 25        | 25     | 0.91%   |
| Fujitsu             | 24        | 24     | 0.87%   |
| SK hynix            | 17        | 18     | 0.62%   |
| China               | 16        | 16     | 0.58%   |
| Micron Technology   | 11        | 11     | 0.4%    |
| OCZ                 | 8         | 8      | 0.29%   |
| GOODRAM             | 7         | 7      | 0.25%   |
| SPCC                | 6         | 6      | 0.22%   |
| LITEON              | 6         | 6      | 0.22%   |
| ASMT                | 6         | 6      | 0.22%   |
| Corsair             | 5         | 5      | 0.18%   |
| Apple               | 5         | 5      | 0.18%   |
| IBM/Hitachi         | 4         | 4      | 0.14%   |
| Transcend           | 3         | 3      | 0.11%   |
| KingSpec            | 3         | 3      | 0.11%   |
| Intenso             | 3         | 3      | 0.11%   |
| Hewlett-Packard     | 3         | 3      | 0.11%   |
| Unknown             | 3         | 3      | 0.11%   |
| WD MediaMax         | 2         | 2      | 0.07%   |
| Plextor             | 2         | 2      | 0.07%   |
| Netac               | 2         | 2      | 0.07%   |
| LITEONIT            | 2         | 2      | 0.07%   |
| KingDian            | 2         | 2      | 0.07%   |
| HPE                 | 2         | 2      | 0.07%   |
| Dogfish             | 2         | 2      | 0.07%   |
| Colorful            | 2         | 2      | 0.07%   |
| ASMedia             | 2         | 2      | 0.07%   |
| Apacer              | 2         | 3      | 0.07%   |
| XPG                 | 1         | 1      | 0.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 741       | 788    | 33.04%  |
| WDC                 | 619       | 677    | 27.6%   |
| Hitachi             | 277       | 289    | 12.35%  |
| Toshiba             | 231       | 233    | 10.3%   |
| Samsung Electronics | 180       | 190    | 8.02%   |
| HGST                | 103       | 104    | 4.59%   |
| Maxtor              | 45        | 46     | 2.01%   |
| Fujitsu             | 24        | 24     | 1.07%   |
| IBM/Hitachi         | 4         | 4      | 0.18%   |
| Apple               | 4         | 4      | 0.18%   |
| WD MediaMax         | 2         | 2      | 0.09%   |
| HPE                 | 2         | 2      | 0.09%   |
| ASMedia             | 2         | 2      | 0.09%   |
| RSH-339             | 1         | 1      | 0.04%   |
| Quantum             | 1         | 1      | 0.04%   |
| Magnetic Data       | 1         | 1      | 0.04%   |
| Initio              | 1         | 1      | 0.04%   |
| IB                  | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |
| Unknown             | 1         | 1      | 0.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2084      | 2374   | 80.09%  |
| SSD     | 494       | 505    | 18.99%  |
| NVMe    | 23        | 23     | 0.88%   |
| Unknown | 1         | 1      | 0.04%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Apple HDD HTS541010A9E662 1TB         | 4         | 4      | 5.41%   |
| Samsung Electronics HD103SJ 1TB       | 3         | 3      | 4.05%   |
| WDC WD800JD-00LSA0 80GB               | 2         | 2      | 2.7%    |
| WDC WD3200BEVT-11ZCT0 320GB           | 2         | 2      | 2.7%    |
| WDC WD2500BEVS-22UST0 250GB           | 2         | 2      | 2.7%    |
| WDC WD20EZRX-00D8PB0 2TB              | 2         | 2      | 2.7%    |
| Seagate ST3500418AS 500GB             | 2         | 3      | 2.7%    |
| Seagate ST3250318AS 250GB             | 2         | 2      | 2.7%    |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 2.7%    |
| Crucial CT500P2SSD8 500GB             | 2         | 2      | 2.7%    |
| WDC WD800JD-75MSA3 80GB               | 1         | 1      | 1.35%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB      | 1         | 1      | 1.35%   |
| WDC WD5000LPLX-75ZNTT0 500GB          | 1         | 1      | 1.35%   |
| WDC WD5000BPVT-60HXZT1 500GB          | 1         | 1      | 1.35%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 1.35%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 1.35%   |
| WDC WD3200AAJS-60Z0A0 320GB           | 1         | 1      | 1.35%   |
| WDC WD2500BEVT-60ZCT1 250GB           | 1         | 1      | 1.35%   |
| WDC WD20EARS-00MVWB0 2TB              | 1         | 1      | 1.35%   |
| WDC WD1600YS-23SHB0 160GB             | 1         | 1      | 1.35%   |
| WDC WD1600BEVT-75A23T0 160GB          | 1         | 1      | 1.35%   |
| WDC WD10JPVX-60JC3T0 1TB              | 1         | 1      | 1.35%   |
| WDC WD10JPVT-75A1YT0 1TB              | 1         | 1      | 1.35%   |
| WDC WD10EALX-759BA1 1TB               | 1         | 1      | 1.35%   |
| TPH00800640GB 640GB                   | 1         | 1      | 1.35%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 1.35%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.35%   |
| Toshiba MK3265GSXN 320GB              | 1         | 1      | 1.35%   |
| Toshiba MK3259GSXP 320GB              | 1         | 1      | 1.35%   |
| Toshiba MK3256GSY 320GB               | 1         | 1      | 1.35%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 1.35%   |
| Seagate STM3250318AS 250GB            | 1         | 1      | 1.35%   |
| Seagate STM31000528AS 1TB             | 1         | 1      | 1.35%   |
| Seagate ST980811AS 80GB               | 1         | 1      | 1.35%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 1.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 1.35%   |
| Seagate ST500DM002-1BD142 500GB       | 1         | 1      | 1.35%   |
| Seagate ST3320418AS 320GB             | 1         | 1      | 1.35%   |
| Seagate ST3160215A 160GB              | 1         | 1      | 1.35%   |
| Seagate ST31000528AS 1TB              | 1         | 1      | 1.35%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 22     | 29.73%  |
| Seagate             | 13        | 14     | 17.57%  |
| Samsung Electronics | 13        | 13     | 17.57%  |
| Hitachi             | 6         | 6      | 8.11%   |
| Toshiba             | 5         | 5      | 6.76%   |
| Apple               | 5         | 5      | 6.76%   |
| Crucial             | 2         | 2      | 2.7%    |
| TPH00800640GB       | 1         | 1      | 1.35%   |
| SK hynix            | 1         | 1      | 1.35%   |
| Maxtor              | 1         | 1      | 1.35%   |
| Kingston            | 1         | 1      | 1.35%   |
| Intel               | 1         | 1      | 1.35%   |
| HGST                | 1         | 1      | 1.35%   |
| GOODRAM             | 1         | 1      | 1.35%   |
| External            | 1         | 1      | 1.35%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 7032      | 10711  | 66.5%   |
| Malfunc  | 2548      | 2903   | 24.09%  |
| Detected | 922       | 1148   | 8.72%   |
| Failed   | 73        | 75     | 0.69%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6569      | 59.99%  |
| AMD                              | 2056      | 18.78%  |
| Samsung Electronics              | 465       | 4.25%   |
| SanDisk                          | 243       | 2.22%   |
| Nvidia                           | 215       | 1.96%   |
| JMicron Technology               | 177       | 1.62%   |
| ASMedia Technology               | 169       | 1.54%   |
| Marvell Technology Group         | 151       | 1.38%   |
| Phison Electronics               | 137       | 1.25%   |
| SK hynix                         | 127       | 1.16%   |
| Kingston Technology Company      | 121       | 1.11%   |
| Micron/Crucial Technology        | 76        | 0.69%   |
| Silicon Motion                   | 65        | 0.59%   |
| VIA Technologies                 | 55        | 0.5%    |
| KIOXIA                           | 45        | 0.41%   |
| ADATA Technology                 | 44        | 0.4%    |
| Toshiba America Info Systems     | 37        | 0.34%   |
| Micron Technology                | 31        | 0.28%   |
| Realtek Semiconductor            | 25        | 0.23%   |
| Solid State Storage Technology   | 23        | 0.21%   |
| Union Memory (Shenzhen)          | 16        | 0.15%   |
| Seagate Technology               | 14        | 0.13%   |
| Silicon Image                    | 13        | 0.12%   |
| Broadcom / LSI                   | 10        | 0.09%   |
| Lite-On Technology               | 9         | 0.08%   |
| Silicon Integrated Systems [SiS] | 8         | 0.07%   |
| LSI Logic / Symbios Logic        | 8         | 0.07%   |
| Integrated Technology Express    | 6         | 0.05%   |
| Apple                            | 5         | 0.05%   |
| Adaptec                          | 5         | 0.05%   |
| Lite-On IT Corp. / Plextor       | 4         | 0.04%   |
| Biwin Storage Technology         | 4         | 0.04%   |
| Shenzhen Longsys Electronics     | 3         | 0.03%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.03%   |
| Yangtze Memory Technologies      | 2         | 0.02%   |
| Promise Technology               | 2         | 0.02%   |
| OCZ Technology Group             | 2         | 0.02%   |
| Lenovo                           | 2         | 0.02%   |
| Unknown                          | 1         | 0.01%   |
| Hewlett-Packard                  | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1235      | 9.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 488       | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 479       | 3.63%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 414       | 3.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 405       | 3.07%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 339       | 2.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 329       | 2.49%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 298       | 2.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 280       | 2.12%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 278       | 2.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 267       | 2.02%   |
| AMD 400 Series Chipset SATA Controller                                                  | 253       | 1.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 229       | 1.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 222       | 1.68%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 222       | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 208       | 1.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 203       | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 196       | 1.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 188       | 1.42%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 187       | 1.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 185       | 1.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 168       | 1.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 164       | 1.24%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 159       | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 158       | 1.2%    |
| Intel SATA Controller [RAID mode]                                                       | 152       | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 151       | 1.14%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 144       | 1.09%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 143       | 1.08%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 135       | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 128       | 0.97%   |
| Samsung NVMe SSD Controller 980                                                         | 119       | 0.9%    |
| AMD FCH SATA Controller D                                                               | 105       | 0.8%    |
| AMD 500 Series Chipset SATA Controller                                                  | 103       | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 102       | 0.77%   |
| Nvidia MCP61 SATA Controller                                                            | 92        | 0.7%    |
| Nvidia MCP61 IDE                                                                        | 85        | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 85        | 0.64%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 84        | 0.64%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 83        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 7250      | 64.6%   |
| IDE  | 1943      | 17.31%  |
| NVMe | 1462      | 13.03%  |
| RAID | 543       | 4.84%   |
| SAS  | 15        | 0.13%   |
| SCSI | 10        | 0.09%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 6891      | 74.54%  |
| AMD    | 2353      | 25.45%  |
| ARM    | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 101       | 1.09%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 79        | 0.85%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 74        | 0.8%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 65        | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 63        | 0.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 60        | 0.65%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 60        | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 56        | 0.61%   |
| AMD Ryzen 5 3600 6-Core Processor             | 56        | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 55        | 0.59%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 54        | 0.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 54        | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 52        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 51        | 0.55%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 49        | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 48        | 0.52%   |
| AMD FX-8350 Eight-Core Processor              | 48        | 0.52%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 47        | 0.51%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 47        | 0.51%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 46        | 0.5%    |
| Intel Core i3-2100 CPU @ 3.10GHz              | 44        | 0.48%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 44        | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 42        | 0.45%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 42        | 0.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 41        | 0.44%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 41        | 0.44%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 41        | 0.44%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 39        | 0.42%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 38        | 0.41%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 38        | 0.41%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 37        | 0.4%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 37        | 0.4%    |
| Intel Core i5-2410M CPU @ 2.30GHz             | 37        | 0.4%    |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 36        | 0.39%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 36        | 0.39%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 35        | 0.38%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 35        | 0.38%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 35        | 0.38%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 35        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 2004      | 21.68%  |
| Intel Core i7           | 1099      | 11.89%  |
| Intel Core i3           | 1054      | 11.4%   |
| Intel Celeron           | 652       | 7.05%   |
| Intel Core 2 Duo        | 630       | 6.81%   |
| AMD Ryzen 5             | 407       | 4.4%    |
| Intel Pentium           | 385       | 4.16%   |
| AMD Ryzen 7             | 250       | 2.7%    |
| AMD FX                  | 199       | 2.15%   |
| Other                   | 191       | 2.07%   |
| Intel Pentium Dual-Core | 191       | 2.07%   |
| Intel Core 2 Quad       | 140       | 1.51%   |
| AMD Ryzen 3             | 139       | 1.5%    |
| Intel Xeon              | 130       | 1.41%   |
| AMD A8                  | 129       | 1.4%    |
| Intel Pentium Silver    | 116       | 1.25%   |
| AMD A6                  | 103       | 1.11%   |
| AMD A4                  | 95        | 1.03%   |
| AMD A10                 | 91        | 0.98%   |
| AMD Athlon II X2        | 79        | 0.85%   |
| Intel Pentium Dual      | 78        | 0.84%   |
| Intel Core 2            | 76        | 0.82%   |
| AMD Phenom II X4        | 71        | 0.77%   |
| AMD E                   | 70        | 0.76%   |
| AMD Athlon 64 X2        | 70        | 0.76%   |
| AMD Athlon              | 70        | 0.76%   |
| AMD Ryzen 9             | 64        | 0.69%   |
| Intel Atom              | 61        | 0.66%   |
| AMD E1                  | 60        | 0.65%   |
| AMD E2                  | 39        | 0.42%   |
| AMD Athlon II X4        | 33        | 0.36%   |
| AMD Phenom              | 27        | 0.29%   |
| Intel Core i9           | 26        | 0.28%   |
| AMD Phenom II X6        | 25        | 0.27%   |
| Intel Pentium Gold      | 22        | 0.24%   |
| Intel Pentium 4         | 22        | 0.24%   |
| AMD Sempron             | 22        | 0.24%   |
| AMD C-60                | 22        | 0.24%   |
| Intel Pentium D         | 20        | 0.22%   |
| Intel Genuine           | 19        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4997      | 54.04%  |
| 4       | 2866      | 31%     |
| 6       | 621       | 6.72%   |
| 8       | 342       | 3.7%    |
| 1       | 236       | 2.55%   |
| 3       | 80        | 0.87%   |
| 12      | 52        | 0.56%   |
| 16      | 26        | 0.28%   |
| 10      | 14        | 0.15%   |
| 14      | 4         | 0.04%   |
| 24      | 3         | 0.03%   |
| 32      | 2         | 0.02%   |
| 20      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 9222      | 99.74%  |
| 2      | 24        | 0.26%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4958      | 53.63%  |
| 1       | 4271      | 46.2%   |
| 8       | 9         | 0.1%    |
| 4       | 5         | 0.05%   |
| 6       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 9239      | 99.94%  |
| Unknown        | 6         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 898       | 9.71%   |
| 0x306a9    | 788       | 8.52%   |
| 0x1067a    | 641       | 6.93%   |
| 0x306c3    | 605       | 6.54%   |
| Unknown    | 285       | 3.08%   |
| 0x20655    | 254       | 2.75%   |
| 0x506e3    | 208       | 2.25%   |
| 0x40651    | 200       | 2.16%   |
| 0x6fd      | 196       | 2.12%   |
| 0x406e3    | 191       | 2.06%   |
| 0x906ea    | 189       | 2.04%   |
| 0x806e9    | 175       | 1.89%   |
| 0x306d4    | 174       | 1.88%   |
| 0x08701021 | 157       | 1.7%    |
| 0x10676    | 153       | 1.65%   |
| 0x906e9    | 149       | 1.61%   |
| 0x08108109 | 147       | 1.59%   |
| 0x30678    | 145       | 1.57%   |
| 0x806ea    | 143       | 1.55%   |
| 0x06001119 | 120       | 1.3%    |
| 0x806ec    | 115       | 1.24%   |
| 0x706a1    | 112       | 1.21%   |
| 0x010000c8 | 109       | 1.18%   |
| 0x6fb      | 97        | 1.05%   |
| 0x20652    | 93        | 1.01%   |
| 0x406c4    | 87        | 0.94%   |
| 0x706a8    | 85        | 0.92%   |
| 0x0800820d | 84        | 0.91%   |
| 0x506c9    | 79        | 0.85%   |
| 0x706e5    | 71        | 0.77%   |
| 0x07030105 | 70        | 0.76%   |
| 0x08101016 | 69        | 0.75%   |
| 0xa0653    | 67        | 0.72%   |
| 0x906c0    | 66        | 0.71%   |
| 0x06006705 | 66        | 0.71%   |
| 0xa0655    | 64        | 0.69%   |
| 0x106e5    | 64        | 0.69%   |
| 0x06000822 | 59        | 0.64%   |
| 0x806c1    | 58        | 0.63%   |
| 0x06003106 | 58        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 930       | 10.06%  |
| KabyLake         | 912       | 9.86%   |
| Haswell          | 835       | 9.03%   |
| Penryn           | 825       | 8.92%   |
| IvyBridge        | 808       | 8.74%   |
| Skylake          | 422       | 4.56%   |
| Core             | 414       | 4.48%   |
| Westmere         | 363       | 3.93%   |
| K10              | 317       | 3.43%   |
| Zen+             | 313       | 3.39%   |
| Piledriver       | 302       | 3.27%   |
| Zen 2            | 287       | 3.1%    |
| Silvermont       | 287       | 3.1%    |
| Zen              | 223       | 2.41%   |
| Goldmont plus    | 197       | 2.13%   |
| Broadwell        | 187       | 2.02%   |
| CometLake        | 166       | 1.8%    |
| Excavator        | 139       | 1.5%    |
| Bobcat           | 136       | 1.47%   |
| K8 Hammer        | 123       | 1.33%   |
| Zen 3            | 121       | 1.31%   |
| Puma             | 108       | 1.17%   |
| Nehalem          | 100       | 1.08%   |
| IceLake          | 100       | 1.08%   |
| Goldmont         | 84        | 0.91%   |
| Steamroller      | 74        | 0.8%    |
| Tremont          | 66        | 0.71%   |
| TigerLake        | 63        | 0.68%   |
| Jaguar           | 60        | 0.65%   |
| Unknown          | 60        | 0.65%   |
| Bonnell          | 50        | 0.54%   |
| NetBurst         | 48        | 0.52%   |
| K10 Llano        | 48        | 0.52%   |
| Bulldozer        | 46        | 0.5%    |
| Alderlake Hybrid | 16        | 0.17%   |
| K8 & K10 hybrid  | 15        | 0.16%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5061      | 49.67%  |
| Nvidia                           | 2584      | 25.36%  |
| AMD                              | 2520      | 24.73%  |
| Matrox Electronics Systems       | 8         | 0.08%   |
| VIA Technologies                 | 6         | 0.06%   |
| Silicon Integrated Systems [SiS] | 6         | 0.06%   |
| ATI Technologies                 | 2         | 0.02%   |
| ASPEED Technology                | 2         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 719       | 6.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 408       | 3.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 257       | 2.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 242       | 2.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 238       | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 218       | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 200       | 1.91%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 173       | 1.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 167       | 1.59%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 164       | 1.57%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 163       | 1.56%   |
| Intel HD Graphics 620                                                                    | 155       | 1.48%   |
| Intel HD Graphics 5500                                                                   | 152       | 1.45%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 137       | 1.31%   |
| Intel HD Graphics 530                                                                    | 133       | 1.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 132       | 1.26%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 129       | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 120       | 1.15%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 120       | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 119       | 1.14%   |
| Intel UHD Graphics 620                                                                   | 114       | 1.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 107       | 1.02%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 105       | 1%      |
| Nvidia GT218 [GeForce 210]                                                               | 104       | 0.99%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 91        | 0.87%   |
| AMD Renoir                                                                               | 91        | 0.87%   |
| Intel HD Graphics 630                                                                    | 90        | 0.86%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 87        | 0.83%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 82        | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 77        | 0.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 75        | 0.72%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 74        | 0.71%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 68        | 0.65%   |
| Intel HD Graphics 500                                                                    | 68        | 0.65%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 66        | 0.63%   |
| Intel JasperLake [UHD Graphics]                                                          | 66        | 0.63%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 63        | 0.6%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 60        | 0.57%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 59        | 0.56%   |
| AMD Cezanne                                                                              | 57        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 4148      | 44.86%  |
| 1 x AMD                 | 2158      | 23.34%  |
| 1 x Nvidia              | 1860      | 20.12%  |
| Intel + Nvidia          | 654       | 7.07%   |
| Intel + AMD             | 162       | 1.75%   |
| 2 x AMD                 | 149       | 1.61%   |
| AMD + Nvidia            | 51        | 0.55%   |
| 2 x Intel               | 24        | 0.26%   |
| 2 x Nvidia              | 16        | 0.17%   |
| 1 x VIA                 | 6         | 0.06%   |
| 1 x SiS                 | 6         | 0.06%   |
| 1 x Matrox              | 5         | 0.05%   |
| Nvidia + Matrox         | 2         | 0.02%   |
| 1 x ASPEED              | 2         | 0.02%   |
| Other                   | 1         | 0.01%   |
| 3 x AMD                 | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 9048      | 97.84%  |
| Unknown     | 189       | 2.04%   |
| Proprietary | 11        | 0.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4400      | 47.58%  |
| 0.01-0.5   | 1428      | 15.44%  |
| 1.01-2.0   | 1290      | 13.95%  |
| 0.51-1.0   | 1144      | 12.37%  |
| 3.01-4.0   | 459       | 4.96%   |
| 7.01-8.0   | 276       | 2.98%   |
| 5.01-6.0   | 146       | 1.58%   |
| 2.01-3.0   | 64        | 0.69%   |
| 8.01-16.0  | 36        | 0.39%   |
| 16.01-24.0 | 4         | 0.04%   |
| 4.01-5.0   | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1376      | 14.85%  |
| AU Optronics            | 981       | 10.59%  |
| LG Display              | 785       | 8.47%   |
| BOE                     | 646       | 6.97%   |
| Chimei Innolux          | 632       | 6.82%   |
| Goldstar                | 596       | 6.43%   |
| Dell                    | 444       | 4.79%   |
| Hewlett-Packard         | 434       | 4.68%   |
| Acer                    | 371       | 4%      |
| Philips                 | 310       | 3.35%   |
| AOC                     | 263       | 2.84%   |
| BenQ                    | 221       | 2.39%   |
| Ancor Communications    | 197       | 2.13%   |
| Lenovo                  | 195       | 2.1%    |
| Chi Mei Optoelectronics | 175       | 1.89%   |
| CPT                     | 119       | 1.28%   |
| ViewSonic               | 115       | 1.24%   |
| Iiyama                  | 108       | 1.17%   |
| Apple                   | 107       | 1.15%   |
| Eizo                    | 81        | 0.87%   |
| Sony                    | 69        | 0.74%   |
| Sharp                   | 65        | 0.7%    |
| LG Philips              | 65        | 0.7%    |
| ASUSTek Computer        | 56        | 0.6%    |
| Fujitsu Siemens         | 49        | 0.53%   |
| InfoVision              | 48        | 0.52%   |
| NEC Computers           | 44        | 0.47%   |
| PANDA                   | 43        | 0.46%   |
| HannStar                | 38        | 0.41%   |
| Toshiba                 | 35        | 0.38%   |
| Panasonic               | 24        | 0.26%   |
| Vizio                   | 23        | 0.25%   |
| Vestel Elektronik       | 22        | 0.24%   |
| Unknown                 | 21        | 0.23%   |
| Sceptre Tech            | 21        | 0.23%   |
| Medion                  | 21        | 0.23%   |
| ___                     | 14        | 0.15%   |
| MStar                   | 14        | 0.15%   |
| InnoLux Display         | 14        | 0.15%   |
| Hitachi                 | 14        | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 101       | 1.08%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 54        | 0.58%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 40        | 0.43%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 39        | 0.42%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 39        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 38        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 37        | 0.4%    |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 36        | 0.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 35        | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 33        | 0.35%   |
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 30        | 0.32%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 30        | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 29        | 0.31%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 27        | 0.29%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 25        | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 24        | 0.26%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch     | 23        | 0.25%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 22        | 0.24%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 22        | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 21        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 21        | 0.22%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 21        | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 20        | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 20        | 0.21%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.21%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 20        | 0.21%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 20        | 0.21%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.21%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 20        | 0.21%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 19        | 0.2%    |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 19        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 17        | 0.18%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 17        | 0.18%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 17        | 0.18%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 17        | 0.18%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 17        | 0.18%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 17        | 0.18%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 16        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3512      | 38.51%  |
| 1366x768 (WXGA)    | 2399      | 26.3%   |
| 1600x900 (HD+)     | 592       | 6.49%   |
| 3840x2160 (4K)     | 431       | 4.73%   |
| 1280x1024 (SXGA)   | 430       | 4.71%   |
| 1680x1050 (WSXGA+) | 344       | 3.77%   |
| 1440x900 (WXGA+)   | 310       | 3.4%    |
| 1280x800 (WXGA)    | 279       | 3.06%   |
| 2560x1440 (QHD)    | 239       | 2.62%   |
| 1920x1200 (WUXGA)  | 150       | 1.64%   |
| 1360x768           | 94        | 1.03%   |
| 2560x1080          | 46        | 0.5%    |
| 3440x1440          | 41        | 0.45%   |
| 1920x540           | 32        | 0.35%   |
| 1024x768 (XGA)     | 32        | 0.35%   |
| 2560x1600          | 20        | 0.22%   |
| 1600x1200          | 20        | 0.22%   |
| 3200x1800 (QHD+)   | 15        | 0.16%   |
| 1024x600           | 15        | 0.16%   |
| 1280x720 (HD)      | 13        | 0.14%   |
| 2160x1440          | 10        | 0.11%   |
| 2880x1800          | 9         | 0.1%    |
| 1280x960           | 9         | 0.1%    |
| 1680x945           | 8         | 0.09%   |
| 3840x1080          | 7         | 0.08%   |
| 2736x1824          | 7         | 0.08%   |
| 2288x1287          | 6         | 0.07%   |
| 2256x1504          | 6         | 0.07%   |
| 2048x1152          | 6         | 0.07%   |
| 1920x1280          | 5         | 0.05%   |
| 3840x2400          | 4         | 0.04%   |
| 1400x1050          | 4         | 0.04%   |
| 1280x768           | 4         | 0.04%   |
| 3840x1600          | 3         | 0.03%   |
| 800x1280           | 2         | 0.02%   |
| 3456x2160          | 2         | 0.02%   |
| 1152x864           | 2         | 0.02%   |
| 3840x1200          | 1         | 0.01%   |
| 3840x1100          | 1         | 0.01%   |
| 3300x2200          | 1         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2193      | 23.64%  |
| 13      | 782       | 8.43%   |
| 23      | 758       | 8.17%   |
| 21      | 713       | 7.69%   |
| 17      | 666       | 7.18%   |
| 27      | 606       | 6.53%   |
| 24      | 553       | 5.96%   |
| 14      | 518       | 5.58%   |
| 19      | 417       | 4.49%   |
| 18      | 324       | 3.49%   |
| 22      | 236       | 2.54%   |
| 31      | 234       | 2.52%   |
| 20      | 197       | 2.12%   |
| 11      | 197       | 2.12%   |
| 12      | 169       | 1.82%   |
| 34      | 83        | 0.89%   |
| 84      | 77        | 0.83%   |
| Unknown | 60        | 0.65%   |
| 32      | 57        | 0.61%   |
| 72      | 47        | 0.51%   |
| 54      | 45        | 0.49%   |
| 26      | 37        | 0.4%    |
| 25      | 35        | 0.38%   |
| 40      | 24        | 0.26%   |
| 10      | 24        | 0.26%   |
| 16      | 23        | 0.25%   |
| 52      | 22        | 0.24%   |
| 65      | 19        | 0.2%    |
| 28      | 14        | 0.15%   |
| 46      | 13        | 0.14%   |
| 37      | 13        | 0.14%   |
| 48      | 11        | 0.12%   |
| 39      | 11        | 0.12%   |
| 33      | 11        | 0.12%   |
| 74      | 9         | 0.1%    |
| 29      | 9         | 0.1%    |
| 60      | 8         | 0.09%   |
| 49      | 8         | 0.09%   |
| 42      | 8         | 0.09%   |
| 43      | 7         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3239      | 35.25%  |
| 501-600        | 1847      | 20.1%   |
| 401-500        | 1673      | 18.21%  |
| 201-300        | 778       | 8.47%   |
| 351-400        | 767       | 8.35%   |
| 601-700        | 317       | 3.45%   |
| 701-800        | 152       | 1.65%   |
| 1001-1500      | 142       | 1.55%   |
| 1501-2000      | 135       | 1.47%   |
| Unknown        | 60        | 0.65%   |
| 801-900        | 54        | 0.59%   |
| 901-1000       | 16        | 0.17%   |
| More than 2000 | 6         | 0.07%   |
| 1-100          | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 7018      | 79.19%  |
| 16/10   | 1139      | 12.85%  |
| 5/4     | 417       | 4.71%   |
| 4/3     | 89        | 1%      |
| 21/9    | 85        | 0.96%   |
| 3/2     | 76        | 0.86%   |
| 6/5     | 10        | 0.11%   |
| 32/9    | 10        | 0.11%   |
| 1.00    | 6         | 0.07%   |
| Unknown | 4         | 0.05%   |
| 1.96    | 2         | 0.02%   |
| 0.67    | 2         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.01    | 1         | 0.01%   |
| 0.75    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2174      | 23.57%  |
| 201-250        | 1832      | 19.87%  |
| 81-90          | 953       | 10.33%  |
| 151-200        | 874       | 9.48%   |
| 301-350        | 636       | 6.9%    |
| 141-150        | 482       | 5.23%   |
| 351-500        | 394       | 4.27%   |
| 121-130        | 368       | 3.99%   |
| 71-80          | 353       | 3.83%   |
| More than 1000 | 254       | 2.75%   |
| 251-300        | 229       | 2.48%   |
| 51-60          | 199       | 2.16%   |
| 61-70          | 155       | 1.68%   |
| 501-1000       | 105       | 1.14%   |
| 131-140        | 83        | 0.9%    |
| Unknown        | 60        | 0.65%   |
| 111-120        | 26        | 0.28%   |
| 41-50          | 23        | 0.25%   |
| 91-100         | 20        | 0.22%   |
| 1-40           | 2         | 0.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 3811      | 42.02%  |
| 101-120       | 3003      | 33.11%  |
| 121-160       | 1645      | 18.14%  |
| 161-240       | 266       | 2.93%   |
| 1-50          | 235       | 2.59%   |
| Unknown       | 60        | 0.66%   |
| More than 240 | 50        | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8461      | 91.49%  |
| 2     | 655       | 7.08%   |
| 0     | 93        | 1.01%   |
| 3     | 31        | 0.34%   |
| 4     | 4         | 0.04%   |
| 6     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 5360      | 39.6%   |
| Intel                             | 3573      | 26.39%  |
| Qualcomm Atheros                  | 2021      | 14.93%  |
| Broadcom                          | 669       | 4.94%   |
| Marvell Technology Group          | 207       | 1.53%   |
| Ralink                            | 187       | 1.38%   |
| Ralink Technology                 | 178       | 1.31%   |
| Nvidia                            | 171       | 1.26%   |
| Broadcom Limited                  | 170       | 1.26%   |
| Samsung Electronics               | 132       | 0.98%   |
| TP-Link                           | 97        | 0.72%   |
| Huawei Technologies               | 64        | 0.47%   |
| Qualcomm Atheros Communications   | 54        | 0.4%    |
| JMicron Technology                | 52        | 0.38%   |
| MediaTek                          | 48        | 0.35%   |
| Dell                              | 44        | 0.33%   |
| D-Link                            | 36        | 0.27%   |
| Ericsson Business Mobile Networks | 34        | 0.25%   |
| D-Link System                     | 34        | 0.25%   |
| NetGear                           | 25        | 0.18%   |
| ASIX Electronics                  | 25        | 0.18%   |
| VIA Technologies                  | 24        | 0.18%   |
| Motorola PCS                      | 21        | 0.16%   |
| Xiaomi                            | 19        | 0.14%   |
| Microsoft                         | 18        | 0.13%   |
| Aquantia                          | 18        | 0.13%   |
| Sierra Wireless                   | 17        | 0.13%   |
| ASUSTek Computer                  | 17        | 0.13%   |
| ZTE WCDMA Technologies MSM        | 14        | 0.1%    |
| Linksys                           | 13        | 0.1%    |
| Hewlett-Packard                   | 13        | 0.1%    |
| Belkin Components                 | 13        | 0.1%    |
| DisplayLink                       | 12        | 0.09%   |
| Edimax Technology                 | 11        | 0.08%   |
| 3Com                              | 10        | 0.07%   |
| IMC Networks                      | 9         | 0.07%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.06%   |
| Qualcomm                          | 8         | 0.06%   |
| AVM                               | 7         | 0.05%   |
| OPPO Electronics                  | 6         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3892      | 24.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 768       | 4.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 398       | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 331       | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 300       | 1.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 262       | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 256       | 1.64%   |
| Intel Wi-Fi 6 AX200                                               | 199       | 1.28%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 198       | 1.27%   |
| Intel Wireless 7265                                               | 168       | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 163       | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 154       | 0.99%   |
| Intel Wireless 8265 / 8275                                        | 151       | 0.97%   |
| Intel I211 Gigabit Network Connection                             | 148       | 0.95%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 140       | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 132       | 0.85%   |
| Intel Wireless 7260                                               | 128       | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 126       | 0.81%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 125       | 0.8%    |
| Intel Ethernet Connection (2) I219-V                              | 120       | 0.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 115       | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 115       | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 114       | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 109       | 0.7%    |
| Intel Wireless 3165                                               | 107       | 0.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 106       | 0.68%   |
| Intel Wireless 8260                                               | 102       | 0.65%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 98        | 0.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 96        | 0.62%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 95        | 0.61%   |
| Nvidia MCP61 Ethernet                                             | 80        | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 79        | 0.51%   |
| Intel WiFi Link 5100                                              | 79        | 0.51%   |
| Intel Wireless 3160                                               | 78        | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 77        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                   | 77        | 0.49%   |
| Intel 82577LM Gigabit Network Connection                          | 73        | 0.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 72        | 0.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 72        | 0.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 69        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2413      | 37.54%  |
| Qualcomm Atheros                | 1606      | 24.98%  |
| Realtek Semiconductor           | 1187      | 18.47%  |
| Broadcom                        | 381       | 5.93%   |
| Ralink                          | 187       | 2.91%   |
| Ralink Technology               | 178       | 2.77%   |
| TP-Link                         | 74        | 1.15%   |
| Broadcom Limited                | 69        | 1.07%   |
| Qualcomm Atheros Communications | 54        | 0.84%   |
| MediaTek                        | 37        | 0.58%   |
| D-Link                          | 32        | 0.5%    |
| Dell                            | 25        | 0.39%   |
| NetGear                         | 21        | 0.33%   |
| Sierra Wireless                 | 17        | 0.26%   |
| Microsoft                       | 17        | 0.26%   |
| ASUSTek Computer                | 17        | 0.26%   |
| D-Link System                   | 16        | 0.25%   |
| Belkin Components               | 13        | 0.2%    |
| Linksys                         | 12        | 0.19%   |
| Edimax Technology               | 11        | 0.17%   |
| Marvell Technology Group        | 9         | 0.14%   |
| IMC Networks                    | 9         | 0.14%   |
| AVM                             | 7         | 0.11%   |
| Wilocity                        | 4         | 0.06%   |
| Sitecom Europe                  | 4         | 0.06%   |
| ZyDAS                           | 3         | 0.05%   |
| Mercucys                        | 3         | 0.05%   |
| Hewlett-Packard                 | 3         | 0.05%   |
| Guillemot                       | 3         | 0.05%   |
| Wacom                           | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| Philips (or NXP)                | 2         | 0.03%   |
| Chu Yuen Enterprise             | 2         | 0.03%   |
| ZyXEL Communications            | 1         | 0.02%   |
| TRENDnet                        | 1         | 0.02%   |
| Senao                           | 1         | 0.02%   |
| PLANEX                          | 1         | 0.02%   |
| Logitec                         | 1         | 0.02%   |
| FIBOCOM                         | 1         | 0.02%   |
| BUFFALO                         | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 331       | 5.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 300       | 4.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 262       | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 256       | 3.97%   |
| Intel Wi-Fi 6 AX200                                                     | 199       | 3.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 198       | 3.07%   |
| Intel Wireless 7265                                                     | 168       | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 163       | 2.53%   |
| Intel Wireless 8265 / 8275                                              | 151       | 2.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 140       | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 132       | 2.05%   |
| Intel Wireless 7260                                                     | 128       | 1.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 115       | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 114       | 1.77%   |
| Intel Wireless 3165                                                     | 107       | 1.66%   |
| Intel Wireless 8260                                                     | 102       | 1.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 96        | 1.49%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 95        | 1.47%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 79        | 1.23%   |
| Intel WiFi Link 5100                                                    | 79        | 1.23%   |
| Intel Wireless 3160                                                     | 78        | 1.21%   |
| Ralink MT7601U Wireless Adapter                                         | 77        | 1.19%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 72        | 1.12%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 72        | 1.12%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 69        | 1.07%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 66        | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 64        | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 64        | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 64        | 0.99%   |
| Intel Wireless-AC 9260                                                  | 62        | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 61        | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 61        | 0.95%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 59        | 0.92%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 58        | 0.9%    |
| Intel Centrino Ultimate-N 6300                                          | 56        | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 54        | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 52        | 0.81%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 51        | 0.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 51        | 0.79%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 50        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4955      | 55.72%  |
| Intel                             | 1971      | 22.17%  |
| Qualcomm Atheros                  | 619       | 6.96%   |
| Broadcom                          | 371       | 4.17%   |
| Marvell Technology Group          | 198       | 2.23%   |
| Nvidia                            | 170       | 1.91%   |
| Samsung Electronics               | 132       | 1.48%   |
| Broadcom Limited                  | 103       | 1.16%   |
| Huawei Technologies               | 57        | 0.64%   |
| JMicron Technology                | 52        | 0.58%   |
| ASIX Electronics                  | 25        | 0.28%   |
| TP-Link                           | 24        | 0.27%   |
| VIA Technologies                  | 22        | 0.25%   |
| Xiaomi                            | 19        | 0.21%   |
| D-Link System                     | 18        | 0.2%    |
| Aquantia                          | 18        | 0.2%    |
| ZTE WCDMA Technologies MSM        | 13        | 0.15%   |
| Motorola PCS                      | 13        | 0.15%   |
| DisplayLink                       | 12        | 0.13%   |
| MediaTek                          | 11        | 0.12%   |
| 3Com                              | 10        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 8         | 0.09%   |
| Qualcomm                          | 8         | 0.09%   |
| OPPO Electronics                  | 6         | 0.07%   |
| T & A Mobile Phones               | 4         | 0.04%   |
| OnePlus                           | 4         | 0.04%   |
| NetGear                           | 4         | 0.04%   |
| ICS Advent                        | 4         | 0.04%   |
| Hewlett-Packard                   | 4         | 0.04%   |
| Google                            | 4         | 0.04%   |
| D-Link                            | 4         | 0.04%   |
| HMD Global                        | 3         | 0.03%   |
| Apple                             | 3         | 0.03%   |
| Sundance Technology Inc / IC Plus | 2         | 0.02%   |
| Spreadtrum Communications         | 2         | 0.02%   |
| Lenovo                            | 2         | 0.02%   |
| HTC (High Tech Computer)          | 2         | 0.02%   |
| vivo                              | 1         | 0.01%   |
| Sitecom Europe                    | 1         | 0.01%   |
| Netchip Technology                | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 3892      | 43.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 768       | 8.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 398       | 4.41%   |
| Intel Ethernet Connection I217-LM                                 | 154       | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 148       | 1.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 126       | 1.4%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 125       | 1.38%   |
| Intel Ethernet Connection (2) I219-V                              | 120       | 1.33%   |
| Intel 82579V Gigabit Network Connection                           | 115       | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 109       | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 106       | 1.17%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 98        | 1.09%   |
| Nvidia MCP61 Ethernet                                             | 80        | 0.89%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 77        | 0.85%   |
| Intel 82577LM Gigabit Network Connection                          | 73        | 0.81%   |
| Intel 82567LM Gigabit Network Connection                          | 65        | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 63        | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 58        | 0.64%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 55        | 0.61%   |
| Intel Ethernet Connection (7) I219-V                              | 55        | 0.61%   |
| Intel Ethernet Controller I225-V                                  | 53        | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 50        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 50        | 0.55%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 48        | 0.53%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 45        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 44        | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 43        | 0.48%   |
| Intel Ethernet Connection I218-LM                                 | 42        | 0.47%   |
| Huawei E353/E3131                                                 | 42        | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 39        | 0.43%   |
| Intel Ethernet Connection I219-LM                                 | 39        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 38        | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 38        | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 35        | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 33        | 0.37%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 33        | 0.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 32        | 0.35%   |
| Intel 82574L Gigabit Network Connection                           | 31        | 0.34%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 30        | 0.33%   |
| Intel Ethernet Connection (2) I218-V                              | 29        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 8515      | 57.37%  |
| WiFi     | 6227      | 41.95%  |
| Modem    | 83        | 0.56%   |
| Unknown  | 18        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 5262      | 58.02%  |
| WiFi     | 3808      | 41.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4824      | 52.17%  |
| 1     | 4214      | 45.57%  |
| 3     | 125       | 1.35%   |
| 0     | 70        | 0.76%   |
| 4     | 11        | 0.12%   |
| 5     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 6918      | 74.76%  |
| Yes     | 2335      | 25.23%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1673      | 37.91%  |
| Qualcomm Atheros Communications | 467       | 10.58%  |
| Realtek Semiconductor           | 453       | 10.27%  |
| Cambridge Silicon Radio         | 323       | 7.32%   |
| Broadcom                        | 312       | 7.07%   |
| Lite-On Technology              | 233       | 5.28%   |
| IMC Networks                    | 190       | 4.31%   |
| Foxconn / Hon Hai               | 135       | 3.06%   |
| Apple                           | 117       | 2.65%   |
| Dell                            | 99        | 2.24%   |
| ASUSTek Computer                | 83        | 1.88%   |
| Toshiba                         | 73        | 1.65%   |
| Hewlett-Packard                 | 63        | 1.43%   |
| Ralink                          | 46        | 1.04%   |
| Realtek                         | 18        | 0.41%   |
| Foxconn International           | 15        | 0.34%   |
| Alps Electric                   | 14        | 0.32%   |
| Ralink Technology               | 13        | 0.29%   |
| Chicony Electronics             | 11        | 0.25%   |
| Marvell Semiconductor           | 10        | 0.23%   |
| MediaTek                        | 9         | 0.2%    |
| Askey Computer                  | 8         | 0.18%   |
| Integrated System Solution      | 7         | 0.16%   |
| Belkin Components               | 6         | 0.14%   |
| Taiyo Yuden                     | 4         | 0.09%   |
| Fujitsu                         | 4         | 0.09%   |
| Unknown                         | 3         | 0.07%   |
| TP-Link                         | 3         | 0.07%   |
| Primax Electronics              | 3         | 0.07%   |
| Micro Star International        | 3         | 0.07%   |
| Edimax Technology               | 3         | 0.07%   |
| Dynex                           | 3         | 0.07%   |
| Unknown                         | 3         | 0.07%   |
| USI                             | 1         | 0.02%   |
| SINO WEALTH                     | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| i.Tech Dynamic Limited          | 1         | 0.02%   |
| D-Link System                   | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 763       | 17.29%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 323       | 7.32%   |
| Realtek Bluetooth Radio                                                             | 269       | 6.1%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 229       | 5.19%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 215       | 4.87%   |
| Intel AX200 Bluetooth                                                               | 192       | 4.35%   |
| Intel AX201 Bluetooth                                                               | 173       | 3.92%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 125       | 2.83%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 114       | 2.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 86        | 1.95%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 80        | 1.81%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 77        | 1.74%   |
| IMC Networks Bluetooth Radio                                                        | 75        | 1.7%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 69        | 1.56%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 61        | 1.38%   |
| IMC Networks Bluetooth Device                                                       | 60        | 1.36%   |
| Lite-On Bluetooth Device                                                            | 56        | 1.27%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 56        | 1.27%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 55        | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 53        | 1.2%    |
| Ralink RT3290 Bluetooth                                                             | 46        | 1.04%   |
| Apple Bluetooth Host Controller                                                     | 46        | 1.04%   |
| Dell DW375 Bluetooth Module                                                         | 45        | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 44        | 1%      |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 43        | 0.97%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 39        | 0.88%   |
| Apple Bluetooth USB Host Controller                                                 | 38        | 0.86%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 35        | 0.79%   |
| Realtek RTL8723B Bluetooth                                                          | 31        | 0.7%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 31        | 0.7%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 30        | 0.68%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 29        | 0.66%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 28        | 0.63%   |
| Intel AX210 Bluetooth                                                               | 27        | 0.61%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 26        | 0.59%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 26        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 24        | 0.54%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 23        | 0.52%   |
| Broadcom BCM2045 Bluetooth                                                          | 23        | 0.52%   |
| Toshiba Bluetooth Device                                                            | 22        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 6713      | 54.73%  |
| AMD                                             | 2766      | 22.55%  |
| Nvidia                                          | 2023      | 16.49%  |
| C-Media Electronics                             | 164       | 1.34%   |
| Creative Labs                                   | 123       | 1%      |
| Logitech                                        | 61        | 0.5%    |
| Texas Instruments                               | 37        | 0.3%    |
| JMTek                                           | 32        | 0.26%   |
| Creative Technology                             | 28        | 0.23%   |
| VIA Technologies                                | 24        | 0.2%    |
| Generalplus Technology                          | 22        | 0.18%   |
| ASUSTek Computer                                | 18        | 0.15%   |
| Razer USA                                       | 12        | 0.1%    |
| Tenx Technology                                 | 10        | 0.08%   |
| GN Netcom                                       | 10        | 0.08%   |
| Realtek Semiconductor                           | 9         | 0.07%   |
| Kingston Technology                             | 9         | 0.07%   |
| Focusrite-Novation                              | 9         | 0.07%   |
| Silicon Integrated Systems [SiS]                | 8         | 0.07%   |
| XMOS                                            | 6         | 0.05%   |
| Thesycon Systemsoftware & Consulting            | 6         | 0.05%   |
| Samson Technologies                             | 6         | 0.05%   |
| Plantronics                                     | 6         | 0.05%   |
| M-Audio                                         | 6         | 0.05%   |
| Giga-Byte Technology                            | 6         | 0.05%   |
| Blue Microphones                                | 6         | 0.05%   |
| Sony                                            | 5         | 0.04%   |
| Dell                                            | 5         | 0.04%   |
| Yamaha                                          | 4         | 0.03%   |
| SteelSeries ApS                                 | 4         | 0.03%   |
| ROCCAT                                          | 4         | 0.03%   |
| PreSonus Audio Electronics                      | 4         | 0.03%   |
| Ensoniq                                         | 4         | 0.03%   |
| Corsair                                         | 4         | 0.03%   |
| Bose                                            | 4         | 0.03%   |
| Apple                                           | 4         | 0.03%   |
| SAVITECH                                        | 3         | 0.02%   |
| Licensed by Sony Computer Entertainment America | 3         | 0.02%   |
| Lenovo                                          | 3         | 0.02%   |
| Hewlett-Packard                                 | 3         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 875       | 5.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 817       | 5.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 563       | 3.84%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 541       | 3.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 537       | 3.66%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 506       | 3.45%   |
| AMD FCH Azalia Controller                                                                         | 484       | 3.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 426       | 2.91%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 407       | 2.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 402       | 2.74%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 343       | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 313       | 2.13%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 252       | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 249       | 1.7%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 237       | 1.62%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 230       | 1.57%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 207       | 1.41%   |
| Intel 8 Series HD Audio Controller                                                                | 202       | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                                          | 201       | 1.37%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 200       | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 196       | 1.34%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 195       | 1.33%   |
| Nvidia High Definition Audio Controller                                                           | 193       | 1.32%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 186       | 1.27%   |
| Intel Broadwell-U Audio Controller                                                                | 179       | 1.22%   |
| Intel 200 Series PCH HD Audio                                                                     | 177       | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 176       | 1.2%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 176       | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 168       | 1.15%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 156       | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 135       | 0.92%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 133       | 0.91%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 128       | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 123       | 0.84%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 116       | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 110       | 0.75%   |
| AMD Wrestler HDMI Audio                                                                           | 108       | 0.74%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 106       | 0.72%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 103       | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 102       | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2015      | 18.48%  |
| SK hynix            | 1610      | 14.76%  |
| Unknown             | 1581      | 14.5%   |
| Kingston            | 1439      | 13.19%  |
| Micron Technology   | 804       | 7.37%   |
| Crucial             | 562       | 5.15%   |
| Corsair             | 451       | 4.14%   |
| G.Skill             | 321       | 2.94%   |
| Elpida              | 304       | 2.79%   |
| A-DATA Technology   | 239       | 2.19%   |
| Ramaxel Technology  | 205       | 1.88%   |
| Nanya Technology    | 182       | 1.67%   |
| Smart               | 123       | 1.13%   |
| Unknown (ABCD)      | 94        | 0.86%   |
| Patriot             | 88        | 0.81%   |
| Unknown             | 82        | 0.75%   |
| Team                | 73        | 0.67%   |
| Goodram             | 56        | 0.51%   |
| Transcend           | 48        | 0.44%   |
| AMD                 | 40        | 0.37%   |
| Apacer              | 39        | 0.36%   |
| Teikon              | 30        | 0.28%   |
| ASint Technology    | 29        | 0.27%   |
| Kingmax             | 26        | 0.24%   |
| Qimonda             | 25        | 0.23%   |
| Silicon Power       | 22        | 0.2%    |
| Toshiba             | 21        | 0.19%   |
| Unifosa             | 18        | 0.17%   |
| High Bridge         | 18        | 0.17%   |
| GeIL                | 18        | 0.17%   |
| Avant               | 16        | 0.15%   |
| PNY                 | 15        | 0.14%   |
| Multilaser          | 13        | 0.12%   |
| CSX                 | 13        | 0.12%   |
| Smart Brazil        | 11        | 0.1%    |
| Goldkey             | 9         | 0.08%   |
| Qumo                | 7         | 0.06%   |
| OCZ                 | 7         | 0.06%   |
| Atermiter           | 7         | 0.06%   |
| TakeMS              | 6         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 109       | 0.92%   |
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 105       | 0.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 103       | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 96        | 0.81%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 92        | 0.78%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 89        | 0.75%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 87        | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 83        | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 83        | 0.7%    |
| Unknown                                                          | 82        | 0.69%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 70        | 0.59%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 70        | 0.59%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 70        | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 67        | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 66        | 0.56%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 66        | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 64        | 0.54%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 60        | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 53        | 0.45%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 51        | 0.43%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 45        | 0.38%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 44        | 0.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 43        | 0.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 43        | 0.36%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 43        | 0.36%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 42        | 0.35%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 42        | 0.35%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 40        | 0.34%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 39        | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 39        | 0.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 38        | 0.32%   |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 37        | 0.31%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 0.31%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s              | 37        | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 36        | 0.3%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 36        | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 35        | 0.3%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 35        | 0.3%    |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 34        | 0.29%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 33        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 4384      | 47.12%  |
| DDR4    | 2742      | 29.47%  |
| DDR2    | 831       | 8.93%   |
| Unknown | 499       | 5.36%   |
| SDRAM   | 444       | 4.77%   |
| LPDDR4  | 230       | 2.47%   |
| DDR     | 83        | 0.89%   |
| LPDDR3  | 62        | 0.67%   |
| DRAM    | 23        | 0.25%   |
| LPDDR5  | 3         | 0.03%   |
| DDR5    | 3         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 4724      | 51.66%  |
| DIMM         | 4176      | 45.67%  |
| Row Of Chips | 210       | 2.3%    |
| Chip         | 19        | 0.21%   |
| Unknown      | 7         | 0.08%   |
| RIMM         | 5         | 0.05%   |
| FB-DIMM      | 3         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 4007      | 38.99%  |
| 8192  | 2685      | 26.13%  |
| 2048  | 2303      | 22.41%  |
| 16384 | 569       | 5.54%   |
| 1024  | 561       | 5.46%   |
| 32768 | 91        | 0.89%   |
| 512   | 55        | 0.54%   |
| 256   | 2         | 0.02%   |
| 3072  | 1         | 0.01%   |
| 64    | 1         | 0.01%   |
| 32    | 1         | 0.01%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 2708      | 26.15%  |
| 1333    | 1232      | 11.9%   |
| 2667    | 913       | 8.82%   |
| 2400    | 712       | 6.88%   |
| 3200    | 550       | 5.31%   |
| 1334    | 498       | 4.81%   |
| 667     | 461       | 4.45%   |
| 800     | 447       | 4.32%   |
| 2133    | 354       | 3.42%   |
| Unknown | 330       | 3.19%   |
| 1067    | 229       | 2.21%   |
| 3600    | 203       | 1.96%   |
| 1867    | 182       | 1.76%   |
| 1066    | 125       | 1.21%   |
| 1866    | 104       | 1%      |
| 3266    | 88        | 0.85%   |
| 4199    | 86        | 0.83%   |
| 2666    | 84        | 0.81%   |
| 2048    | 77        | 0.74%   |
| 533     | 77        | 0.74%   |
| 4267    | 71        | 0.69%   |
| 400     | 69        | 0.67%   |
| 3000    | 60        | 0.58%   |
| 1800    | 60        | 0.58%   |
| 3400    | 58        | 0.56%   |
| 975     | 56        | 0.54%   |
| 2933    | 47        | 0.45%   |
| 3466    | 44        | 0.42%   |
| 333     | 30        | 0.29%   |
| 3866    | 29        | 0.28%   |
| 2800    | 26        | 0.25%   |
| 3733    | 25        | 0.24%   |
| 3800    | 20        | 0.19%   |
| 2000    | 19        | 0.18%   |
| 1639    | 19        | 0.18%   |
| 3066    | 16        | 0.15%   |
| 49926   | 15        | 0.14%   |
| 8400    | 14        | 0.14%   |
| 4266    | 12        | 0.12%   |
| 2200    | 12        | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 142       | 41.64%  |
| Brother Industries    | 65        | 19.06%  |
| Canon                 | 44        | 12.9%   |
| Samsung Electronics   | 34        | 9.97%   |
| Seiko Epson           | 28        | 8.21%   |
| Lexmark International | 7         | 2.05%   |
| QinHeng Electronics   | 4         | 1.17%   |
| Prolific Technology   | 4         | 1.17%   |
| Xerox                 | 3         | 0.88%   |
| Kyocera               | 3         | 0.88%   |
| Dymo-CoStar           | 3         | 0.88%   |
| Ricoh                 | 2         | 0.59%   |
| Oki Data              | 1         | 0.29%   |
| NXP Semiconductors    | 1         | 0.29%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP DeskJet 3630 series               | 7         | 2.04%   |
| HP ENVY 4520 series                  | 6         | 1.75%   |
| HP DeskJet 2620 All-in-One Printer   | 6         | 1.75%   |
| Samsung ML-1640 Series Laser Printer | 5         | 1.46%   |
| Samsung M2020 Series                 | 5         | 1.46%   |
| HP LaserJet 1020                     | 5         | 1.46%   |
| Samsung M2070 Series                 | 4         | 1.17%   |
| QinHeng CH340S                       | 4         | 1.17%   |
| Prolific PL2305 Parallel Port        | 4         | 1.17%   |
| HP LaserJet P1006                    | 4         | 1.17%   |
| HP LaserJet 1018                     | 4         | 1.17%   |
| HP DeskJet 2700 series               | 4         | 1.17%   |
| HP DeskJet 2130 series               | 4         | 1.17%   |
| Brother DCP-7055W                    | 4         | 1.17%   |
| Samsung SCX-3400 Series              | 3         | 0.87%   |
| HP LaserJet P1102                    | 3         | 0.87%   |
| HP LaserJet 1200                     | 3         | 0.87%   |
| HP LaserJet 1010                     | 3         | 0.87%   |
| HP Ink Tank Wireless 410 series      | 3         | 0.87%   |
| HP Deskjet 1050 J410                 | 3         | 0.87%   |
| Canon PIXMA MX920 Series             | 3         | 0.87%   |
| Canon PIXMA MG2500 Series            | 3         | 0.87%   |
| Brother Printer                      | 3         | 0.87%   |
| Brother MFC-J470DW                   | 3         | 0.87%   |
| Seiko Epson XP-243 245 247 Series    | 2         | 0.58%   |
| Seiko Epson L365 Series              | 2         | 0.58%   |
| Seiko Epson L120 Series              | 2         | 0.58%   |
| Seiko Epson ET-4760 Series           | 2         | 0.58%   |
| Samsung ML-2010P Mono Laser Printer  | 2         | 0.58%   |
| Kyocera ECOSYS P5021cdw              | 2         | 0.58%   |
| HP OfficeJet Pro 7720 series         | 2         | 0.58%   |
| HP OfficeJet Pro 6960                | 2         | 0.58%   |
| HP OfficeJet 6950                    | 2         | 0.58%   |
| HP LaserJet Pro M148f-M149f          | 2         | 0.58%   |
| HP LaserJet P1005                    | 2         | 0.58%   |
| HP LaserJet M14-M17                  | 2         | 0.58%   |
| HP LaserJet 1022                     | 2         | 0.58%   |
| HP LaserJet 1000                     | 2         | 0.58%   |
| HP ENVY Photo 6200 series            | 2         | 0.58%   |
| HP ENVY 4500 series                  | 2         | 0.58%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 36        | 52.94%  |
| Hewlett-Packard             | 13        | 19.12%  |
| Seiko Epson                 | 9         | 13.24%  |
| Mustek Systems              | 6         | 8.82%   |
| AGFA-Gevaert NV             | 2         | 2.94%   |
| Plustek                     | 1         | 1.47%   |
| KYE Systems (Mouse Systems) | 1         | 1.47%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 6         | 8.82%   |
| Canon CanoScan LiDE 110                                  | 6         | 8.82%   |
| Canon CanoScan LiDE 100                                  | 5         | 7.35%   |
| Canon CanoScan N1240U/LiDE 30                            | 3         | 4.41%   |
| Canon CanoScan LiDE 120                                  | 3         | 4.41%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2         | 2.94%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 2.94%   |
| Mustek Systems ScanExpress 1200 UB                       | 2         | 2.94%   |
| HP ScanJet 5590                                          | 2         | 2.94%   |
| HP ScanJet 4500C/5550C                                   | 2         | 2.94%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 2.94%   |
| Canon CanoScan LIDE 25                                   | 2         | 2.94%   |
| Seiko Epson Scanner                                      | 1         | 1.47%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 1         | 1.47%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]  | 1         | 1.47%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]        | 1         | 1.47%   |
| Seiko Epson GT-7400U [Perfection 1270]                   | 1         | 1.47%   |
| Plustek 600DPI USB Scanner                               | 1         | 1.47%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 1.47%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 1.47%   |
| Mustek Systems BearPaw 2448 CU Pro                       | 1         | 1.47%   |
| Mustek Systems BearPaw 1200 CU Plus                      | 1         | 1.47%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 1.47%   |
| HP ScanJet G4010                                         | 1         | 1.47%   |
| HP ScanJet 4570c                                         | 1         | 1.47%   |
| HP ScanJet 4370                                          | 1         | 1.47%   |
| HP ScanJet 3800c                                         | 1         | 1.47%   |
| HP ScanJet 3670                                          | 1         | 1.47%   |
| HP ScanJet 2400c                                         | 1         | 1.47%   |
| HP ScanJet 2300c                                         | 1         | 1.47%   |
| HP ScanJet 2200c                                         | 1         | 1.47%   |
| HP PSC 1200                                              | 1         | 1.47%   |
| Canon CanoScan N650U/N656U                               | 1         | 1.47%   |
| Canon CanoScan LiDE 700F                                 | 1         | 1.47%   |
| Canon CanoScan LiDE 70                                   | 1         | 1.47%   |
| Canon CanoScan LiDE 600F                                 | 1         | 1.47%   |
| Canon CanoScan LiDE 60                                   | 1         | 1.47%   |
| Canon CanoScan LiDE 500F                                 | 1         | 1.47%   |
| Canon CanoScan LiDE 220                                  | 1         | 1.47%   |
| Canon CanoScan LiDE 200                                  | 1         | 1.47%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1066      | 23.01%  |
| Realtek Semiconductor                  | 418       | 9.02%   |
| Microdia                               | 409       | 8.83%   |
| IMC Networks                           | 308       | 6.65%   |
| Acer                                   | 277       | 5.98%   |
| Suyin                                  | 260       | 5.61%   |
| Logitech                               | 246       | 5.31%   |
| Sunplus Innovation Technology          | 234       | 5.05%   |
| Cheng Uei Precision Industry (Foxlink) | 171       | 3.69%   |
| Quanta                                 | 152       | 3.28%   |
| Syntek                                 | 133       | 2.87%   |
| Apple                                  | 97        | 2.09%   |
| Lite-On Technology                     | 86        | 1.86%   |
| Alcor Micro                            | 85        | 1.84%   |
| Silicon Motion                         | 83        | 1.79%   |
| Ricoh                                  | 82        | 1.77%   |
| Microsoft                              | 50        | 1.08%   |
| Z-Star Microelectronics                | 40        | 0.86%   |
| Lenovo                                 | 40        | 0.86%   |
| Importek                               | 31        | 0.67%   |
| ALi                                    | 30        | 0.65%   |
| Luxvisions Innotech Limited            | 28        | 0.6%    |
| Primax Electronics                     | 25        | 0.54%   |
| GEMBIRD                                | 18        | 0.39%   |
| DigiTech                               | 16        | 0.35%   |
| Samsung Electronics                    | 14        | 0.3%    |
| Generalplus Technology                 | 14        | 0.3%    |
| Aveo Technology                        | 14        | 0.3%    |
| KYE Systems (Mouse Systems)            | 13        | 0.28%   |
| Sonix Technology                       | 12        | 0.26%   |
| Cubeternet                             | 12        | 0.26%   |
| OmniVision Technologies                | 11        | 0.24%   |
| Genesys Logic                          | 11        | 0.24%   |
| Creative Technology                    | 11        | 0.24%   |
| ARC International                      | 10        | 0.22%   |
| Unknown                                | 8         | 0.17%   |
| Huawei Technologies                    | 8         | 0.17%   |
| Trust                                  | 7         | 0.15%   |
| Sunplus Technology                     | 7         | 0.15%   |
| Hewlett-Packard                        | 7         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 131       | 2.8%    |
| Chicony Integrated Camera                               | 112       | 2.4%    |
| Chicony HD Webcam                                       | 111       | 2.38%   |
| Realtek Integrated_Webcam_HD                            | 89        | 1.9%    |
| Sunplus Integrated_Webcam_HD                            | 75        | 1.61%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 65        | 1.39%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 64        | 1.37%   |
| Realtek Integrated_Webcam_5M                            | 59        | 1.26%   |
| Logitech Webcam C270                                    | 58        | 1.24%   |
| Chicony USB 2.0 Camera                                  | 58        | 1.24%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 50        | 1.07%   |
| Syntek Integrated Camera                                | 49        | 1.05%   |
| Microdia Integrated Webcam                              | 49        | 1.05%   |
| Acer Integrated Camera                                  | 48        | 1.03%   |
| Acer Lenovo EasyCamera                                  | 47        | 1.01%   |
| Chicony VGA Webcam                                      | 45        | 0.96%   |
| IMC Networks Integrated Camera                          | 44        | 0.94%   |
| Realtek USB Camera                                      | 42        | 0.9%    |
| Chicony USB2.0 HD UVC WebCam                            | 39        | 0.83%   |
| Apple Built-in iSight                                   | 39        | 0.83%   |
| Chicony TOSHIBA Web Camera - HD                         | 37        | 0.79%   |
| Chicony HP TrueVision HD                                | 36        | 0.77%   |
| Chicony EasyCamera                                      | 36        | 0.77%   |
| Suyin Integrated_Webcam_HD                              | 35        | 0.75%   |
| Sunplus HD WebCam                                       | 35        | 0.75%   |
| Chicony USB2.0 VGA UVC WebCam                           | 35        | 0.75%   |
| Chicony Lenovo EasyCamera                               | 35        | 0.75%   |
| Syntek Lenovo EasyCamera                                | 34        | 0.73%   |
| Logitech HD Pro Webcam C920                             | 32        | 0.68%   |
| Acer Lenovo Integrated Webcam                           | 31        | 0.66%   |
| Lite-On Integrated Camera                               | 30        | 0.64%   |
| Chicony FJ Camera                                       | 29        | 0.62%   |
| Chicony HP TrueVision HD Camera                         | 28        | 0.6%    |
| Acer EasyCamera                                         | 28        | 0.6%    |
| Quanta HP TrueVision HD Camera                          | 27        | 0.58%   |
| Chicony HP Webcam                                       | 27        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 27        | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 27        | 0.58%   |
| Syntek EasyCamera                                       | 26        | 0.56%   |
| Quanta HP Webcam                                        | 26        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 190       | 37.85%  |
| AuthenTec                  | 81        | 16.14%  |
| Upek                       | 57        | 11.35%  |
| Synaptics                  | 49        | 9.76%   |
| Elan Microelectronics      | 37        | 7.37%   |
| Shenzhen Goodix Technology | 35        | 6.97%   |
| LighTuning Technology      | 26        | 5.18%   |
| STMicroelectronics         | 23        | 4.58%   |
| Focal-systems.Corp         | 2         | 0.4%    |
| Samsung Electronics        | 1         | 0.2%    |
| HOLTEK                     | 1         | 0.2%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 52        | 10.36%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 6.97%   |
| AuthenTec AES2810                                                          | 29        | 5.78%   |
| Shenzhen Goodix  FingerPrint Device                                        | 25        | 4.98%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.58%   |
| STMicroelectronics Fingerprint Reader                                      | 23        | 4.58%   |
| Elan ELAN:Fingerprint                                                      | 23        | 4.58%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 22        | 4.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 3.98%   |
| Validity Sensors VFS491                                                    | 17        | 3.39%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 3.39%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.79%   |
| Elan ELAN:ARM-M4                                                           | 14        | 2.79%   |
| AuthenTec AES1600                                                          | 14        | 2.79%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 13        | 2.59%   |
| Synaptics  WBDI                                                            | 13        | 2.59%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 12        | 2.39%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.19%   |
| Unknown                                                                    | 11        | 2.19%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 1.99%   |
| LighTuning EgisTec_ES603                                                   | 10        | 1.99%   |
| AuthenTec Fingerprint Sensor                                               | 10        | 1.99%   |
| Validity Sensors Fingerprint scanner                                       | 9         | 1.79%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 1.59%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 1.59%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 1.2%    |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.2%    |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1%      |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.8%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 0.8%    |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.8%    |
| Synaptics WBDI Device                                                      | 3         | 0.6%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 0.6%    |
| LighTuning Fingerprint Reader                                              | 3         | 0.6%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 2         | 0.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.4%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.4%    |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.4%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 158       | 51.47%  |
| Alcor Micro                       | 42        | 13.68%  |
| O2 Micro                          | 40        | 13.03%  |
| Lenovo                            | 22        | 7.17%   |
| Upek                              | 20        | 6.51%   |
| SCM Microsystems                  | 6         | 1.95%   |
| Gemalto (was Gemplus)             | 4         | 1.3%    |
| OmniKey                           | 3         | 0.98%   |
| Realtek Semiconductor             | 2         | 0.65%   |
| BIT4ID                            | 2         | 0.65%   |
| VASCO Data Security International | 1         | 0.33%   |
| Reiner SCT Kartensysteme          | 1         | 0.33%   |
| Microchip Technology              | 1         | 0.33%   |
| Hewlett-Packard                   | 1         | 0.33%   |
| Fujitsu Siemens Computers         | 1         | 0.33%   |
| Cherry                            | 1         | 0.33%   |
| Aladdin Knowledge Systems         | 1         | 0.33%   |
| Advanced Card Systems             | 1         | 0.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 88        | 28.66%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 13.68%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 39        | 12.7%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 39        | 12.7%   |
| Lenovo Integrated Smart Card Reader                                          | 22        | 7.17%   |
| Broadcom 5880                                                                | 22        | 7.17%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 20        | 6.51%   |
| Broadcom 58200                                                               | 5         | 1.63%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 3         | 0.98%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 0.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.65%   |
| BIT4ID miniLector EVO                                                        | 2         | 0.65%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.65%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.33%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.33%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.33%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.33%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.33%   |
| OmniKey CardMan 4321                                                         | 1         | 0.33%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.33%   |
| OmniKey CardMan 1021                                                         | 1         | 0.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.33%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.33%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.33%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.33%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.33%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.33%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.33%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.33%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.33%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 7785      | 84.19%  |
| 1     | 1286      | 13.91%  |
| 2     | 163       | 1.76%   |
| 3     | 10        | 0.11%   |
| 6     | 2         | 0.02%   |
| 4     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 502       | 30.82%  |
| Chipcard                 | 298       | 18.29%  |
| Graphics card            | 278       | 17.07%  |
| Net/wireless             | 164       | 10.07%  |
| Multimedia controller    | 103       | 6.32%   |
| Bluetooth                | 77        | 4.73%   |
| Storage                  | 58        | 3.56%   |
| Communication controller | 39        | 2.39%   |
| Camera                   | 35        | 2.15%   |
| Unassigned class         | 28        | 1.72%   |
| Network                  | 10        | 0.61%   |
| Sound                    | 9         | 0.55%   |
| Card reader              | 8         | 0.49%   |
| Flash memory             | 5         | 0.31%   |
| Wireless                 | 4         | 0.25%   |
| Modem                    | 4         | 0.25%   |
| Storage/ata              | 2         | 0.12%   |
| Net/ethernet             | 2         | 0.12%   |
| Unclassified device      | 1         | 0.06%   |
| Storage/raid             | 1         | 0.06%   |
| Dvb card                 | 1         | 0.06%   |

