Linux in Portugal - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Portugal.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Portugal/Desktop/README.md) and [notebooks](/Location/Portugal/Notebook/README.md).

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

Total: 2572

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | M3702WFA                    | All in one  | [878dc1f9b0](https://linux-hardware.org/?probe=878dc1f9b0) | Jan 02, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [68d3d8c6be](https://linux-hardware.org/?probe=68d3d8c6be) | Jan 02, 2024 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [8701a130d2](https://linux-hardware.org/?probe=8701a130d2) | Jan 02, 2024 |
| ASUSTek       | K53SC                       | Notebook    | [1f2ddea9fa](https://linux-hardware.org/?probe=1f2ddea9fa) | Dec 31, 2023 |
| Medion        | M14L-256                    | Notebook    | [0dbbd4db74](https://linux-hardware.org/?probe=0dbbd4db74) | Dec 31, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | Notebook    | [8b28cb5a8f](https://linux-hardware.org/?probe=8b28cb5a8f) | Dec 30, 2023 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [11892aa026](https://linux-hardware.org/?probe=11892aa026) | Dec 30, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [604c05059a](https://linux-hardware.org/?probe=604c05059a) | Dec 29, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [71d20fd45b](https://linux-hardware.org/?probe=71d20fd45b) | Dec 28, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [9a27ea61df](https://linux-hardware.org/?probe=9a27ea61df) | Dec 27, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [a143ecb3c3](https://linux-hardware.org/?probe=a143ecb3c3) | Dec 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3c17f0bdce](https://linux-hardware.org/?probe=3c17f0bdce) | Dec 25, 2023 |
| Dell          | Latitude 7490               | Notebook    | [69205c648f](https://linux-hardware.org/?probe=69205c648f) | Dec 24, 2023 |
| Unknown       | Unknown                     | Notebook    | [006211d916](https://linux-hardware.org/?probe=006211d916) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [dceb1203ed](https://linux-hardware.org/?probe=dceb1203ed) | Dec 23, 2023 |
| Toshiba       | QOSMIO X770                 | Notebook    | [b9557b6218](https://linux-hardware.org/?probe=b9557b6218) | Dec 23, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [51cee07e16](https://linux-hardware.org/?probe=51cee07e16) | Dec 22, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [1049cbc16b](https://linux-hardware.org/?probe=1049cbc16b) | Dec 22, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | Notebook    | [bfc1ebaf00](https://linux-hardware.org/?probe=bfc1ebaf00) | Dec 22, 2023 |
| ASUSTek       | M3702WFA                    | All in one  | [9091136a65](https://linux-hardware.org/?probe=9091136a65) | Dec 22, 2023 |
| ASUSTek       | M3702WFA                    | All in one  | [a6d6ecda48](https://linux-hardware.org/?probe=a6d6ecda48) | Dec 21, 2023 |
| HP            | 350 G1                      | Notebook    | [c219133bce](https://linux-hardware.org/?probe=c219133bce) | Dec 20, 2023 |
| Dell          | Latitude E6510              | Notebook    | [e9aceddae8](https://linux-hardware.org/?probe=e9aceddae8) | Dec 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [7b5e55e475](https://linux-hardware.org/?probe=7b5e55e475) | Dec 18, 2023 |
| ASUSTek       | ROG Zephyrus S15 GX502LX... | Notebook    | [357f74bcc2](https://linux-hardware.org/?probe=357f74bcc2) | Dec 17, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [05f4c47ed0](https://linux-hardware.org/?probe=05f4c47ed0) | Dec 16, 2023 |
| Medion        | M14L-256                    | Notebook    | [6cd85934b3](https://linux-hardware.org/?probe=6cd85934b3) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7a1a444ed0](https://linux-hardware.org/?probe=7a1a444ed0) | Dec 15, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [cee2ad1e7c](https://linux-hardware.org/?probe=cee2ad1e7c) | Dec 15, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [dd6121c135](https://linux-hardware.org/?probe=dd6121c135) | Dec 15, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [9268266cec](https://linux-hardware.org/?probe=9268266cec) | Dec 15, 2023 |
| HP            | EliteBook 8530w             | Notebook    | [6ce01d863a](https://linux-hardware.org/?probe=6ce01d863a) | Dec 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | Notebook    | [a56ec48040](https://linux-hardware.org/?probe=a56ec48040) | Dec 13, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | Notebook    | [490ceeb636](https://linux-hardware.org/?probe=490ceeb636) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [cdcd6ddfc6](https://linux-hardware.org/?probe=cdcd6ddfc6) | Dec 13, 2023 |
| Intel         | H310 Series                 | Desktop     | [9565b22822](https://linux-hardware.org/?probe=9565b22822) | Dec 13, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [e6f39159ad](https://linux-hardware.org/?probe=e6f39159ad) | Dec 13, 2023 |
| Medion        | M14L-256                    | Notebook    | [b5e0624a7f](https://linux-hardware.org/?probe=b5e0624a7f) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af7be431fb](https://linux-hardware.org/?probe=af7be431fb) | Dec 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d27df22c9a](https://linux-hardware.org/?probe=d27df22c9a) | Dec 11, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [d275512269](https://linux-hardware.org/?probe=d275512269) | Dec 11, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [17dd4245b8](https://linux-hardware.org/?probe=17dd4245b8) | Dec 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e521354b60](https://linux-hardware.org/?probe=e521354b60) | Dec 11, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [76a6e4545f](https://linux-hardware.org/?probe=76a6e4545f) | Dec 11, 2023 |
| Lenovo        | ThinkPad T530 242922G       | Notebook    | [2b8062d3cc](https://linux-hardware.org/?probe=2b8062d3cc) | Dec 09, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [7ca4962c57](https://linux-hardware.org/?probe=7ca4962c57) | Dec 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [ccc3f6589d](https://linux-hardware.org/?probe=ccc3f6589d) | Dec 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [e7fabdedad](https://linux-hardware.org/?probe=e7fabdedad) | Dec 07, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [3ffedf98eb](https://linux-hardware.org/?probe=3ffedf98eb) | Dec 07, 2023 |
| Dell          | Latitude E5440              | Notebook    | [56987fc258](https://linux-hardware.org/?probe=56987fc258) | Dec 06, 2023 |
| Dell          | Latitude E5440              | Notebook    | [6cdafbd9d1](https://linux-hardware.org/?probe=6cdafbd9d1) | Dec 06, 2023 |
| ASUSTek       | 1015PEM                     | Notebook    | [cbaedb564f](https://linux-hardware.org/?probe=cbaedb564f) | Dec 06, 2023 |
| Dell          | 0YXT71 A03                  | Desktop     | [a3080a2577](https://linux-hardware.org/?probe=a3080a2577) | Dec 06, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [d54ba07f49](https://linux-hardware.org/?probe=d54ba07f49) | Dec 06, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [7ccb597e5c](https://linux-hardware.org/?probe=7ccb597e5c) | Dec 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [be2d11a5b9](https://linux-hardware.org/?probe=be2d11a5b9) | Dec 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a635fe86e0](https://linux-hardware.org/?probe=a635fe86e0) | Dec 04, 2023 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [9edd2d878e](https://linux-hardware.org/?probe=9edd2d878e) | Dec 04, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | Notebook    | [2ffb70a1ca](https://linux-hardware.org/?probe=2ffb70a1ca) | Dec 03, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [931c17aeb7](https://linux-hardware.org/?probe=931c17aeb7) | Dec 02, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [58b6cdf11c](https://linux-hardware.org/?probe=58b6cdf11c) | Dec 02, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [305a40c9b7](https://linux-hardware.org/?probe=305a40c9b7) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d4a1f56f8d](https://linux-hardware.org/?probe=d4a1f56f8d) | Dec 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [06fdc9d8e6](https://linux-hardware.org/?probe=06fdc9d8e6) | Dec 01, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [6642e4462f](https://linux-hardware.org/?probe=6642e4462f) | Nov 30, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [0d448c331c](https://linux-hardware.org/?probe=0d448c331c) | Nov 30, 2023 |
| TUXEDO        | Book BA1510                 | Notebook    | [0c59322d62](https://linux-hardware.org/?probe=0c59322d62) | Nov 29, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [772e5ce3f6](https://linux-hardware.org/?probe=772e5ce3f6) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX Z790-F GAMING ... | Desktop     | [fc8b74d0f9](https://linux-hardware.org/?probe=fc8b74d0f9) | Nov 29, 2023 |
| Dell          | 0P301D A00                  | Desktop     | [719e31cd97](https://linux-hardware.org/?probe=719e31cd97) | Nov 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [70a7c438a1](https://linux-hardware.org/?probe=70a7c438a1) | Nov 27, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [2ca445207e](https://linux-hardware.org/?probe=2ca445207e) | Nov 26, 2023 |
| ASUSTek       | P7P55D PRO                  | Desktop     | [69ca3b417c](https://linux-hardware.org/?probe=69ca3b417c) | Nov 26, 2023 |
| Gigabyte      | Z270X-Gaming SOC-CF         | Desktop     | [4631cd6f1c](https://linux-hardware.org/?probe=4631cd6f1c) | Nov 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [7667f4a2a0](https://linux-hardware.org/?probe=7667f4a2a0) | Nov 26, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [106d0f0bff](https://linux-hardware.org/?probe=106d0f0bff) | Nov 24, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [aa4097f060](https://linux-hardware.org/?probe=aa4097f060) | Nov 24, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [4cfc87a4cd](https://linux-hardware.org/?probe=4cfc87a4cd) | Nov 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [399542e5be](https://linux-hardware.org/?probe=399542e5be) | Nov 24, 2023 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [db22f8c316](https://linux-hardware.org/?probe=db22f8c316) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [ca5e9fbf52](https://linux-hardware.org/?probe=ca5e9fbf52) | Nov 23, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [ab672024d6](https://linux-hardware.org/?probe=ab672024d6) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bf30102553](https://linux-hardware.org/?probe=bf30102553) | Nov 23, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [7fb275b8f2](https://linux-hardware.org/?probe=7fb275b8f2) | Nov 22, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d1eeb55299](https://linux-hardware.org/?probe=d1eeb55299) | Nov 22, 2023 |
| Dell          | Latitude 7440               | Convertible | [2f33b08515](https://linux-hardware.org/?probe=2f33b08515) | Nov 21, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [8d328f4394](https://linux-hardware.org/?probe=8d328f4394) | Nov 21, 2023 |
| Toshiba       | Satellite P50-B-11V         | Notebook    | [448150c108](https://linux-hardware.org/?probe=448150c108) | Nov 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ebfe063207](https://linux-hardware.org/?probe=ebfe063207) | Nov 19, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8049743efd](https://linux-hardware.org/?probe=8049743efd) | Nov 19, 2023 |
| Timi          | TM1701                      | Notebook    | [f14bab873b](https://linux-hardware.org/?probe=f14bab873b) | Nov 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f5414a4ffe](https://linux-hardware.org/?probe=f5414a4ffe) | Nov 18, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [5dfd0d8f38](https://linux-hardware.org/?probe=5dfd0d8f38) | Nov 18, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [39c61d33cc](https://linux-hardware.org/?probe=39c61d33cc) | Nov 18, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [0820ebd908](https://linux-hardware.org/?probe=0820ebd908) | Nov 16, 2023 |
| Positivo      | Q432A                       | Convertible | [8fcdcfc99e](https://linux-hardware.org/?probe=8fcdcfc99e) | Nov 15, 2023 |
| Jumper        | EZbook                      | Notebook    | [5623f4ec87](https://linux-hardware.org/?probe=5623f4ec87) | Nov 15, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [d4baa90ad5](https://linux-hardware.org/?probe=d4baa90ad5) | Nov 14, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [f4d839670e](https://linux-hardware.org/?probe=f4d839670e) | Nov 13, 2023 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [5dd5ed8025](https://linux-hardware.org/?probe=5dd5ed8025) | Nov 13, 2023 |
| ASUSTek       | PRIME B660M-A D4            | Desktop     | [79accb8ead](https://linux-hardware.org/?probe=79accb8ead) | Nov 12, 2023 |
| Dell          | Latitude 13                 | Notebook    | [4999e3eba9](https://linux-hardware.org/?probe=4999e3eba9) | Nov 09, 2023 |
| Dell          | Latitude 13                 | Notebook    | [acb0bd4f9d](https://linux-hardware.org/?probe=acb0bd4f9d) | Nov 09, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [c301ae970c](https://linux-hardware.org/?probe=c301ae970c) | Nov 08, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [f2a09a997b](https://linux-hardware.org/?probe=f2a09a997b) | Nov 08, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [48a0272952](https://linux-hardware.org/?probe=48a0272952) | Nov 08, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [4f037eafa8](https://linux-hardware.org/?probe=4f037eafa8) | Nov 08, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [216e0bed29](https://linux-hardware.org/?probe=216e0bed29) | Nov 07, 2023 |
| HP            | 2B36                        | Desktop     | [be86be4b09](https://linux-hardware.org/?probe=be86be4b09) | Nov 07, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [45dfbee68a](https://linux-hardware.org/?probe=45dfbee68a) | Nov 05, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [2de5f4ef98](https://linux-hardware.org/?probe=2de5f4ef98) | Nov 05, 2023 |
| Notebook      | N141CU                      | Notebook    | [8f817eeabf](https://linux-hardware.org/?probe=8f817eeabf) | Nov 04, 2023 |
| POV           | I102A                       | Notebook    | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [abe3da8a30](https://linux-hardware.org/?probe=abe3da8a30) | Nov 03, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7ccaf83d7](https://linux-hardware.org/?probe=e7ccaf83d7) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S937               | Notebook    | [e4e8acb8db](https://linux-hardware.org/?probe=e4e8acb8db) | Nov 03, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | Desktop     | [98b382243b](https://linux-hardware.org/?probe=98b382243b) | Nov 03, 2023 |
| Sony          | VGN-CS21S_R                 | Notebook    | [a7eb8de9f5](https://linux-hardware.org/?probe=a7eb8de9f5) | Nov 01, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [70365949d8](https://linux-hardware.org/?probe=70365949d8) | Nov 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [f1387b3bd9](https://linux-hardware.org/?probe=f1387b3bd9) | Nov 01, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [0ec8ac4d00](https://linux-hardware.org/?probe=0ec8ac4d00) | Nov 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [639a14d08d](https://linux-hardware.org/?probe=639a14d08d) | Nov 01, 2023 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7d5fd28d41](https://linux-hardware.org/?probe=7d5fd28d41) | Nov 01, 2023 |
| ABIT          | F-I90HD                     | Desktop     | [2d6d01983c](https://linux-hardware.org/?probe=2d6d01983c) | Nov 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [d58a78a617](https://linux-hardware.org/?probe=d58a78a617) | Oct 31, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [2c79650ee2](https://linux-hardware.org/?probe=2c79650ee2) | Oct 29, 2023 |
| Dell          | Latitude E5400              | Notebook    | [169d73bee0](https://linux-hardware.org/?probe=169d73bee0) | Oct 28, 2023 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | Notebook    | [cb44c39574](https://linux-hardware.org/?probe=cb44c39574) | Oct 27, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | Desktop     | [b9ec438e43](https://linux-hardware.org/?probe=b9ec438e43) | Oct 27, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [3cf7c10977](https://linux-hardware.org/?probe=3cf7c10977) | Oct 25, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d6d5273a5a](https://linux-hardware.org/?probe=d6d5273a5a) | Oct 25, 2023 |
| Dell          | Inspiron 11-3168            | Notebook    | [07fd1e8be9](https://linux-hardware.org/?probe=07fd1e8be9) | Oct 25, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [011bfdd699](https://linux-hardware.org/?probe=011bfdd699) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | Notebook    | [32743a624c](https://linux-hardware.org/?probe=32743a624c) | Oct 24, 2023 |
| Gigabyte      | G5 KC                       | Notebook    | [23d64978d9](https://linux-hardware.org/?probe=23d64978d9) | Oct 24, 2023 |
| Acer          | Aspire X1900                | Desktop     | [6454f71562](https://linux-hardware.org/?probe=6454f71562) | Oct 23, 2023 |
| Lenovo        | 30D0 SDK0J40697 WIN 3305... | Desktop     | [1e4819e6d1](https://linux-hardware.org/?probe=1e4819e6d1) | Oct 23, 2023 |
| Sony          | VGN-FZ21M                   | Notebook    | [ba7c93bcd4](https://linux-hardware.org/?probe=ba7c93bcd4) | Oct 21, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | Notebook    | [801d54f088](https://linux-hardware.org/?probe=801d54f088) | Oct 21, 2023 |
| ASUSTek       | PRIME Z790-P WIFI           | Desktop     | [e7cd525d35](https://linux-hardware.org/?probe=e7cd525d35) | Oct 21, 2023 |
| Toshiba       | Satellite Pro C50-A-1C8     | Notebook    | [69d0758d3d](https://linux-hardware.org/?probe=69d0758d3d) | Oct 19, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [722b608b43](https://linux-hardware.org/?probe=722b608b43) | Oct 18, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [2408be3605](https://linux-hardware.org/?probe=2408be3605) | Oct 16, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [d6e1f3c3b8](https://linux-hardware.org/?probe=d6e1f3c3b8) | Oct 15, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [c99b37a865](https://linux-hardware.org/?probe=c99b37a865) | Oct 15, 2023 |
| Gigabyte      | G7 GD                       | Notebook    | [667243780c](https://linux-hardware.org/?probe=667243780c) | Oct 15, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [3055b32637](https://linux-hardware.org/?probe=3055b32637) | Oct 15, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [086ecfefb8](https://linux-hardware.org/?probe=086ecfefb8) | Oct 15, 2023 |
| ASUSTek       | B75M-PLUS                   | Desktop     | [c1baca90e6](https://linux-hardware.org/?probe=c1baca90e6) | Oct 13, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [bd6f7ac948](https://linux-hardware.org/?probe=bd6f7ac948) | Oct 13, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [3b06edb6bf](https://linux-hardware.org/?probe=3b06edb6bf) | Oct 13, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [adad0100ea](https://linux-hardware.org/?probe=adad0100ea) | Oct 13, 2023 |
| Lenovo        | ThinkPad X250 20CM0048US    | Notebook    | [cf66338531](https://linux-hardware.org/?probe=cf66338531) | Oct 13, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [20b1614237](https://linux-hardware.org/?probe=20b1614237) | Oct 12, 2023 |
| Dell          | 0200DY A01                  | Desktop     | [4e207b6ab6](https://linux-hardware.org/?probe=4e207b6ab6) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [cc3dbe7ccd](https://linux-hardware.org/?probe=cc3dbe7ccd) | Oct 12, 2023 |
| HP            | ProBook 455 15.6 inch G1... | Notebook    | [8c1ef64452](https://linux-hardware.org/?probe=8c1ef64452) | Oct 12, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d5040f4ca4](https://linux-hardware.org/?probe=d5040f4ca4) | Oct 12, 2023 |
| MSI           | Prestige 16Studio A13VE     | Notebook    | [0209063983](https://linux-hardware.org/?probe=0209063983) | Oct 12, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [81409b14c4](https://linux-hardware.org/?probe=81409b14c4) | Oct 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [0198bbbc8c](https://linux-hardware.org/?probe=0198bbbc8c) | Oct 10, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c715105687](https://linux-hardware.org/?probe=c715105687) | Oct 10, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [a2a5c14c8a](https://linux-hardware.org/?probe=a2a5c14c8a) | Oct 09, 2023 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [882d0daf54](https://linux-hardware.org/?probe=882d0daf54) | Oct 09, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [b3fd22ad8e](https://linux-hardware.org/?probe=b3fd22ad8e) | Oct 08, 2023 |
| HP            | Pavilion 15                 | Notebook    | [ae1e07dd63](https://linux-hardware.org/?probe=ae1e07dd63) | Oct 08, 2023 |
| Lenovo        | 3141 SDK0K17763 WIN 1801... | Desktop     | [da32e6e356](https://linux-hardware.org/?probe=da32e6e356) | Oct 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| Acer          | Aspire X1900                | Desktop     | [38b7e52e6b](https://linux-hardware.org/?probe=38b7e52e6b) | Oct 06, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [08aa11c398](https://linux-hardware.org/?probe=08aa11c398) | Oct 05, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [738b1fca84](https://linux-hardware.org/?probe=738b1fca84) | Oct 05, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [74c1d9ddfb](https://linux-hardware.org/?probe=74c1d9ddfb) | Oct 05, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [9b841951f2](https://linux-hardware.org/?probe=9b841951f2) | Oct 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [8ba8fa3184](https://linux-hardware.org/?probe=8ba8fa3184) | Oct 05, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a90e584705](https://linux-hardware.org/?probe=a90e584705) | Oct 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [bf9ddbe725](https://linux-hardware.org/?probe=bf9ddbe725) | Oct 04, 2023 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [ef154408cf](https://linux-hardware.org/?probe=ef154408cf) | Oct 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [3a8b2b229a](https://linux-hardware.org/?probe=3a8b2b229a) | Oct 03, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [b0b5262c87](https://linux-hardware.org/?probe=b0b5262c87) | Oct 02, 2023 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [1d315fb87d](https://linux-hardware.org/?probe=1d315fb87d) | Oct 02, 2023 |
| Acer          | Aspire X1900                | Desktop     | [5d958ae7d1](https://linux-hardware.org/?probe=5d958ae7d1) | Oct 02, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | Notebook    | [d929b857db](https://linux-hardware.org/?probe=d929b857db) | Oct 01, 2023 |
| ASUSTek       | F7SR                        | Notebook    | [b895fd8bb2](https://linux-hardware.org/?probe=b895fd8bb2) | Sep 30, 2023 |
| ASUSTek       | F7SR                        | Notebook    | [1b7493ae6e](https://linux-hardware.org/?probe=1b7493ae6e) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [b6acaf4c61](https://linux-hardware.org/?probe=b6acaf4c61) | Sep 27, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7524eea19f](https://linux-hardware.org/?probe=7524eea19f) | Sep 26, 2023 |
| HP            | G62                         | Notebook    | [50fef7b3fa](https://linux-hardware.org/?probe=50fef7b3fa) | Sep 26, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [1df46b6215](https://linux-hardware.org/?probe=1df46b6215) | Sep 25, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [1d90b7b714](https://linux-hardware.org/?probe=1d90b7b714) | Sep 25, 2023 |
| ASUSTek       | K55VM                       | Notebook    | [3dd45a6297](https://linux-hardware.org/?probe=3dd45a6297) | Sep 24, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [0a29d5f7f6](https://linux-hardware.org/?probe=0a29d5f7f6) | Sep 22, 2023 |
| Notebook      | P7xxTM                      | Notebook    | [e14cfa2f1f](https://linux-hardware.org/?probe=e14cfa2f1f) | Sep 22, 2023 |
| Notebook      | P7xxTM                      | Notebook    | [41b1348520](https://linux-hardware.org/?probe=41b1348520) | Sep 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [98ab1e6859](https://linux-hardware.org/?probe=98ab1e6859) | Sep 21, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [c933105cd8](https://linux-hardware.org/?probe=c933105cd8) | Sep 21, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [7377101d6d](https://linux-hardware.org/?probe=7377101d6d) | Sep 20, 2023 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6088e9b2fa](https://linux-hardware.org/?probe=6088e9b2fa) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [963330511d](https://linux-hardware.org/?probe=963330511d) | Sep 19, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5f8df7dfcb](https://linux-hardware.org/?probe=5f8df7dfcb) | Sep 19, 2023 |
| ASRock        | A520M-HVS                   | Desktop     | [2a7bf627ba](https://linux-hardware.org/?probe=2a7bf627ba) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [50c2f9349d](https://linux-hardware.org/?probe=50c2f9349d) | Sep 18, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [779e737e23](https://linux-hardware.org/?probe=779e737e23) | Sep 18, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [8dd27c1671](https://linux-hardware.org/?probe=8dd27c1671) | Sep 18, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [06b00c7739](https://linux-hardware.org/?probe=06b00c7739) | Sep 18, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [8566235f94](https://linux-hardware.org/?probe=8566235f94) | Sep 17, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [9cfb7b262c](https://linux-hardware.org/?probe=9cfb7b262c) | Sep 17, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [24efefc447](https://linux-hardware.org/?probe=24efefc447) | Sep 17, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [70cb61d1dc](https://linux-hardware.org/?probe=70cb61d1dc) | Sep 17, 2023 |
| MSI           | PS42 8RB                    | Notebook    | [2fa07ede2a](https://linux-hardware.org/?probe=2fa07ede2a) | Sep 16, 2023 |
| HP            | 339A                        | Desktop     | [a9eaaaeeb0](https://linux-hardware.org/?probe=a9eaaaeeb0) | Sep 12, 2023 |
| PC Special... | P7xxTM1                     | Notebook    | [2bdbc2f2e7](https://linux-hardware.org/?probe=2bdbc2f2e7) | Sep 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [03e666ab42](https://linux-hardware.org/?probe=03e666ab42) | Sep 12, 2023 |
| ASUSTek       | GL553VW                     | Notebook    | [3859055e8d](https://linux-hardware.org/?probe=3859055e8d) | Sep 11, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6RF0... | Notebook    | [6c62d111db](https://linux-hardware.org/?probe=6c62d111db) | Sep 10, 2023 |
| HP            | 339A                        | Desktop     | [18bb44efa6](https://linux-hardware.org/?probe=18bb44efa6) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [8dc4477486](https://linux-hardware.org/?probe=8dc4477486) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [e737851117](https://linux-hardware.org/?probe=e737851117) | Sep 10, 2023 |
| Dell          | Inspiron 11-3168            | Notebook    | [57ef365bf9](https://linux-hardware.org/?probe=57ef365bf9) | Sep 10, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [5e9fc2a82f](https://linux-hardware.org/?probe=5e9fc2a82f) | Sep 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [79a666783a](https://linux-hardware.org/?probe=79a666783a) | Sep 07, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | Desktop     | [602bfb550f](https://linux-hardware.org/?probe=602bfb550f) | Sep 06, 2023 |
| JGINYUE       | X79M-PLUS V2.2              | Desktop     | [1535be8e5f](https://linux-hardware.org/?probe=1535be8e5f) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | Notebook    | [c9a07c44d5](https://linux-hardware.org/?probe=c9a07c44d5) | Sep 06, 2023 |
| Gigabyte      | H110M-Gaming3-CF            | Desktop     | [8985e6b1d9](https://linux-hardware.org/?probe=8985e6b1d9) | Sep 05, 2023 |
| HP            | mt40                        | Notebook    | [c3a4682e40](https://linux-hardware.org/?probe=c3a4682e40) | Sep 04, 2023 |
| Lenovo        | ThinkPad SL510 28473QB      | Notebook    | [e1ff8baa87](https://linux-hardware.org/?probe=e1ff8baa87) | Sep 04, 2023 |
| MSI           | H61M-P20                    | Desktop     | [cdf64232fc](https://linux-hardware.org/?probe=cdf64232fc) | Sep 04, 2023 |
| Chuwi         | MiniBook X                  | Convertible | [a298625ea9](https://linux-hardware.org/?probe=a298625ea9) | Sep 04, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [2292824064](https://linux-hardware.org/?probe=2292824064) | Sep 04, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [c13b1a693d](https://linux-hardware.org/?probe=c13b1a693d) | Sep 03, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1e01a32799](https://linux-hardware.org/?probe=1e01a32799) | Sep 01, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1BL0... | Notebook    | [f1e1512fc9](https://linux-hardware.org/?probe=f1e1512fc9) | Sep 01, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [bdae370995](https://linux-hardware.org/?probe=bdae370995) | Aug 30, 2023 |
| ASUSTek       | P8Q77-M                     | Desktop     | [d9760de265](https://linux-hardware.org/?probe=d9760de265) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [0bf7d37cc9](https://linux-hardware.org/?probe=0bf7d37cc9) | Aug 30, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [b3caa97382](https://linux-hardware.org/?probe=b3caa97382) | Aug 30, 2023 |
| Lenovo        | 3000 G410                   | Notebook    | [26c592ddd6](https://linux-hardware.org/?probe=26c592ddd6) | Aug 29, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [fe431ea565](https://linux-hardware.org/?probe=fe431ea565) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a4bd03aafc](https://linux-hardware.org/?probe=a4bd03aafc) | Aug 29, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [e27639a1f9](https://linux-hardware.org/?probe=e27639a1f9) | Aug 29, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [19f07f081f](https://linux-hardware.org/?probe=19f07f081f) | Aug 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5e7257145a](https://linux-hardware.org/?probe=5e7257145a) | Aug 26, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [627068909d](https://linux-hardware.org/?probe=627068909d) | Aug 25, 2023 |
| HP            | 15                          | Notebook    | [76decc7899](https://linux-hardware.org/?probe=76decc7899) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [7e6a7de337](https://linux-hardware.org/?probe=7e6a7de337) | Aug 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [e0a5f63a8b](https://linux-hardware.org/?probe=e0a5f63a8b) | Aug 22, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [99cdeba16c](https://linux-hardware.org/?probe=99cdeba16c) | Aug 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a665e45380](https://linux-hardware.org/?probe=a665e45380) | Aug 19, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [98c9e71be9](https://linux-hardware.org/?probe=98c9e71be9) | Aug 19, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | Notebook    | [b5e6b20270](https://linux-hardware.org/?probe=b5e6b20270) | Aug 18, 2023 |
| Chuwi         | GemiBook XPro               | Notebook    | [41b34e60fd](https://linux-hardware.org/?probe=41b34e60fd) | Aug 18, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [82c579f8a7](https://linux-hardware.org/?probe=82c579f8a7) | Aug 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ee8c1f96e8](https://linux-hardware.org/?probe=ee8c1f96e8) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [7050972395](https://linux-hardware.org/?probe=7050972395) | Aug 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [c2cfa9bd7a](https://linux-hardware.org/?probe=c2cfa9bd7a) | Aug 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460A... | Notebook    | [67a1535765](https://linux-hardware.org/?probe=67a1535765) | Aug 15, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [823e276406](https://linux-hardware.org/?probe=823e276406) | Aug 13, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [af419fe003](https://linux-hardware.org/?probe=af419fe003) | Aug 12, 2023 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [16cd37e4fe](https://linux-hardware.org/?probe=16cd37e4fe) | Aug 12, 2023 |
| LNV           | L40-70                      | Notebook    | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| HP            | 250 G3                      | Notebook    | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| AMI           | Cherry Trail CR             | Mini pc     | [ccb4eadbca](https://linux-hardware.org/?probe=ccb4eadbca) | Aug 08, 2023 |
| HP            | Notebook                    | Notebook    | [02ceb78a4f](https://linux-hardware.org/?probe=02ceb78a4f) | Aug 07, 2023 |
| Medion        | M14L-256                    | Notebook    | [7d0a8921dc](https://linux-hardware.org/?probe=7d0a8921dc) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [45fe14954d](https://linux-hardware.org/?probe=45fe14954d) | Aug 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [d1bca9ae8b](https://linux-hardware.org/?probe=d1bca9ae8b) | Aug 07, 2023 |
| Apple         | MacBook7,1                  | Notebook    | [38d285144e](https://linux-hardware.org/?probe=38d285144e) | Aug 06, 2023 |
| Teclast       | F7S                         | Notebook    | [a844443394](https://linux-hardware.org/?probe=a844443394) | Aug 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [9431f6f4e8](https://linux-hardware.org/?probe=9431f6f4e8) | Aug 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [456ac6507d](https://linux-hardware.org/?probe=456ac6507d) | Aug 05, 2023 |
| Teclast       | F7S                         | Notebook    | [71ab18cda5](https://linux-hardware.org/?probe=71ab18cda5) | Aug 05, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [5b0c2b27e7](https://linux-hardware.org/?probe=5b0c2b27e7) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [2825bbd67b](https://linux-hardware.org/?probe=2825bbd67b) | Aug 04, 2023 |
| ASUSTek       | UX430UNR                    | Notebook    | [89c8324528](https://linux-hardware.org/?probe=89c8324528) | Aug 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d58cf2a585](https://linux-hardware.org/?probe=d58cf2a585) | Jul 31, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [002504b8be](https://linux-hardware.org/?probe=002504b8be) | Jul 29, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [30dabbbc28](https://linux-hardware.org/?probe=30dabbbc28) | Jul 28, 2023 |
| HP            | 3397                        | Desktop     | [e61ccd6dbf](https://linux-hardware.org/?probe=e61ccd6dbf) | Jul 27, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [5a1f6f3395](https://linux-hardware.org/?probe=5a1f6f3395) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | Notebook    | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [daf09efe6e](https://linux-hardware.org/?probe=daf09efe6e) | Jul 24, 2023 |
| Intel         | Unknown                     | Desktop     | [74d458db75](https://linux-hardware.org/?probe=74d458db75) | Jul 23, 2023 |
| BESSTAR Te... | JB9                         | Desktop     | [ea014bad4f](https://linux-hardware.org/?probe=ea014bad4f) | Jul 22, 2023 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [17c94eb7a3](https://linux-hardware.org/?probe=17c94eb7a3) | Jul 22, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [1e0063a74a](https://linux-hardware.org/?probe=1e0063a74a) | Jul 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c1e386e9cc](https://linux-hardware.org/?probe=c1e386e9cc) | Jul 22, 2023 |
| HP            | 829A                        | Mini pc     | [f768f29747](https://linux-hardware.org/?probe=f768f29747) | Jul 22, 2023 |
| Acer          | Extensa 5635ZG              | Notebook    | [337f0cec05](https://linux-hardware.org/?probe=337f0cec05) | Jul 20, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [a2f35813e6](https://linux-hardware.org/?probe=a2f35813e6) | Jul 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [069bfd995c](https://linux-hardware.org/?probe=069bfd995c) | Jul 15, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [7d2f78f0d3](https://linux-hardware.org/?probe=7d2f78f0d3) | Jul 15, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [20e49aa241](https://linux-hardware.org/?probe=20e49aa241) | Jul 14, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e44fde4d59](https://linux-hardware.org/?probe=e44fde4d59) | Jul 14, 2023 |
| HP            | Pavilion dv3                | Notebook    | [94eeea2364](https://linux-hardware.org/?probe=94eeea2364) | Jul 12, 2023 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [65f4b4e813](https://linux-hardware.org/?probe=65f4b4e813) | Jul 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [a61e80c022](https://linux-hardware.org/?probe=a61e80c022) | Jul 11, 2023 |
| Dell          | Latitude E5500              | Notebook    | [03798c7840](https://linux-hardware.org/?probe=03798c7840) | Jul 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [50f23f3476](https://linux-hardware.org/?probe=50f23f3476) | Jul 09, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9fc07d1102](https://linux-hardware.org/?probe=9fc07d1102) | Jul 08, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [4122f6e73c](https://linux-hardware.org/?probe=4122f6e73c) | Jul 06, 2023 |
| HP            | 350 G1                      | Notebook    | [d965c2785d](https://linux-hardware.org/?probe=d965c2785d) | Jul 04, 2023 |
| HP            | 350 G1                      | Notebook    | [bb742c9ffb](https://linux-hardware.org/?probe=bb742c9ffb) | Jul 04, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [83cd667719](https://linux-hardware.org/?probe=83cd667719) | Jun 30, 2023 |
| Acer          | Aspire 5737Z                | Notebook    | [842aa57faf](https://linux-hardware.org/?probe=842aa57faf) | Jun 30, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| MSI           | PS63 Modern 8SC             | Notebook    | [dcbb8108cf](https://linux-hardware.org/?probe=dcbb8108cf) | Jun 29, 2023 |
| Lenovo        | ThinkPad T430 2349OB6       | Notebook    | [f2f66bb9d0](https://linux-hardware.org/?probe=f2f66bb9d0) | Jun 29, 2023 |
| Toshiba       | Satellite X200              | Notebook    | [4a3e7008cf](https://linux-hardware.org/?probe=4a3e7008cf) | Jun 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c05a780b64](https://linux-hardware.org/?probe=c05a780b64) | Jun 27, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [1a17b8ee06](https://linux-hardware.org/?probe=1a17b8ee06) | Jun 26, 2023 |
| Gigabyte      | AERO 15 KD                  | Notebook    | [2fd779cefc](https://linux-hardware.org/?probe=2fd779cefc) | Jun 26, 2023 |
| Dell          | XPS 9315                    | Notebook    | [41bb8bd332](https://linux-hardware.org/?probe=41bb8bd332) | Jun 25, 2023 |
| Dell          | 07N90W A01                  | Desktop     | [67a12e071e](https://linux-hardware.org/?probe=67a12e071e) | Jun 25, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [39ff230ffe](https://linux-hardware.org/?probe=39ff230ffe) | Jun 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4ad837baa7](https://linux-hardware.org/?probe=4ad837baa7) | Jun 24, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fe084d5ddb](https://linux-hardware.org/?probe=fe084d5ddb) | Jun 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [4b866ca19f](https://linux-hardware.org/?probe=4b866ca19f) | Jun 22, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | Notebook    | [22c2768f76](https://linux-hardware.org/?probe=22c2768f76) | Jun 22, 2023 |
| Lenovo        | 1057 SDK0T76530 WIN 3556... | Desktop     | [0502b8f756](https://linux-hardware.org/?probe=0502b8f756) | Jun 20, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [6840ce5f21](https://linux-hardware.org/?probe=6840ce5f21) | Jun 20, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Intel         | NUC5PPYB H76558-108         | Mini pc     | [1d1386c5e2](https://linux-hardware.org/?probe=1d1386c5e2) | Jun 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [2f19a23a54](https://linux-hardware.org/?probe=2f19a23a54) | Jun 17, 2023 |
| HP            | 84FD                        | Desktop     | [968b4e287f](https://linux-hardware.org/?probe=968b4e287f) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [3d8b5e9564](https://linux-hardware.org/?probe=3d8b5e9564) | Jun 17, 2023 |
| HP            | 84FD                        | Desktop     | [1711c65b62](https://linux-hardware.org/?probe=1711c65b62) | Jun 17, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [fb8da18b42](https://linux-hardware.org/?probe=fb8da18b42) | Jun 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bcb3a62b53](https://linux-hardware.org/?probe=bcb3a62b53) | Jun 17, 2023 |
| Dell          | Latitude E5400              | Notebook    | [f5d066d8fc](https://linux-hardware.org/?probe=f5d066d8fc) | Jun 16, 2023 |
| Toshiba       | Satellite X200              | Notebook    | [d57a63387d](https://linux-hardware.org/?probe=d57a63387d) | Jun 15, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [d92c0dea02](https://linux-hardware.org/?probe=d92c0dea02) | Jun 14, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [a63988d437](https://linux-hardware.org/?probe=a63988d437) | Jun 14, 2023 |
| HP            | 18E4                        | Desktop     | [a0d8b92e3a](https://linux-hardware.org/?probe=a0d8b92e3a) | Jun 12, 2023 |
| Sony          | SVF1521J7EW                 | Notebook    | [2d04d992c2](https://linux-hardware.org/?probe=2d04d992c2) | Jun 10, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [edec9d7178](https://linux-hardware.org/?probe=edec9d7178) | Jun 10, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [2ac8db1b4c](https://linux-hardware.org/?probe=2ac8db1b4c) | Jun 10, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [47d37facfc](https://linux-hardware.org/?probe=47d37facfc) | Jun 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8632ddc565](https://linux-hardware.org/?probe=8632ddc565) | Jun 09, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [10d01671ad](https://linux-hardware.org/?probe=10d01671ad) | Jun 08, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [83adb0e53a](https://linux-hardware.org/?probe=83adb0e53a) | Jun 07, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [d46387134e](https://linux-hardware.org/?probe=d46387134e) | Jun 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [1378fdec29](https://linux-hardware.org/?probe=1378fdec29) | Jun 07, 2023 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [6cd3cfcacf](https://linux-hardware.org/?probe=6cd3cfcacf) | Jun 06, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [c058d92130](https://linux-hardware.org/?probe=c058d92130) | Jun 05, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [efa9cac1df](https://linux-hardware.org/?probe=efa9cac1df) | Jun 04, 2023 |
| Lenovo        | 32E9 SDK0T76465 WIN 3422... | Desktop     | [fa41f1f3c2](https://linux-hardware.org/?probe=fa41f1f3c2) | Jun 04, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [f47c68a2a7](https://linux-hardware.org/?probe=f47c68a2a7) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [6964a1da79](https://linux-hardware.org/?probe=6964a1da79) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [767241151a](https://linux-hardware.org/?probe=767241151a) | Jun 03, 2023 |
| Dell          | Latitude 5491               | Notebook    | [6a8a7e6188](https://linux-hardware.org/?probe=6a8a7e6188) | Jun 03, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [3de77b392a](https://linux-hardware.org/?probe=3de77b392a) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [109dbbfff0](https://linux-hardware.org/?probe=109dbbfff0) | Jun 02, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [3f032ab035](https://linux-hardware.org/?probe=3f032ab035) | Jun 02, 2023 |
| HP            | Unknown                     | Notebook    | [626075d6f2](https://linux-hardware.org/?probe=626075d6f2) | Jun 02, 2023 |
| HP            | Unknown                     | Notebook    | [2289bb8d24](https://linux-hardware.org/?probe=2289bb8d24) | Jun 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [302ae0e2dc](https://linux-hardware.org/?probe=302ae0e2dc) | Jun 02, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f17ebfac4b](https://linux-hardware.org/?probe=f17ebfac4b) | May 31, 2023 |
| HP            | Unknown                     | Notebook    | [3eb658702b](https://linux-hardware.org/?probe=3eb658702b) | May 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [93ac1fb021](https://linux-hardware.org/?probe=93ac1fb021) | May 31, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [5881fb6ae2](https://linux-hardware.org/?probe=5881fb6ae2) | May 30, 2023 |
| HP            | Unknown                     | Notebook    | [2007104aeb](https://linux-hardware.org/?probe=2007104aeb) | May 30, 2023 |
| Lenovo        | ThinkPad E490 20N8000RPG    | Notebook    | [73b8bfb3a5](https://linux-hardware.org/?probe=73b8bfb3a5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [84781c068a](https://linux-hardware.org/?probe=84781c068a) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [97f0880258](https://linux-hardware.org/?probe=97f0880258) | May 29, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [1a69603cc6](https://linux-hardware.org/?probe=1a69603cc6) | May 28, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [5684d2005d](https://linux-hardware.org/?probe=5684d2005d) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [462ae1c4f5](https://linux-hardware.org/?probe=462ae1c4f5) | May 28, 2023 |
| HP            | 15                          | Notebook    | [f5373f2397](https://linux-hardware.org/?probe=f5373f2397) | May 27, 2023 |
| HP            | 15                          | Notebook    | [f30c3b3a95](https://linux-hardware.org/?probe=f30c3b3a95) | May 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [0f3f548ff0](https://linux-hardware.org/?probe=0f3f548ff0) | May 27, 2023 |
| ASUSTek       | H81M-R                      | Desktop     | [8edf21a203](https://linux-hardware.org/?probe=8edf21a203) | May 27, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [31c6913c14](https://linux-hardware.org/?probe=31c6913c14) | May 26, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [66c9773a5f](https://linux-hardware.org/?probe=66c9773a5f) | May 26, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [65cc5e45b0](https://linux-hardware.org/?probe=65cc5e45b0) | May 26, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [ac87b1945b](https://linux-hardware.org/?probe=ac87b1945b) | May 26, 2023 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [7080c87654](https://linux-hardware.org/?probe=7080c87654) | May 25, 2023 |
| ASUSTek       | GL702ZC                     | Notebook    | [c60d7fabbb](https://linux-hardware.org/?probe=c60d7fabbb) | May 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [b5a283de1d](https://linux-hardware.org/?probe=b5a283de1d) | May 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [0a65452634](https://linux-hardware.org/?probe=0a65452634) | May 24, 2023 |
| ASUSTek       | GL702ZC                     | Notebook    | [9764417bf8](https://linux-hardware.org/?probe=9764417bf8) | May 24, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [d03d942df4](https://linux-hardware.org/?probe=d03d942df4) | May 24, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [81c0b82d6c](https://linux-hardware.org/?probe=81c0b82d6c) | May 24, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [4c512786cc](https://linux-hardware.org/?probe=4c512786cc) | May 24, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [da0b980bc3](https://linux-hardware.org/?probe=da0b980bc3) | May 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0aba7a98b9](https://linux-hardware.org/?probe=0aba7a98b9) | May 24, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [a11fdd0361](https://linux-hardware.org/?probe=a11fdd0361) | May 23, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [0e982abd6b](https://linux-hardware.org/?probe=0e982abd6b) | May 22, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [87b976a24c](https://linux-hardware.org/?probe=87b976a24c) | May 22, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [63a27f785d](https://linux-hardware.org/?probe=63a27f785d) | May 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d1c4b3ee44](https://linux-hardware.org/?probe=d1c4b3ee44) | May 22, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [f250413f11](https://linux-hardware.org/?probe=f250413f11) | May 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [8d0096c040](https://linux-hardware.org/?probe=8d0096c040) | May 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [ec34d9c9c5](https://linux-hardware.org/?probe=ec34d9c9c5) | May 20, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| HP            | Unknown                     | Notebook    | [8ae91264ca](https://linux-hardware.org/?probe=8ae91264ca) | May 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| Acer          | Aspire E5-521               | Notebook    | [05227be8bc](https://linux-hardware.org/?probe=05227be8bc) | May 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | Notebook    | [7df5747f30](https://linux-hardware.org/?probe=7df5747f30) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [ee37475637](https://linux-hardware.org/?probe=ee37475637) | May 18, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [68406e2c40](https://linux-hardware.org/?probe=68406e2c40) | May 18, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [72b5dfc390](https://linux-hardware.org/?probe=72b5dfc390) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [d7e4640b82](https://linux-hardware.org/?probe=d7e4640b82) | May 15, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [87d2f8b907](https://linux-hardware.org/?probe=87d2f8b907) | May 14, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [7e2caae7ea](https://linux-hardware.org/?probe=7e2caae7ea) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [9a9b88a86c](https://linux-hardware.org/?probe=9a9b88a86c) | May 14, 2023 |
| Vorke         | V1 Plus                     | Desktop     | [19f095fc02](https://linux-hardware.org/?probe=19f095fc02) | May 13, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [a2199ee2c6](https://linux-hardware.org/?probe=a2199ee2c6) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Lenovo        | ThinkPad X61 7673V4Q        | Notebook    | [38acb76489](https://linux-hardware.org/?probe=38acb76489) | May 11, 2023 |
| HP            | G62                         | Notebook    | [68f5984aa8](https://linux-hardware.org/?probe=68f5984aa8) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fda523de2a](https://linux-hardware.org/?probe=fda523de2a) | May 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [a3c2a7c9bf](https://linux-hardware.org/?probe=a3c2a7c9bf) | May 11, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [d9f5e85b9b](https://linux-hardware.org/?probe=d9f5e85b9b) | May 10, 2023 |
| HP            | 225E                        | Desktop     | [06c72d2ecd](https://linux-hardware.org/?probe=06c72d2ecd) | May 10, 2023 |
| Sony          | VGN-FZ31Z                   | Notebook    | [6fe358200a](https://linux-hardware.org/?probe=6fe358200a) | May 09, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [eeb083abcd](https://linux-hardware.org/?probe=eeb083abcd) | May 07, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [70c3231200](https://linux-hardware.org/?probe=70c3231200) | May 07, 2023 |
| Notebook      | N141CU                      | Notebook    | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| Acer          | Aspire E5-523G              | Notebook    | [7a77c66c97](https://linux-hardware.org/?probe=7a77c66c97) | May 06, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [678b4ca4ed](https://linux-hardware.org/?probe=678b4ca4ed) | May 06, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [7b0b45831c](https://linux-hardware.org/?probe=7b0b45831c) | May 06, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [107752eba8](https://linux-hardware.org/?probe=107752eba8) | May 05, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [d7109f5e05](https://linux-hardware.org/?probe=d7109f5e05) | May 05, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [f28f7150ba](https://linux-hardware.org/?probe=f28f7150ba) | May 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [04f1f6146c](https://linux-hardware.org/?probe=04f1f6146c) | May 04, 2023 |
| Dell          | Precision 5540              | Notebook    | [3139d97ce0](https://linux-hardware.org/?probe=3139d97ce0) | May 04, 2023 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [7f1747c3e3](https://linux-hardware.org/?probe=7f1747c3e3) | May 04, 2023 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [a937b9eaeb](https://linux-hardware.org/?probe=a937b9eaeb) | May 04, 2023 |
| Toshiba       | PORTEGE Z830                | Notebook    | [a8cc4a63c2](https://linux-hardware.org/?probe=a8cc4a63c2) | May 03, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [ae1618c708](https://linux-hardware.org/?probe=ae1618c708) | May 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1e26913701](https://linux-hardware.org/?probe=1e26913701) | May 03, 2023 |
| HP            | Unknown                     | Notebook    | [4d0dc62d87](https://linux-hardware.org/?probe=4d0dc62d87) | May 03, 2023 |
| HP            | Unknown                     | Notebook    | [95bbd82535](https://linux-hardware.org/?probe=95bbd82535) | May 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f3e8baa565](https://linux-hardware.org/?probe=f3e8baa565) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [168396ff77](https://linux-hardware.org/?probe=168396ff77) | May 01, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [82d7303d5c](https://linux-hardware.org/?probe=82d7303d5c) | May 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [5cfdd30fa7](https://linux-hardware.org/?probe=5cfdd30fa7) | May 01, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b7ca4beb49](https://linux-hardware.org/?probe=b7ca4beb49) | Apr 30, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c1fe7a5f87](https://linux-hardware.org/?probe=c1fe7a5f87) | Apr 30, 2023 |
| Acer          | E661GXM                     | Desktop     | [d5433b46bd](https://linux-hardware.org/?probe=d5433b46bd) | Apr 30, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d4cfc1e964](https://linux-hardware.org/?probe=d4cfc1e964) | Apr 30, 2023 |
| ASUSTek       | X542URR                     | Notebook    | [910cdd940c](https://linux-hardware.org/?probe=910cdd940c) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [3a6e27c6ce](https://linux-hardware.org/?probe=3a6e27c6ce) | Apr 26, 2023 |
| Intel         | X99H                        | Desktop     | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [11f1e291a7](https://linux-hardware.org/?probe=11f1e291a7) | Apr 25, 2023 |
| Dell          | Inspiron 5521               | Notebook    | [8de2e801a3](https://linux-hardware.org/?probe=8de2e801a3) | Apr 23, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [67f15c6f4a](https://linux-hardware.org/?probe=67f15c6f4a) | Apr 22, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [1fc445ac89](https://linux-hardware.org/?probe=1fc445ac89) | Apr 22, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [ba9bbe1e70](https://linux-hardware.org/?probe=ba9bbe1e70) | Apr 21, 2023 |
| Dell          | Precision 5540              | Notebook    | [66b58fad6c](https://linux-hardware.org/?probe=66b58fad6c) | Apr 19, 2023 |
| Dell          | Precision 5540              | Notebook    | [e114fb911c](https://linux-hardware.org/?probe=e114fb911c) | Apr 19, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [b4c6c1198f](https://linux-hardware.org/?probe=b4c6c1198f) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| AAEON         | UPS-EHL01 V1.0              | Desktop     | [14471b218c](https://linux-hardware.org/?probe=14471b218c) | Apr 18, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4174faae23](https://linux-hardware.org/?probe=4174faae23) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a2b27dd2d6](https://linux-hardware.org/?probe=a2b27dd2d6) | Apr 17, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [14517ef743](https://linux-hardware.org/?probe=14517ef743) | Apr 17, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [4ee307bb03](https://linux-hardware.org/?probe=4ee307bb03) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | Notebook    | [1280936eba](https://linux-hardware.org/?probe=1280936eba) | Apr 13, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [fb3078d5c3](https://linux-hardware.org/?probe=fb3078d5c3) | Apr 12, 2023 |
| Fujitsu       | LIFEBOOK U7411              | Notebook    | [b054f2bcd1](https://linux-hardware.org/?probe=b054f2bcd1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [238037e4b8](https://linux-hardware.org/?probe=238037e4b8) | Apr 11, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [69f8d7dfdf](https://linux-hardware.org/?probe=69f8d7dfdf) | Apr 11, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [e0f6223c25](https://linux-hardware.org/?probe=e0f6223c25) | Apr 10, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [cb009d5401](https://linux-hardware.org/?probe=cb009d5401) | Apr 10, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [69ee985017](https://linux-hardware.org/?probe=69ee985017) | Apr 09, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [617f2a18bb](https://linux-hardware.org/?probe=617f2a18bb) | Apr 09, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [c2132caa73](https://linux-hardware.org/?probe=c2132caa73) | Apr 08, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [2f4fb987b8](https://linux-hardware.org/?probe=2f4fb987b8) | Apr 07, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [0258b5925f](https://linux-hardware.org/?probe=0258b5925f) | Apr 07, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [5ff7c0183d](https://linux-hardware.org/?probe=5ff7c0183d) | Apr 07, 2023 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [0bdc444de8](https://linux-hardware.org/?probe=0bdc444de8) | Apr 05, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [a0e2b31c08](https://linux-hardware.org/?probe=a0e2b31c08) | Apr 05, 2023 |
| Dell          | Latitude 5430               | Notebook    | [6494113c9b](https://linux-hardware.org/?probe=6494113c9b) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming FX705DY_TUF70... | Notebook    | [85e0077c83](https://linux-hardware.org/?probe=85e0077c83) | Apr 03, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [aead33a5e6](https://linux-hardware.org/?probe=aead33a5e6) | Apr 01, 2023 |
| MSI           | MAG A520M VECTOR WIFI       | Desktop     | [3c08cf9aba](https://linux-hardware.org/?probe=3c08cf9aba) | Apr 01, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [1da5570114](https://linux-hardware.org/?probe=1da5570114) | Apr 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a1fa08efc6](https://linux-hardware.org/?probe=a1fa08efc6) | Mar 30, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [e9988edacd](https://linux-hardware.org/?probe=e9988edacd) | Mar 30, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [3db646f782](https://linux-hardware.org/?probe=3db646f782) | Mar 29, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [3b7fe31c07](https://linux-hardware.org/?probe=3b7fe31c07) | Mar 29, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e6b01be2f1](https://linux-hardware.org/?probe=e6b01be2f1) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [b7a0579d38](https://linux-hardware.org/?probe=b7a0579d38) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [88d5c3bb9f](https://linux-hardware.org/?probe=88d5c3bb9f) | Mar 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [d7b0ec58d5](https://linux-hardware.org/?probe=d7b0ec58d5) | Mar 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [701b74ce3e](https://linux-hardware.org/?probe=701b74ce3e) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [e973d0294d](https://linux-hardware.org/?probe=e973d0294d) | Mar 22, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | Notebook    | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7fb78c1c79](https://linux-hardware.org/?probe=7fb78c1c79) | Mar 20, 2023 |
| ASUSTek       | M5A78L LE                   | Desktop     | [e18778e282](https://linux-hardware.org/?probe=e18778e282) | Mar 20, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [47fd974afd](https://linux-hardware.org/?probe=47fd974afd) | Mar 20, 2023 |
| HP            | 3646h                       | Desktop     | [812e12695b](https://linux-hardware.org/?probe=812e12695b) | Mar 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [22290c7abf](https://linux-hardware.org/?probe=22290c7abf) | Mar 19, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [a3cee7c278](https://linux-hardware.org/?probe=a3cee7c278) | Mar 19, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c770db7fd](https://linux-hardware.org/?probe=7c770db7fd) | Mar 18, 2023 |
| Unknown       | Unknown                     | Desktop     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [9765f2823e](https://linux-hardware.org/?probe=9765f2823e) | Mar 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [f13da06079](https://linux-hardware.org/?probe=f13da06079) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e7dd32b931](https://linux-hardware.org/?probe=e7dd32b931) | Mar 15, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [557a08d242](https://linux-hardware.org/?probe=557a08d242) | Mar 15, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [48370f2817](https://linux-hardware.org/?probe=48370f2817) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| Toshiba       | Satellite P300              | Notebook    | [1872bc8b57](https://linux-hardware.org/?probe=1872bc8b57) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [59d2c50a02](https://linux-hardware.org/?probe=59d2c50a02) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| ASUSTek       | X202EV                      | Notebook    | [db21e9ac28](https://linux-hardware.org/?probe=db21e9ac28) | Mar 13, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [7a20b4f81a](https://linux-hardware.org/?probe=7a20b4f81a) | Mar 12, 2023 |
| HP            | ENVY Notebook               | Notebook    | [8a063efa19](https://linux-hardware.org/?probe=8a063efa19) | Mar 09, 2023 |
| MSI           | GF65 Thin 9SD               | Notebook    | [ea69b96e55](https://linux-hardware.org/?probe=ea69b96e55) | Mar 09, 2023 |
| Dell          | Latitude E4310              | Notebook    | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| Lenovo        | ThinkPad T470 20HD0001PG    | Notebook    | [be61e16d11](https://linux-hardware.org/?probe=be61e16d11) | Mar 08, 2023 |
| Dell          | Latitude E5570              | Notebook    | [5a5d668611](https://linux-hardware.org/?probe=5a5d668611) | Mar 07, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [2728efea53](https://linux-hardware.org/?probe=2728efea53) | Mar 05, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [7235211822](https://linux-hardware.org/?probe=7235211822) | Mar 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e61f05b7f6](https://linux-hardware.org/?probe=e61f05b7f6) | Mar 05, 2023 |
| MSI           | GF72 8RD                    | Notebook    | [54eb266d2a](https://linux-hardware.org/?probe=54eb266d2a) | Mar 04, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [240adbe154](https://linux-hardware.org/?probe=240adbe154) | Mar 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C30... | Notebook    | [1fb81359e0](https://linux-hardware.org/?probe=1fb81359e0) | Mar 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [5715b4e8af](https://linux-hardware.org/?probe=5715b4e8af) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [26b308e28a](https://linux-hardware.org/?probe=26b308e28a) | Mar 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [73776ef4dd](https://linux-hardware.org/?probe=73776ef4dd) | Mar 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [73c765dbe2](https://linux-hardware.org/?probe=73c765dbe2) | Mar 01, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [7997191f44](https://linux-hardware.org/?probe=7997191f44) | Feb 28, 2023 |
| ASUSTek       | Z87-PRO                     | Desktop     | [9a6bc5f3af](https://linux-hardware.org/?probe=9a6bc5f3af) | Feb 28, 2023 |
| Lenovo        | ThinkPad T480 20L6SEH700    | Notebook    | [4a187e016b](https://linux-hardware.org/?probe=4a187e016b) | Feb 27, 2023 |
| HP            | Compaq 6730b (FU594ES#AB... | Notebook    | [810cdb1ad1](https://linux-hardware.org/?probe=810cdb1ad1) | Feb 26, 2023 |
| ASUSTek       | B85M-E                      | Desktop     | [8fb68b4ad6](https://linux-hardware.org/?probe=8fb68b4ad6) | Feb 26, 2023 |
| Dell          | 0MY171 A00                  | Desktop     | [795f707b1a](https://linux-hardware.org/?probe=795f707b1a) | Feb 25, 2023 |
| Lenovo        | ThinkPad T480 20L5S03600    | Notebook    | [5c9736ab0c](https://linux-hardware.org/?probe=5c9736ab0c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [7b59cbd067](https://linux-hardware.org/?probe=7b59cbd067) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d99e163be6](https://linux-hardware.org/?probe=d99e163be6) | Feb 24, 2023 |
| HP            | mt40                        | Notebook    | [16e5f8eb5d](https://linux-hardware.org/?probe=16e5f8eb5d) | Feb 23, 2023 |
| MSI           | GF72 8RD                    | Notebook    | [cf6dad63da](https://linux-hardware.org/?probe=cf6dad63da) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [e062475561](https://linux-hardware.org/?probe=e062475561) | Feb 20, 2023 |
| ASUSTek       | BM6630_BM6330_BP6230        | Desktop     | [5d6240bcc6](https://linux-hardware.org/?probe=5d6240bcc6) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [fe75bac6ce](https://linux-hardware.org/?probe=fe75bac6ce) | Feb 19, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [605089c66c](https://linux-hardware.org/?probe=605089c66c) | Feb 19, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [387aa81d4c](https://linux-hardware.org/?probe=387aa81d4c) | Feb 18, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [ebaa8145e1](https://linux-hardware.org/?probe=ebaa8145e1) | Feb 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [bb1c4209c7](https://linux-hardware.org/?probe=bb1c4209c7) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [42b7f88059](https://linux-hardware.org/?probe=42b7f88059) | Feb 16, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [3ebf4858b8](https://linux-hardware.org/?probe=3ebf4858b8) | Feb 16, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [ef69c22820](https://linux-hardware.org/?probe=ef69c22820) | Feb 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [4e6c625797](https://linux-hardware.org/?probe=4e6c625797) | Feb 15, 2023 |
| MSI           | Z68MA-ED55                  | Desktop     | [e2bd6f0fb4](https://linux-hardware.org/?probe=e2bd6f0fb4) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [da3617cc40](https://linux-hardware.org/?probe=da3617cc40) | Feb 14, 2023 |
| Gigabyte      | P65                         | Notebook    | [b3d7faba21](https://linux-hardware.org/?probe=b3d7faba21) | Feb 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4344acac5e](https://linux-hardware.org/?probe=4344acac5e) | Feb 11, 2023 |
| Gigabyte      | P65                         | Notebook    | [25d871afca](https://linux-hardware.org/?probe=25d871afca) | Feb 11, 2023 |
| IBM           | 819046G                     | Desktop     | [a43370bbbd](https://linux-hardware.org/?probe=a43370bbbd) | Feb 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [b6b590fcdf](https://linux-hardware.org/?probe=b6b590fcdf) | Feb 11, 2023 |
| Dell          | Latitude 7370               | Notebook    | [30c62c9e44](https://linux-hardware.org/?probe=30c62c9e44) | Feb 10, 2023 |
| Dell          | Latitude 7370               | Notebook    | [b4e7a5cb63](https://linux-hardware.org/?probe=b4e7a5cb63) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [25e4994344](https://linux-hardware.org/?probe=25e4994344) | Feb 09, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d0319bdf17](https://linux-hardware.org/?probe=d0319bdf17) | Feb 09, 2023 |
| Acer          | Aspire S7-391               | Notebook    | [3777a7d1e9](https://linux-hardware.org/?probe=3777a7d1e9) | Feb 08, 2023 |
| MSI           | A78M-E35                    | Desktop     | [ba4515e5ea](https://linux-hardware.org/?probe=ba4515e5ea) | Feb 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f268d3da5e](https://linux-hardware.org/?probe=f268d3da5e) | Feb 08, 2023 |
| Acer          | Aspire V3-572G              | Notebook    | [7b48d97053](https://linux-hardware.org/?probe=7b48d97053) | Feb 07, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3bba794976](https://linux-hardware.org/?probe=3bba794976) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [b2247eafed](https://linux-hardware.org/?probe=b2247eafed) | Feb 05, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [9299261af6](https://linux-hardware.org/?probe=9299261af6) | Feb 05, 2023 |
| Dell          | Precision 7550              | Notebook    | [9608ff008d](https://linux-hardware.org/?probe=9608ff008d) | Feb 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [e3ab731c3c](https://linux-hardware.org/?probe=e3ab731c3c) | Feb 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [d0cf3a9d76](https://linux-hardware.org/?probe=d0cf3a9d76) | Feb 02, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [367646ee16](https://linux-hardware.org/?probe=367646ee16) | Feb 02, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [a8f54f681a](https://linux-hardware.org/?probe=a8f54f681a) | Feb 01, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| INSYS         | GW1-W149                    | Notebook    | [5a4337006d](https://linux-hardware.org/?probe=5a4337006d) | Jan 28, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1a9e67408e](https://linux-hardware.org/?probe=1a9e67408e) | Jan 28, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [d9ceb3c732](https://linux-hardware.org/?probe=d9ceb3c732) | Jan 27, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [4e8cd1aa46](https://linux-hardware.org/?probe=4e8cd1aa46) | Jan 26, 2023 |
| Acer          | RS740DVF                    | Desktop     | [6aaeb06f9a](https://linux-hardware.org/?probe=6aaeb06f9a) | Jan 26, 2023 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [a9567dc72b](https://linux-hardware.org/?probe=a9567dc72b) | Jan 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [a8ee7729d5](https://linux-hardware.org/?probe=a8ee7729d5) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3a542dd368](https://linux-hardware.org/?probe=3a542dd368) | Jan 22, 2023 |
| ASUSTek       | UX360CA                     | Notebook    | [98fa78d117](https://linux-hardware.org/?probe=98fa78d117) | Jan 22, 2023 |
| Acer          | Aspire E1-522               | Notebook    | [ad5202642a](https://linux-hardware.org/?probe=ad5202642a) | Jan 22, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Pegatron      | Narra6                      | Desktop     | [ac9462ee8e](https://linux-hardware.org/?probe=ac9462ee8e) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [09dbcb3ae4](https://linux-hardware.org/?probe=09dbcb3ae4) | Jan 20, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [a929c23a1b](https://linux-hardware.org/?probe=a929c23a1b) | Jan 20, 2023 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [9324b897c3](https://linux-hardware.org/?probe=9324b897c3) | Jan 19, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [11ce0ed5ad](https://linux-hardware.org/?probe=11ce0ed5ad) | Jan 18, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [95074766b9](https://linux-hardware.org/?probe=95074766b9) | Jan 18, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [cd6cedc906](https://linux-hardware.org/?probe=cd6cedc906) | Jan 17, 2023 |
| ASUSTek       | Benicia                     | Desktop     | [c0441ff1e5](https://linux-hardware.org/?probe=c0441ff1e5) | Jan 17, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [60a0157a51](https://linux-hardware.org/?probe=60a0157a51) | Jan 16, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [0b2ae38776](https://linux-hardware.org/?probe=0b2ae38776) | Jan 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [bbf1dabe59](https://linux-hardware.org/?probe=bbf1dabe59) | Jan 14, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [d45c8ef0ac](https://linux-hardware.org/?probe=d45c8ef0ac) | Jan 13, 2023 |
| Acer          | Aspire V5-122               | Notebook    | [a25a7c3fb1](https://linux-hardware.org/?probe=a25a7c3fb1) | Jan 12, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [7c62282370](https://linux-hardware.org/?probe=7c62282370) | Jan 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [e9783891d1](https://linux-hardware.org/?probe=e9783891d1) | Jan 12, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [07f15478a7](https://linux-hardware.org/?probe=07f15478a7) | Jan 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [71c61d98b9](https://linux-hardware.org/?probe=71c61d98b9) | Jan 10, 2023 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [d27b435baf](https://linux-hardware.org/?probe=d27b435baf) | Jan 10, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [cb970f09e6](https://linux-hardware.org/?probe=cb970f09e6) | Jan 09, 2023 |
| HP            | 0AA4h                       | Desktop     | [8d177b0b8d](https://linux-hardware.org/?probe=8d177b0b8d) | Jan 09, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [39ec0d3441](https://linux-hardware.org/?probe=39ec0d3441) | Jan 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [ce97b4a08f](https://linux-hardware.org/?probe=ce97b4a08f) | Jan 08, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [7e0d372f98](https://linux-hardware.org/?probe=7e0d372f98) | Jan 08, 2023 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [bdc427771d](https://linux-hardware.org/?probe=bdc427771d) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [50d2637c41](https://linux-hardware.org/?probe=50d2637c41) | Jan 07, 2023 |
| HP            | 83EE                        | Desktop     | [cb43945233](https://linux-hardware.org/?probe=cb43945233) | Jan 07, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [aff5a2ce85](https://linux-hardware.org/?probe=aff5a2ce85) | Jan 07, 2023 |
| Schenker      | XMG FUSION 15 (XFU15L19)    | Notebook    | [b69c9f59d5](https://linux-hardware.org/?probe=b69c9f59d5) | Jan 06, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [db0e909d27](https://linux-hardware.org/?probe=db0e909d27) | Jan 06, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9f0fb0adf5](https://linux-hardware.org/?probe=9f0fb0adf5) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | Notebook    | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [eefb2d0334](https://linux-hardware.org/?probe=eefb2d0334) | Jan 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [76d75de6ac](https://linux-hardware.org/?probe=76d75de6ac) | Jan 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [dfb32a8abb](https://linux-hardware.org/?probe=dfb32a8abb) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [bbd09c7b2c](https://linux-hardware.org/?probe=bbd09c7b2c) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [013b1e7816](https://linux-hardware.org/?probe=013b1e7816) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | Notebook    | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [113a2a45b2](https://linux-hardware.org/?probe=113a2a45b2) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [34528f04fe](https://linux-hardware.org/?probe=34528f04fe) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [7295ec02b5](https://linux-hardware.org/?probe=7295ec02b5) | Dec 31, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [2161cbc9a0](https://linux-hardware.org/?probe=2161cbc9a0) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [9d307c5f2f](https://linux-hardware.org/?probe=9d307c5f2f) | Dec 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [bc835cbca9](https://linux-hardware.org/?probe=bc835cbca9) | Dec 31, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [76e9829e66](https://linux-hardware.org/?probe=76e9829e66) | Dec 30, 2022 |
| Toshiba       | Satellite L775-12V          | Notebook    | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [042fb842d2](https://linux-hardware.org/?probe=042fb842d2) | Dec 27, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [ded2e7e4e6](https://linux-hardware.org/?probe=ded2e7e4e6) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [b181e9e5a3](https://linux-hardware.org/?probe=b181e9e5a3) | Dec 26, 2022 |
| MSI           | B350 KRAIT GAMING           | Desktop     | [896aebf101](https://linux-hardware.org/?probe=896aebf101) | Dec 25, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [82f8802857](https://linux-hardware.org/?probe=82f8802857) | Dec 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [f980d6ed2e](https://linux-hardware.org/?probe=f980d6ed2e) | Dec 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 3 21C5C... | Notebook    | [a5dcdfece2](https://linux-hardware.org/?probe=a5dcdfece2) | Dec 23, 2022 |
| Dell          | Latitude E4310              | Notebook    | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [982f470134](https://linux-hardware.org/?probe=982f470134) | Dec 21, 2022 |
| HP            | 0980h                       | Desktop     | [d54665c87c](https://linux-hardware.org/?probe=d54665c87c) | Dec 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| MSI           | H81M-P33                    | Desktop     | [5d91d96949](https://linux-hardware.org/?probe=5d91d96949) | Dec 20, 2022 |
| HP            | 0980h                       | Desktop     | [3faf0c7996](https://linux-hardware.org/?probe=3faf0c7996) | Dec 20, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [41fb3c537a](https://linux-hardware.org/?probe=41fb3c537a) | Dec 19, 2022 |
| Thomson       | PT-NEO14A.2WH32             | Notebook    | [d028ff11a9](https://linux-hardware.org/?probe=d028ff11a9) | Dec 18, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [10e579b77e](https://linux-hardware.org/?probe=10e579b77e) | Dec 18, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [3847c61b81](https://linux-hardware.org/?probe=3847c61b81) | Dec 17, 2022 |
| Dell          | 03V7GF A01                  | Desktop     | [e491b54a3c](https://linux-hardware.org/?probe=e491b54a3c) | Dec 17, 2022 |
| Unknown       | Unknown                     | Desktop     | [988a2e80c0](https://linux-hardware.org/?probe=988a2e80c0) | Dec 17, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Dell          | 0MY171 A00                  | Desktop     | [055bc4ea78](https://linux-hardware.org/?probe=055bc4ea78) | Dec 13, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Dell          | Precision 5510              | Notebook    | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| ASRock        | G31M-GS                     | Desktop     | [2e1fc34b39](https://linux-hardware.org/?probe=2e1fc34b39) | Dec 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [d83227cce9](https://linux-hardware.org/?probe=d83227cce9) | Dec 10, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [4f392d3575](https://linux-hardware.org/?probe=4f392d3575) | Dec 10, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [8008043900](https://linux-hardware.org/?probe=8008043900) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [0c6e399e4f](https://linux-hardware.org/?probe=0c6e399e4f) | Dec 09, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [9c083ab22c](https://linux-hardware.org/?probe=9c083ab22c) | Dec 09, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [f943786d2c](https://linux-hardware.org/?probe=f943786d2c) | Dec 09, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [29c71a771b](https://linux-hardware.org/?probe=29c71a771b) | Dec 08, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [1519fb3a87](https://linux-hardware.org/?probe=1519fb3a87) | Dec 06, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [34157244aa](https://linux-hardware.org/?probe=34157244aa) | Dec 05, 2022 |
| Packard Be... | FIH57                       | Desktop     | [a98f4adbab](https://linux-hardware.org/?probe=a98f4adbab) | Dec 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [8a940a493b](https://linux-hardware.org/?probe=8a940a493b) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [5ab13c42b3](https://linux-hardware.org/?probe=5ab13c42b3) | Dec 03, 2022 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [b3ab0684c5](https://linux-hardware.org/?probe=b3ab0684c5) | Dec 03, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [e28a13071a](https://linux-hardware.org/?probe=e28a13071a) | Dec 02, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [44a7c01e06](https://linux-hardware.org/?probe=44a7c01e06) | Dec 02, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [c03f783ea5](https://linux-hardware.org/?probe=c03f783ea5) | Dec 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a6a71120f2](https://linux-hardware.org/?probe=a6a71120f2) | Nov 30, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [e5468e4258](https://linux-hardware.org/?probe=e5468e4258) | Nov 30, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [6bb64e8108](https://linux-hardware.org/?probe=6bb64e8108) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [bbb8e289a9](https://linux-hardware.org/?probe=bbb8e289a9) | Nov 29, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [def1faf044](https://linux-hardware.org/?probe=def1faf044) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| MSI           | GF72 8RD                    | Notebook    | [fb92041c1b](https://linux-hardware.org/?probe=fb92041c1b) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| HP            | 18E7                        | Desktop     | [5a5c2667a5](https://linux-hardware.org/?probe=5a5c2667a5) | Nov 26, 2022 |
| ASUSTek       | F7SR                        | Notebook    | [ecdba533ea](https://linux-hardware.org/?probe=ecdba533ea) | Nov 25, 2022 |
| ASUSTek       | F7SR                        | Notebook    | [8102d8b361](https://linux-hardware.org/?probe=8102d8b361) | Nov 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ccf106edce](https://linux-hardware.org/?probe=ccf106edce) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [95f653bddb](https://linux-hardware.org/?probe=95f653bddb) | Nov 24, 2022 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [a4a2b60b09](https://linux-hardware.org/?probe=a4a2b60b09) | Nov 24, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [2de63dfd54](https://linux-hardware.org/?probe=2de63dfd54) | Nov 23, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [99fc338b3e](https://linux-hardware.org/?probe=99fc338b3e) | Nov 23, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [814f45a510](https://linux-hardware.org/?probe=814f45a510) | Nov 23, 2022 |
| Apple         | MacBookAir5,1               | Notebook    | [2ded48104d](https://linux-hardware.org/?probe=2ded48104d) | Nov 22, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [8e134485ce](https://linux-hardware.org/?probe=8e134485ce) | Nov 22, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [0584338e31](https://linux-hardware.org/?probe=0584338e31) | Nov 22, 2022 |
| Acer          | Popcorn                     | Notebook    | [6f446a097a](https://linux-hardware.org/?probe=6f446a097a) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| MSI           | 990FXA-GD65                 | Desktop     | [d41acd5075](https://linux-hardware.org/?probe=d41acd5075) | Nov 20, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [02c6e2e360](https://linux-hardware.org/?probe=02c6e2e360) | Nov 18, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [d4c27f1388](https://linux-hardware.org/?probe=d4c27f1388) | Nov 18, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [3b33d1989a](https://linux-hardware.org/?probe=3b33d1989a) | Nov 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [0401b9e939](https://linux-hardware.org/?probe=0401b9e939) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | Notebook    | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [2455b541f5](https://linux-hardware.org/?probe=2455b541f5) | Nov 16, 2022 |
| ASUSTek       | G752VS                      | Notebook    | [364d6d09ab](https://linux-hardware.org/?probe=364d6d09ab) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c54708e797](https://linux-hardware.org/?probe=c54708e797) | Nov 14, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c332019d7e](https://linux-hardware.org/?probe=c332019d7e) | Nov 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e54df5cb0d](https://linux-hardware.org/?probe=e54df5cb0d) | Nov 13, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [2c896d28a8](https://linux-hardware.org/?probe=2c896d28a8) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| ASUSTek       | A6JC                        | Notebook    | [dce6c2a8f4](https://linux-hardware.org/?probe=dce6c2a8f4) | Nov 13, 2022 |
| Packard Be... | EasyNote LV11HC             | Notebook    | [244d508935](https://linux-hardware.org/?probe=244d508935) | Nov 12, 2022 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [dc1c83bed5](https://linux-hardware.org/?probe=dc1c83bed5) | Nov 11, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c1f18206f4](https://linux-hardware.org/?probe=c1f18206f4) | Nov 11, 2022 |
| eMachines     | G525                        | Notebook    | [38b8684942](https://linux-hardware.org/?probe=38b8684942) | Nov 10, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [5205b24cb0](https://linux-hardware.org/?probe=5205b24cb0) | Nov 08, 2022 |
| Dell          | Latitude E6510              | Notebook    | [befb811cfe](https://linux-hardware.org/?probe=befb811cfe) | Nov 05, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [a1cef4e43d](https://linux-hardware.org/?probe=a1cef4e43d) | Nov 04, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [b58a40d876](https://linux-hardware.org/?probe=b58a40d876) | Nov 04, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [fe997bad04](https://linux-hardware.org/?probe=fe997bad04) | Nov 03, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [1bbd4f8bd9](https://linux-hardware.org/?probe=1bbd4f8bd9) | Nov 03, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [27f288e5f1](https://linux-hardware.org/?probe=27f288e5f1) | Nov 01, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c46dd8d9b6](https://linux-hardware.org/?probe=c46dd8d9b6) | Nov 01, 2022 |
| Dell          | Latitude E6510              | Notebook    | [b346d71347](https://linux-hardware.org/?probe=b346d71347) | Oct 29, 2022 |
| Acer          | Aspire SW5-012              | Notebook    | [90dd31edc8](https://linux-hardware.org/?probe=90dd31edc8) | Oct 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Pegatron      | TRUCKEE                     | Desktop     | [2a6fe2bcd1](https://linux-hardware.org/?probe=2a6fe2bcd1) | Oct 28, 2022 |
| Acer          | Aspire ES1-131              | Notebook    | [f0edf4897a](https://linux-hardware.org/?probe=f0edf4897a) | Oct 26, 2022 |
| Dell          | Latitude 7320               | Notebook    | [f249267def](https://linux-hardware.org/?probe=f249267def) | Oct 26, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [8ebb941ac6](https://linux-hardware.org/?probe=8ebb941ac6) | Oct 26, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [fe6fb20830](https://linux-hardware.org/?probe=fe6fb20830) | Oct 25, 2022 |
| Toshiba       | NB300                       | Notebook    | [c5aa7d3c5f](https://linux-hardware.org/?probe=c5aa7d3c5f) | Oct 25, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ede3bcd3f3](https://linux-hardware.org/?probe=ede3bcd3f3) | Oct 24, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [fe9ec739e2](https://linux-hardware.org/?probe=fe9ec739e2) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [6354f13944](https://linux-hardware.org/?probe=6354f13944) | Oct 21, 2022 |
| HP            | G62                         | Notebook    | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [e5f7b07e9c](https://linux-hardware.org/?probe=e5f7b07e9c) | Oct 19, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [25bb674789](https://linux-hardware.org/?probe=25bb674789) | Oct 19, 2022 |
| HP            | 8158 A01                    | Mini pc     | [d7021dfe8a](https://linux-hardware.org/?probe=d7021dfe8a) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [ba7c1c3d83](https://linux-hardware.org/?probe=ba7c1c3d83) | Oct 14, 2022 |
| HP            | 805D                        | Desktop     | [ece9f05ea6](https://linux-hardware.org/?probe=ece9f05ea6) | Oct 14, 2022 |
| HP            | 805D                        | Desktop     | [f10271c447](https://linux-hardware.org/?probe=f10271c447) | Oct 14, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [ca8ac557b3](https://linux-hardware.org/?probe=ca8ac557b3) | Oct 14, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [d83c027361](https://linux-hardware.org/?probe=d83c027361) | Oct 12, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [2460d79ba8](https://linux-hardware.org/?probe=2460d79ba8) | Oct 10, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [9eaf0bffca](https://linux-hardware.org/?probe=9eaf0bffca) | Oct 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [184ecb5e76](https://linux-hardware.org/?probe=184ecb5e76) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | Notebook    | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [be6a0fda35](https://linux-hardware.org/?probe=be6a0fda35) | Oct 08, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [76d2eeb1d0](https://linux-hardware.org/?probe=76d2eeb1d0) | Oct 07, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8061516838](https://linux-hardware.org/?probe=8061516838) | Oct 06, 2022 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [abe6a3fde2](https://linux-hardware.org/?probe=abe6a3fde2) | Oct 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [a3d3100ffa](https://linux-hardware.org/?probe=a3d3100ffa) | Oct 05, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [b50cfdccab](https://linux-hardware.org/?probe=b50cfdccab) | Oct 05, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [8d863ae2d8](https://linux-hardware.org/?probe=8d863ae2d8) | Oct 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a055ed4d2c](https://linux-hardware.org/?probe=a055ed4d2c) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| HP            | ENVY 15                     | Notebook    | [950623d8b2](https://linux-hardware.org/?probe=950623d8b2) | Oct 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [d9a196cd8e](https://linux-hardware.org/?probe=d9a196cd8e) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [516795a4a8](https://linux-hardware.org/?probe=516795a4a8) | Oct 02, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [5bdf95fbdc](https://linux-hardware.org/?probe=5bdf95fbdc) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [7ff2c5ad1c](https://linux-hardware.org/?probe=7ff2c5ad1c) | Oct 01, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [a64cec6a4d](https://linux-hardware.org/?probe=a64cec6a4d) | Oct 01, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [5c5666fa97](https://linux-hardware.org/?probe=5c5666fa97) | Sep 29, 2022 |
| GIADA         | ChiefRiver Platform         | Notebook    | [d0f71cdc7f](https://linux-hardware.org/?probe=d0f71cdc7f) | Sep 26, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [9fff405744](https://linux-hardware.org/?probe=9fff405744) | Sep 26, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [34035b63b6](https://linux-hardware.org/?probe=34035b63b6) | Sep 25, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [84d47822bf](https://linux-hardware.org/?probe=84d47822bf) | Sep 24, 2022 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [3afd2e892b](https://linux-hardware.org/?probe=3afd2e892b) | Sep 24, 2022 |
| Acer          | Predator PH315-51           | Notebook    | [24ae1f3fb8](https://linux-hardware.org/?probe=24ae1f3fb8) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [47f145c034](https://linux-hardware.org/?probe=47f145c034) | Sep 23, 2022 |
| ASUSTek       | X556UF                      | Notebook    | [2f1fe986d8](https://linux-hardware.org/?probe=2f1fe986d8) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| ASRock        | B550 Pro4                   | Desktop     | [a1009d700e](https://linux-hardware.org/?probe=a1009d700e) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [910b604abc](https://linux-hardware.org/?probe=910b604abc) | Sep 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b72e23e590](https://linux-hardware.org/?probe=b72e23e590) | Sep 20, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [70a7e5cad3](https://linux-hardware.org/?probe=70a7e5cad3) | Sep 20, 2022 |
| MSI           | Z77A-G45                    | Desktop     | [b5a8d40602](https://linux-hardware.org/?probe=b5a8d40602) | Sep 18, 2022 |
| Toshiba       | Satellite P845T             | Notebook    | [0d5f5ac925](https://linux-hardware.org/?probe=0d5f5ac925) | Sep 17, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [dd6d053ae2](https://linux-hardware.org/?probe=dd6d053ae2) | Sep 17, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| ASUSTek       | X555LJ                      | Notebook    | [5d27ea49aa](https://linux-hardware.org/?probe=5d27ea49aa) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [e558fd5212](https://linux-hardware.org/?probe=e558fd5212) | Sep 13, 2022 |
| Lenovo        | ThinkPad W540 20BG0016US    | Notebook    | [9f0543edc4](https://linux-hardware.org/?probe=9f0543edc4) | Sep 11, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [4f29128588](https://linux-hardware.org/?probe=4f29128588) | Sep 11, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [a7931f2026](https://linux-hardware.org/?probe=a7931f2026) | Sep 10, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [eb81d635df](https://linux-hardware.org/?probe=eb81d635df) | Sep 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [71717109c3](https://linux-hardware.org/?probe=71717109c3) | Sep 10, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| Apple         | Mac-F2218FA9                | All in one  | [4a791df589](https://linux-hardware.org/?probe=4a791df589) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ab939db2c0](https://linux-hardware.org/?probe=ab939db2c0) | Sep 10, 2022 |
| ASUSTek       | ZenBook UX533FD_UX533FD     | Notebook    | [f9604390e8](https://linux-hardware.org/?probe=f9604390e8) | Sep 10, 2022 |
| Rockchip      | RK3318 BOX                  | Soc         | [bf1aba4ebe](https://linux-hardware.org/?probe=bf1aba4ebe) | Sep 10, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [038f57c2d8](https://linux-hardware.org/?probe=038f57c2d8) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5d61bcd114](https://linux-hardware.org/?probe=5d61bcd114) | Sep 06, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [bcd73bee62](https://linux-hardware.org/?probe=bcd73bee62) | Sep 06, 2022 |
| HP            | Pavilion g6                 | Notebook    | [770b1a8154](https://linux-hardware.org/?probe=770b1a8154) | Sep 05, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c2cd1091cd](https://linux-hardware.org/?probe=c2cd1091cd) | Sep 04, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [66724351c4](https://linux-hardware.org/?probe=66724351c4) | Sep 04, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [b99831e9f4](https://linux-hardware.org/?probe=b99831e9f4) | Sep 03, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a74d79fc0b](https://linux-hardware.org/?probe=a74d79fc0b) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [8a7e7ce8ea](https://linux-hardware.org/?probe=8a7e7ce8ea) | Sep 01, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [6fa51d2c4e](https://linux-hardware.org/?probe=6fa51d2c4e) | Aug 31, 2022 |
| OEM           | Intel H81                   | Desktop     | [4b45e6dc61](https://linux-hardware.org/?probe=4b45e6dc61) | Aug 31, 2022 |
| ASUSTek       | X541UJ                      | Notebook    | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [11efd3dbe0](https://linux-hardware.org/?probe=11efd3dbe0) | Aug 30, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [f90886ae85](https://linux-hardware.org/?probe=f90886ae85) | Aug 30, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [3b26a2ffe2](https://linux-hardware.org/?probe=3b26a2ffe2) | Aug 29, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [98ac365e3c](https://linux-hardware.org/?probe=98ac365e3c) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [73db272ecb](https://linux-hardware.org/?probe=73db272ecb) | Aug 28, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ee07c7a93a](https://linux-hardware.org/?probe=ee07c7a93a) | Aug 27, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [8ffebf0c43](https://linux-hardware.org/?probe=8ffebf0c43) | Aug 26, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [08f930384d](https://linux-hardware.org/?probe=08f930384d) | Aug 25, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [30be913709](https://linux-hardware.org/?probe=30be913709) | Aug 25, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [fc50d4e200](https://linux-hardware.org/?probe=fc50d4e200) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [cb533d9c12](https://linux-hardware.org/?probe=cb533d9c12) | Aug 22, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [ba3fb2513f](https://linux-hardware.org/?probe=ba3fb2513f) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7ee8720a43](https://linux-hardware.org/?probe=7ee8720a43) | Aug 21, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [9131aa23c4](https://linux-hardware.org/?probe=9131aa23c4) | Aug 20, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [ed1f055157](https://linux-hardware.org/?probe=ed1f055157) | Aug 19, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [764eaea2ba](https://linux-hardware.org/?probe=764eaea2ba) | Aug 19, 2022 |
| Lenovo        | ThinkPad P50 20EN0005PG     | Notebook    | [69c8e5eedc](https://linux-hardware.org/?probe=69c8e5eedc) | Aug 19, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [2bf774fae7](https://linux-hardware.org/?probe=2bf774fae7) | Aug 18, 2022 |
| MSI           | B85M-E45                    | Desktop     | [cb991c0789](https://linux-hardware.org/?probe=cb991c0789) | Aug 17, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57732104cd](https://linux-hardware.org/?probe=57732104cd) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| ASUSTek       | Basswood                    | Desktop     | [26e4efad3f](https://linux-hardware.org/?probe=26e4efad3f) | Aug 14, 2022 |
| ASUSTek       | N53SN                       | Notebook    | [6cb4ac4247](https://linux-hardware.org/?probe=6cb4ac4247) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [73a3d7c1cf](https://linux-hardware.org/?probe=73a3d7c1cf) | Aug 12, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [4d1acc8488](https://linux-hardware.org/?probe=4d1acc8488) | Aug 11, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [9979c66e3e](https://linux-hardware.org/?probe=9979c66e3e) | Aug 11, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [48b0dfdee0](https://linux-hardware.org/?probe=48b0dfdee0) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9d6be5eb68](https://linux-hardware.org/?probe=9d6be5eb68) | Aug 08, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [18935d4aff](https://linux-hardware.org/?probe=18935d4aff) | Aug 07, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [154468415c](https://linux-hardware.org/?probe=154468415c) | Aug 05, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [6f355de994](https://linux-hardware.org/?probe=6f355de994) | Aug 04, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [5ebf9417bf](https://linux-hardware.org/?probe=5ebf9417bf) | Aug 04, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [abf1fcf08b](https://linux-hardware.org/?probe=abf1fcf08b) | Aug 02, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [508b0275e3](https://linux-hardware.org/?probe=508b0275e3) | Aug 02, 2022 |
| Gigabyte      | H110M-Gaming3-CF            | Desktop     | [99a140d79b](https://linux-hardware.org/?probe=99a140d79b) | Aug 01, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | Notebook    | [c6ce2d4317](https://linux-hardware.org/?probe=c6ce2d4317) | Jul 31, 2022 |
| HP            | Pavilion dv2000 (RQ116PA... | Notebook    | [eca5fa0c39](https://linux-hardware.org/?probe=eca5fa0c39) | Jul 31, 2022 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [4e30dc6361](https://linux-hardware.org/?probe=4e30dc6361) | Jul 31, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea83758651](https://linux-hardware.org/?probe=ea83758651) | Jul 30, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [bc5b132a8d](https://linux-hardware.org/?probe=bc5b132a8d) | Jul 29, 2022 |
| Toshiba       | Satellite U840              | Notebook    | [c3f00f5b90](https://linux-hardware.org/?probe=c3f00f5b90) | Jul 29, 2022 |
| ASUSTek       | N53SN                       | Notebook    | [2e35ef4a8a](https://linux-hardware.org/?probe=2e35ef4a8a) | Jul 28, 2022 |
| Apple         | Mac-F2238AC8                | All in one  | [5eb6c551b0](https://linux-hardware.org/?probe=5eb6c551b0) | Jul 26, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [0c310749f1](https://linux-hardware.org/?probe=0c310749f1) | Jul 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e95cafce19](https://linux-hardware.org/?probe=e95cafce19) | Jul 26, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [ae71cae955](https://linux-hardware.org/?probe=ae71cae955) | Jul 25, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [ae16c8863a](https://linux-hardware.org/?probe=ae16c8863a) | Jul 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [264bb2f2a1](https://linux-hardware.org/?probe=264bb2f2a1) | Jul 23, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [fc5c252e6e](https://linux-hardware.org/?probe=fc5c252e6e) | Jul 23, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [b3dbd37276](https://linux-hardware.org/?probe=b3dbd37276) | Jul 22, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [c5007c5729](https://linux-hardware.org/?probe=c5007c5729) | Jul 22, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [323aa03c61](https://linux-hardware.org/?probe=323aa03c61) | Jul 18, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [528f562110](https://linux-hardware.org/?probe=528f562110) | Jul 18, 2022 |
| Packard Be... | EasyNote LV11HC             | Notebook    | [c0693d5f9a](https://linux-hardware.org/?probe=c0693d5f9a) | Jul 18, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [bb9f40d075](https://linux-hardware.org/?probe=bb9f40d075) | Jul 18, 2022 |
| Sony          | SVF1521F6EW                 | Notebook    | [3f359d9763](https://linux-hardware.org/?probe=3f359d9763) | Jul 17, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [e1313016ee](https://linux-hardware.org/?probe=e1313016ee) | Jul 17, 2022 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [68884b1723](https://linux-hardware.org/?probe=68884b1723) | Jul 17, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [310a2ada05](https://linux-hardware.org/?probe=310a2ada05) | Jul 13, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [247411abde](https://linux-hardware.org/?probe=247411abde) | Jul 13, 2022 |
| Acer          | FMCP7AM                     | Desktop     | [f2fc2e98c3](https://linux-hardware.org/?probe=f2fc2e98c3) | Jul 10, 2022 |
| IP3 Tech      | AH215                       | All in one  | [10fb10ae7f](https://linux-hardware.org/?probe=10fb10ae7f) | Jul 08, 2022 |
| Sony          | VPCEB3L1E                   | Notebook    | [9af59fca26](https://linux-hardware.org/?probe=9af59fca26) | Jul 08, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [4f31f807cb](https://linux-hardware.org/?probe=4f31f807cb) | Jul 05, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [62d8b20ff8](https://linux-hardware.org/?probe=62d8b20ff8) | Jul 04, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [03bede7266](https://linux-hardware.org/?probe=03bede7266) | Jul 03, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [15088a414c](https://linux-hardware.org/?probe=15088a414c) | Jul 03, 2022 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [bded0a2071](https://linux-hardware.org/?probe=bded0a2071) | Jul 03, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [c0975c6877](https://linux-hardware.org/?probe=c0975c6877) | Jul 02, 2022 |
| ASUSTek       | N61Jq                       | Notebook    | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| Acer          | Aspire A515-54G             | Notebook    | [92d695d6be](https://linux-hardware.org/?probe=92d695d6be) | Jul 02, 2022 |
| HP            | 8169                        | Desktop     | [18c6ea7678](https://linux-hardware.org/?probe=18c6ea7678) | Jul 01, 2022 |
| HP            | 8169                        | Desktop     | [c479baadc1](https://linux-hardware.org/?probe=c479baadc1) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [91c5f849c5](https://linux-hardware.org/?probe=91c5f849c5) | Jun 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [17cb04c5f5](https://linux-hardware.org/?probe=17cb04c5f5) | Jun 29, 2022 |
| HP            | x2 210 G2                   | Tablet      | [812530aed8](https://linux-hardware.org/?probe=812530aed8) | Jun 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [3c116356e3](https://linux-hardware.org/?probe=3c116356e3) | Jun 26, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [e4cd6586b4](https://linux-hardware.org/?probe=e4cd6586b4) | Jun 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [7dde3ae196](https://linux-hardware.org/?probe=7dde3ae196) | Jun 23, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [90038bfa8e](https://linux-hardware.org/?probe=90038bfa8e) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [fd65aaa4b3](https://linux-hardware.org/?probe=fd65aaa4b3) | Jun 21, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [97b9d51036](https://linux-hardware.org/?probe=97b9d51036) | Jun 20, 2022 |
| HP            | ProLiant DL385 G7           | Server      | [89a03359cd](https://linux-hardware.org/?probe=89a03359cd) | Jun 20, 2022 |
| Toshiba       | NB305                       | Notebook    | [1280ac15ba](https://linux-hardware.org/?probe=1280ac15ba) | Jun 17, 2022 |
| MSI           | B85M-E45                    | Desktop     | [58c2ff96e3](https://linux-hardware.org/?probe=58c2ff96e3) | Jun 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [d9b85c0e15](https://linux-hardware.org/?probe=d9b85c0e15) | Jun 16, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [86394fa5df](https://linux-hardware.org/?probe=86394fa5df) | Jun 16, 2022 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [4b1946451e](https://linux-hardware.org/?probe=4b1946451e) | Jun 15, 2022 |
| MSI           | A78M-E45 V2                 | Desktop     | [a2d26ab800](https://linux-hardware.org/?probe=a2d26ab800) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | Desktop     | [70438d549d](https://linux-hardware.org/?probe=70438d549d) | Jun 14, 2022 |
| ASUSTek       | AT5IONT-I                   | Desktop     | [56abd525d8](https://linux-hardware.org/?probe=56abd525d8) | Jun 14, 2022 |
| ASUSTek       | E403SA                      | Notebook    | [9ca6a865ff](https://linux-hardware.org/?probe=9ca6a865ff) | Jun 11, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [f0883ab59b](https://linux-hardware.org/?probe=f0883ab59b) | Jun 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [35dc89f7ff](https://linux-hardware.org/?probe=35dc89f7ff) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | Notebook    | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| HP            | ProLiant DL385 G7           | Server      | [a232d0abd8](https://linux-hardware.org/?probe=a232d0abd8) | Jun 08, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [b5ba2dac2a](https://linux-hardware.org/?probe=b5ba2dac2a) | Jun 06, 2022 |
| Toshiba       | Satellite T130              | Notebook    | [3fe154a2ce](https://linux-hardware.org/?probe=3fe154a2ce) | Jun 06, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [c858bede94](https://linux-hardware.org/?probe=c858bede94) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [f9b7b79d5a](https://linux-hardware.org/?probe=f9b7b79d5a) | Jun 04, 2022 |
| Dell          | Latitude E6400              | Notebook    | [67a5bdc1aa](https://linux-hardware.org/?probe=67a5bdc1aa) | Jun 04, 2022 |
| HP            | Compaq nx7300 (RU464EA#A... | Notebook    | [a44ec57985](https://linux-hardware.org/?probe=a44ec57985) | Jun 02, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [8aff04335d](https://linux-hardware.org/?probe=8aff04335d) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [029a55ffb4](https://linux-hardware.org/?probe=029a55ffb4) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| Lenovo        | ThinkPad T530 2394C98       | Notebook    | [b5aebb2490](https://linux-hardware.org/?probe=b5aebb2490) | May 30, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [f47dbc0616](https://linux-hardware.org/?probe=f47dbc0616) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e72ac27af1](https://linux-hardware.org/?probe=e72ac27af1) | May 30, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [eb522816a1](https://linux-hardware.org/?probe=eb522816a1) | May 29, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [9399a639c8](https://linux-hardware.org/?probe=9399a639c8) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [de7ed0046e](https://linux-hardware.org/?probe=de7ed0046e) | May 29, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [42b16ce834](https://linux-hardware.org/?probe=42b16ce834) | May 28, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [4620e51e7b](https://linux-hardware.org/?probe=4620e51e7b) | May 28, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [9e1d2f7e8a](https://linux-hardware.org/?probe=9e1d2f7e8a) | May 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [533beb13eb](https://linux-hardware.org/?probe=533beb13eb) | May 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f2e5a856f4](https://linux-hardware.org/?probe=f2e5a856f4) | May 25, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| Pine Micro... | Pine64 PinePhone (1.2)      | Phone       | [37f92aa173](https://linux-hardware.org/?probe=37f92aa173) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| Fujitsu       | D3403-A1 S26361-D3403-A1    | Desktop     | [ccf347729e](https://linux-hardware.org/?probe=ccf347729e) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| HP            | EliteBook 8540w             | Notebook    | [2f973c22ec](https://linux-hardware.org/?probe=2f973c22ec) | May 19, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [1ef52e97fa](https://linux-hardware.org/?probe=1ef52e97fa) | May 18, 2022 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [08dedbb3cb](https://linux-hardware.org/?probe=08dedbb3cb) | May 18, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a83bed6668](https://linux-hardware.org/?probe=a83bed6668) | May 16, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [a2ae5d95dd](https://linux-hardware.org/?probe=a2ae5d95dd) | May 15, 2022 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [58f371c0d7](https://linux-hardware.org/?probe=58f371c0d7) | May 13, 2022 |
| Lenovo        | ThinkPad X61 7673AQ5        | Notebook    | [42a17c86f4](https://linux-hardware.org/?probe=42a17c86f4) | May 13, 2022 |
| ASRockRack    | X399D8A-2T                  | Desktop     | [f1d2fbc435](https://linux-hardware.org/?probe=f1d2fbc435) | May 12, 2022 |
| MSI           | GT72VR 6RD                  | Notebook    | [c4cf6c9cd0](https://linux-hardware.org/?probe=c4cf6c9cd0) | May 12, 2022 |
| Gigabyte      | Z77P-D3                     | Desktop     | [40de59e6f7](https://linux-hardware.org/?probe=40de59e6f7) | May 10, 2022 |
| MSI           | Modern 15 A10RAS            | Notebook    | [3e844bb07a](https://linux-hardware.org/?probe=3e844bb07a) | May 08, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [f837aaeb12](https://linux-hardware.org/?probe=f837aaeb12) | May 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [69406bff46](https://linux-hardware.org/?probe=69406bff46) | May 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [56ca785331](https://linux-hardware.org/?probe=56ca785331) | May 08, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [2a10a13430](https://linux-hardware.org/?probe=2a10a13430) | May 06, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [d24187e845](https://linux-hardware.org/?probe=d24187e845) | May 05, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [50ccff3e1a](https://linux-hardware.org/?probe=50ccff3e1a) | May 04, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [9943699a6b](https://linux-hardware.org/?probe=9943699a6b) | May 04, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [47aaf6f556](https://linux-hardware.org/?probe=47aaf6f556) | May 04, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [050aee0a5f](https://linux-hardware.org/?probe=050aee0a5f) | May 03, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [0a6358dc13](https://linux-hardware.org/?probe=0a6358dc13) | May 03, 2022 |
| MSI           | MS-7053                     | Desktop     | [6de132b805](https://linux-hardware.org/?probe=6de132b805) | May 02, 2022 |
| Sony          | VGN-FZ31Z                   | Notebook    | [ebe91972ba](https://linux-hardware.org/?probe=ebe91972ba) | May 01, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [96dbfb494e](https://linux-hardware.org/?probe=96dbfb494e) | Apr 29, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [6c8e397ca3](https://linux-hardware.org/?probe=6c8e397ca3) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [910267bbd5](https://linux-hardware.org/?probe=910267bbd5) | Apr 28, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [22dd67107b](https://linux-hardware.org/?probe=22dd67107b) | Apr 28, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [91c7a6b5a0](https://linux-hardware.org/?probe=91c7a6b5a0) | Apr 27, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [9e591226b7](https://linux-hardware.org/?probe=9e591226b7) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | Notebook    | [5c309ec35d](https://linux-hardware.org/?probe=5c309ec35d) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Portugal/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 203       | 10.97%  |
| Ubuntu 18.04                 | 139       | 7.51%   |
| Ubuntu 22.04                 | 104       | 5.62%   |
| OpenMandriva 4.3             | 50        | 2.7%    |
| Pop!_OS 22.04                | 42        | 2.27%   |
| Zorin 16                     | 40        | 2.16%   |
| Debian 11                    | 40        | 2.16%   |
| Arch Rolling                 | 37        | 2%      |
| OpenMandriva 4.2             | 36        | 1.95%   |
| Zorin 15                     | 29        | 1.57%   |
| Pop!_OS 20.04                | 28        | 1.51%   |
| Fedora 38                    | 26        | 1.41%   |
| Linux Mint 19.3              | 23        | 1.24%   |
| KDE neon 20.04               | 23        | 1.24%   |
| Ubuntu 19.10                 | 22        | 1.19%   |
| Linux Mint 20.3              | 22        | 1.19%   |
| Linux Mint 20                | 22        | 1.19%   |
| Linux Mint 21.2              | 21        | 1.14%   |
| Debian 10                    | 21        | 1.14%   |
| ArcoLinux Rolling            | 21        | 1.14%   |
| Manjaro                      | 20        | 1.08%   |
| Linux Mint 20.1              | 20        | 1.08%   |
| Fedora 34                    | 20        | 1.08%   |
| Pop!_OS 21.04                | 19        | 1.03%   |
| Linux Mint 21.1              | 18        | 0.97%   |
| Debian 12                    | 18        | 0.97%   |
| Ubuntu 19.04                 | 17        | 0.92%   |
| openSUSE Tumbleweed-XXXXXXXX | 17        | 0.92%   |
| OpenMandriva 23.01           | 17        | 0.92%   |
| Fedora 39                    | 17        | 0.92%   |
| Fedora 36                    | 17        | 0.92%   |
| Xubuntu 20.04                | 16        | 0.86%   |
| Ubuntu 23.04                 | 16        | 0.86%   |
| Ubuntu 20.10                 | 16        | 0.86%   |
| OpenMandriva 4.50            | 16        | 0.86%   |
| Arch                         | 16        | 0.86%   |
| Ubuntu 21.10                 | 15        | 0.81%   |
| Ubuntu 21.04                 | 15        | 0.81%   |
| Pop!_OS 20.10                | 15        | 0.81%   |
| Fedora 37                    | 15        | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 551       | 31.47%  |
| Linux Mint    | 167       | 9.54%   |
| OpenMandriva  | 139       | 7.94%   |
| Fedora        | 125       | 7.14%   |
| Pop!_OS       | 115       | 6.57%   |
| Debian        | 89        | 5.08%   |
| Zorin         | 71        | 4.05%   |
| Manjaro       | 56        | 3.2%    |
| Arch          | 53        | 3.03%   |
| Endless       | 41        | 2.34%   |
| KDE neon      | 38        | 2.17%   |
| Xubuntu       | 36        | 2.06%   |
| Kubuntu       | 25        | 1.43%   |
| openSUSE      | 22        | 1.26%   |
| Elementary    | 22        | 1.26%   |
| ArcoLinux     | 22        | 1.26%   |
| ROSA          | 21        | 1.2%    |
| Ubuntu MATE   | 11        | 0.63%   |
| Ubuntu Unity  | 10        | 0.57%   |
| Slackware     | 8         | 0.46%   |
| Kali          | 8         | 0.46%   |
| EndeavourOS   | 8         | 0.46%   |
| Clear Linux   | 8         | 0.46%   |
| Ubuntu Budgie | 7         | 0.4%    |
| Nobara        | 7         | 0.4%    |
| LMDE          | 7         | 0.4%    |
| Lubuntu       | 6         | 0.34%   |
| Gentoo        | 6         | 0.34%   |
| SteamOS       | 5         | 0.29%   |
| NixOS         | 4         | 0.23%   |
| Devuan        | 4         | 0.23%   |
| Xero          | 3         | 0.17%   |
| UbuntuDDE     | 3         | 0.17%   |
| TUXEDO OS     | 3         | 0.17%   |
| Peppermint    | 3         | 0.17%   |
| Parrot        | 3         | 0.17%   |
| MX            | 3         | 0.17%   |
| CentOS        | 3         | 0.17%   |
| XCP-ng        | 2         | 0.11%   |
| Reborn OS     | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 40        | 1.95%   |
| 5.4.0-42-generic         | 38        | 1.86%   |
| 5.10.14-desktop-1omv4002 | 35        | 1.71%   |
| 5.15.0-56-generic        | 19        | 0.93%   |
| 5.4.0-58-generic         | 16        | 0.78%   |
| 5.3.0-46-generic         | 16        | 0.78%   |
| 6.2.6-76060206-generic   | 15        | 0.73%   |
| 6.1.1-desktop-1omv2290   | 15        | 0.73%   |
| 5.4.0-52-generic         | 15        | 0.73%   |
| 5.4.0-29-generic         | 14        | 0.68%   |
| 6.2.6-desktop-1omv2390   | 13        | 0.63%   |
| 5.4.0-26-generic         | 13        | 0.63%   |
| 5.15.0-58-generic        | 13        | 0.63%   |
| 5.15.0-52-generic        | 13        | 0.63%   |
| 5.15.0-48-generic        | 13        | 0.63%   |
| 5.15.0-46-generic        | 13        | 0.63%   |
| 5.11.0-38-generic        | 13        | 0.63%   |
| 5.3.0-28-generic         | 12        | 0.59%   |
| 5.14.14-desktop-1omv4050 | 12        | 0.59%   |
| 5.0.0-37-generic         | 12        | 0.59%   |
| 5.4.0-7634-generic       | 11        | 0.54%   |
| 5.19.0-76051900-generic  | 11        | 0.54%   |
| 5.10.0-8-amd64           | 11        | 0.54%   |
| 5.8.0-43-generic         | 10        | 0.49%   |
| 5.4.0-48-generic         | 10        | 0.49%   |
| 5.15.0-76-generic        | 10        | 0.49%   |
| 5.15.0-41-generic        | 10        | 0.49%   |
| 5.0.0-25-generic         | 10        | 0.49%   |
| 4.18.0-15-generic        | 10        | 0.49%   |
| 6.2.0-36-generic         | 9         | 0.44%   |
| 5.8.0-48-generic         | 9         | 0.44%   |
| 5.3.0-40-generic         | 9         | 0.44%   |
| 5.11.0-43-generic        | 9         | 0.44%   |
| 4.15.0-46-generic        | 9         | 0.44%   |
| 6.2.0-37-generic         | 8         | 0.39%   |
| 6.2.0-26-generic         | 8         | 0.39%   |
| 6.2.0-20-generic         | 8         | 0.39%   |
| 6.1.0-13-amd64           | 8         | 0.39%   |
| 5.8.0-44-generic         | 8         | 0.39%   |
| 5.4.0-37-generic         | 8         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 273       | 14.16%  |
| 5.15.0  | 161       | 8.35%   |
| 4.15.0  | 109       | 5.65%   |
| 5.8.0   | 93        | 4.82%   |
| 5.11.0  | 85        | 4.41%   |
| 5.3.0   | 83        | 4.3%    |
| 5.13.0  | 72        | 3.73%   |
| 6.2.0   | 64        | 3.32%   |
| 5.19.0  | 64        | 3.32%   |
| 5.0.0   | 58        | 3.01%   |
| 4.18.0  | 47        | 2.44%   |
| 5.10.0  | 44        | 2.28%   |
| 5.16.7  | 40        | 2.07%   |
| 5.10.14 | 37        | 1.92%   |
| 6.2.6   | 28        | 1.45%   |
| 6.1.0   | 24        | 1.24%   |
| 4.19.0  | 24        | 1.24%   |
| 6.1.1   | 18        | 0.93%   |
| 6.5.0   | 16        | 0.83%   |
| 5.14.14 | 12        | 0.62%   |
| 6.5.6   | 10        | 0.52%   |
| 6.5.5   | 10        | 0.52%   |
| 5.11.12 | 9         | 0.47%   |
| 6.4.11  | 6         | 0.31%   |
| 6.2.14  | 6         | 0.31%   |
| 6.0.9   | 6         | 0.31%   |
| 6.0.12  | 6         | 0.31%   |
| 5.14.0  | 6         | 0.31%   |
| 4.9.155 | 6         | 0.31%   |
| 4.4.0   | 6         | 0.31%   |
| 6.6.3   | 5         | 0.26%   |
| 6.5.12  | 5         | 0.26%   |
| 6.3.8   | 5         | 0.26%   |
| 6.2.15  | 5         | 0.26%   |
| 6.0.6   | 5         | 0.26%   |
| 6.0.0   | 5         | 0.26%   |
| 5.15.7  | 5         | 0.26%   |
| 5.13.19 | 5         | 0.26%   |
| 5.12.4  | 5         | 0.26%   |
| 6.4.8   | 4         | 0.21%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 289       | 15.2%   |
| 5.15    | 205       | 10.78%  |
| 6.2     | 118       | 6.21%   |
| 5.8     | 116       | 6.1%    |
| 4.15    | 110       | 5.79%   |
| 5.10    | 101       | 5.31%   |
| 5.11    | 99        | 5.21%   |
| 5.3     | 86        | 4.52%   |
| 5.13    | 86        | 4.52%   |
| 5.19    | 84        | 4.42%   |
| 6.1     | 68        | 3.58%   |
| 5.16    | 63        | 3.31%   |
| 5.0     | 59        | 3.1%    |
| 6.5     | 55        | 2.89%   |
| 4.18    | 51        | 2.68%   |
| 6.0     | 34        | 1.79%   |
| 5.14    | 33        | 1.74%   |
| 6.3     | 31        | 1.63%   |
| 4.19    | 28        | 1.47%   |
| 6.4     | 23        | 1.21%   |
| 5.12    | 22        | 1.16%   |
| 4.9     | 20        | 1.05%   |
| 6.6     | 17        | 0.89%   |
| 5.9     | 16        | 0.84%   |
| 5.7     | 16        | 0.84%   |
| 5.17    | 15        | 0.79%   |
| 5.6     | 14        | 0.74%   |
| 5.18    | 13        | 0.68%   |
| 5.5     | 10        | 0.53%   |
| 4.4     | 6         | 0.32%   |
| 5.2     | 4         | 0.21%   |
| 4.12    | 2         | 0.11%   |
| 4.10    | 2         | 0.11%   |
| 5.1     | 1         | 0.05%   |
| 4.1     | 1         | 0.05%   |
| 3.10    | 1         | 0.05%   |
| 2.6     | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1609      | 95.72%  |
| i686    | 63        | 3.75%   |
| aarch64 | 7         | 0.42%   |
| armv7l  | 2         | 0.12%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 783       | 44.24%  |
| KDE5             | 301       | 17.01%  |
| Unknown          | 225       | 12.71%  |
| X-Cinnamon       | 132       | 7.46%   |
| XFCE             | 131       | 7.4%    |
| MATE             | 35        | 1.98%   |
| KDE              | 33        | 1.86%   |
| Pantheon         | 21        | 1.19%   |
| Cinnamon         | 17        | 0.96%   |
| Budgie           | 16        | 0.9%    |
| i3               | 13        | 0.73%   |
| KDE4             | 12        | 0.68%   |
| Unity            | 11        | 0.62%   |
| LXQt             | 7         | 0.4%    |
| awesome          | 7         | 0.4%    |
| LXDE             | 6         | 0.34%   |
| Deepin           | 5         | 0.28%   |
| GNOME Flashback  | 4         | 0.23%   |
| Openbox          | 2         | 0.11%   |
| dwm              | 2         | 0.11%   |
| qtile            | 1         | 0.06%   |
| lightdm-xsession | 1         | 0.06%   |
| LeftWM           | 1         | 0.06%   |
| Hyprland         | 1         | 0.06%   |
| fluxbox          | 1         | 0.06%   |
| Cutefish         | 1         | 0.06%   |
| bspwm            | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1292      | 74.77%  |
| Wayland | 305       | 17.65%  |
| Unknown | 118       | 6.83%   |
| Tty     | 13        | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 926       | 53.01%  |
| SDDM    | 248       | 14.2%   |
| GDM3    | 203       | 11.62%  |
| GDM     | 157       | 8.99%   |
| LightDM | 151       | 8.64%   |
| TDM     | 43        | 2.46%   |
| KDM     | 12        | 0.69%   |
| XDM     | 4         | 0.23%   |
| SLiM    | 2         | 0.11%   |
| GREETD  | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| pt_PT      | 707       | 40.82%  |
| en_US      | 616       | 35.57%  |
| Unknown    | 205       | 11.84%  |
| en_GB      | 93        | 5.37%   |
| C          | 34        | 1.96%   |
| pt_BR      | 28        | 1.62%   |
| ru_RU      | 8         | 0.46%   |
| fr_FR      | 8         | 0.46%   |
| de_DE      | 8         | 0.46%   |
| es_ES      | 5         | 0.29%   |
| en_IE      | 5         | 0.29%   |
| sv_SE      | 3         | 0.17%   |
| POSIX      | 2         | 0.12%   |
| it_IT      | 2         | 0.12%   |
| en_CA      | 2         | 0.12%   |
| sk_SK      | 1         | 0.06%   |
| nl_NL      | 1         | 0.06%   |
| en_US.UTF8 | 1         | 0.06%   |
| en_PT      | 1         | 0.06%   |
| en_IN      | 1         | 0.06%   |
| Default    | 1         | 0.06%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 938       | 54.25%  |
| EFI  | 791       | 45.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1279      | 73.76%  |
| Btrfs    | 170       | 9.8%    |
| Overlay  | 116       | 6.69%   |
| Unknown  | 67        | 3.86%   |
| Tmpfs    | 59        | 3.4%    |
| Xfs      | 21        | 1.21%   |
| Zfs      | 10        | 0.58%   |
| Ext2     | 5         | 0.29%   |
| Ext3     | 4         | 0.23%   |
| Reiserfs | 1         | 0.06%   |
| F2fs     | 1         | 0.06%   |
| Aufs     | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 973       | 56.18%  |
| GPT     | 595       | 34.35%  |
| MBR     | 164       | 9.47%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1494      | 87.73%  |
| Yes       | 209       | 12.27%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1227      | 71.42%  |
| Yes       | 491       | 28.58%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 366       | 21.79%  |
| Hewlett-Packard         | 269       | 16.01%  |
| Lenovo                  | 231       | 13.75%  |
| Acer                    | 120       | 7.14%   |
| MSI                     | 100       | 5.95%   |
| Dell                    | 92        | 5.48%   |
| Toshiba                 | 82        | 4.88%   |
| Gigabyte Technology     | 68        | 4.05%   |
| Sony                    | 45        | 2.68%   |
| Apple                   | 41        | 2.44%   |
| ASRock                  | 29        | 1.73%   |
| HUAWEI                  | 23        | 1.37%   |
| Samsung Electronics     | 18        | 1.07%   |
| Intel                   | 18        | 1.07%   |
| Fujitsu                 | 16        | 0.95%   |
| Notebook                | 10        | 0.6%    |
| Chuwi                   | 9         | 0.54%   |
| Unknown                 | 9         | 0.54%   |
| Foxconn                 | 8         | 0.48%   |
| TUXEDO                  | 7         | 0.42%   |
| Raspberry Pi Foundation | 7         | 0.42%   |
| Packard Bell            | 7         | 0.42%   |
| eMachines               | 6         | 0.36%   |
| AMI                     | 5         | 0.3%    |
| Pegatron                | 4         | 0.24%   |
| Medion                  | 4         | 0.24%   |
| Clevo                   | 4         | 0.24%   |
| Valve                   | 3         | 0.18%   |
| Teclast                 | 3         | 0.18%   |
| Positivo                | 3         | 0.18%   |
| Phoenix/SiS             | 3         | 0.18%   |
| Microsoft               | 3         | 0.18%   |
| LG Electronics          | 3         | 0.18%   |
| Biostar                 | 3         | 0.18%   |
| SLIMBOOK                | 2         | 0.12%   |
| PC Specialist           | 2         | 0.12%   |
| OEM                     | 2         | 0.12%   |
| OBSIDIAN-PC             | 2         | 0.12%   |
| Minix                   | 2         | 0.12%   |
| Jumper                  | 2         | 0.12%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Sony VGN-FZ31Z                         | 21        | 1.25%   |
| ASUS All Series                        | 17        | 1.01%   |
| Lenovo IdeaPad 1 14ADA05 82GW          | 14        | 0.83%   |
| Unknown                                | 14        | 0.83%   |
| HP Pavilion dv6                        | 9         | 0.54%   |
| HP G62                                 | 9         | 0.54%   |
| Toshiba Satellite C660                 | 8         | 0.48%   |
| Lenovo Legion 5 15ACH6H 82JU           | 8         | 0.48%   |
| HP Pavilion g6                         | 8         | 0.48%   |
| HP Notebook                            | 7         | 0.42%   |
| Toshiba Satellite L650                 | 6         | 0.36%   |
| HP Pavilion Notebook                   | 6         | 0.36%   |
| MSI MS-7817                            | 5         | 0.3%    |
| Lenovo Y520-15IKBN 80WK                | 5         | 0.3%    |
| ASUS X555LJ                            | 5         | 0.3%    |
| ASUS X555LD                            | 5         | 0.3%    |
| ASUS X541UV                            | 5         | 0.3%    |
| ASUS VivoBook 15_ASUS Laptop X507LA    | 5         | 0.3%    |
| ASUS P5G41T-M LX                       | 5         | 0.3%    |
| ASUS H110M-K                           | 5         | 0.3%    |
| Acer Extensa 5620                      | 5         | 0.3%    |
| Acer Aspire ES1-520                    | 5         | 0.3%    |
| Toshiba Satellite L500                 | 4         | 0.24%   |
| Toshiba Satellite L40                  | 4         | 0.24%   |
| Toshiba Satellite A200                 | 4         | 0.24%   |
| Lenovo Legion 5 15ARH05H 82B1          | 4         | 0.24%   |
| Lenovo IdeaPad 320-15AST 80XV          | 4         | 0.24%   |
| Lenovo G50-45 80E3                     | 4         | 0.24%   |
| HUAWEI NBLK-WAX9X                      | 4         | 0.24%   |
| HP Pavilion Gaming Laptop 15-ec2xxx    | 4         | 0.24%   |
| HP Pavilion 15                         | 4         | 0.24%   |
| HP OMEN by Laptop 15-dc0xxx            | 4         | 0.24%   |
| HP OMEN by Laptop                      | 4         | 0.24%   |
| HP Compaq Presario CQ60                | 4         | 0.24%   |
| HP Compaq Elite 8300 SFF               | 4         | 0.24%   |
| HP 15                                  | 4         | 0.24%   |
| ASUS X541UJ                            | 4         | 0.24%   |
| ASUS VivoBook_ASUSLaptop X512DA_F512DA | 4         | 0.24%   |
| ASUS M5A78L-M/USB3                     | 4         | 0.24%   |
| Apple MacBookPro8,1                    | 4         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 102       | 6.07%   |
| Acer Aspire           | 96        | 5.71%   |
| Toshiba Satellite     | 71        | 4.23%   |
| HP Pavilion           | 66        | 3.93%   |
| Lenovo IdeaPad        | 59        | 3.51%   |
| ASUS VivoBook         | 41        | 2.44%   |
| HP Compaq             | 35        | 2.08%   |
| Dell Latitude         | 33        | 1.96%   |
| HP EliteBook          | 32        | 1.9%    |
| ASUS PRIME            | 29        | 1.73%   |
| HP Laptop             | 23        | 1.37%   |
| Lenovo Legion         | 22        | 1.31%   |
| Sony VGN-FZ31Z        | 21        | 1.25%   |
| ASUS ROG              | 21        | 1.25%   |
| Dell XPS              | 19        | 1.13%   |
| ASUS All              | 17        | 1.01%   |
| HP ProBook            | 16        | 0.95%   |
| Dell OptiPlex         | 14        | 0.83%   |
| ASUS TUF              | 14        | 0.83%   |
| Unknown               | 14        | 0.83%   |
| HP OMEN               | 13        | 0.77%   |
| Dell Inspiron         | 12        | 0.71%   |
| HP ENVY               | 11        | 0.65%   |
| ASUS ZenBook          | 10        | 0.6%    |
| ASUS P5G41T-M         | 10        | 0.6%    |
| HP G62                | 9         | 0.54%   |
| Dell Precision        | 9         | 0.54%   |
| Acer Extensa          | 9         | 0.54%   |
| RPi Raspberry         | 7         | 0.42%   |
| Lenovo Yoga           | 7         | 0.42%   |
| HP Notebook           | 7         | 0.42%   |
| ASUS P8H61-M          | 7         | 0.42%   |
| Acer Nitro            | 7         | 0.42%   |
| Packard Bell EasyNote | 6         | 0.36%   |
| MSI Modern            | 6         | 0.36%   |
| Lenovo ThinkCentre    | 6         | 0.36%   |
| HP ProLiant           | 6         | 0.36%   |
| HP ProDesk            | 6         | 0.36%   |
| Gigabyte B550         | 6         | 0.36%   |
| Fujitsu LIFEBOOK      | 6         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 164       | 9.76%   |
| 2018    | 147       | 8.75%   |
| 2019    | 126       | 7.5%    |
| 2010    | 125       | 7.44%   |
| 2012    | 101       | 6.01%   |
| 2014    | 99        | 5.89%   |
| 2013    | 98        | 5.83%   |
| 2021    | 97        | 5.77%   |
| 2015    | 93        | 5.54%   |
| 2017    | 87        | 5.18%   |
| 2016    | 84        | 5%      |
| 2007    | 84        | 5%      |
| 2009    | 83        | 4.94%   |
| 2008    | 83        | 4.94%   |
| 2011    | 79        | 4.7%    |
| 2022    | 46        | 2.74%   |
| 2006    | 30        | 1.79%   |
| 2023    | 26        | 1.55%   |
| 2005    | 14        | 0.83%   |
| Unknown | 10        | 0.6%    |
| 2004    | 3         | 0.18%   |
| 2003    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1112      | 66.19%  |
| Desktop        | 488       | 29.05%  |
| Mini pc        | 20        | 1.19%   |
| Convertible    | 19        | 1.13%   |
| Tablet         | 13        | 0.77%   |
| All in one     | 11        | 0.65%   |
| System on chip | 8         | 0.48%   |
| Server         | 8         | 0.48%   |
| Phone          | 1         | 0.06%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1566      | 91.69%  |
| Enabled  | 142       | 8.31%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1673      | 99.58%  |
| Yes  | 7         | 0.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 421       | 24.56%  |
| 4.01-8.0        | 371       | 21.65%  |
| 8.01-16.0       | 291       | 16.98%  |
| 16.01-24.0      | 283       | 16.51%  |
| 32.01-64.0      | 146       | 8.52%   |
| 1.01-2.0        | 98        | 5.72%   |
| 2.01-3.0        | 35        | 2.04%   |
| 64.01-256.0     | 33        | 1.93%   |
| 24.01-32.0      | 21        | 1.23%   |
| 0.51-1.0        | 14        | 0.82%   |
| More than 256.0 | 1         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 680       | 36.38%  |
| 2.01-3.0    | 428       | 22.9%   |
| 4.01-8.0    | 293       | 15.68%  |
| 3.01-4.0    | 216       | 11.56%  |
| 0.51-1.0    | 129       | 6.9%    |
| 8.01-16.0   | 83        | 4.44%   |
| 16.01-24.0  | 16        | 0.86%   |
| 0.01-0.5    | 16        | 0.86%   |
| 24.01-32.0  | 5         | 0.27%   |
| 32.01-64.0  | 1         | 0.05%   |
| 64.01-256.0 | 1         | 0.05%   |
| Unknown     | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1091      | 63.1%   |
| 2      | 422       | 24.41%  |
| 3      | 112       | 6.48%   |
| 4      | 51        | 2.95%   |
| 0      | 19        | 1.1%    |
| 5      | 16        | 0.93%   |
| 6      | 10        | 0.58%   |
| 11     | 2         | 0.12%   |
| 10     | 2         | 0.12%   |
| 7      | 2         | 0.12%   |
| 87     | 1         | 0.06%   |
| 8      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1079      | 64%     |
| Yes       | 607       | 36%     |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1441      | 85.37%  |
| No        | 247       | 14.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1328      | 78.53%  |
| No        | 363       | 21.47%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 997       | 58.44%  |
| No        | 709       | 41.56%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Portugal | 1680      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lisbon                  | 414       | 22.96%  |
| Porto                   | 161       | 8.93%   |
| Amadora                 | 40        | 2.22%   |
| Vila Nova de Gaia       | 39        | 2.16%   |
| Coimbra                 | 38        | 2.11%   |
| Funchal                 | 37        | 2.05%   |
| Braga                   | 34        | 1.89%   |
| Aveiro                  | 33        | 1.83%   |
| Setúbal                | 30        | 1.66%   |
| Leiria                  | 25        | 1.39%   |
| Faro                    | 22        | 1.22%   |
| Loures                  | 21        | 1.16%   |
| Cascais                 | 21        | 1.16%   |
| Guimaraes               | 20        | 1.11%   |
| Almada                  | 18        | 1%      |
| Portimao                | 16        | 0.89%   |
| Sintra                  | 13        | 0.72%   |
| Matosinhos Municipality | 13        | 0.72%   |
| Bragança               | 13        | 0.72%   |
| Viana do Castelo        | 12        | 0.67%   |
| Odivelas                | 12        | 0.67%   |
| Mem Martins             | 12        | 0.67%   |
| Evora                   | 12        | 0.67%   |
| Barreiro                | 12        | 0.67%   |
| Torres Vedras           | 11        | 0.61%   |
| Santarém               | 11        | 0.61%   |
| Póvoa de Varzim        | 11        | 0.61%   |
| Maia                    | 11        | 0.61%   |
| Barcelos                | 11        | 0.61%   |
| Viseu                   | 10        | 0.55%   |
| Vila do Conde           | 10        | 0.55%   |
| Queluz                  | 10        | 0.55%   |
| Povoa de Santa Iria     | 10        | 0.55%   |
| Amora                   | 10        | 0.55%   |
| Alverca do Ribatejo     | 10        | 0.55%   |
| Sao Joao da Madeira     | 9         | 0.5%    |
| Montijo                 | 9         | 0.5%    |
| Trofa                   | 8         | 0.44%   |
| Ponta Delgada           | 8         | 0.44%   |
| Oeiras                  | 8         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 347       | 487    | 14.65%  |
| WDC                         | 308       | 487    | 13.01%  |
| Seagate                     | 281       | 440    | 11.87%  |
| Kingston                    | 202       | 272    | 8.53%   |
| Toshiba                     | 200       | 298    | 8.45%   |
| SanDisk                     | 116       | 141    | 4.9%    |
| Unknown                     | 110       | 155    | 4.65%   |
| Crucial                     | 97        | 128    | 4.1%    |
| Hitachi                     | 79        | 91     | 3.34%   |
| Intel                       | 51        | 80     | 2.15%   |
| HGST                        | 49        | 65     | 2.07%   |
| SK hynix                    | 47        | 55     | 1.98%   |
| Micron Technology           | 41        | 48     | 1.73%   |
| KIOXIA                      | 26        | 44     | 1.1%    |
| Fujitsu                     | 22        | 23     | 0.93%   |
| Maxtor                      | 21        | 35     | 0.89%   |
| GOODRAM                     | 21        | 25     | 0.89%   |
| Phison Electronics          | 19        | 22     | 0.8%    |
| China                       | 17        | 21     | 0.72%   |
| Apple                       | 17        | 17     | 0.72%   |
| PNY                         | 15        | 20     | 0.63%   |
| BlueRay                     | 15        | 20     | 0.63%   |
| S3+                         | 14        | 25     | 0.59%   |
| KIOXIA-EXCERIA              | 14        | 22     | 0.59%   |
| JMicron Technology          | 13        | 14     | 0.55%   |
| Emtec                       | 13        | 15     | 0.55%   |
| Phison                      | 12        | 18     | 0.51%   |
| Micron/Crucial Technology   | 10        | 19     | 0.42%   |
| A-DATA Technology           | 10        | 10     | 0.42%   |
| Unknown                     | 9         | 11     | 0.38%   |
| Transcend                   | 8         | 9      | 0.34%   |
| OCZ                         | 8         | 8      | 0.34%   |
| LITEON                      | 8         | 9      | 0.34%   |
| Kingston Technology Company | 8         | 9      | 0.34%   |
| Hewlett-Packard             | 7         | 8      | 0.3%    |
| Silicon Motion              | 6         | 8      | 0.25%   |
| Gigabyte Technology         | 6         | 7      | 0.25%   |
| Team                        | 5         | 6      | 0.21%   |
| Netac                       | 5         | 6      | 0.21%   |
| KingDian                    | 5         | 8      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 37        | 1.46%   |
| Unknown MMC Card  32GB                              | 29        | 1.14%   |
| Kingston SA400S37120G 120GB SSD                     | 28        | 1.1%    |
| Toshiba MQ01ABD100 1TB                              | 21        | 0.83%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 21        | 0.83%   |
| Kingston SV300S37A120G 120GB SSD                    | 21        | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 20        | 0.79%   |
| HGST HTS721010A9E630 1TB                            | 20        | 0.79%   |
| Unknown MMC Card  64GB                              | 18        | 0.71%   |
| Seagate ST500LT012-1DG142 500GB                     | 18        | 0.71%   |
| Seagate ST1000DM010-2EP102 1TB                      | 18        | 0.71%   |
| Toshiba MQ01ABF050 500GB                            | 16        | 0.63%   |
| Kingston SV300S37A240G 240GB SSD                    | 16        | 0.63%   |
| Crucial CT240M500SSD1 240GB                         | 16        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB                      | 15        | 0.59%   |
| Samsung SSD 850 EVO 250GB                           | 15        | 0.59%   |
| Unknown MMC64G  64GB                                | 14        | 0.55%   |
| Samsung SSD 860 EVO 500GB                           | 14        | 0.55%   |
| Kingston SA400S37480G 480GB SSD                     | 14        | 0.55%   |
| Crucial CT500MX500SSD1 500GB                        | 14        | 0.55%   |
| Seagate ST9500325AS 500GB                           | 13        | 0.51%   |
| SanDisk NVMe SSD Drive 512GB                        | 12        | 0.47%   |
| Crucial CT240BX500SSD1 240GB                        | 12        | 0.47%   |
| Seagate ST3500418AS 500GB                           | 11        | 0.43%   |
| Samsung SSD 860 QVO 1TB                             | 11        | 0.43%   |
| Samsung SSD 850 EVO 500GB                           | 11        | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 10        | 0.39%   |
| Samsung NVMe SSD Drive 512GB                        | 10        | 0.39%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 10        | 0.39%   |
| JMicron Generic 2TB                                 | 10        | 0.39%   |
| Unknown MMC Card  128GB                             | 9         | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB                      | 9         | 0.35%   |
| Seagate Expansion 2TB                               | 9         | 0.35%   |
| Samsung SSD 840 EVO 250GB                           | 9         | 0.35%   |
| Samsung NVMe SSD Drive 500GB                        | 9         | 0.35%   |
| Emtec X150 240GB                                    | 9         | 0.35%   |
| Unknown                                             | 9         | 0.35%   |
| Toshiba HDWD110 1TB                                 | 8         | 0.32%   |
| Seagate ST9320325AS 320GB                           | 8         | 0.32%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 8         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 272       | 427    | 29.86%  |
| WDC                 | 241       | 363    | 26.45%  |
| Toshiba             | 146       | 229    | 16.03%  |
| Hitachi             | 79        | 91     | 8.67%   |
| Samsung Electronics | 59        | 82     | 6.48%   |
| HGST                | 49        | 65     | 5.38%   |
| Fujitsu             | 21        | 22     | 2.31%   |
| Maxtor              | 17        | 24     | 1.87%   |
| ExcelStor           | 5         | 5      | 0.55%   |
| USB                 | 4         | 4      | 0.44%   |
| Apple               | 4         | 4      | 0.44%   |
| Unknown             | 2         | 3      | 0.22%   |
| TO Exter            | 2         | 2      | 0.22%   |
| MSFT                | 2         | 12     | 0.22%   |
| Dell                | 2         | 4      | 0.22%   |
| USB3.0              | 1         | 1      | 0.11%   |
| Quantum             | 1         | 1      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |
| HPE                 | 1         | 4      | 0.11%   |
| Hewlett-Packard     | 1         | 2      | 0.11%   |
| ASMedia             | 1         | 2      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 171       | 221    | 21.3%   |
| Samsung Electronics | 151       | 203    | 18.8%   |
| Crucial             | 89        | 118    | 11.08%  |
| SanDisk             | 49        | 61     | 6.1%    |
| WDC                 | 39        | 59     | 4.86%   |
| Toshiba             | 32        | 43     | 3.99%   |
| GOODRAM             | 19        | 23     | 2.37%   |
| China               | 17        | 21     | 2.12%   |
| Intel               | 16        | 22     | 1.99%   |
| S3+                 | 14        | 25     | 1.74%   |
| Emtec               | 13        | 15     | 1.62%   |
| BlueRay             | 13        | 15     | 1.62%   |
| Apple               | 12        | 12     | 1.49%   |
| PNY                 | 11        | 15     | 1.37%   |
| Micron Technology   | 11        | 15     | 1.37%   |
| JMicron Technology  | 10        | 11     | 1.25%   |
| A-DATA Technology   | 10        | 10     | 1.25%   |
| SK hynix            | 9         | 9      | 1.12%   |
| Transcend           | 8         | 9      | 1%      |
| OCZ                 | 8         | 8      | 1%      |
| KIOXIA-EXCERIA      | 8         | 15     | 1%      |
| Hewlett-Packard     | 6         | 6      | 0.75%   |
| Team                | 5         | 6      | 0.62%   |
| Seagate             | 5         | 7      | 0.62%   |
| LITEON              | 5         | 6      | 0.62%   |
| Unknown             | 4         | 4      | 0.5%    |
| Netac               | 4         | 5      | 0.5%    |
| Maxtor              | 4         | 11     | 0.5%    |
| KingDian            | 4         | 7      | 0.5%    |
| Gigabyte Technology | 4         | 4      | 0.5%    |
| Unknown             | 4         | 5      | 0.5%    |
| Vaseky              | 3         | 3      | 0.37%   |
| 2-Power             | 3         | 4      | 0.37%   |
| TCSUNBOW            | 2         | 2      | 0.25%   |
| Plextor             | 2         | 2      | 0.25%   |
| LITEONIT            | 2         | 2      | 0.25%   |
| KingSpec            | 2         | 2      | 0.25%   |
| Intenso             | 2         | 2      | 0.25%   |
| Dogfish             | 2         | 2      | 0.25%   |
| Zheino              | 1         | 2      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 786       | 1348   | 36.95%  |
| SSD     | 703       | 1045   | 33.05%  |
| NVMe    | 507       | 749    | 23.84%  |
| MMC     | 105       | 149    | 4.94%   |
| Unknown | 26        | 32     | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1228      | 2335   | 64.23%  |
| NVMe | 507       | 745    | 26.52%  |
| MMC  | 105       | 149    | 5.49%   |
| SAS  | 72        | 94     | 3.77%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 992       | 1567   | 66.94%  |
| 0.51-1.0   | 356       | 530    | 24.02%  |
| 1.01-2.0   | 83        | 125    | 5.6%    |
| 4.01-10.0  | 19        | 32     | 1.28%   |
| 2.01-3.0   | 16        | 22     | 1.08%   |
| 3.01-4.0   | 12        | 27     | 0.81%   |
| 10.01-20.0 | 3         | 89     | 0.2%    |
| 0          | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 504       | 28.2%   |
| 251-500        | 418       | 23.39%  |
| 501-1000       | 228       | 12.76%  |
| 51-100         | 145       | 8.11%   |
| 1-20           | 127       | 7.11%   |
| 1001-2000      | 125       | 6.99%   |
| 21-50          | 77        | 4.31%   |
| More than 3000 | 74        | 4.14%   |
| Unknown        | 46        | 2.57%   |
| 2001-3000      | 43        | 2.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 752       | 40.65%  |
| 21-50          | 338       | 18.27%  |
| 101-250        | 215       | 11.62%  |
| 51-100         | 195       | 10.54%  |
| 251-500        | 126       | 6.81%   |
| 501-1000       | 79        | 4.27%   |
| 1001-2000      | 59        | 3.19%   |
| Unknown        | 46        | 2.49%   |
| More than 3000 | 24        | 1.3%    |
| 2001-3000      | 16        | 0.86%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Crucial CT240M500SSD1 240GB        | 14        | 15     | 8.48%   |
| Kingston SV300S37A120G 120GB SSD   | 6         | 6      | 3.64%   |
| Seagate ST9500325AS 500GB          | 3         | 3      | 1.82%   |
| Seagate ST9320325AS 320GB          | 3         | 4      | 1.82%   |
| Seagate ST3500418AS 500GB          | 3         | 3      | 1.82%   |
| Kingston SV300S37A240G 240GB SSD   | 3         | 3      | 1.82%   |
| WDC WD800JD-60LSA0 80GB            | 2         | 2      | 1.21%   |
| WDC WD3200AAJS-00L7A0 320GB        | 2         | 2      | 1.21%   |
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 1.21%   |
| Toshiba MK2552GSX 250GB            | 2         | 2      | 1.21%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 1.21%   |
| Seagate ST500DM002-1BD142 500GB    | 2         | 2      | 1.21%   |
| Seagate ST3320413CS 320GB          | 2         | 2      | 1.21%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 1.21%   |
| Samsung Electronics HD252HJ 250GB  | 2         | 2      | 1.21%   |
| Kingston SUV400S37240G 240GB SSD   | 2         | 2      | 1.21%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.21%   |
| Hitachi HTS543216L9A300 160GB      | 2         | 2      | 1.21%   |
| HGST HTS721010A9E630 1TB           | 2         | 2      | 1.21%   |
| China G521N256GB SSD               | 2         | 3      | 1.21%   |
| WDC WD7500BPVX-60JC3T0 752GB       | 1         | 2      | 0.61%   |
| WDC WD6400AADS-00M2B0 640GB        | 1         | 1      | 0.61%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 1         | 1      | 0.61%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 0.61%   |
| WDC WD5000BPVT-22HXZT1 500GB       | 1         | 1      | 0.61%   |
| WDC WD5000AZRX-00A8LB0 500GB       | 1         | 1      | 0.61%   |
| WDC WD5000AZRX-00A3KB0 500GB       | 1         | 1      | 0.61%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 1         | 1      | 0.61%   |
| WDC WD5000AAKS-00V1A0 500GB        | 1         | 1      | 0.61%   |
| WDC WD5000AAKS-00A7B0 500GB        | 1         | 4      | 0.61%   |
| WDC WD5000AADS-00S9B0 500GB        | 1         | 1      | 0.61%   |
| WDC WD40EFRX-68WT0N0 4TB           | 1         | 2      | 0.61%   |
| WDC WD3200BEVT-22A23T0 320GB       | 1         | 1      | 0.61%   |
| WDC WD3200AAJS-07M0A0 320GB        | 1         | 1      | 0.61%   |
| WDC WD3200AAJS-00B4A0 320GB        | 1         | 1      | 0.61%   |
| WDC WD30EZRS-11J99B1 3TB           | 1         | 1      | 0.61%   |
| WDC WD2500JS-40TGB0 250GB          | 1         | 1      | 0.61%   |
| WDC WD20EARS-00MVWB0 2TB           | 1         | 1      | 0.61%   |
| WDC WD1600BEVT-75A23T0 160GB       | 1         | 1      | 0.61%   |
| WDC WD15EARS-60MVWB0 1TB           | 1         | 1      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 36        | 44     | 22.36%  |
| Seagate             | 29        | 33     | 18.01%  |
| Hitachi             | 16        | 17     | 9.94%   |
| Crucial             | 16        | 18     | 9.94%   |
| Toshiba             | 15        | 16     | 9.32%   |
| Kingston            | 11        | 12     | 6.83%   |
| Samsung Electronics | 9         | 11     | 5.59%   |
| SK hynix            | 4         | 4      | 2.48%   |
| Maxtor              | 4         | 7      | 2.48%   |
| HGST                | 4         | 4      | 2.48%   |
| China               | 3         | 4      | 1.86%   |
| Intel               | 2         | 2      | 1.24%   |
| VNYEZ               | 1         | 1      | 0.62%   |
| USB                 | 1         | 1      | 0.62%   |
| Unknown             | 1         | 1      | 0.62%   |
| SanDisk             | 1         | 1      | 0.62%   |
| Patriot             | 1         | 1      | 0.62%   |
| LITEON              | 1         | 1      | 0.62%   |
| KingDian            | 1         | 2      | 0.62%   |
| HP Phison           | 1         | 1      | 0.62%   |
| Fujitsu             | 1         | 1      | 0.62%   |
| ExcelStor           | 1         | 1      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |
| A-DATA Technology   | 1         | 1      | 0.62%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 36        | 44     | 31.86%  |
| Seagate             | 29        | 33     | 25.66%  |
| Hitachi             | 16        | 17     | 14.16%  |
| Toshiba             | 14        | 15     | 12.39%  |
| Samsung Electronics | 6         | 7      | 5.31%   |
| Maxtor              | 4         | 7      | 3.54%   |
| HGST                | 4         | 4      | 3.54%   |
| USB                 | 1         | 1      | 0.88%   |
| Fujitsu             | 1         | 1      | 0.88%   |
| ExcelStor           | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 105       | 131    | 68.63%  |
| SSD  | 45        | 51     | 29.41%  |
| NVMe | 3         | 3      | 1.96%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Toshiba NVMe SSD Drive 256GB | 1         | 1      | 33.33%  |
| Seagate ST3750640NS 752GB    | 1         | 1      | 33.33%  |
| HGST HTS541010B7E610 1TB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1112      | 2215   | 61.81%  |
| Works    | 535       | 920    | 29.74%  |
| Malfunc  | 149       | 185    | 8.28%   |
| Failed   | 3         | 3      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1089      | 53.57%  |
| AMD                              | 293       | 14.41%  |
| Samsung Electronics              | 166       | 8.17%   |
| Sandisk                          | 96        | 4.72%   |
| Kingston Technology Company      | 41        | 2.02%   |
| Phison Electronics               | 37        | 1.82%   |
| SK hynix                         | 36        | 1.77%   |
| Micron Technology                | 31        | 1.52%   |
| KIOXIA                           | 30        | 1.48%   |
| Nvidia                           | 27        | 1.33%   |
| Toshiba America Info Systems     | 26        | 1.28%   |
| JMicron Technology               | 26        | 1.28%   |
| ASMedia Technology               | 22        | 1.08%   |
| Micron/Crucial Technology        | 18        | 0.89%   |
| Silicon Integrated Systems [SiS] | 16        | 0.79%   |
| VIA Technologies                 | 13        | 0.64%   |
| Marvell Technology Group         | 13        | 0.64%   |
| Union Memory (Shenzhen)          | 8         | 0.39%   |
| Silicon Motion                   | 6         | 0.3%    |
| LSI Logic / Symbios Logic        | 6         | 0.3%    |
| Lite-On Technology               | 6         | 0.3%    |
| Shenzhen Longsys Electronics     | 4         | 0.2%    |
| Lenovo                           | 3         | 0.15%   |
| Hewlett-Packard                  | 3         | 0.15%   |
| ADATA Technology                 | 3         | 0.15%   |
| Solid State Storage Technology   | 2         | 0.1%    |
| Realtek Semiconductor            | 2         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 2         | 0.1%    |
| Adaptec                          | 2         | 0.1%    |
| ULi Electronics                  | 1         | 0.05%   |
| Silicon Image                    | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| Netac Technology                 | 1         | 0.05%   |
| Enmotus                          | 1         | 0.05%   |
| Apple                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 204       | 8.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 84        | 3.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 78        | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 71        | 2.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 66        | 2.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 57        | 2.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 55        | 2.3%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 52        | 2.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 50        | 2.09%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 50        | 2.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 49        | 2.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 48        | 2.01%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 45        | 1.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 43        | 1.8%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 35        | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 33        | 1.38%   |
| AMD 500 Series Chipset SATA Controller                                                  | 31        | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 29        | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 29        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 29        | 1.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28        | 1.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 25        | 1.05%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 23        | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 23        | 0.96%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 23        | 0.96%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 22        | 0.92%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 22        | 0.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 20        | 0.84%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 20        | 0.84%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 20        | 0.84%   |
| Intel SSD 660P Series                                                                   | 19        | 0.8%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 19        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 19        | 0.8%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 19        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 18        | 0.75%   |
| Phison E12 NVMe Controller                                                              | 17        | 0.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 17        | 0.71%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 16        | 0.67%   |
| Intel SATA Controller [RAID mode]                                                       | 16        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 16        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1148      | 54.9%   |
| NVMe | 509       | 24.34%  |
| IDE  | 308       | 14.73%  |
| RAID | 121       | 5.79%   |
| SCSI | 3         | 0.14%   |
| SAS  | 2         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1289      | 76.73%  |
| AMD    | 382       | 22.74%  |
| ARM    | 9         | 0.54%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU T8300 @ 2.40GHz          | 25        | 1.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 1.49%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 21        | 1.25%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 20        | 1.19%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 1.13%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 18        | 1.07%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 16        | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 15        | 0.89%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 0.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 14        | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.83%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 14        | 0.83%   |
| AMD 3020e with Radeon Graphics                | 14        | 0.83%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 13        | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 12        | 0.71%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 12        | 0.71%   |
| AMD Ryzen 5 3600 6-Core Processor             | 12        | 0.71%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 11        | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 11        | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 0.65%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.65%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 10        | 0.59%   |
| Intel Core i5 CPU M 480 @ 2.67GHz             | 10        | 0.59%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 10        | 0.59%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 10        | 0.59%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 10        | 0.59%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 10        | 0.59%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.54%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 0.54%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 0.54%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 0.54%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 9         | 0.54%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 9         | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.48%   |
| Intel Core i7 CPU Q 720 @ 1.60GHz             | 8         | 0.48%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 8         | 0.48%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.48%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 8         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 326       | 19.38%  |
| Intel Core i5           | 293       | 17.42%  |
| Other                   | 130       | 7.73%   |
| Intel Core i3           | 113       | 6.72%   |
| Intel Core 2 Duo        | 107       | 6.36%   |
| AMD Ryzen 5             | 101       | 6%      |
| AMD Ryzen 7             | 96        | 5.71%   |
| Intel Celeron           | 72        | 4.28%   |
| Intel Atom              | 54        | 3.21%   |
| Intel Pentium Dual-Core | 42        | 2.5%    |
| Intel Pentium           | 30        | 1.78%   |
| Intel Xeon              | 28        | 1.66%   |
| Intel Pentium Dual      | 28        | 1.66%   |
| AMD FX                  | 28        | 1.66%   |
| Intel Core 2 Quad       | 25        | 1.49%   |
| Intel Core 2            | 21        | 1.25%   |
| AMD A4                  | 16        | 0.95%   |
| Intel Genuine           | 15        | 0.89%   |
| Intel Pentium 4         | 14        | 0.83%   |
| AMD A6                  | 14        | 0.83%   |
| AMD Ryzen 9             | 13        | 0.77%   |
| AMD Ryzen 3             | 13        | 0.77%   |
| AMD A8                  | 13        | 0.77%   |
| AMD E2                  | 8         | 0.48%   |
| AMD A10                 | 8         | 0.48%   |
| Intel Pentium D         | 6         | 0.36%   |
| Intel Pentium M         | 5         | 0.3%    |
| AMD E                   | 5         | 0.3%    |
| AMD Athlon              | 5         | 0.3%    |
| Intel Core i9           | 4         | 0.24%   |
| AMD Ryzen 7 PRO         | 4         | 0.24%   |
| AMD Ryzen Threadripper  | 3         | 0.18%   |
| AMD Athlon II X3        | 3         | 0.18%   |
| AMD Athlon II X2        | 3         | 0.18%   |
| AMD Athlon 64           | 3         | 0.18%   |
| Intel Pentium Gold      | 2         | 0.12%   |
| Intel Core m3           | 2         | 0.12%   |
| Intel Celeron M         | 2         | 0.12%   |
| ARM BCM                 | 2         | 0.12%   |
| AMD Phenom II X4        | 2         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 710       | 42.19%  |
| 4       | 578       | 34.34%  |
| 6       | 151       | 8.97%   |
| 8       | 120       | 7.13%   |
| 1       | 55        | 3.27%   |
| 3       | 15        | 0.89%   |
| 12      | 14        | 0.83%   |
| 10      | 14        | 0.83%   |
| 16      | 9         | 0.53%   |
| 14      | 9         | 0.53%   |
| Unknown | 5         | 0.3%    |
| 24      | 2         | 0.12%   |
| 36      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1669      | 99.35%  |
| 2       | 7         | 0.42%   |
| Unknown | 4         | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1054      | 62.63%  |
| 1       | 624       | 37.08%  |
| Unknown | 5         | 0.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1612      | 95.33%  |
| Unknown        | 49        | 2.9%    |
| 32-bit         | 23        | 1.36%   |
| 64-bit         | 7         | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 539       | 30.64%  |
| 0x1067a    | 78        | 4.43%   |
| 0x306a9    | 77        | 4.38%   |
| 0x206a7    | 71        | 4.04%   |
| 0x906ea    | 44        | 2.5%    |
| 0x10676    | 41        | 2.33%   |
| 0x806ec    | 38        | 2.16%   |
| 0x306c3    | 38        | 2.16%   |
| 0x806ea    | 36        | 2.05%   |
| 0x6fd      | 34        | 1.93%   |
| 0x806c1    | 29        | 1.65%   |
| 0x506e3    | 29        | 1.65%   |
| 0x40651    | 29        | 1.65%   |
| 0x20655    | 23        | 1.31%   |
| 0x406e3    | 21        | 1.19%   |
| 0x306d4    | 21        | 1.19%   |
| 0x806e9    | 19        | 1.08%   |
| 0x30678    | 19        | 1.08%   |
| 0x20652    | 19        | 1.08%   |
| 0x906e9    | 18        | 1.02%   |
| 0x806eb    | 17        | 0.97%   |
| 0x06000852 | 17        | 0.97%   |
| 0x406c4    | 16        | 0.91%   |
| 0x08701021 | 15        | 0.85%   |
| 0x6fb      | 14        | 0.8%    |
| 0x106e5    | 14        | 0.8%    |
| 0x0a50000c | 14        | 0.8%    |
| 0x08200103 | 14        | 0.8%    |
| 0x08108109 | 14        | 0.8%    |
| 0xa0652    | 13        | 0.74%   |
| 0x6f6      | 13        | 0.74%   |
| 0x0800820d | 13        | 0.74%   |
| 0x406c3    | 11        | 0.63%   |
| 0x08600106 | 11        | 0.63%   |
| 0x0a50000d | 10        | 0.57%   |
| 0x08108102 | 10        | 0.57%   |
| 0x07030105 | 10        | 0.57%   |
| 0x106ca    | 9         | 0.51%   |
| 0x08600104 | 9         | 0.51%   |
| 0x706e5    | 8         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 236       | 14.01%  |
| Penryn           | 155       | 9.2%    |
| Haswell          | 115       | 6.83%   |
| IvyBridge        | 111       | 6.59%   |
| Core             | 95        | 5.64%   |
| SandyBridge      | 93        | 5.52%   |
| Skylake          | 79        | 4.69%   |
| Silvermont       | 71        | 4.22%   |
| Zen 2            | 64        | 3.8%    |
| Westmere         | 62        | 3.68%   |
| Unknown          | 59        | 3.5%    |
| Zen 3            | 58        | 3.44%   |
| Zen+             | 53        | 3.15%   |
| TigerLake        | 49        | 2.91%   |
| Zen              | 43        | 2.55%   |
| Broadwell        | 35        | 2.08%   |
| CometLake        | 31        | 1.84%   |
| Piledriver       | 29        | 1.72%   |
| Alderlake Hybrid | 25        | 1.48%   |
| NetBurst         | 22        | 1.31%   |
| Puma             | 21        | 1.25%   |
| Excavator        | 21        | 1.25%   |
| Bonnell          | 20        | 1.19%   |
| Nehalem          | 19        | 1.13%   |
| Icelake          | 16        | 0.95%   |
| K10              | 15        | 0.89%   |
| P6               | 13        | 0.77%   |
| Jaguar           | 12        | 0.71%   |
| Steamroller      | 10        | 0.59%   |
| Goldmont plus    | 10        | 0.59%   |
| K8 Hammer        | 9         | 0.53%   |
| Goldmont         | 9         | 0.53%   |
| Bobcat           | 7         | 0.42%   |
| Tremont          | 6         | 0.36%   |
| K8 & K10 hybrid  | 4         | 0.24%   |
| Bulldozer        | 3         | 0.18%   |
| K10 Llano        | 2         | 0.12%   |
| Gracemont        | 2         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 931       | 45.06%  |
| Nvidia                           | 619       | 29.96%  |
| AMD                              | 499       | 24.15%  |
| Silicon Integrated Systems [SiS] | 11        | 0.53%   |
| Matrox Electronics Systems       | 3         | 0.15%   |
| ASPEED Technology                | 3         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 78        | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 62        | 2.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 46        | 2.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 46        | 2.15%   |
| Intel UHD Graphics 620                                                                   | 45        | 2.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 45        | 2.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 43        | 2.01%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 37        | 1.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 1.68%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 35        | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 1.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 33        | 1.54%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 1.5%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 32        | 1.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 31        | 1.45%   |
| Intel HD Graphics 5500                                                                   | 29        | 1.36%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 1.36%   |
| Intel HD Graphics 530                                                                    | 28        | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 1.26%   |
| Intel HD Graphics 620                                                                    | 26        | 1.21%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 25        | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 25        | 1.17%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 23        | 1.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 22        | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 21        | 0.98%   |
| Nvidia G86M [GeForce 8600M GS]                                                           | 21        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 0.93%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 19        | 0.89%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 18        | 0.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 18        | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 16        | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 15        | 0.7%    |
| Intel HD Graphics 630                                                                    | 15        | 0.7%    |
| AMD Lucienne                                                                             | 15        | 0.7%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 14        | 0.65%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 0.65%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 14        | 0.65%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 589       | 34.75%  |
| 1 x AMD         | 377       | 22.24%  |
| 1 x Nvidia      | 297       | 17.52%  |
| Intel + Nvidia  | 273       | 16.11%  |
| Intel + AMD     | 50        | 2.95%   |
| AMD + Nvidia    | 44        | 2.6%    |
| 2 x AMD         | 30        | 1.77%   |
| 1 x SiS         | 11        | 0.65%   |
| Other           | 10        | 0.59%   |
| 2 x Intel       | 6         | 0.35%   |
| 2 x Nvidia      | 2         | 0.12%   |
| Nvidia + ASPEED | 2         | 0.12%   |
| 1 x Matrox      | 2         | 0.12%   |
| Nvidia + Matrox | 1         | 0.06%   |
| 1 x ASPEED      | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1328      | 77.62%  |
| Proprietary | 303       | 17.71%  |
| Unknown     | 80        | 4.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 935       | 53.86%  |
| 0.01-0.5   | 263       | 15.15%  |
| 1.01-2.0   | 205       | 11.81%  |
| 0.51-1.0   | 138       | 7.95%   |
| 3.01-4.0   | 97        | 5.59%   |
| 7.01-8.0   | 44        | 2.53%   |
| 5.01-6.0   | 33        | 1.9%    |
| 8.01-16.0  | 15        | 0.86%   |
| 2.01-3.0   | 6         | 0.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 250       | 14.09%  |
| Samsung Electronics     | 221       | 12.46%  |
| Chimei Innolux          | 173       | 9.75%   |
| LG Display              | 152       | 8.57%   |
| BOE                     | 146       | 8.23%   |
| Goldstar                | 129       | 7.27%   |
| Ancor Communications    | 81        | 4.57%   |
| Hewlett-Packard         | 76        | 4.28%   |
| Dell                    | 45        | 2.54%   |
| AOC                     | 41        | 2.31%   |
| Apple                   | 37        | 2.09%   |
| Lenovo                  | 34        | 1.92%   |
| Chi Mei Optoelectronics | 32        | 1.8%    |
| Philips                 | 29        | 1.63%   |
| BenQ                    | 29        | 1.63%   |
| LG Philips              | 25        | 1.41%   |
| Sharp                   | 22        | 1.24%   |
| PANDA                   | 21        | 1.18%   |
| ASUSTek Computer        | 18        | 1.01%   |
| Acer                    | 18        | 1.01%   |
| Sony                    | 15        | 0.85%   |
| LG Electronics          | 13        | 0.73%   |
| Unknown                 | 11        | 0.62%   |
| ViewSonic               | 8         | 0.45%   |
| MSI                     | 8         | 0.45%   |
| InfoVision              | 8         | 0.45%   |
| CPT                     | 7         | 0.39%   |
| Seiko/Epson             | 6         | 0.34%   |
| HannStar                | 6         | 0.34%   |
| Gigabyte Technology     | 6         | 0.34%   |
| HUAWEI                  | 5         | 0.28%   |
| Toshiba                 | 4         | 0.23%   |
| Lenovo Group Limited    | 4         | 0.23%   |
| HPN                     | 4         | 0.23%   |
| Fujitsu Siemens         | 4         | 0.23%   |
| Unknown                 | 4         | 0.23%   |
| Vestel Elektronik       | 3         | 0.17%   |
| Valve                   | 3         | 0.17%   |
| Mi                      | 3         | 0.17%   |
| LGD                     | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch            | 14        | 0.77%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 13        | 0.71%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 12        | 0.66%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 11        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 10        | 0.55%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 9         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 8         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch          | 7         | 0.38%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                     | 7         | 0.38%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                        | 7         | 0.38%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch         | 7         | 0.38%   |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch    | 7         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 6         | 0.33%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 6         | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.33%   |
| AU Optronics LCD Monitor AUO18D4 1280x800 216x135mm 10.0-inch            | 6         | 0.33%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 5         | 0.27%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 5         | 0.27%   |
| LG Philips LCD Monitor LPLDD00 1280x800 331x207mm 15.4-inch              | 5         | 0.27%   |
| LG Display LCD Monitor LGD045D 1366x768 345x194mm 15.6-inch              | 5         | 0.27%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.27%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 5         | 0.27%   |
| HUAWEI AD80HW HWV2402 1920x1080 527x296mm 23.8-inch                      | 5         | 0.27%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 5         | 0.27%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                     | 5         | 0.27%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 5         | 0.27%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15B7 1366x768 344x193mm 15.5-inch          | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 5         | 0.27%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 5         | 0.27%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 5         | 0.27%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 5         | 0.27%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.27%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 680       | 40.38%  |
| 1366x768 (WXGA)    | 404       | 23.99%  |
| 3840x2160 (4K)     | 94        | 5.58%   |
| 1280x1024 (SXGA)   | 77        | 4.57%   |
| 1280x800 (WXGA)    | 65        | 3.86%   |
| 2560x1440 (QHD)    | 52        | 3.09%   |
| 1600x900 (HD+)     | 43        | 2.55%   |
| 1680x1050 (WSXGA+) | 42        | 2.49%   |
| 1440x900 (WXGA+)   | 42        | 2.49%   |
| 1920x1200 (WUXGA)  | 28        | 1.66%   |
| 2560x1080          | 18        | 1.07%   |
| 1360x768           | 15        | 0.89%   |
| Unknown            | 15        | 0.89%   |
| 2560x1600          | 11        | 0.65%   |
| 2160x1440          | 10        | 0.59%   |
| 1024x768 (XGA)     | 10        | 0.59%   |
| 3440x1440          | 9         | 0.53%   |
| 3840x2400          | 7         | 0.42%   |
| 3840x1080          | 7         | 0.42%   |
| 1024x600           | 7         | 0.42%   |
| 2880x1800          | 6         | 0.36%   |
| 2288x1287          | 4         | 0.24%   |
| 1920x540           | 4         | 0.24%   |
| 800x1280           | 3         | 0.18%   |
| 3200x1800 (QHD+)   | 3         | 0.18%   |
| 1400x1050          | 3         | 0.18%   |
| 1152x864           | 3         | 0.18%   |
| 2880x1620          | 2         | 0.12%   |
| 640x480            | 1         | 0.06%   |
| 5760x1080          | 1         | 0.06%   |
| 4560x1080          | 1         | 0.06%   |
| 4480x1600          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |
| 3840x1100          | 1         | 0.06%   |
| 3520x1080          | 1         | 0.06%   |
| 3360x1080          | 1         | 0.06%   |
| 3360x1050          | 1         | 0.06%   |
| 3280x1080          | 1         | 0.06%   |
| 3240x2160          | 1         | 0.06%   |
| 3072x1920          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 576       | 32.43%  |
| 13      | 152       | 8.56%   |
| 14      | 151       | 8.5%    |
| 21      | 118       | 6.64%   |
| 24      | 112       | 6.31%   |
| 27      | 91        | 5.12%   |
| 17      | 88        | 4.95%   |
| 23      | 82        | 4.62%   |
| Unknown | 78        | 4.39%   |
| 19      | 51        | 2.87%   |
| 18      | 30        | 1.69%   |
| 31      | 29        | 1.63%   |
| 34      | 24        | 1.35%   |
| 20      | 23        | 1.3%    |
| 12      | 23        | 1.3%    |
| 16      | 19        | 1.07%   |
| 11      | 18        | 1.01%   |
| 22      | 17        | 0.96%   |
| 10      | 16        | 0.9%    |
| 84      | 13        | 0.73%   |
| 40      | 8         | 0.45%   |
| 25      | 8         | 0.45%   |
| 54      | 7         | 0.39%   |
| 28      | 7         | 0.39%   |
| 72      | 5         | 0.28%   |
| 32      | 5         | 0.28%   |
| 46      | 4         | 0.23%   |
| 33      | 4         | 0.23%   |
| 26      | 3         | 0.17%   |
| 7       | 3         | 0.17%   |
| 48      | 2         | 0.11%   |
| 42      | 2         | 0.11%   |
| 142     | 1         | 0.06%   |
| 60      | 1         | 0.06%   |
| 58      | 1         | 0.06%   |
| 39      | 1         | 0.06%   |
| 37      | 1         | 0.06%   |
| 36      | 1         | 0.06%   |
| 8       | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 840       | 48.14%  |
| 501-600        | 265       | 15.19%  |
| 401-500        | 210       | 12.03%  |
| 201-300        | 132       | 7.56%   |
| 351-400        | 90        | 5.16%   |
| Unknown        | 78        | 4.47%   |
| 601-700        | 46        | 2.64%   |
| 701-800        | 34        | 1.95%   |
| 1501-2000      | 18        | 1.03%   |
| 1001-1500      | 15        | 0.86%   |
| 801-900        | 10        | 0.57%   |
| 1-100          | 3         | 0.17%   |
| 901-1000       | 2         | 0.11%   |
| More than 2000 | 1         | 0.06%   |
| 101-200        | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1181      | 73.63%  |
| 16/10   | 203       | 12.66%  |
| Unknown | 69        | 4.3%    |
| 5/4     | 67        | 4.18%   |
| 21/9    | 28        | 1.75%   |
| 4/3     | 26        | 1.62%   |
| 3/2     | 20        | 1.25%   |
| 6/5     | 3         | 0.19%   |
| 0.67    | 3         | 0.19%   |
| 32/9    | 2         | 0.12%   |
| 3.40    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 568       | 32.18%  |
| 201-250        | 275       | 15.58%  |
| 81-90          | 239       | 13.54%  |
| 151-200        | 97        | 5.5%    |
| 301-350        | 94        | 5.33%   |
| Unknown        | 78        | 4.42%   |
| 141-150        | 68        | 3.85%   |
| 351-500        | 63        | 3.57%   |
| 71-80          | 61        | 3.46%   |
| 121-130        | 38        | 2.15%   |
| 251-300        | 37        | 2.1%    |
| More than 1000 | 29        | 1.64%   |
| 61-70          | 21        | 1.19%   |
| 111-120        | 21        | 1.19%   |
| 51-60          | 19        | 1.08%   |
| 501-1000       | 19        | 1.08%   |
| 41-50          | 16        | 0.91%   |
| 131-140        | 10        | 0.57%   |
| 91-100         | 8         | 0.45%   |
| 1-40           | 4         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 539       | 31.48%  |
| 101-120       | 509       | 29.73%  |
| 121-160       | 448       | 26.17%  |
| 161-240       | 90        | 5.26%   |
| Unknown       | 78        | 4.56%   |
| More than 240 | 27        | 1.58%   |
| 1-50          | 21        | 1.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1343      | 77.63%  |
| 2     | 248       | 14.34%  |
| 0     | 106       | 6.13%   |
| 3     | 29        | 1.68%   |
| 4     | 4         | 0.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 926       | 36.57%  |
| Intel                             | 697       | 27.53%  |
| Qualcomm Atheros                  | 343       | 13.55%  |
| Broadcom                          | 162       | 6.4%    |
| Marvell Technology Group          | 59        | 2.33%   |
| TP-Link                           | 56        | 2.21%   |
| MediaTek                          | 31        | 1.22%   |
| Broadcom Limited                  | 31        | 1.22%   |
| Nvidia                            | 23        | 0.91%   |
| Ralink                            | 22        | 0.87%   |
| Qualcomm Atheros Communications   | 20        | 0.79%   |
| Silicon Integrated Systems [SiS]  | 16        | 0.63%   |
| Ralink Technology                 | 14        | 0.55%   |
| ASIX Electronics                  | 12        | 0.47%   |
| D-Link                            | 9         | 0.36%   |
| ASUSTek Computer                  | 8         | 0.32%   |
| VIA Technologies                  | 5         | 0.2%    |
| Sierra Wireless                   | 5         | 0.2%    |
| Samsung Electronics               | 5         | 0.2%    |
| Lenovo                            | 5         | 0.2%    |
| JMicron Technology                | 5         | 0.2%    |
| Huawei Technologies               | 5         | 0.2%    |
| Ericsson Business Mobile Networks | 5         | 0.2%    |
| Hewlett-Packard                   | 4         | 0.16%   |
| DisplayLink                       | 4         | 0.16%   |
| Dell                              | 4         | 0.16%   |
| D-Link System                     | 4         | 0.16%   |
| Attansic Technology               | 4         | 0.16%   |
| Microsoft                         | 3         | 0.12%   |
| Mercucys                          | 3         | 0.12%   |
| ICS Advent                        | 3         | 0.12%   |
| Edimax Technology                 | 3         | 0.12%   |
| ADMtek                            | 3         | 0.12%   |
| TRENDnet                          | 2         | 0.08%   |
| Mellanox Technologies             | 2         | 0.08%   |
| Fibocom                           | 2         | 0.08%   |
| Dresden Elektronik                | 2         | 0.08%   |
| Belkin Components                 | 2         | 0.08%   |
| Accton Technology                 | 2         | 0.08%   |
| Xiaomi                            | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 626       | 21.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 131       | 4.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 55        | 1.87%   |
| Intel Wi-Fi 6 AX200                                                     | 54        | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 1.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 45        | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 1.4%    |
| Intel Wireless 8265 / 8275                                              | 39        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 37        | 1.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 37        | 1.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 35        | 1.19%   |
| Intel Wi-Fi 6 AX201                                                     | 34        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 31        | 1.06%   |
| Intel Wireless 7265                                                     | 30        | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                       | 28        | 0.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 27        | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 27        | 0.92%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 0.89%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                    | 26        | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 0.89%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]         | 25        | 0.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 25        | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 25        | 0.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 25        | 0.85%   |
| Intel Wireless 7260                                                     | 24        | 0.82%   |
| Intel Wireless 3165                                                     | 24        | 0.82%   |
| Intel Wireless 8260                                                     | 22        | 0.75%   |
| Intel I211 Gigabit Network Connection                                   | 21        | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 0.72%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 20        | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 20        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 0.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 18        | 0.61%   |
| Intel 82579V Gigabit Network Connection                                 | 18        | 0.61%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 17        | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                         | 16        | 0.55%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 563       | 40.65%  |
| Qualcomm Atheros                      | 280       | 20.22%  |
| Realtek Semiconductor                 | 245       | 17.69%  |
| Broadcom                              | 113       | 8.16%   |
| TP-Link                               | 32        | 2.31%   |
| MediaTek                              | 30        | 2.17%   |
| Ralink                                | 22        | 1.59%   |
| Qualcomm Atheros Communications       | 20        | 1.44%   |
| Broadcom Limited                      | 18        | 1.3%    |
| Ralink Technology                     | 14        | 1.01%   |
| D-Link                                | 9         | 0.65%   |
| ASUSTek Computer                      | 8         | 0.58%   |
| Sierra Wireless                       | 5         | 0.36%   |
| Dell                                  | 4         | 0.29%   |
| Mercucys                              | 3         | 0.22%   |
| Marvell Technology Group              | 3         | 0.22%   |
| Edimax Technology                     | 3         | 0.22%   |
| TRENDnet                              | 2         | 0.14%   |
| Microsoft                             | 2         | 0.14%   |
| Fibocom                               | 2         | 0.14%   |
| Belkin Components                     | 2         | 0.14%   |
| Sitecom Europe                        | 1         | 0.07%   |
| Micro Star International              | 1         | 0.07%   |
| D-Link System                         | 1         | 0.07%   |
| Accton Technology                     | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 55        | 3.97%   |
| Intel Wi-Fi 6 AX200                                                     | 54        | 3.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 52        | 3.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 41        | 2.96%   |
| Intel Wireless 8265 / 8275                                              | 39        | 2.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 37        | 2.67%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 35        | 2.53%   |
| Intel Wi-Fi 6 AX201                                                     | 34        | 2.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 31        | 2.24%   |
| Intel Wireless 7265                                                     | 30        | 2.16%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 30        | 2.16%   |
| Broadcom BCM43142 802.11b/g/n                                           | 28        | 2.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 27        | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 27        | 1.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 26        | 1.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 1.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 25        | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 25        | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 25        | 1.8%    |
| Intel Wireless 7260                                                     | 24        | 1.73%   |
| Intel Wireless 3165                                                     | 24        | 1.73%   |
| Intel Wireless 8260                                                     | 22        | 1.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 1.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 20        | 1.44%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 20        | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 19        | 1.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 19        | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 18        | 1.3%    |
| Qualcomm Atheros AR9271 802.11n                                         | 16        | 1.15%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 16        | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 15        | 1.08%   |
| Intel Wireless 3160                                                     | 15        | 1.08%   |
| Intel WiFi Link 5100                                                    | 14        | 1.01%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 12        | 0.87%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 12        | 0.87%   |
| Intel Wireless-AC 9260                                                  | 12        | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 11        | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 10        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 10        | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 841       | 56.1%   |
| Intel                            | 289       | 19.28%  |
| Qualcomm Atheros                 | 99        | 6.6%    |
| Broadcom                         | 68        | 4.54%   |
| Marvell Technology Group         | 56        | 3.74%   |
| TP-Link                          | 25        | 1.67%   |
| Nvidia                           | 23        | 1.53%   |
| Silicon Integrated Systems [SiS] | 16        | 1.07%   |
| Broadcom Limited                 | 13        | 0.87%   |
| ASIX Electronics                 | 12        | 0.8%    |
| VIA Technologies                 | 5         | 0.33%   |
| Lenovo                           | 5         | 0.33%   |
| JMicron Technology               | 5         | 0.33%   |
| Huawei Technologies              | 4         | 0.27%   |
| DisplayLink                      | 4         | 0.27%   |
| Attansic Technology              | 4         | 0.27%   |
| Samsung Electronics              | 3         | 0.2%    |
| ICS Advent                       | 3         | 0.2%    |
| Hewlett-Packard                  | 3         | 0.2%    |
| D-Link System                    | 3         | 0.2%    |
| ADMtek                           | 3         | 0.2%    |
| Mellanox Technologies            | 2         | 0.13%   |
| Xiaomi                           | 1         | 0.07%   |
| T & A Mobile Phones              | 1         | 0.07%   |
| Standard Microsystems            | 1         | 0.07%   |
| Silicom                          | 1         | 0.07%   |
| Qualcomm                         | 1         | 0.07%   |
| Microsoft                        | 1         | 0.07%   |
| Microchip Technology             | 1         | 0.07%   |
| MediaTek                         | 1         | 0.07%   |
| LSI                              | 1         | 0.07%   |
| Archos                           | 1         | 0.07%   |
| Apple                            | 1         | 0.07%   |
| Allwinner Technology             | 1         | 0.07%   |
| Accton Technology                | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 626       | 41.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 131       | 8.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 45        | 2.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 37        | 2.43%   |
| Realtek RTL8125 2.5GbE Controller                                              | 28        | 1.84%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller                           | 26        | 1.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 25        | 1.64%   |
| Intel I211 Gigabit Network Connection                                          | 21        | 1.38%   |
| Intel 82579V Gigabit Network Connection                                        | 18        | 1.18%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 17        | 1.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 15        | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 14        | 0.92%   |
| Intel Ethernet Connection (2) I219-V                                           | 14        | 0.92%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 13        | 0.85%   |
| Intel Ethernet Connection I217-LM                                              | 13        | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                          | 13        | 0.85%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 11        | 0.72%   |
| Intel Ethernet Connection I218-LM                                              | 11        | 0.72%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 10        | 0.66%   |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 0.59%   |
| Intel Ethernet Connection (6) I219-V                                           | 8         | 0.52%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 8         | 0.52%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 8         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 7         | 0.46%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 7         | 0.46%   |
| Intel Ethernet Controller I225-V                                               | 7         | 0.46%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 0.46%   |
| Intel Ethernet Connection (7) I219-V                                           | 7         | 0.46%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 0.46%   |
| Intel Ethernet Connection (2) I218-V                                           | 7         | 0.46%   |
| Intel 82567LM Gigabit Network Connection                                       | 7         | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 7         | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 0.46%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 6         | 0.39%   |
| Nvidia MCP79 Ethernet                                                          | 6         | 0.39%   |
| Nvidia MCP61 Ethernet                                                          | 6         | 0.39%   |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                                          | 6         | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 6         | 0.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 6         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1440      | 51.61%  |
| WiFi     | 1325      | 47.49%  |
| Modem    | 23        | 0.82%   |
| Unknown  | 2         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1045      | 59.21%  |
| Ethernet | 719       | 40.74%  |
| Modem    | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 951       | 56.47%  |
| 1     | 672       | 39.9%   |
| 0     | 35        | 2.08%   |
| 3     | 17        | 1.01%   |
| 6     | 3         | 0.18%   |
| 10    | 2         | 0.12%   |
| 5     | 2         | 0.12%   |
| 4     | 2         | 0.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1232      | 71.38%  |
| Yes  | 494       | 28.62%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 417       | 41.53%  |
| Realtek Semiconductor           | 119       | 11.85%  |
| IMC Networks                    | 65        | 6.47%   |
| Qualcomm Atheros Communications | 63        | 6.27%   |
| Foxconn / Hon Hai               | 46        | 4.58%   |
| Lite-On Technology              | 45        | 4.48%   |
| Cambridge Silicon Radio         | 44        | 4.38%   |
| Broadcom                        | 39        | 3.88%   |
| Apple                           | 38        | 3.78%   |
| ASUSTek Computer                | 36        | 3.59%   |
| Toshiba                         | 21        | 2.09%   |
| Hewlett-Packard                 | 16        | 1.59%   |
| Realtek                         | 11        | 1.1%    |
| Dell                            | 11        | 1.1%    |
| Ralink                          | 10        | 1%      |
| MediaTek                        | 5         | 0.5%    |
| Alps Electric                   | 5         | 0.5%    |
| TP-Link                         | 3         | 0.3%    |
| Ralink Technology               | 2         | 0.2%    |
| Marvell Semiconductor           | 2         | 0.2%    |
| Chicony Electronics             | 2         | 0.2%    |
| Belkin Components               | 2         | 0.2%    |
| Integrated System Solution      | 1         | 0.1%    |
| Foxconn International           | 1         | 0.1%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 151       | 15.04%  |
| Intel Bluetooth Device                                                              | 95        | 9.46%   |
| Realtek Bluetooth Radio                                                             | 87        | 8.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 67        | 6.67%   |
| Intel AX200 Bluetooth                                                               | 55        | 5.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 44        | 4.38%   |
| IMC Networks Bluetooth Device                                                       | 31        | 3.09%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 21        | 2.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 21        | 2.09%   |
| Apple Bluetooth Host Controller                                                     | 18        | 1.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 17        | 1.69%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 17        | 1.69%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 1.59%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 1.59%   |
| IMC Networks Bluetooth Radio                                                        | 14        | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 12        | 1.2%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 12        | 1.2%    |
| Realtek Bluetooth Radio                                                             | 11        | 1.1%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 11        | 1.1%    |
| Ralink RT3290 Bluetooth                                                             | 10        | 1%      |
| Lite-On Bluetooth Device                                                            | 10        | 1%      |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1%      |
| IMC Networks Wireless_Device                                                        | 10        | 1%      |
| Foxconn / Hon Hai Bluetooth Device                                                  | 10        | 1%      |
| Apple Bluetooth USB Host Controller                                                 | 10        | 1%      |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.7%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 7         | 0.7%    |
| Realtek RTL8821A Bluetooth                                                          | 6         | 0.6%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 6         | 0.6%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 6         | 0.6%    |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 0.5%    |
| Toshiba Askey Bluetooth Module                                                      | 5         | 0.5%    |
| MediaTek Wireless_Device                                                            | 5         | 0.5%    |
| Lite-On BCM43142A0                                                                  | 5         | 0.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 5         | 0.5%    |
| Intel AX210 Bluetooth                                                               | 5         | 0.5%    |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 5         | 0.5%    |
| Dell DW375 Bluetooth Module                                                         | 5         | 0.5%    |
| ASUS Bluetooth Device                                                               | 5         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1199      | 52.75%  |
| AMD                                  | 492       | 21.65%  |
| Nvidia                               | 360       | 15.84%  |
| C-Media Electronics                  | 30        | 1.32%   |
| Creative Labs                        | 20        | 0.88%   |
| Silicon Integrated Systems [SiS]     | 16        | 0.7%    |
| Logitech                             | 15        | 0.66%   |
| Kingston Technology                  | 12        | 0.53%   |
| Texas Instruments                    | 11        | 0.48%   |
| Razer USA                            | 11        | 0.48%   |
| JMTek                                | 11        | 0.48%   |
| Realtek Semiconductor                | 8         | 0.35%   |
| Hewlett-Packard                      | 8         | 0.35%   |
| GN Netcom                            | 8         | 0.35%   |
| Plantronics                          | 7         | 0.31%   |
| ASUSTek Computer                     | 6         | 0.26%   |
| Lenovo                               | 5         | 0.22%   |
| Creative Technology                  | 4         | 0.18%   |
| Micro Star International             | 3         | 0.13%   |
| Generalplus Technology               | 3         | 0.13%   |
| Focusrite-Novation                   | 3         | 0.13%   |
| VIA Technologies                     | 2         | 0.09%   |
| SteelSeries ApS                      | 2         | 0.09%   |
| Sony                                 | 2         | 0.09%   |
| Guillemot                            | 2         | 0.09%   |
| EGO SYStems                          | 2         | 0.09%   |
| DSEA A/S                             | 2         | 0.09%   |
| Corsair                              | 2         | 0.09%   |
| Apple                                | 2         | 0.09%   |
| XMOS                                 | 1         | 0.04%   |
| WinChipHead                          | 1         | 0.04%   |
| ULi Electronics                      | 1         | 0.04%   |
| Turtle Beach                         | 1         | 0.04%   |
| Trust                                | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Silicon Motion                       | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |
| Samsung Electronics                  | 1         | 0.04%   |
| Samson Technologies                  | 1         | 0.04%   |
| Philips (or NXP)                     | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 158       | 5.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 110       | 4.11%   |
| Intel Sunrise Point-LP HD Audio                                            | 107       | 4%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 86        | 3.22%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 79        | 2.95%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 78        | 2.92%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 78        | 2.92%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 66        | 2.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 62        | 2.32%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 62        | 2.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 59        | 2.21%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 57        | 2.13%   |
| AMD FCH Azalia Controller                                                  | 52        | 1.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 49        | 1.83%   |
| AMD Starship/Matisse HD Audio Controller                                   | 48        | 1.8%    |
| Intel Haswell-ULT HD Audio Controller                                      | 46        | 1.72%   |
| Intel 8 Series HD Audio Controller                                         | 45        | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 45        | 1.68%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 42        | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 40        | 1.5%    |
| AMD Kabini HDMI/DP Audio                                                   | 39        | 1.46%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 38        | 1.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 37        | 1.38%   |
| Intel Comet Lake PCH-LP cAVS                                               | 37        | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 35        | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 35        | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 34        | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 33        | 1.23%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 27        | 1.01%   |
| Nvidia High Definition Audio Controller                                    | 26        | 0.97%   |
| Nvidia GF108 High Definition Audio Controller                              | 26        | 0.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 25        | 0.93%   |
| Intel Comet Lake PCH cAVS                                                  | 21        | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 21        | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                              | 20        | 0.75%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 20        | 0.75%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                           | 20        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 19        | 0.71%   |
| Nvidia GP106 High Definition Audio Controller                              | 18        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 219       | 23.91%  |
| SK hynix            | 171       | 18.67%  |
| Unknown             | 123       | 13.43%  |
| Kingston            | 119       | 12.99%  |
| Micron Technology   | 78        | 8.52%   |
| G.Skill             | 48        | 5.24%   |
| Crucial             | 30        | 3.28%   |
| Corsair             | 29        | 3.17%   |
| Ramaxel Technology  | 16        | 1.75%   |
| Elpida              | 12        | 1.31%   |
| A-DATA Technology   | 12        | 1.31%   |
| Unknown             | 11        | 1.2%    |
| Team                | 10        | 1.09%   |
| Nanya Technology    | 7         | 0.76%   |
| Unknown (ABCD)      | 4         | 0.44%   |
| Transcend           | 4         | 0.44%   |
| Lexar               | 2         | 0.22%   |
| Apacer              | 2         | 0.22%   |
| Unigen              | 1         | 0.11%   |
| Unifosa             | 1         | 0.11%   |
| Toshiba             | 1         | 0.11%   |
| Teikon              | 1         | 0.11%   |
| Smart               | 1         | 0.11%   |
| Silicon Power       | 1         | 0.11%   |
| PUSKILL             | 1         | 0.11%   |
| Patriot             | 1         | 0.11%   |
| Netlist             | 1         | 0.11%   |
| Kimtigo             | 1         | 0.11%   |
| Infineon            | 1         | 0.11%   |
| Hewlett-Packard     | 1         | 0.11%   |
| GOODRAM             | 1         | 0.11%   |
| Goldkey             | 1         | 0.11%   |
| Essencore Limited   | 1         | 0.11%   |
| CSX                 | 1         | 0.11%   |
| Atermiter           | 1         | 0.11%   |
| ASint Technology    | 1         | 0.11%   |
| 48spaces            | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2GB SODIMM DDR2                          | 24        | 2.45%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s | 16        | 1.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 15        | 1.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s      | 11        | 1.12%   |
| Unknown                                                     | 11        | 1.12%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 9         | 0.92%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 8         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s       | 8         | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 7         | 0.71%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s      | 7         | 0.71%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s       | 6         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 6         | 0.61%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s      | 5         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s      | 5         | 0.51%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 5         | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 5         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 5         | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s    | 5         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s    | 5         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 5         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 5         | 0.51%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 5         | 0.51%   |
| SK hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s      | 4         | 0.41%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s   | 4         | 0.41%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s    | 4         | 0.41%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s    | 4         | 0.41%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 4         | 0.41%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s    | 4         | 0.41%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s      | 4         | 0.41%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s        | 4         | 0.41%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s        | 4         | 0.41%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 4         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 4         | 0.41%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s     | 4         | 0.41%   |
| Kingston RAM 99U5471-012.A00LF 4GB DIMM DDR3 1600MT/s       | 4         | 0.41%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                        | 3         | 0.31%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 3         | 0.31%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                   | 3         | 0.31%   |
| Unknown RAM Module 2048MB SODIMM DDR2                       | 3         | 0.31%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                 | 3         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 364       | 45.5%   |
| DDR3    | 237       | 29.63%  |
| DDR2    | 76        | 9.5%    |
| LPDDR4  | 26        | 3.25%   |
| Unknown | 24        | 3%      |
| SDRAM   | 22        | 2.75%   |
| LPDDR3  | 19        | 2.38%   |
| LPDDR5  | 14        | 1.75%   |
| DDR5    | 10        | 1.25%   |
| DDR     | 8         | 1%      |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 486       | 60.9%   |
| DIMM         | 223       | 27.94%  |
| Row Of Chips | 83        | 10.4%   |
| FB-DIMM      | 2         | 0.25%   |
| Chip         | 2         | 0.25%   |
| Unknown      | 2         | 0.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 300       | 34.72%  |
| 4096    | 228       | 26.39%  |
| 2048    | 138       | 15.97%  |
| 16384   | 127       | 14.7%   |
| 1024    | 32        | 3.7%    |
| 32768   | 29        | 3.36%   |
| 512     | 6         | 0.69%   |
| 12288   | 1         | 0.12%   |
| 3072    | 1         | 0.12%   |
| 256     | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 152       | 17.67%  |
| 2667    | 137       | 15.93%  |
| 3200    | 130       | 15.12%  |
| Unknown | 55        | 6.4%    |
| 2400    | 49        | 5.7%    |
| 1333    | 49        | 5.7%    |
| 2133    | 37        | 4.3%    |
| 667     | 29        | 3.37%   |
| 1334    | 22        | 2.56%   |
| 6400    | 14        | 1.63%   |
| 3600    | 14        | 1.63%   |
| 4267    | 13        | 1.51%   |
| 1867    | 13        | 1.51%   |
| 800     | 13        | 1.51%   |
| 8400    | 12        | 1.4%    |
| 1067    | 12        | 1.4%    |
| 3266    | 10        | 1.16%   |
| 4800    | 8         | 0.93%   |
| 3000    | 8         | 0.93%   |
| 1866    | 8         | 0.93%   |
| 533     | 8         | 0.93%   |
| 2666    | 7         | 0.81%   |
| 4199    | 6         | 0.7%    |
| 3733    | 4         | 0.47%   |
| 3400    | 4         | 0.47%   |
| 2048    | 4         | 0.47%   |
| 1800    | 4         | 0.47%   |
| 1066    | 4         | 0.47%   |
| 400     | 4         | 0.47%   |
| 3800    | 3         | 0.35%   |
| 4000    | 2         | 0.23%   |
| 3534    | 2         | 0.23%   |
| 2933    | 2         | 0.23%   |
| 2733    | 2         | 0.23%   |
| 2000    | 2         | 0.23%   |
| 975     | 2         | 0.23%   |
| 43889   | 1         | 0.12%   |
| 6000    | 1         | 0.12%   |
| 5600    | 1         | 0.12%   |
| 4266    | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 22        | 59.46%  |
| Seiko Epson            | 5         | 13.51%  |
| Canon                  | 3         | 8.11%   |
| Brother Industries     | 2         | 5.41%   |
| Xerox                  | 1         | 2.7%    |
| STMicroelectronics     | 1         | 2.7%    |
| Samsung Electronics    | 1         | 2.7%    |
| Panasonic (Matsushita) | 1         | 2.7%    |
| Lexmark International  | 1         | 2.7%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP Deskjet 1050 J410                                                  | 5         | 12.82%  |
| HP DeskJet F2492 All-in-One                                           | 2         | 5.13%   |
| Xerox Phaser 6000B                                                    | 1         | 2.56%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 2.56%   |
| Seiko Epson XP-225 Series                                             | 1         | 2.56%   |
| Seiko Epson XP-2200 Series                                            | 1         | 2.56%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 2.56%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]                          | 1         | 2.56%   |
| Seiko Epson AcuLaser C1700                                            | 1         | 2.56%   |
| Samsung ML-1640 Series Laser Printer                                  | 1         | 2.56%   |
| Panasonic (Matsushita) KX-FLB851SP                                    | 1         | 2.56%   |
| Lexmark International E120(n)                                         | 1         | 2.56%   |
| HP OfficeJet 5200 series                                              | 1         | 2.56%   |
| HP Officejet 4620 series                                              | 1         | 2.56%   |
| HP Officejet 4500 G510g-m                                             | 1         | 2.56%   |
| HP OfficeJet 3830 series                                              | 1         | 2.56%   |
| HP LaserJet Professional P1102w                                       | 1         | 2.56%   |
| HP LaserJet M14-M17                                                   | 1         | 2.56%   |
| HP ENVY 6000 series                                                   | 1         | 2.56%   |
| HP ENVY 4520 series                                                   | 1         | 2.56%   |
| HP DeskJet F4100 Printer series                                       | 1         | 2.56%   |
| HP DeskJet F300 series                                                | 1         | 2.56%   |
| HP DeskJet 930c                                                       | 1         | 2.56%   |
| HP DeskJet 3630 series                                                | 1         | 2.56%   |
| HP Deskjet 3050A                                                      | 1         | 2.56%   |
| HP Deskjet 3050 J610 series                                           | 1         | 2.56%   |
| HP DeskJet 2700 series                                                | 1         | 2.56%   |
| HP DeskJet 2130 series                                                | 1         | 2.56%   |
| Canon TS6300 series                                                   | 1         | 2.56%   |
| Canon PIXMA TS6250                                                    | 1         | 2.56%   |
| Canon PIXMA MG2900 Series                                             | 1         | 2.56%   |
| Canon LBP6200                                                         | 1         | 2.56%   |
| Brother DCP-L3550CDW                                                  | 1         | 2.56%   |
| Brother DCP-1610W                                                     | 1         | 2.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Mustek Systems  | 5         | 45.45%  |
| Canon           | 4         | 36.36%  |
| Seiko Epson     | 1         | 9.09%   |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Mustek Systems ScanExpress 1200 UB    | 3         | 27.27%  |
| Mustek Systems BearPaw 2448 CU Pro    | 2         | 18.18%  |
| Canon CanoScan 4400F                  | 2         | 18.18%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 9.09%   |
| HP ScanJet 5300c/5370c                | 1         | 9.09%   |
| Canon CanoScan N670U/N676U/LiDE 20    | 1         | 9.09%   |
| Canon CanoScan LiDE 110               | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 268       | 23.7%   |
| IMC Networks                           | 133       | 11.76%  |
| Realtek Semiconductor                  | 80        | 7.07%   |
| Bison Electronics                      | 59        | 5.22%   |
| Suyin                                  | 52        | 4.6%    |
| Microdia                               | 52        | 4.6%    |
| Quanta                                 | 51        | 4.51%   |
| Cheng Uei Precision Industry (Foxlink) | 39        | 3.45%   |
| Sunplus Innovation Technology          | 37        | 3.27%   |
| Logitech                               | 35        | 3.09%   |
| Ricoh                                  | 33        | 2.92%   |
| Lite-On Technology                     | 31        | 2.74%   |
| Syntek                                 | 29        | 2.56%   |
| Apple                                  | 29        | 2.56%   |
| Acer                                   | 20        | 1.77%   |
| Luxvisions Innotech Limited            | 18        | 1.59%   |
| Microsoft                              | 17        | 1.5%    |
| Silicon Motion                         | 16        | 1.41%   |
| Creative Technology                    | 13        | 1.15%   |
| Hewlett-Packard                        | 11        | 0.97%   |
| Alcor Micro                            | 10        | 0.88%   |
| Z-Star Microelectronics                | 8         | 0.71%   |
| Lenovo                                 | 8         | 0.71%   |
| Importek                               | 8         | 0.71%   |
| Generalplus Technology                 | 8         | 0.71%   |
| Sonix Technology                       | 7         | 0.62%   |
| Samsung Electronics                    | 6         | 0.53%   |
| WaveRider Communications               | 4         | 0.35%   |
| Cubeternet                             | 4         | 0.35%   |
| SunplusIT                              | 3         | 0.27%   |
| MacroSilicon                           | 3         | 0.27%   |
| Aveo Technology                        | 3         | 0.27%   |
| ALi                                    | 3         | 0.27%   |
| Trust                                  | 2         | 0.18%   |
| Primax Electronics                     | 2         | 0.18%   |
| Philips (or NXP)                       | 2         | 0.18%   |
| Jieli Technology                       | 2         | 0.18%   |
| DigiTech                               | 2         | 0.18%   |
| Y Media                                | 1         | 0.09%   |
| Xiaomi                                 | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 38        | 3.34%   |
| Chicony Integrated Camera                               | 36        | 3.17%   |
| IMC Networks Integrated Camera                          | 26        | 2.29%   |
| Chicony HD WebCam                                       | 24        | 2.11%   |
| Ricoh Visual Communication Camera VGP-VCC8 [R5U870]     | 22        | 1.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 19        | 1.67%   |
| Realtek USB Camera                                      | 18        | 1.58%   |
| Bison Integrated Camera                                 | 18        | 1.58%   |
| Microdia Integrated_Webcam_HD                           | 17        | 1.5%    |
| Chicony USB2.0 VGA UVC WebCam                           | 17        | 1.5%    |
| Chicony USB 2.0 Camera                                  | 16        | 1.41%   |
| Realtek EasyCamera                                      | 14        | 1.23%   |
| Chicony CNF9055 Toshiba Webcam                          | 13        | 1.14%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 12        | 1.06%   |
| Chicony TOSHIBA Web Camera - HD                         | 12        | 1.06%   |
| Syntek Integrated Camera                                | 11        | 0.97%   |
| Quanta HP Wide Vision HD Camera                         | 11        | 0.97%   |
| Chicony HP Truevision HD                                | 11        | 0.97%   |
| Realtek Integrated_Webcam_HD                            | 10        | 0.88%   |
| Microsoft LifeCam HD-3000                               | 10        | 0.88%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 10        | 0.88%   |
| Lite-On Integrated Camera                               | 10        | 0.88%   |
| IMC Networks HD Camera                                  | 10        | 0.88%   |
| Quanta HP TrueVision HD Camera                          | 9         | 0.79%   |
| Logitech Webcam C270                                    | 9         | 0.79%   |
| Bison HD Webcam                                         | 9         | 0.79%   |
| Apple Built-in iSight                                   | 9         | 0.79%   |
| Realtek HD WebCam                                       | 8         | 0.7%    |
| Chicony VGA Webcam                                      | 8         | 0.7%    |
| Chicony HP HD Camera                                    | 8         | 0.7%    |
| Sunplus Integrated_Webcam_HD                            | 7         | 0.62%   |
| Microdia Sonix USB 2.0 Camera                           | 7         | 0.62%   |
| IMC Networks ov9734_azurewave_camera                    | 7         | 0.62%   |
| HP Webcam HD 2300                                       | 7         | 0.62%   |
| Chicony HP Wide Vision HD Camera                        | 7         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 7         | 0.62%   |
| Apple iPhone 5/5C/5S/6/SE                               | 7         | 0.62%   |
| Syntek EasyCamera                                       | 6         | 0.53%   |
| Sunplus HD WebCam                                       | 6         | 0.53%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 6         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 61        | 35.47%  |
| Validity Sensors                   | 50        | 29.07%  |
| Shenzhen Goodix Technology         | 25        | 14.53%  |
| AuthenTec                          | 12        | 6.98%   |
| Elan Microelectronics              | 8         | 4.65%   |
| Upek                               | 6         | 3.49%   |
| LighTuning Technology              | 5         | 2.91%   |
| STMicroelectronics                 | 3         | 1.74%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 1.16%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 18        | 10.47%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 11        | 6.4%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 4.65%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 6         | 3.49%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.49%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 3.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 2.91%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.91%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 2.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.91%   |
| Synaptics UWP WBDI Device                                                  | 5         | 2.91%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 2.91%   |
| AuthenTec AES1600                                                          | 5         | 2.91%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 2.33%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.33%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.33%   |
| Synaptics UWP WBDI                                                         | 4         | 2.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.33%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 2.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.33%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.33%   |
| Elan ELAN:ARM-M4                                                           | 4         | 2.33%   |
| AuthenTec AES2810                                                          | 4         | 2.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.74%   |
| Synaptics WBDI Device                                                      | 3         | 1.74%   |
| Synaptics WBDI                                                             | 3         | 1.74%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.74%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.74%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.74%   |
| Validity Sensors VFS491                                                    | 2         | 1.16%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.16%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.16%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 2         | 1.16%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 1.16%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.16%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.16%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.16%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.58%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 30        | 32.97%  |
| Broadcom              | 22        | 24.18%  |
| Gemalto (was Gemplus) | 9         | 9.89%   |
| O2 Micro              | 6         | 6.59%   |
| Realtek Semiconductor | 4         | 4.4%    |
| Bit4id                | 4         | 4.4%    |
| Upek                  | 3         | 3.3%    |
| Lenovo                | 3         | 3.3%    |
| SCM Microsystems      | 2         | 2.2%    |
| Chicony Electronics   | 2         | 2.2%    |
| Advanced Card Systems | 2         | 2.2%    |
| Yubico.com            | 1         | 1.1%    |
| Hewlett-Packard       | 1         | 1.1%    |
| Feitian Technologies  | 1         | 1.1%    |
| Cherry                | 1         | 1.1%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 31.87%  |
| Broadcom 58200                                                               | 8         | 8.79%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 5.49%   |
| Broadcom 5880                                                                | 5         | 5.49%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 4.4%    |
| Bit4id miniLector EVO                                                        | 4         | 4.4%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 3.3%    |
| Lenovo Integrated Smart Card Reader                                          | 3         | 3.3%    |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 2.2%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 2.2%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 2.2%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 2.2%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 2.2%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.1%    |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.1%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 1.1%    |
| Feitian Technologies FIDO CCID KB                                            | 1         | 1.1%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.1%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1196      | 69.05%  |
| 1     | 422       | 24.36%  |
| 2     | 89        | 5.14%   |
| 3     | 19        | 1.1%    |
| 4     | 5         | 0.29%   |
| 5     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 190       | 29.28%  |
| Fingerprint reader       | 171       | 26.35%  |
| Net/wireless             | 72        | 11.09%  |
| Chipcard                 | 69        | 10.63%  |
| Multimedia controller    | 55        | 8.47%   |
| Camera                   | 20        | 3.08%   |
| Bluetooth                | 18        | 2.77%   |
| Card reader              | 12        | 1.85%   |
| Communication controller | 9         | 1.39%   |
| Storage                  | 7         | 1.08%   |
| Network                  | 5         | 0.77%   |
| Modem                    | 5         | 0.77%   |
| Net/ethernet             | 4         | 0.62%   |
| Flash memory             | 4         | 0.62%   |
| Sound                    | 3         | 0.46%   |
| Unassigned class         | 2         | 0.31%   |
| Dvb card                 | 2         | 0.31%   |
| Storage/ata              | 1         | 0.15%   |

