Linux in Sweden - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Sweden.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Sweden/Desktop/README.md) and [notebooks](/Location/Sweden/Notebook/README.md).

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

Total: 3214

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | NUC7JYB M37316-600          | Mini pc     | [8487059659](https://linux-hardware.org/?probe=8487059659) | Sep 30, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [3f96bd2883](https://linux-hardware.org/?probe=3f96bd2883) | Sep 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [545098d0d2](https://linux-hardware.org/?probe=545098d0d2) | Sep 29, 2023 |
| MSI           | H97 GAMING 3                | Desktop     | [51f3cd7354](https://linux-hardware.org/?probe=51f3cd7354) | Sep 29, 2023 |
| HP            | ZBook Studio G5             | Notebook    | [239b5a3fd5](https://linux-hardware.org/?probe=239b5a3fd5) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [5c38fe5e79](https://linux-hardware.org/?probe=5c38fe5e79) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [c61d70bcfa](https://linux-hardware.org/?probe=c61d70bcfa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [be49c167d0](https://linux-hardware.org/?probe=be49c167d0) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8c585051a3](https://linux-hardware.org/?probe=8c585051a3) | Sep 27, 2023 |
| MSI           | Z77A-S01                    | Desktop     | [277586f152](https://linux-hardware.org/?probe=277586f152) | Sep 27, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f87aee7d8f](https://linux-hardware.org/?probe=f87aee7d8f) | Sep 26, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [7214093885](https://linux-hardware.org/?probe=7214093885) | Sep 26, 2023 |
| Dell          | Latitude E7270              | Notebook    | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| Dell          | Latitude E5270              | Notebook    | [d091c4fa0e](https://linux-hardware.org/?probe=d091c4fa0e) | Sep 24, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [de5a55aa7b](https://linux-hardware.org/?probe=de5a55aa7b) | Sep 23, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [da796376e1](https://linux-hardware.org/?probe=da796376e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LH0... | Convertible | [9b6bbb4b56](https://linux-hardware.org/?probe=9b6bbb4b56) | Sep 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [3889f9ca9d](https://linux-hardware.org/?probe=3889f9ca9d) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [4679088d4e](https://linux-hardware.org/?probe=4679088d4e) | Sep 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [1893bb3992](https://linux-hardware.org/?probe=1893bb3992) | Sep 22, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [ad989ac089](https://linux-hardware.org/?probe=ad989ac089) | Sep 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4d1743c405](https://linux-hardware.org/?probe=4d1743c405) | Sep 20, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [9e6874d35c](https://linux-hardware.org/?probe=9e6874d35c) | Sep 20, 2023 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [51c58cd13a](https://linux-hardware.org/?probe=51c58cd13a) | Sep 19, 2023 |
| ASUSTek       | P8H61-M EVO                 | Desktop     | [64618297ff](https://linux-hardware.org/?probe=64618297ff) | Sep 19, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [002401cab6](https://linux-hardware.org/?probe=002401cab6) | Sep 18, 2023 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [79142d7f53](https://linux-hardware.org/?probe=79142d7f53) | Sep 17, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [10d32d6284](https://linux-hardware.org/?probe=10d32d6284) | Sep 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [293bc3eab9](https://linux-hardware.org/?probe=293bc3eab9) | Sep 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [f3b7f92416](https://linux-hardware.org/?probe=f3b7f92416) | Sep 16, 2023 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [2fa5c8bb34](https://linux-hardware.org/?probe=2fa5c8bb34) | Sep 16, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [efda5ec51a](https://linux-hardware.org/?probe=efda5ec51a) | Sep 15, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [43f6a3bfc1](https://linux-hardware.org/?probe=43f6a3bfc1) | Sep 14, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [dcd2b90824](https://linux-hardware.org/?probe=dcd2b90824) | Sep 14, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [bd161c3850](https://linux-hardware.org/?probe=bd161c3850) | Sep 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [0cdeaab8be](https://linux-hardware.org/?probe=0cdeaab8be) | Sep 13, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [118c76cef1](https://linux-hardware.org/?probe=118c76cef1) | Sep 12, 2023 |
| Samsung       | R530/R730/P590              | Notebook    | [d9bd973c79](https://linux-hardware.org/?probe=d9bd973c79) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | Maximus VI EXTREME          | Desktop     | [e1eea73611](https://linux-hardware.org/?probe=e1eea73611) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9a23215875](https://linux-hardware.org/?probe=9a23215875) | Sep 11, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [4d658a922b](https://linux-hardware.org/?probe=4d658a922b) | Sep 10, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [03b8175690](https://linux-hardware.org/?probe=03b8175690) | Sep 10, 2023 |
| ASUSTek       | TS10                        | Desktop     | [ad867c5e25](https://linux-hardware.org/?probe=ad867c5e25) | Sep 10, 2023 |
| Dell          | Precision M4800             | Notebook    | [ea570fedac](https://linux-hardware.org/?probe=ea570fedac) | Sep 09, 2023 |
| HP            | ProBook x360 11 G3 EE       | Convertible | [03ce2f9b74](https://linux-hardware.org/?probe=03ce2f9b74) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [3857377d7a](https://linux-hardware.org/?probe=3857377d7a) | Sep 09, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [98ba75a25b](https://linux-hardware.org/?probe=98ba75a25b) | Sep 09, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [0c2dda2476](https://linux-hardware.org/?probe=0c2dda2476) | Sep 09, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [b73ef6339a](https://linux-hardware.org/?probe=b73ef6339a) | Sep 08, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [e71f333094](https://linux-hardware.org/?probe=e71f333094) | Sep 07, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [72516e7752](https://linux-hardware.org/?probe=72516e7752) | Sep 07, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [26448cf759](https://linux-hardware.org/?probe=26448cf759) | Sep 07, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [7cbd11709c](https://linux-hardware.org/?probe=7cbd11709c) | Sep 07, 2023 |
| ASUSTek       | X453MA                      | Notebook    | [c48759c297](https://linux-hardware.org/?probe=c48759c297) | Sep 07, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [26a5d8b449](https://linux-hardware.org/?probe=26a5d8b449) | Sep 06, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [6521407977](https://linux-hardware.org/?probe=6521407977) | Sep 06, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [5dca7c7315](https://linux-hardware.org/?probe=5dca7c7315) | Sep 05, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [07429e910f](https://linux-hardware.org/?probe=07429e910f) | Sep 05, 2023 |
| Dell          | Latitude 7440               | Notebook    | [47f28d7b00](https://linux-hardware.org/?probe=47f28d7b00) | Sep 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [27b2ae9d5b](https://linux-hardware.org/?probe=27b2ae9d5b) | Sep 04, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [c8978cf811](https://linux-hardware.org/?probe=c8978cf811) | Sep 03, 2023 |
| Lenovo        | ThinkPad T440 20B7S0RD00    | Notebook    | [af57fd1655](https://linux-hardware.org/?probe=af57fd1655) | Sep 03, 2023 |
| MSI           | MAG B560M MORTAR            | Desktop     | [62ac121b13](https://linux-hardware.org/?probe=62ac121b13) | Sep 03, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [806eed53dc](https://linux-hardware.org/?probe=806eed53dc) | Sep 02, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [377d5352d8](https://linux-hardware.org/?probe=377d5352d8) | Sep 02, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [b6f6192ef9](https://linux-hardware.org/?probe=b6f6192ef9) | Sep 02, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e4a45bf853](https://linux-hardware.org/?probe=e4a45bf853) | Sep 02, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [19bf85f553](https://linux-hardware.org/?probe=19bf85f553) | Sep 01, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [b938dc8500](https://linux-hardware.org/?probe=b938dc8500) | Aug 31, 2023 |
| HP            | ProBook 6360b               | Notebook    | [0dbff9ebb3](https://linux-hardware.org/?probe=0dbff9ebb3) | Aug 30, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [a21f3ba335](https://linux-hardware.org/?probe=a21f3ba335) | Aug 30, 2023 |
| ASUSTek       | P8P67 PRO                   | Desktop     | [3740c90267](https://linux-hardware.org/?probe=3740c90267) | Aug 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [44e7ba057b](https://linux-hardware.org/?probe=44e7ba057b) | Aug 30, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [7c208705e5](https://linux-hardware.org/?probe=7c208705e5) | Aug 29, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6f5a767b7e](https://linux-hardware.org/?probe=6f5a767b7e) | Aug 29, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [577d9d5dc1](https://linux-hardware.org/?probe=577d9d5dc1) | Aug 29, 2023 |
| ASUSTek       | ROG STRIX B660-A GAMING ... | Desktop     | [0be67de1c9](https://linux-hardware.org/?probe=0be67de1c9) | Aug 29, 2023 |
| Lenovo        | B50-30 80ES                 | Notebook    | [96aa7b5683](https://linux-hardware.org/?probe=96aa7b5683) | Aug 29, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [6736188e61](https://linux-hardware.org/?probe=6736188e61) | Aug 26, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [6a55471f69](https://linux-hardware.org/?probe=6a55471f69) | Aug 26, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [f0a3b05a99](https://linux-hardware.org/?probe=f0a3b05a99) | Aug 25, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [f8f097e135](https://linux-hardware.org/?probe=f8f097e135) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [aa3157f519](https://linux-hardware.org/?probe=aa3157f519) | Aug 24, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [8d3738c790](https://linux-hardware.org/?probe=8d3738c790) | Aug 24, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [e11053f833](https://linux-hardware.org/?probe=e11053f833) | Aug 23, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [799390e547](https://linux-hardware.org/?probe=799390e547) | Aug 23, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [3231dcefb4](https://linux-hardware.org/?probe=3231dcefb4) | Aug 22, 2023 |
| HP            | 845A                        | Desktop     | [4a8699daad](https://linux-hardware.org/?probe=4a8699daad) | Aug 22, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b4133748fc](https://linux-hardware.org/?probe=b4133748fc) | Aug 21, 2023 |
| HP            | 212B                        | Desktop     | [ee20bd40d8](https://linux-hardware.org/?probe=ee20bd40d8) | Aug 21, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [83b6cab3cd](https://linux-hardware.org/?probe=83b6cab3cd) | Aug 20, 2023 |
| Dell          | Latitude 3350               | Notebook    | [e86ce20d6d](https://linux-hardware.org/?probe=e86ce20d6d) | Aug 20, 2023 |
| Lenovo        | ThinkPad T440s 20AR003RM... | Notebook    | [d989b68c65](https://linux-hardware.org/?probe=d989b68c65) | Aug 19, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [aa6781c002](https://linux-hardware.org/?probe=aa6781c002) | Aug 18, 2023 |
| ASUSTek       | M3N                         | Notebook    | [7c4b9386db](https://linux-hardware.org/?probe=7c4b9386db) | Aug 18, 2023 |
| ASUSTek       | U38N                        | Notebook    | [0e0f709353](https://linux-hardware.org/?probe=0e0f709353) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [eb44f4dfc1](https://linux-hardware.org/?probe=eb44f4dfc1) | Aug 17, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [91b8c2a5eb](https://linux-hardware.org/?probe=91b8c2a5eb) | Aug 17, 2023 |
| ASUSTek       | P5QL-ASUS-SE                | Desktop     | [3135a88431](https://linux-hardware.org/?probe=3135a88431) | Aug 17, 2023 |
| Alienware     | 07JNH0 A00                  | Desktop     | [2f82c5eb18](https://linux-hardware.org/?probe=2f82c5eb18) | Aug 14, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [369b0195cc](https://linux-hardware.org/?probe=369b0195cc) | Aug 14, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [a47415983e](https://linux-hardware.org/?probe=a47415983e) | Aug 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [f3e1bb3812](https://linux-hardware.org/?probe=f3e1bb3812) | Aug 11, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [483fc71762](https://linux-hardware.org/?probe=483fc71762) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [0a1e2a7f23](https://linux-hardware.org/?probe=0a1e2a7f23) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [742b085257](https://linux-hardware.org/?probe=742b085257) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [836fcda626](https://linux-hardware.org/?probe=836fcda626) | Aug 11, 2023 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [3e208faa6e](https://linux-hardware.org/?probe=3e208faa6e) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f20a32551b](https://linux-hardware.org/?probe=f20a32551b) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| Gigabyte      | H270N-WIFI-CF               | Desktop     | [bd9c532bbc](https://linux-hardware.org/?probe=bd9c532bbc) | Aug 10, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [e323e9cd7e](https://linux-hardware.org/?probe=e323e9cd7e) | Aug 10, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [a3b9be2f56](https://linux-hardware.org/?probe=a3b9be2f56) | Aug 10, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [4d7fbea818](https://linux-hardware.org/?probe=4d7fbea818) | Aug 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [bdc11616d7](https://linux-hardware.org/?probe=bdc11616d7) | Aug 08, 2023 |
| HP            | Unknown                     | Notebook    | [567a10ceb2](https://linux-hardware.org/?probe=567a10ceb2) | Aug 08, 2023 |
| Lenovo        | ThinkPad W510 4391EC4       | Notebook    | [5e9baa223d](https://linux-hardware.org/?probe=5e9baa223d) | Aug 07, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Fujitsu Si... | AMILO Xa 1526               | Notebook    | [3d49205e68](https://linux-hardware.org/?probe=3d49205e68) | Aug 06, 2023 |
| Toshiba       | Satellite C670D-11P         | Notebook    | [a5c49672d6](https://linux-hardware.org/?probe=a5c49672d6) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [e3fd0f4808](https://linux-hardware.org/?probe=e3fd0f4808) | Aug 04, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [f420f3e1e6](https://linux-hardware.org/?probe=f420f3e1e6) | Aug 04, 2023 |
| Dell          | 0K095G A01                  | Desktop     | [ee2fb87d2f](https://linux-hardware.org/?probe=ee2fb87d2f) | Aug 04, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [bd2d5f588f](https://linux-hardware.org/?probe=bd2d5f588f) | Aug 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [508c18e563](https://linux-hardware.org/?probe=508c18e563) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [53c9161fc5](https://linux-hardware.org/?probe=53c9161fc5) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| Dell          | Latitude E7240              | Notebook    | [87a0310cf0](https://linux-hardware.org/?probe=87a0310cf0) | Aug 02, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [e0c07e2d0c](https://linux-hardware.org/?probe=e0c07e2d0c) | Aug 02, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [a06a335d70](https://linux-hardware.org/?probe=a06a335d70) | Aug 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [9fbfc590ad](https://linux-hardware.org/?probe=9fbfc590ad) | Aug 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| HP            | Unknown                     | Notebook    | [a4d8377dfa](https://linux-hardware.org/?probe=a4d8377dfa) | Aug 01, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [c5205f5512](https://linux-hardware.org/?probe=c5205f5512) | Jul 30, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [d8272e8eeb](https://linux-hardware.org/?probe=d8272e8eeb) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d1a4b2769a](https://linux-hardware.org/?probe=d1a4b2769a) | Jul 29, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [436e1e4e01](https://linux-hardware.org/?probe=436e1e4e01) | Jul 29, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [7d5b443b84](https://linux-hardware.org/?probe=7d5b443b84) | Jul 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [1b9bb7c266](https://linux-hardware.org/?probe=1b9bb7c266) | Jul 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [a8e51655da](https://linux-hardware.org/?probe=a8e51655da) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [9cbedced8b](https://linux-hardware.org/?probe=9cbedced8b) | Jul 28, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [1950bcc818](https://linux-hardware.org/?probe=1950bcc818) | Jul 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [80a34d344b](https://linux-hardware.org/?probe=80a34d344b) | Jul 28, 2023 |
| Acer          | Spin SP111-31               | Convertible | [003fa350a2](https://linux-hardware.org/?probe=003fa350a2) | Jul 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S55L00    | Notebook    | [5b3742984b](https://linux-hardware.org/?probe=5b3742984b) | Jul 27, 2023 |
| Lenovo        | 3743 SDK0J40700 WIN 3258... | Desktop     | [546f011b1a](https://linux-hardware.org/?probe=546f011b1a) | Jul 27, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [47e831a79a](https://linux-hardware.org/?probe=47e831a79a) | Jul 26, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4fc2e4c331](https://linux-hardware.org/?probe=4fc2e4c331) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a060c0999b](https://linux-hardware.org/?probe=a060c0999b) | Jul 26, 2023 |
| Lenovo        | ThinkPad E480 20KN001QMX    | Notebook    | [1ff9753d17](https://linux-hardware.org/?probe=1ff9753d17) | Jul 25, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [ac63d4a30c](https://linux-hardware.org/?probe=ac63d4a30c) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fa1cd70a3](https://linux-hardware.org/?probe=9fa1cd70a3) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [1e169f0ba8](https://linux-hardware.org/?probe=1e169f0ba8) | Jul 23, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [52541ec1ed](https://linux-hardware.org/?probe=52541ec1ed) | Jul 23, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [f291f72d81](https://linux-hardware.org/?probe=f291f72d81) | Jul 23, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [bbd3181f1f](https://linux-hardware.org/?probe=bbd3181f1f) | Jul 22, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [9ab47777ca](https://linux-hardware.org/?probe=9ab47777ca) | Jul 21, 2023 |
| HP            | ProBook 4530s               | Notebook    | [450e93a8de](https://linux-hardware.org/?probe=450e93a8de) | Jul 21, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS        | Desktop     | [c3994db136](https://linux-hardware.org/?probe=c3994db136) | Jul 21, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [b1a5c8b10d](https://linux-hardware.org/?probe=b1a5c8b10d) | Jul 20, 2023 |
| HP            | 15                          | Notebook    | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| ASUSTek       | A_F_K20BF                   | Desktop     | [f2ae40130e](https://linux-hardware.org/?probe=f2ae40130e) | Jul 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [805d981913](https://linux-hardware.org/?probe=805d981913) | Jul 19, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [db2a22c2eb](https://linux-hardware.org/?probe=db2a22c2eb) | Jul 19, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b12aa2eb63](https://linux-hardware.org/?probe=b12aa2eb63) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | Notebook    | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | Notebook    | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Dell          | 0MN1TX A01                  | Desktop     | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b29b313957](https://linux-hardware.org/?probe=b29b313957) | Jul 17, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [f4bc253638](https://linux-hardware.org/?probe=f4bc253638) | Jul 17, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e707b1595f](https://linux-hardware.org/?probe=e707b1595f) | Jul 17, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [65a6e11166](https://linux-hardware.org/?probe=65a6e11166) | Jul 17, 2023 |
| MSI           | GF65 Thin 10SER             | Notebook    | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [21950296b4](https://linux-hardware.org/?probe=21950296b4) | Jul 16, 2023 |
| MSI           | B550M-A PRO                 | Desktop     | [0063ae1936](https://linux-hardware.org/?probe=0063ae1936) | Jul 16, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [6758dfb731](https://linux-hardware.org/?probe=6758dfb731) | Jul 15, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [801eb1eb3c](https://linux-hardware.org/?probe=801eb1eb3c) | Jul 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [e790a3c22f](https://linux-hardware.org/?probe=e790a3c22f) | Jul 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [dae11c33ed](https://linux-hardware.org/?probe=dae11c33ed) | Jul 14, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | Notebook    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [30403bcd32](https://linux-hardware.org/?probe=30403bcd32) | Jul 12, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [c3b936e87a](https://linux-hardware.org/?probe=c3b936e87a) | Jul 12, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [cfc5e42de6](https://linux-hardware.org/?probe=cfc5e42de6) | Jul 11, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [d0035bb703](https://linux-hardware.org/?probe=d0035bb703) | Jul 10, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [2992a0aea9](https://linux-hardware.org/?probe=2992a0aea9) | Jul 10, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [57cc83ff44](https://linux-hardware.org/?probe=57cc83ff44) | Jul 10, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [4b33cf2e09](https://linux-hardware.org/?probe=4b33cf2e09) | Jul 09, 2023 |
| IBM           | ThinkPad T43 18714AG        | Notebook    | [c7d3e6a151](https://linux-hardware.org/?probe=c7d3e6a151) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [ecd8f6cdd2](https://linux-hardware.org/?probe=ecd8f6cdd2) | Jul 09, 2023 |
| ASUSTek       | X550VC                      | Notebook    | [0ea27ea171](https://linux-hardware.org/?probe=0ea27ea171) | Jul 09, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| Gigabyte      | MFLP5IP-00                  | Desktop     | [5f28888f0d](https://linux-hardware.org/?probe=5f28888f0d) | Jul 06, 2023 |
| Medion        | ML-210007                   | Notebook    | [192b83694f](https://linux-hardware.org/?probe=192b83694f) | Jul 06, 2023 |
| Medion        | ML-210007                   | Notebook    | [8bc97d58d2](https://linux-hardware.org/?probe=8bc97d58d2) | Jul 06, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [9c0f0d40b9](https://linux-hardware.org/?probe=9c0f0d40b9) | Jul 05, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [348b9a4a73](https://linux-hardware.org/?probe=348b9a4a73) | Jul 05, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [fceaf9bea9](https://linux-hardware.org/?probe=fceaf9bea9) | Jul 04, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CBA... | Notebook    | [b6d0f85342](https://linux-hardware.org/?probe=b6d0f85342) | Jul 04, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [e2c9e04a7c](https://linux-hardware.org/?probe=e2c9e04a7c) | Jul 04, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [50b65edbc0](https://linux-hardware.org/?probe=50b65edbc0) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [e0fc7e357f](https://linux-hardware.org/?probe=e0fc7e357f) | Jul 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [0ca36f92b8](https://linux-hardware.org/?probe=0ca36f92b8) | Jul 03, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [066d1a2fa8](https://linux-hardware.org/?probe=066d1a2fa8) | Jul 03, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [80810e133e](https://linux-hardware.org/?probe=80810e133e) | Jul 02, 2023 |
| Lenovo        | ThinkPad X230 232578G       | Notebook    | [48df5942cf](https://linux-hardware.org/?probe=48df5942cf) | Jul 02, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [f91dbee23b](https://linux-hardware.org/?probe=f91dbee23b) | Jul 02, 2023 |
| Acer          | Predator G9-593             | Notebook    | [127df9999f](https://linux-hardware.org/?probe=127df9999f) | Jul 01, 2023 |
| TrekStor      | YOURBOOK C11B               | Convertible | [8c2340f01f](https://linux-hardware.org/?probe=8c2340f01f) | Jul 01, 2023 |
| Acer          | Predator G9-593             | Notebook    | [d4dca39223](https://linux-hardware.org/?probe=d4dca39223) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a203a588f9](https://linux-hardware.org/?probe=a203a588f9) | Jun 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [7f9164d1e0](https://linux-hardware.org/?probe=7f9164d1e0) | Jun 29, 2023 |
| Acer          | Aspire XC-840               | Desktop     | [76c750aae4](https://linux-hardware.org/?probe=76c750aae4) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | Notebook    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| ASUSTek       | GA35DX                      | Desktop     | [a91acc04b6](https://linux-hardware.org/?probe=a91acc04b6) | Jun 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [cc161cc65b](https://linux-hardware.org/?probe=cc161cc65b) | Jun 28, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [32e4f74711](https://linux-hardware.org/?probe=32e4f74711) | Jun 28, 2023 |
| MSI           | MAG Z790 TOMAHAWK WIFI      | Desktop     | [9450fc030e](https://linux-hardware.org/?probe=9450fc030e) | Jun 27, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [566e7a4396](https://linux-hardware.org/?probe=566e7a4396) | Jun 26, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [165584477b](https://linux-hardware.org/?probe=165584477b) | Jun 25, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [3c8a1b23bb](https://linux-hardware.org/?probe=3c8a1b23bb) | Jun 24, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [e10aa58dda](https://linux-hardware.org/?probe=e10aa58dda) | Jun 24, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [56208916c9](https://linux-hardware.org/?probe=56208916c9) | Jun 23, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [3d506cafad](https://linux-hardware.org/?probe=3d506cafad) | Jun 22, 2023 |
| MSI           | GX60 1AC                    | Notebook    | [8e15fea8cd](https://linux-hardware.org/?probe=8e15fea8cd) | Jun 22, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a7b7b2c413](https://linux-hardware.org/?probe=a7b7b2c413) | Jun 21, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [d4bd011ff9](https://linux-hardware.org/?probe=d4bd011ff9) | Jun 21, 2023 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [30f85c0f2e](https://linux-hardware.org/?probe=30f85c0f2e) | Jun 21, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [1897f5f0cb](https://linux-hardware.org/?probe=1897f5f0cb) | Jun 20, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9e30c629f3](https://linux-hardware.org/?probe=9e30c629f3) | Jun 19, 2023 |
| Gigabyte      | H87N-WIFI                   | Desktop     | [6579287940](https://linux-hardware.org/?probe=6579287940) | Jun 18, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0c5693c658](https://linux-hardware.org/?probe=0c5693c658) | Jun 18, 2023 |
| OEM           | ALDER LAKE JHS64S           | Desktop     | [0eb1dc0b8e](https://linux-hardware.org/?probe=0eb1dc0b8e) | Jun 16, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [b0361fedbc](https://linux-hardware.org/?probe=b0361fedbc) | Jun 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [da6bfc34aa](https://linux-hardware.org/?probe=da6bfc34aa) | Jun 15, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [74a69e5cca](https://linux-hardware.org/?probe=74a69e5cca) | Jun 15, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [a0e0ea6aa1](https://linux-hardware.org/?probe=a0e0ea6aa1) | Jun 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [91af63490c](https://linux-hardware.org/?probe=91af63490c) | Jun 15, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [39d273ec86](https://linux-hardware.org/?probe=39d273ec86) | Jun 15, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [294cbcd9cd](https://linux-hardware.org/?probe=294cbcd9cd) | Jun 14, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [11fa244fa5](https://linux-hardware.org/?probe=11fa244fa5) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Gigabyte      | B85M-D3V-A                  | Desktop     | [bbcb31d079](https://linux-hardware.org/?probe=bbcb31d079) | Jun 14, 2023 |
| MSI           | Z97 GAMING 3                | Desktop     | [ff01549321](https://linux-hardware.org/?probe=ff01549321) | Jun 14, 2023 |
| Dell          | Latitude 7480               | Notebook    | [375fb09bca](https://linux-hardware.org/?probe=375fb09bca) | Jun 14, 2023 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [3a8338d906](https://linux-hardware.org/?probe=3a8338d906) | Jun 13, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [cda9f3da9c](https://linux-hardware.org/?probe=cda9f3da9c) | Jun 13, 2023 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | Notebook    | [93cd1fd89c](https://linux-hardware.org/?probe=93cd1fd89c) | Jun 13, 2023 |
| Dell          | Latitude 3320               | Notebook    | [e467a71dac](https://linux-hardware.org/?probe=e467a71dac) | Jun 12, 2023 |
| Dell          | Latitude 3320               | Notebook    | [ec4f04b63e](https://linux-hardware.org/?probe=ec4f04b63e) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [88fc978934](https://linux-hardware.org/?probe=88fc978934) | Jun 12, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [0b737be0c6](https://linux-hardware.org/?probe=0b737be0c6) | Jun 12, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5f4978fc61](https://linux-hardware.org/?probe=5f4978fc61) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8a3bd0a576](https://linux-hardware.org/?probe=8a3bd0a576) | Jun 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [2838a84809](https://linux-hardware.org/?probe=2838a84809) | Jun 11, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [d58405f7c1](https://linux-hardware.org/?probe=d58405f7c1) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [86b377710d](https://linux-hardware.org/?probe=86b377710d) | Jun 10, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [2c8c27897b](https://linux-hardware.org/?probe=2c8c27897b) | Jun 09, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6a98d856ee](https://linux-hardware.org/?probe=6a98d856ee) | Jun 07, 2023 |
| Dell          | Latitude 3340               | Notebook    | [4ac9bd4101](https://linux-hardware.org/?probe=4ac9bd4101) | Jun 05, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [4d71226d7c](https://linux-hardware.org/?probe=4d71226d7c) | Jun 04, 2023 |
| ASUSTek       | X505BP                      | Notebook    | [f92e294ba0](https://linux-hardware.org/?probe=f92e294ba0) | Jun 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [eb51cb6dcf](https://linux-hardware.org/?probe=eb51cb6dcf) | Jun 03, 2023 |
| ASUSTek       | Maximus VIII HERO ALPHA     | Desktop     | [48eb50cc43](https://linux-hardware.org/?probe=48eb50cc43) | Jun 03, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [79de4bed98](https://linux-hardware.org/?probe=79de4bed98) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [eda1870d76](https://linux-hardware.org/?probe=eda1870d76) | May 31, 2023 |
| Gigabyte      | X99-UD7 WIFI-CF             | Desktop     | [955e65b76f](https://linux-hardware.org/?probe=955e65b76f) | May 31, 2023 |
| Timi          | RedmiBook 14 II             | Notebook    | [bad37936c6](https://linux-hardware.org/?probe=bad37936c6) | May 30, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [5271bd0b88](https://linux-hardware.org/?probe=5271bd0b88) | May 30, 2023 |
| MSI           | Katana GF76 12UD            | Notebook    | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | Notebook    | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [32fee60a54](https://linux-hardware.org/?probe=32fee60a54) | May 28, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ec91d28c95](https://linux-hardware.org/?probe=ec91d28c95) | May 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [fe2b8b63ac](https://linux-hardware.org/?probe=fe2b8b63ac) | May 28, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [f4411b6232](https://linux-hardware.org/?probe=f4411b6232) | May 27, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [07ecf79e17](https://linux-hardware.org/?probe=07ecf79e17) | May 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c4af5a7969](https://linux-hardware.org/?probe=c4af5a7969) | May 26, 2023 |
| MSI           | MS-B0A1                     | Desktop     | [aa99fb811d](https://linux-hardware.org/?probe=aa99fb811d) | May 26, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [dbfc9be02f](https://linux-hardware.org/?probe=dbfc9be02f) | May 26, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25f6dcaefc](https://linux-hardware.org/?probe=25f6dcaefc) | May 25, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a1a76abc51](https://linux-hardware.org/?probe=a1a76abc51) | May 24, 2023 |
| congatec      | conga-TA7 A.4               | Mini pc     | [686699557a](https://linux-hardware.org/?probe=686699557a) | May 24, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [f2477906c7](https://linux-hardware.org/?probe=f2477906c7) | May 23, 2023 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [266235dc3b](https://linux-hardware.org/?probe=266235dc3b) | May 23, 2023 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [df04cb5fb1](https://linux-hardware.org/?probe=df04cb5fb1) | May 22, 2023 |
| Lenovo        | ThinkPad T550 20CJS1V900    | Notebook    | [9bc275ef54](https://linux-hardware.org/?probe=9bc275ef54) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [117bc29848](https://linux-hardware.org/?probe=117bc29848) | May 22, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [e3af81180a](https://linux-hardware.org/?probe=e3af81180a) | May 22, 2023 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [11c329d15a](https://linux-hardware.org/?probe=11c329d15a) | May 22, 2023 |
| MSI           | Z87-G43                     | Desktop     | [2fa7c1d81d](https://linux-hardware.org/?probe=2fa7c1d81d) | May 21, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [b3564ca1cf](https://linux-hardware.org/?probe=b3564ca1cf) | May 20, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [15d9163f08](https://linux-hardware.org/?probe=15d9163f08) | May 20, 2023 |
| HP            | Compaq 6730s                | Notebook    | [632961079b](https://linux-hardware.org/?probe=632961079b) | May 20, 2023 |
| Notebook      | NLx0MU                      | Notebook    | [e0300907f0](https://linux-hardware.org/?probe=e0300907f0) | May 18, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING S     | Desktop     | [693c7b6d9b](https://linux-hardware.org/?probe=693c7b6d9b) | May 18, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [7a2e636353](https://linux-hardware.org/?probe=7a2e636353) | May 18, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [ca0ae58640](https://linux-hardware.org/?probe=ca0ae58640) | May 18, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2L60... | Notebook    | [a58ebcac7c](https://linux-hardware.org/?probe=a58ebcac7c) | May 17, 2023 |
| Acer          | Revo 70                     | Desktop     | [6cbc11e75b](https://linux-hardware.org/?probe=6cbc11e75b) | May 17, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [0829603c60](https://linux-hardware.org/?probe=0829603c60) | May 17, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [7d818512b8](https://linux-hardware.org/?probe=7d818512b8) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | Notebook    | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [966e89afc3](https://linux-hardware.org/?probe=966e89afc3) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [b4bd4b7d23](https://linux-hardware.org/?probe=b4bd4b7d23) | May 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [3089c7ab46](https://linux-hardware.org/?probe=3089c7ab46) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [a587179a2f](https://linux-hardware.org/?probe=a587179a2f) | May 16, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | Notebook    | [8ab7fe837d](https://linux-hardware.org/?probe=8ab7fe837d) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [8c10a0ad96](https://linux-hardware.org/?probe=8c10a0ad96) | May 16, 2023 |
| Dell          | 0NKW6Y A02                  | Desktop     | [be5ad76a6e](https://linux-hardware.org/?probe=be5ad76a6e) | May 16, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7d44c65f86](https://linux-hardware.org/?probe=7d44c65f86) | May 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [36df0e0f57](https://linux-hardware.org/?probe=36df0e0f57) | May 14, 2023 |
| MSI           | H110I PRO                   | Desktop     | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [beb403e4e0](https://linux-hardware.org/?probe=beb403e4e0) | May 14, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b8c68cfcf](https://linux-hardware.org/?probe=7b8c68cfcf) | May 13, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [17510fcd4f](https://linux-hardware.org/?probe=17510fcd4f) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [5ab21854e6](https://linux-hardware.org/?probe=5ab21854e6) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [b9b6adb18a](https://linux-hardware.org/?probe=b9b6adb18a) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [80dc4be517](https://linux-hardware.org/?probe=80dc4be517) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [c5c05f7e4c](https://linux-hardware.org/?probe=c5c05f7e4c) | May 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | Notebook    | [6eb320d381](https://linux-hardware.org/?probe=6eb320d381) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [4bbb20185b](https://linux-hardware.org/?probe=4bbb20185b) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [f89a68e432](https://linux-hardware.org/?probe=f89a68e432) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [a07acb448b](https://linux-hardware.org/?probe=a07acb448b) | May 12, 2023 |
| Lenovo        | ThinkPad X260 20F600A7MS    | Notebook    | [67daafed56](https://linux-hardware.org/?probe=67daafed56) | May 12, 2023 |
| HP            | Elite x360 830 13 inch G... | Convertible | [d835755922](https://linux-hardware.org/?probe=d835755922) | May 12, 2023 |
| HP            | ProBook 6470b               | Notebook    | [7f1a6e0d48](https://linux-hardware.org/?probe=7f1a6e0d48) | May 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | Notebook    | [f4df381f0e](https://linux-hardware.org/?probe=f4df381f0e) | May 12, 2023 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | Notebook    | [8f6bd394c4](https://linux-hardware.org/?probe=8f6bd394c4) | May 12, 2023 |
| Dell          | 0K240Y A01                  | Desktop     | [cbc84d049a](https://linux-hardware.org/?probe=cbc84d049a) | May 12, 2023 |
| Dell          | 0HHV7N A00                  | Desktop     | [c458dad4b3](https://linux-hardware.org/?probe=c458dad4b3) | May 12, 2023 |
| ASUSTek       | Rampage IV FORMULA          | Desktop     | [b44dd1286b](https://linux-hardware.org/?probe=b44dd1286b) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [c51d42778d](https://linux-hardware.org/?probe=c51d42778d) | May 12, 2023 |
| Dell          | 0K240Y A02                  | Desktop     | [e65b0be462](https://linux-hardware.org/?probe=e65b0be462) | May 12, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [d5bd5c8930](https://linux-hardware.org/?probe=d5bd5c8930) | May 12, 2023 |
| Fujitsu       | LIFEBOOK P702               | Notebook    | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [e661dd9daf](https://linux-hardware.org/?probe=e661dd9daf) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [721f9583d7](https://linux-hardware.org/?probe=721f9583d7) | May 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [bd7c97ad54](https://linux-hardware.org/?probe=bd7c97ad54) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9cbcc36a48](https://linux-hardware.org/?probe=9cbcc36a48) | May 11, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [483f4bbb5d](https://linux-hardware.org/?probe=483f4bbb5d) | May 10, 2023 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [535cc48341](https://linux-hardware.org/?probe=535cc48341) | May 08, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4c3e0a0ac6](https://linux-hardware.org/?probe=4c3e0a0ac6) | May 08, 2023 |
| Dell          | 096JG8 A01                  | Desktop     | [08df3c35ee](https://linux-hardware.org/?probe=08df3c35ee) | May 08, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [3ac194e77a](https://linux-hardware.org/?probe=3ac194e77a) | May 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [1c84c61678](https://linux-hardware.org/?probe=1c84c61678) | May 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [893f259653](https://linux-hardware.org/?probe=893f259653) | May 07, 2023 |
| MSI           | MS-B120                     | Mini pc     | [836697d300](https://linux-hardware.org/?probe=836697d300) | May 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c88845ae9b](https://linux-hardware.org/?probe=c88845ae9b) | May 06, 2023 |
| Dell          | Vostro 3360                 | Notebook    | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [14c71828ca](https://linux-hardware.org/?probe=14c71828ca) | May 05, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [3f515702d2](https://linux-hardware.org/?probe=3f515702d2) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [a15c5113a0](https://linux-hardware.org/?probe=a15c5113a0) | May 05, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b24260cc3](https://linux-hardware.org/?probe=5b24260cc3) | May 05, 2023 |
| Dell          | 02N3WF A02                  | Desktop     | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0b217b3ccc](https://linux-hardware.org/?probe=0b217b3ccc) | May 04, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [2f6fd9e5b0](https://linux-hardware.org/?probe=2f6fd9e5b0) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6cbfaabd66](https://linux-hardware.org/?probe=6cbfaabd66) | May 03, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [4762d9bb4e](https://linux-hardware.org/?probe=4762d9bb4e) | May 03, 2023 |
| Dynabook      | Satellite Pro C50-G-10M     | Notebook    | [d64568ca9c](https://linux-hardware.org/?probe=d64568ca9c) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e8721751c6](https://linux-hardware.org/?probe=e8721751c6) | May 03, 2023 |
| ASRock        | P55 Extreme                 | Desktop     | [e426e8e40b](https://linux-hardware.org/?probe=e426e8e40b) | May 03, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [973f9c6467](https://linux-hardware.org/?probe=973f9c6467) | May 01, 2023 |
| Intel         | D54250WYK H13922-302        | Desktop     | [92f7217eb7](https://linux-hardware.org/?probe=92f7217eb7) | May 01, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [22cf2ddf02](https://linux-hardware.org/?probe=22cf2ddf02) | May 01, 2023 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [56db7fc27f](https://linux-hardware.org/?probe=56db7fc27f) | May 01, 2023 |
| Shuttle       | FS35V4                      | Desktop     | [137fda9bc6](https://linux-hardware.org/?probe=137fda9bc6) | May 01, 2023 |
| MSI           | MS-B120                     | Mini pc     | [8019bfa6d4](https://linux-hardware.org/?probe=8019bfa6d4) | Apr 30, 2023 |
| MSI           | MS-B120                     | Mini pc     | [4f10159e93](https://linux-hardware.org/?probe=4f10159e93) | Apr 30, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [4b47a4606b](https://linux-hardware.org/?probe=4b47a4606b) | Apr 29, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [d97d6d6dff](https://linux-hardware.org/?probe=d97d6d6dff) | Apr 28, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [9a36e5ebaf](https://linux-hardware.org/?probe=9a36e5ebaf) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [1a73639c02](https://linux-hardware.org/?probe=1a73639c02) | Apr 28, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [a6eba14ab4](https://linux-hardware.org/?probe=a6eba14ab4) | Apr 28, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [6f56840307](https://linux-hardware.org/?probe=6f56840307) | Apr 28, 2023 |
| Dell          | Latitude 5430               | Notebook    | [644e44f95a](https://linux-hardware.org/?probe=644e44f95a) | Apr 28, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c53a69bd72](https://linux-hardware.org/?probe=c53a69bd72) | Apr 28, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [ff439c208a](https://linux-hardware.org/?probe=ff439c208a) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [69f1753783](https://linux-hardware.org/?probe=69f1753783) | Apr 26, 2023 |
| Lenovo        | B50-70 80EU                 | Notebook    | [067bc49888](https://linux-hardware.org/?probe=067bc49888) | Apr 26, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [4fcb9881b2](https://linux-hardware.org/?probe=4fcb9881b2) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d49fc2276](https://linux-hardware.org/?probe=6d49fc2276) | Apr 24, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [21c872ac1c](https://linux-hardware.org/?probe=21c872ac1c) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [99e0054492](https://linux-hardware.org/?probe=99e0054492) | Apr 23, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [86b56d3e69](https://linux-hardware.org/?probe=86b56d3e69) | Apr 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [adab9d9f6b](https://linux-hardware.org/?probe=adab9d9f6b) | Apr 22, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [17c955a974](https://linux-hardware.org/?probe=17c955a974) | Apr 21, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [cb9c80dbba](https://linux-hardware.org/?probe=cb9c80dbba) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [3f12350d47](https://linux-hardware.org/?probe=3f12350d47) | Apr 20, 2023 |
| Dell          | Latitude 7490               | Notebook    | [57a719ce62](https://linux-hardware.org/?probe=57a719ce62) | Apr 20, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [69c613b55f](https://linux-hardware.org/?probe=69c613b55f) | Apr 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [83c6b6137d](https://linux-hardware.org/?probe=83c6b6137d) | Apr 20, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [b45a30f071](https://linux-hardware.org/?probe=b45a30f071) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6SV0... | Notebook    | [8f05b53b93](https://linux-hardware.org/?probe=8f05b53b93) | Apr 17, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [4278a9f497](https://linux-hardware.org/?probe=4278a9f497) | Apr 17, 2023 |
| Toshiba       | Satellite C855D-162         | Notebook    | [d8e8774e0b](https://linux-hardware.org/?probe=d8e8774e0b) | Apr 17, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [39106da598](https://linux-hardware.org/?probe=39106da598) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [a9f8183365](https://linux-hardware.org/?probe=a9f8183365) | Apr 16, 2023 |
| Unknown       | Unknown                     | Phone       | [3d8d71ba51](https://linux-hardware.org/?probe=3d8d71ba51) | Apr 16, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [a51c500b65](https://linux-hardware.org/?probe=a51c500b65) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [53c9fe0b8d](https://linux-hardware.org/?probe=53c9fe0b8d) | Apr 15, 2023 |
| Acer          | Aspire A114-33              | Notebook    | [99f95937d4](https://linux-hardware.org/?probe=99f95937d4) | Apr 15, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [b259f47200](https://linux-hardware.org/?probe=b259f47200) | Apr 15, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [40894d0141](https://linux-hardware.org/?probe=40894d0141) | Apr 14, 2023 |
| Toshiba       | PORTEGE X20W-E              | Convertible | [d2c04327fb](https://linux-hardware.org/?probe=d2c04327fb) | Apr 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [b7786541c0](https://linux-hardware.org/?probe=b7786541c0) | Apr 13, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [ec6dc0883b](https://linux-hardware.org/?probe=ec6dc0883b) | Apr 13, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [66924704d2](https://linux-hardware.org/?probe=66924704d2) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [87d43c1f1d](https://linux-hardware.org/?probe=87d43c1f1d) | Apr 12, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [a291f82fe3](https://linux-hardware.org/?probe=a291f82fe3) | Apr 12, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [810aed46d0](https://linux-hardware.org/?probe=810aed46d0) | Apr 11, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5db9e8f875](https://linux-hardware.org/?probe=5db9e8f875) | Apr 11, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [7ddf3af042](https://linux-hardware.org/?probe=7ddf3af042) | Apr 11, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [e3eee10ad1](https://linux-hardware.org/?probe=e3eee10ad1) | Apr 10, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [885fff9ddb](https://linux-hardware.org/?probe=885fff9ddb) | Apr 10, 2023 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [d5fb19d97c](https://linux-hardware.org/?probe=d5fb19d97c) | Apr 08, 2023 |
| HP            | ProBook 4530s               | Notebook    | [efd084d9d5](https://linux-hardware.org/?probe=efd084d9d5) | Apr 07, 2023 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [0ddbf6cc2e](https://linux-hardware.org/?probe=0ddbf6cc2e) | Apr 07, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [a0c75732ae](https://linux-hardware.org/?probe=a0c75732ae) | Apr 06, 2023 |
| LG Electro... | Kabylake Platform           | Notebook    | [8b66f7c170](https://linux-hardware.org/?probe=8b66f7c170) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [0f4a907d19](https://linux-hardware.org/?probe=0f4a907d19) | Apr 05, 2023 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [d337edfd9a](https://linux-hardware.org/?probe=d337edfd9a) | Apr 05, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6ddafae4d0](https://linux-hardware.org/?probe=6ddafae4d0) | Apr 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [01f2e4a69f](https://linux-hardware.org/?probe=01f2e4a69f) | Apr 05, 2023 |
| HP            | ProBook 450 G1              | Notebook    | [f49ec499ed](https://linux-hardware.org/?probe=f49ec499ed) | Apr 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [68322a0698](https://linux-hardware.org/?probe=68322a0698) | Apr 04, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [9d90029e27](https://linux-hardware.org/?probe=9d90029e27) | Apr 04, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [53fc9d8c25](https://linux-hardware.org/?probe=53fc9d8c25) | Apr 04, 2023 |
| Dell          | Precision 5530              | Notebook    | [bf568860cb](https://linux-hardware.org/?probe=bf568860cb) | Apr 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [550f1d522d](https://linux-hardware.org/?probe=550f1d522d) | Apr 04, 2023 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [56a619b537](https://linux-hardware.org/?probe=56a619b537) | Apr 04, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [08074927ff](https://linux-hardware.org/?probe=08074927ff) | Apr 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d57f6cb4c6](https://linux-hardware.org/?probe=d57f6cb4c6) | Apr 03, 2023 |
| Intel         | NUC12WSBi5 M63398-302       | Mini pc     | [785a41f4e9](https://linux-hardware.org/?probe=785a41f4e9) | Apr 02, 2023 |
| Acer          | Predator G3-605             | Desktop     | [f7ca1573d0](https://linux-hardware.org/?probe=f7ca1573d0) | Apr 02, 2023 |
| Acer          | Predator G3-605             | Desktop     | [eb21663788](https://linux-hardware.org/?probe=eb21663788) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [06275c19f3](https://linux-hardware.org/?probe=06275c19f3) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [36e57fb4cf](https://linux-hardware.org/?probe=36e57fb4cf) | Apr 01, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [1fa4ec7b05](https://linux-hardware.org/?probe=1fa4ec7b05) | Apr 01, 2023 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [a89c429c84](https://linux-hardware.org/?probe=a89c429c84) | Mar 31, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [fc0539603c](https://linux-hardware.org/?probe=fc0539603c) | Mar 31, 2023 |
| HP            | 82B4                        | Desktop     | [9712d04ab5](https://linux-hardware.org/?probe=9712d04ab5) | Mar 30, 2023 |
| HP            | ENVY TS Sleekbook 4         | Notebook    | [f897573506](https://linux-hardware.org/?probe=f897573506) | Mar 29, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [50affe59d1](https://linux-hardware.org/?probe=50affe59d1) | Mar 28, 2023 |
| ASUSTek       | TP410UA                     | Convertible | [b74b7f7d31](https://linux-hardware.org/?probe=b74b7f7d31) | Mar 28, 2023 |
| HP            | ProBook 450 G3              | Notebook    | [f0e6089a6e](https://linux-hardware.org/?probe=f0e6089a6e) | Mar 28, 2023 |
| Acer          | Nitro N50-640               | Desktop     | [2219ec0fad](https://linux-hardware.org/?probe=2219ec0fad) | Mar 27, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [011d1b8bf7](https://linux-hardware.org/?probe=011d1b8bf7) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [9fd0ee0183](https://linux-hardware.org/?probe=9fd0ee0183) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [d0f84e1bd4](https://linux-hardware.org/?probe=d0f84e1bd4) | Mar 27, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [c5a3b374a7](https://linux-hardware.org/?probe=c5a3b374a7) | Mar 27, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [8a1c592e98](https://linux-hardware.org/?probe=8a1c592e98) | Mar 27, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [eef16c5e09](https://linux-hardware.org/?probe=eef16c5e09) | Mar 27, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [f403538019](https://linux-hardware.org/?probe=f403538019) | Mar 26, 2023 |
| HP            | 1998                        | Desktop     | [346f37956b](https://linux-hardware.org/?probe=346f37956b) | Mar 26, 2023 |
| Gigabyte      | AORUS 15G KC                | Notebook    | [d87e89d84f](https://linux-hardware.org/?probe=d87e89d84f) | Mar 26, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [6f9300474f](https://linux-hardware.org/?probe=6f9300474f) | Mar 26, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [d1baffa910](https://linux-hardware.org/?probe=d1baffa910) | Mar 25, 2023 |
| HP            | 2B05                        | Desktop     | [b34e6d230c](https://linux-hardware.org/?probe=b34e6d230c) | Mar 24, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b2cdf1deb7](https://linux-hardware.org/?probe=b2cdf1deb7) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [1e549ae67e](https://linux-hardware.org/?probe=1e549ae67e) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e7b4dc0fd4](https://linux-hardware.org/?probe=e7b4dc0fd4) | Mar 23, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bf24fe6112](https://linux-hardware.org/?probe=bf24fe6112) | Mar 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | Notebook    | [883d4de906](https://linux-hardware.org/?probe=883d4de906) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| Shuttle       | SH570                       | Desktop     | [3ef2bf52b7](https://linux-hardware.org/?probe=3ef2bf52b7) | Mar 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [240444cad9](https://linux-hardware.org/?probe=240444cad9) | Mar 21, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [a9a586ef2d](https://linux-hardware.org/?probe=a9a586ef2d) | Mar 20, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [51e5415bb0](https://linux-hardware.org/?probe=51e5415bb0) | Mar 19, 2023 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [c88d5f831a](https://linux-hardware.org/?probe=c88d5f831a) | Mar 19, 2023 |
| Intel         | NUC5CPYB H61145-412         | Mini pc     | [a87d0fe300](https://linux-hardware.org/?probe=a87d0fe300) | Mar 19, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bd119c8898](https://linux-hardware.org/?probe=bd119c8898) | Mar 17, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [87ba801b00](https://linux-hardware.org/?probe=87ba801b00) | Mar 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [f219a6e14a](https://linux-hardware.org/?probe=f219a6e14a) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [dfb8518fa9](https://linux-hardware.org/?probe=dfb8518fa9) | Mar 16, 2023 |
| Acer          | Aspire M3-581T              | Notebook    | [bb4f0202b7](https://linux-hardware.org/?probe=bb4f0202b7) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Google        | Rabbid                      | Notebook    | [621762ceec](https://linux-hardware.org/?probe=621762ceec) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | Notebook    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| ASUSTek       | X550MD                      | Notebook    | [2cd5ae8a43](https://linux-hardware.org/?probe=2cd5ae8a43) | Mar 15, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [016f5cd3be](https://linux-hardware.org/?probe=016f5cd3be) | Mar 14, 2023 |
| Lenovo        | ThinkCentre M58 7638CB8     | Desktop     | [d303f78e26](https://linux-hardware.org/?probe=d303f78e26) | Mar 14, 2023 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [070c7d809a](https://linux-hardware.org/?probe=070c7d809a) | Mar 13, 2023 |
| GPD           | P2 MAX                      | Notebook    | [dd958bf28e](https://linux-hardware.org/?probe=dd958bf28e) | Mar 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [ff9cb78f74](https://linux-hardware.org/?probe=ff9cb78f74) | Mar 13, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [12120178de](https://linux-hardware.org/?probe=12120178de) | Mar 13, 2023 |
| Lenovo        | ThinkPad T510 4313CTO       | Notebook    | [c2f9a6e354](https://linux-hardware.org/?probe=c2f9a6e354) | Mar 13, 2023 |
| HP            | 1825                        | Desktop     | [85011ed37d](https://linux-hardware.org/?probe=85011ed37d) | Mar 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [1169593829](https://linux-hardware.org/?probe=1169593829) | Mar 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [76e4cc71f5](https://linux-hardware.org/?probe=76e4cc71f5) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| HP            | 1998                        | Desktop     | [68d7c4350d](https://linux-hardware.org/?probe=68d7c4350d) | Mar 12, 2023 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c22a046fc6](https://linux-hardware.org/?probe=c22a046fc6) | Mar 11, 2023 |
| SiYW          | V200 Series                 | Desktop     | [7c3751c888](https://linux-hardware.org/?probe=7c3751c888) | Mar 11, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [0555c85a89](https://linux-hardware.org/?probe=0555c85a89) | Mar 11, 2023 |
| HP            | 18E5                        | Desktop     | [82e5831486](https://linux-hardware.org/?probe=82e5831486) | Mar 10, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [03f44a913e](https://linux-hardware.org/?probe=03f44a913e) | Mar 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d15122995](https://linux-hardware.org/?probe=4d15122995) | Mar 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [cc6e719e99](https://linux-hardware.org/?probe=cc6e719e99) | Mar 07, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d1768ecbaa](https://linux-hardware.org/?probe=d1768ecbaa) | Mar 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [081ecd2050](https://linux-hardware.org/?probe=081ecd2050) | Mar 07, 2023 |
| HP            | Presario CQ57               | Notebook    | [33b1812664](https://linux-hardware.org/?probe=33b1812664) | Mar 06, 2023 |
| HP            | Presario CQ57               | Notebook    | [26ec55c2cb](https://linux-hardware.org/?probe=26ec55c2cb) | Mar 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [0d202dc031](https://linux-hardware.org/?probe=0d202dc031) | Mar 06, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [baff849073](https://linux-hardware.org/?probe=baff849073) | Mar 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8814af9b71](https://linux-hardware.org/?probe=8814af9b71) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [deb075440f](https://linux-hardware.org/?probe=deb075440f) | Mar 05, 2023 |
| HP            | 2B05                        | Desktop     | [f21bd9cc58](https://linux-hardware.org/?probe=f21bd9cc58) | Mar 05, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [14211fd55f](https://linux-hardware.org/?probe=14211fd55f) | Mar 04, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [19bd4c1e4e](https://linux-hardware.org/?probe=19bd4c1e4e) | Mar 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f9a2075d54](https://linux-hardware.org/?probe=f9a2075d54) | Mar 04, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | Notebook    | [10c12a6b8a](https://linux-hardware.org/?probe=10c12a6b8a) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Dell          | Precision 3551              | Notebook    | [7c1bc8355a](https://linux-hardware.org/?probe=7c1bc8355a) | Mar 03, 2023 |
| Clevo         | W25xHNx                     | Notebook    | [5227127f81](https://linux-hardware.org/?probe=5227127f81) | Mar 03, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [f3defb812b](https://linux-hardware.org/?probe=f3defb812b) | Mar 03, 2023 |
| Lenovo        | 3178 SDK0J40697 WIN 3305... | Desktop     | [41d9c3d9ed](https://linux-hardware.org/?probe=41d9c3d9ed) | Mar 02, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a279108842](https://linux-hardware.org/?probe=a279108842) | Mar 02, 2023 |
| Fujitsu       | D3224-P1 S26361-D3224-P1    | Desktop     | [53649a9546](https://linux-hardware.org/?probe=53649a9546) | Feb 28, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [45403acec9](https://linux-hardware.org/?probe=45403acec9) | Feb 27, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [3cd0e65d1f](https://linux-hardware.org/?probe=3cd0e65d1f) | Feb 27, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [2fe31a709a](https://linux-hardware.org/?probe=2fe31a709a) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [5ef01d46d4](https://linux-hardware.org/?probe=5ef01d46d4) | Feb 25, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0AE0... | Notebook    | [7f8c9de1aa](https://linux-hardware.org/?probe=7f8c9de1aa) | Feb 24, 2023 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [fc86b476d7](https://linux-hardware.org/?probe=fc86b476d7) | Feb 22, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [de328ac1ad](https://linux-hardware.org/?probe=de328ac1ad) | Feb 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [da461191e8](https://linux-hardware.org/?probe=da461191e8) | Feb 21, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [54b9c4c95c](https://linux-hardware.org/?probe=54b9c4c95c) | Feb 21, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ecc97fee86](https://linux-hardware.org/?probe=ecc97fee86) | Feb 21, 2023 |
| Dell          | Precision M4800             | Notebook    | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| ASUSTek       | G501VW                      | Notebook    | [6e014311b2](https://linux-hardware.org/?probe=6e014311b2) | Feb 20, 2023 |
| MSI           | Z170A GAMING M5             | Desktop     | [5aa73f71fd](https://linux-hardware.org/?probe=5aa73f71fd) | Feb 20, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [7427fa6886](https://linux-hardware.org/?probe=7427fa6886) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [2b56edae65](https://linux-hardware.org/?probe=2b56edae65) | Feb 19, 2023 |
| Intel         | NUC7JYB M37316-600          | Mini pc     | [dde311dcb2](https://linux-hardware.org/?probe=dde311dcb2) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6cc82a744e](https://linux-hardware.org/?probe=6cc82a744e) | Feb 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [96b350db9f](https://linux-hardware.org/?probe=96b350db9f) | Feb 18, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [8e521a2efc](https://linux-hardware.org/?probe=8e521a2efc) | Feb 16, 2023 |
| GPD           | P2 MAX                      | Notebook    | [9a623b2196](https://linux-hardware.org/?probe=9a623b2196) | Feb 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [eac9c046ac](https://linux-hardware.org/?probe=eac9c046ac) | Feb 15, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [3717c2476f](https://linux-hardware.org/?probe=3717c2476f) | Feb 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [7cdc5a7d89](https://linux-hardware.org/?probe=7cdc5a7d89) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4e3ff30332](https://linux-hardware.org/?probe=4e3ff30332) | Feb 15, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [eb40144624](https://linux-hardware.org/?probe=eb40144624) | Feb 13, 2023 |
| HP            | 8455                        | Desktop     | [f75db6c5d5](https://linux-hardware.org/?probe=f75db6c5d5) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX H470-I GAMING     | Desktop     | [3a18e2226c](https://linux-hardware.org/?probe=3a18e2226c) | Feb 12, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [004535fd1c](https://linux-hardware.org/?probe=004535fd1c) | Feb 11, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7a6b34f58c](https://linux-hardware.org/?probe=7a6b34f58c) | Feb 11, 2023 |
| HP            | EliteBook 820 G3            | Notebook    | [c1ac37fee3](https://linux-hardware.org/?probe=c1ac37fee3) | Feb 10, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [6d9d60d4b8](https://linux-hardware.org/?probe=6d9d60d4b8) | Feb 10, 2023 |
| MSI           | MS-B120                     | Mini pc     | [1d365cbddd](https://linux-hardware.org/?probe=1d365cbddd) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [8239d80ae0](https://linux-hardware.org/?probe=8239d80ae0) | Feb 10, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a60a4191b8](https://linux-hardware.org/?probe=a60a4191b8) | Feb 10, 2023 |
| Dell          | Latitude E7250              | Notebook    | [e3c1b1e038](https://linux-hardware.org/?probe=e3c1b1e038) | Feb 09, 2023 |
| AZW           | GTR V01                     | Mini pc     | [2898aebf10](https://linux-hardware.org/?probe=2898aebf10) | Feb 08, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [fd61c4416f](https://linux-hardware.org/?probe=fd61c4416f) | Feb 08, 2023 |
| Dell          | Latitude E7250              | Notebook    | [b4a7701aa4](https://linux-hardware.org/?probe=b4a7701aa4) | Feb 07, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [3797cf0990](https://linux-hardware.org/?probe=3797cf0990) | Feb 07, 2023 |
| ASUSTek       | EB1501P                     | Desktop     | [687e52dcb1](https://linux-hardware.org/?probe=687e52dcb1) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [e553ba2549](https://linux-hardware.org/?probe=e553ba2549) | Feb 06, 2023 |
| Acer          | Aspire XC-895 V:1.0         | Desktop     | [d888ff5291](https://linux-hardware.org/?probe=d888ff5291) | Feb 06, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [0c6df9267b](https://linux-hardware.org/?probe=0c6df9267b) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [452216b5ed](https://linux-hardware.org/?probe=452216b5ed) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN001SUS     | Notebook    | [bbe182e4c2](https://linux-hardware.org/?probe=bbe182e4c2) | Feb 04, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [f265a0e81e](https://linux-hardware.org/?probe=f265a0e81e) | Feb 04, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [9e2380e15d](https://linux-hardware.org/?probe=9e2380e15d) | Feb 03, 2023 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [fac45201b3](https://linux-hardware.org/?probe=fac45201b3) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [1752779e0c](https://linux-hardware.org/?probe=1752779e0c) | Feb 02, 2023 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | Notebook    | [ef707954b8](https://linux-hardware.org/?probe=ef707954b8) | Feb 02, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [6e089e22b1](https://linux-hardware.org/?probe=6e089e22b1) | Feb 01, 2023 |
| Dell          | Latitude 7420               | Notebook    | [f0b8816283](https://linux-hardware.org/?probe=f0b8816283) | Feb 01, 2023 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [431a6c7a3a](https://linux-hardware.org/?probe=431a6c7a3a) | Feb 01, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [f1a9c37047](https://linux-hardware.org/?probe=f1a9c37047) | Jan 31, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [fe2a413caa](https://linux-hardware.org/?probe=fe2a413caa) | Jan 31, 2023 |
| Dell          | Latitude 7420               | Notebook    | [55f81648a1](https://linux-hardware.org/?probe=55f81648a1) | Jan 31, 2023 |
| Dell          | Latitude 7480               | Notebook    | [f3a84b494f](https://linux-hardware.org/?probe=f3a84b494f) | Jan 30, 2023 |
| Dell          | Latitude D630C              | Notebook    | [401357bc99](https://linux-hardware.org/?probe=401357bc99) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | Notebook    | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Gigabyte      | 970A-D3P                    | Desktop     | [f01366b131](https://linux-hardware.org/?probe=f01366b131) | Jan 27, 2023 |
| Dell          | 0Y2MRG A00                  | Desktop     | [54ba66711b](https://linux-hardware.org/?probe=54ba66711b) | Jan 26, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [26f64a2ad0](https://linux-hardware.org/?probe=26f64a2ad0) | Jan 26, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [756bf12bd7](https://linux-hardware.org/?probe=756bf12bd7) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [c4a13a66ed](https://linux-hardware.org/?probe=c4a13a66ed) | Jan 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [cb00a3e89d](https://linux-hardware.org/?probe=cb00a3e89d) | Jan 24, 2023 |
| Google        | Link                        | Notebook    | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [1a9bed0cf3](https://linux-hardware.org/?probe=1a9bed0cf3) | Jan 23, 2023 |
| Dell          | 0Y56T3 A00                  | Desktop     | [7078ea91e9](https://linux-hardware.org/?probe=7078ea91e9) | Jan 22, 2023 |
| AZW           | GTR V01                     | Mini pc     | [1d4c2002d5](https://linux-hardware.org/?probe=1d4c2002d5) | Jan 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [9792de46ad](https://linux-hardware.org/?probe=9792de46ad) | Jan 22, 2023 |
| AMI           | Intel                       | Notebook    | [53a3ba4e8a](https://linux-hardware.org/?probe=53a3ba4e8a) | Jan 21, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [fa1f3d8e3b](https://linux-hardware.org/?probe=fa1f3d8e3b) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [1d10977303](https://linux-hardware.org/?probe=1d10977303) | Jan 21, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [fdbbb4a832](https://linux-hardware.org/?probe=fdbbb4a832) | Jan 21, 2023 |
| Lenovo        | 3730 SDK0T76465 WIN 3422... | Desktop     | [80e51b3319](https://linux-hardware.org/?probe=80e51b3319) | Jan 20, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [d7e7799006](https://linux-hardware.org/?probe=d7e7799006) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [e221c08388](https://linux-hardware.org/?probe=e221c08388) | Jan 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [d2bb65ed09](https://linux-hardware.org/?probe=d2bb65ed09) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [6d6698b316](https://linux-hardware.org/?probe=6d6698b316) | Jan 18, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [8bfae8a964](https://linux-hardware.org/?probe=8bfae8a964) | Jan 17, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0e57f4ecbe](https://linux-hardware.org/?probe=0e57f4ecbe) | Jan 15, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [5b26575c52](https://linux-hardware.org/?probe=5b26575c52) | Jan 15, 2023 |
| Acer          | Aspire A315-43              | Notebook    | [06dfad94f5](https://linux-hardware.org/?probe=06dfad94f5) | Jan 15, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [0533348a3f](https://linux-hardware.org/?probe=0533348a3f) | Jan 14, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [b0308f4270](https://linux-hardware.org/?probe=b0308f4270) | Jan 13, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [262fe40796](https://linux-hardware.org/?probe=262fe40796) | Jan 12, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING       | Desktop     | [18bdf2650e](https://linux-hardware.org/?probe=18bdf2650e) | Jan 12, 2023 |
| ASUSTek       | GA15DH                      | Desktop     | [e480a3bfa3](https://linux-hardware.org/?probe=e480a3bfa3) | Jan 11, 2023 |
| Dell          | Studio 1749                 | Notebook    | [28a19b2c03](https://linux-hardware.org/?probe=28a19b2c03) | Jan 11, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [7697ff8cb4](https://linux-hardware.org/?probe=7697ff8cb4) | Jan 11, 2023 |
| Lenovo        | 30C7 SDK0J40700 WIN 3258... | Desktop     | [994306b125](https://linux-hardware.org/?probe=994306b125) | Jan 11, 2023 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [72bf3e7a8b](https://linux-hardware.org/?probe=72bf3e7a8b) | Jan 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [25090a9dcb](https://linux-hardware.org/?probe=25090a9dcb) | Jan 11, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [aacfe1b351](https://linux-hardware.org/?probe=aacfe1b351) | Jan 11, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [5cfaf7d715](https://linux-hardware.org/?probe=5cfaf7d715) | Jan 10, 2023 |
| ASUSTek       | N552VX                      | Notebook    | [59155b3092](https://linux-hardware.org/?probe=59155b3092) | Jan 10, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [ac85316fc2](https://linux-hardware.org/?probe=ac85316fc2) | Jan 09, 2023 |
| MSI           | GP60 2PE                    | Notebook    | [e1506ca6f6](https://linux-hardware.org/?probe=e1506ca6f6) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [8be13470fb](https://linux-hardware.org/?probe=8be13470fb) | Jan 09, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [980ee9f42c](https://linux-hardware.org/?probe=980ee9f42c) | Jan 07, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [be1be100c9](https://linux-hardware.org/?probe=be1be100c9) | Jan 07, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9a138871a6](https://linux-hardware.org/?probe=9a138871a6) | Jan 06, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [e64152748d](https://linux-hardware.org/?probe=e64152748d) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0cca8fbbb6](https://linux-hardware.org/?probe=0cca8fbbb6) | Jan 05, 2023 |
| Samsung       | R530/R730                   | Notebook    | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Precision M90               | Notebook    | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | Pavilion g6                 | Notebook    | [6cae064dc5](https://linux-hardware.org/?probe=6cae064dc5) | Jan 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [a24229bc3b](https://linux-hardware.org/?probe=a24229bc3b) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2849ffe456](https://linux-hardware.org/?probe=2849ffe456) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [77cc17c28c](https://linux-hardware.org/?probe=77cc17c28c) | Jan 02, 2023 |
| Foxconn       | 2AAF                        | Desktop     | [813a45dc50](https://linux-hardware.org/?probe=813a45dc50) | Jan 01, 2023 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [de65990b87](https://linux-hardware.org/?probe=de65990b87) | Jan 01, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [273f6722e0](https://linux-hardware.org/?probe=273f6722e0) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [09994766ed](https://linux-hardware.org/?probe=09994766ed) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [f4d5ef752c](https://linux-hardware.org/?probe=f4d5ef752c) | Dec 31, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [270ba62d9d](https://linux-hardware.org/?probe=270ba62d9d) | Dec 31, 2022 |
| Shuttle       | SH570                       | Desktop     | [2d7f57de8f](https://linux-hardware.org/?probe=2d7f57de8f) | Dec 31, 2022 |
| Lenovo        | ChiefRiver                  | Desktop     | [847a9e86cd](https://linux-hardware.org/?probe=847a9e86cd) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [16419f6991](https://linux-hardware.org/?probe=16419f6991) | Dec 30, 2022 |
| Lenovo        | Z70-80 80FG                 | Notebook    | [4386242be1](https://linux-hardware.org/?probe=4386242be1) | Dec 30, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [34cd286c5f](https://linux-hardware.org/?probe=34cd286c5f) | Dec 30, 2022 |
| Valve         | Jupiter                     | Notebook    | [15c60654b3](https://linux-hardware.org/?probe=15c60654b3) | Dec 30, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [87d0f67d84](https://linux-hardware.org/?probe=87d0f67d84) | Dec 30, 2022 |
| HP            | 1998                        | Desktop     | [c3404205e3](https://linux-hardware.org/?probe=c3404205e3) | Dec 29, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [b89e7eb1c9](https://linux-hardware.org/?probe=b89e7eb1c9) | Dec 28, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [f37619077b](https://linux-hardware.org/?probe=f37619077b) | Dec 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e979df032a](https://linux-hardware.org/?probe=e979df032a) | Dec 26, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [82a5aa7ead](https://linux-hardware.org/?probe=82a5aa7ead) | Dec 26, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [2ef0101186](https://linux-hardware.org/?probe=2ef0101186) | Dec 25, 2022 |
| GMKtec        | NucBox8                     | Server      | [abc999a1a4](https://linux-hardware.org/?probe=abc999a1a4) | Dec 24, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [04b76a7e78](https://linux-hardware.org/?probe=04b76a7e78) | Dec 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [e4847d5b1f](https://linux-hardware.org/?probe=e4847d5b1f) | Dec 24, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [92f12e3ec7](https://linux-hardware.org/?probe=92f12e3ec7) | Dec 24, 2022 |
| GMKtec        | NucBox8                     | Server      | [66b0fbce86](https://linux-hardware.org/?probe=66b0fbce86) | Dec 24, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [b993283081](https://linux-hardware.org/?probe=b993283081) | Dec 22, 2022 |
| Microsoft     | Surface Pro 2               | Tablet      | [3237ff6784](https://linux-hardware.org/?probe=3237ff6784) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ba82bee4c7](https://linux-hardware.org/?probe=ba82bee4c7) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a2a2f20ef4](https://linux-hardware.org/?probe=a2a2f20ef4) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [92515d8a95](https://linux-hardware.org/?probe=92515d8a95) | Dec 21, 2022 |
| Schenker      | XMG APEX 15 MAX (E22)       | Notebook    | [6b46538fea](https://linux-hardware.org/?probe=6b46538fea) | Dec 21, 2022 |
| Dell          | 0020HJ A01                  | Server      | [e266254c60](https://linux-hardware.org/?probe=e266254c60) | Dec 21, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [5477e8f714](https://linux-hardware.org/?probe=5477e8f714) | Dec 21, 2022 |
| Dell          | Latitude 3380               | Notebook    | [808c693271](https://linux-hardware.org/?probe=808c693271) | Dec 20, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [8a09a51987](https://linux-hardware.org/?probe=8a09a51987) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4fbc0ddbd5](https://linux-hardware.org/?probe=4fbc0ddbd5) | Dec 20, 2022 |
| HP            | 18E7                        | Desktop     | [31011a35a4](https://linux-hardware.org/?probe=31011a35a4) | Dec 17, 2022 |
| ASRock        | Z77 Extreme4                | Desktop     | [3b48a01ef2](https://linux-hardware.org/?probe=3b48a01ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [ffa7e28596](https://linux-hardware.org/?probe=ffa7e28596) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [143d2059a6](https://linux-hardware.org/?probe=143d2059a6) | Dec 16, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [bc3635620b](https://linux-hardware.org/?probe=bc3635620b) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [888e6092a6](https://linux-hardware.org/?probe=888e6092a6) | Dec 15, 2022 |
| HP            | EliteBook 830 G6            | Notebook    | [5248ee7dbe](https://linux-hardware.org/?probe=5248ee7dbe) | Dec 15, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [3403282c8c](https://linux-hardware.org/?probe=3403282c8c) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| Dell          | 0D6H9T A02                  | Desktop     | [6266999282](https://linux-hardware.org/?probe=6266999282) | Dec 15, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a0d408fecd](https://linux-hardware.org/?probe=a0d408fecd) | Dec 15, 2022 |
| Dell          | Latitude E7240              | Notebook    | [c47fc4fadf](https://linux-hardware.org/?probe=c47fc4fadf) | Dec 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6b47a036ab](https://linux-hardware.org/?probe=6b47a036ab) | Dec 14, 2022 |
| Insyde        | G0975                       | Notebook    | [1f4823542d](https://linux-hardware.org/?probe=1f4823542d) | Dec 14, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [39a9464c10](https://linux-hardware.org/?probe=39a9464c10) | Dec 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5a9654c743](https://linux-hardware.org/?probe=5a9654c743) | Dec 13, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [4a3ac966fc](https://linux-hardware.org/?probe=4a3ac966fc) | Dec 13, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [05ffc0ef7a](https://linux-hardware.org/?probe=05ffc0ef7a) | Dec 13, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [502792fe8a](https://linux-hardware.org/?probe=502792fe8a) | Dec 12, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 7 2... | Convertible | [7b8b3c2a86](https://linux-hardware.org/?probe=7b8b3c2a86) | Dec 12, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| Dell          | Latitude 5430               | Notebook    | [b439d1e1a4](https://linux-hardware.org/?probe=b439d1e1a4) | Dec 12, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| Google        | Orco                        | Notebook    | [40acd3207e](https://linux-hardware.org/?probe=40acd3207e) | Dec 10, 2022 |
| Google        | Orco                        | Notebook    | [9c369b40b3](https://linux-hardware.org/?probe=9c369b40b3) | Dec 10, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3a91c2e245](https://linux-hardware.org/?probe=3a91c2e245) | Dec 07, 2022 |
| Lenovo        | ThinkPad T490s 20NX001KM... | Notebook    | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [310ff494e7](https://linux-hardware.org/?probe=310ff494e7) | Dec 06, 2022 |
| HP            | 18E5                        | Desktop     | [9158a7ab6b](https://linux-hardware.org/?probe=9158a7ab6b) | Dec 06, 2022 |
| ASUSTek       | VivoBook S13 X330UA         | Notebook    | [d01d1e9652](https://linux-hardware.org/?probe=d01d1e9652) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [ff90421b87](https://linux-hardware.org/?probe=ff90421b87) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [3bc6ea9cfa](https://linux-hardware.org/?probe=3bc6ea9cfa) | Dec 05, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [aaed16d626](https://linux-hardware.org/?probe=aaed16d626) | Dec 05, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [cd63efdbd4](https://linux-hardware.org/?probe=cd63efdbd4) | Dec 05, 2022 |
| SiYW          | V200 Series                 | Desktop     | [c80a75c310](https://linux-hardware.org/?probe=c80a75c310) | Dec 03, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [7ea8161a05](https://linux-hardware.org/?probe=7ea8161a05) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d8d5459ad6](https://linux-hardware.org/?probe=d8d5459ad6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [994d8e4b1d](https://linux-hardware.org/?probe=994d8e4b1d) | Dec 01, 2022 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [1dddd99280](https://linux-hardware.org/?probe=1dddd99280) | Dec 01, 2022 |
| Lenovo        | ThinkPad L560 20F10034MX    | Notebook    | [34842eb8d9](https://linux-hardware.org/?probe=34842eb8d9) | Dec 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS03B00    | Notebook    | [bd40de3011](https://linux-hardware.org/?probe=bd40de3011) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [258c074e40](https://linux-hardware.org/?probe=258c074e40) | Nov 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [29ec19d38e](https://linux-hardware.org/?probe=29ec19d38e) | Nov 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [997ffc40f0](https://linux-hardware.org/?probe=997ffc40f0) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [efacbf6215](https://linux-hardware.org/?probe=efacbf6215) | Nov 29, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [85ac938c0c](https://linux-hardware.org/?probe=85ac938c0c) | Nov 29, 2022 |
| MSI           | Z370 GAMING PRO CARBON      | Desktop     | [96b383097b](https://linux-hardware.org/?probe=96b383097b) | Nov 29, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [a789d492a4](https://linux-hardware.org/?probe=a789d492a4) | Nov 28, 2022 |
| Lenovo        | ThinkPad T470p 20J60018M... | Notebook    | [c5f7049b04](https://linux-hardware.org/?probe=c5f7049b04) | Nov 28, 2022 |
| Lenovo        | ThinkPad E580 20KS001QMX    | Notebook    | [97fda88c7b](https://linux-hardware.org/?probe=97fda88c7b) | Nov 28, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [8f8f53c15b](https://linux-hardware.org/?probe=8f8f53c15b) | Nov 27, 2022 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [ac8f0475f1](https://linux-hardware.org/?probe=ac8f0475f1) | Nov 27, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [669f6eaf1c](https://linux-hardware.org/?probe=669f6eaf1c) | Nov 26, 2022 |
| ASUSTek       | GA15DH                      | Desktop     | [ec6d666a16](https://linux-hardware.org/?probe=ec6d666a16) | Nov 24, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [b59180988d](https://linux-hardware.org/?probe=b59180988d) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [9758f3268e](https://linux-hardware.org/?probe=9758f3268e) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | Notebook    | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [7121172cc6](https://linux-hardware.org/?probe=7121172cc6) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [c150f785ea](https://linux-hardware.org/?probe=c150f785ea) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [52b55ea024](https://linux-hardware.org/?probe=52b55ea024) | Nov 21, 2022 |
| Dell          | XPS 9320                    | Notebook    | [7ea2296eaf](https://linux-hardware.org/?probe=7ea2296eaf) | Nov 21, 2022 |
| AZW           | GTR V01                     | Mini pc     | [2042d4c2c0](https://linux-hardware.org/?probe=2042d4c2c0) | Nov 21, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [71cb60b441](https://linux-hardware.org/?probe=71cb60b441) | Nov 21, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4f36ecd91b](https://linux-hardware.org/?probe=4f36ecd91b) | Nov 19, 2022 |
| ASRock        | Z790 PG Riptide             | Desktop     | [c852740256](https://linux-hardware.org/?probe=c852740256) | Nov 19, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f10fc36516](https://linux-hardware.org/?probe=f10fc36516) | Nov 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [3534f07f4a](https://linux-hardware.org/?probe=3534f07f4a) | Nov 18, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [86a2f7caea](https://linux-hardware.org/?probe=86a2f7caea) | Nov 18, 2022 |
| Dell          | Latitude 5310               | Notebook    | [8c9625dc17](https://linux-hardware.org/?probe=8c9625dc17) | Nov 17, 2022 |
| Dell          | Latitude 5310               | Notebook    | [958c48cd54](https://linux-hardware.org/?probe=958c48cd54) | Nov 17, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [4c5a2a2f55](https://linux-hardware.org/?probe=4c5a2a2f55) | Nov 16, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [e6600fae5a](https://linux-hardware.org/?probe=e6600fae5a) | Nov 16, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [6cb0948dfd](https://linux-hardware.org/?probe=6cb0948dfd) | Nov 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [64fb474239](https://linux-hardware.org/?probe=64fb474239) | Nov 14, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [08e4620733](https://linux-hardware.org/?probe=08e4620733) | Nov 13, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fa18a7779e](https://linux-hardware.org/?probe=fa18a7779e) | Nov 13, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0bc3c759d6](https://linux-hardware.org/?probe=0bc3c759d6) | Nov 13, 2022 |
| ASUSTek       | 2A73h                       | Desktop     | [557fb98d98](https://linux-hardware.org/?probe=557fb98d98) | Nov 13, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [aea8b4a908](https://linux-hardware.org/?probe=aea8b4a908) | Nov 12, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [4aa0411587](https://linux-hardware.org/?probe=4aa0411587) | Nov 12, 2022 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [091c048c2a](https://linux-hardware.org/?probe=091c048c2a) | Nov 12, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [8dee2ceeb0](https://linux-hardware.org/?probe=8dee2ceeb0) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [6eedcdeb01](https://linux-hardware.org/?probe=6eedcdeb01) | Nov 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [48f127b453](https://linux-hardware.org/?probe=48f127b453) | Nov 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [fd835d99e7](https://linux-hardware.org/?probe=fd835d99e7) | Nov 10, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [fae66184f2](https://linux-hardware.org/?probe=fae66184f2) | Nov 10, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| Acer          | Aspire A515-52              | Notebook    | [ed07b564ec](https://linux-hardware.org/?probe=ed07b564ec) | Nov 07, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b6768dd5b7](https://linux-hardware.org/?probe=b6768dd5b7) | Nov 07, 2022 |
| HP            | 828A                        | Desktop     | [42d15a94b0](https://linux-hardware.org/?probe=42d15a94b0) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [92c837ff5a](https://linux-hardware.org/?probe=92c837ff5a) | Nov 06, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [298819594a](https://linux-hardware.org/?probe=298819594a) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [2765ed4857](https://linux-hardware.org/?probe=2765ed4857) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | Notebook    | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [dd2877fcc2](https://linux-hardware.org/?probe=dd2877fcc2) | Nov 05, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [d95735860b](https://linux-hardware.org/?probe=d95735860b) | Nov 05, 2022 |
| Acer          | Predator G3610              | Desktop     | [783c053a62](https://linux-hardware.org/?probe=783c053a62) | Nov 05, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [7590df932b](https://linux-hardware.org/?probe=7590df932b) | Nov 05, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [ad1ae18c98](https://linux-hardware.org/?probe=ad1ae18c98) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b2af134ab3](https://linux-hardware.org/?probe=b2af134ab3) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [9d1ba43c71](https://linux-hardware.org/?probe=9d1ba43c71) | Nov 04, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [dac055fa29](https://linux-hardware.org/?probe=dac055fa29) | Nov 04, 2022 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [1866954ec7](https://linux-hardware.org/?probe=1866954ec7) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [5c0a96cd5b](https://linux-hardware.org/?probe=5c0a96cd5b) | Nov 04, 2022 |
| HP            | 2B05                        | Desktop     | [95b5255056](https://linux-hardware.org/?probe=95b5255056) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [442942f712](https://linux-hardware.org/?probe=442942f712) | Nov 04, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [df00a6281b](https://linux-hardware.org/?probe=df00a6281b) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [2ec155a4b6](https://linux-hardware.org/?probe=2ec155a4b6) | Nov 03, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [ec359017a2](https://linux-hardware.org/?probe=ec359017a2) | Nov 02, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [72467c5d61](https://linux-hardware.org/?probe=72467c5d61) | Oct 31, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d99707ef15](https://linux-hardware.org/?probe=d99707ef15) | Oct 29, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [063675c104](https://linux-hardware.org/?probe=063675c104) | Oct 29, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e51ca052ec](https://linux-hardware.org/?probe=e51ca052ec) | Oct 28, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [cd6e5e2095](https://linux-hardware.org/?probe=cd6e5e2095) | Oct 27, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [3c67c8efb7](https://linux-hardware.org/?probe=3c67c8efb7) | Oct 27, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [f95081e76e](https://linux-hardware.org/?probe=f95081e76e) | Oct 27, 2022 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [0fcfd33f95](https://linux-hardware.org/?probe=0fcfd33f95) | Oct 27, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [daf7975ca0](https://linux-hardware.org/?probe=daf7975ca0) | Oct 26, 2022 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [51cf8b4f9d](https://linux-hardware.org/?probe=51cf8b4f9d) | Oct 25, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | 2B05                        | Desktop     | [c059b9a786](https://linux-hardware.org/?probe=c059b9a786) | Oct 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [302efb993a](https://linux-hardware.org/?probe=302efb993a) | Oct 22, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [8f3fdb4d9c](https://linux-hardware.org/?probe=8f3fdb4d9c) | Oct 22, 2022 |
| Valve         | Jupiter                     | Notebook    | [024fdc987b](https://linux-hardware.org/?probe=024fdc987b) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| Valve         | Jupiter                     | Notebook    | [6249475f24](https://linux-hardware.org/?probe=6249475f24) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [f3ac5bf3df](https://linux-hardware.org/?probe=f3ac5bf3df) | Oct 20, 2022 |
| HP            | 8056                        | Desktop     | [37ed8a6b64](https://linux-hardware.org/?probe=37ed8a6b64) | Oct 18, 2022 |
| Lenovo        | IdeaPad S340-15APITouch ... | Notebook    | [aa65a51ac6](https://linux-hardware.org/?probe=aa65a51ac6) | Oct 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d727afe327](https://linux-hardware.org/?probe=d727afe327) | Oct 17, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [4138cb5064](https://linux-hardware.org/?probe=4138cb5064) | Oct 17, 2022 |
| HP            | 2AE2                        | Desktop     | [a1a8fcfe49](https://linux-hardware.org/?probe=a1a8fcfe49) | Oct 17, 2022 |
| Apple         | MacBookAir6,1               | Notebook    | [2438851671](https://linux-hardware.org/?probe=2438851671) | Oct 16, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [10a3014c1a](https://linux-hardware.org/?probe=10a3014c1a) | Oct 16, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [4f03e84827](https://linux-hardware.org/?probe=4f03e84827) | Oct 16, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [8457aa21e7](https://linux-hardware.org/?probe=8457aa21e7) | Oct 16, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [4f52cb1040](https://linux-hardware.org/?probe=4f52cb1040) | Oct 15, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [689281cab0](https://linux-hardware.org/?probe=689281cab0) | Oct 15, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [6def734895](https://linux-hardware.org/?probe=6def734895) | Oct 14, 2022 |
| Acer          | Aspire 8950G                | Notebook    | [8888f23e03](https://linux-hardware.org/?probe=8888f23e03) | Oct 14, 2022 |
| Lenovo        | ThinkPad E595 20NF001HMX    | Notebook    | [1ae4e8967a](https://linux-hardware.org/?probe=1ae4e8967a) | Oct 14, 2022 |
| Gigabyte      | AB350M-HD3-CF se1           | Desktop     | [89060aa147](https://linux-hardware.org/?probe=89060aa147) | Oct 13, 2022 |
| Gigabyte      | P65Q                        | Notebook    | [8e83936c53](https://linux-hardware.org/?probe=8e83936c53) | Oct 12, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [512238de46](https://linux-hardware.org/?probe=512238de46) | Oct 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [10ea852e71](https://linux-hardware.org/?probe=10ea852e71) | Oct 12, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [27b7798784](https://linux-hardware.org/?probe=27b7798784) | Oct 11, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [ef1a363500](https://linux-hardware.org/?probe=ef1a363500) | Oct 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [7b6f3fcf28](https://linux-hardware.org/?probe=7b6f3fcf28) | Oct 10, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4564037395](https://linux-hardware.org/?probe=4564037395) | Oct 07, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [c52e60caae](https://linux-hardware.org/?probe=c52e60caae) | Oct 06, 2022 |
| Microsoft     | Surface Pro 7               | Tablet      | [92704e062f](https://linux-hardware.org/?probe=92704e062f) | Oct 05, 2022 |
| MSI           | MEG Z490I UNIFY             | Desktop     | [a60e3c519e](https://linux-hardware.org/?probe=a60e3c519e) | Oct 05, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [71da92bd30](https://linux-hardware.org/?probe=71da92bd30) | Oct 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [28d49251c7](https://linux-hardware.org/?probe=28d49251c7) | Oct 04, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [d67f04fc6e](https://linux-hardware.org/?probe=d67f04fc6e) | Oct 02, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [16a6152e10](https://linux-hardware.org/?probe=16a6152e10) | Oct 02, 2022 |
| Dell          | Latitude E6320              | Notebook    | [69290cc372](https://linux-hardware.org/?probe=69290cc372) | Oct 02, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [e09f793c1a](https://linux-hardware.org/?probe=e09f793c1a) | Oct 01, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9d5f38913b](https://linux-hardware.org/?probe=9d5f38913b) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [37a7291916](https://linux-hardware.org/?probe=37a7291916) | Sep 29, 2022 |
| HP            | 18E5                        | Desktop     | [bcc9927d20](https://linux-hardware.org/?probe=bcc9927d20) | Sep 28, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [6f9bc0cdba](https://linux-hardware.org/?probe=6f9bc0cdba) | Sep 26, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d65cd8309b](https://linux-hardware.org/?probe=d65cd8309b) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [8f29c3dc10](https://linux-hardware.org/?probe=8f29c3dc10) | Sep 24, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [52ddc219ae](https://linux-hardware.org/?probe=52ddc219ae) | Sep 23, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a68d3f20eb](https://linux-hardware.org/?probe=a68d3f20eb) | Sep 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [c81b14b950](https://linux-hardware.org/?probe=c81b14b950) | Sep 23, 2022 |
| Lenovo        | Yoga 13sACN 2021 82CY       | Notebook    | [d374a74e0d](https://linux-hardware.org/?probe=d374a74e0d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e7597fb17](https://linux-hardware.org/?probe=5e7597fb17) | Sep 22, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [5ed0ffde54](https://linux-hardware.org/?probe=5ed0ffde54) | Sep 22, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b35ec1a833](https://linux-hardware.org/?probe=b35ec1a833) | Sep 21, 2022 |
| HP            | Pavilion g7                 | Notebook    | [a5f3f12174](https://linux-hardware.org/?probe=a5f3f12174) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [4d93da1983](https://linux-hardware.org/?probe=4d93da1983) | Sep 20, 2022 |
| HP            | 2B05                        | Desktop     | [18db320ef7](https://linux-hardware.org/?probe=18db320ef7) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4995ae034f](https://linux-hardware.org/?probe=4995ae034f) | Sep 19, 2022 |
| Dell          | Latitude E6320              | Notebook    | [4bf59d7938](https://linux-hardware.org/?probe=4bf59d7938) | Sep 19, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [27b8d384a2](https://linux-hardware.org/?probe=27b8d384a2) | Sep 19, 2022 |
| ASUSTek       | M5A88-V EVO                 | Desktop     | [9dc35eec1a](https://linux-hardware.org/?probe=9dc35eec1a) | Sep 19, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [38d90248df](https://linux-hardware.org/?probe=38d90248df) | Sep 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [4c33a54701](https://linux-hardware.org/?probe=4c33a54701) | Sep 16, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [52fd47ee14](https://linux-hardware.org/?probe=52fd47ee14) | Sep 15, 2022 |
| Dell          | Latitude 7300               | Notebook    | [9802315270](https://linux-hardware.org/?probe=9802315270) | Sep 14, 2022 |
| Dell          | Latitude 7300               | Notebook    | [5d82c4da95](https://linux-hardware.org/?probe=5d82c4da95) | Sep 14, 2022 |
| HP            | 1497                        | Desktop     | [7d44fed5d5](https://linux-hardware.org/?probe=7d44fed5d5) | Sep 13, 2022 |
| HP            | 1497                        | Desktop     | [3afd83b18b](https://linux-hardware.org/?probe=3afd83b18b) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | Notebook    | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [5987ef39e4](https://linux-hardware.org/?probe=5987ef39e4) | Sep 11, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [b8f2004ea5](https://linux-hardware.org/?probe=b8f2004ea5) | Sep 10, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [e77359618c](https://linux-hardware.org/?probe=e77359618c) | Sep 09, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Server      | [cf5955c3e1](https://linux-hardware.org/?probe=cf5955c3e1) | Sep 09, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [082bf17ff0](https://linux-hardware.org/?probe=082bf17ff0) | Sep 08, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| Rockchip      | Unknown                     | Soc         | [37447111b3](https://linux-hardware.org/?probe=37447111b3) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [308047a7cb](https://linux-hardware.org/?probe=308047a7cb) | Sep 07, 2022 |
| Acer          | 1.0                         | Desktop     | [b81c44ff15](https://linux-hardware.org/?probe=b81c44ff15) | Sep 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [b1edd48233](https://linux-hardware.org/?probe=b1edd48233) | Sep 05, 2022 |
| ASUSTek       | PRIME H610M-E D4            | Desktop     | [a8d726946f](https://linux-hardware.org/?probe=a8d726946f) | Sep 04, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [3f17eeffec](https://linux-hardware.org/?probe=3f17eeffec) | Sep 03, 2022 |
| Dell          | Latitude 7300               | Notebook    | [30994e1857](https://linux-hardware.org/?probe=30994e1857) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [4080f853b6](https://linux-hardware.org/?probe=4080f853b6) | Sep 03, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [d54fe6c0ea](https://linux-hardware.org/?probe=d54fe6c0ea) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [47dbe77b54](https://linux-hardware.org/?probe=47dbe77b54) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| Purism        | Librem 14                   | Notebook    | [54d6cbb49d](https://linux-hardware.org/?probe=54d6cbb49d) | Sep 01, 2022 |
| HP            | 18E5                        | Desktop     | [e7c5ab6cc4](https://linux-hardware.org/?probe=e7c5ab6cc4) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| HP            | Pavilion 15                 | Notebook    | [19c7cae23c](https://linux-hardware.org/?probe=19c7cae23c) | Aug 31, 2022 |
| Foxconn       | 2AAF                        | Desktop     | [a23b1b0822](https://linux-hardware.org/?probe=a23b1b0822) | Aug 30, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | Notebook    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [ce2bb0938b](https://linux-hardware.org/?probe=ce2bb0938b) | Aug 26, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [61b05137a7](https://linux-hardware.org/?probe=61b05137a7) | Aug 26, 2022 |
| ASRock        | X99 WS                      | Desktop     | [d16d59fab2](https://linux-hardware.org/?probe=d16d59fab2) | Aug 26, 2022 |
| Foxconn       | P35A01                      | Desktop     | [fa220f1ce6](https://linux-hardware.org/?probe=fa220f1ce6) | Aug 25, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [b19844ee21](https://linux-hardware.org/?probe=b19844ee21) | Aug 25, 2022 |
| ASUSTek       | T100HAN                     | Notebook    | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [6fcc3e058d](https://linux-hardware.org/?probe=6fcc3e058d) | Aug 22, 2022 |
| ASUSTek       | B150M-A                     | Desktop     | [0dac247b92](https://linux-hardware.org/?probe=0dac247b92) | Aug 21, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [c74bbc2f61](https://linux-hardware.org/?probe=c74bbc2f61) | Aug 21, 2022 |
| Samsung       | 935XDB                      | Notebook    | [a8d4f5e6a0](https://linux-hardware.org/?probe=a8d4f5e6a0) | Aug 20, 2022 |
| MSI           | GF63 Thin 10UC              | Notebook    | [b04f79d93a](https://linux-hardware.org/?probe=b04f79d93a) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [87fcf5d702](https://linux-hardware.org/?probe=87fcf5d702) | Aug 19, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [0271f9018f](https://linux-hardware.org/?probe=0271f9018f) | Aug 19, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e2a8c815e](https://linux-hardware.org/?probe=1e2a8c815e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ddc9a7396e](https://linux-hardware.org/?probe=ddc9a7396e) | Aug 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ef1cbed5a4](https://linux-hardware.org/?probe=ef1cbed5a4) | Aug 16, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [cb59c4a321](https://linux-hardware.org/?probe=cb59c4a321) | Aug 15, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [496f0834ae](https://linux-hardware.org/?probe=496f0834ae) | Aug 15, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [63d41691ef](https://linux-hardware.org/?probe=63d41691ef) | Aug 15, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [837159c07a](https://linux-hardware.org/?probe=837159c07a) | Aug 14, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [58d3be66c0](https://linux-hardware.org/?probe=58d3be66c0) | Aug 14, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [6dab67810d](https://linux-hardware.org/?probe=6dab67810d) | Aug 14, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [0b62c9a78f](https://linux-hardware.org/?probe=0b62c9a78f) | Aug 12, 2022 |
| Intel         | NUC6i5SYB H81131-502        | Mini pc     | [2487f351d2](https://linux-hardware.org/?probe=2487f351d2) | Aug 12, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [1091d27582](https://linux-hardware.org/?probe=1091d27582) | Aug 11, 2022 |
| Lenovo        | ThinkPad X201 3626FAG       | Notebook    | [34938e0949](https://linux-hardware.org/?probe=34938e0949) | Aug 11, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [edf947ace6](https://linux-hardware.org/?probe=edf947ace6) | Aug 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [813863fbbf](https://linux-hardware.org/?probe=813863fbbf) | Aug 09, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [3fbc687842](https://linux-hardware.org/?probe=3fbc687842) | Aug 08, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [c530c6e2cb](https://linux-hardware.org/?probe=c530c6e2cb) | Aug 08, 2022 |
| HP            | 304Bh                       | Desktop     | [e1e3f301cb](https://linux-hardware.org/?probe=e1e3f301cb) | Aug 08, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f91ebc68e8](https://linux-hardware.org/?probe=f91ebc68e8) | Aug 08, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [b075418a73](https://linux-hardware.org/?probe=b075418a73) | Aug 07, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [091235281e](https://linux-hardware.org/?probe=091235281e) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Acer          | Veriton N4680G              | Desktop     | [a0f4d75db6](https://linux-hardware.org/?probe=a0f4d75db6) | Aug 06, 2022 |
| Lenovo        | Yoga SLIM 7-14ARE05 82A2    | Notebook    | [431684d65c](https://linux-hardware.org/?probe=431684d65c) | Aug 05, 2022 |
| ASRock        | H270M-ITX/ac                | Desktop     | [273c214064](https://linux-hardware.org/?probe=273c214064) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [a2733a0f87](https://linux-hardware.org/?probe=a2733a0f87) | Aug 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [cdc1f14772](https://linux-hardware.org/?probe=cdc1f14772) | Aug 04, 2022 |
| Samsung       | 700G7C                      | Notebook    | [cd554f5d17](https://linux-hardware.org/?probe=cd554f5d17) | Aug 03, 2022 |
| Dell          | Precision 14 5470           | Notebook    | [089d1a151f](https://linux-hardware.org/?probe=089d1a151f) | Aug 03, 2022 |
| Dell          | 0Y56T3 A00                  | Desktop     | [c52a590c5b](https://linux-hardware.org/?probe=c52a590c5b) | Aug 02, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [64a21844e4](https://linux-hardware.org/?probe=64a21844e4) | Aug 01, 2022 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | Notebook    | [de9a854095](https://linux-hardware.org/?probe=de9a854095) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Sweden/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 272       | 11.75%  |
| Ubuntu 22.04                 | 150       | 6.48%   |
| Ubuntu 18.04                 | 131       | 5.66%   |
| Arch Rolling                 | 63        | 2.72%   |
| Debian 11                    | 56        | 2.42%   |
| Pop!_OS 22.04                | 49        | 2.12%   |
| Pop!_OS 21.04                | 49        | 2.12%   |
| Manjaro                      | 48        | 2.07%   |
| OpenMandriva 4.3             | 41        | 1.77%   |
| Zorin 16                     | 40        | 1.73%   |
| Arch                         | 40        | 1.73%   |
| OpenMandriva 4.2             | 39        | 1.68%   |
| KDE neon 20.04               | 38        | 1.64%   |
| ArcoLinux Rolling            | 37        | 1.6%    |
| Debian 12                    | 36        | 1.56%   |
| Linux Mint 21.1              | 33        | 1.43%   |
| Pop!_OS 20.04                | 31        | 1.34%   |
| Linux Mint 20.3              | 31        | 1.34%   |
| Ubuntu 21.10                 | 29        | 1.25%   |
| Ubuntu 21.04                 | 29        | 1.25%   |
| Pop!_OS 20.10                | 29        | 1.25%   |
| Fedora 37                    | 29        | 1.25%   |
| Fedora 35                    | 29        | 1.25%   |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 1.21%   |
| Ubuntu 19.04                 | 27        | 1.17%   |
| Fedora 34                    | 25        | 1.08%   |
| Ubuntu 19.10                 | 24        | 1.04%   |
| Fedora 38                    | 23        | 0.99%   |
| Fedora 36                    | 23        | 0.99%   |
| Fedora 32                    | 23        | 0.99%   |
| Zorin 15                     | 22        | 0.95%   |
| Linux Mint 20.2              | 20        | 0.86%   |
| Linux Mint 20                | 20        | 0.86%   |
| Xubuntu 20.04                | 19        | 0.82%   |
| Ubuntu 20.10                 | 19        | 0.82%   |
| Fedora 33                    | 19        | 0.82%   |
| Ubuntu 23.04                 | 18        | 0.78%   |
| Linux Mint 20.1              | 17        | 0.73%   |
| Ubuntu 22.10                 | 16        | 0.69%   |
| Fedora 31                    | 15        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 698       | 31.56%  |
| Fedora        | 178       | 8.05%   |
| Linux Mint    | 166       | 7.5%    |
| Pop!_OS       | 164       | 7.41%   |
| Debian        | 125       | 5.65%   |
| OpenMandriva  | 115       | 5.2%    |
| Arch          | 102       | 4.61%   |
| Manjaro       | 96        | 4.34%   |
| Zorin         | 62        | 2.8%    |
| KDE neon      | 50        | 2.26%   |
| Xubuntu       | 44        | 1.99%   |
| ArcoLinux     | 42        | 1.9%    |
| openSUSE      | 35        | 1.58%   |
| Gentoo        | 34        | 1.54%   |
| Kubuntu       | 30        | 1.36%   |
| Kali          | 22        | 0.99%   |
| ROSA          | 20        | 0.9%    |
| EndeavourOS   | 17        | 0.77%   |
| Elementary    | 17        | 0.77%   |
| Ubuntu MATE   | 16        | 0.72%   |
| CentOS        | 14        | 0.63%   |
| Nobara        | 10        | 0.45%   |
| Endless       | 10        | 0.45%   |
| Clear Linux   | 10        | 0.45%   |
| SteamOS       | 9         | 0.41%   |
| LMDE          | 9         | 0.41%   |
| Ubuntu Unity  | 8         | 0.36%   |
| MX            | 8         | 0.36%   |
| Lubuntu       | 7         | 0.32%   |
| Garuda Linux  | 7         | 0.32%   |
| Ubuntu Budgie | 6         | 0.27%   |
| Peppermint    | 6         | 0.27%   |
| Parrot        | 6         | 0.27%   |
| BunsenLabs    | 6         | 0.27%   |
| Solus         | 5         | 0.23%   |
| Slackware     | 4         | 0.18%   |
| Raspbian      | 4         | 0.18%   |
| BlackPanther  | 4         | 0.18%   |
| Alpine        | 4         | 0.18%   |
| Ubuntu Studio | 3         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 39        | 1.54%   |
| 5.10.14-desktop-1omv4002 | 39        | 1.54%   |
| 5.4.0-42-generic         | 33        | 1.3%    |
| 5.15.0-56-generic        | 29        | 1.14%   |
| 5.4.0-58-generic         | 21        | 0.83%   |
| 5.4.0-48-generic         | 20        | 0.79%   |
| 5.15.0-52-generic        | 19        | 0.75%   |
| 5.11.0-7620-generic      | 19        | 0.75%   |
| 5.3.0-40-generic         | 17        | 0.67%   |
| 5.13.0-7614-generic      | 17        | 0.67%   |
| 5.4.0-52-generic         | 16        | 0.63%   |
| 5.15.0-46-generic        | 15        | 0.59%   |
| 5.13.0-30-generic        | 15        | 0.59%   |
| 5.4.0-40-generic         | 14        | 0.55%   |
| 5.15.0-58-generic        | 14        | 0.55%   |
| 5.13.0-39-generic        | 14        | 0.55%   |
| 6.2.6-76060206-generic   | 13        | 0.51%   |
| 5.4.0-7634-generic       | 13        | 0.51%   |
| 5.15.0-48-generic        | 13        | 0.51%   |
| 5.4.0-54-generic         | 12        | 0.47%   |
| 5.4.0-33-generic         | 12        | 0.47%   |
| 5.15.0-78-generic        | 12        | 0.47%   |
| 5.11.0-37-generic        | 12        | 0.47%   |
| 6.2.6-desktop-1omv2390   | 11        | 0.43%   |
| 6.1.0-7-amd64            | 11        | 0.43%   |
| 5.8.0-48-generic         | 11        | 0.43%   |
| 5.4.0-70-generic         | 11        | 0.43%   |
| 5.19.0-35-generic        | 11        | 0.43%   |
| 5.15.0-60-generic        | 11        | 0.43%   |
| 5.15.0-53-generic        | 11        | 0.43%   |
| 5.15.0-50-generic        | 11        | 0.43%   |
| 5.11.0-7614-generic      | 11        | 0.43%   |
| 5.10.0-8-amd64           | 11        | 0.43%   |
| 6.2.0-20-generic         | 10        | 0.39%   |
| 6.1.0-9-amd64            | 10        | 0.39%   |
| 5.8.0-43-generic         | 10        | 0.39%   |
| 5.4.0-65-generic         | 10        | 0.39%   |
| 5.4.0-29-generic         | 10        | 0.39%   |
| 5.19.0-38-generic        | 10        | 0.39%   |
| 5.15.0-41-generic        | 10        | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 339       | 14.02%  |
| 5.15.0  | 220       | 9.1%    |
| 5.11.0  | 129       | 5.33%   |
| 5.13.0  | 120       | 4.96%   |
| 5.8.0   | 98        | 4.05%   |
| 4.15.0  | 81        | 3.35%   |
| 5.3.0   | 76        | 3.14%   |
| 5.10.0  | 76        | 3.14%   |
| 5.19.0  | 73        | 3.02%   |
| 5.0.0   | 59        | 2.44%   |
| 6.1.0   | 53        | 2.19%   |
| 4.18.0  | 47        | 1.94%   |
| 5.16.7  | 40        | 1.65%   |
| 5.10.14 | 40        | 1.65%   |
| 6.2.0   | 38        | 1.57%   |
| 6.2.6   | 25        | 1.03%   |
| 5.17.5  | 13        | 0.54%   |
| 5.14.0  | 13        | 0.54%   |
| 6.1.1   | 12        | 0.5%    |
| 4.19.0  | 11        | 0.45%   |
| 6.2.9   | 10        | 0.41%   |
| 6.0.12  | 10        | 0.41%   |
| 5.18.0  | 10        | 0.41%   |
| 5.12.4  | 10        | 0.41%   |
| 5.17.1  | 9         | 0.37%   |
| 6.4.11  | 8         | 0.33%   |
| 5.16.0  | 8         | 0.33%   |
| 6.4.0   | 7         | 0.29%   |
| 6.3.1   | 7         | 0.29%   |
| 6.1.12  | 7         | 0.29%   |
| 5.7.0   | 7         | 0.29%   |
| 5.19.16 | 7         | 0.29%   |
| 5.15.7  | 7         | 0.29%   |
| 6.4.3   | 6         | 0.25%   |
| 6.3.8   | 6         | 0.25%   |
| 6.3.7   | 6         | 0.25%   |
| 6.3.0   | 6         | 0.25%   |
| 6.1.11  | 6         | 0.25%   |
| 5.9.0   | 6         | 0.25%   |
| 5.8.1   | 6         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 369       | 15.55%  |
| 5.15    | 285       | 12.01%  |
| 5.10    | 162       | 6.83%   |
| 5.11    | 158       | 6.66%   |
| 5.13    | 140       | 5.9%    |
| 5.8     | 135       | 5.69%   |
| 6.1     | 108       | 4.55%   |
| 6.2     | 94        | 3.96%   |
| 5.19    | 91        | 3.83%   |
| 5.3     | 88        | 3.71%   |
| 5.16    | 81        | 3.41%   |
| 4.15    | 81        | 3.41%   |
| 5.0     | 62        | 2.61%   |
| 4.18    | 54        | 2.28%   |
| 5.17    | 48        | 2.02%   |
| 6.0     | 46        | 1.94%   |
| 6.4     | 43        | 1.81%   |
| 6.3     | 41        | 1.73%   |
| 5.18    | 37        | 1.56%   |
| 5.12    | 36        | 1.52%   |
| 5.14    | 35        | 1.47%   |
| 5.9     | 33        | 1.39%   |
| 5.6     | 28        | 1.18%   |
| 5.7     | 24        | 1.01%   |
| 4.19    | 23        | 0.97%   |
| 4.9     | 16        | 0.67%   |
| 5.5     | 15        | 0.63%   |
| 5.1     | 7         | 0.29%   |
| 5.2     | 6         | 0.25%   |
| 4.4     | 6         | 0.25%   |
| 6.5     | 5         | 0.21%   |
| 4.14    | 3         | 0.13%   |
| 4.1     | 3         | 0.13%   |
| 4.20    | 2         | 0.08%   |
| 4.12    | 2         | 0.08%   |
| 3.10    | 2         | 0.08%   |
| 5       | 1         | 0.04%   |
| 4.16    | 1         | 0.04%   |
| 4.13    | 1         | 0.04%   |
| 3.2     | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2074      | 97.74%  |
| i686    | 25        | 1.18%   |
| aarch64 | 15        | 0.71%   |
| armv7l  | 6         | 0.28%   |
| i586    | 1         | 0.05%   |
| armv8l  | 1         | 0.05%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1043      | 46.75%  |
| KDE5            | 316       | 14.16%  |
| Unknown         | 280       | 12.55%  |
| XFCE            | 173       | 7.75%   |
| X-Cinnamon      | 142       | 6.36%   |
| KDE             | 71        | 3.18%   |
| MATE            | 43        | 1.93%   |
| Cinnamon        | 20        | 0.9%    |
| i3              | 18        | 0.81%   |
| Pantheon        | 16        | 0.72%   |
| LXQt            | 16        | 0.72%   |
| LXDE            | 14        | 0.63%   |
| KDE4            | 11        | 0.49%   |
| Budgie          | 10        | 0.45%   |
| Unity           | 9         | 0.4%    |
| Deepin          | 7         | 0.31%   |
| awesome         | 6         | 0.27%   |
| sway            | 5         | 0.22%   |
| GNOME Flashback | 5         | 0.22%   |
| GNOME Classic   | 5         | 0.22%   |
| Openbox         | 4         | 0.18%   |
| DWM             | 3         | 0.13%   |
| BunsenLabs      | 3         | 0.13%   |
| qtile           | 2         | 0.09%   |
| LeftWM          | 2         | 0.09%   |
| xmonad          | 1         | 0.04%   |
| Trinity         | 1         | 0.04%   |
| spectrwm        | 1         | 0.04%   |
| Hyprland        | 1         | 0.04%   |
| GNOME-Flashback | 1         | 0.04%   |
| Enlightenment   | 1         | 0.04%   |
| bspwm           | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1569      | 71.87%  |
| Wayland     | 394       | 18.05%  |
| Unknown     | 138       | 6.32%   |
| Tty         | 81        | 3.71%   |
| Unspecified | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1124      | 50.74%  |
| SDDM    | 281       | 12.69%  |
| GDM3    | 272       | 12.28%  |
| GDM     | 240       | 10.84%  |
| LightDM | 203       | 9.16%   |
| TDM     | 63        | 2.84%   |
| KDM     | 11        | 0.5%    |
| XDM     | 7         | 0.32%   |
| LXDM    | 7         | 0.32%   |
| Ly      | 6         | 0.27%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| en_US       | 1052      | 48.17%  |
| sv_SE       | 602       | 27.56%  |
| Unknown     | 227       | 10.39%  |
| en_GB       | 140       | 6.41%   |
| C           | 53        | 2.43%   |
| de_DE       | 17        | 0.78%   |
| ru_RU       | 15        | 0.69%   |
| en_SE       | 8         | 0.37%   |
| pl_PL       | 7         | 0.32%   |
| en_DK       | 7         | 0.32%   |
| uk_UA       | 4         | 0.18%   |
| fr_FR       | 4         | 0.18%   |
| nb_NO       | 3         | 0.14%   |
| fi_FI       | 3         | 0.14%   |
| en_IE       | 3         | 0.14%   |
| en_CA       | 3         | 0.14%   |
| en_AG       | 3         | 0.14%   |
| bg_BG       | 3         | 0.14%   |
| zh_CN       | 2         | 0.09%   |
| POSIX       | 2         | 0.09%   |
| lt_LT       | 2         | 0.09%   |
| it_IT       | 2         | 0.09%   |
| en_US.utf-8 | 2         | 0.09%   |
| el_GR       | 2         | 0.09%   |
| C.UTF8      | 2         | 0.09%   |
| UTF-8       | 1         | 0.05%   |
| tr_TR       | 1         | 0.05%   |
| sv_SE.UTF8  | 1         | 0.05%   |
| sv_FI       | 1         | 0.05%   |
| sma_SE      | 1         | 0.05%   |
| nn_NO       | 1         | 0.05%   |
| hu_HU       | 1         | 0.05%   |
| hr_HR       | 1         | 0.05%   |
| gl_ES       | 1         | 0.05%   |
| es_VE       | 1         | 0.05%   |
| es_ES       | 1         | 0.05%   |
| en_IN       | 1         | 0.05%   |
| en_GB.UTF8  | 1         | 0.05%   |
| en_GB.utf-8 | 1         | 0.05%   |
| en_AU       | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1137      | 52.11%  |
| BIOS | 1045      | 47.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1604      | 73.21%  |
| Btrfs    | 252       | 11.5%   |
| Overlay  | 143       | 6.53%   |
| Tmpfs    | 60        | 2.74%   |
| Unknown  | 59        | 2.69%   |
| Xfs      | 37        | 1.69%   |
| Zfs      | 19        | 0.87%   |
| Ext2     | 7         | 0.32%   |
| F2fs     | 6         | 0.27%   |
| Ext3     | 2         | 0.09%   |
| XXXXXXX  | 1         | 0.05%   |
| Reiserfs | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1127      | 51.32%  |
| GPT     | 882       | 40.16%  |
| MBR     | 187       | 8.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1889      | 87.37%  |
| Yes       | 273       | 12.63%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1644      | 76.15%  |
| Yes       | 515       | 23.85%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 471       | 22.2%   |
| Lenovo                  | 320       | 15.08%  |
| Hewlett-Packard         | 308       | 14.51%  |
| Dell                    | 227       | 10.7%   |
| MSI                     | 153       | 7.21%   |
| Gigabyte Technology     | 133       | 6.27%   |
| Acer                    | 105       | 4.95%   |
| Apple                   | 70        | 3.3%    |
| ASRock                  | 49        | 2.31%   |
| Intel                   | 29        | 1.37%   |
| Toshiba                 | 17        | 0.8%    |
| Raspberry Pi Foundation | 17        | 0.8%    |
| Fujitsu                 | 17        | 0.8%    |
| Sony                    | 15        | 0.71%   |
| Packard Bell            | 13        | 0.61%   |
| Unknown                 | 12        | 0.57%   |
| Samsung Electronics     | 11        | 0.52%   |
| Notebook                | 9         | 0.42%   |
| Google                  | 9         | 0.42%   |
| Supermicro              | 8         | 0.38%   |
| Valve                   | 7         | 0.33%   |
| Microsoft               | 7         | 0.33%   |
| Fujitsu Siemens         | 7         | 0.33%   |
| Foxconn                 | 7         | 0.33%   |
| Pegatron                | 6         | 0.28%   |
| AAEON                   | 5         | 0.24%   |
| Maxtang                 | 4         | 0.19%   |
| HUAWEI                  | 4         | 0.19%   |
| Alienware               | 4         | 0.19%   |
| TUXEDO                  | 3         | 0.14%   |
| Star Labs               | 3         | 0.14%   |
| Clevo                   | 3         | 0.14%   |
| Timi                    | 2         | 0.09%   |
| Shuttle                 | 2         | 0.09%   |
| Schenker                | 2         | 0.09%   |
| Razer                   | 2         | 0.09%   |
| PC Specialist           | 2         | 0.09%   |
| OEM                     | 2         | 0.09%   |
| Linx                    | 2         | 0.09%   |
| LG Electronics          | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 22        | 1.04%   |
| Unknown                            | 16        | 0.75%   |
| ASUS ROG STRIX B450-F GAMING       | 12        | 0.57%   |
| ASUS ROG STRIX X570-F GAMING       | 10        | 0.47%   |
| ASUS ROG STRIX B550-F GAMING       | 9         | 0.42%   |
| MSI MS-7C37                        | 8         | 0.38%   |
| ASUS PRIME X470-PRO                | 8         | 0.38%   |
| Valve Jupiter                      | 7         | 0.33%   |
| Dell XPS 13 9370                   | 7         | 0.33%   |
| ASUS Z170 PRO GAMING               | 7         | 0.33%   |
| MSI MS-7C02                        | 6         | 0.28%   |
| HP EliteBook Folio 9470m           | 6         | 0.28%   |
| Dell Precision 5540                | 6         | 0.28%   |
| Apple MacBookPro9,2                | 6         | 0.28%   |
| MSI MS-7C52                        | 5         | 0.24%   |
| MSI MS-7817                        | 5         | 0.24%   |
| Lenovo Yoga C740-14IML 81TC        | 5         | 0.24%   |
| Lenovo MIIX 310-10ICR 80SG         | 5         | 0.24%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5   | 5         | 0.24%   |
| HP ProBook 640 G1                  | 5         | 0.24%   |
| HP Pavilion dv7                    | 5         | 0.24%   |
| HP Pavilion 15                     | 5         | 0.24%   |
| HP EliteBook 840 G3                | 5         | 0.24%   |
| HP EliteBook 840 G2                | 5         | 0.24%   |
| Gigabyte B550 AORUS ELITE V2       | 5         | 0.24%   |
| Gigabyte B450M DS3H                | 5         | 0.24%   |
| Dell XPS 15 9570                   | 5         | 0.24%   |
| Dell XPS 13 9310                   | 5         | 0.24%   |
| Dell OptiPlex 7010                 | 5         | 0.24%   |
| ASUS TUF Gaming X570-PLUS          | 5         | 0.24%   |
| ASUS ROG STRIX Z390-F GAMING       | 5         | 0.24%   |
| ASUS ROG STRIX B550-I GAMING       | 5         | 0.24%   |
| ASUS ROG STRIX B350-F GAMING       | 5         | 0.24%   |
| ASUS PRIME X370-PRO                | 5         | 0.24%   |
| ASUS M5A97 R2.0                    | 5         | 0.24%   |
| Apple MacBookPro8,1                | 5         | 0.24%   |
| Apple MacBookPro11,3               | 5         | 0.24%   |
| Acer Aspire V3-571                 | 5         | 0.24%   |
| RPi Raspberry Pi 4 Model B Rev 1.4 | 4         | 0.19%   |
| Maxtang FP30                       | 4         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 175       | 8.25%   |
| ASUS ROG              | 110       | 5.18%   |
| HP EliteBook          | 87        | 4.1%    |
| Acer Aspire           | 67        | 3.16%   |
| Dell Latitude         | 66        | 3.11%   |
| ASUS PRIME            | 53        | 2.5%    |
| Dell Precision        | 52        | 2.45%   |
| Dell XPS              | 47        | 2.21%   |
| HP Pavilion           | 42        | 1.98%   |
| Lenovo IdeaPad        | 41        | 1.93%   |
| HP ProBook            | 39        | 1.84%   |
| Dell OptiPlex         | 31        | 1.46%   |
| HP Compaq             | 28        | 1.32%   |
| Lenovo Yoga           | 25        | 1.18%   |
| ASUS TUF              | 22        | 1.04%   |
| ASUS All              | 22        | 1.04%   |
| ASUS VivoBook         | 21        | 0.99%   |
| HP ZBook              | 19        | 0.9%    |
| RPi Raspberry         | 17        | 0.8%    |
| HP ENVY               | 17        | 0.8%    |
| HP Laptop             | 16        | 0.75%   |
| Unknown               | 16        | 0.75%   |
| Toshiba Satellite     | 14        | 0.66%   |
| Dell Inspiron         | 13        | 0.61%   |
| Lenovo Legion         | 12        | 0.57%   |
| HP EliteDesk          | 12        | 0.57%   |
| ASUS ZenBook          | 12        | 0.57%   |
| Dell Vostro           | 11        | 0.52%   |
| Gigabyte X570         | 10        | 0.47%   |
| ASUS P8Z77-V          | 10        | 0.47%   |
| Acer Swift            | 10        | 0.47%   |
| Packard Bell EasyNote | 9         | 0.42%   |
| Lenovo ThinkCentre    | 9         | 0.42%   |
| Lenovo IdeaCentre     | 9         | 0.42%   |
| Acer Predator         | 9         | 0.42%   |
| MSI MS-7C37           | 8         | 0.38%   |
| Gigabyte B450M        | 8         | 0.38%   |
| ASUS SABERTOOTH       | 8         | 0.38%   |
| ASUS ASUS             | 8         | 0.38%   |
| Acer Nitro            | 8         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 226       | 10.65%  |
| 2019    | 207       | 9.75%   |
| 2020    | 187       | 8.81%   |
| 2021    | 158       | 7.45%   |
| 2013    | 158       | 7.45%   |
| 2012    | 154       | 7.26%   |
| 2011    | 148       | 6.97%   |
| 2017    | 147       | 6.93%   |
| 2015    | 132       | 6.22%   |
| 2014    | 117       | 5.51%   |
| 2016    | 112       | 5.28%   |
| 2010    | 93        | 4.38%   |
| 2022    | 83        | 3.91%   |
| 2008    | 57        | 2.69%   |
| 2009    | 55        | 2.59%   |
| 2007    | 38        | 1.79%   |
| Unknown | 16        | 0.75%   |
| 2023    | 13        | 0.61%   |
| 2006    | 10        | 0.47%   |
| 2005    | 8         | 0.38%   |
| 2004    | 2         | 0.09%   |
| 2002    | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1094      | 51.56%  |
| Desktop        | 849       | 40.01%  |
| Convertible    | 63        | 2.97%   |
| Mini pc        | 43        | 2.03%   |
| System on chip | 19        | 0.9%    |
| All in one     | 19        | 0.9%    |
| Tablet         | 18        | 0.85%   |
| Server         | 14        | 0.66%   |
| Phone          | 3         | 0.14%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1942      | 91%     |
| Enabled  | 192       | 9%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2109      | 99.39%  |
| Yes  | 13        | 0.61%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 510       | 23.69%  |
| 4.01-8.0        | 465       | 21.6%   |
| 8.01-16.0       | 368       | 17.09%  |
| 32.01-64.0      | 334       | 15.51%  |
| 3.01-4.0        | 267       | 12.4%   |
| 64.01-256.0     | 74        | 3.44%   |
| 1.01-2.0        | 57        | 2.65%   |
| 24.01-32.0      | 42        | 1.95%   |
| 0.51-1.0        | 17        | 0.79%   |
| 2.01-3.0        | 16        | 0.74%   |
| More than 256.0 | 2         | 0.09%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 728       | 31.06%  |
| 2.01-3.0   | 574       | 24.49%  |
| 4.01-8.0   | 434       | 18.52%  |
| 3.01-4.0   | 324       | 13.82%  |
| 8.01-16.0  | 123       | 5.25%   |
| 0.51-1.0   | 103       | 4.39%   |
| 16.01-24.0 | 28        | 1.19%   |
| 0.01-0.5   | 23        | 0.98%   |
| 24.01-32.0 | 5         | 0.21%   |
| 32.01-64.0 | 1         | 0.04%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1302      | 59.53%  |
| 2      | 461       | 21.08%  |
| 3      | 188       | 8.6%    |
| 4      | 111       | 5.08%   |
| 5      | 45        | 2.06%   |
| 6      | 32        | 1.46%   |
| 0      | 21        | 0.96%   |
| 7      | 17        | 0.78%   |
| 8      | 5         | 0.23%   |
| 10     | 2         | 0.09%   |
| 26     | 1         | 0.05%   |
| 11     | 1         | 0.05%   |
| 9      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1465      | 68.62%  |
| Yes       | 670       | 31.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1835      | 86.27%  |
| No        | 292       | 13.73%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1556      | 72.71%  |
| No        | 584       | 27.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1329      | 61.7%   |
| No        | 825       | 38.3%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Sweden  | 2122      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Stockholm               | 417       | 18.23%  |
| Gothenburg              | 230       | 10.06%  |
| Malmo                   | 110       | 4.81%   |
| Uppsala                 | 62        | 2.71%   |
| Lund                    | 46        | 2.01%   |
| Linköping              | 41        | 1.79%   |
| Västerås              | 38        | 1.66%   |
| Sollentuna              | 29        | 1.27%   |
| Bromma                  | 29        | 1.27%   |
| Umeå                   | 27        | 1.18%   |
| Vaxjo                   | 25        | 1.09%   |
| Norrköping             | 25        | 1.09%   |
| Solna                   | 24        | 1.05%   |
| Saltsjoe-Boo            | 24        | 1.05%   |
| Örebro                 | 24        | 1.05%   |
| Sundsvall               | 23        | 1.01%   |
| Sundbyberg              | 20        | 0.87%   |
| Vaestra Froelunda       | 19        | 0.83%   |
| Karlstad                | 19        | 0.83%   |
| Haegersten              | 19        | 0.83%   |
| Karlskrona              | 18        | 0.79%   |
| Huddinge                | 17        | 0.74%   |
| Helsingborg             | 17        | 0.74%   |
| Taby                    | 16        | 0.7%    |
| Bandhagen               | 16        | 0.7%    |
| Södertälje            | 15        | 0.66%   |
| Gävle                  | 15        | 0.66%   |
| Kista                   | 14        | 0.61%   |
| Halmstad                | 14        | 0.61%   |
| Nyköping               | 13        | 0.57%   |
| Norsborg                | 13        | 0.57%   |
| Spanga                  | 12        | 0.52%   |
| Moelndal                | 12        | 0.52%   |
| Staffanstorp            | 11        | 0.48%   |
| Skövde                 | 11        | 0.48%   |
| Landskrona              | 11        | 0.48%   |
| Katrineholm             | 11        | 0.48%   |
| Järfälla Municipality | 11        | 0.48%   |
| Upplands Vasby          | 10        | 0.44%   |
| Luleå                  | 10        | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 713       | 1143   | 22.53%  |
| WDC                         | 415       | 668    | 13.12%  |
| Seagate                     | 385       | 627    | 12.17%  |
| Kingston                    | 245       | 347    | 7.74%   |
| Intel                       | 173       | 226    | 5.47%   |
| SanDisk                     | 160       | 205    | 5.06%   |
| Toshiba                     | 156       | 207    | 4.93%   |
| Unknown                     | 112       | 142    | 3.54%   |
| Hitachi                     | 87        | 122    | 2.75%   |
| SK hynix                    | 86        | 99     | 2.72%   |
| Crucial                     | 77        | 109    | 2.43%   |
| Micron Technology           | 72        | 86     | 2.28%   |
| HGST                        | 50        | 60     | 1.58%   |
| Apple                       | 36        | 44     | 1.14%   |
| Kingston Technology Company | 25        | 32     | 0.79%   |
| Corsair                     | 25        | 34     | 0.79%   |
| Phison                      | 23        | 27     | 0.73%   |
| OCZ                         | 23        | 29     | 0.73%   |
| A-DATA Technology           | 23        | 24     | 0.73%   |
| LITEON                      | 19        | 25     | 0.6%    |
| KIOXIA                      | 19        | 20     | 0.6%    |
| Phison Electronics          | 15        | 18     | 0.47%   |
| Intenso                     | 12        | 15     | 0.38%   |
| Fujitsu                     | 12        | 18     | 0.38%   |
| Transcend                   | 11        | 12     | 0.35%   |
| LITEONIT                    | 11        | 19     | 0.35%   |
| Silicon Motion              | 10        | 27     | 0.32%   |
| PNY                         | 9         | 11     | 0.28%   |
| China                       | 9         | 9      | 0.28%   |
| Maxtor                      | 7         | 7      | 0.22%   |
| Micron/Crucial Technology   | 6         | 10     | 0.19%   |
| LaCie                       | 6         | 7      | 0.19%   |
| JMicron Technology          | 6         | 6      | 0.19%   |
| ASMT                        | 6         | 6      | 0.19%   |
| Unknown                     | 6         | 6      | 0.19%   |
| SPCC                        | 5         | 15     | 0.16%   |
| Lenovo                      | 5         | 5      | 0.16%   |
| Verbatim                    | 4         | 8      | 0.13%   |
| Hewlett-Packard             | 4         | 6      | 0.13%   |
| XPG                         | 3         | 3      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 55        | 1.52%   |
| Samsung SSD 850 EVO 500GB                           | 44        | 1.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 43        | 1.19%   |
| Kingston SA400S37120G 120GB SSD                     | 37        | 1.02%   |
| Kingston SV300S37A120G 120GB SSD                    | 31        | 0.86%   |
| Kingston SA400S37240G 240GB SSD                     | 31        | 0.86%   |
| Kingston SA400S37480G 480GB SSD                     | 30        | 0.83%   |
| Samsung SSD 860 EVO 250GB                           | 26        | 0.72%   |
| Samsung SSD 840 EVO 250GB                           | 26        | 0.72%   |
| Samsung SSD 860 EVO 500GB                           | 25        | 0.69%   |
| Samsung NVMe SSD Drive 500GB                        | 25        | 0.69%   |
| Seagate ST4000DM004-2CV104 4TB                      | 23        | 0.63%   |
| Samsung NVMe SSD Drive 512GB                        | 20        | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                      | 19        | 0.52%   |
| SanDisk NVMe SSD Drive 1TB                          | 18        | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB                      | 18        | 0.5%    |
| Unknown MMC Card  32GB                              | 17        | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                      | 16        | 0.44%   |
| Samsung SSD 860 EVO 1TB                             | 16        | 0.44%   |
| Samsung NVMe SSD Drive 1TB                          | 16        | 0.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 16        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB                        | 15        | 0.41%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 15        | 0.41%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 15        | 0.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 14        | 0.39%   |
| WDC WD30EFRX-68EUZN0 3TB                            | 14        | 0.39%   |
| Seagate ST500DM002-1BD142 500GB                     | 14        | 0.39%   |
| Seagate ST2000DM006-2DM164 2TB                      | 14        | 0.39%   |
| HGST HTS721010A9E630 1TB                            | 14        | 0.39%   |
| Seagate ST4000VN008-2DR166 4TB                      | 13        | 0.36%   |
| Seagate ST1000DM003-1CH162 1TB                      | 13        | 0.36%   |
| Samsung SSD 970 EVO Plus 1TB                        | 13        | 0.36%   |
| Samsung SSD 840 EVO 500GB                           | 13        | 0.36%   |
| Samsung SM963 2.5" NVMe PCIe SSD 250GB              | 13        | 0.36%   |
| Unknown SD/MMC/MS PRO 128GB                         | 12        | 0.33%   |
| Toshiba NVMe SSD Drive 512GB                        | 12        | 0.33%   |
| Seagate ST9500325AS 500GB                           | 12        | 0.33%   |
| Seagate Expansion 1TB                               | 12        | 0.33%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 12        | 0.33%   |
| Samsung NVMe SSD Drive 1024GB                       | 12        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 379       | 612    | 36.62%  |
| WDC                 | 318       | 529    | 30.72%  |
| Hitachi             | 87        | 122    | 8.41%   |
| Toshiba             | 84        | 115    | 8.12%   |
| Samsung Electronics | 59        | 94     | 5.7%    |
| HGST                | 50        | 60     | 4.83%   |
| Unknown             | 13        | 15     | 1.26%   |
| Fujitsu             | 12        | 18     | 1.16%   |
| Apple               | 11        | 11     | 1.06%   |
| Maxtor              | 6         | 6      | 0.58%   |
| Intenso             | 3         | 3      | 0.29%   |
| ASMedia             | 3         | 3      | 0.29%   |
| Hewlett-Packard     | 2         | 4      | 0.19%   |
| ASMT                | 2         | 2      | 0.19%   |
| USB3.0              | 1         | 1      | 0.1%    |
| SABRENT             | 1         | 1      | 0.1%    |
| MARVELL             | 1         | 1      | 0.1%    |
| LaCie               | 1         | 1      | 0.1%    |
| JMicron Technology  | 1         | 1      | 0.1%    |
| IB                  | 1         | 2      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 399       | 593    | 33.45%  |
| Kingston            | 188       | 263    | 15.76%  |
| Intel               | 99        | 128    | 8.3%    |
| SanDisk             | 77        | 96     | 6.45%   |
| Crucial             | 73        | 103    | 6.12%   |
| WDC                 | 62        | 83     | 5.2%    |
| Micron Technology   | 42        | 54     | 3.52%   |
| SK hynix            | 25        | 28     | 2.1%    |
| OCZ                 | 23        | 29     | 1.93%   |
| Apple               | 23        | 29     | 1.93%   |
| Toshiba             | 20        | 28     | 1.68%   |
| LITEON              | 18        | 24     | 1.51%   |
| Corsair             | 15        | 18     | 1.26%   |
| A-DATA Technology   | 14        | 15     | 1.17%   |
| Transcend           | 11        | 12     | 0.92%   |
| LITEONIT            | 11        | 19     | 0.92%   |
| China               | 9         | 9      | 0.75%   |
| Intenso             | 7         | 7      | 0.59%   |
| PNY                 | 6         | 8      | 0.5%    |
| SPCC                | 5         | 15     | 0.42%   |
| Verbatim            | 4         | 8      | 0.34%   |
| ASMT                | 4         | 4      | 0.34%   |
| M4-CT128            | 3         | 3      | 0.25%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.25%   |
| JMicron Technology  | 3         | 3      | 0.25%   |
| Seagate             | 2         | 4      | 0.17%   |
| Patriot             | 2         | 3      | 0.17%   |
| OCZ-VERTEX3         | 2         | 2      | 0.17%   |
| KingSpec            | 2         | 2      | 0.17%   |
| INTEL SS            | 2         | 3      | 0.17%   |
| GOODRAM             | 2         | 3      | 0.17%   |
| Emtec               | 2         | 2      | 0.17%   |
| Apacer              | 2         | 2      | 0.17%   |
| XSTAR               | 1         | 2      | 0.08%   |
| WDC WDS2            | 1         | 1      | 0.08%   |
| WDC WDS1            | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |
| TO Exter            | 1         | 1      | 0.08%   |
| tigo                | 1         | 1      | 0.08%   |
| Team                | 1         | 1      | 0.08%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1020      | 1641   | 35.89%  |
| HDD     | 849       | 1601   | 29.87%  |
| NVMe    | 832       | 1177   | 29.28%  |
| MMC     | 106       | 126    | 3.73%   |
| Unknown | 35        | 44     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1482      | 3088   | 58.16%  |
| NVMe | 831       | 1173   | 32.61%  |
| SAS  | 129       | 202    | 5.06%   |
| MMC  | 106       | 126    | 4.16%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1216      | 1982   | 60.08%  |
| 0.51-1.0   | 443       | 672    | 21.89%  |
| 1.01-2.0   | 173       | 266    | 8.55%   |
| 3.01-4.0   | 80        | 132    | 3.95%   |
| 2.01-3.0   | 61        | 96     | 3.01%   |
| 4.01-10.0  | 43        | 83     | 2.12%   |
| 10.01-20.0 | 8         | 11     | 0.4%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 605       | 26.82%  |
| 251-500        | 495       | 21.94%  |
| 501-1000       | 298       | 13.21%  |
| 1-20           | 186       | 8.24%   |
| 1001-2000      | 181       | 8.02%   |
| More than 3000 | 162       | 7.18%   |
| 51-100         | 113       | 5.01%   |
| Unknown        | 83        | 3.68%   |
| 2001-3000      | 71        | 3.15%   |
| 21-50          | 62        | 2.75%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 862       | 37.27%  |
| 21-50          | 342       | 14.79%  |
| 101-250        | 305       | 13.19%  |
| 51-100         | 243       | 10.51%  |
| 251-500        | 161       | 6.96%   |
| 501-1000       | 134       | 5.79%   |
| Unknown        | 83        | 3.59%   |
| 1001-2000      | 74        | 3.2%    |
| More than 3000 | 61        | 2.64%   |
| 2001-3000      | 46        | 1.99%   |
| 0              | 2         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 5         | 5      | 2.79%   |
| Seagate ST9250410AS 250GB                      | 3         | 4      | 1.68%   |
| Samsung Electronics SSD 870 EVO 1TB            | 3         | 3      | 1.68%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 3         | 4      | 1.68%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.68%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 1.12%   |
| WDC WD5000LPVX-22V0TT0 500GB                   | 2         | 2      | 1.12%   |
| WDC WD5000AAKX-75U6AA0 500GB                   | 2         | 2      | 1.12%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 2         | 2      | 1.12%   |
| WDC WD10EZEX-21M2NA0 1TB                       | 2         | 3      | 1.12%   |
| Seagate ST9500420AS 500GB                      | 2         | 2      | 1.12%   |
| Seagate ST4000DM004-2CV104 4TB                 | 2         | 2      | 1.12%   |
| Seagate ST3500418AS 500GB                      | 2         | 2      | 1.12%   |
| Seagate ST2000DX001-1CM164 2TB                 | 2         | 2      | 1.12%   |
| Seagate ST2000DM001-1CH164 2TB                 | 2         | 3      | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 2         | 2      | 1.12%   |
| Samsung Electronics SP2504C 250GB              | 2         | 2      | 1.12%   |
| Samsung Electronics HD501LJ 500GB              | 2         | 2      | 1.12%   |
| Samsung Electronics HD300LJ 304GB              | 2         | 2      | 1.12%   |
| Intel SSDSC2CW120A3 120GB                      | 2         | 2      | 1.12%   |
| Intel SSDSC2BW480A4 480GB                      | 2         | 3      | 1.12%   |
| Intel SSDSC2BW240A4 240GB                      | 2         | 3      | 1.12%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.12%   |
| Crucial CT525MX300SSD1 528GB                   | 2         | 2      | 1.12%   |
| WDC WD7500AACS-00ZJB0 752GB                    | 1         | 1      | 0.56%   |
| WDC WD740GD-00FLA1 74GB                        | 1         | 1      | 0.56%   |
| WDC WD6400AAKS-22A7B2 640GB                    | 1         | 1      | 0.56%   |
| WDC WD60EFRX-68L0BN1 6TB                       | 1         | 6      | 0.56%   |
| WDC WD5000BPKT-60PK4T0 500GB                   | 1         | 1      | 0.56%   |
| WDC WD5000AZRX-00A8LB0 500GB                   | 1         | 2      | 0.56%   |
| WDC WD5000AAKS-00A7B2 500GB                    | 1         | 1      | 0.56%   |
| WDC WD40EFRX-68N32N0 4TB                       | 1         | 2      | 0.56%   |
| WDC WD4003FZEX-00Z4SA0 4TB                     | 1         | 2      | 0.56%   |
| WDC WD3200AAKS-75L9A0 320GB                    | 1         | 1      | 0.56%   |
| WDC WD3200AAKS-00B3A0 320GB                    | 1         | 4      | 0.56%   |
| WDC WD30EFRX-68AX9N0 3TB                       | 1         | 1      | 0.56%   |
| WDC WD20EARS-00MVWB0 2TB                       | 1         | 1      | 0.56%   |
| WDC WD15EARS-00Z5B1 1TB                        | 1         | 1      | 0.56%   |
| WDC WD15EADS-00P8B0 1TB                        | 1         | 2      | 0.56%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 3      | 0.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 52     | 24.28%  |
| WDC                 | 30        | 52     | 17.34%  |
| Samsung Electronics | 20        | 20     | 11.56%  |
| Hitachi             | 16        | 18     | 9.25%   |
| Intel               | 15        | 18     | 8.67%   |
| HGST                | 7         | 8      | 4.05%   |
| Crucial             | 6         | 6      | 3.47%   |
| Toshiba             | 5         | 6      | 2.89%   |
| Kingston            | 5         | 5      | 2.89%   |
| Micron Technology   | 4         | 5      | 2.31%   |
| OCZ                 | 3         | 5      | 1.73%   |
| Corsair             | 3         | 3      | 1.73%   |
| SK hynix            | 2         | 2      | 1.16%   |
| SanDisk             | 2         | 2      | 1.16%   |
| LITEONIT            | 2         | 2      | 1.16%   |
| Fujitsu             | 2         | 2      | 1.16%   |
| Apple               | 2         | 2      | 1.16%   |
| Union Memory        | 1         | 1      | 0.58%   |
| Transcend           | 1         | 1      | 0.58%   |
| Team                | 1         | 1      | 0.58%   |
| PNY                 | 1         | 2      | 0.58%   |
| Hewlett-Packard     | 1         | 1      | 0.58%   |
| China               | 1         | 1      | 0.58%   |
| A-DATA Technology   | 1         | 1      | 0.58%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 52     | 36.84%  |
| WDC                 | 28        | 50     | 24.56%  |
| Hitachi             | 16        | 18     | 14.04%  |
| Samsung Electronics | 12        | 12     | 10.53%  |
| HGST                | 7         | 8      | 6.14%   |
| Toshiba             | 4         | 5      | 3.51%   |
| Fujitsu             | 2         | 2      | 1.75%   |
| Apple               | 2         | 2      | 1.75%   |
| Hewlett-Packard     | 1         | 1      | 0.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 110       | 150    | 66.27%  |
| SSD  | 49        | 59     | 29.52%  |
| NVMe | 7         | 7      | 4.22%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                                           | Computers | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB                                 | 1         | 1      | 50%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1339      | 2856   | 57.39%  |
| Works    | 832       | 1515   | 35.66%  |
| Malfunc  | 160       | 216    | 6.86%   |
| Failed   | 2         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1306      | 47.13%  |
| AMD                              | 454       | 16.38%  |
| Samsung Electronics              | 365       | 13.17%  |
| SanDisk                          | 122       | 4.4%    |
| Kingston Technology Company      | 83        | 3%      |
| SK hynix                         | 59        | 2.13%   |
| Toshiba America Info Systems     | 56        | 2.02%   |
| Phison Electronics               | 49        | 1.77%   |
| ASMedia Technology               | 47        | 1.7%    |
| JMicron Technology               | 38        | 1.37%   |
| Marvell Technology Group         | 33        | 1.19%   |
| Micron Technology                | 31        | 1.12%   |
| Nvidia                           | 22        | 0.79%   |
| KIOXIA                           | 18        | 0.65%   |
| Silicon Motion                   | 12        | 0.43%   |
| ADATA Technology                 | 12        | 0.43%   |
| Micron/Crucial Technology        | 9         | 0.32%   |
| Silicon Image                    | 6         | 0.22%   |
| VIA Technologies                 | 5         | 0.18%   |
| Union Memory (Shenzhen)          | 5         | 0.18%   |
| Lite-On Technology               | 5         | 0.18%   |
| Lenovo                           | 5         | 0.18%   |
| Broadcom / LSI                   | 4         | 0.14%   |
| Apple                            | 4         | 0.14%   |
| Solid State Storage Technology   | 3         | 0.11%   |
| Silicon Integrated Systems [SiS] | 3         | 0.11%   |
| Seagate Technology               | 3         | 0.11%   |
| Realtek Semiconductor            | 3         | 0.11%   |
| LSI Logic / Symbios Logic        | 3         | 0.11%   |
| Hewlett-Packard                  | 3         | 0.11%   |
| Integrated Technology Express    | 1         | 0.04%   |
| HighPoint Technologies           | 1         | 0.04%   |
| Adaptec                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 302       | 9.54%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 194       | 6.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 96        | 3.03%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 94        | 2.97%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 79        | 2.5%    |
| AMD 400 Series Chipset SATA Controller                                         | 76        | 2.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 62        | 1.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 61        | 1.93%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 57        | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 57        | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 54        | 1.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 51        | 1.61%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 48        | 1.52%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 46        | 1.45%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 46        | 1.45%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 46        | 1.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 44        | 1.39%   |
| Samsung NVMe SSD Controller 980                                                | 42        | 1.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 42        | 1.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 40        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 40        | 1.26%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 38        | 1.2%    |
| Intel SSD 660P Series                                                          | 38        | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 37        | 1.17%   |
| Intel SATA Controller [RAID mode]                                              | 37        | 1.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 36        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 36        | 1.14%   |
| Kingston Company A2000 NVMe SSD                                                | 34        | 1.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 31        | 0.98%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 30        | 0.95%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 28        | 0.88%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 25        | 0.79%   |
| Phison E12 NVMe Controller                                                     | 23        | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 23        | 0.73%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 23        | 0.73%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 23        | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 23        | 0.73%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 22        | 0.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 20        | 0.63%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 19        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1505      | 54.61%  |
| NVMe | 839       | 30.44%  |
| IDE  | 240       | 8.71%   |
| RAID | 161       | 5.84%   |
| SAS  | 8         | 0.29%   |
| SCSI | 3         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1541      | 72.62%  |
| AMD      | 559       | 26.34%  |
| ARM      | 21        | 0.99%   |
| QUALCOMM | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 31        | 1.46%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 30        | 1.41%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 26        | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 24        | 1.13%   |
| AMD Ryzen 5 3600 6-Core Processor           | 24        | 1.13%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 20        | 0.94%   |
| Intel Core i5-6600K CPU @ 3.50GHz           | 18        | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 17        | 0.8%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 16        | 0.75%   |
| ARM Processor                               | 15        | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 14        | 0.66%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 14        | 0.66%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 14        | 0.66%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 14        | 0.66%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 14        | 0.66%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 13        | 0.61%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 13        | 0.61%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 12        | 0.56%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 12        | 0.56%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 11        | 0.52%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 11        | 0.52%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 11        | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 11        | 0.52%   |
| Intel Core i5-4690K CPU @ 3.50GHz           | 11        | 0.52%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 11        | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 11        | 0.52%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 11        | 0.52%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 11        | 0.52%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11        | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11        | 0.52%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 10        | 0.47%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 10        | 0.47%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 10        | 0.47%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 10        | 0.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 10        | 0.47%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 10        | 0.47%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 9         | 0.42%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 9         | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9         | 0.42%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 9         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 510       | 24.01%  |
| Intel Core i7           | 468       | 22.03%  |
| Other                   | 168       | 7.91%   |
| AMD Ryzen 5             | 141       | 6.64%   |
| AMD Ryzen 7             | 120       | 5.65%   |
| Intel Core i3           | 87        | 4.1%    |
| Intel Celeron           | 77        | 3.63%   |
| AMD Ryzen 9             | 62        | 2.92%   |
| Intel Core 2 Duo        | 61        | 2.87%   |
| Intel Xeon              | 49        | 2.31%   |
| Intel Pentium           | 34        | 1.6%    |
| AMD FX                  | 34        | 1.6%    |
| Intel Atom              | 28        | 1.32%   |
| AMD Ryzen 3             | 19        | 0.89%   |
| Intel Core i9           | 17        | 0.8%    |
| Intel Core 2 Quad       | 16        | 0.75%   |
| AMD A8                  | 16        | 0.75%   |
| Intel Core 2            | 13        | 0.61%   |
| AMD A6                  | 13        | 0.61%   |
| AMD Ryzen Threadripper  | 11        | 0.52%   |
| Intel Genuine           | 10        | 0.47%   |
| AMD Phenom II X4        | 10        | 0.47%   |
| AMD A4                  | 10        | 0.47%   |
| Intel Pentium Dual-Core | 9         | 0.42%   |
| AMD Ryzen 7 PRO         | 9         | 0.42%   |
| AMD E1                  | 9         | 0.42%   |
| AMD A10                 | 9         | 0.42%   |
| AMD E                   | 8         | 0.38%   |
| Intel Pentium Silver    | 7         | 0.33%   |
| AMD Ryzen 5 PRO         | 7         | 0.33%   |
| AMD Phenom II X6        | 7         | 0.33%   |
| AMD Athlon 64 X2        | 7         | 0.33%   |
| ARM BCM                 | 6         | 0.28%   |
| AMD Athlon II X2        | 6         | 0.28%   |
| Intel Pentium Dual      | 5         | 0.24%   |
| AMD Ryzen Embedded      | 5         | 0.24%   |
| Intel Pentium M         | 4         | 0.19%   |
| Intel Core m3           | 3         | 0.14%   |
| Intel Celeron Dual-Core | 3         | 0.14%   |
| AMD Turion 64 X2 Mobile | 3         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 802       | 37.71%  |
| 2       | 690       | 32.44%  |
| 6       | 262       | 12.32%  |
| 8       | 192       | 9.03%   |
| 12      | 55        | 2.59%   |
| 16      | 32        | 1.5%    |
| 1       | 32        | 1.5%    |
| 3       | 19        | 0.89%   |
| 14      | 15        | 0.71%   |
| 10      | 13        | 0.61%   |
| Unknown | 5         | 0.24%   |
| 18      | 4         | 0.19%   |
| 32      | 2         | 0.09%   |
| 64      | 1         | 0.05%   |
| 28      | 1         | 0.05%   |
| 24      | 1         | 0.05%   |
| 20      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2095      | 98.73%  |
| 2       | 22        | 1.04%   |
| Unknown | 4         | 0.19%   |
| 3       | 1         | 0.05%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1470      | 69.14%  |
| 1       | 651       | 30.62%  |
| Unknown | 5         | 0.24%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2071      | 97.41%  |
| Unknown        | 42        | 1.98%   |
| 32-bit         | 12        | 0.56%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 631       | 28.47%  |
| 0x306c3    | 103       | 4.65%   |
| 0x206a7    | 92        | 4.15%   |
| 0x306a9    | 88        | 3.97%   |
| 0x906ea    | 51        | 2.3%    |
| 0x806c1    | 49        | 2.21%   |
| 0x40651    | 49        | 2.21%   |
| 0x1067a    | 49        | 2.21%   |
| 0x806ea    | 48        | 2.17%   |
| 0x806ec    | 47        | 2.12%   |
| 0x506e3    | 45        | 2.03%   |
| 0x406e3    | 44        | 1.99%   |
| 0x306d4    | 44        | 1.99%   |
| 0x906e9    | 43        | 1.94%   |
| 0x806e9    | 42        | 1.9%    |
| 0x08701021 | 41        | 1.85%   |
| 0x20655    | 28        | 1.26%   |
| 0x0a50000c | 23        | 1.04%   |
| 0x08108109 | 23        | 1.04%   |
| 0x08701013 | 20        | 0.9%    |
| 0x0800820d | 20        | 0.9%    |
| 0x406c4    | 19        | 0.86%   |
| 0x08600106 | 18        | 0.81%   |
| 0x906ed    | 16        | 0.72%   |
| 0x06000852 | 15        | 0.68%   |
| 0x806eb    | 14        | 0.63%   |
| 0x6fd      | 14        | 0.63%   |
| 0x306f2    | 14        | 0.63%   |
| 0x0a201009 | 14        | 0.63%   |
| 0x0810100b | 14        | 0.63%   |
| 0x010000c8 | 14        | 0.63%   |
| 0xa0652    | 13        | 0.59%   |
| 0x906a3    | 13        | 0.59%   |
| 0x30678    | 13        | 0.59%   |
| 0x106e5    | 13        | 0.59%   |
| 0x06001119 | 13        | 0.59%   |
| 0x6f6      | 12        | 0.54%   |
| 0x08608103 | 12        | 0.54%   |
| 0x08001138 | 12        | 0.54%   |
| 0x10676    | 11        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 368       | 17.31%  |
| Haswell          | 221       | 10.4%   |
| SandyBridge      | 141       | 6.63%   |
| IvyBridge        | 131       | 6.16%   |
| Skylake          | 128       | 6.02%   |
| Zen 2            | 120       | 5.64%   |
| Unknown          | 100       | 4.7%    |
| Zen 3            | 92        | 4.33%   |
| Penryn           | 74        | 3.48%   |
| Zen+             | 70        | 3.29%   |
| TigerLake        | 62        | 2.92%   |
| Silvermont       | 57        | 2.68%   |
| Broadwell        | 57        | 2.68%   |
| Westmere         | 53        | 2.49%   |
| Zen              | 52        | 2.45%   |
| Core             | 49        | 2.3%    |
| Piledriver       | 41        | 1.93%   |
| K10              | 41        | 1.93%   |
| CometLake        | 38        | 1.79%   |
| Alderlake Hybrid | 36        | 1.69%   |
| Icelake          | 24        | 1.13%   |
| Goldmont plus    | 23        | 1.08%   |
| Nehalem          | 22        | 1.03%   |
| Excavator        | 18        | 0.85%   |
| K8 Hammer        | 14        | 0.66%   |
| K10 Llano        | 12        | 0.56%   |
| Jaguar           | 12        | 0.56%   |
| Goldmont         | 11        | 0.52%   |
| Bobcat           | 11        | 0.52%   |
| Bulldozer        | 10        | 0.47%   |
| Puma             | 9         | 0.42%   |
| Bonnell          | 8         | 0.38%   |
| P6               | 6         | 0.28%   |
| Tremont          | 4         | 0.19%   |
| Steamroller      | 3         | 0.14%   |
| NetBurst         | 3         | 0.14%   |
| K8 & K10 hybrid  | 3         | 0.14%   |
| K6               | 1         | 0.05%   |
| Geode            | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1103      | 44.84%  |
| Nvidia                           | 782       | 31.79%  |
| AMD                              | 556       | 22.6%   |
| Matrox Electronics Systems       | 9         | 0.37%   |
| ASPEED Technology                | 7         | 0.28%   |
| Silicon Integrated Systems [SiS] | 3         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 93        | 3.65%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 72        | 2.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 65        | 2.55%   |
| Intel UHD Graphics 620                                                                   | 63        | 2.47%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 53        | 2.08%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 52        | 2.04%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 49        | 1.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 47        | 1.85%   |
| Intel HD Graphics 620                                                                    | 44        | 1.73%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 1.73%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 43        | 1.69%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 39        | 1.53%   |
| Intel HD Graphics 5500                                                                   | 38        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 35        | 1.37%   |
| AMD Renoir                                                                               | 34        | 1.34%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 34        | 1.34%   |
| Intel HD Graphics 630                                                                    | 33        | 1.3%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 1.14%   |
| Intel Core Processor Integrated Graphics Controller                                      | 28        | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 27        | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 1.06%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 25        | 0.98%   |
| Intel HD Graphics 530                                                                    | 23        | 0.9%    |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 23        | 0.9%    |
| Nvidia GM206 [GeForce GTX 960]                                                           | 20        | 0.79%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 20        | 0.79%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 20        | 0.79%   |
| AMD Lucienne                                                                             | 20        | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 19        | 0.75%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 19        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 0.75%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 17        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 17        | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 17        | 0.67%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 16        | 0.63%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 16        | 0.63%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 16        | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 0.59%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 797       | 37.26%  |
| 1 x Nvidia               | 496       | 23.19%  |
| 1 x AMD                  | 440       | 20.57%  |
| Intel + Nvidia           | 237       | 11.08%  |
| 2 x AMD                  | 43        | 2.01%   |
| AMD + Nvidia             | 39        | 1.82%   |
| Intel + AMD              | 34        | 1.59%   |
| Other                    | 23        | 1.08%   |
| 1 x Matrox               | 7         | 0.33%   |
| 1 x ASPEED               | 7         | 0.33%   |
| 2 x Nvidia               | 5         | 0.23%   |
| 1 x SiS                  | 3         | 0.14%   |
| 2 x Intel                | 2         | 0.09%   |
| Intel + 2 x Nvidia       | 2         | 0.09%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.09%   |
| 2 x Nvidia + 1 x Matrox  | 1         | 0.05%   |
| Nvidia + Matrox          | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1584      | 73.44%  |
| Proprietary | 476       | 22.07%  |
| Unknown     | 97        | 4.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1199      | 54.8%   |
| 1.01-2.0   | 235       | 10.74%  |
| 0.01-0.5   | 220       | 10.05%  |
| 0.51-1.0   | 133       | 6.08%   |
| 3.01-4.0   | 132       | 6.03%   |
| 7.01-8.0   | 131       | 5.99%   |
| 5.01-6.0   | 63        | 2.88%   |
| 8.01-16.0  | 43        | 1.97%   |
| 2.01-3.0   | 24        | 1.1%    |
| 16.01-24.0 | 8         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 302       | 12.51%  |
| Samsung Electronics     | 288       | 11.93%  |
| LG Display              | 181       | 7.5%    |
| Chimei Innolux          | 168       | 6.96%   |
| Dell                    | 138       | 5.72%   |
| BenQ                    | 126       | 5.22%   |
| Philips                 | 109       | 4.52%   |
| BOE                     | 108       | 4.47%   |
| Ancor Communications    | 100       | 4.14%   |
| Hewlett-Packard         | 99        | 4.1%    |
| AOC                     | 93        | 3.85%   |
| Acer                    | 87        | 3.6%    |
| Sharp                   | 62        | 2.57%   |
| Goldstar                | 60        | 2.49%   |
| Apple                   | 57        | 2.36%   |
| Lenovo                  | 46        | 1.91%   |
| ASUSTek Computer        | 35        | 1.45%   |
| InfoVision              | 25        | 1.04%   |
| MSI                     | 24        | 0.99%   |
| Chi Mei Optoelectronics | 24        | 0.99%   |
| Eizo                    | 22        | 0.91%   |
| LG Philips              | 17        | 0.7%    |
| CSO                     | 17        | 0.7%    |
| Vestel Elektronik       | 15        | 0.62%   |
| Unknown                 | 15        | 0.62%   |
| Sony                    | 15        | 0.62%   |
| Panasonic               | 12        | 0.5%    |
| LG Electronics          | 11        | 0.46%   |
| Fujitsu Siemens         | 11        | 0.46%   |
| ViewSonic               | 9         | 0.37%   |
| PANDA                   | 9         | 0.37%   |
| Gigabyte Technology     | 7         | 0.29%   |
| VOXICON                 | 5         | 0.21%   |
| Toshiba                 | 5         | 0.21%   |
| Microstep               | 5         | 0.21%   |
| LGD                     | 5         | 0.21%   |
| BOE Technology Group    | 5         | 0.21%   |
| Valve                   | 4         | 0.17%   |
| Quanta Display          | 4         | 0.17%   |
| Positivo                | 4         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Vestel Elektronik 32W_LCD_TV VES3700 1920x1080 710x400mm 32.1-inch    | 15        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 15        | 0.6%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 12        | 0.48%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 10        | 0.4%    |
| BenQ G2420HDBL BNQ785F 1920x1080 477x268mm 21.5-inch                  | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 9         | 0.36%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.32%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 8         | 0.32%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 8         | 0.32%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 8         | 0.32%   |
| AOC 2460G4 AOC2460 1920x1080 531x299mm 24.0-inch                      | 8         | 0.32%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 7         | 0.28%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                    | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 7         | 0.28%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 7         | 0.28%   |
| Philips FTV PHL01EA 1920x1080 1440x810mm 65.0-inch                    | 6         | 0.24%   |
| Philips 273ELH PHLC07D 1920x1080 598x336mm 27.0-inch                  | 6         | 0.24%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 6         | 0.24%   |
| Hewlett-Packard E241i HWP3122 1920x1200 518x324mm 24.1-inch           | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 6         | 0.24%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 6         | 0.24%   |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch | 6         | 0.24%   |
| Ancor Communications ASUS PB278 ACI27A3 2560x1440 597x336mm 27.0-inch | 6         | 0.24%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 5         | 0.2%    |
| Philips PHL BDM3270 PHL08E7 2560x1440 708x398mm 32.0-inch             | 5         | 0.2%    |
| Philips PHL 436M6VBP PHLC179 3840x2160 940x530mm 42.5-inch            | 5         | 0.2%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 5         | 0.2%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 5         | 0.2%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 5         | 0.2%    |
| Hewlett-Packard LA2205 HWP2848 1680x1050 473x296mm 22.0-inch          | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 5         | 0.2%    |
| BenQ G2420HDB BNQ7842 1920x1080 477x268mm 21.5-inch                   | 5         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1006      | 43.53%  |
| 1366x768 (WXGA)    | 275       | 11.9%   |
| 3840x2160 (4K)     | 199       | 8.61%   |
| 2560x1440 (QHD)    | 194       | 8.39%   |
| 1680x1050 (WSXGA+) | 81        | 3.5%    |
| 1920x1200 (WUXGA)  | 80        | 3.46%   |
| 3440x1440          | 59        | 2.55%   |
| 1600x900 (HD+)     | 49        | 2.12%   |
| 1280x800 (WXGA)    | 46        | 1.99%   |
| 1280x1024 (SXGA)   | 46        | 1.99%   |
| Unknown            | 40        | 1.73%   |
| 2560x1600          | 32        | 1.38%   |
| 1440x900 (WXGA+)   | 30        | 1.3%    |
| 3840x2400          | 20        | 0.87%   |
| 2880x1800          | 19        | 0.82%   |
| 3840x1080          | 18        | 0.78%   |
| 1024x768 (XGA)     | 13        | 0.56%   |
| 1360x768           | 11        | 0.48%   |
| 1920x540           | 9         | 0.39%   |
| 1280x720 (HD)      | 8         | 0.35%   |
| 3200x1800 (QHD+)   | 7         | 0.3%    |
| 2736x1824          | 7         | 0.3%    |
| 800x1280           | 6         | 0.26%   |
| 2560x1080          | 6         | 0.26%   |
| 1024x600           | 5         | 0.22%   |
| 3840x1600          | 4         | 0.17%   |
| 2288x1287          | 4         | 0.17%   |
| 6400x2160          | 3         | 0.13%   |
| 5760x2160          | 3         | 0.13%   |
| 5760x1080          | 3         | 0.13%   |
| 2160x1440          | 3         | 0.13%   |
| 4480x1440          | 2         | 0.09%   |
| 3840x1200          | 2         | 0.09%   |
| 3200x1200          | 2         | 0.09%   |
| 1280x768           | 2         | 0.09%   |
| 7280x2160          | 1         | 0.04%   |
| 5520x2160          | 1         | 0.04%   |
| 5360x1440          | 1         | 0.04%   |
| 4920x1920          | 1         | 0.04%   |
| 4864x1080          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 427       | 17.87%  |
| 13      | 276       | 11.55%  |
| 27      | 267       | 11.18%  |
| 24      | 251       | 10.51%  |
| 14      | 186       | 7.79%   |
| Unknown | 147       | 6.15%   |
| 23      | 143       | 5.99%   |
| 17      | 87        | 3.64%   |
| 21      | 68        | 2.85%   |
| 12      | 67        | 2.8%    |
| 31      | 58        | 2.43%   |
| 22      | 57        | 2.39%   |
| 34      | 54        | 2.26%   |
| 19      | 46        | 1.93%   |
| 84      | 37        | 1.55%   |
| 11      | 28        | 1.17%   |
| 16      | 21        | 0.88%   |
| 32      | 19        | 0.8%    |
| 20      | 13        | 0.54%   |
| 72      | 12        | 0.5%    |
| 25      | 11        | 0.46%   |
| 65      | 10        | 0.42%   |
| 54      | 9         | 0.38%   |
| 42      | 9         | 0.38%   |
| 18      | 8         | 0.33%   |
| 35      | 7         | 0.29%   |
| 48      | 6         | 0.25%   |
| 40      | 6         | 0.25%   |
| 39      | 6         | 0.25%   |
| 37      | 5         | 0.21%   |
| 29      | 5         | 0.21%   |
| 10      | 5         | 0.21%   |
| 50      | 4         | 0.17%   |
| 49      | 4         | 0.17%   |
| 46      | 3         | 0.13%   |
| 33      | 3         | 0.13%   |
| 7       | 3         | 0.13%   |
| 3       | 3         | 0.13%   |
| 142     | 2         | 0.08%   |
| 55      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 752       | 32.19%  |
| 501-600        | 600       | 25.68%  |
| 201-300        | 257       | 11%     |
| 401-500        | 157       | 6.72%   |
| Unknown        | 147       | 6.29%   |
| 351-400        | 120       | 5.14%   |
| 601-700        | 89        | 3.81%   |
| 701-800        | 76        | 3.25%   |
| 1501-2000      | 51        | 2.18%   |
| 1001-1500      | 42        | 1.8%    |
| 801-900        | 23        | 0.98%   |
| 901-1000       | 13        | 0.56%   |
| 1-100          | 6         | 0.26%   |
| More than 2000 | 2         | 0.09%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1518      | 70.8%   |
| 16/10   | 324       | 15.11%  |
| Unknown | 134       | 6.25%   |
| 21/9    | 66        | 3.08%   |
| 5/4     | 49        | 2.29%   |
| 3/2     | 20        | 0.93%   |
| 4/3     | 14        | 0.65%   |
| 32/9    | 6         | 0.28%   |
| 6/5     | 5         | 0.23%   |
| 0.67    | 3         | 0.14%   |
| 1.00    | 2         | 0.09%   |
| 3.40    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |
| 0.45    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 421       | 17.91%  |
| 201-250        | 387       | 16.47%  |
| 81-90          | 331       | 14.09%  |
| 301-350        | 268       | 11.4%   |
| Unknown        | 147       | 6.26%   |
| 351-500        | 142       | 6.04%   |
| 71-80          | 132       | 5.62%   |
| 251-300        | 100       | 4.26%   |
| More than 1000 | 86        | 3.66%   |
| 151-200        | 71        | 3.02%   |
| 121-130        | 66        | 2.81%   |
| 61-70          | 61        | 2.6%    |
| 501-1000       | 38        | 1.62%   |
| 51-60          | 29        | 1.23%   |
| 111-120        | 23        | 0.98%   |
| 141-150        | 17        | 0.72%   |
| 131-140        | 13        | 0.55%   |
| 41-50          | 6         | 0.26%   |
| 1-40           | 6         | 0.26%   |
| 91-100         | 6         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 727       | 31.86%  |
| 121-160       | 588       | 25.77%  |
| 101-120       | 493       | 21.6%   |
| 161-240       | 184       | 8.06%   |
| Unknown       | 147       | 6.44%   |
| More than 240 | 86        | 3.77%   |
| 1-50          | 57        | 2.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1613      | 74.06%  |
| 2     | 404       | 18.55%  |
| 0     | 109       | 5%      |
| 3     | 46        | 2.11%   |
| 4     | 6         | 0.28%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1198      | 38.9%   |
| Realtek Semiconductor             | 926       | 30.06%  |
| Qualcomm Atheros                  | 293       | 9.51%   |
| Broadcom                          | 185       | 6.01%   |
| MediaTek                          | 55        | 1.79%   |
| Broadcom Limited                  | 46        | 1.49%   |
| Marvell Technology Group          | 31        | 1.01%   |
| ASIX Electronics                  | 23        | 0.75%   |
| Ralink                            | 22        | 0.71%   |
| Nvidia                            | 18        | 0.58%   |
| Hewlett-Packard                   | 18        | 0.58%   |
| TP-Link                           | 16        | 0.52%   |
| Lenovo                            | 16        | 0.52%   |
| ASUSTek Computer                  | 16        | 0.52%   |
| Sierra Wireless                   | 15        | 0.49%   |
| Microsoft                         | 15        | 0.49%   |
| Ralink Technology                 | 14        | 0.45%   |
| Dell                              | 14        | 0.45%   |
| D-Link System                     | 14        | 0.45%   |
| NetGear                           | 13        | 0.42%   |
| D-Link                            | 11        | 0.36%   |
| DisplayLink                       | 10        | 0.32%   |
| Huawei Technologies               | 9         | 0.29%   |
| Ericsson Business Mobile Networks | 8         | 0.26%   |
| Aquantia                          | 7         | 0.23%   |
| Samsung Electronics               | 6         | 0.19%   |
| Qualcomm Atheros Communications   | 6         | 0.19%   |
| Qualcomm                          | 5         | 0.16%   |
| Fibocom                           | 5         | 0.16%   |
| Microchip Technology              | 4         | 0.13%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.1%    |
| Linksys                           | 3         | 0.1%    |
| Belkin Components                 | 3         | 0.1%    |
| Arduino SA                        | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM        | 2         | 0.06%   |
| Xiaomi                            | 2         | 0.06%   |
| Wacom                             | 2         | 0.06%   |
| Texas Instruments                 | 2         | 0.06%   |
| STMicroelectronics                | 2         | 0.06%   |
| Standard Microsystems             | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 647       | 17.5%   |
| Intel I211 Gigabit Network Connection                             | 105       | 2.84%   |
| Intel Wireless 8265 / 8275                                        | 98        | 2.65%   |
| Intel Wi-Fi 6 AX200                                               | 98        | 2.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 74        | 2%      |
| Intel Wireless 7260                                               | 70        | 1.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 1.87%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 59        | 1.6%    |
| Intel Wireless 8260                                               | 55        | 1.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 53        | 1.43%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 1.38%   |
| Intel Wireless 7265                                               | 50        | 1.35%   |
| Intel Wi-Fi 6 AX201                                               | 50        | 1.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 42        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 37        | 1%      |
| Intel Ethernet Connection I217-LM                                 | 37        | 1%      |
| Intel Ethernet Controller I225-V                                  | 35        | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 34        | 0.92%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 34        | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 32        | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 30        | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 30        | 0.81%   |
| Intel 82579V Gigabit Network Connection                           | 30        | 0.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 29        | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 0.78%   |
| Intel Wireless-AC 9260                                            | 26        | 0.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 26        | 0.7%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 26        | 0.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 26        | 0.7%    |
| Intel Ethernet Connection (4) I219-V                              | 25        | 0.68%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 24        | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 24        | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 23        | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 0.6%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 0.57%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 21        | 0.57%   |
| Intel Wireless 3160                                               | 20        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 847       | 51.43%  |
| Qualcomm Atheros                | 229       | 13.9%   |
| Realtek Semiconductor           | 198       | 12.02%  |
| Broadcom                        | 121       | 7.35%   |
| MediaTek                        | 54        | 3.28%   |
| Broadcom Limited                | 28        | 1.7%    |
| Ralink                          | 22        | 1.34%   |
| ASUSTek Computer                | 16        | 0.97%   |
| Sierra Wireless                 | 15        | 0.91%   |
| Ralink Technology               | 14        | 0.85%   |
| TP-Link                         | 13        | 0.79%   |
| NetGear                         | 13        | 0.79%   |
| Microsoft                       | 10        | 0.61%   |
| D-Link System                   | 10        | 0.61%   |
| D-Link                          | 10        | 0.61%   |
| Dell                            | 8         | 0.49%   |
| Qualcomm Atheros Communications | 6         | 0.36%   |
| Marvell Technology Group        | 5         | 0.3%    |
| Fibocom                         | 5         | 0.3%    |
| Hewlett-Packard                 | 4         | 0.24%   |
| Qualcomm                        | 3         | 0.18%   |
| Belkin Components               | 3         | 0.18%   |
| Wacom                           | 2         | 0.12%   |
| Linksys                         | 2         | 0.12%   |
| Edimax Technology               | 2         | 0.12%   |
| ZyXEL Communications            | 1         | 0.06%   |
| Wilocity                        | 1         | 0.06%   |
| Sitecom Europe                  | 1         | 0.06%   |
| Micro Star International        | 1         | 0.06%   |
| IMC Networks                    | 1         | 0.06%   |
| Fujitsu Siemens Computers       | 1         | 0.06%   |
| Chu Yuen Enterprise             | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 98        | 5.91%   |
| Intel Wi-Fi 6 AX200                                            | 98        | 5.91%   |
| Intel Wireless 7260                                            | 70        | 4.22%   |
| Intel Wireless 8260                                            | 55        | 3.32%   |
| Intel Wireless 7265                                            | 50        | 3.02%   |
| Intel Wi-Fi 6 AX201                                            | 50        | 3.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 42        | 2.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 37        | 2.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 34        | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 34        | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 32        | 1.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 30        | 1.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 30        | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 29        | 1.75%   |
| Intel Wireless-AC 9260                                         | 26        | 1.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 26        | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 26        | 1.57%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 26        | 1.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 24        | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 24        | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 23        | 1.39%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 1.27%   |
| Intel Wireless 3160                                            | 20        | 1.21%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 20        | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18        | 1.09%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 18        | 1.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 17        | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 17        | 1.03%   |
| Intel Wireless 3165                                            | 17        | 1.03%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 16        | 0.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 16        | 0.97%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 16        | 0.97%   |
| Intel Centrino Advanced-N 6200                                 | 15        | 0.9%    |
| Intel Centrino Advanced-N 6235                                 | 14        | 0.84%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 14        | 0.84%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 12        | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 12        | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 12        | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 11        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 843       | 43.59%  |
| Intel                                  | 727       | 37.59%  |
| Qualcomm Atheros                       | 97        | 5.02%   |
| Broadcom                               | 91        | 4.71%   |
| Marvell Technology Group               | 26        | 1.34%   |
| ASIX Electronics                       | 23        | 1.19%   |
| Broadcom Limited                       | 19        | 0.98%   |
| Nvidia                                 | 18        | 0.93%   |
| Lenovo                                 | 15        | 0.78%   |
| DisplayLink                            | 10        | 0.52%   |
| Huawei Technologies                    | 7         | 0.36%   |
| Aquantia                               | 7         | 0.36%   |
| Samsung Electronics                    | 6         | 0.31%   |
| Microsoft                              | 5         | 0.26%   |
| Hewlett-Packard                        | 5         | 0.26%   |
| Microchip Technology                   | 4         | 0.21%   |
| D-Link System                          | 4         | 0.21%   |
| TP-Link                                | 3         | 0.16%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.1%    |
| Xiaomi                                 | 2         | 0.1%    |
| Standard Microsystems                  | 2         | 0.1%    |
| Silicon Integrated Systems [SiS]       | 2         | 0.1%    |
| Qualcomm                               | 2         | 0.1%    |
| JMicron Technology                     | 2         | 0.1%    |
| ICS Advent                             | 2         | 0.1%    |
| VIA Technologies                       | 1         | 0.05%   |
| Unknown                                | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |
| Linksys                                | 1         | 0.05%   |
| Gemtek                                 | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| 3Com                                   | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 647       | 32.64%  |
| Intel I211 Gigabit Network Connection                             | 105       | 5.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 74        | 3.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 69        | 3.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 59        | 2.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 53        | 2.67%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 2.57%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 1.87%   |
| Intel Ethernet Controller I225-V                                  | 35        | 1.77%   |
| Intel 82579V Gigabit Network Connection                           | 30        | 1.51%   |
| Intel Ethernet Connection (7) I219-V                              | 29        | 1.46%   |
| Intel Ethernet Connection (4) I219-V                              | 25        | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 24        | 1.21%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 1.21%   |
| Intel Ethernet Connection I219-LM                                 | 22        | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                             | 21        | 1.06%   |
| Intel Ethernet Connection (6) I219-V                              | 20        | 1.01%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 1.01%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18        | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 18        | 0.91%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.81%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.81%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 16        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 0.81%   |
| Intel I210 Gigabit Network Connection                             | 15        | 0.76%   |
| Intel Ethernet Connection I219-V                                  | 15        | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.71%   |
| Intel Ethernet Connection (13) I219-V                             | 12        | 0.61%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11        | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 11        | 0.55%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 11        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 9         | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.4%    |
| Intel Ethernet Connection (5) I219-LM                             | 8         | 0.4%    |
| Intel 82566MM Gigabit Network Connection                          | 8         | 0.4%    |
| DisplayLink Dell Universal Dock D6000                             | 8         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1830      | 53.18%  |
| WiFi     | 1554      | 45.16%  |
| Modem    | 45        | 1.31%   |
| Unknown  | 12        | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1155      | 52.24%  |
| Ethernet | 1054      | 47.67%  |
| Unknown  | 2         | 0.09%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1114      | 52.28%  |
| 1     | 901       | 42.28%  |
| 3     | 56        | 2.63%   |
| 0     | 41        | 1.92%   |
| 4     | 12        | 0.56%   |
| 5     | 5         | 0.23%   |
| 9     | 1         | 0.05%   |
| 6     | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2016      | 94.43%  |
| Yes  | 119       | 5.57%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 698       | 52.09%  |
| Realtek Semiconductor           | 92        | 6.87%   |
| Qualcomm Atheros Communications | 75        | 5.6%    |
| IMC Networks                    | 66        | 4.93%   |
| Apple                           | 64        | 4.78%   |
| Cambridge Silicon Radio         | 63        | 4.7%    |
| ASUSTek Computer                | 62        | 4.63%   |
| Broadcom                        | 55        | 4.1%    |
| Foxconn / Hon Hai               | 52        | 3.88%   |
| Lite-On Technology              | 36        | 2.69%   |
| Hewlett-Packard                 | 17        | 1.27%   |
| Dell                            | 16        | 1.19%   |
| MediaTek                        | 8         | 0.6%    |
| Ralink                          | 7         | 0.52%   |
| Toshiba                         | 5         | 0.37%   |
| Marvell Semiconductor           | 5         | 0.37%   |
| Realtek                         | 3         | 0.22%   |
| Ralink Technology               | 2         | 0.15%   |
| Micro Star International        | 2         | 0.15%   |
| HTC (High Tech Computer)        | 2         | 0.15%   |
| Chicony Electronics             | 2         | 0.15%   |
| Belkin Components               | 2         | 0.15%   |
| USI                             | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Creative Technology             | 1         | 0.07%   |
| Alps Electric                   | 1         | 0.07%   |
| Actions                         | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 292       | 21.69%  |
| Intel AX201 Bluetooth                               | 113       | 8.4%    |
| Intel AX200 Bluetooth                               | 95        | 7.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 76        | 5.65%   |
| Realtek Bluetooth Radio                             | 65        | 4.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 63        | 4.68%   |
| Apple Bluetooth Host Controller                     | 32        | 2.38%   |
| IMC Networks Bluetooth Radio                        | 28        | 2.08%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 27        | 2.01%   |
| Intel AX210 Bluetooth                               | 25        | 1.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 24        | 1.78%   |
| Intel Bluetooth Device                              | 24        | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 23        | 1.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.63%   |
| Foxconn / Hon Hai Bluetooth Device                  | 21        | 1.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 1.34%   |
| Qualcomm Atheros  Bluetooth Device                  | 17        | 1.26%   |
| Apple Bluetooth USB Host Controller                 | 16        | 1.19%   |
| IMC Networks Wireless_Device                        | 15        | 1.11%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.97%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 12        | 0.89%   |
| IMC Networks Bluetooth Device                       | 12        | 0.89%   |
| Foxconn / Hon Hai Wireless_Device                   | 12        | 0.89%   |
| Lite-On Bluetooth Device                            | 11        | 0.82%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 11        | 0.82%   |
| ASUS ASUS USB-BT500                                 | 10        | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.67%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 8         | 0.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 8         | 0.59%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.59%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.52%   |
| Ralink RT3290 Bluetooth                             | 7         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.52%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.52%   |
| Broadcom HP Portable Bumble Bee                     | 6         | 0.45%   |
| ASUS Bluetooth Radio                                | 6         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1465      | 46.27%  |
| AMD                              | 650       | 20.53%  |
| Nvidia                           | 595       | 18.79%  |
| C-Media Electronics              | 60        | 1.9%    |
| Logitech                         | 39        | 1.23%   |
| SteelSeries ApS                  | 22        | 0.69%   |
| Creative Labs                    | 21        | 0.66%   |
| Kingston Technology              | 20        | 0.63%   |
| Realtek Semiconductor            | 15        | 0.47%   |
| Plantronics                      | 15        | 0.47%   |
| Creative Technology              | 15        | 0.47%   |
| GN Netcom                        | 14        | 0.44%   |
| Texas Instruments                | 13        | 0.41%   |
| Focusrite-Novation               | 13        | 0.41%   |
| ASUSTek Computer                 | 13        | 0.41%   |
| Lenovo                           | 12        | 0.38%   |
| Corsair                          | 10        | 0.32%   |
| Razer USA                        | 9         | 0.28%   |
| Micro Star International         | 8         | 0.25%   |
| SAVITECH                         | 7         | 0.22%   |
| RODE Microphones                 | 7         | 0.22%   |
| GYROCOM C&C                      | 6         | 0.19%   |
| Yamaha                           | 5         | 0.16%   |
| JMTek                            | 5         | 0.16%   |
| Blue Microphones                 | 5         | 0.16%   |
| Apple                            | 5         | 0.16%   |
| Sennheiser Communications        | 4         | 0.13%   |
| Hewlett-Packard                  | 4         | 0.13%   |
| Antlion Audio                    | 4         | 0.13%   |
| XMOS                             | 3         | 0.09%   |
| VIA Technologies                 | 3         | 0.09%   |
| Trust                            | 3         | 0.09%   |
| Sony                             | 3         | 0.09%   |
| Silicon Integrated Systems [SiS] | 3         | 0.09%   |
| Samsung Electronics              | 3         | 0.09%   |
| Samson Technologies              | 3         | 0.09%   |
| PreSonus Audio Electronics       | 3         | 0.09%   |
| Generalplus Technology           | 3         | 0.09%   |
| BEHRINGER International          | 3         | 0.09%   |
| Valve Software                   | 2         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 179       | 4.8%    |
| Intel Sunrise Point-LP HD Audio                                            | 171       | 4.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 132       | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 125       | 3.35%   |
| AMD Starship/Matisse HD Audio Controller                                   | 121       | 3.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 107       | 2.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 94        | 2.52%   |
| Intel Cannon Lake PCH cAVS                                                 | 89        | 2.39%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 81        | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 70        | 1.88%   |
| Intel Haswell-ULT HD Audio Controller                                      | 65        | 1.74%   |
| Intel 8 Series HD Audio Controller                                         | 65        | 1.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 62        | 1.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 62        | 1.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 60        | 1.61%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 58        | 1.55%   |
| AMD FCH Azalia Controller                                                  | 56        | 1.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 54        | 1.45%   |
| Intel 200 Series PCH HD Audio                                              | 50        | 1.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 50        | 1.34%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 49        | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 49        | 1.31%   |
| Nvidia GP106 High Definition Audio Controller                              | 48        | 1.29%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 46        | 1.23%   |
| Nvidia GP104 High Definition Audio Controller                              | 44        | 1.18%   |
| Nvidia TU106 High Definition Audio Controller                              | 40        | 1.07%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 38        | 1.02%   |
| Nvidia GP107GL High Definition Audio Controller                            | 37        | 0.99%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 30        | 0.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 30        | 0.8%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 30        | 0.8%    |
| Nvidia GM204 High Definition Audio Controller                              | 29        | 0.78%   |
| Nvidia GF108 High Definition Audio Controller                              | 28        | 0.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 28        | 0.75%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 28        | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                   | 28        | 0.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 27        | 0.72%   |
| AMD Navi 10 HDMI Audio                                                     | 27        | 0.72%   |
| Nvidia GK107 HDMI Audio Controller                                         | 26        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 284       | 22.31%  |
| SK hynix                     | 211       | 16.58%  |
| Corsair                      | 169       | 13.28%  |
| Kingston                     | 155       | 12.18%  |
| Micron Technology            | 143       | 11.23%  |
| Unknown                      | 99        | 7.78%   |
| Crucial                      | 67        | 5.26%   |
| G.Skill                      | 35        | 2.75%   |
| Ramaxel Technology           | 17        | 1.34%   |
| Elpida                       | 17        | 1.34%   |
| A-DATA Technology            | 14        | 1.1%    |
| Unknown (ABCD)               | 10        | 0.79%   |
| Unknown                      | 9         | 0.71%   |
| Nanya Technology             | 8         | 0.63%   |
| Patriot                      | 4         | 0.31%   |
| Team                         | 3         | 0.24%   |
| Transcend                    | 2         | 0.16%   |
| Qimonda                      | 2         | 0.16%   |
| GSkill                       | 2         | 0.16%   |
| GOODRAM                      | 2         | 0.16%   |
| G-Alantic                    | 2         | 0.16%   |
| Avant                        | 2         | 0.16%   |
| Unknown (AB)                 | 1         | 0.08%   |
| Unknown (836D)               | 1         | 0.08%   |
| Unifosa                      | 1         | 0.08%   |
| TEXTORM                      | 1         | 0.08%   |
| SHARETRONIC                  | 1         | 0.08%   |
| Patriot Memory (PDP Systems) | 1         | 0.08%   |
| Netlist                      | 1         | 0.08%   |
| Neo Forza                    | 1         | 0.08%   |
| KingSpec                     | 1         | 0.08%   |
| Innodisk                     | 1         | 0.08%   |
| Hyundai lnc                  | 1         | 0.08%   |
| Hewlett-Packard              | 1         | 0.08%   |
| fef5                         | 1         | 0.08%   |
| ASint Technology             | 1         | 0.08%   |
| Apacer                       | 1         | 0.08%   |
| Ankowall                     | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 24        | 1.76%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.96%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.81%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 11        | 0.81%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.74%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 9         | 0.66%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.66%   |
| Unknown                                                          | 9         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 8         | 0.59%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 8         | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.59%   |
| Kingston RAM KF3200C16D4/8GX 8GB DIMM DDR4 3600MT/s              | 8         | 0.59%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 0.51%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.44%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 6         | 0.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 6         | 0.44%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.44%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.44%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 6         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM LPDDR4 2400MT/s   | 5         | 0.37%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 5         | 0.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.37%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 5         | 0.37%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.37%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 5         | 0.37%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.37%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.37%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 5         | 0.37%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.37%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 5         | 0.37%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s              | 5         | 0.37%   |
| Corsair RAM CMK8GX4M2A2666C16 4GB DIMM DDR4 2747MT/s             | 5         | 0.37%   |
| Corsair RAM CMK16GX4M2Z3600C18 8GB DIMM DDR4 3600MT/s            | 5         | 0.37%   |
| Corsair RAM CMK16GX4M2A2666C16 8GB DIMM DDR4 3400MT/s            | 5         | 0.37%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 4         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 561       | 49.25%  |
| DDR3    | 352       | 30.9%   |
| LPDDR4  | 55        | 4.83%   |
| DDR2    | 39        | 3.42%   |
| LPDDR3  | 36        | 3.16%   |
| DDR5    | 27        | 2.37%   |
| SDRAM   | 26        | 2.28%   |
| Unknown | 19        | 1.67%   |
| LPDDR5  | 10        | 0.88%   |
| DDR     | 9         | 0.79%   |
| DRAM    | 5         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 607       | 53.43%  |
| DIMM         | 416       | 36.62%  |
| Row Of Chips | 94        | 8.27%   |
| Chip         | 11        | 0.97%   |
| Unknown      | 4         | 0.35%   |
| RIMM         | 3         | 0.26%   |
| FB-DIMM      | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 495       | 40.54%  |
| 4096    | 279       | 22.85%  |
| 16384   | 237       | 19.41%  |
| 2048    | 139       | 11.38%  |
| 32768   | 32        | 2.62%   |
| 1024    | 32        | 2.62%   |
| 512     | 6         | 0.49%   |
| Unknown | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 228       | 18.72%  |
| 3200    | 171       | 14.04%  |
| 2667    | 138       | 11.33%  |
| 2400    | 92        | 7.55%   |
| 2133    | 81        | 6.65%   |
| 3600    | 62        | 5.09%   |
| 1333    | 60        | 4.93%   |
| 4267    | 28        | 2.3%    |
| 1334    | 28        | 2.3%    |
| 1867    | 26        | 2.13%   |
| 667     | 26        | 2.13%   |
| Unknown | 22        | 1.81%   |
| 800     | 20        | 1.64%   |
| 4800    | 17        | 1.4%    |
| 1067    | 16        | 1.31%   |
| 3400    | 13        | 1.07%   |
| 3000    | 13        | 1.07%   |
| 1800    | 13        | 1.07%   |
| 6400    | 12        | 0.99%   |
| 3533    | 11        | 0.9%    |
| 4266    | 10        | 0.82%   |
| 1066    | 10        | 0.82%   |
| 3733    | 9         | 0.74%   |
| 3266    | 9         | 0.74%   |
| 2666    | 9         | 0.74%   |
| 3800    | 8         | 0.66%   |
| 2933    | 7         | 0.57%   |
| 4199    | 6         | 0.49%   |
| 1866    | 6         | 0.49%   |
| 6000    | 5         | 0.41%   |
| 3466    | 5         | 0.41%   |
| 2747    | 5         | 0.41%   |
| 3866    | 4         | 0.33%   |
| 8400    | 3         | 0.25%   |
| 2000    | 3         | 0.25%   |
| 49926   | 2         | 0.16%   |
| 5600    | 2         | 0.16%   |
| 3933    | 2         | 0.16%   |
| 3666    | 2         | 0.16%   |
| 3151    | 2         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 13        | 41.94%  |
| Brother Industries    | 6         | 19.35%  |
| Samsung Electronics   | 5         | 16.13%  |
| Canon                 | 3         | 9.68%   |
| Seiko Epson           | 2         | 6.45%   |
| Oki Data              | 1         | 3.23%   |
| Lexmark International | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 2         | 6.45%   |
| HP LaserJet 1020                     | 2         | 6.45%   |
| Seiko Epson XP-4100 Series           | 1         | 3.23%   |
| Seiko Epson Printer                  | 1         | 3.23%   |
| Samsung SCX-3200 Series              | 1         | 3.23%   |
| Samsung M2070 Series                 | 1         | 3.23%   |
| Samsung Color Laser Printer          | 1         | 3.23%   |
| Oki Data USB Device                  | 1         | 3.23%   |
| Lexmark International MX317dn        | 1         | 3.23%   |
| HP OfficeJet Pro 8730                | 1         | 3.23%   |
| HP OfficeJet G55                     | 1         | 3.23%   |
| HP LaserJet Professional P 1102w     | 1         | 3.23%   |
| HP LaserJet P2035                    | 1         | 3.23%   |
| HP LaserJet 1320                     | 1         | 3.23%   |
| HP ENVY 4520 series                  | 1         | 3.23%   |
| HP DeskJet 5650c                     | 1         | 3.23%   |
| HP Deskjet 3050 J610 series          | 1         | 3.23%   |
| HP DeskJet 2700 series               | 1         | 3.23%   |
| HP DeskJet 2130 series               | 1         | 3.23%   |
| HP Color LaserJet CP1215             | 1         | 3.23%   |
| Canon LiDE 300                       | 1         | 3.23%   |
| Canon LBP7010C/7018C                 | 1         | 3.23%   |
| Canon LBP6200                        | 1         | 3.23%   |
| Brother QL-500 label printer         | 1         | 3.23%   |
| Brother HL-5150D series              | 1         | 3.23%   |
| Brother HL-2270DW Laser Printer      | 1         | 3.23%   |
| Brother HL-2130 series               | 1         | 3.23%   |
| Brother DCP-7055W                    | 1         | 3.23%   |
| Brother DCP-7040                     | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 80%     |
| Seiko Epson     | 1         | 10%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 100                     | 2         | 20%     |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1         | 10%     |
| HP ScanJet 2200c                            | 1         | 10%     |
| Canon CanoScan LiDE 700F                    | 1         | 10%     |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |
| Canon CanoScan LiDE 120                     | 1         | 10%     |
| Canon CanoScan LiDE 110                     | 1         | 10%     |
| Canon CanoScan 4400F                        | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 271       | 22.64%  |
| Microdia                               | 109       | 9.11%   |
| IMC Networks                           | 100       | 8.35%   |
| Logitech                               | 96        | 8.02%   |
| Realtek Semiconductor                  | 75        | 6.27%   |
| Bison Electronics                      | 66        | 5.51%   |
| Sunplus Innovation Technology          | 53        | 4.43%   |
| Apple                                  | 51        | 4.26%   |
| Cheng Uei Precision Industry (Foxlink) | 46        | 3.84%   |
| Quanta                                 | 43        | 3.59%   |
| Lite-On Technology                     | 37        | 3.09%   |
| Acer                                   | 34        | 2.84%   |
| Syntek                                 | 31        | 2.59%   |
| Suyin                                  | 30        | 2.51%   |
| Luxvisions Innotech Limited            | 17        | 1.42%   |
| Samsung Electronics                    | 15        | 1.25%   |
| Microsoft                              | 13        | 1.09%   |
| Ricoh                                  | 10        | 0.84%   |
| Lenovo                                 | 10        | 0.84%   |
| Alcor Micro                            | 9         | 0.75%   |
| Silicon Motion                         | 7         | 0.58%   |
| ALi                                    | 6         | 0.5%    |
| Z-Star Microelectronics                | 5         | 0.42%   |
| Creative Technology                    | 5         | 0.42%   |
| Trust                                  | 4         | 0.33%   |
| Sonix Technology                       | 4         | 0.33%   |
| Primax Electronics                     | 4         | 0.33%   |
| DigiTech                               | 4         | 0.33%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.25%   |
| Generalplus Technology                 | 3         | 0.25%   |
| ARC International                      | 3         | 0.25%   |
| SunplusIT                              | 2         | 0.17%   |
| Sunplus Technology                     | 2         | 0.17%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.17%   |
| LG Electronics                         | 2         | 0.17%   |
| Importek                               | 2         | 0.17%   |
| webcamvendor                           | 1         | 0.08%   |
| Valve Software                         | 1         | 0.08%   |
| Tobii Technology AB                    | 1         | 0.08%   |
| Sony                                   | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                | 67        | 5.54%   |
| Microdia Integrated_Webcam_HD                                            | 48        | 3.97%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 40        | 3.31%   |
| IMC Networks Integrated Camera                                           | 31        | 2.56%   |
| Realtek Integrated_Webcam_HD                                             | 26        | 2.15%   |
| Syntek Integrated Camera                                                 | 23        | 1.9%    |
| Chicony HP HD Camera                                                     | 21        | 1.74%   |
| Bison Integrated Camera                                                  | 21        | 1.74%   |
| Chicony HD Webcam                                                        | 19        | 1.57%   |
| Logitech HD Pro Webcam C920                                              | 17        | 1.41%   |
| Logitech Webcam C270                                                     | 16        | 1.32%   |
| Samsung Galaxy series, misc. (MTP mode)                                  | 15        | 1.24%   |
| Sunplus HD WebCam                                                        | 14        | 1.16%   |
| Logitech C922 Pro Stream Webcam                                          | 14        | 1.16%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                                       | 14        | 1.16%   |
| Lite-On HP HD Camera                                                     | 13        | 1.08%   |
| Sunplus Integrated_Webcam_HD                                             | 12        | 0.99%   |
| Quanta HP HD Camera                                                      | 12        | 0.99%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam                      | 12        | 0.99%   |
| Bison SunplusIT Integrated Camera                                        | 12        | 0.99%   |
| Apple Built-in iSight                                                    | 12        | 0.99%   |
| Apple FaceTime HD Camera (Built-in)                                      | 11        | 0.91%   |
| Lite-On Integrated Camera                                                | 10        | 0.83%   |
| Apple FaceTime HD Camera                                                 | 10        | 0.83%   |
| Lite-On HP HD Webcam                                                     | 9         | 0.74%   |
| Chicony HP HD Webcam [Fixed]                                             | 9         | 0.74%   |
| Chicony HP HD Webcam                                                     | 9         | 0.74%   |
| Quanta HD User Facing                                                    | 8         | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 8         | 0.66%   |
| Chicony USB2.0 HD UVC WebCam                                             | 8         | 0.66%   |
| Chicony HP Wide Vision HD Camera                                         | 8         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 8         | 0.66%   |
| Acer Lenovo EasyCamera                                                   | 8         | 0.66%   |
| Syntek Lenovo EasyCamera                                                 | 7         | 0.58%   |
| Suyin HP TrueVision HD                                                   | 7         | 0.58%   |
| Realtek USB2.0 HD UVC WebCam                                             | 7         | 0.58%   |
| Microdia USB 2.0 Camera                                                  | 7         | 0.58%   |
| Luxvisions Innotech Limited HP HD Camera                                 | 7         | 0.58%   |
| Chicony USB2.0 Camera                                                    | 7         | 0.58%   |
| Chicony Integrated HP HD Webcam                                          | 7         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 130       | 43.92%  |
| Synaptics                  | 90        | 30.41%  |
| Shenzhen Goodix Technology | 28        | 9.46%   |
| Elan Microelectronics      | 13        | 4.39%   |
| Upek                       | 11        | 3.72%   |
| AuthenTec                  | 11        | 3.72%   |
| LighTuning Technology      | 7         | 2.36%   |
| STMicroelectronics         | 6         | 2.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 14.19%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 5.74%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 17        | 5.74%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 16        | 5.41%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 4.39%   |
| Shenzhen Goodix FingerPrint                                                | 13        | 4.39%   |
| Validity Sensors VFS491                                                    | 12        | 4.05%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 3.38%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 3.38%   |
| Synaptics WBDI                                                             | 9         | 3.04%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 3.04%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.36%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 2.36%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 2.03%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.03%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 2.03%   |
| Elan ELAN:Fingerprint                                                      | 6         | 2.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.69%   |
| Synaptics  WBDI                                                            | 5         | 1.69%   |
| AuthenTec AES2810                                                          | 5         | 1.69%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.69%   |
| Synaptics UWP WBDI                                                         | 4         | 1.35%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.35%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 1.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 1.01%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.01%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 3         | 1.01%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 1.01%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.01%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.68%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.68%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.68%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.68%   |
| Unknown                                                                    | 2         | 0.68%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.34%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Alcor Micro                       | 68        | 42.77%  |
| Broadcom                          | 61        | 38.36%  |
| O2 Micro                          | 11        | 6.92%   |
| Lenovo                            | 6         | 3.77%   |
| Upek                              | 5         | 3.14%   |
| Gemalto (was Gemplus)             | 3         | 1.89%   |
| Yubico.com                        | 1         | 0.63%   |
| VASCO Data Security International | 1         | 0.63%   |
| Hewlett-Packard                   | 1         | 0.63%   |
| Chicony Electronics               | 1         | 0.63%   |
| Cherry                            | 1         | 0.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 65        | 40.88%  |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 11.32%  |
| Broadcom 58200                                                               | 17        | 10.69%  |
| Broadcom 5880                                                                | 13        | 8.18%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 7.55%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 5.66%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.77%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 3.14%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.89%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 1.89%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.26%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.63%   |
| VASCO Data Security International DIGIPASS 920                               | 1         | 0.63%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.63%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.63%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1426      | 65.65%  |
| 1     | 562       | 25.87%  |
| 2     | 158       | 7.27%   |
| 3     | 17        | 0.78%   |
| 4     | 7         | 0.32%   |
| 7     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 294       | 31.48%  |
| Graphics card            | 173       | 18.52%  |
| Chipcard                 | 143       | 15.31%  |
| Net/wireless             | 86        | 9.21%   |
| Multimedia controller    | 58        | 6.21%   |
| Communication controller | 43        | 4.6%    |
| Camera                   | 30        | 3.21%   |
| Unassigned class         | 28        | 3%      |
| Bluetooth                | 22        | 2.36%   |
| Sound                    | 17        | 1.82%   |
| Card reader              | 13        | 1.39%   |
| Net/ethernet             | 9         | 0.96%   |
| Storage                  | 4         | 0.43%   |
| Storage/ata              | 2         | 0.21%   |
| Network                  | 2         | 0.21%   |
| Modem                    | 2         | 0.21%   |
| Flash memory             | 2         | 0.21%   |
| Firewire controller      | 2         | 0.21%   |
| Storage/raid             | 1         | 0.11%   |
| Storage/nvme             | 1         | 0.11%   |
| Storage/ide              | 1         | 0.11%   |
| Dvb card                 | 1         | 0.11%   |

