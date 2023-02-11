Linux in Spain - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Spain/Desktop/README.md) and [notebooks](/Location/Spain/Notebook/README.md).

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

Total: 6882

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookPro11,1              | Notebook    | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | Notebook    | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| Jetway        | I61G-ITX                    | Desktop     | [24cf6ad56e](https://linux-hardware.org/?probe=24cf6ad56e) | Jan 31, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | Notebook    | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b5f1f3cb42](https://linux-hardware.org/?probe=b5f1f3cb42) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | Notebook    | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | 339A                        | Desktop     | [3bc7df3921](https://linux-hardware.org/?probe=3bc7df3921) | Jan 30, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [190e9b4aee](https://linux-hardware.org/?probe=190e9b4aee) | Jan 30, 2023 |
| HP            | G62                         | Notebook    | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | Notebook    | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | Notebook    | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Intel         | powered classmate PC        | Notebook    | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [72e0a3fde5](https://linux-hardware.org/?probe=72e0a3fde5) | Jan 28, 2023 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [a1cb8edb5a](https://linux-hardware.org/?probe=a1cb8edb5a) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | Notebook    | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | 312D NOK                    | Mini pc     | [854a69817d](https://linux-hardware.org/?probe=854a69817d) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [cd55d1ec5d](https://linux-hardware.org/?probe=cd55d1ec5d) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | Notebook    | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| HP            | 3397                        | Desktop     | [764f737fcf](https://linux-hardware.org/?probe=764f737fcf) | Jan 27, 2023 |
| Medion        | MS-7675                     | Desktop     | [1d9d209dbf](https://linux-hardware.org/?probe=1d9d209dbf) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| HP            | 3397                        | Desktop     | [10b6614763](https://linux-hardware.org/?probe=10b6614763) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | Notebook    | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| MSI           | MS-7383                     | Desktop     | [d47659fcf8](https://linux-hardware.org/?probe=d47659fcf8) | Jan 25, 2023 |
| MSI           | MS-7383                     | Desktop     | [b848100b0e](https://linux-hardware.org/?probe=b848100b0e) | Jan 25, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [73bef1464f](https://linux-hardware.org/?probe=73bef1464f) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [e1d742770d](https://linux-hardware.org/?probe=e1d742770d) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| MSI           | MS-B1831                    | Desktop     | [64348a9180](https://linux-hardware.org/?probe=64348a9180) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| HP            | 2B34                        | Desktop     | [ca97840b4b](https://linux-hardware.org/?probe=ca97840b4b) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | Notebook    | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [95898eae6d](https://linux-hardware.org/?probe=95898eae6d) | Jan 23, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [872cd0446b](https://linux-hardware.org/?probe=872cd0446b) | Jan 23, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| Gigabyte      | H81M-S2H                    | Desktop     | [b2aecb083b](https://linux-hardware.org/?probe=b2aecb083b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [73779874bd](https://linux-hardware.org/?probe=73779874bd) | Jan 23, 2023 |
| ASRock        | 960GM/U3S3 FX               | Desktop     | [39f5980c8d](https://linux-hardware.org/?probe=39f5980c8d) | Jan 22, 2023 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [70bd257f2c](https://linux-hardware.org/?probe=70bd257f2c) | Jan 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [88d7926aef](https://linux-hardware.org/?probe=88d7926aef) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | Notebook    | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [05c0d355e1](https://linux-hardware.org/?probe=05c0d355e1) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [eb73cef296](https://linux-hardware.org/?probe=eb73cef296) | Jan 22, 2023 |
| Eii           | GB01                        | Desktop     | [0b5b540112](https://linux-hardware.org/?probe=0b5b540112) | Jan 22, 2023 |
| Qilive        | QW2214SP                    | Notebook    | [2dba516c91](https://linux-hardware.org/?probe=2dba516c91) | Jan 22, 2023 |
| Clevo         | W150ER                      | Notebook    | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | Notebook    | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| AZW           | U59                         | Desktop     | [de70883bbf](https://linux-hardware.org/?probe=de70883bbf) | Jan 20, 2023 |
| MSI           | H170 GAMING M3              | Desktop     | [2fe05693b8](https://linux-hardware.org/?probe=2fe05693b8) | Jan 20, 2023 |
| Toshiba       | NB520                       | Notebook    | [0252e3bec1](https://linux-hardware.org/?probe=0252e3bec1) | Jan 20, 2023 |
| ECS           | APLD-MINI                   | Desktop     | [78e90e4760](https://linux-hardware.org/?probe=78e90e4760) | Jan 20, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | Notebook    | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Intel         | NUC8BEB J72693-308          | Mini pc     | [26e47819f8](https://linux-hardware.org/?probe=26e47819f8) | Jan 18, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [bb86adb1ed](https://linux-hardware.org/?probe=bb86adb1ed) | Jan 18, 2023 |
| Dell          | Latitude 5410               | Notebook    | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| Gigabyte      | B460M DS3H                  | Desktop     | [4d510de3d8](https://linux-hardware.org/?probe=4d510de3d8) | Jan 18, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [9f9fa2e0be](https://linux-hardware.org/?probe=9f9fa2e0be) | Jan 18, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [6b721444d5](https://linux-hardware.org/?probe=6b721444d5) | Jan 18, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [7f1cfd2c02](https://linux-hardware.org/?probe=7f1cfd2c02) | Jan 18, 2023 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [8f292282cb](https://linux-hardware.org/?probe=8f292282cb) | Jan 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0d3da58e45](https://linux-hardware.org/?probe=0d3da58e45) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| MSI           | B560M-A PRO                 | Desktop     | [8b665c7b84](https://linux-hardware.org/?probe=8b665c7b84) | Jan 18, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [70c0fea989](https://linux-hardware.org/?probe=70c0fea989) | Jan 18, 2023 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [273e93cce5](https://linux-hardware.org/?probe=273e93cce5) | Jan 18, 2023 |
| Eii           | GB01                        | Desktop     | [35c7a7739d](https://linux-hardware.org/?probe=35c7a7739d) | Jan 18, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [407f5b7997](https://linux-hardware.org/?probe=407f5b7997) | Jan 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [e44a974b71](https://linux-hardware.org/?probe=e44a974b71) | Jan 17, 2023 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [04e8f0fb25](https://linux-hardware.org/?probe=04e8f0fb25) | Jan 17, 2023 |
| HP            | 3047h                       | Desktop     | [ad1e495439](https://linux-hardware.org/?probe=ad1e495439) | Jan 17, 2023 |
| MSI           | H510M-A PRO                 | Desktop     | [7d05783196](https://linux-hardware.org/?probe=7d05783196) | Jan 17, 2023 |
| ASUSTek       | M4N68T-M-V2                 | Desktop     | [53b9512a96](https://linux-hardware.org/?probe=53b9512a96) | Jan 17, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0e4dd4c424](https://linux-hardware.org/?probe=0e4dd4c424) | Jan 17, 2023 |
| Dell          | Latitude 7490               | Notebook    | [390dc07426](https://linux-hardware.org/?probe=390dc07426) | Jan 17, 2023 |
| ASUSTek       | 1018P                       | Notebook    | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| HP            | Pro x2 612 G2               | Tablet      | [be72db11da](https://linux-hardware.org/?probe=be72db11da) | Jan 16, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5a622c4769](https://linux-hardware.org/?probe=5a622c4769) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | Notebook    | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c854a01151](https://linux-hardware.org/?probe=c854a01151) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b0abb21613](https://linux-hardware.org/?probe=b0abb21613) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [623477fd9e](https://linux-hardware.org/?probe=623477fd9e) | Jan 16, 2023 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [a8ab10ee00](https://linux-hardware.org/?probe=a8ab10ee00) | Jan 16, 2023 |
| ASUSTek       | K55DR                       | Notebook    | [0dde03d33e](https://linux-hardware.org/?probe=0dde03d33e) | Jan 16, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [92f9f48219](https://linux-hardware.org/?probe=92f9f48219) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| Sony          | VGN-AR51J                   | Notebook    | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| Dell          | Latitude E5550              | Notebook    | [ccbb0c484f](https://linux-hardware.org/?probe=ccbb0c484f) | Jan 15, 2023 |
| Dell          | Latitude E5550              | Notebook    | [28471496b4](https://linux-hardware.org/?probe=28471496b4) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [9816c00c67](https://linux-hardware.org/?probe=9816c00c67) | Jan 15, 2023 |
| HP            | Presario CQ57               | Notebook    | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| MSI           | MS-B1711                    | Desktop     | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [b6b45a8594](https://linux-hardware.org/?probe=b6b45a8594) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [812b55536d](https://linux-hardware.org/?probe=812b55536d) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [a69d4b7b4f](https://linux-hardware.org/?probe=a69d4b7b4f) | Jan 15, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [0dba4d0126](https://linux-hardware.org/?probe=0dba4d0126) | Jan 14, 2023 |
| ASUSTek       | PRIME H310M-E               | Desktop     | [7732b2e5e1](https://linux-hardware.org/?probe=7732b2e5e1) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [b70eca9c43](https://linux-hardware.org/?probe=b70eca9c43) | Jan 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cb802849a](https://linux-hardware.org/?probe=9cb802849a) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| NEC Comput... | ECS-945G                    | Desktop     | [8226ffab22](https://linux-hardware.org/?probe=8226ffab22) | Jan 14, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [af87fe7cb0](https://linux-hardware.org/?probe=af87fe7cb0) | Jan 14, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [c54bd7b409](https://linux-hardware.org/?probe=c54bd7b409) | Jan 14, 2023 |
| MSI           | Stealth GS77 12UHS          | Notebook    | [6a6636d3ba](https://linux-hardware.org/?probe=6a6636d3ba) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4f439c171e](https://linux-hardware.org/?probe=4f439c171e) | Jan 14, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [6ae0a203a7](https://linux-hardware.org/?probe=6ae0a203a7) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [76ce1a38ba](https://linux-hardware.org/?probe=76ce1a38ba) | Jan 13, 2023 |
| Lenovo        | 3144 SDK0J40697 WIN 3305... | Mini pc     | [0d01d0023b](https://linux-hardware.org/?probe=0d01d0023b) | Jan 13, 2023 |
| HP            | 8433 11                     | Desktop     | [bc44066299](https://linux-hardware.org/?probe=bc44066299) | Jan 13, 2023 |
| HP            | 212A                        | Desktop     | [92f32467ec](https://linux-hardware.org/?probe=92f32467ec) | Jan 13, 2023 |
| eMachines     | E725                        | Notebook    | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| Biostar       | B250MHC                     | Desktop     | [100bfd62e6](https://linux-hardware.org/?probe=100bfd62e6) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [0402d5609b](https://linux-hardware.org/?probe=0402d5609b) | Jan 13, 2023 |
| Unknown       | Unknown                     | Desktop     | [287fab2142](https://linux-hardware.org/?probe=287fab2142) | Jan 13, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| HP            | Mini 110-3100               | Notebook    | [e6f11256b8](https://linux-hardware.org/?probe=e6f11256b8) | Jan 12, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [9d63c96c7a](https://linux-hardware.org/?probe=9d63c96c7a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [bd4173beb3](https://linux-hardware.org/?probe=bd4173beb3) | Jan 12, 2023 |
| Lenovo        | 3102 SDK0K17763 WIN 1801... | Desktop     | [a3ce2fe598](https://linux-hardware.org/?probe=a3ce2fe598) | Jan 12, 2023 |
| Dell          | 0FM586                      | Desktop     | [529bc38dd7](https://linux-hardware.org/?probe=529bc38dd7) | Jan 12, 2023 |
| ASRock        | X570 Steel Legend           | Desktop     | [600094ae29](https://linux-hardware.org/?probe=600094ae29) | Jan 12, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [15648a0bb0](https://linux-hardware.org/?probe=15648a0bb0) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [4ce3e32165](https://linux-hardware.org/?probe=4ce3e32165) | Jan 12, 2023 |
| Intel         | NUC10i3FNB M38070-307       | Mini pc     | [26089f2f9b](https://linux-hardware.org/?probe=26089f2f9b) | Jan 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [32acfb0bee](https://linux-hardware.org/?probe=32acfb0bee) | Jan 12, 2023 |
| ALLDOCUBE     | i1405C                      | Notebook    | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [64d4a8c163](https://linux-hardware.org/?probe=64d4a8c163) | Jan 11, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [e4ca0a9947](https://linux-hardware.org/?probe=e4ca0a9947) | Jan 11, 2023 |
| ASUSTek       | X541UV                      | Notebook    | [41358ca49b](https://linux-hardware.org/?probe=41358ca49b) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | Notebook    | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | Notebook    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| Acer          | Aspire 5253G                | Notebook    | [930e997f3a](https://linux-hardware.org/?probe=930e997f3a) | Jan 11, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [e829eab59d](https://linux-hardware.org/?probe=e829eab59d) | Jan 10, 2023 |
| ASUSTek       | K53U                        | Notebook    | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Gigabyte      | X79-UP4                     | Desktop     | [89397e1c47](https://linux-hardware.org/?probe=89397e1c47) | Jan 10, 2023 |
| Sony          | VPCCW1S1E                   | Notebook    | [5cc5248e94](https://linux-hardware.org/?probe=5cc5248e94) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | Notebook    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| MSI           | PRO A320M-B                 | Desktop     | [3ffa3cf6f0](https://linux-hardware.org/?probe=3ffa3cf6f0) | Jan 10, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | Notebook    | [be6a0a28e1](https://linux-hardware.org/?probe=be6a0a28e1) | Jan 10, 2023 |
| Medion        | AXA                         | All in one  | [37a1a1bc8b](https://linux-hardware.org/?probe=37a1a1bc8b) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| MSI           | Modern 14 B10RBSW           | Notebook    | [3dea4fbc97](https://linux-hardware.org/?probe=3dea4fbc97) | Jan 10, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [60f83cacd0](https://linux-hardware.org/?probe=60f83cacd0) | Jan 10, 2023 |
| Acer          | Aspire E1-531G              | Notebook    | [2476cc24c1](https://linux-hardware.org/?probe=2476cc24c1) | Jan 10, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [f56cccfdc7](https://linux-hardware.org/?probe=f56cccfdc7) | Jan 09, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [1905ffef34](https://linux-hardware.org/?probe=1905ffef34) | Jan 09, 2023 |
| ASUSTek       | K53SC                       | Notebook    | [002a8bdf0c](https://linux-hardware.org/?probe=002a8bdf0c) | Jan 09, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [dc659db065](https://linux-hardware.org/?probe=dc659db065) | Jan 09, 2023 |
| ASUSTek       | K54L                        | Notebook    | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Lenovo        | G480 20150                  | Notebook    | [31f01e01fe](https://linux-hardware.org/?probe=31f01e01fe) | Jan 09, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3698ce3c60](https://linux-hardware.org/?probe=3698ce3c60) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [532f3544a2](https://linux-hardware.org/?probe=532f3544a2) | Jan 09, 2023 |
| Samsung       | 950QED                      | Convertible | [186e8cc52c](https://linux-hardware.org/?probe=186e8cc52c) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| Pyramid       | CPYSKI0002 A                | Desktop     | [0b20d79be6](https://linux-hardware.org/?probe=0b20d79be6) | Jan 09, 2023 |
| Dell          | Studio 1558                 | Notebook    | [0e01a19694](https://linux-hardware.org/?probe=0e01a19694) | Jan 09, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [10efec9ea3](https://linux-hardware.org/?probe=10efec9ea3) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| MSI           | Bravo 17 A4DDK              | Notebook    | [cf73810d98](https://linux-hardware.org/?probe=cf73810d98) | Jan 08, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0e302b3507](https://linux-hardware.org/?probe=0e302b3507) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | Notebook    | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| ASUSTek       | X540YA                      | Notebook    | [b7021632b6](https://linux-hardware.org/?probe=b7021632b6) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [333358164d](https://linux-hardware.org/?probe=333358164d) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Acer          | Aspire C24-860              | All in one  | [ab25618998](https://linux-hardware.org/?probe=ab25618998) | Jan 07, 2023 |
| Acer          | TravelMate P256-MG          | Notebook    | [e090a2b61c](https://linux-hardware.org/?probe=e090a2b61c) | Jan 07, 2023 |
| ASUSTek       | K53U                        | Notebook    | [46610b735e](https://linux-hardware.org/?probe=46610b735e) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASRock        | H110M-HDV                   | Desktop     | [deff7fc898](https://linux-hardware.org/?probe=deff7fc898) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ef473bb212](https://linux-hardware.org/?probe=ef473bb212) | Jan 07, 2023 |
| Google        | Candy                       | Notebook    | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [7831fb0431](https://linux-hardware.org/?probe=7831fb0431) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| Chuwi         | HeroBook Air                | Notebook    | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [46c8437a45](https://linux-hardware.org/?probe=46c8437a45) | Jan 05, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [9fd9040304](https://linux-hardware.org/?probe=9fd9040304) | Jan 05, 2023 |
| Unknown       | AM02                        | Mini pc     | [6f6c81bf78](https://linux-hardware.org/?probe=6f6c81bf78) | Jan 05, 2023 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [7921dc0197](https://linux-hardware.org/?probe=7921dc0197) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Dell          | 0FM586                      | Desktop     | [7e181126bc](https://linux-hardware.org/?probe=7e181126bc) | Jan 03, 2023 |
| Dell          | 0FM586                      | Desktop     | [fff469554f](https://linux-hardware.org/?probe=fff469554f) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| HP            | 250 G2                      | Notebook    | [430425dd1c](https://linux-hardware.org/?probe=430425dd1c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b557b201c4](https://linux-hardware.org/?probe=b557b201c4) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [3da2c535f7](https://linux-hardware.org/?probe=3da2c535f7) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | Notebook    | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [509cc939cc](https://linux-hardware.org/?probe=509cc939cc) | Jan 01, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [b0e7bc419b](https://linux-hardware.org/?probe=b0e7bc419b) | Jan 01, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [220854be2e](https://linux-hardware.org/?probe=220854be2e) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | Notebook    | [5ada77ec03](https://linux-hardware.org/?probe=5ada77ec03) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | Notebook    | [817985e5bf](https://linux-hardware.org/?probe=817985e5bf) | Jan 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [c4eccac7c7](https://linux-hardware.org/?probe=c4eccac7c7) | Dec 31, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| MSI           | Boston                      | Desktop     | [a5fd252dc2](https://linux-hardware.org/?probe=a5fd252dc2) | Dec 30, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [70dc568eae](https://linux-hardware.org/?probe=70dc568eae) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | Notebook    | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | Notebook    | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | Notebook    | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [328cfe3747](https://linux-hardware.org/?probe=328cfe3747) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | Notebook    | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Teclast       | TbooK 16 Power              | Tablet      | [c8a0dcd956](https://linux-hardware.org/?probe=c8a0dcd956) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | Notebook    | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | Notebook    | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | Notebook    | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [305018336b](https://linux-hardware.org/?probe=305018336b) | Dec 26, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [aef3959b18](https://linux-hardware.org/?probe=aef3959b18) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [9c75de7af7](https://linux-hardware.org/?probe=9c75de7af7) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | Notebook    | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [d759e5fe02](https://linux-hardware.org/?probe=d759e5fe02) | Dec 25, 2022 |
| Lenovo        | 318D                        | All in one  | [1bc8e7088b](https://linux-hardware.org/?probe=1bc8e7088b) | Dec 24, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | MS-B1421                    | Desktop     | [58968767bd](https://linux-hardware.org/?probe=58968767bd) | Dec 24, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [416b0bb4e1](https://linux-hardware.org/?probe=416b0bb4e1) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [ba498df129](https://linux-hardware.org/?probe=ba498df129) | Dec 23, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | Notebook    | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| MSI           | 2A9C                        | Desktop     | [031afb1b20](https://linux-hardware.org/?probe=031afb1b20) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7502622c61](https://linux-hardware.org/?probe=7502622c61) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | Notebook    | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | Notebook    | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | Notebook    | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [c3835ed07f](https://linux-hardware.org/?probe=c3835ed07f) | Dec 20, 2022 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [405443fc24](https://linux-hardware.org/?probe=405443fc24) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [d2c931919d](https://linux-hardware.org/?probe=d2c931919d) | Dec 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [e048dd7a4e](https://linux-hardware.org/?probe=e048dd7a4e) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | Notebook    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | Notebook    | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| HP            | 8597                        | Desktop     | [5a7ae7c6d7](https://linux-hardware.org/?probe=5a7ae7c6d7) | Dec 19, 2022 |
| Alienware     | x17 R1                      | Notebook    | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c47ff5ba34](https://linux-hardware.org/?probe=c47ff5ba34) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | Notebook    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Intel         | DH55TC AAE70932-303         | Desktop     | [631f80f725](https://linux-hardware.org/?probe=631f80f725) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [be98ae95c3](https://linux-hardware.org/?probe=be98ae95c3) | Dec 17, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [b6c7b47859](https://linux-hardware.org/?probe=b6c7b47859) | Dec 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [3af8ddb8cc](https://linux-hardware.org/?probe=3af8ddb8cc) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | Notebook    | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Lenovo        | 318D                        | All in one  | [da52280286](https://linux-hardware.org/?probe=da52280286) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [bbf59c4c2a](https://linux-hardware.org/?probe=bbf59c4c2a) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [33d60ebbbe](https://linux-hardware.org/?probe=33d60ebbbe) | Dec 16, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [83c2de0b09](https://linux-hardware.org/?probe=83c2de0b09) | Dec 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [7d1ece638c](https://linux-hardware.org/?probe=7d1ece638c) | Dec 14, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [f46b869c82](https://linux-hardware.org/?probe=f46b869c82) | Dec 14, 2022 |
| Pro-B         | INSYS                       | Desktop     | [40650eefcc](https://linux-hardware.org/?probe=40650eefcc) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [8fd3c60681](https://linux-hardware.org/?probe=8fd3c60681) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | Notebook    | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [9d665864a0](https://linux-hardware.org/?probe=9d665864a0) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [0af09d12d5](https://linux-hardware.org/?probe=0af09d12d5) | Dec 13, 2022 |
| Intel         | Eaglelake Fab D             | Desktop     | [ed5c44a200](https://linux-hardware.org/?probe=ed5c44a200) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Gigabyte      | Z370M DS3H-CF               | Desktop     | [238bda76a3](https://linux-hardware.org/?probe=238bda76a3) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | Notebook    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [c832b9b688](https://linux-hardware.org/?probe=c832b9b688) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | Notebook    | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| Dell          | 0P67HD A00                  | Desktop     | [67f13377be](https://linux-hardware.org/?probe=67f13377be) | Dec 12, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [7870cee549](https://linux-hardware.org/?probe=7870cee549) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | Notebook    | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | Notebook    | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | Notebook    | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Lenovo        | 318D                        | All in one  | [e088d4027d](https://linux-hardware.org/?probe=e088d4027d) | Dec 10, 2022 |
| Acidanther... | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [aefce63130](https://linux-hardware.org/?probe=aefce63130) | Dec 10, 2022 |
| Lenovo        | 318D                        | All in one  | [c72c2382b3](https://linux-hardware.org/?probe=c72c2382b3) | Dec 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [deab1a46db](https://linux-hardware.org/?probe=deab1a46db) | Dec 10, 2022 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [560e61c57f](https://linux-hardware.org/?probe=560e61c57f) | Dec 10, 2022 |
| MSI           | PRO Z690-A                  | Desktop     | [3e5339eeae](https://linux-hardware.org/?probe=3e5339eeae) | Dec 10, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [e098953c51](https://linux-hardware.org/?probe=e098953c51) | Dec 09, 2022 |
| Lenovo        | 31900058 STD                | All in one  | [314ed3ea05](https://linux-hardware.org/?probe=314ed3ea05) | Dec 09, 2022 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [fbbd6a06c8](https://linux-hardware.org/?probe=fbbd6a06c8) | Dec 09, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [b80c17a638](https://linux-hardware.org/?probe=b80c17a638) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [527789fc7d](https://linux-hardware.org/?probe=527789fc7d) | Dec 08, 2022 |
| Dell          | Latitude E6500              | Notebook    | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | Notebook    | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [4be2d528de](https://linux-hardware.org/?probe=4be2d528de) | Dec 06, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [787a504fd5](https://linux-hardware.org/?probe=787a504fd5) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [345597cd78](https://linux-hardware.org/?probe=345597cd78) | Dec 06, 2022 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [689479ce87](https://linux-hardware.org/?probe=689479ce87) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2A50... | Notebook    | [082e17aab7](https://linux-hardware.org/?probe=082e17aab7) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [302b36a67e](https://linux-hardware.org/?probe=302b36a67e) | Dec 05, 2022 |
| Gigabyte      | H510M S2H V2                | Desktop     | [b0b53bc408](https://linux-hardware.org/?probe=b0b53bc408) | Dec 05, 2022 |
| Toshiba       | PORTEGE M800                | Notebook    | [baf04ad2b3](https://linux-hardware.org/?probe=baf04ad2b3) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [5ae5166847](https://linux-hardware.org/?probe=5ae5166847) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1a52a1c699](https://linux-hardware.org/?probe=1a52a1c699) | Dec 05, 2022 |
| Gigabyte      | GA-880GA-UD3H               | Desktop     | [0a028304a1](https://linux-hardware.org/?probe=0a028304a1) | Dec 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [30f8bd2ae9](https://linux-hardware.org/?probe=30f8bd2ae9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | Notebook    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| MSI           | A320M-A PRO                 | Desktop     | [1b37803020](https://linux-hardware.org/?probe=1b37803020) | Dec 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [88e60fc0ba](https://linux-hardware.org/?probe=88e60fc0ba) | Dec 04, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [db7e5686f3](https://linux-hardware.org/?probe=db7e5686f3) | Dec 03, 2022 |
| HP            | 2AE2                        | Desktop     | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [dba5f63d66](https://linux-hardware.org/?probe=dba5f63d66) | Dec 03, 2022 |
| Medion        | D3F3-EM2                    | Desktop     | [e46ba957f0](https://linux-hardware.org/?probe=e46ba957f0) | Dec 02, 2022 |
| HP            | 8648                        | Desktop     | [79673ee467](https://linux-hardware.org/?probe=79673ee467) | Dec 02, 2022 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [85eab170d2](https://linux-hardware.org/?probe=85eab170d2) | Dec 02, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [9b1ef89e7e](https://linux-hardware.org/?probe=9b1ef89e7e) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f27e558f3](https://linux-hardware.org/?probe=0f27e558f3) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| ASUSTek       | UX550VD                     | Notebook    | [a3f2aafbf1](https://linux-hardware.org/?probe=a3f2aafbf1) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [b4aeee5799](https://linux-hardware.org/?probe=b4aeee5799) | Nov 30, 2022 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [dda393ca54](https://linux-hardware.org/?probe=dda393ca54) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Medion        | D3F3-EM                     | Desktop     | [ae428a6a6a](https://linux-hardware.org/?probe=ae428a6a6a) | Nov 29, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [cee0622b1f](https://linux-hardware.org/?probe=cee0622b1f) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [9d7352a65d](https://linux-hardware.org/?probe=9d7352a65d) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a95de3b373](https://linux-hardware.org/?probe=a95de3b373) | Nov 29, 2022 |
| HP            | Notebook                    | Notebook    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [d5f03d47ba](https://linux-hardware.org/?probe=d5f03d47ba) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | Notebook    | [e0701bc81d](https://linux-hardware.org/?probe=e0701bc81d) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [8bd9aae635](https://linux-hardware.org/?probe=8bd9aae635) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [c95bbb16de](https://linux-hardware.org/?probe=c95bbb16de) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | Notebook    | [3be194cb8a](https://linux-hardware.org/?probe=3be194cb8a) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | Notebook    | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [b680eec959](https://linux-hardware.org/?probe=b680eec959) | Nov 26, 2022 |
| Foxconn       | 2ABF                        | Desktop     | [d95233ff31](https://linux-hardware.org/?probe=d95233ff31) | Nov 26, 2022 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [4ded1fb943](https://linux-hardware.org/?probe=4ded1fb943) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [419b7f448b](https://linux-hardware.org/?probe=419b7f448b) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| MSI           | Z170A GAMING M3             | Desktop     | [982d7f7d0b](https://linux-hardware.org/?probe=982d7f7d0b) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [fc5f72597d](https://linux-hardware.org/?probe=fc5f72597d) | Nov 25, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| HP            | ProBook 430 G3              | Notebook    | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [e311874280](https://linux-hardware.org/?probe=e311874280) | Nov 24, 2022 |
| Lenovo        | 312A NOK                    | Desktop     | [94cdaff2c9](https://linux-hardware.org/?probe=94cdaff2c9) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| ASRock        | B75 Pro3                    | Desktop     | [e359d0bd70](https://linux-hardware.org/?probe=e359d0bd70) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | Notebook    | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | Notebook    | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | Desktop     | [1deb081598](https://linux-hardware.org/?probe=1deb081598) | Nov 23, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [fc74dc1357](https://linux-hardware.org/?probe=fc74dc1357) | Nov 22, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [f2ecb3f4a8](https://linux-hardware.org/?probe=f2ecb3f4a8) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | Notebook    | [347af27c05](https://linux-hardware.org/?probe=347af27c05) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [5f50e13ad0](https://linux-hardware.org/?probe=5f50e13ad0) | Nov 21, 2022 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [81c02af38c](https://linux-hardware.org/?probe=81c02af38c) | Nov 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [934f31fcac](https://linux-hardware.org/?probe=934f31fcac) | Nov 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [8de96e0012](https://linux-hardware.org/?probe=8de96e0012) | Nov 20, 2022 |
| Gigabyte      | H97M-D3H                    | Desktop     | [4e0102dff6](https://linux-hardware.org/?probe=4e0102dff6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [8bd0cdff15](https://linux-hardware.org/?probe=8bd0cdff15) | Nov 19, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [71b3224c4d](https://linux-hardware.org/?probe=71b3224c4d) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [9311687e42](https://linux-hardware.org/?probe=9311687e42) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | Notebook    | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [9d276a36d8](https://linux-hardware.org/?probe=9d276a36d8) | Nov 19, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [362cf69f1f](https://linux-hardware.org/?probe=362cf69f1f) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Acer          | Extensa 5220                | Notebook    | [0bf5f727ac](https://linux-hardware.org/?probe=0bf5f727ac) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | Notebook    | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [469ead98f8](https://linux-hardware.org/?probe=469ead98f8) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [248fcb5f13](https://linux-hardware.org/?probe=248fcb5f13) | Nov 17, 2022 |
| Acer          | Extensa 5220                | Notebook    | [8e9441be64](https://linux-hardware.org/?probe=8e9441be64) | Nov 17, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| Dell          | Latitude E5470              | Notebook    | [ae3d91be5a](https://linux-hardware.org/?probe=ae3d91be5a) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [567b81705d](https://linux-hardware.org/?probe=567b81705d) | Nov 15, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [389d8cf0e0](https://linux-hardware.org/?probe=389d8cf0e0) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| HP            | 0AA8h                       | Desktop     | [0f88d64eeb](https://linux-hardware.org/?probe=0f88d64eeb) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [722455f99d](https://linux-hardware.org/?probe=722455f99d) | Nov 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c9e0bcd9d6](https://linux-hardware.org/?probe=c9e0bcd9d6) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [f588871a3a](https://linux-hardware.org/?probe=f588871a3a) | Nov 14, 2022 |
| HP            | 1495                        | Desktop     | [5086b0aa3e](https://linux-hardware.org/?probe=5086b0aa3e) | Nov 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [c16c0f7d8f](https://linux-hardware.org/?probe=c16c0f7d8f) | Nov 13, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [092c39d271](https://linux-hardware.org/?probe=092c39d271) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| Dell          | G3 3579                     | Notebook    | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [fed6627c3e](https://linux-hardware.org/?probe=fed6627c3e) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [76609a3bd3](https://linux-hardware.org/?probe=76609a3bd3) | Nov 12, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [ea1d9a2fa4](https://linux-hardware.org/?probe=ea1d9a2fa4) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [e0b38a3d54](https://linux-hardware.org/?probe=e0b38a3d54) | Nov 11, 2022 |
| Timi          | TM1703                      | Notebook    | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [1117e533c3](https://linux-hardware.org/?probe=1117e533c3) | Nov 11, 2022 |
| HP            | 805E                        | All in one  | [fdd688e64e](https://linux-hardware.org/?probe=fdd688e64e) | Nov 11, 2022 |
| HP            | 805E                        | All in one  | [c37ec12e5f](https://linux-hardware.org/?probe=c37ec12e5f) | Nov 11, 2022 |
| LG Electro... | 16Z90Q-G.AD78B              | Notebook    | [e5129b607e](https://linux-hardware.org/?probe=e5129b607e) | Nov 09, 2022 |
| HP            | Pavilion g7                 | Notebook    | [3a18145808](https://linux-hardware.org/?probe=3a18145808) | Nov 09, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [4b5ec389d9](https://linux-hardware.org/?probe=4b5ec389d9) | Nov 09, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [292caf8ccf](https://linux-hardware.org/?probe=292caf8ccf) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [94746f0b72](https://linux-hardware.org/?probe=94746f0b72) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [61bf21f7dd](https://linux-hardware.org/?probe=61bf21f7dd) | Nov 09, 2022 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [3900976672](https://linux-hardware.org/?probe=3900976672) | Nov 08, 2022 |
| ASUSTek       | A88XM-PLUS                  | Desktop     | [e6eee311ea](https://linux-hardware.org/?probe=e6eee311ea) | Nov 08, 2022 |
| Valve         | Jupiter                     | Notebook    | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c36ab935b5](https://linux-hardware.org/?probe=c36ab935b5) | Nov 08, 2022 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [0aad7f7578](https://linux-hardware.org/?probe=0aad7f7578) | Nov 07, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | Notebook    | [bbb94242ec](https://linux-hardware.org/?probe=bbb94242ec) | Nov 07, 2022 |
| HP            | ZBook Studio 15.6 inch G... | Notebook    | [000b225d22](https://linux-hardware.org/?probe=000b225d22) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [80dc1502e1](https://linux-hardware.org/?probe=80dc1502e1) | Nov 06, 2022 |
| LG Electro... | 15Z990-V.AA78B              | Notebook    | [5ca4c426d8](https://linux-hardware.org/?probe=5ca4c426d8) | Nov 05, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [431f0124a5](https://linux-hardware.org/?probe=431f0124a5) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | Notebook    | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [5c5b229108](https://linux-hardware.org/?probe=5c5b229108) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | Notebook    | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| HP            | Compaq Presario A900        | Notebook    | [4c48500597](https://linux-hardware.org/?probe=4c48500597) | Nov 04, 2022 |
| Toshiba       | Satellite Pro A200          | Notebook    | [09ae3b0b13](https://linux-hardware.org/?probe=09ae3b0b13) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bd3b4f723e](https://linux-hardware.org/?probe=bd3b4f723e) | Nov 04, 2022 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ab4089c760](https://linux-hardware.org/?probe=ab4089c760) | Nov 04, 2022 |
| HP            | EliteBook Folio 1040 G1     | Notebook    | [1582ffa7f2](https://linux-hardware.org/?probe=1582ffa7f2) | Nov 04, 2022 |
| HP            | 8459                        | Desktop     | [378537c13c](https://linux-hardware.org/?probe=378537c13c) | Nov 04, 2022 |
| HP            | 1998                        | Desktop     | [ba48cbeebe](https://linux-hardware.org/?probe=ba48cbeebe) | Nov 04, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [93b2e9aea5](https://linux-hardware.org/?probe=93b2e9aea5) | Nov 04, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [8c069a1707](https://linux-hardware.org/?probe=8c069a1707) | Nov 03, 2022 |
| ASUSTek       | M3A78 PRO                   | Desktop     | [5466838c04](https://linux-hardware.org/?probe=5466838c04) | Nov 03, 2022 |
| Packard Be... | EasyNote MZ45               | Notebook    | [93dada1577](https://linux-hardware.org/?probe=93dada1577) | Nov 03, 2022 |
| Valve         | Jupiter                     | Notebook    | [62160ec2e5](https://linux-hardware.org/?probe=62160ec2e5) | Nov 03, 2022 |
| Dell          | 0X9M3X A04                  | Desktop     | [3bec3377a8](https://linux-hardware.org/?probe=3bec3377a8) | Nov 03, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [347b32510b](https://linux-hardware.org/?probe=347b32510b) | Nov 03, 2022 |
| HP            | G62                         | Notebook    | [a00ba1aae7](https://linux-hardware.org/?probe=a00ba1aae7) | Nov 03, 2022 |
| HP            | 250 G4                      | Notebook    | [ff497e0d4c](https://linux-hardware.org/?probe=ff497e0d4c) | Nov 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | Notebook    | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [f0db98f6bb](https://linux-hardware.org/?probe=f0db98f6bb) | Nov 01, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [fc832e8881](https://linux-hardware.org/?probe=fc832e8881) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | Notebook    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | Notebook    | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | Notebook    | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [202065a62d](https://linux-hardware.org/?probe=202065a62d) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | Notebook    | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1deed25a21](https://linux-hardware.org/?probe=1deed25a21) | Oct 30, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [416db8870a](https://linux-hardware.org/?probe=416db8870a) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | Notebook    | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | Notebook    | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7d6c392e74](https://linux-hardware.org/?probe=7d6c392e74) | Oct 29, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [ab324c3cdd](https://linux-hardware.org/?probe=ab324c3cdd) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [4234f1fe02](https://linux-hardware.org/?probe=4234f1fe02) | Oct 29, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [6ab822b64c](https://linux-hardware.org/?probe=6ab822b64c) | Oct 29, 2022 |
| MSI           | P45 Platinum                | Desktop     | [5507d45c35](https://linux-hardware.org/?probe=5507d45c35) | Oct 29, 2022 |
| Dell          | 0D24M8 A01                  | Desktop     | [55aa58c274](https://linux-hardware.org/?probe=55aa58c274) | Oct 29, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [56f93814ea](https://linux-hardware.org/?probe=56f93814ea) | Oct 28, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | Notebook    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| Unknown       | Unknown                     | Soc         | [44fc490d82](https://linux-hardware.org/?probe=44fc490d82) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [2ae55c9228](https://linux-hardware.org/?probe=2ae55c9228) | Oct 27, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [ea04a21af7](https://linux-hardware.org/?probe=ea04a21af7) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | Notebook    | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Intel         | H410M-E                     | Desktop     | [854c3ec5b1](https://linux-hardware.org/?probe=854c3ec5b1) | Oct 27, 2022 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [5b6d2d2922](https://linux-hardware.org/?probe=5b6d2d2922) | Oct 27, 2022 |
| Chuwi         | CoreBox                     | Mini pc     | [033d6281bd](https://linux-hardware.org/?probe=033d6281bd) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | Notebook    | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [f9e114a7e9](https://linux-hardware.org/?probe=f9e114a7e9) | Oct 26, 2022 |
| Intel         | H410M-E                     | Desktop     | [69d7d07e13](https://linux-hardware.org/?probe=69d7d07e13) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | Notebook    | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [696c30d8c3](https://linux-hardware.org/?probe=696c30d8c3) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | Notebook    | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [c05a08e1af](https://linux-hardware.org/?probe=c05a08e1af) | Oct 25, 2022 |
| Unknown       | SKYBAY                      | Desktop     | [63f22191e8](https://linux-hardware.org/?probe=63f22191e8) | Oct 24, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [936e43f0bc](https://linux-hardware.org/?probe=936e43f0bc) | Oct 24, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [0a2cbff604](https://linux-hardware.org/?probe=0a2cbff604) | Oct 24, 2022 |
| ASUSTek       | X550EA                      | Notebook    | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | Notebook    | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [cce3979970](https://linux-hardware.org/?probe=cce3979970) | Oct 22, 2022 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [6105b0d3a9](https://linux-hardware.org/?probe=6105b0d3a9) | Oct 22, 2022 |
| HP            | Pavilion g6                 | Notebook    | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d5f16dde87](https://linux-hardware.org/?probe=d5f16dde87) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | Notebook    | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | Notebook    | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| HP            | 8459                        | Desktop     | [c2ebcf9e20](https://linux-hardware.org/?probe=c2ebcf9e20) | Oct 21, 2022 |
| Shenzhen W... | AERO 2 Pro                  | Mini pc     | [95ca32a110](https://linux-hardware.org/?probe=95ca32a110) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| HP            | 8459                        | Desktop     | [d8ec2e7ee9](https://linux-hardware.org/?probe=d8ec2e7ee9) | Oct 20, 2022 |
| ASUSTek       | K54C                        | Notebook    | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [18c1a4a04d](https://linux-hardware.org/?probe=18c1a4a04d) | Oct 19, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff6334ee8f](https://linux-hardware.org/?probe=ff6334ee8f) | Oct 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [9622704d8f](https://linux-hardware.org/?probe=9622704d8f) | Oct 18, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| Gigabyte      | B450M GAMING                | Desktop     | [e1eacaa737](https://linux-hardware.org/?probe=e1eacaa737) | Oct 18, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [c6e10b3bcb](https://linux-hardware.org/?probe=c6e10b3bcb) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | Notebook    | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| MSI           | IONA                        | Desktop     | [7c164d5733](https://linux-hardware.org/?probe=7c164d5733) | Oct 17, 2022 |
| ASRock        | H110M-HDV                   | Desktop     | [3d1fde3114](https://linux-hardware.org/?probe=3d1fde3114) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | Notebook    | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [a7941186ab](https://linux-hardware.org/?probe=a7941186ab) | Oct 16, 2022 |
| MSI           | Stealth GS66 12UGS          | Notebook    | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| HP            | 1495                        | Desktop     | [109913631a](https://linux-hardware.org/?probe=109913631a) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Supermicro    | X10SL7-F                    | Server      | [8bfcad8486](https://linux-hardware.org/?probe=8bfcad8486) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [c3c46266d1](https://linux-hardware.org/?probe=c3c46266d1) | Oct 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [99fe717434](https://linux-hardware.org/?probe=99fe717434) | Oct 15, 2022 |
| MSI           | Z97 GAMING 3                | Desktop     | [b75b67267c](https://linux-hardware.org/?probe=b75b67267c) | Oct 14, 2022 |
| Google        | Liara                       | Notebook    | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Gigabyte      | P55M-UD2                    | Desktop     | [0e3ba8fdb3](https://linux-hardware.org/?probe=0e3ba8fdb3) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [57e988db9d](https://linux-hardware.org/?probe=57e988db9d) | Oct 14, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [78abe50673](https://linux-hardware.org/?probe=78abe50673) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | Notebook    | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | Notebook    | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [100f7e1b46](https://linux-hardware.org/?probe=100f7e1b46) | Oct 12, 2022 |
| Gigabyte      | EP43-DS3L                   | Desktop     | [5b1999a241](https://linux-hardware.org/?probe=5b1999a241) | Oct 12, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [1a2fe5eeb4](https://linux-hardware.org/?probe=1a2fe5eeb4) | Oct 12, 2022 |
| ASUSTek       | B150I PRO GAMING/WIFI/AU... | Desktop     | [f3b5809fc9](https://linux-hardware.org/?probe=f3b5809fc9) | Oct 12, 2022 |
| HP            | 3397                        | Desktop     | [c374208e14](https://linux-hardware.org/?probe=c374208e14) | Oct 11, 2022 |
| HP            | Laptop 17-cn2xxx            | Notebook    | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [dd9695948c](https://linux-hardware.org/?probe=dd9695948c) | Oct 11, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [b8c2a39217](https://linux-hardware.org/?probe=b8c2a39217) | Oct 10, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [c3a4a7983b](https://linux-hardware.org/?probe=c3a4a7983b) | Oct 10, 2022 |
| BESSTAR Te... | T3 MRD                      | Desktop     | [d223d492fe](https://linux-hardware.org/?probe=d223d492fe) | Oct 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | Notebook    | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [97bbb3b52b](https://linux-hardware.org/?probe=97bbb3b52b) | Oct 09, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [bef5f7f7d7](https://linux-hardware.org/?probe=bef5f7f7d7) | Oct 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | Notebook    | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [dd8bbe4068](https://linux-hardware.org/?probe=dd8bbe4068) | Oct 08, 2022 |
| Medion        | E2221T MD61083              | Convertible | [9f7f0f4ea8](https://linux-hardware.org/?probe=9f7f0f4ea8) | Oct 07, 2022 |
| Medion        | E2221T MD61083              | Convertible | [2eaf3df98c](https://linux-hardware.org/?probe=2eaf3df98c) | Oct 07, 2022 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [5b30b0591e](https://linux-hardware.org/?probe=5b30b0591e) | Oct 07, 2022 |
| Notebook      | W65_W67RB                   | Notebook    | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Unknown       | Intel X79                   | Desktop     | [9c0ffde822](https://linux-hardware.org/?probe=9c0ffde822) | Oct 06, 2022 |
| Toshiba       | Satellite R830              | Notebook    | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [2550504760](https://linux-hardware.org/?probe=2550504760) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [6f0bd5a568](https://linux-hardware.org/?probe=6f0bd5a568) | Oct 06, 2022 |
| Medion        | MS-7797                     | Desktop     | [9137d0eacf](https://linux-hardware.org/?probe=9137d0eacf) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | Notebook    | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | Notebook    | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Lenovo        | 1031 SDK0E50510 WIN 2625... | Desktop     | [771e19629c](https://linux-hardware.org/?probe=771e19629c) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [6a765c4673](https://linux-hardware.org/?probe=6a765c4673) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | Notebook    | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [c6dd3eef5d](https://linux-hardware.org/?probe=c6dd3eef5d) | Oct 05, 2022 |
| Acer          | EQ35M                       | Desktop     | [4ad6d2e719](https://linux-hardware.org/?probe=4ad6d2e719) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | Notebook    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | Notebook    | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | Notebook    | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [8d5a649ba5](https://linux-hardware.org/?probe=8d5a649ba5) | Oct 03, 2022 |
| Shuttle       | DH470                       | Desktop     | [408e44b18b](https://linux-hardware.org/?probe=408e44b18b) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | Notebook    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | Notebook    | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Intel         | D34010WYK H14771-304        | Desktop     | [fc1fb9966e](https://linux-hardware.org/?probe=fc1fb9966e) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [b902f5d873](https://linux-hardware.org/?probe=b902f5d873) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | Notebook    | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| Acer          | Batman A01                  | Desktop     | [f8ebe348e4](https://linux-hardware.org/?probe=f8ebe348e4) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [d19e0fb48b](https://linux-hardware.org/?probe=d19e0fb48b) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| Gigabyte      | H81M-D2V                    | Desktop     | [21a601e10a](https://linux-hardware.org/?probe=21a601e10a) | Sep 30, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [4707a778dc](https://linux-hardware.org/?probe=4707a778dc) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [6d92b99f8e](https://linux-hardware.org/?probe=6d92b99f8e) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [255a0a928a](https://linux-hardware.org/?probe=255a0a928a) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | Notebook    | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [b3b8d3e04f](https://linux-hardware.org/?probe=b3b8d3e04f) | Sep 26, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [9795d4f9aa](https://linux-hardware.org/?probe=9795d4f9aa) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [77d108e391](https://linux-hardware.org/?probe=77d108e391) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | Notebook    | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | 3098 NOK                    | Desktop     | [0f6ea5edfa](https://linux-hardware.org/?probe=0f6ea5edfa) | Sep 25, 2022 |
| HP            | 2B35                        | Desktop     | [724e0d61e3](https://linux-hardware.org/?probe=724e0d61e3) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Acer          | Aspire X1900                | Desktop     | [c7b768051b](https://linux-hardware.org/?probe=c7b768051b) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | Notebook    | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [173834876c](https://linux-hardware.org/?probe=173834876c) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Lenovo        | ThinkPad T450 20BV001CSP    | Notebook    | [9233c6db8f](https://linux-hardware.org/?probe=9233c6db8f) | Sep 24, 2022 |
| HP            | 15                          | Notebook    | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [4a1323c81e](https://linux-hardware.org/?probe=4a1323c81e) | Sep 24, 2022 |
| AZW           | GTR V01                     | Mini pc     | [927faa3232](https://linux-hardware.org/?probe=927faa3232) | Sep 23, 2022 |
| Shuttle       | DH470                       | Desktop     | [d00d31309a](https://linux-hardware.org/?probe=d00d31309a) | Sep 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| Shuttle       | DH470                       | Desktop     | [cb519b4bfe](https://linux-hardware.org/?probe=cb519b4bfe) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | Notebook    | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| ASUSTek       | P5K                         | Desktop     | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Sony          | VPCEB1Z1E                   | Notebook    | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| HP            | Presario CQ57               | Notebook    | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [d79e046c6d](https://linux-hardware.org/?probe=d79e046c6d) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Minix         | NEO G41V-4 Max              | Desktop     | [a1640603ca](https://linux-hardware.org/?probe=a1640603ca) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | Notebook    | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Unknown       | 1.0                         | Desktop     | [1ef071c553](https://linux-hardware.org/?probe=1ef071c553) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | Notebook    | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| MSI           | Z370 PC PRO                 | Desktop     | [7967e43f1d](https://linux-hardware.org/?probe=7967e43f1d) | Sep 20, 2022 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | Desktop     | [37fcfc48c5](https://linux-hardware.org/?probe=37fcfc48c5) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | Notebook    | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | Notebook    | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | Notebook    | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | Notebook    | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | Notebook    | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | Notebook    | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [94d45ff789](https://linux-hardware.org/?probe=94d45ff789) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| ASUSTek       | H110M-D                     | Desktop     | [7ea35cc80a](https://linux-hardware.org/?probe=7ea35cc80a) | Sep 18, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [7f906bad42](https://linux-hardware.org/?probe=7f906bad42) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | Notebook    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [0b32a9e842](https://linux-hardware.org/?probe=0b32a9e842) | Sep 17, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [e552983263](https://linux-hardware.org/?probe=e552983263) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [fab04fe2c7](https://linux-hardware.org/?probe=fab04fe2c7) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| HP            | Compaq 6720s                | Notebook    | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | Notebook    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | Notebook    | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Valve         | Jupiter                     | Notebook    | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | Notebook    | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| INFINITY      | Unknown                     | Notebook    | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | Notebook    | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb169c543e](https://linux-hardware.org/?probe=eb169c543e) | Sep 14, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [7f6ce1e4ea](https://linux-hardware.org/?probe=7f6ce1e4ea) | Sep 14, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [32884ec101](https://linux-hardware.org/?probe=32884ec101) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| BESSTAR Te... | T3 MRD                      | Desktop     | [0b03396c93](https://linux-hardware.org/?probe=0b03396c93) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Acer          | Aspire X3990                | Desktop     | [64cddc5f85](https://linux-hardware.org/?probe=64cddc5f85) | Sep 13, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | Convertible | [c5ebccdc5d](https://linux-hardware.org/?probe=c5ebccdc5d) | Sep 13, 2022 |
| Samsung       | 305V4A/305V5A               | Notebook    | [ba2ad7bf06](https://linux-hardware.org/?probe=ba2ad7bf06) | Sep 13, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [7858c98403](https://linux-hardware.org/?probe=7858c98403) | Sep 13, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [74a9860a2e](https://linux-hardware.org/?probe=74a9860a2e) | Sep 13, 2022 |
| Dell          | Latitude 7420               | Notebook    | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | Notebook    | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | Notebook    | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [93a5a7089c](https://linux-hardware.org/?probe=93a5a7089c) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | Notebook    | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | Notebook    | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [1552e587a8](https://linux-hardware.org/?probe=1552e587a8) | Sep 13, 2022 |
| Toshiba       | Satellite L50D-B            | Notebook    | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | Notebook    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [175f37281b](https://linux-hardware.org/?probe=175f37281b) | Sep 12, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | Notebook    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| MSI           | B560M PRO                   | Desktop     | [6c43058545](https://linux-hardware.org/?probe=6c43058545) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | Notebook    | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | Notebook    | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [841be89be6](https://linux-hardware.org/?probe=841be89be6) | Sep 10, 2022 |
| MSI           | MAG B550 TORPEDO            | Desktop     | [626cf13c17](https://linux-hardware.org/?probe=626cf13c17) | Sep 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [0caf1e7324](https://linux-hardware.org/?probe=0caf1e7324) | Sep 10, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| AXDIA Inte... | WINPAD V10                  | Notebook    | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [83be030771](https://linux-hardware.org/?probe=83be030771) | Sep 09, 2022 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | Desktop     | [06d3f051d1](https://linux-hardware.org/?probe=06d3f051d1) | Sep 09, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [dad38946f6](https://linux-hardware.org/?probe=dad38946f6) | Sep 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [efc8c6b2e7](https://linux-hardware.org/?probe=efc8c6b2e7) | Sep 08, 2022 |
| Lenovo        | B570e 521524G               | Notebook    | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| MSI           | IONA                        | Desktop     | [11d081dfc3](https://linux-hardware.org/?probe=11d081dfc3) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | Notebook    | [2817268e91](https://linux-hardware.org/?probe=2817268e91) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | Notebook    | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [c8a237d75e](https://linux-hardware.org/?probe=c8a237d75e) | Sep 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [1cf7076b74](https://linux-hardware.org/?probe=1cf7076b74) | Sep 07, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [ca8d36ee7e](https://linux-hardware.org/?probe=ca8d36ee7e) | Sep 07, 2022 |
| ECS           | GeForce 8000 series         | Desktop     | [7a60cea111](https://linux-hardware.org/?probe=7a60cea111) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | Notebook    | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| MSI           | Prestige 15 A10SC           | Notebook    | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| Medion        | H61H2-LM3 V1.0              | Desktop     | [96b497db35](https://linux-hardware.org/?probe=96b497db35) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [c0ad8b81fa](https://linux-hardware.org/?probe=c0ad8b81fa) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [9128ddb611](https://linux-hardware.org/?probe=9128ddb611) | Sep 05, 2022 |
| Chuwi         | Hi10 Go                     | Notebook    | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Notebook      | N141CU                      | Notebook    | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | 8767 A                      | Desktop     | [33800541e3](https://linux-hardware.org/?probe=33800541e3) | Sep 04, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [ea22a308c9](https://linux-hardware.org/?probe=ea22a308c9) | Sep 03, 2022 |
| ASRock        | X399 Phantom Gaming 6       | Desktop     | [bd2f18b5a5](https://linux-hardware.org/?probe=bd2f18b5a5) | Sep 03, 2022 |
| HP            | Compaq 8510w                | Notebook    | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [6596b0d415](https://linux-hardware.org/?probe=6596b0d415) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [99613365f5](https://linux-hardware.org/?probe=99613365f5) | Sep 01, 2022 |
| MSI           | Katana GF66 12UC            | Notebook    | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [b84d0acafb](https://linux-hardware.org/?probe=b84d0acafb) | Sep 01, 2022 |
| Dell          | 07PXPY A04                  | Server      | [f0b9cd86ef](https://linux-hardware.org/?probe=f0b9cd86ef) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | Notebook    | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3955b91269](https://linux-hardware.org/?probe=3955b91269) | Sep 01, 2022 |
| HP            | ProLiant DL165 G7           | Server      | [3148482797](https://linux-hardware.org/?probe=3148482797) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [12033c4a8b](https://linux-hardware.org/?probe=12033c4a8b) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| MSI           | H97M-G43                    | Desktop     | [978d5b45be](https://linux-hardware.org/?probe=978d5b45be) | Aug 31, 2022 |
| Gigabyte      | P85-D3                      | Desktop     | [71ce0b707c](https://linux-hardware.org/?probe=71ce0b707c) | Aug 31, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1f4a6a9ec3](https://linux-hardware.org/?probe=1f4a6a9ec3) | Aug 31, 2022 |
| Notebook      | N24_25JU                    | Notebook    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | Notebook    | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| sunxi         | Allwinner sun7i (A20) Fa... | Soc         | [632a8a0ad8](https://linux-hardware.org/?probe=632a8a0ad8) | Aug 30, 2022 |
| ASUSTek       | F3F                         | Notebook    | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Notebook                    | Notebook    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [99f7df96c2](https://linux-hardware.org/?probe=99f7df96c2) | Aug 29, 2022 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [df4630db27](https://linux-hardware.org/?probe=df4630db27) | Aug 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [7e03afa646](https://linux-hardware.org/?probe=7e03afa646) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | Notebook    | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | Notebook    | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| speedmaste... | E131x series                | Notebook    | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [68248e8ec4](https://linux-hardware.org/?probe=68248e8ec4) | Aug 26, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [437b0cd64f](https://linux-hardware.org/?probe=437b0cd64f) | Aug 26, 2022 |
| ASUSTek       | K52Jc                       | Notebook    | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [28ebe8cc1f](https://linux-hardware.org/?probe=28ebe8cc1f) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [292f932c92](https://linux-hardware.org/?probe=292f932c92) | Aug 25, 2022 |
| Gigabyte      | H81M-D3H                    | Desktop     | [89ced19bd4](https://linux-hardware.org/?probe=89ced19bd4) | Aug 25, 2022 |
| Fujitsu       | D3173-A1 S26361-D3173-A1    | Mini pc     | [273ce0954a](https://linux-hardware.org/?probe=273ce0954a) | Aug 25, 2022 |
| MSI           | H97M-G43                    | Desktop     | [3f781247f0](https://linux-hardware.org/?probe=3f781247f0) | Aug 25, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | Notebook    | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| HP            | 3647h                       | Desktop     | [dc17a52501](https://linux-hardware.org/?probe=dc17a52501) | Aug 23, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | Notebook    | [97c61c3095](https://linux-hardware.org/?probe=97c61c3095) | Aug 22, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 712       | 14.21%  |
| Ubuntu 18.04       | 502       | 10.02%  |
| Debian 11          | 199       | 3.97%   |
| Ubuntu 22.04       | 185       | 3.69%   |
| OpenMandriva 4.2   | 181       | 3.61%   |
| OpenMandriva 4.3   | 117       | 2.34%   |
| KDE neon 20.04     | 111       | 2.22%   |
| Zorin 16           | 83        | 1.66%   |
| Debian 10          | 81        | 1.62%   |
| Manjaro            | 77        | 1.54%   |
| Linux Mint 20.3    | 74        | 1.48%   |
| Ubuntu 20.10       | 72        | 1.44%   |
| Linux Mint 19.3    | 70        | 1.4%    |
| Arch               | 65        | 1.3%    |
| Ubuntu 19.04       | 61        | 1.22%   |
| Arch Rolling       | 61        | 1.22%   |
| Xubuntu 20.04      | 60        | 1.2%    |
| Ubuntu 19.10       | 58        | 1.16%   |
| Linux Mint 20.1    | 57        | 1.14%   |
| OpenMandriva 23.01 | 54        | 1.08%   |
| Ubuntu 21.04       | 53        | 1.06%   |
| Fedora 36          | 53        | 1.06%   |
| Linux Mint 20      | 52        | 1.04%   |
| Ubuntu 21.10       | 50        | 1%      |
| Linux Mint 20.2    | 47        | 0.94%   |
| Fedora 35          | 47        | 0.94%   |
| Xubuntu 18.04      | 46        | 0.92%   |
| ROSA R10           | 43        | 0.86%   |
| Kubuntu 20.04      | 43        | 0.86%   |
| Fedora 34          | 40        | 0.8%    |
| Zorin 15           | 39        | 0.78%   |
| Fedora 33          | 38        | 0.76%   |
| Pop!_OS 20.04      | 37        | 0.74%   |
| Linux Mint 21      | 35        | 0.7%    |
| Ubuntu 18.10       | 33        | 0.66%   |
| Linux Mint 19.2    | 30        | 0.6%    |
| Ubuntu 16.04       | 29        | 0.58%   |
| Debian Testing     | 29        | 0.58%   |
| Ubuntu MATE 20.04  | 28        | 0.56%   |
| ROSA R11           | 28        | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1697      | 35.67%  |
| Linux Mint    | 388       | 8.16%   |
| OpenMandriva  | 383       | 8.05%   |
| Debian        | 336       | 7.06%   |
| Fedora        | 230       | 4.83%   |
| Manjaro       | 183       | 3.85%   |
| KDE neon      | 134       | 2.82%   |
| Zorin         | 127       | 2.67%   |
| Arch          | 124       | 2.61%   |
| Endless       | 123       | 2.59%   |
| Xubuntu       | 121       | 2.54%   |
| Pop!_OS       | 112       | 2.35%   |
| ROSA          | 106       | 2.23%   |
| Kubuntu       | 101       | 2.12%   |
| Ubuntu MATE   | 54        | 1.14%   |
| Elementary    | 49        | 1.03%   |
| openSUSE      | 42        | 0.88%   |
| Gentoo        | 42        | 0.88%   |
| Ubuntu Unity  | 39        | 0.82%   |
| ArcoLinux     | 34        | 0.71%   |
| Lubuntu       | 28        | 0.59%   |
| BlackPanther  | 28        | 0.59%   |
| Kali          | 27        | 0.57%   |
| SteamOS       | 19        | 0.4%    |
| LMDE          | 19        | 0.4%    |
| Parrot        | 18        | 0.38%   |
| EndeavourOS   | 16        | 0.34%   |
| Clear Linux   | 15        | 0.32%   |
| MX            | 14        | 0.29%   |
| Ubuntu Budgie | 12        | 0.25%   |
| Garuda Linux  | 9         | 0.19%   |
| Reborn OS     | 8         | 0.17%   |
| Nobara        | 8         | 0.17%   |
| CentOS        | 8         | 0.17%   |
| Deepin        | 6         | 0.13%   |
| Ubuntu Studio | 5         | 0.11%   |
| Solus         | 5         | 0.11%   |
| RHEL          | 5         | 0.11%   |
| Peppermint    | 5         | 0.11%   |
| LFS           | 4         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 3.24%   |
| 5.16.7-desktop-1omv4003         | 116       | 2.13%   |
| 5.4.0-42-generic                | 96        | 1.76%   |
| 5.4.0-58-generic                | 60        | 1.1%    |
| 5.15.0-56-generic               | 57        | 1.04%   |
| 5.10.0-8-amd64                  | 56        | 1.03%   |
| 6.1.1-desktop-1omv2290          | 53        | 0.97%   |
| 5.4.0-52-generic                | 49        | 0.9%    |
| 5.4.0-54-generic                | 48        | 0.88%   |
| 5.4.0-26-generic                | 47        | 0.86%   |
| 5.15.0-52-generic               | 44        | 0.81%   |
| 5.3.0-28-generic                | 42        | 0.77%   |
| 5.4.0-48-generic                | 39        | 0.71%   |
| 5.3.0-40-generic                | 37        | 0.68%   |
| 5.11.0-27-generic               | 37        | 0.68%   |
| 5.0.0-37-generic                | 36        | 0.66%   |
| 5.4.0-29-generic                | 34        | 0.62%   |
| 5.4.0-65-generic                | 32        | 0.59%   |
| 5.3.0-46-generic                | 32        | 0.59%   |
| 5.11.0-43-generic               | 32        | 0.59%   |
| 5.13.0-30-generic               | 31        | 0.57%   |
| 5.0.0-32-generic                | 30        | 0.55%   |
| 5.4.0-72-generic                | 29        | 0.53%   |
| 5.4.0-40-generic                | 29        | 0.53%   |
| 5.15.0-48-generic               | 29        | 0.53%   |
| 5.10.0-18-amd64                 | 29        | 0.53%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 29        | 0.53%   |
| 5.15.0-58-generic               | 28        | 0.51%   |
| 5.4.0-47-generic                | 27        | 0.49%   |
| 5.4.0-37-generic                | 27        | 0.49%   |
| 5.3.0-51-generic                | 27        | 0.49%   |
| 5.15.0-53-generic               | 26        | 0.48%   |
| 5.13.0-39-generic               | 26        | 0.48%   |
| 5.13.0-28-generic               | 26        | 0.48%   |
| 5.11.0-41-generic               | 26        | 0.48%   |
| 5.8.0-43-generic                | 25        | 0.46%   |
| 5.8.0-44-generic                | 24        | 0.44%   |
| 5.11.0-37-generic               | 24        | 0.44%   |
| 5.4.0-70-generic                | 23        | 0.42%   |
| 5.3.0-45-generic                | 23        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 936       | 18.26%  |
| 4.15.0  | 414       | 8.08%   |
| 5.15.0  | 360       | 7.02%   |
| 5.11.0  | 275       | 5.37%   |
| 5.8.0   | 266       | 5.19%   |
| 5.3.0   | 254       | 4.96%   |
| 5.10.0  | 236       | 4.6%    |
| 5.13.0  | 235       | 4.59%   |
| 5.0.0   | 198       | 3.86%   |
| 5.10.14 | 179       | 3.49%   |
| 5.16.7  | 120       | 2.34%   |
| 4.18.0  | 113       | 2.2%    |
| 4.19.0  | 83        | 1.62%   |
| 6.1.1   | 63        | 1.23%   |
| 5.19.0  | 51        | 1%      |
| 4.9.60  | 33        | 0.64%   |
| 6.0.0   | 24        | 0.47%   |
| 4.4.0   | 22        | 0.43%   |
| 4.18.16 | 22        | 0.43%   |
| 5.18.0  | 19        | 0.37%   |
| 5.14.0  | 19        | 0.37%   |
| 5.9.16  | 15        | 0.29%   |
| 5.17.5  | 15        | 0.29%   |
| 5.9.0   | 13        | 0.25%   |
| 5.7.0   | 12        | 0.23%   |
| 5.3.18  | 12        | 0.23%   |
| 5.12.4  | 12        | 0.23%   |
| 4.9.20  | 12        | 0.23%   |
| 5.16.11 | 11        | 0.21%   |
| 5.16.0  | 11        | 0.21%   |
| 5.15.6  | 11        | 0.21%   |
| 5.8.11  | 10        | 0.2%    |
| 5.6.0   | 10        | 0.2%    |
| 5.15.32 | 10        | 0.2%    |
| 5.13.12 | 10        | 0.2%    |
| 5.11.12 | 10        | 0.2%    |
| 6.0.8   | 9         | 0.18%   |
| 6.0.6   | 9         | 0.18%   |
| 6.0.12  | 9         | 0.18%   |
| 5.17.1  | 9         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 999       | 19.72%  |
| 5.10    | 495       | 9.77%   |
| 5.15    | 472       | 9.32%   |
| 4.15    | 414       | 8.17%   |
| 5.11    | 332       | 6.55%   |
| 5.8     | 326       | 6.43%   |
| 5.3     | 282       | 5.57%   |
| 5.13    | 273       | 5.39%   |
| 5.0     | 202       | 3.99%   |
| 5.16    | 180       | 3.55%   |
| 4.18    | 136       | 2.68%   |
| 5.19    | 108       | 2.13%   |
| 4.19    | 98        | 1.93%   |
| 6.0     | 94        | 1.86%   |
| 6.1     | 88        | 1.74%   |
| 4.9     | 79        | 1.56%   |
| 5.14    | 72        | 1.42%   |
| 5.18    | 65        | 1.28%   |
| 5.9     | 52        | 1.03%   |
| 5.6     | 51        | 1.01%   |
| 5.17    | 47        | 0.93%   |
| 5.7     | 45        | 0.89%   |
| 5.12    | 44        | 0.87%   |
| 5.5     | 26        | 0.51%   |
| 4.4     | 26        | 0.51%   |
| 4.1     | 9         | 0.18%   |
| 5.2     | 8         | 0.16%   |
| 5.1     | 7         | 0.14%   |
| 4.16    | 6         | 0.12%   |
| 3.10    | 6         | 0.12%   |
| 4.20    | 4         | 0.08%   |
| 4.17    | 4         | 0.08%   |
| 4.13    | 4         | 0.08%   |
| 4.8     | 3         | 0.06%   |
| 4.14    | 3         | 0.06%   |
| 3.16    | 3         | 0.06%   |
| 4.12    | 2         | 0.04%   |
| 3.18    | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4391      | 95.62%  |
| i686    | 171       | 3.72%   |
| aarch64 | 23        | 0.5%    |
| armv7l  | 6         | 0.13%   |
| armv8l  | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 2047      | 42.36%  |
| KDE5             | 835       | 17.28%  |
| Unknown          | 625       | 12.93%  |
| XFCE             | 354       | 7.33%   |
| X-Cinnamon       | 301       | 6.23%   |
| KDE              | 157       | 3.25%   |
| MATE             | 148       | 3.06%   |
| KDE4             | 47        | 0.97%   |
| Cinnamon         | 47        | 0.97%   |
| Pantheon         | 45        | 0.93%   |
| LXQt             | 42        | 0.87%   |
| Unity            | 38        | 0.79%   |
| i3               | 29        | 0.6%    |
| Budgie           | 21        | 0.43%   |
| LXDE             | 20        | 0.41%   |
| Deepin           | 19        | 0.39%   |
| GNOME Flashback  | 14        | 0.29%   |
| openbox          | 8         | 0.17%   |
| GNOME Classic    | 6         | 0.12%   |
| bspwm            | 5         | 0.1%    |
| qtile            | 4         | 0.08%   |
| Enlightenment    | 3         | 0.06%   |
| DWM              | 3         | 0.06%   |
| xmonad           | 2         | 0.04%   |
| trinity          | 2         | 0.04%   |
| LeftWM           | 2         | 0.04%   |
| river            | 1         | 0.02%   |
| Lubuntu          | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| ICEWM            | 1         | 0.02%   |
| i3-with-shmlog   | 1         | 0.02%   |
| fvwm             | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| awesome          | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3761      | 79.6%   |
| Wayland | 561       | 11.87%  |
| Unknown | 336       | 7.11%   |
| Tty     | 67        | 1.42%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2551      | 53.5%   |
| SDDM    | 738       | 15.48%  |
| GDM     | 537       | 11.26%  |
| GDM3    | 371       | 7.78%   |
| LightDM | 347       | 7.28%   |
| TDM     | 150       | 3.15%   |
| KDM     | 48        | 1.01%   |
| XDM     | 13        | 0.27%   |
| Ly      | 5         | 0.1%    |
| SLiM    | 4         | 0.08%   |
| LXDM    | 4         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang           | Computers | Percent |
|----------------|-----------|---------|
| es_ES          | 2744      | 58.05%  |
| en_US          | 785       | 16.61%  |
| Unknown        | 634       | 13.41%  |
| ca_ES          | 171       | 3.62%   |
| en_GB          | 98        | 2.07%   |
| C              | 45        | 0.95%   |
| gl_ES          | 32        | 0.68%   |
| de_DE          | 29        | 0.61%   |
| eu_ES          | 24        | 0.51%   |
| fr_FR          | 19        | 0.4%    |
| ru_RU          | 16        | 0.34%   |
| it_IT          | 15        | 0.32%   |
| an_ES          | 12        | 0.25%   |
| es_MX          | 9         | 0.19%   |
| es_AR          | 9         | 0.19%   |
| pt_BR          | 6         | 0.13%   |
| en_IE          | 6         | 0.13%   |
| ca_AD          | 6         | 0.13%   |
| C.UTF8         | 5         | 0.11%   |
| ro_RO          | 4         | 0.08%   |
| pl_PL          | 4         | 0.08%   |
| en_AG          | 4         | 0.08%   |
| ca_ES@valencia | 4         | 0.08%   |
| pt_PT          | 3         | 0.06%   |
| nl_NL          | 3         | 0.06%   |
| fr_BE          | 3         | 0.06%   |
| es_ES.UTF8     | 3         | 0.06%   |
| POSIX          | 2         | 0.04%   |
| fr_CH          | 2         | 0.04%   |
| es_US          | 2         | 0.04%   |
| es_BO          | 2         | 0.04%   |
| en_DK          | 2         | 0.04%   |
| en_AU          | 2         | 0.04%   |
| de_AT          | 2         | 0.04%   |
| bg_BG          | 2         | 0.04%   |
| zh_CN          | 1         | 0.02%   |
| sp_SP          | 1         | 0.02%   |
| spanish        | 1         | 0.02%   |
| nb_NO          | 1         | 0.02%   |
| et_EE          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2435      | 51.9%   |
| EFI  | 2257      | 48.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3628      | 77.24%  |
| Overlay  | 415       | 8.84%   |
| Btrfs    | 294       | 6.26%   |
| Unknown  | 212       | 4.51%   |
| Xfs      | 60        | 1.28%   |
| Ext3     | 33        | 0.7%    |
| Zfs      | 23        | 0.49%   |
| Ext2     | 16        | 0.34%   |
| Tmpfs    | 7         | 0.15%   |
| Reiserfs | 4         | 0.09%   |
| Jfs      | 2         | 0.04%   |
| Aufs     | 2         | 0.04%   |
| F2fs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2746      | 58.41%  |
| GPT     | 1454      | 30.93%  |
| MBR     | 501       | 10.66%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3915      | 83.46%  |
| Yes       | 776       | 16.54%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3113      | 66.53%  |
| Yes       | 1566      | 33.47%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 888       | 19.35%  |
| Hewlett-Packard         | 659       | 14.36%  |
| Lenovo                  | 540       | 11.76%  |
| MSI                     | 400       | 8.71%   |
| Gigabyte Technology     | 385       | 8.39%   |
| Acer                    | 307       | 6.69%   |
| Dell                    | 284       | 6.19%   |
| ASRock                  | 118       | 2.57%   |
| Apple                   | 107       | 2.33%   |
| Toshiba                 | 104       | 2.27%   |
| Intel                   | 68        | 1.48%   |
| Unknown                 | 63        | 1.37%   |
| Packard Bell            | 43        | 0.94%   |
| Sony                    | 38        | 0.83%   |
| Medion                  | 37        | 0.81%   |
| HUAWEI                  | 34        | 0.74%   |
| Chuwi                   | 32        | 0.7%    |
| Samsung Electronics     | 30        | 0.65%   |
| Notebook                | 26        | 0.57%   |
| SLIMBOOK                | 25        | 0.54%   |
| LG Electronics          | 21        | 0.46%   |
| Fujitsu                 | 20        | 0.44%   |
| Raspberry Pi Foundation | 19        | 0.41%   |
| Pegatron                | 18        | 0.39%   |
| eMachines               | 18        | 0.39%   |
| ECS                     | 17        | 0.37%   |
| Valve                   | 15        | 0.33%   |
| Teclast                 | 13        | 0.28%   |
| BESSTAR Tech            | 13        | 0.28%   |
| Timi                    | 12        | 0.26%   |
| Fujitsu Siemens         | 12        | 0.26%   |
| Foxconn                 | 12        | 0.26%   |
| AMI                     | 11        | 0.24%   |
| Huanan                  | 10        | 0.22%   |
| Clevo                   | 8         | 0.17%   |
| AZW                     | 8         | 0.17%   |
| Supermicro              | 7         | 0.15%   |
| Shuttle                 | 6         | 0.13%   |
| Microsoft               | 6         | 0.13%   |
| IBM                     | 6         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 88        | 1.92%   |
| ASUS All Series                            | 52        | 1.13%   |
| Lenovo ThinkCentre E73 10DR0033SP          | 22        | 0.48%   |
| HP Pavilion g6                             | 21        | 0.46%   |
| HP Pavilion dv6                            | 19        | 0.41%   |
| HP Notebook                                | 18        | 0.39%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.39%   |
| Valve Jupiter                              | 15        | 0.33%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 15        | 0.33%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.33%   |
| Gigabyte B450M DS3H                        | 12        | 0.26%   |
| MSI MS-7C37                                | 11        | 0.24%   |
| HP G62                                     | 11        | 0.24%   |
| RPi Raspberry Pi                           | 10        | 0.22%   |
| MSI MS-7817                                | 10        | 0.22%   |
| HP Laptop 15-da0xxx                        | 10        | 0.22%   |
| Gigabyte 970A-DS3P                         | 10        | 0.22%   |
| Dell XPS 13 7390                           | 10        | 0.22%   |
| ASUS P5G41T-M LX                           | 10        | 0.22%   |
| HP Pavilion 15                             | 9         | 0.2%    |
| HP Laptop 15s-eq1xxx                       | 9         | 0.2%    |
| Gigabyte H110M-S2H                         | 9         | 0.2%    |
| MSI Prestige 15 A11SCS                     | 8         | 0.17%   |
| MSI MS-7B79                                | 8         | 0.17%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 8         | 0.17%   |
| Gigabyte B450 AORUS M                      | 8         | 0.17%   |
| ASUS X555LAB                               | 8         | 0.17%   |
| ASUS X550VX                                | 8         | 0.17%   |
| ASUS X540NA                                | 8         | 0.17%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.17%   |
| ASUS PRIME B450M-A                         | 8         | 0.17%   |
| ASUS PRIME A320M-K                         | 8         | 0.17%   |
| MSI MS-7C02                                | 7         | 0.15%   |
| MSI MS-7B86                                | 7         | 0.15%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.15%   |
| Lenovo G50-70 20351                        | 7         | 0.15%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.15%   |
| HP Pavilion dv7                            | 7         | 0.15%   |
| HP OMEN by Laptop                          | 7         | 0.15%   |
| HP Laptop 15s-fq1xxx                       | 7         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 224       | 4.88%   |
| Lenovo ThinkPad       | 170       | 3.7%    |
| HP Pavilion           | 138       | 3.01%   |
| Lenovo IdeaPad        | 128       | 2.79%   |
| HP Compaq             | 88        | 1.92%   |
| Unknown               | 88        | 1.92%   |
| Dell Latitude         | 85        | 1.85%   |
| Toshiba Satellite     | 80        | 1.74%   |
| ASUS PRIME            | 79        | 1.72%   |
| ASUS VivoBook         | 75        | 1.63%   |
| HP Laptop             | 68        | 1.48%   |
| HP EliteBook          | 62        | 1.35%   |
| ASUS ROG              | 60        | 1.31%   |
| ASUS TUF              | 59        | 1.29%   |
| Dell XPS              | 56        | 1.22%   |
| Lenovo ThinkCentre    | 52        | 1.13%   |
| ASUS All              | 52        | 1.13%   |
| Dell OptiPlex         | 44        | 0.96%   |
| HP ProBook            | 40        | 0.87%   |
| Dell Inspiron         | 39        | 0.85%   |
| ASUS ZenBook          | 34        | 0.74%   |
| Packard Bell EasyNote | 31        | 0.68%   |
| HP 250                | 31        | 0.68%   |
| MSI Prestige          | 24        | 0.52%   |
| Lenovo Yoga           | 24        | 0.52%   |
| HP OMEN               | 22        | 0.48%   |
| Lenovo Legion         | 21        | 0.46%   |
| Gigabyte X570         | 21        | 0.46%   |
| MSI Modern            | 20        | 0.44%   |
| Gigabyte B450M        | 20        | 0.44%   |
| Dell Precision        | 20        | 0.44%   |
| RPi Raspberry         | 19        | 0.41%   |
| HP ENVY               | 19        | 0.41%   |
| Lenovo ThinkBook      | 18        | 0.39%   |
| HP Notebook           | 18        | 0.39%   |
| Acer Extensa          | 18        | 0.39%   |
| ASUS ASUS             | 17        | 0.37%   |
| Acer TravelMate       | 16        | 0.35%   |
| Valve Jupiter         | 15        | 0.33%   |
| Gigabyte B450         | 15        | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 477       | 10.39%  |
| 2019    | 436       | 9.5%    |
| 2020    | 389       | 8.47%   |
| 2014    | 319       | 6.95%   |
| 2012    | 288       | 6.27%   |
| 2013    | 285       | 6.21%   |
| 2017    | 281       | 6.12%   |
| 2021    | 274       | 5.97%   |
| 2011    | 274       | 5.97%   |
| 2015    | 266       | 5.8%    |
| 2010    | 251       | 5.47%   |
| 2009    | 222       | 4.84%   |
| 2008    | 219       | 4.77%   |
| 2016    | 216       | 4.71%   |
| 2007    | 157       | 3.42%   |
| 2022    | 90        | 1.96%   |
| 2006    | 81        | 1.76%   |
| Unknown | 29        | 0.63%   |
| 2005    | 22        | 0.48%   |
| 2004    | 7         | 0.15%   |
| 2003    | 3         | 0.07%   |
| 2002    | 2         | 0.04%   |
| 2001    | 2         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2539      | 55.32%  |
| Desktop        | 1741      | 37.93%  |
| All in one     | 79        | 1.72%   |
| Convertible    | 69        | 1.5%    |
| Mini pc        | 68        | 1.48%   |
| Tablet         | 39        | 0.85%   |
| System on chip | 26        | 0.57%   |
| Server         | 25        | 0.54%   |
| Phone          | 3         | 0.07%   |
| Stick pc       | 1         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4313      | 93.4%   |
| Enabled  | 305       | 6.6%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4584      | 99.87%  |
| Yes  | 6         | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1037      | 22.23%  |
| 3.01-4.0        | 987       | 21.16%  |
| 16.01-24.0      | 947       | 20.3%   |
| 8.01-16.0       | 852       | 18.26%  |
| 32.01-64.0      | 380       | 8.15%   |
| 1.01-2.0        | 221       | 4.74%   |
| 2.01-3.0        | 75        | 1.61%   |
| 64.01-256.0     | 60        | 1.29%   |
| 0.51-1.0        | 56        | 1.2%    |
| 24.01-32.0      | 43        | 0.92%   |
| More than 256.0 | 4         | 0.09%   |
| 0.01-0.5        | 2         | 0.04%   |
| Unknown         | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 2004      | 39.46%  |
| 2.01-3.0   | 1280      | 25.21%  |
| 4.01-8.0   | 618       | 12.17%  |
| 3.01-4.0   | 541       | 10.65%  |
| 0.51-1.0   | 401       | 7.9%    |
| 8.01-16.0  | 160       | 3.15%   |
| 0.01-0.5   | 56        | 1.1%    |
| 24.01-32.0 | 8         | 0.16%   |
| 16.01-24.0 | 8         | 0.16%   |
| 32.01-64.0 | 1         | 0.02%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2838      | 59.87%  |
| 2       | 1176      | 24.81%  |
| 3       | 384       | 8.1%    |
| 4       | 167       | 3.52%   |
| 5       | 69        | 1.46%   |
| 0       | 41        | 0.86%   |
| 6       | 31        | 0.65%   |
| 7       | 13        | 0.27%   |
| 9       | 7         | 0.15%   |
| 8       | 6         | 0.13%   |
| 11      | 2         | 0.04%   |
| 10      | 2         | 0.04%   |
| 35      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2722      | 58.73%  |
| Yes       | 1913      | 41.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3988      | 86.56%  |
| No        | 619       | 13.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3449      | 74.52%  |
| No        | 1179      | 25.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2611      | 56.2%   |
| No        | 2035      | 43.8%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Spain   | 4590      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 753       | 15.07%  |
| Barcelona                  | 502       | 10.05%  |
| Valencia                   | 170       | 3.4%    |
| Seville                    | 170       | 3.4%    |
| Zaragoza                   | 75        | 1.5%    |
| Málaga                    | 74        | 1.48%   |
| Granada                    | 65        | 1.3%    |
| Valladolid                 | 51        | 1.02%   |
| Sabadell                   | 48        | 0.96%   |
| Palma                      | 48        | 0.96%   |
| Córdoba                   | 47        | 0.94%   |
| Bilbao                     | 47        | 0.94%   |
| Alcobendas                 | 47        | 0.94%   |
| Las Palmas de Gran Canaria | 45        | 0.9%    |
| Vigo                       | 43        | 0.86%   |
| Ourense                    | 37        | 0.74%   |
| Murcia                     | 36        | 0.72%   |
| Pamplona                   | 33        | 0.66%   |
| Donostia / San Sebastian   | 31        | 0.62%   |
| Alicante                   | 31        | 0.62%   |
| Oviedo                     | 29        | 0.58%   |
| Alcalá de Henares         | 29        | 0.58%   |
| Santa Cruz de Tenerife     | 27        | 0.54%   |
| Gijón                     | 27        | 0.54%   |
| A Coruña                  | 27        | 0.54%   |
| Santiago de Compostela     | 25        | 0.5%    |
| Almería                   | 25        | 0.5%    |
| Mostoles                   | 24        | 0.48%   |
| León                      | 24        | 0.48%   |
| Barakaldo                  | 23        | 0.46%   |
| Vitoria-Gasteiz            | 21        | 0.42%   |
| Salamanca                  | 21        | 0.42%   |
| Burgos                     | 21        | 0.42%   |
| Albacete                   | 21        | 0.42%   |
| Santander                  | 19        | 0.38%   |
| Getxo                      | 19        | 0.38%   |
| Terrassa                   | 18        | 0.36%   |
| Lugo                       | 18        | 0.36%   |
| Cartagena                  | 18        | 0.36%   |
| Reus                       | 17        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 1152      | 1758   | 17.19%  |
| WDC                         | 946       | 1375   | 14.12%  |
| Samsung Electronics         | 878       | 1245   | 13.1%   |
| Kingston                    | 759       | 1038   | 11.32%  |
| Toshiba                     | 497       | 739    | 7.42%   |
| SanDisk                     | 360       | 477    | 5.37%   |
| Unknown                     | 257       | 326    | 3.83%   |
| Crucial                     | 249       | 344    | 3.72%   |
| Hitachi                     | 209       | 249    | 3.12%   |
| SK hynix                    | 155       | 200    | 2.31%   |
| Intel                       | 139       | 180    | 2.07%   |
| HGST                        | 120       | 152    | 1.79%   |
| Micron Technology           | 103       | 122    | 1.54%   |
| China                       | 59        | 80     | 0.88%   |
| Phison                      | 51        | 57     | 0.76%   |
| Fujitsu                     | 43        | 49     | 0.64%   |
| KIOXIA                      | 37        | 45     | 0.55%   |
| Maxtor                      | 36        | 48     | 0.54%   |
| Apple                       | 36        | 50     | 0.54%   |
| Micron/Crucial Technology   | 34        | 42     | 0.51%   |
| OCZ                         | 31        | 40     | 0.46%   |
| Silicon Motion              | 26        | 32     | 0.39%   |
| JMicron Technology          | 23        | 25     | 0.34%   |
| Netac                       | 22        | 31     | 0.33%   |
| Transcend                   | 21        | 41     | 0.31%   |
| KIOXIA-EXCERIA              | 21        | 28     | 0.31%   |
| A-DATA Technology           | 20        | 27     | 0.3%    |
| LITEON                      | 19        | 20     | 0.28%   |
| Corsair                     | 19        | 24     | 0.28%   |
| Unknown                     | 19        | 21     | 0.28%   |
| KingSpec                    | 18        | 24     | 0.27%   |
| USB30                       | 16        | 30     | 0.24%   |
| PNY                         | 16        | 24     | 0.24%   |
| KingDian                    | 16        | 19     | 0.24%   |
| EMTEC                       | 15        | 18     | 0.22%   |
| Kingston Technology Company | 13        | 16     | 0.19%   |
| Phison Electronics          | 11        | 12     | 0.16%   |
| Patriot                     | 11        | 18     | 0.16%   |
| Intenso                     | 11        | 14     | 0.16%   |
| Drevo                       | 10        | 13     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 249       | 3.39%   |
| Kingston SA400S37480G 480GB SSD        | 109       | 1.48%   |
| Seagate ST1000DM010-2EP102 1TB         | 86        | 1.17%   |
| Kingston SA400S37120G 120GB SSD        | 77        | 1.05%   |
| Seagate ST500DM002-1BD142 500GB        | 71        | 0.97%   |
| Kingston SV300S37A120G 120GB SSD       | 69        | 0.94%   |
| Seagate ST3500418AS 500GB              | 60        | 0.82%   |
| Samsung SSD 860 EVO 500GB              | 56        | 0.76%   |
| Unknown MMC Card  64GB                 | 52        | 0.71%   |
| Unknown MMC Card  32GB                 | 47        | 0.64%   |
| Seagate ST1000DM003-1ER162 1TB         | 44        | 0.6%    |
| Crucial CT500MX500SSD1 500GB           | 44        | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB         | 43        | 0.58%   |
| Samsung SSD 850 EVO 500GB              | 43        | 0.58%   |
| Samsung SSD 850 EVO 250GB              | 43        | 0.58%   |
| Toshiba DT01ACA100 1TB                 | 42        | 0.57%   |
| Seagate ST500LT012-1DG142 500GB        | 42        | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB         | 41        | 0.56%   |
| Toshiba MQ01ABD100 1TB                 | 39        | 0.53%   |
| Seagate ST9500325AS 500GB              | 38        | 0.52%   |
| Kingston SUV400S37240G 240GB SSD       | 38        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 37        | 0.5%    |
| HGST HTS721010A9E630 1TB               | 37        | 0.5%    |
| SanDisk SSD PLUS 480GB                 | 36        | 0.49%   |
| Samsung NVMe SSD Drive 512GB           | 36        | 0.49%   |
| Samsung NVMe SSD Drive 500GB           | 36        | 0.49%   |
| Toshiba MQ01ABF050 500GB               | 34        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB          | 34        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB         | 34        | 0.46%   |
| Kingston SV300S37A240G 240GB SSD       | 33        | 0.45%   |
| Seagate ST31000528AS 1TB               | 32        | 0.44%   |
| SanDisk NVMe SSD Drive 512GB           | 32        | 0.44%   |
| Intel NVMe SSD Drive 512GB             | 30        | 0.41%   |
| Unknown SD/MMC/MS PRO 2GB              | 29        | 0.39%   |
| Unknown MMC Card  128GB                | 28        | 0.38%   |
| Toshiba MQ04ABF100 1TB                 | 28        | 0.38%   |
| Toshiba MQ01ABD050 500GB               | 28        | 0.38%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 28        | 0.38%   |
| Toshiba TR200 240GB SSD                | 27        | 0.37%   |
| WDC WD20EARX-00PASB0 2TB               | 26        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1141      | 1742   | 40.22%  |
| WDC                 | 743       | 1072   | 26.19%  |
| Toshiba             | 357       | 496    | 12.58%  |
| Hitachi             | 209       | 249    | 7.37%   |
| HGST                | 120       | 152    | 4.23%   |
| Samsung Electronics | 115       | 142    | 4.05%   |
| Fujitsu             | 42        | 48     | 1.48%   |
| Maxtor              | 31        | 42     | 1.09%   |
| Unknown             | 29        | 34     | 1.02%   |
| Apple               | 15        | 19     | 0.53%   |
| ASMT                | 8         | 12     | 0.28%   |
| USB3.0              | 6         | 6      | 0.21%   |
| Hewlett-Packard     | 3         | 4      | 0.11%   |
| USB                 | 2         | 2      | 0.07%   |
| SABRENT             | 2         | 2      | 0.07%   |
| Intenso             | 2         | 2      | 0.07%   |
| Quantum             | 1         | 1      | 0.04%   |
| PHD 3.0             | 1         | 1      | 0.04%   |
| OEM                 | 1         | 1      | 0.04%   |
| Maxone              | 1         | 1      | 0.04%   |
| LaCie               | 1         | 1      | 0.04%   |
| JMicron Technology  | 1         | 1      | 0.04%   |
| IBM-207x            | 1         | 8      | 0.04%   |
| IBM                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| Generic-            | 1         | 1      | 0.04%   |
| China               | 1         | 1      | 0.04%   |
| ASMedia             | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 692       | 945    | 30.21%  |
| Samsung Electronics | 399       | 548    | 17.42%  |
| Crucial             | 223       | 309    | 9.73%   |
| SanDisk             | 218       | 272    | 9.52%   |
| WDC                 | 118       | 166    | 5.15%   |
| Toshiba             | 93        | 165    | 4.06%   |
| China               | 57        | 78     | 2.49%   |
| SK hynix            | 36        | 40     | 1.57%   |
| Micron Technology   | 33        | 41     | 1.44%   |
| Intel               | 33        | 49     | 1.44%   |
| OCZ                 | 31        | 40     | 1.35%   |
| Netac               | 22        | 31     | 0.96%   |
| Transcend           | 20        | 40     | 0.87%   |
| LITEON              | 18        | 18     | 0.79%   |
| KingSpec            | 18        | 24     | 0.79%   |
| A-DATA Technology   | 17        | 24     | 0.74%   |
| USB30               | 16        | 30     | 0.7%    |
| KIOXIA-EXCERIA      | 16        | 20     | 0.7%    |
| KingDian            | 15        | 18     | 0.65%   |
| Apple               | 15        | 18     | 0.65%   |
| JMicron Technology  | 14        | 15     | 0.61%   |
| Emtec               | 13        | 16     | 0.57%   |
| PNY                 | 10        | 18     | 0.44%   |
| Patriot             | 10        | 17     | 0.44%   |
| Unknown             | 10        | 10     | 0.44%   |
| Intenso             | 9         | 10     | 0.39%   |
| FORESEE             | 9         | 11     | 0.39%   |
| Teclast             | 8         | 8      | 0.35%   |
| Corsair             | 8         | 11     | 0.35%   |
| Drevo               | 7         | 9      | 0.31%   |
| GOODRAM             | 6         | 8      | 0.26%   |
| Maxtor              | 5         | 6      | 0.22%   |
| LITEONIT            | 5         | 6      | 0.22%   |
| BAITITON            | 5         | 5      | 0.22%   |
| Hoodisk             | 4         | 5      | 0.17%   |
| Dogfish             | 4         | 4      | 0.17%   |
| Unknown             | 3         | 3      | 0.13%   |
| TCSUNBOW            | 3         | 3      | 0.13%   |
| SPCC                | 3         | 3      | 0.13%   |
| Plextor             | 3         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2418      | 4043   | 40.54%  |
| SSD     | 1972      | 3126   | 33.06%  |
| NVMe    | 1263      | 1756   | 21.17%  |
| MMC     | 234       | 305    | 3.92%   |
| Unknown | 78        | 96     | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3507      | 6985   | 67.16%  |
| NVMe | 1261      | 1751   | 24.15%  |
| MMC  | 234       | 305    | 4.48%   |
| SAS  | 220       | 285    | 4.21%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2819      | 4621   | 62.69%  |
| 0.51-1.0   | 1187      | 1730   | 26.4%   |
| 1.01-2.0   | 302       | 489    | 6.72%   |
| 3.01-4.0   | 75        | 121    | 1.67%   |
| 2.01-3.0   | 73        | 115    | 1.62%   |
| 4.01-10.0  | 40        | 92     | 0.89%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1366      | 28.06%  |
| 251-500        | 1134      | 23.29%  |
| 501-1000       | 640       | 13.15%  |
| 1-20           | 387       | 7.95%   |
| 51-100         | 335       | 6.88%   |
| 1001-2000      | 331       | 6.8%    |
| 21-50          | 210       | 4.31%   |
| More than 3000 | 185       | 3.8%    |
| 2001-3000      | 162       | 3.33%   |
| Unknown        | 118       | 2.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2003      | 39.58%  |
| 21-50          | 861       | 17.01%  |
| 101-250        | 646       | 12.76%  |
| 51-100         | 520       | 10.27%  |
| 251-500        | 373       | 7.37%   |
| 501-1000       | 263       | 5.2%    |
| 1001-2000      | 152       | 3%      |
| Unknown        | 118       | 2.33%   |
| More than 3000 | 69        | 1.36%   |
| 2001-3000      | 54        | 1.07%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB    | 12        | 12     | 2.82%   |
| Kingston SV300S37A120G 120GB SSD   | 12        | 14     | 2.82%   |
| Seagate ST3500418AS 500GB          | 11        | 17     | 2.58%   |
| Seagate ST9500325AS 500GB          | 8         | 10     | 1.88%   |
| Seagate ST500LT012-1DG142 500GB    | 7         | 7      | 1.64%   |
| Seagate ST1000DM003-1CH162 1TB     | 6         | 7      | 1.41%   |
| SanDisk SSD PLUS 480GB             | 6         | 7      | 1.41%   |
| Seagate ST3500320AS 500GB          | 5         | 8      | 1.17%   |
| Seagate ST31000528AS 1TB           | 5         | 6      | 1.17%   |
| HGST HTS545050A7E680 500GB         | 5         | 7      | 1.17%   |
| WDC WD5000AAKX-001CA0 500GB        | 4         | 6      | 0.94%   |
| Seagate ST9500420AS 500GB          | 4         | 4      | 0.94%   |
| Seagate ST9250827AS 250GB          | 4         | 4      | 0.94%   |
| Seagate ST31500341AS 1TB           | 4         | 4      | 0.94%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 4      | 0.94%   |
| Seagate ST1000DM003-1ER162 1TB     | 4         | 7      | 0.94%   |
| HGST HTS721010A9E630 1TB           | 4         | 4      | 0.94%   |
| Drevo X1 SSD 240GB                 | 4         | 6      | 0.94%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 3         | 3      | 0.7%    |
| WDC WD20EZRX-00DC0B0 2TB           | 3         | 3      | 0.7%    |
| WDC WD20EARX-00PASB0 2TB           | 3         | 4      | 0.7%    |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 3      | 0.7%    |
| Seagate ST3250310AS 250GB          | 3         | 3      | 0.7%    |
| Seagate ST2000DL003-9VT166 2TB     | 3         | 4      | 0.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 0.7%    |
| Seagate ST1000DM010-2EP102 1TB     | 3         | 4      | 0.7%    |
| Samsung Electronics HD501LJ 500GB  | 3         | 3      | 0.7%    |
| Kingston SUV400S37240G 240GB SSD   | 3         | 4      | 0.7%    |
| Kingston SA400S37480G 480GB SSD    | 3         | 6      | 0.7%    |
| Hitachi HTS545050A7E380 500GB      | 3         | 3      | 0.7%    |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 0.7%    |
| Fujitsu MHZ2250BH G2 250GB         | 3         | 4      | 0.7%    |
| WDC WD6400AAKS-22A7B0 640GB        | 2         | 2      | 0.47%   |
| WDC WD5000BPVT-60HXZT3 500GB       | 2         | 2      | 0.47%   |
| WDC WD5000AAKS-402AA0 500GB        | 2         | 2      | 0.47%   |
| WDC WD40EZRX-00SPEB0 4TB           | 2         | 3      | 0.47%   |
| WDC WD40EFRX-68WT0N0 4TB           | 2         | 2      | 0.47%   |
| WDC WD3200BEKT-60V5T1 320GB        | 2         | 2      | 0.47%   |
| WDC WD2500AAJS-00B4A0 250GB        | 2         | 2      | 0.47%   |
| WDC WD20EFRX-68EUZN0 2TB           | 2         | 5      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 145       | 184    | 34.86%  |
| WDC                 | 74        | 91     | 17.79%  |
| Toshiba             | 28        | 30     | 6.73%   |
| Samsung Electronics | 28        | 29     | 6.73%   |
| Hitachi             | 28        | 30     | 6.73%   |
| Kingston            | 23        | 29     | 5.53%   |
| HGST                | 18        | 21     | 4.33%   |
| SanDisk             | 12        | 13     | 2.88%   |
| Intel               | 10        | 10     | 2.4%    |
| Maxtor              | 8         | 8      | 1.92%   |
| Crucial             | 8         | 9      | 1.92%   |
| Fujitsu             | 6         | 7      | 1.44%   |
| Drevo               | 5         | 7      | 1.2%    |
| OCZ                 | 3         | 3      | 0.72%   |
| Micron Technology   | 3         | 3      | 0.72%   |
| China               | 3         | 4      | 0.72%   |
| SK hynix            | 2         | 2      | 0.48%   |
| KingDian            | 2         | 2      | 0.48%   |
| Transcend           | 1         | 4      | 0.24%   |
| Patriot             | 1         | 1      | 0.24%   |
| Intenso             | 1         | 1      | 0.24%   |
| IBM                 | 1         | 1      | 0.24%   |
| Hypertec            | 1         | 1      | 0.24%   |
| Dogfish             | 1         | 1      | 0.24%   |
| ASMT                | 1         | 2      | 0.24%   |
| Apple               | 1         | 1      | 0.24%   |
| A-DATA Technology   | 1         | 1      | 0.24%   |
| Unknown             | 1         | 1      | 0.24%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 145       | 184    | 45.17%  |
| WDC                 | 72        | 89     | 22.43%  |
| Hitachi             | 28        | 30     | 8.72%   |
| Toshiba             | 23        | 25     | 7.17%   |
| HGST                | 18        | 21     | 5.61%   |
| Samsung Electronics | 17        | 18     | 5.3%    |
| Maxtor              | 8         | 8      | 2.49%   |
| Fujitsu             | 6         | 7      | 1.87%   |
| IBM                 | 1         | 1      | 0.31%   |
| China               | 1         | 1      | 0.31%   |
| ASMT                | 1         | 2      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 301       | 387    | 76.98%  |
| SSD  | 83        | 102    | 21.23%  |
| NVMe | 7         | 7      | 1.79%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-60ZAT1 500GB       | 1         | 1      | 8.33%   |
| Toshiba DT01ACA200 2TB            | 1         | 1      | 8.33%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 8.33%   |
| Seagate ST3500830AS 500GB         | 1         | 1      | 8.33%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 8.33%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 8.33%   |
| Seagate ST31000520AS 1TB          | 1         | 1      | 8.33%   |
| Seagate ST31000333AS 1TB          | 1         | 1      | 8.33%   |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 8.33%   |
| Samsung Electronics HD253GJ 250GB | 1         | 1      | 8.33%   |
| Samsung Electronics HD103SJ 1TB   | 1         | 1      | 8.33%   |
| Hitachi HDS721010DLE630 1TB       | 1         | 1      | 8.33%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 50%     |
| Samsung Electronics | 3         | 3      | 25%     |
| WDC                 | 1         | 1      | 8.33%   |
| Toshiba             | 1         | 1      | 8.33%   |
| Hitachi             | 1         | 1      | 8.33%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2947      | 5894   | 59.15%  |
| Works    | 1647      | 2924   | 33.06%  |
| Malfunc  | 376       | 496    | 7.55%   |
| Failed   | 12        | 12     | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3129      | 55.99%  |
| AMD                              | 796       | 14.24%  |
| Samsung Electronics              | 424       | 7.59%   |
| SanDisk                          | 244       | 4.37%   |
| SK hynix                         | 110       | 1.97%   |
| Nvidia                           | 104       | 1.86%   |
| Kingston Technology Company      | 89        | 1.59%   |
| Phison Electronics               | 84        | 1.5%    |
| JMicron Technology               | 78        | 1.4%    |
| ASMedia Technology               | 76        | 1.36%   |
| Micron Technology                | 72        | 1.29%   |
| Marvell Technology Group         | 61        | 1.09%   |
| Micron/Crucial Technology        | 56        | 1%      |
| Toshiba America Info Systems     | 53        | 0.95%   |
| KIOXIA                           | 50        | 0.89%   |
| Silicon Motion                   | 33        | 0.59%   |
| VIA Technologies                 | 32        | 0.57%   |
| Silicon Integrated Systems [SiS] | 21        | 0.38%   |
| LSI Logic / Symbios Logic        | 13        | 0.23%   |
| Union Memory (Shenzhen)          | 7         | 0.13%   |
| Hewlett-Packard                  | 6         | 0.11%   |
| Silicon Image                    | 5         | 0.09%   |
| Apple                            | 5         | 0.09%   |
| Realtek Semiconductor            | 4         | 0.07%   |
| ADATA Technology                 | 4         | 0.07%   |
| Solid State Storage Technology   | 3         | 0.05%   |
| O2 Micro                         | 3         | 0.05%   |
| Lite-On Technology               | 3         | 0.05%   |
| Broadcom / LSI                   | 3         | 0.05%   |
| Adaptec                          | 3         | 0.05%   |
| Seagate Technology               | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Lenovo                           | 2         | 0.04%   |
| Integrated Technology Express    | 2         | 0.04%   |
| ULi Electronics                  | 1         | 0.02%   |
| Swissbit                         | 1         | 0.02%   |
| Shenzhen Longsys Electronics     | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| HighPoint Technologies           | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 554       | 8.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 243       | 3.7%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 233       | 3.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 231       | 3.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 141       | 2.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 137       | 2.09%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 125       | 1.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 123       | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                                  | 123       | 1.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 119       | 1.81%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 118       | 1.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 112       | 1.7%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 96        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 92        | 1.4%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 91        | 1.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 87        | 1.32%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 85        | 1.29%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 84        | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 83        | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 82        | 1.25%   |
| Samsung NVMe SSD Controller 980                                                         | 81        | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 80        | 1.22%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 78        | 1.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 77        | 1.17%   |
| Intel SATA Controller [RAID mode]                                                       | 75        | 1.14%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 75        | 1.14%   |
| Micron Non-Volatile memory controller                                                   | 72        | 1.1%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 68        | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 67        | 1.02%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 65        | 0.99%   |
| Intel SSD 660P Series                                                                   | 61        | 0.93%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 59        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 59        | 0.9%    |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 54        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 52        | 0.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 52        | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 48        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 47        | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 45        | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 45        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3287      | 57.59%  |
| NVMe | 1275      | 22.34%  |
| IDE  | 784       | 13.74%  |
| RAID | 346       | 6.06%   |
| SCSI | 9         | 0.16%   |
| SAS  | 7         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3560      | 77.56%  |
| AMD          | 999       | 21.76%  |
| ARM          | 28        | 0.61%   |
| QUALCOMM     | 2         | 0.04%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 60        | 1.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 55        | 1.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 51        | 1.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 47        | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 44        | 0.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 42        | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 39        | 0.85%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 38        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 37        | 0.8%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 37        | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 36        | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 36        | 0.78%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 0.76%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 33        | 0.72%   |
| AMD Ryzen 5 3600 6-Core Processor             | 32        | 0.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz             | 31        | 0.67%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 28        | 0.61%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 28        | 0.61%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 27        | 0.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 27        | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 26        | 0.56%   |
| Intel Core i3-4150 CPU @ 3.50GHz              | 26        | 0.56%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 26        | 0.56%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 0.54%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 0.54%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 23        | 0.5%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 23        | 0.5%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 23        | 0.5%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 23        | 0.5%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 22        | 0.48%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 22        | 0.48%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 21        | 0.46%   |
| ARM Processor                                 | 21        | 0.46%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 21        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 20        | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 19        | 0.41%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 19        | 0.41%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.39%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.39%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 18        | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 883       | 19.19%  |
| Intel Core i7           | 869       | 18.89%  |
| Intel Core i3           | 375       | 8.15%   |
| Intel Celeron           | 285       | 6.19%   |
| Other                   | 280       | 6.09%   |
| AMD Ryzen 5             | 239       | 5.19%   |
| Intel Core 2 Duo        | 231       | 5.02%   |
| AMD Ryzen 7             | 211       | 4.59%   |
| Intel Atom              | 133       | 2.89%   |
| Intel Xeon              | 93        | 2.02%   |
| Intel Pentium           | 86        | 1.87%   |
| Intel Pentium Dual-Core | 77        | 1.67%   |
| Intel Core 2 Quad       | 72        | 1.56%   |
| AMD FX                  | 59        | 1.28%   |
| Intel Pentium Dual      | 52        | 1.13%   |
| Intel Core 2            | 48        | 1.04%   |
| AMD A4                  | 44        | 0.96%   |
| AMD Ryzen 3             | 40        | 0.87%   |
| AMD Ryzen 9             | 39        | 0.85%   |
| AMD A6                  | 36        | 0.78%   |
| Intel Genuine           | 32        | 0.7%    |
| AMD A10                 | 32        | 0.7%    |
| AMD A8                  | 28        | 0.61%   |
| Intel Core i9           | 26        | 0.57%   |
| Intel Pentium 4         | 25        | 0.54%   |
| AMD Athlon 64 X2        | 24        | 0.52%   |
| AMD E1                  | 21        | 0.46%   |
| AMD Athlon II X2        | 21        | 0.46%   |
| AMD Athlon              | 19        | 0.41%   |
| AMD Phenom II X4        | 14        | 0.3%    |
| AMD E                   | 14        | 0.3%    |
| AMD Ryzen 7 PRO         | 11        | 0.24%   |
| Intel Pentium D         | 10        | 0.22%   |
| AMD Phenom              | 10        | 0.22%   |
| Intel Pentium Silver    | 9         | 0.2%    |
| Intel Pentium M         | 9         | 0.2%    |
| AMD Phenom II X6        | 8         | 0.17%   |
| Intel Pentium Gold      | 7         | 0.15%   |
| Intel Core m3           | 7         | 0.15%   |
| Intel Celeron M         | 7         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1924      | 41.77%  |
| 4       | 1621      | 35.19%  |
| 6       | 424       | 9.21%   |
| 8       | 311       | 6.75%   |
| 1       | 175       | 3.8%    |
| 12      | 52        | 1.13%   |
| 10      | 21        | 0.46%   |
| 3       | 20        | 0.43%   |
| 16      | 18        | 0.39%   |
| 14      | 18        | 0.39%   |
| Unknown | 13        | 0.28%   |
| 20      | 3         | 0.07%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 40      | 1         | 0.02%   |
| 32      | 1         | 0.02%   |
| 28      | 1         | 0.02%   |
| 24      | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4554      | 99.19%  |
| 2       | 34        | 0.74%   |
| Unknown | 3         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2855      | 62.04%  |
| 1       | 1733      | 37.66%  |
| Unknown | 13        | 0.28%   |
| 4       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4405      | 95.39%  |
| Unknown        | 113       | 2.45%   |
| 32-bit         | 66        | 1.43%   |
| 64-bit         | 34        | 0.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 922       | 19.39%  |
| 0x306c3    | 249       | 5.24%   |
| 0x206a7    | 226       | 4.75%   |
| 0x306a9    | 207       | 4.35%   |
| 0x1067a    | 173       | 3.64%   |
| 0x906ea    | 138       | 2.9%    |
| 0x806ea    | 114       | 2.4%    |
| 0x6fd      | 104       | 2.19%   |
| 0x806c1    | 103       | 2.17%   |
| 0x506e3    | 102       | 2.15%   |
| 0x40651    | 98        | 2.06%   |
| 0x806ec    | 97        | 2.04%   |
| 0x20655    | 96        | 2.02%   |
| 0x806e9    | 89        | 1.87%   |
| 0x406e3    | 87        | 1.83%   |
| 0x306d4    | 75        | 1.58%   |
| 0x906e9    | 68        | 1.43%   |
| 0x08108109 | 67        | 1.41%   |
| 0x30678    | 54        | 1.14%   |
| 0x10676    | 54        | 1.14%   |
| 0x6fb      | 49        | 1.03%   |
| 0x20652    | 47        | 0.99%   |
| 0x08701021 | 46        | 0.97%   |
| 0x706a1    | 45        | 0.95%   |
| 0x0a50000c | 41        | 0.86%   |
| 0x0800820d | 41        | 0.86%   |
| 0x706e5    | 40        | 0.84%   |
| 0x406c4    | 40        | 0.84%   |
| 0x506c9    | 39        | 0.82%   |
| 0xa0652    | 37        | 0.78%   |
| 0x06006705 | 36        | 0.76%   |
| 0x6f6      | 35        | 0.74%   |
| 0x08600106 | 34        | 0.72%   |
| 0x08108102 | 34        | 0.72%   |
| 0x010000c8 | 33        | 0.69%   |
| 0x706a8    | 32        | 0.67%   |
| 0x06001119 | 32        | 0.67%   |
| 0x06000852 | 32        | 0.67%   |
| 0x806eb    | 30        | 0.63%   |
| 0x906ed    | 28        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 713       | 15.5%   |
| Haswell          | 445       | 9.67%   |
| Penryn           | 289       | 6.28%   |
| SandyBridge      | 281       | 6.11%   |
| Core             | 249       | 5.41%   |
| IvyBridge        | 244       | 5.3%    |
| Skylake          | 230       | 5%      |
| Zen+             | 183       | 3.98%   |
| Zen 2            | 174       | 3.78%   |
| Westmere         | 171       | 3.72%   |
| Silvermont       | 160       | 3.48%   |
| TigerLake        | 135       | 2.93%   |
| Unknown          | 112       | 2.43%   |
| Broadwell        | 103       | 2.24%   |
| CometLake        | 102       | 2.22%   |
| Zen 3            | 98        | 2.13%   |
| Goldmont plus    | 92        | 2%      |
| Piledriver       | 89        | 1.93%   |
| K10              | 89        | 1.93%   |
| Zen              | 84        | 1.83%   |
| IceLake          | 68        | 1.48%   |
| Bonnell          | 64        | 1.39%   |
| Excavator        | 62        | 1.35%   |
| K8 Hammer        | 52        | 1.13%   |
| Goldmont         | 44        | 0.96%   |
| Nehalem          | 43        | 0.93%   |
| NetBurst         | 38        | 0.83%   |
| Puma             | 31        | 0.67%   |
| P6               | 30        | 0.65%   |
| Alderlake Hybrid | 29        | 0.63%   |
| Jaguar           | 26        | 0.57%   |
| Bobcat           | 22        | 0.48%   |
| Steamroller      | 20        | 0.43%   |
| K10 Llano        | 9         | 0.2%    |
| Tremont          | 8         | 0.17%   |
| Bulldozer        | 8         | 0.17%   |
| K8 & K10 hybrid  | 3         | 0.07%   |
| K6               | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2640      | 48.73%  |
| Nvidia                                       | 1585      | 29.25%  |
| AMD                                          | 1142      | 21.08%  |
| Matrox Electronics Systems                   | 17        | 0.31%   |
| Silicon Integrated Systems [SiS]             | 13        | 0.24%   |
| VIA Technologies                             | 10        | 0.18%   |
| ASPEED Technology                            | 8         | 0.15%   |
| XGI Technology (eXtreme Graphics Innovation) | 1         | 0.02%   |
| Silicon Motion                               | 1         | 0.02%   |
| ATI Technologies                             | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 195       | 3.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 129       | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 126       | 2.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 125       | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 115       | 2.05%   |
| Intel UHD Graphics 620                                                                   | 114       | 2.03%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 105       | 1.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 101       | 1.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 97        | 1.73%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 93        | 1.66%   |
| Intel HD Graphics 620                                                                    | 91        | 1.62%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 87        | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 86        | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 84        | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 84        | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 83        | 1.48%   |
| AMD Renoir                                                                               | 83        | 1.48%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 76        | 1.36%   |
| Intel HD Graphics 5500                                                                   | 73        | 1.3%    |
| Intel HD Graphics 530                                                                    | 70        | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 70        | 1.25%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 66        | 1.18%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 65        | 1.16%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 62        | 1.11%   |
| Intel HD Graphics 630                                                                    | 62        | 1.11%   |
| Nvidia GT218 [GeForce 210]                                                               | 57        | 1.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 55        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 53        | 0.95%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 50        | 0.89%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 50        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 45        | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 45        | 0.8%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 45        | 0.8%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 44        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 43        | 0.77%   |
| Intel HD Graphics 500                                                                    | 42        | 0.75%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 40        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 40        | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 37        | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 37        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| 1 x Intel              | 1887      | 40.85%  |
| 1 x AMD                | 897       | 19.42%  |
| 1 x Nvidia             | 888       | 19.22%  |
| Intel + Nvidia         | 597       | 12.92%  |
| Intel + AMD            | 95        | 2.06%   |
| AMD + Nvidia           | 82        | 1.78%   |
| 2 x AMD                | 69        | 1.49%   |
| Other                  | 33        | 0.71%   |
| 2 x Nvidia             | 14        | 0.3%    |
| 1 x Matrox             | 14        | 0.3%    |
| 1 x SiS                | 13        | 0.28%   |
| 1 x VIA                | 10        | 0.22%   |
| 1 x ASPEED             | 5         | 0.11%   |
| 2 x Intel              | 4         | 0.09%   |
| Nvidia + Matrox        | 3         | 0.06%   |
| Nvidia + ASPEED        | 3         | 0.06%   |
| 3 x AMD                | 1         | 0.02%   |
| 1 x XGI                | 1         | 0.02%   |
| 1 x Silicon Motion     | 1         | 0.02%   |
| 1 x Intel + 3 x Nvidia | 1         | 0.02%   |
| Intel + 2 x AMD        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3694      | 79.24%  |
| Proprietary | 772       | 16.56%  |
| Unknown     | 196       | 4.2%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2483      | 52.46%  |
| 1.01-2.0   | 657       | 13.88%  |
| 0.01-0.5   | 568       | 12%     |
| 3.01-4.0   | 363       | 7.67%   |
| 0.51-1.0   | 352       | 7.44%   |
| 7.01-8.0   | 169       | 3.57%   |
| 5.01-6.0   | 85        | 1.8%    |
| 2.01-3.0   | 26        | 0.55%   |
| 8.01-16.0  | 25        | 0.53%   |
| 16.01-24.0 | 5         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 583       | 11.78%  |
| AU Optronics            | 529       | 10.69%  |
| Chimei Innolux          | 471       | 9.52%   |
| LG Display              | 417       | 8.43%   |
| Goldstar                | 358       | 7.23%   |
| BOE                     | 341       | 6.89%   |
| Hewlett-Packard         | 241       | 4.87%   |
| BenQ                    | 201       | 4.06%   |
| Dell                    | 194       | 3.92%   |
| Acer                    | 174       | 3.52%   |
| Ancor Communications    | 150       | 3.03%   |
| Philips                 | 131       | 2.65%   |
| AOC                     | 99        | 2%      |
| Apple                   | 96        | 1.94%   |
| Chi Mei Optoelectronics | 92        | 1.86%   |
| Sharp                   | 86        | 1.74%   |
| Lenovo                  | 75        | 1.52%   |
| PANDA                   | 56        | 1.13%   |
| LG Electronics          | 53        | 1.07%   |
| Unknown                 | 46        | 0.93%   |
| Sony                    | 46        | 0.93%   |
| HannStar                | 41        | 0.83%   |
| LG Philips              | 39        | 0.79%   |
| ASUSTek Computer        | 31        | 0.63%   |
| ViewSonic               | 27        | 0.55%   |
| InfoVision              | 20        | 0.4%    |
| MSI                     | 19        | 0.38%   |
| Eizo                    | 14        | 0.28%   |
| OEM                     | 11        | 0.22%   |
| CPT                     | 11        | 0.22%   |
| Toshiba                 | 10        | 0.2%    |
| ___                     | 9         | 0.18%   |
| Vestel Elektronik       | 9         | 0.18%   |
| Panasonic               | 9         | 0.18%   |
| Hitachi                 | 9         | 0.18%   |
| Quanta Display          | 8         | 0.16%   |
| Packard Bell            | 8         | 0.16%   |
| NEC Computers           | 8         | 0.16%   |
| Iiyama                  | 8         | 0.16%   |
| Xiaomi                  | 7         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 64        | 1.25%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 33        | 0.65%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 30        | 0.59%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 29        | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 25        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 22        | 0.43%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.41%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.41%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 20        | 0.39%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 19        | 0.37%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.33%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 17        | 0.33%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch              | 16        | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.29%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 15        | 0.29%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                  | 14        | 0.27%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 14        | 0.27%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 14        | 0.27%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 14        | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 13        | 0.25%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 13        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.25%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 13        | 0.25%   |
| AOC 2270W AOC2270 1920x1080 477x268mm 21.5-inch                          | 13        | 0.25%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.23%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch                 | 12        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 12        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 12        | 0.23%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 12        | 0.23%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.23%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 11        | 0.22%   |
| Goldstar FULL HD GSM5AB9 1920x1080 480x270mm 21.7-inch                   | 11        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 11        | 0.22%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 10        | 0.2%    |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 10        | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2037      | 43.22%  |
| 1366x768 (WXGA)    | 995       | 21.11%  |
| 3840x2160 (4K)     | 215       | 4.56%   |
| 1280x1024 (SXGA)   | 201       | 4.26%   |
| 2560x1440 (QHD)    | 170       | 3.61%   |
| 1280x800 (WXGA)    | 155       | 3.29%   |
| 1680x1050 (WSXGA+) | 144       | 3.06%   |
| 1440x900 (WXGA+)   | 139       | 2.95%   |
| 1600x900 (HD+)     | 104       | 2.21%   |
| 1920x1200 (WUXGA)  | 83        | 1.76%   |
| Unknown            | 57        | 1.21%   |
| 2560x1080          | 52        | 1.1%    |
| 1360x768           | 44        | 0.93%   |
| 1024x600           | 40        | 0.85%   |
| 3440x1440          | 29        | 0.62%   |
| 2560x1600          | 25        | 0.53%   |
| 1024x768 (XGA)     | 24        | 0.51%   |
| 2160x1440          | 21        | 0.45%   |
| 3840x1080          | 16        | 0.34%   |
| 800x1280           | 15        | 0.32%   |
| 2880x1800          | 13        | 0.28%   |
| 1920x540           | 13        | 0.28%   |
| 1600x1200          | 13        | 0.28%   |
| 3200x1800 (QHD+)   | 8         | 0.17%   |
| 2288x1287          | 6         | 0.13%   |
| 3840x2400          | 5         | 0.11%   |
| 3200x1080          | 5         | 0.11%   |
| 4480x1080          | 4         | 0.08%   |
| 1920x1280          | 4         | 0.08%   |
| 1280x768           | 4         | 0.08%   |
| 3840x1200          | 3         | 0.06%   |
| 3600x1080          | 3         | 0.06%   |
| 3360x1080          | 3         | 0.06%   |
| 2960x1050          | 3         | 0.06%   |
| 2736x1824          | 3         | 0.06%   |
| 2048x1152          | 3         | 0.06%   |
| 1400x1050          | 3         | 0.06%   |
| 5760x2160          | 2         | 0.04%   |
| 4480x1440          | 2         | 0.04%   |
| 3840x1600          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1441      | 29.18%  |
| 13      | 374       | 7.57%   |
| 24      | 359       | 7.27%   |
| 21      | 350       | 7.09%   |
| 27      | 317       | 6.42%   |
| Unknown | 285       | 5.77%   |
| 23      | 281       | 5.69%   |
| 17      | 262       | 5.3%    |
| 14      | 250       | 5.06%   |
| 19      | 148       | 3%      |
| 18      | 117       | 2.37%   |
| 22      | 84        | 1.7%    |
| 34      | 74        | 1.5%    |
| 31      | 70        | 1.42%   |
| 20      | 69        | 1.4%    |
| 12      | 65        | 1.32%   |
| 11      | 49        | 0.99%   |
| 10      | 49        | 0.99%   |
| 84      | 42        | 0.85%   |
| 16      | 36        | 0.73%   |
| 26      | 24        | 0.49%   |
| 25      | 24        | 0.49%   |
| 72      | 23        | 0.47%   |
| 54      | 23        | 0.47%   |
| 32      | 20        | 0.4%    |
| 40      | 17        | 0.34%   |
| 52      | 7         | 0.14%   |
| 46      | 7         | 0.14%   |
| 28      | 7         | 0.14%   |
| 65      | 6         | 0.12%   |
| 142     | 5         | 0.1%    |
| 48      | 5         | 0.1%    |
| 7       | 5         | 0.1%    |
| 60      | 4         | 0.08%   |
| 33      | 4         | 0.08%   |
| 8       | 4         | 0.08%   |
| 47      | 3         | 0.06%   |
| 43      | 3         | 0.06%   |
| 42      | 3         | 0.06%   |
| 37      | 3         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1944      | 40.06%  |
| 501-600        | 895       | 18.44%  |
| 401-500        | 695       | 14.32%  |
| 201-300        | 384       | 7.91%   |
| Unknown        | 285       | 5.87%   |
| 351-400        | 266       | 5.48%   |
| 601-700        | 115       | 2.37%   |
| 701-800        | 95        | 1.96%   |
| 1501-2000      | 67        | 1.38%   |
| 1001-1500      | 59        | 1.22%   |
| 801-900        | 26        | 0.54%   |
| 1-100          | 7         | 0.14%   |
| 901-1000       | 6         | 0.12%   |
| More than 2000 | 5         | 0.1%    |
| 101-200        | 4         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3286      | 73.41%  |
| 16/10   | 561       | 12.53%  |
| Unknown | 234       | 5.23%   |
| 5/4     | 185       | 4.13%   |
| 21/9    | 77        | 1.72%   |
| 4/3     | 52        | 1.16%   |
| 3/2     | 49        | 1.09%   |
| 0.62    | 12        | 0.27%   |
| 1.00    | 5         | 0.11%   |
| 0.67    | 5         | 0.11%   |
| 32/9    | 4         | 0.09%   |
| 6/5     | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |
| 1.03    | 1         | 0.02%   |
| 0.58    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |
| 0.45    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1442      | 29.39%  |
| 201-250        | 873       | 17.79%  |
| 81-90          | 440       | 8.97%   |
| 301-350        | 326       | 6.64%   |
| 151-200        | 321       | 6.54%   |
| Unknown        | 285       | 5.81%   |
| 141-150        | 209       | 4.26%   |
| 71-80          | 184       | 3.75%   |
| 351-500        | 170       | 3.47%   |
| 251-300        | 130       | 2.65%   |
| More than 1000 | 120       | 2.45%   |
| 121-130        | 116       | 2.36%   |
| 61-70          | 57        | 1.16%   |
| 51-60          | 49        | 1%      |
| 41-50          | 49        | 1%      |
| 501-1000       | 45        | 0.92%   |
| 131-140        | 35        | 0.71%   |
| 111-120        | 26        | 0.53%   |
| 91-100         | 18        | 0.37%   |
| 1-40           | 11        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1665      | 34.91%  |
| 101-120       | 1325      | 27.78%  |
| 121-160       | 1103      | 23.12%  |
| Unknown       | 285       | 5.97%   |
| 161-240       | 229       | 4.8%    |
| 1-50          | 101       | 2.12%   |
| More than 240 | 62        | 1.3%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3740      | 79.61%  |
| 2     | 667       | 14.2%   |
| 0     | 209       | 4.45%   |
| 3     | 77        | 1.64%   |
| 4     | 5         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2630      | 37.91%  |
| Intel                             | 1932      | 27.85%  |
| Qualcomm Atheros                  | 890       | 12.83%  |
| Broadcom                          | 428       | 6.17%   |
| TP-Link                           | 113       | 1.63%   |
| Ralink Technology                 | 112       | 1.61%   |
| Marvell Technology Group          | 106       | 1.53%   |
| Broadcom Limited                  | 94        | 1.35%   |
| Nvidia                            | 87        | 1.25%   |
| Ralink                            | 76        | 1.1%    |
| MediaTek                          | 46        | 0.66%   |
| Qualcomm Atheros Communications   | 41        | 0.59%   |
| Samsung Electronics               | 28        | 0.4%    |
| Xiaomi                            | 26        | 0.37%   |
| D-Link                            | 23        | 0.33%   |
| ASIX Electronics                  | 22        | 0.32%   |
| Silicon Integrated Systems [SiS]  | 19        | 0.27%   |
| VIA Technologies                  | 17        | 0.25%   |
| ASUSTek Computer                  | 17        | 0.25%   |
| D-Link System                     | 16        | 0.23%   |
| Qualcomm                          | 14        | 0.2%    |
| Sierra Wireless                   | 12        | 0.17%   |
| Hewlett-Packard                   | 12        | 0.17%   |
| Ericsson Business Mobile Networks | 12        | 0.17%   |
| DisplayLink                       | 12        | 0.17%   |
| Belkin Components                 | 12        | 0.17%   |
| JMicron Technology                | 11        | 0.16%   |
| Dell                              | 11        | 0.16%   |
| Lenovo                            | 9         | 0.13%   |
| Microsoft                         | 7         | 0.1%    |
| Huawei Technologies               | 7         | 0.1%    |
| ZyDAS                             | 5         | 0.07%   |
| Microchip Technology              | 5         | 0.07%   |
| Edimax Technology                 | 5         | 0.07%   |
| NetGear                           | 4         | 0.06%   |
| LSI                               | 4         | 0.06%   |
| Gemtek                            | 4         | 0.06%   |
| Attansic Technology               | 4         | 0.06%   |
| Accton Technology                 | 4         | 0.06%   |
| Toshiba                           | 3         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1803      | 22.56%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 294       | 3.68%   |
| Intel Wi-Fi 6 AX200                                                     | 177       | 2.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 137       | 1.71%   |
| Intel Wireless 8265 / 8275                                              | 116       | 1.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 114       | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 107       | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 104       | 1.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 103       | 1.29%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 101       | 1.26%   |
| Intel Wi-Fi 6 AX201                                                     | 101       | 1.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 99        | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 99        | 1.24%   |
| Intel Wireless 7265                                                     | 95        | 1.19%   |
| Intel Wireless 3165                                                     | 86        | 1.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 84        | 1.05%   |
| Intel I211 Gigabit Network Connection                                   | 80        | 1%      |
| Intel Ethernet Connection (2) I219-V                                    | 77        | 0.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 67        | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 65        | 0.81%   |
| Intel Wireless 7260                                                     | 65        | 0.81%   |
| Realtek RTL8125 2.5GbE Controller                                       | 64        | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 47        | 0.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 46        | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 0.55%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 0.55%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 0.54%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 42        | 0.53%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 42        | 0.53%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 42        | 0.53%   |
| Intel WiFi Link 5100                                                    | 41        | 0.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 41        | 0.51%   |
| Intel Wireless 8260                                                     | 40        | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 39        | 0.49%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 0.49%   |
| Intel 82579V Gigabit Network Connection                                 | 38        | 0.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 37        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1453      | 39.6%   |
| Realtek Semiconductor             | 691       | 18.83%  |
| Qualcomm Atheros                  | 686       | 18.7%   |
| Broadcom                          | 263       | 7.17%   |
| Ralink Technology                 | 112       | 3.05%   |
| TP-Link                           | 94        | 2.56%   |
| Ralink                            | 76        | 2.07%   |
| Broadcom Limited                  | 64        | 1.74%   |
| MediaTek                          | 45        | 1.23%   |
| Qualcomm Atheros Communications   | 41        | 1.12%   |
| D-Link                            | 23        | 0.63%   |
| ASUSTek Computer                  | 17        | 0.46%   |
| Sierra Wireless                   | 12        | 0.33%   |
| Belkin Components                 | 12        | 0.33%   |
| D-Link System                     | 10        | 0.27%   |
| Microsoft                         | 7         | 0.19%   |
| Dell                              | 6         | 0.16%   |
| ZyDAS                             | 5         | 0.14%   |
| Marvell Technology Group          | 5         | 0.14%   |
| Edimax Technology                 | 5         | 0.14%   |
| Qualcomm                          | 4         | 0.11%   |
| NetGear                           | 4         | 0.11%   |
| Hewlett-Packard                   | 4         | 0.11%   |
| Gemtek                            | 4         | 0.11%   |
| Ericsson Business Mobile Networks | 4         | 0.11%   |
| Texas Instruments                 | 3         | 0.08%   |
| Linksys                           | 3         | 0.08%   |
| Sitecom Europe                    | 2         | 0.05%   |
| Fibocom                           | 2         | 0.05%   |
| Accton Technology                 | 2         | 0.05%   |
| ZyXEL Communications              | 1         | 0.03%   |
| Xiaomi                            | 1         | 0.03%   |
| Wilocity                          | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| TRENDnet                          | 1         | 0.03%   |
| Tenda                             | 1         | 0.03%   |
| Standard Microsystems             | 1         | 0.03%   |
| Samsung Electronics               | 1         | 0.03%   |
| AirTies Wireless Networks         | 1         | 0.03%   |
| 3Com                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 177       | 4.79%   |
| Intel Wireless 8265 / 8275                                              | 116       | 3.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 114       | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 107       | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 103       | 2.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 101       | 2.73%   |
| Intel Wi-Fi 6 AX201                                                     | 101       | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 99        | 2.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 99        | 2.68%   |
| Intel Wireless 7265                                                     | 95        | 2.57%   |
| Intel Wireless 3165                                                     | 86        | 2.33%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 84        | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 1.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 67        | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 65        | 1.76%   |
| Intel Wireless 7260                                                     | 65        | 1.76%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 55        | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                           | 47        | 1.27%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 46        | 1.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 45        | 1.22%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 44        | 1.19%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 44        | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 43        | 1.16%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 42        | 1.14%   |
| Intel WiFi Link 5100                                                    | 41        | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 41        | 1.11%   |
| Intel Wireless 8260                                                     | 40        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 39        | 1.06%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 1.06%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 37        | 1%      |
| Qualcomm Atheros AR9271 802.11n                                         | 37        | 1%      |
| Intel Wireless 3160                                                     | 36        | 0.97%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 35        | 0.95%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 33        | 0.89%   |
| Realtek 802.11ac NIC                                                    | 33        | 0.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 33        | 0.89%   |
| Intel Wireless-AC 9260                                                  | 30        | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 29        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 29        | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 29        | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2346      | 56.38%  |
| Intel                                  | 871       | 20.93%  |
| Qualcomm Atheros                       | 285       | 6.85%   |
| Broadcom                               | 211       | 5.07%   |
| Marvell Technology Group               | 102       | 2.45%   |
| Nvidia                                 | 87        | 2.09%   |
| Broadcom Limited                       | 32        | 0.77%   |
| Samsung Electronics                    | 27        | 0.65%   |
| Xiaomi                                 | 25        | 0.6%    |
| ASIX Electronics                       | 22        | 0.53%   |
| TP-Link                                | 19        | 0.46%   |
| Silicon Integrated Systems [SiS]       | 19        | 0.46%   |
| VIA Technologies                       | 17        | 0.41%   |
| DisplayLink                            | 12        | 0.29%   |
| JMicron Technology                     | 11        | 0.26%   |
| Qualcomm                               | 10        | 0.24%   |
| Lenovo                                 | 9         | 0.22%   |
| D-Link System                          | 6         | 0.14%   |
| LSI                                    | 4         | 0.1%    |
| Hewlett-Packard                        | 4         | 0.1%    |
| Attansic Technology                    | 4         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 3         | 0.07%   |
| Microchip Technology                   | 3         | 0.07%   |
| IBM                                    | 3         | 0.07%   |
| Aquantia                               | 3         | 0.07%   |
| Apple                                  | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.05%   |
| Huawei Technologies                    | 2         | 0.05%   |
| Google                                 | 2         | 0.05%   |
| Davicom Semiconductor                  | 2         | 0.05%   |
| ADMtek                                 | 2         | 0.05%   |
| Accton Technology                      | 2         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| OPPO Electronics                       | 1         | 0.02%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.02%   |
| National Semiconductor                 | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
| Meizu                                  | 1         | 0.02%   |
| MediaTek                               | 1         | 0.02%   |
| ICS Advent                             | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1803      | 42.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 294       | 6.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 137       | 3.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 104       | 2.45%   |
| Intel I211 Gigabit Network Connection                             | 80        | 1.89%   |
| Intel Ethernet Connection (2) I219-V                              | 77        | 1.81%   |
| Realtek RTL8125 2.5GbE Controller                                 | 64        | 1.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 42        | 0.99%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 42        | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 38        | 0.9%    |
| Intel Ethernet Connection (7) I219-V                              | 37        | 0.87%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 36        | 0.85%   |
| Intel Ethernet Connection I217-LM                                 | 35        | 0.82%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 32        | 0.75%   |
| Intel Ethernet Controller I225-V                                  | 31        | 0.73%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 28        | 0.66%   |
| Nvidia MCP79 Ethernet                                             | 27        | 0.64%   |
| Nvidia MCP61 Ethernet                                             | 27        | 0.64%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 25        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 25        | 0.59%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 24        | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 23        | 0.54%   |
| Intel Ethernet Connection (2) I218-V                              | 23        | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 23        | 0.54%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 21        | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 21        | 0.49%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 20        | 0.47%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 19        | 0.45%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 19        | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 19        | 0.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 18        | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.42%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 0.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 18        | 0.42%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 16        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3984      | 53.25%  |
| WiFi     | 3446      | 46.06%  |
| Modem    | 48        | 0.64%   |
| Unknown  | 4         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2617      | 54.66%  |
| Ethernet | 2171      | 45.34%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2474      | 53.63%  |
| 1     | 1944      | 42.14%  |
| 0     | 107       | 2.32%   |
| 3     | 65        | 1.41%   |
| 4     | 15        | 0.33%   |
| 6     | 4         | 0.09%   |
| 5     | 4         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4454      | 96.64%  |
| Yes  | 155       | 3.36%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1148      | 43.4%   |
| Realtek Semiconductor           | 317       | 11.98%  |
| Cambridge Silicon Radio         | 232       | 8.77%   |
| IMC Networks                    | 162       | 6.12%   |
| Qualcomm Atheros Communications | 152       | 5.75%   |
| Broadcom                        | 115       | 4.35%   |
| Apple                           | 105       | 3.97%   |
| Lite-On Technology              | 88        | 3.33%   |
| Foxconn / Hon Hai               | 79        | 2.99%   |
| ASUSTek Computer                | 47        | 1.78%   |
| Toshiba                         | 35        | 1.32%   |
| Realtek                         | 33        | 1.25%   |
| Dell                            | 27        | 1.02%   |
| Hewlett-Packard                 | 22        | 0.83%   |
| Ralink                          | 17        | 0.64%   |
| Alps Electric                   | 13        | 0.49%   |
| Belkin Components               | 9         | 0.34%   |
| Foxconn International           | 8         | 0.3%    |
| Integrated System Solution      | 7         | 0.26%   |
| TP-Link                         | 6         | 0.23%   |
| Ralink Technology               | 4         | 0.15%   |
| MediaTek                        | 4         | 0.15%   |
| Marvell Semiconductor           | 3         | 0.11%   |
| Edimax Technology               | 3         | 0.11%   |
| Roper                           | 2         | 0.08%   |
| Askey Computer                  | 2         | 0.08%   |
| Taiyo Yuden                     | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Logitech                        | 1         | 0.04%   |
| Corsair                         | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 439       | 16.6%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 232       | 8.77%   |
| Realtek Bluetooth Radio                             | 225       | 8.51%   |
| Intel Bluetooth Device                              | 216       | 8.17%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 189       | 7.15%   |
| Intel AX200 Bluetooth                               | 172       | 6.5%    |
| IMC Networks Bluetooth Radio                        | 77        | 2.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 63        | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 59        | 2.23%   |
| Lite-On Bluetooth Device                            | 47        | 1.78%   |
| IMC Networks Bluetooth Device                       | 47        | 1.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 43        | 1.63%   |
| Apple Bluetooth Host Controller                     | 41        | 1.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 36        | 1.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 35        | 1.32%   |
| Realtek Bluetooth Radio                             | 33        | 1.25%   |
| Apple Bluetooth USB Host Controller                 | 31        | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 30        | 1.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 28        | 1.06%   |
| Intel AX210 Bluetooth                               | 28        | 1.06%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 0.87%   |
| Lite-On Atheros AR3012 Bluetooth                    | 22        | 0.83%   |
| IMC Networks Wireless_Device                        | 22        | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 19        | 0.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 18        | 0.68%   |
| Ralink RT3290 Bluetooth                             | 17        | 0.64%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 15        | 0.57%   |
| Foxconn / Hon Hai Wireless_Device                   | 14        | 0.53%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.53%   |
| Apple Bluetooth HCI                                 | 13        | 0.49%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 0.45%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.45%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.42%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 11        | 0.42%   |
| Toshiba Integrated Bluetooth HCI                    | 10        | 0.38%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.38%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.3%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3358      | 54.21%  |
| AMD                                  | 1212      | 19.56%  |
| Nvidia                               | 1084      | 17.5%   |
| C-Media Electronics                  | 98        | 1.58%   |
| Creative Labs                        | 37        | 0.6%    |
| Logitech                             | 34        | 0.55%   |
| Texas Instruments                    | 23        | 0.37%   |
| JMTek                                | 22        | 0.36%   |
| Silicon Integrated Systems [SiS]     | 21        | 0.34%   |
| GN Netcom                            | 19        | 0.31%   |
| VIA Technologies                     | 18        | 0.29%   |
| Kingston Technology                  | 17        | 0.27%   |
| Plantronics                          | 16        | 0.26%   |
| Corsair                              | 14        | 0.23%   |
| Focusrite-Novation                   | 12        | 0.19%   |
| ASUSTek Computer                     | 12        | 0.19%   |
| Realtek Semiconductor                | 11        | 0.18%   |
| Creative Technology                  | 11        | 0.18%   |
| Generalplus Technology               | 10        | 0.16%   |
| Lenovo                               | 9         | 0.15%   |
| SteelSeries ApS                      | 8         | 0.13%   |
| Sennheiser Communications            | 7         | 0.11%   |
| Ensoniq                              | 6         | 0.1%    |
| BEHRINGER International              | 6         | 0.1%    |
| Thesycon Systemsoftware & Consulting | 5         | 0.08%   |
| M-Audio                              | 5         | 0.08%   |
| Hewlett-Packard                      | 5         | 0.08%   |
| Yamaha                               | 4         | 0.06%   |
| Tenx Technology                      | 4         | 0.06%   |
| Razer USA                            | 4         | 0.06%   |
| Dell                                 | 4         | 0.06%   |
| Blue Microphones                     | 4         | 0.06%   |
| Apple                                | 4         | 0.06%   |
| Sony                                 | 3         | 0.05%   |
| SAVITECH                             | 3         | 0.05%   |
| QinHeng Electronics                  | 3         | 0.05%   |
| PreSonus Audio Electronics           | 3         | 0.05%   |
| Micro Star International             | 3         | 0.05%   |
| Guillemot                            | 3         | 0.05%   |
| Evolution Electronics                | 3         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 337       | 4.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 319       | 4.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 261       | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 258       | 3.53%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 244       | 3.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 215       | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 198       | 2.71%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 184       | 2.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 183       | 2.5%    |
| Intel Cannon Lake PCH cAVS                                                 | 178       | 2.43%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 149       | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 146       | 2%      |
| AMD Renoir Radeon High Definition Audio Controller                         | 137       | 1.87%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 136       | 1.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 135       | 1.84%   |
| AMD FCH Azalia Controller                                                  | 132       | 1.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 127       | 1.74%   |
| Intel 8 Series HD Audio Controller                                         | 127       | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                      | 126       | 1.72%   |
| AMD Starship/Matisse HD Audio Controller                                   | 121       | 1.65%   |
| Nvidia GP107GL High Definition Audio Controller                            | 110       | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 104       | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 101       | 1.38%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 99        | 1.35%   |
| Intel 200 Series PCH HD Audio                                              | 97        | 1.33%   |
| Intel Comet Lake PCH-LP cAVS                                               | 96        | 1.31%   |
| Intel Broadwell-U Audio Controller                                         | 95        | 1.3%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 92        | 1.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 87        | 1.19%   |
| Nvidia High Definition Audio Controller                                    | 83        | 1.13%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 78        | 1.07%   |
| AMD Kabini HDMI/DP Audio                                                   | 66        | 0.9%    |
| Intel Comet Lake PCH cAVS                                                  | 65        | 0.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 64        | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 61        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 60        | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 57        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 55        | 0.75%   |
| Nvidia GP106 High Definition Audio Controller                              | 51        | 0.7%    |
| AMD High Definition Audio Controller                                       | 50        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 587       | 22.75%  |
| SK hynix            | 411       | 15.93%  |
| Kingston            | 403       | 15.62%  |
| Unknown             | 283       | 10.97%  |
| Micron Technology   | 234       | 9.07%   |
| Crucial             | 178       | 6.9%    |
| Corsair             | 112       | 4.34%   |
| G.Skill             | 81        | 3.14%   |
| Ramaxel Technology  | 64        | 2.48%   |
| Elpida              | 35        | 1.36%   |
| Unknown (ABCD)      | 33        | 1.28%   |
| A-DATA Technology   | 22        | 0.85%   |
| Nanya Technology    | 21        | 0.81%   |
| Silicon Power       | 13        | 0.5%    |
| GOODRAM             | 10        | 0.39%   |
| Unknown             | 10        | 0.39%   |
| Transcend           | 8         | 0.31%   |
| Team                | 7         | 0.27%   |
| Apacer              | 7         | 0.27%   |
| Unifosa             | 6         | 0.23%   |
| Wilk                | 4         | 0.16%   |
| Patriot             | 4         | 0.16%   |
| ASint Technology    | 4         | 0.16%   |
| Kllisre             | 3         | 0.12%   |
| Atermiter           | 3         | 0.12%   |
| Timetec             | 2         | 0.08%   |
| SHARETRONIC         | 2         | 0.08%   |
| Qimonda             | 2         | 0.08%   |
| PNY                 | 2         | 0.08%   |
| Micron/Elpida       | 2         | 0.08%   |
| KomputerBay         | 2         | 0.08%   |
| Innodisk            | 2         | 0.08%   |
| Exceleram           | 2         | 0.08%   |
| Avant               | 2         | 0.08%   |
| Unknown (AB)        | 1         | 0.04%   |
| Unknown (0x5846)    | 1         | 0.04%   |
| Unknown (07FB)      | 1         | 0.04%   |
| Toshiba             | 1         | 0.04%   |
| Thermaltake         | 1         | 0.04%   |
| Pioneer             | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 29        | 1.05%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 22        | 0.79%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 21        | 0.76%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.76%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 18        | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 18        | 0.65%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 18        | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 17        | 0.61%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 16        | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 16        | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 15        | 0.54%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3                       | 15        | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 12        | 0.43%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 12        | 0.43%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.43%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 12        | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.43%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.4%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 11        | 0.4%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.4%    |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s            | 11        | 0.4%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 0.4%    |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.36%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.36%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.36%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 10        | 0.36%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.36%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 10        | 0.36%   |
| Unknown                                                          | 10        | 0.36%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 9         | 0.32%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 9         | 0.32%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 9         | 0.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1065      | 47.31%  |
| DDR3    | 732       | 32.52%  |
| DDR2    | 131       | 5.82%   |
| LPDDR4  | 79        | 3.51%   |
| Unknown | 76        | 3.38%   |
| SDRAM   | 68        | 3.02%   |
| LPDDR3  | 56        | 2.49%   |
| DDR5    | 16        | 0.71%   |
| DDR     | 16        | 0.71%   |
| LPDDR5  | 6         | 0.27%   |
| DRAM    | 6         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1327      | 58.93%  |
| DIMM         | 764       | 33.93%  |
| Row Of Chips | 147       | 6.53%   |
| Chip         | 9         | 0.4%    |
| FB-DIMM      | 3         | 0.13%   |
| RIMM         | 2         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 932       | 38.17%  |
| 4096  | 673       | 27.56%  |
| 2048  | 337       | 13.8%   |
| 16384 | 335       | 13.72%  |
| 1024  | 106       | 4.34%   |
| 32768 | 46        | 1.88%   |
| 512   | 8         | 0.33%   |
| 65536 | 2         | 0.08%   |
| 256   | 2         | 0.08%   |
| 3072  | 1         | 0.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 460       | 18.86%  |
| 2667    | 362       | 14.84%  |
| 3200    | 349       | 14.31%  |
| 2400    | 193       | 7.91%   |
| 1333    | 164       | 6.72%   |
| 2133    | 125       | 5.13%   |
| 667     | 87        | 3.57%   |
| 1334    | 78        | 3.2%    |
| 800     | 69        | 2.83%   |
| 3600    | 64        | 2.62%   |
| Unknown | 56        | 2.3%    |
| 1867    | 54        | 2.21%   |
| 8400    | 30        | 1.23%   |
| 4267    | 28        | 1.15%   |
| 1067    | 25        | 1.03%   |
| 3466    | 24        | 0.98%   |
| 3266    | 19        | 0.78%   |
| 2933    | 19        | 0.78%   |
| 1866    | 18        | 0.74%   |
| 1066    | 17        | 0.7%    |
| 533     | 16        | 0.66%   |
| 4800    | 15        | 0.62%   |
| 3400    | 15        | 0.62%   |
| 2733    | 13        | 0.53%   |
| 2048    | 13        | 0.53%   |
| 4199    | 12        | 0.49%   |
| 3733    | 12        | 0.49%   |
| 3000    | 12        | 0.49%   |
| 2666    | 8         | 0.33%   |
| 6400    | 7         | 0.29%   |
| 2800    | 7         | 0.29%   |
| 4266    | 5         | 0.21%   |
| 3800    | 5         | 0.21%   |
| 1639    | 5         | 0.21%   |
| 975     | 5         | 0.21%   |
| 400     | 5         | 0.21%   |
| 3500    | 4         | 0.16%   |
| 1800    | 4         | 0.16%   |
| 333     | 3         | 0.12%   |
| 5200    | 2         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 62        | 49.6%   |
| Brother Industries       | 23        | 18.4%   |
| Canon                    | 13        | 10.4%   |
| Samsung Electronics      | 9         | 7.2%    |
| Seiko Epson              | 8         | 6.4%    |
| Oki Data                 | 3         | 2.4%    |
| Dymo-CoStar              | 2         | 1.6%    |
| Ricoh                    | 1         | 0.8%    |
| Magic Control Technology | 1         | 0.8%    |
| Lexmark International    | 1         | 0.8%    |
| Kyocera                  | 1         | 0.8%    |
| Apple                    | 1         | 0.8%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| HP LaserJet 1018                                | 5         | 3.97%   |
| Brother HL-2030 Laser Printer                   | 5         | 3.97%   |
| Canon PIXMA MG2500 Series                       | 4         | 3.17%   |
| Oki Data USB Device                             | 3         | 2.38%   |
| HP LaserJet 1020                                | 3         | 2.38%   |
| HP DeskJet F2492 All-in-One                     | 3         | 2.38%   |
| HP DeskJet 2700 series                          | 3         | 2.38%   |
| HP DeskJet 2600 series                          | 3         | 2.38%   |
| HP Deskjet 1050 J410                            | 3         | 2.38%   |
| Canon LiDE 400                                  | 3         | 2.38%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 1.59%   |
| Samsung M2070 Series                            | 2         | 1.59%   |
| HP LaserJet 1010                                | 2         | 1.59%   |
| HP ENVY 5540 series                             | 2         | 1.59%   |
| HP ENVY 5000 series                             | 2         | 1.59%   |
| HP ENVY 4520 series                             | 2         | 1.59%   |
| HP DeskJet 5550                                 | 2         | 1.59%   |
| HP DeskJet 3630 series                          | 2         | 1.59%   |
| Dymo-CoStar LabelWriter 450                     | 2         | 1.59%   |
| Brother Printer                                 | 2         | 1.59%   |
| Brother MFC-J5330DW                             | 2         | 1.59%   |
| Brother DCP-1510                                | 2         | 1.59%   |
| Seiko Epson XP-255 257 Series                   | 1         | 0.79%   |
| Seiko Epson XP-230 Series                       | 1         | 0.79%   |
| Seiko Epson XP-225 Series                       | 1         | 0.79%   |
| Seiko Epson WF-2830 Series                      | 1         | 0.79%   |
| Seiko Epson Printer                             | 1         | 0.79%   |
| Seiko Epson L555 Series                         | 1         | 0.79%   |
| Seiko Epson L1300 Series                        | 1         | 0.79%   |
| Seiko Epson ET-2700 Series                      | 1         | 0.79%   |
| Samsung SCX-4300 Series                         | 1         | 0.79%   |
| Samsung SCX-3400 Series                         | 1         | 0.79%   |
| Samsung SCX-3200 Series                         | 1         | 0.79%   |
| Samsung ML-1640 Series Laser Printer            | 1         | 0.79%   |
| Samsung M267x 287x Series                       | 1         | 0.79%   |
| Ricoh SP 112                                    | 1         | 0.79%   |
| Magic Control BAY-3U1S1P Parallel Port          | 1         | 0.79%   |
| Lexmark International B2236dw                   | 1         | 0.79%   |
| Kyocera ECOSYS M5521cdn                         | 1         | 0.79%   |
| HP PSC-1315/PSC-1317                            | 1         | 0.79%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 14        | 43.75%  |
| Hewlett-Packard             | 8         | 25%     |
| Seiko Epson                 | 6         | 18.75%  |
| Acer Peripherals (now BenQ) | 2         | 6.25%   |
| Mustek Systems              | 1         | 3.13%   |
| KYE Systems (Mouse Systems) | 1         | 3.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 4         | 12.5%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]       | 2         | 6.25%   |
| HP Scanjet 300                                           | 2         | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.25%   |
| Canon CanoScan N650U/N656U                               | 2         | 6.25%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.25%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 2         | 6.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 1         | 3.13%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 3.13%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]        | 1         | 3.13%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.13%   |
| Mustek Systems ScanExpress 1200 CU                       | 1         | 3.13%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4             | 1         | 3.13%   |
| HP Scanjet N6010                                         | 1         | 3.13%   |
| HP ScanJet 5200c                                         | 1         | 3.13%   |
| HP ScanJet 4570c                                         | 1         | 3.13%   |
| HP ScanJet 4300c                                         | 1         | 3.13%   |
| HP ScanJet 3570c                                         | 1         | 3.13%   |
| HP ScanJet 3300c                                         | 1         | 3.13%   |
| Canon CanoScan LiDE 700F                                 | 1         | 3.13%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 1         | 3.13%   |
| Canon CanoScan LIDE 25                                   | 1         | 3.13%   |
| Canon CanoScan LiDE 220                                  | 1         | 3.13%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 608       | 22.92%  |
| IMC Networks                           | 289       | 10.89%  |
| Acer                                   | 250       | 9.42%   |
| Realtek Semiconductor                  | 170       | 6.41%   |
| Microdia                               | 166       | 6.26%   |
| Logitech                               | 125       | 4.71%   |
| Suyin                                  | 117       | 4.41%   |
| Sunplus Innovation Technology          | 116       | 4.37%   |
| Quanta                                 | 115       | 4.33%   |
| Cheng Uei Precision Industry (Foxlink) | 95        | 3.58%   |
| Syntek                                 | 75        | 2.83%   |
| Apple                                  | 72        | 2.71%   |
| Alcor Micro                            | 47        | 1.77%   |
| Lite-On Technology                     | 42        | 1.58%   |
| Luxvisions Innotech Limited            | 35        | 1.32%   |
| Ricoh                                  | 30        | 1.13%   |
| Silicon Motion                         | 20        | 0.75%   |
| Samsung Electronics                    | 20        | 0.75%   |
| Creative Technology                    | 18        | 0.68%   |
| Z-Star Microelectronics                | 16        | 0.6%    |
| Microsoft                              | 16        | 0.6%    |
| GEMBIRD                                | 13        | 0.49%   |
| Generalplus Technology                 | 11        | 0.41%   |
| Sonix Technology                       | 10        | 0.38%   |
| Lenovo                                 | 9         | 0.34%   |
| KYE Systems (Mouse Systems)            | 9         | 0.34%   |
| Importek                               | 9         | 0.34%   |
| SunplusIT                              | 8         | 0.3%    |
| Sunplus Technology                     | 8         | 0.3%    |
| ARC International                      | 8         | 0.3%    |
| ALi                                    | 8         | 0.3%    |
| Jieli Technology                       | 7         | 0.26%   |
| icSpring                               | 7         | 0.26%   |
| Primax Electronics                     | 6         | 0.23%   |
| Intel                                  | 6         | 0.23%   |
| Genesys Logic                          | 6         | 0.23%   |
| Cubeternet                             | 6         | 0.23%   |
| 2M UVC CAMERA                          | 6         | 0.23%   |
| Trust                                  | 4         | 0.15%   |
| OmniVision Technologies                | 4         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 77        | 2.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 67        | 2.51%   |
| Chicony HD Webcam                                       | 65        | 2.43%   |
| Chicony integrated camera                               | 62        | 2.32%   |
| Acer Integrated Camera                                  | 60        | 2.25%   |
| Microdia Integrated_Webcam_HD                           | 56        | 2.1%    |
| Acer HD Webcam                                          | 52        | 1.95%   |
| IMC Networks Integrated Camera                          | 44        | 1.65%   |
| Chicony USB2.0 VGA UVC WebCam                           | 41        | 1.54%   |
| Realtek Integrated_Webcam_HD                            | 34        | 1.27%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 31        | 1.16%   |
| Logitech Webcam C270                                    | 31        | 1.16%   |
| Apple Built-in iSight                                   | 31        | 1.16%   |
| Realtek USB Camera                                      | 29        | 1.09%   |
| Quanta HP TrueVision HD Camera                          | 29        | 1.09%   |
| Syntek Integrated Camera                                | 28        | 1.05%   |
| Chicony EasyCamera                                      | 27        | 1.01%   |
| Sunplus HD WebCam                                       | 26        | 0.97%   |
| Microdia Webcam Vitade AF                               | 24        | 0.9%    |
| Chicony USB 2.0 Camera                                  | 24        | 0.9%    |
| Acer EasyCamera                                         | 21        | 0.79%   |
| Samsung Galaxy A5 (MTP)                                 | 20        | 0.75%   |
| Acer Lenovo EasyCamera                                  | 20        | 0.75%   |
| Chicony USB2.0 HD UVC WebCam                            | 19        | 0.71%   |
| Chicony HP Truevision HD                                | 19        | 0.71%   |
| Acer HD Camera                                          | 19        | 0.71%   |
| Syntek EasyCamera                                       | 18        | 0.67%   |
| Lite-On Integrated Camera                               | 18        | 0.67%   |
| Apple FaceTime HD Camera (Built-in)                     | 18        | 0.67%   |
| Syntek Lenovo EasyCamera                                | 17        | 0.64%   |
| Chicony VGA WebCam                                      | 17        | 0.64%   |
| Chicony HP TrueVision HD Camera                         | 17        | 0.64%   |
| Chicony HP HD Camera                                    | 17        | 0.64%   |
| Realtek Lenovo EasyCamera                               | 16        | 0.6%    |
| Quanta HP HD Camera                                     | 16        | 0.6%    |
| Microdia USB 2.0 Camera                                 | 16        | 0.6%    |
| Logitech HD Pro Webcam C920                             | 16        | 0.6%    |
| Chicony TOSHIBA Web Camera - HD                         | 16        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 16        | 0.6%    |
| Acer BisonCam, NB Pro                                   | 16        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 112       | 29.87%  |
| Validity Sensors           | 89        | 23.73%  |
| Shenzhen Goodix Technology | 61        | 16.27%  |
| Elan Microelectronics      | 37        | 9.87%   |
| AuthenTec                  | 35        | 9.33%   |
| Upek                       | 23        | 6.13%   |
| LighTuning Technology      | 12        | 3.2%    |
| STMicroelectronics         | 6         | 1.6%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 48        | 12.8%   |
| Shenzhen Goodix  Fingerprint Device                                        | 42        | 11.2%   |
| Elan ELAN:Fingerprint                                                      | 34        | 9.07%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 26        | 6.93%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 5.07%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 5.07%   |
| Shenzhen Goodix Fingerprint Reader                                         | 16        | 4.27%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 3.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3.2%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.93%   |
| Synaptics  WBDI                                                            | 10        | 2.67%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.13%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 2.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.13%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 1.87%   |
| Validity Sensors Synaptics WBDI                                            | 6         | 1.6%    |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.6%    |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.6%    |
| AuthenTec AES1600                                                          | 6         | 1.6%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.33%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.33%   |
| AuthenTec AES2810                                                          | 5         | 1.33%   |
| Validity Sensors VFS491                                                    | 4         | 1.07%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.07%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.07%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.07%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 1.07%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.8%    |
| LighTuning Fingerprint Sensor                                              | 3         | 0.8%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.8%    |
| Elan ELAN:ARM-M4                                                           | 3         | 0.8%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.8%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.53%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.53%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.53%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.53%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.27%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 67        | 34.72%  |
| Broadcom                  | 50        | 25.91%  |
| O2 Micro                  | 23        | 11.92%  |
| Lenovo                    | 8         | 4.15%   |
| Advanced Card Systems     | 8         | 4.15%   |
| Chicony Electronics       | 6         | 3.11%   |
| Realtek Semiconductor     | 5         | 2.59%   |
| Cherry                    | 5         | 2.59%   |
| C3PO                      | 5         | 2.59%   |
| Upek                      | 4         | 2.07%   |
| SCM Microsystems          | 3         | 1.55%   |
| Gemalto (was Gemplus)     | 3         | 1.55%   |
| OmniKey                   | 2         | 1.04%   |
| Hewlett-Packard           | 2         | 1.04%   |
| In Focus Systems          | 1         | 0.52%   |
| Fujitsu Siemens Computers | 1         | 0.52%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 63        | 32.64%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 11.4%   |
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 9.33%   |
| Broadcom 5880                                                                | 14        | 7.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 4.66%   |
| Broadcom 58200                                                               | 9         | 4.66%   |
| Lenovo Integrated Smart Card Reader                                          | 8         | 4.15%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 6         | 3.11%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 6         | 3.11%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 2.59%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.07%   |
| Cherry SmartTerminal XX1X                                                    | 4         | 2.07%   |
| C3PO LTC31v2                                                                 | 4         | 2.07%   |
| Alcor Micro Watchdata W 1981                                                 | 4         | 2.07%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 1.04%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 1.04%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 2         | 1.04%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.04%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.52%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.52%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.52%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.52%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.52%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.52%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.52%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.52%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.52%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3442      | 73.17%  |
| 1     | 1000      | 21.26%  |
| 2     | 218       | 4.63%   |
| 3     | 29        | 0.62%   |
| 4     | 7         | 0.15%   |
| 5     | 5         | 0.11%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 400       | 26.25%  |
| Fingerprint reader       | 367       | 24.08%  |
| Net/wireless             | 223       | 14.63%  |
| Chipcard                 | 157       | 10.3%   |
| Multimedia controller    | 93        | 6.1%    |
| Camera                   | 50        | 3.28%   |
| Communication controller | 47        | 3.08%   |
| Bluetooth                | 38        | 2.49%   |
| Unassigned class         | 28        | 1.84%   |
| Storage                  | 23        | 1.51%   |
| Sound                    | 22        | 1.44%   |
| Card reader              | 21        | 1.38%   |
| Net/ethernet             | 14        | 0.92%   |
| Network                  | 10        | 0.66%   |
| Flash memory             | 10        | 0.66%   |
| Modem                    | 9         | 0.59%   |
| Dvb card                 | 6         | 0.39%   |
| Firewire controller      | 3         | 0.2%    |
| Tv card                  | 1         | 0.07%   |
| Storage/raid             | 1         | 0.07%   |
| Storage/ide              | 1         | 0.07%   |

