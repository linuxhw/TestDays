Linux in Brazil - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 20731

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ENVY 15                     | Notebook    | [5f301610ee](https://linux-hardware.org/?probe=5f301610ee) | Nov 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [5fafb134cf](https://linux-hardware.org/?probe=5fafb134cf) | Nov 06, 2023 |
| HP            | ENVY 15                     | Notebook    | [150ca6a1a0](https://linux-hardware.org/?probe=150ca6a1a0) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [7974075b64](https://linux-hardware.org/?probe=7974075b64) | Nov 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [bb021ca517](https://linux-hardware.org/?probe=bb021ca517) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Positivo      | C41TF                       | Notebook    | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [24a052bf0c](https://linux-hardware.org/?probe=24a052bf0c) | Nov 06, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [99a6c38b5d](https://linux-hardware.org/?probe=99a6c38b5d) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f0b35f0acb](https://linux-hardware.org/?probe=f0b35f0acb) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7060a82ed0](https://linux-hardware.org/?probe=7060a82ed0) | Nov 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c520e5a3b2](https://linux-hardware.org/?probe=c520e5a3b2) | Nov 05, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [f45893cbf7](https://linux-hardware.org/?probe=f45893cbf7) | Nov 05, 2023 |
| Digibras      | NH4CU53                     | Notebook    | [2c274cbad8](https://linux-hardware.org/?probe=2c274cbad8) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [459eb3cd2a](https://linux-hardware.org/?probe=459eb3cd2a) | Nov 04, 2023 |
| Toshiba       | STI 001359                  | Desktop     | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| Dell          | Latitude E6430              | Notebook    | [6a724d5aa8](https://linux-hardware.org/?probe=6a724d5aa8) | Nov 04, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [013a7815c3](https://linux-hardware.org/?probe=013a7815c3) | Nov 04, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c1523fb6a1](https://linux-hardware.org/?probe=c1523fb6a1) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [80d949b057](https://linux-hardware.org/?probe=80d949b057) | Nov 04, 2023 |
| Google        | Bluebird                    | Notebook    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| MSI           | MS-1759                     | Notebook    | [2dd46c2a71](https://linux-hardware.org/?probe=2dd46c2a71) | Nov 04, 2023 |
| Google        | Bluebird                    | Notebook    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | 246 G6 Notebook PC          | Notebook    | [cd997e5a97](https://linux-hardware.org/?probe=cd997e5a97) | Nov 03, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [f8aed4abab](https://linux-hardware.org/?probe=f8aed4abab) | Nov 03, 2023 |
| Dell          | Latitude 3420               | Notebook    | [9211e0f588](https://linux-hardware.org/?probe=9211e0f588) | Nov 03, 2023 |
| Multilaser    | PC13X                       | Notebook    | [1c6a314055](https://linux-hardware.org/?probe=1c6a314055) | Nov 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [baf30122ca](https://linux-hardware.org/?probe=baf30122ca) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2aa4f1a7f7](https://linux-hardware.org/?probe=2aa4f1a7f7) | Nov 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [429b14ee32](https://linux-hardware.org/?probe=429b14ee32) | Nov 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a08b1cfa29](https://linux-hardware.org/?probe=a08b1cfa29) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [6987861086](https://linux-hardware.org/?probe=6987861086) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [5d06dbbe5f](https://linux-hardware.org/?probe=5d06dbbe5f) | Nov 03, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [e14eb66450](https://linux-hardware.org/?probe=e14eb66450) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [9552d5f729](https://linux-hardware.org/?probe=9552d5f729) | Nov 02, 2023 |
| Acer          | AO722                       | Notebook    | [3464dc7b3c](https://linux-hardware.org/?probe=3464dc7b3c) | Nov 02, 2023 |
| HP            | 0B54h D                     | Desktop     | [4ec7776a76](https://linux-hardware.org/?probe=4ec7776a76) | Nov 02, 2023 |
| Dell          | Latitude 3440               | Notebook    | [b50ed47992](https://linux-hardware.org/?probe=b50ed47992) | Nov 02, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [0f5f162498](https://linux-hardware.org/?probe=0f5f162498) | Nov 02, 2023 |
| Dell          | Latitude 3440               | Notebook    | [9426910684](https://linux-hardware.org/?probe=9426910684) | Nov 02, 2023 |
| HP            | ZBook 17 G5                 | Notebook    | [4377844e75](https://linux-hardware.org/?probe=4377844e75) | Nov 02, 2023 |
| Samsung       | 960XFH                      | Notebook    | [6076e144ac](https://linux-hardware.org/?probe=6076e144ac) | Nov 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b03928bc33](https://linux-hardware.org/?probe=b03928bc33) | Nov 01, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [a1d2f7988e](https://linux-hardware.org/?probe=a1d2f7988e) | Nov 01, 2023 |
| ASUSTek       | PRIME H510M-D               | Desktop     | [d6749e3f8b](https://linux-hardware.org/?probe=d6749e3f8b) | Nov 01, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | Notebook    | [643c7ccd9b](https://linux-hardware.org/?probe=643c7ccd9b) | Nov 01, 2023 |
| Gigabyte      | B75M-HD3                    | Desktop     | [e27c813285](https://linux-hardware.org/?probe=e27c813285) | Oct 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [446efaf1bb](https://linux-hardware.org/?probe=446efaf1bb) | Oct 31, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [d735ec288c](https://linux-hardware.org/?probe=d735ec288c) | Oct 31, 2023 |
| AMD           | A88K                        | Desktop     | [963e38ef9a](https://linux-hardware.org/?probe=963e38ef9a) | Oct 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [27c6a9540f](https://linux-hardware.org/?probe=27c6a9540f) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [5b8af0fd77](https://linux-hardware.org/?probe=5b8af0fd77) | Oct 31, 2023 |
| Dell          | G15 5515                    | Notebook    | [c59e97ba9e](https://linux-hardware.org/?probe=c59e97ba9e) | Oct 31, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [ac709dc975](https://linux-hardware.org/?probe=ac709dc975) | Oct 31, 2023 |
| ASUSTek       | H81M-C/BR                   | Desktop     | [b92870ed6a](https://linux-hardware.org/?probe=b92870ed6a) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [40ae523147](https://linux-hardware.org/?probe=40ae523147) | Oct 31, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [b637cedab4](https://linux-hardware.org/?probe=b637cedab4) | Oct 31, 2023 |
| Dell          | Latitude 5400               | Notebook    | [e7f91d1c69](https://linux-hardware.org/?probe=e7f91d1c69) | Oct 30, 2023 |
| LG Electro... | 14Z980-G.BH51P1             | Notebook    | [879ba00b91](https://linux-hardware.org/?probe=879ba00b91) | Oct 30, 2023 |
| Intel         | H61                         | Desktop     | [0f282da58e](https://linux-hardware.org/?probe=0f282da58e) | Oct 30, 2023 |
| Acer          | Aspire 5733                 | Notebook    | [8a925b3630](https://linux-hardware.org/?probe=8a925b3630) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [931f0ed896](https://linux-hardware.org/?probe=931f0ed896) | Oct 30, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [7d5dc09b04](https://linux-hardware.org/?probe=7d5dc09b04) | Oct 30, 2023 |
| Samsung       | 730QED                      | Convertible | [c62a2f62e4](https://linux-hardware.org/?probe=c62a2f62e4) | Oct 30, 2023 |
| Intel         | B75                         | Desktop     | [a46db29108](https://linux-hardware.org/?probe=a46db29108) | Oct 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE13    | Notebook    | [28a8f59777](https://linux-hardware.org/?probe=28a8f59777) | Oct 29, 2023 |
| Sony          | VPCCW13FB                   | Notebook    | [96516448b2](https://linux-hardware.org/?probe=96516448b2) | Oct 29, 2023 |
| Sony          | VPCCW13FB                   | Notebook    | [7092dfafd9](https://linux-hardware.org/?probe=7092dfafd9) | Oct 29, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3ea0191175](https://linux-hardware.org/?probe=3ea0191175) | Oct 29, 2023 |
| Intel         | B75                         | Desktop     | [7b6b287377](https://linux-hardware.org/?probe=7b6b287377) | Oct 28, 2023 |
| Intel         | JSL MRD                     | Desktop     | [689d88c57b](https://linux-hardware.org/?probe=689d88c57b) | Oct 28, 2023 |
| Samsung       | 370E4K                      | Notebook    | [78ec3e796a](https://linux-hardware.org/?probe=78ec3e796a) | Oct 28, 2023 |
| Dell          | 076VHM A02                  | Desktop     | [456e31167b](https://linux-hardware.org/?probe=456e31167b) | Oct 28, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [6aa696ac55](https://linux-hardware.org/?probe=6aa696ac55) | Oct 28, 2023 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [10bcfab3cb](https://linux-hardware.org/?probe=10bcfab3cb) | Oct 28, 2023 |
| Intel         | H61                         | Desktop     | [1496665abb](https://linux-hardware.org/?probe=1496665abb) | Oct 27, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [5dac9d85f1](https://linux-hardware.org/?probe=5dac9d85f1) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1cb73bada5](https://linux-hardware.org/?probe=1cb73bada5) | Oct 27, 2023 |
| Intel         | H61                         | Desktop     | [fccff5fcb2](https://linux-hardware.org/?probe=fccff5fcb2) | Oct 27, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [9d34ff8710](https://linux-hardware.org/?probe=9d34ff8710) | Oct 27, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [114e1e6d66](https://linux-hardware.org/?probe=114e1e6d66) | Oct 27, 2023 |
| Sony          | SVS13A25PBS                 | Notebook    | [7cb087bd2d](https://linux-hardware.org/?probe=7cb087bd2d) | Oct 27, 2023 |
| Avell High... | 1513 Mxti                   | Notebook    | [9f5d60c02b](https://linux-hardware.org/?probe=9f5d60c02b) | Oct 27, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [b64c6bb72a](https://linux-hardware.org/?probe=b64c6bb72a) | Oct 26, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [8516768801](https://linux-hardware.org/?probe=8516768801) | Oct 26, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [2129ab3e24](https://linux-hardware.org/?probe=2129ab3e24) | Oct 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [2bee900f03](https://linux-hardware.org/?probe=2bee900f03) | Oct 26, 2023 |
| Dell          | 0K240Y A04                  | Desktop     | [5bf155abe0](https://linux-hardware.org/?probe=5bf155abe0) | Oct 26, 2023 |
| Dell          | Inspiron 3437               | Notebook    | [a57068abbc](https://linux-hardware.org/?probe=a57068abbc) | Oct 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [c9e8482167](https://linux-hardware.org/?probe=c9e8482167) | Oct 26, 2023 |
| Lenovo        | Y720-15IKB 81CQ             | Notebook    | [7aec151a1c](https://linux-hardware.org/?probe=7aec151a1c) | Oct 25, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [7fc2a154e5](https://linux-hardware.org/?probe=7fc2a154e5) | Oct 25, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [138843c6dc](https://linux-hardware.org/?probe=138843c6dc) | Oct 25, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [25c0172035](https://linux-hardware.org/?probe=25c0172035) | Oct 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [9a4561dabf](https://linux-hardware.org/?probe=9a4561dabf) | Oct 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [76d22d10e6](https://linux-hardware.org/?probe=76d22d10e6) | Oct 25, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [94f358053d](https://linux-hardware.org/?probe=94f358053d) | Oct 24, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [2fb1e4bb71](https://linux-hardware.org/?probe=2fb1e4bb71) | Oct 24, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [54a6d9d5d0](https://linux-hardware.org/?probe=54a6d9d5d0) | Oct 24, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [101b5bda5b](https://linux-hardware.org/?probe=101b5bda5b) | Oct 24, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [879198d56a](https://linux-hardware.org/?probe=879198d56a) | Oct 24, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f99b06d89a](https://linux-hardware.org/?probe=f99b06d89a) | Oct 24, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0e451d6616](https://linux-hardware.org/?probe=0e451d6616) | Oct 24, 2023 |
| Lenovo        | Y720-15IKB 81CQ             | Notebook    | [c0601dc338](https://linux-hardware.org/?probe=c0601dc338) | Oct 24, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [61d3768e3f](https://linux-hardware.org/?probe=61d3768e3f) | Oct 24, 2023 |
| Danuri        | B550M-PX                    | Desktop     | [e24df1ad61](https://linux-hardware.org/?probe=e24df1ad61) | Oct 24, 2023 |
| Intel         | H61 V124                    | Desktop     | [034689793f](https://linux-hardware.org/?probe=034689793f) | Oct 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [744dddac21](https://linux-hardware.org/?probe=744dddac21) | Oct 24, 2023 |
| Alienware     | m15 R6                      | Notebook    | [c6711f7b02](https://linux-hardware.org/?probe=c6711f7b02) | Oct 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [83d3faf177](https://linux-hardware.org/?probe=83d3faf177) | Oct 23, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [24a664955f](https://linux-hardware.org/?probe=24a664955f) | Oct 23, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [65494c95ec](https://linux-hardware.org/?probe=65494c95ec) | Oct 23, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [c931b1ef73](https://linux-hardware.org/?probe=c931b1ef73) | Oct 23, 2023 |
| Intel         | H61 V124                    | Desktop     | [2405df9db3](https://linux-hardware.org/?probe=2405df9db3) | Oct 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [da2cda923f](https://linux-hardware.org/?probe=da2cda923f) | Oct 23, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [9c24bc3329](https://linux-hardware.org/?probe=9c24bc3329) | Oct 23, 2023 |
| AZW           | Gemini M                    | Desktop     | [31ec911dd7](https://linux-hardware.org/?probe=31ec911dd7) | Oct 23, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [6a62fa5cb6](https://linux-hardware.org/?probe=6a62fa5cb6) | Oct 23, 2023 |
| HP            | Pavilion dv7                | Notebook    | [c3e7ebfd20](https://linux-hardware.org/?probe=c3e7ebfd20) | Oct 23, 2023 |
| Acer          | Aspire E5-573               | Notebook    | [d83f4bf9ad](https://linux-hardware.org/?probe=d83f4bf9ad) | Oct 23, 2023 |
| Dell          | G15 5515                    | Notebook    | [758d007f45](https://linux-hardware.org/?probe=758d007f45) | Oct 23, 2023 |
| Dell          | G15 5515                    | Notebook    | [5853f5312f](https://linux-hardware.org/?probe=5853f5312f) | Oct 23, 2023 |
| Positivo      | C4128G-15                   | Notebook    | [8d9aa2f206](https://linux-hardware.org/?probe=8d9aa2f206) | Oct 23, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e756845de4](https://linux-hardware.org/?probe=e756845de4) | Oct 23, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [60402f4ad8](https://linux-hardware.org/?probe=60402f4ad8) | Oct 23, 2023 |
| AZW           | BT3 X                       | Desktop     | [c1e3c10fc4](https://linux-hardware.org/?probe=c1e3c10fc4) | Oct 23, 2023 |
| AZW           | BT3 X                       | Desktop     | [78328e112b](https://linux-hardware.org/?probe=78328e112b) | Oct 23, 2023 |
| Biostar       | B450MH                      | Desktop     | [d082b0cf9d](https://linux-hardware.org/?probe=d082b0cf9d) | Oct 23, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [48d2114a2e](https://linux-hardware.org/?probe=48d2114a2e) | Oct 22, 2023 |
| HP            | Folio 13                    | Notebook    | [b7ed500d93](https://linux-hardware.org/?probe=b7ed500d93) | Oct 22, 2023 |
| Intel         | B75                         | Desktop     | [96f9a95f89](https://linux-hardware.org/?probe=96f9a95f89) | Oct 22, 2023 |
| Clevo         | M660SR                      | Notebook    | [56f8ab01f9](https://linux-hardware.org/?probe=56f8ab01f9) | Oct 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [2de56b09e8](https://linux-hardware.org/?probe=2de56b09e8) | Oct 22, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [588ad7e7ef](https://linux-hardware.org/?probe=588ad7e7ef) | Oct 22, 2023 |
| Intel         | H81                         | Desktop     | [f9351663fb](https://linux-hardware.org/?probe=f9351663fb) | Oct 21, 2023 |
| Dell          | Inspiron 3437               | Notebook    | [331cbd427d](https://linux-hardware.org/?probe=331cbd427d) | Oct 21, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [4f2229b9fa](https://linux-hardware.org/?probe=4f2229b9fa) | Oct 21, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3379c8b4e7](https://linux-hardware.org/?probe=3379c8b4e7) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [961c369ea4](https://linux-hardware.org/?probe=961c369ea4) | Oct 21, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [ad7ca8e192](https://linux-hardware.org/?probe=ad7ca8e192) | Oct 21, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f19c18154b](https://linux-hardware.org/?probe=f19c18154b) | Oct 21, 2023 |
| Gateway       | NV55C                       | Notebook    | [bb0eb9e5dd](https://linux-hardware.org/?probe=bb0eb9e5dd) | Oct 21, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [d3b1d639f5](https://linux-hardware.org/?probe=d3b1d639f5) | Oct 21, 2023 |
| Compaq        | 434                         | Notebook    | [094bba21f8](https://linux-hardware.org/?probe=094bba21f8) | Oct 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [deaf93db4b](https://linux-hardware.org/?probe=deaf93db4b) | Oct 21, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [436e243db6](https://linux-hardware.org/?probe=436e243db6) | Oct 21, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [0b9affbbb3](https://linux-hardware.org/?probe=0b9affbbb3) | Oct 21, 2023 |
| Acer          | Spin SP314-51               | Convertible | [b8e1c5b1dd](https://linux-hardware.org/?probe=b8e1c5b1dd) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [ca61a8649a](https://linux-hardware.org/?probe=ca61a8649a) | Oct 21, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [6108985945](https://linux-hardware.org/?probe=6108985945) | Oct 21, 2023 |
| LG Electro... | R410-G.BP21P1               | Notebook    | [36849f1a4c](https://linux-hardware.org/?probe=36849f1a4c) | Oct 21, 2023 |
| MACHINIST     | X99-MR9D PLUS V1.0          | Desktop     | [aaeff9a386](https://linux-hardware.org/?probe=aaeff9a386) | Oct 20, 2023 |
| HP            | Folio 13                    | Notebook    | [99ff48ac3f](https://linux-hardware.org/?probe=99ff48ac3f) | Oct 20, 2023 |
| Avell High... | B.ON                        | Notebook    | [7f8ce9da76](https://linux-hardware.org/?probe=7f8ce9da76) | Oct 20, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [ddc0c78bff](https://linux-hardware.org/?probe=ddc0c78bff) | Oct 20, 2023 |
| Dell          | Latitude 3490               | Notebook    | [174ee1b12e](https://linux-hardware.org/?probe=174ee1b12e) | Oct 20, 2023 |
| Dell          | Vostro 3300                 | Notebook    | [827b95e65c](https://linux-hardware.org/?probe=827b95e65c) | Oct 20, 2023 |
| Gigabyte      | 990XA-UD3 R5                | Desktop     | [c7d22a23d2](https://linux-hardware.org/?probe=c7d22a23d2) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [be03ed57d8](https://linux-hardware.org/?probe=be03ed57d8) | Oct 20, 2023 |
| Lenovo        | 30D0 NOK                    | Desktop     | [e67eff74dc](https://linux-hardware.org/?probe=e67eff74dc) | Oct 20, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [e648a8c32a](https://linux-hardware.org/?probe=e648a8c32a) | Oct 20, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [46d5d338b3](https://linux-hardware.org/?probe=46d5d338b3) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [6bb9b08c6e](https://linux-hardware.org/?probe=6bb9b08c6e) | Oct 20, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [db4e9dfc27](https://linux-hardware.org/?probe=db4e9dfc27) | Oct 20, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3fd9b0b53f](https://linux-hardware.org/?probe=3fd9b0b53f) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3b1da376dc](https://linux-hardware.org/?probe=3b1da376dc) | Oct 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [0506dfa238](https://linux-hardware.org/?probe=0506dfa238) | Oct 19, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [aa95d1c178](https://linux-hardware.org/?probe=aa95d1c178) | Oct 19, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [3dc947b334](https://linux-hardware.org/?probe=3dc947b334) | Oct 19, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [aeec82cef9](https://linux-hardware.org/?probe=aeec82cef9) | Oct 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [e94e48868c](https://linux-hardware.org/?probe=e94e48868c) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [abafeadb35](https://linux-hardware.org/?probe=abafeadb35) | Oct 19, 2023 |
| Compaq        | Presario CQ-23              | Notebook    | [15c10707d0](https://linux-hardware.org/?probe=15c10707d0) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [ab3c18427d](https://linux-hardware.org/?probe=ab3c18427d) | Oct 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a8e2b482f4](https://linux-hardware.org/?probe=a8e2b482f4) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [ab21923ddd](https://linux-hardware.org/?probe=ab21923ddd) | Oct 19, 2023 |
| Gigabyte      | H87-D3H-CF                  | Desktop     | [b1f1e05664](https://linux-hardware.org/?probe=b1f1e05664) | Oct 19, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [486e66cdee](https://linux-hardware.org/?probe=486e66cdee) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [495a705c9e](https://linux-hardware.org/?probe=495a705c9e) | Oct 18, 2023 |
| Dell          | 0DT021 A00                  | Server      | [f8f771286c](https://linux-hardware.org/?probe=f8f771286c) | Oct 18, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [315376a82a](https://linux-hardware.org/?probe=315376a82a) | Oct 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cf6314850a](https://linux-hardware.org/?probe=cf6314850a) | Oct 18, 2023 |
| Positivo      | Mobile                      | Notebook    | [5dedeac18e](https://linux-hardware.org/?probe=5dedeac18e) | Oct 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d7ddb794ec](https://linux-hardware.org/?probe=d7ddb794ec) | Oct 18, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [dbfa513b31](https://linux-hardware.org/?probe=dbfa513b31) | Oct 18, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [877ec2dd85](https://linux-hardware.org/?probe=877ec2dd85) | Oct 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d77237b330](https://linux-hardware.org/?probe=d77237b330) | Oct 18, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [65ee0747bc](https://linux-hardware.org/?probe=65ee0747bc) | Oct 18, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [50aa4fc1e1](https://linux-hardware.org/?probe=50aa4fc1e1) | Oct 18, 2023 |
| Lenovo        | B330S-15IKBR 81JV           | Notebook    | [5df1834272](https://linux-hardware.org/?probe=5df1834272) | Oct 18, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [041aba02ce](https://linux-hardware.org/?probe=041aba02ce) | Oct 17, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [6280e4287a](https://linux-hardware.org/?probe=6280e4287a) | Oct 17, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [27d26a4a15](https://linux-hardware.org/?probe=27d26a4a15) | Oct 17, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [54150823a1](https://linux-hardware.org/?probe=54150823a1) | Oct 17, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [e567a72b4c](https://linux-hardware.org/?probe=e567a72b4c) | Oct 17, 2023 |
| Lenovo        | B330S-15IKBR 81JV           | Notebook    | [9e1356181f](https://linux-hardware.org/?probe=9e1356181f) | Oct 17, 2023 |
| Dell          | Inspiron 5448               | Notebook    | [5901b49079](https://linux-hardware.org/?probe=5901b49079) | Oct 17, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [da5796de02](https://linux-hardware.org/?probe=da5796de02) | Oct 17, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [33cba76fe6](https://linux-hardware.org/?probe=33cba76fe6) | Oct 17, 2023 |
| HP            | Folio 13 - 2000             | Notebook    | [c541a1603c](https://linux-hardware.org/?probe=c541a1603c) | Oct 17, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [c615f7ee38](https://linux-hardware.org/?probe=c615f7ee38) | Oct 17, 2023 |
| Positivo      | POS-PIG43BC SIM             | Desktop     | [ded7e15a49](https://linux-hardware.org/?probe=ded7e15a49) | Oct 17, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ac47775d14](https://linux-hardware.org/?probe=ac47775d14) | Oct 17, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [25ba718720](https://linux-hardware.org/?probe=25ba718720) | Oct 16, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [d271c61b92](https://linux-hardware.org/?probe=d271c61b92) | Oct 16, 2023 |
| Intel         | H61                         | Desktop     | [2bd77947d1](https://linux-hardware.org/?probe=2bd77947d1) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [e87c9aab74](https://linux-hardware.org/?probe=e87c9aab74) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [e66f442843](https://linux-hardware.org/?probe=e66f442843) | Oct 16, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [eab86d1cc0](https://linux-hardware.org/?probe=eab86d1cc0) | Oct 16, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [ea1c91d413](https://linux-hardware.org/?probe=ea1c91d413) | Oct 16, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [fcc76a61ae](https://linux-hardware.org/?probe=fcc76a61ae) | Oct 16, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [fb2bf1baa8](https://linux-hardware.org/?probe=fb2bf1baa8) | Oct 16, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [0ca88d127f](https://linux-hardware.org/?probe=0ca88d127f) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [7f9e09a9e1](https://linux-hardware.org/?probe=7f9e09a9e1) | Oct 16, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [2571e4fd1b](https://linux-hardware.org/?probe=2571e4fd1b) | Oct 16, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [b1a36d42aa](https://linux-hardware.org/?probe=b1a36d42aa) | Oct 16, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [116667b041](https://linux-hardware.org/?probe=116667b041) | Oct 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [4faf7bb285](https://linux-hardware.org/?probe=4faf7bb285) | Oct 15, 2023 |
| Biostar       | A320MH                      | Desktop     | [d797fd8fa3](https://linux-hardware.org/?probe=d797fd8fa3) | Oct 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [90b07f2a8b](https://linux-hardware.org/?probe=90b07f2a8b) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [47788537bf](https://linux-hardware.org/?probe=47788537bf) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [30723700f1](https://linux-hardware.org/?probe=30723700f1) | Oct 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [52e554d0dc](https://linux-hardware.org/?probe=52e554d0dc) | Oct 15, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [e4dc0eeb72](https://linux-hardware.org/?probe=e4dc0eeb72) | Oct 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [c12987d53a](https://linux-hardware.org/?probe=c12987d53a) | Oct 15, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [a9599537b8](https://linux-hardware.org/?probe=a9599537b8) | Oct 15, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [079342de2b](https://linux-hardware.org/?probe=079342de2b) | Oct 15, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [68075a7e8f](https://linux-hardware.org/?probe=68075a7e8f) | Oct 15, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [9dae04bd63](https://linux-hardware.org/?probe=9dae04bd63) | Oct 15, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [2f6c2f44d3](https://linux-hardware.org/?probe=2f6c2f44d3) | Oct 15, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [579dc4dabc](https://linux-hardware.org/?probe=579dc4dabc) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [33a143a23d](https://linux-hardware.org/?probe=33a143a23d) | Oct 15, 2023 |
| PCWare        | IPMH61R1                    | Desktop     | [145dc39d14](https://linux-hardware.org/?probe=145dc39d14) | Oct 14, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [3c91ad6491](https://linux-hardware.org/?probe=3c91ad6491) | Oct 14, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [160af8609e](https://linux-hardware.org/?probe=160af8609e) | Oct 14, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [42e5a09fe2](https://linux-hardware.org/?probe=42e5a09fe2) | Oct 14, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [a1ada382fa](https://linux-hardware.org/?probe=a1ada382fa) | Oct 14, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [4280b509c6](https://linux-hardware.org/?probe=4280b509c6) | Oct 14, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [0a86fd4e1d](https://linux-hardware.org/?probe=0a86fd4e1d) | Oct 14, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [d45a6f5bf2](https://linux-hardware.org/?probe=d45a6f5bf2) | Oct 14, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [06aa8e692c](https://linux-hardware.org/?probe=06aa8e692c) | Oct 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [b00d98a451](https://linux-hardware.org/?probe=b00d98a451) | Oct 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [15168951ed](https://linux-hardware.org/?probe=15168951ed) | Oct 13, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [27ea9922a6](https://linux-hardware.org/?probe=27ea9922a6) | Oct 13, 2023 |
| Unknown       | MZ-B75-S                    | Desktop     | [6d58c79c33](https://linux-hardware.org/?probe=6d58c79c33) | Oct 13, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [7d186ff304](https://linux-hardware.org/?probe=7d186ff304) | Oct 13, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [2b45321310](https://linux-hardware.org/?probe=2b45321310) | Oct 13, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [edb6e06451](https://linux-hardware.org/?probe=edb6e06451) | Oct 13, 2023 |
| Digibras      | NH4CU53                     | Notebook    | [40f4cfc21c](https://linux-hardware.org/?probe=40f4cfc21c) | Oct 13, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f5e57e4558](https://linux-hardware.org/?probe=f5e57e4558) | Oct 13, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [1f1524c080](https://linux-hardware.org/?probe=1f1524c080) | Oct 13, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [0592faaf34](https://linux-hardware.org/?probe=0592faaf34) | Oct 12, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [65b1e10033](https://linux-hardware.org/?probe=65b1e10033) | Oct 12, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [6d2fdd060b](https://linux-hardware.org/?probe=6d2fdd060b) | Oct 12, 2023 |
| ASRock        | A320M-HD R4.0               | Desktop     | [1b1dd0c7fd](https://linux-hardware.org/?probe=1b1dd0c7fd) | Oct 12, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [94754c98ce](https://linux-hardware.org/?probe=94754c98ce) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [d7d6c5206f](https://linux-hardware.org/?probe=d7d6c5206f) | Oct 12, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [34792695eb](https://linux-hardware.org/?probe=34792695eb) | Oct 12, 2023 |
| Dell          | Latitude 3490               | Notebook    | [1c5aa8fca4](https://linux-hardware.org/?probe=1c5aa8fca4) | Oct 12, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [f68b19bbe5](https://linux-hardware.org/?probe=f68b19bbe5) | Oct 12, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [5e2f8bdc4d](https://linux-hardware.org/?probe=5e2f8bdc4d) | Oct 12, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [586d280ca5](https://linux-hardware.org/?probe=586d280ca5) | Oct 12, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [b71efdb817](https://linux-hardware.org/?probe=b71efdb817) | Oct 11, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [616aecbfbd](https://linux-hardware.org/?probe=616aecbfbd) | Oct 11, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [a6e6952b42](https://linux-hardware.org/?probe=a6e6952b42) | Oct 11, 2023 |
| Gateway       | NE570                       | Notebook    | [533fec5226](https://linux-hardware.org/?probe=533fec5226) | Oct 11, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [89ae9695ef](https://linux-hardware.org/?probe=89ae9695ef) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5566e985cf](https://linux-hardware.org/?probe=5566e985cf) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [835f369588](https://linux-hardware.org/?probe=835f369588) | Oct 11, 2023 |
| Avell High... | B.ON                        | Notebook    | [3a419fbd20](https://linux-hardware.org/?probe=3a419fbd20) | Oct 11, 2023 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [9acd34e892](https://linux-hardware.org/?probe=9acd34e892) | Oct 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [19f231af9a](https://linux-hardware.org/?probe=19f231af9a) | Oct 11, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [6324053514](https://linux-hardware.org/?probe=6324053514) | Oct 10, 2023 |
| Positivo      | POS-PIH110DV                | Desktop     | [f45f2f425b](https://linux-hardware.org/?probe=f45f2f425b) | Oct 10, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [0e1ec62b3b](https://linux-hardware.org/?probe=0e1ec62b3b) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c0882707d4](https://linux-hardware.org/?probe=c0882707d4) | Oct 10, 2023 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [c39ce018d6](https://linux-hardware.org/?probe=c39ce018d6) | Oct 10, 2023 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [a794ef5a77](https://linux-hardware.org/?probe=a794ef5a77) | Oct 10, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c397035651](https://linux-hardware.org/?probe=c397035651) | Oct 10, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7508b7cf4f](https://linux-hardware.org/?probe=7508b7cf4f) | Oct 10, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [8a64a738ca](https://linux-hardware.org/?probe=8a64a738ca) | Oct 10, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2192f74b2d](https://linux-hardware.org/?probe=2192f74b2d) | Oct 09, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [4a1888b421](https://linux-hardware.org/?probe=4a1888b421) | Oct 09, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [1da5f9aefa](https://linux-hardware.org/?probe=1da5f9aefa) | Oct 09, 2023 |
| Dell          | 0478VN A00                  | Desktop     | [8881cc216c](https://linux-hardware.org/?probe=8881cc216c) | Oct 09, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [407c6f0e29](https://linux-hardware.org/?probe=407c6f0e29) | Oct 09, 2023 |
| Gigabyte      | 945GZM-S2                   | Desktop     | [f9bafdf396](https://linux-hardware.org/?probe=f9bafdf396) | Oct 09, 2023 |
| Lenovo        | ThinkPad T490 20N3S8HL00    | Notebook    | [e75ca9bf06](https://linux-hardware.org/?probe=e75ca9bf06) | Oct 09, 2023 |
| Lenovo        | G480 20149                  | Notebook    | [ff58b011f2](https://linux-hardware.org/?probe=ff58b011f2) | Oct 09, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [f2fe39dcc0](https://linux-hardware.org/?probe=f2fe39dcc0) | Oct 09, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [f78bda610e](https://linux-hardware.org/?probe=f78bda610e) | Oct 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [508c438c6a](https://linux-hardware.org/?probe=508c438c6a) | Oct 09, 2023 |
| MACHINIST     | E5-MR9A V1.0                | Desktop     | [4be00bee3e](https://linux-hardware.org/?probe=4be00bee3e) | Oct 09, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [d7188e68cb](https://linux-hardware.org/?probe=d7188e68cb) | Oct 08, 2023 |
| ASRock        | A320M-HD R4.0               | Desktop     | [84fc58ce28](https://linux-hardware.org/?probe=84fc58ce28) | Oct 08, 2023 |
| Itautec       | SM 3321 SM-3321 Padrao 0... | Desktop     | [923cec3568](https://linux-hardware.org/?probe=923cec3568) | Oct 08, 2023 |
| Intel         | DG41WV AAE90316-102         | Desktop     | [c666aa6077](https://linux-hardware.org/?probe=c666aa6077) | Oct 08, 2023 |
| Unknown       | Unknown                     | Desktop     | [1eeecb8823](https://linux-hardware.org/?probe=1eeecb8823) | Oct 08, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [b580accff5](https://linux-hardware.org/?probe=b580accff5) | Oct 08, 2023 |
| Lenovo        | ThinkPad E14 20RB0028BR     | Notebook    | [bb9133e0b8](https://linux-hardware.org/?probe=bb9133e0b8) | Oct 08, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [b8557f2880](https://linux-hardware.org/?probe=b8557f2880) | Oct 08, 2023 |
| MACHINIST     | E5-MR9A V1.0                | Desktop     | [68e7f53229](https://linux-hardware.org/?probe=68e7f53229) | Oct 08, 2023 |
| AZW           | GTR V01                     | Mini pc     | [c2718a5c04](https://linux-hardware.org/?probe=c2718a5c04) | Oct 08, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [7e5e46c41a](https://linux-hardware.org/?probe=7e5e46c41a) | Oct 08, 2023 |
| Acer          | Swift SF514-56T             | Notebook    | [0d2d2cf2ae](https://linux-hardware.org/?probe=0d2d2cf2ae) | Oct 08, 2023 |
| HP            | ENVY dv7                    | Notebook    | [05ca6a125d](https://linux-hardware.org/?probe=05ca6a125d) | Oct 08, 2023 |
| HP            | Folio 13                    | Notebook    | [f4ed29d660](https://linux-hardware.org/?probe=f4ed29d660) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [3e5383da88](https://linux-hardware.org/?probe=3e5383da88) | Oct 08, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [687287904f](https://linux-hardware.org/?probe=687287904f) | Oct 08, 2023 |
| HP            | Pavilion g4                 | Notebook    | [cab160aff3](https://linux-hardware.org/?probe=cab160aff3) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [907f3a4cf1](https://linux-hardware.org/?probe=907f3a4cf1) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d003fa7343](https://linux-hardware.org/?probe=d003fa7343) | Oct 08, 2023 |
| ASUSTek       | G60JX                       | Notebook    | [e455f7fb08](https://linux-hardware.org/?probe=e455f7fb08) | Oct 08, 2023 |
| ASUSTek       | G60JX                       | Notebook    | [335e991de2](https://linux-hardware.org/?probe=335e991de2) | Oct 08, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [1756f5ba93](https://linux-hardware.org/?probe=1756f5ba93) | Oct 08, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [ac5943ef0c](https://linux-hardware.org/?probe=ac5943ef0c) | Oct 08, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [e1cfe6d474](https://linux-hardware.org/?probe=e1cfe6d474) | Oct 08, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [c59dc86e48](https://linux-hardware.org/?probe=c59dc86e48) | Oct 08, 2023 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [7b7ac9e326](https://linux-hardware.org/?probe=7b7ac9e326) | Oct 07, 2023 |
| Acer          | Swift SF514-56T             | Notebook    | [9f94f8934f](https://linux-hardware.org/?probe=9f94f8934f) | Oct 07, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | Notebook    | [d375cfe649](https://linux-hardware.org/?probe=d375cfe649) | Oct 07, 2023 |
| Samsung       | 960XFH                      | Notebook    | [0d8aca1f6e](https://linux-hardware.org/?probe=0d8aca1f6e) | Oct 07, 2023 |
| Samsung       | 960XFH                      | Notebook    | [a2138fa3f8](https://linux-hardware.org/?probe=a2138fa3f8) | Oct 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [7bd2b6300f](https://linux-hardware.org/?probe=7bd2b6300f) | Oct 07, 2023 |
| ASUSTek       | BM1AF_BP1AF_BM6AF           | Desktop     | [bad5263013](https://linux-hardware.org/?probe=bad5263013) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [40c01d2bf5](https://linux-hardware.org/?probe=40c01d2bf5) | Oct 07, 2023 |
| Gigabyte      | A520M K V2                  | Desktop     | [839ad0c4b6](https://linux-hardware.org/?probe=839ad0c4b6) | Oct 07, 2023 |
| Gigabyte      | A520M K V2                  | Desktop     | [f3e7c14b62](https://linux-hardware.org/?probe=f3e7c14b62) | Oct 07, 2023 |
| Dell          | Latitude 3490               | Notebook    | [723d6797ae](https://linux-hardware.org/?probe=723d6797ae) | Oct 07, 2023 |
| Dell          | Inspiron 5421               | Notebook    | [90c1f511a6](https://linux-hardware.org/?probe=90c1f511a6) | Oct 06, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [39ee83fbf5](https://linux-hardware.org/?probe=39ee83fbf5) | Oct 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [62c8d86cfa](https://linux-hardware.org/?probe=62c8d86cfa) | Oct 06, 2023 |
| Intel         | H61                         | Desktop     | [1abb1c8f57](https://linux-hardware.org/?probe=1abb1c8f57) | Oct 06, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [2e48163fbd](https://linux-hardware.org/?probe=2e48163fbd) | Oct 06, 2023 |
| Sony          | VGN-SR150A                  | Notebook    | [f8fcbe4227](https://linux-hardware.org/?probe=f8fcbe4227) | Oct 06, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [45a4c0fbe0](https://linux-hardware.org/?probe=45a4c0fbe0) | Oct 06, 2023 |
| Positivo B... | VJFE55F11X-B0211H           | Notebook    | [8d54d8438d](https://linux-hardware.org/?probe=8d54d8438d) | Oct 05, 2023 |
| Dell          | 0478VN A00                  | Desktop     | [511df57852](https://linux-hardware.org/?probe=511df57852) | Oct 05, 2023 |
| Biostar       | B450MH                      | Desktop     | [b47659f758](https://linux-hardware.org/?probe=b47659f758) | Oct 05, 2023 |
| Acer          | Aspire ES1-572              | Notebook    | [651a8f8f97](https://linux-hardware.org/?probe=651a8f8f97) | Oct 05, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [e346a58990](https://linux-hardware.org/?probe=e346a58990) | Oct 05, 2023 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [fc6322811e](https://linux-hardware.org/?probe=fc6322811e) | Oct 04, 2023 |
| Philco Inf... | EC10IS2                     | Notebook    | [f85315b46a](https://linux-hardware.org/?probe=f85315b46a) | Oct 04, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [80010c71e1](https://linux-hardware.org/?probe=80010c71e1) | Oct 04, 2023 |
| Dell          | Inspiron 5490               | Notebook    | [5ab40107ce](https://linux-hardware.org/?probe=5ab40107ce) | Oct 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a49cef1179](https://linux-hardware.org/?probe=a49cef1179) | Oct 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a72a2ee89e](https://linux-hardware.org/?probe=a72a2ee89e) | Oct 04, 2023 |
| Positivo      | S14BW01                     | Notebook    | [3027fc7d9b](https://linux-hardware.org/?probe=3027fc7d9b) | Oct 04, 2023 |
| Dell          | Inspiron 5575               | Notebook    | [48afb4262c](https://linux-hardware.org/?probe=48afb4262c) | Oct 04, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [6ea97d511f](https://linux-hardware.org/?probe=6ea97d511f) | Oct 04, 2023 |
| Lenovo        | NOK                         | Desktop     | [dd6bffed79](https://linux-hardware.org/?probe=dd6bffed79) | Oct 04, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [8356867b4d](https://linux-hardware.org/?probe=8356867b4d) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7bb81b99a0](https://linux-hardware.org/?probe=7bb81b99a0) | Oct 04, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [06d30a9c8d](https://linux-hardware.org/?probe=06d30a9c8d) | Oct 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cf2552023d](https://linux-hardware.org/?probe=cf2552023d) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [5813f8d107](https://linux-hardware.org/?probe=5813f8d107) | Oct 03, 2023 |
| MSI           | CR620                       | Notebook    | [be490381a9](https://linux-hardware.org/?probe=be490381a9) | Oct 03, 2023 |
| Dell          | 0P0MXR A00                  | Desktop     | [06af26dae3](https://linux-hardware.org/?probe=06af26dae3) | Oct 03, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [81c44f8b56](https://linux-hardware.org/?probe=81c44f8b56) | Oct 03, 2023 |
| Dell          | 0P0MXR A00                  | Desktop     | [9b4bfad0cc](https://linux-hardware.org/?probe=9b4bfad0cc) | Oct 03, 2023 |
| Dell          | Inspiron 5480               | Notebook    | [666fbb9e46](https://linux-hardware.org/?probe=666fbb9e46) | Oct 03, 2023 |
| Unknown       | Phitronics G31VS-M          | Desktop     | [a30a4e0d2e](https://linux-hardware.org/?probe=a30a4e0d2e) | Oct 03, 2023 |
| Intel         | H61                         | Desktop     | [977f3d58ab](https://linux-hardware.org/?probe=977f3d58ab) | Oct 03, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [b4f51ced7a](https://linux-hardware.org/?probe=b4f51ced7a) | Oct 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [90883fd019](https://linux-hardware.org/?probe=90883fd019) | Oct 02, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [9574c05fb2](https://linux-hardware.org/?probe=9574c05fb2) | Oct 02, 2023 |
| Compaq        | 420                         | Notebook    | [b327579e60](https://linux-hardware.org/?probe=b327579e60) | Oct 02, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [020c2fbbf8](https://linux-hardware.org/?probe=020c2fbbf8) | Oct 02, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [2435f20a18](https://linux-hardware.org/?probe=2435f20a18) | Oct 02, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [cf9e8e26c2](https://linux-hardware.org/?probe=cf9e8e26c2) | Oct 02, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [60a8a7d13f](https://linux-hardware.org/?probe=60a8a7d13f) | Oct 02, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [7ff4fd8349](https://linux-hardware.org/?probe=7ff4fd8349) | Oct 02, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [28a54d8189](https://linux-hardware.org/?probe=28a54d8189) | Oct 02, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [a348906862](https://linux-hardware.org/?probe=a348906862) | Oct 02, 2023 |
| Pegatron      | SM3330 0112                 | Desktop     | [290983ac13](https://linux-hardware.org/?probe=290983ac13) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [f510af1acf](https://linux-hardware.org/?probe=f510af1acf) | Oct 01, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [44bfa52d57](https://linux-hardware.org/?probe=44bfa52d57) | Oct 01, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [27e61d282f](https://linux-hardware.org/?probe=27e61d282f) | Oct 01, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [8fa784881e](https://linux-hardware.org/?probe=8fa784881e) | Oct 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [aae60ff071](https://linux-hardware.org/?probe=aae60ff071) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [7b44ef8cd1](https://linux-hardware.org/?probe=7b44ef8cd1) | Oct 01, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [b79529501a](https://linux-hardware.org/?probe=b79529501a) | Oct 01, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [a1f20bb140](https://linux-hardware.org/?probe=a1f20bb140) | Sep 30, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1449844643](https://linux-hardware.org/?probe=1449844643) | Sep 30, 2023 |
| Toshiba       | STI 009169                  | Desktop     | [0b76bae8f3](https://linux-hardware.org/?probe=0b76bae8f3) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [63aafe31f1](https://linux-hardware.org/?probe=63aafe31f1) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [770e7037d3](https://linux-hardware.org/?probe=770e7037d3) | Sep 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ba4aa68077](https://linux-hardware.org/?probe=ba4aa68077) | Sep 30, 2023 |
| Unknown       | Phitronics N68C-M           | Desktop     | [72b5c903d3](https://linux-hardware.org/?probe=72b5c903d3) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| Intel         | H61                         | Desktop     | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| Intel         | H61                         | Desktop     | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| Tectoy        | Pense Bem Notebook          | Notebook    | [6a6e6af34c](https://linux-hardware.org/?probe=6a6e6af34c) | Sep 29, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [6177caee37](https://linux-hardware.org/?probe=6177caee37) | Sep 29, 2023 |
| Positivo      | C14CR01                     | Notebook    | [11b171838d](https://linux-hardware.org/?probe=11b171838d) | Sep 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [772e866a05](https://linux-hardware.org/?probe=772e866a05) | Sep 29, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [c0301c2fbb](https://linux-hardware.org/?probe=c0301c2fbb) | Sep 29, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [0e67f3a0f3](https://linux-hardware.org/?probe=0e67f3a0f3) | Sep 29, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [e55a394d41](https://linux-hardware.org/?probe=e55a394d41) | Sep 29, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ccc715eeb6](https://linux-hardware.org/?probe=ccc715eeb6) | Sep 29, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [51272b2713](https://linux-hardware.org/?probe=51272b2713) | Sep 28, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81JN     | Notebook    | [747f0d45fe](https://linux-hardware.org/?probe=747f0d45fe) | Sep 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ce3a9f8960](https://linux-hardware.org/?probe=ce3a9f8960) | Sep 28, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [62ba806672](https://linux-hardware.org/?probe=62ba806672) | Sep 28, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [1509f60079](https://linux-hardware.org/?probe=1509f60079) | Sep 28, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b6f9976e23](https://linux-hardware.org/?probe=b6f9976e23) | Sep 28, 2023 |
| ASUSTek       | K45VM                       | Notebook    | [6c167e69a4](https://linux-hardware.org/?probe=6c167e69a4) | Sep 28, 2023 |
| Acer          | Acadia V1.35                | Notebook    | [c2074b2535](https://linux-hardware.org/?probe=c2074b2535) | Sep 28, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [acd3733ebf](https://linux-hardware.org/?probe=acd3733ebf) | Sep 27, 2023 |
| EUROCOM       | RACER 2.0                   | Notebook    | [4351733d37](https://linux-hardware.org/?probe=4351733d37) | Sep 27, 2023 |
| Positivo      | POS-RIH470EM 11179450       | Desktop     | [cf8e3e73bb](https://linux-hardware.org/?probe=cf8e3e73bb) | Sep 27, 2023 |
| Samsung       | 550XDA                      | Notebook    | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| Unknown       | Unknown                     | Desktop     | [cb12d6c853](https://linux-hardware.org/?probe=cb12d6c853) | Sep 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f47347fb9b](https://linux-hardware.org/?probe=f47347fb9b) | Sep 27, 2023 |
| Dell          | System XPS L502X            | Notebook    | [06d6fd95d1](https://linux-hardware.org/?probe=06d6fd95d1) | Sep 27, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [c20a9f8f96](https://linux-hardware.org/?probe=c20a9f8f96) | Sep 27, 2023 |
| Dell          | G15 5520                    | Notebook    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Inspiron 5423               | Notebook    | [a6a3b2697f](https://linux-hardware.org/?probe=a6a3b2697f) | Sep 26, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [6ebf39a37a](https://linux-hardware.org/?probe=6ebf39a37a) | Sep 26, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [644a616222](https://linux-hardware.org/?probe=644a616222) | Sep 26, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [811818acb8](https://linux-hardware.org/?probe=811818acb8) | Sep 26, 2023 |
| Huanan        | X99-8M-F V1.2               | Desktop     | [4ddba514a1](https://linux-hardware.org/?probe=4ddba514a1) | Sep 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [acde6e2ba0](https://linux-hardware.org/?probe=acde6e2ba0) | Sep 26, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3d8dfdbf80](https://linux-hardware.org/?probe=3d8dfdbf80) | Sep 26, 2023 |
| HP            | Folio 13                    | Notebook    | [a5a1ae29a7](https://linux-hardware.org/?probe=a5a1ae29a7) | Sep 26, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [89d81885ff](https://linux-hardware.org/?probe=89d81885ff) | Sep 26, 2023 |
| Intel         | H61                         | Desktop     | [ee0266b53c](https://linux-hardware.org/?probe=ee0266b53c) | Sep 25, 2023 |
| Intel         | W7645                       | Notebook    | [8a83c23785](https://linux-hardware.org/?probe=8a83c23785) | Sep 25, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [0b586071f1](https://linux-hardware.org/?probe=0b586071f1) | Sep 25, 2023 |
| HP            | Presario CQ43               | Notebook    | [c206dc84ad](https://linux-hardware.org/?probe=c206dc84ad) | Sep 25, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [a2f6814940](https://linux-hardware.org/?probe=a2f6814940) | Sep 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8a7db88ae5](https://linux-hardware.org/?probe=8a7db88ae5) | Sep 25, 2023 |
| Dell          | Latitude E5440              | Notebook    | [f4accb1cb0](https://linux-hardware.org/?probe=f4accb1cb0) | Sep 25, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [fee2fdb49a](https://linux-hardware.org/?probe=fee2fdb49a) | Sep 25, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [705c3fdeff](https://linux-hardware.org/?probe=705c3fdeff) | Sep 25, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [e74a87d3f4](https://linux-hardware.org/?probe=e74a87d3f4) | Sep 25, 2023 |
| HP            | Presario CQ43               | Notebook    | [b2663eb2fa](https://linux-hardware.org/?probe=b2663eb2fa) | Sep 25, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [6d6d719f30](https://linux-hardware.org/?probe=6d6d719f30) | Sep 25, 2023 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [69cccf347a](https://linux-hardware.org/?probe=69cccf347a) | Sep 25, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [c643f10970](https://linux-hardware.org/?probe=c643f10970) | Sep 24, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [cdbacef976](https://linux-hardware.org/?probe=cdbacef976) | Sep 24, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [eb82ffb863](https://linux-hardware.org/?probe=eb82ffb863) | Sep 24, 2023 |
| OEM           | B75 Ver:1.41                | Desktop     | [01109ec772](https://linux-hardware.org/?probe=01109ec772) | Sep 24, 2023 |
| Lenovo        | ThinkCentre A70z 0401B7P    | Desktop     | [21a635940f](https://linux-hardware.org/?probe=21a635940f) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d71e760b5c](https://linux-hardware.org/?probe=d71e760b5c) | Sep 24, 2023 |
| PCWare        | APM-A320G                   | Desktop     | [64080404a6](https://linux-hardware.org/?probe=64080404a6) | Sep 24, 2023 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [9f17460970](https://linux-hardware.org/?probe=9f17460970) | Sep 24, 2023 |
| HOUTER        | OROPC                       | Desktop     | [96625070be](https://linux-hardware.org/?probe=96625070be) | Sep 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [84bba5e5a7](https://linux-hardware.org/?probe=84bba5e5a7) | Sep 24, 2023 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [3c2427ba03](https://linux-hardware.org/?probe=3c2427ba03) | Sep 23, 2023 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [586c05976a](https://linux-hardware.org/?probe=586c05976a) | Sep 23, 2023 |
| HOUTER        | OROPC                       | Desktop     | [3f78fb9290](https://linux-hardware.org/?probe=3f78fb9290) | Sep 23, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [c2cb8052f9](https://linux-hardware.org/?probe=c2cb8052f9) | Sep 23, 2023 |
| HP            | Presario CQ43               | Notebook    | [d5ee5e4318](https://linux-hardware.org/?probe=d5ee5e4318) | Sep 23, 2023 |
| Gigabyte      | GA-880GMA-UD2H              | Desktop     | [fbeac0cab4](https://linux-hardware.org/?probe=fbeac0cab4) | Sep 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [7022eac21d](https://linux-hardware.org/?probe=7022eac21d) | Sep 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [287bf4d933](https://linux-hardware.org/?probe=287bf4d933) | Sep 23, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [c74511d498](https://linux-hardware.org/?probe=c74511d498) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [04141bd71c](https://linux-hardware.org/?probe=04141bd71c) | Sep 22, 2023 |
| Dell          | Latitude E7440              | Notebook    | [53e90ca355](https://linux-hardware.org/?probe=53e90ca355) | Sep 22, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [65a21a4968](https://linux-hardware.org/?probe=65a21a4968) | Sep 22, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [47e5429752](https://linux-hardware.org/?probe=47e5429752) | Sep 22, 2023 |
| HP            | Folio 13                    | Notebook    | [66f8752b64](https://linux-hardware.org/?probe=66f8752b64) | Sep 22, 2023 |
| Lenovo        | ThinkPad X220 4286BB2       | Notebook    | [a3b217a707](https://linux-hardware.org/?probe=a3b217a707) | Sep 21, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [a35f78cead](https://linux-hardware.org/?probe=a35f78cead) | Sep 21, 2023 |
| Positivo      | POS-AG31AP                  | Desktop     | [2e2072e3ca](https://linux-hardware.org/?probe=2e2072e3ca) | Sep 21, 2023 |
| Megaware      | MW-HDC-M 02/24/2012 - ME... | Desktop     | [d3c9063140](https://linux-hardware.org/?probe=d3c9063140) | Sep 21, 2023 |
| Intel         | B75                         | Desktop     | [37b59e6605](https://linux-hardware.org/?probe=37b59e6605) | Sep 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [dd328a6f1f](https://linux-hardware.org/?probe=dd328a6f1f) | Sep 21, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [522d50a437](https://linux-hardware.org/?probe=522d50a437) | Sep 21, 2023 |
| Samsung       | 550XDA                      | Notebook    | [2d15b3f4ca](https://linux-hardware.org/?probe=2d15b3f4ca) | Sep 21, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e2dda8ebb1](https://linux-hardware.org/?probe=e2dda8ebb1) | Sep 21, 2023 |
| Intel         | H55                         | Desktop     | [03693f8574](https://linux-hardware.org/?probe=03693f8574) | Sep 21, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [5e05853c00](https://linux-hardware.org/?probe=5e05853c00) | Sep 20, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [5a74bb7dde](https://linux-hardware.org/?probe=5a74bb7dde) | Sep 20, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [f7629203e7](https://linux-hardware.org/?probe=f7629203e7) | Sep 20, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [49bb68e979](https://linux-hardware.org/?probe=49bb68e979) | Sep 20, 2023 |
| ASUSTek       | Z450UA                      | Notebook    | [60d85e59da](https://linux-hardware.org/?probe=60d85e59da) | Sep 20, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [16b2b018c1](https://linux-hardware.org/?probe=16b2b018c1) | Sep 20, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [01d8f27500](https://linux-hardware.org/?probe=01d8f27500) | Sep 20, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [d8305c7c45](https://linux-hardware.org/?probe=d8305c7c45) | Sep 20, 2023 |
| Dell          | 06HR05 A00                  | Desktop     | [a01d6b8630](https://linux-hardware.org/?probe=a01d6b8630) | Sep 20, 2023 |
| Samsung       | 960XFH                      | Notebook    | [c25c858bd4](https://linux-hardware.org/?probe=c25c858bd4) | Sep 19, 2023 |
| Apple         | Mac-F2208EC8                | Mini pc     | [8f90540e05](https://linux-hardware.org/?probe=8f90540e05) | Sep 19, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7ff48f538f](https://linux-hardware.org/?probe=7ff48f538f) | Sep 19, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [1f6ca2e4f7](https://linux-hardware.org/?probe=1f6ca2e4f7) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [6d9002e7e3](https://linux-hardware.org/?probe=6d9002e7e3) | Sep 19, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [c53d44303e](https://linux-hardware.org/?probe=c53d44303e) | Sep 19, 2023 |
| wpc           | zrd616                      | Desktop     | [f218d73abb](https://linux-hardware.org/?probe=f218d73abb) | Sep 19, 2023 |
| Biostar       | B550GTQ                     | Desktop     | [5478c7bc91](https://linux-hardware.org/?probe=5478c7bc91) | Sep 19, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [6588973c54](https://linux-hardware.org/?probe=6588973c54) | Sep 19, 2023 |
| Samsung       | 550XDA                      | Notebook    | [763631bfe7](https://linux-hardware.org/?probe=763631bfe7) | Sep 19, 2023 |
| Daten Tecn... | DT02-M4                     | Notebook    | [67c158a4f1](https://linux-hardware.org/?probe=67c158a4f1) | Sep 19, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [1bd2a17c99](https://linux-hardware.org/?probe=1bd2a17c99) | Sep 19, 2023 |
| Biostar       | H61MLC                      | Desktop     | [154ead8447](https://linux-hardware.org/?probe=154ead8447) | Sep 19, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [28d0c94948](https://linux-hardware.org/?probe=28d0c94948) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | Notebook    | [d68a92e72a](https://linux-hardware.org/?probe=d68a92e72a) | Sep 19, 2023 |
| Lenovo        | B490 37722QP                | Notebook    | [8b335d6bb0](https://linux-hardware.org/?probe=8b335d6bb0) | Sep 19, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [00ce48a639](https://linux-hardware.org/?probe=00ce48a639) | Sep 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0ec89ecd46](https://linux-hardware.org/?probe=0ec89ecd46) | Sep 19, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [430ed1fe6c](https://linux-hardware.org/?probe=430ed1fe6c) | Sep 19, 2023 |
| HP            | Compaq Mini 311-1100        | Notebook    | [418d54b71d](https://linux-hardware.org/?probe=418d54b71d) | Sep 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0b036a6058](https://linux-hardware.org/?probe=0b036a6058) | Sep 18, 2023 |
| Dell          | 076VHM A02                  | Desktop     | [518361bbc5](https://linux-hardware.org/?probe=518361bbc5) | Sep 18, 2023 |
| Positivo      | POS-EIH610EX 11187943       | Desktop     | [10fbe8fd9b](https://linux-hardware.org/?probe=10fbe8fd9b) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [5701fbde3e](https://linux-hardware.org/?probe=5701fbde3e) | Sep 18, 2023 |
| Dell          | Inspiron 5480               | Notebook    | [51aca22643](https://linux-hardware.org/?probe=51aca22643) | Sep 18, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [514a5308f2](https://linux-hardware.org/?probe=514a5308f2) | Sep 18, 2023 |
| ASUSTek       | X450CA                      | Notebook    | [b43a3aa61c](https://linux-hardware.org/?probe=b43a3aa61c) | Sep 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [5597daf348](https://linux-hardware.org/?probe=5597daf348) | Sep 18, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [aebeeb7401](https://linux-hardware.org/?probe=aebeeb7401) | Sep 17, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [1875fb96e5](https://linux-hardware.org/?probe=1875fb96e5) | Sep 17, 2023 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [e1805d26c3](https://linux-hardware.org/?probe=e1805d26c3) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [d4d891ca35](https://linux-hardware.org/?probe=d4d891ca35) | Sep 17, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [2e8cd612d8](https://linux-hardware.org/?probe=2e8cd612d8) | Sep 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [b8459514db](https://linux-hardware.org/?probe=b8459514db) | Sep 17, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [1e71e60505](https://linux-hardware.org/?probe=1e71e60505) | Sep 17, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [8db77afc82](https://linux-hardware.org/?probe=8db77afc82) | Sep 17, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [56f2d4d1eb](https://linux-hardware.org/?probe=56f2d4d1eb) | Sep 17, 2023 |
| ANGXUN        | X99 V1.0                    | Desktop     | [c6c6277bf3](https://linux-hardware.org/?probe=c6c6277bf3) | Sep 17, 2023 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [656da36be3](https://linux-hardware.org/?probe=656da36be3) | Sep 17, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [48ea99b656](https://linux-hardware.org/?probe=48ea99b656) | Sep 16, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [d42482a830](https://linux-hardware.org/?probe=d42482a830) | Sep 16, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [f95cfdee8d](https://linux-hardware.org/?probe=f95cfdee8d) | Sep 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [6f73b0398c](https://linux-hardware.org/?probe=6f73b0398c) | Sep 16, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [7b10a3651b](https://linux-hardware.org/?probe=7b10a3651b) | Sep 16, 2023 |
| Dell          | Latitude E6430              | Notebook    | [a426075604](https://linux-hardware.org/?probe=a426075604) | Sep 16, 2023 |
| Compaq        | 420                         | Notebook    | [a0ce747ff2](https://linux-hardware.org/?probe=a0ce747ff2) | Sep 16, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Notebook    | [4298a1ab82](https://linux-hardware.org/?probe=4298a1ab82) | Sep 16, 2023 |
| Biostar       | X370GTN                     | Desktop     | [1ac44acadd](https://linux-hardware.org/?probe=1ac44acadd) | Sep 16, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [8a404c05c2](https://linux-hardware.org/?probe=8a404c05c2) | Sep 15, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [100f789658](https://linux-hardware.org/?probe=100f789658) | Sep 15, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [8c1887fa93](https://linux-hardware.org/?probe=8c1887fa93) | Sep 15, 2023 |
| Digibras      | CL341                       | Notebook    | [a358f5d40c](https://linux-hardware.org/?probe=a358f5d40c) | Sep 15, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [bf4d733039](https://linux-hardware.org/?probe=bf4d733039) | Sep 15, 2023 |
| Lenovo        | Slim Pro 9 14IRP8 83BV      | Notebook    | [bc86928972](https://linux-hardware.org/?probe=bc86928972) | Sep 15, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e484eea129](https://linux-hardware.org/?probe=e484eea129) | Sep 14, 2023 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [135712cd9e](https://linux-hardware.org/?probe=135712cd9e) | Sep 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [cbe7fd494b](https://linux-hardware.org/?probe=cbe7fd494b) | Sep 14, 2023 |
| Itautec       | Infoway                     | Notebook    | [d4a8bc6420](https://linux-hardware.org/?probe=d4a8bc6420) | Sep 14, 2023 |
| HP            | Folio 13                    | Notebook    | [9ed048b9e4](https://linux-hardware.org/?probe=9ed048b9e4) | Sep 14, 2023 |
| Acer          | Swift SF314-511             | Notebook    | [4714deba45](https://linux-hardware.org/?probe=4714deba45) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9fde2c205d](https://linux-hardware.org/?probe=9fde2c205d) | Sep 14, 2023 |
| Dell          | Vostro 1520                 | Notebook    | [5d70233702](https://linux-hardware.org/?probe=5d70233702) | Sep 14, 2023 |
| Intel         | H61                         | Desktop     | [5dd60be36a](https://linux-hardware.org/?probe=5dd60be36a) | Sep 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0be4e6cba4](https://linux-hardware.org/?probe=0be4e6cba4) | Sep 13, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [6c9eaad10e](https://linux-hardware.org/?probe=6c9eaad10e) | Sep 13, 2023 |
| Positivo      | C14CR21                     | Notebook    | [9d48466eab](https://linux-hardware.org/?probe=9d48466eab) | Sep 13, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [df7945af41](https://linux-hardware.org/?probe=df7945af41) | Sep 13, 2023 |
| Pegatron      | 2AC3                        | Desktop     | [4cee44e8ac](https://linux-hardware.org/?probe=4cee44e8ac) | Sep 13, 2023 |
| Dell          | Latitude E4300              | Notebook    | [ed27d2d51c](https://linux-hardware.org/?probe=ed27d2d51c) | Sep 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [c2088a6e42](https://linux-hardware.org/?probe=c2088a6e42) | Sep 13, 2023 |
| HOUTER        | OROPC                       | Desktop     | [711d8f8d80](https://linux-hardware.org/?probe=711d8f8d80) | Sep 13, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [07e5f3eb14](https://linux-hardware.org/?probe=07e5f3eb14) | Sep 13, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [32b69241bf](https://linux-hardware.org/?probe=32b69241bf) | Sep 13, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [3c36dccf79](https://linux-hardware.org/?probe=3c36dccf79) | Sep 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [bee3c23461](https://linux-hardware.org/?probe=bee3c23461) | Sep 12, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [cb58094846](https://linux-hardware.org/?probe=cb58094846) | Sep 12, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [31cc220aae](https://linux-hardware.org/?probe=31cc220aae) | Sep 12, 2023 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | Desktop     | [fd4e189b56](https://linux-hardware.org/?probe=fd4e189b56) | Sep 12, 2023 |
| Acer          | Aspire A514-54              | Notebook    | [8ddb560fdc](https://linux-hardware.org/?probe=8ddb560fdc) | Sep 12, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [4318e0630c](https://linux-hardware.org/?probe=4318e0630c) | Sep 12, 2023 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [caef8df1be](https://linux-hardware.org/?probe=caef8df1be) | Sep 12, 2023 |
| Intel         | H61                         | Desktop     | [513ebd18a2](https://linux-hardware.org/?probe=513ebd18a2) | Sep 12, 2023 |
| Intel         | H61                         | Desktop     | [fec08a2214](https://linux-hardware.org/?probe=fec08a2214) | Sep 12, 2023 |
| PCWare        | IPMH81G1                    | Desktop     | [181367c2db](https://linux-hardware.org/?probe=181367c2db) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [564a2ea72e](https://linux-hardware.org/?probe=564a2ea72e) | Sep 12, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [68f0df2a6c](https://linux-hardware.org/?probe=68f0df2a6c) | Sep 12, 2023 |
| Dell          | Latitude E6420              | Notebook    | [2a15e9a8e0](https://linux-hardware.org/?probe=2a15e9a8e0) | Sep 12, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [a1f824e885](https://linux-hardware.org/?probe=a1f824e885) | Sep 12, 2023 |
| Positivo      | S14CT01                     | Notebook    | [57ed555d4b](https://linux-hardware.org/?probe=57ed555d4b) | Sep 11, 2023 |
| Dell          | Inspiron 5458               | Notebook    | [ab3824f3d0](https://linux-hardware.org/?probe=ab3824f3d0) | Sep 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [ecdef7173c](https://linux-hardware.org/?probe=ecdef7173c) | Sep 11, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [61dc55f063](https://linux-hardware.org/?probe=61dc55f063) | Sep 11, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [c780b34220](https://linux-hardware.org/?probe=c780b34220) | Sep 11, 2023 |
| Gigabyte      | H610M H DDR4                | Desktop     | [e3e2a65f4a](https://linux-hardware.org/?probe=e3e2a65f4a) | Sep 11, 2023 |
| Dell          | 0YXT71 A01                  | Desktop     | [36991ac5a6](https://linux-hardware.org/?probe=36991ac5a6) | Sep 11, 2023 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [7f5f0fccd0](https://linux-hardware.org/?probe=7f5f0fccd0) | Sep 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [fdc2e70c28](https://linux-hardware.org/?probe=fdc2e70c28) | Sep 11, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [7caa16d219](https://linux-hardware.org/?probe=7caa16d219) | Sep 11, 2023 |
| Dell          | Latitude E6420              | Notebook    | [7e57362cdc](https://linux-hardware.org/?probe=7e57362cdc) | Sep 11, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [671415f9ca](https://linux-hardware.org/?probe=671415f9ca) | Sep 11, 2023 |
| Samsung       | 530XBB                      | Notebook    | [f6039477c2](https://linux-hardware.org/?probe=f6039477c2) | Sep 11, 2023 |
| Philco        | DTC-A55                     | Desktop     | [30cdd25bb0](https://linux-hardware.org/?probe=30cdd25bb0) | Sep 11, 2023 |
| Sony          | VGN-FZ140E                  | Notebook    | [361226919e](https://linux-hardware.org/?probe=361226919e) | Sep 11, 2023 |
| Samsung       | 550XED                      | Notebook    | [69d754d35b](https://linux-hardware.org/?probe=69d754d35b) | Sep 11, 2023 |
| Samsung       | 550XED                      | Notebook    | [8187eca3e3](https://linux-hardware.org/?probe=8187eca3e3) | Sep 11, 2023 |
| Login Info... | LOG-H61H2-M2                | Desktop     | [fa6e51b9bf](https://linux-hardware.org/?probe=fa6e51b9bf) | Sep 11, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [772c3204b4](https://linux-hardware.org/?probe=772c3204b4) | Sep 10, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [4f0a6ec78c](https://linux-hardware.org/?probe=4f0a6ec78c) | Sep 10, 2023 |
| Positivo      | C464F                       | Notebook    | [e8154e06d4](https://linux-hardware.org/?probe=e8154e06d4) | Sep 10, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [6dc842bbb4](https://linux-hardware.org/?probe=6dc842bbb4) | Sep 10, 2023 |
| Daten Tecn... | DA75PRO                     | Desktop     | [343cbab6e9](https://linux-hardware.org/?probe=343cbab6e9) | Sep 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [bc06d42fa2](https://linux-hardware.org/?probe=bc06d42fa2) | Sep 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [2f9aef143e](https://linux-hardware.org/?probe=2f9aef143e) | Sep 10, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8e988d79b7](https://linux-hardware.org/?probe=8e988d79b7) | Sep 09, 2023 |
| Intel         | H61                         | Desktop     | [f8eaac6637](https://linux-hardware.org/?probe=f8eaac6637) | Sep 09, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [0916725ace](https://linux-hardware.org/?probe=0916725ace) | Sep 09, 2023 |
| ASUSTek       | PRIME H310M-E/BR            | Desktop     | [87971ac772](https://linux-hardware.org/?probe=87971ac772) | Sep 09, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [8723b09478](https://linux-hardware.org/?probe=8723b09478) | Sep 09, 2023 |
| Dell          | G15 5511                    | Notebook    | [c382a29576](https://linux-hardware.org/?probe=c382a29576) | Sep 09, 2023 |
| Lenovo        | V720-14 80Y1                | Notebook    | [ec869beffd](https://linux-hardware.org/?probe=ec869beffd) | Sep 09, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [7403fec062](https://linux-hardware.org/?probe=7403fec062) | Sep 09, 2023 |
| MSI           | MAG B560M BAZOOKA           | Desktop     | [c3ba2033e2](https://linux-hardware.org/?probe=c3ba2033e2) | Sep 09, 2023 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [9d0bacfabd](https://linux-hardware.org/?probe=9d0bacfabd) | Sep 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [2b74633199](https://linux-hardware.org/?probe=2b74633199) | Sep 09, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [3bb12f9fa5](https://linux-hardware.org/?probe=3bb12f9fa5) | Sep 09, 2023 |
| Standard      | HBT-M Series                | All in one  | [59b9b6af6d](https://linux-hardware.org/?probe=59b9b6af6d) | Sep 09, 2023 |
| Standard      | HBT-M Series                | All in one  | [08e2968c66](https://linux-hardware.org/?probe=08e2968c66) | Sep 09, 2023 |
| Dell          | Latitude 7390               | Notebook    | [3644f0b002](https://linux-hardware.org/?probe=3644f0b002) | Sep 08, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [0c30921512](https://linux-hardware.org/?probe=0c30921512) | Sep 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [480df18bcb](https://linux-hardware.org/?probe=480df18bcb) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [7c5a19bc69](https://linux-hardware.org/?probe=7c5a19bc69) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [4695b758c9](https://linux-hardware.org/?probe=4695b758c9) | Sep 08, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [e8a4fb3aea](https://linux-hardware.org/?probe=e8a4fb3aea) | Sep 08, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [6dbe579385](https://linux-hardware.org/?probe=6dbe579385) | Sep 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e8fe3531c7](https://linux-hardware.org/?probe=e8fe3531c7) | Sep 08, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [d35d89339d](https://linux-hardware.org/?probe=d35d89339d) | Sep 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [edf1e3f8c4](https://linux-hardware.org/?probe=edf1e3f8c4) | Sep 08, 2023 |
| ECS           | BSWI-D2                     | Desktop     | [0bf71b9f12](https://linux-hardware.org/?probe=0bf71b9f12) | Sep 08, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [8fc5475fd3](https://linux-hardware.org/?probe=8fc5475fd3) | Sep 08, 2023 |
| Samsung       | 730QED                      | Convertible | [67039750cc](https://linux-hardware.org/?probe=67039750cc) | Sep 08, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [b05fdf4d62](https://linux-hardware.org/?probe=b05fdf4d62) | Sep 08, 2023 |
| Intel         | H61                         | Desktop     | [929cfae9af](https://linux-hardware.org/?probe=929cfae9af) | Sep 08, 2023 |
| Digibras      | NH4CU03                     | Notebook    | [0d0d0bf884](https://linux-hardware.org/?probe=0d0d0bf884) | Sep 07, 2023 |
| HP            | G42                         | Notebook    | [b33a0d0bf6](https://linux-hardware.org/?probe=b33a0d0bf6) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [89772ef854](https://linux-hardware.org/?probe=89772ef854) | Sep 07, 2023 |
| ASUSTek       | N56VZ                       | Notebook    | [37b42fff22](https://linux-hardware.org/?probe=37b42fff22) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c9ea6ff204](https://linux-hardware.org/?probe=c9ea6ff204) | Sep 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [584a31e54e](https://linux-hardware.org/?probe=584a31e54e) | Sep 07, 2023 |
| Intel         | HM570                       | Desktop     | [ea25bde02e](https://linux-hardware.org/?probe=ea25bde02e) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2b734c4a23](https://linux-hardware.org/?probe=2b734c4a23) | Sep 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [2eae1044fc](https://linux-hardware.org/?probe=2eae1044fc) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [d98f5a5a06](https://linux-hardware.org/?probe=d98f5a5a06) | Sep 07, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [35b6b3a9dd](https://linux-hardware.org/?probe=35b6b3a9dd) | Sep 07, 2023 |
| Gigabyte      | G31M-S2C                    | Desktop     | [a7fb813c79](https://linux-hardware.org/?probe=a7fb813c79) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [4e54155977](https://linux-hardware.org/?probe=4e54155977) | Sep 07, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [8274cbca33](https://linux-hardware.org/?probe=8274cbca33) | Sep 07, 2023 |
| Acer          | AO722                       | Notebook    | [ae49a1e9c0](https://linux-hardware.org/?probe=ae49a1e9c0) | Sep 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [db4ba96400](https://linux-hardware.org/?probe=db4ba96400) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e207539e68](https://linux-hardware.org/?probe=e207539e68) | Sep 07, 2023 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [a4624a95da](https://linux-hardware.org/?probe=a4624a95da) | Sep 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [da21e863a4](https://linux-hardware.org/?probe=da21e863a4) | Sep 07, 2023 |
| Multilaser    | PC31X                       | Notebook    | [96d451c4a5](https://linux-hardware.org/?probe=96d451c4a5) | Sep 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [7410c2416c](https://linux-hardware.org/?probe=7410c2416c) | Sep 07, 2023 |
| Alienware     | m15 R7                      | Notebook    | [9e6b80bbf2](https://linux-hardware.org/?probe=9e6b80bbf2) | Sep 07, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [0be77d9ece](https://linux-hardware.org/?probe=0be77d9ece) | Sep 07, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f8453df937](https://linux-hardware.org/?probe=f8453df937) | Sep 07, 2023 |
| Toshiba       | STI 006998G                 | Desktop     | [d34aadcc92](https://linux-hardware.org/?probe=d34aadcc92) | Sep 07, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [a1537a06ee](https://linux-hardware.org/?probe=a1537a06ee) | Sep 07, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [03726302da](https://linux-hardware.org/?probe=03726302da) | Sep 07, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [ef99cba7a5](https://linux-hardware.org/?probe=ef99cba7a5) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [29f1d7759a](https://linux-hardware.org/?probe=29f1d7759a) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [344a00d524](https://linux-hardware.org/?probe=344a00d524) | Sep 06, 2023 |
| Standard      | MB45II/MB45IN               | Notebook    | [1e46c6aa81](https://linux-hardware.org/?probe=1e46c6aa81) | Sep 06, 2023 |
| ASUSTek       | P8H77-M                     | Desktop     | [ebc8d3e851](https://linux-hardware.org/?probe=ebc8d3e851) | Sep 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [5d22a61587](https://linux-hardware.org/?probe=5d22a61587) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [ba05ae3ca2](https://linux-hardware.org/?probe=ba05ae3ca2) | Sep 06, 2023 |
| HP            | 3047h                       | Desktop     | [9b6ecf8471](https://linux-hardware.org/?probe=9b6ecf8471) | Sep 06, 2023 |
| HP            | 3047h                       | Desktop     | [51ba95dc5a](https://linux-hardware.org/?probe=51ba95dc5a) | Sep 06, 2023 |
| Lenovo        | Yoga 520-14IKB 80YM         | Convertible | [a7e1067ce7](https://linux-hardware.org/?probe=a7e1067ce7) | Sep 06, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [299a459ec5](https://linux-hardware.org/?probe=299a459ec5) | Sep 06, 2023 |
| Lenovo        | IdeaPad Z360                | Notebook    | [1bb5ebf339](https://linux-hardware.org/?probe=1bb5ebf339) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [0deab6fc8b](https://linux-hardware.org/?probe=0deab6fc8b) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [aa37593b87](https://linux-hardware.org/?probe=aa37593b87) | Sep 06, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [230cd8c32e](https://linux-hardware.org/?probe=230cd8c32e) | Sep 06, 2023 |
| Dell          | G3 3500                     | Notebook    | [5da26d2241](https://linux-hardware.org/?probe=5da26d2241) | Sep 06, 2023 |
| Biostar       | G31M+                       | Desktop     | [24eb0eb2db](https://linux-hardware.org/?probe=24eb0eb2db) | Sep 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [da71ec43ea](https://linux-hardware.org/?probe=da71ec43ea) | Sep 06, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80UH      | Notebook    | [479d5ea49e](https://linux-hardware.org/?probe=479d5ea49e) | Sep 06, 2023 |
| HP            | 0B54h D                     | Desktop     | [978ff127e9](https://linux-hardware.org/?probe=978ff127e9) | Sep 05, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [4a055a6f9c](https://linux-hardware.org/?probe=4a055a6f9c) | Sep 05, 2023 |
| Biostar       | A320MH                      | Desktop     | [1907707516](https://linux-hardware.org/?probe=1907707516) | Sep 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [a64157168e](https://linux-hardware.org/?probe=a64157168e) | Sep 05, 2023 |
| Biostar       | A320MH                      | Desktop     | [f13f5f9fe9](https://linux-hardware.org/?probe=f13f5f9fe9) | Sep 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [190675e9f1](https://linux-hardware.org/?probe=190675e9f1) | Sep 05, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [5bec99a137](https://linux-hardware.org/?probe=5bec99a137) | Sep 05, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [dc22012520](https://linux-hardware.org/?probe=dc22012520) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [0576ca20ab](https://linux-hardware.org/?probe=0576ca20ab) | Sep 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [0841c5e196](https://linux-hardware.org/?probe=0841c5e196) | Sep 05, 2023 |
| Dell          | G15 5530                    | Notebook    | [91dcc569ee](https://linux-hardware.org/?probe=91dcc569ee) | Sep 05, 2023 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [710c22af52](https://linux-hardware.org/?probe=710c22af52) | Sep 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a658addd87](https://linux-hardware.org/?probe=a658addd87) | Sep 05, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c02fef3ca2](https://linux-hardware.org/?probe=c02fef3ca2) | Sep 05, 2023 |
| ASRock        | E35LM1                      | Desktop     | [663d9ac1e1](https://linux-hardware.org/?probe=663d9ac1e1) | Sep 04, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [bcd06888e4](https://linux-hardware.org/?probe=bcd06888e4) | Sep 04, 2023 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [f2ac0f8904](https://linux-hardware.org/?probe=f2ac0f8904) | Sep 04, 2023 |
| ASRock        | A55M-HVS                    | Desktop     | [eaa27d1ba6](https://linux-hardware.org/?probe=eaa27d1ba6) | Sep 04, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [5cb02e099f](https://linux-hardware.org/?probe=5cb02e099f) | Sep 04, 2023 |
| ASRock        | N68-S3 FX                   | Desktop     | [2b503dd2b6](https://linux-hardware.org/?probe=2b503dd2b6) | Sep 04, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9b43cf14a3](https://linux-hardware.org/?probe=9b43cf14a3) | Sep 04, 2023 |
| Dell          | Inspiron 3576               | Notebook    | [5139d104cc](https://linux-hardware.org/?probe=5139d104cc) | Sep 04, 2023 |
| Acer          | Aspire A315-56              | Notebook    | [1f090fc4fd](https://linux-hardware.org/?probe=1f090fc4fd) | Sep 04, 2023 |
| Dell          | Inspiron 7580               | Notebook    | [b021fe57a6](https://linux-hardware.org/?probe=b021fe57a6) | Sep 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [8253da4d01](https://linux-hardware.org/?probe=8253da4d01) | Sep 04, 2023 |
| Lenovo        | IdeaPad S400 Touch VIUS3    | Notebook    | [d2ac233994](https://linux-hardware.org/?probe=d2ac233994) | Sep 04, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6046f9d74b](https://linux-hardware.org/?probe=6046f9d74b) | Sep 04, 2023 |
| Compaq        | 430                         | Notebook    | [ac9fb09e14](https://linux-hardware.org/?probe=ac9fb09e14) | Sep 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [aeebc4664f](https://linux-hardware.org/?probe=aeebc4664f) | Sep 04, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8d52d37e1e](https://linux-hardware.org/?probe=8d52d37e1e) | Sep 04, 2023 |
| HP            | ENVY 14 SPECTRE             | Notebook    | [1f0a26899c](https://linux-hardware.org/?probe=1f0a26899c) | Sep 04, 2023 |
| HP            | 1000                        | Notebook    | [59cd8d1250](https://linux-hardware.org/?probe=59cd8d1250) | Sep 04, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [908a64b09a](https://linux-hardware.org/?probe=908a64b09a) | Sep 04, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1c048ac799](https://linux-hardware.org/?probe=1c048ac799) | Sep 04, 2023 |
| Dell          | 0CU409                      | Desktop     | [ca461ddc28](https://linux-hardware.org/?probe=ca461ddc28) | Sep 04, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [8d171f78bf](https://linux-hardware.org/?probe=8d171f78bf) | Sep 04, 2023 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [7e0c89dfdb](https://linux-hardware.org/?probe=7e0c89dfdb) | Sep 04, 2023 |
| Samsung       | RV415                       | Notebook    | [dc6aa3101f](https://linux-hardware.org/?probe=dc6aa3101f) | Sep 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b8a2b22a6c](https://linux-hardware.org/?probe=b8a2b22a6c) | Sep 03, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [522a10f139](https://linux-hardware.org/?probe=522a10f139) | Sep 03, 2023 |
| HP            | Folio 13                    | Notebook    | [d5844cc9e8](https://linux-hardware.org/?probe=d5844cc9e8) | Sep 03, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [f0b466e572](https://linux-hardware.org/?probe=f0b466e572) | Sep 03, 2023 |
| Lenovo        | ThinkPad E490 20N9001RBR    | Notebook    | [b9de538f7e](https://linux-hardware.org/?probe=b9de538f7e) | Sep 03, 2023 |
| Intel         | H61                         | Desktop     | [209644dbc2](https://linux-hardware.org/?probe=209644dbc2) | Sep 03, 2023 |
| Dell          | Inspiron 5537               | Notebook    | [3aa237c8c6](https://linux-hardware.org/?probe=3aa237c8c6) | Sep 03, 2023 |
| LG Electro... | 22V280 FAB1                 | All in one  | [f02e3011d3](https://linux-hardware.org/?probe=f02e3011d3) | Sep 03, 2023 |
| AMD           | A88K                        | Desktop     | [d58c29d4ad](https://linux-hardware.org/?probe=d58c29d4ad) | Sep 03, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e58d4f8405](https://linux-hardware.org/?probe=e58d4f8405) | Sep 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [2b257d37b3](https://linux-hardware.org/?probe=2b257d37b3) | Sep 03, 2023 |
| MEGA          | G41T-M7 LGT                 | Desktop     | [8d645686ff](https://linux-hardware.org/?probe=8d645686ff) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [c93a88de93](https://linux-hardware.org/?probe=c93a88de93) | Sep 02, 2023 |
| HP            | 3646h                       | Desktop     | [cd226fee15](https://linux-hardware.org/?probe=cd226fee15) | Sep 02, 2023 |
| Multilaser    | UM125                       | Mini pc     | [a43bdb65de](https://linux-hardware.org/?probe=a43bdb65de) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [76b9023610](https://linux-hardware.org/?probe=76b9023610) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f5f8737b58](https://linux-hardware.org/?probe=f5f8737b58) | Sep 02, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [df01a7432c](https://linux-hardware.org/?probe=df01a7432c) | Sep 02, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [5ee8cbf433](https://linux-hardware.org/?probe=5ee8cbf433) | Sep 02, 2023 |
| Samsung       | 530XBB                      | Notebook    | [30365848c4](https://linux-hardware.org/?probe=30365848c4) | Sep 02, 2023 |
| Dell          | Latitude 7400               | Notebook    | [c98434cc21](https://linux-hardware.org/?probe=c98434cc21) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2a9211117f](https://linux-hardware.org/?probe=2a9211117f) | Sep 02, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [5897684d9e](https://linux-hardware.org/?probe=5897684d9e) | Sep 02, 2023 |
| Samsung       | 500R5L/501R5L/500R5P        | Notebook    | [681c0ca0f9](https://linux-hardware.org/?probe=681c0ca0f9) | Sep 02, 2023 |
| Dell          | Latitude 2120               | Notebook    | [65eed61467](https://linux-hardware.org/?probe=65eed61467) | Sep 02, 2023 |
| Dell          | Latitude 3410               | Notebook    | [695e65a1f0](https://linux-hardware.org/?probe=695e65a1f0) | Sep 02, 2023 |
| Samsung       | 370E4K                      | Notebook    | [19f41e00da](https://linux-hardware.org/?probe=19f41e00da) | Sep 02, 2023 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [1c1b1adcc9](https://linux-hardware.org/?probe=1c1b1adcc9) | Sep 02, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [6953a7b5f2](https://linux-hardware.org/?probe=6953a7b5f2) | Sep 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [87e1726495](https://linux-hardware.org/?probe=87e1726495) | Sep 01, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [e73e853358](https://linux-hardware.org/?probe=e73e853358) | Sep 01, 2023 |
| Positivo      | POS-EIH610EX 11189814       | Desktop     | [e6a9006a72](https://linux-hardware.org/?probe=e6a9006a72) | Sep 01, 2023 |
| Dell          | 0XT4CY A01                  | Desktop     | [26665d2c19](https://linux-hardware.org/?probe=26665d2c19) | Sep 01, 2023 |
| Samsung       | 550XED                      | Notebook    | [ba2fe18193](https://linux-hardware.org/?probe=ba2fe18193) | Sep 01, 2023 |
| Dell          | G15 5520                    | Notebook    | [9cfb8ce55a](https://linux-hardware.org/?probe=9cfb8ce55a) | Sep 01, 2023 |
| Positivo      | POS-EIH610EX 11189814       | Desktop     | [e222369e70](https://linux-hardware.org/?probe=e222369e70) | Sep 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1f29e90c7f](https://linux-hardware.org/?probe=1f29e90c7f) | Sep 01, 2023 |
| Intel         | X99H                        | Desktop     | [e020530bc8](https://linux-hardware.org/?probe=e020530bc8) | Sep 01, 2023 |
| Foxconn       | A6VMX 0A                    | Desktop     | [338cdb7d40](https://linux-hardware.org/?probe=338cdb7d40) | Sep 01, 2023 |
| Intel         | H110                        | Desktop     | [05970c6811](https://linux-hardware.org/?probe=05970c6811) | Sep 01, 2023 |
| Positivo      | Mobile                      | Notebook    | [3b32864073](https://linux-hardware.org/?probe=3b32864073) | Sep 01, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [77c6379594](https://linux-hardware.org/?probe=77c6379594) | Sep 01, 2023 |
| ASUSTek       | PRIME H410M-D               | Desktop     | [332e78dfba](https://linux-hardware.org/?probe=332e78dfba) | Sep 01, 2023 |
| Foxconn       | G31MXP FAB:1.1              | Desktop     | [4fc2089efc](https://linux-hardware.org/?probe=4fc2089efc) | Sep 01, 2023 |
| ASUSTek       | M4A78LT-M-LE                | Desktop     | [d3d5887ff3](https://linux-hardware.org/?probe=d3d5887ff3) | Sep 01, 2023 |
| Google        | Barla                       | Notebook    | [1beaca005d](https://linux-hardware.org/?probe=1beaca005d) | Sep 01, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [7fd4c8ad9c](https://linux-hardware.org/?probe=7fd4c8ad9c) | Sep 01, 2023 |
| HP            | 1489                        | All in one  | [c53e87bce8](https://linux-hardware.org/?probe=c53e87bce8) | Sep 01, 2023 |
| HP            | Presario CQ43               | Notebook    | [9a02828a68](https://linux-hardware.org/?probe=9a02828a68) | Sep 01, 2023 |
| AMD           | A88K                        | Desktop     | [08a455504f](https://linux-hardware.org/?probe=08a455504f) | Sep 01, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [42eb5f3ad4](https://linux-hardware.org/?probe=42eb5f3ad4) | Aug 31, 2023 |
| PCWare        | IPX1800E1                   | Desktop     | [bfe03f751b](https://linux-hardware.org/?probe=bfe03f751b) | Aug 31, 2023 |
| Intel         | H61                         | Desktop     | [d0bd2f4cfa](https://linux-hardware.org/?probe=d0bd2f4cfa) | Aug 31, 2023 |
| Intel         | B75                         | Desktop     | [d8367a0977](https://linux-hardware.org/?probe=d8367a0977) | Aug 31, 2023 |
| MSI           | H61M-P20/W8                 | Desktop     | [c35045d386](https://linux-hardware.org/?probe=c35045d386) | Aug 31, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [311af8113f](https://linux-hardware.org/?probe=311af8113f) | Aug 31, 2023 |
| Red Hat       | RHEL RHEL-9.2.0 PC          | Desktop     | [ee06e81f13](https://linux-hardware.org/?probe=ee06e81f13) | Aug 31, 2023 |
| Intel         | H55                         | Desktop     | [955198ab64](https://linux-hardware.org/?probe=955198ab64) | Aug 31, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [fd3c900751](https://linux-hardware.org/?probe=fd3c900751) | Aug 31, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [064705b919](https://linux-hardware.org/?probe=064705b919) | Aug 31, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [b9c66b93e7](https://linux-hardware.org/?probe=b9c66b93e7) | Aug 31, 2023 |
| MACHINIST     | E5-D8-MAX V1.0              | Desktop     | [339734178a](https://linux-hardware.org/?probe=339734178a) | Aug 31, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [6c5da44516](https://linux-hardware.org/?probe=6c5da44516) | Aug 31, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [9e1df9ff88](https://linux-hardware.org/?probe=9e1df9ff88) | Aug 31, 2023 |
| Megaware      | MW-NM70HD-MI 06/11/2012 ... | Desktop     | [7b8812491c](https://linux-hardware.org/?probe=7b8812491c) | Aug 31, 2023 |
| HP            | Pavilion dv4                | Notebook    | [c84d5215be](https://linux-hardware.org/?probe=c84d5215be) | Aug 30, 2023 |
| Dell          | G15 5530                    | Notebook    | [1027c8fe19](https://linux-hardware.org/?probe=1027c8fe19) | Aug 30, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [79783b33ff](https://linux-hardware.org/?probe=79783b33ff) | Aug 30, 2023 |
| Avell High... | C62 MOB                     | Notebook    | [04e247a3d3](https://linux-hardware.org/?probe=04e247a3d3) | Aug 30, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [ebcd50f639](https://linux-hardware.org/?probe=ebcd50f639) | Aug 30, 2023 |
| Itautec       | ST 4254 ST-4254 Padrao 0... | Desktop     | [fbbbe0087a](https://linux-hardware.org/?probe=fbbbe0087a) | Aug 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [9cf292357b](https://linux-hardware.org/?probe=9cf292357b) | Aug 30, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7075df2d62](https://linux-hardware.org/?probe=7075df2d62) | Aug 30, 2023 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [e3f4b109ff](https://linux-hardware.org/?probe=e3f4b109ff) | Aug 30, 2023 |
| Foxconn       | Lucknow                     | Desktop     | [eece5a84ae](https://linux-hardware.org/?probe=eece5a84ae) | Aug 30, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [500ef94276](https://linux-hardware.org/?probe=500ef94276) | Aug 29, 2023 |
| Positivo      | POS-RIB360EE 11144907       | Desktop     | [c392d83e8e](https://linux-hardware.org/?probe=c392d83e8e) | Aug 29, 2023 |
| MSI           | H61M-E22/W8                 | Desktop     | [2439d2ed95](https://linux-hardware.org/?probe=2439d2ed95) | Aug 29, 2023 |
| LG Electro... | V720                        | All in one  | [28f525b5a1](https://linux-hardware.org/?probe=28f525b5a1) | Aug 29, 2023 |
| LG Electro... | V720                        | All in one  | [7fdfb84d04](https://linux-hardware.org/?probe=7fdfb84d04) | Aug 29, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [7094317c17](https://linux-hardware.org/?probe=7094317c17) | Aug 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2a5afc6557](https://linux-hardware.org/?probe=2a5afc6557) | Aug 29, 2023 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [dcd9ab0f79](https://linux-hardware.org/?probe=dcd9ab0f79) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z470                | Notebook    | [d3c372d869](https://linux-hardware.org/?probe=d3c372d869) | Aug 29, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [a5f9c0a211](https://linux-hardware.org/?probe=a5f9c0a211) | Aug 29, 2023 |
| Sony          | VPCEA36FX                   | Notebook    | [174aefbf35](https://linux-hardware.org/?probe=174aefbf35) | Aug 29, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [fd0950b7c1](https://linux-hardware.org/?probe=fd0950b7c1) | Aug 28, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [f94a46ad17](https://linux-hardware.org/?probe=f94a46ad17) | Aug 28, 2023 |
| Unknown       | SEI Robotics SEI610         | Soc         | [9ee073735e](https://linux-hardware.org/?probe=9ee073735e) | Aug 28, 2023 |
| Intel         | H81                         | Desktop     | [9b70a28b25](https://linux-hardware.org/?probe=9b70a28b25) | Aug 28, 2023 |
| Intel         | DX79SR AAG57199-200         | Desktop     | [418a709636](https://linux-hardware.org/?probe=418a709636) | Aug 28, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [a4fe691c36](https://linux-hardware.org/?probe=a4fe691c36) | Aug 28, 2023 |
| Lenovo        | Legion 5 15IMH 82CF         | Notebook    | [4d8ac47399](https://linux-hardware.org/?probe=4d8ac47399) | Aug 28, 2023 |
| AZW           | GK mini                     | Mini pc     | [64b25422b0](https://linux-hardware.org/?probe=64b25422b0) | Aug 28, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [94f2581f9f](https://linux-hardware.org/?probe=94f2581f9f) | Aug 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [40c64b6ec2](https://linux-hardware.org/?probe=40c64b6ec2) | Aug 28, 2023 |
| Acer          | Aspire 5741Z                | Notebook    | [2127326562](https://linux-hardware.org/?probe=2127326562) | Aug 28, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [379728237a](https://linux-hardware.org/?probe=379728237a) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [30006f030a](https://linux-hardware.org/?probe=30006f030a) | Aug 28, 2023 |
| Gigabyte      | B75M-D3P                    | Desktop     | [73562af96c](https://linux-hardware.org/?probe=73562af96c) | Aug 28, 2023 |
| Acer          | Aspire 4738                 | Notebook    | [6051c9190a](https://linux-hardware.org/?probe=6051c9190a) | Aug 28, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [65408b783f](https://linux-hardware.org/?probe=65408b783f) | Aug 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [e02ef868a3](https://linux-hardware.org/?probe=e02ef868a3) | Aug 28, 2023 |
| Positivo      | C14CU51                     | Notebook    | [7fa280c987](https://linux-hardware.org/?probe=7fa280c987) | Aug 28, 2023 |
| Positivo      | POS-PQ45AU                  | Desktop     | [aba45a4f14](https://linux-hardware.org/?probe=aba45a4f14) | Aug 27, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [bf483bc8d3](https://linux-hardware.org/?probe=bf483bc8d3) | Aug 27, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [5036ce79f9](https://linux-hardware.org/?probe=5036ce79f9) | Aug 27, 2023 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [c9935dab6b](https://linux-hardware.org/?probe=c9935dab6b) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8b82375189](https://linux-hardware.org/?probe=8b82375189) | Aug 27, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [b2ecdef159](https://linux-hardware.org/?probe=b2ecdef159) | Aug 27, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [0211379a67](https://linux-hardware.org/?probe=0211379a67) | Aug 27, 2023 |
| LG Electro... | A530-T.BE76P1               | Notebook    | [6b9ae23c76](https://linux-hardware.org/?probe=6b9ae23c76) | Aug 27, 2023 |
| LG Electro... | White Tip Mountain FAB3     | All in one  | [91204c1c19](https://linux-hardware.org/?probe=91204c1c19) | Aug 27, 2023 |
| Samsung       | 300E4M/300E4S/300E4L        | Notebook    | [633ddecba0](https://linux-hardware.org/?probe=633ddecba0) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a284c141d8](https://linux-hardware.org/?probe=a284c141d8) | Aug 27, 2023 |
| Timi          | TM1701                      | Notebook    | [2a6a4225a0](https://linux-hardware.org/?probe=2a6a4225a0) | Aug 27, 2023 |
| Timi          | TM1701                      | Notebook    | [8ea7c21e18](https://linux-hardware.org/?probe=8ea7c21e18) | Aug 27, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [8ee437beac](https://linux-hardware.org/?probe=8ee437beac) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [7566a0ed19](https://linux-hardware.org/?probe=7566a0ed19) | Aug 27, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [dcb65a221f](https://linux-hardware.org/?probe=dcb65a221f) | Aug 27, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [35fede08aa](https://linux-hardware.org/?probe=35fede08aa) | Aug 26, 2023 |
| Positivo      | CHT14B                      | Notebook    | [81a8519b9e](https://linux-hardware.org/?probe=81a8519b9e) | Aug 26, 2023 |
| Lenovo        | ThinkCentre M58e 7303AZ2    | Desktop     | [2eb35196a6](https://linux-hardware.org/?probe=2eb35196a6) | Aug 26, 2023 |
| HP            | 1998                        | Desktop     | [2c6c07a7d3](https://linux-hardware.org/?probe=2c6c07a7d3) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | Notebook    | [c0957b3538](https://linux-hardware.org/?probe=c0957b3538) | Aug 26, 2023 |
| Intel         | D33217CK G76541-301         | Desktop     | [24b3b7aac4](https://linux-hardware.org/?probe=24b3b7aac4) | Aug 26, 2023 |
| Positivo      | POS-PIG41BA POSITIVO        | Desktop     | [05dc1d19de](https://linux-hardware.org/?probe=05dc1d19de) | Aug 26, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [01750cc1d8](https://linux-hardware.org/?probe=01750cc1d8) | Aug 26, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [77e9d34f16](https://linux-hardware.org/?probe=77e9d34f16) | Aug 26, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [1f47bfe737](https://linux-hardware.org/?probe=1f47bfe737) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [f0f9f25268](https://linux-hardware.org/?probe=f0f9f25268) | Aug 26, 2023 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [95aa33fc09](https://linux-hardware.org/?probe=95aa33fc09) | Aug 26, 2023 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [6fc7c35bc9](https://linux-hardware.org/?probe=6fc7c35bc9) | Aug 26, 2023 |
| Google        | Kasumi                      | Notebook    | [9af5f77257](https://linux-hardware.org/?probe=9af5f77257) | Aug 25, 2023 |
| Dell          | Latitude E6440              | Notebook    | [759a858fa1](https://linux-hardware.org/?probe=759a858fa1) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [878476c63f](https://linux-hardware.org/?probe=878476c63f) | Aug 25, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [275cd1500e](https://linux-hardware.org/?probe=275cd1500e) | Aug 25, 2023 |
| Dell          | 0T656F A01                  | Desktop     | [fe9ddfe6d0](https://linux-hardware.org/?probe=fe9ddfe6d0) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [49769c9b38](https://linux-hardware.org/?probe=49769c9b38) | Aug 25, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [e3bc104b50](https://linux-hardware.org/?probe=e3bc104b50) | Aug 25, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [decfff1e51](https://linux-hardware.org/?probe=decfff1e51) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | Notebook    | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [2e62ce7973](https://linux-hardware.org/?probe=2e62ce7973) | Aug 25, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [34e1a0c5c4](https://linux-hardware.org/?probe=34e1a0c5c4) | Aug 24, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [4d99c3a598](https://linux-hardware.org/?probe=4d99c3a598) | Aug 24, 2023 |
| HP            | 3047h                       | Desktop     | [5c415723ef](https://linux-hardware.org/?probe=5c415723ef) | Aug 24, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [09db81cde4](https://linux-hardware.org/?probe=09db81cde4) | Aug 24, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [648f667e11](https://linux-hardware.org/?probe=648f667e11) | Aug 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [a7fbf7edf2](https://linux-hardware.org/?probe=a7fbf7edf2) | Aug 24, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [744be89da4](https://linux-hardware.org/?probe=744be89da4) | Aug 24, 2023 |
| Lenovo        | ThinkServer RD450 70DC00... | Server      | [71859969f5](https://linux-hardware.org/?probe=71859969f5) | Aug 24, 2023 |
| Dell          | Inspiron 7572               | Notebook    | [84f4498af0](https://linux-hardware.org/?probe=84f4498af0) | Aug 24, 2023 |
| Unknown       | Unknown                     | Soc         | [ddc3d0b271](https://linux-hardware.org/?probe=ddc3d0b271) | Aug 24, 2023 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [0cf842e282](https://linux-hardware.org/?probe=0cf842e282) | Aug 24, 2023 |
| Gigabyte      | H310M M.2                   | Desktop     | [9b1205f50a](https://linux-hardware.org/?probe=9b1205f50a) | Aug 24, 2023 |
| Lenovo        | ThinkServer RD450 70DC00... | Server      | [cfeb45f5a1](https://linux-hardware.org/?probe=cfeb45f5a1) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460 20FMA00F00    | Notebook    | [370de86ed7](https://linux-hardware.org/?probe=370de86ed7) | Aug 24, 2023 |
| ASUSTek       | P7H55-M BR                  | Desktop     | [820b86d560](https://linux-hardware.org/?probe=820b86d560) | Aug 24, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | Notebook    | [5e5059f835](https://linux-hardware.org/?probe=5e5059f835) | Aug 23, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [fd9fa02e66](https://linux-hardware.org/?probe=fd9fa02e66) | Aug 23, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [d44597af00](https://linux-hardware.org/?probe=d44597af00) | Aug 23, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [f8990a10d8](https://linux-hardware.org/?probe=f8990a10d8) | Aug 23, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [a09e28d1d6](https://linux-hardware.org/?probe=a09e28d1d6) | Aug 23, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a5357a41b4](https://linux-hardware.org/?probe=a5357a41b4) | Aug 23, 2023 |
| Positivo      | POS-PIH110DV                | Desktop     | [75f0f78d6c](https://linux-hardware.org/?probe=75f0f78d6c) | Aug 23, 2023 |
| Dell          | 0WY45N A00                  | Desktop     | [523c93534d](https://linux-hardware.org/?probe=523c93534d) | Aug 23, 2023 |
| Acer          | Aspire A314-35              | Notebook    | [c9896d5610](https://linux-hardware.org/?probe=c9896d5610) | Aug 23, 2023 |
| Positivo      | M7X0S Bottom                | Notebook    | [f78713080f](https://linux-hardware.org/?probe=f78713080f) | Aug 23, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [38849e44bb](https://linux-hardware.org/?probe=38849e44bb) | Aug 23, 2023 |
| Positivo      | C14CU51                     | Notebook    | [b8c9fbc7b7](https://linux-hardware.org/?probe=b8c9fbc7b7) | Aug 23, 2023 |
| Samsung       | 370E4K                      | Notebook    | [074e0669c7](https://linux-hardware.org/?probe=074e0669c7) | Aug 22, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [ac09f27b9d](https://linux-hardware.org/?probe=ac09f27b9d) | Aug 22, 2023 |
| Intel         | H55                         | Desktop     | [8320e0c758](https://linux-hardware.org/?probe=8320e0c758) | Aug 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [49b4227da5](https://linux-hardware.org/?probe=49b4227da5) | Aug 22, 2023 |
| Dell          | Inspiron N4050              | Notebook    | [7d5c45785c](https://linux-hardware.org/?probe=7d5c45785c) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [82c63f13d1](https://linux-hardware.org/?probe=82c63f13d1) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [1aee954611](https://linux-hardware.org/?probe=1aee954611) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f2d55c9619](https://linux-hardware.org/?probe=f2d55c9619) | Aug 22, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [698fbb24ed](https://linux-hardware.org/?probe=698fbb24ed) | Aug 22, 2023 |
| Intel         | H81                         | Desktop     | [fe1e95123d](https://linux-hardware.org/?probe=fe1e95123d) | Aug 22, 2023 |
| Acer          | Aspire 5250                 | Notebook    | [8812e20762](https://linux-hardware.org/?probe=8812e20762) | Aug 22, 2023 |
| Dell          | 0DT021 A00                  | Server      | [8598fe0d4b](https://linux-hardware.org/?probe=8598fe0d4b) | Aug 22, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [cdef569014](https://linux-hardware.org/?probe=cdef569014) | Aug 22, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [d5350f0d1c](https://linux-hardware.org/?probe=d5350f0d1c) | Aug 22, 2023 |
| ASUSTek       | Z450UAK                     | Notebook    | [68fb2ce5ec](https://linux-hardware.org/?probe=68fb2ce5ec) | Aug 22, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [04a07b8fa6](https://linux-hardware.org/?probe=04a07b8fa6) | Aug 22, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [6a3c737df2](https://linux-hardware.org/?probe=6a3c737df2) | Aug 22, 2023 |
| Intel         | HuronRiver Platform         | Notebook    | [7cf233eb4d](https://linux-hardware.org/?probe=7cf233eb4d) | Aug 22, 2023 |
| Sony          | SVE14123CBW                 | Notebook    | [b7891b51b2](https://linux-hardware.org/?probe=b7891b51b2) | Aug 21, 2023 |
| Sony          | SVE14123CBW                 | Notebook    | [9730d7f8f5](https://linux-hardware.org/?probe=9730d7f8f5) | Aug 21, 2023 |
| TaNix         | TX3 (QZ)                    | Soc         | [d8a6683747](https://linux-hardware.org/?probe=d8a6683747) | Aug 21, 2023 |
| ASUSTek       | TUF B360M-PLUS GAMING/BR    | Desktop     | [9762e16c0e](https://linux-hardware.org/?probe=9762e16c0e) | Aug 21, 2023 |
| Acer          | Aspire 5750Z                | Notebook    | [8c15b251a7](https://linux-hardware.org/?probe=8c15b251a7) | Aug 21, 2023 |
| AMD           | Inagua CRB                  | Desktop     | [9455337239](https://linux-hardware.org/?probe=9455337239) | Aug 21, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [534e1dc3e5](https://linux-hardware.org/?probe=534e1dc3e5) | Aug 21, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [d1ee285db9](https://linux-hardware.org/?probe=d1ee285db9) | Aug 21, 2023 |
| Packard Be... | EasyNote MZ36               | Notebook    | [d628db6497](https://linux-hardware.org/?probe=d628db6497) | Aug 21, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [feeca36aa9](https://linux-hardware.org/?probe=feeca36aa9) | Aug 21, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [e2c346429e](https://linux-hardware.org/?probe=e2c346429e) | Aug 21, 2023 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [4590ebf626](https://linux-hardware.org/?probe=4590ebf626) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [930d312c36](https://linux-hardware.org/?probe=930d312c36) | Aug 21, 2023 |
| Samsung       | 270E5G/270E5U               | Notebook    | [2bc8c24081](https://linux-hardware.org/?probe=2bc8c24081) | Aug 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b86411b8b0](https://linux-hardware.org/?probe=b86411b8b0) | Aug 21, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [665dbda021](https://linux-hardware.org/?probe=665dbda021) | Aug 21, 2023 |
| Sony          | VPCEG15FB                   | Notebook    | [e3b2126509](https://linux-hardware.org/?probe=e3b2126509) | Aug 20, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [ee47d4b6a7](https://linux-hardware.org/?probe=ee47d4b6a7) | Aug 20, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [41edd1a16e](https://linux-hardware.org/?probe=41edd1a16e) | Aug 20, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [5b7f4b5a45](https://linux-hardware.org/?probe=5b7f4b5a45) | Aug 20, 2023 |
| Megaware      | MW-G31T-M7                  | Desktop     | [3bed885307](https://linux-hardware.org/?probe=3bed885307) | Aug 20, 2023 |
| Lenovo        | ThinkPad Edge 0578A66       | Notebook    | [6b3703818a](https://linux-hardware.org/?probe=6b3703818a) | Aug 20, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [03bd8885a0](https://linux-hardware.org/?probe=03bd8885a0) | Aug 20, 2023 |
| EUROCOM       | RACER 2.0                   | Notebook    | [b27f687c16](https://linux-hardware.org/?probe=b27f687c16) | Aug 20, 2023 |
| Alienware     | m15 R4                      | Notebook    | [46f36f26ff](https://linux-hardware.org/?probe=46f36f26ff) | Aug 20, 2023 |
| Bananapi      | BPI-M5                      | Soc         | [0bd2202791](https://linux-hardware.org/?probe=0bd2202791) | Aug 19, 2023 |
| Apple         | MacBookPro4,1               | Notebook    | [1c57edc329](https://linux-hardware.org/?probe=1c57edc329) | Aug 19, 2023 |
| Megaware      | MW-G31T-M7                  | Desktop     | [774ca523db](https://linux-hardware.org/?probe=774ca523db) | Aug 19, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | Notebook    | [f75baa8a07](https://linux-hardware.org/?probe=f75baa8a07) | Aug 19, 2023 |
| Alienware     | m15 R4                      | Notebook    | [cf9a9e0729](https://linux-hardware.org/?probe=cf9a9e0729) | Aug 19, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [1d08f612ba](https://linux-hardware.org/?probe=1d08f612ba) | Aug 19, 2023 |
| Dell          | Inspiron 5447               | Notebook    | [07a24f8880](https://linux-hardware.org/?probe=07a24f8880) | Aug 19, 2023 |
| ASUSTek       | UX410UQK                    | Notebook    | [cf7a7946dc](https://linux-hardware.org/?probe=cf7a7946dc) | Aug 19, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [e625280525](https://linux-hardware.org/?probe=e625280525) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f44bc6c057](https://linux-hardware.org/?probe=f44bc6c057) | Aug 19, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [921d699e5d](https://linux-hardware.org/?probe=921d699e5d) | Aug 19, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [bbf0f31c1b](https://linux-hardware.org/?probe=bbf0f31c1b) | Aug 19, 2023 |
| Positivo      | CHT14B                      | Notebook    | [28106aa94b](https://linux-hardware.org/?probe=28106aa94b) | Aug 19, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [3cdfdae368](https://linux-hardware.org/?probe=3cdfdae368) | Aug 19, 2023 |
| Lenovo        | B490 377224P                | Notebook    | [0e516ea22b](https://linux-hardware.org/?probe=0e516ea22b) | Aug 19, 2023 |
| Toshiba       | IS 1422                     | Notebook    | [2ad1bbf471](https://linux-hardware.org/?probe=2ad1bbf471) | Aug 18, 2023 |
| Samsung       | 750QFG                      | Convertible | [ff0b9fb300](https://linux-hardware.org/?probe=ff0b9fb300) | Aug 18, 2023 |
| HP            | 0266                        | Desktop     | [636546711d](https://linux-hardware.org/?probe=636546711d) | Aug 18, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [58af8f5102](https://linux-hardware.org/?probe=58af8f5102) | Aug 18, 2023 |
| ECS           | A55F-M4                     | Desktop     | [93a5944754](https://linux-hardware.org/?probe=93a5944754) | Aug 18, 2023 |
| Acer          | Aspire E1-421               | Notebook    | [bab5968f80](https://linux-hardware.org/?probe=bab5968f80) | Aug 18, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [ae37d9f640](https://linux-hardware.org/?probe=ae37d9f640) | Aug 18, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [cce6cb2878](https://linux-hardware.org/?probe=cce6cb2878) | Aug 18, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [04ebdc3ec0](https://linux-hardware.org/?probe=04ebdc3ec0) | Aug 18, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [55b9d87888](https://linux-hardware.org/?probe=55b9d87888) | Aug 18, 2023 |
| MSI           | X470 GAMING M7 AC           | Desktop     | [92f8391f8f](https://linux-hardware.org/?probe=92f8391f8f) | Aug 18, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [024d9028bb](https://linux-hardware.org/?probe=024d9028bb) | Aug 18, 2023 |
| ASRock        | H61M-HG4                    | Desktop     | [6fbc46fea9](https://linux-hardware.org/?probe=6fbc46fea9) | Aug 17, 2023 |
| Dell          | G3 3579                     | Notebook    | [567acf505b](https://linux-hardware.org/?probe=567acf505b) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | Desktop     | [1aeba3a6ec](https://linux-hardware.org/?probe=1aeba3a6ec) | Aug 17, 2023 |
| QIYIDA        | X79 (INTEL Xeon E5/Corei... | Desktop     | [b44417fa3d](https://linux-hardware.org/?probe=b44417fa3d) | Aug 17, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [1739e9ff2d](https://linux-hardware.org/?probe=1739e9ff2d) | Aug 17, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [93f7041d2f](https://linux-hardware.org/?probe=93f7041d2f) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [1f416788fa](https://linux-hardware.org/?probe=1f416788fa) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [35b8929f7f](https://linux-hardware.org/?probe=35b8929f7f) | Aug 17, 2023 |
| ASUSTek       | B150M-C/BR                  | Desktop     | [78e12f014e](https://linux-hardware.org/?probe=78e12f014e) | Aug 17, 2023 |
| Intel         | H55                         | Desktop     | [9d45836b3b](https://linux-hardware.org/?probe=9d45836b3b) | Aug 17, 2023 |
| Daten Tecn... | DV3N-4                      | Notebook    | [7a95cb94da](https://linux-hardware.org/?probe=7a95cb94da) | Aug 17, 2023 |
| ASRock        | A320M-HD R4.0               | Desktop     | [f67dd298b1](https://linux-hardware.org/?probe=f67dd298b1) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [cf9cfddfa5](https://linux-hardware.org/?probe=cf9cfddfa5) | Aug 16, 2023 |
| Acer          | Aspire A315-33              | Notebook    | [a1db467e0a](https://linux-hardware.org/?probe=a1db467e0a) | Aug 16, 2023 |
| Acer          | Aspire 5050                 | Notebook    | [63329f0ff6](https://linux-hardware.org/?probe=63329f0ff6) | Aug 16, 2023 |
| Intel         | MAHOBAY                     | Desktop     | [6c3b1a6ddd](https://linux-hardware.org/?probe=6c3b1a6ddd) | Aug 16, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [ec4afb1917](https://linux-hardware.org/?probe=ec4afb1917) | Aug 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [8733f22b33](https://linux-hardware.org/?probe=8733f22b33) | Aug 16, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [d7ec063f46](https://linux-hardware.org/?probe=d7ec063f46) | Aug 16, 2023 |
| PCWare        | IPMH110G                    | Desktop     | [c07caba6a9](https://linux-hardware.org/?probe=c07caba6a9) | Aug 16, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [a6ad62b671](https://linux-hardware.org/?probe=a6ad62b671) | Aug 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f88687d2f0](https://linux-hardware.org/?probe=f88687d2f0) | Aug 15, 2023 |
| Dell          | Vostro 3501                 | Notebook    | [c36d4d9de0](https://linux-hardware.org/?probe=c36d4d9de0) | Aug 15, 2023 |
| Positivo      | POS-RIQ470EN 11190998       | Desktop     | [1eec60309a](https://linux-hardware.org/?probe=1eec60309a) | Aug 15, 2023 |
| HP            | 3047h                       | Desktop     | [b136128b47](https://linux-hardware.org/?probe=b136128b47) | Aug 15, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5e5606074a](https://linux-hardware.org/?probe=5e5606074a) | Aug 15, 2023 |
| Multilaser    | PC13X                       | Notebook    | [d79767b027](https://linux-hardware.org/?probe=d79767b027) | Aug 15, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [11dafc79e8](https://linux-hardware.org/?probe=11dafc79e8) | Aug 15, 2023 |
| Topstar       | Cantiga & ICH9M Chipset     | Notebook    | [5102056c71](https://linux-hardware.org/?probe=5102056c71) | Aug 15, 2023 |
| Dell          | Latitude E6530              | Notebook    | [9cbe752127](https://linux-hardware.org/?probe=9cbe752127) | Aug 15, 2023 |
| Intel         | B75A                        | Desktop     | [c081fb2ca8](https://linux-hardware.org/?probe=c081fb2ca8) | Aug 15, 2023 |
| Positivo      | S14CT01                     | Notebook    | [e865565207](https://linux-hardware.org/?probe=e865565207) | Aug 15, 2023 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [f6892c6532](https://linux-hardware.org/?probe=f6892c6532) | Aug 15, 2023 |
| HP            | 3047h                       | Desktop     | [4c2aba9453](https://linux-hardware.org/?probe=4c2aba9453) | Aug 14, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [da3036b8e3](https://linux-hardware.org/?probe=da3036b8e3) | Aug 14, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8803256d2e](https://linux-hardware.org/?probe=8803256d2e) | Aug 14, 2023 |
| ASUSTek       | H110M-C/BR                  | Desktop     | [e6da28e1fb](https://linux-hardware.org/?probe=e6da28e1fb) | Aug 14, 2023 |
| Positivo      | N1250                       | Notebook    | [8c1d1f89f7](https://linux-hardware.org/?probe=8c1d1f89f7) | Aug 14, 2023 |
| Positivo      | N1250                       | Notebook    | [17ce4f01a7](https://linux-hardware.org/?probe=17ce4f01a7) | Aug 14, 2023 |
| Positivo      | Mobile                      | Notebook    | [4111fa6520](https://linux-hardware.org/?probe=4111fa6520) | Aug 14, 2023 |
| Lenovo        | ThinkCentre Edge71 1577K... | Desktop     | [8127e491dc](https://linux-hardware.org/?probe=8127e491dc) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c342e06960](https://linux-hardware.org/?probe=c342e06960) | Aug 14, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [495c01f301](https://linux-hardware.org/?probe=495c01f301) | Aug 14, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1543      | 10.49%  |
| Ubuntu 18.04       | 1041      | 7.08%   |
| Ubuntu 22.04       | 640       | 4.35%   |
| OpenMandriva 4.2   | 344       | 2.34%   |
| Pop!_OS 20.04      | 319       | 2.17%   |
| Linux Mint 20      | 315       | 2.14%   |
| OpenMandriva 4.3   | 300       | 2.04%   |
| Linux Mint 19.3    | 289       | 1.97%   |
| Pop!_OS 22.04      | 275       | 1.87%   |
| Linux Mint 19.1    | 235       | 1.6%    |
| Manjaro            | 231       | 1.57%   |
| Linux Mint 20.3    | 231       | 1.57%   |
| Zorin 16           | 230       | 1.56%   |
| Ubuntu 19.04       | 218       | 1.48%   |
| KDE neon 20.04     | 215       | 1.46%   |
| Linux Mint 20.1    | 213       | 1.45%   |
| Debian 11          | 201       | 1.37%   |
| Fedora 38          | 197       | 1.34%   |
| Arch Rolling       | 196       | 1.33%   |
| Arch               | 189       | 1.29%   |
| Linux Mint 20.2    | 185       | 1.26%   |
| Linux Mint 21.1    | 176       | 1.2%    |
| Ubuntu 19.10       | 173       | 1.18%   |
| Debian 10          | 155       | 1.05%   |
| Zorin 15           | 152       | 1.03%   |
| OpenMandriva 23.01 | 133       | 0.9%    |
| Pop!_OS 21.04      | 127       | 0.86%   |
| Pop!_OS 20.10      | 127       | 0.86%   |
| OpenMandriva 23.03 | 125       | 0.85%   |
| Fedora 37          | 124       | 0.84%   |
| Fedora 34          | 120       | 0.82%   |
| Fedora 36          | 119       | 0.81%   |
| Xubuntu 20.04      | 118       | 0.8%    |
| Fedora 32          | 111       | 0.75%   |
| Pop!_OS 21.10      | 110       | 0.75%   |
| Fedora 35          | 110       | 0.75%   |
| Linux Mint 21      | 109       | 0.74%   |
| OpenMandriva 23.08 | 107       | 0.73%   |
| Fedora 33          | 105       | 0.71%   |
| Linux Mint 19.2    | 104       | 0.71%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 4002      | 28.63%  |
| Linux Mint    | 1889      | 13.51%  |
| Endless       | 1071      | 7.66%   |
| OpenMandriva  | 1050      | 7.51%   |
| Pop!_OS       | 923       | 6.6%    |
| Fedora        | 896       | 6.41%   |
| Debian        | 526       | 3.76%   |
| Manjaro       | 420       | 3%      |
| Zorin         | 391       | 2.8%    |
| Arch          | 372       | 2.66%   |
| KDE neon      | 285       | 2.04%   |
| Xubuntu       | 245       | 1.75%   |
| Kubuntu       | 228       | 1.63%   |
| openSUSE      | 153       | 1.09%   |
| Ubuntu MATE   | 143       | 1.02%   |
| ROSA          | 136       | 0.97%   |
| Lubuntu       | 115       | 0.82%   |
| Elementary    | 106       | 0.76%   |
| Ubuntu Unity  | 90        | 0.64%   |
| ArcoLinux     | 85        | 0.61%   |
| LMDE          | 80        | 0.57%   |
| Kali          | 74        | 0.53%   |
| BigLinux      | 52        | 0.37%   |
| Deepin        | 47        | 0.34%   |
| Ubuntu Budgie | 46        | 0.33%   |
| LinuxFX       | 40        | 0.29%   |
| Clear Linux   | 38        | 0.27%   |
| CentOS        | 33        | 0.24%   |
| BlackPanther  | 30        | 0.21%   |
| EndeavourOS   | 28        | 0.2%    |
| SteamOS       | 22        | 0.16%   |
| Gentoo        | 22        | 0.16%   |
| Nobara        | 20        | 0.14%   |
| Garuda Linux  | 18        | 0.13%   |
| Parrot        | 17        | 0.12%   |
| MX            | 16        | 0.11%   |
| Peppermint    | 15        | 0.11%   |
| Solus         | 13        | 0.09%   |
| Linux Lite    | 13        | 0.09%   |
| UbuntuDDE     | 12        | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 710       | 4.47%   |
| 5.10.14-desktop-1omv4002 | 333       | 2.1%    |
| 5.8.0-14-generic         | 318       | 2%      |
| 5.16.7-desktop-1omv4003  | 280       | 1.76%   |
| 4.15.0-46-generic        | 156       | 0.98%   |
| 5.3.0-28-generic         | 146       | 0.92%   |
| 5.4.0-48-generic         | 138       | 0.87%   |
| 5.4.0-19-generic         | 138       | 0.87%   |
| 6.2.6-desktop-1omv2390   | 123       | 0.77%   |
| 6.1.1-desktop-1omv2290   | 123       | 0.77%   |
| 5.4.0-7634-generic       | 123       | 0.77%   |
| 5.15.0-56-generic        | 120       | 0.76%   |
| 5.11.0-35-generic        | 113       | 0.71%   |
| 5.4.0-58-generic         | 111       | 0.7%    |
| 5.4.0-40-generic         | 111       | 0.7%    |
| 5.4.0-26-generic         | 106       | 0.67%   |
| 5.4.0-52-generic         | 101       | 0.64%   |
| 4.18.0-15-generic        | 97        | 0.61%   |
| 5.4.0-47-generic         | 96        | 0.6%    |
| 5.3.0-40-generic         | 89        | 0.56%   |
| 6.4.11-desktop-1omv2390  | 81        | 0.51%   |
| 5.11.0-7620-generic      | 78        | 0.49%   |
| 5.0.0-32-generic         | 78        | 0.49%   |
| 5.3.0-46-generic         | 77        | 0.48%   |
| 5.0.0-37-generic         | 72        | 0.45%   |
| 4.15.0-20-generic        | 72        | 0.45%   |
| 6.2.6-76060206-generic   | 71        | 0.45%   |
| 5.4.0-70-generic         | 71        | 0.45%   |
| 5.15.0-52-generic        | 69        | 0.43%   |
| 5.15.0-47-generic        | 69        | 0.43%   |
| 5.4.0-91-generic         | 68        | 0.43%   |
| 5.4.0-72-generic         | 68        | 0.43%   |
| 5.15.0-46-generic        | 68        | 0.43%   |
| 5.4.0-80-generic         | 63        | 0.4%    |
| 5.3.0-23-generic         | 63        | 0.4%    |
| 5.4.0-29-generic         | 62        | 0.39%   |
| 4.18.0-16-generic        | 62        | 0.39%   |
| 5.4.0-65-generic         | 61        | 0.38%   |
| 5.4.0-37-generic         | 61        | 0.38%   |
| 5.15.0-58-generic        | 61        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 3061      | 20.32%  |
| 5.15.0  | 1073      | 7.12%   |
| 4.15.0  | 954       | 6.33%   |
| 5.8.0   | 902       | 5.99%   |
| 5.3.0   | 799       | 5.3%    |
| 5.11.0  | 721       | 4.79%   |
| 5.0.0   | 566       | 3.76%   |
| 5.13.0  | 472       | 3.13%   |
| 4.18.0  | 417       | 2.77%   |
| 5.19.0  | 369       | 2.45%   |
| 5.10.14 | 335       | 2.22%   |
| 5.16.7  | 280       | 1.86%   |
| 5.10.0  | 263       | 1.75%   |
| 6.2.0   | 217       | 1.44%   |
| 6.2.6   | 200       | 1.33%   |
| 4.19.0  | 184       | 1.22%   |
| 6.1.1   | 133       | 0.88%   |
| 6.1.0   | 103       | 0.68%   |
| 6.4.11  | 98        | 0.65%   |
| 5.17.5  | 59        | 0.39%   |
| 6.0.12  | 48        | 0.32%   |
| 4.4.0   | 48        | 0.32%   |
| 5.7.9   | 47        | 0.31%   |
| 5.14.0  | 42        | 0.28%   |
| 4.9.0   | 42        | 0.28%   |
| 5.16.11 | 41        | 0.27%   |
| 6.4.8   | 37        | 0.25%   |
| 6.4.6   | 36        | 0.24%   |
| 6.5.5   | 34        | 0.23%   |
| 6.2.9   | 31        | 0.21%   |
| 5.15.5  | 31        | 0.21%   |
| 5.7.0   | 30        | 0.2%    |
| 5.15.15 | 30        | 0.2%    |
| 5.9.16  | 28        | 0.19%   |
| 5.16.13 | 28        | 0.19%   |
| 5.14.21 | 28        | 0.19%   |
| 5.6.19  | 27        | 0.18%   |
| 4.9.60  | 27        | 0.18%   |
| 6.0.0   | 25        | 0.17%   |
| 5.3.18  | 25        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3187      | 21.45%  |
| 5.15    | 1357      | 9.13%   |
| 5.8     | 1015      | 6.83%   |
| 4.15    | 954       | 6.42%   |
| 5.3     | 870       | 5.85%   |
| 5.11    | 819       | 5.51%   |
| 5.10    | 794       | 5.34%   |
| 5.0     | 608       | 4.09%   |
| 6.2     | 582       | 3.92%   |
| 5.13    | 565       | 3.8%    |
| 5.16    | 471       | 3.17%   |
| 5.19    | 470       | 3.16%   |
| 4.18    | 450       | 3.03%   |
| 6.1     | 430       | 2.89%   |
| 6.4     | 285       | 1.92%   |
| 4.19    | 220       | 1.48%   |
| 6.0     | 198       | 1.33%   |
| 5.7     | 172       | 1.16%   |
| 5.17    | 156       | 1.05%   |
| 5.14    | 147       | 0.99%   |
| 5.18    | 139       | 0.94%   |
| 6.5     | 133       | 0.89%   |
| 5.6     | 128       | 0.86%   |
| 6.3     | 121       | 0.81%   |
| 5.12    | 113       | 0.76%   |
| 5.9     | 111       | 0.75%   |
| 4.9     | 110       | 0.74%   |
| 4.4     | 54        | 0.36%   |
| 5.5     | 50        | 0.34%   |
| 5.1     | 39        | 0.26%   |
| 5.2     | 29        | 0.2%    |
| 3.10    | 19        | 0.13%   |
| 4.13    | 13        | 0.09%   |
| 4.1     | 12        | 0.08%   |
| 4.20    | 10        | 0.07%   |
| 4.10    | 9         | 0.06%   |
| 4.12    | 6         | 0.04%   |
| 4.14    | 5         | 0.03%   |
| 4.8     | 3         | 0.02%   |
| 4.17    | 2         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 12993     | 97.44%  |
| i686    | 306       | 2.29%   |
| aarch64 | 23        | 0.17%   |
| armv7l  | 13        | 0.1%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 6405      | 45.88%  |
| KDE5            | 1945      | 13.93%  |
| Unknown         | 1849      | 13.24%  |
| X-Cinnamon      | 1173      | 8.4%    |
| XFCE            | 944       | 6.76%   |
| MATE            | 390       | 2.79%   |
| KDE             | 312       | 2.23%   |
| Cinnamon        | 236       | 1.69%   |
| LXQt            | 131       | 0.94%   |
| Pantheon        | 95        | 0.68%   |
| Unity           | 92        | 0.66%   |
| Budgie          | 67        | 0.48%   |
| KDE4            | 66        | 0.47%   |
| Deepin          | 63        | 0.45%   |
| LXDE            | 57        | 0.41%   |
| i3              | 38        | 0.27%   |
| GNOME Flashback | 16        | 0.11%   |
| GNOME Classic   | 16        | 0.11%   |
| awesome         | 11        | 0.08%   |
| sway            | 9         | 0.06%   |
| Hyprland        | 7         | 0.05%   |
| Openbox         | 6         | 0.04%   |
| Enlightenment   | 6         | 0.04%   |
| bspwm           | 4         | 0.03%   |
| icewm           | 3         | 0.02%   |
| Endless:GNOME   | 3         | 0.02%   |
| qtile           | 2         | 0.01%   |
| xmonad          | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| Phosh:GNOME     | 1         | 0.01%   |
| Lubuntu         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| Hypr            | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| GNOME:Phosh     | 1         | 0.01%   |
| GNOME-Classic   | 1         | 0.01%   |
| fluxbox         | 1         | 0.01%   |
| DDE             | 1         | 0.01%   |
| chadwm          | 1         | 0.01%   |
| 03WindowMaker   | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 10821     | 78.84%  |
| Wayland | 1894      | 13.8%   |
| Unknown | 913       | 6.65%   |
| Tty     | 96        | 0.7%    |
| Web     | 2         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8322      | 60.12%  |
| SDDM    | 1690      | 12.21%  |
| GDM     | 1326      | 9.58%   |
| GDM3    | 1085      | 7.84%   |
| LightDM | 787       | 5.69%   |
| TDM     | 538       | 3.89%   |
| KDM     | 66        | 0.48%   |
| XDM     | 12        | 0.09%   |
| SLiM    | 8         | 0.06%   |
| LXDM    | 4         | 0.03%   |
| SLIMSKI | 2         | 0.01%   |
| MDM     | 2         | 0.01%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 9028      | 66.14%  |
| en_US       | 2512      | 18.4%   |
| Unknown     | 1706      | 12.5%   |
| C           | 206       | 1.51%   |
| en_GB       | 61        | 0.45%   |
| pt_PT       | 56        | 0.41%   |
| es_ES       | 19        | 0.14%   |
| en_CA       | 12        | 0.09%   |
| de_DE       | 7         | 0.05%   |
| fr_FR       | 6         | 0.04%   |
| POSIX       | 3         | 0.02%   |
| C.UTF8      | 3         | 0.02%   |
| pt_BRutf8   | 2         | 0.01%   |
| ja_JP       | 2         | 0.01%   |
| it_IT       | 2         | 0.01%   |
| es_CL       | 2         | 0.01%   |
| en_DK       | 2         | 0.01%   |
| en_AG       | 2         | 0.01%   |
| UTF-8       | 1         | 0.01%   |
| ru_RU       | 1         | 0.01%   |
| pt_BR~      | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| es_VE       | 1         | 0.01%   |
| es_PY       | 1         | 0.01%   |
| es_MX       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_ZA       | 1         | 0.01%   |
| en_US.UTF8  | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| en_IE.UTF8  | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| de_CH       | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 7673      | 56.13%  |
| EFI  | 5997      | 43.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 10260     | 74.73%  |
| Btrfs   | 1171      | 8.53%   |
| Overlay | 1114      | 8.11%   |
| Unknown | 707       | 5.15%   |
| Tmpfs   | 247       | 1.8%    |
| Xfs     | 112       | 0.82%   |
| Zfs     | 50        | 0.36%   |
| Ext3    | 22        | 0.16%   |
| Ext2    | 21        | 0.15%   |
| F2fs    | 19        | 0.14%   |
| Aufs    | 4         | 0.03%   |
| XXXXXXX | 1         | 0.01%   |
| Jfs     | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8650      | 63.04%  |
| GPT     | 3520      | 25.65%  |
| MBR     | 1552      | 11.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 11938     | 88.03%  |
| Yes       | 1624      | 11.97%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10053     | 74.05%  |
| Yes       | 3523      | 25.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell                   | 2155      | 16.17%  |
| ASUSTek Computer       | 1758      | 13.19%  |
| Acer                   | 1518      | 11.39%  |
| Lenovo                 | 1155      | 8.67%   |
| Gigabyte Technology    | 867       | 6.51%   |
| Positivo               | 747       | 5.6%    |
| Hewlett-Packard        | 709       | 5.32%   |
| Samsung Electronics    | 685       | 5.14%   |
| Intel                  | 513       | 3.85%   |
| ASRock                 | 440       | 3.3%    |
| Unknown                | 248       | 1.86%   |
| MSI                    | 239       | 1.79%   |
| Sony                   | 166       | 1.25%   |
| Apple                  | 149       | 1.12%   |
| LG Electronics         | 137       | 1.03%   |
| Itautec                | 123       | 0.92%   |
| PCWare                 | 122       | 0.92%   |
| Semp Toshiba           | 117       | 0.88%   |
| Biostar                | 108       | 0.81%   |
| Avell High Performance | 90        | 0.68%   |
| Pegatron               | 76        | 0.57%   |
| Digibras               | 76        | 0.57%   |
| ECS                    | 67        | 0.5%    |
| Multilaser             | 58        | 0.44%   |
| OEM                    | 56        | 0.42%   |
| Philco                 | 50        | 0.38%   |
| Compaq                 | 50        | 0.38%   |
| Positivo Bahia - VAIO  | 43        | 0.32%   |
| Huanan                 | 43        | 0.32%   |
| Toshiba                | 36        | 0.27%   |
| Megaware               | 35        | 0.26%   |
| Foxconn                | 32        | 0.24%   |
| Notebook               | 28        | 0.21%   |
| Clevo                  | 26        | 0.2%    |
| Daten Tecnologia       | 25        | 0.19%   |
| Gateway                | 23        | 0.17%   |
| Login Informatica      | 22        | 0.17%   |
| Google                 | 21        | 0.16%   |
| MACHINIST              | 20        | 0.15%   |
| Compal                 | 19        | 0.14%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Unknown                                     | 313       | 2.35%   |
| ASUS All Series                             | 153       | 1.15%   |
| Acer Nitro AN515-54                         | 138       | 1.04%   |
| Positivo Mobile                             | 129       | 0.97%   |
| Intel H61                                   | 101       | 0.76%   |
| Acer Nitro AN515-44                         | 88        | 0.66%   |
| Samsung 340XAA/350XAA/550XAA                | 73        | 0.55%   |
| Acer Aspire A315-53                         | 70        | 0.53%   |
| Dell Inspiron 5566                          | 69        | 0.52%   |
| Lenovo IdeaPad S145-15API 81V7              | 68        | 0.51%   |
| ASUS PRIME B450M-GAMING/BR                  | 66        | 0.5%    |
| Dell Inspiron 15-3567                       | 62        | 0.47%   |
| Lenovo IdeaPad 330-15IKB 81FE               | 60        | 0.45%   |
| Dell Inspiron 3583                          | 60        | 0.45%   |
| ASRock A320M-HD                             | 59        | 0.44%   |
| Lenovo IdeaPad S145-15IWL 81S9              | 57        | 0.43%   |
| Intel H55                                   | 55        | 0.41%   |
| ASUS PRIME A320M-K/BR                       | 54        | 0.41%   |
| Acer Aspire A315-34                         | 54        | 0.41%   |
| ASUS M5A78L-M LX/BR                         | 53        | 0.4%    |
| Acer Nitro AN517-51                         | 53        | 0.4%    |
| Acer Aspire A515-51                         | 53        | 0.4%    |
| Samsung 300E5M/300E5L                       | 50        | 0.38%   |
| Lenovo IdeaPad 320-15IKB 80YH               | 50        | 0.38%   |
| Semp Toshiba STI                            | 49        | 0.37%   |
| Acer Nitro AN515-43                         | 46        | 0.35%   |
| Samsung 550XDA                              | 45        | 0.34%   |
| Dell Inspiron 3442                          | 44        | 0.33%   |
| Positivo S14CT01                            | 43        | 0.32%   |
| Lenovo IdeaPad 3 15ALC6 82MF                | 42        | 0.32%   |
| HP G42                                      | 42        | 0.32%   |
| Itautec Infoway                             | 41        | 0.31%   |
| Gigabyte A320M-S2H                          | 41        | 0.31%   |
| Dell Inspiron N4050                         | 41        | 0.31%   |
| Gigabyte H61M-S1                            | 40        | 0.3%    |
| Dell Inspiron 3421                          | 40        | 0.3%    |
| Acer Nitro AN515-52                         | 39        | 0.29%   |
| ASRock B450M Steel Legend                   | 37        | 0.28%   |
| ASUS P8H61-M LX3 R2.0                       | 36        | 0.27%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 35        | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 1206      | 9.05%   |
| Acer Aspire        | 981       | 7.36%   |
| Lenovo IdeaPad     | 573       | 4.3%    |
| Acer Nitro         | 421       | 3.16%   |
| Unknown            | 313       | 2.35%   |
| Dell Vostro        | 270       | 2.03%   |
| ASUS PRIME         | 256       | 1.92%   |
| Lenovo ThinkPad    | 228       | 1.71%   |
| HP Pavilion        | 211       | 1.58%   |
| Dell Latitude      | 210       | 1.58%   |
| Dell OptiPlex      | 174       | 1.31%   |
| ASUS VivoBook      | 156       | 1.17%   |
| ASUS All           | 153       | 1.15%   |
| ASUS TUF           | 136       | 1.02%   |
| ASUS M5A78L-M      | 132       | 0.99%   |
| Positivo Mobile    | 129       | 0.97%   |
| Itautec Infoway    | 116       | 0.87%   |
| HP Compaq          | 113       | 0.85%   |
| Intel H61          | 106       | 0.8%    |
| ASUS P8H61-M       | 92        | 0.69%   |
| Samsung 340XAA     | 73        | 0.55%   |
| Lenovo ThinkCentre | 73        | 0.55%   |
| Dell XPS           | 63        | 0.47%   |
| ASUS ROG           | 62        | 0.47%   |
| ASRock A320M-HD    | 62        | 0.47%   |
| Dell G3            | 61        | 0.46%   |
| Semp Toshiba STI   | 57        | 0.43%   |
| Intel H55          | 55        | 0.41%   |
| HP ProBook         | 51        | 0.38%   |
| Samsung 300E5M     | 50        | 0.38%   |
| Samsung RV411      | 48        | 0.36%   |
| Samsung 550XDA     | 45        | 0.34%   |
| Positivo S14CT01   | 43        | 0.32%   |
| HP G42             | 42        | 0.32%   |
| Gigabyte A320M-S2H | 41        | 0.31%   |
| Gigabyte H61M-S1   | 40        | 0.3%    |
| Gigabyte B450M     | 40        | 0.3%    |
| Dell System        | 40        | 0.3%    |
| HP EliteBook       | 39        | 0.29%   |
| ASRock B450M       | 39        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 1375      | 10.32%  |
| 2012    | 1314      | 9.86%   |
| 2018    | 1242      | 9.32%   |
| 2011    | 1224      | 9.18%   |
| 2017    | 1062      | 7.97%   |
| 2013    | 998       | 7.49%   |
| 2010    | 828       | 6.21%   |
| 2016    | 819       | 6.14%   |
| 2014    | 795       | 5.96%   |
| 2020    | 764       | 5.73%   |
| 2021    | 605       | 4.54%   |
| 2009    | 562       | 4.22%   |
| 2008    | 532       | 3.99%   |
| 2015    | 480       | 3.6%    |
| 2007    | 304       | 2.28%   |
| 2022    | 188       | 1.41%   |
| 2006    | 102       | 0.77%   |
| Unknown | 60        | 0.45%   |
| 2023    | 38        | 0.29%   |
| 2005    | 26        | 0.2%    |
| 2004    | 9         | 0.07%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 7887      | 59.18%  |
| Desktop        | 5066      | 38.01%  |
| All in one     | 111       | 0.83%   |
| Convertible    | 99        | 0.74%   |
| Mini pc        | 56        | 0.42%   |
| Server         | 48        | 0.36%   |
| System on chip | 32        | 0.24%   |
| Tablet         | 25        | 0.19%   |
| Phone          | 2         | 0.02%   |
| Other          | 1         | 0.01%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 12098     | 90.1%   |
| Enabled  | 1330      | 9.9%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 13303     | 99.81%  |
| Yes  | 25        | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3673      | 27%     |
| 3.01-4.0        | 3459      | 25.42%  |
| 8.01-16.0       | 2348      | 17.26%  |
| 16.01-24.0      | 2181      | 16.03%  |
| 1.01-2.0        | 853       | 6.27%   |
| 32.01-64.0      | 480       | 3.53%   |
| 2.01-3.0        | 286       | 2.1%    |
| 24.01-32.0      | 143       | 1.05%   |
| 64.01-256.0     | 109       | 0.8%    |
| 0.51-1.0        | 63        | 0.46%   |
| More than 256.0 | 7         | 0.05%   |
| 0.01-0.5        | 2         | 0.01%   |
| Unknown         | 2         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 5367      | 36.33%  |
| 2.01-3.0    | 4011      | 27.15%  |
| 3.01-4.0    | 1905      | 12.9%   |
| 4.01-8.0    | 1872      | 12.67%  |
| 0.51-1.0    | 1048      | 7.09%   |
| 8.01-16.0   | 375       | 2.54%   |
| 0.01-0.5    | 131       | 0.89%   |
| 16.01-24.0  | 41        | 0.28%   |
| 24.01-32.0  | 9         | 0.06%   |
| 32.01-64.0  | 5         | 0.03%   |
| Unknown     | 5         | 0.03%   |
| 64.01-256.0 | 2         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8436      | 61.54%  |
| 2       | 3771      | 27.51%  |
| 3       | 847       | 6.18%   |
| 4       | 325       | 2.37%   |
| 0       | 131       | 0.96%   |
| 5       | 104       | 0.76%   |
| 6       | 64        | 0.47%   |
| 7       | 12        | 0.09%   |
| 8       | 8         | 0.06%   |
| 9       | 6         | 0.04%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 8525      | 63.44%  |
| Yes       | 4912      | 36.56%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12161     | 91.09%  |
| No        | 1189      | 8.91%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9767      | 72.68%  |
| No        | 3671      | 27.32%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6863      | 50.91%  |
| No        | 6618      | 49.09%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 13328     | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 1692      | 12.1%   |
| Rio de Janeiro        | 826       | 5.91%   |
| Brasília             | 435       | 3.11%   |
| Curitiba              | 388       | 2.78%   |
| Belo Horizonte        | 384       | 2.75%   |
| Porto Alegre          | 306       | 2.19%   |
| Fortaleza             | 293       | 2.1%    |
| Campinas              | 210       | 1.5%    |
| Salvador              | 203       | 1.45%   |
| Recife                | 180       | 1.29%   |
| Goiânia              | 157       | 1.12%   |
| Florianópolis        | 155       | 1.11%   |
| Santo André          | 151       | 1.08%   |
| Natal                 | 123       | 0.88%   |
| Osasco                | 118       | 0.84%   |
| Manaus                | 115       | 0.82%   |
| Sao José dos Campos  | 113       | 0.81%   |
| Niterói              | 104       | 0.74%   |
| Campo Grande          | 101       | 0.72%   |
| Guarulhos             | 100       | 0.72%   |
| Belém                | 93        | 0.67%   |
| Maringá              | 91        | 0.65%   |
| Sao Luís             | 90        | 0.64%   |
| Sorocaba              | 89        | 0.64%   |
| Joao Pessoa           | 86        | 0.62%   |
| Joinville             | 84        | 0.6%    |
| Londrina              | 82        | 0.59%   |
| Teresina              | 79        | 0.57%   |
| Aracaju               | 77        | 0.55%   |
| Uberlândia           | 75        | 0.54%   |
| Ribeirao Preto        | 74        | 0.53%   |
| Juiz de Fora          | 71        | 0.51%   |
| Maceió               | 67        | 0.48%   |
| Serra                 | 63        | 0.45%   |
| Duque de Caxias       | 62        | 0.44%   |
| Sao Jose              | 60        | 0.43%   |
| Sao Bernardo do Campo | 59        | 0.42%   |
| Cuiabá               | 58        | 0.41%   |
| Sao Carlos            | 56        | 0.4%    |
| Blumenau              | 56        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 3684      | 4771   | 19.71%  |
| Seagate                        | 3494      | 4981   | 18.69%  |
| Kingston                       | 1931      | 2518   | 10.33%  |
| Samsung Electronics            | 1811      | 2525   | 9.69%   |
| Toshiba                        | 1037      | 1223   | 5.55%   |
| SanDisk                        | 944       | 1282   | 5.05%   |
| Unknown                        | 566       | 776    | 3.03%   |
| A-DATA Technology              | 530       | 676    | 2.84%   |
| China                          | 487       | 585    | 2.61%   |
| Hitachi                        | 405       | 497    | 2.17%   |
| Crucial                        | 359       | 468    | 1.92%   |
| Intel                          | 323       | 403    | 1.73%   |
| ADATA Technology               | 230       | 272    | 1.23%   |
| Silicon Motion                 | 210       | 267    | 1.12%   |
| SK hynix                       | 166       | 231    | 0.89%   |
| HGST                           | 150       | 178    | 0.8%    |
| KingSpec                       | 145       | 164    | 0.78%   |
| LITEON                         | 135       | 160    | 0.72%   |
| Maxtor                         | 127       | 149    | 0.68%   |
| Lexar                          | 101       | 118    | 0.54%   |
| Realtek Semiconductor          | 94        | 120    | 0.5%    |
| Netac                          | 80        | 102    | 0.43%   |
| JMicron Technology             | 78        | 87     | 0.42%   |
| Phison                         | 70        | 92     | 0.37%   |
| Corsair                        | 66        | 78     | 0.35%   |
| XPG                            | 62        | 77     | 0.33%   |
| SSSTC                          | 61        | 63     | 0.33%   |
| Fujitsu                        | 60        | 71     | 0.32%   |
| Patriot                        | 57        | 77     | 0.3%    |
| Kingston Technology Company    | 56        | 67     | 0.3%    |
| PNY                            | 55        | 71     | 0.29%   |
| Unknown                        | 55        | 64     | 0.29%   |
| XrayDisk                       | 54        | 72     | 0.29%   |
| Apple                          | 52        | 72     | 0.28%   |
| Hewlett-Packard                | 51        | 62     | 0.27%   |
| Solid State Storage            | 48        | 58     | 0.26%   |
| Solid State Storage Technology | 42        | 56     | 0.22%   |
| MAXIO Technology (Hangzhou)    | 41        | 50     | 0.22%   |
| KIOXIA                         | 41        | 49     | 0.22%   |
| Gigabyte Technology            | 40        | 54     | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 656       | 3.28%   |
| WDC WD10SPZX-21Z10T0 1TB            | 496       | 2.48%   |
| Kingston SA400S37480G 480GB SSD     | 345       | 1.73%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 329       | 1.65%   |
| Kingston SA400S37120G 120GB SSD     | 329       | 1.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 313       | 1.57%   |
| Seagate ST500DM002-1BD142 500GB     | 270       | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB      | 241       | 1.21%   |
| Toshiba MQ01ABD100 1TB              | 162       | 0.81%   |
| Kingston SV300S37A120G 120GB SSD    | 157       | 0.79%   |
| Unknown MMC Card  32GB              | 156       | 0.78%   |
| WDC WD10SPZX-24Z10 1TB              | 152       | 0.76%   |
| SanDisk SSD PLUS 240GB              | 150       | 0.75%   |
| Seagate Expansion 1TB               | 135       | 0.68%   |
| Samsung HD322HJ 320GB               | 133       | 0.67%   |
| Seagate ST1000LM035-1RK172 1TB      | 132       | 0.66%   |
| Crucial CT240BX500SSD1 240GB        | 122       | 0.61%   |
| WDC WD10JPVX-22JC3T0 1TB            | 119       | 0.6%    |
| Samsung HD502HJ 500GB               | 113       | 0.57%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 111       | 0.56%   |
| Samsung HD161HJ 160GB               | 111       | 0.56%   |
| Samsung HM321HI 320GB               | 110       | 0.55%   |
| SanDisk SSD PLUS 120GB              | 106       | 0.53%   |
| Samsung HD502HI 500GB               | 105       | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB      | 103       | 0.52%   |
| Intel NVMe SSD Drive 512GB          | 103       | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB      | 101       | 0.51%   |
| Seagate ST9500325AS 500GB           | 97        | 0.49%   |
| A-DATA IM2S3338-128GD2 128GB SSD    | 93        | 0.47%   |
| Toshiba MQ04ABF100 1TB              | 92        | 0.46%   |
| WDC WD10SPZX-75Z10T2 1TB            | 89        | 0.45%   |
| Toshiba MQ01ABF050 500GB            | 86        | 0.43%   |
| SanDisk SDSSDA240G 240GB            | 82        | 0.41%   |
| WDC WD5000AAKX-003CA0 500GB         | 81        | 0.41%   |
| Seagate ST3500418AS 500GB           | 80        | 0.4%    |
| WDC WD10JPVX-75JC3T0 1TB            | 76        | 0.38%   |
| SanDisk SSD PLUS 480GB              | 76        | 0.38%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 75        | 0.38%   |
| Seagate ST3500312CS 500GB           | 73        | 0.37%   |
| SanDisk NVMe SSD Drive 512GB        | 73        | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3477      | 4945   | 35.46%  |
| WDC                 | 3272      | 4116   | 33.37%  |
| Samsung Electronics | 1216      | 1601   | 12.4%   |
| Toshiba             | 981       | 1153   | 10.01%  |
| Hitachi             | 405       | 497    | 4.13%   |
| HGST                | 150       | 178    | 1.53%   |
| Maxtor              | 117       | 137    | 1.19%   |
| Fujitsu             | 59        | 69     | 0.6%    |
| Unknown             | 37        | 42     | 0.38%   |
| Apple               | 20        | 32     | 0.2%    |
| Hewlett-Packard     | 18        | 23     | 0.18%   |
| ExcelStor           | 11        | 12     | 0.11%   |
| SAGE                | 8         | 13     | 0.08%   |
| USB3.0              | 5         | 5      | 0.05%   |
| JMicron Technology  | 5         | 6      | 0.05%   |
| HPE                 | 5         | 5      | 0.05%   |
| External            | 4         | 4      | 0.04%   |
| Initio              | 2         | 2      | 0.02%   |
| WALRAM              | 1         | 1      | 0.01%   |
| Phison              | 1         | 1      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 2      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1833      | 2368   | 32.24%  |
| SanDisk             | 684       | 949    | 12.03%  |
| China               | 485       | 582    | 8.53%   |
| WDC                 | 415       | 531    | 7.3%    |
| Samsung Electronics | 367       | 570    | 6.45%   |
| Crucial             | 342       | 445    | 6.01%   |
| A-DATA Technology   | 298       | 361    | 5.24%   |
| KingSpec            | 139       | 158    | 2.44%   |
| LITEON              | 121       | 145    | 2.13%   |
| Lexar               | 96        | 113    | 1.69%   |
| Netac               | 58        | 74     | 1.02%   |
| Intel               | 55        | 69     | 0.97%   |
| Patriot             | 54        | 73     | 0.95%   |
| PNY                 | 53        | 69     | 0.93%   |
| Corsair             | 51        | 60     | 0.9%    |
| Gigabyte Technology | 32        | 45     | 0.56%   |
| Unknown             | 31        | 33     | 0.55%   |
| KingDian            | 30        | 39     | 0.53%   |
| XrayDisk            | 29        | 34     | 0.51%   |
| Apple               | 29        | 35     | 0.51%   |
| Smart               | 27        | 31     | 0.47%   |
| Hewlett-Packard     | 25        | 29     | 0.44%   |
| Unknown             | 22        | 24     | 0.39%   |
| SK hynix            | 22        | 26     | 0.39%   |
| Toshiba             | 21        | 28     | 0.37%   |
| Seagate             | 18        | 22     | 0.32%   |
| OCZ                 | 16        | 17     | 0.28%   |
| BHT                 | 14        | 19     | 0.25%   |
| WALRAM              | 13        | 13     | 0.23%   |
| LITEONIT            | 13        | 20     | 0.23%   |
| Team                | 12        | 31     | 0.21%   |
| Micron Technology   | 12        | 15     | 0.21%   |
| HUSKY               | 12        | 16     | 0.21%   |
| Win Memory          | 11        | 12     | 0.19%   |
| Maxtor              | 10        | 12     | 0.18%   |
| HS-SSD-C100         | 10        | 10     | 0.18%   |
| S3+                 | 7         | 7      | 0.12%   |
| RZX                 | 7         | 14     | 0.12%   |
| Plextor             | 7         | 8      | 0.12%   |
| Pichau              | 7         | 7      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 8675      | 12858  | 51.28%  |
| SSD     | 5119      | 7353   | 30.26%  |
| NVMe    | 2489      | 3447   | 14.71%  |
| MMC     | 439       | 627    | 2.6%    |
| Unknown | 194       | 257    | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11548     | 19936  | 77.64%  |
| NVMe | 2437      | 3373   | 16.39%  |
| SAS  | 449       | 606    | 3.02%   |
| MMC  | 439       | 627    | 2.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 8764      | 13241  | 63.54%  |
| 0.51-1.0        | 4236      | 5760   | 30.71%  |
| 1.01-2.0        | 552       | 770    | 4%      |
| 2.01-3.0        | 99        | 139    | 0.72%   |
| 3.01-4.0        | 92        | 223    | 0.67%   |
| 4.01-10.0       | 41        | 68     | 0.3%    |
| 10.01-20.0      | 6         | 8      | 0.04%   |
| More than 100.0 | 1         | 1      | 0.01%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 3935      | 27.78%  |
| 251-500        | 3410      | 24.07%  |
| 501-1000       | 2286      | 16.14%  |
| 1-20           | 1124      | 7.93%   |
| 1001-2000      | 1053      | 7.43%   |
| 51-100         | 896       | 6.32%   |
| 21-50          | 630       | 4.45%   |
| 2001-3000      | 301       | 2.12%   |
| More than 3000 | 275       | 1.94%   |
| Unknown        | 257       | 1.81%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 5564      | 38.02%  |
| 21-50          | 3099      | 21.18%  |
| 101-250        | 1830      | 12.5%   |
| 51-100         | 1772      | 12.11%  |
| 251-500        | 985       | 6.73%   |
| 501-1000       | 680       | 4.65%   |
| 1001-2000      | 295       | 2.02%   |
| Unknown        | 257       | 1.76%   |
| 2001-3000      | 78        | 0.53%   |
| More than 3000 | 74        | 0.51%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 49        | 53     | 3.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 46        | 53     | 3.09%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 34        | 36     | 2.29%   |
| Samsung Electronics HD322HJ 320GB   | 28        | 39     | 1.88%   |
| WDC WD5000AAKX-003CA0 500GB         | 26        | 27     | 1.75%   |
| Seagate ST9500325AS 500GB           | 25        | 27     | 1.68%   |
| Samsung Electronics HD161HJ 160GB   | 24        | 25     | 1.61%   |
| Samsung Electronics HD502HI 500GB   | 21        | 25     | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB      | 16        | 17     | 1.08%   |
| Samsung Electronics HD502HJ 500GB   | 16        | 17     | 1.08%   |
| Toshiba MQ01ABD100 1TB              | 14        | 14     | 0.94%   |
| Seagate ST500LT012-9WS142 500GB     | 14        | 16     | 0.94%   |
| Kingston SV300S37A120G 120GB SSD    | 14        | 15     | 0.94%   |
| Toshiba MQ01ABD050 500GB            | 13        | 13     | 0.87%   |
| WDC WD10EARS-00Y5B1 1TB             | 12        | 14     | 0.81%   |
| Seagate ST9320325AS 320GB           | 12        | 12     | 0.81%   |
| Seagate ST1000DM010-2EP102 1TB      | 12        | 15     | 0.81%   |
| Samsung Electronics HM321HI 320GB   | 12        | 12     | 0.81%   |
| Seagate ST3500418AS 500GB           | 11        | 16     | 0.74%   |
| Maxtor STM3160215AS 160GB           | 11        | 13     | 0.74%   |
| WDC WD3200AAJS-00L7A0 320GB         | 10        | 10     | 0.67%   |
| Samsung Electronics HM160HI 160GB   | 10        | 10     | 0.67%   |
| Samsung Electronics HD250HJ 250GB   | 10        | 11     | 0.67%   |
| Samsung Electronics HD103SI 1TB     | 10        | 13     | 0.67%   |
| Samsung Electronics HD080HJ 80GB    | 10        | 12     | 0.67%   |
| Seagate ST3320418AS 320GB           | 9         | 13     | 0.61%   |
| Seagate ST31000524AS 1TB            | 9         | 9      | 0.61%   |
| Samsung Electronics HD103SJ 1TB     | 9         | 11     | 0.61%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 10     | 0.61%   |
| Kingston SA400S37240G 240GB SSD     | 9         | 9      | 0.61%   |
| China SSD 120GB                     | 9         | 9      | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 8         | 9      | 0.54%   |
| Seagate ST3500413AS 500GB           | 8         | 9      | 0.54%   |
| Seagate ST2000DM001-1CH164 2TB      | 8         | 10     | 0.54%   |
| Seagate ST1000DM003-1ER162 1TB      | 8         | 10     | 0.54%   |
| Seagate ST1000DM003-1CH162 1TB      | 8         | 11     | 0.54%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 15     | 0.54%   |
| Toshiba MQ02ABD100H 1TB             | 7         | 10     | 0.47%   |
| Toshiba MQ01ABF050 500GB            | 7         | 7      | 0.47%   |
| Toshiba MQ01ABD032 320GB            | 7         | 8      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 453       | 541    | 31.81%  |
| WDC                   | 315       | 363    | 22.12%  |
| Samsung Electronics   | 220       | 276    | 15.45%  |
| Toshiba               | 115       | 126    | 8.08%   |
| Hitachi               | 70        | 74     | 4.92%   |
| Kingston              | 52        | 63     | 3.65%   |
| China                 | 34        | 37     | 2.39%   |
| Maxtor                | 24        | 27     | 1.69%   |
| SanDisk               | 23        | 25     | 1.62%   |
| HGST                  | 13        | 14     | 0.91%   |
| A-DATA Technology     | 13        | 15     | 0.91%   |
| XPG                   | 7         | 7      | 0.49%   |
| Intel                 | 7         | 7      | 0.49%   |
| Netac                 | 6         | 7      | 0.42%   |
| Crucial               | 6         | 6      | 0.42%   |
| LITEON                | 5         | 6      | 0.35%   |
| Fujitsu               | 5         | 6      | 0.35%   |
| PNY                   | 4         | 6      | 0.28%   |
| KingSpec              | 4         | 4      | 0.28%   |
| Unknown               | 4         | 4      | 0.28%   |
| OCZ                   | 3         | 3      | 0.21%   |
| JMicron Technology    | 3         | 3      | 0.21%   |
| Hewlett-Packard       | 3         | 4      | 0.21%   |
| Apple                 | 3         | 3      | 0.21%   |
| XrayDisk              | 2         | 4      | 0.14%   |
| WALRAM                | 2         | 2      | 0.14%   |
| Realtek Semiconductor | 2         | 3      | 0.14%   |
| Micron Technology     | 2         | 2      | 0.14%   |
| ExcelStor             | 2         | 3      | 0.14%   |
| Corsair               | 2         | 2      | 0.14%   |
| Team                  | 1         | 1      | 0.07%   |
| SSSTC                 | 1         | 1      | 0.07%   |
| SK hynix              | 1         | 1      | 0.07%   |
| Silicon Motion        | 1         | 1      | 0.07%   |
| ShiJi                 | 1         | 4      | 0.07%   |
| SAGE                  | 1         | 1      | 0.07%   |
| Reeinno               | 1         | 1      | 0.07%   |
| QIANGHE               | 1         | 1      | 0.07%   |
| Plextor               | 1         | 1      | 0.07%   |
| OCZ-VERTEX3           | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 453       | 541    | 37.81%  |
| WDC                 | 295       | 340    | 24.62%  |
| Samsung Electronics | 214       | 269    | 17.86%  |
| Toshiba             | 114       | 125    | 9.52%   |
| Hitachi             | 70        | 74     | 5.84%   |
| Maxtor              | 24        | 27     | 2%      |
| HGST                | 13        | 14     | 1.09%   |
| Fujitsu             | 5         | 6      | 0.42%   |
| Hewlett-Packard     | 3         | 4      | 0.25%   |
| ExcelStor           | 2         | 3      | 0.17%   |
| Apple               | 2         | 2      | 0.17%   |
| SAGE                | 1         | 1      | 0.08%   |
| Initio              | 1         | 1      | 0.08%   |
| FEASSO              | 1         | 2      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1098      | 1409   | 82.93%  |
| SSD  | 194       | 220    | 14.65%  |
| NVMe | 32        | 39     | 2.42%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 4         | 4      | 11.11%  |
| Samsung Electronics HD502HJ 500GB                | 3         | 7      | 8.33%   |
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 5.56%   |
| Samsung Electronics HM250HI 250GB                | 2         | 2      | 5.56%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1         | 1      | 2.78%   |
| WDC WD3200BPVT-22JJ5T0 320GB                     | 1         | 1      | 2.78%   |
| WDC WD3200BPVT-00JJ5T0 320GB                     | 1         | 1      | 2.78%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 2.78%   |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 2.78%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 2.78%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 2.78%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.78%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.78%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 2.78%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.78%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 2.78%   |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 2.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.78%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 2.78%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 2.78%   |
| Samsung Electronics HM641JI 640GB                | 1         | 1      | 2.78%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 2.78%   |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 2.78%   |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 2.78%   |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 2.78%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 2.78%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 2.78%   |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 2.78%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 18     | 38.89%  |
| Seagate             | 10        | 10     | 27.78%  |
| WDC                 | 6         | 6      | 16.67%  |
| Toshiba             | 3         | 3      | 8.33%   |
| Hitachi             | 2         | 2      | 5.56%   |
| Maxtor              | 1         | 1      | 2.78%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 9326      | 16822  | 65.31%  |
| Works    | 3641      | 6011   | 25.5%   |
| Malfunc  | 1275      | 1668   | 8.93%   |
| Failed   | 36        | 40     | 0.25%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 10069     | 65.37%  |
| AMD                              | 2215      | 14.38%  |
| ADATA Technology                 | 491       | 3.19%   |
| SanDisk                          | 332       | 2.16%   |
| Samsung Electronics              | 284       | 1.84%   |
| Nvidia                           | 271       | 1.76%   |
| Silicon Motion                   | 237       | 1.54%   |
| Kingston Technology Company      | 166       | 1.08%   |
| Solid State Storage Technology   | 158       | 1.03%   |
| SK hynix                         | 137       | 0.89%   |
| Realtek Semiconductor            | 129       | 0.84%   |
| Phison Electronics               | 127       | 0.82%   |
| Silicon Integrated Systems [SiS] | 107       | 0.69%   |
| Marvell Technology Group         | 94        | 0.61%   |
| JMicron Technology               | 88        | 0.57%   |
| ASMedia Technology               | 81        | 0.53%   |
| VIA Technologies                 | 75        | 0.49%   |
| Micron/Crucial Technology        | 49        | 0.32%   |
| MAXIO Technology (Hangzhou)      | 49        | 0.32%   |
| KIOXIA                           | 39        | 0.25%   |
| Toshiba America Info Systems     | 30        | 0.19%   |
| Lite-On Technology               | 27        | 0.18%   |
| LSI Logic / Symbios Logic        | 26        | 0.17%   |
| Micron Technology                | 25        | 0.16%   |
| Netac Technology                 | 14        | 0.09%   |
| Broadcom / LSI                   | 14        | 0.09%   |
| Union Memory (Shenzhen)          | 9         | 0.06%   |
| Shenzhen Longsys Electronics     | 7         | 0.05%   |
| Silicon Image                    | 6         | 0.04%   |
| Beijing Starblaze Technology     | 6         | 0.04%   |
| Seagate Technology               | 5         | 0.03%   |
| OCZ Technology Group             | 4         | 0.03%   |
| INNOGRIT                         | 4         | 0.03%   |
| Dell                             | 4         | 0.03%   |
| Apple                            | 4         | 0.03%   |
| Adaptec                          | 4         | 0.03%   |
| Hewlett-Packard                  | 3         | 0.02%   |
| TenaFe                           | 2         | 0.01%   |
| O2 Micro                         | 2         | 0.01%   |
| Lenovo                           | 2         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1343      | 7.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1110      | 5.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 921       | 4.92%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 681       | 3.64%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 632       | 3.38%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 529       | 2.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 490       | 2.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 461       | 2.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 438       | 2.34%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 421       | 2.25%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 354       | 1.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 344       | 1.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 338       | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 328       | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 273       | 1.46%   |
| AMD FCH SATA Controller D                                                               | 266       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 261       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 261       | 1.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 260       | 1.39%   |
| AMD 400 Series Chipset SATA Controller                                                  | 255       | 1.36%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 231       | 1.23%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 213       | 1.14%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 207       | 1.11%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 199       | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 193       | 1.03%   |
| Nvidia MCP61 SATA Controller                                                            | 186       | 0.99%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 186       | 0.99%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 178       | 0.95%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 173       | 0.92%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 171       | 0.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 162       | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 162       | 0.87%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 161       | 0.86%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                                     | 161       | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 160       | 0.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 154       | 0.82%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                              | 153       | 0.82%   |
| Nvidia MCP61 IDE                                                                        | 152       | 0.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 143       | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 143       | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 10240     | 63.48%  |
| IDE  | 2552      | 15.82%  |
| NVMe | 2446      | 15.16%  |
| RAID | 866       | 5.37%   |
| SCSI | 17        | 0.11%   |
| SAS  | 9         | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 10774     | 80.84%  |
| AMD          | 2513      | 18.86%  |
| ARM          | 33        | 0.25%   |
| CentaurHauls | 5         | 0.04%   |
| Qualcomm     | 2         | 0.02%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 284       | 2.12%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 167       | 1.25%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 160       | 1.2%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 153       | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 152       | 1.14%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 142       | 1.06%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 141       | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 139       | 1.04%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 135       | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 124       | 0.93%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 118       | 0.88%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 113       | 0.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 110       | 0.82%   |
| AMD FX-6300 Six-Core Processor                | 102       | 0.76%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 100       | 0.75%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 99        | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 99        | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 98        | 0.73%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 97        | 0.73%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 97        | 0.73%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 95        | 0.71%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 94        | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 92        | 0.69%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 89        | 0.67%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 89        | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 87        | 0.65%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 87        | 0.65%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 87        | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 85        | 0.64%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 84        | 0.63%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 79        | 0.59%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 75        | 0.56%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 75        | 0.56%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 72        | 0.54%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 72        | 0.54%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 71        | 0.53%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 71        | 0.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 70        | 0.52%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 70        | 0.52%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 69        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3225      | 24.14%  |
| Intel Core i7           | 2070      | 15.49%  |
| Intel Core i3           | 1818      | 13.61%  |
| Intel Celeron           | 909       | 6.8%    |
| AMD Ryzen 5             | 652       | 4.88%   |
| Intel Core 2 Duo        | 567       | 4.24%   |
| Other                   | 485       | 3.63%   |
| AMD Ryzen 7             | 383       | 2.87%   |
| Intel Pentium Dual-Core | 342       | 2.56%   |
| Intel Atom              | 331       | 2.48%   |
| Intel Pentium           | 309       | 2.31%   |
| Intel Xeon              | 287       | 2.15%   |
| AMD FX                  | 284       | 2.13%   |
| Intel Pentium Dual      | 154       | 1.15%   |
| AMD Ryzen 3             | 126       | 0.94%   |
| Intel Core 2 Quad       | 107       | 0.8%    |
| AMD Phenom II X4        | 86        | 0.64%   |
| AMD Athlon II X2        | 77        | 0.58%   |
| AMD A4                  | 71        | 0.53%   |
| AMD E                   | 64        | 0.48%   |
| AMD A10                 | 63        | 0.47%   |
| Intel Core 2            | 59        | 0.44%   |
| AMD A6                  | 57        | 0.43%   |
| AMD Athlon              | 55        | 0.41%   |
| AMD Ryzen 9             | 53        | 0.4%    |
| AMD Athlon 64 X2        | 51        | 0.38%   |
| AMD A8                  | 51        | 0.38%   |
| AMD C-60                | 46        | 0.34%   |
| Intel Genuine           | 43        | 0.32%   |
| AMD E1                  | 37        | 0.28%   |
| AMD Phenom II X6        | 33        | 0.25%   |
| AMD Sempron             | 32        | 0.24%   |
| Intel Pentium 4         | 29        | 0.22%   |
| AMD C-70                | 27        | 0.2%    |
| Intel Pentium Gold      | 26        | 0.19%   |
| Intel Core i9           | 23        | 0.17%   |
| AMD Phenom II X2        | 21        | 0.16%   |
| AMD C-50                | 20        | 0.15%   |
| AMD Athlon II X4        | 18        | 0.13%   |
| Intel Celeron Dual-Core | 17        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 6942      | 51.97%  |
| 4       | 4249      | 31.81%  |
| 6       | 958       | 7.17%   |
| 8       | 471       | 3.53%   |
| 1       | 362       | 2.71%   |
| 3       | 151       | 1.13%   |
| 12      | 81        | 0.61%   |
| 10      | 48        | 0.36%   |
| 14      | 34        | 0.25%   |
| 16      | 24        | 0.18%   |
| Unknown | 18        | 0.13%   |
| 24      | 6         | 0.04%   |
| 20      | 6         | 0.04%   |
| 28      | 2         | 0.01%   |
| 18      | 2         | 0.01%   |
| 5       | 2         | 0.01%   |
| 32      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 13274     | 99.59%  |
| 2       | 48        | 0.36%   |
| Unknown | 5         | 0.04%   |
| 16      | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 8706      | 65.21%  |
| 1       | 4623      | 34.63%  |
| Unknown | 18        | 0.13%   |
| 4       | 2         | 0.01%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 12739     | 95.09%  |
| Unknown        | 545       | 4.07%   |
| 32-bit         | 62        | 0.46%   |
| 64-bit         | 51        | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3349      | 24.12%  |
| 0x306a9    | 1043      | 7.51%   |
| 0x206a7    | 1027      | 7.4%    |
| 0x1067a    | 674       | 4.86%   |
| 0x806e9    | 427       | 3.08%   |
| 0x906ea    | 425       | 3.06%   |
| 0x306c3    | 388       | 2.79%   |
| 0x20655    | 387       | 2.79%   |
| 0x40651    | 360       | 2.59%   |
| 0x806ec    | 337       | 2.43%   |
| 0x306d4    | 295       | 2.13%   |
| 0x406e3    | 285       | 2.05%   |
| 0x806ea    | 262       | 1.89%   |
| 0x6fd      | 258       | 1.86%   |
| 0x906e9    | 222       | 1.6%    |
| 0x806c1    | 212       | 1.53%   |
| 0x406c4    | 193       | 1.39%   |
| 0x08108109 | 192       | 1.38%   |
| 0x06000852 | 159       | 1.15%   |
| 0x010000c8 | 138       | 0.99%   |
| 0x30678    | 133       | 0.96%   |
| 0x20652    | 100       | 0.72%   |
| 0x05000119 | 100       | 0.72%   |
| 0x08600103 | 90        | 0.65%   |
| 0x0800820d | 89        | 0.64%   |
| 0x906ed    | 88        | 0.63%   |
| 0x706e5    | 88        | 0.63%   |
| 0x08108102 | 88        | 0.63%   |
| 0x10676    | 85        | 0.61%   |
| 0x706a1    | 79        | 0.57%   |
| 0x506e3    | 79        | 0.57%   |
| 0x08701021 | 79        | 0.57%   |
| 0x6fb      | 67        | 0.48%   |
| 0x406c3    | 64        | 0.46%   |
| 0x106ca    | 64        | 0.46%   |
| 0x706a8    | 62        | 0.45%   |
| 0x306f2    | 62        | 0.45%   |
| 0x806eb    | 58        | 0.42%   |
| 0x0600611a | 57        | 0.41%   |
| 0x08701013 | 55        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2386      | 17.88%  |
| IvyBridge        | 1368      | 10.25%  |
| SandyBridge      | 1292      | 9.68%   |
| Haswell          | 1017      | 7.62%   |
| Penryn           | 907       | 6.8%    |
| Westmere         | 614       | 4.6%    |
| Core             | 509       | 3.81%   |
| Silvermont       | 506       | 3.79%   |
| Skylake          | 486       | 3.64%   |
| Zen+             | 469       | 3.51%   |
| Broadwell        | 380       | 2.85%   |
| K10              | 322       | 2.41%   |
| Piledriver       | 306       | 2.29%   |
| Zen 2            | 304       | 2.28%   |
| TigerLake        | 299       | 2.24%   |
| Zen              | 248       | 1.86%   |
| Unknown          | 208       | 1.56%   |
| CometLake        | 198       | 1.48%   |
| Bobcat           | 184       | 1.38%   |
| Goldmont plus    | 181       | 1.36%   |
| Zen 3            | 172       | 1.29%   |
| IceLake          | 155       | 1.16%   |
| Bonnell          | 135       | 1.01%   |
| K8 Hammer        | 113       | 0.85%   |
| Excavator        | 94        | 0.7%    |
| Nehalem          | 84        | 0.63%   |
| Alderlake Hybrid | 66        | 0.49%   |
| Goldmont         | 53        | 0.4%    |
| NetBurst         | 52        | 0.39%   |
| K10 Llano        | 50        | 0.37%   |
| Bulldozer        | 47        | 0.35%   |
| Steamroller      | 46        | 0.34%   |
| Jaguar           | 41        | 0.31%   |
| P6               | 26        | 0.19%   |
| K8 & K10 hybrid  | 11        | 0.08%   |
| Tremont          | 7         | 0.05%   |
| Puma             | 7         | 0.05%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8947      | 56.21%  |
| Nvidia                           | 3888      | 24.43%  |
| AMD                              | 2875      | 18.06%  |
| Silicon Integrated Systems [SiS] | 104       | 0.65%   |
| VIA Technologies                 | 57        | 0.36%   |
| Matrox Electronics Systems       | 28        | 0.18%   |
| ASPEED Technology                | 9         | 0.06%   |
| Silicon Motion                   | 4         | 0.03%   |
| ATI Technologies                 | 4         | 0.03%   |
| S3 Graphics                      | 1         | 0.01%   |
| Red Hat                          | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1071      | 6.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 800       | 4.91%   |
| Intel HD Graphics 620                                                                    | 571       | 3.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 527       | 3.23%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 442       | 2.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 406       | 2.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 392       | 2.41%   |
| Intel HD Graphics 5500                                                                   | 334       | 2.05%   |
| Intel UHD Graphics 620                                                                   | 323       | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 321       | 1.97%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 318       | 1.95%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 315       | 1.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 310       | 1.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 276       | 1.69%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 274       | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 251       | 1.54%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 212       | 1.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 195       | 1.2%    |
| Intel HD Graphics 630                                                                    | 195       | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 191       | 1.17%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 183       | 1.12%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 182       | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 181       | 1.11%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 175       | 1.07%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 155       | 0.95%   |
| Nvidia GT218 [GeForce 210]                                                               | 154       | 0.94%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 146       | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 146       | 0.9%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 119       | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 117       | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 107       | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                                            | 106       | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 102       | 0.63%   |
| Nvidia GM108M [GeForce MX110]                                                            | 101       | 0.62%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 100       | 0.61%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 99        | 0.61%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 98        | 0.6%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 98        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 95        | 0.58%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 94        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 6591      | 49.13%  |
| 1 x AMD                 | 2119      | 15.79%  |
| 1 x Nvidia              | 1852      | 13.8%   |
| Intel + Nvidia          | 1807      | 13.47%  |
| Intel + AMD             | 446       | 3.32%   |
| AMD + Nvidia            | 195       | 1.45%   |
| 2 x AMD                 | 122       | 0.91%   |
| 1 x SiS                 | 104       | 0.78%   |
| 1 x VIA                 | 56        | 0.42%   |
| Other                   | 38        | 0.28%   |
| 1 x Matrox              | 27        | 0.2%    |
| 2 x Intel               | 23        | 0.17%   |
| 2 x Nvidia              | 18        | 0.13%   |
| 1 x ASPEED              | 8         | 0.06%   |
| Intel + Silicon Motion  | 2         | 0.01%   |
| 1 x Silicon Motion      | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| 1 x Red Hat             | 1         | 0.01%   |
| Nvidia + Silicon Motion | 1         | 0.01%   |
| Nvidia + ASPEED         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + Matrox            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 10735     | 79.54%  |
| Proprietary | 2241      | 16.6%   |
| Unknown     | 521       | 3.86%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8407      | 61.46%  |
| 1.01-2.0   | 1881      | 13.75%  |
| 0.01-0.5   | 1146      | 8.38%   |
| 0.51-1.0   | 870       | 6.36%   |
| 3.01-4.0   | 840       | 6.14%   |
| 7.01-8.0   | 235       | 1.72%   |
| 5.01-6.0   | 199       | 1.45%   |
| 2.01-3.0   | 67        | 0.49%   |
| 8.01-16.0  | 28        | 0.2%    |
| 16.01-24.0 | 3         | 0.02%   |
| 4.01-5.0   | 2         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2075      | 14.41%  |
| Goldstar                | 1886      | 13.09%  |
| BOE                     | 1723      | 11.96%  |
| AU Optronics            | 1683      | 11.69%  |
| Chimei Innolux          | 1358      | 9.43%   |
| LG Display              | 1231      | 8.55%   |
| AOC                     | 961       | 6.67%   |
| Dell                    | 594       | 4.12%   |
| Philips                 | 391       | 2.71%   |
| Acer                    | 227       | 1.58%   |
| Chi Mei Optoelectronics | 167       | 1.16%   |
| LG Electronics          | 162       | 1.12%   |
| Hewlett-Packard         | 149       | 1.03%   |
| InfoVision              | 135       | 0.94%   |
| PANDA                   | 130       | 0.9%    |
| Apple                   | 129       | 0.9%    |
| Lenovo                  | 119       | 0.83%   |
| Sony                    | 97        | 0.67%   |
| Unknown                 | 70        | 0.49%   |
| BenQ                    | 70        | 0.49%   |
| RTK                     | 51        | 0.35%   |
| HannStar                | 50        | 0.35%   |
| CPT                     | 50        | 0.35%   |
| Positivo                | 49        | 0.34%   |
| LG Philips              | 44        | 0.31%   |
| Panasonic               | 38        | 0.26%   |
| ASUSTek Computer        | 38        | 0.26%   |
| SLD                     | 34        | 0.24%   |
| InnoLux Display         | 32        | 0.22%   |
| GDH                     | 31        | 0.22%   |
| Sharp                   | 29        | 0.2%    |
| Unknown (XXX)           | 27        | 0.19%   |
| Ancor Communications    | 27        | 0.19%   |
| VIE                     | 22        | 0.15%   |
| NCS                     | 21        | 0.15%   |
| Toshiba                 | 20        | 0.14%   |
| MTD                     | 20        | 0.14%   |
| STA                     | 19        | 0.13%   |
| HB@                     | 17        | 0.12%   |
| AGO                     | 17        | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 187       | 1.26%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 129       | 0.87%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 125       | 0.84%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 125       | 0.84%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 122       | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 114       | 0.77%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 110       | 0.74%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 106       | 0.72%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 105       | 0.71%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 103       | 0.7%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 99        | 0.67%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 84        | 0.57%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 82        | 0.55%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 80        | 0.54%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 80        | 0.54%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 79        | 0.53%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 78        | 0.53%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 76        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 69        | 0.47%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 68        | 0.46%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 67        | 0.45%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 65        | 0.44%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 61        | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 60        | 0.41%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 60        | 0.41%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 60        | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 57        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 57        | 0.38%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 57        | 0.38%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 56        | 0.38%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 54        | 0.36%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 51        | 0.34%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 51        | 0.34%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 51        | 0.34%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 48        | 0.32%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 47        | 0.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 47        | 0.32%   |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 46        | 0.31%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch          | 45        | 0.3%    |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 45        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 5513      | 39.33%  |
| 1920x1080 (FHD)    | 4474      | 31.92%  |
| 1600x900 (HD+)     | 586       | 4.18%   |
| 2560x1080          | 458       | 3.27%   |
| 1440x900 (WXGA+)   | 455       | 3.25%   |
| 1360x768           | 377       | 2.69%   |
| 3840x2160 (4K)     | 365       | 2.6%    |
| 1280x1024 (SXGA)   | 365       | 2.6%    |
| 1280x800 (WXGA)    | 338       | 2.41%   |
| 1680x1050 (WSXGA+) | 207       | 1.48%   |
| 2560x1440 (QHD)    | 159       | 1.13%   |
| 1024x768 (XGA)     | 128       | 0.91%   |
| Unknown            | 111       | 0.79%   |
| 1920x1200 (WUXGA)  | 75        | 0.54%   |
| 1280x720 (HD)      | 55        | 0.39%   |
| 1920x540           | 46        | 0.33%   |
| 1024x600           | 43        | 0.31%   |
| 3840x1080          | 30        | 0.21%   |
| 2288x1287          | 28        | 0.2%    |
| 3440x1440          | 23        | 0.16%   |
| 2560x1600          | 23        | 0.16%   |
| 800x1280           | 11        | 0.08%   |
| 2880x1800          | 9         | 0.06%   |
| 1152x864           | 9         | 0.06%   |
| 3840x2400          | 7         | 0.05%   |
| 1600x1200          | 7         | 0.05%   |
| 5760x1080          | 6         | 0.04%   |
| 4480x1080          | 6         | 0.04%   |
| 2736x1824          | 6         | 0.04%   |
| 1280x960           | 6         | 0.04%   |
| 3360x1080          | 5         | 0.04%   |
| 3286x1080          | 5         | 0.04%   |
| 3200x1080          | 5         | 0.04%   |
| 3200x1800 (QHD+)   | 4         | 0.03%   |
| 3600x1080          | 3         | 0.02%   |
| 3520x1080          | 3         | 0.02%   |
| 2732x768           | 3         | 0.02%   |
| 2160x1440          | 3         | 0.02%   |
| 6400x1080          | 2         | 0.01%   |
| 5120x1440          | 2         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4195      | 29%     |
| 14      | 1709      | 11.82%  |
| 13      | 1508      | 10.43%  |
| 18      | 953       | 6.59%   |
| 21      | 929       | 6.42%   |
| 23      | 864       | 5.97%   |
| 17      | 576       | 3.98%   |
| Unknown | 544       | 3.76%   |
| 24      | 453       | 3.13%   |
| 34      | 396       | 2.74%   |
| 20      | 362       | 2.5%    |
| 27      | 358       | 2.48%   |
| 19      | 340       | 2.35%   |
| 31      | 161       | 1.11%   |
| 11      | 133       | 0.92%   |
| 22      | 125       | 0.86%   |
| 12      | 89        | 0.62%   |
| 54      | 75        | 0.52%   |
| 40      | 74        | 0.51%   |
| 72      | 71        | 0.49%   |
| 28      | 71        | 0.49%   |
| 32      | 66        | 0.46%   |
| 84      | 58        | 0.4%    |
| 16      | 53        | 0.37%   |
| 10      | 49        | 0.34%   |
| 52      | 43        | 0.3%    |
| 26      | 41        | 0.28%   |
| 46      | 35        | 0.24%   |
| 142     | 16        | 0.11%   |
| 37      | 16        | 0.11%   |
| 25      | 13        | 0.09%   |
| 48      | 11        | 0.08%   |
| 7       | 11        | 0.08%   |
| 65      | 7         | 0.05%   |
| 58      | 7         | 0.05%   |
| 49      | 6         | 0.04%   |
| 43      | 6         | 0.04%   |
| 47      | 5         | 0.03%   |
| 39      | 5         | 0.03%   |
| 55      | 4         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 7283      | 51.08%  |
| 401-500        | 2573      | 18.05%  |
| 501-600        | 1602      | 11.24%  |
| Unknown        | 544       | 3.82%   |
| 201-300        | 538       | 3.77%   |
| 351-400        | 504       | 3.53%   |
| 701-800        | 464       | 3.25%   |
| 601-700        | 281       | 1.97%   |
| 1001-1500      | 201       | 1.41%   |
| 1501-2000      | 131       | 0.92%   |
| 801-900        | 98        | 0.69%   |
| More than 2000 | 16        | 0.11%   |
| 901-1000       | 12        | 0.08%   |
| 1-100          | 11        | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 10392     | 79.88%  |
| 16/10   | 1052      | 8.09%   |
| Unknown | 457       | 3.51%   |
| 21/9    | 447       | 3.44%   |
| 5/4     | 363       | 2.79%   |
| 4/3     | 190       | 1.46%   |
| 3/2     | 64        | 0.49%   |
| 1.00    | 18        | 0.14%   |
| 0.67    | 11        | 0.08%   |
| 32/9    | 8         | 0.06%   |
| 0.56    | 3         | 0.02%   |
| 2.00    | 2         | 0.02%   |
| 6/5     | 1         | 0.01%   |
| 0.31    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 4155      | 28.89%  |
| 81-90          | 3007      | 20.91%  |
| 201-250        | 2010      | 13.97%  |
| 141-150        | 1145      | 7.96%   |
| 151-200        | 1006      | 6.99%   |
| 351-500        | 645       | 4.48%   |
| Unknown        | 544       | 3.78%   |
| 301-350        | 370       | 2.57%   |
| More than 1000 | 301       | 2.09%   |
| 71-80          | 212       | 1.47%   |
| 251-300        | 179       | 1.24%   |
| 121-130        | 164       | 1.14%   |
| 501-1000       | 159       | 1.11%   |
| 131-140        | 138       | 0.96%   |
| 51-60          | 133       | 0.92%   |
| 91-100         | 56        | 0.39%   |
| 61-70          | 51        | 0.35%   |
| 41-50          | 49        | 0.34%   |
| 111-120        | 49        | 0.34%   |
| 1-40           | 11        | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 5779      | 41.4%   |
| 51-100        | 4632      | 33.18%  |
| 121-160       | 2349      | 16.83%  |
| Unknown       | 545       | 3.9%    |
| 1-50          | 399       | 2.86%   |
| 161-240       | 222       | 1.59%   |
| More than 240 | 33        | 0.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 10784     | 79.08%  |
| 2     | 2194      | 16.09%  |
| 0     | 540       | 3.96%   |
| 3     | 112       | 0.82%   |
| 4     | 7         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 9533      | 45.21%  |
| Qualcomm Atheros                  | 3999      | 18.97%  |
| Intel                             | 3672      | 17.41%  |
| Broadcom                          | 973       | 4.61%   |
| Ralink Technology                 | 451       | 2.14%   |
| Marvell Technology Group          | 250       | 1.19%   |
| Ralink                            | 243       | 1.15%   |
| JMicron Technology                | 236       | 1.12%   |
| Nvidia                            | 223       | 1.06%   |
| TP-Link                           | 207       | 0.98%   |
| Broadcom Limited                  | 207       | 0.98%   |
| Qualcomm Atheros Communications   | 142       | 0.67%   |
| Samsung Electronics               | 127       | 0.6%    |
| Silicon Integrated Systems [SiS]  | 105       | 0.5%    |
| D-Link                            | 80        | 0.38%   |
| VIA Technologies                  | 73        | 0.35%   |
| MediaTek                          | 73        | 0.35%   |
| Xiaomi                            | 60        | 0.28%   |
| Microsoft                         | 53        | 0.25%   |
| Motorola PCS                      | 51        | 0.24%   |
| ASIX Electronics                  | 49        | 0.23%   |
| D-Link System                     | 44        | 0.21%   |
| ICS Advent                        | 20        | 0.09%   |
| Motorola                          | 14        | 0.07%   |
| DisplayLink                       | 14        | 0.07%   |
| Huawei Technologies               | 12        | 0.06%   |
| Dell                              | 10        | 0.05%   |
| Edimax Technology                 | 9         | 0.04%   |
| LG Electronics                    | 8         | 0.04%   |
| Qualcomm                          | 7         | 0.03%   |
| Microchip Technology              | 7         | 0.03%   |
| ASUSTek Computer                  | 7         | 0.03%   |
| Mercucys                          | 6         | 0.03%   |
| QinHeng Electronics               | 5         | 0.02%   |
| Lenovo                            | 5         | 0.02%   |
| Arduino SA                        | 5         | 0.02%   |
| Accton Technology                 | 5         | 0.02%   |
| 3Com                              | 5         | 0.02%   |
| Sundance Technology Inc / IC Plus | 4         | 0.02%   |
| STMicroelectronics                | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6248      | 27.04%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2024      | 8.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 934       | 4.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 829       | 3.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 705       | 3.05%   |
| Intel Wi-Fi 6 AX200                                               | 400       | 1.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 347       | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 344       | 1.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 337       | 1.46%   |
| Intel Wi-Fi 6 AX201                                               | 277       | 1.2%    |
| Ralink MT7601U Wireless Adapter                                   | 258       | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 232       | 1%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 199       | 0.86%   |
| Intel Wireless 7265                                               | 197       | 0.85%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 188       | 0.81%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 168       | 0.73%   |
| Nvidia MCP61 Ethernet                                             | 164       | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 161       | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 149       | 0.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 137       | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 134       | 0.58%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 128       | 0.55%   |
| Qualcomm Atheros AR9271 802.11n                                   | 127       | 0.55%   |
| Intel Wireless 7260                                               | 125       | 0.54%   |
| Realtek RTL8125 2.5GbE Controller                                 | 124       | 0.54%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 121       | 0.52%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter          | 121       | 0.52%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter             | 120       | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 117       | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 111       | 0.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 111       | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 108       | 0.47%   |
| Intel Wireless 3165                                               | 106       | 0.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 101       | 0.44%   |
| Intel Ethernet Connection (2) I219-V                              | 99        | 0.43%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 98        | 0.42%   |
| Realtek 802.11ac NIC                                              | 96        | 0.42%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 95        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 94        | 0.41%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 94        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3498      | 34.37%  |
| Intel                                 | 2856      | 28.06%  |
| Realtek Semiconductor                 | 1794      | 17.63%  |
| Broadcom                              | 598       | 5.88%   |
| Ralink Technology                     | 451       | 4.43%   |
| Ralink                                | 243       | 2.39%   |
| TP-Link                               | 187       | 1.84%   |
| Qualcomm Atheros Communications       | 142       | 1.4%    |
| Broadcom Limited                      | 117       | 1.15%   |
| D-Link                                | 80        | 0.79%   |
| MediaTek                              | 62        | 0.61%   |
| Microsoft                             | 53        | 0.52%   |
| D-Link System                         | 31        | 0.3%    |
| Marvell Technology Group              | 9         | 0.09%   |
| Edimax Technology                     | 9         | 0.09%   |
| Mercucys                              | 6         | 0.06%   |
| Dell                                  | 6         | 0.06%   |
| Micro Star International              | 4         | 0.04%   |
| Linksys                               | 4         | 0.04%   |
| Encore Electronics                    | 4         | 0.04%   |
| NetGear                               | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Xiaomi                                | 2         | 0.02%   |
| Sierra Wireless                       | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| IMC Networks                          | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Accton Technology                     | 2         | 0.02%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| Ericsson Business Mobile Networks     | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 934       | 9.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 829       | 8.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 705       | 6.88%   |
| Intel Wi-Fi 6 AX200                                            | 400       | 3.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 347       | 3.39%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 344       | 3.36%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 337       | 3.29%   |
| Intel Wi-Fi 6 AX201                                            | 277       | 2.7%    |
| Ralink MT7601U Wireless Adapter                                | 258       | 2.52%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 232       | 2.26%   |
| Intel Wireless 7265                                            | 197       | 1.92%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 188       | 1.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 149       | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 137       | 1.34%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 134       | 1.31%   |
| Qualcomm Atheros AR9271 802.11n                                | 127       | 1.24%   |
| Intel Wireless 7260                                            | 125       | 1.22%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 121       | 1.18%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 121       | 1.18%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 120       | 1.17%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 111       | 1.08%   |
| Intel Wireless 3165                                            | 106       | 1.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 101       | 0.99%   |
| Realtek 802.11ac NIC                                           | 96        | 0.94%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 94        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 93        | 0.91%   |
| Ralink RT5370 Wireless Adapter                                 | 92        | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 91        | 0.89%   |
| Intel Wireless 3160                                            | 88        | 0.86%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 87        | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 87        | 0.85%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 82        | 0.8%    |
| Intel Wireless 8265 / 8275                                     | 80        | 0.78%   |
| Intel Centrino Advanced-N 6235                                 | 75        | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 75        | 0.73%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 70        | 0.68%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 67        | 0.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 66        | 0.64%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 62        | 0.61%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 60        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 8728      | 69.26%  |
| Intel                             | 1234      | 9.79%   |
| Qualcomm Atheros                  | 767       | 6.09%   |
| Broadcom                          | 469       | 3.72%   |
| Marvell Technology Group          | 241       | 1.91%   |
| JMicron Technology                | 236       | 1.87%   |
| Nvidia                            | 222       | 1.76%   |
| Samsung Electronics               | 126       | 1%      |
| Silicon Integrated Systems [SiS]  | 105       | 0.83%   |
| Broadcom Limited                  | 97        | 0.77%   |
| VIA Technologies                  | 72        | 0.57%   |
| Xiaomi                            | 58        | 0.46%   |
| ASIX Electronics                  | 49        | 0.39%   |
| Motorola PCS                      | 39        | 0.31%   |
| TP-Link                           | 20        | 0.16%   |
| ICS Advent                        | 20        | 0.16%   |
| DisplayLink                       | 14        | 0.11%   |
| D-Link System                     | 13        | 0.1%    |
| MediaTek                          | 10        | 0.08%   |
| Huawei Technologies               | 7         | 0.06%   |
| Qualcomm                          | 6         | 0.05%   |
| LG Electronics                    | 6         | 0.05%   |
| Microchip Technology              | 5         | 0.04%   |
| Lenovo                            | 5         | 0.04%   |
| ASUSTek Computer                  | 5         | 0.04%   |
| 3Com                              | 5         | 0.04%   |
| Sundance Technology Inc / IC Plus | 4         | 0.03%   |
| OPPO Electronics                  | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.02%   |
| Dell                              | 3         | 0.02%   |
| Aquantia                          | 3         | 0.02%   |
| Apple                             | 3         | 0.02%   |
| Accton Technology                 | 3         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Spreadtrum Communications         | 2         | 0.02%   |
| IBM                               | 2         | 0.02%   |
| Standard Microsystems             | 1         | 0.01%   |
| SK hynix                          | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 6248      | 48.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 2024      | 15.85%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 199       | 1.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 168       | 1.32%   |
| Nvidia MCP61 Ethernet                                             | 164       | 1.28%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 161       | 1.26%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 128       | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 124       | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 117       | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 111       | 0.87%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 108       | 0.85%   |
| Intel Ethernet Connection (2) I219-V                              | 99        | 0.78%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 98        | 0.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 95        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 94        | 0.74%   |
| Intel I211 Gigabit Network Connection                             | 88        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 88        | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 82        | 0.64%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 81        | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 74        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 74        | 0.58%   |
| Intel 82579V Gigabit Network Connection                           | 70        | 0.55%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller               | 68        | 0.53%   |
| Intel Ethernet Connection I217-LM                                 | 65        | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 55        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 54        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 53        | 0.41%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 52        | 0.41%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 45        | 0.35%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 45        | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 42        | 0.33%   |
| Intel 82578DC Gigabit Network Connection                          | 41        | 0.32%   |
| ASIX AX88179 Gigabit Ethernet                                     | 41        | 0.32%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40        | 0.31%   |
| Motorola PCS motorola one macro                                   | 39        | 0.31%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 39        | 0.31%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 37        | 0.29%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 0.29%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 33        | 0.26%   |
| Intel Ethernet Connection (2) I218-V                              | 33        | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 12148     | 55.22%  |
| WiFi     | 9760      | 44.36%  |
| Modem    | 67        | 0.3%    |
| Unknown  | 25        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 7994      | 57.82%  |
| Ethernet | 5829      | 42.16%  |
| Unknown  | 2         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 7652      | 57.13%  |
| 1     | 5214      | 38.92%  |
| 0     | 409       | 3.05%   |
| 3     | 91        | 0.68%   |
| 4     | 21        | 0.16%   |
| 10    | 3         | 0.02%   |
| 5     | 3         | 0.02%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10175     | 74.23%  |
| Yes  | 3532      | 25.77%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2465      | 35.66%  |
| Qualcomm Atheros Communications | 1716      | 24.82%  |
| Lite-On Technology              | 705       | 10.2%   |
| Cambridge Silicon Radio         | 582       | 8.42%   |
| Realtek Semiconductor           | 310       | 4.48%   |
| Broadcom                        | 237       | 3.43%   |
| IMC Networks                    | 167       | 2.42%   |
| Apple                           | 154       | 2.23%   |
| Foxconn / Hon Hai               | 136       | 1.97%   |
| Dell                            | 86        | 1.24%   |
| Hewlett-Packard                 | 64        | 0.93%   |
| Ralink                          | 57        | 0.82%   |
| Smart Modular Technologies      | 49        | 0.71%   |
| Qcom                            | 29        | 0.42%   |
| ASUSTek Computer                | 24        | 0.35%   |
| MediaTek                        | 19        | 0.27%   |
| Ralink Technology               | 17        | 0.25%   |
| Foxconn International           | 15        | 0.22%   |
| Alps Electric                   | 15        | 0.22%   |
| Askey Computer                  | 10        | 0.14%   |
| Integrated System Solution      | 8         | 0.12%   |
| Toshiba                         | 6         | 0.09%   |
| Micro Star International        | 6         | 0.09%   |
| Actions                         | 6         | 0.09%   |
| Opticis                         | 5         | 0.07%   |
| ISSC                            | 4         | 0.06%   |
| Marvell Semiconductor           | 3         | 0.04%   |
| Conwise Technology              | 3         | 0.04%   |
| Unknown                         | 3         | 0.04%   |
| Syntek                          | 2         | 0.03%   |
| SINO WEALTH                     | 2         | 0.03%   |
| Realtek                         | 2         | 0.03%   |
| USI                             | 1         | 0.01%   |
| TP-Link                         | 1         | 0.01%   |
| Motorola PCS                    | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| D-Link                          | 1         | 0.01%   |
| AboCom Systems                  | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 992       | 14.35%  |
| Intel Bluetooth wireless interface                                                  | 790       | 11.42%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 628       | 9.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 582       | 8.42%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 391       | 5.65%   |
| Intel AX200 Bluetooth                                                               | 389       | 5.63%   |
| Intel AX201 Bluetooth                                                               | 281       | 4.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 262       | 3.79%   |
| Realtek Bluetooth Radio                                                             | 237       | 3.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 158       | 2.28%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 152       | 2.2%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 132       | 1.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 106       | 1.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 102       | 1.48%   |
| Lite-On Bluetooth Device                                                            | 96        | 1.39%   |
| Intel Bluetooth Device                                                              | 93        | 1.34%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 92        | 1.33%   |
| IMC Networks Bluetooth Radio                                                        | 90        | 1.3%    |
| Apple Bluetooth Host Controller                                                     | 72        | 1.04%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 68        | 0.98%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 62        | 0.9%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 60        | 0.87%   |
| Ralink RT3290 Bluetooth                                                             | 57        | 0.82%   |
| Smart Modular Bluetooth Device                                                      | 49        | 0.71%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 48        | 0.69%   |
| Intel AX210 Bluetooth                                                               | 40        | 0.58%   |
| Apple Bluetooth USB Host Controller                                                 | 37        | 0.54%   |
| Dell Wireless 365 Bluetooth                                                         | 36        | 0.52%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 34        | 0.49%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 34        | 0.49%   |
| IMC Networks Bluetooth Device                                                       | 33        | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 31        | 0.45%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 25        | 0.36%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 25        | 0.36%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.35%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 23        | 0.33%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 22        | 0.32%   |
| Lite-On Wireless_Device                                                             | 22        | 0.32%   |
| Dell DW375 Bluetooth Module                                                         | 20        | 0.29%   |
| MediaTek Wireless_Device                                                            | 19        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 10281     | 59.77%  |
| AMD                                             | 2840      | 16.51%  |
| Nvidia                                          | 2639      | 15.34%  |
| C-Media Electronics                             | 291       | 1.69%   |
| Generalplus Technology                          | 142       | 0.83%   |
| Logitech                                        | 107       | 0.62%   |
| Silicon Integrated Systems [SiS]                | 106       | 0.62%   |
| VIA Technologies                                | 79        | 0.46%   |
| JMTek                                           | 74        | 0.43%   |
| Kingston Technology                             | 66        | 0.38%   |
| Texas Instruments                               | 50        | 0.29%   |
| Creative Labs                                   | 42        | 0.24%   |
| Corsair                                         | 32        | 0.19%   |
| Microsoft                                       | 28        | 0.16%   |
| Plantronics                                     | 23        | 0.13%   |
| Razer USA                                       | 19        | 0.11%   |
| Realtek Semiconductor                           | 17        | 0.1%    |
| GN Netcom                                       | 17        | 0.1%    |
| BEHRINGER International                         | 17        | 0.1%    |
| Sony                                            | 16        | 0.09%   |
| Licensed by Sony Computer Entertainment America | 16        | 0.09%   |
| Tenx Technology                                 | 15        | 0.09%   |
| Dell                                            | 13        | 0.08%   |
| Goldvish                                        | 12        | 0.07%   |
| Jieli Technology                                | 11        | 0.06%   |
| JBL                                             | 11        | 0.06%   |
| Focusrite-Novation                              | 11        | 0.06%   |
| Samson Technologies                             | 10        | 0.06%   |
| SteelSeries ApS                                 | 8         | 0.05%   |
| M-Audio                                         | 8         | 0.05%   |
| HECATE G4 TE GAMING HEADSET                     | 8         | 0.05%   |
| ASUSTek Computer                                | 8         | 0.05%   |
| Samsung Electronics                             | 7         | 0.04%   |
| Fry's Electronics                               | 7         | 0.04%   |
| fifine Microphones                              | 7         | 0.04%   |
| Creative Technology                             | 7         | 0.04%   |
| Philips (or NXP)                                | 6         | 0.03%   |
| Tdlasunnic                                      | 5         | 0.03%   |
| KTMicro                                         | 5         | 0.03%   |
| Elite Silicon                                   | 5         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1326      | 6.62%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1276      | 6.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1274      | 6.36%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 793       | 3.96%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 748       | 3.74%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 650       | 3.25%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 605       | 3.02%   |
| Intel Cannon Lake PCH cAVS                                                                        | 563       | 2.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 471       | 2.35%   |
| Intel 8 Series HD Audio Controller                                                                | 444       | 2.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 439       | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 425       | 2.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 400       | 2%      |
| Intel Broadwell-U Audio Controller                                                                | 357       | 1.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 354       | 1.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 346       | 1.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 334       | 1.67%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 321       | 1.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 298       | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 291       | 1.45%   |
| AMD FCH Azalia Controller                                                                         | 280       | 1.4%    |
| Nvidia High Definition Audio Controller                                                           | 259       | 1.29%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 243       | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 237       | 1.18%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 236       | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 227       | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 205       | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 200       | 1%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 198       | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 188       | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 181       | 0.9%    |
| Nvidia MCP61 High Definition Audio                                                                | 180       | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 180       | 0.9%    |
| Intel 200 Series PCH HD Audio                                                                     | 163       | 0.81%   |
| AMD Wrestler HDMI Audio                                                                           | 161       | 0.8%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 161       | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 160       | 0.8%    |
| Generalplus Technology USB Audio Device                                                           | 142       | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 131       | 0.65%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 129       | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 1000      | 16.89%  |
| Kingston            | 943       | 15.92%  |
| Smart               | 795       | 13.42%  |
| Samsung Electronics | 561       | 9.47%   |
| SK hynix            | 392       | 6.62%   |
| A-DATA Technology   | 364       | 6.15%   |
| Corsair             | 260       | 4.39%   |
| Teikon              | 203       | 3.43%   |
| Micron Technology   | 202       | 3.41%   |
| Crucial             | 200       | 3.38%   |
| Smart Brazil        | 125       | 2.11%   |
| Unknown             | 78        | 1.32%   |
| High Bridge         | 70        | 1.18%   |
| Team                | 61        | 1.03%   |
| Multilaser          | 53        | 0.89%   |
| Elpida              | 53        | 0.89%   |
| Unknown (ABCD)      | 47        | 0.79%   |
| G.Skill             | 45        | 0.76%   |
| Apacer              | 36        | 0.61%   |
| Patriot             | 31        | 0.52%   |
| Nanya Technology    | 26        | 0.44%   |
| Kllisre             | 25        | 0.42%   |
| Atermiter           | 24        | 0.41%   |
| Avant               | 18        | 0.3%    |
| Ramaxel Technology  | 15        | 0.25%   |
| PUSKILL             | 15        | 0.25%   |
| HT Micron           | 13        | 0.22%   |
| Smart Modular       | 12        | 0.2%    |
| Kreton              | 12        | 0.2%    |
| HBS                 | 12        | 0.2%    |
| RZX                 | 10        | 0.17%   |
| GeIL                | 10        | 0.17%   |
| CSX                 | 10        | 0.17%   |
| Kingmax             | 8         | 0.14%   |
| Asgard              | 8         | 0.14%   |
| Unknown (0x0B5E)    | 7         | 0.12%   |
| Transcend           | 7         | 0.12%   |
| Walton Chaintech    | 6         | 0.1%    |
| Unknown (82B5)      | 6         | 0.1%    |
| Positivo            | 6         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s     | 85        | 1.31%   |
| Unknown                                                          | 78        | 1.2%    |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s            | 58        | 0.89%   |
| Smart RAM SH564568FH8NZPHSCR 2048MB SODIMM DDR3 1333MT/s         | 56        | 0.86%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 51        | 0.79%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s            | 50        | 0.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 50        | 0.77%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 47        | 0.72%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s            | 44        | 0.68%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 43        | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 41        | 0.63%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 40        | 0.62%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s            | 38        | 0.59%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 36        | 0.55%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 34        | 0.52%   |
| Smart RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s            | 33        | 0.51%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 33        | 0.51%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s              | 33        | 0.51%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 30        | 0.46%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 29        | 0.45%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s            | 29        | 0.45%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s            | 27        | 0.42%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s             | 27        | 0.42%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 26        | 0.4%    |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s            | 26        | 0.4%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 24        | 0.37%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s           | 24        | 0.37%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s            | 24        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 23        | 0.35%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s           | 23        | 0.35%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 22        | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.34%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s             | 22        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 21        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR2                                 | 21        | 0.32%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s            | 21        | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 20        | 0.31%   |
| Unknown RAM Module 4GB DIMM SDRAM                                | 20        | 0.31%   |
| Smart RAM SH564128FH8N6TNSQG 4GB DIMM DDR3 1600MT/s              | 20        | 0.31%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s           | 19        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 2105      | 42.01%  |
| DDR4         | 1885      | 37.62%  |
| DDR2         | 322       | 6.43%   |
| Unknown      | 226       | 4.51%   |
| SDRAM        | 209       | 4.17%   |
| LPDDR4       | 106       | 2.12%   |
| DDR          | 48        | 0.96%   |
| LPDDR3       | 36        | 0.72%   |
| DDR5         | 36        | 0.72%   |
| DRAM         | 24        | 0.48%   |
| LPDDR5       | 11        | 0.22%   |
| RAM          | 2         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2725      | 54.7%   |
| DIMM         | 2090      | 41.95%  |
| Row Of Chips | 138       | 2.77%   |
| Unknown      | 19        | 0.38%   |
| RIMM         | 4         | 0.08%   |
| FB-DIMM      | 4         | 0.08%   |
| Chip         | 2         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 2017      | 35.54%  |
| 8192  | 1686      | 29.71%  |
| 2048  | 1092      | 19.24%  |
| 16384 | 536       | 9.44%   |
| 1024  | 175       | 3.08%   |
| 32768 | 145       | 2.56%   |
| 512   | 18        | 0.32%   |
| 256   | 3         | 0.05%   |
| 15616 | 1         | 0.02%   |
| 1536  | 1         | 0.02%   |
| 16    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1216      | 21.66%  |
| 2667    | 705       | 12.56%  |
| 1333    | 694       | 12.36%  |
| 2400    | 504       | 8.98%   |
| 3200    | 389       | 6.93%   |
| Unknown | 285       | 5.08%   |
| 1334    | 267       | 4.76%   |
| 800     | 178       | 3.17%   |
| 2133    | 177       | 3.15%   |
| 667     | 169       | 3.01%   |
| 3600    | 84        | 1.5%    |
| 1066    | 83        | 1.48%   |
| 3000    | 71        | 1.26%   |
| 3400    | 65        | 1.16%   |
| 1067    | 65        | 1.16%   |
| 1867    | 55        | 0.98%   |
| 4199    | 43        | 0.77%   |
| 4267    | 41        | 0.73%   |
| 3466    | 39        | 0.69%   |
| 533     | 39        | 0.69%   |
| 2666    | 36        | 0.64%   |
| 1866    | 36        | 0.64%   |
| 2800    | 31        | 0.55%   |
| 4800    | 28        | 0.5%    |
| 2933    | 28        | 0.5%    |
| 3733    | 26        | 0.46%   |
| 2048    | 23        | 0.41%   |
| 400     | 23        | 0.41%   |
| 975     | 22        | 0.39%   |
| 3800    | 18        | 0.32%   |
| 3151    | 17        | 0.3%    |
| 333     | 16        | 0.29%   |
| 3266    | 14        | 0.25%   |
| 6400    | 9         | 0.16%   |
| 3334    | 9         | 0.16%   |
| 8400    | 7         | 0.12%   |
| 1800    | 7         | 0.12%   |
| 3333    | 5         | 0.09%   |
| 1200    | 5         | 0.09%   |
| 41632   | 4         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 124       | 42.32%  |
| Seiko Epson           | 82        | 27.99%  |
| Samsung Electronics   | 27        | 9.22%   |
| Canon                 | 25        | 8.53%   |
| Brother Industries    | 21        | 7.17%   |
| Lexmark International | 3         | 1.02%   |
| QinHeng Electronics   | 2         | 0.68%   |
| Apple                 | 2         | 0.68%   |
| Xerox                 | 1         | 0.34%   |
| Ricoh                 | 1         | 0.34%   |
| Prolific Technology   | 1         | 0.34%   |
| Pantum                | 1         | 0.34%   |
| Oki Data              | 1         | 0.34%   |
| MIIIW                 | 1         | 0.34%   |
| ARGOX                 | 1         | 0.34%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                   | 14        | 4.71%   |
| Seiko Epson ET-2600 Series                   | 11        | 3.7%    |
| Seiko Epson L355 Series                      | 9         | 3.03%   |
| HP Ink Tank Wireless 410 series              | 9         | 3.03%   |
| HP DeskJet 2700 series                       | 9         | 3.03%   |
| HP DeskJet 2130 series                       | 9         | 3.03%   |
| Seiko Epson L365 Series                      | 8         | 2.69%   |
| Canon G3010 series                           | 8         | 2.69%   |
| HP Deskjet 3050 J610 series                  | 7         | 2.36%   |
| HP Deskjet 2540 series                       | 7         | 2.36%   |
| HP LaserJet 1020                             | 6         | 2.02%   |
| HP DeskJet F4100 Printer series              | 6         | 2.02%   |
| Samsung SCX-4200 series                      | 5         | 1.68%   |
| Samsung M2070 Series                         | 5         | 1.68%   |
| Samsung M2020 Series                         | 5         | 1.68%   |
| HP LaserJet Professional P1102w              | 5         | 1.68%   |
| HP LaserJet P1005                            | 5         | 1.68%   |
| HP DeskJet 3630 series                       | 5         | 1.68%   |
| HP DeskJet 2600 series                       | 5         | 1.68%   |
| HP Deskjet 2050 J510                         | 5         | 1.68%   |
| Seiko Epson L360 Series                      | 4         | 1.35%   |
| HP Deskjet F4400 series                      | 4         | 1.35%   |
| HP DeskJet F4200 series                      | 4         | 1.35%   |
| Seiko Epson XP-240 Series                    | 3         | 1.01%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 3         | 1.01%   |
| Seiko Epson L375 Series                      | 3         | 1.01%   |
| Seiko Epson L3110 Series                     | 3         | 1.01%   |
| Seiko Epson L210 Series                      | 3         | 1.01%   |
| Samsung SCX-3200 Series                      | 3         | 1.01%   |
| HP LaserJet 1018                             | 3         | 1.01%   |
| Canon PIXMA MG3600 Series                    | 3         | 1.01%   |
| Brother HL-1200 series                       | 3         | 1.01%   |
| Seiko Epson USB2.0 Printer                   | 2         | 0.67%   |
| Seiko Epson L6160 Series                     | 2         | 0.67%   |
| Seiko Epson L380 Series                      | 2         | 0.67%   |
| Seiko Epson L120 Series                      | 2         | 0.67%   |
| Seiko Epson ET-2810 Series                   | 2         | 0.67%   |
| Seiko Epson ET-2700 Series                   | 2         | 0.67%   |
| Samsung SCX-3400 Series                      | 2         | 0.67%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.67%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 42.86%  |
| Hewlett-Packard | 8         | 38.1%   |
| Seiko Epson     | 2         | 9.52%   |
| Plustek         | 1         | 4.76%   |
| Mustek Systems  | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 23.81%  |
| Canon CanoScan LIDE 25                                  | 4         | 19.05%  |
| Canon CanoScan LiDE 110                                 | 2         | 9.52%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 4.76%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 4.76%   |
| Plustek 1200dpi USB Scanner                             | 1         | 4.76%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 4.76%   |
| HP ScanJet G4050                                        | 1         | 4.76%   |
| HP ScanJet 3800c                                        | 1         | 4.76%   |
| HP Scanjet 200                                          | 1         | 4.76%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 4.76%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 4.76%   |
| Canon CanoScan LiDE 210                                 | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1574      | 19.08%  |
| Microdia                               | 948       | 11.49%  |
| Realtek Semiconductor                  | 758       | 9.19%   |
| Quanta                                 | 650       | 7.88%   |
| Silicon Motion                         | 601       | 7.29%   |
| Sunplus Innovation Technology          | 564       | 6.84%   |
| Bison Electronics                      | 396       | 4.8%    |
| IMC Networks                           | 349       | 4.23%   |
| Logitech                               | 309       | 3.75%   |
| Suyin                                  | 302       | 3.66%   |
| Syntek                                 | 247       | 2.99%   |
| Alcor Micro                            | 161       | 1.95%   |
| Apple                                  | 140       | 1.7%    |
| Acer                                   | 131       | 1.59%   |
| Samsung Electronics                    | 104       | 1.26%   |
| Cheng Uei Precision Industry (Foxlink) | 98        | 1.19%   |
| Generalplus Technology                 | 77        | 0.93%   |
| Z-Star Microelectronics                | 66        | 0.8%    |
| Microsoft                              | 64        | 0.78%   |
| Ricoh                                  | 53        | 0.64%   |
| Sonix Technology                       | 52        | 0.63%   |
| ALi                                    | 50        | 0.61%   |
| SunplusIT                              | 36        | 0.44%   |
| GEMBIRD                                | 28        | 0.34%   |
| Aveo Technology                        | 28        | 0.34%   |
| Lite-On Technology                     | 26        | 0.32%   |
| OmniVision Technologies                | 25        | 0.3%    |
| Importek                               | 25        | 0.3%    |
| Unknown                                | 24        | 0.29%   |
| Jieli Technology                       | 23        | 0.28%   |
| Pixart Imaging                         | 22        | 0.27%   |
| icSpring                               | 22        | 0.27%   |
| LG Electronics                         | 19        | 0.23%   |
| Cubeternet                             | 19        | 0.23%   |
| Y Media                                | 16        | 0.19%   |
| Lenovo                                 | 16        | 0.19%   |
| Genesys Logic                          | 14        | 0.17%   |
| Luxvisions Innotech Limited            | 12        | 0.15%   |
| Sunplus Technology                     | 11        | 0.13%   |
| Shenzhen Kingcome Optoelectronic       | 11        | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 373       | 4.51%   |
| Realtek Integrated_Webcam_HD              | 329       | 3.98%   |
| Quanta HD User Facing                     | 283       | 3.42%   |
| Chicony HD User Facing                    | 230       | 2.78%   |
| Silicon Motion Web Camera                 | 225       | 2.72%   |
| Sunplus Integrated_Webcam_HD              | 220       | 2.66%   |
| Chicony HD WebCam                         | 208       | 2.52%   |
| Quanta VGA WebCam                         | 199       | 2.41%   |
| Chicony Integrated Camera                 | 171       | 2.07%   |
| Chicony USB 2.0 Camera                    | 150       | 1.82%   |
| Chicony VGA WebCam                        | 148       | 1.79%   |
| Syntek Integrated Camera                  | 145       | 1.75%   |
| Realtek Integrated Webcam                 | 119       | 1.44%   |
| Sunplus HD WebCam                         | 116       | 1.4%    |
| Logitech Webcam C270                      | 105       | 1.27%   |
| Samsung Galaxy series, misc. (MTP mode)   | 103       | 1.25%   |
| Alcor Micro USB 2.0 Camera                | 96        | 1.16%   |
| Quanta HD Webcam                          | 90        | 1.09%   |
| Microdia Laptop_Integrated_Webcam_HD      | 82        | 0.99%   |
| Bison EasyCamera                          | 71        | 0.86%   |
| Logitech HD Pro Webcam C920               | 66        | 0.8%    |
| IMC Networks Integrated Camera            | 66        | 0.8%    |
| Microdia Dell Laptop Integrated Webcam HD | 64        | 0.77%   |
| Bison HD Webcam                           | 63        | 0.76%   |
| Bison Lenovo EasyCamera                   | 58        | 0.7%    |
| Silicon Motion WebCam SC-10HDD12636N      | 55        | 0.67%   |
| Microdia Integrated Webcam HD             | 53        | 0.64%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 53        | 0.64%   |
| Realtek USB Camera                        | 51        | 0.62%   |
| IMC Networks USB2.0 HD UVC WebCam         | 51        | 0.62%   |
| Generalplus GENERAL WEBCAM                | 50        | 0.61%   |
| Bison BisonCam, NB Pro                    | 49        | 0.59%   |
| Sonix USB2.0 HD UVC WebCam                | 48        | 0.58%   |
| Chicony EasyCamera                        | 48        | 0.58%   |
| Bison VGA WebCam                          | 48        | 0.58%   |
| Silicon Motion WebCam SCB-1100N           | 46        | 0.56%   |
| Silicon Motion WebCam SC-13HDL11939N      | 44        | 0.53%   |
| Realtek HD WebCam                         | 44        | 0.53%   |
| Suyin Integrated_Webcam_HD                | 43        | 0.52%   |
| Syntek EasyCamera                         | 42        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 312       | 46.22%  |
| Synaptics                  | 84        | 12.44%  |
| Shenzhen Goodix Technology | 77        | 11.41%  |
| Upek                       | 63        | 9.33%   |
| AuthenTec                  | 63        | 9.33%   |
| LighTuning Technology      | 34        | 5.04%   |
| Samsung Electronics        | 19        | 2.81%   |
| Elan Microelectronics      | 11        | 1.63%   |
| STMicroelectronics         | 4         | 0.59%   |
| Futronic Technology        | 2         | 0.3%    |
| Focal-systems.Corp         | 2         | 0.3%    |
| Dell                       | 2         | 0.3%    |
| Next Biometrics            | 1         | 0.15%   |
| DigitalPersona             | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 119       | 17.63%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 53        | 7.85%   |
| Shenzhen Goodix Fingerprint Reader                     | 46        | 6.81%   |
| Validity Sensors VFS495 Fingerprint Reader             | 30        | 4.44%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 28        | 4.15%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 26        | 3.85%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 26        | 3.85%   |
| Validity Sensors VFS471 Fingerprint Reader             | 24        | 3.56%   |
| Validity Sensors Fingerprint scanner                   | 24        | 3.56%   |
| Shenzhen Goodix  FingerPrint Device                    | 22        | 3.26%   |
| Validity Sensors VFS301 Fingerprint Reader             | 20        | 2.96%   |
| Synaptics  WBDI                                        | 20        | 2.96%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 20        | 2.96%   |
| Samsung Fingerprint Device                             | 19        | 2.81%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 16        | 2.37%   |
| Validity Sensors VFS101 Fingerprint Reader             | 14        | 2.07%   |
| AuthenTec AES2810                                      | 14        | 2.07%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 14        | 2.07%   |
| Validity Sensors VFS491                                | 12        | 1.78%   |
| Validity Sensors VFS451 Fingerprint Reader             | 12        | 1.78%   |
| Elan ELAN:Fingerprint                                  | 11        | 1.63%   |
| AuthenTec Fingerprint Sensor                           | 11        | 1.63%   |
| Validity Sensors VFS300 Fingerprint Reader             | 9         | 1.33%   |
| Validity Sensors Swipe Fingerprint Sensor              | 9         | 1.33%   |
| Upek TCS5B Fingerprint sensor                          | 9         | 1.33%   |
| Shenzhen Goodix FingerPrint                            | 9         | 1.33%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 8         | 1.19%   |
| Validity Sensors Synaptics WBDI                        | 6         | 0.89%   |
| Synaptics WBDI                                         | 6         | 0.89%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 6         | 0.89%   |
| STMicroelectronics Fingerprint Reader                  | 4         | 0.59%   |
| AuthenTec AES1600                                      | 4         | 0.59%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 3         | 0.44%   |
| Synaptics Fingerprint reader [HP G6]                   | 2         | 0.3%    |
| LighTuning Fingerprint Sensor                          | 2         | 0.3%    |
| Futronic FS81 Fingerprint Scanner Module               | 2         | 0.3%    |
| Focal-systems.Corp FT9201Fingerprint.                  | 2         | 0.3%    |
| Dell MS819 Wired Mouse With Fingerprint Reader         | 2         | 0.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 0.15%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 0.15%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 96        | 45.5%   |
| Alcor Micro                       | 29        | 13.74%  |
| Gemalto (was Gemplus)             | 16        | 7.58%   |
| Lenovo                            | 14        | 6.64%   |
| Giesecke & Devrient               | 13        | 6.16%   |
| Upek                              | 10        | 4.74%   |
| Aladdin Knowledge Systems         | 8         | 3.79%   |
| Watchdata                         | 7         | 3.32%   |
| SCM Microsystems                  | 4         | 1.9%    |
| OmniKey                           | 3         | 1.42%   |
| O2 Micro                          | 3         | 1.42%   |
| Chicony Electronics               | 3         | 1.42%   |
| Castles Technology                | 2         | 0.95%   |
| VASCO Data Security International | 1         | 0.47%   |
| Realtek Semiconductor             | 1         | 0.47%   |
| Advanced Card Systems             | 1         | 0.47%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 29        | 13.74%  |
| Broadcom 58200                                                               | 27        | 12.8%   |
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 11.85%  |
| Broadcom 5880                                                                | 24        | 11.37%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 9.48%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 15        | 7.11%   |
| Lenovo Integrated Smart Card Reader                                          | 14        | 6.64%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 4.74%   |
| Aladdin Knowledge Systems Token JC                                           | 8         | 3.79%   |
| Watchdata USB Key                                                            | 7         | 3.32%   |
| Giesecke & Devrient StarSign CUT                                             | 7         | 3.32%   |
| Giesecke & Devrient StarSign CUT S                                           | 6         | 2.84%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.42%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 0.95%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.95%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.95%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 0.95%   |
| Castles Technology EZCCID Smart Card Reader                                  | 2         | 0.95%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.47%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.47%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.47%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.47%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.47%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 10716     | 78.96%  |
| 1     | 2458      | 18.11%  |
| 2     | 314       | 2.31%   |
| 3     | 53        | 0.39%   |
| 4     | 20        | 0.15%   |
| 7     | 4         | 0.03%   |
| 5     | 3         | 0.02%   |
| 8     | 2         | 0.01%   |
| 6     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1023      | 31.69%  |
| Fingerprint reader       | 671       | 20.79%  |
| Net/wireless             | 414       | 12.83%  |
| Multimedia controller    | 289       | 8.95%   |
| Chipcard                 | 179       | 5.55%   |
| Communication controller | 130       | 4.03%   |
| Bluetooth                | 103       | 3.19%   |
| Camera                   | 93        | 2.88%   |
| Unassigned class         | 70        | 2.17%   |
| Sound                    | 68        | 2.11%   |
| Storage                  | 49        | 1.52%   |
| Net/ethernet             | 40        | 1.24%   |
| Modem                    | 24        | 0.74%   |
| Flash memory             | 22        | 0.68%   |
| Card reader              | 14        | 0.43%   |
| Network                  | 10        | 0.31%   |
| Storage/ide              | 8         | 0.25%   |
| Storage/raid             | 7         | 0.22%   |
| Firewire controller      | 6         | 0.19%   |
| Storage/nvme             | 3         | 0.09%   |
| Wireless                 | 1         | 0.03%   |
| Video                    | 1         | 0.03%   |
| Unclassified device      | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

