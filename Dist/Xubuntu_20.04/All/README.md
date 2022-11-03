Xubuntu 20.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Xubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Xubuntu_20.04/Desktop/README.md) and [notebooks](/Dist/Xubuntu_20.04/Notebook/README.md).

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

Total: 2763

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [428b353c2c](https://linux-hardware.org/?probe=428b353c2c) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | Desktop     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [32b9b29220](https://linux-hardware.org/?probe=32b9b29220) | Oct 31, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [caefae88bf](https://linux-hardware.org/?probe=caefae88bf) | Oct 30, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | Notebook    | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [fef5f08978](https://linux-hardware.org/?probe=fef5f08978) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| Dell          | Latitude E5270              | Notebook    | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| MSI           | GS40 6QE Phantom            | Notebook    | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Dell          | 0N36HY A09                  | Server      | [464fda30a8](https://linux-hardware.org/?probe=464fda30a8) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | Notebook    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | Notebook    | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | Notebook    | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| HP            | 255 G1                      | Notebook    | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [fc4e415fe4](https://linux-hardware.org/?probe=fc4e415fe4) | Oct 02, 2022 |
| Acer          | Aspire A315-55G             | Notebook    | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [1001ccbbaf](https://linux-hardware.org/?probe=1001ccbbaf) | Sep 30, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| Lenovo        | IdeaPad N585 20179          | Notebook    | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | Notebook    | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | Notebook    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| Dell          | Precision 7750              | Notebook    | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d852f09d43](https://linux-hardware.org/?probe=d852f09d43) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a0bdfffa04](https://linux-hardware.org/?probe=a0bdfffa04) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [196e6b048b](https://linux-hardware.org/?probe=196e6b048b) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [8e95a850da](https://linux-hardware.org/?probe=8e95a850da) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [499d354033](https://linux-hardware.org/?probe=499d354033) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [a830a7b6e5](https://linux-hardware.org/?probe=a830a7b6e5) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [19ba71f923](https://linux-hardware.org/?probe=19ba71f923) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ad888e4455](https://linux-hardware.org/?probe=ad888e4455) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [d35bf4c513](https://linux-hardware.org/?probe=d35bf4c513) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [dce51bb6d6](https://linux-hardware.org/?probe=dce51bb6d6) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [3bc232858d](https://linux-hardware.org/?probe=3bc232858d) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [ca79460771](https://linux-hardware.org/?probe=ca79460771) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [1e24243624](https://linux-hardware.org/?probe=1e24243624) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [b0625e01e3](https://linux-hardware.org/?probe=b0625e01e3) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [f97cd53683](https://linux-hardware.org/?probe=f97cd53683) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | Desktop     | [cd3fc03204](https://linux-hardware.org/?probe=cd3fc03204) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| HP            | 1000                        | Notebook    | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | Notebook    | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0R092H                      | Desktop     | [a22af2bad5](https://linux-hardware.org/?probe=a22af2bad5) | Sep 09, 2022 |
| ASRock        | Q1900-ITX                   | Desktop     | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| MSI           | MS-7387                     | Desktop     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| Dell          | Latitude 9520               | Notebook    | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| Dell          | 0NV0M7 A02                  | Desktop     | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | M4A78T-E                    | Desktop     | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [c3212ee5a3](https://linux-hardware.org/?probe=c3212ee5a3) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [673b33ac0c](https://linux-hardware.org/?probe=673b33ac0c) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [18a2d69632](https://linux-hardware.org/?probe=18a2d69632) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [965107cf86](https://linux-hardware.org/?probe=965107cf86) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [d8f5734dd8](https://linux-hardware.org/?probe=d8f5734dd8) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [b2f37a3080](https://linux-hardware.org/?probe=b2f37a3080) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [91857942dd](https://linux-hardware.org/?probe=91857942dd) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [940fb9c208](https://linux-hardware.org/?probe=940fb9c208) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [10315fa577](https://linux-hardware.org/?probe=10315fa577) | Sep 02, 2022 |
| ECS           | G31T-M9                     | Desktop     | [aedc37e8e4](https://linux-hardware.org/?probe=aedc37e8e4) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | Notebook    | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Medion        | H110H4-EM                   | Desktop     | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| DNI           | SNDTP-1513N 5508015890      | Desktop     | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Intel         | H61                         | Desktop     | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| HP            | 844C                        | Desktop     | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [38fd87d37c](https://linux-hardware.org/?probe=38fd87d37c) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | Notebook    | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | Notebook    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| MSI           | X370 KRAIT GAMING           | Desktop     | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| Packard Be... | EasyNote TJ66               | Notebook    | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| Dell          | 07T4MC A06                  | Desktop     | [d6c22de1e9](https://linux-hardware.org/?probe=d6c22de1e9) | Aug 18, 2022 |
| Dell          | 0RY007                      | Desktop     | [a863b6949c](https://linux-hardware.org/?probe=a863b6949c) | Aug 16, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| Dell          | 0RY007                      | Desktop     | [592206f3e1](https://linux-hardware.org/?probe=592206f3e1) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | Notebook    | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Dell          | 0RY007                      | Desktop     | [05edd2876d](https://linux-hardware.org/?probe=05edd2876d) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | Desktop     | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [4574011966](https://linux-hardware.org/?probe=4574011966) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | Desktop     | [8454f0f091](https://linux-hardware.org/?probe=8454f0f091) | Aug 09, 2022 |
| Dell          | System XPS L502X            | Notebook    | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [64b08b679f](https://linux-hardware.org/?probe=64b08b679f) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | Notebook    | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | Notebook    | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | Notebook    | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | Notebook    | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [7325fb8135](https://linux-hardware.org/?probe=7325fb8135) | Jul 30, 2022 |
| Intel         | SHARKBAY                    | Desktop     | [bd5b812271](https://linux-hardware.org/?probe=bd5b812271) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| ASUSTek       | P5QL/EPU                    | Desktop     | [797c3b1dc2](https://linux-hardware.org/?probe=797c3b1dc2) | Jul 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e2cd5c8d4b](https://linux-hardware.org/?probe=e2cd5c8d4b) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | Notebook    | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | Notebook    | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | Notebook    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | 1496                        | Desktop     | [7797b2d6dd](https://linux-hardware.org/?probe=7797b2d6dd) | Jul 14, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | Notebook    | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | Notebook    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| HP            | 158A                        | Desktop     | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | Notebook    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [d1aa8fe23d](https://linux-hardware.org/?probe=d1aa8fe23d) | Jul 05, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [5703355b59](https://linux-hardware.org/?probe=5703355b59) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | Notebook    | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [3633eb51d4](https://linux-hardware.org/?probe=3633eb51d4) | Jul 01, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [8f90bed577](https://linux-hardware.org/?probe=8f90bed577) | Jul 01, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [a55837dc17](https://linux-hardware.org/?probe=a55837dc17) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [87b9ce1db1](https://linux-hardware.org/?probe=87b9ce1db1) | Jun 28, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | Notebook    | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [4562c09862](https://linux-hardware.org/?probe=4562c09862) | Jun 24, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [8cf9d783a3](https://linux-hardware.org/?probe=8cf9d783a3) | Jun 23, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [515b063f08](https://linux-hardware.org/?probe=515b063f08) | Jun 18, 2022 |
| Intel         | NUC7i3BNB J22859-312        | Mini pc     | [89d99d840f](https://linux-hardware.org/?probe=89d99d840f) | Jun 17, 2022 |
| Lenovo        | ThinkCentre M71e 5033AR1    | Desktop     | [dd0f797f78](https://linux-hardware.org/?probe=dd0f797f78) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [f340c1d172](https://linux-hardware.org/?probe=f340c1d172) | Jun 17, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | Notebook    | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | Notebook    | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| Packard Be... | EasyNote TK11BZ             | Notebook    | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| GPU Compan... | GWTN116-3                   | Notebook    | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [7f48bb6a8a](https://linux-hardware.org/?probe=7f48bb6a8a) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [5eaef9db5a](https://linux-hardware.org/?probe=5eaef9db5a) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | Notebook    | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| Lenovo        | CRESCENTBAY SDK0E50510 W... | All in one  | [0ce0f27bac](https://linux-hardware.org/?probe=0ce0f27bac) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| ASRockRack    | ROMED8-2T                   | Desktop     | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| Unknown       | Unknown                     | Soc         | [0c5a37efd2](https://linux-hardware.org/?probe=0c5a37efd2) | Jun 05, 2022 |
| MSI           | PR601/VR603                 | Notebook    | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| HP            | 3397                        | Desktop     | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | Notebook    | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | Notebook    | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | Desktop     | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| Medion        | E15407                      | Notebook    | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | Notebook    | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| HP            | 2B29                        | Desktop     | [d2ab16d631](https://linux-hardware.org/?probe=d2ab16d631) | May 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [64aa376623](https://linux-hardware.org/?probe=64aa376623) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [d6adaef7cc](https://linux-hardware.org/?probe=d6adaef7cc) | May 28, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [c848e4649e](https://linux-hardware.org/?probe=c848e4649e) | May 28, 2022 |
| TUXEDO        | N14xWU                      | Notebook    | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| ASUSTek       | X510UA                      | Notebook    | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | Notebook    | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | Notebook    | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | Notebook    | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Acer          | Aspire G7750                | Desktop     | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| HP            | 158A                        | Desktop     | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | Notebook    | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| Dell          | Latitude 5580               | Notebook    | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| MSI           | AM1I                        | Desktop     | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | Notebook    | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| ECS           | Asterope                    | Desktop     | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| HP            | 82B4                        | Desktop     | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [cace04f39a](https://linux-hardware.org/?probe=cace04f39a) | May 12, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| AMI           | Cherry Trail CR             | Notebook    | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | Notebook    | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Gigabyte      | Z68A-D3-B3                  | Desktop     | [573e425cb6](https://linux-hardware.org/?probe=573e425cb6) | May 08, 2022 |
| HP            | Compaq 6820s                | Notebook    | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | Notebook    | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| HP            | 3397                        | Desktop     | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| HP            | 158A                        | Desktop     | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Razer         | Blade Stealth 13 Late 20... | Notebook    | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Unknown       | Intel X79                   | Desktop     | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Dell          | Inspiron 3135               | Notebook    | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Dell          | Latitude 7480               | Notebook    | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | Notebook    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | Notebook    | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Nvidia        | Tegra                       | Soc         | [36bbd53ec1](https://linux-hardware.org/?probe=36bbd53ec1) | Apr 23, 2022 |
| Gigabyte      | G33M-DS2R                   | Desktop     | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5a662b428e](https://linux-hardware.org/?probe=5a662b428e) | Apr 21, 2022 |
| Hardkernel    | ODROID-M1                   | Soc         | [481e87aa23](https://linux-hardware.org/?probe=481e87aa23) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| HP            | 18E5                        | Desktop     | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | Desktop     | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| HP            | Compaq 6730s                | Notebook    | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [521cf503e2](https://linux-hardware.org/?probe=521cf503e2) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | 21B4 A01                    | Desktop     | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| HP            | Compaq 6730s                | Notebook    | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | Notebook    | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | Notebook    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | Notebook    | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | Notebook    | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [0123ade8f7](https://linux-hardware.org/?probe=0123ade8f7) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [6280e20fbe](https://linux-hardware.org/?probe=6280e20fbe) | Apr 11, 2022 |
| Acer          | Nitro N50-610               | Desktop     | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | Desktop     | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | Desktop     | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Toshiba       | NB505                       | Notebook    | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | Notebook    | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Dell          | Latitude 5521               | Notebook    | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | Notebook    | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| Dell          | 0GY6Y8 A03                  | Desktop     | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [c081f43e18](https://linux-hardware.org/?probe=c081f43e18) | Apr 05, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| MSI           | GX70 3CC                    | Notebook    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | 18E5                        | Desktop     | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| Dell          | 0WM839 A00                  | All in one  | [b5edf6760d](https://linux-hardware.org/?probe=b5edf6760d) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| Dell          | OptiPlex 760                | Desktop     | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| Medion        | Crawler E25                 | Notebook    | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Dell          | Studio 1450                 | Notebook    | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| HP            | 21B4 A01                    | Desktop     | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | Notebook    | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Lenovo        | 36FD SDK0J40709 WIN 3259... | All in one  | [75410d5871](https://linux-hardware.org/?probe=75410d5871) | Mar 27, 2022 |
| Toshiba       | NB505                       | Notebook    | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| Pegatron      | Benicia                     | Desktop     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | Notebook    | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | Desktop     | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | Desktop     | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| ASUSTek       | X501A                       | Notebook    | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | Notebook    | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | Notebook    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| ECS           | H87H3-M                     | Desktop     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | Notebook    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | Notebook    | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| Samsung       | R530/R730/R540              | Notebook    | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | Notebook    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| Dell          | Inspiron 7437               | Notebook    | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Acer          | Aspire X1920                | Desktop     | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| Dell          | 0RW199                      | Desktop     | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | Notebook    | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | Notebook    | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Fujitsu       | LIFEBOOK T939               | Convertible | [aa341bdff4](https://linux-hardware.org/?probe=aa341bdff4) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | Notebook    | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | Notebook    | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| VIT           | P3400                       | Notebook    | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | Notebook    | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | Notebook    | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| LG Electro... | 22V240 FAB3                 | All in one  | [23b20c26f2](https://linux-hardware.org/?probe=23b20c26f2) | Feb 24, 2022 |
| Acer          | TPDS05 R3700                | Desktop     | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| MSI           | G41M-P25                    | Desktop     | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | Desktop     | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| Dell          | Vostro V130                 | Notebook    | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| ASRock        | K10N78M                     | Desktop     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| Dell          | Precision 3561              | Notebook    | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | Notebook    | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| MSI           | A55M-P33                    | Desktop     | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| Gateway       | M-6307                      | Notebook    | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | Notebook    | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [4cb6628353](https://linux-hardware.org/?probe=4cb6628353) | Feb 14, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [43ac6b6d18](https://linux-hardware.org/?probe=43ac6b6d18) | Feb 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6f11ea4988](https://linux-hardware.org/?probe=6f11ea4988) | Feb 14, 2022 |
| Sony          | VPCEB3E1E                   | Notebook    | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| HP            | 3031h                       | Desktop     | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| HP            | ProBook 650 G3              | Notebook    | [54a5c321be](https://linux-hardware.org/?probe=54a5c321be) | Feb 08, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| Unknown       | Intel X79                   | Desktop     | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [1feae56050](https://linux-hardware.org/?probe=1feae56050) | Feb 06, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | Notebook    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| HP            | EliteBook 8530p             | Notebook    | [a2fc96b3dc](https://linux-hardware.org/?probe=a2fc96b3dc) | Feb 05, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [e4b5396bf7](https://linux-hardware.org/?probe=e4b5396bf7) | Feb 04, 2022 |
| HP            | Pavilion 17                 | Notebook    | [f0d4a99870](https://linux-hardware.org/?probe=f0d4a99870) | Feb 04, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | Notebook    | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| Dell          | 0XCR8D A01                  | Desktop     | [a68034b1e8](https://linux-hardware.org/?probe=a68034b1e8) | Feb 03, 2022 |
| HP            | 872E                        | Mini pc     | [8366a84cdb](https://linux-hardware.org/?probe=8366a84cdb) | Feb 02, 2022 |
| HP            | 872E                        | Mini pc     | [533e06f8ac](https://linux-hardware.org/?probe=533e06f8ac) | Feb 02, 2022 |
| Dell          | 051FJ8 A00                  | Desktop     | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [172fc399f5](https://linux-hardware.org/?probe=172fc399f5) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [bba0be98c7](https://linux-hardware.org/?probe=bba0be98c7) | Feb 01, 2022 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | Desktop     | [27b9e98a16](https://linux-hardware.org/?probe=27b9e98a16) | Feb 01, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [20e43b8b53](https://linux-hardware.org/?probe=20e43b8b53) | Jan 29, 2022 |
| Dell          | Studio 1450                 | Notebook    | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| ASRock        | M3A UCC                     | Desktop     | [8ca7699b4c](https://linux-hardware.org/?probe=8ca7699b4c) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | Notebook    | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| Pegatron      | Benicia                     | Desktop     | [8d1af3f3af](https://linux-hardware.org/?probe=8d1af3f3af) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [321264426f](https://linux-hardware.org/?probe=321264426f) | Jan 26, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| Unknown       | Unknown                     | Desktop     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| HP            | G42                         | Notebook    | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | Notebook    | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e0197893fc](https://linux-hardware.org/?probe=e0197893fc) | Jan 24, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [b7fb25920a](https://linux-hardware.org/?probe=b7fb25920a) | Jan 23, 2022 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [77545529dc](https://linux-hardware.org/?probe=77545529dc) | Jan 21, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Lenovo        | B590 37612MG                | Notebook    | [cc8d1271b0](https://linux-hardware.org/?probe=cc8d1271b0) | Jan 21, 2022 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [6906b181eb](https://linux-hardware.org/?probe=6906b181eb) | Jan 20, 2022 |
| Dell          | Latitude E6330              | Notebook    | [c7b076f945](https://linux-hardware.org/?probe=c7b076f945) | Jan 20, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b6de24e7df](https://linux-hardware.org/?probe=b6de24e7df) | Jan 20, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [452df44e84](https://linux-hardware.org/?probe=452df44e84) | Jan 20, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | Desktop     | [44b718700d](https://linux-hardware.org/?probe=44b718700d) | Jan 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [262dcaf21e](https://linux-hardware.org/?probe=262dcaf21e) | Jan 18, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [5187874180](https://linux-hardware.org/?probe=5187874180) | Jan 18, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c1f8df4bbd](https://linux-hardware.org/?probe=c1f8df4bbd) | Jan 18, 2022 |
| Dell          | Latitude D630               | Notebook    | [6327eec09e](https://linux-hardware.org/?probe=6327eec09e) | Jan 18, 2022 |
| Gigabyte      | MZBSWBP-00                  | Desktop     | [a8699a0a00](https://linux-hardware.org/?probe=a8699a0a00) | Jan 18, 2022 |
| Lenovo        | ThinkPad W520 42844MG       | Notebook    | [cf460c52bb](https://linux-hardware.org/?probe=cf460c52bb) | Jan 16, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [2afe3ef5cc](https://linux-hardware.org/?probe=2afe3ef5cc) | Jan 16, 2022 |
| Lenovo        | ThinkPad X260 20F5S22K0Z    | Notebook    | [e83aec04ca](https://linux-hardware.org/?probe=e83aec04ca) | Jan 16, 2022 |
| Dell          | 0PP150 A00                  | Desktop     | [554774c3c8](https://linux-hardware.org/?probe=554774c3c8) | Jan 16, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [d735255913](https://linux-hardware.org/?probe=d735255913) | Jan 15, 2022 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [368d168909](https://linux-hardware.org/?probe=368d168909) | Jan 15, 2022 |
| Insyde        | Braswell                    | Notebook    | [a5bca1e5e8](https://linux-hardware.org/?probe=a5bca1e5e8) | Jan 14, 2022 |
| Dell          | Latitude 5480               | Notebook    | [d95c781c2e](https://linux-hardware.org/?probe=d95c781c2e) | Jan 14, 2022 |
| Dell          | Latitude 5480               | Notebook    | [d58108295c](https://linux-hardware.org/?probe=d58108295c) | Jan 14, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | Desktop     | [78902354bb](https://linux-hardware.org/?probe=78902354bb) | Jan 14, 2022 |
| HP            | 829A                        | Mini pc     | [9526ea61c6](https://linux-hardware.org/?probe=9526ea61c6) | Jan 13, 2022 |
| ASUSTek       | M4A78L-M                    | Desktop     | [dfb87ada40](https://linux-hardware.org/?probe=dfb87ada40) | Jan 13, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [6892ab87e1](https://linux-hardware.org/?probe=6892ab87e1) | Jan 13, 2022 |
| Medion        | Akoya THE TOUCH 10          | Notebook    | [7606a573d6](https://linux-hardware.org/?probe=7606a573d6) | Jan 12, 2022 |
| Lenovo        | IdeaPad S415 Touch 20319    | Notebook    | [d59706fc52](https://linux-hardware.org/?probe=d59706fc52) | Jan 11, 2022 |
| HP            | 3031h                       | Desktop     | [46b02ff904](https://linux-hardware.org/?probe=46b02ff904) | Jan 11, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [b01004055c](https://linux-hardware.org/?probe=b01004055c) | Jan 11, 2022 |
| MOTION        | KEX00                       | Notebook    | [8e36590e72](https://linux-hardware.org/?probe=8e36590e72) | Jan 10, 2022 |
| HP            | 3031h                       | Desktop     | [2e78e6c7f8](https://linux-hardware.org/?probe=2e78e6c7f8) | Jan 10, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | Notebook    | [bbcda99dab](https://linux-hardware.org/?probe=bbcda99dab) | Jan 10, 2022 |
| Alienware     | m15 R3                      | Notebook    | [8cff8c6d3f](https://linux-hardware.org/?probe=8cff8c6d3f) | Jan 09, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [7f20d8ac9a](https://linux-hardware.org/?probe=7f20d8ac9a) | Jan 09, 2022 |
| Acer          | Extensa 5620                | Notebook    | [41a1c7001c](https://linux-hardware.org/?probe=41a1c7001c) | Jan 08, 2022 |
| MSI           | H61M-P23                    | Desktop     | [14690b4128](https://linux-hardware.org/?probe=14690b4128) | Jan 08, 2022 |
| Sony          | SVF15A190X                  | Notebook    | [6d729a76af](https://linux-hardware.org/?probe=6d729a76af) | Jan 08, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | 073MMW A03                  | Desktop     | [65c164f304](https://linux-hardware.org/?probe=65c164f304) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | Desktop     | [ef69bbfd12](https://linux-hardware.org/?probe=ef69bbfd12) | Jan 07, 2022 |
| Dell          | Latitude E6500              | Notebook    | [8355df56a3](https://linux-hardware.org/?probe=8355df56a3) | Jan 07, 2022 |
| Gateway       | NV53A                       | Notebook    | [2e67e3a86e](https://linux-hardware.org/?probe=2e67e3a86e) | Jan 05, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a7f4591b40](https://linux-hardware.org/?probe=a7f4591b40) | Jan 05, 2022 |
| HP            | 0AA8h                       | Desktop     | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [aefb321446](https://linux-hardware.org/?probe=aefb321446) | Jan 04, 2022 |
| HP            | 0AA8h                       | Desktop     | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Intel         | DP35DP AAD81073-209         | Desktop     | [f6ec40d0f8](https://linux-hardware.org/?probe=f6ec40d0f8) | Jan 01, 2022 |
| Packard Be... | EasyNote TK87               | Notebook    | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [127df37eab](https://linux-hardware.org/?probe=127df37eab) | Jan 01, 2022 |
| HP            | G60                         | Notebook    | [08350a2b75](https://linux-hardware.org/?probe=08350a2b75) | Jan 01, 2022 |
| Dell          | Inspiron N5030              | Notebook    | [fc6d58d758](https://linux-hardware.org/?probe=fc6d58d758) | Jan 01, 2022 |
| Dell          | Inspiron 5765               | Notebook    | [c3a91857b3](https://linux-hardware.org/?probe=c3a91857b3) | Jan 01, 2022 |
| ASUSTek       | P5K-E                       | Desktop     | [f1c3532217](https://linux-hardware.org/?probe=f1c3532217) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | Notebook    | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| ECS           | G41T-M2                     | Desktop     | [6b4159a357](https://linux-hardware.org/?probe=6b4159a357) | Dec 29, 2021 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [2ab97853e3](https://linux-hardware.org/?probe=2ab97853e3) | Dec 29, 2021 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [bc14137c9c](https://linux-hardware.org/?probe=bc14137c9c) | Dec 29, 2021 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [596bdeff81](https://linux-hardware.org/?probe=596bdeff81) | Dec 27, 2021 |
| HP            | EliteBook 8440p (VD484AV... | Notebook    | [ba4cf422e7](https://linux-hardware.org/?probe=ba4cf422e7) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| Toshiba       | Satellite C50-A-19U         | Notebook    | [6a61931dde](https://linux-hardware.org/?probe=6a61931dde) | Dec 26, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [00c1f1b6df](https://linux-hardware.org/?probe=00c1f1b6df) | Dec 26, 2021 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| ASRock        | A75M-ITX                    | Desktop     | [1070ea74d9](https://linux-hardware.org/?probe=1070ea74d9) | Dec 25, 2021 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [a14e38d07e](https://linux-hardware.org/?probe=a14e38d07e) | Dec 24, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [2ef30c62b5](https://linux-hardware.org/?probe=2ef30c62b5) | Dec 24, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [6eec25d058](https://linux-hardware.org/?probe=6eec25d058) | Dec 24, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [602d3e0afd](https://linux-hardware.org/?probe=602d3e0afd) | Dec 23, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3b47550de1](https://linux-hardware.org/?probe=3b47550de1) | Dec 23, 2021 |
| HP            | 3398                        | Desktop     | [759e3821b8](https://linux-hardware.org/?probe=759e3821b8) | Dec 22, 2021 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [c26a2c5c03](https://linux-hardware.org/?probe=c26a2c5c03) | Dec 22, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [123bdbfa71](https://linux-hardware.org/?probe=123bdbfa71) | Dec 22, 2021 |
| Google        | Nami                        | Notebook    | [045f17f15d](https://linux-hardware.org/?probe=045f17f15d) | Dec 22, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [d29b59a855](https://linux-hardware.org/?probe=d29b59a855) | Dec 21, 2021 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [22f2f5c84b](https://linux-hardware.org/?probe=22f2f5c84b) | Dec 21, 2021 |
| HP            | 18E7                        | Desktop     | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [32340d057e](https://linux-hardware.org/?probe=32340d057e) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [8986819d3f](https://linux-hardware.org/?probe=8986819d3f) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a94bf3ef84](https://linux-hardware.org/?probe=a94bf3ef84) | Dec 19, 2021 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [e3c5530718](https://linux-hardware.org/?probe=e3c5530718) | Dec 19, 2021 |
| Dell          | 0VD5HY A04                  | Desktop     | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| ASUSTek       | P5GC-MX                     | Desktop     | [499a024e97](https://linux-hardware.org/?probe=499a024e97) | Dec 18, 2021 |
| ASUSTek       | E200HA                      | Notebook    | [bcd4913896](https://linux-hardware.org/?probe=bcd4913896) | Dec 17, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [7c3c9b5cdd](https://linux-hardware.org/?probe=7c3c9b5cdd) | Dec 17, 2021 |
| Dell          | System XPS L502X            | Notebook    | [4588c107ed](https://linux-hardware.org/?probe=4588c107ed) | Dec 16, 2021 |
| Biostar       | H110MHC                     | Desktop     | [bb74f304fd](https://linux-hardware.org/?probe=bb74f304fd) | Dec 16, 2021 |
| Packard Be... | EasyNote TK13BZ             | Notebook    | [e08d4e940c](https://linux-hardware.org/?probe=e08d4e940c) | Dec 15, 2021 |
| Toshiba       | Satellite A105              | Notebook    | [4bddc587d8](https://linux-hardware.org/?probe=4bddc587d8) | Dec 15, 2021 |
| MSI           | MS-B0501 100                | Desktop     | [ca4048db98](https://linux-hardware.org/?probe=ca4048db98) | Dec 14, 2021 |
| Gigabyte      | EX58-UD4P                   | Desktop     | [aa8da2e23c](https://linux-hardware.org/?probe=aa8da2e23c) | Dec 14, 2021 |
| Gateway       | NV53A                       | Notebook    | [1912b6b8c5](https://linux-hardware.org/?probe=1912b6b8c5) | Dec 14, 2021 |
| ASUSTek       | X55U                        | Notebook    | [6260fe5ca9](https://linux-hardware.org/?probe=6260fe5ca9) | Dec 13, 2021 |
| Dell          | 0T656F A02                  | Desktop     | [c6fcad51e9](https://linux-hardware.org/?probe=c6fcad51e9) | Dec 13, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Dell          | 073MMW A00                  | Desktop     | [c5c064c84f](https://linux-hardware.org/?probe=c5c064c84f) | Dec 13, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [1617abd2f4](https://linux-hardware.org/?probe=1617abd2f4) | Dec 12, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [1f799f28c2](https://linux-hardware.org/?probe=1f799f28c2) | Dec 12, 2021 |
| Dell          | Inspiron 13-5378            | Notebook    | [22b04adc28](https://linux-hardware.org/?probe=22b04adc28) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [11ff47f723](https://linux-hardware.org/?probe=11ff47f723) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [0dd637c0b8](https://linux-hardware.org/?probe=0dd637c0b8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [1b7f8b1fb9](https://linux-hardware.org/?probe=1b7f8b1fb9) | Dec 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [8684f34a9e](https://linux-hardware.org/?probe=8684f34a9e) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [204f77ca68](https://linux-hardware.org/?probe=204f77ca68) | Dec 10, 2021 |
| Lenovo        | ThinkPad T61 64669YG        | Notebook    | [f0c57ccd03](https://linux-hardware.org/?probe=f0c57ccd03) | Dec 10, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [c505dc1521](https://linux-hardware.org/?probe=c505dc1521) | Dec 09, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [a4f61b0f15](https://linux-hardware.org/?probe=a4f61b0f15) | Dec 09, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [2c5d450c67](https://linux-hardware.org/?probe=2c5d450c67) | Dec 08, 2021 |
| Acer          | Veriton E430 v1.0           | Desktop     | [5c857f1bb6](https://linux-hardware.org/?probe=5c857f1bb6) | Dec 08, 2021 |
| ECS           | Nettle2                     | Desktop     | [bb67b27e67](https://linux-hardware.org/?probe=bb67b27e67) | Dec 07, 2021 |
| Dell          | 01W26N A00                  | Desktop     | [7c3e61ec94](https://linux-hardware.org/?probe=7c3e61ec94) | Dec 06, 2021 |
| Acer          | Aspire 5336                 | Notebook    | [ce9d41eb2f](https://linux-hardware.org/?probe=ce9d41eb2f) | Dec 06, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [b4382c3b38](https://linux-hardware.org/?probe=b4382c3b38) | Dec 04, 2021 |
| Gigabyte      | EP35-DS4                    | Desktop     | [570104ad1e](https://linux-hardware.org/?probe=570104ad1e) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [bc211e09fd](https://linux-hardware.org/?probe=bc211e09fd) | Dec 04, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2e34a3a698](https://linux-hardware.org/?probe=2e34a3a698) | Dec 04, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [9f1502866b](https://linux-hardware.org/?probe=9f1502866b) | Dec 03, 2021 |
| Dixonsxp      | Unknown                     | Notebook    | [093fef7eaa](https://linux-hardware.org/?probe=093fef7eaa) | Dec 03, 2021 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [674712f2a1](https://linux-hardware.org/?probe=674712f2a1) | Dec 03, 2021 |
| Toshiba       | Satellite L870-196          | Notebook    | [15ed850b16](https://linux-hardware.org/?probe=15ed850b16) | Dec 02, 2021 |
| Medion        | H81M-P33                    | Desktop     | [29b3a27675](https://linux-hardware.org/?probe=29b3a27675) | Dec 02, 2021 |
| Dell          | Latitude 5401               | Notebook    | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| HP            | 2000                        | Notebook    | [f16b490828](https://linux-hardware.org/?probe=f16b490828) | Dec 01, 2021 |
| HP            | 0AA4h                       | Desktop     | [f7438f59ac](https://linux-hardware.org/?probe=f7438f59ac) | Dec 01, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [90453b887a](https://linux-hardware.org/?probe=90453b887a) | Dec 01, 2021 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [190d1b6a29](https://linux-hardware.org/?probe=190d1b6a29) | Dec 01, 2021 |
| ASUSTek       | E203NAS                     | Notebook    | [c400f4df81](https://linux-hardware.org/?probe=c400f4df81) | Nov 30, 2021 |
| Shuttle       | NC03U                       | Desktop     | [2453ada3ba](https://linux-hardware.org/?probe=2453ada3ba) | Nov 30, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [6d6caad964](https://linux-hardware.org/?probe=6d6caad964) | Nov 29, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [29e9d64420](https://linux-hardware.org/?probe=29e9d64420) | Nov 29, 2021 |
| ASUSTek       | P7P55D                      | Desktop     | [85f288d39b](https://linux-hardware.org/?probe=85f288d39b) | Nov 29, 2021 |
| Samsung       | R530/R730/P590              | Notebook    | [0bbf67316b](https://linux-hardware.org/?probe=0bbf67316b) | Nov 28, 2021 |
| Acer          | EG43LMK                     | Desktop     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| Acer          | Swift SF114-34              | Notebook    | [d0170808b3](https://linux-hardware.org/?probe=d0170808b3) | Nov 27, 2021 |
| HP            | 0AA8h                       | Desktop     | [1d80d6636e](https://linux-hardware.org/?probe=1d80d6636e) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [71d58a102c](https://linux-hardware.org/?probe=71d58a102c) | Nov 26, 2021 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [d9b3bd7851](https://linux-hardware.org/?probe=d9b3bd7851) | Nov 26, 2021 |
| Lenovo        | IdeaPad Y570 0862           | Notebook    | [c795d5132c](https://linux-hardware.org/?probe=c795d5132c) | Nov 26, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [8b1485f27d](https://linux-hardware.org/?probe=8b1485f27d) | Nov 25, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [311cb04cc5](https://linux-hardware.org/?probe=311cb04cc5) | Nov 25, 2021 |
| HP            | Pavilion 17                 | Notebook    | [43944b4f78](https://linux-hardware.org/?probe=43944b4f78) | Nov 24, 2021 |
| HP            | Pavilion dv9700             | Notebook    | [5a583ec569](https://linux-hardware.org/?probe=5a583ec569) | Nov 24, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [76361c26c6](https://linux-hardware.org/?probe=76361c26c6) | Nov 24, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d61128f6f4](https://linux-hardware.org/?probe=d61128f6f4) | Nov 24, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [fe8ad04ad3](https://linux-hardware.org/?probe=fe8ad04ad3) | Nov 23, 2021 |
| TrekStor      | Primetab T13B               | Tablet      | [19b9435dff](https://linux-hardware.org/?probe=19b9435dff) | Nov 23, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [39d84bdde8](https://linux-hardware.org/?probe=39d84bdde8) | Nov 22, 2021 |
| Alienware     | M17x                        | Notebook    | [13acf7a3f9](https://linux-hardware.org/?probe=13acf7a3f9) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | Notebook    | [65a59cf71c](https://linux-hardware.org/?probe=65a59cf71c) | Nov 22, 2021 |
| Lenovo        | Edge 15 80K9                | Notebook    | [55d87b9d59](https://linux-hardware.org/?probe=55d87b9d59) | Nov 22, 2021 |
| ASUSTek       | M3N78-EM                    | Desktop     | [b358f07f1d](https://linux-hardware.org/?probe=b358f07f1d) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| ASUSTek       | M3N78-EM                    | Desktop     | [930c018424](https://linux-hardware.org/?probe=930c018424) | Nov 20, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [53462f848a](https://linux-hardware.org/?probe=53462f848a) | Nov 20, 2021 |
| Dell          | 014GRG A02                  | Desktop     | [c23455dd49](https://linux-hardware.org/?probe=c23455dd49) | Nov 20, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [b75a64f96a](https://linux-hardware.org/?probe=b75a64f96a) | Nov 19, 2021 |
| ASUSTek       | B150-PLUS                   | Desktop     | [3c4c353831](https://linux-hardware.org/?probe=3c4c353831) | Nov 19, 2021 |
| Lenovo        | ThinkPad T61 766511G        | Notebook    | [e1c74cc580](https://linux-hardware.org/?probe=e1c74cc580) | Nov 19, 2021 |
| HP            | ProBook 650 G3              | Notebook    | [def83e3614](https://linux-hardware.org/?probe=def83e3614) | Nov 19, 2021 |
| MSI           | 3666h                       | Desktop     | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| MSI           | GT75VR 7RE                  | Notebook    | [02a0e2b5c8](https://linux-hardware.org/?probe=02a0e2b5c8) | Nov 19, 2021 |
| ONE-NETBOO... | A1                          | Notebook    | [aff2f60770](https://linux-hardware.org/?probe=aff2f60770) | Nov 19, 2021 |
| ASRock        | Z97 Extreme4                | Desktop     | [fc86b0fc2e](https://linux-hardware.org/?probe=fc86b0fc2e) | Nov 18, 2021 |
| MSI           | 3666h                       | Desktop     | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| ASUSTek       | P5LD2-VM                    | Desktop     | [befbf7345c](https://linux-hardware.org/?probe=befbf7345c) | Nov 17, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [dfba89a8f0](https://linux-hardware.org/?probe=dfba89a8f0) | Nov 17, 2021 |
| HP            | 0AA8h                       | Desktop     | [5cd5f5de04](https://linux-hardware.org/?probe=5cd5f5de04) | Nov 16, 2021 |
| ASRock        | H470 Phantom Gaming 4       | Desktop     | [07ef26c830](https://linux-hardware.org/?probe=07ef26c830) | Nov 16, 2021 |
| Dell          | Latitude 7370               | Notebook    | [b43fadb11c](https://linux-hardware.org/?probe=b43fadb11c) | Nov 16, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [343fdf2e23](https://linux-hardware.org/?probe=343fdf2e23) | Nov 16, 2021 |
| Apple         | Mac-F2218EC8                | All in one  | [93af642a5d](https://linux-hardware.org/?probe=93af642a5d) | Nov 15, 2021 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [dad15363d9](https://linux-hardware.org/?probe=dad15363d9) | Nov 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [ea402fa75e](https://linux-hardware.org/?probe=ea402fa75e) | Nov 14, 2021 |
| Dell          | Latitude E6430              | Notebook    | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | Desktop     | [a8398f9036](https://linux-hardware.org/?probe=a8398f9036) | Nov 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [78651b05bb](https://linux-hardware.org/?probe=78651b05bb) | Nov 13, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [746f0808f4](https://linux-hardware.org/?probe=746f0808f4) | Nov 12, 2021 |
| Dell          | G15 5510                    | Notebook    | [178497a15b](https://linux-hardware.org/?probe=178497a15b) | Nov 12, 2021 |
| Lenovo        | 3734 SDK0L77769 WIN 3423... | All in one  | [51d1a5ac24](https://linux-hardware.org/?probe=51d1a5ac24) | Nov 12, 2021 |
| ASUSTek       | X501A                       | Notebook    | [f1eb057027](https://linux-hardware.org/?probe=f1eb057027) | Nov 11, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [269b146e10](https://linux-hardware.org/?probe=269b146e10) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | Desktop     | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [3e94ac7df1](https://linux-hardware.org/?probe=3e94ac7df1) | Nov 09, 2021 |
| Lenovo        | ThinkPad T410 2537MT3       | Notebook    | [76965c829b](https://linux-hardware.org/?probe=76965c829b) | Nov 09, 2021 |
| Medion        | H110H4-EM                   | Desktop     | [3ecf7775d6](https://linux-hardware.org/?probe=3ecf7775d6) | Nov 09, 2021 |
| Sony          | VPCF13M1E                   | Notebook    | [9858905cc2](https://linux-hardware.org/?probe=9858905cc2) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [9456930b53](https://linux-hardware.org/?probe=9456930b53) | Nov 08, 2021 |
| ASUSTek       | ROG Strix G531GT_GL531GT    | Notebook    | [685c3c0f3f](https://linux-hardware.org/?probe=685c3c0f3f) | Nov 08, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f40b389872](https://linux-hardware.org/?probe=f40b389872) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [d7a0b05df7](https://linux-hardware.org/?probe=d7a0b05df7) | Nov 07, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [425b956614](https://linux-hardware.org/?probe=425b956614) | Nov 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [cd1647c038](https://linux-hardware.org/?probe=cd1647c038) | Nov 07, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [53cfd83c43](https://linux-hardware.org/?probe=53cfd83c43) | Nov 07, 2021 |
| System76      | Oryx Pro                    | Notebook    | [39d1d14e62](https://linux-hardware.org/?probe=39d1d14e62) | Nov 07, 2021 |
| HP            | Pavilion g6                 | Notebook    | [ed14748445](https://linux-hardware.org/?probe=ed14748445) | Nov 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b4c93f107b](https://linux-hardware.org/?probe=b4c93f107b) | Nov 07, 2021 |
| NCR           | Pocono BIOS.3.1             | Desktop     | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| Dell          | G3 3500                     | Notebook    | [acc14d7efc](https://linux-hardware.org/?probe=acc14d7efc) | Nov 07, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d864187bdc](https://linux-hardware.org/?probe=d864187bdc) | Nov 06, 2021 |
| Dell          | Precision M4600             | Notebook    | [acd5115099](https://linux-hardware.org/?probe=acd5115099) | Nov 06, 2021 |
| MSI           | GL63 8RC                    | Notebook    | [068ed7518b](https://linux-hardware.org/?probe=068ed7518b) | Nov 06, 2021 |
| Dell          | G3 3500                     | Notebook    | [ea3cdd3cc4](https://linux-hardware.org/?probe=ea3cdd3cc4) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [617d2f5444](https://linux-hardware.org/?probe=617d2f5444) | Nov 06, 2021 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [305cca4bc8](https://linux-hardware.org/?probe=305cca4bc8) | Nov 06, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0c1490178d](https://linux-hardware.org/?probe=0c1490178d) | Nov 06, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [d7fe8595a3](https://linux-hardware.org/?probe=d7fe8595a3) | Nov 05, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [9d85113feb](https://linux-hardware.org/?probe=9d85113feb) | Nov 05, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f8c0647646](https://linux-hardware.org/?probe=f8c0647646) | Nov 05, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [8859c97474](https://linux-hardware.org/?probe=8859c97474) | Nov 05, 2021 |
| Toshiba       | Satellite P745              | Notebook    | [59b3468fb9](https://linux-hardware.org/?probe=59b3468fb9) | Nov 04, 2021 |
| HP            | ProBook 6450b               | Notebook    | [603fac0b2e](https://linux-hardware.org/?probe=603fac0b2e) | Nov 04, 2021 |
| Dell          | Latitude D630               | Notebook    | [f212896c99](https://linux-hardware.org/?probe=f212896c99) | Nov 04, 2021 |
| Dell          | Precision M4600             | Notebook    | [155f9ec4f4](https://linux-hardware.org/?probe=155f9ec4f4) | Nov 04, 2021 |
| Medion        | MS-7366                     | Desktop     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| Toshiba       | Satellite C70D-B            | Notebook    | [9fd353eaff](https://linux-hardware.org/?probe=9fd353eaff) | Nov 04, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [fa6b87b50d](https://linux-hardware.org/?probe=fa6b87b50d) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [070b533b05](https://linux-hardware.org/?probe=070b533b05) | Nov 02, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [86dd6331fc](https://linux-hardware.org/?probe=86dd6331fc) | Nov 02, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [29af280c0e](https://linux-hardware.org/?probe=29af280c0e) | Nov 01, 2021 |
| ASUSTek       | P2540UA                     | Notebook    | [f10ce209c4](https://linux-hardware.org/?probe=f10ce209c4) | Nov 01, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [22b5b29b32](https://linux-hardware.org/?probe=22b5b29b32) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [c1965ee087](https://linux-hardware.org/?probe=c1965ee087) | Nov 01, 2021 |
| MSI           | GL63 8RC                    | Notebook    | [ad6c3506c1](https://linux-hardware.org/?probe=ad6c3506c1) | Nov 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [22728e37fe](https://linux-hardware.org/?probe=22728e37fe) | Oct 31, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [68a5bdc18a](https://linux-hardware.org/?probe=68a5bdc18a) | Oct 31, 2021 |
| Dell          | Precision M4600             | Notebook    | [f442df91a1](https://linux-hardware.org/?probe=f442df91a1) | Oct 31, 2021 |
| Khadas        | VIM3                        | Soc         | [14bc5c234d](https://linux-hardware.org/?probe=14bc5c234d) | Oct 30, 2021 |
| VIT           | P3400                       | Notebook    | [58cc91aba3](https://linux-hardware.org/?probe=58cc91aba3) | Oct 30, 2021 |
| Acer          | Aspire X3990                | Desktop     | [967427d98c](https://linux-hardware.org/?probe=967427d98c) | Oct 29, 2021 |
| Acer          | Aspire X3990                | Desktop     | [7ccc4b3004](https://linux-hardware.org/?probe=7ccc4b3004) | Oct 29, 2021 |
| sunxi         | Libre Computer Board ALL... | Soc         | [8f5ad2889e](https://linux-hardware.org/?probe=8f5ad2889e) | Oct 29, 2021 |
| HP            | 8433 11                     | Desktop     | [6183f8775b](https://linux-hardware.org/?probe=6183f8775b) | Oct 29, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [48434e75fb](https://linux-hardware.org/?probe=48434e75fb) | Oct 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [13addb7994](https://linux-hardware.org/?probe=13addb7994) | Oct 28, 2021 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [5ce9661292](https://linux-hardware.org/?probe=5ce9661292) | Oct 28, 2021 |
| HP            | Compaq 6730s                | Notebook    | [8bc4483616](https://linux-hardware.org/?probe=8bc4483616) | Oct 27, 2021 |
| Khadas        | VIM3                        | Soc         | [ef5d046e03](https://linux-hardware.org/?probe=ef5d046e03) | Oct 27, 2021 |
| HP            | Pavilion g4                 | Notebook    | [90f6743fbd](https://linux-hardware.org/?probe=90f6743fbd) | Oct 27, 2021 |
| ASUSTek       | X501A                       | Notebook    | [2e47dd4121](https://linux-hardware.org/?probe=2e47dd4121) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [2c2443341f](https://linux-hardware.org/?probe=2c2443341f) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [16306ffb37](https://linux-hardware.org/?probe=16306ffb37) | Oct 25, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| Toshiba       | Satellite L850              | Notebook    | [066f99ecbc](https://linux-hardware.org/?probe=066f99ecbc) | Oct 25, 2021 |
| Alienware     | m17 R4                      | Notebook    | [5c569c3982](https://linux-hardware.org/?probe=5c569c3982) | Oct 24, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2b52b81540](https://linux-hardware.org/?probe=2b52b81540) | Oct 24, 2021 |
| HP            | Compaq 6730s                | Notebook    | [587b440ce4](https://linux-hardware.org/?probe=587b440ce4) | Oct 24, 2021 |
| Dell          | 042P49 A00                  | Desktop     | [7bb7c6c3cb](https://linux-hardware.org/?probe=7bb7c6c3cb) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [68f1525bef](https://linux-hardware.org/?probe=68f1525bef) | Oct 23, 2021 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [1146299277](https://linux-hardware.org/?probe=1146299277) | Oct 23, 2021 |
| HP            | Compaq Presario CQ61        | Notebook    | [cb8b850048](https://linux-hardware.org/?probe=cb8b850048) | Oct 23, 2021 |
| MSI           | Z97 GAMING 5                | Desktop     | [0273030434](https://linux-hardware.org/?probe=0273030434) | Oct 22, 2021 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [f76ae4b159](https://linux-hardware.org/?probe=f76ae4b159) | Oct 22, 2021 |
| HP            | kip                         | Notebook    | [18f48f3a5b](https://linux-hardware.org/?probe=18f48f3a5b) | Oct 22, 2021 |
| Lenovo        | ThinkPad W510 431963G       | Notebook    | [ba467258aa](https://linux-hardware.org/?probe=ba467258aa) | Oct 21, 2021 |
| HP            | Notebook                    | Notebook    | [fb90bf9dc7](https://linux-hardware.org/?probe=fb90bf9dc7) | Oct 21, 2021 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [6be3808b94](https://linux-hardware.org/?probe=6be3808b94) | Oct 21, 2021 |
| HP            | 1998                        | Desktop     | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Lenovo        | IdeaPad U550 20034,3749     | Notebook    | [3bbec8b8fd](https://linux-hardware.org/?probe=3bbec8b8fd) | Oct 21, 2021 |
| Dell          | 0PU052                      | Desktop     | [7e7d0bc489](https://linux-hardware.org/?probe=7e7d0bc489) | Oct 21, 2021 |
| ASUSTek       | PRIME H310T                 | Desktop     | [b0e10a4766](https://linux-hardware.org/?probe=b0e10a4766) | Oct 20, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [a119d97189](https://linux-hardware.org/?probe=a119d97189) | Oct 20, 2021 |
| Toshiba       | Satellite Pro C850-1G8      | Notebook    | [8ad9f2f898](https://linux-hardware.org/?probe=8ad9f2f898) | Oct 20, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [7fb2681427](https://linux-hardware.org/?probe=7fb2681427) | Oct 20, 2021 |
| Lenovo        | B5400 s20278Q               | Notebook    | [c71ca98310](https://linux-hardware.org/?probe=c71ca98310) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [a2aee507a3](https://linux-hardware.org/?probe=a2aee507a3) | Oct 19, 2021 |
| Lenovo        | ThinkPad T510 4384A78       | Notebook    | [5a3e03b67e](https://linux-hardware.org/?probe=5a3e03b67e) | Oct 19, 2021 |
| Dell          | 0KX11M A04                  | Server      | [df26c4e8c4](https://linux-hardware.org/?probe=df26c4e8c4) | Oct 19, 2021 |
| Samsung       | R530/R730/P590              | Notebook    | [e76e147759](https://linux-hardware.org/?probe=e76e147759) | Oct 19, 2021 |
| ASRock        | G31M-VS2                    | Desktop     | [555bb7179c](https://linux-hardware.org/?probe=555bb7179c) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [63cab5e07f](https://linux-hardware.org/?probe=63cab5e07f) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [355e464f7f](https://linux-hardware.org/?probe=355e464f7f) | Oct 19, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [235b6e8d1a](https://linux-hardware.org/?probe=235b6e8d1a) | Oct 18, 2021 |
| Acer          | Extensa 5630                | Notebook    | [4823b348aa](https://linux-hardware.org/?probe=4823b348aa) | Oct 18, 2021 |
| HP            | 8717                        | Desktop     | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| Dell          | Inspiron 3537               | Notebook    | [255aca010b](https://linux-hardware.org/?probe=255aca010b) | Oct 18, 2021 |
| Dell          | Latitude E6440              | Notebook    | [640d2341de](https://linux-hardware.org/?probe=640d2341de) | Oct 17, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| Gigabyte      | M68MT-D3P                   | Desktop     | [9debdd654c](https://linux-hardware.org/?probe=9debdd654c) | Oct 15, 2021 |
| NCR           | Pocono BIOS.3.1             | Desktop     | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [b9218a0347](https://linux-hardware.org/?probe=b9218a0347) | Oct 15, 2021 |
| Supermicro    | X8DTH                       | Server      | [ad4abe60cd](https://linux-hardware.org/?probe=ad4abe60cd) | Oct 13, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [ef126ad790](https://linux-hardware.org/?probe=ef126ad790) | Oct 13, 2021 |
| Clientron     | Pineview-D                  | Desktop     | [59bf0b789c](https://linux-hardware.org/?probe=59bf0b789c) | Oct 13, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [125473d905](https://linux-hardware.org/?probe=125473d905) | Oct 13, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [6163de66f1](https://linux-hardware.org/?probe=6163de66f1) | Oct 12, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e922eda008](https://linux-hardware.org/?probe=e922eda008) | Oct 12, 2021 |
| eMachines     | G730                        | Notebook    | [b24afe5dc2](https://linux-hardware.org/?probe=b24afe5dc2) | Oct 12, 2021 |
| Foxconn       | 2AB1h                       | Desktop     | [6216ce3f5c](https://linux-hardware.org/?probe=6216ce3f5c) | Oct 12, 2021 |
| HP            | ProBook 650 G4              | Notebook    | [ea1c62ead1](https://linux-hardware.org/?probe=ea1c62ead1) | Oct 12, 2021 |
| Dell          | Latitude 7370               | Notebook    | [348b718b2b](https://linux-hardware.org/?probe=348b718b2b) | Oct 11, 2021 |
| HP            | Notebook                    | Notebook    | [732cc33a53](https://linux-hardware.org/?probe=732cc33a53) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [56135a7fa6](https://linux-hardware.org/?probe=56135a7fa6) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | Desktop     | [d7676eeb32](https://linux-hardware.org/?probe=d7676eeb32) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [c49cbf2f7a](https://linux-hardware.org/?probe=c49cbf2f7a) | Oct 11, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [6d2f43a452](https://linux-hardware.org/?probe=6d2f43a452) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [6beb9ddceb](https://linux-hardware.org/?probe=6beb9ddceb) | Oct 09, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-K               | Desktop     | [a4da124d05](https://linux-hardware.org/?probe=a4da124d05) | Oct 08, 2021 |
| Dell          | Precision 5540              | Notebook    | [b59369e8e7](https://linux-hardware.org/?probe=b59369e8e7) | Oct 08, 2021 |
| Multilaser    | UB32X                       | Notebook    | [e5e22df913](https://linux-hardware.org/?probe=e5e22df913) | Oct 08, 2021 |
| Gigabyte      | X38-DS4                     | Desktop     | [5e06d3cb35](https://linux-hardware.org/?probe=5e06d3cb35) | Oct 08, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [248c508eb0](https://linux-hardware.org/?probe=248c508eb0) | Oct 07, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [0735063fbe](https://linux-hardware.org/?probe=0735063fbe) | Oct 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [399430cdbe](https://linux-hardware.org/?probe=399430cdbe) | Oct 06, 2021 |
| Lenovo        | ThinkPad E14 20RA0016RT     | Notebook    | [d09fddd2b5](https://linux-hardware.org/?probe=d09fddd2b5) | Oct 06, 2021 |
| Lenovo        | ThinkCentre A55 92658HG     | Desktop     | [edc1f2768d](https://linux-hardware.org/?probe=edc1f2768d) | Oct 05, 2021 |
| Acer          | Aspire X1430                | Desktop     | [0864e39368](https://linux-hardware.org/?probe=0864e39368) | Oct 05, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [697843fefc](https://linux-hardware.org/?probe=697843fefc) | Oct 05, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [9ba5143844](https://linux-hardware.org/?probe=9ba5143844) | Oct 04, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [70b6961d1d](https://linux-hardware.org/?probe=70b6961d1d) | Oct 03, 2021 |
| ASUSTek       | X455LD                      | Notebook    | [7587f9b825](https://linux-hardware.org/?probe=7587f9b825) | Oct 03, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [e8fd995776](https://linux-hardware.org/?probe=e8fd995776) | Oct 03, 2021 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [37caf69047](https://linux-hardware.org/?probe=37caf69047) | Oct 02, 2021 |
| Sony          | VGN-NR38E_S                 | Notebook    | [8cb5fc39c1](https://linux-hardware.org/?probe=8cb5fc39c1) | Oct 01, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [5cccf30dd4](https://linux-hardware.org/?probe=5cccf30dd4) | Oct 01, 2021 |
| ASUSTek       | K53E                        | Notebook    | [c98e6e26ce](https://linux-hardware.org/?probe=c98e6e26ce) | Oct 01, 2021 |
| ASRock        | Z170 Gaming K4              | Desktop     | [f107c84c00](https://linux-hardware.org/?probe=f107c84c00) | Sep 30, 2021 |
| Insyde        | Harrisonville               | Desktop     | [2b7a8ba5fc](https://linux-hardware.org/?probe=2b7a8ba5fc) | Sep 30, 2021 |
| Fujitsu Si... | AMILO Pa 1510               | Notebook    | [73a0747f86](https://linux-hardware.org/?probe=73a0747f86) | Sep 29, 2021 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [8fa77435f7](https://linux-hardware.org/?probe=8fa77435f7) | Sep 29, 2021 |
| HP            | 2175                        | Desktop     | [856907ec52](https://linux-hardware.org/?probe=856907ec52) | Sep 28, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [97872be09f](https://linux-hardware.org/?probe=97872be09f) | Sep 28, 2021 |
| Toshiba       | Satellite C55-A             | Notebook    | [c79d4daf0a](https://linux-hardware.org/?probe=c79d4daf0a) | Sep 28, 2021 |
| ASUSTek       | PRIME H310T                 | Desktop     | [58721f0765](https://linux-hardware.org/?probe=58721f0765) | Sep 28, 2021 |
| Dell          | 0N826N A03                  | Desktop     | [fc1d74c246](https://linux-hardware.org/?probe=fc1d74c246) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7e710da685](https://linux-hardware.org/?probe=7e710da685) | Sep 27, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [87dd9f48a9](https://linux-hardware.org/?probe=87dd9f48a9) | Sep 26, 2021 |
| Dell          | Studio 1558                 | Notebook    | [05f781c843](https://linux-hardware.org/?probe=05f781c843) | Sep 25, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [ce0d8f233c](https://linux-hardware.org/?probe=ce0d8f233c) | Sep 24, 2021 |
| Shenzhen A... | X96 Max                     | Soc         | [6160d9149f](https://linux-hardware.org/?probe=6160d9149f) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| HP            | Compaq 6710b (GB889ET#AB... | Notebook    | [2fcbe348d6](https://linux-hardware.org/?probe=2fcbe348d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [df7ff85482](https://linux-hardware.org/?probe=df7ff85482) | Sep 23, 2021 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [36c78f1667](https://linux-hardware.org/?probe=36c78f1667) | Sep 23, 2021 |
| HP            | Notebook                    | Notebook    | [0253eca654](https://linux-hardware.org/?probe=0253eca654) | Sep 22, 2021 |
| HP            | Notebook                    | Notebook    | [9afc140a7e](https://linux-hardware.org/?probe=9afc140a7e) | Sep 22, 2021 |
| HP            | 21F5                        | Desktop     | [d6613e1901](https://linux-hardware.org/?probe=d6613e1901) | Sep 22, 2021 |
| ASUSTek       | T100HAN                     | Notebook    | [aabfa3e289](https://linux-hardware.org/?probe=aabfa3e289) | Sep 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | Desktop     | [7abd7a20df](https://linux-hardware.org/?probe=7abd7a20df) | Sep 21, 2021 |
| HP            | Compaq CQ45                 | Notebook    | [87a47d3bc8](https://linux-hardware.org/?probe=87a47d3bc8) | Sep 20, 2021 |
| Clevo         | W760SUB                     | Notebook    | [8ae1ea1d6b](https://linux-hardware.org/?probe=8ae1ea1d6b) | Sep 20, 2021 |
| HP            | ProBook 4510s               | Notebook    | [721b35cbcb](https://linux-hardware.org/?probe=721b35cbcb) | Sep 19, 2021 |
| NCR           | Pocono                      | Desktop     | [bbd821ad81](https://linux-hardware.org/?probe=bbd821ad81) | Sep 18, 2021 |
| Lenovo        | G460 0677                   | Notebook    | [6f23b54ef5](https://linux-hardware.org/?probe=6f23b54ef5) | Sep 17, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [ad597e71b6](https://linux-hardware.org/?probe=ad597e71b6) | Sep 16, 2021 |
| Dell          | Latitude D630               | Notebook    | [260bb1528f](https://linux-hardware.org/?probe=260bb1528f) | Sep 15, 2021 |
| Dell          | Inspiron 3437               | Notebook    | [67069e48f0](https://linux-hardware.org/?probe=67069e48f0) | Sep 15, 2021 |
| Lenovo        | G480 20150                  | Notebook    | [d7d8be3a08](https://linux-hardware.org/?probe=d7d8be3a08) | Sep 15, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [ea9fbdbba6](https://linux-hardware.org/?probe=ea9fbdbba6) | Sep 14, 2021 |
| Dell          | 0XHGV1 A00                  | Desktop     | [c7f133cbb9](https://linux-hardware.org/?probe=c7f133cbb9) | Sep 14, 2021 |
| Foxconn       | 2A8C                        | Desktop     | [f7b2ed152f](https://linux-hardware.org/?probe=f7b2ed152f) | Sep 12, 2021 |
| HP            | 15                          | Notebook    | [d88dbb5aa3](https://linux-hardware.org/?probe=d88dbb5aa3) | Sep 12, 2021 |
| HP            | Pavilion dm4                | Notebook    | [a10c76835b](https://linux-hardware.org/?probe=a10c76835b) | Sep 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [bced59049e](https://linux-hardware.org/?probe=bced59049e) | Sep 11, 2021 |
| Samsung       | 930QCG                      | Convertible | [2169c592d9](https://linux-hardware.org/?probe=2169c592d9) | Sep 11, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e2ad40d8c1](https://linux-hardware.org/?probe=e2ad40d8c1) | Sep 10, 2021 |
| Lenovo        | ThinkPad T520 4243AP1       | Notebook    | [3abbaccc90](https://linux-hardware.org/?probe=3abbaccc90) | Sep 09, 2021 |
| ASUSTek       | M3N18L T-M3N8200            | Desktop     | [bd8410bceb](https://linux-hardware.org/?probe=bd8410bceb) | Sep 09, 2021 |
| MSI           | GF75 Thin 9SD               | Notebook    | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | ProBook 4510s               | Notebook    | [b2e4641005](https://linux-hardware.org/?probe=b2e4641005) | Sep 09, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [3ca698d670](https://linux-hardware.org/?probe=3ca698d670) | Sep 09, 2021 |
| Dell          | Vostro 1700                 | Notebook    | [37bd4db385](https://linux-hardware.org/?probe=37bd4db385) | Sep 09, 2021 |
| Itautec       | Infoway a7420               | Notebook    | [282046f0c0](https://linux-hardware.org/?probe=282046f0c0) | Sep 09, 2021 |
| HP            | G60                         | Notebook    | [065e03350f](https://linux-hardware.org/?probe=065e03350f) | Sep 09, 2021 |
| HP            | G60                         | Notebook    | [4d35031cdf](https://linux-hardware.org/?probe=4d35031cdf) | Sep 09, 2021 |
| Biostar       | G41D3C                      | Desktop     | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [7b81d32161](https://linux-hardware.org/?probe=7b81d32161) | Sep 07, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [7ff32b60eb](https://linux-hardware.org/?probe=7ff32b60eb) | Sep 05, 2021 |
| Apple         | Mac-F2208EC8                | Mini pc     | [452356fda6](https://linux-hardware.org/?probe=452356fda6) | Sep 05, 2021 |
| Dell          | Latitude E4310              | Notebook    | [5e7233f129](https://linux-hardware.org/?probe=5e7233f129) | Sep 05, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [631ee4fd97](https://linux-hardware.org/?probe=631ee4fd97) | Sep 05, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [441840f603](https://linux-hardware.org/?probe=441840f603) | Sep 04, 2021 |
| HP            | 14                          | Notebook    | [9f574ea069](https://linux-hardware.org/?probe=9f574ea069) | Sep 04, 2021 |
| Gateway       | NV57H                       | Notebook    | [5ccb66dc7c](https://linux-hardware.org/?probe=5ccb66dc7c) | Sep 03, 2021 |
| OEM           | BayTrail JHS365             | Desktop     | [e82d82c85b](https://linux-hardware.org/?probe=e82d82c85b) | Sep 03, 2021 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [899954b326](https://linux-hardware.org/?probe=899954b326) | Sep 02, 2021 |
| Acer          | Aspire XC-603G              | Desktop     | [888a6f7244](https://linux-hardware.org/?probe=888a6f7244) | Sep 02, 2021 |
| HP            | 3032h                       | Desktop     | [4b261dcd37](https://linux-hardware.org/?probe=4b261dcd37) | Sep 02, 2021 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [b9fdcaf2f7](https://linux-hardware.org/?probe=b9fdcaf2f7) | Sep 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e47d2dc721](https://linux-hardware.org/?probe=e47d2dc721) | Sep 02, 2021 |
| Acer          | Aspire E1-772               | Notebook    | [2b6d07434a](https://linux-hardware.org/?probe=2b6d07434a) | Sep 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ee916ec895](https://linux-hardware.org/?probe=ee916ec895) | Sep 01, 2021 |
| Acer          | Aspire E1-772               | Notebook    | [4c1d560351](https://linux-hardware.org/?probe=4c1d560351) | Sep 01, 2021 |
| HP            | Notebook                    | Notebook    | [6afc243dea](https://linux-hardware.org/?probe=6afc243dea) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | Desktop     | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| Lenovo        | ThinkPad X395 20NLS0J400    | Notebook    | [cd2fa55d01](https://linux-hardware.org/?probe=cd2fa55d01) | Sep 01, 2021 |
| MSI           | Z97-G43                     | Desktop     | [364baf5248](https://linux-hardware.org/?probe=364baf5248) | Aug 31, 2021 |
| ASRock        | Q1900M                      | Desktop     | [bdb4eba3e4](https://linux-hardware.org/?probe=bdb4eba3e4) | Aug 31, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [0631958800](https://linux-hardware.org/?probe=0631958800) | Aug 29, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [89c397b882](https://linux-hardware.org/?probe=89c397b882) | Aug 29, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | 15                          | Notebook    | [8e64e4a38f](https://linux-hardware.org/?probe=8e64e4a38f) | Aug 26, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | Notebook    | [932fb79537](https://linux-hardware.org/?probe=932fb79537) | Aug 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | Desktop     | [aa1a98a9d6](https://linux-hardware.org/?probe=aa1a98a9d6) | Aug 25, 2021 |
| MSI           | PR601/VR603                 | Notebook    | [836a501df0](https://linux-hardware.org/?probe=836a501df0) | Aug 25, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| Lenovo        | B40-45 20394                | Notebook    | [551749a1af](https://linux-hardware.org/?probe=551749a1af) | Aug 25, 2021 |
| Notebook      | W970SUW                     | Notebook    | [231346d40a](https://linux-hardware.org/?probe=231346d40a) | Aug 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [fae18649fd](https://linux-hardware.org/?probe=fae18649fd) | Aug 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [f0824b7193](https://linux-hardware.org/?probe=f0824b7193) | Aug 24, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | Notebook    | [74c2a834e7](https://linux-hardware.org/?probe=74c2a834e7) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [8d43ff5f35](https://linux-hardware.org/?probe=8d43ff5f35) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [23fcf2122e](https://linux-hardware.org/?probe=23fcf2122e) | Aug 23, 2021 |
| Dell          | Studio 1569                 | Notebook    | [600cbb330c](https://linux-hardware.org/?probe=600cbb330c) | Aug 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f128b4ee5a](https://linux-hardware.org/?probe=f128b4ee5a) | Aug 23, 2021 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [08e78aa61d](https://linux-hardware.org/?probe=08e78aa61d) | Aug 23, 2021 |
| Acer          | Aspire XC-603G              | Desktop     | [3aca23ef5f](https://linux-hardware.org/?probe=3aca23ef5f) | Aug 22, 2021 |
| Foxconn       | 2A8C                        | Desktop     | [f3ae3bb84c](https://linux-hardware.org/?probe=f3ae3bb84c) | Aug 21, 2021 |
| ASUSTek       | X501A                       | Notebook    | [e9784e8db3](https://linux-hardware.org/?probe=e9784e8db3) | Aug 21, 2021 |
| Alienware     | 0N4R4N A00                  | Desktop     | [bf5947b943](https://linux-hardware.org/?probe=bf5947b943) | Aug 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS12E0... | Notebook    | [fb7ab1b2d1](https://linux-hardware.org/?probe=fb7ab1b2d1) | Aug 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [df5f5f1ab4](https://linux-hardware.org/?probe=df5f5f1ab4) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1639c4e352](https://linux-hardware.org/?probe=1639c4e352) | Aug 20, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a7c72d0be5](https://linux-hardware.org/?probe=a7c72d0be5) | Aug 20, 2021 |
| ASRock        | A320M-HDV                   | Desktop     | [42ab0a8ca5](https://linux-hardware.org/?probe=42ab0a8ca5) | Aug 20, 2021 |
| Acer          | Aspire X1470                | Desktop     | [79d5cfd4fd](https://linux-hardware.org/?probe=79d5cfd4fd) | Aug 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [6651af56b1](https://linux-hardware.org/?probe=6651af56b1) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | Notebook    | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [a0e952ee9c](https://linux-hardware.org/?probe=a0e952ee9c) | Aug 19, 2021 |
| Google        | Kip                         | Notebook    | [11ba4592bc](https://linux-hardware.org/?probe=11ba4592bc) | Aug 19, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [37a5e6b984](https://linux-hardware.org/?probe=37a5e6b984) | Aug 18, 2021 |
| HP            | 255 G1                      | Notebook    | [4998946adc](https://linux-hardware.org/?probe=4998946adc) | Aug 18, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [a5b305d6f5](https://linux-hardware.org/?probe=a5b305d6f5) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [dbb548b728](https://linux-hardware.org/?probe=dbb548b728) | Aug 18, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [ce21a853bc](https://linux-hardware.org/?probe=ce21a853bc) | Aug 18, 2021 |
| Dell          | Latitude E5520              | Notebook    | [9e4e9c3dea](https://linux-hardware.org/?probe=9e4e9c3dea) | Aug 17, 2021 |
| Lenovo        | B5400 s20278Q               | Notebook    | [24ebde0d00](https://linux-hardware.org/?probe=24ebde0d00) | Aug 17, 2021 |
| Dell          | Latitude E4310              | Notebook    | [489bf81791](https://linux-hardware.org/?probe=489bf81791) | Aug 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4740529a1f](https://linux-hardware.org/?probe=4740529a1f) | Aug 17, 2021 |
| MSI           | Boston                      | Desktop     | [eb189f6da8](https://linux-hardware.org/?probe=eb189f6da8) | Aug 17, 2021 |
| HP            | 0B54h D                     | Desktop     | [f68a448d75](https://linux-hardware.org/?probe=f68a448d75) | Aug 17, 2021 |
| Gateway       | SX2185                      | Desktop     | [6e9745ae09](https://linux-hardware.org/?probe=6e9745ae09) | Aug 17, 2021 |
| HP            | 0B54h D                     | Desktop     | [9fd9d289f2](https://linux-hardware.org/?probe=9fd9d289f2) | Aug 17, 2021 |
| Lenovo        | ThinkPad W540 20BHS0KY08    | Notebook    | [6ba4712f8d](https://linux-hardware.org/?probe=6ba4712f8d) | Aug 16, 2021 |
| Dell          | Vostro 3491                 | Notebook    | [0f23db87f7](https://linux-hardware.org/?probe=0f23db87f7) | Aug 16, 2021 |
| HP            | ProBook 6470b               | Notebook    | [f42e212309](https://linux-hardware.org/?probe=f42e212309) | Aug 14, 2021 |
| ASUSTek       | B85-PLUS                    | Desktop     | [10fd5746f0](https://linux-hardware.org/?probe=10fd5746f0) | Aug 14, 2021 |
| HP            | Compaq 8710w                | Notebook    | [1e1d518b29](https://linux-hardware.org/?probe=1e1d518b29) | Aug 14, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [3ff1b8f6dc](https://linux-hardware.org/?probe=3ff1b8f6dc) | Aug 14, 2021 |
| Lenovo        | ThinkPad W540 20BHS1HR00    | Notebook    | [514e20d875](https://linux-hardware.org/?probe=514e20d875) | Aug 14, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [23b1aab5c3](https://linux-hardware.org/?probe=23b1aab5c3) | Aug 13, 2021 |
| Toshiba       | Satellite P205D             | Notebook    | [95f23ff5ec](https://linux-hardware.org/?probe=95f23ff5ec) | Aug 13, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e78e29878](https://linux-hardware.org/?probe=2e78e29878) | Aug 12, 2021 |
| Dell          | Vostro 3491                 | Notebook    | [125085e464](https://linux-hardware.org/?probe=125085e464) | Aug 12, 2021 |
| ASUSTek       | N550JV                      | Notebook    | [a0023fa7d2](https://linux-hardware.org/?probe=a0023fa7d2) | Aug 12, 2021 |
| HP            | 0B54h D                     | Desktop     | [49eb423362](https://linux-hardware.org/?probe=49eb423362) | Aug 11, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [4a660bcb77](https://linux-hardware.org/?probe=4a660bcb77) | Aug 11, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [0cf6373ba8](https://linux-hardware.org/?probe=0cf6373ba8) | Aug 10, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [adee49adad](https://linux-hardware.org/?probe=adee49adad) | Aug 10, 2021 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0b019ac936](https://linux-hardware.org/?probe=0b019ac936) | Aug 09, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [c2ed04ce87](https://linux-hardware.org/?probe=c2ed04ce87) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | Desktop     | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| Dell          | 0WMJ54 A00                  | Desktop     | [d577241d35](https://linux-hardware.org/?probe=d577241d35) | Aug 08, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [6f97e49163](https://linux-hardware.org/?probe=6f97e49163) | Aug 08, 2021 |
| Toshiba       | Satellite P205D             | Notebook    | [827f451413](https://linux-hardware.org/?probe=827f451413) | Aug 07, 2021 |
| Toshiba       | Satellite P205D             | Notebook    | [a39bd5d78b](https://linux-hardware.org/?probe=a39bd5d78b) | Aug 07, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [c45499e754](https://linux-hardware.org/?probe=c45499e754) | Aug 07, 2021 |
| Toshiba       | Satellite A100              | Notebook    | [7d3f237f02](https://linux-hardware.org/?probe=7d3f237f02) | Aug 07, 2021 |
| UNOWHY        | Y13G010S4EI                 | Notebook    | [a642818617](https://linux-hardware.org/?probe=a642818617) | Aug 06, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [c3ac112d1b](https://linux-hardware.org/?probe=c3ac112d1b) | Aug 06, 2021 |
| Notebook      | P65_P67RGRERA               | Notebook    | [07d63d9efc](https://linux-hardware.org/?probe=07d63d9efc) | Aug 06, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [01a2971d58](https://linux-hardware.org/?probe=01a2971d58) | Aug 06, 2021 |
| Acer          | Aspire ES1-111              | Notebook    | [5f5802297c](https://linux-hardware.org/?probe=5f5802297c) | Aug 05, 2021 |
| ASUSTek       | X455YA                      | Notebook    | [7ceff8b834](https://linux-hardware.org/?probe=7ceff8b834) | Aug 05, 2021 |
| Lenovo        | G460 0677                   | Notebook    | [18dd5bf1b0](https://linux-hardware.org/?probe=18dd5bf1b0) | Aug 05, 2021 |
| Dell          | 0PN455 A00                  | All in one  | [3936fd702b](https://linux-hardware.org/?probe=3936fd702b) | Aug 04, 2021 |
| HP            | EliteBook x360 1040 G7 N... | Convertible | [ca10831a1e](https://linux-hardware.org/?probe=ca10831a1e) | Aug 04, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [3bca4552ab](https://linux-hardware.org/?probe=3bca4552ab) | Aug 04, 2021 |
| HP            | 1998                        | Desktop     | [e6d0744e85](https://linux-hardware.org/?probe=e6d0744e85) | Aug 04, 2021 |
| HP            | 1998                        | Desktop     | [b3b909d152](https://linux-hardware.org/?probe=b3b909d152) | Aug 04, 2021 |
| HP            | 2000                        | Notebook    | [27633bfd4b](https://linux-hardware.org/?probe=27633bfd4b) | Aug 03, 2021 |
| Acer          | Swift SF314-54G             | Notebook    | [8076357ae9](https://linux-hardware.org/?probe=8076357ae9) | Aug 03, 2021 |
| Lenovo        | G460 0677                   | Notebook    | [1563cdbde9](https://linux-hardware.org/?probe=1563cdbde9) | Aug 02, 2021 |
| HP            | 3646h                       | Desktop     | [60fb363058](https://linux-hardware.org/?probe=60fb363058) | Aug 02, 2021 |
| HP            | 2B29                        | Desktop     | [06babd8c13](https://linux-hardware.org/?probe=06babd8c13) | Aug 01, 2021 |
| HP            | 0B54h D                     | Desktop     | [a7f0b16b1f](https://linux-hardware.org/?probe=a7f0b16b1f) | Jul 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [0aae2dd454](https://linux-hardware.org/?probe=0aae2dd454) | Jul 30, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [fb919a9b90](https://linux-hardware.org/?probe=fb919a9b90) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [fb839f1401](https://linux-hardware.org/?probe=fb839f1401) | Jul 30, 2021 |
| Lenovo        | ThinkPad T500 2241CG9       | Notebook    | [912d324ee3](https://linux-hardware.org/?probe=912d324ee3) | Jul 29, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [90e216200b](https://linux-hardware.org/?probe=90e216200b) | Jul 29, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [4e46cf5851](https://linux-hardware.org/?probe=4e46cf5851) | Jul 29, 2021 |
| Sony          | SVE1512C6EB                 | Notebook    | [e1ce6add06](https://linux-hardware.org/?probe=e1ce6add06) | Jul 28, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [0a30fad96c](https://linux-hardware.org/?probe=0a30fad96c) | Jul 27, 2021 |
| HP            | 15                          | Notebook    | [6b1274ba87](https://linux-hardware.org/?probe=6b1274ba87) | Jul 27, 2021 |
| HP            | 15                          | Notebook    | [28f688d410](https://linux-hardware.org/?probe=28f688d410) | Jul 27, 2021 |
| BANGHO        | Suma 1025                   | Tablet      | [a8fd7a9a44](https://linux-hardware.org/?probe=a8fd7a9a44) | Jul 26, 2021 |
| MSI           | MS-7181                     | Desktop     | [f2c624a258](https://linux-hardware.org/?probe=f2c624a258) | Jul 26, 2021 |
| WinFast       | 6100M2MA FAB1.0             | Desktop     | [f994eb2a66](https://linux-hardware.org/?probe=f994eb2a66) | Jul 26, 2021 |
| Intel         | DQ67SW AAG12527-310         | Desktop     | [36a4037b9d](https://linux-hardware.org/?probe=36a4037b9d) | Jul 26, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [15aef595c1](https://linux-hardware.org/?probe=15aef595c1) | Jul 26, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [9a8bc84b14](https://linux-hardware.org/?probe=9a8bc84b14) | Jul 26, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [69bc249119](https://linux-hardware.org/?probe=69bc249119) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [d6e4e7f445](https://linux-hardware.org/?probe=d6e4e7f445) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [7d7ebd3f1e](https://linux-hardware.org/?probe=7d7ebd3f1e) | Jul 25, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [56198fa6c1](https://linux-hardware.org/?probe=56198fa6c1) | Jul 24, 2021 |
| Dell          | 03KWTV A02                  | Desktop     | [b292aa69b5](https://linux-hardware.org/?probe=b292aa69b5) | Jul 24, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [94f41122bf](https://linux-hardware.org/?probe=94f41122bf) | Jul 24, 2021 |
| HP            | Notebook                    | Notebook    | [75e72e2359](https://linux-hardware.org/?probe=75e72e2359) | Jul 24, 2021 |
| HP            | 1589                        | Desktop     | [2885bdaad2](https://linux-hardware.org/?probe=2885bdaad2) | Jul 23, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [a81a047059](https://linux-hardware.org/?probe=a81a047059) | Jul 23, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [3cc56271ad](https://linux-hardware.org/?probe=3cc56271ad) | Jul 23, 2021 |
| Dell          | Inspiron 7560               | Notebook    | [46032a26c5](https://linux-hardware.org/?probe=46032a26c5) | Jul 23, 2021 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | Notebook    | [a76718434c](https://linux-hardware.org/?probe=a76718434c) | Jul 23, 2021 |
| MSI           | Z370-A PRO                  | Desktop     | [b125a65313](https://linux-hardware.org/?probe=b125a65313) | Jul 22, 2021 |
| Toshiba       | PORTEGE R930                | Notebook    | [6141314610](https://linux-hardware.org/?probe=6141314610) | Jul 22, 2021 |
| Dell          | Latitude E6330              | Notebook    | [772c8f269b](https://linux-hardware.org/?probe=772c8f269b) | Jul 21, 2021 |
| HP            | Unknown                     | Notebook    | [3f71deefd5](https://linux-hardware.org/?probe=3f71deefd5) | Jul 20, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | Notebook    | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [63865e14f0](https://linux-hardware.org/?probe=63865e14f0) | Jul 19, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2895631c36](https://linux-hardware.org/?probe=2895631c36) | Jul 19, 2021 |
| HP            | Laptop 17-by4xxx            | Notebook    | [d66405d958](https://linux-hardware.org/?probe=d66405d958) | Jul 19, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [f8767723e4](https://linux-hardware.org/?probe=f8767723e4) | Jul 18, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [29e1b14111](https://linux-hardware.org/?probe=29e1b14111) | Jul 18, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [088adbd181](https://linux-hardware.org/?probe=088adbd181) | Jul 18, 2021 |
| ASRock        | 880GM-LE                    | Desktop     | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [561ed2dd58](https://linux-hardware.org/?probe=561ed2dd58) | Jul 18, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [838188303a](https://linux-hardware.org/?probe=838188303a) | Jul 17, 2021 |
| Samsung       | R530/R730/P530              | Notebook    | [f95d4bb8f5](https://linux-hardware.org/?probe=f95d4bb8f5) | Jul 17, 2021 |
| Dell          | 0VNP2H A00                  | Desktop     | [167ec81986](https://linux-hardware.org/?probe=167ec81986) | Jul 17, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [8263a1f725](https://linux-hardware.org/?probe=8263a1f725) | Jul 17, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| Lenovo        | ThinkPad E485 20KU001CGE    | Notebook    | [4a42a910a2](https://linux-hardware.org/?probe=4a42a910a2) | Jul 15, 2021 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [ebbe4a088d](https://linux-hardware.org/?probe=ebbe4a088d) | Jul 15, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [3f9fb487ad](https://linux-hardware.org/?probe=3f9fb487ad) | Jul 15, 2021 |
| ASUSTek       | M3A-H/HDMI                  | Desktop     | [6c97b09b3f](https://linux-hardware.org/?probe=6c97b09b3f) | Jul 14, 2021 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [d871a17735](https://linux-hardware.org/?probe=d871a17735) | Jul 14, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [46fb536e9d](https://linux-hardware.org/?probe=46fb536e9d) | Jul 13, 2021 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [ee2fa49a14](https://linux-hardware.org/?probe=ee2fa49a14) | Jul 13, 2021 |
| HP            | 0A64h                       | Desktop     | [317c62b0b9](https://linux-hardware.org/?probe=317c62b0b9) | Jul 13, 2021 |
| HP            | 0A64h                       | Desktop     | [7495976a12](https://linux-hardware.org/?probe=7495976a12) | Jul 13, 2021 |
| Lenovo        | ThinkPad W530 24479Q7       | Notebook    | [1feeb254be](https://linux-hardware.org/?probe=1feeb254be) | Jul 12, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [03c69f44e3](https://linux-hardware.org/?probe=03c69f44e3) | Jul 12, 2021 |
| Dell          | Inspiron 5485               | Notebook    | [d97549e586](https://linux-hardware.org/?probe=d97549e586) | Jul 11, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [6103626346](https://linux-hardware.org/?probe=6103626346) | Jul 11, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bb0f20f7a9](https://linux-hardware.org/?probe=bb0f20f7a9) | Jul 10, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [5416b8d0da](https://linux-hardware.org/?probe=5416b8d0da) | Jul 10, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [9f1b7a37f2](https://linux-hardware.org/?probe=9f1b7a37f2) | Jul 07, 2021 |
| HP            | Laptop 17-by4xxx            | Notebook    | [bd9ce451e8](https://linux-hardware.org/?probe=bd9ce451e8) | Jul 07, 2021 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [252d84e173](https://linux-hardware.org/?probe=252d84e173) | Jul 05, 2021 |
| Acer          | AOD270                      | Notebook    | [c829f9921a](https://linux-hardware.org/?probe=c829f9921a) | Jul 05, 2021 |
| MSI           | Boston                      | Desktop     | [72f1bfa2f0](https://linux-hardware.org/?probe=72f1bfa2f0) | Jul 05, 2021 |
| MSI           | Boston                      | Desktop     | [ff82275c70](https://linux-hardware.org/?probe=ff82275c70) | Jul 04, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_20.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Computers | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 97        | 4.49%   |
| 5.4.0-48-generic    | 54        | 2.5%    |
| 5.11.0-27-generic   | 50        | 2.31%   |
| 5.4.0-52-generic    | 47        | 2.18%   |
| 5.4.0-29-generic    | 46        | 2.13%   |
| 5.4.0-58-generic    | 45        | 2.08%   |
| 5.4.0-65-generic    | 43        | 1.99%   |
| 5.4.0-54-generic    | 40        | 1.85%   |
| 5.4.0-42-lowlatency | 40        | 1.85%   |
| 5.4.0-26-generic    | 38        | 1.76%   |
| 5.4.0-40-generic    | 35        | 1.62%   |
| 5.4.0-47-generic    | 33        | 1.53%   |
| 5.4.0-37-generic    | 33        | 1.53%   |
| 5.4.0-31-generic    | 30        | 1.39%   |
| 5.4.0-29-lowlatency | 27        | 1.25%   |
| 5.4.0-66-generic    | 26        | 1.2%    |
| 5.4.0-33-generic    | 25        | 1.16%   |
| 5.4.0-89-generic    | 23        | 1.06%   |
| 5.8.0-53-generic    | 22        | 1.02%   |
| 5.4.0-72-generic    | 21        | 0.97%   |
| 5.4.0-70-generic    | 21        | 0.97%   |
| 5.4.0-40-lowlatency | 21        | 0.97%   |
| 5.8.0-43-generic    | 20        | 0.93%   |
| 5.4.0-91-generic    | 20        | 0.93%   |
| 5.13.0-30-generic   | 20        | 0.93%   |
| 5.11.0-37-generic   | 20        | 0.93%   |
| 5.4.0-58-lowlatency | 19        | 0.88%   |
| 5.4.0-56-generic    | 19        | 0.88%   |
| 5.4.0-77-generic    | 18        | 0.83%   |
| 5.4.0-65-lowlatency | 18        | 0.83%   |
| 5.4.0-45-generic    | 18        | 0.83%   |
| 5.4.0-37-lowlatency | 18        | 0.83%   |
| 5.4.0-125-generic   | 18        | 0.83%   |
| 5.4.0-67-generic    | 17        | 0.79%   |
| 5.4.0-53-generic    | 17        | 0.79%   |
| 5.4.0-52-lowlatency | 17        | 0.79%   |
| 5.4.0-126-generic   | 17        | 0.79%   |
| 5.4.0-81-generic    | 16        | 0.74%   |
| 5.4.0-74-generic    | 16        | 0.74%   |
| 5.8.0-50-generic    | 15        | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1294      | 67.75%  |
| 5.11.0  | 202       | 10.58%  |
| 5.8.0   | 169       | 8.85%   |
| 5.13.0  | 131       | 6.86%   |
| 5.15.0  | 42        | 2.2%    |
| 5.10.0  | 5         | 0.26%   |
| 5.6.0   | 3         | 0.16%   |
| 5.14.0  | 3         | 0.16%   |
| 5.9.0   | 2         | 0.1%    |
| 5.7.7   | 2         | 0.1%    |
| 5.7.6   | 2         | 0.1%    |
| 5.7.0   | 2         | 0.1%    |
| 5.3.0   | 2         | 0.1%    |
| 5.16.0  | 2         | 0.1%    |
| 5.12.12 | 2         | 0.1%    |
| 5.12.10 | 2         | 0.1%    |
| 4.4.254 | 2         | 0.1%    |
| 4.15.0  | 2         | 0.1%    |
| 5.9.8   | 1         | 0.05%   |
| 5.9.6   | 1         | 0.05%   |
| 5.9.16  | 1         | 0.05%   |
| 5.9.14  | 1         | 0.05%   |
| 5.9.1   | 1         | 0.05%   |
| 5.8.5   | 1         | 0.05%   |
| 5.8.18  | 1         | 0.05%   |
| 5.8.16  | 1         | 0.05%   |
| 5.8.13  | 1         | 0.05%   |
| 5.8.1   | 1         | 0.05%   |
| 5.7.17  | 1         | 0.05%   |
| 5.7.1   | 1         | 0.05%   |
| 5.6.6   | 1         | 0.05%   |
| 5.6.19  | 1         | 0.05%   |
| 5.4.67  | 1         | 0.05%   |
| 5.4.65  | 1         | 0.05%   |
| 5.4.64  | 1         | 0.05%   |
| 5.4.107 | 1         | 0.05%   |
| 5.18.0  | 1         | 0.05%   |
| 5.17.0  | 1         | 0.05%   |
| 5.15.36 | 1         | 0.05%   |
| 5.15.25 | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1298      | 68.03%  |
| 5.11    | 203       | 10.64%  |
| 5.8     | 174       | 9.12%   |
| 5.13    | 131       | 6.87%   |
| 5.15    | 45        | 2.36%   |
| 5.10    | 10        | 0.52%   |
| 5.7     | 8         | 0.42%   |
| 5.9     | 7         | 0.37%   |
| 5.14    | 6         | 0.31%   |
| 5.6     | 5         | 0.26%   |
| 5.12    | 5         | 0.26%   |
| 4.4     | 4         | 0.21%   |
| 4.9     | 3         | 0.16%   |
| 5.3     | 2         | 0.1%    |
| 5.16    | 2         | 0.1%    |
| 4.15    | 2         | 0.1%    |
| 5.18    | 1         | 0.05%   |
| 5.17    | 1         | 0.05%   |
| 4.19    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1845      | 98.72%  |
| aarch64 | 19        | 1.02%   |
| armv7l  | 5         | 0.27%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| XFCE            | 1791      | 95.83%  |
| GNOME           | 54        | 2.89%   |
| KDE5            | 5         | 0.27%   |
| i3              | 5         | 0.27%   |
| Unity           | 3         | 0.16%   |
| MATE            | 2         | 0.11%   |
| LXQt            | 2         | 0.11%   |
| GNOME Flashback | 2         | 0.11%   |
| Cinnamon        | 2         | 0.11%   |
| xmonad          | 1         | 0.05%   |
| X-Cinnamon      | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1820      | 97.38%  |
| Tty     | 37        | 1.98%   |
| Wayland | 8         | 0.43%   |
| Web     | 3         | 0.16%   |
| Unknown | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 941       | 48.96%  |
| LightDM | 586       | 30.49%  |
| TDM     | 339       | 17.64%  |
| GDM     | 34        | 1.77%   |
| GDM3    | 15        | 0.78%   |
| SDDM    | 4         | 0.21%   |
| XDM     | 3         | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 631       | 33.69%  |
| de_DE | 204       | 10.89%  |
| fr_FR | 180       | 9.61%   |
| pt_BR | 105       | 5.61%   |
| ru_RU | 89        | 4.75%   |
| C     | 87        | 4.64%   |
| it_IT | 86        | 4.59%   |
| en_GB | 76        | 4.06%   |
| en_CA | 49        | 2.62%   |
| es_ES | 42        | 2.24%   |
| pl_PL | 34        | 1.82%   |
| en_AU | 26        | 1.39%   |
| ja_JP | 21        | 1.12%   |
| nl_NL | 20        | 1.07%   |
| es_AR | 20        | 1.07%   |
| hu_HU | 18        | 0.96%   |
| en_IN | 13        | 0.69%   |
| cs_CZ | 11        | 0.59%   |
| es_MX | 10        | 0.53%   |
| de_AT | 10        | 0.53%   |
| sv_SE | 9         | 0.48%   |
| fi_FI | 9         | 0.48%   |
| de_CH | 9         | 0.48%   |
| fr_CA | 8         | 0.43%   |
| fr_BE | 8         | 0.43%   |
| ru_UA | 6         | 0.32%   |
| es_CO | 6         | 0.32%   |
| pt_PT | 5         | 0.27%   |
| es_PE | 5         | 0.27%   |
| zh_CN | 4         | 0.21%   |
| ro_RO | 4         | 0.21%   |
| en_ZA | 4         | 0.21%   |
| en_NZ | 4         | 0.21%   |
| el_GR | 4         | 0.21%   |
| zh_TW | 3         | 0.16%   |
| uk_UA | 3         | 0.16%   |
| tr_TR | 3         | 0.16%   |
| sl_SI | 3         | 0.16%   |
| nl_BE | 3         | 0.16%   |
| lt_LT | 3         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1126      | 59.83%  |
| EFI  | 756       | 40.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1725      | 92.1%   |
| Overlay | 86        | 4.59%   |
| Btrfs   | 27        | 1.44%   |
| Zfs     | 18        | 0.96%   |
| Xfs     | 8         | 0.43%   |
| Ext2    | 4         | 0.21%   |
| Ext3    | 3         | 0.16%   |
| Unknown | 2         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1149      | 61.25%  |
| GPT     | 423       | 22.55%  |
| MBR     | 304       | 16.2%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1566      | 82.38%  |
| Yes       | 335       | 17.62%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1220      | 64.41%  |
| Yes       | 674       | 35.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 303       | 16.21%  |
| ASUSTek Computer        | 278       | 14.87%  |
| Dell                    | 247       | 13.22%  |
| Lenovo                  | 226       | 12.09%  |
| Gigabyte Technology     | 116       | 6.21%   |
| Acer                    | 110       | 5.89%   |
| MSI                     | 79        | 4.23%   |
| ASRock                  | 73        | 3.91%   |
| Toshiba                 | 51        | 2.73%   |
| Apple                   | 39        | 2.09%   |
| Intel                   | 32        | 1.71%   |
| Medion                  | 26        | 1.39%   |
| Samsung Electronics     | 23        | 1.23%   |
| Fujitsu                 | 21        | 1.12%   |
| ECS                     | 19        | 1.02%   |
| Unknown                 | 18        | 0.96%   |
| Sony                    | 15        | 0.8%    |
| Packard Bell            | 12        | 0.64%   |
| Notebook                | 12        | 0.64%   |
| Raspberry Pi Foundation | 10        | 0.54%   |
| Fujitsu Siemens         | 10        | 0.54%   |
| Positivo                | 8         | 0.43%   |
| Pegatron                | 7         | 0.37%   |
| Foxconn                 | 7         | 0.37%   |
| Clevo                   | 7         | 0.37%   |
| eMachines               | 5         | 0.27%   |
| AMI                     | 5         | 0.27%   |
| HUAWEI                  | 4         | 0.21%   |
| Google                  | 4         | 0.21%   |
| Gateway                 | 4         | 0.21%   |
| Biostar                 | 4         | 0.21%   |
| TUXEDO                  | 3         | 0.16%   |
| Schenker                | 3         | 0.16%   |
| Nvidia                  | 3         | 0.16%   |
| LG Electronics          | 3         | 0.16%   |
| Itautec                 | 3         | 0.16%   |
| GPU Company             | 3         | 0.16%   |
| Dynabook                | 3         | 0.16%   |
| Alienware               | 3         | 0.16%   |
| Supermicro              | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 26        | 1.39%   |
| ASUS All Series                        | 16        | 0.86%   |
| Gigabyte H410M S2H                     | 15        | 0.8%    |
| HP Notebook                            | 11        | 0.59%   |
| ECS G31T-M9                            | 9         | 0.48%   |
| Dell OptiPlex 7010                     | 8         | 0.43%   |
| Dell Latitude D630                     | 8         | 0.43%   |
| HP Pavilion dv6                        | 6         | 0.32%   |
| Dell Latitude E6430                    | 6         | 0.32%   |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.32%   |
| HP 15                                  | 5         | 0.27%   |
| Dell OptiPlex 780                      | 5         | 0.27%   |
| Dell OptiPlex 755                      | 5         | 0.27%   |
| Dell OptiPlex 390                      | 5         | 0.27%   |
| ASUS TUF Gaming X570-PLUS              | 5         | 0.27%   |
| RPi Raspberry Pi 4 Model B Rev 1.4     | 4         | 0.21%   |
| MSI MS-7B79                            | 4         | 0.21%   |
| MSI MS-7721                            | 4         | 0.21%   |
| Intel H61                              | 4         | 0.21%   |
| HP ProDesk 405 G6 Desktop Mini PC      | 4         | 0.21%   |
| HP Pavilion dv7                        | 4         | 0.21%   |
| HP EliteBook 8560p                     | 4         | 0.21%   |
| HP Compaq Elite 8300 SFF               | 4         | 0.21%   |
| Gigabyte B450M DS3H                    | 4         | 0.21%   |
| Dell OptiPlex 9020                     | 4         | 0.21%   |
| Dell OptiPlex 760                      | 4         | 0.21%   |
| Dell Latitude E6330                    | 4         | 0.21%   |
| ASUS K53SC                             | 4         | 0.21%   |
| ASRock N68C-S UCC                      | 4         | 0.21%   |
| Apple Macmini4,1                       | 4         | 0.21%   |
| Toshiba Satellite A100                 | 3         | 0.16%   |
| Toshiba PORTEGE R930                   | 3         | 0.16%   |
| RPi Raspberry Pi 4 Model B Rev 1.1     | 3         | 0.16%   |
| MSI MS-7A34                            | 3         | 0.16%   |
| MSI MS-7693                            | 3         | 0.16%   |
| HP Z420 Workstation                    | 3         | 0.16%   |
| HP ProDesk 600 G1 SFF                  | 3         | 0.16%   |
| HP ProBook 4540s                       | 3         | 0.16%   |
| HP Presario C700                       | 3         | 0.16%   |
| HP Pavilion Gaming Laptop 15-ec0xxx    | 3         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 117       | 6.26%   |
| Acer Aspire           | 73        | 3.91%   |
| Dell Latitude         | 66        | 3.53%   |
| Dell Inspiron         | 64        | 3.42%   |
| HP Pavilion           | 53        | 2.84%   |
| HP Compaq             | 53        | 2.84%   |
| Dell OptiPlex         | 51        | 2.73%   |
| Toshiba Satellite     | 41        | 2.19%   |
| Lenovo IdeaPad        | 34        | 1.82%   |
| HP EliteBook          | 33        | 1.77%   |
| Unknown               | 26        | 1.39%   |
| ASUS PRIME            | 25        | 1.34%   |
| HP ProBook            | 22        | 1.18%   |
| ASUS VivoBook         | 22        | 1.18%   |
| HP Laptop             | 21        | 1.12%   |
| Lenovo ThinkCentre    | 19        | 1.02%   |
| Dell Precision        | 17        | 0.91%   |
| ASUS All              | 16        | 0.86%   |
| Gigabyte H410M        | 15        | 0.8%    |
| Dell Vostro           | 15        | 0.8%    |
| ASUS TUF              | 14        | 0.75%   |
| HP ProDesk            | 12        | 0.64%   |
| HP Notebook           | 12        | 0.64%   |
| Acer Extensa          | 12        | 0.64%   |
| RPi Raspberry         | 10        | 0.54%   |
| Fujitsu ESPRIMO       | 10        | 0.54%   |
| ECS G31T-M9           | 9         | 0.48%   |
| ASUS ROG              | 9         | 0.48%   |
| Dell Studio           | 8         | 0.43%   |
| Packard Bell EasyNote | 7         | 0.37%   |
| HP ENVY               | 7         | 0.37%   |
| Dell XPS              | 7         | 0.37%   |
| Dell PowerEdge        | 7         | 0.37%   |
| Lenovo IdeaCentre     | 6         | 0.32%   |
| HP ProLiant           | 6         | 0.32%   |
| HP EliteDesk          | 6         | 0.32%   |
| HP 255                | 6         | 0.32%   |
| Fujitsu LIFEBOOK      | 6         | 0.32%   |
| ASUS M5A78L-M         | 6         | 0.32%   |
| Toshiba PORTEGE       | 5         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 175       | 9.36%   |
| 2012    | 173       | 9.26%   |
| 2013    | 159       | 8.51%   |
| 2010    | 148       | 7.92%   |
| 2019    | 136       | 7.28%   |
| 2020    | 125       | 6.69%   |
| 2009    | 122       | 6.53%   |
| 2018    | 119       | 6.37%   |
| 2014    | 116       | 6.21%   |
| 2008    | 116       | 6.21%   |
| 2017    | 110       | 5.89%   |
| 2007    | 96        | 5.14%   |
| 2015    | 88        | 4.71%   |
| 2016    | 74        | 3.96%   |
| 2021    | 49        | 2.62%   |
| 2006    | 30        | 1.61%   |
| Unknown | 19        | 1.02%   |
| 2005    | 10        | 0.54%   |
| 2022    | 4         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 982       | 52.54%  |
| Desktop        | 782       | 41.84%  |
| Mini pc        | 25        | 1.34%   |
| All in one     | 24        | 1.28%   |
| System on chip | 22        | 1.18%   |
| Convertible    | 20        | 1.07%   |
| Server         | 10        | 0.54%   |
| Tablet         | 4         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1759      | 93.86%  |
| Enabled  | 115       | 6.14%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1864      | 99.73%  |
| Yes  | 5         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 513       | 27.1%   |
| 4.01-8.0        | 399       | 21.08%  |
| 8.01-16.0       | 293       | 15.48%  |
| 16.01-24.0      | 291       | 15.37%  |
| 1.01-2.0        | 156       | 8.24%   |
| 32.01-64.0      | 112       | 5.92%   |
| 64.01-256.0     | 42        | 2.22%   |
| 2.01-3.0        | 40        | 2.11%   |
| 0.51-1.0        | 23        | 1.22%   |
| 24.01-32.0      | 22        | 1.16%   |
| More than 256.0 | 1         | 0.05%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 942       | 46.06%  |
| 2.01-3.0   | 434       | 21.22%  |
| 0.51-1.0   | 258       | 12.62%  |
| 4.01-8.0   | 193       | 9.44%   |
| 3.01-4.0   | 150       | 7.33%   |
| 8.01-16.0  | 53        | 2.59%   |
| 16.01-24.0 | 6         | 0.29%   |
| 24.01-32.0 | 5         | 0.24%   |
| 0.01-0.5   | 4         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1123      | 58.58%  |
| 2      | 486       | 25.35%  |
| 3      | 164       | 8.56%   |
| 4      | 63        | 3.29%   |
| 5      | 31        | 1.62%   |
| 0      | 24        | 1.25%   |
| 6      | 11        | 0.57%   |
| 7      | 8         | 0.42%   |
| 10     | 3         | 0.16%   |
| 9      | 2         | 0.1%    |
| 8      | 2         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 983       | 52.4%   |
| No        | 893       | 47.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1704      | 91.12%  |
| No        | 166       | 8.88%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1331      | 70.65%  |
| No        | 553       | 29.35%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1048      | 55.36%  |
| Yes       | 845       | 44.64%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 339       | 18.06%  |
| Germany      | 247       | 13.16%  |
| France       | 185       | 9.86%   |
| Brazil       | 114       | 6.07%   |
| Russia       | 105       | 5.59%   |
| Italy        | 99        | 5.27%   |
| Canada       | 94        | 5.01%   |
| UK           | 75        | 4%      |
| Spain        | 60        | 3.2%    |
| Netherlands  | 54        | 2.88%   |
| Poland       | 38        | 2.02%   |
| Australia    | 28        | 1.49%   |
| Japan        | 25        | 1.33%   |
| Argentina    | 24        | 1.28%   |
| Ukraine      | 22        | 1.17%   |
| Belgium      | 22        | 1.17%   |
| Sweden       | 19        | 1.01%   |
| Hungary      | 19        | 1.01%   |
| Finland      | 18        | 0.96%   |
| Mexico       | 17        | 0.91%   |
| Portugal     | 16        | 0.85%   |
| Czechia      | 15        | 0.8%    |
| Austria      | 15        | 0.8%    |
| Indonesia    | 13        | 0.69%   |
| India        | 13        | 0.69%   |
| Romania      | 12        | 0.64%   |
| Greece       | 12        | 0.64%   |
| Switzerland  | 11        | 0.59%   |
| Bulgaria     | 10        | 0.53%   |
| Turkey       | 9         | 0.48%   |
| Norway       | 8         | 0.43%   |
| Slovenia     | 7         | 0.37%   |
| Colombia     | 7         | 0.37%   |
| Denmark      | 6         | 0.32%   |
| Thailand     | 5         | 0.27%   |
| South Africa | 5         | 0.27%   |
| Peru         | 5         | 0.27%   |
| New Zealand  | 5         | 0.27%   |
| Lithuania    | 5         | 0.27%   |
| Uruguay      | 4         | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 25        | 1.27%   |
| Paris             | 25        | 1.27%   |
| Québec           | 19        | 0.97%   |
| Berlin            | 19        | 0.97%   |
| Moscow            | 18        | 0.92%   |
| Hamburg           | 16        | 0.81%   |
| Warsaw            | 13        | 0.66%   |
| Sydney            | 13        | 0.66%   |
| Munich            | 13        | 0.66%   |
| Sao Paulo         | 12        | 0.61%   |
| Budapest          | 12        | 0.61%   |
| Amsterdam         | 12        | 0.61%   |
| Rome              | 11        | 0.56%   |
| Milan             | 11        | 0.56%   |
| Madrid            | 11        | 0.56%   |
| Vancouver         | 10        | 0.51%   |
| Rio de Janeiro    | 10        | 0.51%   |
| St Petersburg     | 9         | 0.46%   |
| Montreal          | 9         | 0.46%   |
| Toronto           | 8         | 0.41%   |
| Frankfurt am Main | 8         | 0.41%   |
| Cologne           | 8         | 0.41%   |
| Chicago           | 8         | 0.41%   |
| Barcelona         | 8         | 0.41%   |
| Athens            | 8         | 0.41%   |
| Vienna            | 7         | 0.36%   |
| Kyiv              | 7         | 0.36%   |
| Helsinki          | 7         | 0.36%   |
| Belo Horizonte    | 7         | 0.36%   |
| Lisbon            | 6         | 0.31%   |
| Leipzig           | 6         | 0.31%   |
| Karlsruhe         | 6         | 0.31%   |
| Genoa             | 6         | 0.31%   |
| Springfield       | 5         | 0.25%   |
| Sofia             | 5         | 0.25%   |
| Seattle           | 5         | 0.25%   |
| Saint Paul        | 5         | 0.25%   |
| Pittsburgh        | 5         | 0.25%   |
| Mannheim          | 5         | 0.25%   |
| Lima              | 5         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 481       | 714    | 18.09%  |
| WDC                 | 451       | 645    | 16.96%  |
| Samsung Electronics | 373       | 504    | 14.03%  |
| Toshiba             | 183       | 226    | 6.88%   |
| Unknown             | 134       | 161    | 5.04%   |
| Kingston            | 131       | 160    | 4.93%   |
| Hitachi             | 128       | 170    | 4.81%   |
| SanDisk             | 98        | 127    | 3.69%   |
| Crucial             | 80        | 100    | 3.01%   |
| HGST                | 52        | 62     | 1.96%   |
| Intel               | 51        | 77     | 1.92%   |
| SK hynix            | 41        | 47     | 1.54%   |
| A-DATA Technology   | 41        | 50     | 1.54%   |
| Fujitsu             | 28        | 35     | 1.05%   |
| Micron Technology   | 24        | 26     | 0.9%    |
| China               | 22        | 23     | 0.83%   |
| Maxtor              | 20        | 27     | 0.75%   |
| Patriot             | 18        | 21     | 0.68%   |
| Intenso             | 18        | 25     | 0.68%   |
| PNY                 | 16        | 22     | 0.6%    |
| Phison              | 13        | 17     | 0.49%   |
| OCZ                 | 13        | 18     | 0.49%   |
| Transcend           | 12        | 13     | 0.45%   |
| KIOXIA              | 12        | 16     | 0.45%   |
| Apple               | 11        | 15     | 0.41%   |
| LITEON              | 10        | 12     | 0.38%   |
| Apacer              | 10        | 12     | 0.38%   |
| SPCC                | 7         | 12     | 0.26%   |
| Silicon Motion      | 7         | 7      | 0.26%   |
| LITEONIT            | 7         | 9      | 0.26%   |
| Hewlett-Packard     | 7         | 8      | 0.26%   |
| JMicron Technology  | 6         | 6      | 0.23%   |
| ASMT                | 6         | 8      | 0.23%   |
| KingSpec            | 5         | 6      | 0.19%   |
| GOODRAM             | 5         | 6      | 0.19%   |
| Unknown             | 5         | 5      | 0.19%   |
| USB3.0              | 4         | 5      | 0.15%   |
| Smartbuy            | 4         | 4      | 0.15%   |
| SABRENT             | 4         | 4      | 0.15%   |
| Mushkin             | 4         | 4      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 41        | 1.39%   |
| Unknown MMC Card  32GB              | 28        | 0.95%   |
| Seagate ST500DM002-1BD142 500GB     | 23        | 0.78%   |
| Samsung SSD 850 EVO 250GB           | 23        | 0.78%   |
| Kingston SA400S37480G 480GB SSD     | 23        | 0.78%   |
| Samsung SSD 860 EVO 500GB           | 22        | 0.75%   |
| Seagate ST500LT012-1DG142 500GB     | 19        | 0.65%   |
| Seagate ST1000DM010-2EP102 1TB      | 19        | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 18        | 0.61%   |
| Unknown MMC Card  64GB              | 17        | 0.58%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 17        | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB      | 15        | 0.51%   |
| Samsung SSD 860 EVO 1TB             | 15        | 0.51%   |
| Unknown SD/MMC/MS PRO 1TB           | 13        | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB      | 13        | 0.44%   |
| Seagate Expansion 2TB               | 13        | 0.44%   |
| HGST HTS721010A9E630 1TB            | 13        | 0.44%   |
| Crucial CT500MX500SSD1 500GB        | 13        | 0.44%   |
| Unknown MMC Card  128GB             | 12        | 0.41%   |
| Kingston SA400S37120G 120GB SSD     | 12        | 0.41%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.37%   |
| Toshiba MQ01ABD100 1TB              | 11        | 0.37%   |
| Seagate ST3500418AS 500GB           | 11        | 0.37%   |
| Seagate ST2000DM008-2FR102 2TB      | 11        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD    | 11        | 0.37%   |
| Unknown MMC Card  16GB              | 10        | 0.34%   |
| Seagate ST500LT012-9WS142 500GB     | 10        | 0.34%   |
| Seagate ST31000524AS 1TB            | 10        | 0.34%   |
| Seagate ST1000DM003-1CH162 1TB      | 10        | 0.34%   |
| Samsung NVMe SSD Drive 512GB        | 10        | 0.34%   |
| Samsung HM321HI 320GB               | 10        | 0.34%   |
| Seagate ST4000DM004-2CV104 4TB      | 9         | 0.31%   |
| Seagate ST31000528AS 1TB            | 9         | 0.31%   |
| Samsung SSD 860 EVO 250GB           | 9         | 0.31%   |
| Samsung SSD 850 EVO 500GB           | 9         | 0.31%   |
| Samsung NVMe SSD Drive 1TB          | 9         | 0.31%   |
| Patriot Burst 120GB SSD             | 9         | 0.31%   |
| Hitachi HTS547550A9E384 500GB       | 9         | 0.31%   |
| Hitachi HDS721050CLA362 500GB       | 9         | 0.31%   |
| HGST HTS541010A9E680 1TB            | 9         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 472       | 702    | 34.18%  |
| WDC                 | 390       | 560    | 28.24%  |
| Toshiba             | 151       | 189    | 10.93%  |
| Hitachi             | 128       | 170    | 9.27%   |
| Samsung Electronics | 96        | 123    | 6.95%   |
| HGST                | 52        | 62     | 3.77%   |
| Fujitsu             | 27        | 34     | 1.96%   |
| Maxtor              | 19        | 26     | 1.38%   |
| Unknown             | 14        | 16     | 1.01%   |
| USB3.0              | 4         | 5      | 0.29%   |
| Intenso             | 4         | 5      | 0.29%   |
| SABRENT             | 3         | 3      | 0.22%   |
| ASMT                | 3         | 5      | 0.22%   |
| WD MediaMax         | 2         | 2      | 0.14%   |
| Hewlett-Packard     | 2         | 2      | 0.14%   |
| Apple               | 2         | 3      | 0.14%   |
| SAGE                | 1         | 1      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| LaCie               | 1         | 4      | 0.07%   |
| ICY BOX             | 1         | 1      | 0.07%   |
| HPE                 | 1         | 4      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| ExcelStor           | 1         | 1      | 0.07%   |
| CLOVER              | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |
| Apricorn            | 1         | 1      | 0.07%   |
| ACASIS              | 1         | 1      | 0.07%   |
| Unknown             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 195       | 254    | 23.1%   |
| Kingston            | 120       | 147    | 14.22%  |
| SanDisk             | 78        | 104    | 9.24%   |
| Crucial             | 73        | 93     | 8.65%   |
| WDC                 | 41        | 49     | 4.86%   |
| A-DATA Technology   | 35        | 43     | 4.15%   |
| Intel               | 24        | 36     | 2.84%   |
| China               | 22        | 23     | 2.61%   |
| Patriot             | 18        | 21     | 2.13%   |
| Micron Technology   | 17        | 18     | 2.01%   |
| PNY                 | 16        | 22     | 1.9%    |
| Toshiba             | 15        | 18     | 1.78%   |
| SK hynix            | 13        | 13     | 1.54%   |
| OCZ                 | 12        | 16     | 1.42%   |
| Intenso             | 12        | 14     | 1.42%   |
| Transcend           | 11        | 11     | 1.3%    |
| LITEON              | 10        | 12     | 1.18%   |
| Apacer              | 10        | 12     | 1.18%   |
| SPCC                | 7         | 12     | 0.83%   |
| LITEONIT            | 7         | 9      | 0.83%   |
| Unknown             | 5         | 6      | 0.59%   |
| GOODRAM             | 5         | 6      | 0.59%   |
| Apple               | 5         | 6      | 0.59%   |
| Smartbuy            | 4         | 4      | 0.47%   |
| Mushkin             | 4         | 4      | 0.47%   |
| KingSpec            | 4         | 5      | 0.47%   |
| KingDian            | 4         | 4      | 0.47%   |
| Hewlett-Packard     | 4         | 6      | 0.47%   |
| Corsair             | 4         | 4      | 0.47%   |
| Team                | 3         | 4      | 0.36%   |
| Seagate             | 3         | 3      | 0.36%   |
| Lexar               | 3         | 3      | 0.36%   |
| Kingmax             | 3         | 3      | 0.36%   |
| Drevo               | 3         | 3      | 0.36%   |
| ASMT                | 3         | 3      | 0.36%   |
| TO Exter            | 2         | 2      | 0.24%   |
| SUNEAST             | 2         | 3      | 0.24%   |
| OWC                 | 2         | 2      | 0.24%   |
| OCZ-VERTEX3         | 2         | 2      | 0.24%   |
| Netac               | 2         | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1137      | 1925   | 48.3%   |
| SSD     | 757       | 1050   | 32.16%  |
| NVMe    | 306       | 390    | 13%     |
| MMC     | 117       | 141    | 4.97%   |
| Unknown | 37        | 46     | 1.57%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1582      | 2871   | 74.66%  |
| NVMe | 303       | 386    | 14.3%   |
| SAS  | 117       | 154    | 5.52%   |
| MMC  | 117       | 141    | 5.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1238      | 1856   | 62.43%  |
| 0.51-1.0   | 490       | 702    | 24.71%  |
| 1.01-2.0   | 144       | 226    | 7.26%   |
| 3.01-4.0   | 46        | 86     | 2.32%   |
| 2.01-3.0   | 32        | 57     | 1.61%   |
| 4.01-10.0  | 30        | 45     | 1.51%   |
| 10.01-20.0 | 2         | 2      | 0.1%    |
| 0          | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 610       | 31.59%  |
| 251-500        | 452       | 23.41%  |
| 501-1000       | 268       | 13.88%  |
| 51-100         | 138       | 7.15%   |
| 1001-2000      | 135       | 6.99%   |
| 21-50          | 102       | 5.28%   |
| More than 3000 | 85        | 4.4%    |
| 1-20           | 80        | 4.14%   |
| 2001-3000      | 49        | 2.54%   |
| Unknown        | 12        | 0.62%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 738       | 36.83%  |
| 21-50          | 350       | 17.47%  |
| 101-250        | 289       | 14.42%  |
| 51-100         | 258       | 12.87%  |
| 251-500        | 141       | 7.04%   |
| 501-1000       | 103       | 5.14%   |
| 1001-2000      | 58        | 2.89%   |
| More than 3000 | 34        | 1.7%    |
| 2001-3000      | 21        | 1.05%   |
| Unknown        | 12        | 0.6%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 4         | 4      | 2.38%   |
| Seagate ST500LT012-9WS142 500GB    | 3         | 3      | 1.79%   |
| Seagate ST500DM002-1BD142 500GB    | 3         | 3      | 1.79%   |
| Hitachi HDS721050CLA362 500GB      | 3         | 3      | 1.79%   |
| WDC WD7500BPKX-00HPJT0 752GB       | 2         | 2      | 1.19%   |
| WDC WD4000FYYZ-01UL1B1 4TB         | 2         | 3      | 1.19%   |
| WDC WD1002FAEX-00Z3A0 1TB          | 2         | 2      | 1.19%   |
| Toshiba MQ01ABD100 1TB             | 2         | 3      | 1.19%   |
| Seagate ST9320325AS 320GB          | 2         | 2      | 1.19%   |
| Seagate ST3250318AS 250GB          | 2         | 2      | 1.19%   |
| Seagate ST2000DM001-1CH164 2TB     | 2         | 3      | 1.19%   |
| Seagate ST1000DL002-9TT153 1TB     | 2         | 2      | 1.19%   |
| Samsung Electronics HD103SI 1TB    | 2         | 2      | 1.19%   |
| Samsung Electronics HD081GJ 80GB   | 2         | 2      | 1.19%   |
| Kingston SA400S37240G 240GB SSD    | 2         | 2      | 1.19%   |
| Hitachi HTS725032A9A364 320GB      | 2         | 2      | 1.19%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.19%   |
| HGST HTS545050A7E680 500GB         | 2         | 2      | 1.19%   |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 1      | 0.6%    |
| WDC WD6400AAKS-22A7B2 640GB        | 1         | 1      | 0.6%    |
| WDC WD6400AAKS-22A7B0 640GB        | 1         | 1      | 0.6%    |
| WDC WD5000LPVX-08V0TT5 500GB       | 1         | 1      | 0.6%    |
| WDC WD5000LPCX-00VHAT0 500GB       | 1         | 1      | 0.6%    |
| WDC WD5000BEVT-22ZAT0 500GB        | 1         | 1      | 0.6%    |
| WDC WD5000BEKT-75KA9T0 500GB       | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-08U6AA0 500GB       | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-08ERMA0 500GB       | 1         | 1      | 0.6%    |
| WDC WD5000AAKS-22V1A0 500GB        | 1         | 1      | 0.6%    |
| WDC WD5000AAKS-00A7B0 500GB        | 1         | 1      | 0.6%    |
| WDC WD400EB-00CPF0 40GB            | 1         | 1      | 0.6%    |
| WDC WD3200BEVT-75ZCT1 320GB        | 1         | 1      | 0.6%    |
| WDC WD3200AVJS-63TBA0 320GB        | 1         | 1      | 0.6%    |
| WDC WD3200AAKS-00L9A0 320GB        | 1         | 1      | 0.6%    |
| WDC WD3200AAJS-60Z0A0 320GB        | 1         | 1      | 0.6%    |
| WDC WD3200AAJS-08L7A0 320GB        | 1         | 1      | 0.6%    |
| WDC WD20EZRX-00D8PB0 2TB           | 1         | 2      | 0.6%    |
| WDC WD20EFRX-68EUZN0 2TB           | 1         | 1      | 0.6%    |
| WDC WD1600BJKT-75F4T0 160GB        | 1         | 1      | 0.6%    |
| WDC WD1600AAJS-00L7A0 160GB        | 1         | 1      | 0.6%    |
| WDC WD10SPCX-24HWST1 1TB           | 1         | 1      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 51     | 28.83%  |
| WDC                 | 34        | 40     | 20.86%  |
| Toshiba             | 16        | 20     | 9.82%   |
| Hitachi             | 14        | 14     | 8.59%   |
| Samsung Electronics | 12        | 15     | 7.36%   |
| SK hynix            | 5         | 5      | 3.07%   |
| HGST                | 5         | 6      | 3.07%   |
| Kingston            | 4         | 4      | 2.45%   |
| Fujitsu             | 4         | 5      | 2.45%   |
| A-DATA Technology   | 3         | 4      | 1.84%   |
| OCZ                 | 2         | 2      | 1.23%   |
| Micron Technology   | 2         | 2      | 1.23%   |
| Maxtor              | 2         | 2      | 1.23%   |
| Intel               | 2         | 2      | 1.23%   |
| Unknown             | 1         | 1      | 0.61%   |
| SanDisk             | 1         | 1      | 0.61%   |
| Mushkin             | 1         | 1      | 0.61%   |
| LDLC                | 1         | 1      | 0.61%   |
| ICY BOX             | 1         | 1      | 0.61%   |
| FORESEE             | 1         | 1      | 0.61%   |
| Crucial             | 1         | 1      | 0.61%   |
| China               | 1         | 1      | 0.61%   |
| Avant               | 1         | 1      | 0.61%   |
| Apple               | 1         | 1      | 0.61%   |
| Apacer              | 1         | 1      | 0.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 51     | 35.34%  |
| WDC                 | 34        | 40     | 25.56%  |
| Toshiba             | 16        | 20     | 12.03%  |
| Hitachi             | 14        | 14     | 10.53%  |
| Samsung Electronics | 10        | 12     | 7.52%   |
| HGST                | 5         | 6      | 3.76%   |
| Fujitsu             | 4         | 5      | 3.01%   |
| Maxtor              | 2         | 2      | 1.5%    |
| ICY BOX             | 1         | 1      | 0.75%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 125       | 151    | 80.65%  |
| SSD  | 28        | 30     | 18.06%  |
| NVMe | 2         | 2      | 1.29%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Toshiba DT01ACA200 2TB           | 1         | 1      | 33.33%  |
| Seagate ST500DM002-1BC142 500GB  | 1         | 1      | 33.33%  |
| A-DATA Technology SP800 32GB SSD | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 1         | 1      | 33.33%  |
| Seagate           | 1         | 1      | 33.33%  |
| A-DATA Technology | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1219      | 2417   | 61.6%   |
| Works    | 604       | 949    | 30.52%  |
| Malfunc  | 153       | 183    | 7.73%   |
| Failed   | 3         | 3      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1296      | 60.87%  |
| AMD                              | 348       | 16.35%  |
| Samsung Electronics              | 105       | 4.93%   |
| Nvidia                           | 59        | 2.77%   |
| SanDisk                          | 47        | 2.21%   |
| ASMedia Technology               | 36        | 1.69%   |
| JMicron Technology               | 32        | 1.5%    |
| Marvell Technology Group         | 26        | 1.22%   |
| SK hynix                         | 23        | 1.08%   |
| VIA Technologies                 | 16        | 0.75%   |
| Toshiba America Info Systems     | 14        | 0.66%   |
| KIOXIA                           | 14        | 0.66%   |
| Phison Electronics               | 13        | 0.61%   |
| Kingston Technology Company      | 11        | 0.52%   |
| Micron/Crucial Technology        | 9         | 0.42%   |
| LSI Logic / Symbios Logic        | 9         | 0.42%   |
| ADATA Technology                 | 9         | 0.42%   |
| Silicon Motion                   | 8         | 0.38%   |
| Micron Technology                | 8         | 0.38%   |
| Silicon Integrated Systems [SiS] | 6         | 0.28%   |
| Realtek Semiconductor            | 6         | 0.28%   |
| Silicon Image                    | 5         | 0.23%   |
| Broadcom / LSI                   | 5         | 0.23%   |
| Hewlett-Packard                  | 4         | 0.19%   |
| Apple                            | 4         | 0.19%   |
| Union Memory (Shenzhen)          | 3         | 0.14%   |
| Seagate Technology               | 2         | 0.09%   |
| Promise Technology               | 2         | 0.09%   |
| Integrated Technology Express    | 2         | 0.09%   |
| Adaptec                          | 2         | 0.09%   |
| Unknown                          | 1         | 0.05%   |
| Solid State Storage Technology   | 1         | 0.05%   |
| OCZ Technology Group             | 1         | 0.05%   |
| Lite-On Technology               | 1         | 0.05%   |
| Lenovo                           | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 216       | 8.18%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 96        | 3.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 83        | 3.14%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 68        | 2.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 67        | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 66        | 2.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 61        | 2.31%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 60        | 2.27%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 58        | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 58        | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 56        | 2.12%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 56        | 2.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 53        | 2.01%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 52        | 1.97%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 49        | 1.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 39        | 1.48%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 39        | 1.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 38        | 1.44%   |
| AMD 400 Series Chipset SATA Controller                                                  | 37        | 1.4%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 36        | 1.36%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 34        | 1.29%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 34        | 1.29%   |
| Intel SATA Controller [RAID mode]                                                       | 33        | 1.25%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 32        | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 27        | 1.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 24        | 0.91%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 22        | 0.83%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 22        | 0.83%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 22        | 0.83%   |
| Nvidia MCP61 SATA Controller                                                            | 21        | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 21        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 21        | 0.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 20        | 0.76%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 20        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 19        | 0.72%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 19        | 0.72%   |
| Nvidia MCP61 IDE                                                                        | 18        | 0.68%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 18        | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 17        | 0.64%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 17        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1336      | 59.48%  |
| IDE  | 457       | 20.35%  |
| NVMe | 295       | 13.13%  |
| RAID | 142       | 6.32%   |
| SAS  | 9         | 0.4%    |
| SCSI | 7         | 0.31%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1421      | 76.03%  |
| AMD          | 422       | 22.58%  |
| ARM          | 24        | 1.28%   |
| CentaurHauls | 2         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| ARM Processor                                 | 19        | 1.01%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 17        | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.75%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 14        | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 13        | 0.69%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 12        | 0.64%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 12        | 0.64%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 11        | 0.59%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 11        | 0.59%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 10        | 0.53%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.53%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 10        | 0.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 10        | 0.53%   |
| Intel Core i3-4130 CPU @ 3.40GHz              | 10        | 0.53%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 10        | 0.53%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 10        | 0.53%   |
| AMD FX-8350 Eight-Core Processor              | 10        | 0.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.48%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 9         | 0.48%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 9         | 0.48%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 9         | 0.48%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz          | 9         | 0.48%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 9         | 0.48%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 9         | 0.48%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 9         | 0.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.43%   |
| Intel Core i5-6400 CPU @ 2.70GHz              | 8         | 0.43%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.43%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 8         | 0.43%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.43%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.43%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 8         | 0.43%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 8         | 0.43%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 8         | 0.43%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 8         | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 8         | 0.43%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 8         | 0.43%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz   | 7         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 349       | 18.61%  |
| Intel Core i7           | 295       | 15.73%  |
| Intel Core i3           | 167       | 8.91%   |
| Intel Core 2 Duo        | 146       | 7.79%   |
| Intel Celeron           | 112       | 5.97%   |
| Intel Pentium           | 65        | 3.47%   |
| Other                   | 62        | 3.31%   |
| AMD Ryzen 5             | 62        | 3.31%   |
| Intel Xeon              | 51        | 2.72%   |
| Intel Pentium Dual-Core | 47        | 2.51%   |
| Intel Atom              | 46        | 2.45%   |
| AMD Ryzen 7             | 44        | 2.35%   |
| AMD FX                  | 28        | 1.49%   |
| Intel Core 2 Quad       | 26        | 1.39%   |
| AMD A8                  | 23        | 1.23%   |
| Intel Core 2            | 22        | 1.17%   |
| Intel Pentium Dual      | 21        | 1.12%   |
| AMD A6                  | 18        | 0.96%   |
| AMD E1                  | 17        | 0.91%   |
| AMD Athlon II X2        | 17        | 0.91%   |
| AMD Ryzen 3             | 16        | 0.85%   |
| AMD Phenom II X4        | 16        | 0.85%   |
| AMD Athlon 64 X2        | 14        | 0.75%   |
| AMD A10                 | 14        | 0.75%   |
| AMD Ryzen 9             | 12        | 0.64%   |
| AMD E                   | 12        | 0.64%   |
| AMD A4                  | 12        | 0.64%   |
| Intel Core i9           | 9         | 0.48%   |
| AMD Turion 64 X2 Mobile | 9         | 0.48%   |
| AMD Ryzen 7 PRO         | 9         | 0.48%   |
| AMD E2                  | 8         | 0.43%   |
| AMD Athlon              | 8         | 0.43%   |
| Intel Genuine           | 7         | 0.37%   |
| Intel Pentium Silver    | 6         | 0.32%   |
| AMD Ryzen 5 PRO         | 6         | 0.32%   |
| AMD Athlon II X4        | 6         | 0.32%   |
| Intel Pentium D         | 5         | 0.27%   |
| Intel Pentium 4         | 5         | 0.27%   |
| AMD Sempron             | 5         | 0.27%   |
| AMD Phenom II X6        | 5         | 0.27%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 909       | 48.53%  |
| 4      | 677       | 36.15%  |
| 6      | 111       | 5.93%   |
| 8      | 79        | 4.22%   |
| 1      | 59        | 3.15%   |
| 12     | 16        | 0.85%   |
| 3      | 9         | 0.48%   |
| 16     | 7         | 0.37%   |
| 10     | 3         | 0.16%   |
| 24     | 1         | 0.05%   |
| 20     | 1         | 0.05%   |
| 14     | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1847      | 98.82%  |
| 2      | 22        | 1.18%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 989       | 52.83%  |
| 1      | 883       | 47.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1852      | 99.09%  |
| Unknown        | 17        | 0.91%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 220       | 11.55%  |
| 0x206a7    | 158       | 8.3%    |
| 0x306a9    | 137       | 7.2%    |
| 0x1067a    | 125       | 6.57%   |
| 0x306c3    | 94        | 4.94%   |
| 0x6fd      | 60        | 3.15%   |
| 0x20655    | 46        | 2.42%   |
| 0x10676    | 38        | 2%      |
| 0x506e3    | 36        | 1.89%   |
| 0x40651    | 34        | 1.79%   |
| 0x906ea    | 33        | 1.73%   |
| 0x806ea    | 32        | 1.68%   |
| 0x30678    | 32        | 1.68%   |
| 0x010000c8 | 32        | 1.68%   |
| 0x406e3    | 30        | 1.58%   |
| 0x906e9    | 27        | 1.42%   |
| 0x08108109 | 27        | 1.42%   |
| 0x806ec    | 26        | 1.37%   |
| 0x20652    | 25        | 1.31%   |
| 0x806e9    | 24        | 1.26%   |
| 0x6fb      | 24        | 1.26%   |
| 0x306d4    | 24        | 1.26%   |
| 0x406c4    | 23        | 1.21%   |
| 0x06000852 | 23        | 1.21%   |
| 0x05000119 | 22        | 1.16%   |
| 0x806c1    | 21        | 1.1%    |
| 0x0800820d | 21        | 1.1%    |
| 0xa0653    | 19        | 1%      |
| 0x6f6      | 19        | 1%      |
| 0x08701021 | 19        | 1%      |
| 0x07030105 | 19        | 1%      |
| 0xa0652    | 17        | 0.89%   |
| 0x406c3    | 17        | 0.89%   |
| 0x106e5    | 17        | 0.89%   |
| 0x0700010f | 17        | 0.89%   |
| 0x706a1    | 15        | 0.79%   |
| 0x706e5    | 14        | 0.74%   |
| 0x106ca    | 14        | 0.74%   |
| 0x06001119 | 14        | 0.74%   |
| 0x906ed    | 13        | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 182       | 9.72%   |
| SandyBridge      | 178       | 9.5%    |
| Penryn           | 175       | 9.34%   |
| Haswell          | 153       | 8.17%   |
| IvyBridge        | 152       | 8.12%   |
| Core             | 123       | 6.57%   |
| Westmere         | 85        | 4.54%   |
| Silvermont       | 79        | 4.22%   |
| Skylake          | 77        | 4.11%   |
| K10              | 63        | 3.36%   |
| Zen+             | 60        | 3.2%    |
| Zen 2            | 49        | 2.62%   |
| CometLake        | 43        | 2.3%    |
| Piledriver       | 41        | 2.19%   |
| K8 Hammer        | 39        | 2.08%   |
| Unknown          | 34        | 1.82%   |
| Zen              | 32        | 1.71%   |
| Bobcat           | 30        | 1.6%    |
| Broadwell        | 29        | 1.55%   |
| Nehalem          | 27        | 1.44%   |
| TigerLake        | 24        | 1.28%   |
| Puma             | 24        | 1.28%   |
| Goldmont plus    | 22        | 1.17%   |
| IceLake          | 21        | 1.12%   |
| Bonnell          | 21        | 1.12%   |
| Jaguar           | 18        | 0.96%   |
| Excavator        | 17        | 0.91%   |
| Zen 3            | 16        | 0.85%   |
| Goldmont         | 16        | 0.85%   |
| K10 Llano        | 12        | 0.64%   |
| NetBurst         | 11        | 0.59%   |
| K8 & K10 hybrid  | 7         | 0.37%   |
| Steamroller      | 6         | 0.32%   |
| Bulldozer        | 5         | 0.27%   |
| Alderlake Hybrid | 2         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1044      | 49.55%  |
| Nvidia                           | 572       | 27.15%  |
| AMD                              | 470       | 22.31%  |
| Matrox Electronics Systems       | 10        | 0.47%   |
| VIA Technologies                 | 6         | 0.28%   |
| Silicon Integrated Systems [SiS] | 3         | 0.14%   |
| ASPEED Technology                | 2         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 127       | 5.79%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 85        | 3.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 56        | 2.55%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 53        | 2.42%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 41        | 1.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 40        | 1.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 39        | 1.78%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 38        | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 38        | 1.73%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 37        | 1.69%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 37        | 1.69%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 36        | 1.64%   |
| Intel UHD Graphics 620                                                                   | 35        | 1.6%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 31        | 1.41%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31        | 1.41%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 28        | 1.28%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 27        | 1.23%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 26        | 1.19%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 24        | 1.09%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 24        | 1.09%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 1%      |
| Intel HD Graphics 620                                                                    | 22        | 1%      |
| Intel HD Graphics 530                                                                    | 22        | 1%      |
| AMD Renoir                                                                               | 19        | 0.87%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18        | 0.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 18        | 0.82%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 17        | 0.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 17        | 0.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 17        | 0.77%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 17        | 0.77%   |
| Intel HD Graphics 5500                                                                   | 16        | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 16        | 0.73%   |
| Intel HD Graphics 630                                                                    | 15        | 0.68%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 15        | 0.68%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 14        | 0.64%   |
| Nvidia GT218 [GeForce 210]                                                               | 13        | 0.59%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 13        | 0.59%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 13        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 12        | 0.55%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 11        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 817       | 43.5%   |
| 1 x Nvidia               | 382       | 20.34%  |
| 1 x AMD                  | 378       | 20.13%  |
| Intel + Nvidia           | 161       | 8.57%   |
| Intel + AMD              | 46        | 2.45%   |
| Other                    | 26        | 1.38%   |
| 2 x AMD                  | 25        | 1.33%   |
| AMD + Nvidia             | 16        | 0.85%   |
| 1 x Matrox               | 7         | 0.37%   |
| 1 x VIA                  | 6         | 0.32%   |
| 2 x Nvidia               | 4         | 0.21%   |
| 1 x SiS                  | 3         | 0.16%   |
| Nvidia + ASPEED          | 2         | 0.11%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.05%   |
| 2 x AMD + 1 x Nvidia     | 1         | 0.05%   |
| Nvidia + Matrox          | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + Matrox             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1471      | 78.12%  |
| Proprietary | 326       | 17.31%  |
| Unknown     | 86        | 4.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 983       | 51.87%  |
| 0.01-0.5   | 297       | 15.67%  |
| 1.01-2.0   | 209       | 11.03%  |
| 0.51-1.0   | 206       | 10.87%  |
| 3.01-4.0   | 115       | 6.07%   |
| 7.01-8.0   | 41        | 2.16%   |
| 5.01-6.0   | 25        | 1.32%   |
| 8.01-16.0  | 9         | 0.47%   |
| 2.01-3.0   | 8         | 0.42%   |
| 4.01-5.0   | 1         | 0.05%   |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 278       | 14.07%  |
| AU Optronics            | 205       | 10.37%  |
| LG Display              | 189       | 9.56%   |
| Chimei Innolux          | 122       | 6.17%   |
| Dell                    | 118       | 5.97%   |
| BOE                     | 108       | 5.47%   |
| Goldstar                | 87        | 4.4%    |
| Hewlett-Packard         | 79        | 4%      |
| Acer                    | 71        | 3.59%   |
| AOC                     | 52        | 2.63%   |
| Philips                 | 50        | 2.53%   |
| Chi Mei Optoelectronics | 49        | 2.48%   |
| Lenovo                  | 48        | 2.43%   |
| Ancor Communications    | 40        | 2.02%   |
| BenQ                    | 33        | 1.67%   |
| Apple                   | 31        | 1.57%   |
| LG Philips              | 24        | 1.21%   |
| Unknown                 | 22        | 1.11%   |
| HannStar                | 22        | 1.11%   |
| ViewSonic               | 21        | 1.06%   |
| Sony                    | 21        | 1.06%   |
| LG Electronics          | 21        | 1.06%   |
| Iiyama                  | 21        | 1.06%   |
| Fujitsu Siemens         | 19        | 0.96%   |
| Sharp                   | 17        | 0.86%   |
| Panasonic               | 16        | 0.81%   |
| InfoVision              | 14        | 0.71%   |
| NEC Computers           | 10        | 0.51%   |
| Medion                  | 9         | 0.46%   |
| Toshiba                 | 8         | 0.4%    |
| PANDA                   | 8         | 0.4%    |
| Eizo                    | 8         | 0.4%    |
| Vizio                   | 7         | 0.35%   |
| ASUSTek Computer        | 6         | 0.3%    |
| Vestel Elektronik       | 5         | 0.25%   |
| Lenovo Group Limited    | 5         | 0.25%   |
| MStar                   | 4         | 0.2%    |
| LPL                     | 4         | 0.2%    |
| LGD                     | 4         | 0.2%    |
| Idek Iiyama             | 4         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                       | 15        | 0.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 9         | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 9         | 0.44%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                       | 8         | 0.39%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 8         | 0.39%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 0.39%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                      | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 7         | 0.34%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 7         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.3%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 5         | 0.25%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                    | 5         | 0.25%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.25%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 5         | 0.25%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch        | 4         | 0.2%    |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 4         | 0.2%    |
| MStar Demo MST0030 1920x1080 708x398mm 32.0-inch                         | 4         | 0.2%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 4         | 0.2%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 4         | 0.2%    |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 4         | 0.2%    |
| Lenovo LCD Monitor LEN40A0 1366x768 309x174mm 14.0-inch                  | 4         | 0.2%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 4         | 0.2%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 4         | 0.2%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 4         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 4         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1130 1366x768 256x144mm 11.6-inch          | 4         | 0.2%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.2%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 4         | 0.2%    |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 4         | 0.2%    |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.2%    |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 4         | 0.2%    |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch            | 4         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 709       | 36.95%  |
| 1366x768 (WXGA)    | 434       | 22.62%  |
| 1280x1024 (SXGA)   | 97        | 5.05%   |
| 1600x900 (HD+)     | 95        | 4.95%   |
| 1440x900 (WXGA+)   | 91        | 4.74%   |
| 1280x800 (WXGA)    | 87        | 4.53%   |
| 3840x2160 (4K)     | 79        | 4.12%   |
| 1680x1050 (WSXGA+) | 66        | 3.44%   |
| 2560x1440 (QHD)    | 41        | 2.14%   |
| 1920x1200 (WUXGA)  | 41        | 2.14%   |
| Unknown            | 35        | 1.82%   |
| 1360x768           | 23        | 1.2%    |
| 1024x600           | 13        | 0.68%   |
| 3840x1080          | 12        | 0.63%   |
| 1600x1200          | 11        | 0.57%   |
| 1024x768 (XGA)     | 11        | 0.57%   |
| 2560x1600          | 7         | 0.36%   |
| 1920x540           | 7         | 0.36%   |
| 1280x720 (HD)      | 7         | 0.36%   |
| 3440x1440          | 6         | 0.31%   |
| 5120x1440          | 4         | 0.21%   |
| 2560x1080          | 4         | 0.21%   |
| 3840x1200          | 3         | 0.16%   |
| 3200x1800 (QHD+)   | 3         | 0.16%   |
| 3200x1080          | 3         | 0.16%   |
| 2880x1800          | 3         | 0.16%   |
| 2288x1287          | 3         | 0.16%   |
| 3840x2400          | 2         | 0.1%    |
| 3286x1080          | 2         | 0.1%    |
| 3200x900           | 2         | 0.1%    |
| 2960x1050          | 2         | 0.1%    |
| 6400x1440          | 1         | 0.05%   |
| 5760x2160          | 1         | 0.05%   |
| 5760x1200          | 1         | 0.05%   |
| 5280x2160          | 1         | 0.05%   |
| 4480x1440          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3360x1080          | 1         | 0.05%   |
| 3280x1080          | 1         | 0.05%   |
| 3200x1024          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 452       | 23.1%   |
| 14      | 165       | 8.43%   |
| Unknown | 162       | 8.28%   |
| 13      | 142       | 7.26%   |
| 17      | 137       | 7%      |
| 24      | 116       | 5.93%   |
| 23      | 116       | 5.93%   |
| 21      | 102       | 5.21%   |
| 19      | 95        | 4.85%   |
| 27      | 84        | 4.29%   |
| 18      | 59        | 3.01%   |
| 20      | 45        | 2.3%    |
| 22      | 39        | 1.99%   |
| 31      | 38        | 1.94%   |
| 12      | 35        | 1.79%   |
| 11      | 28        | 1.43%   |
| 84      | 17        | 0.87%   |
| 10      | 17        | 0.87%   |
| 72      | 10        | 0.51%   |
| 54      | 9         | 0.46%   |
| 40      | 9         | 0.46%   |
| 34      | 9         | 0.46%   |
| 16      | 9         | 0.46%   |
| 32      | 8         | 0.41%   |
| 25      | 8         | 0.41%   |
| 26      | 7         | 0.36%   |
| 52      | 6         | 0.31%   |
| 48      | 5         | 0.26%   |
| 37      | 4         | 0.2%    |
| 28      | 4         | 0.2%    |
| 57      | 2         | 0.1%    |
| 49      | 2         | 0.1%    |
| 47      | 2         | 0.1%    |
| 46      | 2         | 0.1%    |
| 29      | 2         | 0.1%    |
| 142     | 1         | 0.05%   |
| 74      | 1         | 0.05%   |
| 69      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |
| 60      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 724       | 37.42%  |
| 501-600        | 307       | 15.87%  |
| 401-500        | 276       | 14.26%  |
| 351-400        | 166       | 8.58%   |
| Unknown        | 162       | 8.37%   |
| 201-300        | 149       | 7.7%    |
| 601-700        | 57        | 2.95%   |
| 1501-2000      | 29        | 1.5%    |
| 1001-1500      | 29        | 1.5%    |
| 701-800        | 17        | 0.88%   |
| 801-900        | 15        | 0.78%   |
| 901-1000       | 2         | 0.1%    |
| More than 2000 | 1         | 0.05%   |
| 101-200        | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1228      | 68%     |
| 16/10   | 281       | 15.56%  |
| Unknown | 150       | 8.31%   |
| 5/4     | 95        | 5.26%   |
| 4/3     | 27        | 1.5%    |
| 21/9    | 9         | 0.5%    |
| 3/2     | 8         | 0.44%   |
| 6/5     | 3         | 0.17%   |
| 32/9    | 1         | 0.06%   |
| 3.20    | 1         | 0.06%   |
| 1.96    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 454       | 23.32%  |
| 201-250        | 304       | 15.61%  |
| 81-90          | 248       | 12.74%  |
| 151-200        | 175       | 8.99%   |
| Unknown        | 162       | 8.32%   |
| 301-350        | 88        | 4.52%   |
| 141-150        | 87        | 4.47%   |
| 121-130        | 74        | 3.8%    |
| 351-500        | 58        | 2.98%   |
| More than 1000 | 54        | 2.77%   |
| 71-80          | 53        | 2.72%   |
| 251-300        | 53        | 2.72%   |
| 61-70          | 33        | 1.69%   |
| 51-60          | 28        | 1.44%   |
| 131-140        | 23        | 1.18%   |
| 501-1000       | 23        | 1.18%   |
| 41-50          | 17        | 0.87%   |
| 91-100         | 7         | 0.36%   |
| 111-120        | 5         | 0.26%   |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 705       | 37.3%   |
| 101-120       | 527       | 27.88%  |
| 121-160       | 380       | 20.11%  |
| Unknown       | 162       | 8.57%   |
| 161-240       | 53        | 2.8%    |
| 1-50          | 49        | 2.59%   |
| More than 240 | 14        | 0.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1545      | 81.44%  |
| 2     | 249       | 13.13%  |
| 0     | 83        | 4.38%   |
| 3     | 17        | 0.9%    |
| 4     | 3         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1002      | 35.44%  |
| Intel                             | 799       | 28.26%  |
| Qualcomm Atheros                  | 345       | 12.2%   |
| Broadcom                          | 211       | 7.46%   |
| Nvidia                            | 48        | 1.7%    |
| Marvell Technology Group          | 47        | 1.66%   |
| Ralink Technology                 | 39        | 1.38%   |
| Broadcom Limited                  | 37        | 1.31%   |
| TP-Link                           | 36        | 1.27%   |
| Ralink                            | 32        | 1.13%   |
| Qualcomm Atheros Communications   | 17        | 0.6%    |
| Samsung Electronics               | 15        | 0.53%   |
| NetGear                           | 13        | 0.46%   |
| Huawei Technologies               | 13        | 0.46%   |
| D-Link System                     | 12        | 0.42%   |
| JMicron Technology                | 11        | 0.39%   |
| MediaTek                          | 10        | 0.35%   |
| Sierra Wireless                   | 9         | 0.32%   |
| D-Link                            | 9         | 0.32%   |
| VIA Technologies                  | 8         | 0.28%   |
| Ericsson Business Mobile Networks | 7         | 0.25%   |
| Edimax Technology                 | 7         | 0.25%   |
| Xiaomi                            | 6         | 0.21%   |
| DisplayLink                       | 6         | 0.21%   |
| ASUSTek Computer                  | 6         | 0.21%   |
| Silicon Integrated Systems [SiS]  | 5         | 0.18%   |
| Lenovo                            | 5         | 0.18%   |
| Belkin Components                 | 5         | 0.18%   |
| Qualcomm                          | 4         | 0.14%   |
| Microsoft                         | 4         | 0.14%   |
| Linksys                           | 4         | 0.14%   |
| Dell                              | 4         | 0.14%   |
| AVM                               | 4         | 0.14%   |
| Attansic Technology               | 4         | 0.14%   |
| ASIX Electronics                  | 4         | 0.14%   |
| Aquantia                          | 4         | 0.14%   |
| TRENDnet                          | 3         | 0.11%   |
| FIBOCOM                           | 3         | 0.11%   |
| Motorola PCS                      | 2         | 0.07%   |
| LG Electronics                    | 2         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 666       | 20.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 165       | 5.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 100       | 3.05%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 53        | 1.62%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 49        | 1.5%    |
| Intel Wi-Fi 6 AX200                                                     | 45        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 43        | 1.31%   |
| Intel Ethernet Connection I217-LM                                       | 39        | 1.19%   |
| Intel Wireless 8265 / 8275                                              | 36        | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 34        | 1.04%   |
| Intel Wireless 7260                                                     | 33        | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 0.98%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 31        | 0.95%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 0.85%   |
| Intel Wireless 7265                                                     | 28        | 0.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.73%   |
| Intel I211 Gigabit Network Connection                                   | 24        | 0.73%   |
| Intel 82579V Gigabit Network Connection                                 | 24        | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 22        | 0.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 21        | 0.64%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 21        | 0.64%   |
| Intel Wireless 8260                                                     | 21        | 0.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 0.61%   |
| Nvidia MCP61 Ethernet                                                   | 20        | 0.61%   |
| Intel Wireless-AC 9260                                                  | 20        | 0.61%   |
| Intel Ethernet Connection (2) I219-V                                    | 20        | 0.61%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 19        | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 19        | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 18        | 0.55%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                | 18        | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 17        | 0.52%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 0.49%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 16        | 0.49%   |
| Ralink MT7601U Wireless Adapter                                         | 16        | 0.49%   |
| Intel Wireless 3165                                                     | 16        | 0.49%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 0.49%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 524       | 37.11%  |
| Qualcomm Atheros                      | 281       | 19.9%   |
| Realtek Semiconductor                 | 247       | 17.49%  |
| Broadcom                              | 130       | 9.21%   |
| Ralink Technology                     | 39        | 2.76%   |
| TP-Link                               | 34        | 2.41%   |
| Ralink                                | 32        | 2.27%   |
| Broadcom Limited                      | 18        | 1.27%   |
| Qualcomm Atheros Communications       | 17        | 1.2%    |
| NetGear                               | 13        | 0.92%   |
| Sierra Wireless                       | 9         | 0.64%   |
| D-Link                                | 9         | 0.64%   |
| D-Link System                         | 8         | 0.57%   |
| Edimax Technology                     | 7         | 0.5%    |
| ASUSTek Computer                      | 6         | 0.42%   |
| Belkin Components                     | 5         | 0.35%   |
| Microsoft                             | 4         | 0.28%   |
| MediaTek                              | 4         | 0.28%   |
| Linksys                               | 4         | 0.28%   |
| AVM                                   | 4         | 0.28%   |
| TRENDnet                              | 3         | 0.21%   |
| FIBOCOM                               | 3         | 0.21%   |
| IMC Networks                          | 2         | 0.14%   |
| Dell                                  | 2         | 0.14%   |
| ZyXEL Communications                  | 1         | 0.07%   |
| ZyDAS                                 | 1         | 0.07%   |
| Qualcomm                              | 1         | 0.07%   |
| Philips (or NXP)                      | 1         | 0.07%   |
| Marvell Technology Group              | 1         | 0.07%   |
| Hewlett-Packard                       | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 53        | 3.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 49        | 3.43%   |
| Intel Wi-Fi 6 AX200                                                     | 45        | 3.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 43        | 3.01%   |
| Intel Wireless 8265 / 8275                                              | 36        | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 2.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 34        | 2.38%   |
| Intel Wireless 7260                                                     | 33        | 2.31%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 32        | 2.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 31        | 2.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 28        | 1.96%   |
| Intel Wireless 7265                                                     | 28        | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.68%   |
| Intel Wireless 8260                                                     | 21        | 1.47%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 20        | 1.4%    |
| Intel Wireless-AC 9260                                                  | 20        | 1.4%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 19        | 1.33%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 19        | 1.33%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 18        | 1.26%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 1.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 17        | 1.19%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 1.12%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 16        | 1.12%   |
| Ralink MT7601U Wireless Adapter                                         | 16        | 1.12%   |
| Intel Wireless 3165                                                     | 16        | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 16        | 1.12%   |
| Intel Centrino Advanced-N 6200                                          | 16        | 1.12%   |
| Qualcomm Atheros AR9271 802.11n                                         | 15        | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.05%   |
| Intel Centrino Ultimate-N 6300                                          | 14        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 14        | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 13        | 0.91%   |
| Intel Wireless 3160                                                     | 13        | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 13        | 0.91%   |
| Intel Centrino Advanced-N 6235                                          | 13        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 0.91%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                 | 12        | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 12        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.84%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 897       | 49.94%  |
| Intel                            | 479       | 26.67%  |
| Broadcom                         | 103       | 5.73%   |
| Qualcomm Atheros                 | 102       | 5.68%   |
| Nvidia                           | 48        | 2.67%   |
| Marvell Technology Group         | 46        | 2.56%   |
| Broadcom Limited                 | 19        | 1.06%   |
| Samsung Electronics              | 15        | 0.84%   |
| JMicron Technology               | 11        | 0.61%   |
| VIA Technologies                 | 8         | 0.45%   |
| Huawei Technologies              | 8         | 0.45%   |
| MediaTek                         | 7         | 0.39%   |
| Xiaomi                           | 6         | 0.33%   |
| DisplayLink                      | 6         | 0.33%   |
| Silicon Integrated Systems [SiS] | 5         | 0.28%   |
| Lenovo                           | 5         | 0.28%   |
| D-Link System                    | 4         | 0.22%   |
| Attansic Technology              | 4         | 0.22%   |
| ASIX Electronics                 | 4         | 0.22%   |
| Aquantia                         | 4         | 0.22%   |
| Qualcomm                         | 3         | 0.17%   |
| TP-Link                          | 2         | 0.11%   |
| Motorola PCS                     | 2         | 0.11%   |
| LG Electronics                   | 2         | 0.11%   |
| Apple                            | 2         | 0.11%   |
| 3Com                             | 2         | 0.11%   |
| Mellanox Technologies            | 1         | 0.06%   |
| IBM                              | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 666       | 36.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 165       | 9.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 100       | 5.49%   |
| Intel Ethernet Connection I217-LM                                 | 39        | 2.14%   |
| Intel I211 Gigabit Network Connection                             | 24        | 1.32%   |
| Intel 82579V Gigabit Network Connection                           | 24        | 1.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22        | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 21        | 1.15%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 21        | 1.15%   |
| Nvidia MCP61 Ethernet                                             | 20        | 1.1%    |
| Intel Ethernet Connection (2) I219-V                              | 20        | 1.1%    |
| Intel 82577LM Gigabit Network Connection                          | 18        | 0.99%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 16        | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 15        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.77%   |
| Intel Ethernet Connection I217-V                                  | 14        | 0.77%   |
| Intel 82567LM Gigabit Network Connection                          | 14        | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.66%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.66%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 12        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 11        | 0.6%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 11        | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 0.55%   |
| Nvidia MCP77 Ethernet                                             | 10        | 0.55%   |
| Intel Ethernet Connection (4) I219-V                              | 10        | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.55%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 9         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 9         | 0.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 0.49%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.49%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 9         | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 8         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 8         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.44%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 8         | 0.44%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 7         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1703      | 55.62%  |
| WiFi     | 1331      | 43.47%  |
| Modem    | 26        | 0.85%   |
| Unknown  | 2         | 0.07%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1045      | 54.23%  |
| Ethernet | 882       | 45.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1022      | 54.48%  |
| 1     | 754       | 40.19%  |
| 0     | 58        | 3.09%   |
| 3     | 29        | 1.55%   |
| 4     | 11        | 0.59%   |
| 10    | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1602      | 84.32%  |
| Yes  | 298       | 15.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 342       | 40.05%  |
| Qualcomm Atheros Communications | 90        | 10.54%  |
| Realtek Semiconductor           | 78        | 9.13%   |
| Broadcom                        | 77        | 9.02%   |
| Cambridge Silicon Radio         | 57        | 6.67%   |
| Apple                           | 34        | 3.98%   |
| IMC Networks                    | 30        | 3.51%   |
| Lite-On Technology              | 29        | 3.4%    |
| Dell                            | 25        | 2.93%   |
| Foxconn / Hon Hai               | 19        | 2.22%   |
| Hewlett-Packard                 | 18        | 2.11%   |
| Ralink                          | 11        | 1.29%   |
| Toshiba                         | 9         | 1.05%   |
| ASUSTek Computer                | 9         | 1.05%   |
| Integrated System Solution      | 5         | 0.59%   |
| Alps Electric                   | 4         | 0.47%   |
| Chicony Electronics             | 3         | 0.35%   |
| Realtek                         | 2         | 0.23%   |
| Edimax Technology               | 2         | 0.23%   |
| TP-Link                         | 1         | 0.12%   |
| Taiyo Yuden                     | 1         | 0.12%   |
| Sitecom Europe                  | 1         | 0.12%   |
| Ralink Technology               | 1         | 0.12%   |
| Qcom                            | 1         | 0.12%   |
| MediaTek                        | 1         | 0.12%   |
| Fujitsu                         | 1         | 0.12%   |
| Foxconn International           | 1         | 0.12%   |
| Conwise Technology              | 1         | 0.12%   |
| Unknown                         | 1         | 0.12%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 140       | 16.37%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 57        | 6.67%   |
| Intel AX201 Bluetooth                               | 52        | 6.08%   |
| Intel AX200 Bluetooth                               | 46        | 5.38%   |
| Realtek Bluetooth Radio                             | 40        | 4.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 38        | 4.44%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 36        | 4.21%   |
| Realtek  Bluetooth 4.2 Adapter                      | 25        | 2.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 2.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 2.22%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.87%   |
| Intel Wireless-AC 3168 Bluetooth                    | 16        | 1.87%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 1.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 1.52%   |
| Apple Bluetooth Host Controller                     | 13        | 1.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 12        | 1.4%    |
| Ralink RT3290 Bluetooth                             | 11        | 1.29%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 11        | 1.29%   |
| Lite-On Bluetooth Device                            | 11        | 1.29%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 1.29%   |
| IMC Networks Bluetooth Device                       | 10        | 1.17%   |
| Realtek RTL8723B Bluetooth                          | 9         | 1.05%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 1.05%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.94%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 8         | 0.94%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 0.82%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.82%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.82%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.82%   |
| Apple Bluetooth HCI                                 | 7         | 0.82%   |
| IMC Networks Bluetooth Radio                        | 6         | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.7%    |
| Dell Wireless 365 Bluetooth                         | 6         | 0.7%    |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 6         | 0.7%    |
| Broadcom BCM2045 Bluetooth                          | 6         | 0.7%    |
| Apple Bluetooth USB Host Controller                 | 6         | 0.7%    |
| Foxconn / Hon Hai BCM20702A0                        | 5         | 0.58%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 5         | 0.58%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.47%   |
| Intel AX210 Bluetooth                               | 4         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1340      | 53.58%  |
| AMD                              | 476       | 19.03%  |
| Nvidia                           | 422       | 16.87%  |
| C-Media Electronics              | 40        | 1.6%    |
| Creative Labs                    | 31        | 1.24%   |
| Logitech                         | 19        | 0.76%   |
| VIA Technologies                 | 16        | 0.64%   |
| Texas Instruments                | 14        | 0.56%   |
| GN Netcom                        | 11        | 0.44%   |
| Focusrite-Novation               | 9         | 0.36%   |
| Yamaha                           | 8         | 0.32%   |
| Silicon Integrated Systems [SiS] | 6         | 0.24%   |
| Lenovo                           | 6         | 0.24%   |
| Sennheiser Communications        | 5         | 0.2%    |
| Realtek Semiconductor            | 5         | 0.2%    |
| M-Audio                          | 5         | 0.2%    |
| Generalplus Technology           | 5         | 0.2%    |
| Plantronics                      | 4         | 0.16%   |
| TEAC                             | 3         | 0.12%   |
| JMTek                            | 3         | 0.12%   |
| EGO SYStems                      | 3         | 0.12%   |
| Creative Technology              | 3         | 0.12%   |
| BEHRINGER International          | 3         | 0.12%   |
| AKAI Professional M.I.           | 3         | 0.12%   |
| ZOOM                             | 2         | 0.08%   |
| Textech International            | 2         | 0.08%   |
| TerraTec Electronic              | 2         | 0.08%   |
| Samson Technologies              | 2         | 0.08%   |
| PreSonus Audio Electronics       | 2         | 0.08%   |
| KORG                             | 2         | 0.08%   |
| ESI Audiotechnik                 | 2         | 0.08%   |
| Corsair                          | 2         | 0.08%   |
| Cambridge Silicon Radio          | 2         | 0.08%   |
| Blue Microphones                 | 2         | 0.08%   |
| ASUSTek Computer                 | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| Alesis                           | 2         | 0.08%   |
| XMOS                             | 1         | 0.04%   |
| Xilinx                           | 1         | 0.04%   |
| Unknown                          | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 157       | 5.37%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 150       | 5.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 99        | 3.39%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 99        | 3.39%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 96        | 3.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 92        | 3.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 90        | 3.08%   |
| AMD FCH Azalia Controller                                                                         | 89        | 3.05%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 89        | 3.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 88        | 3.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 74        | 2.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 66        | 2.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 55        | 1.88%   |
| AMD Kabini HDMI/DP Audio                                                                          | 47        | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 42        | 1.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 41        | 1.4%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 39        | 1.33%   |
| Intel Cannon Lake PCH cAVS                                                                        | 39        | 1.33%   |
| Intel 8 Series HD Audio Controller                                                                | 39        | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 37        | 1.27%   |
| Nvidia High Definition Audio Controller                                                           | 35        | 1.2%    |
| AMD Starship/Matisse HD Audio Controller                                                          | 35        | 1.2%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 34        | 1.16%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 33        | 1.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 31        | 1.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 30        | 1.03%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 29        | 0.99%   |
| Intel 200 Series PCH HD Audio                                                                     | 27        | 0.92%   |
| Intel Broadwell-U Audio Controller                                                                | 25        | 0.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 0.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 24        | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 24        | 0.82%   |
| AMD Wrestler HDMI Audio                                                                           | 24        | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 0.79%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 23        | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 22        | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 22        | 0.75%   |
| Nvidia MCP61 High Definition Audio                                                                | 21        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 21        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 219       | 21.7%   |
| SK hynix                                         | 186       | 18.43%  |
| Unknown                                          | 156       | 15.46%  |
| Kingston                                         | 108       | 10.7%   |
| Micron Technology                                | 84        | 8.33%   |
| Crucial                                          | 57        | 5.65%   |
| Corsair                                          | 39        | 3.87%   |
| G.Skill                                          | 27        | 2.68%   |
| Elpida                                           | 24        | 2.38%   |
| Ramaxel Technology                               | 18        | 1.78%   |
| Nanya Technology                                 | 12        | 1.19%   |
| A-DATA Technology                                | 12        | 1.19%   |
| Unknown (ABCD)                                   | 8         | 0.79%   |
| Smart                                            | 8         | 0.79%   |
| Transcend                                        | 7         | 0.69%   |
| Team                                             | 6         | 0.59%   |
| Goodram                                          | 6         | 0.59%   |
| Unifosa                                          | 3         | 0.3%    |
| Patriot                                          | 3         | 0.3%    |
| Apacer                                           | 3         | 0.3%    |
| Teikon                                           | 2         | 0.2%    |
| Avant                                            | 2         | 0.2%    |
| Unknown                                          | 2         | 0.2%    |
| Walton Chaintech                                 | 1         | 0.1%    |
| V-GeN                                            | 1         | 0.1%    |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.1%    |
| Unknown (0x0043415455000000)                     | 1         | 0.1%    |
| Toshiba                                          | 1         | 0.1%    |
| Timetec                                          | 1         | 0.1%    |
| Smart Brazil                                     | 1         | 0.1%    |
| SHARETRONIC                                      | 1         | 0.1%    |
| Sesame                                           | 1         | 0.1%    |
| Positivo                                         | 1         | 0.1%    |
| PNY                                              | 1         | 0.1%    |
| Memox                                            | 1         | 0.1%    |
| GeIL                                             | 1         | 0.1%    |
| CSX                                              | 1         | 0.1%    |
| Axiom                                            | 1         | 0.1%    |
| ASint Technology                                 | 1         | 0.1%    |
| 9?02                                             | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s            | 15        | 1.36%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 9         | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 0.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 0.64%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.64%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.64%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.64%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 6         | 0.55%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 6         | 0.55%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 6         | 0.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.55%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.55%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 5         | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 5         | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 5         | 0.45%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.45%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 5         | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.45%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 5         | 0.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.45%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.45%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 5         | 0.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.45%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 4         | 0.36%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.36%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 4         | 0.36%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.36%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.36%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.36%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s           | 4         | 0.36%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 354       | 39.82%  |
| DDR4    | 332       | 37.35%  |
| DDR2    | 81        | 9.11%   |
| SDRAM   | 44        | 4.95%   |
| Unknown | 29        | 3.26%   |
| LPDDR4  | 21        | 2.36%   |
| LPDDR3  | 16        | 1.8%    |
| DDR     | 9         | 1.01%   |
| DRAM    | 2         | 0.22%   |
| EEPROM  | 1         | 0.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 509       | 58.24%  |
| DIMM         | 326       | 37.3%   |
| Row Of Chips | 32        | 3.66%   |
| Chip         | 5         | 0.57%   |
| FB-DIMM      | 1         | 0.11%   |
| Unknown      | 1         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 307       | 31.85%  |
| 8192  | 277       | 28.73%  |
| 2048  | 190       | 19.71%  |
| 16384 | 117       | 12.14%  |
| 1024  | 53        | 5.5%    |
| 32768 | 13        | 1.35%   |
| 512   | 5         | 0.52%   |
| 1536  | 1         | 0.1%    |
| 1     | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 211       | 22.3%   |
| 2667    | 146       | 15.43%  |
| 1333    | 84        | 8.88%   |
| 3200    | 74        | 7.82%   |
| 2400    | 68        | 7.19%   |
| 667     | 43        | 4.55%   |
| 1334    | 38        | 4.02%   |
| 800     | 37        | 3.91%   |
| Unknown | 37        | 3.91%   |
| 2133    | 36        | 3.81%   |
| 1067    | 16        | 1.69%   |
| 1066    | 16        | 1.69%   |
| 1867    | 15        | 1.59%   |
| 3600    | 13        | 1.37%   |
| 1866    | 12        | 1.27%   |
| 3266    | 11        | 1.16%   |
| 4199    | 10        | 1.06%   |
| 2666    | 9         | 0.95%   |
| 4267    | 7         | 0.74%   |
| 3000    | 7         | 0.74%   |
| 1800    | 7         | 0.74%   |
| 533     | 6         | 0.63%   |
| 3800    | 4         | 0.42%   |
| 2048    | 4         | 0.42%   |
| 400     | 4         | 0.42%   |
| 2733    | 3         | 0.32%   |
| 975     | 3         | 0.32%   |
| 49926   | 2         | 0.21%   |
| 3400    | 2         | 0.21%   |
| 2800    | 2         | 0.21%   |
| 2200    | 2         | 0.21%   |
| 1639    | 2         | 0.21%   |
| 8400    | 1         | 0.11%   |
| 4333    | 1         | 0.11%   |
| 4000    | 1         | 0.11%   |
| 3866    | 1         | 0.11%   |
| 3466    | 1         | 0.11%   |
| 3100    | 1         | 0.11%   |
| 2933    | 1         | 0.11%   |
| 2866    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 30        | 37.5%   |
| Brother Industries    | 18        | 22.5%   |
| Canon                 | 13        | 16.25%  |
| Samsung Electronics   | 5         | 6.25%   |
| Zebra                 | 4         | 5%      |
| Seiko Epson           | 3         | 3.75%   |
| STMicroelectronics    | 1         | 1.25%   |
| QinHeng Electronics   | 1         | 1.25%   |
| Prolific Technology   | 1         | 1.25%   |
| Pantum                | 1         | 1.25%   |
| Lexmark International | 1         | 1.25%   |
| Kyocera               | 1         | 1.25%   |
| Dymo-CoStar           | 1         | 1.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet 400 M401dne                                               | 4         | 5%      |
| Zebra ZP 450 Printer                                                  | 3         | 3.75%   |
| HP LaserJet P1005                                                     | 3         | 3.75%   |
| Brother HL-5370DW series                                              | 3         | 3.75%   |
| Seiko Epson L222 Series                                               | 2         | 2.5%    |
| HP OfficeJet Pro 7730 series                                          | 2         | 2.5%    |
| HP LaserJet 1320                                                      | 2         | 2.5%    |
| HP DeskJet 3700 series                                                | 2         | 2.5%    |
| Brother HL-L2320D series                                              | 2         | 2.5%    |
| Brother HL-5340 series                                                | 2         | 2.5%    |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 1.25%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 1         | 1.25%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 1.25%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1         | 1.25%   |
| Samsung SCX-4200 series                                               | 1         | 1.25%   |
| Samsung ML-2525W Series                                               | 1         | 1.25%   |
| Samsung M2070 Series                                                  | 1         | 1.25%   |
| Samsung M2020 Series                                                  | 1         | 1.25%   |
| QinHeng CH340S                                                        | 1         | 1.25%   |
| Prolific PL2305 Parallel Port                                         | 1         | 1.25%   |
| Pantum P2000 Series                                                   | 1         | 1.25%   |
| Lexmark International E360d                                           | 1         | 1.25%   |
| Kyocera Mita FS-920                                                   | 1         | 1.25%   |
| HP OfficeJet Pro 9010 series                                          | 1         | 1.25%   |
| HP Officejet Pro 6230                                                 | 1         | 1.25%   |
| HP LaserJet P2055 series                                              | 1         | 1.25%   |
| HP LaserJet P2015 series                                              | 1         | 1.25%   |
| HP LaserJet P1006                                                     | 1         | 1.25%   |
| HP LaserJet M14-M17                                                   | 1         | 1.25%   |
| HP LaserJet CP 1025                                                   | 1         | 1.25%   |
| HP LaserJet 1020                                                      | 1         | 1.25%   |
| HP LaserJet 1018                                                      | 1         | 1.25%   |
| HP ENVY 4520 series                                                   | 1         | 1.25%   |
| HP Deskjet F4400 series                                               | 1         | 1.25%   |
| HP DeskJet F300 series                                                | 1         | 1.25%   |
| HP DeskJet F2100 Printer series                                       | 1         | 1.25%   |
| HP DeskJet 5850c                                                      | 1         | 1.25%   |
| HP DeskJet 3630 series                                                | 1         | 1.25%   |
| HP Deskjet 3050A                                                      | 1         | 1.25%   |
| HP Color LaserJet CP1215                                              | 1         | 1.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 12        | 63.16%  |
| Seiko Epson     | 4         | 21.05%  |
| Hewlett-Packard | 3         | 15.79%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3         | 15.79%  |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]            | 1         | 5.26%   |
| Seiko Epson GT-X770 [Perfection V500]                       | 1         | 5.26%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1         | 5.26%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1         | 5.26%   |
| HP ScanJet 82x0C                                            | 1         | 5.26%   |
| HP ScanJet 5590                                             | 1         | 5.26%   |
| HP ScanJet 3570c                                            | 1         | 5.26%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1         | 5.26%   |
| Canon CanoScan LiDE 90                                      | 1         | 5.26%   |
| Canon CanoScan LIDE 25                                      | 1         | 5.26%   |
| Canon CanoScan LiDE 220                                     | 1         | 5.26%   |
| Canon CanoScan LiDE 210                                     | 1         | 5.26%   |
| Canon CanoScan LiDE 200                                     | 1         | 5.26%   |
| Canon CanoScan LiDE 120                                     | 1         | 5.26%   |
| Canon CanoScan LiDE 110                                     | 1         | 5.26%   |
| Canon CanoScan LiDE 100                                     | 1         | 5.26%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 252       | 24.85%  |
| Microdia                               | 76        | 7.5%    |
| Realtek Semiconductor                  | 67        | 6.61%   |
| IMC Networks                           | 66        | 6.51%   |
| Acer                                   | 62        | 6.11%   |
| Sunplus Innovation Technology          | 55        | 5.42%   |
| Logitech                               | 53        | 5.23%   |
| Suyin                                  | 49        | 4.83%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 3.25%   |
| Apple                                  | 33        | 3.25%   |
| Quanta                                 | 30        | 2.96%   |
| Lite-On Technology                     | 26        | 2.56%   |
| Syntek                                 | 24        | 2.37%   |
| Alcor Micro                            | 20        | 1.97%   |
| Silicon Motion                         | 19        | 1.87%   |
| Ricoh                                  | 17        | 1.68%   |
| Samsung Electronics                    | 12        | 1.18%   |
| Microsoft                              | 12        | 1.18%   |
| Lenovo                                 | 8         | 0.79%   |
| Z-Star Microelectronics                | 7         | 0.69%   |
| Luxvisions Innotech Limited            | 6         | 0.59%   |
| Importek                               | 6         | 0.59%   |
| Generalplus Technology                 | 6         | 0.59%   |
| MacroSilicon                           | 5         | 0.49%   |
| Jieli Technology                       | 5         | 0.49%   |
| ALi                                    | 5         | 0.49%   |
| OmniVision Technologies                | 4         | 0.39%   |
| GEMBIRD                                | 4         | 0.39%   |
| DigiTech                               | 4         | 0.39%   |
| ARC International                      | 4         | 0.39%   |
| Trust                                  | 3         | 0.3%    |
| Sunplus Technology                     | 3         | 0.3%    |
| Primax Electronics                     | 3         | 0.3%    |
| Cubeternet                             | 3         | 0.3%    |
| Creative Technology                    | 3         | 0.3%    |
| Unknown                                | 2         | 0.2%    |
| Razer USA                              | 2         | 0.2%    |
| KYE Systems (Mouse Systems)            | 2         | 0.2%    |
| icSpring                               | 2         | 0.2%    |
| Hewlett-Packard                        | 2         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                   | 39        | 3.83%   |
| Realtek Integrated_Webcam_HD                                | 18        | 1.77%   |
| Chicony USB 2.0 Camera                                      | 18        | 1.77%   |
| Microdia Integrated_Webcam_HD                               | 17        | 1.67%   |
| IMC Networks USB2.0 HD UVC WebCam                           | 15        | 1.47%   |
| Logitech Webcam C270                                        | 14        | 1.37%   |
| IMC Networks Integrated Camera                              | 13        | 1.28%   |
| Sunplus Integrated_Webcam_HD                                | 12        | 1.18%   |
| Samsung Galaxy series, misc. (MTP mode)                     | 12        | 1.18%   |
| Chicony TOSHIBA Web Camera - HD                             | 12        | 1.18%   |
| Chicony HP Truevision HD                                    | 12        | 1.18%   |
| Chicony HD WebCam                                           | 11        | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam            | 11        | 1.08%   |
| Acer Lenovo EasyCamera                                      | 11        | 1.08%   |
| Microdia Integrated Webcam                                  | 10        | 0.98%   |
| Logitech HD Pro Webcam C920                                 | 10        | 0.98%   |
| Lite-On Integrated Camera                                   | 10        | 0.98%   |
| Chicony USB2.0 VGA UVC WebCam                               | 10        | 0.98%   |
| Apple iPhone 5/5C/5S/6/SE                                   | 10        | 0.98%   |
| Apple Built-in iSight                                       | 10        | 0.98%   |
| Acer Integrated Camera                                      | 10        | 0.98%   |
| Syntek Lenovo EasyCamera                                    | 9         | 0.88%   |
| Syntek Integrated Camera                                    | 9         | 0.88%   |
| Lite-On HP HD Camera                                        | 9         | 0.88%   |
| Alcor Micro USB 2.0 WebCamera                               | 9         | 0.88%   |
| Suyin HP TrueVision HD                                      | 8         | 0.79%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 8         | 0.79%   |
| Chicony Lenovo EasyCamera                                   | 8         | 0.79%   |
| Chicony USB2.0 Camera                                       | 7         | 0.69%   |
| Chicony Integrated Camera (1280x720@30)                     | 7         | 0.69%   |
| Acer BisonCam, NB Pro                                       | 7         | 0.69%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 6         | 0.59%   |
| Quanta HP TrueVision HD Camera                              | 6         | 0.59%   |
| IMC Networks UVC VGA Webcam                                 | 6         | 0.59%   |
| Chicony FJ Camera                                           | 6         | 0.59%   |
| Apple FaceTime HD Camera (Built-in)                         | 6         | 0.59%   |
| Suyin HP TrueVision HD Integrated Webcam                    | 5         | 0.49%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 5         | 0.49%   |
| Sunplus HD WebCam                                           | 5         | 0.49%   |
| Sunplus Asus Webcam                                         | 5         | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 73        | 40.78%  |
| Synaptics                  | 39        | 21.79%  |
| AuthenTec                  | 29        | 16.2%   |
| Upek                       | 11        | 6.15%   |
| Shenzhen Goodix Technology | 9         | 5.03%   |
| LighTuning Technology      | 7         | 3.91%   |
| STMicroelectronics         | 6         | 3.35%   |
| Elan Microelectronics      | 4         | 2.23%   |
| Samsung Electronics        | 1         | 0.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 19        | 10.61%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 15        | 8.38%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 5.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 5.59%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 5.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 4.47%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 4.47%   |
| AuthenTec AES2810                                                          | 8         | 4.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 3.91%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 3.91%   |
| Validity Sensors VFS491                                                    | 6         | 3.35%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 3.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 3.35%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 3.35%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 3.35%   |
| Unknown                                                                    | 6         | 3.35%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.23%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.23%   |
| AuthenTec AES1600                                                          | 4         | 2.23%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.68%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.12%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.12%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.12%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.12%   |
| LighTuning Fingerprint Reader                                              | 2         | 1.12%   |
| LighTuning EgisTec_ES603                                                   | 2         | 1.12%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.12%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.12%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.56%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.56%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.56%   |
| Synaptics WBDI Device                                                      | 1         | 0.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.56%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.56%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.56%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 36        | 34.95%  |
| Alcor Micro               | 27        | 26.21%  |
| O2 Micro                  | 15        | 14.56%  |
| Lenovo                    | 9         | 8.74%   |
| Upek                      | 8         | 7.77%   |
| OmniKey                   | 3         | 2.91%   |
| Reiner SCT Kartensysteme  | 1         | 0.97%   |
| Gemalto (was Gemplus)     | 1         | 0.97%   |
| Fujitsu Siemens Computers | 1         | 0.97%   |
| Cherry                    | 1         | 0.97%   |
| C3PO                      | 1         | 0.97%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 27        | 26.21%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 14        | 13.59%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 13.59%  |
| Broadcom 5880                                                                | 10        | 9.71%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 7.77%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 7.77%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.8%    |
| Broadcom 58200                                                               | 5         | 4.85%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.94%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.97%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.97%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.97%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.97%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.97%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.97%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.97%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.97%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1406      | 74.27%  |
| 1     | 396       | 20.92%  |
| 2     | 72        | 3.8%    |
| 3     | 8         | 0.42%   |
| 4     | 7         | 0.37%   |
| 5     | 2         | 0.11%   |
| 10    | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 179       | 30.81%  |
| Graphics card            | 110       | 18.93%  |
| Chipcard                 | 98        | 16.87%  |
| Net/wireless             | 66        | 11.36%  |
| Communication controller | 21        | 3.61%   |
| Unassigned class         | 16        | 2.75%   |
| Camera                   | 16        | 2.75%   |
| Bluetooth                | 14        | 2.41%   |
| Sound                    | 12        | 2.07%   |
| Card reader              | 12        | 2.07%   |
| Multimedia controller    | 11        | 1.89%   |
| Storage                  | 10        | 1.72%   |
| Net/ethernet             | 5         | 0.86%   |
| Flash memory             | 5         | 0.86%   |
| Network                  | 2         | 0.34%   |
| Modem                    | 2         | 0.34%   |
| Storage/raid             | 1         | 0.17%   |
| Dvb card                 | 1         | 0.17%   |

