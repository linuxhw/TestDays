OpenMandriva 4.3 - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 4.3.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_4.3/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_4.3/Notebook/README.md).

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

Total: 3703

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY m6                     | Notebook    | [9043724da5](https://linux-hardware.org/?probe=9043724da5) | Nov 02, 2022 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [83a1fc191a](https://linux-hardware.org/?probe=83a1fc191a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0a79270558](https://linux-hardware.org/?probe=0a79270558) | Nov 02, 2022 |
| Panasonic     | CF-C1BWFBZ1M                | Notebook    | [18a81d5db2](https://linux-hardware.org/?probe=18a81d5db2) | Nov 02, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [44f768478e](https://linux-hardware.org/?probe=44f768478e) | Nov 02, 2022 |
| Acer          | Aspire X1430                | Desktop     | [f48a8d45d8](https://linux-hardware.org/?probe=f48a8d45d8) | Nov 01, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [44c6e56cd9](https://linux-hardware.org/?probe=44c6e56cd9) | Nov 01, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [0470f02ccb](https://linux-hardware.org/?probe=0470f02ccb) | Nov 01, 2022 |
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
| Intel         | powered classmate PC        | Notebook    | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [5f7d9d2a04](https://linux-hardware.org/?probe=5f7d9d2a04) | Oct 30, 2022 |
| Prestigio     | PSB133S01ZFP                | Notebook    | [e10becbd35](https://linux-hardware.org/?probe=e10becbd35) | Oct 30, 2022 |
| Dell          | Latitude E7240              | Notebook    | [7605a5bf1c](https://linux-hardware.org/?probe=7605a5bf1c) | Oct 30, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [12b6232cdd](https://linux-hardware.org/?probe=12b6232cdd) | Oct 30, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [f8bdcbce4e](https://linux-hardware.org/?probe=f8bdcbce4e) | Oct 29, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | Desktop     | [2a7d6b757b](https://linux-hardware.org/?probe=2a7d6b757b) | Oct 29, 2022 |
| Dell          | Studio 1737                 | Notebook    | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| HP            | Compaq 615                  | Notebook    | [ae90fa3742](https://linux-hardware.org/?probe=ae90fa3742) | Oct 29, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [6e9cb9c0e0](https://linux-hardware.org/?probe=6e9cb9c0e0) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [ffb4369f83](https://linux-hardware.org/?probe=ffb4369f83) | Oct 29, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [2f79de6974](https://linux-hardware.org/?probe=2f79de6974) | Oct 28, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [88e6b582c9](https://linux-hardware.org/?probe=88e6b582c9) | Oct 28, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6b57390808](https://linux-hardware.org/?probe=6b57390808) | Oct 28, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [41e9e7aba7](https://linux-hardware.org/?probe=41e9e7aba7) | Oct 28, 2022 |
| HP            | Pavilion Laptop 15-cc0xx    | Notebook    | [0ca2ea7180](https://linux-hardware.org/?probe=0ca2ea7180) | Oct 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [8d93ee0286](https://linux-hardware.org/?probe=8d93ee0286) | Oct 28, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [ca5c26654a](https://linux-hardware.org/?probe=ca5c26654a) | Oct 27, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [4d5068a3be](https://linux-hardware.org/?probe=4d5068a3be) | Oct 27, 2022 |
| Acer          | Aspire 8730                 | Notebook    | [86bffd9523](https://linux-hardware.org/?probe=86bffd9523) | Oct 27, 2022 |
| Acer          | Aspire E3-112               | Notebook    | [fd34f66305](https://linux-hardware.org/?probe=fd34f66305) | Oct 26, 2022 |
| Acer          | Veriton M275                | Desktop     | [c4604d6f2a](https://linux-hardware.org/?probe=c4604d6f2a) | Oct 26, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [e2f30e0f1e](https://linux-hardware.org/?probe=e2f30e0f1e) | Oct 26, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [b50585b578](https://linux-hardware.org/?probe=b50585b578) | Oct 26, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [fa0daeab26](https://linux-hardware.org/?probe=fa0daeab26) | Oct 26, 2022 |
| Acer          | Veriton NBU                 | Desktop     | [7be04cd3ed](https://linux-hardware.org/?probe=7be04cd3ed) | Oct 25, 2022 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [2fb43f4be2](https://linux-hardware.org/?probe=2fb43f4be2) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [218d55e0ca](https://linux-hardware.org/?probe=218d55e0ca) | Oct 25, 2022 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [a25c84e8f1](https://linux-hardware.org/?probe=a25c84e8f1) | Oct 25, 2022 |
| Panasonic     | CFSX4-1                     | Notebook    | [2ddae6e0e1](https://linux-hardware.org/?probe=2ddae6e0e1) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bfa28dd791](https://linux-hardware.org/?probe=bfa28dd791) | Oct 24, 2022 |
| Dell          | 0GX297                      | Desktop     | [a047bbd7a0](https://linux-hardware.org/?probe=a047bbd7a0) | Oct 24, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [82afa0e5bc](https://linux-hardware.org/?probe=82afa0e5bc) | Oct 24, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d6e17c05b2](https://linux-hardware.org/?probe=d6e17c05b2) | Oct 24, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [b7315785a1](https://linux-hardware.org/?probe=b7315785a1) | Oct 24, 2022 |
| ASUSTek       | A7U                         | Notebook    | [867f26dde1](https://linux-hardware.org/?probe=867f26dde1) | Oct 24, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [cce2975614](https://linux-hardware.org/?probe=cce2975614) | Oct 24, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| Acer          | TravelMate B311-31          | Notebook    | [010dd1e876](https://linux-hardware.org/?probe=010dd1e876) | Oct 24, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [683ac39f80](https://linux-hardware.org/?probe=683ac39f80) | Oct 24, 2022 |
| Packard Be... | EasyNote ENTE70BH           | Notebook    | [2135a5aed7](https://linux-hardware.org/?probe=2135a5aed7) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| Acer          | WMCP78M                     | Desktop     | [f4e3945dea](https://linux-hardware.org/?probe=f4e3945dea) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| Lenovo        | ThinkPad X240 20AMS01M00    | Notebook    | [2f1c7b7716](https://linux-hardware.org/?probe=2f1c7b7716) | Oct 23, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12b83ecfd4](https://linux-hardware.org/?probe=12b83ecfd4) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Dell          | 0HX555                      | Desktop     | [86339c4a3f](https://linux-hardware.org/?probe=86339c4a3f) | Oct 22, 2022 |
| Philco        | DTC-A55                     | Desktop     | [5c7d64ff3f](https://linux-hardware.org/?probe=5c7d64ff3f) | Oct 22, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [78218a5b63](https://linux-hardware.org/?probe=78218a5b63) | Oct 21, 2022 |
| Dell          | Precision M6800             | Notebook    | [9b909039ee](https://linux-hardware.org/?probe=9b909039ee) | Oct 21, 2022 |
| ZOTAC         | ZBOX-QCM7T3000/EN072080S... | Mini pc     | [612f0f6e06](https://linux-hardware.org/?probe=612f0f6e06) | Oct 21, 2022 |
| MSI           | H61M-P20                    | Desktop     | [a50648c486](https://linux-hardware.org/?probe=a50648c486) | Oct 21, 2022 |
| Lenovo        | ThinkPad T520 42434WU       | Notebook    | [d118d39c58](https://linux-hardware.org/?probe=d118d39c58) | Oct 21, 2022 |
| MSI           | GT70 0NC/GT70 0NC           | Notebook    | [592b788d62](https://linux-hardware.org/?probe=592b788d62) | Oct 20, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [6c32002395](https://linux-hardware.org/?probe=6c32002395) | Oct 20, 2022 |
| Dell          | Latitude E5410              | Notebook    | [f3b5d196ef](https://linux-hardware.org/?probe=f3b5d196ef) | Oct 20, 2022 |
| ASRock        | H81 Pro BTC R2.0            | Desktop     | [2ead6c088f](https://linux-hardware.org/?probe=2ead6c088f) | Oct 20, 2022 |
| Sony          | SVE1513B1EW                 | Notebook    | [77ef0b542b](https://linux-hardware.org/?probe=77ef0b542b) | Oct 20, 2022 |
| Dell          | 0V52N7 A01                  | Server      | [c3990d0066](https://linux-hardware.org/?probe=c3990d0066) | Oct 19, 2022 |
| Acer          | Aspire E5-574               | Notebook    | [d9797d9fa7](https://linux-hardware.org/?probe=d9797d9fa7) | Oct 19, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [239627f1d1](https://linux-hardware.org/?probe=239627f1d1) | Oct 19, 2022 |
| HP            | 1825                        | Desktop     | [e0a35f1d0f](https://linux-hardware.org/?probe=e0a35f1d0f) | Oct 19, 2022 |
| Samsung       | 550XDA                      | Notebook    | [fcfceeaf04](https://linux-hardware.org/?probe=fcfceeaf04) | Oct 19, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [e14791bb51](https://linux-hardware.org/?probe=e14791bb51) | Oct 19, 2022 |
| HP            | 805D                        | Desktop     | [a70ef30fce](https://linux-hardware.org/?probe=a70ef30fce) | Oct 19, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [770d8bf876](https://linux-hardware.org/?probe=770d8bf876) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| ASUSTek       | P5KPL-E                     | Desktop     | [2f1e1cbbf4](https://linux-hardware.org/?probe=2f1e1cbbf4) | Oct 18, 2022 |
| Lenovo        | G480                        | Notebook    | [984691a38d](https://linux-hardware.org/?probe=984691a38d) | Oct 18, 2022 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [5823a0c5d0](https://linux-hardware.org/?probe=5823a0c5d0) | Oct 18, 2022 |
| HP            | Unknown                     | Notebook    | [4a0df43034](https://linux-hardware.org/?probe=4a0df43034) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [a1e9be5323](https://linux-hardware.org/?probe=a1e9be5323) | Oct 17, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [29f6ba9612](https://linux-hardware.org/?probe=29f6ba9612) | Oct 17, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [5872b35f8c](https://linux-hardware.org/?probe=5872b35f8c) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [8d9bc873e4](https://linux-hardware.org/?probe=8d9bc873e4) | Oct 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [9e37b60507](https://linux-hardware.org/?probe=9e37b60507) | Oct 16, 2022 |
| Dell          | Latitude E6430              | Notebook    | [2e8f3bd664](https://linux-hardware.org/?probe=2e8f3bd664) | Oct 16, 2022 |
| ASRock        | Z87 Pro3                    | Desktop     | [364a0afaff](https://linux-hardware.org/?probe=364a0afaff) | Oct 16, 2022 |
| Dell          | 0XFWHV A00                  | Desktop     | [4a5716d169](https://linux-hardware.org/?probe=4a5716d169) | Oct 16, 2022 |
| Gigabyte      | F2A88XM-HD3P                | Desktop     | [b5c41a9fef](https://linux-hardware.org/?probe=b5c41a9fef) | Oct 16, 2022 |
| Dell          | Latitude E6420              | Notebook    | [913e2b1acd](https://linux-hardware.org/?probe=913e2b1acd) | Oct 15, 2022 |
| HP            | 1850                        | Desktop     | [eda9bb7861](https://linux-hardware.org/?probe=eda9bb7861) | Oct 15, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | Notebook    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [3c51ad7454](https://linux-hardware.org/?probe=3c51ad7454) | Oct 15, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [a19fc69283](https://linux-hardware.org/?probe=a19fc69283) | Oct 15, 2022 |
| Intel         | DP45SG AAE27733-403         | Desktop     | [f391a78f4d](https://linux-hardware.org/?probe=f391a78f4d) | Oct 15, 2022 |
| LG Electro... | S460-G.BG31P1               | Notebook    | [a0b3b8e905](https://linux-hardware.org/?probe=a0b3b8e905) | Oct 15, 2022 |
| Dell          | Latitude 3340               | Notebook    | [d99dbe3b99](https://linux-hardware.org/?probe=d99dbe3b99) | Oct 14, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [720d282dfe](https://linux-hardware.org/?probe=720d282dfe) | Oct 14, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [bddc33ef5a](https://linux-hardware.org/?probe=bddc33ef5a) | Oct 14, 2022 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [1feb9942e8](https://linux-hardware.org/?probe=1feb9942e8) | Oct 14, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [e5f4bf84f8](https://linux-hardware.org/?probe=e5f4bf84f8) | Oct 14, 2022 |
| Compaq        | PRESARIOCQ18                | Notebook    | [5172032993](https://linux-hardware.org/?probe=5172032993) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| Dell          | Latitude E5440              | Notebook    | [432aa93109](https://linux-hardware.org/?probe=432aa93109) | Oct 14, 2022 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [a9f67e3f57](https://linux-hardware.org/?probe=a9f67e3f57) | Oct 13, 2022 |
| Dell          | Inspiron 5551               | Notebook    | [64865d9bb5](https://linux-hardware.org/?probe=64865d9bb5) | Oct 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [6144d2247a](https://linux-hardware.org/?probe=6144d2247a) | Oct 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [4cadd86832](https://linux-hardware.org/?probe=4cadd86832) | Oct 13, 2022 |
| Dell          | Studio 1555                 | Notebook    | [52104abe69](https://linux-hardware.org/?probe=52104abe69) | Oct 13, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3a190d5718](https://linux-hardware.org/?probe=3a190d5718) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [bb386c7d60](https://linux-hardware.org/?probe=bb386c7d60) | Oct 13, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [65e0a41b8d](https://linux-hardware.org/?probe=65e0a41b8d) | Oct 13, 2022 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [48ee58de23](https://linux-hardware.org/?probe=48ee58de23) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| HP            | G42                         | Notebook    | [fd42e3aedb](https://linux-hardware.org/?probe=fd42e3aedb) | Oct 12, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| Star Labs     | StarLite                    | Notebook    | [627ad33197](https://linux-hardware.org/?probe=627ad33197) | Oct 12, 2022 |
| HP            | 1497                        | Desktop     | [ff6d690da4](https://linux-hardware.org/?probe=ff6d690da4) | Oct 12, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [ff58ea3dc1](https://linux-hardware.org/?probe=ff58ea3dc1) | Oct 12, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| AMD           | A88                         | Desktop     | [1ee2502537](https://linux-hardware.org/?probe=1ee2502537) | Oct 12, 2022 |
| Pegatron      | IPM31G                      | Desktop     | [75d4fc0b55](https://linux-hardware.org/?probe=75d4fc0b55) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [18c02300b9](https://linux-hardware.org/?probe=18c02300b9) | Oct 11, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [1680fa50c0](https://linux-hardware.org/?probe=1680fa50c0) | Oct 11, 2022 |
| HP            | 2171                        | Desktop     | [105af7e899](https://linux-hardware.org/?probe=105af7e899) | Oct 11, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [4bc40092b2](https://linux-hardware.org/?probe=4bc40092b2) | Oct 11, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| Lenovo        | ThinkCentre M58 7359WES     | Desktop     | [1c00ee45c1](https://linux-hardware.org/?probe=1c00ee45c1) | Oct 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [92ab2501ea](https://linux-hardware.org/?probe=92ab2501ea) | Oct 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [22cf469faa](https://linux-hardware.org/?probe=22cf469faa) | Oct 10, 2022 |
| Acer          | Aspire XC-230               | Desktop     | [d213bca85f](https://linux-hardware.org/?probe=d213bca85f) | Oct 10, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [792528e3b2](https://linux-hardware.org/?probe=792528e3b2) | Oct 10, 2022 |
| Gigabyte      | 945GM-S2                    | Desktop     | [3087d063e3](https://linux-hardware.org/?probe=3087d063e3) | Oct 10, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| HP            | 829E                        | Mini pc     | [465ec7a2fe](https://linux-hardware.org/?probe=465ec7a2fe) | Oct 10, 2022 |
| Gigabyte      | F2A58M-HD2                  | Desktop     | [a219433035](https://linux-hardware.org/?probe=a219433035) | Oct 10, 2022 |
| AZW           | U59                         | Desktop     | [8300f61a93](https://linux-hardware.org/?probe=8300f61a93) | Oct 10, 2022 |
| HP            | 805D                        | Desktop     | [8938f51322](https://linux-hardware.org/?probe=8938f51322) | Oct 09, 2022 |
| Lenovo        | Dory CRB                    | Desktop     | [33ae78632a](https://linux-hardware.org/?probe=33ae78632a) | Oct 09, 2022 |
| Dell          | Latitude E6410              | Notebook    | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3e7ef86329](https://linux-hardware.org/?probe=3e7ef86329) | Oct 09, 2022 |
| ASUSTek       | X550VB                      | Notebook    | [a7c1c1cb1b](https://linux-hardware.org/?probe=a7c1c1cb1b) | Oct 09, 2022 |
| Dell          | Inspiron N7010              | Notebook    | [8d58156239](https://linux-hardware.org/?probe=8d58156239) | Oct 09, 2022 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [cf3661bb7c](https://linux-hardware.org/?probe=cf3661bb7c) | Oct 09, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [8918b1b82e](https://linux-hardware.org/?probe=8918b1b82e) | Oct 09, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d172225c0b](https://linux-hardware.org/?probe=d172225c0b) | Oct 08, 2022 |
| MSI           | A55M-P33                    | Desktop     | [127b8f180e](https://linux-hardware.org/?probe=127b8f180e) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [3665682cc6](https://linux-hardware.org/?probe=3665682cc6) | Oct 08, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9d44a35e48](https://linux-hardware.org/?probe=9d44a35e48) | Oct 08, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [e40ba3988f](https://linux-hardware.org/?probe=e40ba3988f) | Oct 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [feb96964b1](https://linux-hardware.org/?probe=feb96964b1) | Oct 08, 2022 |
| Dell          | 0MN1TX A01                  | Desktop     | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [3e7cc2c14a](https://linux-hardware.org/?probe=3e7cc2c14a) | Oct 07, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b699753cc6](https://linux-hardware.org/?probe=b699753cc6) | Oct 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [509deb10b3](https://linux-hardware.org/?probe=509deb10b3) | Oct 07, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [9dc72dc357](https://linux-hardware.org/?probe=9dc72dc357) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7a7bc387f4](https://linux-hardware.org/?probe=7a7bc387f4) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| ASUSTek       | M2V-MX                      | Desktop     | [55b3f7f6b0](https://linux-hardware.org/?probe=55b3f7f6b0) | Oct 06, 2022 |
| HP            | 18E4                        | Desktop     | [d9deeda238](https://linux-hardware.org/?probe=d9deeda238) | Oct 05, 2022 |
| Positivo      | C14CR01                     | Notebook    | [7c0d0b2efd](https://linux-hardware.org/?probe=7c0d0b2efd) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [f9224c972e](https://linux-hardware.org/?probe=f9224c972e) | Oct 05, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f7626421b2](https://linux-hardware.org/?probe=f7626421b2) | Oct 05, 2022 |
| Gigabyte      | H110M-S2PH-CF               | Desktop     | [580c13ac38](https://linux-hardware.org/?probe=580c13ac38) | Oct 05, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [8a18115a5b](https://linux-hardware.org/?probe=8a18115a5b) | Oct 04, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [612b4b36a1](https://linux-hardware.org/?probe=612b4b36a1) | Oct 04, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [65103a04c3](https://linux-hardware.org/?probe=65103a04c3) | Oct 04, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [b8ad7a8464](https://linux-hardware.org/?probe=b8ad7a8464) | Oct 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [60de9a1977](https://linux-hardware.org/?probe=60de9a1977) | Oct 04, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [89400b60b0](https://linux-hardware.org/?probe=89400b60b0) | Oct 04, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5e60e8faae](https://linux-hardware.org/?probe=5e60e8faae) | Oct 04, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Intel         | H55                         | Desktop     | [73719c58ab](https://linux-hardware.org/?probe=73719c58ab) | Oct 03, 2022 |
| Dell          | Latitude E6420              | Notebook    | [cc0d33aedb](https://linux-hardware.org/?probe=cc0d33aedb) | Oct 03, 2022 |
| Acer          | TravelMate 5744             | Notebook    | [4817d4810d](https://linux-hardware.org/?probe=4817d4810d) | Oct 03, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [f6a6361e08](https://linux-hardware.org/?probe=f6a6361e08) | Oct 03, 2022 |
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
| MSI           | B75MA-E33                   | Desktop     | [a14df6d116](https://linux-hardware.org/?probe=a14df6d116) | Oct 02, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [ce1567bb35](https://linux-hardware.org/?probe=ce1567bb35) | Oct 02, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d4f76a4236](https://linux-hardware.org/?probe=d4f76a4236) | Oct 01, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [9c6340e585](https://linux-hardware.org/?probe=9c6340e585) | Oct 01, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [ba72c7ee42](https://linux-hardware.org/?probe=ba72c7ee42) | Oct 01, 2022 |
| MSI           | MS-7235                     | Desktop     | [838e2c27f1](https://linux-hardware.org/?probe=838e2c27f1) | Oct 01, 2022 |
| Lenovo        | 3000 N200 0769B4G           | Notebook    | [947f124efc](https://linux-hardware.org/?probe=947f124efc) | Oct 01, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [68b0c0ca1a](https://linux-hardware.org/?probe=68b0c0ca1a) | Oct 01, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [1a0d8b695d](https://linux-hardware.org/?probe=1a0d8b695d) | Oct 01, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [a46521af41](https://linux-hardware.org/?probe=a46521af41) | Oct 01, 2022 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [982b143d73](https://linux-hardware.org/?probe=982b143d73) | Oct 01, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [d967f57569](https://linux-hardware.org/?probe=d967f57569) | Oct 01, 2022 |
| ASUSTek       | M5A87                       | Desktop     | [89ca067566](https://linux-hardware.org/?probe=89ca067566) | Oct 01, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [8c24fa2271](https://linux-hardware.org/?probe=8c24fa2271) | Oct 01, 2022 |
| Gigabyte      | B360 AORUS GAMING 3-CF      | Desktop     | [87a1c21540](https://linux-hardware.org/?probe=87a1c21540) | Oct 01, 2022 |
| Sony          | VPCYB3V1E                   | Notebook    | [de50c8a304](https://linux-hardware.org/?probe=de50c8a304) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [646f4ffa8e](https://linux-hardware.org/?probe=646f4ffa8e) | Oct 01, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [75b0aa3c75](https://linux-hardware.org/?probe=75b0aa3c75) | Sep 30, 2022 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [a6b14fdcf3](https://linux-hardware.org/?probe=a6b14fdcf3) | Sep 30, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [cfe1aba7e6](https://linux-hardware.org/?probe=cfe1aba7e6) | Sep 30, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [66877298d4](https://linux-hardware.org/?probe=66877298d4) | Sep 30, 2022 |
| Dell          | Latitude E6520              | Notebook    | [04817b4ceb](https://linux-hardware.org/?probe=04817b4ceb) | Sep 30, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [9018f40ad5](https://linux-hardware.org/?probe=9018f40ad5) | Sep 30, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [11e4602764](https://linux-hardware.org/?probe=11e4602764) | Sep 30, 2022 |
| Dell          | Latitude 3310               | Notebook    | [3c4874fa51](https://linux-hardware.org/?probe=3c4874fa51) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [d153a4f97a](https://linux-hardware.org/?probe=d153a4f97a) | Sep 29, 2022 |
| Toshiba       | Satellite L505              | Notebook    | [3e91e2bfaf](https://linux-hardware.org/?probe=3e91e2bfaf) | Sep 29, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [3990ec6cb0](https://linux-hardware.org/?probe=3990ec6cb0) | Sep 29, 2022 |
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
| Sony          | VPCEH1S1R                   | Notebook    | [5214bb023f](https://linux-hardware.org/?probe=5214bb023f) | Sep 27, 2022 |
| Dell          | Latitude 3300               | Notebook    | [365349d964](https://linux-hardware.org/?probe=365349d964) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [af23e43e99](https://linux-hardware.org/?probe=af23e43e99) | Sep 27, 2022 |
| Dell          | Latitude 3310               | Notebook    | [313ab64584](https://linux-hardware.org/?probe=313ab64584) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [d46d96565b](https://linux-hardware.org/?probe=d46d96565b) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f5f99a7234](https://linux-hardware.org/?probe=f5f99a7234) | Sep 27, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7cea84adb2](https://linux-hardware.org/?probe=7cea84adb2) | Sep 27, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [a33ab40c8b](https://linux-hardware.org/?probe=a33ab40c8b) | Sep 27, 2022 |
| Dell          | Latitude 3120               | Convertible | [bc34bf4d73](https://linux-hardware.org/?probe=bc34bf4d73) | Sep 27, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [3bafc34ffc](https://linux-hardware.org/?probe=3bafc34ffc) | Sep 27, 2022 |
| Packard Be... | EasyNote LS44SB             | Notebook    | [184a0768bd](https://linux-hardware.org/?probe=184a0768bd) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [56ac60a3dc](https://linux-hardware.org/?probe=56ac60a3dc) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [898f9bf963](https://linux-hardware.org/?probe=898f9bf963) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [8736347f60](https://linux-hardware.org/?probe=8736347f60) | Sep 26, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ee7c1fce66](https://linux-hardware.org/?probe=ee7c1fce66) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9d1392e945](https://linux-hardware.org/?probe=9d1392e945) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0f1fb4687f](https://linux-hardware.org/?probe=0f1fb4687f) | Sep 26, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [6ce0a09785](https://linux-hardware.org/?probe=6ce0a09785) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [a6ce17cd6b](https://linux-hardware.org/?probe=a6ce17cd6b) | Sep 26, 2022 |
| Acer          | Aspire V5-471               | Notebook    | [66437a2187](https://linux-hardware.org/?probe=66437a2187) | Sep 26, 2022 |
| Dell          | Latitude 3310               | Notebook    | [87af9a8980](https://linux-hardware.org/?probe=87af9a8980) | Sep 26, 2022 |
| Dell          | Latitude 3120               | Convertible | [9458cffde8](https://linux-hardware.org/?probe=9458cffde8) | Sep 26, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8749a17d26](https://linux-hardware.org/?probe=8749a17d26) | Sep 25, 2022 |
| Intel         | NUC10i7FNB K61360-305       | Mini pc     | [a7aadaeed0](https://linux-hardware.org/?probe=a7aadaeed0) | Sep 25, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [41db205ec7](https://linux-hardware.org/?probe=41db205ec7) | Sep 25, 2022 |
| Lenovo        | ThinkPad SL500 27464DG      | Notebook    | [6c2b4ce4b1](https://linux-hardware.org/?probe=6c2b4ce4b1) | Sep 25, 2022 |
| ASUSTek       | CM1740                      | Desktop     | [6ebc913933](https://linux-hardware.org/?probe=6ebc913933) | Sep 25, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [6c6ae30eba](https://linux-hardware.org/?probe=6c6ae30eba) | Sep 24, 2022 |
| HP            | Pavilion 15                 | Notebook    | [32670a0451](https://linux-hardware.org/?probe=32670a0451) | Sep 24, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [02925c7220](https://linux-hardware.org/?probe=02925c7220) | Sep 24, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [e78a82387b](https://linux-hardware.org/?probe=e78a82387b) | Sep 24, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [c354f2b293](https://linux-hardware.org/?probe=c354f2b293) | Sep 24, 2022 |
| Dell          | Inspiron 3721               | Notebook    | [7411a700cf](https://linux-hardware.org/?probe=7411a700cf) | Sep 24, 2022 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [dafafa97a4](https://linux-hardware.org/?probe=dafafa97a4) | Sep 24, 2022 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [ceda61113a](https://linux-hardware.org/?probe=ceda61113a) | Sep 23, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [991137f04f](https://linux-hardware.org/?probe=991137f04f) | Sep 23, 2022 |
| Dell          | 0PTTT9 A00                  | Desktop     | [21bde061e9](https://linux-hardware.org/?probe=21bde061e9) | Sep 23, 2022 |
| Dell          | Latitude 3120               | Convertible | [5281ee08e1](https://linux-hardware.org/?probe=5281ee08e1) | Sep 23, 2022 |
| Dell          | Latitude 3310               | Notebook    | [4c5dc33267](https://linux-hardware.org/?probe=4c5dc33267) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9c4d48864b](https://linux-hardware.org/?probe=9c4d48864b) | Sep 23, 2022 |
| Lenovo        | ThinkCentre Edge71 1578D... | Desktop     | [95dded89b8](https://linux-hardware.org/?probe=95dded89b8) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [443df1ca5c](https://linux-hardware.org/?probe=443df1ca5c) | Sep 23, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [061ef6f153](https://linux-hardware.org/?probe=061ef6f153) | Sep 23, 2022 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [a99682c38d](https://linux-hardware.org/?probe=a99682c38d) | Sep 23, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e1a3ca1d32](https://linux-hardware.org/?probe=e1a3ca1d32) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [2b37d81d4c](https://linux-hardware.org/?probe=2b37d81d4c) | Sep 22, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [2527dc6ea0](https://linux-hardware.org/?probe=2527dc6ea0) | Sep 22, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [9b451feb14](https://linux-hardware.org/?probe=9b451feb14) | Sep 22, 2022 |
| HP            | Compaq 15                   | Notebook    | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Lenovo        | ThinkPad X200s 7470WWD      | Notebook    | [268aa65de3](https://linux-hardware.org/?probe=268aa65de3) | Sep 22, 2022 |
| ASUSTek       | K70AD                       | Notebook    | [49dff3ffb5](https://linux-hardware.org/?probe=49dff3ffb5) | Sep 22, 2022 |
| ASUSTek       | X441BA                      | Notebook    | [e542a68ddf](https://linux-hardware.org/?probe=e542a68ddf) | Sep 21, 2022 |
| Lenovo        | 30BB SDK0J40697 WIN 3305... | All in one  | [989f23b214](https://linux-hardware.org/?probe=989f23b214) | Sep 21, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [978c6dd9dd](https://linux-hardware.org/?probe=978c6dd9dd) | Sep 21, 2022 |
| HP            | 1998                        | Desktop     | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| Dell          | G5 5505                     | Notebook    | [82017aa2ae](https://linux-hardware.org/?probe=82017aa2ae) | Sep 21, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [752cb8efae](https://linux-hardware.org/?probe=752cb8efae) | Sep 21, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [dd730980b1](https://linux-hardware.org/?probe=dd730980b1) | Sep 20, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a82f4ceccc](https://linux-hardware.org/?probe=a82f4ceccc) | Sep 20, 2022 |
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
| Dell          | Latitude 3300               | Notebook    | [a2513a9849](https://linux-hardware.org/?probe=a2513a9849) | Sep 19, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [892c3fb361](https://linux-hardware.org/?probe=892c3fb361) | Sep 18, 2022 |
| NEC Comput... | PC-VK26MXZCE                | Notebook    | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [f5fb874e1e](https://linux-hardware.org/?probe=f5fb874e1e) | Sep 18, 2022 |
| HP            | 2B29                        | Desktop     | [391e407d29](https://linux-hardware.org/?probe=391e407d29) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| HP            | 843F                        | Desktop     | [7694ed2ffa](https://linux-hardware.org/?probe=7694ed2ffa) | Sep 18, 2022 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [b9503c9c28](https://linux-hardware.org/?probe=b9503c9c28) | Sep 18, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [65c4f113d8](https://linux-hardware.org/?probe=65c4f113d8) | Sep 18, 2022 |
| HP            | ProBook 6470b               | Notebook    | [3821322b95](https://linux-hardware.org/?probe=3821322b95) | Sep 18, 2022 |
| Acer          | Switch SA5-271P             | Tablet      | [c9900a8e2f](https://linux-hardware.org/?probe=c9900a8e2f) | Sep 17, 2022 |
| HP            | Notebook                    | Notebook    | [d29681d2ed](https://linux-hardware.org/?probe=d29681d2ed) | Sep 17, 2022 |
| Lenovo        | ThinkPad E570 20H5009NUS    | Notebook    | [c64258edc0](https://linux-hardware.org/?probe=c64258edc0) | Sep 17, 2022 |
| Toshiba       | TECRA S10                   | Notebook    | [602d81b7c5](https://linux-hardware.org/?probe=602d81b7c5) | Sep 17, 2022 |
| Toshiba       | Satellite P845T             | Notebook    | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [f75308c465](https://linux-hardware.org/?probe=f75308c465) | Sep 17, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [19d0260ef6](https://linux-hardware.org/?probe=19d0260ef6) | Sep 17, 2022 |
| HP            | 255 G5 Notebook PC          | Notebook    | [6d8f7ffe97](https://linux-hardware.org/?probe=6d8f7ffe97) | Sep 17, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [93b43e5bb5](https://linux-hardware.org/?probe=93b43e5bb5) | Sep 16, 2022 |
| Lenovo        | ThinkPad T420 4180A32       | Notebook    | [44841341fd](https://linux-hardware.org/?probe=44841341fd) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e472e7fdde](https://linux-hardware.org/?probe=e472e7fdde) | Sep 16, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1ccce4a76a](https://linux-hardware.org/?probe=1ccce4a76a) | Sep 16, 2022 |
| Dell          | Latitude 3120               | Convertible | [e04ec1834f](https://linux-hardware.org/?probe=e04ec1834f) | Sep 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [52fe410fe3](https://linux-hardware.org/?probe=52fe410fe3) | Sep 16, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| Lenovo        | IdeaPad Y570 20091          | Notebook    | [5e2681360e](https://linux-hardware.org/?probe=5e2681360e) | Sep 15, 2022 |
| Lenovo        | ThinkPad T530 2429F33       | Notebook    | [790a0f2a25](https://linux-hardware.org/?probe=790a0f2a25) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9d15a7c8a2](https://linux-hardware.org/?probe=9d15a7c8a2) | Sep 14, 2022 |
| HP            | 1495                        | Desktop     | [462389df36](https://linux-hardware.org/?probe=462389df36) | Sep 14, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [832824de54](https://linux-hardware.org/?probe=832824de54) | Sep 14, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [39b26715f0](https://linux-hardware.org/?probe=39b26715f0) | Sep 14, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | Desktop     | [6ee9d3e2c4](https://linux-hardware.org/?probe=6ee9d3e2c4) | Sep 14, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [677d683644](https://linux-hardware.org/?probe=677d683644) | Sep 14, 2022 |
| Timi          | TM1612                      | Notebook    | [536fc04dcb](https://linux-hardware.org/?probe=536fc04dcb) | Sep 14, 2022 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [06d4572f5e](https://linux-hardware.org/?probe=06d4572f5e) | Sep 14, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [daab24c8b6](https://linux-hardware.org/?probe=daab24c8b6) | Sep 14, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [331a481ab0](https://linux-hardware.org/?probe=331a481ab0) | Sep 14, 2022 |
| Lenovo        | ThinkPad X230 2324GA1       | Notebook    | [c4e6cc1489](https://linux-hardware.org/?probe=c4e6cc1489) | Sep 14, 2022 |
| Toshiba       | Satellite L55-B             | Notebook    | [b593ff9e20](https://linux-hardware.org/?probe=b593ff9e20) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| Dell          | Latitude 3120               | Convertible | [a8315e1147](https://linux-hardware.org/?probe=a8315e1147) | Sep 13, 2022 |
| Sun Micros... | ASSY,MOTHERBOARD,X4170 5... | Server      | [ea845ec5ea](https://linux-hardware.org/?probe=ea845ec5ea) | Sep 13, 2022 |
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
| HP            | 158B                        | Desktop     | [ba2366e9ad](https://linux-hardware.org/?probe=ba2366e9ad) | Sep 12, 2022 |
| HP            | ProBook 440 G1              | Notebook    | [58b48039ce](https://linux-hardware.org/?probe=58b48039ce) | Sep 12, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [73684f0e47](https://linux-hardware.org/?probe=73684f0e47) | Sep 12, 2022 |
| HP            | 304Bh                       | Desktop     | [0a7bcbdd9e](https://linux-hardware.org/?probe=0a7bcbdd9e) | Sep 11, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [5d0092ffc1](https://linux-hardware.org/?probe=5d0092ffc1) | Sep 11, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [910cdee832](https://linux-hardware.org/?probe=910cdee832) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| HP            | Notebook                    | Notebook    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [9e730cbd6a](https://linux-hardware.org/?probe=9e730cbd6a) | Sep 11, 2022 |
| MSI           | 0A48                        | Desktop     | [2619140b48](https://linux-hardware.org/?probe=2619140b48) | Sep 10, 2022 |
| Dell          | 01TKCC A01                  | Desktop     | [6d032338c0](https://linux-hardware.org/?probe=6d032338c0) | Sep 10, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [5fb806b2c8](https://linux-hardware.org/?probe=5fb806b2c8) | Sep 10, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b5842ca017](https://linux-hardware.org/?probe=b5842ca017) | Sep 10, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [0533bc0e86](https://linux-hardware.org/?probe=0533bc0e86) | Sep 10, 2022 |
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
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [cd84312899](https://linux-hardware.org/?probe=cd84312899) | Sep 09, 2022 |
| Dell          | 04075X A00                  | All in one  | [e2ff438b3c](https://linux-hardware.org/?probe=e2ff438b3c) | Sep 09, 2022 |
| Dell          | Precision 7560              | Notebook    | [3e2d1a120c](https://linux-hardware.org/?probe=3e2d1a120c) | Sep 09, 2022 |
| Dell          | Latitude E4300              | Notebook    | [634c1467f8](https://linux-hardware.org/?probe=634c1467f8) | Sep 09, 2022 |
| Dell          | Latitude 3120               | Convertible | [6b2b6b7aa9](https://linux-hardware.org/?probe=6b2b6b7aa9) | Sep 09, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [36b349b529](https://linux-hardware.org/?probe=36b349b529) | Sep 09, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [5c21c2acc6](https://linux-hardware.org/?probe=5c21c2acc6) | Sep 09, 2022 |
| Positivo      | H14BT58                     | Notebook    | [669a466b1c](https://linux-hardware.org/?probe=669a466b1c) | Sep 09, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [1a5c8e32b7](https://linux-hardware.org/?probe=1a5c8e32b7) | Sep 09, 2022 |
| Lenovo        | IdeaPad S400 20195          | Notebook    | [6bd3292f42](https://linux-hardware.org/?probe=6bd3292f42) | Sep 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [ee7071f4e7](https://linux-hardware.org/?probe=ee7071f4e7) | Sep 08, 2022 |
| Gigabyte      | A520M DS3H                  | Desktop     | [036c262ad4](https://linux-hardware.org/?probe=036c262ad4) | Sep 08, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [1c9d752f91](https://linux-hardware.org/?probe=1c9d752f91) | Sep 07, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4a39ae67d5](https://linux-hardware.org/?probe=4a39ae67d5) | Sep 07, 2022 |
| Lenovo        | G580                        | Notebook    | [922ede2a50](https://linux-hardware.org/?probe=922ede2a50) | Sep 07, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [70e3d85420](https://linux-hardware.org/?probe=70e3d85420) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| Positivo      | POS-PQ45AU                  | Desktop     | [2770dcd81a](https://linux-hardware.org/?probe=2770dcd81a) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [22171cc2a6](https://linux-hardware.org/?probe=22171cc2a6) | Sep 07, 2022 |
| Unknown       | GSUO H61V10C                | Desktop     | [4eeb38bb0a](https://linux-hardware.org/?probe=4eeb38bb0a) | Sep 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14f91e3a08](https://linux-hardware.org/?probe=14f91e3a08) | Sep 07, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [cf398ae303](https://linux-hardware.org/?probe=cf398ae303) | Sep 07, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [cca59cbb3c](https://linux-hardware.org/?probe=cca59cbb3c) | Sep 07, 2022 |
| Positivo      | Mobile                      | Notebook    | [1378222b07](https://linux-hardware.org/?probe=1378222b07) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [c6eefaabf9](https://linux-hardware.org/?probe=c6eefaabf9) | Sep 07, 2022 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [46161b573f](https://linux-hardware.org/?probe=46161b573f) | Sep 06, 2022 |
| Lenovo        | ThinkPad Edge E531 68856... | Notebook    | [498682ac13](https://linux-hardware.org/?probe=498682ac13) | Sep 06, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [c211642362](https://linux-hardware.org/?probe=c211642362) | Sep 06, 2022 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [8a66fbdadd](https://linux-hardware.org/?probe=8a66fbdadd) | Sep 06, 2022 |
| Sony          | VPCSB3X9E                   | Notebook    | [03bd901e4f](https://linux-hardware.org/?probe=03bd901e4f) | Sep 06, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | ThinkPad T420 4236PNP       | Notebook    | [7c3dc0af20](https://linux-hardware.org/?probe=7c3dc0af20) | Sep 06, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [78e0cb1ca2](https://linux-hardware.org/?probe=78e0cb1ca2) | Sep 06, 2022 |
| Acer          | Aspire 5745                 | Notebook    | [39bc7728ac](https://linux-hardware.org/?probe=39bc7728ac) | Sep 06, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [c16dc3a768](https://linux-hardware.org/?probe=c16dc3a768) | Sep 06, 2022 |
| Lenovo        | ThinkPad L440 20ASS11T00    | Notebook    | [526d97c730](https://linux-hardware.org/?probe=526d97c730) | Sep 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [537708f71a](https://linux-hardware.org/?probe=537708f71a) | Sep 06, 2022 |
| HP            | Stream Laptop 14-cb0XX      | Notebook    | [6f848cd309](https://linux-hardware.org/?probe=6f848cd309) | Sep 06, 2022 |
| Dell          | Vostro 14-5480              | Notebook    | [fb3ae25db8](https://linux-hardware.org/?probe=fb3ae25db8) | Sep 06, 2022 |
| Dell          | Latitude E6220              | Notebook    | [af87786838](https://linux-hardware.org/?probe=af87786838) | Sep 05, 2022 |
| Lenovo        | ThinkPad T530 2429W4Y       | Notebook    | [572b46f025](https://linux-hardware.org/?probe=572b46f025) | Sep 05, 2022 |
| ASUSTek       | K53BY                       | Notebook    | [efbc2be1a7](https://linux-hardware.org/?probe=efbc2be1a7) | Sep 05, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [d9a3103936](https://linux-hardware.org/?probe=d9a3103936) | Sep 05, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [ac68238341](https://linux-hardware.org/?probe=ac68238341) | Sep 05, 2022 |
| Toshiba       | Satellite C55-A-157         | Notebook    | [483a0f4f49](https://linux-hardware.org/?probe=483a0f4f49) | Sep 05, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [a783dcd3ca](https://linux-hardware.org/?probe=a783dcd3ca) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| HP            | 8076                        | Desktop     | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [4d5b865aed](https://linux-hardware.org/?probe=4d5b865aed) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| ASUSTek       | X45C                        | Notebook    | [7267b251b6](https://linux-hardware.org/?probe=7267b251b6) | Sep 05, 2022 |
| PCWare        | IPMH61R3                    | Desktop     | [1cbe0ee116](https://linux-hardware.org/?probe=1cbe0ee116) | Sep 04, 2022 |
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
| Dell          | Latitude 3120               | Convertible | [cb976a52d2](https://linux-hardware.org/?probe=cb976a52d2) | Sep 02, 2022 |
| HP            | 8053                        | Desktop     | [2e48f3f13e](https://linux-hardware.org/?probe=2e48f3f13e) | Sep 02, 2022 |
| Dell          | 0TP412                      | Desktop     | [73ec9dcd98](https://linux-hardware.org/?probe=73ec9dcd98) | Sep 02, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [b9502cc4a9](https://linux-hardware.org/?probe=b9502cc4a9) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d27c20dcf9](https://linux-hardware.org/?probe=d27c20dcf9) | Sep 01, 2022 |
| Packard Be... | DOT S                       | Notebook    | [b5b03f1cf7](https://linux-hardware.org/?probe=b5b03f1cf7) | Sep 01, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [143e6e1816](https://linux-hardware.org/?probe=143e6e1816) | Sep 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [e2fc506c38](https://linux-hardware.org/?probe=e2fc506c38) | Sep 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| Dell          | Latitude 3190               | Notebook    | [d30269b33c](https://linux-hardware.org/?probe=d30269b33c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [c48154f5f4](https://linux-hardware.org/?probe=c48154f5f4) | Sep 01, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [c9a801a4d2](https://linux-hardware.org/?probe=c9a801a4d2) | Sep 01, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [7140822520](https://linux-hardware.org/?probe=7140822520) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASRock        | X99 Taichi                  | Desktop     | [4cd4bf6c89](https://linux-hardware.org/?probe=4cd4bf6c89) | Sep 01, 2022 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [1a173c5ea0](https://linux-hardware.org/?probe=1a173c5ea0) | Sep 01, 2022 |
| HP            | Pavilion g6                 | Notebook    | [cc725d880c](https://linux-hardware.org/?probe=cc725d880c) | Aug 31, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [7850c07cdc](https://linux-hardware.org/?probe=7850c07cdc) | Aug 31, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [710d1e9a9b](https://linux-hardware.org/?probe=710d1e9a9b) | Aug 31, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [120400698e](https://linux-hardware.org/?probe=120400698e) | Aug 31, 2022 |
| Vorke         | V1 Plus                     | Desktop     | [0f36a3adcb](https://linux-hardware.org/?probe=0f36a3adcb) | Aug 31, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [c9ebe69583](https://linux-hardware.org/?probe=c9ebe69583) | Aug 30, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [f3389e42f8](https://linux-hardware.org/?probe=f3389e42f8) | Aug 30, 2022 |
| Gigabyte      | VM900M                      | Desktop     | [f446d835da](https://linux-hardware.org/?probe=f446d835da) | Aug 30, 2022 |
| Dell          | 0R230R A00                  | Desktop     | [0ea749e83c](https://linux-hardware.org/?probe=0ea749e83c) | Aug 30, 2022 |
| Dell          | Precision M6400             | Notebook    | [3cf32e24fa](https://linux-hardware.org/?probe=3cf32e24fa) | Aug 30, 2022 |
| HP            | 0A60h                       | Desktop     | [d801f7cb0c](https://linux-hardware.org/?probe=d801f7cb0c) | Aug 30, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [33aaa7baf4](https://linux-hardware.org/?probe=33aaa7baf4) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M91p 4518AU8    | Desktop     | [0099ab3432](https://linux-hardware.org/?probe=0099ab3432) | Aug 29, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [536742931b](https://linux-hardware.org/?probe=536742931b) | Aug 29, 2022 |
| Dell          | Latitude 3300               | Notebook    | [bea8e53929](https://linux-hardware.org/?probe=bea8e53929) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Lenovo        | ThinkCentre M58p 6234CL2    | Desktop     | [14449a705a](https://linux-hardware.org/?probe=14449a705a) | Aug 29, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [ce25a77e25](https://linux-hardware.org/?probe=ce25a77e25) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [99f7df96c2](https://linux-hardware.org/?probe=99f7df96c2) | Aug 29, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [efb40be4e1](https://linux-hardware.org/?probe=efb40be4e1) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| Dell          | Studio 1735                 | Notebook    | [912f409b37](https://linux-hardware.org/?probe=912f409b37) | Aug 28, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [d8a4e4d954](https://linux-hardware.org/?probe=d8a4e4d954) | Aug 28, 2022 |
| HP            | 620                         | Notebook    | [b16c60f4cf](https://linux-hardware.org/?probe=b16c60f4cf) | Aug 28, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [91371e505d](https://linux-hardware.org/?probe=91371e505d) | Aug 28, 2022 |
| Acer          | AO722                       | Notebook    | [377ad8686f](https://linux-hardware.org/?probe=377ad8686f) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [a18db0fafd](https://linux-hardware.org/?probe=a18db0fafd) | Aug 27, 2022 |
| ASUSTek       | P8B WS                      | Desktop     | [5f89ab0d00](https://linux-hardware.org/?probe=5f89ab0d00) | Aug 27, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [f74dc71ad8](https://linux-hardware.org/?probe=f74dc71ad8) | Aug 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [d6c013a669](https://linux-hardware.org/?probe=d6c013a669) | Aug 27, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [67712f11d9](https://linux-hardware.org/?probe=67712f11d9) | Aug 27, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [459c7c1eee](https://linux-hardware.org/?probe=459c7c1eee) | Aug 27, 2022 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | Notebook    | [1ea46f19be](https://linux-hardware.org/?probe=1ea46f19be) | Aug 27, 2022 |
| MSI           | G31TM-P21                   | Desktop     | [cf0bc232f5](https://linux-hardware.org/?probe=cf0bc232f5) | Aug 26, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [22cc477cd2](https://linux-hardware.org/?probe=22cc477cd2) | Aug 26, 2022 |
| Apple         | Mac-CFF7D910A743CAAF iMa... | All in one  | [1b562e8768](https://linux-hardware.org/?probe=1b562e8768) | Aug 26, 2022 |
| MSI           | 760GM-P21                   | Desktop     | [7e45cde899](https://linux-hardware.org/?probe=7e45cde899) | Aug 26, 2022 |
| HP            | 1497                        | Desktop     | [82e518a338](https://linux-hardware.org/?probe=82e518a338) | Aug 26, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e4a6425675](https://linux-hardware.org/?probe=e4a6425675) | Aug 26, 2022 |
| HP            | 15                          | Notebook    | [310d617e09](https://linux-hardware.org/?probe=310d617e09) | Aug 26, 2022 |
| Dell          | 06MC09 A00                  | Mini pc     | [71402e3c39](https://linux-hardware.org/?probe=71402e3c39) | Aug 26, 2022 |
| Dell          | 0RJ290                      | Desktop     | [ca82162ed5](https://linux-hardware.org/?probe=ca82162ed5) | Aug 25, 2022 |
| Acer          | Aspire XC-710 V:1.1         | Desktop     | [0b76e0f97d](https://linux-hardware.org/?probe=0b76e0f97d) | Aug 25, 2022 |
| Foxconn       | H61M/H61M-S                 | Desktop     | [18e7da32e9](https://linux-hardware.org/?probe=18e7da32e9) | Aug 25, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [0462079328](https://linux-hardware.org/?probe=0462079328) | Aug 25, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [72888e9acb](https://linux-hardware.org/?probe=72888e9acb) | Aug 25, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [1c98247f4c](https://linux-hardware.org/?probe=1c98247f4c) | Aug 25, 2022 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [82da7782ec](https://linux-hardware.org/?probe=82da7782ec) | Aug 25, 2022 |
| HP            | 829A                        | Mini pc     | [76cb57e98d](https://linux-hardware.org/?probe=76cb57e98d) | Aug 25, 2022 |
| OEM           | A320                        | Desktop     | [4dffd629cf](https://linux-hardware.org/?probe=4dffd629cf) | Aug 25, 2022 |
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
| Dell          | 08HPGT A01                  | Desktop     | [744f838dc2](https://linux-hardware.org/?probe=744f838dc2) | Aug 24, 2022 |
| Supermicro    | X10SDV-8C+-LN2F             | Server      | [a4ec1f93e5](https://linux-hardware.org/?probe=a4ec1f93e5) | Aug 23, 2022 |
| Acer          | Aspire A315-54K             | Notebook    | [685d6acc51](https://linux-hardware.org/?probe=685d6acc51) | Aug 23, 2022 |
| ICP / iEi     | B217 V1.0                   | Desktop     | [9b540ece9f](https://linux-hardware.org/?probe=9b540ece9f) | Aug 23, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [7dae220687](https://linux-hardware.org/?probe=7dae220687) | Aug 23, 2022 |
| Dell          | Latitude E5470              | Notebook    | [4cf5f4680f](https://linux-hardware.org/?probe=4cf5f4680f) | Aug 23, 2022 |
| HP            | 8158 A01                    | Mini pc     | [443d203df8](https://linux-hardware.org/?probe=443d203df8) | Aug 22, 2022 |
| Google        | Galtic                      | Notebook    | [f06baf315d](https://linux-hardware.org/?probe=f06baf315d) | Aug 22, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [1de0aeba8f](https://linux-hardware.org/?probe=1de0aeba8f) | Aug 22, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [ca7534d4dc](https://linux-hardware.org/?probe=ca7534d4dc) | Aug 22, 2022 |
| Intel         | NUC11ATBC4 M53051-202       | Mini pc     | [6568854eef](https://linux-hardware.org/?probe=6568854eef) | Aug 22, 2022 |
| Acer          | Enduro EUN314-51WG          | Notebook    | [aa9ea3d520](https://linux-hardware.org/?probe=aa9ea3d520) | Aug 22, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [3d9c208d81](https://linux-hardware.org/?probe=3d9c208d81) | Aug 22, 2022 |
| Dell          | Latitude 3300               | Notebook    | [e8b139ecad](https://linux-hardware.org/?probe=e8b139ecad) | Aug 22, 2022 |
| Dell          | Latitude 3310               | Notebook    | [dedda1b96c](https://linux-hardware.org/?probe=dedda1b96c) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [fa5f1121d5](https://linux-hardware.org/?probe=fa5f1121d5) | Aug 22, 2022 |
| Lenovo        | 36FB SDK0L77769 WIN 3423... | All in one  | [c65b675fc8](https://linux-hardware.org/?probe=c65b675fc8) | Aug 22, 2022 |
| Intel         | H61                         | Desktop     | [f0a810114c](https://linux-hardware.org/?probe=f0a810114c) | Aug 22, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | Notebook    | [fdbec5aab2](https://linux-hardware.org/?probe=fdbec5aab2) | Aug 22, 2022 |
| Fujitsu       | LIFEBOOK UH552              | Notebook    | [15a1f49654](https://linux-hardware.org/?probe=15a1f49654) | Aug 21, 2022 |
| Acer          | AO725                       | Notebook    | [5eed64f77d](https://linux-hardware.org/?probe=5eed64f77d) | Aug 21, 2022 |
| ASUSTek       | Z87-C                       | Desktop     | [8de83c544f](https://linux-hardware.org/?probe=8de83c544f) | Aug 21, 2022 |
| HP            | 1998                        | Desktop     | [69b6b04268](https://linux-hardware.org/?probe=69b6b04268) | Aug 21, 2022 |
| Lenovo        | ThinkPad X200 7458FZ3       | Notebook    | [232835b00b](https://linux-hardware.org/?probe=232835b00b) | Aug 21, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [1292b2297f](https://linux-hardware.org/?probe=1292b2297f) | Aug 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [bb19c0586c](https://linux-hardware.org/?probe=bb19c0586c) | Aug 20, 2022 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [142e25352d](https://linux-hardware.org/?probe=142e25352d) | Aug 20, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [56a34e0816](https://linux-hardware.org/?probe=56a34e0816) | Aug 20, 2022 |
| ASUSTek       | P5KPL-SE                    | Desktop     | [2925e63a87](https://linux-hardware.org/?probe=2925e63a87) | Aug 20, 2022 |
| AZW           | MII-V                       | Desktop     | [59698f6b33](https://linux-hardware.org/?probe=59698f6b33) | Aug 20, 2022 |
| OEM           | Intel H81                   | Desktop     | [5e354c60d1](https://linux-hardware.org/?probe=5e354c60d1) | Aug 20, 2022 |
| HP            | Pavilion dv6                | Notebook    | [0aae35eb95](https://linux-hardware.org/?probe=0aae35eb95) | Aug 19, 2022 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [803031cd3b](https://linux-hardware.org/?probe=803031cd3b) | Aug 19, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [74b0bedd54](https://linux-hardware.org/?probe=74b0bedd54) | Aug 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [c954da96ad](https://linux-hardware.org/?probe=c954da96ad) | Aug 18, 2022 |
| Intel         | NUC7i7BNB J31145-310        | Mini pc     | [d9f1c174b3](https://linux-hardware.org/?probe=d9f1c174b3) | Aug 18, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [870fcf0f3c](https://linux-hardware.org/?probe=870fcf0f3c) | Aug 18, 2022 |
| Dell          | Latitude E5510              | Notebook    | [c7defb71d5](https://linux-hardware.org/?probe=c7defb71d5) | Aug 18, 2022 |
| Medion        | Akoya E6418 MD99620         | Notebook    | [6817b38103](https://linux-hardware.org/?probe=6817b38103) | Aug 18, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d29438c201](https://linux-hardware.org/?probe=d29438c201) | Aug 18, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a0a7a845e3](https://linux-hardware.org/?probe=a0a7a845e3) | Aug 18, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [de6e02672c](https://linux-hardware.org/?probe=de6e02672c) | Aug 18, 2022 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [d78fb85708](https://linux-hardware.org/?probe=d78fb85708) | Aug 18, 2022 |
| Positivo B... | S14SL03                     | Notebook    | [558f5a2f24](https://linux-hardware.org/?probe=558f5a2f24) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Acer          | MRS600M                     | Desktop     | [ec4c10d06e](https://linux-hardware.org/?probe=ec4c10d06e) | Aug 17, 2022 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [870d7102f5](https://linux-hardware.org/?probe=870d7102f5) | Aug 17, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [944a99ea66](https://linux-hardware.org/?probe=944a99ea66) | Aug 17, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [471659ffff](https://linux-hardware.org/?probe=471659ffff) | Aug 17, 2022 |
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
| Acer          | Aspire ES1-532G             | Notebook    | [cf05c858ab](https://linux-hardware.org/?probe=cf05c858ab) | Aug 15, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6c31827147](https://linux-hardware.org/?probe=6c31827147) | Aug 15, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| HP            | 2AE2                        | Desktop     | [1fd0bb70dc](https://linux-hardware.org/?probe=1fd0bb70dc) | Aug 15, 2022 |
| Dell          | Inspiron 1501               | Notebook    | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Gigabyte      | P43-ES3G                    | Desktop     | [2b0691bddd](https://linux-hardware.org/?probe=2b0691bddd) | Aug 15, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [56ee42afe3](https://linux-hardware.org/?probe=56ee42afe3) | Aug 15, 2022 |
| Dell          | 0NC2VH A01                  | Desktop     | [170b178361](https://linux-hardware.org/?probe=170b178361) | Aug 15, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [4b1440875b](https://linux-hardware.org/?probe=4b1440875b) | Aug 14, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [15ffff65c0](https://linux-hardware.org/?probe=15ffff65c0) | Aug 14, 2022 |
| HP            | ProBook 4330s               | Notebook    | [62ff6ffc08](https://linux-hardware.org/?probe=62ff6ffc08) | Aug 14, 2022 |
| HP            | 18E7                        | Desktop     | [06374a6240](https://linux-hardware.org/?probe=06374a6240) | Aug 14, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [55c4e8059c](https://linux-hardware.org/?probe=55c4e8059c) | Aug 14, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [30146876c6](https://linux-hardware.org/?probe=30146876c6) | Aug 14, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [e9c64a8a5c](https://linux-hardware.org/?probe=e9c64a8a5c) | Aug 14, 2022 |
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
| Toshiba       | Satellite L500              | Notebook    | [0d58c17039](https://linux-hardware.org/?probe=0d58c17039) | Aug 13, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [fd41ccab04](https://linux-hardware.org/?probe=fd41ccab04) | Aug 13, 2022 |
| HP            | 1850                        | Desktop     | [33933e3e5d](https://linux-hardware.org/?probe=33933e3e5d) | Aug 12, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [50b7221c5a](https://linux-hardware.org/?probe=50b7221c5a) | Aug 12, 2022 |
| Positivo      | Mobile                      | Notebook    | [bddf3b59d4](https://linux-hardware.org/?probe=bddf3b59d4) | Aug 12, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bc32ff70b7](https://linux-hardware.org/?probe=bc32ff70b7) | Aug 12, 2022 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [762d78160d](https://linux-hardware.org/?probe=762d78160d) | Aug 12, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [ff1be50f8c](https://linux-hardware.org/?probe=ff1be50f8c) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | Notebook    | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| ASUSTek       | K73BR                       | Notebook    | [67f5d3f176](https://linux-hardware.org/?probe=67f5d3f176) | Aug 12, 2022 |
| Acer          | Aspire 4330 V1.22           | Notebook    | [dee8895134](https://linux-hardware.org/?probe=dee8895134) | Aug 12, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [c1b14847f1](https://linux-hardware.org/?probe=c1b14847f1) | Aug 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [2f3db9cd91](https://linux-hardware.org/?probe=2f3db9cd91) | Aug 12, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [d949d71a19](https://linux-hardware.org/?probe=d949d71a19) | Aug 12, 2022 |
| Lenovo        | Unknown                     | Notebook    | [79688945e1](https://linux-hardware.org/?probe=79688945e1) | Aug 11, 2022 |
| ASRock        | Z97M Pro4                   | Desktop     | [245d189a61](https://linux-hardware.org/?probe=245d189a61) | Aug 11, 2022 |
| Dell          | G5 5505                     | Notebook    | [cbbcb7c9a2](https://linux-hardware.org/?probe=cbbcb7c9a2) | Aug 11, 2022 |
| Dell          | Vostro 3401                 | Notebook    | [29f3354492](https://linux-hardware.org/?probe=29f3354492) | Aug 11, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [73bf30c596](https://linux-hardware.org/?probe=73bf30c596) | Aug 11, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c765f5b81c](https://linux-hardware.org/?probe=c765f5b81c) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| HP            | Pavilion dm3                | Notebook    | [7152a48ede](https://linux-hardware.org/?probe=7152a48ede) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [3b20387bcc](https://linux-hardware.org/?probe=3b20387bcc) | Aug 10, 2022 |
| HP            | 240 G3                      | Notebook    | [77225815d2](https://linux-hardware.org/?probe=77225815d2) | Aug 10, 2022 |
| ASRock        | H81M-DGS                    | Desktop     | [31bdc504d4](https://linux-hardware.org/?probe=31bdc504d4) | Aug 10, 2022 |
| Dell          | 07KY25 A00                  | Desktop     | [676025f81a](https://linux-hardware.org/?probe=676025f81a) | Aug 10, 2022 |
| ASUSTek       | TUF B360-PRO GAMING         | Desktop     | [62d813423e](https://linux-hardware.org/?probe=62d813423e) | Aug 10, 2022 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [58947090d5](https://linux-hardware.org/?probe=58947090d5) | Aug 09, 2022 |
| eMachines     | Veriton V2110               | Desktop     | [3492540d77](https://linux-hardware.org/?probe=3492540d77) | Aug 09, 2022 |
| Lenovo        | 36ED SDK0M26027 WIN 3273... | All in one  | [6481787b51](https://linux-hardware.org/?probe=6481787b51) | Aug 09, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [2df31a9fbf](https://linux-hardware.org/?probe=2df31a9fbf) | Aug 09, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [4f83e69c06](https://linux-hardware.org/?probe=4f83e69c06) | Aug 09, 2022 |
| ASUSTek       | Z87-PRO                     | Desktop     | [89a77b442f](https://linux-hardware.org/?probe=89a77b442f) | Aug 09, 2022 |
| HP            | 630                         | Notebook    | [fc9bc69e9a](https://linux-hardware.org/?probe=fc9bc69e9a) | Aug 09, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [0afee77b44](https://linux-hardware.org/?probe=0afee77b44) | Aug 09, 2022 |
| Gigabyte      | EP35-DS3P                   | Desktop     | [5c29aee903](https://linux-hardware.org/?probe=5c29aee903) | Aug 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| ASUSTek       | AT3IONT-I DELUXE            | Desktop     | [642e31466d](https://linux-hardware.org/?probe=642e31466d) | Aug 08, 2022 |
| Dell          | 0782GW A01                  | Desktop     | [b3ebc3aed3](https://linux-hardware.org/?probe=b3ebc3aed3) | Aug 08, 2022 |
| Acer          | Nitro AN515-31              | Notebook    | [0dbab56588](https://linux-hardware.org/?probe=0dbab56588) | Aug 08, 2022 |
| HP            | 15                          | Notebook    | [ef66e0296e](https://linux-hardware.org/?probe=ef66e0296e) | Aug 08, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [616a031820](https://linux-hardware.org/?probe=616a031820) | Aug 08, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| HP            | 304Bh                       | Desktop     | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [362398e54e](https://linux-hardware.org/?probe=362398e54e) | Aug 08, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| Intel         | H61                         | Desktop     | [eabc8be629](https://linux-hardware.org/?probe=eabc8be629) | Aug 08, 2022 |
| BESSTAR Te... | AB1                         | Mini pc     | [fc51f2c4b7](https://linux-hardware.org/?probe=fc51f2c4b7) | Aug 08, 2022 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [4d6a861120](https://linux-hardware.org/?probe=4d6a861120) | Aug 07, 2022 |
| HP            | Compaq 15                   | Notebook    | [de4b6e0511](https://linux-hardware.org/?probe=de4b6e0511) | Aug 07, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [95f444c24c](https://linux-hardware.org/?probe=95f444c24c) | Aug 07, 2022 |
| Gigabyte      | EP45-UD3R                   | Desktop     | [6c434341ce](https://linux-hardware.org/?probe=6c434341ce) | Aug 07, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [0b63e92a55](https://linux-hardware.org/?probe=0b63e92a55) | Aug 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f9850e0a1e](https://linux-hardware.org/?probe=f9850e0a1e) | Aug 07, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [4e36acba35](https://linux-hardware.org/?probe=4e36acba35) | Aug 07, 2022 |
| Dell          | Latitude 3189               | Notebook    | [63c2818521](https://linux-hardware.org/?probe=63c2818521) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [810a9d1c2c](https://linux-hardware.org/?probe=810a9d1c2c) | Aug 07, 2022 |
| MSI           | GL75 Leopard 10SDK          | Notebook    | [bfceb8ba35](https://linux-hardware.org/?probe=bfceb8ba35) | Aug 07, 2022 |
| Lenovo        | IdeaPad S145-15IKB 81VD     | Notebook    | [f3a36d0f3a](https://linux-hardware.org/?probe=f3a36d0f3a) | Aug 07, 2022 |
| Acer          | Swift SF114-31              | Notebook    | [b1cba472dc](https://linux-hardware.org/?probe=b1cba472dc) | Aug 06, 2022 |
| HP            | 2215                        | Desktop     | [75304ada6c](https://linux-hardware.org/?probe=75304ada6c) | Aug 06, 2022 |
| Lenovo        | ThinkPad T430s 2356LNG      | Notebook    | [255560d675](https://linux-hardware.org/?probe=255560d675) | Aug 06, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [77092711a0](https://linux-hardware.org/?probe=77092711a0) | Aug 06, 2022 |
| Toshiba       | STI 006998G                 | Desktop     | [3de3fa77fc](https://linux-hardware.org/?probe=3de3fa77fc) | Aug 06, 2022 |
| ASRock        | H110M-STX                   | Desktop     | [62b1924710](https://linux-hardware.org/?probe=62b1924710) | Aug 06, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [4015089c1e](https://linux-hardware.org/?probe=4015089c1e) | Aug 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [8913065613](https://linux-hardware.org/?probe=8913065613) | Aug 06, 2022 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [6b1d79046a](https://linux-hardware.org/?probe=6b1d79046a) | Aug 06, 2022 |
| ASUSTek       | UX303UA                     | Notebook    | [73145490fa](https://linux-hardware.org/?probe=73145490fa) | Aug 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [dbf000aacd](https://linux-hardware.org/?probe=dbf000aacd) | Aug 06, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [daa1f68f01](https://linux-hardware.org/?probe=daa1f68f01) | Aug 06, 2022 |
| MACHINIST     | X79 (INTEL Xeon E5/Corei... | Desktop     | [a722bef081](https://linux-hardware.org/?probe=a722bef081) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [b9a68ae76c](https://linux-hardware.org/?probe=b9a68ae76c) | Aug 06, 2022 |
| MSI           | Z87-G43 GAMING              | Desktop     | [490239de9e](https://linux-hardware.org/?probe=490239de9e) | Aug 05, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [1ad9e54625](https://linux-hardware.org/?probe=1ad9e54625) | Aug 05, 2022 |
| Supermicro    | X8DTL                       | Server      | [efb288164c](https://linux-hardware.org/?probe=efb288164c) | Aug 05, 2022 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [b68c110fde](https://linux-hardware.org/?probe=b68c110fde) | Aug 05, 2022 |
| Acer          | E1-510                      | Notebook    | [05ea3ff386](https://linux-hardware.org/?probe=05ea3ff386) | Aug 05, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [f6b820d15f](https://linux-hardware.org/?probe=f6b820d15f) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [f52779262f](https://linux-hardware.org/?probe=f52779262f) | Aug 05, 2022 |
| Dell          | Latitude 3310               | Notebook    | [97ac18f196](https://linux-hardware.org/?probe=97ac18f196) | Aug 05, 2022 |
| Dell          | Latitude 3410               | Notebook    | [8181c3588f](https://linux-hardware.org/?probe=8181c3588f) | Aug 05, 2022 |
| Dell          | Precision M4700             | Notebook    | [25efd53898](https://linux-hardware.org/?probe=25efd53898) | Aug 05, 2022 |
| HP            | ProBook 6450b               | Notebook    | [699b27e34f](https://linux-hardware.org/?probe=699b27e34f) | Aug 05, 2022 |
| Dell          | 0KG317                      | Desktop     | [65c105e2be](https://linux-hardware.org/?probe=65c105e2be) | Aug 04, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [d5d981cf7b](https://linux-hardware.org/?probe=d5d981cf7b) | Aug 04, 2022 |
| Lenovo        | ThinkPad X230 2325U9T       | Notebook    | [0f0e8ec24f](https://linux-hardware.org/?probe=0f0e8ec24f) | Aug 04, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [8c6442a868](https://linux-hardware.org/?probe=8c6442a868) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Dell          | Latitude 3490               | Notebook    | [fa1c5f753f](https://linux-hardware.org/?probe=fa1c5f753f) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [1b51c25d37](https://linux-hardware.org/?probe=1b51c25d37) | Aug 04, 2022 |
| Dell          | Latitude 3310               | Notebook    | [9b9bed6ac6](https://linux-hardware.org/?probe=9b9bed6ac6) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [9a4f5806f8](https://linux-hardware.org/?probe=9a4f5806f8) | Aug 04, 2022 |
| Dell          | Latitude 3120               | Convertible | [d3e0c77946](https://linux-hardware.org/?probe=d3e0c77946) | Aug 04, 2022 |
| Intel         | NUC6i7KYB H90766-403        | Mini pc     | [fa04804b78](https://linux-hardware.org/?probe=fa04804b78) | Aug 04, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [dabb21caca](https://linux-hardware.org/?probe=dabb21caca) | Aug 04, 2022 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [7893ade7cb](https://linux-hardware.org/?probe=7893ade7cb) | Aug 04, 2022 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f9e07e62c2](https://linux-hardware.org/?probe=f9e07e62c2) | Aug 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [0725792da0](https://linux-hardware.org/?probe=0725792da0) | Aug 04, 2022 |
| Dell          | System Inspiron N4110       | Notebook    | [22938e2e62](https://linux-hardware.org/?probe=22938e2e62) | Aug 03, 2022 |
| Gigabyte      | B360M GAMING HD             | Desktop     | [95e1eb0fcb](https://linux-hardware.org/?probe=95e1eb0fcb) | Aug 03, 2022 |
| Lenovo        | ThinkPad T530 2429W4Z       | Notebook    | [2d95f7cc7e](https://linux-hardware.org/?probe=2d95f7cc7e) | Aug 03, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | Notebook    | [f1d5a6ab3f](https://linux-hardware.org/?probe=f1d5a6ab3f) | Aug 03, 2022 |
| Lenovo        | 3102                        | Desktop     | [73e0fee2bc](https://linux-hardware.org/?probe=73e0fee2bc) | Aug 03, 2022 |
| Lenovo        | ThinkPad SL510 28477NG      | Notebook    | [5ddf195177](https://linux-hardware.org/?probe=5ddf195177) | Aug 03, 2022 |
| Gigabyte      | Z170X-UD3-CF                | Desktop     | [450fee0496](https://linux-hardware.org/?probe=450fee0496) | Aug 03, 2022 |
| HP            | 2B29                        | Desktop     | [5fcf3a8320](https://linux-hardware.org/?probe=5fcf3a8320) | Aug 02, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [97dba8f5e3](https://linux-hardware.org/?probe=97dba8f5e3) | Aug 02, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [f6f97a58c4](https://linux-hardware.org/?probe=f6f97a58c4) | Aug 02, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [6b790e8a9b](https://linux-hardware.org/?probe=6b790e8a9b) | Aug 02, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [1a35a6d7dc](https://linux-hardware.org/?probe=1a35a6d7dc) | Aug 02, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [4f1fca6662](https://linux-hardware.org/?probe=4f1fca6662) | Aug 02, 2022 |
| Dell          | Latitude E6430              | Notebook    | [15e26c7cc5](https://linux-hardware.org/?probe=15e26c7cc5) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [31bd0a48c9](https://linux-hardware.org/?probe=31bd0a48c9) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [71c6ba6061](https://linux-hardware.org/?probe=71c6ba6061) | Aug 01, 2022 |
| Dell          | Latitude E7450              | Notebook    | [38051fe609](https://linux-hardware.org/?probe=38051fe609) | Aug 01, 2022 |
| Packard Be... | EasyNote TK13BZ             | Notebook    | [530d3ad8db](https://linux-hardware.org/?probe=530d3ad8db) | Aug 01, 2022 |
| TrekStor      | Primebook C13               | Convertible | [e45c26fec9](https://linux-hardware.org/?probe=e45c26fec9) | Aug 01, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [daaf600950](https://linux-hardware.org/?probe=daaf600950) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| HP            | ProBook 440 G2              | Notebook    | [00dd80ba31](https://linux-hardware.org/?probe=00dd80ba31) | Aug 01, 2022 |
| Acer          | Z476                        | Notebook    | [ade85b90c1](https://linux-hardware.org/?probe=ade85b90c1) | Aug 01, 2022 |
| HP            | 339A                        | Desktop     | [251a764917](https://linux-hardware.org/?probe=251a764917) | Aug 01, 2022 |
| Toshiba       | Satellite-C845              | Notebook    | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | Notebook    | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [d58be7b6d1](https://linux-hardware.org/?probe=d58be7b6d1) | Aug 01, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [7051f56dda](https://linux-hardware.org/?probe=7051f56dda) | Aug 01, 2022 |
| MSI           | Z77A-GD65                   | Desktop     | [fcadad42a5](https://linux-hardware.org/?probe=fcadad42a5) | Aug 01, 2022 |
| Acer          | Aspire ES1-523              | Notebook    | [d14f053671](https://linux-hardware.org/?probe=d14f053671) | Aug 01, 2022 |
| HP            | 843F                        | Desktop     | [eeba83fecb](https://linux-hardware.org/?probe=eeba83fecb) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Packard Be... | EasyNote TM85               | Notebook    | [a6df06f9e5](https://linux-hardware.org/?probe=a6df06f9e5) | Jul 31, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [7e6cd7bcb3](https://linux-hardware.org/?probe=7e6cd7bcb3) | Jul 31, 2022 |
| Lenovo        | ThinkPad T460 20FMS02R0G    | Notebook    | [0aa31e3c39](https://linux-hardware.org/?probe=0aa31e3c39) | Jul 31, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [490edd75cf](https://linux-hardware.org/?probe=490edd75cf) | Jul 31, 2022 |
| HP            | ProBook 6570b               | Notebook    | [333a24bdee](https://linux-hardware.org/?probe=333a24bdee) | Jul 31, 2022 |
| Acer          | Aspire VN7-791G             | Notebook    | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| Toshiba       | All In One PC MP            | All in one  | [4d493ab3df](https://linux-hardware.org/?probe=4d493ab3df) | Jul 31, 2022 |
| ASUSTek       | P8B75-M LX                  | Desktop     | [653f46c8e3](https://linux-hardware.org/?probe=653f46c8e3) | Jul 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6204ce9d95](https://linux-hardware.org/?probe=6204ce9d95) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| MSI           | B85M-P33                    | Desktop     | [6e9af1d1e4](https://linux-hardware.org/?probe=6e9af1d1e4) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [cb7c9442d6](https://linux-hardware.org/?probe=cb7c9442d6) | Jul 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [a8e41fdaaa](https://linux-hardware.org/?probe=a8e41fdaaa) | Jul 31, 2022 |
| eMachines     | Unknown                     | Notebook    | [8c6dcb08a7](https://linux-hardware.org/?probe=8c6dcb08a7) | Jul 31, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [7b0b52e138](https://linux-hardware.org/?probe=7b0b52e138) | Jul 31, 2022 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [25db3983fe](https://linux-hardware.org/?probe=25db3983fe) | Jul 30, 2022 |
| Compaq        | Presario CQ-23              | Notebook    | [76ea82c314](https://linux-hardware.org/?probe=76ea82c314) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [10ece2cb6c](https://linux-hardware.org/?probe=10ece2cb6c) | Jul 30, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [b846739765](https://linux-hardware.org/?probe=b846739765) | Jul 30, 2022 |
| ASUSTek       | K501LX                      | Notebook    | [8ea0c7daa9](https://linux-hardware.org/?probe=8ea0c7daa9) | Jul 30, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [edd98c5418](https://linux-hardware.org/?probe=edd98c5418) | Jul 30, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ee5c151c3a](https://linux-hardware.org/?probe=ee5c151c3a) | Jul 30, 2022 |
| ASUSTek       | K53E                        | Notebook    | [3ca340212e](https://linux-hardware.org/?probe=3ca340212e) | Jul 30, 2022 |
| Lenovo        | G570 4334                   | Notebook    | [a29c1c816a](https://linux-hardware.org/?probe=a29c1c816a) | Jul 30, 2022 |
| Fujitsu       | LIFEBOOK V1020              | Notebook    | [e33ac2916d](https://linux-hardware.org/?probe=e33ac2916d) | Jul 30, 2022 |
| ASRock        | J5040-ITX                   | Desktop     | [2cc4fd5d75](https://linux-hardware.org/?probe=2cc4fd5d75) | Jul 30, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [c30fca013c](https://linux-hardware.org/?probe=c30fca013c) | Jul 30, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [fdb72c3ec3](https://linux-hardware.org/?probe=fdb72c3ec3) | Jul 29, 2022 |
| HP            | 2ADC                        | Desktop     | [86608333bc](https://linux-hardware.org/?probe=86608333bc) | Jul 29, 2022 |
| Acer          | Aspire A317-33              | Notebook    | [ab07e43574](https://linux-hardware.org/?probe=ab07e43574) | Jul 29, 2022 |
| Sony          | VPCEA45FL                   | Notebook    | [8079ec1351](https://linux-hardware.org/?probe=8079ec1351) | Jul 29, 2022 |
| Lenovo        | ThinkPad T440s 20ARS4PR0... | Notebook    | [5b91ff037d](https://linux-hardware.org/?probe=5b91ff037d) | Jul 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [231ebd2edc](https://linux-hardware.org/?probe=231ebd2edc) | Jul 29, 2022 |
| PCWare        | IPMH61R2                    | Desktop     | [b3245af28d](https://linux-hardware.org/?probe=b3245af28d) | Jul 29, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [02e9f6a808](https://linux-hardware.org/?probe=02e9f6a808) | Jul 29, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [a42627d17e](https://linux-hardware.org/?probe=a42627d17e) | Jul 29, 2022 |
| HP            | 0AA0h                       | Desktop     | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| HP            | 18E4                        | Desktop     | [d13265fa57](https://linux-hardware.org/?probe=d13265fa57) | Jul 29, 2022 |
| Lenovo        | ThinkPad S5 Yoga 15 20DR... | Notebook    | [147d305ac1](https://linux-hardware.org/?probe=147d305ac1) | Jul 29, 2022 |
| Lenovo        | ThinkPad X230 23253B3       | Notebook    | [fa19ec3adf](https://linux-hardware.org/?probe=fa19ec3adf) | Jul 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [e1d666e84a](https://linux-hardware.org/?probe=e1d666e84a) | Jul 29, 2022 |
| Google        | Candy                       | Notebook    | [cba2906cfd](https://linux-hardware.org/?probe=cba2906cfd) | Jul 29, 2022 |
| HP            | ProBook 430 G5              | Notebook    | [f424705bd7](https://linux-hardware.org/?probe=f424705bd7) | Jul 29, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [e3f2dd0271](https://linux-hardware.org/?probe=e3f2dd0271) | Jul 29, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [03b39a36f1](https://linux-hardware.org/?probe=03b39a36f1) | Jul 29, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [61a6277614](https://linux-hardware.org/?probe=61a6277614) | Jul 28, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [668a02296d](https://linux-hardware.org/?probe=668a02296d) | Jul 28, 2022 |
| HP            | ProBook 4515s               | Notebook    | [b9759d3b5d](https://linux-hardware.org/?probe=b9759d3b5d) | Jul 28, 2022 |
| Dell          | OptiPlex 780                | Desktop     | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| ASRock        | Z97 Anniversary             | Desktop     | [768b11cbe4](https://linux-hardware.org/?probe=768b11cbe4) | Jul 28, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [1bc8def241](https://linux-hardware.org/?probe=1bc8def241) | Jul 28, 2022 |
| MSI           | AM1I                        | Desktop     | [63e6d4040e](https://linux-hardware.org/?probe=63e6d4040e) | Jul 28, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [75477a4d7a](https://linux-hardware.org/?probe=75477a4d7a) | Jul 28, 2022 |
| ASUSTek       | K53U                        | Notebook    | [7db28a1538](https://linux-hardware.org/?probe=7db28a1538) | Jul 28, 2022 |
| Acer          | Aspire 3100                 | Notebook    | [26c6af2a55](https://linux-hardware.org/?probe=26c6af2a55) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | Notebook    | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [a555c41bb7](https://linux-hardware.org/?probe=a555c41bb7) | Jul 28, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [1357e3b3d3](https://linux-hardware.org/?probe=1357e3b3d3) | Jul 28, 2022 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [93ad7b0efb](https://linux-hardware.org/?probe=93ad7b0efb) | Jul 28, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [db492973ec](https://linux-hardware.org/?probe=db492973ec) | Jul 28, 2022 |
| HP            | 2000                        | Notebook    | [531b786836](https://linux-hardware.org/?probe=531b786836) | Jul 28, 2022 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [afaf75a141](https://linux-hardware.org/?probe=afaf75a141) | Jul 28, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [cc72c3c914](https://linux-hardware.org/?probe=cc72c3c914) | Jul 28, 2022 |
| Wortmann      | TERRA_MOBILE_1528P/1748P    | Notebook    | [7bcdc30be3](https://linux-hardware.org/?probe=7bcdc30be3) | Jul 28, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [24e94dd87e](https://linux-hardware.org/?probe=24e94dd87e) | Jul 28, 2022 |
| Digibras      | NH4CU03                     | Notebook    | [bf8a8c589a](https://linux-hardware.org/?probe=bf8a8c589a) | Jul 28, 2022 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | Desktop     | [0068653ca3](https://linux-hardware.org/?probe=0068653ca3) | Jul 28, 2022 |
| Positivo      | H14BT58                     | Notebook    | [7f271e5d68](https://linux-hardware.org/?probe=7f271e5d68) | Jul 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [d64175b64b](https://linux-hardware.org/?probe=d64175b64b) | Jul 28, 2022 |
| Toshiba       | Satellite C850D-11K         | Notebook    | [544f2db462](https://linux-hardware.org/?probe=544f2db462) | Jul 28, 2022 |
| Sony          | VPCS110FL                   | Notebook    | [8576955f3c](https://linux-hardware.org/?probe=8576955f3c) | Jul 28, 2022 |
| ASRock        | A88M-ITX/ac                 | Desktop     | [e339941033](https://linux-hardware.org/?probe=e339941033) | Jul 27, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [71b03b93a2](https://linux-hardware.org/?probe=71b03b93a2) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [94a6b79798](https://linux-hardware.org/?probe=94a6b79798) | Jul 27, 2022 |
| Acer          | Aspire X1930                | Desktop     | [6a650f512e](https://linux-hardware.org/?probe=6a650f512e) | Jul 27, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [b7fabad758](https://linux-hardware.org/?probe=b7fabad758) | Jul 27, 2022 |
| HP            | Pavilion g7                 | Notebook    | [75fa7f0ce4](https://linux-hardware.org/?probe=75fa7f0ce4) | Jul 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d0ef6d20cf](https://linux-hardware.org/?probe=d0ef6d20cf) | Jul 27, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | All in one  | [d8cbb25698](https://linux-hardware.org/?probe=d8cbb25698) | Jul 27, 2022 |
| Foxconn       | A76ML-K 30                  | Desktop     | [7b118c6a6b](https://linux-hardware.org/?probe=7b118c6a6b) | Jul 27, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [8f0daaf341](https://linux-hardware.org/?probe=8f0daaf341) | Jul 27, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [610282a0e6](https://linux-hardware.org/?probe=610282a0e6) | Jul 27, 2022 |
| Dell          | Latitude E6330              | Notebook    | [5ee8d985ed](https://linux-hardware.org/?probe=5ee8d985ed) | Jul 27, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [17f64584bb](https://linux-hardware.org/?probe=17f64584bb) | Jul 27, 2022 |
| Dell          | 0YF8P5 A00                  | Desktop     | [04ebe8cd88](https://linux-hardware.org/?probe=04ebe8cd88) | Jul 27, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5b4bccdf27](https://linux-hardware.org/?probe=5b4bccdf27) | Jul 27, 2022 |
| HP            | Compaq 6720s                | Notebook    | [d8546f791c](https://linux-hardware.org/?probe=d8546f791c) | Jul 27, 2022 |
| HP            | 1495                        | Desktop     | [61a8f473e2](https://linux-hardware.org/?probe=61a8f473e2) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| Acer          | TravelMate P633-M           | Notebook    | [7d346db799](https://linux-hardware.org/?probe=7d346db799) | Jul 27, 2022 |
| ASUSTek       | PN51-S1                     | Mini pc     | [6362df4235](https://linux-hardware.org/?probe=6362df4235) | Jul 27, 2022 |
| Lenovo        | ThinkPad T420 4236CTO       | Notebook    | [6797b09b3b](https://linux-hardware.org/?probe=6797b09b3b) | Jul 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [cf1f919243](https://linux-hardware.org/?probe=cf1f919243) | Jul 27, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [44954e91a2](https://linux-hardware.org/?probe=44954e91a2) | Jul 27, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [eb1ff40d2d](https://linux-hardware.org/?probe=eb1ff40d2d) | Jul 27, 2022 |
| Sony          | VPCEB26FG                   | Notebook    | [49c139799c](https://linux-hardware.org/?probe=49c139799c) | Jul 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [eeb9068dca](https://linux-hardware.org/?probe=eeb9068dca) | Jul 27, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [06fe56588b](https://linux-hardware.org/?probe=06fe56588b) | Jul 27, 2022 |
| Gigabyte      | H55M-S2H                    | Desktop     | [a9a6ab85ac](https://linux-hardware.org/?probe=a9a6ab85ac) | Jul 27, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [b76e9e02fa](https://linux-hardware.org/?probe=b76e9e02fa) | Jul 27, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [0cfb15d654](https://linux-hardware.org/?probe=0cfb15d654) | Jul 27, 2022 |
| ASRock        | FM2A88X-ITX+                | Desktop     | [24e0844619](https://linux-hardware.org/?probe=24e0844619) | Jul 27, 2022 |
| Acer          | IPXHW-RL                    | Desktop     | [d99b7cb71e](https://linux-hardware.org/?probe=d99b7cb71e) | Jul 27, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6af993caf7](https://linux-hardware.org/?probe=6af993caf7) | Jul 27, 2022 |
| Intel         | DH67VR AAG27177-201         | Desktop     | [3aeca135cd](https://linux-hardware.org/?probe=3aeca135cd) | Jul 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [faf9360275](https://linux-hardware.org/?probe=faf9360275) | Jul 26, 2022 |
| Toshiba       | Satellite C870D-116         | Notebook    | [d92af8246c](https://linux-hardware.org/?probe=d92af8246c) | Jul 26, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [05947b595a](https://linux-hardware.org/?probe=05947b595a) | Jul 26, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [e487b063ea](https://linux-hardware.org/?probe=e487b063ea) | Jul 26, 2022 |
| HP            | ProBook 645 G1              | Notebook    | [457c35707a](https://linux-hardware.org/?probe=457c35707a) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [17954b8ac5](https://linux-hardware.org/?probe=17954b8ac5) | Jul 26, 2022 |
| Dell          | 0C27VV A03                  | Desktop     | [c1c4edd1e5](https://linux-hardware.org/?probe=c1c4edd1e5) | Jul 26, 2022 |
| Acer          | Aspire 3810T                | Notebook    | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [f9003ad850](https://linux-hardware.org/?probe=f9003ad850) | Jul 26, 2022 |
| Dell          | Latitude 131L               | Notebook    | [ec8717bc3f](https://linux-hardware.org/?probe=ec8717bc3f) | Jul 26, 2022 |
| HP            | 8446                        | All in one  | [ad79d02ff6](https://linux-hardware.org/?probe=ad79d02ff6) | Jul 26, 2022 |
| Dell          | Latitude 3300               | Notebook    | [64cf4b87d9](https://linux-hardware.org/?probe=64cf4b87d9) | Jul 26, 2022 |
| Toshiba       | dynabook R734/K             | Notebook    | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [5eb6c551b0](https://linux-hardware.org/?probe=5eb6c551b0) | Jul 26, 2022 |
| Login Info... | LOG-H310M-G                 | Desktop     | [f02a0ed6dd](https://linux-hardware.org/?probe=f02a0ed6dd) | Jul 26, 2022 |
| Acer          | Aspire XC-830               | Desktop     | [02572035c8](https://linux-hardware.org/?probe=02572035c8) | Jul 26, 2022 |
| Dell          | 04YP6J A02                  | Desktop     | [8161693c82](https://linux-hardware.org/?probe=8161693c82) | Jul 26, 2022 |
| Pegatron      | 2AE2                        | Desktop     | [772ded1d83](https://linux-hardware.org/?probe=772ded1d83) | Jul 25, 2022 |
| Dell          | 0V8WGR A01                  | Desktop     | [76ddff41fc](https://linux-hardware.org/?probe=76ddff41fc) | Jul 25, 2022 |
| Dell          | Vostro 15-3568              | Notebook    | [da71f235a2](https://linux-hardware.org/?probe=da71f235a2) | Jul 25, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [e470dff38f](https://linux-hardware.org/?probe=e470dff38f) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [660665c762](https://linux-hardware.org/?probe=660665c762) | Jul 25, 2022 |
| Lenovo        | ThinkCentre M58p 6137B28    | Desktop     | [5473e97fa6](https://linux-hardware.org/?probe=5473e97fa6) | Jul 25, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0fe12d0d48](https://linux-hardware.org/?probe=0fe12d0d48) | Jul 25, 2022 |
| Acer          | Aspire 5741G                | Notebook    | [a4f8482423](https://linux-hardware.org/?probe=a4f8482423) | Jul 25, 2022 |
| Gigabyte      | H170M-D3H-GSM-CF            | Desktop     | [ace82a6273](https://linux-hardware.org/?probe=ace82a6273) | Jul 25, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [375ba933ba](https://linux-hardware.org/?probe=375ba933ba) | Jul 25, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [e6b9106560](https://linux-hardware.org/?probe=e6b9106560) | Jul 24, 2022 |
| Wistron       | ProLiant ML110 G5           | Desktop     | [fdb0300292](https://linux-hardware.org/?probe=fdb0300292) | Jul 24, 2022 |
| Dell          | 0VHWTR A01                  | Desktop     | [9796d6eca3](https://linux-hardware.org/?probe=9796d6eca3) | Jul 24, 2022 |
| Lenovo        | ThinkPad P50 20EN0008GE     | Notebook    | [93ec0d85ab](https://linux-hardware.org/?probe=93ec0d85ab) | Jul 24, 2022 |
| Toshiba       | Portable PC                 | Notebook    | [00cd85e866](https://linux-hardware.org/?probe=00cd85e866) | Jul 24, 2022 |
| Apple         | MacBookAir9,1               | Notebook    | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [7923ed68b5](https://linux-hardware.org/?probe=7923ed68b5) | Jul 24, 2022 |
| HP            | Notebook                    | Notebook    | [17893fb905](https://linux-hardware.org/?probe=17893fb905) | Jul 24, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [7af6c5cebe](https://linux-hardware.org/?probe=7af6c5cebe) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | Notebook    | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [60af40882b](https://linux-hardware.org/?probe=60af40882b) | Jul 24, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [7bb0cce634](https://linux-hardware.org/?probe=7bb0cce634) | Jul 24, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ea3f7e3b48](https://linux-hardware.org/?probe=ea3f7e3b48) | Jul 23, 2022 |
| Dell          | Latitude E6430              | Notebook    | [8bc3b0f962](https://linux-hardware.org/?probe=8bc3b0f962) | Jul 23, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c4c41ad0b5](https://linux-hardware.org/?probe=c4c41ad0b5) | Jul 23, 2022 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [dc8bafd932](https://linux-hardware.org/?probe=dc8bafd932) | Jul 23, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [bad4adf823](https://linux-hardware.org/?probe=bad4adf823) | Jul 23, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [72a44c6eea](https://linux-hardware.org/?probe=72a44c6eea) | Jul 23, 2022 |
| Pegatron      | NARRA5                      | Desktop     | [368503425d](https://linux-hardware.org/?probe=368503425d) | Jul 23, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [7e7606e64d](https://linux-hardware.org/?probe=7e7606e64d) | Jul 23, 2022 |
| AZW           | GT-R                        | Notebook    | [eb7604ea1c](https://linux-hardware.org/?probe=eb7604ea1c) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | Notebook    | [fe5dae3d4a](https://linux-hardware.org/?probe=fe5dae3d4a) | Jul 22, 2022 |
| HP            | 0A68h                       | Desktop     | [cc4b39e6d0](https://linux-hardware.org/?probe=cc4b39e6d0) | Jul 22, 2022 |
| Lenovo        | ThinkPad T61 6458W4B        | Notebook    | [3d51bdb900](https://linux-hardware.org/?probe=3d51bdb900) | Jul 22, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [8fc99169c3](https://linux-hardware.org/?probe=8fc99169c3) | Jul 22, 2022 |
| Lenovo        | ThinkPad Helix 36986EU      | Notebook    | [294d96aff6](https://linux-hardware.org/?probe=294d96aff6) | Jul 22, 2022 |
| Positivo      | J14AL11                     | Notebook    | [7510e905d8](https://linux-hardware.org/?probe=7510e905d8) | Jul 22, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [80dcd8a0f7](https://linux-hardware.org/?probe=80dcd8a0f7) | Jul 22, 2022 |
| Gigabyte      | Z87-HD3                     | Desktop     | [e6bf6ea62f](https://linux-hardware.org/?probe=e6bf6ea62f) | Jul 21, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [321d2817a3](https://linux-hardware.org/?probe=321d2817a3) | Jul 21, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [56ce195301](https://linux-hardware.org/?probe=56ce195301) | Jul 21, 2022 |
| HP            | Notebook                    | Notebook    | [e859de5718](https://linux-hardware.org/?probe=e859de5718) | Jul 21, 2022 |
| Dell          | Latitude 3310               | Notebook    | [bc6103f96b](https://linux-hardware.org/?probe=bc6103f96b) | Jul 21, 2022 |
| HP            | 1998                        | Desktop     | [82c8302941](https://linux-hardware.org/?probe=82c8302941) | Jul 21, 2022 |
| Dell          | Latitude 3310               | Notebook    | [abe159e82a](https://linux-hardware.org/?probe=abe159e82a) | Jul 21, 2022 |
| Dell          | Latitude 3310               | Notebook    | [d90f147df3](https://linux-hardware.org/?probe=d90f147df3) | Jul 21, 2022 |
| Dell          | Latitude 3310               | Notebook    | [324b95a49a](https://linux-hardware.org/?probe=324b95a49a) | Jul 21, 2022 |
| METAPHYUNI    | MetamechBook                | Notebook    | [169a9a0636](https://linux-hardware.org/?probe=169a9a0636) | Jul 21, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Lenovo        | 1.0                         | Desktop     | [e520e716cf](https://linux-hardware.org/?probe=e520e716cf) | Jul 21, 2022 |
| Dell          | Latitude E5450              | Notebook    | [c8243bf1a8](https://linux-hardware.org/?probe=c8243bf1a8) | Jul 20, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [34942a8abc](https://linux-hardware.org/?probe=34942a8abc) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [c1d1e739cf](https://linux-hardware.org/?probe=c1d1e739cf) | Jul 20, 2022 |
| Acer          | Veriton M290                | Desktop     | [647393aa0c](https://linux-hardware.org/?probe=647393aa0c) | Jul 20, 2022 |
| PCChips       | A15G                        | Desktop     | [4cdd689308](https://linux-hardware.org/?probe=4cdd689308) | Jul 20, 2022 |
| Dell          | Latitude 3190 2-in-1        | Convertible | [762e21d62f](https://linux-hardware.org/?probe=762e21d62f) | Jul 20, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [fe2f5a993c](https://linux-hardware.org/?probe=fe2f5a993c) | Jul 20, 2022 |
| Dell          | Latitude 3310               | Notebook    | [086f88be40](https://linux-hardware.org/?probe=086f88be40) | Jul 20, 2022 |
| Dell          | Inspiron 5579               | Notebook    | [52e88ad171](https://linux-hardware.org/?probe=52e88ad171) | Jul 20, 2022 |
| Dell          | Latitude 3310               | Notebook    | [0cb2abc6bc](https://linux-hardware.org/?probe=0cb2abc6bc) | Jul 20, 2022 |
| Dell          | Latitude 3310               | Notebook    | [dbd9b101c2](https://linux-hardware.org/?probe=dbd9b101c2) | Jul 20, 2022 |
| Dell          | Latitude 5285               | Notebook    | [2b46125d79](https://linux-hardware.org/?probe=2b46125d79) | Jul 20, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_4.3/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003       | 3555      | 96.47%  |
| 5.16.13-desktop-1omv4003      | 95        | 2.58%   |
| 5.17.1-desktop-2omv4050       | 17        | 0.46%   |
| 5.14.14-desktop-1omv4050      | 4         | 0.11%   |
| 5.16.5-desktop-2omv4003       | 3         | 0.08%   |
| 5.17.1-desktop-clang-2omv4050 | 2         | 0.05%   |
| 5.16.9-desktop-1omv4003       | 2         | 0.05%   |
| 5.16.3-desktop-2omv4050       | 2         | 0.05%   |
| 5.17.7-desktop-1omv4090       | 1         | 0.03%   |
| 5.16.9-desktop-1omv4050       | 1         | 0.03%   |
| 5.16.7-desktop-clang-1omv4003 | 1         | 0.03%   |
| 5.15.14-1-lts                 | 1         | 0.03%   |
| 5.10.14-desktop-1omv4002      | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16.7  | 3556      | 96.5%   |
| 5.16.13 | 95        | 2.58%   |
| 5.17.1  | 19        | 0.52%   |
| 5.14.14 | 4         | 0.11%   |
| 5.16.9  | 3         | 0.08%   |
| 5.16.5  | 3         | 0.08%   |
| 5.16.3  | 2         | 0.05%   |
| 5.17.7  | 1         | 0.03%   |
| 5.15.14 | 1         | 0.03%   |
| 5.10.14 | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.16    | 3658      | 99.29%  |
| 5.17    | 20        | 0.54%   |
| 5.14    | 4         | 0.11%   |
| 5.15    | 1         | 0.03%   |
| 5.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3684      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDE5    | 3671      | 99.65%  |
| LXQt    | 7         | 0.19%   |
| Unknown | 6         | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3662      | 99.4%   |
| Wayland | 22        | 0.6%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| SDDM | 3684      | 100%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 2096      | 56.88%  |
| de_DE | 341       | 9.25%   |
| ru_RU | 179       | 4.86%   |
| fr_FR | 170       | 4.61%   |
| pt_BR | 146       | 3.96%   |
| it_IT | 100       | 2.71%   |
| pl_PL | 97        | 2.63%   |
| es_ES | 71        | 1.93%   |
| en_GB | 70        | 1.9%    |
| de_AT | 38        | 1.03%   |
| es_AR | 35        | 0.95%   |
| cs_CZ | 33        | 0.9%    |
| es_MX | 31        | 0.84%   |
| en_IN | 24        | 0.65%   |
| en_CA | 19        | 0.52%   |
| pt_PT | 18        | 0.49%   |
| hu_HU | 17        | 0.46%   |
| tr_TR | 16        | 0.43%   |
| de_CH | 15        | 0.41%   |
| nl_NL | 14        | 0.38%   |
| es_CO | 14        | 0.38%   |
| en_AU | 14        | 0.38%   |
| fr_CA | 13        | 0.35%   |
| es_CL | 12        | 0.33%   |
| nl_BE | 9         | 0.24%   |
| ru_UA | 8         | 0.22%   |
| fr_BE | 8         | 0.22%   |
| es_VE | 8         | 0.22%   |
| es_PE | 6         | 0.16%   |
| nb_NO | 5         | 0.14%   |
| es_CR | 5         | 0.14%   |
| da_DK | 5         | 0.14%   |
| ro_RO | 4         | 0.11%   |
| fr_CH | 4         | 0.11%   |
| uk_UA | 3         | 0.08%   |
| es_UY | 3         | 0.08%   |
| es_SV | 3         | 0.08%   |
| es_EC | 3         | 0.08%   |
| en_ZA | 3         | 0.08%   |
| es_PY | 2         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1954      | 53.04%  |
| BIOS | 1730      | 46.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Overlay  | 3079      | 83.55%  |
| Ext4     | 594       | 16.12%  |
| Xfs      | 4         | 0.11%   |
| F2fs     | 3         | 0.08%   |
| Btrfs    | 3         | 0.08%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 2476      | 67.19%  |
| MBR     | 1193      | 32.37%  |
| Unknown | 16        | 0.43%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2060      | 55.9%   |
| No        | 1625      | 44.1%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1855      | 50.35%  |
| Yes       | 1829      | 49.65%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ASUSTek Computer      | 584       | 15.85%  |
| Dell                  | 519       | 14.09%  |
| Hewlett-Packard       | 476       | 12.92%  |
| Lenovo                | 436       | 11.83%  |
| Gigabyte Technology   | 326       | 8.85%   |
| Acer                  | 239       | 6.49%   |
| MSI                   | 216       | 5.86%   |
| ASRock                | 157       | 4.26%   |
| Toshiba               | 86        | 2.33%   |
| Intel                 | 81        | 2.2%    |
| Fujitsu               | 58        | 1.57%   |
| Apple                 | 52        | 1.41%   |
| Sony                  | 38        | 1.03%   |
| Samsung Electronics   | 35        | 0.95%   |
| Positivo              | 26        | 0.71%   |
| Biostar               | 23        | 0.62%   |
| Foxconn               | 22        | 0.6%    |
| Packard Bell          | 20        | 0.54%   |
| Medion                | 20        | 0.54%   |
| Unknown               | 17        | 0.46%   |
| Pegatron              | 14        | 0.38%   |
| TUXEDO                | 10        | 0.27%   |
| ECS                   | 10        | 0.27%   |
| BESSTAR Tech          | 10        | 0.27%   |
| Fujitsu Siemens       | 9         | 0.24%   |
| AZW                   | 9         | 0.24%   |
| Alienware             | 9         | 0.24%   |
| Philco                | 8         | 0.22%   |
| HUAWEI                | 8         | 0.22%   |
| LG Electronics        | 7         | 0.19%   |
| Chuwi                 | 7         | 0.19%   |
| Shuttle               | 6         | 0.16%   |
| Notebook              | 6         | 0.16%   |
| eMachines             | 6         | 0.16%   |
| Compaq                | 6         | 0.16%   |
| Supermicro            | 5         | 0.14%   |
| Microsoft             | 5         | 0.14%   |
| Gateway               | 5         | 0.14%   |
| Positivo Bahia - VAIO | 4         | 0.11%   |
| Digibras              | 4         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Dell Latitude 3120            | 48        | 1.3%    |
| Dell Latitude 3190 2-in-1     | 34        | 0.92%   |
| ASUS All Series               | 32        | 0.87%   |
| Unknown                       | 32        | 0.87%   |
| Dell Latitude 3310            | 29        | 0.79%   |
| Gigabyte H410M H V3           | 27        | 0.73%   |
| ASUS SABERTOOTH Z77           | 19        | 0.52%   |
| HP Notebook                   | 14        | 0.38%   |
| Dell OptiPlex 7010            | 14        | 0.38%   |
| Lenovo IdeaPad 1 14ADA05 82GW | 11        | 0.3%    |
| HP Pavilion g6                | 9         | 0.24%   |
| Dell OptiPlex 780             | 9         | 0.24%   |
| Intel H61                     | 8         | 0.22%   |
| Dell Latitude 3300            | 8         | 0.22%   |
| ASUS PRIME B450M-A II         | 8         | 0.22%   |
| HP Pavilion dv6               | 7         | 0.19%   |
| Dell OptiPlex 790             | 7         | 0.19%   |
| Dell Latitude E7450           | 7         | 0.19%   |
| Sony VGN-FZ31Z                | 6         | 0.16%   |
| Positivo Mobile               | 6         | 0.16%   |
| MSI MS-7C91                   | 6         | 0.16%   |
| MSI MS-7C37                   | 6         | 0.16%   |
| MSI MS-7A38                   | 6         | 0.16%   |
| MSI MS-7721                   | 6         | 0.16%   |
| HP Laptop 14-fq0xxx           | 6         | 0.16%   |
| HP EliteDesk 800 G1 SFF       | 6         | 0.16%   |
| HP Compaq Pro 6300 SFF        | 6         | 0.16%   |
| Dell XPS 15 9530              | 6         | 0.16%   |
| Dell Precision M6800          | 6         | 0.16%   |
| Dell OptiPlex 9020            | 6         | 0.16%   |
| Dell OptiPlex 7020            | 6         | 0.16%   |
| Dell Latitude E7240           | 6         | 0.16%   |
| Dell Latitude E6430           | 6         | 0.16%   |
| Dell Latitude E6420           | 6         | 0.16%   |
| Dell Latitude 3189            | 6         | 0.16%   |
| ASUS ROG STRIX B550-F GAMING  | 6         | 0.16%   |
| Acer Aspire A515-51G          | 6         | 0.16%   |
| MSI MS-7C84                   | 5         | 0.14%   |
| MSI MS-7C02                   | 5         | 0.14%   |
| MSI MS-7B79                   | 5         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Latitude         | 260       | 7.06%   |
| Acer Aspire           | 165       | 4.48%   |
| Lenovo ThinkPad       | 137       | 3.72%   |
| Lenovo IdeaPad        | 115       | 3.12%   |
| Dell OptiPlex         | 92        | 2.5%    |
| HP Pavilion           | 89        | 2.42%   |
| HP Compaq             | 72        | 1.95%   |
| ASUS PRIME            | 72        | 1.95%   |
| Toshiba Satellite     | 71        | 1.93%   |
| Dell Inspiron         | 68        | 1.85%   |
| HP Laptop             | 56        | 1.52%   |
| Lenovo ThinkCentre    | 53        | 1.44%   |
| HP ProBook            | 43        | 1.17%   |
| ASUS VivoBook         | 38        | 1.03%   |
| ASUS TUF              | 35        | 0.95%   |
| ASUS ROG              | 34        | 0.92%   |
| ASUS All              | 32        | 0.87%   |
| Unknown               | 32        | 0.87%   |
| Gigabyte H410M        | 31        | 0.84%   |
| Dell Precision        | 30        | 0.81%   |
| HP EliteDesk          | 25        | 0.68%   |
| HP EliteBook          | 25        | 0.68%   |
| Fujitsu LIFEBOOK      | 25        | 0.68%   |
| Dell XPS              | 25        | 0.68%   |
| ASUS SABERTOOTH       | 25        | 0.68%   |
| HP ProDesk            | 23        | 0.62%   |
| Fujitsu ESPRIMO       | 21        | 0.57%   |
| Dell Vostro           | 20        | 0.54%   |
| Lenovo IdeaCentre     | 18        | 0.49%   |
| ASUS M5A78L-M         | 16        | 0.43%   |
| Packard Bell EasyNote | 14        | 0.38%   |
| HP Notebook           | 14        | 0.38%   |
| Acer Swift            | 13        | 0.35%   |
| Gigabyte B450M        | 12        | 0.33%   |
| Acer Nitro            | 12        | 0.33%   |
| Acer Extensa          | 11        | 0.3%    |
| Lenovo Yoga           | 10        | 0.27%   |
| HP ENVY               | 10        | 0.27%   |
| Gigabyte X570         | 10        | 0.27%   |
| Intel H61             | 9         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 356       | 9.66%   |
| 2011    | 321       | 8.71%   |
| 2021    | 308       | 8.36%   |
| 2013    | 304       | 8.25%   |
| 2019    | 299       | 8.12%   |
| 2020    | 292       | 7.93%   |
| 2018    | 259       | 7.03%   |
| 2014    | 247       | 6.7%    |
| 2010    | 240       | 6.51%   |
| 2016    | 194       | 5.27%   |
| 2017    | 184       | 4.99%   |
| 2015    | 175       | 4.75%   |
| 2009    | 163       | 4.42%   |
| 2008    | 156       | 4.23%   |
| 2007    | 108       | 2.93%   |
| 2006    | 50        | 1.36%   |
| 2022    | 20        | 0.54%   |
| 2005    | 4         | 0.11%   |
| Unknown | 4         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1730      | 46.96%  |
| Desktop     | 1698      | 46.09%  |
| Convertible | 115       | 3.12%   |
| Mini pc     | 60        | 1.63%   |
| All in one  | 59        | 1.6%    |
| Tablet      | 11        | 0.3%    |
| Server      | 11        | 0.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3684      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3679      | 99.86%  |
| Yes  | 5         | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1079      | 29.29%  |
| 3.01-4.0        | 926       | 25.14%  |
| 8.01-16.0       | 651       | 17.67%  |
| 16.01-24.0      | 545       | 14.79%  |
| 32.01-64.0      | 220       | 5.97%   |
| 1.01-2.0        | 116       | 3.15%   |
| 24.01-32.0      | 47        | 1.28%   |
| 2.01-3.0        | 45        | 1.22%   |
| 64.01-256.0     | 45        | 1.22%   |
| 0.51-1.0        | 8         | 0.22%   |
| More than 256.0 | 2         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 2747      | 74.57%  |
| 0.51-1.0  | 585       | 15.88%  |
| 2.01-3.0  | 261       | 7.08%   |
| 0.01-0.5  | 42        | 1.14%   |
| 3.01-4.0  | 26        | 0.71%   |
| 4.01-8.0  | 15        | 0.41%   |
| 8.01-16.0 | 8         | 0.22%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 2144      | 58.2%   |
| 2      | 925       | 25.11%  |
| 3      | 293       | 7.95%   |
| 4      | 149       | 4.04%   |
| 0      | 68        | 1.85%   |
| 5      | 56        | 1.52%   |
| 6      | 24        | 0.65%   |
| 7      | 9         | 0.24%   |
| 8      | 6         | 0.16%   |
| 9      | 4         | 0.11%   |
| 12     | 3         | 0.08%   |
| 15     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |
| 10     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1876      | 50.92%  |
| Yes       | 1808      | 49.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3292      | 89.36%  |
| No        | 392       | 10.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2536      | 68.84%  |
| No        | 1148      | 31.16%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1894      | 51.41%  |
| No        | 1790      | 48.59%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 462       | 12.54%  |
| USA         | 436       | 11.83%  |
| Brazil      | 239       | 6.49%   |
| France      | 232       | 6.3%    |
| Russia      | 214       | 5.81%   |
| Netherlands | 188       | 5.1%    |
| Poland      | 175       | 4.75%   |
| Italy       | 153       | 4.15%   |
| UK          | 112       | 3.04%   |
| Spain       | 100       | 2.71%   |
| Canada      | 96        | 2.61%   |
| India       | 72        | 1.95%   |
| Australia   | 68        | 1.85%   |
| Mexico      | 63        | 1.71%   |
| Austria     | 51        | 1.38%   |
| Japan       | 48        | 1.3%    |
| Czechia     | 47        | 1.28%   |
| Indonesia   | 46        | 1.25%   |
| Argentina   | 46        | 1.25%   |
| Portugal    | 45        | 1.22%   |
| Ukraine     | 42        | 1.14%   |
| Switzerland | 39        | 1.06%   |
| Sweden      | 35        | 0.95%   |
| Romania     | 34        | 0.92%   |
| Turkey      | 33        | 0.9%    |
| Colombia    | 30        | 0.81%   |
| Hungary     | 28        | 0.76%   |
| Belgium     | 28        | 0.76%   |
| Serbia      | 24        | 0.65%   |
| Slovakia    | 22        | 0.6%    |
| Finland     | 20        | 0.54%   |
| China       | 19        | 0.52%   |
| Bulgaria    | 19        | 0.52%   |
| Greece      | 18        | 0.49%   |
| Egypt       | 17        | 0.46%   |
| Chile       | 17        | 0.46%   |
| Peru        | 16        | 0.43%   |
| New Zealand | 15        | 0.41%   |
| Israel      | 15        | 0.41%   |
| Venezuela   | 14        | 0.38%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Schagen        | 137       | 3.72%   |
| Moscow         | 43        | 1.17%   |
| Berlin         | 32        | 0.87%   |
| Sao Paulo      | 31        | 0.84%   |
| Paris          | 29        | 0.79%   |
| Vienna         | 26        | 0.71%   |
| Milan          | 23        | 0.62%   |
| Warsaw         | 22        | 0.6%    |
| Gonikoppal     | 22        | 0.6%    |
| Sydney         | 20        | 0.54%   |
| Strzyzow       | 17        | 0.46%   |
| Prague         | 16        | 0.43%   |
| Munich         | 16        | 0.43%   |
| Mexico City    | 15        | 0.41%   |
| Istanbul       | 15        | 0.41%   |
| Hamburg        | 15        | 0.41%   |
| Belgrade       | 15        | 0.41%   |
| St Petersburg  | 14        | 0.38%   |
| Rio de Janeiro | 13        | 0.35%   |
| Lima           | 12        | 0.33%   |
| Krakow         | 12        | 0.33%   |
| Jakarta        | 12        | 0.33%   |
| Cascais        | 11        | 0.3%    |
| Cairo          | 11        | 0.3%    |
| Brisbane       | 11        | 0.3%    |
| Bengaluru      | 11        | 0.3%    |
| Wroclaw        | 10        | 0.27%   |
| Rome           | 10        | 0.27%   |
| Madrid         | 10        | 0.27%   |
| Buenos Aires   | 10        | 0.27%   |
| Zagreb         | 9         | 0.24%   |
| San Jose       | 9         | 0.24%   |
| Kyiv           | 9         | 0.24%   |
| Helsinki       | 9         | 0.24%   |
| Dortmund       | 9         | 0.24%   |
| Curitiba       | 9         | 0.24%   |
| Barcelona      | 9         | 0.24%   |
| Yekaterinburg  | 8         | 0.22%   |
| Montreal       | 8         | 0.22%   |
| Gdansk         | 8         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 894       | 1067   | 16.83%  |
| Seagate             | 780       | 938    | 14.68%  |
| Samsung Electronics | 692       | 821    | 13.03%  |
| Toshiba             | 370       | 393    | 6.97%   |
| Kingston            | 311       | 331    | 5.85%   |
| Crucial             | 246       | 284    | 4.63%   |
| SanDisk             | 218       | 242    | 4.1%    |
| Hitachi             | 210       | 218    | 3.95%   |
| Unknown             | 140       | 151    | 2.64%   |
| A-DATA Technology   | 136       | 144    | 2.56%   |
| SK hynix            | 131       | 135    | 2.47%   |
| HGST                | 96        | 106    | 1.81%   |
| Intel               | 66        | 71     | 1.24%   |
| China               | 50        | 54     | 0.94%   |
| Micron Technology   | 49        | 49     | 0.92%   |
| Unknown             | 38        | 38     | 0.72%   |
| PNY                 | 37        | 44     | 0.7%    |
| GOODRAM             | 36        | 38     | 0.68%   |
| LITEON              | 35        | 35     | 0.66%   |
| Intenso             | 34        | 34     | 0.64%   |
| SPCC                | 32        | 35     | 0.6%    |
| KIOXIA              | 32        | 32     | 0.6%    |
| ASMT                | 31        | 34     | 0.58%   |
| Patriot             | 28        | 29     | 0.53%   |
| Maxtor              | 26        | 30     | 0.49%   |
| JMicron Technology  | 26        | 27     | 0.49%   |
| Apacer              | 26        | 27     | 0.49%   |
| Gigabyte Technology | 25        | 25     | 0.47%   |
| Fujitsu             | 24        | 24     | 0.45%   |
| Corsair             | 23        | 24     | 0.43%   |
| Apple               | 23        | 23     | 0.43%   |
| SSSTC               | 22        | 22     | 0.41%   |
| Transcend           | 21        | 23     | 0.4%    |
| Phison              | 21        | 23     | 0.4%    |
| OCZ                 | 21        | 21     | 0.4%    |
| Netac               | 21        | 22     | 0.4%    |
| KingSpec            | 18        | 18     | 0.34%   |
| Hewlett-Packard     | 18        | 21     | 0.34%   |
| Silicon Motion      | 16        | 18     | 0.3%    |
| Team                | 11        | 11     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 68        | 1.17%   |
| Seagate ST500DM002-1BD142 500GB     | 54        | 0.93%   |
| Seagate ST1000DM010-2EP102 1TB      | 47        | 0.81%   |
| Kingston SA400S37120G 120GB SSD     | 41        | 0.71%   |
| Samsung SSD 860 EVO 500GB           | 40        | 0.69%   |
| Toshiba MQ01ABF050 500GB            | 38        | 0.65%   |
| Samsung SSD 860 EVO 250GB           | 38        | 0.65%   |
| Kingston SA400S37480G 480GB SSD     | 38        | 0.65%   |
| Unknown                             | 38        | 0.65%   |
| Crucial CT500MX500SSD1 500GB        | 37        | 0.64%   |
| Samsung SSD 850 EVO 250GB           | 36        | 0.62%   |
| WDC WD10EZEX-08WN4A0 1TB            | 33        | 0.57%   |
| Unknown SD/MMC/MS PRO 1TB           | 33        | 0.57%   |
| Toshiba MQ01ABD100 1TB              | 32        | 0.55%   |
| Crucial CT240BX500SSD1 240GB        | 32        | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB      | 31        | 0.53%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 31        | 0.53%   |
| Toshiba DT01ACA100 1TB              | 27        | 0.46%   |
| Seagate ST500LT012-1DG142 500GB     | 27        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB      | 27        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB         | 27        | 0.46%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 26        | 0.45%   |
| Toshiba MQ04ABF100 1TB              | 26        | 0.45%   |
| Toshiba DT01ACA050 500GB            | 26        | 0.45%   |
| Kingston SV300S37A120G 120GB SSD    | 26        | 0.45%   |
| Samsung SSD 850 EVO 500GB           | 24        | 0.41%   |
| Crucial CT480BX500SSD1 480GB        | 23        | 0.4%    |
| SK hynix BC711 NVMe 128GB           | 22        | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB      | 22        | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB      | 22        | 0.38%   |
| A-DATA SU750 256GB SSD              | 22        | 0.38%   |
| Seagate ST9500325AS 500GB           | 19        | 0.33%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 18        | 0.31%   |
| Toshiba HDWD110 1TB                 | 18        | 0.31%   |
| Seagate ST2000DM001-1ER164 2TB      | 18        | 0.31%   |
| SanDisk SSD PLUS 240GB              | 18        | 0.31%   |
| HGST HTS721010A9E630 1TB            | 18        | 0.31%   |
| HGST HTS545050A7E680 500GB          | 18        | 0.31%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 17        | 0.29%   |
| Seagate ST1000DM003-1SB102 1TB      | 17        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 768       | 917    | 31.7%   |
| WDC                 | 723       | 844    | 29.84%  |
| Toshiba             | 327       | 346    | 13.5%   |
| Hitachi             | 210       | 218    | 8.67%   |
| Samsung Electronics | 147       | 164    | 6.07%   |
| HGST                | 96        | 106    | 3.96%   |
| Unknown             | 34        | 34     | 1.4%    |
| Maxtor              | 24        | 28     | 0.99%   |
| Fujitsu             | 24        | 24     | 0.99%   |
| Apple               | 14        | 14     | 0.58%   |
| SABRENT             | 7         | 8      | 0.29%   |
| ASMT                | 6         | 9      | 0.25%   |
| WD MediaMax         | 4         | 5      | 0.17%   |
| ASMedia             | 4         | 4      | 0.17%   |
| USB3.0              | 3         | 3      | 0.12%   |
| Magnetic Data       | 3         | 3      | 0.12%   |
| JMicron Technology  | 3         | 3      | 0.12%   |
| Intenso             | 3         | 3      | 0.12%   |
| IBM/Hitachi         | 3         | 3      | 0.12%   |
| SAGE                | 2         | 2      | 0.08%   |
| HPE                 | 2         | 2      | 0.08%   |
| Hewlett-Packard     | 2         | 2      | 0.08%   |
| Unknown             | 2         | 2      | 0.08%   |
| SATAFIRM            | 1         | 1      | 0.04%   |
| RSH-339             | 1         | 1      | 0.04%   |
| Quantum             | 1         | 1      | 0.04%   |
| QC-FT-D             | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| Initio              | 1         | 1      | 0.04%   |
| Inateck             | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| Config              | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 385       | 426    | 19.28%  |
| Kingston            | 260       | 273    | 13.02%  |
| Crucial             | 210       | 240    | 10.52%  |
| SanDisk             | 193       | 212    | 9.66%   |
| WDC                 | 109       | 117    | 5.46%   |
| A-DATA Technology   | 105       | 106    | 5.26%   |
| China               | 49        | 53     | 2.45%   |
| SK hynix            | 36        | 37     | 1.8%    |
| Micron Technology   | 36        | 36     | 1.8%    |
| GOODRAM             | 34        | 34     | 1.7%    |
| PNY                 | 32        | 37     | 1.6%    |
| LITEON              | 32        | 32     | 1.6%    |
| Toshiba             | 29        | 30     | 1.45%   |
| Intenso             | 28        | 28     | 1.4%    |
| Intel               | 28        | 29     | 1.4%    |
| SPCC                | 24        | 26     | 1.2%    |
| Patriot             | 24        | 25     | 1.2%    |
| Apacer              | 24        | 24     | 1.2%    |
| Unknown             | 23        | 23     | 1.15%   |
| ASMT                | 22        | 22     | 1.1%    |
| OCZ                 | 21        | 21     | 1.05%   |
| Transcend           | 19        | 20     | 0.95%   |
| Netac               | 18        | 19     | 0.9%    |
| KingSpec            | 18        | 18     | 0.9%    |
| Gigabyte Technology | 15        | 15     | 0.75%   |
| Team                | 11        | 11     | 0.55%   |
| LITEONIT            | 11        | 11     | 0.55%   |
| Hewlett-Packard     | 11        | 13     | 0.55%   |
| Corsair             | 10        | 10     | 0.5%    |
| KIOXIA-EXCERIA      | 8         | 8      | 0.4%    |
| Lexar               | 7         | 7      | 0.35%   |
| KingFast            | 7         | 7      | 0.35%   |
| KingDian            | 7         | 7      | 0.35%   |
| Apple               | 7         | 7      | 0.35%   |
| Leven               | 6         | 6      | 0.3%    |
| TCSUNBOW            | 5         | 5      | 0.25%   |
| Seagate             | 5         | 5      | 0.25%   |
| TO Exter            | 4         | 4      | 0.2%    |
| Plextor             | 4         | 4      | 0.2%    |
| INNOVATION IT       | 4         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2061      | 2756   | 43.66%  |
| SSD     | 1712      | 2129   | 36.26%  |
| NVMe    | 770       | 886    | 16.31%  |
| MMC     | 126       | 133    | 2.67%   |
| Unknown | 52        | 64     | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3125      | 4685   | 73.56%  |
| NVMe | 753       | 861    | 17.73%  |
| SAS  | 244       | 289    | 5.74%   |
| MMC  | 126       | 133    | 2.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2473      | 3155   | 63.35%  |
| 0.51-1.0   | 1012      | 1221   | 25.92%  |
| 1.01-2.0   | 261       | 303    | 6.69%   |
| 3.01-4.0   | 57        | 80     | 1.46%   |
| 2.01-3.0   | 50        | 58     | 1.28%   |
| 4.01-10.0  | 44        | 61     | 1.13%   |
| 10.01-20.0 | 7         | 7      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2130      | 57.8%   |
| 101-250        | 495       | 13.43%  |
| 251-500        | 297       | 8.06%   |
| Unknown        | 289       | 7.84%   |
| 501-1000       | 150       | 4.07%   |
| 21-50          | 129       | 3.5%    |
| 51-100         | 126       | 3.42%   |
| 1001-2000      | 47        | 1.28%   |
| More than 3000 | 13        | 0.35%   |
| 2001-3000      | 9         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3134      | 85.07%  |
| Unknown        | 289       | 7.84%   |
| 101-250        | 72        | 1.95%   |
| 51-100         | 63        | 1.71%   |
| 21-50          | 56        | 1.52%   |
| 251-500        | 30        | 0.81%   |
| 501-1000       | 21        | 0.57%   |
| 1001-2000      | 13        | 0.35%   |
| More than 3000 | 3         | 0.08%   |
| 2001-3000      | 3         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 25        | 26     | 2.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 14        | 14     | 1.3%    |
| HGST HTS545050A7E680 500GB          | 14        | 14     | 1.3%    |
| Seagate ST9500325AS 500GB           | 12        | 12     | 1.11%   |
| Toshiba MQ01ABF050 500GB            | 11        | 11     | 1.02%   |
| HGST HTS541010A9E680 1TB            | 10        | 10     | 0.93%   |
| Seagate ST9320325AS 320GB           | 9         | 9      | 0.83%   |
| Kingston SV300S37A120G 120GB SSD    | 9         | 9      | 0.83%   |
| Hitachi HTS543232A7A384 320GB       | 9         | 9      | 0.83%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 8      | 0.74%   |
| Seagate ST3500413AS 500GB           | 8         | 8      | 0.74%   |
| Seagate ST500LT012-1DG142 500GB     | 7         | 7      | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB      | 7         | 7      | 0.65%   |
| Seagate ST1000DM003-9YN162 1TB      | 7         | 7      | 0.65%   |
| HGST HTS721010A9E630 1TB            | 7         | 8      | 0.65%   |
| HGST HTS545050A7E380 500GB          | 7         | 7      | 0.65%   |
| Toshiba MQ01ABD100 1TB              | 6         | 6      | 0.56%   |
| Toshiba MQ01ABD050 500GB            | 6         | 6      | 0.56%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 6         | 6      | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB      | 6         | 6      | 0.56%   |
| Samsung Electronics HD322HJ 320GB   | 6         | 6      | 0.56%   |
| Hitachi HTS725032A7E630 320GB       | 6         | 6      | 0.56%   |
| HGST HTS725050A7E630 500GB          | 6         | 6      | 0.56%   |
| Crucial CT240M500SSD1 240GB         | 6         | 6      | 0.56%   |
| Seagate ST9250410AS 250GB           | 5         | 5      | 0.46%   |
| Seagate ST3500418AS 500GB           | 5         | 5      | 0.46%   |
| Seagate ST1000DM003-1SB102 1TB      | 5         | 5      | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB      | 5         | 5      | 0.46%   |
| SanDisk SSD U100 256GB              | 5         | 5      | 0.46%   |
| SanDisk SSD PLUS 480GB              | 5         | 5      | 0.46%   |
| GOODRAM SSD 120GB                   | 5         | 5      | 0.46%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 4         | 4      | 0.37%   |
| WDC WD5000AAKS-00V1A0 500GB         | 4         | 4      | 0.37%   |
| WDC WD5000AADS-00S9B0 500GB         | 4         | 4      | 0.37%   |
| WDC WD3200AAJS-00L7A0 320GB         | 4         | 4      | 0.37%   |
| WDC WD20EZRZ-00Z5HB0 2TB            | 4         | 4      | 0.37%   |
| WDC WD10EZEX-08WN4A0 1TB            | 4         | 4      | 0.37%   |
| Toshiba MK1246GSX 120GB             | 4         | 4      | 0.37%   |
| Toshiba DT01ACA100 1TB              | 4         | 4      | 0.37%   |
| Toshiba DT01ACA050 500GB            | 4         | 4      | 0.37%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 275       | 293    | 26.29%  |
| WDC                 | 222       | 238    | 21.22%  |
| Hitachi             | 110       | 112    | 10.52%  |
| Toshiba             | 92        | 92     | 8.8%    |
| Samsung Electronics | 87        | 90     | 8.32%   |
| HGST                | 53        | 54     | 5.07%   |
| SanDisk             | 27        | 27     | 2.58%   |
| Kingston            | 25        | 25     | 2.39%   |
| Crucial             | 22        | 23     | 2.1%    |
| Maxtor              | 16        | 16     | 1.53%   |
| A-DATA Technology   | 15        | 15     | 1.43%   |
| Intel               | 11        | 11     | 1.05%   |
| Fujitsu             | 11        | 11     | 1.05%   |
| SK hynix            | 8         | 9      | 0.76%   |
| Micron Technology   | 8         | 8      | 0.76%   |
| GOODRAM             | 5         | 5      | 0.48%   |
| China               | 5         | 5      | 0.48%   |
| ASMT                | 4         | 4      | 0.38%   |
| Apple               | 4         | 4      | 0.38%   |
| OCZ                 | 3         | 3      | 0.29%   |
| LITEON              | 3         | 3      | 0.29%   |
| IBM/Hitachi         | 3         | 3      | 0.29%   |
| Transcend           | 2         | 2      | 0.19%   |
| SPCC                | 2         | 2      | 0.19%   |
| KingSpec            | 2         | 2      | 0.19%   |
| Hewlett-Packard     | 2         | 2      | 0.19%   |
| Corsair             | 2         | 2      | 0.19%   |
| ASMedia             | 2         | 2      | 0.19%   |
| Unknown             | 2         | 2      | 0.19%   |
| WDC WDS2            | 1         | 1      | 0.1%    |
| WD MediaMax         | 1         | 1      | 0.1%    |
| Vaseky              | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 1      | 0.1%    |
| TEXTORM             | 1         | 1      | 0.1%    |
| TCSUNBOW            | 1         | 1      | 0.1%    |
| RSH-339             | 1         | 1      | 0.1%    |
| PNY                 | 1         | 1      | 0.1%    |
| Patriot             | 1         | 1      | 0.1%    |
| Neo                 | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 1      | 0.1%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 275       | 293    | 32.39%  |
| WDC                 | 210       | 224    | 24.73%  |
| Hitachi             | 110       | 112    | 12.96%  |
| Toshiba             | 89        | 89     | 10.48%  |
| Samsung Electronics | 70        | 72     | 8.24%   |
| HGST                | 53        | 54     | 6.24%   |
| Maxtor              | 16        | 16     | 1.88%   |
| Fujitsu             | 11        | 11     | 1.3%    |
| IBM/Hitachi         | 3         | 3      | 0.35%   |
| Apple               | 3         | 3      | 0.35%   |
| ASMedia             | 2         | 2      | 0.24%   |
| WD MediaMax         | 1         | 1      | 0.12%   |
| RSH-339             | 1         | 1      | 0.12%   |
| Magnetic Data       | 1         | 1      | 0.12%   |
| Initio              | 1         | 1      | 0.12%   |
| HPE                 | 1         | 1      | 0.12%   |
| ExcelStor           | 1         | 1      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 782       | 886    | 79.96%  |
| SSD     | 185       | 191    | 18.92%  |
| NVMe    | 10        | 10     | 1.02%   |
| Unknown | 1         | 1      | 0.1%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HD103SJ 1TB                  | 3         | 3      | 8.57%   |
| Apple HDD HTS541010A9E662 1TB                    | 3         | 3      | 8.57%   |
| WDC WD3200BEVT-11ZCT0 320GB                      | 2         | 2      | 5.71%   |
| WDC WD5000BEVT-22ZAT0 500GB                      | 1         | 1      | 2.86%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 2.86%   |
| WDC WD3200AAJS-60Z0A0 320GB                      | 1         | 1      | 2.86%   |
| WDC WD2500BEVT-60ZCT1 250GB                      | 1         | 1      | 2.86%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1         | 1      | 2.86%   |
| WDC WD1600YS-23SHB0 160GB                        | 1         | 1      | 2.86%   |
| WDC WD1600BEVT-75A23T0 160GB                     | 1         | 1      | 2.86%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 2.86%   |
| Toshiba MK3265GSXN 320GB                         | 1         | 1      | 2.86%   |
| Toshiba MK3256GSY 320GB                          | 1         | 1      | 2.86%   |
| Seagate STM31000528AS 1TB                        | 1         | 1      | 2.86%   |
| Seagate ST980811AS 80GB                          | 1         | 1      | 2.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.86%   |
| Seagate ST3160215A 160GB                         | 1         | 1      | 2.86%   |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 2.86%   |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 2.86%   |
| Samsung Electronics HM160HI 160GB                | 1         | 1      | 2.86%   |
| Samsung Electronics HD502IJ 500GB                | 1         | 1      | 2.86%   |
| Samsung Electronics HD103UJ 1TB                  | 1         | 1      | 2.86%   |
| Intel SSDSA2BW160G3 160GB                        | 1         | 1      | 2.86%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 2.86%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 2.86%   |
| Hitachi HDS721010DLE630 1TB                      | 1         | 1      | 2.86%   |
| Hitachi HDP725050GLA360 500GB                    | 1         | 1      | 2.86%   |
| GOODRAM SSDPR-PX500-256-80 256GB                 | 1         | 1      | 2.86%   |
| Apple HDD HTS545050A7E362 500GB                  | 1         | 1      | 2.86%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 10     | 28.57%  |
| Samsung Electronics | 8         | 8      | 22.86%  |
| Seagate             | 4         | 4      | 11.43%  |
| Hitachi             | 4         | 4      | 11.43%  |
| Apple               | 4         | 4      | 11.43%  |
| Toshiba             | 3         | 3      | 8.57%   |
| Intel               | 1         | 1      | 2.86%   |
| GOODRAM             | 1         | 1      | 2.86%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 2925      | 4463   | 68.9%   |
| Malfunc  | 956       | 1088   | 22.52%  |
| Detected | 330       | 382    | 7.77%   |
| Failed   | 34        | 35     | 0.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2578      | 57.79%  |
| AMD                              | 787       | 17.64%  |
| Samsung Electronics              | 214       | 4.8%    |
| SanDisk                          | 112       | 2.51%   |
| SK hynix                         | 89        | 2%      |
| JMicron Technology               | 79        | 1.77%   |
| Nvidia                           | 74        | 1.66%   |
| ASMedia Technology               | 71        | 1.59%   |
| Phison Electronics               | 60        | 1.34%   |
| Marvell Technology Group         | 60        | 1.34%   |
| Kingston Technology Company      | 55        | 1.23%   |
| Silicon Motion                   | 39        | 0.87%   |
| Micron/Crucial Technology        | 39        | 0.87%   |
| KIOXIA                           | 34        | 0.76%   |
| ADATA Technology                 | 28        | 0.63%   |
| Solid State Storage Technology   | 21        | 0.47%   |
| VIA Technologies                 | 18        | 0.4%    |
| Micron Technology                | 17        | 0.38%   |
| Realtek Semiconductor            | 16        | 0.36%   |
| Toshiba America Info Systems     | 15        | 0.34%   |
| Seagate Technology               | 8         | 0.18%   |
| Union Memory (Shenzhen)          | 7         | 0.16%   |
| Broadcom / LSI                   | 7         | 0.16%   |
| Lite-On Technology               | 6         | 0.13%   |
| Silicon Integrated Systems [SiS] | 5         | 0.11%   |
| Integrated Technology Express    | 5         | 0.11%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| Silicon Image                    | 2         | 0.04%   |
| Shenzhen Longsys Electronics     | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| LSI Logic / Symbios Logic        | 2         | 0.04%   |
| Apple                            | 2         | 0.04%   |
| Unknown                          | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Biwin Storage Technology         | 1         | 0.02%   |
| Adaptec                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 462       | 8.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 201       | 3.82%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 194       | 3.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 162       | 3.08%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 126       | 2.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 120       | 2.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 115       | 2.19%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 111       | 2.11%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 104       | 1.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 102       | 1.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 101       | 1.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 100       | 1.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 96        | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                                  | 96        | 1.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 83        | 1.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 80        | 1.52%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 72        | 1.37%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 69        | 1.31%   |
| Samsung NVMe SSD Controller 980                                                         | 67        | 1.27%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 67        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 66        | 1.25%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 65        | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 64        | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 64        | 1.22%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 63        | 1.2%    |
| AMD 500 Series Chipset SATA Controller                                                  | 63        | 1.2%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 61        | 1.16%   |
| Intel SATA Controller [RAID mode]                                                       | 60        | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 58        | 1.1%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 58        | 1.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 55        | 1.05%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 51        | 0.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 51        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 51        | 0.97%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 51        | 0.97%   |
| SK hynix Gold P31 SSD                                                                   | 42        | 0.8%    |
| AMD FCH SATA Controller D                                                               | 36        | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 35        | 0.67%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 34        | 0.65%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 32        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2837      | 62.5%   |
| NVMe | 750       | 16.52%  |
| IDE  | 709       | 15.62%  |
| RAID | 233       | 5.13%   |
| SAS  | 7         | 0.15%   |
| SCSI | 3         | 0.07%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 2759      | 74.89%  |
| AMD    | 925       | 25.11%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Pentium Silver N6000 @ 1.10GHz          | 54        | 1.47%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 39        | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 30        | 0.81%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 30        | 0.81%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 28        | 0.76%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 27        | 0.73%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 0.73%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 24        | 0.65%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 24        | 0.65%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 24        | 0.65%   |
| AMD Ryzen 5 3600 6-Core Processor             | 23        | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 21        | 0.57%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 21        | 0.57%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 21        | 0.57%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 20        | 0.54%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 20        | 0.54%   |
| AMD 3020e with Radeon Graphics                | 20        | 0.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 19        | 0.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 19        | 0.52%   |
| AMD FX-8350 Eight-Core Processor              | 19        | 0.52%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 18        | 0.49%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 17        | 0.46%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 17        | 0.46%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 17        | 0.46%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 17        | 0.46%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 16        | 0.43%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 16        | 0.43%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 16        | 0.43%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 15        | 0.41%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 15        | 0.41%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 0.41%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 14        | 0.38%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 14        | 0.38%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 14        | 0.38%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 0.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.38%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 14        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 877       | 23.81%  |
| Intel Core i3           | 395       | 10.72%  |
| Intel Core i7           | 381       | 10.34%  |
| Intel Celeron           | 268       | 7.27%   |
| Intel Core 2 Duo        | 204       | 5.54%   |
| AMD Ryzen 5             | 164       | 4.45%   |
| Intel Pentium           | 139       | 3.77%   |
| AMD Ryzen 7             | 123       | 3.34%   |
| Other                   | 110       | 2.99%   |
| Intel Pentium Silver    | 99        | 2.69%   |
| AMD FX                  | 75        | 2.04%   |
| Intel Pentium Dual-Core | 65        | 1.76%   |
| Intel Xeon              | 63        | 1.71%   |
| Intel Core 2 Quad       | 57        | 1.55%   |
| AMD Ryzen 3             | 57        | 1.55%   |
| AMD A8                  | 44        | 1.19%   |
| AMD A6                  | 39        | 1.06%   |
| AMD A4                  | 39        | 1.06%   |
| AMD A10                 | 32        | 0.87%   |
| AMD Athlon              | 29        | 0.79%   |
| AMD E1                  | 28        | 0.76%   |
| AMD Phenom II X4        | 26        | 0.71%   |
| Intel Core 2            | 25        | 0.68%   |
| AMD Athlon II X2        | 25        | 0.68%   |
| Intel Pentium Dual      | 24        | 0.65%   |
| Intel Atom              | 24        | 0.65%   |
| AMD Ryzen 9             | 23        | 0.62%   |
| AMD E                   | 22        | 0.6%    |
| AMD Athlon 64 X2        | 22        | 0.6%    |
| Intel Core i9           | 16        | 0.43%   |
| AMD E2                  | 13        | 0.35%   |
| AMD Ryzen 5 PRO         | 11        | 0.3%    |
| Intel Genuine           | 10        | 0.27%   |
| AMD Sempron             | 9         | 0.24%   |
| AMD C-60                | 9         | 0.24%   |
| AMD Athlon II X4        | 9         | 0.24%   |
| Intel Pentium Gold      | 8         | 0.22%   |
| AMD Phenom              | 8         | 0.22%   |
| AMD Athlon X4           | 8         | 0.22%   |
| AMD Athlon II X3        | 7         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1864      | 50.6%   |
| 4      | 1175      | 31.89%  |
| 6      | 314       | 8.52%   |
| 8      | 172       | 4.67%   |
| 1      | 85        | 2.31%   |
| 3      | 32        | 0.87%   |
| 12     | 18        | 0.49%   |
| 16     | 13        | 0.35%   |
| 10     | 8         | 0.22%   |
| 14     | 2         | 0.05%   |
| 20     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 3671      | 99.65%  |
| 2      | 13        | 0.35%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2007      | 54.48%  |
| 1      | 1667      | 45.25%  |
| 8      | 8         | 0.22%   |
| 4      | 2         | 0.05%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3682      | 99.95%  |
| Unknown        | 2         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 298       | 8.09%   |
| 0x306a9    | 297       | 8.06%   |
| 0x306c3    | 244       | 6.62%   |
| 0x1067a    | 227       | 6.16%   |
| Unknown    | 101       | 2.74%   |
| 0x20655    | 94        | 2.55%   |
| 0x906ea    | 90        | 2.44%   |
| 0x506e3    | 87        | 2.36%   |
| 0x406e3    | 79        | 2.14%   |
| 0x306d4    | 74        | 2.01%   |
| 0x806e9    | 69        | 1.87%   |
| 0x40651    | 67        | 1.82%   |
| 0x08108109 | 67        | 1.82%   |
| 0x906c0    | 65        | 1.76%   |
| 0x6fd      | 64        | 1.74%   |
| 0x806ea    | 62        | 1.68%   |
| 0x08701021 | 62        | 1.68%   |
| 0x706a8    | 61        | 1.66%   |
| 0x906e9    | 59        | 1.6%    |
| 0x806ec    | 55        | 1.49%   |
| 0x30678    | 53        | 1.44%   |
| 0xa0655    | 49        | 1.33%   |
| 0x706a1    | 44        | 1.19%   |
| 0x10676    | 43        | 1.17%   |
| 0x0a50000c | 38        | 1.03%   |
| 0x06001119 | 38        | 1.03%   |
| 0x010000c8 | 38        | 1.03%   |
| 0x6fb      | 37        | 1%      |
| 0x20652    | 37        | 1%      |
| 0xa0653    | 35        | 0.95%   |
| 0x506c9    | 34        | 0.92%   |
| 0x706e5    | 33        | 0.9%    |
| 0x806c1    | 32        | 0.87%   |
| 0x406c4    | 32        | 0.87%   |
| 0x0800820d | 32        | 0.87%   |
| 0x08600106 | 28        | 0.76%   |
| 0x06006705 | 28        | 0.76%   |
| 0x07030105 | 27        | 0.73%   |
| 0x106e5    | 26        | 0.71%   |
| 0x06000822 | 26        | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 399       | 10.83%  |
| Haswell          | 323       | 8.77%   |
| SandyBridge      | 311       | 8.44%   |
| IvyBridge        | 308       | 8.36%   |
| Penryn           | 278       | 7.55%   |
| Skylake          | 175       | 4.75%   |
| Core             | 145       | 3.94%   |
| Westmere         | 141       | 3.83%   |
| Zen+             | 122       | 3.31%   |
| Zen 2            | 115       | 3.12%   |
| Silvermont       | 108       | 2.93%   |
| Piledriver       | 107       | 2.9%    |
| Goldmont plus    | 105       | 2.85%   |
| K10              | 102       | 2.77%   |
| CometLake        | 100       | 2.71%   |
| Zen 3            | 84        | 2.28%   |
| Broadwell        | 82        | 2.23%   |
| Zen              | 81        | 2.2%    |
| Tremont          | 65        | 1.76%   |
| Icelake          | 56        | 1.52%   |
| Excavator        | 54        | 1.47%   |
| Bobcat           | 45        | 1.22%   |
| K8 Hammer        | 43        | 1.17%   |
| Nehalem          | 41        | 1.11%   |
| Puma             | 39        | 1.06%   |
| Unknown          | 36        | 0.98%   |
| Goldmont         | 35        | 0.95%   |
| TigerLake        | 34        | 0.92%   |
| Steamroller      | 30        | 0.81%   |
| Jaguar           | 28        | 0.76%   |
| K10 Llano        | 24        | 0.65%   |
| Bonnell          | 21        | 0.57%   |
| NetBurst         | 14        | 0.38%   |
| Bulldozer        | 14        | 0.38%   |
| Alderlake Hybrid | 12        | 0.33%   |
| K8 & K10 hybrid  | 7         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2056      | 50.57%  |
| AMD                              | 1002      | 24.64%  |
| Nvidia                           | 995       | 24.47%  |
| Silicon Integrated Systems [SiS] | 4         | 0.1%    |
| VIA Technologies                 | 3         | 0.07%   |
| Matrox Electronics Systems       | 3         | 0.07%   |
| ASPEED Technology                | 2         | 0.05%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 241       | 5.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 166       | 3.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 104       | 2.5%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 103       | 2.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 86        | 2.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 76        | 1.83%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 74        | 1.78%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 67        | 1.61%   |
| Intel JasperLake [UHD Graphics]                                                          | 65        | 1.56%   |
| Intel HD Graphics 5500                                                                   | 63        | 1.51%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 62        | 1.49%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 61        | 1.47%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 58        | 1.39%   |
| Intel HD Graphics 620                                                                    | 58        | 1.39%   |
| Intel HD Graphics 530                                                                    | 58        | 1.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 56        | 1.35%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 55        | 1.32%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 54        | 1.3%    |
| Nvidia GK208B [GeForce GT 710]                                                           | 50        | 1.2%    |
| Intel UHD Graphics 620                                                                   | 50        | 1.2%    |
| AMD Cezanne                                                                              | 48        | 1.15%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 47        | 1.13%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 47        | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 1.1%    |
| AMD Renoir                                                                               | 44        | 1.06%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 43        | 1.03%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 42        | 1.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 37        | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 37        | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 36        | 0.86%   |
| Intel HD Graphics 630                                                                    | 35        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 33        | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 31        | 0.74%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 30        | 0.72%   |
| Nvidia GT218 [GeForce 210]                                                               | 29        | 0.7%    |
| AMD Lucienne                                                                             | 28        | 0.67%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 27        | 0.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 27        | 0.65%   |
| Intel HD Graphics 500                                                                    | 27        | 0.65%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 25        | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 1691      | 45.9%   |
| 1 x AMD                 | 875       | 23.75%  |
| 1 x Nvidia              | 704       | 19.11%  |
| Intel + Nvidia          | 269       | 7.3%    |
| Intel + AMD             | 61        | 1.66%   |
| 2 x AMD                 | 51        | 1.38%   |
| AMD + Nvidia            | 15        | 0.41%   |
| 2 x Nvidia              | 5         | 0.14%   |
| 1 x SiS                 | 4         | 0.11%   |
| 1 x VIA                 | 3         | 0.08%   |
| 1 x ASPEED              | 2         | 0.05%   |
| 3 x AMD                 | 1         | 0.03%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.03%   |
| Nvidia + Matrox         | 1         | 0.03%   |
| 1 x Matrox              | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3590      | 97.45%  |
| Unknown     | 91        | 2.47%   |
| Proprietary | 3         | 0.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1817      | 49.32%  |
| 0.01-0.5   | 550       | 14.93%  |
| 1.01-2.0   | 490       | 13.3%   |
| 0.51-1.0   | 404       | 10.97%  |
| 3.01-4.0   | 187       | 5.08%   |
| 7.01-8.0   | 123       | 3.34%   |
| 5.01-6.0   | 63        | 1.71%   |
| 2.01-3.0   | 30        | 0.81%   |
| 8.01-16.0  | 17        | 0.46%   |
| 16.01-24.0 | 3         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 491       | 13.24%  |
| AU Optronics            | 411       | 11.08%  |
| LG Display              | 339       | 9.14%   |
| BOE                     | 286       | 7.71%   |
| Chimei Innolux          | 277       | 7.47%   |
| Goldstar                | 223       | 6.01%   |
| Dell                    | 193       | 5.2%    |
| Hewlett-Packard         | 187       | 5.04%   |
| Acer                    | 142       | 3.83%   |
| Philips                 | 127       | 3.43%   |
| AOC                     | 118       | 3.18%   |
| BenQ                    | 81        | 2.18%   |
| Lenovo                  | 77        | 2.08%   |
| Ancor Communications    | 66        | 1.78%   |
| Chi Mei Optoelectronics | 63        | 1.7%    |
| ViewSonic               | 53        | 1.43%   |
| Apple                   | 43        | 1.16%   |
| Iiyama                  | 34        | 0.92%   |
| Sharp                   | 30        | 0.81%   |
| Sony                    | 27        | 0.73%   |
| InfoVision              | 23        | 0.62%   |
| LG Philips              | 22        | 0.59%   |
| Eizo                    | 22        | 0.59%   |
| ASUSTek Computer        | 21        | 0.57%   |
| NEC Computers           | 18        | 0.49%   |
| Toshiba                 | 17        | 0.46%   |
| HannStar                | 16        | 0.43%   |
| Fujitsu Siemens         | 15        | 0.4%    |
| PANDA                   | 13        | 0.35%   |
| Unknown                 | 10        | 0.27%   |
| Sceptre Tech            | 10        | 0.27%   |
| Panasonic               | 10        | 0.27%   |
| CPT                     | 10        | 0.27%   |
| ___                     | 9         | 0.24%   |
| TCL                     | 9         | 0.24%   |
| Hitachi                 | 9         | 0.24%   |
| Vestel Elektronik       | 8         | 0.22%   |
| MSI                     | 8         | 0.22%   |
| Medion                  | 8         | 0.22%   |
| Vizio                   | 7         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE093D 1366x768 256x144mm 11.6-inch                     | 33        | 0.88%   |
| Dell D1918H DEL2005 1366x768 410x230mm 18.5-inch                         | 22        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 20        | 0.53%   |
| AU Optronics LCD Monitor AUO202D 1920x1080 293x165mm 13.2-inch           | 20        | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 16        | 0.43%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 16        | 0.43%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 15        | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 15        | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.4%    |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.37%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 14        | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 13        | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 13        | 0.35%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 13        | 0.35%   |
| AU Optronics LCD Monitor AUO7E91 1366x768 256x144mm 11.6-inch            | 12        | 0.32%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.29%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.29%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 10        | 0.27%   |
| BOE LCD Monitor BOE0744 1366x768 256x144mm 11.6-inch                     | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 10        | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 10        | 0.27%   |
| AOC 24G1WG3 AOC2401 1920x1080 521x293mm 23.5-inch                        | 10        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 9         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 9         | 0.24%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 8         | 0.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch     | 8         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 8         | 0.21%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 8         | 0.21%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 8         | 0.21%   |
| BOE LCD Monitor BOE097B 1366x768 256x144mm 11.6-inch                     | 8         | 0.21%   |
| BOE LCD Monitor BOE07B9 1920x1080 293x165mm 13.2-inch                    | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 8         | 0.21%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.21%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                  | 7         | 0.19%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 7         | 0.19%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 7         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1419      | 39.04%  |
| 1366x768 (WXGA)    | 1007      | 27.7%   |
| 3840x2160 (4K)     | 193       | 5.31%   |
| 1600x900 (HD+)     | 186       | 5.12%   |
| 1280x1024 (SXGA)   | 149       | 4.1%    |
| 2560x1440 (QHD)    | 122       | 3.36%   |
| 1440x900 (WXGA+)   | 111       | 3.05%   |
| 1680x1050 (WSXGA+) | 105       | 2.89%   |
| 1280x800 (WXGA)    | 89        | 2.45%   |
| 1920x1200 (WUXGA)  | 67        | 1.84%   |
| 1360x768           | 38        | 1.05%   |
| 3440x1440          | 25        | 0.69%   |
| 2560x1080          | 22        | 0.61%   |
| 1920x540           | 13        | 0.36%   |
| 1024x768 (XGA)     | 12        | 0.33%   |
| 3200x1800 (QHD+)   | 11        | 0.3%    |
| 2560x1600          | 8         | 0.22%   |
| 1600x1200          | 7         | 0.19%   |
| 2160x1440          | 6         | 0.17%   |
| 1280x720 (HD)      | 6         | 0.17%   |
| 2880x1800          | 4         | 0.11%   |
| 2288x1287          | 4         | 0.11%   |
| 1920x1280          | 4         | 0.11%   |
| 1024x600           | 4         | 0.11%   |
| 2736x1824          | 3         | 0.08%   |
| 2048x1152          | 3         | 0.08%   |
| 1280x960           | 3         | 0.08%   |
| 3840x1080          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 1680x945           | 2         | 0.06%   |
| 3840x2400          | 1         | 0.03%   |
| 3840x1600          | 1         | 0.03%   |
| 3840x1200          | 1         | 0.03%   |
| 3456x2160          | 1         | 0.03%   |
| 3200x2000          | 1         | 0.03%   |
| 1400x1050          | 1         | 0.03%   |
| 1280x768           | 1         | 0.03%   |
| Unknown            | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 835       | 22.51%  |
| 13      | 316       | 8.52%   |
| 23      | 287       | 7.74%   |
| 27      | 280       | 7.55%   |
| 21      | 276       | 7.44%   |
| 17      | 244       | 6.58%   |
| 24      | 229       | 6.17%   |
| 14      | 204       | 5.5%    |
| 19      | 154       | 4.15%   |
| 11      | 134       | 3.61%   |
| 18      | 114       | 3.07%   |
| 31      | 92        | 2.48%   |
| 12      | 81        | 2.18%   |
| 22      | 79        | 2.13%   |
| 20      | 66        | 1.78%   |
| 34      | 43        | 1.16%   |
| 84      | 38        | 1.02%   |
| 32      | 27        | 0.73%   |
| Unknown | 22        | 0.59%   |
| 72      | 18        | 0.49%   |
| 54      | 16        | 0.43%   |
| 26      | 16        | 0.43%   |
| 25      | 15        | 0.4%    |
| 65      | 12        | 0.32%   |
| 40      | 12        | 0.32%   |
| 16      | 11        | 0.3%    |
| 52      | 10        | 0.27%   |
| 10      | 9         | 0.24%   |
| 48      | 7         | 0.19%   |
| 39      | 7         | 0.19%   |
| 33      | 6         | 0.16%   |
| 74      | 5         | 0.13%   |
| 46      | 5         | 0.13%   |
| 142     | 4         | 0.11%   |
| 47      | 4         | 0.11%   |
| 43      | 4         | 0.11%   |
| 29      | 4         | 0.11%   |
| 28      | 4         | 0.11%   |
| 42      | 3         | 0.08%   |
| 37      | 3         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1255      | 34.14%  |
| 501-600        | 772       | 21%     |
| 401-500        | 611       | 16.62%  |
| 201-300        | 376       | 10.23%  |
| 351-400        | 281       | 7.64%   |
| 601-700        | 124       | 3.37%   |
| 701-800        | 76        | 2.07%   |
| 1001-1500      | 63        | 1.71%   |
| 1501-2000      | 61        | 1.66%   |
| 801-900        | 25        | 0.68%   |
| Unknown        | 22        | 0.6%    |
| 901-1000       | 6         | 0.16%   |
| More than 2000 | 4         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2868      | 81.02%  |
| 16/10   | 411       | 11.61%  |
| 5/4     | 144       | 4.07%   |
| 21/9    | 45        | 1.27%   |
| 4/3     | 33        | 0.93%   |
| 3/2     | 26        | 0.73%   |
| 1.00    | 4         | 0.11%   |
| 6/5     | 3         | 0.08%   |
| 32/9    | 2         | 0.06%   |
| 1.96    | 2         | 0.06%   |
| 3.20    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 831       | 22.53%  |
| 201-250        | 698       | 18.93%  |
| 81-90          | 385       | 10.44%  |
| 151-200        | 305       | 8.27%   |
| 301-350        | 294       | 7.97%   |
| 351-500        | 171       | 4.64%   |
| 141-150        | 169       | 4.58%   |
| 71-80          | 143       | 3.88%   |
| 121-130        | 140       | 3.8%    |
| 51-60          | 134       | 3.63%   |
| More than 1000 | 114       | 3.09%   |
| 251-300        | 106       | 2.87%   |
| 61-70          | 72        | 1.95%   |
| 501-1000       | 47        | 1.27%   |
| 131-140        | 32        | 0.87%   |
| Unknown        | 22        | 0.6%    |
| 111-120        | 10        | 0.27%   |
| 41-50          | 9         | 0.24%   |
| 91-100         | 6         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1464      | 40.29%  |
| 101-120       | 1157      | 31.84%  |
| 121-160       | 734       | 20.2%   |
| 161-240       | 136       | 3.74%   |
| 1-50          | 99        | 2.72%   |
| More than 240 | 22        | 0.61%   |
| Unknown       | 22        | 0.61%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3344      | 90.77%  |
| 2     | 279       | 7.57%   |
| 0     | 43        | 1.17%   |
| 3     | 16        | 0.43%   |
| 7     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2155      | 40.33%  |
| Intel                             | 1564      | 29.27%  |
| Qualcomm Atheros                  | 687       | 12.86%  |
| Broadcom                          | 251       | 4.7%    |
| Ralink Technology                 | 80        | 1.5%    |
| Ralink                            | 72        | 1.35%   |
| Marvell Technology Group          | 69        | 1.29%   |
| Nvidia                            | 57        | 1.07%   |
| Broadcom Limited                  | 53        | 0.99%   |
| TP-Link                           | 44        | 0.82%   |
| MediaTek                          | 25        | 0.47%   |
| Samsung Electronics               | 18        | 0.34%   |
| Huawei Technologies               | 18        | 0.34%   |
| Dell                              | 17        | 0.32%   |
| Qualcomm Atheros Communications   | 16        | 0.3%    |
| Ericsson Business Mobile Networks | 16        | 0.3%    |
| JMicron Technology                | 15        | 0.28%   |
| D-Link System                     | 14        | 0.26%   |
| NetGear                           | 13        | 0.24%   |
| D-Link                            | 12        | 0.22%   |
| ASIX Electronics                  | 12        | 0.22%   |
| Motorola PCS                      | 11        | 0.21%   |
| Sierra Wireless                   | 9         | 0.17%   |
| VIA Technologies                  | 8         | 0.15%   |
| Aquantia                          | 8         | 0.15%   |
| Microsoft                         | 7         | 0.13%   |
| Hewlett-Packard                   | 7         | 0.13%   |
| Xiaomi                            | 6         | 0.11%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.09%   |
| DisplayLink                       | 5         | 0.09%   |
| ASUSTek Computer                  | 5         | 0.09%   |
| OnePlus                           | 4         | 0.07%   |
| Edimax Technology                 | 4         | 0.07%   |
| Belkin Components                 | 4         | 0.07%   |
| AVM                               | 4         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.06%   |
| Linksys                           | 3         | 0.06%   |
| Google                            | 3         | 0.06%   |
| T & A Mobile Phones               | 2         | 0.04%   |
| Spreadtrum Communications         | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1533      | 24.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 279       | 4.51%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 160       | 2.59%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 104       | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 91        | 1.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 90        | 1.46%   |
| Intel Wi-Fi 6 AX200                                               | 90        | 1.46%   |
| Intel Wireless 8265 / 8275                                        | 88        | 1.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 85        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 85        | 1.37%   |
| Intel Wireless 7265                                               | 82        | 1.33%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 66        | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 64        | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 63        | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 62        | 1%      |
| Intel Wi-Fi 6 AX201 160MHz                                        | 59        | 0.95%   |
| Intel Wireless 7260                                               | 56        | 0.91%   |
| Intel Wireless 3165                                               | 56        | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 0.87%   |
| Intel I211 Gigabit Network Connection                             | 54        | 0.87%   |
| Intel 82579V Gigabit Network Connection                           | 51        | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 50        | 0.81%   |
| Intel Wireless 8260                                               | 49        | 0.79%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 45        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 44        | 0.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 43        | 0.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 41        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 38        | 0.61%   |
| Intel Wireless 3160                                               | 37        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 34        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 34        | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 33        | 0.53%   |
| Intel Ethernet Connection (7) I219-V                              | 31        | 0.5%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 31        | 0.5%    |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 30        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                   | 28        | 0.45%   |
| Intel Ethernet Controller I225-V                                  | 28        | 0.45%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 26        | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 26        | 0.42%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1083      | 41.26%  |
| Qualcomm Atheros                      | 549       | 20.91%  |
| Realtek Semiconductor                 | 500       | 19.05%  |
| Broadcom                              | 154       | 5.87%   |
| Ralink Technology                     | 80        | 3.05%   |
| Ralink                                | 72        | 2.74%   |
| TP-Link                               | 30        | 1.14%   |
| MediaTek                              | 23        | 0.88%   |
| Broadcom Limited                      | 23        | 0.88%   |
| Qualcomm Atheros Communications       | 16        | 0.61%   |
| D-Link                                | 12        | 0.46%   |
| NetGear                               | 11        | 0.42%   |
| Dell                                  | 10        | 0.38%   |
| Sierra Wireless                       | 9         | 0.34%   |
| Microsoft                             | 7         | 0.27%   |
| D-Link System                         | 7         | 0.27%   |
| ASUSTek Computer                      | 5         | 0.19%   |
| Marvell Technology Group              | 4         | 0.15%   |
| Edimax Technology                     | 4         | 0.15%   |
| Belkin Components                     | 4         | 0.15%   |
| AVM                                   | 4         | 0.15%   |
| Linksys                               | 3         | 0.11%   |
| Hewlett-Packard                       | 3         | 0.11%   |
| IMC Networks                          | 2         | 0.08%   |
| Chu Yuen Enterprise                   | 2         | 0.08%   |
| ZyDAS                                 | 1         | 0.04%   |
| TRENDnet                              | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Qcom                                  | 1         | 0.04%   |
| Philips (or NXP)                      | 1         | 0.04%   |
| Logitec                               | 1         | 0.04%   |
| Guillemot                             | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 104       | 3.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 91        | 3.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 90        | 3.42%   |
| Intel Wi-Fi 6 AX200                                                     | 90        | 3.42%   |
| Intel Wireless 8265 / 8275                                              | 88        | 3.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 3.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 85        | 3.23%   |
| Intel Wireless 7265                                                     | 82        | 3.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 64        | 2.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 2.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 62        | 2.36%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 59        | 2.24%   |
| Intel Wireless 7260                                                     | 56        | 2.13%   |
| Intel Wireless 3165                                                     | 56        | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 50        | 1.9%    |
| Intel Wireless 8260                                                     | 49        | 1.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 45        | 1.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 1.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 41        | 1.56%   |
| Intel Wireless 3160                                                     | 37        | 1.41%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 34        | 1.29%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 34        | 1.29%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 33        | 1.25%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 30        | 1.14%   |
| Ralink MT7601U Wireless Adapter                                         | 28        | 1.06%   |
| Intel WiFi Link 5100                                                    | 26        | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 25        | 0.95%   |
| Intel Centrino Wireless-N 2230                                          | 25        | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 25        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                          | 24        | 0.91%   |
| Intel Wi-Fi 6 AX201                                                     | 23        | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 23        | 0.87%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 22        | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 22        | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 22        | 0.84%   |
| Intel Wireless-AC 9260                                                  | 21        | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 20        | 0.76%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 19        | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 18        | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 18        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1958      | 56.92%  |
| Intel                             | 831       | 24.16%  |
| Qualcomm Atheros                  | 208       | 6.05%   |
| Broadcom                          | 137       | 3.98%   |
| Marvell Technology Group          | 65        | 1.89%   |
| Nvidia                            | 57        | 1.66%   |
| Broadcom Limited                  | 30        | 0.87%   |
| Samsung Electronics               | 18        | 0.52%   |
| JMicron Technology                | 15        | 0.44%   |
| TP-Link                           | 14        | 0.41%   |
| Huawei Technologies               | 13        | 0.38%   |
| ASIX Electronics                  | 12        | 0.35%   |
| VIA Technologies                  | 8         | 0.23%   |
| Aquantia                          | 8         | 0.23%   |
| D-Link System                     | 7         | 0.2%    |
| Xiaomi                            | 6         | 0.17%   |
| Motorola PCS                      | 6         | 0.17%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.15%   |
| DisplayLink                       | 5         | 0.15%   |
| OnePlus                           | 4         | 0.12%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.09%   |
| Hewlett-Packard                   | 3         | 0.09%   |
| Google                            | 3         | 0.09%   |
| T & A Mobile Phones               | 2         | 0.06%   |
| Spreadtrum Communications         | 2         | 0.06%   |
| Qualcomm                          | 2         | 0.06%   |
| OPPO Electronics                  | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |
| MediaTek                          | 2         | 0.06%   |
| HTC (High Tech Computer)          | 2         | 0.06%   |
| 3Com                              | 2         | 0.06%   |
| vivo                              | 1         | 0.03%   |
| Sundance Technology Inc / IC Plus | 1         | 0.03%   |
| Netchip Technology                | 1         | 0.03%   |
| Mellanox Technologies             | 1         | 0.03%   |
| Lenovo                            | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |
| Emulex                            | 1         | 0.03%   |
| Adnaco Technology                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1533      | 43.68%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 279       | 7.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 160       | 4.56%   |
| Intel Ethernet Connection I217-LM                                              | 72        | 2.05%   |
| Realtek RTL8125 2.5GbE Controller                                              | 66        | 1.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 54        | 1.54%   |
| Intel I211 Gigabit Network Connection                                          | 54        | 1.54%   |
| Intel 82579V Gigabit Network Connection                                        | 51        | 1.45%   |
| Intel Ethernet Connection (2) I219-V                                           | 44        | 1.25%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 38        | 1.08%   |
| Intel Ethernet Connection (7) I219-V                                           | 31        | 0.88%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 31        | 0.88%   |
| Intel Ethernet Controller I225-V                                               | 28        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 26        | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 26        | 0.74%   |
| Nvidia MCP61 Ethernet                                                          | 26        | 0.74%   |
| Intel Ethernet Connection I217-V                                               | 24        | 0.68%   |
| Intel Ethernet Connection I218-LM                                              | 21        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                       | 21        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 20        | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 20        | 0.57%   |
| Intel Ethernet Connection (2) I219-LM                                          | 20        | 0.57%   |
| Intel Ethernet Connection I219-LM                                              | 19        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                                       | 19        | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 18        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 17        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 16        | 0.46%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 15        | 0.43%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 14        | 0.4%    |
| Intel 82574L Gigabit Network Connection                                        | 14        | 0.4%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 14        | 0.4%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 13        | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 13        | 0.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 13        | 0.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 12        | 0.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 12        | 0.34%   |
| Nvidia MCP79 Ethernet                                                          | 12        | 0.34%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 12        | 0.34%   |
| Intel Ethernet Connection (2) I218-V                                           | 12        | 0.34%   |
| Intel 82578DM Gigabit Network Connection                                       | 12        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3291      | 56.06%  |
| WiFi     | 2537      | 43.22%  |
| Modem    | 33        | 0.56%   |
| Unknown  | 9         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2003      | 55.45%  |
| WiFi     | 1609      | 44.55%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1908      | 51.79%  |
| 1     | 1680      | 45.6%   |
| 3     | 59        | 1.6%    |
| 0     | 31        | 0.84%   |
| 4     | 5         | 0.14%   |
| 5     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2630      | 71.39%  |
| Yes  | 1054      | 28.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 818       | 42.85%  |
| Realtek Semiconductor           | 195       | 10.21%  |
| Qualcomm Atheros Communications | 174       | 9.11%   |
| Broadcom                        | 125       | 6.55%   |
| Cambridge Silicon Radio         | 122       | 6.39%   |
| Lite-On Technology              | 90        | 4.71%   |
| IMC Networks                    | 76        | 3.98%   |
| Foxconn / Hon Hai               | 54        | 2.83%   |
| Apple                           | 49        | 2.57%   |
| Dell                            | 40        | 2.1%    |
| Toshiba                         | 30        | 1.57%   |
| ASUSTek Computer                | 30        | 1.57%   |
| Hewlett-Packard                 | 24        | 1.26%   |
| Ralink                          | 22        | 1.15%   |
| Alps Electric                   | 7         | 0.37%   |
| Realtek                         | 6         | 0.31%   |
| Ralink Technology               | 6         | 0.31%   |
| MediaTek                        | 6         | 0.31%   |
| Marvell Semiconductor           | 4         | 0.21%   |
| Fujitsu                         | 3         | 0.16%   |
| Foxconn International           | 3         | 0.16%   |
| Edimax Technology               | 3         | 0.16%   |
| Askey Computer                  | 3         | 0.16%   |
| Unknown                         | 3         | 0.16%   |
| Unknown                         | 2         | 0.1%    |
| TP-Link                         | 2         | 0.1%    |
| Chicony Electronics             | 2         | 0.1%    |
| Belkin Components               | 2         | 0.1%    |
| USI                             | 1         | 0.05%   |
| Taiyo Yuden                     | 1         | 0.05%   |
| SINO WEALTH                     | 1         | 0.05%   |
| Primax Electronics              | 1         | 0.05%   |
| Opticis                         | 1         | 0.05%   |
| Integrated System Solution      | 1         | 0.05%   |
| Dynex                           | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 371       | 19.43%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 122       | 6.39%   |
| Realtek Bluetooth Radio                                                             | 117       | 6.13%   |
| Intel AX201 Bluetooth                                                               | 115       | 6.02%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 108       | 5.66%   |
| Intel AX200 Bluetooth                                                               | 89        | 4.66%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 70        | 3.67%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 60        | 3.14%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 47        | 2.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 35        | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 35        | 1.83%   |
| IMC Networks Bluetooth Radio                                                        | 35        | 1.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 30        | 1.57%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 27        | 1.41%   |
| IMC Networks Bluetooth Device                                                       | 27        | 1.41%   |
| Lite-On Bluetooth Device                                                            | 26        | 1.36%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 25        | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 23        | 1.2%    |
| Ralink RT3290 Bluetooth                                                             | 22        | 1.15%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 21        | 1.1%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 20        | 1.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 20        | 1.05%   |
| Dell DW375 Bluetooth Module                                                         | 20        | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 17        | 0.89%   |
| Apple Bluetooth Host Controller                                                     | 17        | 0.89%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 16        | 0.84%   |
| Intel AX210 Bluetooth                                                               | 16        | 0.84%   |
| Apple Bluetooth USB Host Controller                                                 | 16        | 0.84%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 13        | 0.68%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 12        | 0.63%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 11        | 0.58%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 11        | 0.58%   |
| Realtek RTL8723B Bluetooth                                                          | 10        | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 10        | 0.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 10        | 0.52%   |
| Broadcom BCM2045 Bluetooth                                                          | 9         | 0.47%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 9         | 0.47%   |
| Toshiba RT Bluetooth Radio                                                          | 8         | 0.42%   |
| Broadcom HP Portable SoftSailing                                                    | 8         | 0.42%   |
| ASUS ASUS USB-BT500                                                                 | 8         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2692      | 54.6%   |
| AMD                                          | 1117      | 22.66%  |
| Nvidia                                       | 775       | 15.72%  |
| C-Media Electronics                          | 75        | 1.52%   |
| Creative Labs                                | 46        | 0.93%   |
| Logitech                                     | 33        | 0.67%   |
| Texas Instruments                            | 17        | 0.34%   |
| JMTek                                        | 14        | 0.28%   |
| Creative Technology                          | 14        | 0.28%   |
| Generalplus Technology                       | 11        | 0.22%   |
| ASUSTek Computer                             | 9         | 0.18%   |
| GN Netcom                                    | 7         | 0.14%   |
| VIA Technologies                             | 6         | 0.12%   |
| XMOS                                         | 5         | 0.1%    |
| Silicon Integrated Systems [SiS]             | 5         | 0.1%    |
| Tenx Technology                              | 4         | 0.08%   |
| Realtek Semiconductor                        | 4         | 0.08%   |
| Plantronics                                  | 4         | 0.08%   |
| Blue Microphones                             | 4         | 0.08%   |
| Sony                                         | 3         | 0.06%   |
| Samson Technologies                          | 3         | 0.06%   |
| Razer USA                                    | 3         | 0.06%   |
| Kingston Technology                          | 3         | 0.06%   |
| Focusrite-Novation                           | 3         | 0.06%   |
| Apple                                        | 3         | 0.06%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.04%   |
| Trust                                        | 2         | 0.04%   |
| SteelSeries ApS                              | 2         | 0.04%   |
| ROCCAT                                       | 2         | 0.04%   |
| PreSonus Audio Electronics                   | 2         | 0.04%   |
| No brand                                     | 2         | 0.04%   |
| M-Audio                                      | 2         | 0.04%   |
| Lenovo                                       | 2         | 0.04%   |
| Hewlett-Packard                              | 2         | 0.04%   |
| GYROCOM C&C                                  | 2         | 0.04%   |
| FiiO Electronics Technology                  | 2         | 0.04%   |
| ESS Technology                               | 2         | 0.04%   |
| Dell                                         | 2         | 0.04%   |
| Corsair                                      | 2         | 0.04%   |
| Conexant Systems                             | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 320       | 5.42%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 284       | 4.81%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 265       | 4.49%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 220       | 3.73%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 207       | 3.51%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 196       | 3.32%   |
| AMD FCH Azalia Controller                                                                         | 184       | 3.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 172       | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 155       | 2.63%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 147       | 2.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 129       | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 119       | 2.02%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 115       | 1.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 104       | 1.76%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 101       | 1.71%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 96        | 1.63%   |
| Intel Cannon Lake PCH cAVS                                                                        | 96        | 1.63%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 92        | 1.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 80        | 1.36%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 78        | 1.32%   |
| Intel Broadwell-U Audio Controller                                                                | 78        | 1.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 76        | 1.29%   |
| AMD Kabini HDMI/DP Audio                                                                          | 74        | 1.25%   |
| Intel 200 Series PCH HD Audio                                                                     | 73        | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 69        | 1.17%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 68        | 1.15%   |
| Intel 8 Series HD Audio Controller                                                                | 68        | 1.15%   |
| Intel Jasper Lake HD Audio                                                                        | 65        | 1.1%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 64        | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 62        | 1.05%   |
| Nvidia High Definition Audio Controller                                                           | 58        | 0.98%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 58        | 0.98%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 58        | 0.98%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 57        | 0.97%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 53        | 0.9%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 52        | 0.88%   |
| Intel Audio device                                                                                | 51        | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 43        | 0.73%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 41        | 0.69%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 40        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 804       | 18.36%  |
| SK hynix            | 699       | 15.97%  |
| Unknown             | 559       | 12.77%  |
| Kingston            | 550       | 12.56%  |
| Micron Technology   | 373       | 8.52%   |
| Crucial             | 222       | 5.07%   |
| Corsair             | 184       | 4.2%    |
| G.Skill             | 145       | 3.31%   |
| A-DATA Technology   | 101       | 2.31%   |
| Ramaxel Technology  | 88        | 2.01%   |
| Elpida              | 71        | 1.62%   |
| Smart               | 56        | 1.28%   |
| Unknown             | 56        | 1.28%   |
| Nanya Technology    | 54        | 1.23%   |
| Patriot             | 42        | 0.96%   |
| Unknown (ABCD)      | 39        | 0.89%   |
| Team                | 35        | 0.8%    |
| GOODRAM             | 19        | 0.43%   |
| Transcend           | 17        | 0.39%   |
| Teikon              | 16        | 0.37%   |
| AMD                 | 15        | 0.34%   |
| ASint Technology    | 11        | 0.25%   |
| Qimonda             | 10        | 0.23%   |
| CSX                 | 10        | 0.23%   |
| Apacer              | 10        | 0.23%   |
| Silicon Power       | 9         | 0.21%   |
| PNY                 | 8         | 0.18%   |
| Unifosa             | 7         | 0.16%   |
| Kingmax             | 7         | 0.16%   |
| GeIL                | 7         | 0.16%   |
| Smart Brazil        | 6         | 0.14%   |
| Goldkey             | 6         | 0.14%   |
| Toshiba             | 5         | 0.11%   |
| Multilaser          | 5         | 0.11%   |
| High Bridge         | 5         | 0.11%   |
| Avant               | 5         | 0.11%   |
| Sesame              | 4         | 0.09%   |
| OM Nanotech         | 4         | 0.09%   |
| KLEVV               | 4         | 0.09%   |
| Super Talent        | 3         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 56        | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 49        | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 45        | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 45        | 0.95%   |
| SK hynix RAM HCNNNBKMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 44        | 0.93%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.86%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 41        | 0.86%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 37        | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 0.78%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 29        | 0.61%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 28        | 0.59%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 28        | 0.59%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 27        | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 27        | 0.57%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 26        | 0.55%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 26        | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 23        | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 20        | 0.42%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 18        | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 18        | 0.38%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 18        | 0.38%   |
| Micron RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s             | 18        | 0.38%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s            | 18        | 0.38%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 17        | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 17        | 0.36%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 17        | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.36%   |
| Micron RAM Module 8GB DIMM DDR4 2666MT/s                         | 17        | 0.36%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 16        | 0.34%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 16        | 0.34%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 16        | 0.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 16        | 0.34%   |
| SK hynix RAM 0000000000-00000 8GB SODIMM DDR4 2400MT/s           | 16        | 0.34%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 16        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 15        | 0.32%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 15        | 0.32%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 15        | 0.32%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 15        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 1631      | 43.96%  |
| DDR4    | 1270      | 34.23%  |
| DDR2    | 286       | 7.71%   |
| Unknown | 161       | 4.34%   |
| SDRAM   | 160       | 4.31%   |
| LPDDR4  | 129       | 3.48%   |
| LPDDR3  | 31        | 0.84%   |
| DDR     | 28        | 0.75%   |
| DRAM    | 11        | 0.3%    |
| DDR5    | 3         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1912      | 52.2%   |
| DIMM         | 1602      | 43.73%  |
| Row Of Chips | 131       | 3.58%   |
| Chip         | 11        | 0.3%    |
| Unknown      | 4         | 0.11%   |
| RIMM         | 2         | 0.05%   |
| FB-DIMM      | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 1553      | 37.86%  |
| 8192  | 1229      | 29.96%  |
| 2048  | 799       | 19.48%  |
| 16384 | 262       | 6.39%   |
| 1024  | 189       | 4.61%   |
| 32768 | 52        | 1.27%   |
| 512   | 18        | 0.44%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1051      | 25.63%  |
| 1333    | 411       | 10.02%  |
| 2667    | 395       | 9.63%   |
| 2400    | 316       | 7.71%   |
| 3200    | 315       | 7.68%   |
| 1334    | 174       | 4.24%   |
| 800     | 159       | 3.88%   |
| 667     | 141       | 3.44%   |
| 2133    | 140       | 3.41%   |
| Unknown | 115       | 2.8%    |
| 3600    | 98        | 2.39%   |
| 1067    | 82        | 2%      |
| 1867    | 80        | 1.95%   |
| 4267    | 59        | 1.44%   |
| 2666    | 53        | 1.29%   |
| 1866    | 46        | 1.12%   |
| 1066    | 42        | 1.02%   |
| 3266    | 32        | 0.78%   |
| 2048    | 31        | 0.76%   |
| 4199    | 28        | 0.68%   |
| 533     | 27        | 0.66%   |
| 3000    | 25        | 0.61%   |
| 3400    | 24        | 0.59%   |
| 1800    | 21        | 0.51%   |
| 975     | 21        | 0.51%   |
| 400     | 20        | 0.49%   |
| 2933    | 16        | 0.39%   |
| 3866    | 15        | 0.37%   |
| 333     | 12        | 0.29%   |
| 3466    | 11        | 0.27%   |
| 8400    | 10        | 0.24%   |
| 3733    | 10        | 0.24%   |
| 2800    | 9         | 0.22%   |
| 4266    | 8         | 0.2%    |
| 1639    | 8         | 0.2%    |
| 3066    | 7         | 0.17%   |
| 3800    | 6         | 0.15%   |
| 49926   | 5         | 0.12%   |
| 4800    | 5         | 0.12%   |
| 2000    | 5         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 52        | 39.39%  |
| Brother Industries    | 31        | 23.48%  |
| Canon                 | 18        | 13.64%  |
| Samsung Electronics   | 10        | 7.58%   |
| Seiko Epson           | 8         | 6.06%   |
| Lexmark International | 5         | 3.79%   |
| Xerox                 | 2         | 1.52%   |
| Kyocera               | 2         | 1.52%   |
| Ricoh                 | 1         | 0.76%   |
| QinHeng Electronics   | 1         | 0.76%   |
| Prolific Technology   | 1         | 0.76%   |
| NXP Semiconductors    | 1         | 0.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Brother DCP-7055W                            | 4         | 3.03%   |
| HP LaserJet 1010                             | 3         | 2.27%   |
| Seiko Epson ET-4760 Series                   | 2         | 1.52%   |
| Samsung SCX-3400 Series                      | 2         | 1.52%   |
| Samsung M2070 Series                         | 2         | 1.52%   |
| Samsung M2020 Series                         | 2         | 1.52%   |
| HP LaserJet 1200                             | 2         | 1.52%   |
| HP LaserJet 1020                             | 2         | 1.52%   |
| HP LaserJet 1018                             | 2         | 1.52%   |
| HP Ink Tank Wireless 410 series              | 2         | 1.52%   |
| HP ENVY 4520 series                          | 2         | 1.52%   |
| HP ENVY 4500 series                          | 2         | 1.52%   |
| HP Deskjet 1050 J410                         | 2         | 1.52%   |
| Brother MFC-L2710DW series                   | 2         | 1.52%   |
| Brother MFC-J470DW                           | 2         | 1.52%   |
| Brother DCP-T310                             | 2         | 1.52%   |
| Xerox Phaser 6510                            | 1         | 0.76%   |
| Xerox Phaser 6010N                           | 1         | 0.76%   |
| Seiko Epson XP-2100 Series                   | 1         | 0.76%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 1         | 0.76%   |
| Seiko Epson L365 Series                      | 1         | 0.76%   |
| Seiko Epson L3210 Series                     | 1         | 0.76%   |
| Seiko Epson L120 Series                      | 1         | 0.76%   |
| Seiko Epson ET-3750 Series                   | 1         | 0.76%   |
| Samsung ML-2850 Series                       | 1         | 0.76%   |
| Samsung M267x 287x Series                    | 1         | 0.76%   |
| Samsung CLP-325 Color Laser Printer          | 1         | 0.76%   |
| Samsung CLP-310 Color Laser Printer          | 1         | 0.76%   |
| Ricoh SP 211                                 | 1         | 0.76%   |
| QinHeng CH340S                               | 1         | 0.76%   |
| Prolific PL2305 Parallel Port                | 1         | 0.76%   |
| NXP Semiconductors Printer-80                | 1         | 0.76%   |
| Lexmark International X364dn                 | 1         | 0.76%   |
| Lexmark International MS710                  | 1         | 0.76%   |
| Lexmark International MS431dn                | 1         | 0.76%   |
| Lexmark International CX410de                | 1         | 0.76%   |
| Lexmark International B2236dw                | 1         | 0.76%   |
| Kyocera ECOSYS P5021cdw                      | 1         | 0.76%   |
| Kyocera ECOSYS P2040dw                       | 1         | 0.76%   |
| HP PSC 1400                                  | 1         | 0.76%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 13        | 68.42%  |
| Seiko Epson     | 3         | 15.79%  |
| Mustek Systems  | 2         | 10.53%  |
| Hewlett-Packard | 1         | 5.26%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                  | 3         | 15.79%  |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 2         | 10.53%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 10.53%  |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 10.53%  |
| Canon CanoScan LiDE 100                                  | 2         | 10.53%  |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 5.26%   |
| Mustek Systems SNAPSCAN e22                              | 1         | 5.26%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 5.26%   |
| HP ScanJet 2400c                                         | 1         | 5.26%   |
| Canon CanoScan LiDE 600F                                 | 1         | 5.26%   |
| Canon CanoScan LiDE 210                                  | 1         | 5.26%   |
| Canon CanoScan LiDE 120                                  | 1         | 5.26%   |
| Canon CanoScan 5200F                                     | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 419       | 21.54%  |
| Realtek Semiconductor                  | 235       | 12.08%  |
| Microdia                               | 216       | 11.11%  |
| Sunplus Innovation Technology          | 115       | 5.91%   |
| IMC Networks                           | 112       | 5.76%   |
| Acer                                   | 102       | 5.24%   |
| Logitech                               | 101       | 5.19%   |
| Suyin                                  | 73        | 3.75%   |
| Cheng Uei Precision Industry (Foxlink) | 72        | 3.7%    |
| Quanta                                 | 67        | 3.44%   |
| Syntek                                 | 54        | 2.78%   |
| Lite-On Technology                     | 42        | 2.16%   |
| Apple                                  | 42        | 2.16%   |
| Silicon Motion                         | 33        | 1.7%    |
| Ricoh                                  | 30        | 1.54%   |
| Alcor Micro                            | 27        | 1.39%   |
| ALi                                    | 18        | 0.93%   |
| Microsoft                              | 17        | 0.87%   |
| Importek                               | 14        | 0.72%   |
| Z-Star Microelectronics                | 13        | 0.67%   |
| Lenovo                                 | 13        | 0.67%   |
| Luxvisions Innotech Limited            | 12        | 0.62%   |
| Sonix Technology                       | 9         | 0.46%   |
| Primax Electronics                     | 9         | 0.46%   |
| Generalplus Technology                 | 9         | 0.46%   |
| Sunplus Technology                     | 5         | 0.26%   |
| Samsung Electronics                    | 5         | 0.26%   |
| KYE Systems (Mouse Systems)            | 5         | 0.26%   |
| Hewlett-Packard                        | 5         | 0.26%   |
| DigiTech                               | 5         | 0.26%   |
| Unknown                                | 4         | 0.21%   |
| Trust                                  | 4         | 0.21%   |
| GEMBIRD                                | 4         | 0.21%   |
| Cubeternet                             | 4         | 0.21%   |
| Aveo Technology                        | 4         | 0.21%   |
| ARC International                      | 4         | 0.21%   |
| Pixart Imaging                         | 2         | 0.1%    |
| OmniVision Technologies                | 2         | 0.1%    |
| Nebraska Furniture Mart                | 2         | 0.1%    |
| MacroSilicon                           | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD            | 96        | 4.85%   |
| Realtek Integrated_Webcam_5M             | 59        | 2.98%   |
| Chicony Integrated Camera                | 55        | 2.78%   |
| Realtek Integrated_Webcam_HD             | 53        | 2.68%   |
| Sunplus Integrated_Webcam_HD             | 47        | 2.37%   |
| Chicony HD WebCam                        | 44        | 2.22%   |
| Microdia Integrated Webcam               | 27        | 1.36%   |
| Syntek Integrated Camera                 | 26        | 1.31%   |
| Logitech Webcam C270                     | 25        | 1.26%   |
| IMC Networks USB2.0 HD UVC WebCam        | 24        | 1.21%   |
| Chicony USB 2.0 Camera                   | 23        | 1.16%   |
| IMC Networks Integrated Camera           | 21        | 1.06%   |
| Realtek USB Camera                       | 20        | 1.01%   |
| Acer Integrated Camera                   | 19        | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 18        | 0.91%   |
| Chicony VGA Webcam                       | 18        | 0.91%   |
| Chicony USB2.0 VGA UVC WebCam            | 18        | 0.91%   |
| Chicony TOSHIBA Web Camera - HD          | 18        | 0.91%   |
| Microdia Integrated_Webcam_5M            | 17        | 0.86%   |
| Chicony FJ Camera                        | 16        | 0.81%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 15        | 0.76%   |
| Realtek EasyCamera                       | 15        | 0.76%   |
| Chicony Lenovo EasyCamera                | 15        | 0.76%   |
| Apple Built-in iSight                    | 15        | 0.76%   |
| Acer Lenovo EasyCamera                   | 15        | 0.76%   |
| Microdia USB 2.0 Camera                  | 14        | 0.71%   |
| Chicony HP TrueVision HD Camera          | 14        | 0.71%   |
| Chicony HD User Facing                   | 14        | 0.71%   |
| Sunplus HD WebCam                        | 13        | 0.66%   |
| Quanta HP TrueVision HD Camera           | 13        | 0.66%   |
| Realtek Lenovo EasyCamera                | 12        | 0.61%   |
| Quanta HD User Facing                    | 12        | 0.61%   |
| Logitech HD Pro Webcam C920              | 12        | 0.61%   |
| Lite-On Integrated Camera                | 12        | 0.61%   |
| Chicony EasyCamera                       | 12        | 0.61%   |
| Syntek Lenovo EasyCamera                 | 11        | 0.56%   |
| Realtek USB2.0 HD UVC WebCam             | 11        | 0.56%   |
| Logitech HD Webcam C525                  | 11        | 0.56%   |
| Lite-On HP HD Webcam                     | 11        | 0.56%   |
| Chicony USB2.0 HD UVC WebCam             | 11        | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 63        | 36%     |
| AuthenTec                  | 25        | 14.29%  |
| Upek                       | 19        | 10.86%  |
| Synaptics                  | 17        | 9.71%   |
| Elan Microelectronics      | 16        | 9.14%   |
| Shenzhen Goodix Technology | 14        | 8%      |
| LighTuning Technology      | 10        | 5.71%   |
| STMicroelectronics         | 8         | 4.57%   |
| Samsung Electronics        | 1         | 0.57%   |
| HOLTEK                     | 1         | 0.57%   |
| Focal-systems.Corp         | 1         | 0.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor      | 18        | 10.29%  |
| Validity Sensors VFS495 Fingerprint Reader                  | 16        | 9.14%   |
| Shenzhen Goodix  FingerPrint Device                         | 9         | 5.14%   |
| STMicroelectronics Fingerprint Reader                       | 8         | 4.57%   |
| Elan ELAN:Fingerprint                                       | 8         | 4.57%   |
| Elan ELAN:ARM-M4                                            | 8         | 4.57%   |
| Validity Sensors VFS491                                     | 7         | 4%      |
| AuthenTec AES2810                                           | 7         | 4%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor           | 6         | 3.43%   |
| Validity Sensors Swipe Fingerprint Sensor                   | 6         | 3.43%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 6         | 3.43%   |
| Validity Sensors VFS5011 Fingerprint Reader                 | 5         | 2.86%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 5         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                 | 5         | 2.86%   |
| AuthenTec AES1600                                           | 5         | 2.86%   |
| Unknown                                                     | 5         | 2.86%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 4         | 2.29%   |
| Shenzhen Goodix Fingerprint Reader                          | 4         | 2.29%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 3         | 1.71%   |
| Validity Sensors VFS451 Fingerprint Reader                  | 3         | 1.71%   |
| Validity Sensors VFS301 Fingerprint Reader                  | 3         | 1.71%   |
| Validity Sensors Fingerprint scanner                        | 3         | 1.71%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 3         | 1.71%   |
| LighTuning EgisTec_ES603                                    | 3         | 1.71%   |
| AuthenTec Fingerprint Sensor                                | 3         | 1.71%   |
| AuthenTec AES2550 Fingerprint Sensor                        | 3         | 1.71%   |
| Validity Sensors Synaptics WBDI                             | 2         | 1.14%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 0.57%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 1         | 0.57%   |
| Validity Sensors VFS101 Fingerprint Reader                  | 1         | 0.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 0.57%   |
| Upek TCS5B Fingerprint sensor                               | 1         | 0.57%   |
| Synaptics WBDI Device                                       | 1         | 0.57%   |
| Synaptics  WBDI                                             | 1         | 0.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 1         | 0.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader            | 1         | 0.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 1         | 0.57%   |
| Shenzhen Goodix FingerPrint                                 | 1         | 0.57%   |
| Samsung Fingerprint Sensor Device - 730B                    | 1         | 0.57%   |
| LighTuning Fingerprint Sensor                               | 1         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 71        | 54.2%   |
| O2 Micro              | 16        | 12.21%  |
| Alcor Micro           | 15        | 11.45%  |
| Upek                  | 11        | 8.4%    |
| Lenovo                | 8         | 6.11%   |
| SCM Microsystems      | 3         | 2.29%   |
| Gemalto (was Gemplus) | 3         | 2.29%   |
| Realtek Semiconductor | 2         | 1.53%   |
| Cherry                | 1         | 0.76%   |
| BIT4ID                | 1         | 0.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 32        | 24.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 22        | 16.79%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 15        | 11.45%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 10.69%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 8.4%    |
| Broadcom 5880                                                                | 11        | 8.4%    |
| Lenovo Integrated Smart Card Reader                                          | 8         | 6.11%   |
| Broadcom 58200                                                               | 5         | 3.82%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.53%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.53%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 1.53%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader                              | 1         | 0.76%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.76%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.76%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.76%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.76%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.76%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3055      | 82.93%  |
| 1     | 546       | 14.82%  |
| 2     | 74        | 2.01%   |
| 3     | 7         | 0.19%   |
| 6     | 1         | 0.03%   |
| 4     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 175       | 24.72%  |
| Graphics card            | 136       | 19.21%  |
| Chipcard                 | 127       | 17.94%  |
| Multimedia controller    | 70        | 9.89%   |
| Net/wireless             | 65        | 9.18%   |
| Bluetooth                | 45        | 6.36%   |
| Storage                  | 22        | 3.11%   |
| Communication controller | 18        | 2.54%   |
| Camera                   | 17        | 2.4%    |
| Unassigned class         | 12        | 1.69%   |
| Network                  | 6         | 0.85%   |
| Sound                    | 4         | 0.56%   |
| Wireless                 | 3         | 0.42%   |
| Flash memory             | 3         | 0.42%   |
| Net/ethernet             | 2         | 0.28%   |
| Card reader              | 2         | 0.28%   |
| Storage/raid             | 1         | 0.14%   |

