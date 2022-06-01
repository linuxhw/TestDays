Ubuntu 22.04 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Ubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Ubuntu_22.04/Notebook/README.md).

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

Total: 1244

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | Notebook    | [ac0d3882ca](https://linux-hardware.org/?probe=ac0d3882ca) | Jun 01, 2022 |
| Alienware     | 0XJKKD A00                  | Desktop     | [ae3a750f2e](https://linux-hardware.org/?probe=ae3a750f2e) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [d12c2f9f7c](https://linux-hardware.org/?probe=d12c2f9f7c) | Jun 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS29U0... | Notebook    | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [f4906f3799](https://linux-hardware.org/?probe=f4906f3799) | Jun 01, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [45d3300158](https://linux-hardware.org/?probe=45d3300158) | Jun 01, 2022 |
| Dell          | 0NK5PH A00                  | Desktop     | [960e8817bf](https://linux-hardware.org/?probe=960e8817bf) | Jun 01, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [88ef811c4d](https://linux-hardware.org/?probe=88ef811c4d) | May 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [08fe1f2d0f](https://linux-hardware.org/?probe=08fe1f2d0f) | May 31, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7099867859](https://linux-hardware.org/?probe=7099867859) | May 31, 2022 |
| Maibenben     | XiaoMai5                    | Notebook    | [db343bc7eb](https://linux-hardware.org/?probe=db343bc7eb) | May 31, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [ef73457d51](https://linux-hardware.org/?probe=ef73457d51) | May 31, 2022 |
| Dell          | Inspiron 14 7420 2-in-1     | Notebook    | [131a117ca2](https://linux-hardware.org/?probe=131a117ca2) | May 31, 2022 |
| Pegatron      | 2AED                        | Desktop     | [67df0b1c08](https://linux-hardware.org/?probe=67df0b1c08) | May 31, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [726e3b4cd7](https://linux-hardware.org/?probe=726e3b4cd7) | May 31, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [199523cb84](https://linux-hardware.org/?probe=199523cb84) | May 31, 2022 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ddafd23ad4](https://linux-hardware.org/?probe=ddafd23ad4) | May 31, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [989b41f386](https://linux-hardware.org/?probe=989b41f386) | May 31, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [65ae31976a](https://linux-hardware.org/?probe=65ae31976a) | May 31, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [0d7be8de90](https://linux-hardware.org/?probe=0d7be8de90) | May 31, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [72484e859d](https://linux-hardware.org/?probe=72484e859d) | May 31, 2022 |
| Dell          | 0200DY A01                  | Desktop     | [c3c585ba02](https://linux-hardware.org/?probe=c3c585ba02) | May 31, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [37af34e2e7](https://linux-hardware.org/?probe=37af34e2e7) | May 31, 2022 |
| Unknown       | Unknown                     | Desktop     | [c2d6d647d8](https://linux-hardware.org/?probe=c2d6d647d8) | May 31, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [0d21170323](https://linux-hardware.org/?probe=0d21170323) | May 31, 2022 |
| ASUSTek       | G73Jh                       | Notebook    | [b7db998ac4](https://linux-hardware.org/?probe=b7db998ac4) | May 31, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [9f7d224ed7](https://linux-hardware.org/?probe=9f7d224ed7) | May 31, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [2652284f1a](https://linux-hardware.org/?probe=2652284f1a) | May 31, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [4ad762abcb](https://linux-hardware.org/?probe=4ad762abcb) | May 31, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [aeb3a20df7](https://linux-hardware.org/?probe=aeb3a20df7) | May 31, 2022 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [ab6fb60b96](https://linux-hardware.org/?probe=ab6fb60b96) | May 31, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [d24672a3cd](https://linux-hardware.org/?probe=d24672a3cd) | May 31, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| Toshiba       | Satellite C850D-115         | Notebook    | [fca373e327](https://linux-hardware.org/?probe=fca373e327) | May 31, 2022 |
| Gigabyte      | Q35M-S2                     | Desktop     | [7ef3498226](https://linux-hardware.org/?probe=7ef3498226) | May 30, 2022 |
| Dell          | Inspiron 5491 2n1           | Convertible | [652f774655](https://linux-hardware.org/?probe=652f774655) | May 30, 2022 |
| HP            | Spectre 13 x2 PC            | Notebook    | [9b67243691](https://linux-hardware.org/?probe=9b67243691) | May 30, 2022 |
| Dell          | Latitude 7400               | Notebook    | [685a5a8006](https://linux-hardware.org/?probe=685a5a8006) | May 30, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [be0f84abb3](https://linux-hardware.org/?probe=be0f84abb3) | May 30, 2022 |
| Toshiba       | Satellite C50D-B            | Notebook    | [ce4eb9abc2](https://linux-hardware.org/?probe=ce4eb9abc2) | May 30, 2022 |
| ASRock        | 870 Extreme3                | Desktop     | [7e2000d3a1](https://linux-hardware.org/?probe=7e2000d3a1) | May 30, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [904ddbbbb1](https://linux-hardware.org/?probe=904ddbbbb1) | May 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YFC... | Notebook    | [784e1ca4cc](https://linux-hardware.org/?probe=784e1ca4cc) | May 30, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [e6145c7453](https://linux-hardware.org/?probe=e6145c7453) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [b0e96de917](https://linux-hardware.org/?probe=b0e96de917) | May 30, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [c40635b66e](https://linux-hardware.org/?probe=c40635b66e) | May 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [6b394ac051](https://linux-hardware.org/?probe=6b394ac051) | May 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [59d0634230](https://linux-hardware.org/?probe=59d0634230) | May 30, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [b4f73129a2](https://linux-hardware.org/?probe=b4f73129a2) | May 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [5766b308a7](https://linux-hardware.org/?probe=5766b308a7) | May 30, 2022 |
| HP            | 8711                        | Mini pc     | [e6822ab801](https://linux-hardware.org/?probe=e6822ab801) | May 30, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [b1cf8ca505](https://linux-hardware.org/?probe=b1cf8ca505) | May 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [44e2ec7714](https://linux-hardware.org/?probe=44e2ec7714) | May 30, 2022 |
| ASUSTek       | X99-E-10G WS                | Desktop     | [83e525ca4e](https://linux-hardware.org/?probe=83e525ca4e) | May 30, 2022 |
| ECS           | MCP61M-M3                   | Desktop     | [b785b68657](https://linux-hardware.org/?probe=b785b68657) | May 29, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [4c1c5915bc](https://linux-hardware.org/?probe=4c1c5915bc) | May 29, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | Notebook    | [84f8bf29fd](https://linux-hardware.org/?probe=84f8bf29fd) | May 29, 2022 |
| Acer          | Aspire A515-51              | Notebook    | [443f0579bb](https://linux-hardware.org/?probe=443f0579bb) | May 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0b83e8fa79](https://linux-hardware.org/?probe=0b83e8fa79) | May 29, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [432c1135b8](https://linux-hardware.org/?probe=432c1135b8) | May 29, 2022 |
| Dell          | Inspiron 3420               | Notebook    | [2e79e10052](https://linux-hardware.org/?probe=2e79e10052) | May 29, 2022 |
| Lenovo        | ThinkPad T480s 20L8S34C0... | Notebook    | [c272fc283f](https://linux-hardware.org/?probe=c272fc283f) | May 29, 2022 |
| Intel         | DQ35JO AAD82085-803         | Desktop     | [40429e6d9a](https://linux-hardware.org/?probe=40429e6d9a) | May 29, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [b1670ac481](https://linux-hardware.org/?probe=b1670ac481) | May 29, 2022 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [4fec6454b4](https://linux-hardware.org/?probe=4fec6454b4) | May 29, 2022 |
| Biostar       | G41U3G                      | Desktop     | [1c6caef665](https://linux-hardware.org/?probe=1c6caef665) | May 29, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [b4b8c3db64](https://linux-hardware.org/?probe=b4b8c3db64) | May 29, 2022 |
| HP            | Pavilion g6                 | Notebook    | [a82494e1f3](https://linux-hardware.org/?probe=a82494e1f3) | May 29, 2022 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d7800ffe07](https://linux-hardware.org/?probe=d7800ffe07) | May 29, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | Notebook    | [6e41ef26bf](https://linux-hardware.org/?probe=6e41ef26bf) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [bcca466c5e](https://linux-hardware.org/?probe=bcca466c5e) | May 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [c11ae8de66](https://linux-hardware.org/?probe=c11ae8de66) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [c1dd2cf1be](https://linux-hardware.org/?probe=c1dd2cf1be) | May 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [0df520da7e](https://linux-hardware.org/?probe=0df520da7e) | May 29, 2022 |
| ASUSTek       | UX360CA                     | Notebook    | [63fac2dc9b](https://linux-hardware.org/?probe=63fac2dc9b) | May 29, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [b83d80f5d2](https://linux-hardware.org/?probe=b83d80f5d2) | May 29, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [10ade1b182](https://linux-hardware.org/?probe=10ade1b182) | May 29, 2022 |
| HP            | Pavilion Laptop 15t-eg10... | Notebook    | [e24b789c03](https://linux-hardware.org/?probe=e24b789c03) | May 29, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7fd1e065eb](https://linux-hardware.org/?probe=7fd1e065eb) | May 29, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [55dfdf01c6](https://linux-hardware.org/?probe=55dfdf01c6) | May 29, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [44b220163b](https://linux-hardware.org/?probe=44b220163b) | May 28, 2022 |
| Shuttle       | FS81                        | Desktop     | [756f86d9fc](https://linux-hardware.org/?probe=756f86d9fc) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [3c144d36f0](https://linux-hardware.org/?probe=3c144d36f0) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [7220b6a007](https://linux-hardware.org/?probe=7220b6a007) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [962defa2c3](https://linux-hardware.org/?probe=962defa2c3) | May 28, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [bd97a6b3dd](https://linux-hardware.org/?probe=bd97a6b3dd) | May 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9ff7306bbd](https://linux-hardware.org/?probe=9ff7306bbd) | May 28, 2022 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [e5fdf1083f](https://linux-hardware.org/?probe=e5fdf1083f) | May 28, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c0399b42b7](https://linux-hardware.org/?probe=c0399b42b7) | May 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [61cbe48681](https://linux-hardware.org/?probe=61cbe48681) | May 28, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [b32a949b01](https://linux-hardware.org/?probe=b32a949b01) | May 28, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [ee508ca972](https://linux-hardware.org/?probe=ee508ca972) | May 28, 2022 |
| HP            | Pavilion dv8                | Notebook    | [e2e28a055e](https://linux-hardware.org/?probe=e2e28a055e) | May 28, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [0086280448](https://linux-hardware.org/?probe=0086280448) | May 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [87b4d5df31](https://linux-hardware.org/?probe=87b4d5df31) | May 28, 2022 |
| HP            | 15                          | Notebook    | [d44aca33f7](https://linux-hardware.org/?probe=d44aca33f7) | May 28, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1a31d93797](https://linux-hardware.org/?probe=1a31d93797) | May 28, 2022 |
| Google        | Phaser360                   | Notebook    | [1795c158e4](https://linux-hardware.org/?probe=1795c158e4) | May 28, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [1094233e96](https://linux-hardware.org/?probe=1094233e96) | May 28, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [2aaa53dd85](https://linux-hardware.org/?probe=2aaa53dd85) | May 28, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [5458522367](https://linux-hardware.org/?probe=5458522367) | May 28, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [ce112fb9d2](https://linux-hardware.org/?probe=ce112fb9d2) | May 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [bd7aea9bfd](https://linux-hardware.org/?probe=bd7aea9bfd) | May 28, 2022 |
| Intel         | Greencity                   | Server      | [841df68a54](https://linux-hardware.org/?probe=841df68a54) | May 28, 2022 |
| Acer          | Veriton X2631G V:1.0        | Desktop     | [26e26a3995](https://linux-hardware.org/?probe=26e26a3995) | May 28, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [3a472b96d3](https://linux-hardware.org/?probe=3a472b96d3) | May 27, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2651c1881a](https://linux-hardware.org/?probe=2651c1881a) | May 27, 2022 |
| HP            | Pavilion dv6000 (GP639EA... | Notebook    | [7f3e3aada0](https://linux-hardware.org/?probe=7f3e3aada0) | May 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [8e0891e3c7](https://linux-hardware.org/?probe=8e0891e3c7) | May 27, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [84cc31cb32](https://linux-hardware.org/?probe=84cc31cb32) | May 27, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [0000ab45a7](https://linux-hardware.org/?probe=0000ab45a7) | May 27, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [b98a471ead](https://linux-hardware.org/?probe=b98a471ead) | May 27, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [44162ea497](https://linux-hardware.org/?probe=44162ea497) | May 27, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [5dbf3199e0](https://linux-hardware.org/?probe=5dbf3199e0) | May 27, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [5dc9e065e3](https://linux-hardware.org/?probe=5dc9e065e3) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [397d64e10c](https://linux-hardware.org/?probe=397d64e10c) | May 27, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [f5beaba229](https://linux-hardware.org/?probe=f5beaba229) | May 27, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2624ebd3a1](https://linux-hardware.org/?probe=2624ebd3a1) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [41529bd0e1](https://linux-hardware.org/?probe=41529bd0e1) | May 27, 2022 |
| Medion        | S6421 MD60703               | Notebook    | [9fffed019c](https://linux-hardware.org/?probe=9fffed019c) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9CTO1WW    | Notebook    | [a74cc1410a](https://linux-hardware.org/?probe=a74cc1410a) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [da6bd78cdb](https://linux-hardware.org/?probe=da6bd78cdb) | May 27, 2022 |
| ASUSTek       | B150-PLUS                   | Desktop     | [bdcda1dabc](https://linux-hardware.org/?probe=bdcda1dabc) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [b122151e55](https://linux-hardware.org/?probe=b122151e55) | May 27, 2022 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [3fdbd67fa3](https://linux-hardware.org/?probe=3fdbd67fa3) | May 27, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | Notebook    | [63bc3a2ce5](https://linux-hardware.org/?probe=63bc3a2ce5) | May 27, 2022 |
| Dell          | Inspiron 15 3510            | Notebook    | [860cd7b1f5](https://linux-hardware.org/?probe=860cd7b1f5) | May 27, 2022 |
| Dell          | Inspiron 15 3510            | Notebook    | [3d9ff1d25f](https://linux-hardware.org/?probe=3d9ff1d25f) | May 27, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0cf6ee749e](https://linux-hardware.org/?probe=0cf6ee749e) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [f10aecd449](https://linux-hardware.org/?probe=f10aecd449) | May 27, 2022 |
| ASUSTek       | STRIKER II FORMULA          | Desktop     | [df37e5c694](https://linux-hardware.org/?probe=df37e5c694) | May 27, 2022 |
| Dell          | Inspiron One 2320           | All in one  | [82b5a900c4](https://linux-hardware.org/?probe=82b5a900c4) | May 27, 2022 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [d7adff5a41](https://linux-hardware.org/?probe=d7adff5a41) | May 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a4d6e798d](https://linux-hardware.org/?probe=8a4d6e798d) | May 26, 2022 |
| Dell          | 02P9X9 A05                  | Server      | [495ed7a7a4](https://linux-hardware.org/?probe=495ed7a7a4) | May 26, 2022 |
| Fujitsu       | D2759 S26361-D2759-A13 W... | Server      | [b4cf75e580](https://linux-hardware.org/?probe=b4cf75e580) | May 26, 2022 |
| Alienware     | 15 R3                       | Notebook    | [84df370117](https://linux-hardware.org/?probe=84df370117) | May 26, 2022 |
| Dell          | 0MY171 A01                  | Desktop     | [9500786a21](https://linux-hardware.org/?probe=9500786a21) | May 26, 2022 |
| Gateway       | NV57H                       | Notebook    | [75c484ec74](https://linux-hardware.org/?probe=75c484ec74) | May 26, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [9e1d2f7e8a](https://linux-hardware.org/?probe=9e1d2f7e8a) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3774c9e6e6](https://linux-hardware.org/?probe=3774c9e6e6) | May 26, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [d4b6f36ee5](https://linux-hardware.org/?probe=d4b6f36ee5) | May 26, 2022 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [22ce653e17](https://linux-hardware.org/?probe=22ce653e17) | May 26, 2022 |
| Dell          | Inspiron 3420               | Notebook    | [a3509450fc](https://linux-hardware.org/?probe=a3509450fc) | May 26, 2022 |
| Dell          | Inspiron 3420               | Notebook    | [63592b1c26](https://linux-hardware.org/?probe=63592b1c26) | May 26, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [f1ccdbbba4](https://linux-hardware.org/?probe=f1ccdbbba4) | May 26, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [60a16a0a17](https://linux-hardware.org/?probe=60a16a0a17) | May 26, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [1e3cb9027d](https://linux-hardware.org/?probe=1e3cb9027d) | May 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [f52de609a0](https://linux-hardware.org/?probe=f52de609a0) | May 26, 2022 |
| Panasonic     | CF53-4                      | Notebook    | [5ca3312ac9](https://linux-hardware.org/?probe=5ca3312ac9) | May 26, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [e38c676047](https://linux-hardware.org/?probe=e38c676047) | May 26, 2022 |
| Acer          | TravelMate 5742Z            | Notebook    | [fd6407ece1](https://linux-hardware.org/?probe=fd6407ece1) | May 26, 2022 |
| Gigabyte      | GA-E7AUM-DS2H               | Desktop     | [9f18dbe621](https://linux-hardware.org/?probe=9f18dbe621) | May 26, 2022 |
| HP            | Pavilion tx2500             | Notebook    | [4f5faea87f](https://linux-hardware.org/?probe=4f5faea87f) | May 26, 2022 |
| ASRock        | Z270 Gaming K6              | Desktop     | [fbf8e08024](https://linux-hardware.org/?probe=fbf8e08024) | May 25, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [4f083f0d35](https://linux-hardware.org/?probe=4f083f0d35) | May 25, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [69cec459af](https://linux-hardware.org/?probe=69cec459af) | May 25, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [4c0609eff4](https://linux-hardware.org/?probe=4c0609eff4) | May 25, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [cff9e3245c](https://linux-hardware.org/?probe=cff9e3245c) | May 25, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [fc05deca82](https://linux-hardware.org/?probe=fc05deca82) | May 25, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [6a41815a3a](https://linux-hardware.org/?probe=6a41815a3a) | May 25, 2022 |
| Acer          | Aspire C24-865              | All in one  | [c0215bd100](https://linux-hardware.org/?probe=c0215bd100) | May 25, 2022 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [9d9a7dc189](https://linux-hardware.org/?probe=9d9a7dc189) | May 25, 2022 |
| Positivo      | AT510                       | Notebook    | [2845c5ebd6](https://linux-hardware.org/?probe=2845c5ebd6) | May 25, 2022 |
| ASRock        | AB350M Pro4                 | Desktop     | [dd39f18241](https://linux-hardware.org/?probe=dd39f18241) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [74796bddc6](https://linux-hardware.org/?probe=74796bddc6) | May 25, 2022 |
| Alienware     | m15 R7                      | Notebook    | [d8155181ec](https://linux-hardware.org/?probe=d8155181ec) | May 25, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [200070a992](https://linux-hardware.org/?probe=200070a992) | May 25, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [364356854c](https://linux-hardware.org/?probe=364356854c) | May 25, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [25e4d08ac2](https://linux-hardware.org/?probe=25e4d08ac2) | May 25, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [5251ce0950](https://linux-hardware.org/?probe=5251ce0950) | May 25, 2022 |
| HP            | Notebook                    | Notebook    | [87460a83e8](https://linux-hardware.org/?probe=87460a83e8) | May 25, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [0d439f9812](https://linux-hardware.org/?probe=0d439f9812) | May 25, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [afa36e649d](https://linux-hardware.org/?probe=afa36e649d) | May 25, 2022 |
| Dell          | 0DT029 A00                  | Desktop     | [17b19530f5](https://linux-hardware.org/?probe=17b19530f5) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [24b9b9fc85](https://linux-hardware.org/?probe=24b9b9fc85) | May 25, 2022 |
| ASUSTek       | ROG Strix G512LU_G512LU     | Notebook    | [7d581f520f](https://linux-hardware.org/?probe=7d581f520f) | May 25, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [cee3591bcd](https://linux-hardware.org/?probe=cee3591bcd) | May 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a649429f59](https://linux-hardware.org/?probe=a649429f59) | May 25, 2022 |
| AMI           | Intel                       | Notebook    | [6f43f8000f](https://linux-hardware.org/?probe=6f43f8000f) | May 25, 2022 |
| Acer          | TravelMate 8372             | Notebook    | [fda4340056](https://linux-hardware.org/?probe=fda4340056) | May 25, 2022 |
| Dell          | Vostro 3590                 | Notebook    | [911d4f5b0c](https://linux-hardware.org/?probe=911d4f5b0c) | May 25, 2022 |
| Dell          | Vostro 3590                 | Notebook    | [84edfb2984](https://linux-hardware.org/?probe=84edfb2984) | May 24, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [51aaf4adcd](https://linux-hardware.org/?probe=51aaf4adcd) | May 24, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [0517751353](https://linux-hardware.org/?probe=0517751353) | May 24, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [cce2c3d087](https://linux-hardware.org/?probe=cce2c3d087) | May 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [62974af203](https://linux-hardware.org/?probe=62974af203) | May 24, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [c00f6e1b2a](https://linux-hardware.org/?probe=c00f6e1b2a) | May 24, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [a26b5f2e62](https://linux-hardware.org/?probe=a26b5f2e62) | May 24, 2022 |
| Dell          | 0WG864                      | Desktop     | [5bda6fbb3a](https://linux-hardware.org/?probe=5bda6fbb3a) | May 24, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [fea70c6484](https://linux-hardware.org/?probe=fea70c6484) | May 24, 2022 |
| LG Electro... | 17Z90N-V.AA77G              | Notebook    | [701a55dbe1](https://linux-hardware.org/?probe=701a55dbe1) | May 24, 2022 |
| Gigabyte      | P55-UD3L                    | Desktop     | [256b5355c3](https://linux-hardware.org/?probe=256b5355c3) | May 24, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [4107e267d7](https://linux-hardware.org/?probe=4107e267d7) | May 24, 2022 |
| Dell          | Latitude 5420               | Notebook    | [28c0f1ba96](https://linux-hardware.org/?probe=28c0f1ba96) | May 24, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | Notebook    | [7e4dbd239c](https://linux-hardware.org/?probe=7e4dbd239c) | May 24, 2022 |
| LG Electro... | 15Z95P-P.AAE8U1             | Notebook    | [b6f94c26a6](https://linux-hardware.org/?probe=b6f94c26a6) | May 24, 2022 |
| MSI           | Prestige 15 A11SCS          | Notebook    | [2433529434](https://linux-hardware.org/?probe=2433529434) | May 24, 2022 |
| Toshiba       | Satellite Pro U400          | Notebook    | [4aeeca648d](https://linux-hardware.org/?probe=4aeeca648d) | May 24, 2022 |
| Medion        | P7649 MD60817               | Notebook    | [afcecb3b4e](https://linux-hardware.org/?probe=afcecb3b4e) | May 24, 2022 |
| Allview       | Allbook H                   | Notebook    | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [9f202f07cd](https://linux-hardware.org/?probe=9f202f07cd) | May 24, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [ddd705ecaf](https://linux-hardware.org/?probe=ddd705ecaf) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [764a660c33](https://linux-hardware.org/?probe=764a660c33) | May 24, 2022 |
| Dell          | Inspiron 5557               | Notebook    | [1b07902e70](https://linux-hardware.org/?probe=1b07902e70) | May 24, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [0656adeb11](https://linux-hardware.org/?probe=0656adeb11) | May 24, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [bd95cdf1cd](https://linux-hardware.org/?probe=bd95cdf1cd) | May 24, 2022 |
| Unknown       | Aspire E                    | Notebook    | [d437b15b97](https://linux-hardware.org/?probe=d437b15b97) | May 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [322f05198a](https://linux-hardware.org/?probe=322f05198a) | May 24, 2022 |
| Unknown       | Aspire E                    | Notebook    | [f46b38824f](https://linux-hardware.org/?probe=f46b38824f) | May 24, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [eb16993291](https://linux-hardware.org/?probe=eb16993291) | May 24, 2022 |
| Dell          | Vostro 3550                 | Notebook    | [b40dbcb6e4](https://linux-hardware.org/?probe=b40dbcb6e4) | May 23, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [7152b312be](https://linux-hardware.org/?probe=7152b312be) | May 23, 2022 |
| MSI           | H97M-G43                    | Desktop     | [4c1e9752b6](https://linux-hardware.org/?probe=4c1e9752b6) | May 23, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [7b3acdb5ac](https://linux-hardware.org/?probe=7b3acdb5ac) | May 23, 2022 |
| Dell          | Latitude E7470              | Notebook    | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [77ff0216c6](https://linux-hardware.org/?probe=77ff0216c6) | May 23, 2022 |
| ASUSTek       | PRIME B660M-A AC D4         | Desktop     | [286688e46b](https://linux-hardware.org/?probe=286688e46b) | May 23, 2022 |
| Intel         | NUC8BEB J72692-310          | Mini pc     | [8dccf1be64](https://linux-hardware.org/?probe=8dccf1be64) | May 23, 2022 |
| Dell          | 02P9X9 A05                  | Server      | [9c274b7318](https://linux-hardware.org/?probe=9c274b7318) | May 23, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [afeae78ecd](https://linux-hardware.org/?probe=afeae78ecd) | May 23, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [70b5e91823](https://linux-hardware.org/?probe=70b5e91823) | May 23, 2022 |
| Shuttle       | FS110                       | Desktop     | [d1147263be](https://linux-hardware.org/?probe=d1147263be) | May 23, 2022 |
| Fujitsu       | D2759 S26361-D2759-A13 W... | Server      | [f5aefeb81c](https://linux-hardware.org/?probe=f5aefeb81c) | May 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [86440c2017](https://linux-hardware.org/?probe=86440c2017) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [43a374c1d4](https://linux-hardware.org/?probe=43a374c1d4) | May 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [80ccb1775d](https://linux-hardware.org/?probe=80ccb1775d) | May 23, 2022 |
| Intel         | H55                         | Desktop     | [8dd80b1c9d](https://linux-hardware.org/?probe=8dd80b1c9d) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b58e8317a1](https://linux-hardware.org/?probe=b58e8317a1) | May 23, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [a700df310a](https://linux-hardware.org/?probe=a700df310a) | May 23, 2022 |
| Intel         | H55                         | Desktop     | [c383403505](https://linux-hardware.org/?probe=c383403505) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f5ff0b74e4](https://linux-hardware.org/?probe=f5ff0b74e4) | May 23, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [e59616f367](https://linux-hardware.org/?probe=e59616f367) | May 23, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [9678842f4f](https://linux-hardware.org/?probe=9678842f4f) | May 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [d49bf6427c](https://linux-hardware.org/?probe=d49bf6427c) | May 23, 2022 |
| Supermicro    | C9Z390-CG-IW                | Server      | [8648fc0825](https://linux-hardware.org/?probe=8648fc0825) | May 23, 2022 |
| MSI           | 2AE0                        | Desktop     | [ea14a764bb](https://linux-hardware.org/?probe=ea14a764bb) | May 22, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [a97b4f8a75](https://linux-hardware.org/?probe=a97b4f8a75) | May 22, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [9020ffe67d](https://linux-hardware.org/?probe=9020ffe67d) | May 22, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [fc1233f258](https://linux-hardware.org/?probe=fc1233f258) | May 22, 2022 |
| Intel         | NUC6i5SYB H81131-503        | Mini pc     | [594e42160c](https://linux-hardware.org/?probe=594e42160c) | May 22, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [1f931afa11](https://linux-hardware.org/?probe=1f931afa11) | May 22, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [1ca9184b98](https://linux-hardware.org/?probe=1ca9184b98) | May 22, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [ee04d8165a](https://linux-hardware.org/?probe=ee04d8165a) | May 22, 2022 |
| Toshiba       | Satellite L755D             | Notebook    | [3614e30a7e](https://linux-hardware.org/?probe=3614e30a7e) | May 22, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [8949bc2cf8](https://linux-hardware.org/?probe=8949bc2cf8) | May 22, 2022 |
| Lenovo        | ThinkPad T530 2359CTO       | Notebook    | [277734b1fe](https://linux-hardware.org/?probe=277734b1fe) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [e7c21e067a](https://linux-hardware.org/?probe=e7c21e067a) | May 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [8ed772fb1d](https://linux-hardware.org/?probe=8ed772fb1d) | May 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [85ec601970](https://linux-hardware.org/?probe=85ec601970) | May 22, 2022 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | Notebook    | [d728114b9b](https://linux-hardware.org/?probe=d728114b9b) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [a7c99d7f14](https://linux-hardware.org/?probe=a7c99d7f14) | May 22, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [70c677bafe](https://linux-hardware.org/?probe=70c677bafe) | May 22, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [a37dd040cc](https://linux-hardware.org/?probe=a37dd040cc) | May 22, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [1ceb70430f](https://linux-hardware.org/?probe=1ceb70430f) | May 22, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [495bcbd710](https://linux-hardware.org/?probe=495bcbd710) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6f5d1c9f06](https://linux-hardware.org/?probe=6f5d1c9f06) | May 22, 2022 |
| Lenovo        | ThinkPad T530 2359CTO       | Notebook    | [9a7b6da037](https://linux-hardware.org/?probe=9a7b6da037) | May 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [5ecfcfab7b](https://linux-hardware.org/?probe=5ecfcfab7b) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae7670331c](https://linux-hardware.org/?probe=ae7670331c) | May 22, 2022 |
| Acer          | Aspire C24-865              | All in one  | [98c5c2fbfd](https://linux-hardware.org/?probe=98c5c2fbfd) | May 22, 2022 |
| Lenovo        | G780 2182                   | Notebook    | [4ba22e506c](https://linux-hardware.org/?probe=4ba22e506c) | May 22, 2022 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [a1d48698b0](https://linux-hardware.org/?probe=a1d48698b0) | May 22, 2022 |
| Shuttle       | FS110                       | Desktop     | [4845946b59](https://linux-hardware.org/?probe=4845946b59) | May 22, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [8d2abc6eb8](https://linux-hardware.org/?probe=8d2abc6eb8) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6f780776df](https://linux-hardware.org/?probe=6f780776df) | May 22, 2022 |
| Dell          | G15 5510                    | Notebook    | [0ca1f736f9](https://linux-hardware.org/?probe=0ca1f736f9) | May 22, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [40e9bdb15d](https://linux-hardware.org/?probe=40e9bdb15d) | May 22, 2022 |
| HP            | 18E4                        | Desktop     | [e8bc371de1](https://linux-hardware.org/?probe=e8bc371de1) | May 22, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6e46286500](https://linux-hardware.org/?probe=6e46286500) | May 21, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [722a69de0d](https://linux-hardware.org/?probe=722a69de0d) | May 21, 2022 |
| Dell          | Latitude E7470              | Notebook    | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [5f03a4b52d](https://linux-hardware.org/?probe=5f03a4b52d) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [aac14b5554](https://linux-hardware.org/?probe=aac14b5554) | May 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [3b904a10e3](https://linux-hardware.org/?probe=3b904a10e3) | May 21, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [3ea531093a](https://linux-hardware.org/?probe=3ea531093a) | May 21, 2022 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [01fcce62c6](https://linux-hardware.org/?probe=01fcce62c6) | May 21, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [6763ad45ce](https://linux-hardware.org/?probe=6763ad45ce) | May 21, 2022 |
| MSI           | CX61 2PC                    | Notebook    | [0efd671877](https://linux-hardware.org/?probe=0efd671877) | May 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [e165a36a31](https://linux-hardware.org/?probe=e165a36a31) | May 21, 2022 |
| Intel         | NUC8BEB J72693-309          | Mini pc     | [ecc465abb8](https://linux-hardware.org/?probe=ecc465abb8) | May 21, 2022 |
| Dell          | Inspiron 5521               | Notebook    | [59c909c05e](https://linux-hardware.org/?probe=59c909c05e) | May 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [f1f75187e1](https://linux-hardware.org/?probe=f1f75187e1) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [d6c9df82c6](https://linux-hardware.org/?probe=d6c9df82c6) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [da6b66b74f](https://linux-hardware.org/?probe=da6b66b74f) | May 21, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [cedcf3fa98](https://linux-hardware.org/?probe=cedcf3fa98) | May 21, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [72560a6e0c](https://linux-hardware.org/?probe=72560a6e0c) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| Acer          | Swift SF514-54T             | Notebook    | [29b06de977](https://linux-hardware.org/?probe=29b06de977) | May 21, 2022 |
| HP            | Notebook                    | Notebook    | [a1be02b2d6](https://linux-hardware.org/?probe=a1be02b2d6) | May 21, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [9869bcac0c](https://linux-hardware.org/?probe=9869bcac0c) | May 21, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [dad32d6137](https://linux-hardware.org/?probe=dad32d6137) | May 21, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [395e3badb3](https://linux-hardware.org/?probe=395e3badb3) | May 21, 2022 |
| HP            | 18E4                        | Desktop     | [e567895819](https://linux-hardware.org/?probe=e567895819) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [6d384d3502](https://linux-hardware.org/?probe=6d384d3502) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [aa4b76df10](https://linux-hardware.org/?probe=aa4b76df10) | May 21, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [8a1f2ffc65](https://linux-hardware.org/?probe=8a1f2ffc65) | May 20, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [286611f4de](https://linux-hardware.org/?probe=286611f4de) | May 20, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [72a96fc8a3](https://linux-hardware.org/?probe=72a96fc8a3) | May 20, 2022 |
| Entroware     | Triton                      | Notebook    | [2bfa3e5cc8](https://linux-hardware.org/?probe=2bfa3e5cc8) | May 20, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [3af76337a4](https://linux-hardware.org/?probe=3af76337a4) | May 20, 2022 |
| MSI           | Stealth GS66 12UE           | Notebook    | [98bccdf1f2](https://linux-hardware.org/?probe=98bccdf1f2) | May 20, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [f644b30d69](https://linux-hardware.org/?probe=f644b30d69) | May 20, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [1e441cdd81](https://linux-hardware.org/?probe=1e441cdd81) | May 20, 2022 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [12b3ea9a8b](https://linux-hardware.org/?probe=12b3ea9a8b) | May 20, 2022 |
| Acer          | Aspire C24-865              | All in one  | [97f59bfda5](https://linux-hardware.org/?probe=97f59bfda5) | May 20, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | Notebook    | [59279fc1ba](https://linux-hardware.org/?probe=59279fc1ba) | May 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [20309ca84a](https://linux-hardware.org/?probe=20309ca84a) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [73c9c54bb6](https://linux-hardware.org/?probe=73c9c54bb6) | May 20, 2022 |
| Medion        | H81H3-EM2                   | Desktop     | [ba616a92bf](https://linux-hardware.org/?probe=ba616a92bf) | May 20, 2022 |
| Acer          | Z2621G                      | All in one  | [139c780029](https://linux-hardware.org/?probe=139c780029) | May 20, 2022 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [7dcdef576a](https://linux-hardware.org/?probe=7dcdef576a) | May 20, 2022 |
| Alienware     | x17 R2                      | Notebook    | [019dbb46a4](https://linux-hardware.org/?probe=019dbb46a4) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a69b44dedb](https://linux-hardware.org/?probe=a69b44dedb) | May 20, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [8b4b27f72d](https://linux-hardware.org/?probe=8b4b27f72d) | May 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [e876753143](https://linux-hardware.org/?probe=e876753143) | May 20, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [f4894739f4](https://linux-hardware.org/?probe=f4894739f4) | May 20, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1b672f1faa](https://linux-hardware.org/?probe=1b672f1faa) | May 20, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [5c989cad8d](https://linux-hardware.org/?probe=5c989cad8d) | May 20, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [d2232927a7](https://linux-hardware.org/?probe=d2232927a7) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [586933cfe0](https://linux-hardware.org/?probe=586933cfe0) | May 20, 2022 |
| HP            | ZBook Studio 16.0 inch G... | Notebook    | [7b11b85bc2](https://linux-hardware.org/?probe=7b11b85bc2) | May 19, 2022 |
| HP            | 8767 A                      | Desktop     | [a1b50431fa](https://linux-hardware.org/?probe=a1b50431fa) | May 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [342929d56c](https://linux-hardware.org/?probe=342929d56c) | May 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7a5744012f](https://linux-hardware.org/?probe=7a5744012f) | May 19, 2022 |
| MSI           | MPG B550I GAMING EDGE MA... | Desktop     | [407d3e4f43](https://linux-hardware.org/?probe=407d3e4f43) | May 19, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [9f4f14ebd1](https://linux-hardware.org/?probe=9f4f14ebd1) | May 19, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [bdc2dbdba3](https://linux-hardware.org/?probe=bdc2dbdba3) | May 19, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [8e4aca2b1f](https://linux-hardware.org/?probe=8e4aca2b1f) | May 19, 2022 |
| Intel         | ChiefRiver                  | Desktop     | [4d38806404](https://linux-hardware.org/?probe=4d38806404) | May 19, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [6a9166ca20](https://linux-hardware.org/?probe=6a9166ca20) | May 19, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [dd7489603b](https://linux-hardware.org/?probe=dd7489603b) | May 19, 2022 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [e05dd4d3f6](https://linux-hardware.org/?probe=e05dd4d3f6) | May 19, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d5712e1976](https://linux-hardware.org/?probe=d5712e1976) | May 19, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [6ea1e6d50a](https://linux-hardware.org/?probe=6ea1e6d50a) | May 19, 2022 |
| MSI           | Prestige 14 A12UC           | Notebook    | [189b62a372](https://linux-hardware.org/?probe=189b62a372) | May 19, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [af3a0c021a](https://linux-hardware.org/?probe=af3a0c021a) | May 19, 2022 |
| HP            | 8924 0100                   | All in one  | [67c69eba1d](https://linux-hardware.org/?probe=67c69eba1d) | May 19, 2022 |
| HP            | 8924 0100                   | All in one  | [496b64fffa](https://linux-hardware.org/?probe=496b64fffa) | May 19, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [1472f65ca0](https://linux-hardware.org/?probe=1472f65ca0) | May 19, 2022 |
| SLIMBOOK      | PROX14-10                   | Notebook    | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [2db4f5f5ff](https://linux-hardware.org/?probe=2db4f5f5ff) | May 19, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [d30a648e90](https://linux-hardware.org/?probe=d30a648e90) | May 19, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [6d97ad191a](https://linux-hardware.org/?probe=6d97ad191a) | May 19, 2022 |
| Samsung       | 930QDB                      | Convertible | [42c8637cfa](https://linux-hardware.org/?probe=42c8637cfa) | May 19, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [d845952849](https://linux-hardware.org/?probe=d845952849) | May 19, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Gigabyte      | AX370M-DS3H-CF              | Desktop     | [39fb6cd4e3](https://linux-hardware.org/?probe=39fb6cd4e3) | May 19, 2022 |
| Acer          | Swift SF314-52              | Notebook    | [4c199417ea](https://linux-hardware.org/?probe=4c199417ea) | May 19, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b2eceeef6d](https://linux-hardware.org/?probe=b2eceeef6d) | May 19, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [736bd1ab68](https://linux-hardware.org/?probe=736bd1ab68) | May 18, 2022 |
| Alienware     | m15                         | Notebook    | [88f12bc13a](https://linux-hardware.org/?probe=88f12bc13a) | May 18, 2022 |
| ASUSTek       | PRIME B360M-D               | Desktop     | [6a00f5f597](https://linux-hardware.org/?probe=6a00f5f597) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [6c41f73e8a](https://linux-hardware.org/?probe=6c41f73e8a) | May 18, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [90d9ac6bf3](https://linux-hardware.org/?probe=90d9ac6bf3) | May 18, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [6aea229376](https://linux-hardware.org/?probe=6aea229376) | May 18, 2022 |
| ECS           | GF7050VT-M5                 | Desktop     | [485f780320](https://linux-hardware.org/?probe=485f780320) | May 18, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [ab5a307891](https://linux-hardware.org/?probe=ab5a307891) | May 18, 2022 |
| Dell          | Latitude 5400               | Notebook    | [402603a522](https://linux-hardware.org/?probe=402603a522) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [54f3323bd2](https://linux-hardware.org/?probe=54f3323bd2) | May 18, 2022 |
| Microsoft     | Surface 3                   | Tablet      | [37b1a8f178](https://linux-hardware.org/?probe=37b1a8f178) | May 18, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [57610c67ba](https://linux-hardware.org/?probe=57610c67ba) | May 18, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [1ef52e97fa](https://linux-hardware.org/?probe=1ef52e97fa) | May 18, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [eaea352b1a](https://linux-hardware.org/?probe=eaea352b1a) | May 18, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [60579b7d68](https://linux-hardware.org/?probe=60579b7d68) | May 18, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [badf4d0a88](https://linux-hardware.org/?probe=badf4d0a88) | May 18, 2022 |
| Gigabyte      | Z370 AORUS ULTRA GAMING-... | Desktop     | [ea23b1fec2](https://linux-hardware.org/?probe=ea23b1fec2) | May 18, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [9ff24e3f8b](https://linux-hardware.org/?probe=9ff24e3f8b) | May 18, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [13bacdb7b6](https://linux-hardware.org/?probe=13bacdb7b6) | May 18, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [a1b9d7e608](https://linux-hardware.org/?probe=a1b9d7e608) | May 18, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [66a07f5e71](https://linux-hardware.org/?probe=66a07f5e71) | May 18, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [1dba88e243](https://linux-hardware.org/?probe=1dba88e243) | May 18, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [3856a337bb](https://linux-hardware.org/?probe=3856a337bb) | May 18, 2022 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [99e949c3e8](https://linux-hardware.org/?probe=99e949c3e8) | May 18, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [6fba9a10da](https://linux-hardware.org/?probe=6fba9a10da) | May 18, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [87a148ac90](https://linux-hardware.org/?probe=87a148ac90) | May 18, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [cb6038cd9b](https://linux-hardware.org/?probe=cb6038cd9b) | May 18, 2022 |
| Acer          | Aspire 5250                 | Notebook    | [7ca9e60266](https://linux-hardware.org/?probe=7ca9e60266) | May 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [2b8318661b](https://linux-hardware.org/?probe=2b8318661b) | May 17, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [625d790cde](https://linux-hardware.org/?probe=625d790cde) | May 17, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [216bdf2075](https://linux-hardware.org/?probe=216bdf2075) | May 17, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [f92e29b330](https://linux-hardware.org/?probe=f92e29b330) | May 17, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [5fee96836d](https://linux-hardware.org/?probe=5fee96836d) | May 17, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [1bce5b14e3](https://linux-hardware.org/?probe=1bce5b14e3) | May 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [a76c24b01b](https://linux-hardware.org/?probe=a76c24b01b) | May 17, 2022 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [78a9ab4d15](https://linux-hardware.org/?probe=78a9ab4d15) | May 17, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [9a945a6cf5](https://linux-hardware.org/?probe=9a945a6cf5) | May 17, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [8bf515d1d3](https://linux-hardware.org/?probe=8bf515d1d3) | May 17, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ac086e77c6](https://linux-hardware.org/?probe=ac086e77c6) | May 17, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [ce6b14cd55](https://linux-hardware.org/?probe=ce6b14cd55) | May 17, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [6459eab7e8](https://linux-hardware.org/?probe=6459eab7e8) | May 17, 2022 |
| HP            | 8924 0100                   | All in one  | [ba5d4617f9](https://linux-hardware.org/?probe=ba5d4617f9) | May 17, 2022 |
| Lenovo        | SDK0F82993 WIN              | All in one  | [39c4df81a2](https://linux-hardware.org/?probe=39c4df81a2) | May 17, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [2886b99972](https://linux-hardware.org/?probe=2886b99972) | May 17, 2022 |
| Dell          | Inspiron 5735               | Notebook    | [b678e46de2](https://linux-hardware.org/?probe=b678e46de2) | May 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [f08826b5b4](https://linux-hardware.org/?probe=f08826b5b4) | May 17, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [e0697c999e](https://linux-hardware.org/?probe=e0697c999e) | May 17, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [7709c37037](https://linux-hardware.org/?probe=7709c37037) | May 17, 2022 |
| Microsoft     | Surface Book 3              | Tablet      | [343a0ed611](https://linux-hardware.org/?probe=343a0ed611) | May 17, 2022 |
| Acer          | Aspire one 1-431            | Notebook    | [33b2da3e70](https://linux-hardware.org/?probe=33b2da3e70) | May 17, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [e7e00fe579](https://linux-hardware.org/?probe=e7e00fe579) | May 17, 2022 |
| Dell          | Precision 5560              | Notebook    | [f7b7c1b7ac](https://linux-hardware.org/?probe=f7b7c1b7ac) | May 17, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [1d12d6b59a](https://linux-hardware.org/?probe=1d12d6b59a) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | Notebook    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [e3bdbed050](https://linux-hardware.org/?probe=e3bdbed050) | May 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [097aa719da](https://linux-hardware.org/?probe=097aa719da) | May 16, 2022 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [2298d45b84](https://linux-hardware.org/?probe=2298d45b84) | May 16, 2022 |
| HP            | 22F8                        | Desktop     | [70f6561c5c](https://linux-hardware.org/?probe=70f6561c5c) | May 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [031c2ec486](https://linux-hardware.org/?probe=031c2ec486) | May 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [d4f9f894b6](https://linux-hardware.org/?probe=d4f9f894b6) | May 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1454db93a0](https://linux-hardware.org/?probe=1454db93a0) | May 16, 2022 |
| Teclast       | F15 Plus                    | Notebook    | [1163da6e09](https://linux-hardware.org/?probe=1163da6e09) | May 16, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [6d5340f5fa](https://linux-hardware.org/?probe=6d5340f5fa) | May 16, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [5f3fea62ab](https://linux-hardware.org/?probe=5f3fea62ab) | May 16, 2022 |
| Lenovo        | G580 2189                   | Notebook    | [e7de790c8a](https://linux-hardware.org/?probe=e7de790c8a) | May 16, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | Notebook    | [2b5c24c068](https://linux-hardware.org/?probe=2b5c24c068) | May 16, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [faf97fa9a0](https://linux-hardware.org/?probe=faf97fa9a0) | May 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b9b65db051](https://linux-hardware.org/?probe=b9b65db051) | May 16, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [1b0cb5afca](https://linux-hardware.org/?probe=1b0cb5afca) | May 16, 2022 |
| Alienware     | x17 R2                      | Notebook    | [b755419e26](https://linux-hardware.org/?probe=b755419e26) | May 16, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [915b4b3bf1](https://linux-hardware.org/?probe=915b4b3bf1) | May 16, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [6c433b3b60](https://linux-hardware.org/?probe=6c433b3b60) | May 16, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [3bf7390ce3](https://linux-hardware.org/?probe=3bf7390ce3) | May 16, 2022 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [246f442b9b](https://linux-hardware.org/?probe=246f442b9b) | May 15, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [71b7fc78c3](https://linux-hardware.org/?probe=71b7fc78c3) | May 15, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [e2ed8b47c2](https://linux-hardware.org/?probe=e2ed8b47c2) | May 15, 2022 |
| Dell          | 02P9X9 A05                  | Server      | [ecd211b72b](https://linux-hardware.org/?probe=ecd211b72b) | May 15, 2022 |
| Dell          | 02P9X9 A05                  | Server      | [182b2c11c5](https://linux-hardware.org/?probe=182b2c11c5) | May 15, 2022 |
| Alienware     | m15                         | Notebook    | [1cadce5105](https://linux-hardware.org/?probe=1cadce5105) | May 15, 2022 |
| MSI           | GS73VR 7RG                  | Notebook    | [3815425b08](https://linux-hardware.org/?probe=3815425b08) | May 15, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [7de7df5240](https://linux-hardware.org/?probe=7de7df5240) | May 15, 2022 |
| Dell          | Latitude E5420              | Notebook    | [12b3efbfad](https://linux-hardware.org/?probe=12b3efbfad) | May 15, 2022 |
| Dell          | Latitude E5420              | Notebook    | [f6050892da](https://linux-hardware.org/?probe=f6050892da) | May 15, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [5ad0b4a6c6](https://linux-hardware.org/?probe=5ad0b4a6c6) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [99976087b6](https://linux-hardware.org/?probe=99976087b6) | May 15, 2022 |
| Acer          | H57M01                      | Desktop     | [9116ecebcb](https://linux-hardware.org/?probe=9116ecebcb) | May 15, 2022 |
| MSI           | GX60 1AC                    | Notebook    | [5d29d3316a](https://linux-hardware.org/?probe=5d29d3316a) | May 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [d4e303b92c](https://linux-hardware.org/?probe=d4e303b92c) | May 15, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [8eff9fb0c8](https://linux-hardware.org/?probe=8eff9fb0c8) | May 15, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [a2fa413622](https://linux-hardware.org/?probe=a2fa413622) | May 15, 2022 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [af5eec886b](https://linux-hardware.org/?probe=af5eec886b) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [021f95ce24](https://linux-hardware.org/?probe=021f95ce24) | May 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9ce2f8b28b](https://linux-hardware.org/?probe=9ce2f8b28b) | May 15, 2022 |
| TUXEDO        | P95_HR                      | Notebook    | [05d8136964](https://linux-hardware.org/?probe=05d8136964) | May 15, 2022 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [e819cbe6f7](https://linux-hardware.org/?probe=e819cbe6f7) | May 15, 2022 |
| Toshiba       | Satellite L50-A-115         | Notebook    | [186b630cd2](https://linux-hardware.org/?probe=186b630cd2) | May 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3d2e586d03](https://linux-hardware.org/?probe=3d2e586d03) | May 15, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5f67a595f4](https://linux-hardware.org/?probe=5f67a595f4) | May 15, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [a58685906f](https://linux-hardware.org/?probe=a58685906f) | May 15, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [d247cf55a1](https://linux-hardware.org/?probe=d247cf55a1) | May 15, 2022 |
| ASUSTek       | K52De                       | Notebook    | [83206ce723](https://linux-hardware.org/?probe=83206ce723) | May 14, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5ce4d54b58](https://linux-hardware.org/?probe=5ce4d54b58) | May 14, 2022 |
| Intel         | NUC11DBBi7 M17027-402       | Mini pc     | [eb66ae7323](https://linux-hardware.org/?probe=eb66ae7323) | May 14, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [b28d047360](https://linux-hardware.org/?probe=b28d047360) | May 14, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [d7f98d5384](https://linux-hardware.org/?probe=d7f98d5384) | May 14, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [36ccfac84d](https://linux-hardware.org/?probe=36ccfac84d) | May 14, 2022 |
| Lenovo        | ThinkPad T500 2241W2B       | Notebook    | [2bd7b2d9a4](https://linux-hardware.org/?probe=2bd7b2d9a4) | May 14, 2022 |
| LG Electro... | 15Z990-HA50K                | Notebook    | [e5cf57d2f4](https://linux-hardware.org/?probe=e5cf57d2f4) | May 14, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [b061586ff0](https://linux-hardware.org/?probe=b061586ff0) | May 14, 2022 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [a292b16ff7](https://linux-hardware.org/?probe=a292b16ff7) | May 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [0f4e4f3887](https://linux-hardware.org/?probe=0f4e4f3887) | May 14, 2022 |
| Lenovo        | IdeaPad Flex-14IWL 81SQ     | Convertible | [5fec8110f3](https://linux-hardware.org/?probe=5fec8110f3) | May 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [bf7abc840c](https://linux-hardware.org/?probe=bf7abc840c) | May 14, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [3fc95850aa](https://linux-hardware.org/?probe=3fc95850aa) | May 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [d4ea8d2b79](https://linux-hardware.org/?probe=d4ea8d2b79) | May 14, 2022 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [975e7a6b47](https://linux-hardware.org/?probe=975e7a6b47) | May 14, 2022 |
| Acer          | H57M01                      | Desktop     | [42100344af](https://linux-hardware.org/?probe=42100344af) | May 14, 2022 |
| ASUSTek       | N73SV                       | Notebook    | [062b80185f](https://linux-hardware.org/?probe=062b80185f) | May 14, 2022 |
| Intel         | NUC8BEB J72692-306          | Mini pc     | [a9c9d7da8d](https://linux-hardware.org/?probe=a9c9d7da8d) | May 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [107ca55bd4](https://linux-hardware.org/?probe=107ca55bd4) | May 14, 2022 |
| Intel         | X99 V1.0                    | Desktop     | [554b088978](https://linux-hardware.org/?probe=554b088978) | May 14, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [1090b6739e](https://linux-hardware.org/?probe=1090b6739e) | May 14, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [4fe9787a82](https://linux-hardware.org/?probe=4fe9787a82) | May 14, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [f784f7eb95](https://linux-hardware.org/?probe=f784f7eb95) | May 14, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [6c320568d0](https://linux-hardware.org/?probe=6c320568d0) | May 14, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [6af47b6a1c](https://linux-hardware.org/?probe=6af47b6a1c) | May 14, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [f367f3bb66](https://linux-hardware.org/?probe=f367f3bb66) | May 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eab2c9895a](https://linux-hardware.org/?probe=eab2c9895a) | May 14, 2022 |
| Lenovo        | Legion Y7000P 2019 81Q5     | Notebook    | [2b7a0725f0](https://linux-hardware.org/?probe=2b7a0725f0) | May 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eab6a0ee2a](https://linux-hardware.org/?probe=eab6a0ee2a) | May 14, 2022 |
| HP            | Pavilion g7                 | Notebook    | [d08c014458](https://linux-hardware.org/?probe=d08c014458) | May 14, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [3eaceb3a18](https://linux-hardware.org/?probe=3eaceb3a18) | May 14, 2022 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [1fbf8759b0](https://linux-hardware.org/?probe=1fbf8759b0) | May 14, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [4316b121b1](https://linux-hardware.org/?probe=4316b121b1) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [37e8088329](https://linux-hardware.org/?probe=37e8088329) | May 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [7f46e36f35](https://linux-hardware.org/?probe=7f46e36f35) | May 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [81b3317aa8](https://linux-hardware.org/?probe=81b3317aa8) | May 14, 2022 |
| Acer          | Aspire R5-571T              | Notebook    | [4d1362123c](https://linux-hardware.org/?probe=4d1362123c) | May 14, 2022 |
| Dell          | Inspiron 7380               | Notebook    | [ce19144efb](https://linux-hardware.org/?probe=ce19144efb) | May 14, 2022 |
| Samsung       | 940X5N                      | Convertible | [5464750288](https://linux-hardware.org/?probe=5464750288) | May 13, 2022 |
| Acer          | Veriton M670G               | Desktop     | [a583d3a342](https://linux-hardware.org/?probe=a583d3a342) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [58f371c0d7](https://linux-hardware.org/?probe=58f371c0d7) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0e9a009c11](https://linux-hardware.org/?probe=0e9a009c11) | May 13, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [5693f5ee45](https://linux-hardware.org/?probe=5693f5ee45) | May 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [836b9e0442](https://linux-hardware.org/?probe=836b9e0442) | May 13, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [8af018aabb](https://linux-hardware.org/?probe=8af018aabb) | May 13, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [fd15b34806](https://linux-hardware.org/?probe=fd15b34806) | May 13, 2022 |
| Shuttle       | DS10U                       | Desktop     | [2f2acb55e9](https://linux-hardware.org/?probe=2f2acb55e9) | May 13, 2022 |
| HP            | 250 G4 Notebook PC          | Notebook    | [996bc01199](https://linux-hardware.org/?probe=996bc01199) | May 13, 2022 |
| Acer          | Aspire C24-865              | All in one  | [b164e17b68](https://linux-hardware.org/?probe=b164e17b68) | May 13, 2022 |
| Sony          | VPCEH1M0E                   | Notebook    | [eefe7eee06](https://linux-hardware.org/?probe=eefe7eee06) | May 13, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [06030eee20](https://linux-hardware.org/?probe=06030eee20) | May 13, 2022 |
| AVITA         | NS14A8                      | Notebook    | [bc86f7a17e](https://linux-hardware.org/?probe=bc86f7a17e) | May 13, 2022 |
| ASUSTek       | X551MA                      | Notebook    | [6a39b7b0da](https://linux-hardware.org/?probe=6a39b7b0da) | May 13, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [4bc9a160a1](https://linux-hardware.org/?probe=4bc9a160a1) | May 13, 2022 |
| Intel         | NUC11DBBi7 M17027-402       | Mini pc     | [bf859bebee](https://linux-hardware.org/?probe=bf859bebee) | May 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [6251446c92](https://linux-hardware.org/?probe=6251446c92) | May 13, 2022 |
| Dell          | G3 3779                     | Notebook    | [c1da54a43b](https://linux-hardware.org/?probe=c1da54a43b) | May 13, 2022 |
| Intel         | DH67BL AAG10189-210         | Desktop     | [2340d530cd](https://linux-hardware.org/?probe=2340d530cd) | May 13, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [40cc6f33b5](https://linux-hardware.org/?probe=40cc6f33b5) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [ed659a9633](https://linux-hardware.org/?probe=ed659a9633) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f7d3a9220c](https://linux-hardware.org/?probe=f7d3a9220c) | May 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3fe223176c](https://linux-hardware.org/?probe=3fe223176c) | May 13, 2022 |
| Acer          | Aspire X3400                | Desktop     | [9dd76b4599](https://linux-hardware.org/?probe=9dd76b4599) | May 13, 2022 |
| Intel         | NUC11DBBi7 M17027-402       | Mini pc     | [70ec843de0](https://linux-hardware.org/?probe=70ec843de0) | May 13, 2022 |
| Acer          | Aspire X3400                | Desktop     | [b590b149fc](https://linux-hardware.org/?probe=b590b149fc) | May 13, 2022 |
| HP            | Pavilion 17                 | Notebook    | [60fbd20766](https://linux-hardware.org/?probe=60fbd20766) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [24d4683d52](https://linux-hardware.org/?probe=24d4683d52) | May 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ff2faf9bb7](https://linux-hardware.org/?probe=ff2faf9bb7) | May 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [235beb3d5f](https://linux-hardware.org/?probe=235beb3d5f) | May 13, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [7d7287d1b8](https://linux-hardware.org/?probe=7d7287d1b8) | May 13, 2022 |
| Lenovo        | ThinkPad T420s 4170CTO      | Notebook    | [4e58c3e210](https://linux-hardware.org/?probe=4e58c3e210) | May 13, 2022 |
| Dell          | Latitude 3400               | Notebook    | [caa5d59cbd](https://linux-hardware.org/?probe=caa5d59cbd) | May 13, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [a2abab3a72](https://linux-hardware.org/?probe=a2abab3a72) | May 13, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a2e10758ca](https://linux-hardware.org/?probe=a2e10758ca) | May 13, 2022 |
| Dell          | Inspiron 3541               | Notebook    | [7873185850](https://linux-hardware.org/?probe=7873185850) | May 12, 2022 |
| Dell          | 0773VG A02                  | Desktop     | [0743f4573d](https://linux-hardware.org/?probe=0743f4573d) | May 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [5ea934bd19](https://linux-hardware.org/?probe=5ea934bd19) | May 12, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e854926e0](https://linux-hardware.org/?probe=8e854926e0) | May 12, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f3ad419505](https://linux-hardware.org/?probe=f3ad419505) | May 12, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [1c358bb926](https://linux-hardware.org/?probe=1c358bb926) | May 12, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [2e7753a944](https://linux-hardware.org/?probe=2e7753a944) | May 12, 2022 |
| Dell          | 0HY9JP A01                  | Desktop     | [0026740e3f](https://linux-hardware.org/?probe=0026740e3f) | May 12, 2022 |
| TUXEDO        | N2x0WU                      | Notebook    | [b70a08c999](https://linux-hardware.org/?probe=b70a08c999) | May 12, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [4d2b2c6a3c](https://linux-hardware.org/?probe=4d2b2c6a3c) | May 12, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [a9e9868b12](https://linux-hardware.org/?probe=a9e9868b12) | May 12, 2022 |
| Alienware     | x17 R2                      | Notebook    | [0a81fc619e](https://linux-hardware.org/?probe=0a81fc619e) | May 12, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [a80ef1636d](https://linux-hardware.org/?probe=a80ef1636d) | May 12, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [eaefbf2773](https://linux-hardware.org/?probe=eaefbf2773) | May 12, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [a4ce7187a6](https://linux-hardware.org/?probe=a4ce7187a6) | May 12, 2022 |
| Shuttle       | FH87                        | Desktop     | [42cb5c0ef7](https://linux-hardware.org/?probe=42cb5c0ef7) | May 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [91404c39c7](https://linux-hardware.org/?probe=91404c39c7) | May 12, 2022 |
| Dell          | Latitude 5520               | Notebook    | [927a4b0ed0](https://linux-hardware.org/?probe=927a4b0ed0) | May 12, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [d4fa91d7b4](https://linux-hardware.org/?probe=d4fa91d7b4) | May 12, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [d2b843c446](https://linux-hardware.org/?probe=d2b843c446) | May 12, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [ac2dfe7138](https://linux-hardware.org/?probe=ac2dfe7138) | May 12, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [debbc95647](https://linux-hardware.org/?probe=debbc95647) | May 12, 2022 |
| HP            | 0AECh D                     | Desktop     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [578328d0b5](https://linux-hardware.org/?probe=578328d0b5) | May 12, 2022 |
| Acer          | Swift SF514-55T             | Notebook    | [02cae91736](https://linux-hardware.org/?probe=02cae91736) | May 12, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [c195f80f3c](https://linux-hardware.org/?probe=c195f80f3c) | May 12, 2022 |
| Chuwi         | MiniBook X                  | Notebook    | [541609a32e](https://linux-hardware.org/?probe=541609a32e) | May 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [7931f8191f](https://linux-hardware.org/?probe=7931f8191f) | May 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [271a8ba23e](https://linux-hardware.org/?probe=271a8ba23e) | May 11, 2022 |
| HP            | Pavilion dv6                | Notebook    | [9e5da14b9f](https://linux-hardware.org/?probe=9e5da14b9f) | May 11, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a6f3293aea](https://linux-hardware.org/?probe=a6f3293aea) | May 11, 2022 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Notebook    | [dd8a564470](https://linux-hardware.org/?probe=dd8a564470) | May 11, 2022 |
| MSI           | Z97S SLI Krait Edition      | Desktop     | [861cbb7b6e](https://linux-hardware.org/?probe=861cbb7b6e) | May 11, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [14f5c24c81](https://linux-hardware.org/?probe=14f5c24c81) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [c01cff4387](https://linux-hardware.org/?probe=c01cff4387) | May 11, 2022 |
| ASUSTek       | K54LY                       | Notebook    | [9e60c12b38](https://linux-hardware.org/?probe=9e60c12b38) | May 11, 2022 |
| Dell          | 0WMJ54 A00                  | Desktop     | [393406b0e8](https://linux-hardware.org/?probe=393406b0e8) | May 11, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [0e12a4aa26](https://linux-hardware.org/?probe=0e12a4aa26) | May 11, 2022 |
| Intel         | B75                         | Desktop     | [d2a9132d48](https://linux-hardware.org/?probe=d2a9132d48) | May 11, 2022 |
| Dell          | 0F96C8 A00                  | All in one  | [b0e5c67fda](https://linux-hardware.org/?probe=b0e5c67fda) | May 11, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [c378efbd3d](https://linux-hardware.org/?probe=c378efbd3d) | May 11, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [62c6121a76](https://linux-hardware.org/?probe=62c6121a76) | May 11, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [dae406c3b6](https://linux-hardware.org/?probe=dae406c3b6) | May 11, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [64f2ed4df2](https://linux-hardware.org/?probe=64f2ed4df2) | May 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [7286fd4e36](https://linux-hardware.org/?probe=7286fd4e36) | May 11, 2022 |
| HP            | 15                          | Notebook    | [c54400b509](https://linux-hardware.org/?probe=c54400b509) | May 11, 2022 |
| Google        | Rabbid                      | Notebook    | [2cabce6789](https://linux-hardware.org/?probe=2cabce6789) | May 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [65e46938b9](https://linux-hardware.org/?probe=65e46938b9) | May 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [26e3806b59](https://linux-hardware.org/?probe=26e3806b59) | May 10, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [718b76a026](https://linux-hardware.org/?probe=718b76a026) | May 10, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5b6165bc68](https://linux-hardware.org/?probe=5b6165bc68) | May 10, 2022 |
| Dell          | Precision 5750              | Notebook    | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| HP            | 2000                        | Notebook    | [d0e74bfff6](https://linux-hardware.org/?probe=d0e74bfff6) | May 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [ce3addb8a4](https://linux-hardware.org/?probe=ce3addb8a4) | May 10, 2022 |
| ASRock        | B550 Steel Legend           | Desktop     | [a940d31b37](https://linux-hardware.org/?probe=a940d31b37) | May 10, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | Desktop     | [74862d462d](https://linux-hardware.org/?probe=74862d462d) | May 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [47b730f9bd](https://linux-hardware.org/?probe=47b730f9bd) | May 10, 2022 |
| Toshiba       | PORTEGE Z930                | Notebook    | [fff817aea6](https://linux-hardware.org/?probe=fff817aea6) | May 10, 2022 |
| Gigabyte      | H97N                        | Desktop     | [21f1bf0f0c](https://linux-hardware.org/?probe=21f1bf0f0c) | May 10, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [b9afe34b9a](https://linux-hardware.org/?probe=b9afe34b9a) | May 10, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [3d0817538d](https://linux-hardware.org/?probe=3d0817538d) | May 10, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [02925e8fac](https://linux-hardware.org/?probe=02925e8fac) | May 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [0c00ea5df7](https://linux-hardware.org/?probe=0c00ea5df7) | May 10, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ec67204e7c](https://linux-hardware.org/?probe=ec67204e7c) | May 10, 2022 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [67b3694f6a](https://linux-hardware.org/?probe=67b3694f6a) | May 10, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [37806600f2](https://linux-hardware.org/?probe=37806600f2) | May 10, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [82bbcd17e8](https://linux-hardware.org/?probe=82bbcd17e8) | May 10, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [66e2cf708d](https://linux-hardware.org/?probe=66e2cf708d) | May 10, 2022 |
| Otazak        | iPC45                       | Convertible | [a4918ca165](https://linux-hardware.org/?probe=a4918ca165) | May 10, 2022 |
| ASRock        | J4105B-ITX                  | Desktop     | [6e507d9a68](https://linux-hardware.org/?probe=6e507d9a68) | May 09, 2022 |
| ECS           | A68M-C4DL                   | Desktop     | [b8c60cf7a0](https://linux-hardware.org/?probe=b8c60cf7a0) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [05b7c2c72c](https://linux-hardware.org/?probe=05b7c2c72c) | May 09, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a9e6ecf483](https://linux-hardware.org/?probe=a9e6ecf483) | May 09, 2022 |
| ASUSTek       | PRIME Z690M-HZ              | Desktop     | [7987b700d5](https://linux-hardware.org/?probe=7987b700d5) | May 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [ae80aa69fe](https://linux-hardware.org/?probe=ae80aa69fe) | May 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [b57ce8e7e1](https://linux-hardware.org/?probe=b57ce8e7e1) | May 09, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [b3cac7c464](https://linux-hardware.org/?probe=b3cac7c464) | May 09, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [38e20673c2](https://linux-hardware.org/?probe=38e20673c2) | May 09, 2022 |
| ASRock        | J4105B-ITX                  | Desktop     | [c4eea9f630](https://linux-hardware.org/?probe=c4eea9f630) | May 09, 2022 |
| Intel         | H61                         | Desktop     | [3f5d8ae941](https://linux-hardware.org/?probe=3f5d8ae941) | May 09, 2022 |
| Lenovo        | ThinkPad T430s 2356JR1      | Notebook    | [2c97326b6b](https://linux-hardware.org/?probe=2c97326b6b) | May 09, 2022 |
| Chuwi         | UBook X                     | Convertible | [4c17a86234](https://linux-hardware.org/?probe=4c17a86234) | May 09, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [65d7984ad4](https://linux-hardware.org/?probe=65d7984ad4) | May 09, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [34a4a272f5](https://linux-hardware.org/?probe=34a4a272f5) | May 09, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b93966ec3c](https://linux-hardware.org/?probe=b93966ec3c) | May 09, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [5e07819ad6](https://linux-hardware.org/?probe=5e07819ad6) | May 09, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [2b88c091bf](https://linux-hardware.org/?probe=2b88c091bf) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [f48ef1adaf](https://linux-hardware.org/?probe=f48ef1adaf) | May 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [ceaf962cba](https://linux-hardware.org/?probe=ceaf962cba) | May 09, 2022 |
| Dell          | Precision 5540              | Notebook    | [1744609574](https://linux-hardware.org/?probe=1744609574) | May 09, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [22dd4a6344](https://linux-hardware.org/?probe=22dd4a6344) | May 09, 2022 |
| HP            | Pavilion g6                 | Notebook    | [267b134fdd](https://linux-hardware.org/?probe=267b134fdd) | May 09, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [71e7f1c760](https://linux-hardware.org/?probe=71e7f1c760) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [89f0b017b1](https://linux-hardware.org/?probe=89f0b017b1) | May 09, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [bd7335e1cd](https://linux-hardware.org/?probe=bd7335e1cd) | May 09, 2022 |
| Gateway       | P-7805u                     | Notebook    | [0192b23d62](https://linux-hardware.org/?probe=0192b23d62) | May 09, 2022 |
| ASUSTek       | Pro WS C621-64L SAGE-10G... | Desktop     | [4ebf4d9cc8](https://linux-hardware.org/?probe=4ebf4d9cc8) | May 09, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d18df271fd](https://linux-hardware.org/?probe=d18df271fd) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [77145b587d](https://linux-hardware.org/?probe=77145b587d) | May 09, 2022 |
| Gigabyte      | Z97X-Gaming 5               | Desktop     | [e3f65dec10](https://linux-hardware.org/?probe=e3f65dec10) | May 09, 2022 |
| Dell          | Precision 7510              | Notebook    | [5f3136d1fd](https://linux-hardware.org/?probe=5f3136d1fd) | May 09, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [422c9f9cae](https://linux-hardware.org/?probe=422c9f9cae) | May 09, 2022 |
| Google        | Blooglet                    | Notebook    | [64b4f18c1c](https://linux-hardware.org/?probe=64b4f18c1c) | May 09, 2022 |
| CompuLab      | SBC-ATCFL                   | Mini pc     | [bb0c0e7b99](https://linux-hardware.org/?probe=bb0c0e7b99) | May 09, 2022 |
| Google        | Blooglet                    | Notebook    | [f3dc91bf66](https://linux-hardware.org/?probe=f3dc91bf66) | May 09, 2022 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [344bc071a2](https://linux-hardware.org/?probe=344bc071a2) | May 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [f269fd3294](https://linux-hardware.org/?probe=f269fd3294) | May 09, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [aa7c15cb1a](https://linux-hardware.org/?probe=aa7c15cb1a) | May 09, 2022 |
| Acer          | Aspire Z3-705               | All in one  | [a25af1cf28](https://linux-hardware.org/?probe=a25af1cf28) | May 09, 2022 |
| HP            | 1998                        | Desktop     | [bb8d501109](https://linux-hardware.org/?probe=bb8d501109) | May 09, 2022 |
| Toshiba       | IS 1413G                    | Notebook    | [fbb3e61ebf](https://linux-hardware.org/?probe=fbb3e61ebf) | May 09, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [a42f9094ec](https://linux-hardware.org/?probe=a42f9094ec) | May 09, 2022 |
| ASUSTek       | P5Q SE/R                    | Desktop     | [c99b0a0683](https://linux-hardware.org/?probe=c99b0a0683) | May 08, 2022 |
| HP            | Laptop 17z-ca300            | Notebook    | [c43f2b0e29](https://linux-hardware.org/?probe=c43f2b0e29) | May 08, 2022 |
| Acer          | Revo RL80                   | Desktop     | [c48857049a](https://linux-hardware.org/?probe=c48857049a) | May 08, 2022 |
| Dell          | Inspiron 7573               | Convertible | [c09d9d45e5](https://linux-hardware.org/?probe=c09d9d45e5) | May 08, 2022 |
| Pegatron      | Eureka3                     | Desktop     | [e383533179](https://linux-hardware.org/?probe=e383533179) | May 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [69406bff46](https://linux-hardware.org/?probe=69406bff46) | May 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [56ca785331](https://linux-hardware.org/?probe=56ca785331) | May 08, 2022 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [28fc5f92bc](https://linux-hardware.org/?probe=28fc5f92bc) | May 08, 2022 |
| MSI           | GE62 2QD                    | Notebook    | [cef8637026](https://linux-hardware.org/?probe=cef8637026) | May 08, 2022 |
| HP            | ProBook 4520s               | Notebook    | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| HP            | 870C                        | Desktop     | [adb470192a](https://linux-hardware.org/?probe=adb470192a) | May 08, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [abccbed349](https://linux-hardware.org/?probe=abccbed349) | May 08, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [691a4c0ca5](https://linux-hardware.org/?probe=691a4c0ca5) | May 08, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [7ff6997105](https://linux-hardware.org/?probe=7ff6997105) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [acf562b58b](https://linux-hardware.org/?probe=acf562b58b) | May 08, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [1a3e2da376](https://linux-hardware.org/?probe=1a3e2da376) | May 08, 2022 |
| Acer          | Aspire 5253G                | Notebook    | [6f6b26ee56](https://linux-hardware.org/?probe=6f6b26ee56) | May 08, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [97e2613936](https://linux-hardware.org/?probe=97e2613936) | May 08, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [30cfb22760](https://linux-hardware.org/?probe=30cfb22760) | May 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [3227adfd1a](https://linux-hardware.org/?probe=3227adfd1a) | May 07, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c589ad9143](https://linux-hardware.org/?probe=c589ad9143) | May 07, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [6371d77b5d](https://linux-hardware.org/?probe=6371d77b5d) | May 07, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [71e0ef1fc9](https://linux-hardware.org/?probe=71e0ef1fc9) | May 07, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d2932b8b78](https://linux-hardware.org/?probe=d2932b8b78) | May 07, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| HP            | Notebook                    | Notebook    | [04f5e602de](https://linux-hardware.org/?probe=04f5e602de) | May 07, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [0c04c6cb24](https://linux-hardware.org/?probe=0c04c6cb24) | May 07, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [7f0c87b783](https://linux-hardware.org/?probe=7f0c87b783) | May 07, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [c1143872e6](https://linux-hardware.org/?probe=c1143872e6) | May 07, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [5c5f2f2b5c](https://linux-hardware.org/?probe=5c5f2f2b5c) | May 07, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [09480b1677](https://linux-hardware.org/?probe=09480b1677) | May 07, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [3bc2a1e87e](https://linux-hardware.org/?probe=3bc2a1e87e) | May 07, 2022 |
| PC Special... | Recoil II                   | Notebook    | [4eeb154eea](https://linux-hardware.org/?probe=4eeb154eea) | May 07, 2022 |
| ASUSTek       | UX360UAK                    | Convertible | [c0bfa1dddf](https://linux-hardware.org/?probe=c0bfa1dddf) | May 06, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [c0d0f6435b](https://linux-hardware.org/?probe=c0d0f6435b) | May 06, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [cae67b53da](https://linux-hardware.org/?probe=cae67b53da) | May 06, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [e2abcd94ce](https://linux-hardware.org/?probe=e2abcd94ce) | May 06, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [b080a2bae5](https://linux-hardware.org/?probe=b080a2bae5) | May 06, 2022 |
| HP            | 1495                        | Desktop     | [4b63b733be](https://linux-hardware.org/?probe=4b63b733be) | May 06, 2022 |
| Toshiba       | Satellite C70-C-11L         | Notebook    | [32fd52cba1](https://linux-hardware.org/?probe=32fd52cba1) | May 06, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec38b16f17](https://linux-hardware.org/?probe=ec38b16f17) | May 06, 2022 |
| Toshiba       | Satellite C70-C-11L         | Notebook    | [bda878ed3a](https://linux-hardware.org/?probe=bda878ed3a) | May 06, 2022 |
| Toshiba       | dynabook R731/37EK          | Notebook    | [10ed6c8741](https://linux-hardware.org/?probe=10ed6c8741) | May 06, 2022 |
| Medion        | E7222                       | Notebook    | [658905b8e4](https://linux-hardware.org/?probe=658905b8e4) | May 06, 2022 |
| Gateway       | NV55C                       | Notebook    | [2cbbfa9c42](https://linux-hardware.org/?probe=2cbbfa9c42) | May 06, 2022 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7d4d1cb642](https://linux-hardware.org/?probe=7d4d1cb642) | May 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | Notebook    | [1863683cb7](https://linux-hardware.org/?probe=1863683cb7) | May 06, 2022 |
| Acer          | Aspire A317-32              | Notebook    | [ae2c984a96](https://linux-hardware.org/?probe=ae2c984a96) | May 06, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [24340ea9a8](https://linux-hardware.org/?probe=24340ea9a8) | May 06, 2022 |
| Google        | Panther                     | Desktop     | [4b7366ed94](https://linux-hardware.org/?probe=4b7366ed94) | May 06, 2022 |
| ASRock        | B85M DASH/OL R2.0           | Desktop     | [61c86467ba](https://linux-hardware.org/?probe=61c86467ba) | May 06, 2022 |
| Lenovo        | ThinkPad L13 20R3S10R00     | Notebook    | [b173909e06](https://linux-hardware.org/?probe=b173909e06) | May 06, 2022 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [d2eb5ae290](https://linux-hardware.org/?probe=d2eb5ae290) | May 05, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [63540ee2db](https://linux-hardware.org/?probe=63540ee2db) | May 05, 2022 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | Notebook    | [f9bb1a20a9](https://linux-hardware.org/?probe=f9bb1a20a9) | May 05, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [e5edebd8c7](https://linux-hardware.org/?probe=e5edebd8c7) | May 05, 2022 |
| Toshiba       | Satellite C655              | Notebook    | [791bf14da8](https://linux-hardware.org/?probe=791bf14da8) | May 05, 2022 |
| MSI           | B550M PRO-VDH               | Desktop     | [40f4bf344a](https://linux-hardware.org/?probe=40f4bf344a) | May 05, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3055b0e95f](https://linux-hardware.org/?probe=3055b0e95f) | May 05, 2022 |
| Medion        | E7222                       | Notebook    | [1e12090b57](https://linux-hardware.org/?probe=1e12090b57) | May 05, 2022 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [13c20da3be](https://linux-hardware.org/?probe=13c20da3be) | May 05, 2022 |
| Dell          | Latitude 7420               | Notebook    | [7fd2239abb](https://linux-hardware.org/?probe=7fd2239abb) | May 05, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [f26171e0fb](https://linux-hardware.org/?probe=f26171e0fb) | May 05, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [3cab505f0a](https://linux-hardware.org/?probe=3cab505f0a) | May 05, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [3112ea6d6a](https://linux-hardware.org/?probe=3112ea6d6a) | May 05, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [7b488333bb](https://linux-hardware.org/?probe=7b488333bb) | May 05, 2022 |
| Vestel        | V Note 1341                 | Notebook    | [d5a260dc00](https://linux-hardware.org/?probe=d5a260dc00) | May 05, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [f03b0f28ef](https://linux-hardware.org/?probe=f03b0f28ef) | May 05, 2022 |
| MSI           | 770-C45                     | Desktop     | [0e9179888b](https://linux-hardware.org/?probe=0e9179888b) | May 05, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [dc8d8b070e](https://linux-hardware.org/?probe=dc8d8b070e) | May 05, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [145317db95](https://linux-hardware.org/?probe=145317db95) | May 05, 2022 |
| Intel         | NUC8i7HNB J68197-503        | Mini pc     | [54e4287d25](https://linux-hardware.org/?probe=54e4287d25) | May 05, 2022 |
| HP            | Laptop 14-fq0xxx            | Notebook    | [5be2ebf3e2](https://linux-hardware.org/?probe=5be2ebf3e2) | May 05, 2022 |
| Acer          | TravelMate P653-M           | Notebook    | [221d943970](https://linux-hardware.org/?probe=221d943970) | May 04, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [280a764142](https://linux-hardware.org/?probe=280a764142) | May 04, 2022 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [2b8dd47e10](https://linux-hardware.org/?probe=2b8dd47e10) | May 04, 2022 |
| MSI           | H55M-E23                    | Desktop     | [d42084b294](https://linux-hardware.org/?probe=d42084b294) | May 04, 2022 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [540a55671c](https://linux-hardware.org/?probe=540a55671c) | May 04, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d5cd65ba5b](https://linux-hardware.org/?probe=d5cd65ba5b) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [180a5d086f](https://linux-hardware.org/?probe=180a5d086f) | May 04, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [f47683cd76](https://linux-hardware.org/?probe=f47683cd76) | May 04, 2022 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [4ce66ff579](https://linux-hardware.org/?probe=4ce66ff579) | May 04, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d9ec0c5eea](https://linux-hardware.org/?probe=d9ec0c5eea) | May 04, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [156de9d4de](https://linux-hardware.org/?probe=156de9d4de) | May 04, 2022 |
| ASUSTek       | T300FA                      | Notebook    | [af1316bab5](https://linux-hardware.org/?probe=af1316bab5) | May 04, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6c1a4b1bc6](https://linux-hardware.org/?probe=6c1a4b1bc6) | May 04, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [c2ab1a3ec2](https://linux-hardware.org/?probe=c2ab1a3ec2) | May 04, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [7dc76bf420](https://linux-hardware.org/?probe=7dc76bf420) | May 04, 2022 |
| ASUSTek       | B150M PRO GAMING            | Desktop     | [a31ab08668](https://linux-hardware.org/?probe=a31ab08668) | May 04, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [3bdd958639](https://linux-hardware.org/?probe=3bdd958639) | May 04, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | Notebook    | [64eb136705](https://linux-hardware.org/?probe=64eb136705) | May 03, 2022 |
| HP            | Pavilion Laptop 15z-cw10... | Notebook    | [923eb0c417](https://linux-hardware.org/?probe=923eb0c417) | May 03, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e2dfdb6af2](https://linux-hardware.org/?probe=e2dfdb6af2) | May 03, 2022 |
| Acer          | Aspire V5-552G              | Notebook    | [caa6467c0e](https://linux-hardware.org/?probe=caa6467c0e) | May 03, 2022 |
| Acer          | Aspire V5-552G              | Notebook    | [c3255ca484](https://linux-hardware.org/?probe=c3255ca484) | May 03, 2022 |
| Dell          | 0P301D A02                  | Desktop     | [ab9edfbc39](https://linux-hardware.org/?probe=ab9edfbc39) | May 03, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [8e8d49463e](https://linux-hardware.org/?probe=8e8d49463e) | May 03, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [8e512a77d7](https://linux-hardware.org/?probe=8e512a77d7) | May 03, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [0a6358dc13](https://linux-hardware.org/?probe=0a6358dc13) | May 03, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [5d62fcaf51](https://linux-hardware.org/?probe=5d62fcaf51) | May 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS6LB00    | Notebook    | [3d7e88cdae](https://linux-hardware.org/?probe=3d7e88cdae) | May 03, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [e9ad2578c3](https://linux-hardware.org/?probe=e9ad2578c3) | May 03, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [bd62b32976](https://linux-hardware.org/?probe=bd62b32976) | May 03, 2022 |
| Acer          | FX58M                       | Desktop     | [0a6673afb9](https://linux-hardware.org/?probe=0a6673afb9) | May 03, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ecc7f176ff](https://linux-hardware.org/?probe=ecc7f176ff) | May 03, 2022 |
| Lenovo        | IdeaPad Y470 20090          | Notebook    | [690c12e995](https://linux-hardware.org/?probe=690c12e995) | May 03, 2022 |
| Lenovo        | ThinkPad T430 2349AK5       | Notebook    | [78f64f92f3](https://linux-hardware.org/?probe=78f64f92f3) | May 03, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [af004a928f](https://linux-hardware.org/?probe=af004a928f) | May 03, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [ca68b014a7](https://linux-hardware.org/?probe=ca68b014a7) | May 03, 2022 |
| Gigabyte      | H110-D3A-CF                 | Desktop     | [74e69f5610](https://linux-hardware.org/?probe=74e69f5610) | May 03, 2022 |
| Dell          | Inspiron 5755               | Notebook    | [5ae0d07e61](https://linux-hardware.org/?probe=5ae0d07e61) | May 03, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [b32500381a](https://linux-hardware.org/?probe=b32500381a) | May 03, 2022 |
| Acer          | Aspire one 1-131            | Notebook    | [ade813cf7f](https://linux-hardware.org/?probe=ade813cf7f) | May 03, 2022 |
| Shuttle       | FG41 V20                    | Desktop     | [fd07bdf7b5](https://linux-hardware.org/?probe=fd07bdf7b5) | May 02, 2022 |
| Dell          | Precision M4800             | Notebook    | [266c0c151d](https://linux-hardware.org/?probe=266c0c151d) | May 02, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [93884340db](https://linux-hardware.org/?probe=93884340db) | May 02, 2022 |
| Alienware     | 07JNH0 A02                  | Desktop     | [d39a57aed6](https://linux-hardware.org/?probe=d39a57aed6) | May 02, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [09eded1793](https://linux-hardware.org/?probe=09eded1793) | May 02, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [4e6ed2eaa3](https://linux-hardware.org/?probe=4e6ed2eaa3) | May 02, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bbbfaa9157](https://linux-hardware.org/?probe=bbbfaa9157) | May 02, 2022 |
| HP            | Presario CQ42               | Notebook    | [93ac0fd52a](https://linux-hardware.org/?probe=93ac0fd52a) | May 02, 2022 |
| Sony          | VPCS13V9E                   | Notebook    | [0b565d3fac](https://linux-hardware.org/?probe=0b565d3fac) | May 02, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [aa294d2650](https://linux-hardware.org/?probe=aa294d2650) | May 02, 2022 |
| Dell          | Precision 7530              | Notebook    | [ef011e846b](https://linux-hardware.org/?probe=ef011e846b) | May 02, 2022 |
| Toshiba       | Satellite P850              | Notebook    | [8e97662196](https://linux-hardware.org/?probe=8e97662196) | May 02, 2022 |
| Dell          | 09M8Y8 A01                  | Desktop     | [301694185a](https://linux-hardware.org/?probe=301694185a) | May 02, 2022 |
| Avell High... | B.ON                        | Notebook    | [5de402efe5](https://linux-hardware.org/?probe=5de402efe5) | May 02, 2022 |
| Dell          | Latitude E6510              | Notebook    | [916f405c55](https://linux-hardware.org/?probe=916f405c55) | May 02, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [334e009f9c](https://linux-hardware.org/?probe=334e009f9c) | May 02, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [6a29f83afe](https://linux-hardware.org/?probe=6a29f83afe) | May 02, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [88f6586c4b](https://linux-hardware.org/?probe=88f6586c4b) | May 02, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [dd85719ec6](https://linux-hardware.org/?probe=dd85719ec6) | May 02, 2022 |
| Lenovo        | ThinkPad T480 20L50000RT    | Notebook    | [b636694d0c](https://linux-hardware.org/?probe=b636694d0c) | May 02, 2022 |
| Lenovo        | ThinkPad T480 20L50000RT    | Notebook    | [142fb350da](https://linux-hardware.org/?probe=142fb350da) | May 02, 2022 |
| Framework     | Laptop                      | Notebook    | [4de04607db](https://linux-hardware.org/?probe=4de04607db) | May 02, 2022 |
| Dell          | 0HHV7N A00                  | Desktop     | [7636489d8e](https://linux-hardware.org/?probe=7636489d8e) | May 01, 2022 |
| Lenovo        | N22 80S6                    | Notebook    | [f08359857b](https://linux-hardware.org/?probe=f08359857b) | May 01, 2022 |
| ASUSTek       | X550LD                      | Notebook    | [5625deb6aa](https://linux-hardware.org/?probe=5625deb6aa) | May 01, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [99e0958898](https://linux-hardware.org/?probe=99e0958898) | May 01, 2022 |
| Dell          | Vostro 5470                 | Notebook    | [85d403928b](https://linux-hardware.org/?probe=85d403928b) | May 01, 2022 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [fb167ea17d](https://linux-hardware.org/?probe=fb167ea17d) | May 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [0b847ba92b](https://linux-hardware.org/?probe=0b847ba92b) | May 01, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [965ebad5cb](https://linux-hardware.org/?probe=965ebad5cb) | May 01, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c37aaf2585](https://linux-hardware.org/?probe=c37aaf2585) | May 01, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [cb532b211e](https://linux-hardware.org/?probe=cb532b211e) | May 01, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [0eb277ff80](https://linux-hardware.org/?probe=0eb277ff80) | May 01, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [549ca9da46](https://linux-hardware.org/?probe=549ca9da46) | May 01, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [ec3ccc4967](https://linux-hardware.org/?probe=ec3ccc4967) | May 01, 2022 |
| Acer          | TravelMate P253             | Notebook    | [89812a5d4a](https://linux-hardware.org/?probe=89812a5d4a) | May 01, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c396021a33](https://linux-hardware.org/?probe=c396021a33) | May 01, 2022 |
| Dell          | Latitude 3490               | Notebook    | [ff6e81ce15](https://linux-hardware.org/?probe=ff6e81ce15) | May 01, 2022 |
| Acer          | F5-573                      | Notebook    | [47c8b0dd51](https://linux-hardware.org/?probe=47c8b0dd51) | May 01, 2022 |
| Dell          | Vostro 1720                 | Notebook    | [fd52613ee2](https://linux-hardware.org/?probe=fd52613ee2) | May 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2d06b54d63](https://linux-hardware.org/?probe=2d06b54d63) | May 01, 2022 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [e260e2021b](https://linux-hardware.org/?probe=e260e2021b) | May 01, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [50d37d9cf7](https://linux-hardware.org/?probe=50d37d9cf7) | May 01, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [cc016ce0c5](https://linux-hardware.org/?probe=cc016ce0c5) | May 01, 2022 |
| Lenovo        | B50-30 20382                | Notebook    | [1eb95bb123](https://linux-hardware.org/?probe=1eb95bb123) | May 01, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [a5fd51cc39](https://linux-hardware.org/?probe=a5fd51cc39) | May 01, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [fbbae98a18](https://linux-hardware.org/?probe=fbbae98a18) | May 01, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [36bd67db48](https://linux-hardware.org/?probe=36bd67db48) | May 01, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [f30bbca593](https://linux-hardware.org/?probe=f30bbca593) | May 01, 2022 |
| Dell          | Latitude E6420              | Notebook    | [8c12f58910](https://linux-hardware.org/?probe=8c12f58910) | May 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [f7b04a093f](https://linux-hardware.org/?probe=f7b04a093f) | May 01, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [adc0bdd7f8](https://linux-hardware.org/?probe=adc0bdd7f8) | May 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [39c9900546](https://linux-hardware.org/?probe=39c9900546) | May 01, 2022 |
| ASUSTek       | PU551LA                     | Notebook    | [19e1b6041b](https://linux-hardware.org/?probe=19e1b6041b) | May 01, 2022 |
| Positivo      | POS-ECIG41BSA               | Desktop     | [b622f7f43f](https://linux-hardware.org/?probe=b622f7f43f) | Apr 30, 2022 |
| Medion        | MS-7616                     | Desktop     | [f3572ea9a5](https://linux-hardware.org/?probe=f3572ea9a5) | Apr 30, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [94272db5ec](https://linux-hardware.org/?probe=94272db5ec) | Apr 30, 2022 |
| Alienware     | x17 R2                      | Notebook    | [d78db966bc](https://linux-hardware.org/?probe=d78db966bc) | Apr 30, 2022 |
| Dell          | Vostro 1720                 | Notebook    | [bc8f50b9fb](https://linux-hardware.org/?probe=bc8f50b9fb) | Apr 30, 2022 |
| Dell          | Vostro 1720                 | Notebook    | [56cc7a9a54](https://linux-hardware.org/?probe=56cc7a9a54) | Apr 30, 2022 |
| Gigabyte      | H61M-DS2 x.x                | Desktop     | [463e99eb8c](https://linux-hardware.org/?probe=463e99eb8c) | Apr 30, 2022 |
| Lenovo        | 81VS                        | Notebook    | [1ff46f7cdc](https://linux-hardware.org/?probe=1ff46f7cdc) | Apr 30, 2022 |
| Lenovo        | 81VS                        | Notebook    | [ea23b0e852](https://linux-hardware.org/?probe=ea23b0e852) | Apr 30, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [ff568c874c](https://linux-hardware.org/?probe=ff568c874c) | Apr 30, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [f140b54261](https://linux-hardware.org/?probe=f140b54261) | Apr 30, 2022 |
| Dell          | System XPS L502X            | Notebook    | [77e1846d8d](https://linux-hardware.org/?probe=77e1846d8d) | Apr 30, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [f5d70fb9d3](https://linux-hardware.org/?probe=f5d70fb9d3) | Apr 30, 2022 |
| Itautec       | Infoway w7535               | Notebook    | [ac87d9e508](https://linux-hardware.org/?probe=ac87d9e508) | Apr 30, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d7913302d5](https://linux-hardware.org/?probe=d7913302d5) | Apr 30, 2022 |
| Dell          | G7 7700                     | Notebook    | [462862ed56](https://linux-hardware.org/?probe=462862ed56) | Apr 30, 2022 |
| Toshiba       | Dakar10FW8                  | Notebook    | [fbe2aaac31](https://linux-hardware.org/?probe=fbe2aaac31) | Apr 30, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [b6cbc6e523](https://linux-hardware.org/?probe=b6cbc6e523) | Apr 30, 2022 |
| NSX           | SB1402                      | Notebook    | [c9d79a4fe5](https://linux-hardware.org/?probe=c9d79a4fe5) | Apr 30, 2022 |
| ASUSTek       | X550VC                      | Notebook    | [16223d208e](https://linux-hardware.org/?probe=16223d208e) | Apr 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [a7fe3cb0f6](https://linux-hardware.org/?probe=a7fe3cb0f6) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [f62d8963d7](https://linux-hardware.org/?probe=f62d8963d7) | Apr 30, 2022 |
| Lenovo        | G40-70 80GA                 | Notebook    | [fcd20cb250](https://linux-hardware.org/?probe=fcd20cb250) | Apr 30, 2022 |
| HP            | ProBook 4520s               | Notebook    | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| ASRock        | B75M-ITX                    | Desktop     | [dbc851e0d3](https://linux-hardware.org/?probe=dbc851e0d3) | Apr 30, 2022 |
| Dell          | Latitude 9420               | Notebook    | [4ba28afe84](https://linux-hardware.org/?probe=4ba28afe84) | Apr 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [1abef3591b](https://linux-hardware.org/?probe=1abef3591b) | Apr 30, 2022 |
| HP            | 3396                        | Desktop     | [468c2975ee](https://linux-hardware.org/?probe=468c2975ee) | Apr 30, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [51625474b7](https://linux-hardware.org/?probe=51625474b7) | Apr 30, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | Desktop     | [2f215a330a](https://linux-hardware.org/?probe=2f215a330a) | Apr 30, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [0b23621ed1](https://linux-hardware.org/?probe=0b23621ed1) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [865091bbc1](https://linux-hardware.org/?probe=865091bbc1) | Apr 30, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [5ee29c3982](https://linux-hardware.org/?probe=5ee29c3982) | Apr 30, 2022 |
| HP            | Laptop 17-by3xxx            | Notebook    | [087399e252](https://linux-hardware.org/?probe=087399e252) | Apr 30, 2022 |
| MSI           | A88XM-E45 V2                | Desktop     | [a50ad068b1](https://linux-hardware.org/?probe=a50ad068b1) | Apr 30, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7797c23169](https://linux-hardware.org/?probe=7797c23169) | Apr 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [55e76f131d](https://linux-hardware.org/?probe=55e76f131d) | Apr 30, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [f639c7c8f5](https://linux-hardware.org/?probe=f639c7c8f5) | Apr 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [58dfeebbb5](https://linux-hardware.org/?probe=58dfeebbb5) | Apr 29, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [aac5097e2a](https://linux-hardware.org/?probe=aac5097e2a) | Apr 29, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | Notebook    | [96dbfb494e](https://linux-hardware.org/?probe=96dbfb494e) | Apr 29, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [d1e0096b2d](https://linux-hardware.org/?probe=d1e0096b2d) | Apr 29, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [655905bb3b](https://linux-hardware.org/?probe=655905bb3b) | Apr 29, 2022 |
| HP            | EliteBook 8570w             | Notebook    | [e6f47edf47](https://linux-hardware.org/?probe=e6f47edf47) | Apr 29, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [fe522bdf2e](https://linux-hardware.org/?probe=fe522bdf2e) | Apr 29, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [62b044e6e7](https://linux-hardware.org/?probe=62b044e6e7) | Apr 29, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [6df44e9098](https://linux-hardware.org/?probe=6df44e9098) | Apr 29, 2022 |
| Lenovo        | ThinkPad T450 20BV001YMS    | Notebook    | [f38b762c83](https://linux-hardware.org/?probe=f38b762c83) | Apr 29, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [686f4acac4](https://linux-hardware.org/?probe=686f4acac4) | Apr 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [6affdcee0f](https://linux-hardware.org/?probe=6affdcee0f) | Apr 29, 2022 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [111d072676](https://linux-hardware.org/?probe=111d072676) | Apr 29, 2022 |
| Dell          | 07WP95 A02                  | Desktop     | [8dd4d42608](https://linux-hardware.org/?probe=8dd4d42608) | Apr 29, 2022 |
| Huanan        | X99-BD4 V/OPCZAO            | Desktop     | [a5743a1922](https://linux-hardware.org/?probe=a5743a1922) | Apr 29, 2022 |
| HP            | ENVY dv7                    | Notebook    | [dbd8feaee0](https://linux-hardware.org/?probe=dbd8feaee0) | Apr 29, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [e7ca44864b](https://linux-hardware.org/?probe=e7ca44864b) | Apr 29, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [0c0af6919d](https://linux-hardware.org/?probe=0c0af6919d) | Apr 29, 2022 |
| Pepper Job... | GLK-UC2X                    | Desktop     | [28495f32bd](https://linux-hardware.org/?probe=28495f32bd) | Apr 29, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [b989838f70](https://linux-hardware.org/?probe=b989838f70) | Apr 29, 2022 |
| Teclast       | F7 Plus                     | Notebook    | [8096cf3295](https://linux-hardware.org/?probe=8096cf3295) | Apr 29, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [27df4d83ea](https://linux-hardware.org/?probe=27df4d83ea) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [519ed87066](https://linux-hardware.org/?probe=519ed87066) | Apr 29, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [c46a1d595b](https://linux-hardware.org/?probe=c46a1d595b) | Apr 29, 2022 |
| MSI           | A78M-E35                    | Desktop     | [8f9bf75a08](https://linux-hardware.org/?probe=8f9bf75a08) | Apr 29, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [411c79850c](https://linux-hardware.org/?probe=411c79850c) | Apr 29, 2022 |
| ASUSTek       | Z87-WS                      | Desktop     | [1c67952875](https://linux-hardware.org/?probe=1c67952875) | Apr 29, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [d291472a69](https://linux-hardware.org/?probe=d291472a69) | Apr 28, 2022 |
| Acer          | Aspire A515-54              | Notebook    | [4ff968ef61](https://linux-hardware.org/?probe=4ff968ef61) | Apr 28, 2022 |
| Dell          | Precision 7510              | Notebook    | [afaea67857](https://linux-hardware.org/?probe=afaea67857) | Apr 28, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [8e5289a5e7](https://linux-hardware.org/?probe=8e5289a5e7) | Apr 28, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [1f6bbce46b](https://linux-hardware.org/?probe=1f6bbce46b) | Apr 28, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [92f92ef4ee](https://linux-hardware.org/?probe=92f92ef4ee) | Apr 28, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [5c90931c74](https://linux-hardware.org/?probe=5c90931c74) | Apr 28, 2022 |
| LG Electro... | 16T90P-G.AA78G              | Convertible | [42a891a892](https://linux-hardware.org/?probe=42a891a892) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [773f69d63b](https://linux-hardware.org/?probe=773f69d63b) | Apr 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [06ef070e40](https://linux-hardware.org/?probe=06ef070e40) | Apr 28, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [8ef803f8c9](https://linux-hardware.org/?probe=8ef803f8c9) | Apr 28, 2022 |
| Dell          | Latitude 5420               | Notebook    | [26abde11eb](https://linux-hardware.org/?probe=26abde11eb) | Apr 28, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [96739891ab](https://linux-hardware.org/?probe=96739891ab) | Apr 28, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [919872f97b](https://linux-hardware.org/?probe=919872f97b) | Apr 28, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [703a704f72](https://linux-hardware.org/?probe=703a704f72) | Apr 28, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [3e88e21f3c](https://linux-hardware.org/?probe=3e88e21f3c) | Apr 28, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [2943b21899](https://linux-hardware.org/?probe=2943b21899) | Apr 28, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [c4f91167bb](https://linux-hardware.org/?probe=c4f91167bb) | Apr 27, 2022 |
| Toshiba       | Satellite Pro S500          | Notebook    | [eb4ae51e74](https://linux-hardware.org/?probe=eb4ae51e74) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | Notebook    | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [820098c075](https://linux-hardware.org/?probe=820098c075) | Apr 27, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c7da3d4c4f](https://linux-hardware.org/?probe=c7da3d4c4f) | Apr 27, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b923126955](https://linux-hardware.org/?probe=b923126955) | Apr 27, 2022 |
| Dell          | Inspiron N4010              | Notebook    | [4d84b677ae](https://linux-hardware.org/?probe=4d84b677ae) | Apr 27, 2022 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [4c6852d631](https://linux-hardware.org/?probe=4c6852d631) | Apr 27, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [f06ce3d416](https://linux-hardware.org/?probe=f06ce3d416) | Apr 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f369da2680](https://linux-hardware.org/?probe=f369da2680) | Apr 27, 2022 |
| Dell          | Latitude E6510              | Notebook    | [10d60e00c2](https://linux-hardware.org/?probe=10d60e00c2) | Apr 27, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6e793edd01](https://linux-hardware.org/?probe=6e793edd01) | Apr 27, 2022 |
| Dell          | Inspiron 5415               | Notebook    | [5edac5d5a6](https://linux-hardware.org/?probe=5edac5d5a6) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [a3f49d1a04](https://linux-hardware.org/?probe=a3f49d1a04) | Apr 27, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b47f678ce9](https://linux-hardware.org/?probe=b47f678ce9) | Apr 27, 2022 |
| ASRock        | H61M-VG4                    | Desktop     | [fff58f97e8](https://linux-hardware.org/?probe=fff58f97e8) | Apr 27, 2022 |
| Dell          | Latitude E6520              | Notebook    | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [3c53a0e59d](https://linux-hardware.org/?probe=3c53a0e59d) | Apr 27, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [f09766a481](https://linux-hardware.org/?probe=f09766a481) | Apr 27, 2022 |
| Noblex        | N14WD21                     | Notebook    | [a8a7a4e1d5](https://linux-hardware.org/?probe=a8a7a4e1d5) | Apr 27, 2022 |
| Lenovo        | ThinkPad X250 20CLS52P0F    | Notebook    | [a4d291ccda](https://linux-hardware.org/?probe=a4d291ccda) | Apr 27, 2022 |
| HP            | 22F8                        | Desktop     | [eb4d49a17b](https://linux-hardware.org/?probe=eb4d49a17b) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [56da721176](https://linux-hardware.org/?probe=56da721176) | Apr 27, 2022 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [1619af58d4](https://linux-hardware.org/?probe=1619af58d4) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [a696a35961](https://linux-hardware.org/?probe=a696a35961) | Apr 27, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [87cc990d93](https://linux-hardware.org/?probe=87cc990d93) | Apr 27, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [3a96bf8237](https://linux-hardware.org/?probe=3a96bf8237) | Apr 27, 2022 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [e408254cc8](https://linux-hardware.org/?probe=e408254cc8) | Apr 27, 2022 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [3c6aace75c](https://linux-hardware.org/?probe=3c6aace75c) | Apr 27, 2022 |
| MSI           | 880GMA-E35                  | Desktop     | [6ff68166f7](https://linux-hardware.org/?probe=6ff68166f7) | Apr 26, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [31bc958302](https://linux-hardware.org/?probe=31bc958302) | Apr 26, 2022 |
| Lenovo        | ThinkPad T430u 335337G      | Notebook    | [8446691cb3](https://linux-hardware.org/?probe=8446691cb3) | Apr 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [3b4a331875](https://linux-hardware.org/?probe=3b4a331875) | Apr 26, 2022 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [b55ed2fbd6](https://linux-hardware.org/?probe=b55ed2fbd6) | Apr 26, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [bca722d45d](https://linux-hardware.org/?probe=bca722d45d) | Apr 26, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [50c760fc94](https://linux-hardware.org/?probe=50c760fc94) | Apr 26, 2022 |
| Dell          | 0WR7PY A03                  | Desktop     | [4ac0a4dff1](https://linux-hardware.org/?probe=4ac0a4dff1) | Apr 26, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [17ccf19b71](https://linux-hardware.org/?probe=17ccf19b71) | Apr 26, 2022 |
| Lenovo        | ThinkPad L490 20Q5002GPG    | Notebook    | [9e591226b7](https://linux-hardware.org/?probe=9e591226b7) | Apr 26, 2022 |
| Dell          | 0VNM11 A00                  | Desktop     | [6aae7c23ad](https://linux-hardware.org/?probe=6aae7c23ad) | Apr 26, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [e06fd46729](https://linux-hardware.org/?probe=e06fd46729) | Apr 26, 2022 |
| Biostar       | J3160NH                     | Desktop     | [8ffd3a1aa4](https://linux-hardware.org/?probe=8ffd3a1aa4) | Apr 26, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [bd827295e5](https://linux-hardware.org/?probe=bd827295e5) | Apr 26, 2022 |
| Dell          | G15 5510                    | Notebook    | [5126d58147](https://linux-hardware.org/?probe=5126d58147) | Apr 26, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [ff35a6956d](https://linux-hardware.org/?probe=ff35a6956d) | Apr 25, 2022 |
| MSI           | Z68A-GD80                   | Desktop     | [fedca9082a](https://linux-hardware.org/?probe=fedca9082a) | Apr 25, 2022 |
| Dell          | G15 5510                    | Notebook    | [ef1787abc5](https://linux-hardware.org/?probe=ef1787abc5) | Apr 25, 2022 |
| Lenovo        | ThinkPad X230 2324GA7       | Notebook    | [a5138b511d](https://linux-hardware.org/?probe=a5138b511d) | Apr 25, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [9e7c80a9d0](https://linux-hardware.org/?probe=9e7c80a9d0) | Apr 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | Notebook    | [3fcb247b21](https://linux-hardware.org/?probe=3fcb247b21) | Apr 25, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [07ccc93cd4](https://linux-hardware.org/?probe=07ccc93cd4) | Apr 25, 2022 |
| MSI           | GF65 Thin 10UE              | Notebook    | [b099b2ab43](https://linux-hardware.org/?probe=b099b2ab43) | Apr 25, 2022 |
| MSI           | GF65 Thin 10UE              | Notebook    | [79fc46c6f0](https://linux-hardware.org/?probe=79fc46c6f0) | Apr 25, 2022 |
| HP            | ProBook 4520s               | Notebook    | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [1b1bf8dddf](https://linux-hardware.org/?probe=1b1bf8dddf) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [4c3bf947f5](https://linux-hardware.org/?probe=4c3bf947f5) | Apr 25, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [17f9b4e988](https://linux-hardware.org/?probe=17f9b4e988) | Apr 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fe067fc3d4](https://linux-hardware.org/?probe=fe067fc3d4) | Apr 25, 2022 |
| ASUSTek       | H81M-V3                     | Desktop     | [4d87f6f113](https://linux-hardware.org/?probe=4d87f6f113) | Apr 25, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [fb26f3ab65](https://linux-hardware.org/?probe=fb26f3ab65) | Apr 25, 2022 |
| AMI           | Intel                       | Notebook    | [87e32073a4](https://linux-hardware.org/?probe=87e32073a4) | Apr 24, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [5f9ffc8d46](https://linux-hardware.org/?probe=5f9ffc8d46) | Apr 24, 2022 |
| Sony          | VPCEH25FM                   | Notebook    | [bceedddb01](https://linux-hardware.org/?probe=bceedddb01) | Apr 24, 2022 |
| Acer          | Aspire A515-56G             | Notebook    | [492dd679be](https://linux-hardware.org/?probe=492dd679be) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [6564561a75](https://linux-hardware.org/?probe=6564561a75) | Apr 24, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [54aa68a653](https://linux-hardware.org/?probe=54aa68a653) | Apr 24, 2022 |
| Acer          | Aspire A515-56G             | Notebook    | [5fc4dbeaad](https://linux-hardware.org/?probe=5fc4dbeaad) | Apr 24, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [96b772b4e6](https://linux-hardware.org/?probe=96b772b4e6) | Apr 24, 2022 |
| Acer          | FX58M                       | Desktop     | [3074ddb372](https://linux-hardware.org/?probe=3074ddb372) | Apr 24, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [4f77777c97](https://linux-hardware.org/?probe=4f77777c97) | Apr 24, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [52259207bb](https://linux-hardware.org/?probe=52259207bb) | Apr 24, 2022 |
| HP            | 255 G6 Notebook PC          | Notebook    | [ad390bd7b7](https://linux-hardware.org/?probe=ad390bd7b7) | Apr 24, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [3fff5f40c3](https://linux-hardware.org/?probe=3fff5f40c3) | Apr 24, 2022 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [090b87ad9b](https://linux-hardware.org/?probe=090b87ad9b) | Apr 24, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [af6b49b2a5](https://linux-hardware.org/?probe=af6b49b2a5) | Apr 24, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [30bac0dca3](https://linux-hardware.org/?probe=30bac0dca3) | Apr 24, 2022 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0e448efcb](https://linux-hardware.org/?probe=e0e448efcb) | Apr 24, 2022 |
| HP            | ENVY x360 Convertible       | Convertible | [34ac6fff67](https://linux-hardware.org/?probe=34ac6fff67) | Apr 24, 2022 |
| Avell High... | C65 MOB                     | Notebook    | [b8e185c194](https://linux-hardware.org/?probe=b8e185c194) | Apr 24, 2022 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [e0298dd8f0](https://linux-hardware.org/?probe=e0298dd8f0) | Apr 24, 2022 |
| HP            | 21EF                        | Desktop     | [9e37979ea3](https://linux-hardware.org/?probe=9e37979ea3) | Apr 23, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d0a5573598](https://linux-hardware.org/?probe=d0a5573598) | Apr 23, 2022 |
| Medion        | E7220                       | Notebook    | [c2d7457304](https://linux-hardware.org/?probe=c2d7457304) | Apr 23, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [929f99800a](https://linux-hardware.org/?probe=929f99800a) | Apr 23, 2022 |
| Dell          | Latitude 5290               | Notebook    | [e373cb6fa1](https://linux-hardware.org/?probe=e373cb6fa1) | Apr 23, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [2da43c32a4](https://linux-hardware.org/?probe=2da43c32a4) | Apr 23, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [ab5986371d](https://linux-hardware.org/?probe=ab5986371d) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [3b01c4a4a5](https://linux-hardware.org/?probe=3b01c4a4a5) | Apr 23, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [47cbc95032](https://linux-hardware.org/?probe=47cbc95032) | Apr 23, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | Notebook    | [59a49b2d04](https://linux-hardware.org/?probe=59a49b2d04) | Apr 23, 2022 |
| MSI           | MS-1T11                     | Desktop     | [9c16a631ef](https://linux-hardware.org/?probe=9c16a631ef) | Apr 23, 2022 |
| MSI           | MS-1T11                     | Desktop     | [e263cd80f5](https://linux-hardware.org/?probe=e263cd80f5) | Apr 23, 2022 |
| ASUSTek       | K46CA                       | Notebook    | [e762eba391](https://linux-hardware.org/?probe=e762eba391) | Apr 23, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c46c916a16](https://linux-hardware.org/?probe=c46c916a16) | Apr 23, 2022 |
| HP            | 22F8                        | Desktop     | [67dc13d1ad](https://linux-hardware.org/?probe=67dc13d1ad) | Apr 23, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [8ff97fd246](https://linux-hardware.org/?probe=8ff97fd246) | Apr 23, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [30209dbcd1](https://linux-hardware.org/?probe=30209dbcd1) | Apr 23, 2022 |
| ASUSTek       | PRIME B560-PLUS             | Desktop     | [8e31efa5fa](https://linux-hardware.org/?probe=8e31efa5fa) | Apr 23, 2022 |
| Dell          | Latitude 5580               | Notebook    | [cbd7aaec4a](https://linux-hardware.org/?probe=cbd7aaec4a) | Apr 23, 2022 |
| Chuwi         | Unknown                     | Notebook    | [96105ecbb2](https://linux-hardware.org/?probe=96105ecbb2) | Apr 23, 2022 |
| Lenovo        | ThinkPad P50 20EQS64N1N     | Notebook    | [c3d792a237](https://linux-hardware.org/?probe=c3d792a237) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [0c1628930f](https://linux-hardware.org/?probe=0c1628930f) | Apr 22, 2022 |
| Dell          | 088DT1 A01                  | Desktop     | [9e72ff0940](https://linux-hardware.org/?probe=9e72ff0940) | Apr 22, 2022 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [32cb202a0e](https://linux-hardware.org/?probe=32cb202a0e) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [d35c4838f2](https://linux-hardware.org/?probe=d35c4838f2) | Apr 22, 2022 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [61e0546ed7](https://linux-hardware.org/?probe=61e0546ed7) | Apr 22, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6718ac3459](https://linux-hardware.org/?probe=6718ac3459) | Apr 22, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f3e50d22aa](https://linux-hardware.org/?probe=f3e50d22aa) | Apr 22, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [36b0510bae](https://linux-hardware.org/?probe=36b0510bae) | Apr 22, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [135c98b96d](https://linux-hardware.org/?probe=135c98b96d) | Apr 22, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [d90f38b2ad](https://linux-hardware.org/?probe=d90f38b2ad) | Apr 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [91fc5d74c6](https://linux-hardware.org/?probe=91fc5d74c6) | Apr 22, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [377315649e](https://linux-hardware.org/?probe=377315649e) | Apr 22, 2022 |
| ASRock        | Z370 Pro4-IB                | Desktop     | [c0c51e4d53](https://linux-hardware.org/?probe=c0c51e4d53) | Apr 22, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [cd1bc2095f](https://linux-hardware.org/?probe=cd1bc2095f) | Apr 22, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [f2680af572](https://linux-hardware.org/?probe=f2680af572) | Apr 22, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [8abbc8a322](https://linux-hardware.org/?probe=8abbc8a322) | Apr 22, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3320719d25](https://linux-hardware.org/?probe=3320719d25) | Apr 22, 2022 |
| MSI           | Stealth GS77 12UGS          | Notebook    | [33afc70a54](https://linux-hardware.org/?probe=33afc70a54) | Apr 22, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [6061f1cd1e](https://linux-hardware.org/?probe=6061f1cd1e) | Apr 22, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [b0dc5471af](https://linux-hardware.org/?probe=b0dc5471af) | Apr 22, 2022 |
| Dell          | 0HD5W2 A00                  | Desktop     | [ddfd89e9dc](https://linux-hardware.org/?probe=ddfd89e9dc) | Apr 22, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [35e11e3e60](https://linux-hardware.org/?probe=35e11e3e60) | Apr 22, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [6dac014a49](https://linux-hardware.org/?probe=6dac014a49) | Apr 22, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [a76e953825](https://linux-hardware.org/?probe=a76e953825) | Apr 22, 2022 |
| Lenovo        | IdeaPad 500S-13ISK 80Q2     | Notebook    | [4548a301f8](https://linux-hardware.org/?probe=4548a301f8) | Apr 22, 2022 |
| HUAWEI        | DRC-WXX                     | Tablet      | [d459a4ef7d](https://linux-hardware.org/?probe=d459a4ef7d) | Apr 22, 2022 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [8f132efef2](https://linux-hardware.org/?probe=8f132efef2) | Apr 21, 2022 |
| Acer          | Aspire 7530G                | Notebook    | [710b429d94](https://linux-hardware.org/?probe=710b429d94) | Apr 21, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [8ef18c7ea4](https://linux-hardware.org/?probe=8ef18c7ea4) | Apr 21, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [0f748e86d4](https://linux-hardware.org/?probe=0f748e86d4) | Apr 21, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [58a8282067](https://linux-hardware.org/?probe=58a8282067) | Apr 21, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [18578239d6](https://linux-hardware.org/?probe=18578239d6) | Apr 21, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [5266d4c66b](https://linux-hardware.org/?probe=5266d4c66b) | Apr 21, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [70d107a754](https://linux-hardware.org/?probe=70d107a754) | Apr 21, 2022 |
| HP            | 8054                        | Desktop     | [f9ec7b0896](https://linux-hardware.org/?probe=f9ec7b0896) | Apr 21, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b84eab559e](https://linux-hardware.org/?probe=b84eab559e) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [6d291b9c9c](https://linux-hardware.org/?probe=6d291b9c9c) | Apr 21, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [bf31ebdabe](https://linux-hardware.org/?probe=bf31ebdabe) | Apr 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [a3aa6e30b9](https://linux-hardware.org/?probe=a3aa6e30b9) | Apr 21, 2022 |
| ASUSTek       | X450LA                      | Notebook    | [997a83a67c](https://linux-hardware.org/?probe=997a83a67c) | Apr 20, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [a6bd59cad3](https://linux-hardware.org/?probe=a6bd59cad3) | Apr 20, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [a8af23856d](https://linux-hardware.org/?probe=a8af23856d) | Apr 20, 2022 |
| Intel         | W7650                       | Notebook    | [edb281c81e](https://linux-hardware.org/?probe=edb281c81e) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [d10be6941f](https://linux-hardware.org/?probe=d10be6941f) | Apr 20, 2022 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [a92dda8ded](https://linux-hardware.org/?probe=a92dda8ded) | Apr 20, 2022 |
| Dell          | Latitude 3410               | Notebook    | [d932874d9c](https://linux-hardware.org/?probe=d932874d9c) | Apr 19, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [350979cb0a](https://linux-hardware.org/?probe=350979cb0a) | Apr 19, 2022 |
| Lenovo        | B575e 36852EG               | Notebook    | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| ASUSTek       | G771JW                      | Notebook    | [9b04178e4d](https://linux-hardware.org/?probe=9b04178e4d) | Apr 18, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [a5584e7ec2](https://linux-hardware.org/?probe=a5584e7ec2) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | Notebook    | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [3faf048414](https://linux-hardware.org/?probe=3faf048414) | Apr 18, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [e693d05883](https://linux-hardware.org/?probe=e693d05883) | Apr 17, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a2b841241d](https://linux-hardware.org/?probe=a2b841241d) | Apr 17, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [a0325fabb2](https://linux-hardware.org/?probe=a0325fabb2) | Apr 17, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [d775ab24fe](https://linux-hardware.org/?probe=d775ab24fe) | Apr 17, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [800aefa57e](https://linux-hardware.org/?probe=800aefa57e) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [1ed579d3d1](https://linux-hardware.org/?probe=1ed579d3d1) | Apr 16, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [dae8a4db62](https://linux-hardware.org/?probe=dae8a4db62) | Apr 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| Google        | Phaser360                   | Notebook    | [ab97623a21](https://linux-hardware.org/?probe=ab97623a21) | Apr 16, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [90c143abed](https://linux-hardware.org/?probe=90c143abed) | Apr 16, 2022 |
| Timi          | A34                         | Notebook    | [ff24fc7e19](https://linux-hardware.org/?probe=ff24fc7e19) | Apr 15, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [b95a9bcbf0](https://linux-hardware.org/?probe=b95a9bcbf0) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [3e2989ae49](https://linux-hardware.org/?probe=3e2989ae49) | Apr 15, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [cf9feaf8ec](https://linux-hardware.org/?probe=cf9feaf8ec) | Apr 15, 2022 |
| Sony          | VGN-NS38E_S                 | Notebook    | [1b8177c97a](https://linux-hardware.org/?probe=1b8177c97a) | Apr 14, 2022 |
| Lenovo        | Legion R7000 2020 82B6      | Notebook    | [260c012f44](https://linux-hardware.org/?probe=260c012f44) | Apr 14, 2022 |
| System76      | Serval WS                   | Notebook    | [f02bcd64a2](https://linux-hardware.org/?probe=f02bcd64a2) | Apr 14, 2022 |
| Gigabyte      | B75M-D3P                    | Desktop     | [cfb6502298](https://linux-hardware.org/?probe=cfb6502298) | Apr 14, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [bacc580e7a](https://linux-hardware.org/?probe=bacc580e7a) | Apr 13, 2022 |
| PC Special... | PCx0Dx                      | Notebook    | [6b0f05bf07](https://linux-hardware.org/?probe=6b0f05bf07) | Apr 13, 2022 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | Notebook    | [a31cc5eb3b](https://linux-hardware.org/?probe=a31cc5eb3b) | Apr 13, 2022 |
| Multilaser    | M11W                        | Notebook    | [4be432c77a](https://linux-hardware.org/?probe=4be432c77a) | Apr 13, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [fecdd237a4](https://linux-hardware.org/?probe=fecdd237a4) | Apr 11, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [1d1ff81694](https://linux-hardware.org/?probe=1d1ff81694) | Apr 11, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [e4ea2782f9](https://linux-hardware.org/?probe=e4ea2782f9) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [f394924315](https://linux-hardware.org/?probe=f394924315) | Apr 10, 2022 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [9edb3bbc43](https://linux-hardware.org/?probe=9edb3bbc43) | Apr 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [ce0316a106](https://linux-hardware.org/?probe=ce0316a106) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [1009093226](https://linux-hardware.org/?probe=1009093226) | Apr 10, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [0def0def83](https://linux-hardware.org/?probe=0def0def83) | Apr 09, 2022 |
| HP            | 840 G6                      | Notebook    | [7f8b25d480](https://linux-hardware.org/?probe=7f8b25d480) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [9a4f7c7381](https://linux-hardware.org/?probe=9a4f7c7381) | Apr 09, 2022 |
| Toshiba       | Satellite L50-A             | Notebook    | [ce1ec01972](https://linux-hardware.org/?probe=ce1ec01972) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [62c84ef4b4](https://linux-hardware.org/?probe=62c84ef4b4) | Apr 09, 2022 |
| Lenovo        | 3098 SDK0E50510 WIN 2625... | Desktop     | [07bde861ad](https://linux-hardware.org/?probe=07bde861ad) | Apr 09, 2022 |
| Supermicro    | H12SSL-i                    | Server      | [7bdae699e5](https://linux-hardware.org/?probe=7bdae699e5) | Apr 09, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [2240b6c593](https://linux-hardware.org/?probe=2240b6c593) | Apr 09, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [1f799cdbef](https://linux-hardware.org/?probe=1f799cdbef) | Apr 09, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8a07adc0f8](https://linux-hardware.org/?probe=8a07adc0f8) | Apr 09, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [470a09fc31](https://linux-hardware.org/?probe=470a09fc31) | Apr 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [f242f094a9](https://linux-hardware.org/?probe=f242f094a9) | Apr 09, 2022 |
| Unknown       | HX90                        | Desktop     | [913b92a244](https://linux-hardware.org/?probe=913b92a244) | Apr 08, 2022 |
| HP            | 1495                        | Desktop     | [36ea4763de](https://linux-hardware.org/?probe=36ea4763de) | Apr 08, 2022 |
| Unknown       | Unknown                     | Soc         | [99029e9661](https://linux-hardware.org/?probe=99029e9661) | Apr 08, 2022 |
| Maxtang       | FP30 V1.0                   | Desktop     | [2062d8578e](https://linux-hardware.org/?probe=2062d8578e) | Apr 08, 2022 |
| Supermicro    | H12SSL-i                    | Server      | [4f88fe663e](https://linux-hardware.org/?probe=4f88fe663e) | Apr 08, 2022 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | Notebook    | [ae77218dcf](https://linux-hardware.org/?probe=ae77218dcf) | Apr 07, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [8ab4c1618d](https://linux-hardware.org/?probe=8ab4c1618d) | Apr 07, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [fa9314716d](https://linux-hardware.org/?probe=fa9314716d) | Apr 07, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [322440c462](https://linux-hardware.org/?probe=322440c462) | Apr 06, 2022 |
| HP            | 840 G6                      | Notebook    | [76665316f7](https://linux-hardware.org/?probe=76665316f7) | Apr 06, 2022 |
| Dell          | G5 5590                     | Notebook    | [86d53d1c79](https://linux-hardware.org/?probe=86d53d1c79) | Apr 06, 2022 |
| Framework     | Laptop                      | Notebook    | [59a51973bb](https://linux-hardware.org/?probe=59a51973bb) | Apr 05, 2022 |
| Medion        | E15303                      | Notebook    | [21bdec99bb](https://linux-hardware.org/?probe=21bdec99bb) | Apr 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d2f9498bd2](https://linux-hardware.org/?probe=d2f9498bd2) | Apr 05, 2022 |
| Acer          | Aspire XC-603               | Desktop     | [ef344607ad](https://linux-hardware.org/?probe=ef344607ad) | Apr 04, 2022 |
| Packard Be... | IMEDIA S2110A               | Desktop     | [b8bf871708](https://linux-hardware.org/?probe=b8bf871708) | Apr 04, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [b7c7776f50](https://linux-hardware.org/?probe=b7c7776f50) | Apr 04, 2022 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [d9cbb34331](https://linux-hardware.org/?probe=d9cbb34331) | Apr 04, 2022 |
| Lenovo        | ThinkPad E495 20NEA00QUS    | Notebook    | [062e604ef0](https://linux-hardware.org/?probe=062e604ef0) | Apr 04, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [7da8a936ea](https://linux-hardware.org/?probe=7da8a936ea) | Apr 04, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [99a152f9c7](https://linux-hardware.org/?probe=99a152f9c7) | Apr 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | Notebook    | [43ff476479](https://linux-hardware.org/?probe=43ff476479) | Apr 03, 2022 |
| Samsung       | R580/R590                   | Notebook    | [0b95325a5e](https://linux-hardware.org/?probe=0b95325a5e) | Apr 03, 2022 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [a052a5e936](https://linux-hardware.org/?probe=a052a5e936) | Apr 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [bdb683ff40](https://linux-hardware.org/?probe=bdb683ff40) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [ec51dcaf0a](https://linux-hardware.org/?probe=ec51dcaf0a) | Apr 03, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [ad5d38e378](https://linux-hardware.org/?probe=ad5d38e378) | Apr 02, 2022 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [d103b2cb25](https://linux-hardware.org/?probe=d103b2cb25) | Apr 02, 2022 |
| MSI           | MAG B660M MORTAR DDR4       | Desktop     | [a9f2820894](https://linux-hardware.org/?probe=a9f2820894) | Apr 02, 2022 |
| Dell          | 07PR60 A00                  | Desktop     | [40f34fbc8f](https://linux-hardware.org/?probe=40f34fbc8f) | Apr 01, 2022 |
| Intel         | S2600CP G50768-505          | Server      | [cdfba65630](https://linux-hardware.org/?probe=cdfba65630) | Apr 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a799c6c916](https://linux-hardware.org/?probe=a799c6c916) | Apr 01, 2022 |
| TrekStor      | Primetab S11B               | Tablet      | [c98cdfd7c7](https://linux-hardware.org/?probe=c98cdfd7c7) | Apr 01, 2022 |
| Fujitsu       | D3223-C1 S26361-D3223-C1    | Desktop     | [f0fdc95810](https://linux-hardware.org/?probe=f0fdc95810) | Apr 01, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [9e1e2b2ae7](https://linux-hardware.org/?probe=9e1e2b2ae7) | Apr 01, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [6b0cd44dbb](https://linux-hardware.org/?probe=6b0cd44dbb) | Apr 01, 2022 |
| Alienware     | M11x                        | Notebook    | [f83c01bb34](https://linux-hardware.org/?probe=f83c01bb34) | Apr 01, 2022 |
| Avell High... | A70 MOB                     | Notebook    | [9e095642f0](https://linux-hardware.org/?probe=9e095642f0) | Apr 01, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [a14dde61dc](https://linux-hardware.org/?probe=a14dde61dc) | Apr 01, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [ce2e9f743d](https://linux-hardware.org/?probe=ce2e9f743d) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ceee79344c](https://linux-hardware.org/?probe=ceee79344c) | Mar 31, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [4ccce61117](https://linux-hardware.org/?probe=4ccce61117) | Mar 30, 2022 |
| HP            | 250 G4                      | Notebook    | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Medion        | S4401 MD61533               | Convertible | [0017875c99](https://linux-hardware.org/?probe=0017875c99) | Mar 30, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [f21ef43d0f](https://linux-hardware.org/?probe=f21ef43d0f) | Mar 30, 2022 |
| MSI           | GP76 Leopard 11UG           | Notebook    | [93a6b587c2](https://linux-hardware.org/?probe=93a6b587c2) | Mar 29, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [30c09eec3b](https://linux-hardware.org/?probe=30c09eec3b) | Mar 28, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dbdd71e8b8](https://linux-hardware.org/?probe=dbdd71e8b8) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [ecf7b98552](https://linux-hardware.org/?probe=ecf7b98552) | Mar 28, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [e5b0f5c259](https://linux-hardware.org/?probe=e5b0f5c259) | Mar 27, 2022 |
| Le Cube 1     | Unknown                     | Desktop     | [a881cc0397](https://linux-hardware.org/?probe=a881cc0397) | Mar 26, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [64e505d8d7](https://linux-hardware.org/?probe=64e505d8d7) | Mar 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [4fb374e78b](https://linux-hardware.org/?probe=4fb374e78b) | Mar 25, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [f06216a521](https://linux-hardware.org/?probe=f06216a521) | Mar 24, 2022 |
| HP            | 1589                        | Desktop     | [8c1f30bb6f](https://linux-hardware.org/?probe=8c1f30bb6f) | Mar 23, 2022 |
| HP            | Pavilion x2 Detachable      | Notebook    | [a82a2739a8](https://linux-hardware.org/?probe=a82a2739a8) | Mar 22, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [b03762a80b](https://linux-hardware.org/?probe=b03762a80b) | Mar 22, 2022 |
| Framework     | Laptop                      | Notebook    | [b8fcafa943](https://linux-hardware.org/?probe=b8fcafa943) | Mar 20, 2022 |
| Lenovo        | Edge 15 80H1                | Notebook    | [bd2b981053](https://linux-hardware.org/?probe=bd2b981053) | Mar 14, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [3c0450f79e](https://linux-hardware.org/?probe=3c0450f79e) | Mar 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [1c22760a82](https://linux-hardware.org/?probe=1c22760a82) | Mar 12, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [264fcd47ff](https://linux-hardware.org/?probe=264fcd47ff) | Mar 12, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [91a4d09517](https://linux-hardware.org/?probe=91a4d09517) | Mar 12, 2022 |
| ASRock        | 970 Extreme3 R2.0           | Desktop     | [f417e6a6ef](https://linux-hardware.org/?probe=f417e6a6ef) | Mar 11, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [1804e5eb77](https://linux-hardware.org/?probe=1804e5eb77) | Mar 09, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [256dc440ec](https://linux-hardware.org/?probe=256dc440ec) | Mar 09, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8a87e0ca46](https://linux-hardware.org/?probe=8a87e0ca46) | Mar 07, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [9fd12bdd29](https://linux-hardware.org/?probe=9fd12bdd29) | Mar 06, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [915ca09de4](https://linux-hardware.org/?probe=915ca09de4) | Mar 05, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [1fb25ad2c3](https://linux-hardware.org/?probe=1fb25ad2c3) | Mar 05, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c7dfd52f76](https://linux-hardware.org/?probe=c7dfd52f76) | Mar 05, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [f86a14c16d](https://linux-hardware.org/?probe=f86a14c16d) | Mar 05, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [aa80ded615](https://linux-hardware.org/?probe=aa80ded615) | Mar 04, 2022 |
| ASUSTek       | M4A87TD/USB3                | Desktop     | [3e997c5618](https://linux-hardware.org/?probe=3e997c5618) | Mar 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [206f3a7c01](https://linux-hardware.org/?probe=206f3a7c01) | Mar 02, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [35ab38818d](https://linux-hardware.org/?probe=35ab38818d) | Feb 28, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [01dd9cefa7](https://linux-hardware.org/?probe=01dd9cefa7) | Feb 28, 2022 |
| HP            | Presario CQ42               | Notebook    | [de34294599](https://linux-hardware.org/?probe=de34294599) | Feb 27, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [18d37562a8](https://linux-hardware.org/?probe=18d37562a8) | Feb 26, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [d8af57f59a](https://linux-hardware.org/?probe=d8af57f59a) | Feb 26, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [7fe4a3390b](https://linux-hardware.org/?probe=7fe4a3390b) | Feb 25, 2022 |
| Timi          | TM1709                      | Notebook    | [16e699bea8](https://linux-hardware.org/?probe=16e699bea8) | Feb 25, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [076c8f6e01](https://linux-hardware.org/?probe=076c8f6e01) | Feb 23, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [85c09f63f0](https://linux-hardware.org/?probe=85c09f63f0) | Feb 23, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [90c43679f7](https://linux-hardware.org/?probe=90c43679f7) | Feb 23, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [52976ad94b](https://linux-hardware.org/?probe=52976ad94b) | Feb 23, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [973f8ebf5e](https://linux-hardware.org/?probe=973f8ebf5e) | Feb 17, 2022 |
| MSI           | Stealth GS66 12UHS          | Notebook    | [bb8ef51c23](https://linux-hardware.org/?probe=bb8ef51c23) | Feb 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | Notebook    | [da103e44c5](https://linux-hardware.org/?probe=da103e44c5) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [1055dc7082](https://linux-hardware.org/?probe=1055dc7082) | Feb 14, 2022 |
| HP            | 620                         | Notebook    | [bd89b469e4](https://linux-hardware.org/?probe=bd89b469e4) | Feb 14, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [20d30ebe0b](https://linux-hardware.org/?probe=20d30ebe0b) | Feb 13, 2022 |
| MSI           | X370 GAMING PRO CARBON A... | Desktop     | [fa5ed1f68b](https://linux-hardware.org/?probe=fa5ed1f68b) | Feb 13, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [e329340668](https://linux-hardware.org/?probe=e329340668) | Feb 11, 2022 |
| Dell          | 0YXT71 A03                  | Desktop     | [19227aa57d](https://linux-hardware.org/?probe=19227aa57d) | Feb 11, 2022 |
| HP            | 212B                        | Desktop     | [fab24340a5](https://linux-hardware.org/?probe=fab24340a5) | Feb 10, 2022 |
| HP            | Pavilion 15                 | Notebook    | [9246e37578](https://linux-hardware.org/?probe=9246e37578) | Feb 09, 2022 |
| ASUSTek       | K52Je                       | Notebook    | [e1010983cf](https://linux-hardware.org/?probe=e1010983cf) | Feb 09, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [878c4247cb](https://linux-hardware.org/?probe=878c4247cb) | Feb 09, 2022 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [735bc0f806](https://linux-hardware.org/?probe=735bc0f806) | Feb 04, 2022 |
| Dell          | Latitude 3330               | Notebook    | [c3b39f74b4](https://linux-hardware.org/?probe=c3b39f74b4) | Jan 31, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | Notebook    | [0a04b2d1b1](https://linux-hardware.org/?probe=0a04b2d1b1) | Jan 31, 2022 |
| HP            | 15                          | Notebook    | [81961b52a9](https://linux-hardware.org/?probe=81961b52a9) | Jan 29, 2022 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [f45dc3454a](https://linux-hardware.org/?probe=f45dc3454a) | Jan 25, 2022 |
| Unknown       | Unknown                     | Soc         | [f60622cca7](https://linux-hardware.org/?probe=f60622cca7) | Jan 23, 2022 |
| Unknown       | Unknown                     | Soc         | [fb25f8463c](https://linux-hardware.org/?probe=fb25f8463c) | Jan 23, 2022 |
| HP            | ProBook 445 G7              | Notebook    | [bceca55120](https://linux-hardware.org/?probe=bceca55120) | Jan 23, 2022 |
| ASUSTek       | P5P41T/USB3                 | Desktop     | [105593cece](https://linux-hardware.org/?probe=105593cece) | Jan 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [2de98fb4d8](https://linux-hardware.org/?probe=2de98fb4d8) | Jan 22, 2022 |
| HP            | ProBook 650 G5              | Notebook    | [111cb6822e](https://linux-hardware.org/?probe=111cb6822e) | Jan 21, 2022 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [e092fc4b26](https://linux-hardware.org/?probe=e092fc4b26) | Jan 20, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [245123d0a8](https://linux-hardware.org/?probe=245123d0a8) | Jan 20, 2022 |
| Gigabyte      | GB-BSi7-1165G7              | Desktop     | [ab94ff1199](https://linux-hardware.org/?probe=ab94ff1199) | Jan 20, 2022 |
| Dell          | Latitude E6510              | Notebook    | [c0d3a6c31a](https://linux-hardware.org/?probe=c0d3a6c31a) | Jan 16, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [b2655bbd43](https://linux-hardware.org/?probe=b2655bbd43) | Jan 15, 2022 |
| Google        | Kefka                       | Notebook    | [e62fa3eea6](https://linux-hardware.org/?probe=e62fa3eea6) | Jan 10, 2022 |
| Timi          | RedmiBook Pro 15S           | Notebook    | [034079628f](https://linux-hardware.org/?probe=034079628f) | Jan 07, 2022 |
| Lenovo        | ThinkPad T400 2768WGB       | Notebook    | [ac0e3dfe29](https://linux-hardware.org/?probe=ac0e3dfe29) | Jan 07, 2022 |
| MSI           | C236A WORKSTATION           | Desktop     | [97795d3ebc](https://linux-hardware.org/?probe=97795d3ebc) | Jan 07, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [666b0b18f5](https://linux-hardware.org/?probe=666b0b18f5) | Dec 30, 2021 |
| Intel         | H61                         | Desktop     | [e2b49aa759](https://linux-hardware.org/?probe=e2b49aa759) | Dec 30, 2021 |
| MSI           | GT73VR 6RE                  | Notebook    | [0f41e5dd07](https://linux-hardware.org/?probe=0f41e5dd07) | Dec 28, 2021 |
| Lenovo        | Legion 7 16ACHg6 82N6       | Notebook    | [be79b3cd82](https://linux-hardware.org/?probe=be79b3cd82) | Dec 26, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ccc85b0783](https://linux-hardware.org/?probe=ccc85b0783) | Dec 13, 2021 |
| Lenovo        | 3141 NOK                    | Desktop     | [cc90d7c889](https://linux-hardware.org/?probe=cc90d7c889) | Dec 13, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0db33a5b23](https://linux-hardware.org/?probe=0db33a5b23) | Dec 10, 2021 |
| MSI           | Modern 15 A11MU             | Notebook    | [34b31c53cd](https://linux-hardware.org/?probe=34b31c53cd) | Dec 07, 2021 |
| Toshiba       | PORTEGE Z10T-A              | Notebook    | [5257d76a92](https://linux-hardware.org/?probe=5257d76a92) | Dec 05, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [f219ee63ff](https://linux-hardware.org/?probe=f219ee63ff) | Nov 30, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [3199d159a4](https://linux-hardware.org/?probe=3199d159a4) | Nov 30, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [dcd5217827](https://linux-hardware.org/?probe=dcd5217827) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | Desktop     | [16854f2502](https://linux-hardware.org/?probe=16854f2502) | Nov 29, 2021 |
| Gigabyte      | M52L-S3                     | Desktop     | [e6f3417028](https://linux-hardware.org/?probe=e6f3417028) | Nov 27, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d191e3f97f](https://linux-hardware.org/?probe=d191e3f97f) | Nov 22, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [6381b11078](https://linux-hardware.org/?probe=6381b11078) | Nov 22, 2021 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [c0134f6231](https://linux-hardware.org/?probe=c0134f6231) | Nov 11, 2021 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [4d659bf7e4](https://linux-hardware.org/?probe=4d659bf7e4) | Nov 11, 2021 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [36e64b8256](https://linux-hardware.org/?probe=36e64b8256) | Nov 10, 2021 |
| ASUSTek       | X58L                        | Notebook    | [c3df58b13b](https://linux-hardware.org/?probe=c3df58b13b) | Nov 10, 2021 |
| ASUSTek       | X58L                        | Notebook    | [e1425f037e](https://linux-hardware.org/?probe=e1425f037e) | Nov 10, 2021 |
| ASUSTek       | X58L                        | Notebook    | [f64ba3a9e4](https://linux-hardware.org/?probe=f64ba3a9e4) | Nov 10, 2021 |
| Dell          | Inspiron 1464               | Notebook    | [26f50eb4a8](https://linux-hardware.org/?probe=26f50eb4a8) | Nov 06, 2021 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [6b1a282c17](https://linux-hardware.org/?probe=6b1a282c17) | Nov 05, 2021 |
| Dell          | Inspiron 1464               | Notebook    | [4063779d5a](https://linux-hardware.org/?probe=4063779d5a) | Nov 01, 2021 |
| MSI           | MS-7235                     | Desktop     | [bbfa7fb897](https://linux-hardware.org/?probe=bbfa7fb897) | Oct 24, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.15.0-27-generic           | 300       | 30.71%  |
| 5.15.0-25-generic           | 170       | 17.4%   |
| 5.15.0-30-generic           | 152       | 15.56%  |
| 5.15.0-33-generic           | 124       | 12.69%  |
| 5.15.0-23-generic           | 36        | 3.68%   |
| 5.15.0-18-generic           | 25        | 2.56%   |
| 5.15.0-1006-raspi           | 15        | 1.54%   |
| 5.15.0-28-generic           | 12        | 1.23%   |
| 5.13.0-19-generic           | 12        | 1.23%   |
| 5.15.0-32-generic           | 11        | 1.13%   |
| 5.15.0-22-generic           | 9         | 0.92%   |
| 5.15.0-17-generic           | 8         | 0.82%   |
| 5.15.0-1005-raspi           | 8         | 0.82%   |
| 5.17.0-051700-generic       | 5         | 0.51%   |
| 5.15.0-35-generic           | 5         | 0.51%   |
| 5.17.2-051702-generic       | 4         | 0.41%   |
| 5.17.0-1003-oem             | 4         | 0.41%   |
| 5.18.0-051800-generic       | 3         | 0.31%   |
| 5.17.9-051709-generic       | 3         | 0.31%   |
| 5.17.8-051708-generic       | 3         | 0.31%   |
| 5.17.6-051706-generic       | 3         | 0.31%   |
| 5.17.5-051705-generic       | 3         | 0.31%   |
| 5.17.4-051704-generic       | 3         | 0.31%   |
| 5.18.0-051800rc1-generic    | 2         | 0.2%    |
| 5.17.1-051701-generic       | 2         | 0.2%    |
| 5.17.0-1004-oem             | 2         | 0.2%    |
| 5.16.0-051600-generic       | 2         | 0.2%    |
| 5.15.0-27-lowlatency        | 2         | 0.2%    |
| 5.4.0-faked                 | 1         | 0.1%    |
| 5.18.0-051800rc7-generic    | 1         | 0.1%    |
| 5.17.9-xanmod1-x64v2        | 1         | 0.1%    |
| 5.17.8-xanmod1              | 1         | 0.1%    |
| 5.17.7-surface              | 1         | 0.1%    |
| 5.17.7-051707-generic       | 1         | 0.1%    |
| 5.17.5-xanmod1              | 1         | 0.1%    |
| 5.17.5-surface              | 1         | 0.1%    |
| 5.17.0-void25-nomac-znver3  | 1         | 0.1%    |
| 5.17.0-tkg-cacule           | 1         | 0.1%    |
| 5.17.0-9.1-liquorix-amd64   | 1         | 0.1%    |
| 5.17.0-4.1-liquorix-amd64   | 1         | 0.1%    |
| 5.17.0-1006-oem             | 1         | 0.1%    |
| 5.17.0-051700rc7-generic    | 1         | 0.1%    |
| 5.17.0-051700rc6-generic    | 1         | 0.1%    |
| 5.17.0-051700rc5-lowlatency | 1         | 0.1%    |
| 5.16.2-051602-generic       | 1         | 0.1%    |
| 5.16.11-76051611-generic    | 1         | 0.1%    |
| 5.15.6-051506-generic       | 1         | 0.1%    |
| 5.15.39-051539-generic      | 1         | 0.1%    |
| 5.15.36-051536-generic      | 1         | 0.1%    |
| 5.15.17-xanmod2             | 1         | 0.1%    |
| 5.15.15-76051515-generic    | 1         | 0.1%    |
| 5.15.13-051513-generic      | 1         | 0.1%    |
| 5.15.12-051512-generic      | 1         | 0.1%    |
| 5.15.11-051511-generic      | 1         | 0.1%    |
| 5.15.10-051510-generic      | 1         | 0.1%    |
| 5.15.0-33-lowlatency        | 1         | 0.1%    |
| 5.15.0-322205121620-generic | 1         | 0.1%    |
| 5.15.0-30-lowlatency        | 1         | 0.1%    |
| 5.15.0-14-generic           | 1         | 0.1%    |
| 5.15.0-13-generic           | 1         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.0  | 866       | 90.78%  |
| 5.17.0  | 19        | 1.99%   |
| 5.13.0  | 17        | 1.78%   |
| 5.18.0  | 6         | 0.63%   |
| 5.17.5  | 5         | 0.52%   |
| 5.17.9  | 4         | 0.42%   |
| 5.17.8  | 4         | 0.42%   |
| 5.17.2  | 4         | 0.42%   |
| 5.17.6  | 3         | 0.31%   |
| 5.17.4  | 3         | 0.31%   |
| 5.14.0  | 3         | 0.31%   |
| 5.17.7  | 2         | 0.21%   |
| 5.17.1  | 2         | 0.21%   |
| 5.16.0  | 2         | 0.21%   |
| 5.4.0   | 1         | 0.1%    |
| 5.16.2  | 1         | 0.1%    |
| 5.16.11 | 1         | 0.1%    |
| 5.15.6  | 1         | 0.1%    |
| 5.15.39 | 1         | 0.1%    |
| 5.15.36 | 1         | 0.1%    |
| 5.15.17 | 1         | 0.1%    |
| 5.15.15 | 1         | 0.1%    |
| 5.15.13 | 1         | 0.1%    |
| 5.15.12 | 1         | 0.1%    |
| 5.15.11 | 1         | 0.1%    |
| 5.15.10 | 1         | 0.1%    |
| 5.13.19 | 1         | 0.1%    |
| 3.16.85 | 1         | 0.1%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 875       | 91.72%  |
| 5.17    | 46        | 4.82%   |
| 5.13    | 18        | 1.89%   |
| 5.18    | 6         | 0.63%   |
| 5.16    | 4         | 0.42%   |
| 5.14    | 3         | 0.31%   |
| 5.4     | 1         | 0.1%    |
| 3.16    | 1         | 0.1%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 926       | 97.27%  |
| aarch64 | 26        | 2.73%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 894       | 93.61%  |
| Unknown           | 33        | 3.46%   |
| X-Cinnamon        | 9         | 0.94%   |
| GNOME Flashback   | 7         | 0.73%   |
| Unity             | 5         | 0.52%   |
| i3                | 2         | 0.21%   |
| Yaru:ubuntu:GNOME | 1         | 0.1%    |
| GNUstep           | 1         | 0.1%    |
| GNOME Classic     | 1         | 0.1%    |
| Cinnamon          | 1         | 0.1%    |
| awesome           | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 593       | 61.71%  |
| X11     | 335       | 34.86%  |
| Unknown | 17        | 1.77%   |
| Tty     | 16        | 1.66%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM3    | 852       | 89.21%  |
| Unknown | 84        | 8.8%    |
| LightDM | 10        | 1.05%   |
| GDM     | 5         | 0.52%   |
| SDDM    | 3         | 0.31%   |
| XDM     | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 434       | 45.59%  |
| de_DE   | 78        | 8.19%   |
| en_GB   | 48        | 5.04%   |
| fr_FR   | 42        | 4.41%   |
| pt_BR   | 41        | 4.31%   |
| es_ES   | 33        | 3.47%   |
| en_CA   | 27        | 2.84%   |
| ru_RU   | 25        | 2.63%   |
| en_IN   | 25        | 2.63%   |
| it_IT   | 19        | 2%      |
| pl_PL   | 18        | 1.89%   |
| en_AU   | 14        | 1.47%   |
| zh_CN   | 12        | 1.26%   |
| cs_CZ   | 11        | 1.16%   |
| C       | 7         | 0.74%   |
| pt_PT   | 6         | 0.63%   |
| ja_JP   | 6         | 0.63%   |
| fi_FI   | 6         | 0.63%   |
| de_CH   | 6         | 0.63%   |
| tr_TR   | 5         | 0.53%   |
| hu_HU   | 5         | 0.53%   |
| es_AR   | 5         | 0.53%   |
| en_IL   | 5         | 0.53%   |
| da_DK   | 5         | 0.53%   |
| sv_SE   | 4         | 0.42%   |
| nl_NL   | 4         | 0.42%   |
| es_EC   | 4         | 0.42%   |
| Unknown | 4         | 0.42%   |
| zh_TW   | 3         | 0.32%   |
| nl_BE   | 3         | 0.32%   |
| es_PE   | 3         | 0.32%   |
| en_ZA   | 3         | 0.32%   |
| en_NZ   | 3         | 0.32%   |
| bg_BG   | 3         | 0.32%   |
| sk_SK   | 2         | 0.21%   |
| ro_RO   | 2         | 0.21%   |
| ko_KR   | 2         | 0.21%   |
| fr_BE   | 2         | 0.21%   |
| es_MX   | 2         | 0.21%   |
| es_CL   | 2         | 0.21%   |
| en_PH   | 2         | 0.21%   |
| en_HK   | 2         | 0.21%   |
| el_GR   | 2         | 0.21%   |
| de_AT   | 2         | 0.21%   |
| ca_ES   | 2         | 0.21%   |
| uk_UA   | 1         | 0.11%   |
| th_TH   | 1         | 0.11%   |
| sl_SI   | 1         | 0.11%   |
| ru_UA   | 1         | 0.11%   |
| nb_NO   | 1         | 0.11%   |
| hr_HR   | 1         | 0.11%   |
| fr_CH   | 1         | 0.11%   |
| eu_ES   | 1         | 0.11%   |
| es_CR   | 1         | 0.11%   |
| en_ZW   | 1         | 0.11%   |
| en_SG   | 1         | 0.11%   |
| de_IT   | 1         | 0.11%   |
| de_BE   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 586       | 61.04%  |
| EFI  | 374       | 38.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 873       | 91.41%  |
| Zfs     | 30        | 3.14%   |
| Overlay | 30        | 3.14%   |
| Btrfs   | 13        | 1.36%   |
| Xfs     | 8         | 0.84%   |
| Ext2    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 603       | 63.08%  |
| GPT     | 333       | 34.83%  |
| MBR     | 20        | 2.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 845       | 88.48%  |
| Yes       | 110       | 11.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 592       | 61.86%  |
| Yes       | 365       | 38.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 144       | 15.13%  |
| ASUSTek Computer               | 134       | 14.08%  |
| Hewlett-Packard                | 133       | 13.97%  |
| Dell                           | 119       | 12.5%   |
| MSI                            | 67        | 7.04%   |
| Gigabyte Technology            | 53        | 5.57%   |
| Acer                           | 51        | 5.36%   |
| Raspberry Pi Foundation        | 24        | 2.52%   |
| Toshiba                        | 19        | 2%      |
| Intel                          | 19        | 2%      |
| ASRock                         | 19        | 2%      |
| Apple                          | 16        | 1.68%   |
| HUAWEI                         | 11        | 1.16%   |
| Alienware                      | 11        | 1.16%   |
| Unknown                        | 10        | 1.05%   |
| Medion                         | 9         | 0.95%   |
| Samsung Electronics            | 8         | 0.84%   |
| Fujitsu                        | 6         | 0.63%   |
| Chuwi                          | 6         | 0.63%   |
| Sony                           | 5         | 0.53%   |
| Shuttle                        | 5         | 0.53%   |
| Microsoft                      | 5         | 0.53%   |
| Google                         | 5         | 0.53%   |
| Timi                           | 4         | 0.42%   |
| Pegatron                       | 4         | 0.42%   |
| LG Electronics                 | 4         | 0.42%   |
| Avell High Performance         | 4         | 0.42%   |
| AMI                            | 4         | 0.42%   |
| Supermicro                     | 3         | 0.32%   |
| Positivo                       | 3         | 0.32%   |
| Gateway                        | 3         | 0.32%   |
| Framework                      | 3         | 0.32%   |
| ECS                            | 3         | 0.32%   |
| TUXEDO                         | 2         | 0.21%   |
| Teclast                        | 2         | 0.21%   |
| PC Specialist                  | 2         | 0.21%   |
| Huanan                         | 2         | 0.21%   |
| Biostar                        | 2         | 0.21%   |
| Vestel                         | 1         | 0.11%   |
| TrekStor                       | 1         | 0.11%   |
| System76                       | 1         | 0.11%   |
| SLIMBOOK                       | 1         | 0.11%   |
| Shenzhen Wangang Technology    | 1         | 0.11%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.11%   |
| Pepper Jobs                    | 1         | 0.11%   |
| Panasonic                      | 1         | 0.11%   |
| Packard Bell                   | 1         | 0.11%   |
| Otazak                         | 1         | 0.11%   |
| NSX                            | 1         | 0.11%   |
| Noblex                         | 1         | 0.11%   |
| Multilaser                     | 1         | 0.11%   |
| mPTech                         | 1         | 0.11%   |
| Maxtang                        | 1         | 0.11%   |
| Maibenben                      | 1         | 0.11%   |
| Le Cube 1                      | 1         | 0.11%   |
| Itautec                        | 1         | 0.11%   |
| Inventec                       | 1         | 0.11%   |
| HONOR                          | 1         | 0.11%   |
| GPU Company                    | 1         | 0.11%   |
| Foxconn                        | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| RPi Raspberry Pi                                  | 17        | 1.79%   |
| Unknown                                           | 12        | 1.26%   |
| ASUS All Series                                   | 9         | 0.95%   |
| Dell OptiPlex 7010                                | 4         | 0.42%   |
| Alienware x17 R2                                  | 4         | 0.42%   |
| RPi Raspberry Pi 4 Model B Rev 1.4                | 3         | 0.32%   |
| MSI MS-7C52                                       | 3         | 0.32%   |
| MSI MS-7C37                                       | 3         | 0.32%   |
| Lenovo Yoga Duet 7 13ITL6 82MA                    | 3         | 0.32%   |
| Lenovo IdeaPad 5 14ITL05 82FE                     | 3         | 0.32%   |
| HP ZBook 15 G5                                    | 3         | 0.32%   |
| HP Pavilion g6                                    | 3         | 0.32%   |
| HP Notebook                                       | 3         | 0.32%   |
| HP 15                                             | 3         | 0.32%   |
| Framework Laptop                                  | 3         | 0.32%   |
| Dell Latitude E6510                               | 3         | 0.32%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM             | 3         | 0.32%   |
| ASUS N550JV                                       | 3         | 0.32%   |
| Acer Swift SF314-42                               | 3         | 0.32%   |
| RPi Raspberry Pi 4 Model B Rev 1.5                | 2         | 0.21%   |
| RPi Raspberry Pi 4 Model B Rev 1.2                | 2         | 0.21%   |
| MSI MS-7D54                                       | 2         | 0.21%   |
| MSI MS-7C95                                       | 2         | 0.21%   |
| MSI MS-7C92                                       | 2         | 0.21%   |
| MSI MS-7C91                                       | 2         | 0.21%   |
| MSI MS-7C02                                       | 2         | 0.21%   |
| MSI MS-7A38                                       | 2         | 0.21%   |
| MSI MS-7721                                       | 2         | 0.21%   |
| Lenovo Z50-75 80EC                                | 2         | 0.21%   |
| Lenovo Z50-70 20354                               | 2         | 0.21%   |
| Lenovo ThinkBook 14-IML 20RV                      | 2         | 0.21%   |
| Lenovo IdeaPadFlex 5 14ITL05 82HS                 | 2         | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81DE                     | 2         | 0.21%   |
| Intel H61                                         | 2         | 0.21%   |
| HUAWEI HVY-WXX9                                   | 2         | 0.21%   |
| HP ZBook Power 15.6 inch G8 Mobile Workstation PC | 2         | 0.21%   |
| HP ZBook 15 G6                                    | 2         | 0.21%   |
| HP ProLiant DL380p Gen8                           | 2         | 0.21%   |
| HP ProBook 650 G1                                 | 2         | 0.21%   |
| HP ProBook 470 G1                                 | 2         | 0.21%   |
| HP ProBook 450 G8 Notebook PC                     | 2         | 0.21%   |
| HP ProBook 430 G1                                 | 2         | 0.21%   |
| HP Laptop 15s-fq1xxx                              | 2         | 0.21%   |
| HP Laptop 15-dw3xxx                               | 2         | 0.21%   |
| HP Laptop 15-bs0xx                                | 2         | 0.21%   |
| HP EliteBook 850 G6                               | 2         | 0.21%   |
| HP EliteBook 840 G8 Notebook PC                   | 2         | 0.21%   |
| HP EliteBook 840 G3                               | 2         | 0.21%   |
| HP Compaq 8200 Elite SFF PC                       | 2         | 0.21%   |
| HP 255 G6 Notebook PC                             | 2         | 0.21%   |
| Gigabyte Z77X-UD3H                                | 2         | 0.21%   |
| Gigabyte X99-UD4-CF                               | 2         | 0.21%   |
| Gigabyte X570 AORUS MASTER                        | 2         | 0.21%   |
| Fujitsu PRIMERGY TX150 S7                         | 2         | 0.21%   |
| Fujitsu CELSIUS R570-2                            | 2         | 0.21%   |
| Dell XPS 15 9570                                  | 2         | 0.21%   |
| Dell XPS 15 7590                                  | 2         | 0.21%   |
| Dell Vostro 15 3515                               | 2         | 0.21%   |
| Dell Precision WorkStation 690                    | 2         | 0.21%   |
| Dell Precision 7510                               | 2         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 49        | 5.15%   |
| Dell Inspiron      | 37        | 3.89%   |
| Lenovo IdeaPad     | 30        | 3.15%   |
| Acer Aspire        | 29        | 3.05%   |
| HP Pavilion        | 25        | 2.63%   |
| RPi Raspberry      | 24        | 2.52%   |
| Dell Latitude      | 21        | 2.21%   |
| ASUS ROG           | 21        | 2.21%   |
| HP ProBook         | 18        | 1.89%   |
| Dell OptiPlex      | 17        | 1.79%   |
| HP Laptop          | 16        | 1.68%   |
| Toshiba Satellite  | 15        | 1.58%   |
| HP EliteBook       | 15        | 1.58%   |
| Dell Precision     | 14        | 1.47%   |
| ASUS VivoBook      | 14        | 1.47%   |
| Lenovo Yoga        | 12        | 1.26%   |
| Dell XPS           | 12        | 1.26%   |
| Unknown            | 12        | 1.26%   |
| ASUS PRIME         | 11        | 1.16%   |
| Lenovo ThinkBook   | 9         | 0.95%   |
| HP ZBook           | 9         | 0.95%   |
| HP ENVY            | 9         | 0.95%   |
| ASUS All           | 9         | 0.95%   |
| Acer Swift         | 9         | 0.95%   |
| Dell Vostro        | 8         | 0.84%   |
| Lenovo Legion      | 7         | 0.74%   |
| Lenovo IdeaPadFlex | 6         | 0.63%   |
| Microsoft Surface  | 5         | 0.53%   |
| HP Spectre         | 5         | 0.53%   |
| HP EliteDesk       | 5         | 0.53%   |
| ASUS Zenbook       | 5         | 0.53%   |
| ASUS ASUS          | 5         | 0.53%   |
| MSI Stealth        | 4         | 0.42%   |
| Lenovo ThinkCentre | 4         | 0.42%   |
| Gigabyte X570      | 4         | 0.42%   |
| ASUS TUF           | 4         | 0.42%   |
| Alienware x17      | 4         | 0.42%   |
| Acer TravelMate    | 4         | 0.42%   |
| Acer Nitro         | 4         | 0.42%   |
| MSI MS-7C52        | 3         | 0.32%   |
| MSI MS-7C37        | 3         | 0.32%   |
| HP ProLiant        | 3         | 0.32%   |
| HP Notebook        | 3         | 0.32%   |
| HP Compaq          | 3         | 0.32%   |
| HP 255             | 3         | 0.32%   |
| HP 250             | 3         | 0.32%   |
| HP 15              | 3         | 0.32%   |
| Framework Laptop   | 3         | 0.32%   |
| ASUS PRO           | 3         | 0.32%   |
| ASUS N550JV        | 3         | 0.32%   |
| ASUS CROSSHAIR     | 3         | 0.32%   |
| Toshiba PORTEGE    | 2         | 0.21%   |
| Timi RedmiBook     | 2         | 0.21%   |
| MSI Prestige       | 2         | 0.21%   |
| MSI MS-7D54        | 2         | 0.21%   |
| MSI MS-7C95        | 2         | 0.21%   |
| MSI MS-7C92        | 2         | 0.21%   |
| MSI MS-7C91        | 2         | 0.21%   |
| MSI MS-7C02        | 2         | 0.21%   |
| MSI MS-7A38        | 2         | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 145       | 15.23%  |
| 2020    | 135       | 14.18%  |
| 2019    | 92        | 9.66%   |
| 2018    | 80        | 8.4%    |
| 2012    | 59        | 6.2%    |
| 2014    | 58        | 6.09%   |
| 2013    | 55        | 5.78%   |
| 2011    | 48        | 5.04%   |
| 2017    | 47        | 4.94%   |
| 2010    | 47        | 4.94%   |
| 2016    | 43        | 4.52%   |
| 2015    | 37        | 3.89%   |
| 2022    | 31        | 3.26%   |
| Unknown | 26        | 2.73%   |
| 2008    | 21        | 2.21%   |
| 2009    | 19        | 2%      |
| 2007    | 4         | 0.42%   |
| 2006    | 4         | 0.42%   |
| 2005    | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 530       | 55.67%  |
| Desktop        | 301       | 31.62%  |
| Convertible    | 43        | 4.52%   |
| System on chip | 26        | 2.73%   |
| Mini pc        | 18        | 1.89%   |
| Tablet         | 12        | 1.26%   |
| All in one     | 11        | 1.16%   |
| Server         | 11        | 1.16%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 864       | 90.57%  |
| Enabled  | 90        | 9.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 947       | 99.47%  |
| Yes  | 5         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 256       | 26.86%  |
| 16.01-24.0      | 198       | 20.78%  |
| 8.01-16.0       | 177       | 18.57%  |
| 3.01-4.0        | 126       | 13.22%  |
| 32.01-64.0      | 112       | 11.75%  |
| 64.01-256.0     | 42        | 4.41%   |
| 24.01-32.0      | 19        | 1.99%   |
| 1.01-2.0        | 14        | 1.47%   |
| 2.01-3.0        | 7         | 0.73%   |
| More than 256.0 | 2         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 305       | 31.44%  |
| 2.01-3.0   | 277       | 28.56%  |
| 4.01-8.0   | 174       | 17.94%  |
| 3.01-4.0   | 149       | 15.36%  |
| 8.01-16.0  | 41        | 4.23%   |
| 0.51-1.0   | 9         | 0.93%   |
| 32.01-64.0 | 4         | 0.41%   |
| 16.01-24.0 | 4         | 0.41%   |
| 0.01-0.5   | 4         | 0.41%   |
| 24.01-32.0 | 3         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 581       | 60.65%  |
| 2      | 224       | 23.38%  |
| 3      | 61        | 6.37%   |
| 4      | 35        | 3.65%   |
| 5      | 18        | 1.88%   |
| 0      | 18        | 1.88%   |
| 6      | 7         | 0.73%   |
| 8      | 4         | 0.42%   |
| 7      | 4         | 0.42%   |
| 13     | 3         | 0.31%   |
| 20     | 1         | 0.1%    |
| 10     | 1         | 0.1%    |
| 9      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 651       | 68.31%  |
| Yes       | 302       | 31.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 752       | 78.91%  |
| No        | 201       | 21.09%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 742       | 77.86%  |
| No        | 211       | 22.14%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 641       | 67.12%  |
| No        | 314       | 32.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 174       | 18.28%  |
| Germany      | 96        | 10.08%  |
| Brazil       | 52        | 5.46%   |
| France       | 48        | 5.04%   |
| UK           | 44        | 4.62%   |
| Russia       | 33        | 3.47%   |
| Spain        | 32        | 3.36%   |
| Poland       | 32        | 3.36%   |
| Italy        | 32        | 3.36%   |
| India        | 28        | 2.94%   |
| Canada       | 28        | 2.94%   |
| Netherlands  | 22        | 2.31%   |
| Sweden       | 16        | 1.68%   |
| Czechia      | 16        | 1.68%   |
| Australia    | 16        | 1.68%   |
| Argentina    | 16        | 1.68%   |
| Finland      | 15        | 1.58%   |
| China        | 14        | 1.47%   |
| Turkey       | 13        | 1.37%   |
| Romania      | 13        | 1.37%   |
| Switzerland  | 11        | 1.16%   |
| Mexico       | 10        | 1.05%   |
| Japan        | 10        | 1.05%   |
| Belgium      | 10        | 1.05%   |
| Portugal     | 8         | 0.84%   |
| Denmark      | 8         | 0.84%   |
| Bulgaria     | 7         | 0.74%   |
| Taiwan       | 6         | 0.63%   |
| South Korea  | 6         | 0.63%   |
| Peru         | 6         | 0.63%   |
| Hungary      | 6         | 0.63%   |
| Austria      | 6         | 0.63%   |
| Norway       | 5         | 0.53%   |
| Israel       | 5         | 0.53%   |
| Ecuador      | 5         | 0.53%   |
| Ukraine      | 4         | 0.42%   |
| Thailand     | 4         | 0.42%   |
| Serbia       | 4         | 0.42%   |
| New Zealand  | 4         | 0.42%   |
| Indonesia    | 4         | 0.42%   |
| Vietnam      | 3         | 0.32%   |
| South Africa | 3         | 0.32%   |
| Slovakia     | 3         | 0.32%   |
| Pakistan     | 3         | 0.32%   |
| Nepal        | 3         | 0.32%   |
| Morocco      | 3         | 0.32%   |
| Iran         | 3         | 0.32%   |
| Greece       | 3         | 0.32%   |
| Egypt        | 3         | 0.32%   |
| Costa Rica   | 3         | 0.32%   |
| Colombia     | 3         | 0.32%   |
| Chile        | 3         | 0.32%   |
| Bangladesh   | 3         | 0.32%   |
| Slovenia     | 2         | 0.21%   |
| Singapore    | 2         | 0.21%   |
| Saudi Arabia | 2         | 0.21%   |
| Philippines  | 2         | 0.21%   |
| Myanmar      | 2         | 0.21%   |
| Lithuania    | 2         | 0.21%   |
| Latvia       | 2         | 0.21%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 10        | 1.05%   |
| Madrid         | 8         | 0.84%   |
| Helsinki       | 8         | 0.84%   |
| Berlin         | 8         | 0.84%   |
| Warsaw         | 7         | 0.73%   |
| Sydney         | 7         | 0.73%   |
| St Petersburg  | 7         | 0.73%   |
| Debica         | 7         | 0.73%   |
| Dallas         | 7         | 0.73%   |
| Sao Paulo      | 6         | 0.63%   |
| San Jose       | 6         | 0.63%   |
| Milan          | 6         | 0.63%   |
| Bucharest      | 6         | 0.63%   |
| Barcelona      | 6         | 0.63%   |
| Prague         | 5         | 0.52%   |
| Istanbul       | 5         | 0.52%   |
| Brisbane       | 5         | 0.52%   |
| San Francisco  | 4         | 0.42%   |
| Rome           | 4         | 0.42%   |
| Paris          | 4         | 0.42%   |
| Gothenburg     | 4         | 0.42%   |
| Curitiba       | 4         | 0.42%   |
| Buenos Aires   | 4         | 0.42%   |
| Beijing        | 4         | 0.42%   |
| Tel Aviv       | 3         | 0.31%   |
| Tampa          | 3         | 0.31%   |
| Stuttgart      | 3         | 0.31%   |
| Sofia          | 3         | 0.31%   |
| Santiago       | 3         | 0.31%   |
| Rio de Janeiro | 3         | 0.31%   |
| Recife         | 3         | 0.31%   |
| Ottawa         | 3         | 0.31%   |
| Moses Lake     | 3         | 0.31%   |
| London         | 3         | 0.31%   |
| Lima           | 3         | 0.31%   |
| Leipzig        | 3         | 0.31%   |
| Houston        | 3         | 0.31%   |
| Hamburg        | 3         | 0.31%   |
| Frederiksberg  | 3         | 0.31%   |
| Chicago        | 3         | 0.31%   |
| Budapest       | 3         | 0.31%   |
| Brno           | 3         | 0.31%   |
| Arequipa       | 3         | 0.31%   |
| Amsterdam      | 3         | 0.31%   |
| Zurich         | 2         | 0.21%   |
| Zagreb         | 2         | 0.21%   |
| Yerevan        | 2         | 0.21%   |
| Yangon         | 2         | 0.21%   |
| Wroclaw        | 2         | 0.21%   |
| Wiesbaden      | 2         | 0.21%   |
| Vancouver      | 2         | 0.21%   |
| Una            | 2         | 0.21%   |
| Toronto        | 2         | 0.21%   |
| Tampere        | 2         | 0.21%   |
| Taipei         | 2         | 0.21%   |
| Steenbecque    | 2         | 0.21%   |
| Singapore      | 2         | 0.21%   |
| Seoul          | 2         | 0.21%   |
| Seattle        | 2         | 0.21%   |
| Ryde           | 2         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 223       | 292    | 16.69%  |
| WDC                         | 180       | 279    | 13.47%  |
| Seagate                     | 173       | 225    | 12.95%  |
| SanDisk                     | 75        | 80     | 5.61%   |
| Kingston                    | 71        | 81     | 5.31%   |
| Toshiba                     | 69        | 85     | 5.16%   |
| Unknown                     | 64        | 77     | 4.79%   |
| SK Hynix                    | 61        | 64     | 4.57%   |
| Crucial                     | 41        | 47     | 3.07%   |
| Intel                       | 37        | 44     | 2.77%   |
| Micron Technology           | 33        | 37     | 2.47%   |
| Hitachi                     | 29        | 33     | 2.17%   |
| HGST                        | 26        | 29     | 1.95%   |
| KIOXIA                      | 20        | 22     | 1.5%    |
| Phison                      | 19        | 21     | 1.42%   |
| A-DATA Technology           | 18        | 21     | 1.35%   |
| PNY                         | 10        | 12     | 0.75%   |
| Apple                       | 10        | 11     | 0.75%   |
| Unknown                     | 10        | 10     | 0.75%   |
| Netac                       | 9         | 10     | 0.67%   |
| OCZ                         | 7         | 15     | 0.52%   |
| Micron/Crucial Technology   | 7         | 10     | 0.52%   |
| Hewlett-Packard             | 7         | 26     | 0.52%   |
| China                       | 7         | 8      | 0.52%   |
| Silicon Motion              | 6         | 6      | 0.45%   |
| Intenso                     | 6         | 7      | 0.45%   |
| Lexar                       | 5         | 5      | 0.37%   |
| Gigabyte Technology         | 5         | 5      | 0.37%   |
| SPCC                        | 4         | 4      | 0.3%    |
| XPG                         | 3         | 4      | 0.22%   |
| Transcend                   | 3         | 3      | 0.22%   |
| PLEXTOR                     | 3         | 3      | 0.22%   |
| MAXIO Technology (Hangzhou) | 3         | 3      | 0.22%   |
| KIOXIA-EXCERIA              | 3         | 4      | 0.22%   |
| JMicron                     | 3         | 3      | 0.22%   |
| Dogfish                     | 3         | 3      | 0.22%   |
| Corsair                     | 3         | 3      | 0.22%   |
| ASMT                        | 3         | 3      | 0.22%   |
| ADATA Technology            | 3         | 4      | 0.22%   |
| YMTC                        | 2         | 2      | 0.15%   |
| walram                      | 2         | 2      | 0.15%   |
| USB3.0                      | 2         | 2      | 0.15%   |
| Teclast                     | 2         | 2      | 0.15%   |
| Team                        | 2         | 3      | 0.15%   |
| S3+                         | 2         | 2      | 0.15%   |
| Patriot                     | 2         | 2      | 0.15%   |
| OEM                         | 2         | 2      | 0.15%   |
| MAXTOR                      | 2         | 3      | 0.15%   |
| LONDISK                     | 2         | 3      | 0.15%   |
| Lenovo                      | 2         | 2      | 0.15%   |
| KLEVV                       | 2         | 3      | 0.15%   |
| KingSpec                    | 2         | 2      | 0.15%   |
| KingFast                    | 2         | 2      | 0.15%   |
| GOODRAM                     | 2         | 2      | 0.15%   |
| FORESEE                     | 2         | 2      | 0.15%   |
| BIWIN                       | 2         | 2      | 0.15%   |
| Apacer                      | 2         | 2      | 0.15%   |
| W800S                       | 1         | 1      | 0.07%   |
| ViperTeq                    | 1         | 1      | 0.07%   |
| Verbatim                    | 1         | 1      | 0.07%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB        | 17        | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 0.86%   |
| Samsung SSD 860 EVO 500GB           | 13        | 0.86%   |
| Samsung NVMe SSD Drive 1TB          | 13        | 0.86%   |
| Kingston SA400S37240G 240GB SSD     | 11        | 0.73%   |
| Toshiba MQ01ABD100 1TB              | 10        | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB      | 10        | 0.66%   |
| Samsung NVMe SSD Drive 1024GB       | 10        | 0.66%   |
| Intel NVMe SSD Drive 512GB          | 10        | 0.66%   |
| Unknown                             | 10        | 0.66%   |
| Samsung SSD 850 EVO 500GB           | 9         | 0.6%    |
| Samsung NVMe SSD Drive 256GB        | 9         | 0.6%    |
| Kingston SA400S37480G 480GB SSD     | 9         | 0.6%    |
| Seagate ST500DM002-1BD142 500GB     | 8         | 0.53%   |
| Sandisk NVMe SSD Drive 512GB        | 8         | 0.53%   |
| Sandisk NVMe SSD Drive 1TB          | 8         | 0.53%   |
| Samsung NVMe SSD Drive 500GB        | 8         | 0.53%   |
| Crucial CT500MX500SSD1 500GB        | 8         | 0.53%   |
| Unknown SD/MMC/MS PRO 999GB         | 7         | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB      | 7         | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB      | 7         | 0.46%   |
| Seagate ST1000DM003-1ER162 1TB      | 7         | 0.46%   |
| Sandisk NVMe SSD Drive 500GB        | 7         | 0.46%   |
| Samsung SSD 980 PRO 1TB             | 7         | 0.46%   |
| Samsung SSD 850 EVO 250GB           | 7         | 0.46%   |
| Micron NVMe SSD Drive 512GB         | 7         | 0.46%   |
| HGST HTS545050A7E680 500GB          | 7         | 0.46%   |
| Crucial CT1000MX500SSD1 1TB         | 7         | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB            | 6         | 0.4%    |
| Unknown MMC Card  64GB              | 6         | 0.4%    |
| Toshiba NVMe SSD Drive 512GB        | 6         | 0.4%    |
| SK Hynix NVMe SSD Drive 512GB       | 6         | 0.4%    |
| SK Hynix NVMe SSD Drive 256GB       | 6         | 0.4%    |
| Seagate ST2000LM007-1R8174 2TB      | 6         | 0.4%    |
| Samsung SSD 980 1TB                 | 6         | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB      | 6         | 0.4%    |
| Samsung SSD 970 EVO Plus 1TB        | 6         | 0.4%    |
| Samsung MZALQ512HALU-000L2 512GB    | 6         | 0.4%    |
| Toshiba MQ04ABF100 1TB              | 5         | 0.33%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD | 5         | 0.33%   |
| Toshiba HDWD110 1TB                 | 5         | 0.33%   |
| Seagate ST500LT012-1DG142 500GB     | 5         | 0.33%   |
| Seagate ST31000528AS 1TB            | 5         | 0.33%   |
| Samsung SSD 870 QVO 1TB             | 5         | 0.33%   |
| Micron/Crucial NVMe SSD Drive 1TB   | 5         | 0.33%   |
| HGST HTS721010A9E630 1TB            | 5         | 0.33%   |
| Unknown MMC Card  32GB              | 4         | 0.27%   |
| Toshiba DT01ACA200 2TB              | 4         | 0.27%   |
| Toshiba DT01ACA050 500GB            | 4         | 0.27%   |
| SK Hynix NVMe SSD Drive 1024GB      | 4         | 0.27%   |
| SK Hynix HFM001TD3JX013N 1TB        | 4         | 0.27%   |
| Seagate ST9500325AS 500GB           | 4         | 0.27%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 0.27%   |
| Seagate ST1000DM003-1CH162 1TB      | 4         | 0.27%   |
| Sandisk NVMe SSD Drive 256GB        | 4         | 0.27%   |
| Sandisk NVMe SSD Drive 1024GB       | 4         | 0.27%   |
| Samsung SSD 970 EVO Plus 2TB        | 4         | 0.27%   |
| Samsung MZVLQ512HALU-000H1 512GB    | 4         | 0.27%   |
| Samsung MZVLB1T0HBLR-000L2 1TB      | 4         | 0.27%   |
| Phison NVMe SSD Drive 2TB           | 4         | 0.27%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 165       | 217    | 38.28%  |
| WDC                 | 129       | 207    | 29.93%  |
| Toshiba             | 45        | 57     | 10.44%  |
| Hitachi             | 28        | 32     | 6.5%    |
| HGST                | 26        | 29     | 6.03%   |
| Samsung Electronics | 16        | 18     | 3.71%   |
| Unknown             | 7         | 8      | 1.62%   |
| Apple               | 6         | 7      | 1.39%   |
| Hewlett-Packard     | 2         | 20     | 0.46%   |
| ASMT                | 2         | 2      | 0.46%   |
| USB                 | 1         | 1      | 0.23%   |
| StoreJet            | 1         | 1      | 0.23%   |
| SABRENT             | 1         | 1      | 0.23%   |
| MAXTOR              | 1         | 2      | 0.23%   |
| Fujitsu             | 1         | 1      | 0.23%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 79        | 94     | 19.55%  |
| Kingston            | 52        | 58     | 12.87%  |
| SanDisk             | 38        | 39     | 9.41%   |
| Crucial             | 37        | 43     | 9.16%   |
| WDC                 | 28        | 32     | 6.93%   |
| SK Hynix            | 14        | 14     | 3.47%   |
| A-DATA Technology   | 14        | 17     | 3.47%   |
| Intel               | 11        | 11     | 2.72%   |
| PNY                 | 9         | 11     | 2.23%   |
| Netac               | 8         | 9      | 1.98%   |
| China               | 7         | 8      | 1.73%   |
| Micron Technology   | 6         | 8      | 1.49%   |
| Toshiba             | 5         | 6      | 1.24%   |
| OCZ                 | 5         | 5      | 1.24%   |
| Lexar               | 5         | 5      | 1.24%   |
| Unknown             | 5         | 5      | 1.24%   |
| SPCC                | 4         | 4      | 0.99%   |
| Intenso             | 4         | 5      | 0.99%   |
| Hewlett-Packard     | 4         | 5      | 0.99%   |
| Transcend           | 3         | 3      | 0.74%   |
| PLEXTOR             | 3         | 3      | 0.74%   |
| Gigabyte Technology | 3         | 3      | 0.74%   |
| Dogfish             | 3         | 3      | 0.74%   |
| Corsair             | 3         | 3      | 0.74%   |
| Apple               | 3         | 3      | 0.74%   |
| USB3.0              | 2         | 2      | 0.5%    |
| Teclast             | 2         | 2      | 0.5%    |
| Seagate             | 2         | 2      | 0.5%    |
| S3+                 | 2         | 2      | 0.5%    |
| Phison              | 2         | 2      | 0.5%    |
| Patriot             | 2         | 2      | 0.5%    |
| LONDISK             | 2         | 3      | 0.5%    |
| KLEVV               | 2         | 3      | 0.5%    |
| KIOXIA-EXCERIA      | 2         | 3      | 0.5%    |
| KingSpec            | 2         | 2      | 0.5%    |
| JMicron             | 2         | 2      | 0.5%    |
| GOODRAM             | 2         | 2      | 0.5%    |
| FORESEE             | 2         | 2      | 0.5%    |
| BIWIN               | 2         | 2      | 0.5%    |
| W800S               | 1         | 1      | 0.25%   |
| ViperTeq            | 1         | 1      | 0.25%   |
| Verbatim            | 1         | 1      | 0.25%   |
| Vaseky              | 1         | 1      | 0.25%   |
| UMAX                | 1         | 1      | 0.25%   |
| TCSUNBOW-X5         | 1         | 1      | 0.25%   |
| TAMMUZ              | 1         | 1      | 0.25%   |
| Smartbuy            | 1         | 1      | 0.25%   |
| MidasForce          | 1         | 1      | 0.25%   |
| MAXTOR              | 1         | 1      | 0.25%   |
| LITEON              | 1         | 1      | 0.25%   |
| LDLC                | 1         | 1      | 0.25%   |
| Hitachi             | 1         | 1      | 0.25%   |
| EMTEC               | 1         | 1      | 0.25%   |
| E535N               | 1         | 1      | 0.25%   |
| Dell                | 1         | 1      | 0.25%   |
| BHT                 | 1         | 1      | 0.25%   |
| BAITITON            | 1         | 1      | 0.25%   |
| AXIOM               | 1         | 1      | 0.25%   |
| ASMT                | 1         | 1      | 0.25%   |
| ASMedia             | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 411       | 517    | 33.69%  |
| HDD     | 370       | 603    | 30.33%  |
| SSD     | 347       | 451    | 28.44%  |
| MMC     | 63        | 74     | 5.16%   |
| Unknown | 29        | 33     | 2.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 576       | 1011   | 52.08%  |
| NVMe | 409       | 515    | 36.98%  |
| MMC  | 63        | 74     | 5.7%    |
| SAS  | 58        | 78     | 5.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 407       | 520    | 53.27%  |
| 0.51-1.0   | 231       | 291    | 30.24%  |
| 1.01-2.0   | 71        | 130    | 9.29%   |
| 3.01-4.0   | 21        | 28     | 2.75%   |
| 4.01-10.0  | 20        | 63     | 2.62%   |
| 2.01-3.0   | 8         | 10     | 1.05%   |
| 10.01-20.0 | 6         | 12     | 0.79%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 272       | 28.22%  |
| 251-500        | 241       | 25%     |
| 501-1000       | 153       | 15.87%  |
| 1001-2000      | 74        | 7.68%   |
| 51-100         | 64        | 6.64%   |
| 1-20           | 55        | 5.71%   |
| More than 3000 | 50        | 5.19%   |
| 2001-3000      | 26        | 2.7%    |
| 21-50          | 24        | 2.49%   |
| Unknown        | 5         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 404       | 41.61%  |
| 21-50          | 165       | 16.99%  |
| 51-100         | 119       | 12.26%  |
| 101-250        | 114       | 11.74%  |
| 251-500        | 73        | 7.52%   |
| 501-1000       | 35        | 3.6%    |
| 1001-2000      | 25        | 2.57%   |
| More than 3000 | 23        | 2.37%   |
| 2001-3000      | 7         | 0.72%   |
| Unknown        | 5         | 0.51%   |
| 0              | 1         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 4         | 5      | 8.51%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 4.26%   |
| Seagate ST9500325AS 500GB                           | 2         | 2      | 4.26%   |
| HGST HTS545050A7E680 500GB                          | 2         | 2      | 4.26%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 2.13%   |
| WDC WD5000BEVT-00A0RT0 500GB                        | 1         | 1      | 2.13%   |
| WDC WD5000AAKX-08ERMA0 500GB                        | 1         | 1      | 2.13%   |
| WDC WD5000AAKS-65V0A0 500GB                         | 1         | 1      | 2.13%   |
| WDC WD3200BEKT-60V5T1 320GB                         | 1         | 1      | 2.13%   |
| WDC WD20EARX-008FB0 2TB                             | 1         | 2      | 2.13%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 2.13%   |
| WDC WD10JPVX-00JC3T0 1TB                            | 1         | 1      | 2.13%   |
| WDC WD10EZEX-22MFCA0 1TB                            | 1         | 1      | 2.13%   |
| WDC WD10EFRX-68FYTN0 1TB                            | 1         | 1      | 2.13%   |
| WDC WD1003FBYX-01Y7B1 1TB                           | 1         | 1      | 2.13%   |
| Toshiba MQ01ABF032 320GB                            | 1         | 1      | 2.13%   |
| Toshiba MK5065GSX 500GB                             | 1         | 1      | 2.13%   |
| SK Hynix SC210 2.5 7MM 128GB SSD                    | 1         | 1      | 2.13%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.13%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.13%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 2.13%   |
| Seagate ST3750640NS 752GB                           | 1         | 2      | 2.13%   |
| Seagate ST320LM001 HN-M320MBB 320GB                 | 1         | 1      | 2.13%   |
| Seagate ST2000DX002-2DV164 2TB                      | 1         | 1      | 2.13%   |
| Seagate ST1000LM014-SSHD-8GB                        | 1         | 1      | 2.13%   |
| SanDisk SD8SBAT256G1122 256GB SSD                   | 1         | 1      | 2.13%   |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 2.13%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 2.13%   |
| Samsung Electronics HM121HI 120GB                   | 1         | 1      | 2.13%   |
| Micron Technology MTFDDAK256TBN-1AR1ZABHA 256GB SSD | 1         | 1      | 2.13%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 2.13%   |
| Kingston SV300S37A60G 64GB SSD                      | 1         | 1      | 2.13%   |
| Kingston SA400S37240G 240GB SSD                     | 1         | 1      | 2.13%   |
| Intenso SSD 120GB                                   | 1         | 1      | 2.13%   |
| Intel SSDSA2M160G2LE 160GB                          | 1         | 1      | 2.13%   |
| Hitachi HTS543232L9A300 320GB                       | 1         | 1      | 2.13%   |
| Hitachi HDS721010CLA332 1TB                         | 1         | 1      | 2.13%   |
| HGST HTS721010A9E630 1TB                            | 1         | 2      | 2.13%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.13%   |
| HGST HTS541010A7E630 1TB                            | 1         | 1      | 2.13%   |
| Apple HDD ST1000LM024 1TB                           | 1         | 2      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 27.66%  |
| WDC                 | 11        | 12     | 23.4%   |
| HGST                | 5         | 6      | 10.64%  |
| Toshiba             | 4         | 4      | 8.51%   |
| Samsung Electronics | 3         | 3      | 6.38%   |
| Kingston            | 2         | 2      | 4.26%   |
| Hitachi             | 2         | 2      | 4.26%   |
| SK Hynix            | 1         | 1      | 2.13%   |
| SanDisk             | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| LITEON              | 1         | 1      | 2.13%   |
| Intenso             | 1         | 1      | 2.13%   |
| Intel               | 1         | 1      | 2.13%   |
| Apple               | 1         | 2      | 2.13%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 15     | 34.21%  |
| WDC                 | 11        | 12     | 28.95%  |
| HGST                | 5         | 6      | 13.16%  |
| Toshiba             | 4         | 4      | 10.53%  |
| Samsung Electronics | 2         | 2      | 5.26%   |
| Hitachi             | 2         | 2      | 5.26%   |
| Apple               | 1         | 2      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 37        | 43     | 80.43%  |
| SSD  | 9         | 9      | 19.57%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 617       | 1124   | 62.2%   |
| Works    | 329       | 502    | 33.17%  |
| Malfunc  | 46        | 52     | 4.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 590       | 47.16%  |
| AMD                          | 170       | 13.59%  |
| Samsung Electronics          | 145       | 11.59%  |
| Sandisk                      | 69        | 5.52%   |
| SK Hynix                     | 46        | 3.68%   |
| Micron Technology            | 27        | 2.16%   |
| Phison Electronics           | 21        | 1.68%   |
| Toshiba America Info Systems | 20        | 1.6%    |
| KIOXIA                       | 20        | 1.6%    |
| Kingston Technology Company  | 20        | 1.6%    |
| ASMedia Technology           | 19        | 1.52%   |
| Marvell Technology Group     | 17        | 1.36%   |
| Nvidia                       | 15        | 1.2%    |
| JMicron Technology           | 12        | 0.96%   |
| Micron/Crucial Technology    | 11        | 0.88%   |
| Silicon Motion               | 8         | 0.64%   |
| LSI Logic / Symbios Logic    | 8         | 0.64%   |
| ADATA Technology             | 8         | 0.64%   |
| MAXIO Technology (Hangzhou)  | 3         | 0.24%   |
| Yangtze Memory Technologies  | 2         | 0.16%   |
| VIA Technologies             | 2         | 0.16%   |
| Silicon Image                | 2         | 0.16%   |
| Shenzhen Longsys Electronics | 2         | 0.16%   |
| Realtek Semiconductor        | 2         | 0.16%   |
| OCZ Technology Group         | 2         | 0.16%   |
| Lenovo                       | 2         | 0.16%   |
| Hewlett-Packard              | 2         | 0.16%   |
| Zhaoxin                      | 1         | 0.08%   |
| Unknown                      | 1         | 0.08%   |
| Union Memory (Shenzhen)      | 1         | 0.08%   |
| Seagate Technology           | 1         | 0.08%   |
| Chelsio Communications       | 1         | 0.08%   |
| Broadcom / LSI               | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 129       | 9.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 65        | 4.64%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 48        | 3.43%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 45        | 3.21%   |
| Samsung NVMe SSD Controller 980                                                         | 40        | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 37        | 2.64%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 36        | 2.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 30        | 2.14%   |
| Micron Non-Volatile memory controller                                                   | 26        | 1.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 25        | 1.78%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 24        | 1.71%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 24        | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 24        | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 23        | 1.64%   |
| SK Hynix Gold P31 SSD                                                                   | 21        | 1.5%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 19        | 1.36%   |
| AMD 400 Series Chipset SATA Controller                                                  | 19        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 18        | 1.28%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 18        | 1.28%   |
| KIOXIA Non-Volatile memory controller                                                   | 17        | 1.21%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 17        | 1.21%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 15        | 1.07%   |
| Sandisk Non-Volatile memory controller                                                  | 15        | 1.07%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 15        | 1.07%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 14        | 1%      |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 14        | 1%      |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                              | 13        | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 13        | 0.93%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                         | 13        | 0.93%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 13        | 0.93%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 12        | 0.86%   |
| SK Hynix BC511                                                                          | 11        | 0.79%   |
| Intel SSD 660P Series                                                                   | 11        | 0.79%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 11        | 0.79%   |
| AMD 500 Series Chipset SATA Controller                                                  | 11        | 0.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 10        | 0.71%   |
| Intel SATA Controller [RAID mode]                                                       | 10        | 0.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10        | 0.71%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 9         | 0.64%   |
| Intel Non-Volatile memory controller                                                    | 9         | 0.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 9         | 0.64%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 9         | 0.64%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 9         | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 9         | 0.64%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 9         | 0.64%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                         | 8         | 0.57%   |
| Kingston Company Company Non-Volatile memory controller                                 | 8         | 0.57%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 8         | 0.57%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 8         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 8         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 8         | 0.57%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 8         | 0.57%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 8         | 0.57%   |
| Phison PS5013 E13 NVMe Controller                                                       | 7         | 0.5%    |
| Phison E16 PCIe4 NVMe Controller                                                        | 7         | 0.5%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 7         | 0.5%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 7         | 0.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 7         | 0.5%    |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 6         | 0.43%   |
| Phison E12 NVMe Controller                                                              | 6         | 0.43%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 629       | 50.6%   |
| NVMe | 407       | 32.74%  |
| RAID | 97        | 7.8%    |
| IDE  | 96        | 7.72%   |
| SAS  | 9         | 0.72%   |
| SCSI | 5         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 696       | 73.11%  |
| AMD          | 229       | 24.05%  |
| ARM          | 25        | 2.63%   |
| QUALCOMM     | 1         | 0.11%   |
| CentaurHauls | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 32        | 3.36%   |
| ARM Processor                                 | 25        | 2.63%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 17        | 1.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 1.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 10        | 1.05%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 1.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 0.95%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.84%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 7         | 0.74%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 7         | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 7         | 0.74%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 7         | 0.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 7         | 0.74%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 7         | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.63%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 0.63%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 0.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 6         | 0.63%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 6         | 0.63%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 6         | 0.63%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 6         | 0.63%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 0.63%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 6         | 0.63%   |
| Intel Core i7-4790K CPU @ 4.00GHz             | 5         | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 0.53%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 5         | 0.53%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.53%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.53%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 5         | 0.53%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 5         | 0.53%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.53%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.53%   |
| AMD Phenom II X4 965 Processor                | 5         | 0.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.42%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 4         | 0.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 4         | 0.42%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 4         | 0.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.42%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 0.42%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 4         | 0.42%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 4         | 0.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.42%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 4         | 0.42%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 0.42%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 4         | 0.42%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 4         | 0.42%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 0.42%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 4         | 0.42%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 4         | 0.42%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 4         | 0.42%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 4         | 0.42%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 0.42%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.42%   |
| Intel Xeon CPU X3430 @ 2.40GHz                | 3         | 0.32%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.32%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 3         | 0.32%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 198       | 20.8%   |
| Intel Core i7                  | 154       | 16.18%  |
| Other                          | 140       | 14.71%  |
| Intel Core i3                  | 78        | 8.19%   |
| AMD Ryzen 5                    | 64        | 6.72%   |
| AMD Ryzen 7                    | 59        | 6.2%    |
| Intel Celeron                  | 49        | 5.15%   |
| Intel Xeon                     | 33        | 3.47%   |
| Intel Core 2 Duo               | 19        | 2%      |
| Intel Pentium                  | 17        | 1.79%   |
| AMD Ryzen 9                    | 16        | 1.68%   |
| Intel Core 2 Quad              | 10        | 1.05%   |
| AMD FX                         | 10        | 1.05%   |
| AMD A6                         | 10        | 1.05%   |
| AMD A10                        | 9         | 0.95%   |
| Intel Atom                     | 7         | 0.74%   |
| AMD Phenom II X4               | 7         | 0.74%   |
| AMD Ryzen 3                    | 6         | 0.63%   |
| AMD A4                         | 6         | 0.63%   |
| Intel Core i9                  | 5         | 0.53%   |
| AMD Ryzen 7 PRO                | 5         | 0.53%   |
| AMD A8                         | 5         | 0.53%   |
| Intel Pentium Silver           | 3         | 0.32%   |
| Intel Pentium Dual-Core        | 3         | 0.32%   |
| Intel Pentium Dual             | 3         | 0.32%   |
| AMD Phenom II X6               | 3         | 0.32%   |
| Intel Core 2                   | 2         | 0.21%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.21%   |
| AMD Ryzen 5 PRO                | 2         | 0.21%   |
| AMD GX                         | 2         | 0.21%   |
| AMD E1                         | 2         | 0.21%   |
| AMD Athlon II X4               | 2         | 0.21%   |
| AMD Athlon                     | 2         | 0.21%   |
| QUALCOMM AArch64               | 1         | 0.11%   |
| Intel Pentium 4                | 1         | 0.11%   |
| Intel Genuine                  | 1         | 0.11%   |
| Intel Core m3                  | 1         | 0.11%   |
| Intel Core M                   | 1         | 0.11%   |
| Intel Core 2 Extreme           | 1         | 0.11%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.11%   |
| AMD Ryzen Threadripper         | 1         | 0.11%   |
| AMD Ryzen Embedded             | 1         | 0.11%   |
| AMD Phenom II                  | 1         | 0.11%   |
| AMD Phenom                     | 1         | 0.11%   |
| AMD EPYC                       | 1         | 0.11%   |
| AMD E2                         | 1         | 0.11%   |
| AMD E                          | 1         | 0.11%   |
| AMD C-50                       | 1         | 0.11%   |
| AMD Athlon II X3               | 1         | 0.11%   |
| AMD Athlon II                  | 1         | 0.11%   |
| AMD Athlon 64 X2               | 1         | 0.11%   |
| AMD Athlon 64                  | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 397       | 41.7%   |
| 2       | 298       | 31.3%   |
| 8       | 103       | 10.82%  |
| 6       | 96        | 10.08%  |
| 12      | 14        | 1.47%   |
| 14      | 12        | 1.26%   |
| 16      | 9         | 0.95%   |
| 10      | 7         | 0.74%   |
| 3       | 5         | 0.53%   |
| 1       | 4         | 0.42%   |
| Unknown | 4         | 0.42%   |
| 28      | 2         | 0.21%   |
| 64      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 934       | 98.11%  |
| 2       | 14        | 1.47%   |
| Unknown | 4         | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 673       | 70.69%  |
| 1       | 275       | 28.89%  |
| Unknown | 4         | 0.42%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 930       | 97.69%  |
| Unknown        | 22        | 2.31%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 542       | 56.28%  |
| 0x806c1    | 48        | 4.98%   |
| 0x306a9    | 27        | 2.8%    |
| 0x806ea    | 24        | 2.49%   |
| 0x806ec    | 22        | 2.28%   |
| 0x0a50000c | 22        | 2.28%   |
| 0x306c3    | 17        | 1.77%   |
| 0x906ea    | 15        | 1.56%   |
| 0x206a7    | 14        | 1.45%   |
| 0x906a3    | 12        | 1.25%   |
| 0x706e5    | 10        | 1.04%   |
| 0x706a8    | 9         | 0.93%   |
| 0x08108109 | 9         | 0.93%   |
| 0x906e9    | 8         | 0.83%   |
| 0x08600106 | 8         | 0.83%   |
| 0x806e9    | 7         | 0.73%   |
| 0x806d1    | 7         | 0.73%   |
| 0x506e3    | 7         | 0.73%   |
| 0x40651    | 7         | 0.73%   |
| 0x08600104 | 7         | 0.73%   |
| 0x06001119 | 7         | 0.73%   |
| 0xa0652    | 6         | 0.62%   |
| 0x706a1    | 6         | 0.62%   |
| 0x1067a    | 6         | 0.62%   |
| 0x0a201016 | 6         | 0.62%   |
| 0x08701021 | 6         | 0.62%   |
| 0x906ed    | 5         | 0.52%   |
| 0x806eb    | 5         | 0.52%   |
| 0x20655    | 5         | 0.52%   |
| 0x08608103 | 5         | 0.52%   |
| 0x506c9    | 4         | 0.42%   |
| 0x306e4    | 4         | 0.42%   |
| 0x306d4    | 4         | 0.42%   |
| 0x90672    | 3         | 0.31%   |
| 0x406e3    | 3         | 0.31%   |
| 0x30678    | 3         | 0.31%   |
| 0x08701013 | 3         | 0.31%   |
| 0x0810100b | 3         | 0.31%   |
| 0x07030105 | 3         | 0.31%   |
| 0x010000c8 | 3         | 0.31%   |
| 0xa0655    | 2         | 0.21%   |
| 0xa0653    | 2         | 0.21%   |
| 0x906eb    | 2         | 0.21%   |
| 0x90675    | 2         | 0.21%   |
| 0x306f2    | 2         | 0.21%   |
| 0x0a50000b | 2         | 0.21%   |
| 0x0a201009 | 2         | 0.21%   |
| 0x0800820d | 2         | 0.21%   |
| 0x06006705 | 2         | 0.21%   |
| 0x0600611a | 2         | 0.21%   |
| 0x06003106 | 2         | 0.21%   |
| 0x06000852 | 2         | 0.21%   |
| 0xa0671    | 1         | 0.1%    |
| 0x906ec    | 1         | 0.1%    |
| 0x906c0    | 1         | 0.1%    |
| 0x806c2    | 1         | 0.1%    |
| 0x6fd      | 1         | 0.1%    |
| 0x6fa      | 1         | 0.1%    |
| 0x50654    | 1         | 0.1%    |
| 0x406f1    | 1         | 0.1%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 148       | 15.55%  |
| Haswell          | 81        | 8.51%   |
| IvyBridge        | 67        | 7.04%   |
| TigerLake        | 66        | 6.93%   |
| Unknown          | 63        | 6.62%   |
| Zen 3            | 52        | 5.46%   |
| Zen 2            | 50        | 5.25%   |
| SandyBridge      | 50        | 5.25%   |
| Skylake          | 42        | 4.41%   |
| Penryn           | 30        | 3.15%   |
| IceLake          | 28        | 2.94%   |
| Zen+             | 27        | 2.84%   |
| Goldmont plus    | 26        | 2.73%   |
| Westmere         | 25        | 2.63%   |
| CometLake        | 24        | 2.52%   |
| Silvermont       | 22        | 2.31%   |
| Piledriver       | 17        | 1.79%   |
| K10              | 16        | 1.68%   |
| Broadwell        | 16        | 1.68%   |
| Alderlake Hybrid | 16        | 1.68%   |
| Zen              | 14        | 1.47%   |
| Excavator        | 13        | 1.37%   |
| Core             | 13        | 1.37%   |
| Nehalem          | 12        | 1.26%   |
| Puma             | 7         | 0.74%   |
| Goldmont         | 7         | 0.74%   |
| Bobcat           | 5         | 0.53%   |
| Steamroller      | 4         | 0.42%   |
| K8 Hammer        | 3         | 0.32%   |
| K10 Llano        | 3         | 0.32%   |
| K8 & K10 hybrid  | 2         | 0.21%   |
| Tremont          | 1         | 0.11%   |
| NetBurst         | 1         | 0.11%   |
| Jaguar           | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 550       | 49.55%  |
| Nvidia                     | 310       | 27.93%  |
| AMD                        | 236       | 21.26%  |
| Matrox Electronics Systems | 8         | 0.72%   |
| ASPEED Technology          | 5         | 0.45%   |
| Zhaoxin                    | 1         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 63        | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 36        | 3.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 36        | 3.18%   |
| Intel UHD Graphics 620                                                                   | 34        | 3%      |
| AMD Cezanne                                                                              | 33        | 2.91%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 2.12%   |
| AMD Renoir                                                                               | 24        | 2.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 23        | 2.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 23        | 2.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 21        | 1.85%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 18        | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 16        | 1.41%   |
| Intel HD Graphics 620                                                                    | 16        | 1.41%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 1.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 16        | 1.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 15        | 1.32%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 1.32%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 14        | 1.24%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.24%   |
| AMD Lucienne                                                                             | 14        | 1.24%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 13        | 1.15%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 1.15%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 13        | 1.15%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 11        | 0.97%   |
| Intel HD Graphics 530                                                                    | 11        | 0.97%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 11        | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 0.79%   |
| Intel HD Graphics 630                                                                    | 9         | 0.79%   |
| Intel HD Graphics 5500                                                                   | 9         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 0.79%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 0.79%   |
| Intel Iris Plus Graphics G7                                                              | 8         | 0.71%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.62%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 7         | 0.62%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 0.62%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 7         | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.53%   |
| Nvidia TU117M                                                                            | 6         | 0.53%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 6         | 0.53%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 6         | 0.53%   |
| Intel HD Graphics 500                                                                    | 6         | 0.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 6         | 0.53%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 6         | 0.53%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 0.44%   |
| Nvidia GT218 [GeForce 210]                                                               | 5         | 0.44%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5         | 0.44%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 5         | 0.44%   |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 5         | 0.44%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 5         | 0.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.44%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 0.44%   |
| Intel AlderLake-S GT1                                                                    | 5         | 0.44%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.44%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 0.44%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.35%   |
| Nvidia GP108M [GeForce MX250]                                                            | 4         | 0.35%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 384       | 40.25%  |
| 1 x AMD         | 183       | 19.18%  |
| 1 x Nvidia      | 153       | 16.04%  |
| Intel + Nvidia  | 130       | 13.63%  |
| Other           | 29        | 3.04%   |
| Intel + AMD     | 23        | 2.41%   |
| AMD + Nvidia    | 20        | 2.1%    |
| 2 x AMD         | 11        | 1.15%   |
| 1 x Matrox      | 7         | 0.73%   |
| 2 x Nvidia      | 6         | 0.63%   |
| 1 x ASPEED      | 4         | 0.42%   |
| 2 x Intel       | 1         | 0.1%    |
| 1 x Zhaoxin     | 1         | 0.1%    |
| Nvidia + Matrox | 1         | 0.1%    |
| Nvidia + ASPEED | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 705       | 73.9%   |
| Proprietary | 189       | 19.81%  |
| Unknown     | 60        | 6.29%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 747       | 78.06%  |
| 1.01-2.0   | 59        | 6.17%   |
| 0.51-1.0   | 39        | 4.08%   |
| 0.01-0.5   | 39        | 4.08%   |
| 3.01-4.0   | 29        | 3.03%   |
| 7.01-8.0   | 24        | 2.51%   |
| 8.01-16.0  | 11        | 1.15%   |
| 5.01-6.0   | 7         | 0.73%   |
| 4.01-5.0   | 1         | 0.1%    |
| 2.01-3.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 138       | 13.39%  |
| AU Optronics            | 130       | 12.61%  |
| BOE                     | 114       | 11.06%  |
| LG Display              | 84        | 8.15%   |
| Chimei Innolux          | 82        | 7.95%   |
| Dell                    | 63        | 6.11%   |
| Goldstar                | 53        | 5.14%   |
| Acer                    | 26        | 2.52%   |
| Hewlett-Packard         | 25        | 2.42%   |
| Ancor Communications    | 24        | 2.33%   |
| Sharp                   | 22        | 2.13%   |
| BenQ                    | 22        | 2.13%   |
| AOC                     | 21        | 2.04%   |
| Lenovo                  | 19        | 1.84%   |
| Philips                 | 17        | 1.65%   |
| PANDA                   | 15        | 1.45%   |
| Apple                   | 13        | 1.26%   |
| ASUSTek Computer        | 12        | 1.16%   |
| ViewSonic               | 11        | 1.07%   |
| InfoVision              | 11        | 1.07%   |
| CSO                     | 8         | 0.78%   |
| Sony                    | 7         | 0.68%   |
| Chi Mei Optoelectronics | 7         | 0.68%   |
| LG Electronics          | 6         | 0.58%   |
| Unknown                 | 5         | 0.48%   |
| Iiyama                  | 5         | 0.48%   |
| Onkyo                   | 4         | 0.39%   |
| Vizio                   | 3         | 0.29%   |
| Unknown (XXX)           | 3         | 0.29%   |
| OEM                     | 3         | 0.29%   |
| CPT                     | 3         | 0.29%   |
| Unknown                 | 3         | 0.29%   |
| Vestel Elektronik       | 2         | 0.19%   |
| Toshiba                 | 2         | 0.19%   |
| Sceptre Tech            | 2         | 0.19%   |
| RTK                     | 2         | 0.19%   |
| Pixio                   | 2         | 0.19%   |
| Panasonic               | 2         | 0.19%   |
| NEC Computers           | 2         | 0.19%   |
| MStar                   | 2         | 0.19%   |
| MSI                     | 2         | 0.19%   |
| Medion                  | 2         | 0.19%   |
| LG Philips              | 2         | 0.19%   |
| InnoLux Display         | 2         | 0.19%   |
| HUAWEI                  | 2         | 0.19%   |
| HKC                     | 2         | 0.19%   |
| HannStar                | 2         | 0.19%   |
| Fujitsu Siemens         | 2         | 0.19%   |
| Eizo                    | 2         | 0.19%   |
| CTV                     | 2         | 0.19%   |
| CHD                     | 2         | 0.19%   |
| ___                     | 1         | 0.1%    |
| WST                     | 1         | 0.1%    |
| TMX                     | 1         | 0.1%    |
| TCT                     | 1         | 0.1%    |
| Sunplus                 | 1         | 0.1%    |
| STA                     | 1         | 0.1%    |
| SPU                     | 1         | 0.1%    |
| SLD                     | 1         | 0.1%    |
| Skyworth                | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 6         | 0.57%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 5         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.47%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.47%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.38%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 0.38%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.38%   |
| Dell U2414H DELA0B2 1920x1080 527x296mm 23.8-inch                     | 4         | 0.38%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch       | 4         | 0.38%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 4         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.28%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.28%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 3         | 0.28%   |
| LG Display LCD Monitor LGD0465 1366x768 344x194mm 15.5-inch           | 3         | 0.28%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 3         | 0.28%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch          | 3         | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 3         | 0.28%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 3         | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 3         | 0.28%   |
| CSO LCD Monitor CSO1301 2160x1350 280x175mm 13.0-inch                 | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14FF 1920x1080 309x173mm 13.9-inch      | 3         | 0.28%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 3         | 0.28%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 3         | 0.28%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 3         | 0.28%   |
| BOE LCD Monitor BOE06F2 1920x1080 309x173mm 13.9-inch                 | 3         | 0.28%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 3         | 0.28%   |
| BenQ GL2780 BNQ78EC 1920x1080 598x336mm 27.0-inch                     | 3         | 0.28%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.28%   |
| AU Optronics LCD Monitor AUO299C 1920x1080 382x215mm 17.3-inch        | 3         | 0.28%   |
| AOC U2790B AOC2790 3840x2160 597x336mm 27.0-inch                      | 3         | 0.28%   |
| AOC 24G1WG4 AOC2401 1920x1080 521x293mm 23.5-inch                     | 3         | 0.28%   |
| Ancor Communications VE248 ACI2494 1920x1080 531x299mm 24.0-inch      | 3         | 0.28%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 3         | 0.28%   |
| Unknown                                                               | 3         | 0.28%   |
| ViewSonic VA2719 Series VSCC132 1920x1080 598x336mm 27.0-inch         | 2         | 0.19%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                         | 2         | 0.19%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 0.19%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch     | 2         | 0.19%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 2         | 0.19%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 2         | 0.19%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 2         | 0.19%   |
| Samsung Electronics LS28AG700N SAM7177 3840x2160 632x360mm 28.6-inch  | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch  | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch  | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SAM7103 3840x2160 700x390mm 31.5-inch | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SAM0C3C 1366x768 609x347mm 27.6-inch  | 2         | 0.19%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                     | 2         | 0.19%   |
| Samsung Electronics LC24RG50 SAM0F90 1920x1080 532x304mm 24.1-inch    | 2         | 0.19%   |
| Philips 234EL PHLC069 1920x1080 509x286mm 23.0-inch                   | 2         | 0.19%   |
| Philips 227E4LH PHLC0AC 1920x1080 477x268mm 21.5-inch                 | 2         | 0.19%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 2         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 474       | 48.37%  |
| 1366x768 (WXGA)    | 152       | 15.51%  |
| 3840x2160 (4K)     | 80        | 8.16%   |
| 2560x1440 (QHD)    | 54        | 5.51%   |
| 1600x900 (HD+)     | 40        | 4.08%   |
| 1280x1024 (SXGA)   | 24        | 2.45%   |
| 1680x1050 (WSXGA+) | 23        | 2.35%   |
| 1920x1200 (WUXGA)  | 22        | 2.24%   |
| 1440x900 (WXGA+)   | 14        | 1.43%   |
| 3440x1440          | 11        | 1.12%   |
| 2560x1600          | 11        | 1.12%   |
| 1280x800 (WXGA)    | 10        | 1.02%   |
| 2880x1800          | 8         | 0.82%   |
| 2560x1080          | 8         | 0.82%   |
| 1920x540           | 5         | 0.51%   |
| 3840x2400          | 4         | 0.41%   |
| 2256x1504          | 4         | 0.41%   |
| 2160x1440          | 4         | 0.41%   |
| Unknown            | 4         | 0.41%   |
| 2736x1824          | 3         | 0.31%   |
| 2160x1350          | 3         | 0.31%   |
| 3840x1080          | 2         | 0.2%    |
| 1360x768           | 2         | 0.2%    |
| 1024x768 (XGA)     | 2         | 0.2%    |
| 6400x2160          | 1         | 0.1%    |
| 4480x1440          | 1         | 0.1%    |
| 4480x1080          | 1         | 0.1%    |
| 3840x1600          | 1         | 0.1%    |
| 3456x2160          | 1         | 0.1%    |
| 3240x2160          | 1         | 0.1%    |
| 3200x2000          | 1         | 0.1%    |
| 3000x2000          | 1         | 0.1%    |
| 2520x1680          | 1         | 0.1%    |
| 2464x900           | 1         | 0.1%    |
| 2240x1400          | 1         | 0.1%    |
| 2048x1536          | 1         | 0.1%    |
| 2048x1152          | 1         | 0.1%    |
| 1600x1200          | 1         | 0.1%    |
| 1280x768           | 1         | 0.1%    |
| 1080x1920          | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 272       | 26.36%  |
| 14      | 102       | 9.88%   |
| 13      | 101       | 9.79%   |
| 27      | 76        | 7.36%   |
| 24      | 68        | 6.59%   |
| 23      | 63        | 6.1%    |
| 21      | 62        | 6.01%   |
| 17      | 62        | 6.01%   |
| Unknown | 33        | 3.2%    |
| 22      | 18        | 1.74%   |
| 19      | 18        | 1.74%   |
| 34      | 17        | 1.65%   |
| 31      | 16        | 1.55%   |
| 20      | 12        | 1.16%   |
| 16      | 12        | 1.16%   |
| 12      | 12        | 1.16%   |
| 32      | 10        | 0.97%   |
| 11      | 10        | 0.97%   |
| 84      | 9         | 0.87%   |
| 18      | 7         | 0.68%   |
| 72      | 6         | 0.58%   |
| 54      | 6         | 0.58%   |
| 40      | 5         | 0.48%   |
| 43      | 4         | 0.39%   |
| 26      | 4         | 0.39%   |
| 46      | 3         | 0.29%   |
| 25      | 3         | 0.29%   |
| 65      | 2         | 0.19%   |
| 52      | 2         | 0.19%   |
| 48      | 2         | 0.19%   |
| 42      | 2         | 0.19%   |
| 33      | 2         | 0.19%   |
| 28      | 2         | 0.19%   |
| 86      | 1         | 0.1%    |
| 63      | 1         | 0.1%    |
| 57      | 1         | 0.1%    |
| 55      | 1         | 0.1%    |
| 37      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 35      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |
| 10      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 434       | 42.67%  |
| 501-600     | 189       | 18.58%  |
| 401-500     | 110       | 10.82%  |
| 201-300     | 78        | 7.67%   |
| 351-400     | 64        | 6.29%   |
| Unknown     | 33        | 3.24%   |
| 601-700     | 32        | 3.15%   |
| 701-800     | 30        | 2.95%   |
| 1001-1500   | 18        | 1.77%   |
| 1501-2000   | 16        | 1.57%   |
| 801-900     | 7         | 0.69%   |
| 901-1000    | 6         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 731       | 79.2%   |
| 16/10   | 104       | 11.27%  |
| Unknown | 22        | 2.38%   |
| 5/4     | 21        | 2.28%   |
| 21/9    | 18        | 1.95%   |
| 3/2     | 17        | 1.84%   |
| 4/3     | 5         | 0.54%   |
| 32/9    | 3         | 0.33%   |
| 6/5     | 2         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 271       | 26.46%  |
| 201-250        | 166       | 16.21%  |
| 81-90          | 162       | 15.82%  |
| 301-350        | 80        | 7.81%   |
| 151-200        | 48        | 4.69%   |
| 351-500        | 47        | 4.59%   |
| 121-130        | 45        | 4.39%   |
| 71-80          | 40        | 3.91%   |
| Unknown        | 33        | 3.22%   |
| More than 1000 | 29        | 2.83%   |
| 251-300        | 24        | 2.34%   |
| 141-150        | 21        | 2.05%   |
| 501-1000       | 19        | 1.86%   |
| 61-70          | 11        | 1.07%   |
| 111-120        | 11        | 1.07%   |
| 51-60          | 10        | 0.98%   |
| 131-140        | 3         | 0.29%   |
| 91-100         | 3         | 0.29%   |
| 41-50          | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 316       | 31.51%  |
| 51-100        | 283       | 28.22%  |
| 101-120       | 235       | 23.43%  |
| 161-240       | 76        | 7.58%   |
| More than 240 | 33        | 3.29%   |
| Unknown       | 33        | 3.29%   |
| 1-50          | 27        | 2.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 732       | 76.41%  |
| 2     | 162       | 16.91%  |
| 0     | 54        | 5.64%   |
| 3     | 7         | 0.73%   |
| 4     | 3         | 0.31%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 517       | 37.6%   |
| Intel                                  | 481       | 34.98%  |
| Qualcomm Atheros                       | 155       | 11.27%  |
| Broadcom                               | 55        | 4%      |
| MEDIATEK                               | 24        | 1.75%   |
| Ralink                                 | 13        | 0.95%   |
| Nvidia                                 | 13        | 0.95%   |
| Broadcom Limited                       | 13        | 0.95%   |
| Marvell Technology Group               | 12        | 0.87%   |
| ASIX Electronics                       | 9         | 0.65%   |
| TP-Link                                | 7         | 0.51%   |
| Ralink Technology                      | 6         | 0.44%   |
| DisplayLink                            | 6         | 0.44%   |
| Samsung Electronics                    | 5         | 0.36%   |
| Microsoft                              | 5         | 0.36%   |
| JMicron Technology                     | 4         | 0.29%   |
| ASUSTek Computer                       | 4         | 0.29%   |
| Sierra Wireless                        | 3         | 0.22%   |
| Mellanox Technologies                  | 3         | 0.22%   |
| Xiaomi                                 | 2         | 0.15%   |
| U-Blox                                 | 2         | 0.15%   |
| Qualcomm                               | 2         | 0.15%   |
| OPPO Electronics                       | 2         | 0.15%   |
| NetGear                                | 2         | 0.15%   |
| Lenovo                                 | 2         | 0.15%   |
| IMC Networks                           | 2         | 0.15%   |
| Ericsson Business Mobile Networks      | 2         | 0.15%   |
| Aquantia                               | 2         | 0.15%   |
| U.S. Robotics                          | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| SEGGER                                 | 1         | 0.07%   |
| Qualcomm Atheros Communications        | 1         | 0.07%   |
| Pulse-Eight                            | 1         | 0.07%   |
| Prolific Technology                    | 1         | 0.07%   |
| Motorola PCS                           | 1         | 0.07%   |
| Microchip Technology                   | 1         | 0.07%   |
| Micro Star International               | 1         | 0.07%   |
| Linksys                                | 1         | 0.07%   |
| Lego Group                             | 1         | 0.07%   |
| Insyde Software                        | 1         | 0.07%   |
| ICS Advent                             | 1         | 0.07%   |
| Huawei Technologies                    | 1         | 0.07%   |
| HMD Global                             | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |
| Fibocom                                | 1         | 0.07%   |
| D-Link System                          | 1         | 0.07%   |
| D-Link                                 | 1         | 0.07%   |
| Chelsio Communications                 | 1         | 0.07%   |
| AVM                                    | 1         | 0.07%   |
| American Megatrends                    | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 317       | 19.81%  |
| Intel Wi-Fi 6 AX200                                               | 57        | 3.56%   |
| Intel Wi-Fi 6 AX201                                               | 52        | 3.25%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 47        | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 35        | 2.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 31        | 1.94%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 29        | 1.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 27        | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 1.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 1.44%   |
| Intel Wireless 8265 / 8275                                        | 22        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 19        | 1.19%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 19        | 1.19%   |
| Intel I211 Gigabit Network Connection                             | 19        | 1.19%   |
| Intel Wireless 7260                                               | 18        | 1.13%   |
| Intel Wireless 3165                                               | 18        | 1.13%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18        | 1.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 17        | 1.06%   |
| Intel Wireless 8260                                               | 17        | 1.06%   |
| Intel Wireless 7265                                               | 17        | 1.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 16        | 1%      |
| Intel Comet Lake PCH CNVi WiFi                                    | 15        | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 15        | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 14        | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 13        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 12        | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 12        | 0.75%   |
| Intel Ethernet Connection (2) I219-V                              | 12        | 0.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 10        | 0.63%   |
| Realtek Killer E3000 2.5GbE Controller                            | 10        | 0.63%   |
| Intel Ethernet Controller I225-V                                  | 10        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 10        | 0.63%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 10        | 0.63%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 9         | 0.56%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 9         | 0.56%   |
| Intel Wireless-AC 9260                                            | 9         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.5%    |
| Intel 82574L Gigabit Network Connection                           | 8         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.44%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.44%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 0.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 7         | 0.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.44%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 6         | 0.38%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.38%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.38%   |
| Intel Ethernet Connection (13) I219-V                             | 6         | 0.38%   |
| Intel Centrino Wireless-N 2230                                    | 6         | 0.38%   |
| Intel 82579V Gigabit Network Connection                           | 6         | 0.38%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 6         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 379       | 49.54%  |
| Realtek Semiconductor           | 143       | 18.69%  |
| Qualcomm Atheros                | 120       | 15.69%  |
| Broadcom                        | 36        | 4.71%   |
| MEDIATEK                        | 24        | 3.14%   |
| Ralink                          | 13        | 1.7%    |
| Broadcom Limited                | 10        | 1.31%   |
| TP-Link                         | 7         | 0.92%   |
| Ralink Technology               | 6         | 0.78%   |
| Microsoft                       | 4         | 0.52%   |
| ASUSTek Computer                | 4         | 0.52%   |
| Sierra Wireless                 | 3         | 0.39%   |
| NetGear                         | 2         | 0.26%   |
| Marvell Technology Group        | 2         | 0.26%   |
| IMC Networks                    | 2         | 0.26%   |
| U.S. Robotics                   | 1         | 0.13%   |
| Qualcomm Atheros Communications | 1         | 0.13%   |
| Qualcomm                        | 1         | 0.13%   |
| Micro Star International        | 1         | 0.13%   |
| Linksys                         | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| Fibocom                         | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |
| D-Link                          | 1         | 0.13%   |
| AVM                             | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 57        | 7.4%    |
| Intel Wi-Fi 6 AX201                                            | 52        | 6.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 31        | 4.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 29        | 3.77%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 3.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 2.99%   |
| Intel Wireless 8265 / 8275                                     | 22        | 2.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 19        | 2.47%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 19        | 2.47%   |
| Intel Wireless 7260                                            | 18        | 2.34%   |
| Intel Wireless 3165                                            | 18        | 2.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18        | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 17        | 2.21%   |
| Intel Wireless 8260                                            | 17        | 2.21%   |
| Intel Wireless 7265                                            | 17        | 2.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 16        | 2.08%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 15        | 1.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 14        | 1.82%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 13        | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 12        | 1.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 11        | 1.43%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 10        | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 10        | 1.3%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 9         | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 1.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9         | 1.17%   |
| Intel Wireless-AC 9260                                         | 9         | 1.17%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 0.91%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 7         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 0.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 7         | 0.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 0.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 0.78%   |
| Intel Centrino Wireless-N 2230                                 | 6         | 0.78%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 6         | 0.78%   |
| Intel Wireless 3160                                            | 5         | 0.65%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 4         | 0.52%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 0.52%   |
| Realtek 802.11ac NIC                                           | 4         | 0.52%   |
| Microsoft XBOX ACC                                             | 4         | 0.52%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 4         | 0.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 0.52%   |
| TP-Link 802.11ac WLAN Adapter                                  | 3         | 0.39%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.39%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 3         | 0.39%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 3         | 0.39%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 3         | 0.39%   |
| MEDIATEK MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 3         | 0.39%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 3         | 0.39%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 0.39%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 3         | 0.39%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.39%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 0.26%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 2         | 0.26%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 0.26%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 0.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 442       | 55.67%  |
| Intel                                  | 207       | 26.07%  |
| Qualcomm Atheros                       | 48        | 6.05%   |
| Broadcom                               | 29        | 3.65%   |
| Nvidia                                 | 13        | 1.64%   |
| Marvell Technology Group               | 10        | 1.26%   |
| ASIX Electronics                       | 9         | 1.13%   |
| DisplayLink                            | 6         | 0.76%   |
| Samsung Electronics                    | 5         | 0.63%   |
| JMicron Technology                     | 4         | 0.5%    |
| Broadcom Limited                       | 3         | 0.38%   |
| Xiaomi                                 | 2         | 0.25%   |
| OPPO Electronics                       | 2         | 0.25%   |
| Mellanox Technologies                  | 2         | 0.25%   |
| Lenovo                                 | 2         | 0.25%   |
| Aquantia                               | 2         | 0.25%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.13%   |
| Qualcomm                               | 1         | 0.13%   |
| Microsoft                              | 1         | 0.13%   |
| Insyde Software                        | 1         | 0.13%   |
| ICS Advent                             | 1         | 0.13%   |
| HMD Global                             | 1         | 0.13%   |
| Chelsio Communications                 | 1         | 0.13%   |
| American Megatrends                    | 1         | 0.13%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 317       | 38.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 47        | 5.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 35        | 4.28%   |
| Realtek RTL8125 2.5GbE Controller                                              | 27        | 3.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 24        | 2.94%   |
| Intel I211 Gigabit Network Connection                                          | 19        | 2.33%   |
| Intel Ethernet Connection (2) I219-V                                           | 12        | 1.47%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 10        | 1.22%   |
| Intel Ethernet Controller I225-V                                               | 10        | 1.22%   |
| Intel Ethernet Connection I217-V                                               | 10        | 1.22%   |
| Intel Ethernet Connection (6) I219-V                                           | 10        | 1.22%   |
| Intel Ethernet Connection (2) I219-LM                                          | 9         | 1.1%    |
| Intel Ethernet Connection (7) I219-LM                                          | 8         | 0.98%   |
| Intel Ethernet Connection (4) I219-LM                                          | 8         | 0.98%   |
| Intel 82574L Gigabit Network Connection                                        | 8         | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 7         | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 7         | 0.86%   |
| Intel Ethernet Connection I217-LM                                              | 7         | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 7         | 0.86%   |
| Intel Ethernet Connection I219-LM                                              | 6         | 0.73%   |
| Intel Ethernet Connection (4) I219-V                                           | 6         | 0.73%   |
| Intel Ethernet Connection (13) I219-V                                          | 6         | 0.73%   |
| Intel 82579V Gigabit Network Connection                                        | 6         | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 5         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 5         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 0.61%   |
| Intel I210 Gigabit Network Connection                                          | 5         | 0.61%   |
| Intel Ethernet Connection (6) I219-LM                                          | 5         | 0.61%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                              | 5         | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 0.61%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 4         | 0.49%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 4         | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 4         | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.49%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 0.49%   |
| Intel Ethernet Connection (7) I219-V                                           | 4         | 0.49%   |
| Intel Ethernet Connection (2) I218-V                                           | 4         | 0.49%   |
| DisplayLink Dell Universal Dock D6000                                          | 4         | 0.49%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 3         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 3         | 0.37%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 3         | 0.37%   |
| Nvidia MCP77 Ethernet                                                          | 3         | 0.37%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 3         | 0.37%   |
| Intel Ethernet Controller X550                                                 | 3         | 0.37%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.37%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 0.37%   |
| Intel Ethernet Connection (14) I219-V                                          | 3         | 0.37%   |
| Intel Ethernet Connection (13) I219-LM                                         | 3         | 0.37%   |
| Intel Ethernet Connection (11) I219-LM                                         | 3         | 0.37%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 3         | 0.37%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 0.24%   |
| Realtek Realtek Ethernet controller                                            | 2         | 0.24%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.24%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 2         | 0.24%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.24%   |
| OPPO realme X50 5G                                                             | 2         | 0.24%   |
| Nvidia MCP61 Ethernet                                                          | 2         | 0.24%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 748       | 49.77%  |
| WiFi     | 742       | 49.37%  |
| Modem    | 10        | 0.67%   |
| Unknown  | 3         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 566       | 58.35%  |
| Ethernet | 404       | 41.65%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 482       | 50.63%  |
| 1     | 401       | 42.12%  |
| 0     | 36        | 3.78%   |
| 3     | 27        | 2.84%   |
| 4     | 3         | 0.32%   |
| 5     | 2         | 0.21%   |
| 8     | 1         | 0.11%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 672       | 70.44%  |
| Yes  | 282       | 29.56%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 339       | 52.31%  |
| Realtek Semiconductor           | 70        | 10.8%   |
| Qualcomm Atheros Communications | 58        | 8.95%   |
| IMC Networks                    | 34        | 5.25%   |
| Cambridge Silicon Radio         | 34        | 5.25%   |
| Lite-On Technology              | 19        | 2.93%   |
| Broadcom                        | 18        | 2.78%   |
| Foxconn / Hon Hai               | 15        | 2.31%   |
| Apple                           | 14        | 2.16%   |
| ASUSTek Computer                | 9         | 1.39%   |
| Realtek                         | 6         | 0.93%   |
| Ralink                          | 6         | 0.93%   |
| Dell                            | 6         | 0.93%   |
| Toshiba                         | 5         | 0.77%   |
| MediaTek                        | 3         | 0.46%   |
| Marvell Semiconductor           | 2         | 0.31%   |
| TRENDnet                        | 1         | 0.15%   |
| TP-Link                         | 1         | 0.15%   |
| Ralink Technology               | 1         | 0.15%   |
| Opticis                         | 1         | 0.15%   |
| Micro Star International        | 1         | 0.15%   |
| Logitech                        | 1         | 0.15%   |
| Hewlett-Packard                 | 1         | 0.15%   |
| Foxconn International           | 1         | 0.15%   |
| Belkin Components               | 1         | 0.15%   |
| Unknown                         | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 94        | 14.48%  |
| Intel AX201 Bluetooth                               | 88        | 13.56%  |
| Intel AX200 Bluetooth                               | 53        | 8.17%   |
| Realtek Bluetooth Radio                             | 45        | 6.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 42        | 6.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 34        | 5.24%   |
| Qualcomm Atheros  Bluetooth Device                  | 27        | 4.16%   |
| Intel AX210 Bluetooth                               | 18        | 2.77%   |
| Intel Bluetooth Device                              | 16        | 2.47%   |
| IMC Networks Wireless_Device                        | 13        | 2%      |
| Realtek 802.11ac WLAN Adapter                       | 12        | 1.85%   |
| IMC Networks Bluetooth Radio                        | 11        | 1.69%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 1.54%   |
| Realtek  Bluetooth 4.2 Adapter                      | 9         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 9         | 1.39%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 1.23%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 1.08%   |
| Realtek Bluetooth Radio                             | 6         | 0.92%   |
| Ralink RT3290 Bluetooth                             | 6         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.92%   |
| Apple Bluetooth USB Host Controller                 | 6         | 0.92%   |
| Apple Bluetooth Host Controller                     | 6         | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.77%   |
| Lite-On Bluetooth Device                            | 5         | 0.77%   |
| IMC Networks Bluetooth Device                       | 5         | 0.77%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 0.77%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.77%   |
| Toshiba Bluetooth Device                            | 4         | 0.62%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 3         | 0.46%   |
| MediaTek Wireless_Device                            | 3         | 0.46%   |
| Dell Wireless 365 Bluetooth                         | 3         | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.46%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3         | 0.46%   |
| ASUS ASUS USB-BT500                                 | 3         | 0.46%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.31%   |
| Marvell Bluetooth and Wireless LAN Composite        | 2         | 0.31%   |
| Lite-On Wireless_Device                             | 2         | 0.31%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 2         | 0.31%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.31%   |
| IMC Networks Bluetooth USB Host Controller          | 2         | 0.31%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.31%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 2         | 0.31%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.31%   |
| Broadcom BCM2070 Bluetooth Device                   | 2         | 0.31%   |
| TRENDnet TBW-108UB USB Adapter                      | 1         | 0.15%   |
| TP-Link UB500 Adapter                               | 1         | 0.15%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.15%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.15%   |
| Realtek Bluetooth 5.1 Radio                         | 1         | 0.15%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.15%   |
| Qualcomm Atheros Bluetooth (AR3011)                 | 1         | 0.15%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.15%   |
| Opticis Bluetooth Radio                             | 1         | 0.15%   |
| Micro Star International Bluetooth Device           | 1         | 0.15%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.15%   |
| Lite-On BCM20702A0                                  | 1         | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 667       | 53.4%   |
| AMD                                          | 258       | 20.66%  |
| Nvidia                                       | 228       | 18.25%  |
| C-Media Electronics                          | 17        | 1.36%   |
| Logitech                                     | 10        | 0.8%    |
| Corsair                                      | 6         | 0.48%   |
| Creative Labs                                | 5         | 0.4%    |
| Plantronics                                  | 4         | 0.32%   |
| Texas Instruments                            | 3         | 0.24%   |
| Kingston Technology                          | 3         | 0.24%   |
| GN Netcom                                    | 3         | 0.24%   |
| Generalplus Technology                       | 3         | 0.24%   |
| XMOS                                         | 2         | 0.16%   |
| SteelSeries ApS                              | 2         | 0.16%   |
| Realtek Semiconductor                        | 2         | 0.16%   |
| Razer USA                                    | 2         | 0.16%   |
| Micro Star International                     | 2         | 0.16%   |
| Lenovo                                       | 2         | 0.16%   |
| Creative Technology                          | 2         | 0.16%   |
| ASUSTek Computer                             | 2         | 0.16%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.08%   |
| Zhaoxin                                      | 1         | 0.08%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.08%   |
| Syntek                                       | 1         | 0.08%   |
| Sennheiser Communications                    | 1         | 0.08%   |
| Samsung Electronics                          | 1         | 0.08%   |
| PreSonus Audio Electronics                   | 1         | 0.08%   |
| Nektar                                       | 1         | 0.08%   |
| Nam Tai E&E Products                         | 1         | 0.08%   |
| Medeli Electronics                           | 1         | 0.08%   |
| Huawei Technologies                          | 1         | 0.08%   |
| Hewlett-Packard                              | 1         | 0.08%   |
| Giga-Byte Technology                         | 1         | 0.08%   |
| Focusrite-Novation                           | 1         | 0.08%   |
| FIFINE Microphones                           | 1         | 0.08%   |
| Ensoniq                                      | 1         | 0.08%   |
| Elgato Systems                               | 1         | 0.08%   |
| DigiTech                                     | 1         | 0.08%   |
| Cambridge Silicon Radio                      | 1         | 0.08%   |
| Bose                                         | 1         | 0.08%   |
| BEHRINGER International                      | 1         | 0.08%   |
| Audio-Technica                               | 1         | 0.08%   |
| Audient                                      | 1         | 0.08%   |
| Astro Gaming                                 | 1         | 0.08%   |
| Arturia                                      | 1         | 0.08%   |
| Apple                                        | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 98        | 6.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 72        | 4.84%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 70        | 4.7%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 66        | 4.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 56        | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 50        | 3.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 43        | 2.89%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 39        | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 33        | 2.22%   |
| Intel Cannon Lake PCH cAVS                                                                        | 31        | 2.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 1.88%   |
| Nvidia Audio device                                                                               | 27        | 1.81%   |
| AMD FCH Azalia Controller                                                                         | 27        | 1.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 26        | 1.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 26        | 1.75%   |
| Intel 8 Series HD Audio Controller                                                                | 26        | 1.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 26        | 1.75%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 25        | 1.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 24        | 1.61%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 24        | 1.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 20        | 1.34%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 19        | 1.28%   |
| Intel Comet Lake PCH cAVS                                                                         | 19        | 1.28%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 18        | 1.21%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 17        | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 16        | 1.08%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 15        | 1.01%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 15        | 1.01%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 14        | 0.94%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 13        | 0.87%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 13        | 0.87%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 0.81%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 12        | 0.81%   |
| Nvidia High Definition Audio Controller                                                           | 11        | 0.74%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 0.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 11        | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 10        | 0.67%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 0.67%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 10        | 0.67%   |
| AMD Navi 10 HDMI Audio                                                                            | 10        | 0.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 0.6%    |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 9         | 0.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 0.6%    |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 9         | 0.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 0.6%    |
| AMD High Definition Audio Controller                                                              | 9         | 0.6%    |
| Nvidia TU116 High Definition Audio Controller                                                     | 8         | 0.54%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 8         | 0.54%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 0.54%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 0.54%   |
| Intel 200 Series PCH HD Audio                                                                     | 8         | 0.54%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.54%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 7         | 0.47%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 0.47%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 7         | 0.47%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 7         | 0.47%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 138       | 25.84%  |
| SK Hynix            | 101       | 18.91%  |
| Micron Technology   | 68        | 12.73%  |
| Kingston            | 55        | 10.3%   |
| Crucial             | 26        | 4.87%   |
| Corsair             | 25        | 4.68%   |
| Unknown             | 21        | 3.93%   |
| G.Skill             | 17        | 3.18%   |
| Ramaxel Technology  | 14        | 2.62%   |
| Unknown (ABCD)      | 11        | 2.06%   |
| A-DATA Technology   | 10        | 1.87%   |
| Team                | 6         | 1.12%   |
| Nanya Technology    | 5         | 0.94%   |
| Smart               | 4         | 0.75%   |
| Patriot             | 4         | 0.75%   |
| Hewlett-Packard     | 3         | 0.56%   |
| Elpida              | 3         | 0.56%   |
| PNY                 | 2         | 0.37%   |
| Kllisre             | 2         | 0.37%   |
| GOODRAM             | 2         | 0.37%   |
| GeIL                | 2         | 0.37%   |
| AMD                 | 2         | 0.37%   |
| Unknown             | 2         | 0.37%   |
| Wilk                | 1         | 0.19%   |
| V-Color             | 1         | 0.19%   |
| Transcend           | 1         | 0.19%   |
| TIMETEC             | 1         | 0.19%   |
| Silicon Power       | 1         | 0.19%   |
| Shenzhen WODPOSIT   | 1         | 0.19%   |
| SanMax              | 1         | 0.19%   |
| Multilaser          | 1         | 0.19%   |
| Kingmax             | 1         | 0.19%   |
| fef5                | 1         | 0.19%   |
| ASint Technology    | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 10        | 1.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s          | 10        | 1.76%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s         | 8         | 1.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s    | 8         | 1.41%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s          | 7         | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s          | 7         | 1.23%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s          | 7         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s           | 7         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s  | 6         | 1.05%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s         | 5         | 0.88%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s         | 4         | 0.7%    |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                   | 4         | 0.7%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s          | 4         | 0.7%    |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s         | 4         | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s          | 4         | 0.7%    |
| SK Hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s        | 3         | 0.53%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s      | 3         | 0.53%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s         | 3         | 0.53%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s     | 3         | 0.53%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                   | 3         | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s       | 3         | 0.53%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s          | 3         | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s          | 3         | 0.53%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 3         | 0.53%   |
| Samsung RAM M471A1G44BB0-CWE 8192MB SODIMM DDR4 3200MT/s       | 3         | 0.53%   |
| Samsung RAM M425R4GA3BB0-CQKOD 32GB SODIMM 4800MT/s            | 3         | 0.53%   |
| Ramaxel RAM RMSA3260NA78HAF-2666 8GB SODIMM DDR4 2667MT/s      | 3         | 0.53%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s          | 3         | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s          | 3         | 0.53%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 3         | 0.53%   |
| Unknown RAM Module 4GB SODIMM DDR3                             | 2         | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 2         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR3                             | 2         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 2         | 0.35%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s            | 2         | 0.35%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                     | 2         | 0.35%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s          | 2         | 0.35%   |
| SK Hynix RAM Module 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.35%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 3200MT/s                  | 2         | 0.35%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.35%   |
| SK Hynix RAM HMCG88MEBSA092N 32GB SODIMM 4800MT/s              | 2         | 0.35%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s     | 2         | 0.35%   |
| SK Hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.35%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s   | 2         | 0.35%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16384MB SODIMM DDR4 2667MT/s     | 2         | 0.35%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.35%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s         | 2         | 0.35%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s      | 2         | 0.35%   |
| SK Hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s | 2         | 0.35%   |
| SK Hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s | 2         | 0.35%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s          | 2         | 0.35%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s       | 2         | 0.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s          | 2         | 0.35%   |
| Samsung RAM M425R2GA3BB0-CQKOD 16GB SODIMM 4800MT/s            | 2         | 0.35%   |
| Samsung RAM M391A2K43BB1-CTD 16384MB DIMM DDR4 3600MT/s        | 2         | 0.35%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s   | 2         | 0.35%   |
| Samsung RAM K4A8G165WC-BCTD 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.35%   |
| Ramaxel RAM RMT3170MN68F9F1600 4GB SODIMM DDR3 1600MT/s        | 2         | 0.35%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s        | 2         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 275       | 58.89%  |
| DDR3    | 107       | 22.91%  |
| LPDDR4  | 40        | 8.57%   |
| Unknown | 18        | 3.85%   |
| LPDDR3  | 13        | 2.78%   |
| SDRAM   | 7         | 1.5%    |
| DDR2    | 7         | 1.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 287       | 61.32%  |
| DIMM         | 114       | 24.36%  |
| Row Of Chips | 61        | 13.03%  |
| Unknown      | 4         | 0.85%   |
| RIMM         | 1         | 0.21%   |
| FB-DIMM      | 1         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 215       | 41.83%  |
| 4096   | 144       | 28.02%  |
| 16384  | 78        | 15.18%  |
| 2048   | 35        | 6.81%   |
| 32768  | 34        | 6.61%   |
| 1024   | 5         | 0.97%   |
| 6144   | 2         | 0.39%   |
| 131072 | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 127       | 25.71%  |
| 2667    | 89        | 18.02%  |
| 1600    | 85        | 17.21%  |
| 2400    | 39        | 7.89%   |
| 2133    | 24        | 4.86%   |
| 4267    | 18        | 3.64%   |
| 1333    | 15        | 3.04%   |
| 3600    | 13        | 2.63%   |
| 4800    | 11        | 2.23%   |
| 1867    | 8         | 1.62%   |
| 3266    | 7         | 1.42%   |
| 1334    | 7         | 1.42%   |
| 3466    | 6         | 1.21%   |
| 2666    | 5         | 1.01%   |
| Unknown | 5         | 1.01%   |
| 4266    | 4         | 0.81%   |
| 2933    | 4         | 0.81%   |
| 4199    | 3         | 0.61%   |
| 3000    | 3         | 0.61%   |
| 1066    | 3         | 0.61%   |
| 667     | 3         | 0.61%   |
| 1866    | 2         | 0.4%    |
| 1067    | 2         | 0.4%    |
| 800     | 2         | 0.4%    |
| 4600    | 1         | 0.2%    |
| 4000    | 1         | 0.2%    |
| 3666    | 1         | 0.2%    |
| 3533    | 1         | 0.2%    |
| 3467    | 1         | 0.2%    |
| 3400    | 1         | 0.2%    |
| 3100    | 1         | 0.2%    |
| 1800    | 1         | 0.2%    |
| 400     | 1         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 31.58%  |
| Samsung Electronics   | 5         | 26.32%  |
| Brother Industries    | 4         | 21.05%  |
| Canon                 | 3         | 15.79%  |
| Lexmark International | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung SCX-4600 Series                               | 1         | 5%      |
| Samsung ML-216x Series Laser Printer                  | 1         | 5%      |
| Samsung Composite Device                              | 1         | 5%      |
| Samsung C48x Series Color Laser Multifunction Printer | 1         | 5%      |
| Samsung C43x Series                                   | 1         | 5%      |
| Lexmark International B2442dw                         | 1         | 5%      |
| HP OfficeJet 8700                                     | 1         | 5%      |
| HP OfficeJet 5500 series                              | 1         | 5%      |
| HP OfficeJet 3830 series                              | 1         | 5%      |
| HP LaserJet M14-M17                                   | 1         | 5%      |
| HP DeskJet 2700 series                                | 1         | 5%      |
| HP DeskJet 1110 series                                | 1         | 5%      |
| Canon MF632C/634C                                     | 1         | 5%      |
| Canon MF4320-4350                                     | 1         | 5%      |
| Canon MF3110                                          | 1         | 5%      |
| Canon iR2004/2204 UFRII LT                            | 1         | 5%      |
| Brother MFC-J485DW                                    | 1         | 5%      |
| Brother HL-1440 Laser Printer                         | 1         | 5%      |
| Brother HL-1200 series                                | 1         | 5%      |
| Brother DCP-1510                                      | 1         | 5%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 220 | 1         | 33.33%  |
| Canon CanoScan LiDE 200 | 1         | 33.33%  |
| Canon CanoScan LiDE 100 | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 108       | 17.36%  |
| IMC Networks                           | 61        | 9.81%   |
| Microdia                               | 52        | 8.36%   |
| Acer                                   | 48        | 7.72%   |
| Realtek Semiconductor                  | 45        | 7.23%   |
| Quanta                                 | 42        | 6.75%   |
| Logitech                               | 42        | 6.75%   |
| Sunplus Innovation Technology          | 39        | 6.27%   |
| Syntek                                 | 26        | 4.18%   |
| Cheng Uei Precision Industry (Foxlink) | 21        | 3.38%   |
| Luxvisions Innotech Limited            | 18        | 2.89%   |
| Suyin                                  | 15        | 2.41%   |
| Lite-On Technology                     | 13        | 2.09%   |
| Apple                                  | 13        | 2.09%   |
| Samsung Electronics                    | 9         | 1.45%   |
| Alcor Micro                            | 9         | 1.45%   |
| Silicon Motion                         | 6         | 0.96%   |
| Microsoft                              | 5         | 0.8%    |
| Importek                               | 5         | 0.8%    |
| Ricoh                                  | 4         | 0.64%   |
| USB Camera                             | 3         | 0.48%   |
| Sonix Technology                       | 3         | 0.48%   |
| Generalplus Technology                 | 3         | 0.48%   |
| Z-Star Microelectronics                | 2         | 0.32%   |
| Razer USA                              | 2         | 0.32%   |
| Jieli Technology                       | 2         | 0.32%   |
| Intel                                  | 2         | 0.32%   |
| Guillemot                              | 2         | 0.32%   |
| Y Media                                | 1         | 0.16%   |
| WCM_USB                                | 1         | 0.16%   |
| WaveRider Communications               | 1         | 0.16%   |
| Trust                                  | 1         | 0.16%   |
| SunplusIT                              | 1         | 0.16%   |
| Sony                                   | 1         | 0.16%   |
| ShineTech                              | 1         | 0.16%   |
| Primax Electronics                     | 1         | 0.16%   |
| Pixart Imaging                         | 1         | 0.16%   |
| MacroSilicon                           | 1         | 0.16%   |
| lihappe8                               | 1         | 0.16%   |
| Lenovo                                 | 1         | 0.16%   |
| Hewlett-Packard                        | 1         | 0.16%   |
| HD USB Camera                          | 1         | 0.16%   |
| Google                                 | 1         | 0.16%   |
| GEMBIRD                                | 1         | 0.16%   |
| Cubeternet                             | 1         | 0.16%   |
| Creative Technology                    | 1         | 0.16%   |
| Arkmicro Technologies                  | 1         | 0.16%   |
| ALi                                    | 1         | 0.16%   |
| 2M UVC CAMERA                          | 1         | 0.16%   |
| Unknown                                | 1         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 31        | 4.94%   |
| Microdia Integrated_Webcam_HD                        | 29        | 4.62%   |
| IMC Networks Integrated Camera                       | 17        | 2.71%   |
| Acer Integrated Camera                               | 17        | 2.71%   |
| Realtek Integrated_Webcam_HD                         | 16        | 2.55%   |
| Logitech HD Pro Webcam C920                          | 15        | 2.39%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 14        | 2.23%   |
| Syntek Integrated Camera                             | 12        | 1.91%   |
| Chicony HD WebCam                                    | 11        | 1.75%   |
| Quanta HD User Facing                                | 10        | 1.59%   |
| Chicony HP HD Camera                                 | 10        | 1.59%   |
| Sunplus Integrated_Webcam_HD                         | 9         | 1.43%   |
| Samsung Galaxy A5 (MTP)                              | 9         | 1.43%   |
| Chicony TOSHIBA Web Camera - HD                      | 8         | 1.27%   |
| Syntek Lenovo EasyCamera                             | 7         | 1.11%   |
| Sunplus HK 1080P K20Pro                              | 7         | 1.11%   |
| Logitech Webcam C270                                 | 7         | 1.11%   |
| Cheng Uei Precision Industry (Foxlink) Webcam        | 7         | 1.11%   |
| Quanta HP Wide Vision HD Camera                      | 6         | 0.96%   |
| Quanta HP HD Camera                                  | 6         | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 6         | 0.96%   |
| IMC Networks HD Camera                               | 6         | 0.96%   |
| Realtek Integrated Webcam                            | 5         | 0.8%    |
| Realtek HD WebCam                                    | 5         | 0.8%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 5         | 0.8%    |
| Luxvisions Innotech Limited HP HD Camera             | 5         | 0.8%    |
| IMC Networks HP TrueVision HD Camera                 | 5         | 0.8%    |
| Chicony USB2.0 HD UVC WebCam                         | 5         | 0.8%    |
| Apple iPhone 5/5C/5S/6/SE                            | 5         | 0.8%    |
| Alcor Micro SHUNCCM2MP                               | 5         | 0.8%    |
| Acer Lenovo EasyCamera                               | 5         | 0.8%    |
| Syntek EasyCamera                                    | 4         | 0.64%   |
| Sunplus HD WebCam                                    | 4         | 0.64%   |
| Quanta HP Webcam                                     | 4         | 0.64%   |
| Microdia Webcam Vitade AF                            | 4         | 0.64%   |
| Logitech C922 Pro Stream Webcam                      | 4         | 0.64%   |
| Chicony HP TrueVision HD Camera                      | 4         | 0.64%   |
| Acer HD Camera                                       | 4         | 0.64%   |
| Acer BisonCam, NB Pro                                | 4         | 0.64%   |
| USB Camera USB Camera                                | 3         | 0.48%   |
| Suyin HP TrueVision HD                               | 3         | 0.48%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 3         | 0.48%   |
| Sonix USB2.0 HD UVC WebCam                           | 3         | 0.48%   |
| Realtek USB Camera                                   | 3         | 0.48%   |
| Realtek HP Webcam                                    | 3         | 0.48%   |
| Quanta HD Webcam                                     | 3         | 0.48%   |
| Luxvisions Innotech Limited Integrated Camera        | 3         | 0.48%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 3         | 0.48%   |
| Logitech HD Webcam C525                              | 3         | 0.48%   |
| Lite-On Integrated Camera                            | 3         | 0.48%   |
| Lite-On HP HD Webcam                                 | 3         | 0.48%   |
| Lite-On HP HD Camera                                 | 3         | 0.48%   |
| IMC Networks ov9734_azurewave_camera                 | 3         | 0.48%   |
| Chicony ThinkPad T490 Webcam                         | 3         | 0.48%   |
| Chicony Lenovo EasyCamera                            | 3         | 0.48%   |
| Chicony HP TrueVision HD                             | 3         | 0.48%   |
| Chicony HP HD Webcam                                 | 3         | 0.48%   |
| Chicony HD User Facing                               | 3         | 0.48%   |
| Apple Built-in iSight                                | 3         | 0.48%   |
| Acer Lenovo Integrated Webcam                        | 3         | 0.48%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 47        | 33.1%   |
| Shenzhen Goodix Technology | 34        | 23.94%  |
| Validity Sensors           | 31        | 21.83%  |
| Elan Microelectronics      | 13        | 9.15%   |
| LighTuning Technology      | 7         | 4.93%   |
| AuthenTec                  | 5         | 3.52%   |
| Upek                       | 3         | 2.11%   |
| Focal-systems.Corp         | 1         | 0.7%    |
| Dell                       | 1         | 0.7%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 23        | 16.2%   |
| Unknown                                                                    | 22        | 15.49%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 6.34%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 6.34%   |
| Elan ELAN:ARM-M4                                                           | 9         | 6.34%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 4.93%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 4.23%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 4.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 3.52%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.82%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 2.11%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.11%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.11%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 2.11%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.41%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.41%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 1.41%   |
| Synaptics  WBDI                                                            | 2         | 1.41%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.41%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.7%    |
| Validity Sensors VFS491                                                    | 1         | 0.7%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.7%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.7%    |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.7%    |
| Synaptics WBDI Device                                                      | 1         | 0.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.7%    |
| LighTuning Fingerprint Reader                                              | 1         | 0.7%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.7%    |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.7%    |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.7%    |
| AuthenTec AES2810                                                          | 1         | 0.7%    |
| AuthenTec AES1600                                                          | 1         | 0.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 17        | 56.67%  |
| Alcor Micro           | 10        | 33.33%  |
| Upek                  | 1         | 3.33%   |
| Realtek Semiconductor | 1         | 3.33%   |
| NXP Semiconductors    | 1         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 33.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 20%     |
| Broadcom 58200                                                               | 6         | 20%     |
| Broadcom 5880                                                                | 4         | 13.33%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.33%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 3.33%   |
| NXP Semiconductors PR533                                                     | 1         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 648       | 67.92%  |
| 1     | 250       | 26.21%  |
| 2     | 50        | 5.24%   |
| 3     | 3         | 0.31%   |
| 5     | 2         | 0.21%   |
| 7     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 139       | 38.94%  |
| Graphics card            | 76        | 21.29%  |
| Net/wireless             | 31        | 8.68%   |
| Chipcard                 | 28        | 7.84%   |
| Multimedia controller    | 17        | 4.76%   |
| Bluetooth                | 13        | 3.64%   |
| Sound                    | 11        | 3.08%   |
| Camera                   | 11        | 3.08%   |
| Unassigned class         | 10        | 2.8%    |
| Communication controller | 7         | 1.96%   |
| Storage                  | 6         | 1.68%   |
| Network                  | 3         | 0.84%   |
| Card reader              | 3         | 0.84%   |
| Storage/raid             | 1         | 0.28%   |
| Net/ethernet             | 1         | 0.28%   |

