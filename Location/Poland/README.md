Linux in Poland - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Poland/Desktop/README.md) and [notebooks](/Location/Poland/Notebook/README.md).

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

Total: 8034

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | G565 20071                  | Notebook    | [786aafb0e9](https://linux-hardware.org/?probe=786aafb0e9) | Sep 07, 2023 |
| HP            | 1589                        | Desktop     | [550b95765c](https://linux-hardware.org/?probe=550b95765c) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Dell          | 0T10XW A00                  | Desktop     | [89f4028960](https://linux-hardware.org/?probe=89f4028960) | Sep 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [01ede034b7](https://linux-hardware.org/?probe=01ede034b7) | Sep 05, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [1aa546be8c](https://linux-hardware.org/?probe=1aa546be8c) | Sep 05, 2023 |
| MSI           | P55-GD65                    | Desktop     | [2b514a72b1](https://linux-hardware.org/?probe=2b514a72b1) | Sep 05, 2023 |
| Dell          | Precision M4800             | Notebook    | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| Prestigio     | Smartbook PSB116A           | Notebook    | [d70df77a35](https://linux-hardware.org/?probe=d70df77a35) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f51b98f4cd](https://linux-hardware.org/?probe=f51b98f4cd) | Sep 04, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | Notebook    | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [26c9b8cc2c](https://linux-hardware.org/?probe=26c9b8cc2c) | Sep 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [8585671bfb](https://linux-hardware.org/?probe=8585671bfb) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [a9fdf4f92b](https://linux-hardware.org/?probe=a9fdf4f92b) | Sep 03, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [dcb8595c51](https://linux-hardware.org/?probe=dcb8595c51) | Sep 03, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [5f73c55303](https://linux-hardware.org/?probe=5f73c55303) | Sep 03, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | Notebook    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Fujitsu       | D3313-B1 S26361-D3313-B1    | Desktop     | [8533d021f8](https://linux-hardware.org/?probe=8533d021f8) | Sep 02, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [53b682d960](https://linux-hardware.org/?probe=53b682d960) | Sep 02, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [9f3df2894e](https://linux-hardware.org/?probe=9f3df2894e) | Sep 02, 2023 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [f6a5d73879](https://linux-hardware.org/?probe=f6a5d73879) | Sep 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [fd0297e4e0](https://linux-hardware.org/?probe=fd0297e4e0) | Sep 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [d5d9154715](https://linux-hardware.org/?probe=d5d9154715) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | Notebook    | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| HP            | 1589                        | Desktop     | [447cae1b4c](https://linux-hardware.org/?probe=447cae1b4c) | Sep 01, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [ff1be33f8e](https://linux-hardware.org/?probe=ff1be33f8e) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | Notebook    | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [0ac2938640](https://linux-hardware.org/?probe=0ac2938640) | Aug 31, 2023 |
| ASUSTek       | Crosshair V Formula         | Desktop     | [85cb771ac1](https://linux-hardware.org/?probe=85cb771ac1) | Aug 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ca52538b46](https://linux-hardware.org/?probe=ca52538b46) | Aug 31, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [b900fd0bc7](https://linux-hardware.org/?probe=b900fd0bc7) | Aug 31, 2023 |
| HP            | ProBook 4530s               | Notebook    | [09fddaab4d](https://linux-hardware.org/?probe=09fddaab4d) | Aug 31, 2023 |
| Dell          | Latitude 7390               | Notebook    | [a9c1ad1756](https://linux-hardware.org/?probe=a9c1ad1756) | Aug 31, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [ca7a99ecd9](https://linux-hardware.org/?probe=ca7a99ecd9) | Aug 31, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [76f095d7c2](https://linux-hardware.org/?probe=76f095d7c2) | Aug 31, 2023 |
| HP            | 8158 A01                    | Mini pc     | [9be38fb21f](https://linux-hardware.org/?probe=9be38fb21f) | Aug 30, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [f3e3f12f08](https://linux-hardware.org/?probe=f3e3f12f08) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3977e85dce](https://linux-hardware.org/?probe=3977e85dce) | Aug 30, 2023 |
| HP            | 3047h                       | Desktop     | [5a35a1ebd1](https://linux-hardware.org/?probe=5a35a1ebd1) | Aug 30, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [a2f37c4111](https://linux-hardware.org/?probe=a2f37c4111) | Aug 30, 2023 |
| Dell          | Latitude 5430               | Notebook    | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | Notebook    | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Dell          | Latitude E6520              | Notebook    | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [567a59e1bc](https://linux-hardware.org/?probe=567a59e1bc) | Aug 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| Dell          | Latitude D630               | Notebook    | [d23ff7e118](https://linux-hardware.org/?probe=d23ff7e118) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | Notebook    | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [9071631c6d](https://linux-hardware.org/?probe=9071631c6d) | Aug 28, 2023 |
| ASUSTek       | ZenBook UX362FA_UX362FA     | Convertible | [e09a09d01e](https://linux-hardware.org/?probe=e09a09d01e) | Aug 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e6e9efdb61](https://linux-hardware.org/?probe=e6e9efdb61) | Aug 26, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [af55d05855](https://linux-hardware.org/?probe=af55d05855) | Aug 26, 2023 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | Desktop     | [228bdfda30](https://linux-hardware.org/?probe=228bdfda30) | Aug 26, 2023 |
| Essentiel ... | MS-7848                     | Desktop     | [9ce89a0c87](https://linux-hardware.org/?probe=9ce89a0c87) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| Lenovo        | ThinkPad E520 1143CWG       | Notebook    | [66d9a31686](https://linux-hardware.org/?probe=66d9a31686) | Aug 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | Notebook    | [01ae0852df](https://linux-hardware.org/?probe=01ae0852df) | Aug 25, 2023 |
| Dell          | Latitude E6400              | Notebook    | [4526151015](https://linux-hardware.org/?probe=4526151015) | Aug 25, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [38448389ce](https://linux-hardware.org/?probe=38448389ce) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [bb854d7896](https://linux-hardware.org/?probe=bb854d7896) | Aug 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1f69210d69](https://linux-hardware.org/?probe=1f69210d69) | Aug 25, 2023 |
| Gigabyte      | GA-MA770T-UD3P              | Desktop     | [d1e0d41982](https://linux-hardware.org/?probe=d1e0d41982) | Aug 24, 2023 |
| Dell          | XPS 9320                    | Notebook    | [1ba8e13634](https://linux-hardware.org/?probe=1ba8e13634) | Aug 24, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [e6c72eb614](https://linux-hardware.org/?probe=e6c72eb614) | Aug 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [12ac0bf5ed](https://linux-hardware.org/?probe=12ac0bf5ed) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [097bbaf86a](https://linux-hardware.org/?probe=097bbaf86a) | Aug 24, 2023 |
| Dell          | Latitude 3520               | Notebook    | [92ef936c86](https://linux-hardware.org/?probe=92ef936c86) | Aug 24, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [71ba491330](https://linux-hardware.org/?probe=71ba491330) | Aug 24, 2023 |
| Gigabyte      | P67A-UD7-B3                 | Desktop     | [912d956729](https://linux-hardware.org/?probe=912d956729) | Aug 24, 2023 |
| ASUSTek       | EX-A320M-GAMING             | Desktop     | [a28ee4ea6b](https://linux-hardware.org/?probe=a28ee4ea6b) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | Notebook    | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5a9badb376](https://linux-hardware.org/?probe=5a9badb376) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c080c15699](https://linux-hardware.org/?probe=c080c15699) | Aug 22, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a03d5e6451](https://linux-hardware.org/?probe=a03d5e6451) | Aug 21, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [fd5614f8d1](https://linux-hardware.org/?probe=fd5614f8d1) | Aug 21, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [3911bdd51d](https://linux-hardware.org/?probe=3911bdd51d) | Aug 20, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [1979db3345](https://linux-hardware.org/?probe=1979db3345) | Aug 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [d1af143bed](https://linux-hardware.org/?probe=d1af143bed) | Aug 19, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [637bd422c5](https://linux-hardware.org/?probe=637bd422c5) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [f5751cb101](https://linux-hardware.org/?probe=f5751cb101) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [800ad97443](https://linux-hardware.org/?probe=800ad97443) | Aug 19, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [054a5a44ad](https://linux-hardware.org/?probe=054a5a44ad) | Aug 18, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [2173b6b2b0](https://linux-hardware.org/?probe=2173b6b2b0) | Aug 18, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [d84596d3c1](https://linux-hardware.org/?probe=d84596d3c1) | Aug 18, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [d05585906d](https://linux-hardware.org/?probe=d05585906d) | Aug 18, 2023 |
| Lenovo        | ThinkPad L480 20LTS6S904    | Notebook    | [32ded049ec](https://linux-hardware.org/?probe=32ded049ec) | Aug 17, 2023 |
| Valve         | Jupiter                     | Notebook    | [b2c7c5cb9f](https://linux-hardware.org/?probe=b2c7c5cb9f) | Aug 17, 2023 |
| HP            | Laptop 14-df0xxx            | Notebook    | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| Unknown       | Unknown                     | Convertible | [24b989fc80](https://linux-hardware.org/?probe=24b989fc80) | Aug 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [f3c603341d](https://linux-hardware.org/?probe=f3c603341d) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | Notebook    | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [bd75f21361](https://linux-hardware.org/?probe=bd75f21361) | Aug 16, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [4906f87d9e](https://linux-hardware.org/?probe=4906f87d9e) | Aug 16, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [abb0a09230](https://linux-hardware.org/?probe=abb0a09230) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| Lenovo        | ThinkPad T470 20HES07J00    | Notebook    | [32ec341753](https://linux-hardware.org/?probe=32ec341753) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| Samsung       | 530U4E/540U4E               | Notebook    | [7189151ffc](https://linux-hardware.org/?probe=7189151ffc) | Aug 15, 2023 |
| MSI           | H310M PRO-VDH               | Desktop     | [fe173bc6ed](https://linux-hardware.org/?probe=fe173bc6ed) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| Lenovo        | G580                        | Notebook    | [ceeee3c405](https://linux-hardware.org/?probe=ceeee3c405) | Aug 15, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [69deac32bd](https://linux-hardware.org/?probe=69deac32bd) | Aug 14, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [076c807d2d](https://linux-hardware.org/?probe=076c807d2d) | Aug 14, 2023 |
| Samsung       | 530U4E/540U4E               | Notebook    | [6a886e53b9](https://linux-hardware.org/?probe=6a886e53b9) | Aug 14, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [7ff2052c0f](https://linux-hardware.org/?probe=7ff2052c0f) | Aug 14, 2023 |
| Lenovo        | ThinkPad 10 2nd 20E4S0SQ... | Tablet      | [833489f8a8](https://linux-hardware.org/?probe=833489f8a8) | Aug 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [8af14f1aaa](https://linux-hardware.org/?probe=8af14f1aaa) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| Acer          | Predator G5-793             | Notebook    | [bb25759563](https://linux-hardware.org/?probe=bb25759563) | Aug 13, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [84b4b40450](https://linux-hardware.org/?probe=84b4b40450) | Aug 13, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [25a3921b74](https://linux-hardware.org/?probe=25a3921b74) | Aug 13, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [cf6dfa50ef](https://linux-hardware.org/?probe=cf6dfa50ef) | Aug 12, 2023 |
| Valve         | Jupiter                     | Notebook    | [b770999baf](https://linux-hardware.org/?probe=b770999baf) | Aug 12, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [b296a33ab3](https://linux-hardware.org/?probe=b296a33ab3) | Aug 12, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [b9b9ef9f84](https://linux-hardware.org/?probe=b9b9ef9f84) | Aug 12, 2023 |
| Apple         | MacBookPro13,3              | Notebook    | [b43e2738d9](https://linux-hardware.org/?probe=b43e2738d9) | Aug 12, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | Notebook    | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [7e4a63e58c](https://linux-hardware.org/?probe=7e4a63e58c) | Aug 12, 2023 |
| HP            | Pavilion dv7                | Notebook    | [fc48a936d7](https://linux-hardware.org/?probe=fc48a936d7) | Aug 12, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| HP            | 83E8                        | Desktop     | [a782638343](https://linux-hardware.org/?probe=a782638343) | Aug 11, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | Notebook    | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Google        | Kip                         | Notebook    | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d38ef662d4](https://linux-hardware.org/?probe=d38ef662d4) | Aug 10, 2023 |
| Unknown       | Unknown                     | Desktop     | [78f477986b](https://linux-hardware.org/?probe=78f477986b) | Aug 10, 2023 |
| Dell          | Latitude E6540              | Notebook    | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [a6eabbbfef](https://linux-hardware.org/?probe=a6eabbbfef) | Aug 09, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | EliteBook 845 G9            | Notebook    | [1ff8d81e4e](https://linux-hardware.org/?probe=1ff8d81e4e) | Aug 09, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a5e0e043cb](https://linux-hardware.org/?probe=a5e0e043cb) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Acer          | Aspire 5732Z                | Notebook    | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| MSI           | 970A-G43 PLUS               | Desktop     | [133d4b58c9](https://linux-hardware.org/?probe=133d4b58c9) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [f6b63d9967](https://linux-hardware.org/?probe=f6b63d9967) | Aug 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f2547c0339](https://linux-hardware.org/?probe=f2547c0339) | Aug 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [93e4fee7df](https://linux-hardware.org/?probe=93e4fee7df) | Aug 08, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [25bb416eb3](https://linux-hardware.org/?probe=25bb416eb3) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [beecacb434](https://linux-hardware.org/?probe=beecacb434) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [fb8e926bd4](https://linux-hardware.org/?probe=fb8e926bd4) | Aug 07, 2023 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [5a254fe1d6](https://linux-hardware.org/?probe=5a254fe1d6) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [164e109040](https://linux-hardware.org/?probe=164e109040) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [270c9a3ea0](https://linux-hardware.org/?probe=270c9a3ea0) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [db5a797fc0](https://linux-hardware.org/?probe=db5a797fc0) | Aug 06, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [23ecc4a8e5](https://linux-hardware.org/?probe=23ecc4a8e5) | Aug 06, 2023 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [dcd061dff8](https://linux-hardware.org/?probe=dcd061dff8) | Aug 05, 2023 |
| Dell          | 0K6VXP A00                  | Mini pc     | [4f0b615c8e](https://linux-hardware.org/?probe=4f0b615c8e) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | Notebook    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude 5421               | Notebook    | [d01013b679](https://linux-hardware.org/?probe=d01013b679) | Aug 05, 2023 |
| Dell          | Latitude 5421               | Notebook    | [5dfde4e6ac](https://linux-hardware.org/?probe=5dfde4e6ac) | Aug 05, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [420353bf79](https://linux-hardware.org/?probe=420353bf79) | Aug 04, 2023 |
| Gigabyte      | RC14UD                      | Notebook    | [6ad0758102](https://linux-hardware.org/?probe=6ad0758102) | Aug 04, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [34edcb7dae](https://linux-hardware.org/?probe=34edcb7dae) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [bd994e4cc6](https://linux-hardware.org/?probe=bd994e4cc6) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [ab2f3b8c7b](https://linux-hardware.org/?probe=ab2f3b8c7b) | Aug 04, 2023 |
| Lenovo        | Gardenia CRB SDK0J40700 ... | All in one  | [9f27152a86](https://linux-hardware.org/?probe=9f27152a86) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Lenovo        | 3140 SDK0J40697 WIN 3305... | Desktop     | [a61b8168b7](https://linux-hardware.org/?probe=a61b8168b7) | Aug 02, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [12990c5c80](https://linux-hardware.org/?probe=12990c5c80) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9be3b9bb83](https://linux-hardware.org/?probe=9be3b9bb83) | Aug 02, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [1acfa69d70](https://linux-hardware.org/?probe=1acfa69d70) | Aug 02, 2023 |
| HP            | 8054                        | Desktop     | [f53df18325](https://linux-hardware.org/?probe=f53df18325) | Aug 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8bc1531bf6](https://linux-hardware.org/?probe=8bc1531bf6) | Aug 02, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ca00849760](https://linux-hardware.org/?probe=ca00849760) | Aug 02, 2023 |
| Dell          | Inspiron 13-5368            | Notebook    | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [5d63b469f8](https://linux-hardware.org/?probe=5d63b469f8) | Aug 01, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| ECS           | H61H2-M6                    | Desktop     | [836267e5f7](https://linux-hardware.org/?probe=836267e5f7) | Aug 01, 2023 |
| HP            | 82B5                        | All in one  | [e63af4a7b9](https://linux-hardware.org/?probe=e63af4a7b9) | Aug 01, 2023 |
| Fujitsu       | D3543-A1 S26361-D3543-A1... | Desktop     | [30389578ca](https://linux-hardware.org/?probe=30389578ca) | Aug 01, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [af6a2cb993](https://linux-hardware.org/?probe=af6a2cb993) | Jul 31, 2023 |
| Gigabyte      | B75M-D3H                    | Desktop     | [3aeae112c3](https://linux-hardware.org/?probe=3aeae112c3) | Jul 31, 2023 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [ce76d8b410](https://linux-hardware.org/?probe=ce76d8b410) | Jul 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [762d07665a](https://linux-hardware.org/?probe=762d07665a) | Jul 31, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cd8671be26](https://linux-hardware.org/?probe=cd8671be26) | Jul 31, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [eb13fb97fb](https://linux-hardware.org/?probe=eb13fb97fb) | Jul 30, 2023 |
| ASUSTek       | E200HA                      | Notebook    | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [8e59554b8d](https://linux-hardware.org/?probe=8e59554b8d) | Jul 30, 2023 |
| Google        | Relm                        | Notebook    | [1c8bd1f9dd](https://linux-hardware.org/?probe=1c8bd1f9dd) | Jul 30, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [39bd06bd9b](https://linux-hardware.org/?probe=39bd06bd9b) | Jul 30, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | Notebook    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Dell          | Latitude E7240              | Notebook    | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [fad00d6412](https://linux-hardware.org/?probe=fad00d6412) | Jul 29, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [24b2f4274d](https://linux-hardware.org/?probe=24b2f4274d) | Jul 29, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [690e49362b](https://linux-hardware.org/?probe=690e49362b) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| Gigabyte      | EP45T-UD3LR                 | Desktop     | [c2928283bd](https://linux-hardware.org/?probe=c2928283bd) | Jul 28, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ca9b6e0320](https://linux-hardware.org/?probe=ca9b6e0320) | Jul 28, 2023 |
| Toshiba       | Satellite C50D-A-11G        | Notebook    | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [f0bd5c3409](https://linux-hardware.org/?probe=f0bd5c3409) | Jul 27, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Latitude 9420               | Notebook    | [03c3ca79c4](https://linux-hardware.org/?probe=03c3ca79c4) | Jul 26, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [355fadbc12](https://linux-hardware.org/?probe=355fadbc12) | Jul 26, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [863a5cb9da](https://linux-hardware.org/?probe=863a5cb9da) | Jul 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e79fd50f34](https://linux-hardware.org/?probe=e79fd50f34) | Jul 26, 2023 |
| Lenovo        | ThinkCentre M58 3231W2Y     | Desktop     | [72f09cd320](https://linux-hardware.org/?probe=72f09cd320) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [3cb7454711](https://linux-hardware.org/?probe=3cb7454711) | Jul 25, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [290a0dd297](https://linux-hardware.org/?probe=290a0dd297) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| ZOTAC         | ZBOX-BI322                  | Mini pc     | [f595927b7b](https://linux-hardware.org/?probe=f595927b7b) | Jul 25, 2023 |
| HP            | 212B                        | Desktop     | [8e6a290d51](https://linux-hardware.org/?probe=8e6a290d51) | Jul 25, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5ec24ea9ad](https://linux-hardware.org/?probe=5ec24ea9ad) | Jul 25, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [9ffd99b082](https://linux-hardware.org/?probe=9ffd99b082) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| HP            | 198E                        | Desktop     | [c2f7b19d13](https://linux-hardware.org/?probe=c2f7b19d13) | Jul 24, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [816a8d70bb](https://linux-hardware.org/?probe=816a8d70bb) | Jul 24, 2023 |
| Timi          | TM1701                      | Notebook    | [eb1246586e](https://linux-hardware.org/?probe=eb1246586e) | Jul 24, 2023 |
| ASUSTek       | F7E                         | Notebook    | [2aef1cc2c4](https://linux-hardware.org/?probe=2aef1cc2c4) | Jul 24, 2023 |
| Timi          | TM1701                      | Notebook    | [17fefbecba](https://linux-hardware.org/?probe=17fefbecba) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A715-74G             | Notebook    | [b27862dc34](https://linux-hardware.org/?probe=b27862dc34) | Jul 24, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [9243bb6a08](https://linux-hardware.org/?probe=9243bb6a08) | Jul 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a2fcdf6c36](https://linux-hardware.org/?probe=a2fcdf6c36) | Jul 24, 2023 |
| ASUSTek       | X555LD                      | Notebook    | [732fe69d59](https://linux-hardware.org/?probe=732fe69d59) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [10e8c0d4ad](https://linux-hardware.org/?probe=10e8c0d4ad) | Jul 23, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b21b29c46e](https://linux-hardware.org/?probe=b21b29c46e) | Jul 23, 2023 |
| Google        | Snappy                      | Notebook    | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Dell          | 0VD92X A00                  | Desktop     | [675e646d05](https://linux-hardware.org/?probe=675e646d05) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| ASRock        | B85M                        | Desktop     | [c4f0b0b1fa](https://linux-hardware.org/?probe=c4f0b0b1fa) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | Notebook    | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| HP            | 3032h                       | Desktop     | [f6a4202b21](https://linux-hardware.org/?probe=f6a4202b21) | Jul 21, 2023 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [73a56d2df7](https://linux-hardware.org/?probe=73a56d2df7) | Jul 21, 2023 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [d2d53e7406](https://linux-hardware.org/?probe=d2d53e7406) | Jul 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [fcdb1fdeed](https://linux-hardware.org/?probe=fcdb1fdeed) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0bd52b9adf](https://linux-hardware.org/?probe=0bd52b9adf) | Jul 20, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [26c19ee81f](https://linux-hardware.org/?probe=26c19ee81f) | Jul 19, 2023 |
| Dell          | Latitude 9420               | Notebook    | [750f80b869](https://linux-hardware.org/?probe=750f80b869) | Jul 19, 2023 |
| Dell          | Latitude 9420               | Notebook    | [a4ba4bfde1](https://linux-hardware.org/?probe=a4ba4bfde1) | Jul 19, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | Notebook    | [17c6866da9](https://linux-hardware.org/?probe=17c6866da9) | Jul 18, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [8ff38f3782](https://linux-hardware.org/?probe=8ff38f3782) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| Teclast       | F6 Pro                      | Notebook    | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | Notebook    | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [c527cf56ad](https://linux-hardware.org/?probe=c527cf56ad) | Jul 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | Notebook    | [0c460a8007](https://linux-hardware.org/?probe=0c460a8007) | Jul 17, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f4936b2064](https://linux-hardware.org/?probe=f4936b2064) | Jul 17, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [111c0b962d](https://linux-hardware.org/?probe=111c0b962d) | Jul 16, 2023 |
| Dell          | Latitude E6440              | Notebook    | [4e40dc49f3](https://linux-hardware.org/?probe=4e40dc49f3) | Jul 16, 2023 |
| HP            | Pavilion HDX9200            | Notebook    | [d893c8a2d1](https://linux-hardware.org/?probe=d893c8a2d1) | Jul 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0T101    | Notebook    | [6154504eac](https://linux-hardware.org/?probe=6154504eac) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | Notebook    | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| MSI           | GE70 2QD                    | Notebook    | [f8ddf3a3a3](https://linux-hardware.org/?probe=f8ddf3a3a3) | Jul 15, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | Notebook    | [8ce6db48b9](https://linux-hardware.org/?probe=8ce6db48b9) | Jul 15, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9e829a5538](https://linux-hardware.org/?probe=9e829a5538) | Jul 14, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [f0736c39fe](https://linux-hardware.org/?probe=f0736c39fe) | Jul 13, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Dell          | Latitude E6330              | Notebook    | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | Notebook    | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Seeed Stud... | ODYSSEY-X86J4105 SD-BS-C... | Desktop     | [b5374c8055](https://linux-hardware.org/?probe=b5374c8055) | Jul 12, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [67ef58f2b3](https://linux-hardware.org/?probe=67ef58f2b3) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | Notebook    | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | Notebook    | [a78428eb21](https://linux-hardware.org/?probe=a78428eb21) | Jul 11, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [97f39991c3](https://linux-hardware.org/?probe=97f39991c3) | Jul 11, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [1ed238ea9b](https://linux-hardware.org/?probe=1ed238ea9b) | Jul 11, 2023 |
| ASRock        | H81M                        | Desktop     | [042e2e3b56](https://linux-hardware.org/?probe=042e2e3b56) | Jul 11, 2023 |
| ASRock        | H81M                        | Desktop     | [c4b398d08c](https://linux-hardware.org/?probe=c4b398d08c) | Jul 11, 2023 |
| HP            | 82B5                        | All in one  | [3f1fecd5c3](https://linux-hardware.org/?probe=3f1fecd5c3) | Jul 11, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ab32a0e447](https://linux-hardware.org/?probe=ab32a0e447) | Jul 11, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | Notebook    | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| Google        | Guado                       | Desktop     | [d14465ad06](https://linux-hardware.org/?probe=d14465ad06) | Jul 10, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [b118891f3d](https://linux-hardware.org/?probe=b118891f3d) | Jul 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [38420a6afe](https://linux-hardware.org/?probe=38420a6afe) | Jul 10, 2023 |
| MSI           | X99A GAMING 9 ACK           | Desktop     | [4a36d070b4](https://linux-hardware.org/?probe=4a36d070b4) | Jul 10, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [73b13fd5eb](https://linux-hardware.org/?probe=73b13fd5eb) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [03da98871c](https://linux-hardware.org/?probe=03da98871c) | Jul 10, 2023 |
| HP            | 1998                        | Desktop     | [15e8251d36](https://linux-hardware.org/?probe=15e8251d36) | Jul 10, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [d4ca6c4f81](https://linux-hardware.org/?probe=d4ca6c4f81) | Jul 10, 2023 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [1e6fc6f253](https://linux-hardware.org/?probe=1e6fc6f253) | Jul 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [14c6f3f286](https://linux-hardware.org/?probe=14c6f3f286) | Jul 10, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [6a55de667a](https://linux-hardware.org/?probe=6a55de667a) | Jul 09, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [215d2135b3](https://linux-hardware.org/?probe=215d2135b3) | Jul 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [60e671ef49](https://linux-hardware.org/?probe=60e671ef49) | Jul 09, 2023 |
| ASUSTek       | X555LJ                      | Notebook    | [2dfec77944](https://linux-hardware.org/?probe=2dfec77944) | Jul 09, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b29db59f6a](https://linux-hardware.org/?probe=b29db59f6a) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [570f59305c](https://linux-hardware.org/?probe=570f59305c) | Jul 08, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [6d62d0cdbf](https://linux-hardware.org/?probe=6d62d0cdbf) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [9b8e16f852](https://linux-hardware.org/?probe=9b8e16f852) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | Notebook    | [6a67dec7ab](https://linux-hardware.org/?probe=6a67dec7ab) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | Notebook    | [b735ddd9a6](https://linux-hardware.org/?probe=b735ddd9a6) | Jul 08, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [e4bb31a52c](https://linux-hardware.org/?probe=e4bb31a52c) | Jul 07, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [2d342d7a37](https://linux-hardware.org/?probe=2d342d7a37) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [49c59b6c86](https://linux-hardware.org/?probe=49c59b6c86) | Jul 07, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [df2a737853](https://linux-hardware.org/?probe=df2a737853) | Jul 07, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [9ecae424ad](https://linux-hardware.org/?probe=9ecae424ad) | Jul 07, 2023 |
| Gigabyte      | B85M-HD3                    | Desktop     | [43034103ef](https://linux-hardware.org/?probe=43034103ef) | Jul 06, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Google        | Guado                       | Desktop     | [8bd38f802a](https://linux-hardware.org/?probe=8bd38f802a) | Jul 06, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [b7a676e2fc](https://linux-hardware.org/?probe=b7a676e2fc) | Jul 05, 2023 |
| Dell          | Latitude 7420               | Notebook    | [44c51e8365](https://linux-hardware.org/?probe=44c51e8365) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | Notebook    | [53f8e37edc](https://linux-hardware.org/?probe=53f8e37edc) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | Notebook    | [a105861e1d](https://linux-hardware.org/?probe=a105861e1d) | Jul 05, 2023 |
| Dell          | Latitude 7420               | Notebook    | [9eae2c6ad4](https://linux-hardware.org/?probe=9eae2c6ad4) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| Gigabyte      | GA-790FXTA-UD5              | Desktop     | [685f105356](https://linux-hardware.org/?probe=685f105356) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3e5dc0c313](https://linux-hardware.org/?probe=3e5dc0c313) | Jul 05, 2023 |
| HP            | 339A                        | Desktop     | [8d051ead1c](https://linux-hardware.org/?probe=8d051ead1c) | Jul 05, 2023 |
| ASRock        | Z370 Killer SLI             | Desktop     | [e7c0ca1bfc](https://linux-hardware.org/?probe=e7c0ca1bfc) | Jul 05, 2023 |
| HP            | 550                         | Notebook    | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| HP            | 650                         | Notebook    | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [71ab16d717](https://linux-hardware.org/?probe=71ab16d717) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1a32b23618](https://linux-hardware.org/?probe=1a32b23618) | Jul 04, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [abc4554a51](https://linux-hardware.org/?probe=abc4554a51) | Jul 04, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [2be3b17236](https://linux-hardware.org/?probe=2be3b17236) | Jul 04, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [df1fff149d](https://linux-hardware.org/?probe=df1fff149d) | Jul 04, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [22a13c2e16](https://linux-hardware.org/?probe=22a13c2e16) | Jul 03, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | Notebook    | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [f567c6c550](https://linux-hardware.org/?probe=f567c6c550) | Jul 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [8bb4af1cb5](https://linux-hardware.org/?probe=8bb4af1cb5) | Jul 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [67281face4](https://linux-hardware.org/?probe=67281face4) | Jul 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [f928781025](https://linux-hardware.org/?probe=f928781025) | Jul 03, 2023 |
| Acer          | FX58M                       | Desktop     | [44e563ac2a](https://linux-hardware.org/?probe=44e563ac2a) | Jul 02, 2023 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6e52890194](https://linux-hardware.org/?probe=6e52890194) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [fef890b931](https://linux-hardware.org/?probe=fef890b931) | Jul 02, 2023 |
| Google        | Relm                        | Notebook    | [ef72648bb6](https://linux-hardware.org/?probe=ef72648bb6) | Jul 02, 2023 |
| MSI           | MS-B9181                    | Desktop     | [47b3ce0c58](https://linux-hardware.org/?probe=47b3ce0c58) | Jul 02, 2023 |
| Acer          | FX58M                       | Desktop     | [69f3a5d4fb](https://linux-hardware.org/?probe=69f3a5d4fb) | Jul 02, 2023 |
| Gigabyte      | P55M-UD2                    | Desktop     | [babec703df](https://linux-hardware.org/?probe=babec703df) | Jul 02, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [03879163c2](https://linux-hardware.org/?probe=03879163c2) | Jul 02, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9e65cd9bd1](https://linux-hardware.org/?probe=9e65cd9bd1) | Jul 02, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [f923d36676](https://linux-hardware.org/?probe=f923d36676) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| Packard Be... | EasyNote TSX66HR            | Notebook    | [96253a3da8](https://linux-hardware.org/?probe=96253a3da8) | Jul 01, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [eea1d9623c](https://linux-hardware.org/?probe=eea1d9623c) | Jun 30, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c99236ef84](https://linux-hardware.org/?probe=c99236ef84) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | Notebook    | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | Latitude E6540              | Notebook    | [a526c901ee](https://linux-hardware.org/?probe=a526c901ee) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Medion        | BTDD-TI                     | All in one  | [64b84cf34d](https://linux-hardware.org/?probe=64b84cf34d) | Jun 29, 2023 |
| Gigabyte      | P31-DS3L                    | Desktop     | [0d32728bdf](https://linux-hardware.org/?probe=0d32728bdf) | Jun 28, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [34df27504f](https://linux-hardware.org/?probe=34df27504f) | Jun 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [cab34ec3dc](https://linux-hardware.org/?probe=cab34ec3dc) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | Notebook    | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [50656fb7ec](https://linux-hardware.org/?probe=50656fb7ec) | Jun 28, 2023 |
| HP            | 21B4 A01                    | Desktop     | [4d9322819d](https://linux-hardware.org/?probe=4d9322819d) | Jun 28, 2023 |
| ASUSTek       | K54C                        | Notebook    | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [0817dd25ff](https://linux-hardware.org/?probe=0817dd25ff) | Jun 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [157d424ec0](https://linux-hardware.org/?probe=157d424ec0) | Jun 26, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b4fcf1904c](https://linux-hardware.org/?probe=b4fcf1904c) | Jun 26, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e55023fb8b](https://linux-hardware.org/?probe=e55023fb8b) | Jun 26, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0b72aec1b9](https://linux-hardware.org/?probe=0b72aec1b9) | Jun 26, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| HP            | 21B4 A01                    | Desktop     | [e277fd2772](https://linux-hardware.org/?probe=e277fd2772) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [3c54b7ee02](https://linux-hardware.org/?probe=3c54b7ee02) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| eMachines     | eME732ZG                    | Notebook    | [4e1d6873ff](https://linux-hardware.org/?probe=4e1d6873ff) | Jun 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [0ec7fedf29](https://linux-hardware.org/?probe=0ec7fedf29) | Jun 24, 2023 |
| Packard Be... | EasyNote TK85               | Notebook    | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| Intel         | H81                         | Desktop     | [65ad18a4bd](https://linux-hardware.org/?probe=65ad18a4bd) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | Notebook    | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | Notebook    | [feced26491](https://linux-hardware.org/?probe=feced26491) | Jun 23, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [c75670186a](https://linux-hardware.org/?probe=c75670186a) | Jun 23, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [a036f44a4c](https://linux-hardware.org/?probe=a036f44a4c) | Jun 22, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [0b8cf1cae7](https://linux-hardware.org/?probe=0b8cf1cae7) | Jun 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [8845f67824](https://linux-hardware.org/?probe=8845f67824) | Jun 22, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d4d7534ac3](https://linux-hardware.org/?probe=d4d7534ac3) | Jun 22, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [0f5435c665](https://linux-hardware.org/?probe=0f5435c665) | Jun 22, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | Notebook    | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [d7c44291c1](https://linux-hardware.org/?probe=d7c44291c1) | Jun 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bbfb6ff07f](https://linux-hardware.org/?probe=bbfb6ff07f) | Jun 20, 2023 |
| Lenovo        | B570 HuronRiver Platform    | Notebook    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [f2d80b2558](https://linux-hardware.org/?probe=f2d80b2558) | Jun 19, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [1559b0a68d](https://linux-hardware.org/?probe=1559b0a68d) | Jun 19, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [22d8476417](https://linux-hardware.org/?probe=22d8476417) | Jun 19, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e2fc6bb607](https://linux-hardware.org/?probe=e2fc6bb607) | Jun 19, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| ASRock        | Z87 Extreme4                | Desktop     | [dcd3e79cb1](https://linux-hardware.org/?probe=dcd3e79cb1) | Jun 18, 2023 |
| HP            | Pavilion dv2                | Notebook    | [3f3b0104a4](https://linux-hardware.org/?probe=3f3b0104a4) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [17c61c0aee](https://linux-hardware.org/?probe=17c61c0aee) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| HP            | Notebook                    | Notebook    | [60eebb0602](https://linux-hardware.org/?probe=60eebb0602) | Jun 18, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [e01ed6ab42](https://linux-hardware.org/?probe=e01ed6ab42) | Jun 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f7c9224ef1](https://linux-hardware.org/?probe=f7c9224ef1) | Jun 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [f553a4e5e7](https://linux-hardware.org/?probe=f553a4e5e7) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [c60ca4bcc4](https://linux-hardware.org/?probe=c60ca4bcc4) | Jun 17, 2023 |
| Dell          | Latitude 9420               | Convertible | [444f324394](https://linux-hardware.org/?probe=444f324394) | Jun 16, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [93da970965](https://linux-hardware.org/?probe=93da970965) | Jun 16, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [858be00df4](https://linux-hardware.org/?probe=858be00df4) | Jun 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [dc48180bc7](https://linux-hardware.org/?probe=dc48180bc7) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| Dell          | Latitude E6400              | Notebook    | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | Notebook    | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| ASUSTek       | P8H61-M LX R2.0             | Desktop     | [558c031517](https://linux-hardware.org/?probe=558c031517) | Jun 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [29869b2464](https://linux-hardware.org/?probe=29869b2464) | Jun 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [bdd96d41a7](https://linux-hardware.org/?probe=bdd96d41a7) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [16ad11571a](https://linux-hardware.org/?probe=16ad11571a) | Jun 15, 2023 |
| Lenovo        | ThinkPad T490 20N20032US    | Notebook    | [3df7663e0d](https://linux-hardware.org/?probe=3df7663e0d) | Jun 15, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [c612df2e8c](https://linux-hardware.org/?probe=c612df2e8c) | Jun 15, 2023 |
| ASUSTek       | K52N                        | Notebook    | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| ASRock        | B85M                        | Desktop     | [19f8b16937](https://linux-hardware.org/?probe=19f8b16937) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | Desktop     | [dbe7676807](https://linux-hardware.org/?probe=dbe7676807) | Jun 15, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [7ae654d4e2](https://linux-hardware.org/?probe=7ae654d4e2) | Jun 14, 2023 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [39e2711f1f](https://linux-hardware.org/?probe=39e2711f1f) | Jun 13, 2023 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [2ae3c4aaca](https://linux-hardware.org/?probe=2ae3c4aaca) | Jun 13, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [ad01f2c38d](https://linux-hardware.org/?probe=ad01f2c38d) | Jun 13, 2023 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [1361d3551c](https://linux-hardware.org/?probe=1361d3551c) | Jun 12, 2023 |
| Xunlong       | Orange Pi PC                | Soc         | [2a93adb1f0](https://linux-hardware.org/?probe=2a93adb1f0) | Jun 12, 2023 |
| Dell          | 0TKM9Y A00                  | Mini pc     | [1fad9d3d52](https://linux-hardware.org/?probe=1fad9d3d52) | Jun 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | Notebook    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [2ea9fd5a4a](https://linux-hardware.org/?probe=2ea9fd5a4a) | Jun 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [273795ce3d](https://linux-hardware.org/?probe=273795ce3d) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [8a9a32ba11](https://linux-hardware.org/?probe=8a9a32ba11) | Jun 12, 2023 |
| Google        | Blorb                       | Notebook    | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [de08f65c4d](https://linux-hardware.org/?probe=de08f65c4d) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| HP            | 3397                        | Desktop     | [9f71c4173c](https://linux-hardware.org/?probe=9f71c4173c) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Dell          | Precision 5520              | Notebook    | [bcbd324c4b](https://linux-hardware.org/?probe=bcbd324c4b) | Jun 11, 2023 |
| Dell          | Precision 5520              | Notebook    | [ab408edcbd](https://linux-hardware.org/?probe=ab408edcbd) | Jun 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [d6681f05ec](https://linux-hardware.org/?probe=d6681f05ec) | Jun 11, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [0e257c3bd8](https://linux-hardware.org/?probe=0e257c3bd8) | Jun 11, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [92fd36b27a](https://linux-hardware.org/?probe=92fd36b27a) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | Notebook    | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [5d8df77ade](https://linux-hardware.org/?probe=5d8df77ade) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| MSI           | Z87-G43                     | Desktop     | [554f8ea405](https://linux-hardware.org/?probe=554f8ea405) | Jun 08, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [04d84e44a5](https://linux-hardware.org/?probe=04d84e44a5) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| Unknown       | Unknown                     | Soc         | [b23e0f6e09](https://linux-hardware.org/?probe=b23e0f6e09) | Jun 08, 2023 |
| Fujitsu       | CELSIUS H730                | Notebook    | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [022138ad16](https://linux-hardware.org/?probe=022138ad16) | Jun 06, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [50304f8088](https://linux-hardware.org/?probe=50304f8088) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df787c227](https://linux-hardware.org/?probe=1df787c227) | Jun 05, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [e22c496628](https://linux-hardware.org/?probe=e22c496628) | Jun 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [72eb9f0d86](https://linux-hardware.org/?probe=72eb9f0d86) | Jun 05, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [580ae6529e](https://linux-hardware.org/?probe=580ae6529e) | Jun 05, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| HP            | 21B4 A01                    | Desktop     | [5d394c52ed](https://linux-hardware.org/?probe=5d394c52ed) | Jun 04, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [8706eff580](https://linux-hardware.org/?probe=8706eff580) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [7af9263ba9](https://linux-hardware.org/?probe=7af9263ba9) | Jun 04, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ae24cbf98d](https://linux-hardware.org/?probe=ae24cbf98d) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [e3770a95f6](https://linux-hardware.org/?probe=e3770a95f6) | Jun 04, 2023 |
| Dell          | Latitude D620               | Notebook    | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | Notebook    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| ASUSTek       | P8H61                       | Desktop     | [7e9f999121](https://linux-hardware.org/?probe=7e9f999121) | Jun 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [1a4437e831](https://linux-hardware.org/?probe=1a4437e831) | Jun 02, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | Notebook    | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| HP            | 845A                        | Desktop     | [b68054952b](https://linux-hardware.org/?probe=b68054952b) | Jun 01, 2023 |
| Supermicro    | X8DTU                       | Server      | [2e1d03c7da](https://linux-hardware.org/?probe=2e1d03c7da) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | Notebook    | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| Unknown       | Unknown                     | Phone       | [bd6f4745f0](https://linux-hardware.org/?probe=bd6f4745f0) | Jun 01, 2023 |
| HP            | 82B5                        | All in one  | [77ecbfa91c](https://linux-hardware.org/?probe=77ecbfa91c) | Jun 01, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [b819db60d1](https://linux-hardware.org/?probe=b819db60d1) | Jun 01, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [9872e0cb5c](https://linux-hardware.org/?probe=9872e0cb5c) | May 31, 2023 |
| Inventec      | 0PY33N A01                  | Mini pc     | [01452a68b3](https://linux-hardware.org/?probe=01452a68b3) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [1903d991a3](https://linux-hardware.org/?probe=1903d991a3) | May 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| Dell          | 02N3WF A01                  | Desktop     | [c02695ea7d](https://linux-hardware.org/?probe=c02695ea7d) | May 30, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [1df34e179b](https://linux-hardware.org/?probe=1df34e179b) | May 30, 2023 |
| Dell          | 040DDP A01                  | Desktop     | [bce6b61241](https://linux-hardware.org/?probe=bce6b61241) | May 29, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [ca1cea162c](https://linux-hardware.org/?probe=ca1cea162c) | May 29, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [edfe02a7ae](https://linux-hardware.org/?probe=edfe02a7ae) | May 29, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [92b569d076](https://linux-hardware.org/?probe=92b569d076) | May 28, 2023 |
| ASRock        | G41M-VS3                    | Desktop     | [4d002c31be](https://linux-hardware.org/?probe=4d002c31be) | May 28, 2023 |
| Dell          | Latitude 7480               | Notebook    | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| Gateway       | DT55                        | Desktop     | [22d84550c6](https://linux-hardware.org/?probe=22d84550c6) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [d06e7ba405](https://linux-hardware.org/?probe=d06e7ba405) | May 28, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [9099d721d2](https://linux-hardware.org/?probe=9099d721d2) | May 27, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8311d009bd](https://linux-hardware.org/?probe=8311d009bd) | May 27, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| ASRock        | H81M-VG4                    | Desktop     | [4e7b273239](https://linux-hardware.org/?probe=4e7b273239) | May 27, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| ASUSTek       | A8N-E                       | Desktop     | [2baf5b889b](https://linux-hardware.org/?probe=2baf5b889b) | May 26, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Dell          | Latitude E5440              | Notebook    | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| Notebook      | NV4xPZ                      | Notebook    | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| Acer          | WG43M                       | Desktop     | [9afcfc4a44](https://linux-hardware.org/?probe=9afcfc4a44) | May 26, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [53db1863ab](https://linux-hardware.org/?probe=53db1863ab) | May 25, 2023 |
| ASUSTek       | GL552VW                     | Notebook    | [0466edde83](https://linux-hardware.org/?probe=0466edde83) | May 25, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d72352c0dc](https://linux-hardware.org/?probe=d72352c0dc) | May 25, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [654aa3909f](https://linux-hardware.org/?probe=654aa3909f) | May 24, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [06333c9c97](https://linux-hardware.org/?probe=06333c9c97) | May 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Acer          | Aspire E5-571G              | Notebook    | [6531b22151](https://linux-hardware.org/?probe=6531b22151) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Google        | Snappy                      | Notebook    | [8e9ad9e9d3](https://linux-hardware.org/?probe=8e9ad9e9d3) | May 24, 2023 |
| Lenovo        | Unknown                     | Notebook    | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [b5e28ef2ab](https://linux-hardware.org/?probe=b5e28ef2ab) | May 23, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [7b6c90320b](https://linux-hardware.org/?probe=7b6c90320b) | May 23, 2023 |
| Gigabyte      | B250-FinTech-CF             | Desktop     | [d8d33293ef](https://linux-hardware.org/?probe=d8d33293ef) | May 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [e4f2e7ecb6](https://linux-hardware.org/?probe=e4f2e7ecb6) | May 23, 2023 |
| HP            | 530                         | Notebook    | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| ASUSTek       | PRIME B760M-A D4            | Desktop     | [6ba02717d9](https://linux-hardware.org/?probe=6ba02717d9) | May 22, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| MSI           | B360M PRO-VDH               | Desktop     | [93a41eca5e](https://linux-hardware.org/?probe=93a41eca5e) | May 22, 2023 |
| Dell          | Latitude 3190               | Notebook    | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [46de86898c](https://linux-hardware.org/?probe=46de86898c) | May 22, 2023 |
| Medion        | BTDD-TI                     | All in one  | [ef28026334](https://linux-hardware.org/?probe=ef28026334) | May 22, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [e7af79968d](https://linux-hardware.org/?probe=e7af79968d) | May 22, 2023 |
| ASUSTek       | K84L                        | Notebook    | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [b160fbf41e](https://linux-hardware.org/?probe=b160fbf41e) | May 21, 2023 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [cc90a5ca05](https://linux-hardware.org/?probe=cc90a5ca05) | May 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [03b17bc271](https://linux-hardware.org/?probe=03b17bc271) | May 21, 2023 |
| HP            | Unknown                     | Notebook    | [8894bf0f31](https://linux-hardware.org/?probe=8894bf0f31) | May 21, 2023 |
| Gigabyte      | GA-78LMT-S2PT               | Desktop     | [04ea462ce6](https://linux-hardware.org/?probe=04ea462ce6) | May 21, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [2e68f6cae7](https://linux-hardware.org/?probe=2e68f6cae7) | May 21, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [f7d7036598](https://linux-hardware.org/?probe=f7d7036598) | May 21, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [72adb50172](https://linux-hardware.org/?probe=72adb50172) | May 20, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [50e85498e7](https://linux-hardware.org/?probe=50e85498e7) | May 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [cf5c419d13](https://linux-hardware.org/?probe=cf5c419d13) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [87e60904b9](https://linux-hardware.org/?probe=87e60904b9) | May 20, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Dell          | 0F3KHR A01                  | Desktop     | [c48ab194c6](https://linux-hardware.org/?probe=c48ab194c6) | May 20, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [db9774a799](https://linux-hardware.org/?probe=db9774a799) | May 19, 2023 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [76bae0c7fb](https://linux-hardware.org/?probe=76bae0c7fb) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | Notebook    | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| Intel         | NUC12WSBi7 M46422-304       | Mini pc     | [b63f2ef351](https://linux-hardware.org/?probe=b63f2ef351) | May 18, 2023 |
| Medion        | BTDD-TI                     | All in one  | [cc45e1f2f4](https://linux-hardware.org/?probe=cc45e1f2f4) | May 18, 2023 |
| MSI           | GL75 9SE                    | Notebook    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [99d6173179](https://linux-hardware.org/?probe=99d6173179) | May 18, 2023 |
| Dell          | 0GDG8Y A00                  | Desktop     | [bc0a4ba851](https://linux-hardware.org/?probe=bc0a4ba851) | May 18, 2023 |
| Lenovo        | 1030 SDK0J40697 WIN 3305... | Desktop     | [af1e17cc95](https://linux-hardware.org/?probe=af1e17cc95) | May 17, 2023 |
| ASUSTek       | P5G41T-M                    | Desktop     | [89d938fcef](https://linux-hardware.org/?probe=89d938fcef) | May 17, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [200610da74](https://linux-hardware.org/?probe=200610da74) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [2f6a330442](https://linux-hardware.org/?probe=2f6a330442) | May 17, 2023 |
| Google        | Snappy                      | Notebook    | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [197ec890d6](https://linux-hardware.org/?probe=197ec890d6) | May 16, 2023 |
| Pegatron      | VIOLET                      | Desktop     | [fa6dc417d4](https://linux-hardware.org/?probe=fa6dc417d4) | May 16, 2023 |
| Foxconn       | P35A01                      | Desktop     | [d3f10a59ba](https://linux-hardware.org/?probe=d3f10a59ba) | May 16, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [db27da6896](https://linux-hardware.org/?probe=db27da6896) | May 15, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [d4ad39c5d7](https://linux-hardware.org/?probe=d4ad39c5d7) | May 15, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [4a352d010e](https://linux-hardware.org/?probe=4a352d010e) | May 15, 2023 |
| Dell          | Latitude 3190               | Notebook    | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [0aa84055bf](https://linux-hardware.org/?probe=0aa84055bf) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [3466945196](https://linux-hardware.org/?probe=3466945196) | May 15, 2023 |
| HP            | 339A                        | Desktop     | [35fdefb4eb](https://linux-hardware.org/?probe=35fdefb4eb) | May 15, 2023 |
| Lenovo        | B590 20206                  | Notebook    | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | B50-70 20384                | Notebook    | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Lenovo        | ThinkCentre M58 7627AD5     | Desktop     | [e0b4de3daf](https://linux-hardware.org/?probe=e0b4de3daf) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | Notebook    | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [660bd404a0](https://linux-hardware.org/?probe=660bd404a0) | May 14, 2023 |
| ASUSTek       | K53BR                       | Notebook    | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [091a42a1c0](https://linux-hardware.org/?probe=091a42a1c0) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [309a617781](https://linux-hardware.org/?probe=309a617781) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [55abeba9a3](https://linux-hardware.org/?probe=55abeba9a3) | May 13, 2023 |
| Dell          | 0GWHMW A00                  | Desktop     | [d2dbc10885](https://linux-hardware.org/?probe=d2dbc10885) | May 13, 2023 |
| Gigabyte      | B360M DS3H                  | Desktop     | [82dbe1cdf7](https://linux-hardware.org/?probe=82dbe1cdf7) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | Notebook    | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | Notebook    | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [8fdc05a6ad](https://linux-hardware.org/?probe=8fdc05a6ad) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | Notebook    | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [6950584e4c](https://linux-hardware.org/?probe=6950584e4c) | May 12, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [29b8cfc7e6](https://linux-hardware.org/?probe=29b8cfc7e6) | May 12, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [9f88d81e33](https://linux-hardware.org/?probe=9f88d81e33) | May 12, 2023 |
| HP            | ProBook 4535s               | Notebook    | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | 3047h                       | Desktop     | [bb0087d307](https://linux-hardware.org/?probe=bb0087d307) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | Notebook    | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [b9a3dfd029](https://linux-hardware.org/?probe=b9a3dfd029) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| Toshiba       | Satellite L40               | Notebook    | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e0ebf9fa8a](https://linux-hardware.org/?probe=e0ebf9fa8a) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [4ca3ad7158](https://linux-hardware.org/?probe=4ca3ad7158) | May 11, 2023 |
| ASUSTek       | B85-PLUS                    | Desktop     | [9346ce422f](https://linux-hardware.org/?probe=9346ce422f) | May 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [5bfb32e683](https://linux-hardware.org/?probe=5bfb32e683) | May 11, 2023 |
| HP            | EliteBook 745 G3            | Notebook    | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [7a97d5d5ab](https://linux-hardware.org/?probe=7a97d5d5ab) | May 10, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | Notebook    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| MSI           | B85-G43                     | Desktop     | [878fbbb243](https://linux-hardware.org/?probe=878fbbb243) | May 09, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | Notebook    | [6272f76b0b](https://linux-hardware.org/?probe=6272f76b0b) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | Notebook    | [e3cc11d5e4](https://linux-hardware.org/?probe=e3cc11d5e4) | May 08, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [afe5236688](https://linux-hardware.org/?probe=afe5236688) | May 08, 2023 |
| Dell          | Latitude 3190               | Notebook    | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [a8e82695ee](https://linux-hardware.org/?probe=a8e82695ee) | May 08, 2023 |
| Valve         | Jupiter                     | Notebook    | [e6397e7f9f](https://linux-hardware.org/?probe=e6397e7f9f) | May 08, 2023 |
| HP            | 15                          | Notebook    | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | Latitude 5520               | Notebook    | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| Acer          | TravelMate 6592             | Notebook    | [d655aad3c5](https://linux-hardware.org/?probe=d655aad3c5) | May 07, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [c0ade7c98e](https://linux-hardware.org/?probe=c0ade7c98e) | May 07, 2023 |
| Dell          | Latitude 5290               | Notebook    | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | Notebook    | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a1e7385ffa](https://linux-hardware.org/?probe=a1e7385ffa) | May 07, 2023 |
| Gigabyte      | G41M-Combo                  | Desktop     | [077ced1a40](https://linux-hardware.org/?probe=077ced1a40) | May 06, 2023 |
| Fujitsu Si... | D2804-A1 S26361-D2804-A1    | Desktop     | [4278efc4ca](https://linux-hardware.org/?probe=4278efc4ca) | May 06, 2023 |
| Toshiba       | Satellite L300D             | Notebook    | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [50fba20da2](https://linux-hardware.org/?probe=50fba20da2) | May 05, 2023 |
| ASUSTek       | K75DE                       | Notebook    | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [8774a893d6](https://linux-hardware.org/?probe=8774a893d6) | May 05, 2023 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [b8f920797f](https://linux-hardware.org/?probe=b8f920797f) | May 05, 2023 |
| Dell          | Inspiron 5770               | Notebook    | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| Gigabyte      | GA-MA790XT-UD4P             | Desktop     | [c9a5bee99d](https://linux-hardware.org/?probe=c9a5bee99d) | May 05, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [6aa9a8317d](https://linux-hardware.org/?probe=6aa9a8317d) | May 04, 2023 |
| HP            | EliteBook x360 1030 G3      | Convertible | [08a19ae7b9](https://linux-hardware.org/?probe=08a19ae7b9) | May 04, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| HP            | EliteBook 8540p             | Notebook    | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Google        | Meep                        | Notebook    | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | Latitude 5490               | Notebook    | [20c5ad2ee2](https://linux-hardware.org/?probe=20c5ad2ee2) | May 03, 2023 |
| Dell          | Latitude E6410              | Notebook    | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [91f2551511](https://linux-hardware.org/?probe=91f2551511) | May 03, 2023 |
| Packard Be... | EasyNote TE69BM             | Notebook    | [fc905a42fb](https://linux-hardware.org/?probe=fc905a42fb) | May 03, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Dell          | 09WH54 A00                  | Desktop     | [0afa4006cd](https://linux-hardware.org/?probe=0afa4006cd) | May 03, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [795672236a](https://linux-hardware.org/?probe=795672236a) | May 02, 2023 |
| Packard Be... | EasyNote LJ65               | Notebook    | [77860cab79](https://linux-hardware.org/?probe=77860cab79) | May 02, 2023 |
| HP            | 1589                        | Desktop     | [c817b08584](https://linux-hardware.org/?probe=c817b08584) | May 02, 2023 |
| HP            | 1589                        | Desktop     | [890241aeb6](https://linux-hardware.org/?probe=890241aeb6) | May 02, 2023 |
| Lenovo        | SHARKBAY NO DPK             | Desktop     | [01bd34ece8](https://linux-hardware.org/?probe=01bd34ece8) | May 01, 2023 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [211eb49a00](https://linux-hardware.org/?probe=211eb49a00) | May 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [15c40bae27](https://linux-hardware.org/?probe=15c40bae27) | May 01, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [a644bc676e](https://linux-hardware.org/?probe=a644bc676e) | May 01, 2023 |
| HP            | Compaq 6910p                | Notebook    | [a697e756f5](https://linux-hardware.org/?probe=a697e756f5) | May 01, 2023 |
| Dell          | Latitude 3190               | Notebook    | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c03693e806](https://linux-hardware.org/?probe=c03693e806) | May 01, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2fcc250a35](https://linux-hardware.org/?probe=2fcc250a35) | May 01, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| MSI           | B450M PRO-M2                | Desktop     | [b650f0a26e](https://linux-hardware.org/?probe=b650f0a26e) | Apr 30, 2023 |
| Dell          | Latitude XT2                | Notebook    | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| Acer          | AO725                       | Notebook    | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [ff639a78ec](https://linux-hardware.org/?probe=ff639a78ec) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | Notebook    | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| ASRock        | Z370 Gaming K6              | Desktop     | [a5ff738639](https://linux-hardware.org/?probe=a5ff738639) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7c378d88a2](https://linux-hardware.org/?probe=7c378d88a2) | Apr 29, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ee996917df](https://linux-hardware.org/?probe=ee996917df) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f502c40867](https://linux-hardware.org/?probe=f502c40867) | Apr 29, 2023 |
| Acer          | Aspire V5-552G              | Notebook    | [07c58a5169](https://linux-hardware.org/?probe=07c58a5169) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [b2c012c1e2](https://linux-hardware.org/?probe=b2c012c1e2) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [23b5cbfb33](https://linux-hardware.org/?probe=23b5cbfb33) | Apr 27, 2023 |
| Acer          | Aspire 7250                 | Notebook    | [8e8e082e3d](https://linux-hardware.org/?probe=8e8e082e3d) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | Notebook    | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| ASUSTek       | P5K/EPU                     | Desktop     | [33ef71c7e7](https://linux-hardware.org/?probe=33ef71c7e7) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [f1f2ad2731](https://linux-hardware.org/?probe=f1f2ad2731) | Apr 26, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [a3065a1b59](https://linux-hardware.org/?probe=a3065a1b59) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | Notebook    | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [856de630ec](https://linux-hardware.org/?probe=856de630ec) | Apr 25, 2023 |
| Dell          | Cherry Trail CR A00         | Mini pc     | [f1fb89d0f7](https://linux-hardware.org/?probe=f1fb89d0f7) | Apr 25, 2023 |
| Dell          | 03NVJ6 A02                  | Desktop     | [74a0632f6e](https://linux-hardware.org/?probe=74a0632f6e) | Apr 25, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | Notebook    | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3eb401d939](https://linux-hardware.org/?probe=3eb401d939) | Apr 25, 2023 |
| Dell          | Latitude E5470              | Notebook    | [37fabb89aa](https://linux-hardware.org/?probe=37fabb89aa) | Apr 25, 2023 |
| Lenovo        | G700                        | Notebook    | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [9649423c20](https://linux-hardware.org/?probe=9649423c20) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [af486ae4ae](https://linux-hardware.org/?probe=af486ae4ae) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| Medion        | X681X                       | Notebook    | [d72837ad07](https://linux-hardware.org/?probe=d72837ad07) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [76b3daef92](https://linux-hardware.org/?probe=76b3daef92) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| Dell          | Latitude 3190               | Notebook    | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7bbac9f9bf](https://linux-hardware.org/?probe=7bbac9f9bf) | Apr 24, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [35c362eb4f](https://linux-hardware.org/?probe=35c362eb4f) | Apr 24, 2023 |
| Samsung       | R510/P510                   | Notebook    | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [f98c5f7d2e](https://linux-hardware.org/?probe=f98c5f7d2e) | Apr 23, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [e959cc70fa](https://linux-hardware.org/?probe=e959cc70fa) | Apr 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [652e029529](https://linux-hardware.org/?probe=652e029529) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [bee909cfcd](https://linux-hardware.org/?probe=bee909cfcd) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c101faa12e](https://linux-hardware.org/?probe=c101faa12e) | Apr 23, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [1c439a695b](https://linux-hardware.org/?probe=1c439a695b) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Dell          | Precision 7550              | Notebook    | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Dell          | Latitude D620               | Notebook    | [7b0c5ec6f2](https://linux-hardware.org/?probe=7b0c5ec6f2) | Apr 22, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [510237facd](https://linux-hardware.org/?probe=510237facd) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | Notebook    | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [c1139db413](https://linux-hardware.org/?probe=c1139db413) | Apr 22, 2023 |
| MSI           | P55-GD65                    | Desktop     | [90cc53b6dd](https://linux-hardware.org/?probe=90cc53b6dd) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [3056a65306](https://linux-hardware.org/?probe=3056a65306) | Apr 22, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [51ef82c2fd](https://linux-hardware.org/?probe=51ef82c2fd) | Apr 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [be207ea29f](https://linux-hardware.org/?probe=be207ea29f) | Apr 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [87d3a8b29f](https://linux-hardware.org/?probe=87d3a8b29f) | Apr 20, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [cde1ecf1c6](https://linux-hardware.org/?probe=cde1ecf1c6) | Apr 20, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [904089ce14](https://linux-hardware.org/?probe=904089ce14) | Apr 20, 2023 |
| Dell          | Precision M6600             | Notebook    | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | Notebook    | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [1396746fba](https://linux-hardware.org/?probe=1396746fba) | Apr 20, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| Dell          | Latitude 7410               | Notebook    | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | Notebook    | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Dell          | Precision M6800             | Notebook    | [b39d3f31df](https://linux-hardware.org/?probe=b39d3f31df) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [a0b6c23c0b](https://linux-hardware.org/?probe=a0b6c23c0b) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [35ec02005f](https://linux-hardware.org/?probe=35ec02005f) | Apr 17, 2023 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [0244194778](https://linux-hardware.org/?probe=0244194778) | Apr 17, 2023 |
| Acer          | Swift SFA16-41              | Notebook    | [1232f86e3e](https://linux-hardware.org/?probe=1232f86e3e) | Apr 17, 2023 |
| Dell          | Latitude D830               | Notebook    | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | Notebook    | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [c59c5c0cdf](https://linux-hardware.org/?probe=c59c5c0cdf) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [391b43ba8c](https://linux-hardware.org/?probe=391b43ba8c) | Apr 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [c8513ddcf3](https://linux-hardware.org/?probe=c8513ddcf3) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [4fad8fc758](https://linux-hardware.org/?probe=4fad8fc758) | Apr 16, 2023 |
| Dell          | Latitude E6330              | Notebook    | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| Acer          | AO722                       | Notebook    | [af4e100c16](https://linux-hardware.org/?probe=af4e100c16) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [7613566248](https://linux-hardware.org/?probe=7613566248) | Apr 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [9206720811](https://linux-hardware.org/?probe=9206720811) | Apr 14, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [3c77a2b081](https://linux-hardware.org/?probe=3c77a2b081) | Apr 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [c1558fbc72](https://linux-hardware.org/?probe=c1558fbc72) | Apr 14, 2023 |
| MSI           | B85-G43                     | Desktop     | [0363360efa](https://linux-hardware.org/?probe=0363360efa) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [9341670151](https://linux-hardware.org/?probe=9341670151) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 4291AY8       | Notebook    | [b2bc70473d](https://linux-hardware.org/?probe=b2bc70473d) | Apr 13, 2023 |
| Dell          | 0GXM1W A00                  | Desktop     | [f96d907026](https://linux-hardware.org/?probe=f96d907026) | Apr 13, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [5586a15d29](https://linux-hardware.org/?probe=5586a15d29) | Apr 13, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [1d6ace19a5](https://linux-hardware.org/?probe=1d6ace19a5) | Apr 13, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [d21971f30f](https://linux-hardware.org/?probe=d21971f30f) | Apr 13, 2023 |
| Dell          | Latitude E6230              | Notebook    | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Acer          | WG43M                       | Desktop     | [e22afb229d](https://linux-hardware.org/?probe=e22afb229d) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | Notebook    | [f1999ee14e](https://linux-hardware.org/?probe=f1999ee14e) | Apr 11, 2023 |
| HP            | 8158 A01                    | Mini pc     | [a7d7e5c675](https://linux-hardware.org/?probe=a7d7e5c675) | Apr 11, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [b85f3476ed](https://linux-hardware.org/?probe=b85f3476ed) | Apr 11, 2023 |
| Dell          | Latitude 7390               | Notebook    | [9361f06955](https://linux-hardware.org/?probe=9361f06955) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | Notebook    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| HP            | Pavilion dv7                | Notebook    | [000c77d7d5](https://linux-hardware.org/?probe=000c77d7d5) | Apr 10, 2023 |
| HP            | Pavilion dv7                | Notebook    | [08e5108cda](https://linux-hardware.org/?probe=08e5108cda) | Apr 10, 2023 |
| HP            | 3032h                       | Desktop     | [824604840a](https://linux-hardware.org/?probe=824604840a) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [d829fac91c](https://linux-hardware.org/?probe=d829fac91c) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [bd05976130](https://linux-hardware.org/?probe=bd05976130) | Apr 10, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [001091b5fd](https://linux-hardware.org/?probe=001091b5fd) | Apr 10, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [34f1d57aec](https://linux-hardware.org/?probe=34f1d57aec) | Apr 10, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0beaf2366c](https://linux-hardware.org/?probe=0beaf2366c) | Apr 09, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | Notebook    | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [6f8748297a](https://linux-hardware.org/?probe=6f8748297a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [869d7607e9](https://linux-hardware.org/?probe=869d7607e9) | Apr 08, 2023 |
| Acer          | Aspire 5336                 | Notebook    | [6e419f3401](https://linux-hardware.org/?probe=6e419f3401) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | Notebook    | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| MSI           | MS-B0A21                    | Desktop     | [93db7f66f1](https://linux-hardware.org/?probe=93db7f66f1) | Apr 08, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [370d1404f2](https://linux-hardware.org/?probe=370d1404f2) | Apr 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [b8dd840f5d](https://linux-hardware.org/?probe=b8dd840f5d) | Apr 08, 2023 |
| Samsung       | 400B4C/400B5C/200B4C/200... | Notebook    | [8026ca606e](https://linux-hardware.org/?probe=8026ca606e) | Apr 07, 2023 |
| Dell          | Inspiron 11-3162            | Notebook    | [accdfd2253](https://linux-hardware.org/?probe=accdfd2253) | Apr 07, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [7d4b6838e2](https://linux-hardware.org/?probe=7d4b6838e2) | Apr 07, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [413528fa5a](https://linux-hardware.org/?probe=413528fa5a) | Apr 07, 2023 |
| MSI           | GP76 Leopard 10UE           | Notebook    | [c7b870bb22](https://linux-hardware.org/?probe=c7b870bb22) | Apr 07, 2023 |
| Toshiba       | Satellite C855-12N          | Notebook    | [69e30b2fd8](https://linux-hardware.org/?probe=69e30b2fd8) | Apr 07, 2023 |
| HP            | 620                         | Notebook    | [2e14b2c046](https://linux-hardware.org/?probe=2e14b2c046) | Apr 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | ProBook 4740s               | Notebook    | [14fb51de44](https://linux-hardware.org/?probe=14fb51de44) | Apr 06, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [a71051ab5a](https://linux-hardware.org/?probe=a71051ab5a) | Apr 06, 2023 |
| eMachines     | E720 V1.09                  | Notebook    | [278ca903ac](https://linux-hardware.org/?probe=278ca903ac) | Apr 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Samsung       | 730U3E/740U3E               | Notebook    | [2be8e6430c](https://linux-hardware.org/?probe=2be8e6430c) | Apr 05, 2023 |
| Kruger&Mat... | KM1406                      | Notebook    | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f1398d5ada](https://linux-hardware.org/?probe=f1398d5ada) | Apr 05, 2023 |
| Toshiba       | Satellite C50-A             | Notebook    | [8e02a6dbed](https://linux-hardware.org/?probe=8e02a6dbed) | Apr 05, 2023 |
| ASRock        | B75 Pro3-M                  | Desktop     | [81b76a458e](https://linux-hardware.org/?probe=81b76a458e) | Apr 05, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [b469666726](https://linux-hardware.org/?probe=b469666726) | Apr 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [b9e77efbb1](https://linux-hardware.org/?probe=b9e77efbb1) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Google        | Cyan                        | Notebook    | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [379f9d7af7](https://linux-hardware.org/?probe=379f9d7af7) | Apr 04, 2023 |
| HP            | 82B5                        | All in one  | [59fe255866](https://linux-hardware.org/?probe=59fe255866) | Apr 04, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [6e8ca2befa](https://linux-hardware.org/?probe=6e8ca2befa) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| Lenovo        | B50-80 80LT                 | Notebook    | [163bfb5525](https://linux-hardware.org/?probe=163bfb5525) | Apr 03, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [64fa944dfd](https://linux-hardware.org/?probe=64fa944dfd) | Apr 03, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [f0026163c3](https://linux-hardware.org/?probe=f0026163c3) | Apr 03, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [71a388a292](https://linux-hardware.org/?probe=71a388a292) | Apr 03, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [7c4676c380](https://linux-hardware.org/?probe=7c4676c380) | Apr 03, 2023 |
| HP            | Stream Notebook             | Notebook    | [27610e0a39](https://linux-hardware.org/?probe=27610e0a39) | Apr 03, 2023 |
| MSI           | PH67A-C43                   | Desktop     | [8e7c8a3d67](https://linux-hardware.org/?probe=8e7c8a3d67) | Apr 03, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [59bdd9d328](https://linux-hardware.org/?probe=59bdd9d328) | Apr 03, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [79ec23e706](https://linux-hardware.org/?probe=79ec23e706) | Apr 03, 2023 |
| ASUSTek       | TP300LJ                     | Notebook    | [7da5aab332](https://linux-hardware.org/?probe=7da5aab332) | Apr 02, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [c98048fb64](https://linux-hardware.org/?probe=c98048fb64) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME      | Desktop     | [03fe72ba57](https://linux-hardware.org/?probe=03fe72ba57) | Apr 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [60e80d51ab](https://linux-hardware.org/?probe=60e80d51ab) | Apr 02, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [a51ad3deda](https://linux-hardware.org/?probe=a51ad3deda) | Apr 02, 2023 |
| HP            | ProBook 455 G1              | Notebook    | [869f36fc4c](https://linux-hardware.org/?probe=869f36fc4c) | Apr 01, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [b7848305ec](https://linux-hardware.org/?probe=b7848305ec) | Apr 01, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [383835a445](https://linux-hardware.org/?probe=383835a445) | Apr 01, 2023 |
| Lenovo        | G560 20042                  | Notebook    | [c5a4783dfb](https://linux-hardware.org/?probe=c5a4783dfb) | Apr 01, 2023 |
| Dell          | 0TTDMJ A00                  | Desktop     | [5d6606235d](https://linux-hardware.org/?probe=5d6606235d) | Apr 01, 2023 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [dff9959cd7](https://linux-hardware.org/?probe=dff9959cd7) | Mar 31, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [e5a729243d](https://linux-hardware.org/?probe=e5a729243d) | Mar 31, 2023 |
| Samsung       | 950XED                      | Notebook    | [c3b37a213a](https://linux-hardware.org/?probe=c3b37a213a) | Mar 31, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [4d69417ed0](https://linux-hardware.org/?probe=4d69417ed0) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6e93ca4159](https://linux-hardware.org/?probe=6e93ca4159) | Mar 31, 2023 |
| Acer          | TravelMate 8172Z            | Notebook    | [10cc090653](https://linux-hardware.org/?probe=10cc090653) | Mar 31, 2023 |
| Dell          | Latitude D620               | Notebook    | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| Acer          | WG43M                       | Desktop     | [3b626d2ff9](https://linux-hardware.org/?probe=3b626d2ff9) | Mar 31, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [aa9a729217](https://linux-hardware.org/?probe=aa9a729217) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| ASRock        | X670E PG Lightning          | Desktop     | [6078dd3087](https://linux-hardware.org/?probe=6078dd3087) | Mar 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [f78b6ab8c5](https://linux-hardware.org/?probe=f78b6ab8c5) | Mar 30, 2023 |
| ASUSTek       | M4A77T/USB3                 | Desktop     | [b593e25f2a](https://linux-hardware.org/?probe=b593e25f2a) | Mar 30, 2023 |
| Intel         | DQ45CB E30148-207           | Desktop     | [e47e1626c3](https://linux-hardware.org/?probe=e47e1626c3) | Mar 29, 2023 |
| Dell          | Latitude E6530              | Notebook    | [eb7392d1ae](https://linux-hardware.org/?probe=eb7392d1ae) | Mar 29, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [680c7a04ed](https://linux-hardware.org/?probe=680c7a04ed) | Mar 29, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [e7b163ea80](https://linux-hardware.org/?probe=e7b163ea80) | Mar 29, 2023 |
| GPD           | G1621-02                    | Notebook    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fa1a582da6](https://linux-hardware.org/?probe=fa1a582da6) | Mar 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [94cdfc44d1](https://linux-hardware.org/?probe=94cdfc44d1) | Mar 28, 2023 |
| Kiano         | Elegance 14.2               | Notebook    | [ea2013b347](https://linux-hardware.org/?probe=ea2013b347) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | Notebook    | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Notebook    | [856b789461](https://linux-hardware.org/?probe=856b789461) | Mar 28, 2023 |
| Dell          | Latitude 7490               | Notebook    | [41d01ead49](https://linux-hardware.org/?probe=41d01ead49) | Mar 28, 2023 |
| Dell          | 0G261D A00                  | Desktop     | [f63f67f28f](https://linux-hardware.org/?probe=f63f67f28f) | Mar 28, 2023 |
| ASRock        | Z77 Extreme6                | Desktop     | [365cc196f2](https://linux-hardware.org/?probe=365cc196f2) | Mar 27, 2023 |
| Dell          | Inspiron 5735               | Notebook    | [823a6ece98](https://linux-hardware.org/?probe=823a6ece98) | Mar 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS47P00    | Notebook    | [e287203572](https://linux-hardware.org/?probe=e287203572) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [16ba0fa199](https://linux-hardware.org/?probe=16ba0fa199) | Mar 27, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7d0c0336c1](https://linux-hardware.org/?probe=7d0c0336c1) | Mar 27, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [aaeb6059a2](https://linux-hardware.org/?probe=aaeb6059a2) | Mar 27, 2023 |
| HP            | 895D                        | Desktop     | [1cba23395d](https://linux-hardware.org/?probe=1cba23395d) | Mar 27, 2023 |
| Dell          | Precision 7670              | Notebook    | [eece926391](https://linux-hardware.org/?probe=eece926391) | Mar 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| HP            | 1998                        | Desktop     | [2d5e0737e5](https://linux-hardware.org/?probe=2d5e0737e5) | Mar 27, 2023 |
| Dell          | Precision 7670              | Notebook    | [5b8f0590ec](https://linux-hardware.org/?probe=5b8f0590ec) | Mar 27, 2023 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [1c37ecb6c7](https://linux-hardware.org/?probe=1c37ecb6c7) | Mar 26, 2023 |
| ASRock        | AM1H-ITX                    | Desktop     | [8f1dcf05eb](https://linux-hardware.org/?probe=8f1dcf05eb) | Mar 26, 2023 |
| HP            | ProLiant DL360 G7           | Server      | [4e4f63c868](https://linux-hardware.org/?probe=4e4f63c868) | Mar 26, 2023 |
| Acer          | WG43M                       | Desktop     | [74320e2d13](https://linux-hardware.org/?probe=74320e2d13) | Mar 26, 2023 |
| Lenovo        | ThinkPad T520 4243RP3       | Notebook    | [38fa314d2f](https://linux-hardware.org/?probe=38fa314d2f) | Mar 26, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [0a19e934c3](https://linux-hardware.org/?probe=0a19e934c3) | Mar 26, 2023 |
| MSI           | Creator Z16 A11UET          | Notebook    | [0133ab37af](https://linux-hardware.org/?probe=0133ab37af) | Mar 26, 2023 |
| Sony          | VGN-BX61VN                  | Notebook    | [76f62cf9c1](https://linux-hardware.org/?probe=76f62cf9c1) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [45abc5547d](https://linux-hardware.org/?probe=45abc5547d) | Mar 26, 2023 |
| Lenovo        | G510 20238                  | Notebook    | [f406bad420](https://linux-hardware.org/?probe=f406bad420) | Mar 26, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [4fcf740ee9](https://linux-hardware.org/?probe=4fcf740ee9) | Mar 25, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [71fc8dc05c](https://linux-hardware.org/?probe=71fc8dc05c) | Mar 25, 2023 |
| Lenovo        | ThinkPad W520 4282PQ7       | Notebook    | [ff42aa158f](https://linux-hardware.org/?probe=ff42aa158f) | Mar 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [1301dd9965](https://linux-hardware.org/?probe=1301dd9965) | Mar 25, 2023 |
| HP            | Notebook                    | Notebook    | [7c4088912e](https://linux-hardware.org/?probe=7c4088912e) | Mar 25, 2023 |
| HP            | EliteBook x360 1040 G5      | Convertible | [eaf933f33a](https://linux-hardware.org/?probe=eaf933f33a) | Mar 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [caa720b95b](https://linux-hardware.org/?probe=caa720b95b) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | Notebook    | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [6a7628c31d](https://linux-hardware.org/?probe=6a7628c31d) | Mar 25, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [c7bf2c9968](https://linux-hardware.org/?probe=c7bf2c9968) | Mar 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [29a94d3d9e](https://linux-hardware.org/?probe=29a94d3d9e) | Mar 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c3a6c3f669](https://linux-hardware.org/?probe=c3a6c3f669) | Mar 25, 2023 |
| Samsung       | 950QED                      | Convertible | [14fa80f70c](https://linux-hardware.org/?probe=14fa80f70c) | Mar 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7f32708bde](https://linux-hardware.org/?probe=7f32708bde) | Mar 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [446c510c65](https://linux-hardware.org/?probe=446c510c65) | Mar 24, 2023 |
| Toshiba       | Satellite C855-12N          | Notebook    | [cb9692876c](https://linux-hardware.org/?probe=cb9692876c) | Mar 24, 2023 |
| HP            | 304Ah                       | Desktop     | [43990fede2](https://linux-hardware.org/?probe=43990fede2) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | Notebook    | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| MSI           | Creator Z17 A12UHST         | Notebook    | [47814b01b6](https://linux-hardware.org/?probe=47814b01b6) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | Notebook    | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [d18034c36c](https://linux-hardware.org/?probe=d18034c36c) | Mar 24, 2023 |
| Dell          | 0NDYHG A01                  | Desktop     | [93bc601af0](https://linux-hardware.org/?probe=93bc601af0) | Mar 23, 2023 |
| Dell          | Latitude E7450              | Notebook    | [c1e43b6a40](https://linux-hardware.org/?probe=c1e43b6a40) | Mar 23, 2023 |
| Lenovo        | G580                        | Notebook    | [367ed9241a](https://linux-hardware.org/?probe=367ed9241a) | Mar 23, 2023 |
| Dell          | 0DPRKF A01                  | Server      | [fdc74a5707](https://linux-hardware.org/?probe=fdc74a5707) | Mar 23, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d32ee19009](https://linux-hardware.org/?probe=d32ee19009) | Mar 23, 2023 |
| Lenovo        | G580                        | Notebook    | [6ee526d77a](https://linux-hardware.org/?probe=6ee526d77a) | Mar 22, 2023 |
| Acer          | Aspire VN7-791              | Notebook    | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [f6ad6626ff](https://linux-hardware.org/?probe=f6ad6626ff) | Mar 22, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [0ae6ab3ff6](https://linux-hardware.org/?probe=0ae6ab3ff6) | Mar 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [31ee1d66d8](https://linux-hardware.org/?probe=31ee1d66d8) | Mar 21, 2023 |
| Gigabyte      | EX38-DS4                    | Desktop     | [6dd3e18637](https://linux-hardware.org/?probe=6dd3e18637) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [a9e094374a](https://linux-hardware.org/?probe=a9e094374a) | Mar 20, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [a03658793c](https://linux-hardware.org/?probe=a03658793c) | Mar 20, 2023 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [6df656c198](https://linux-hardware.org/?probe=6df656c198) | Mar 20, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [1bad88b80e](https://linux-hardware.org/?probe=1bad88b80e) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [7b4a68e88a](https://linux-hardware.org/?probe=7b4a68e88a) | Mar 20, 2023 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [cd708d0e58](https://linux-hardware.org/?probe=cd708d0e58) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a71c5a4629](https://linux-hardware.org/?probe=a71c5a4629) | Mar 19, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [888ec192b4](https://linux-hardware.org/?probe=888ec192b4) | Mar 19, 2023 |
| ASRock        | X370 Gaming X               | Desktop     | [4f98540a7b](https://linux-hardware.org/?probe=4f98540a7b) | Mar 19, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [efbab00e4b](https://linux-hardware.org/?probe=efbab00e4b) | Mar 19, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [919ccc204b](https://linux-hardware.org/?probe=919ccc204b) | Mar 19, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [703ea3d03c](https://linux-hardware.org/?probe=703ea3d03c) | Mar 18, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 590       | 10.57%  |
| OpenMandriva 4.2   | 317       | 5.68%   |
| Ubuntu 18.04       | 281       | 5.03%   |
| Ubuntu 22.04       | 250       | 4.48%   |
| OpenMandriva 4.3   | 231       | 4.14%   |
| Debian 11          | 158       | 2.83%   |
| Arch Rolling       | 138       | 2.47%   |
| ROSA R10           | 98        | 1.76%   |
| OpenMandriva 23.03 | 94        | 1.68%   |
| OpenMandriva 23.01 | 90        | 1.61%   |
| Zorin 16           | 81        | 1.45%   |
| Linux Mint 21.1    | 78        | 1.4%    |
| Manjaro            | 75        | 1.34%   |
| Linux Mint 20.3    | 71        | 1.27%   |
| ROSA R9            | 70        | 1.25%   |
| ROSA R11           | 69        | 1.24%   |
| Arch               | 68        | 1.22%   |
| Linux Mint 20.1    | 66        | 1.18%   |
| Fedora 37          | 66        | 1.18%   |
| ROSA R11.1         | 65        | 1.16%   |
| KDE neon 20.04     | 64        | 1.15%   |
| Fedora 36          | 60        | 1.07%   |
| Ubuntu 20.10       | 57        | 1.02%   |
| Fedora 38          | 57        | 1.02%   |
| Pop!_OS 22.04      | 54        | 0.97%   |
| Linux Mint 20.2    | 53        | 0.95%   |
| Ubuntu 21.04       | 50        | 0.9%    |
| Linux Mint 20      | 49        | 0.88%   |
| Ubuntu 19.10       | 48        | 0.86%   |
| Linux Mint 19.3    | 48        | 0.86%   |
| Ubuntu 22.10       | 46        | 0.82%   |
| Ubuntu 21.10       | 44        | 0.79%   |
| Fedora 35          | 43        | 0.77%   |
| ROSA R8            | 42        | 0.75%   |
| Fedora 33          | 41        | 0.73%   |
| Linux Mint 21      | 40        | 0.72%   |
| Debian 10          | 40        | 0.72%   |
| Fedora 34          | 39        | 0.7%    |
| Xubuntu 20.04      | 38        | 0.68%   |
| Fedora 32          | 38        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1372      | 26.63%  |
| OpenMandriva  | 762       | 14.79%  |
| Linux Mint    | 421       | 8.17%   |
| Fedora        | 349       | 6.77%   |
| ROSA          | 336       | 6.52%   |
| Debian        | 254       | 4.93%   |
| Manjaro       | 201       | 3.9%    |
| Arch          | 198       | 3.84%   |
| Pop!_OS       | 151       | 2.93%   |
| Zorin         | 120       | 2.33%   |
| Kubuntu       | 102       | 1.98%   |
| KDE neon      | 93        | 1.8%    |
| Xubuntu       | 80        | 1.55%   |
| Gentoo        | 49        | 0.95%   |
| openSUSE      | 47        | 0.91%   |
| Kali          | 47        | 0.91%   |
| ArcoLinux     | 41        | 0.8%    |
| Lubuntu       | 38        | 0.74%   |
| Endless       | 36        | 0.7%    |
| Elementary    | 35        | 0.68%   |
| EndeavourOS   | 31        | 0.6%    |
| LMDE          | 30        | 0.58%   |
| SteamOS       | 27        | 0.52%   |
| Ubuntu MATE   | 22        | 0.43%   |
| Ubuntu Unity  | 21        | 0.41%   |
| Clear Linux   | 21        | 0.41%   |
| MX            | 20        | 0.39%   |
| Nobara        | 19        | 0.37%   |
| BlackPanther  | 18        | 0.35%   |
| CentOS        | 14        | 0.27%   |
| Ubuntu Budgie | 13        | 0.25%   |
| Garuda Linux  | 13        | 0.25%   |
| Peppermint    | 10        | 0.19%   |
| LinuxFX       | 10        | 0.19%   |
| Xero          | 9         | 0.17%   |
| Raspbian      | 8         | 0.16%   |
| NixOS         | 8         | 0.16%   |
| Linux Lite    | 8         | 0.16%   |
| EuroLinux     | 7         | 0.14%   |
| Parrot        | 6         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                         | Computers | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 303       | 4.86%   |
| 5.16.7-desktop-1omv4003         | 212       | 3.4%    |
| 6.2.6-desktop-1omv2390          | 90        | 1.44%   |
| 6.1.1-desktop-1omv2290          | 80        | 1.28%   |
| 5.4.0-42-generic                | 78        | 1.25%   |
| 5.15.0-56-generic               | 59        | 0.95%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 54        | 0.87%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 53        | 0.85%   |
| 5.15.0-43-generic               | 41        | 0.66%   |
| 5.4.0-26-generic                | 40        | 0.64%   |
| 5.15.0-58-generic               | 39        | 0.63%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 39        | 0.63%   |
| 5.4.0-52-generic                | 38        | 0.61%   |
| 5.4.0-48-generic                | 36        | 0.58%   |
| 5.15.0-52-generic               | 36        | 0.58%   |
| 5.19.0-35-generic               | 35        | 0.56%   |
| 5.4.0-58-generic                | 33        | 0.53%   |
| 5.4.0-29-generic                | 30        | 0.48%   |
| 5.3.0-46-generic                | 30        | 0.48%   |
| 5.4.0-54-generic                | 28        | 0.45%   |
| 5.19.0-32-generic               | 28        | 0.45%   |
| 5.8.0-43-generic                | 27        | 0.43%   |
| 5.13.0-39-generic               | 27        | 0.43%   |
| 5.11.0-37-generic               | 27        | 0.43%   |
| 5.4.0-40-generic                | 26        | 0.42%   |
| 5.4.0-37-generic                | 25        | 0.4%    |
| 5.15.0-48-generic               | 25        | 0.4%    |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 24        | 0.39%   |
| 5.4.0-66-generic                | 23        | 0.37%   |
| 5.4.0-33-generic                | 23        | 0.37%   |
| 5.13.0-27-generic               | 23        | 0.37%   |
| 5.3.0-42-generic                | 22        | 0.35%   |
| 5.16.13-desktop-1omv4003        | 22        | 0.35%   |
| 5.15.0-60-generic               | 22        | 0.35%   |
| 5.11.0-27-generic               | 22        | 0.35%   |
| 5.0.0-37-generic                | 22        | 0.35%   |
| 5.10.0-21-amd64                 | 21        | 0.34%   |
| 5.8.0-48-generic                | 20        | 0.32%   |
| 5.4.0-91-generic                | 20        | 0.32%   |
| 5.4.0-65-generic                | 20        | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 766       | 13.05%  |
| 5.15.0  | 430       | 7.33%   |
| 5.10.14 | 305       | 5.2%    |
| 4.15.0  | 287       | 4.89%   |
| 5.11.0  | 223       | 3.8%    |
| 5.8.0   | 222       | 3.78%   |
| 5.16.7  | 215       | 3.66%   |
| 5.13.0  | 204       | 3.48%   |
| 5.10.0  | 167       | 2.85%   |
| 5.3.0   | 166       | 2.83%   |
| 5.19.0  | 166       | 2.83%   |
| 6.2.6   | 112       | 1.91%   |
| 5.0.0   | 101       | 1.72%   |
| 4.18.0  | 91        | 1.55%   |
| 6.1.1   | 82        | 1.4%    |
| 4.9.60  | 66        | 1.12%   |
| 4.9.20  | 62        | 1.06%   |
| 4.19.0  | 54        | 0.92%   |
| 6.1.0   | 48        | 0.82%   |
| 6.2.0   | 44        | 0.75%   |
| 5.14.0  | 35        | 0.6%    |
| 4.1.34  | 32        | 0.55%   |
| 4.1.38  | 28        | 0.48%   |
| 6.0.0   | 26        | 0.44%   |
| 5.16.13 | 24        | 0.41%   |
| 5.17.5  | 20        | 0.34%   |
| 5.11.12 | 19        | 0.32%   |
| 5.9.0   | 18        | 0.31%   |
| 5.4.32  | 18        | 0.31%   |
| 6.4.11  | 17        | 0.29%   |
| 6.0.12  | 17        | 0.29%   |
| 4.9.76  | 16        | 0.27%   |
| 4.9.155 | 16        | 0.27%   |
| 4.9.124 | 16        | 0.27%   |
| 6.0.7   | 15        | 0.26%   |
| 5.17.0  | 15        | 0.26%   |
| 6.3.5   | 14        | 0.24%   |
| 6.0.8   | 14        | 0.24%   |
| 6.1.12  | 13        | 0.22%   |
| 5.6.0   | 13        | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 867       | 15.25%  |
| 5.10    | 587       | 10.32%  |
| 5.15    | 573       | 10.08%  |
| 5.16    | 309       | 5.43%   |
| 5.11    | 289       | 5.08%   |
| 4.15    | 287       | 5.05%   |
| 5.8     | 280       | 4.92%   |
| 6.1     | 242       | 4.26%   |
| 6.2     | 240       | 4.22%   |
| 5.13    | 235       | 4.13%   |
| 5.19    | 224       | 3.94%   |
| 5.3     | 186       | 3.27%   |
| 4.9     | 184       | 3.24%   |
| 6.0     | 131       | 2.3%    |
| 5.0     | 111       | 1.95%   |
| 4.18    | 103       | 1.81%   |
| 5.14    | 94        | 1.65%   |
| 5.17    | 79        | 1.39%   |
| 5.9     | 74        | 1.3%    |
| 5.6     | 70        | 1.23%   |
| 5.18    | 70        | 1.23%   |
| 4.19    | 67        | 1.18%   |
| 6.3     | 66        | 1.16%   |
| 4.1     | 63        | 1.11%   |
| 5.12    | 60        | 1.06%   |
| 6.4     | 57        | 1%      |
| 5.5     | 39        | 0.69%   |
| 5.7     | 35        | 0.62%   |
| 4.4     | 17        | 0.3%    |
| 5.1     | 8         | 0.14%   |
| 3.10    | 7         | 0.12%   |
| 5.2     | 5         | 0.09%   |
| 4.20    | 4         | 0.07%   |
| 4.16    | 3         | 0.05%   |
| 4.13    | 3         | 0.05%   |
| 4.8     | 2         | 0.04%   |
| 4.7     | 2         | 0.04%   |
| 4.14    | 2         | 0.04%   |
| 4.12    | 2         | 0.04%   |
| 4.10    | 2         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 4748      | 95.94%  |
| i686    | 150       | 3.03%   |
| aarch64 | 26        | 0.53%   |
| armv7l  | 18        | 0.36%   |
| armv8l  | 3         | 0.06%   |
| armv6l  | 2         | 0.04%   |
| ppc64   | 1         | 0.02%   |
| ppc     | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 1867      | 35.79%  |
| KDE5            | 1382      | 26.5%   |
| Unknown         | 497       | 9.53%   |
| XFCE            | 365       | 7%      |
| X-Cinnamon      | 292       | 5.6%    |
| KDE4            | 177       | 3.39%   |
| MATE            | 131       | 2.51%   |
| KDE             | 126       | 2.42%   |
| LXQt            | 70        | 1.34%   |
| Cinnamon        | 68        | 1.3%    |
| LXDE            | 50        | 0.96%   |
| i3              | 35        | 0.67%   |
| Pantheon        | 34        | 0.65%   |
| Unity           | 24        | 0.46%   |
| Budgie          | 21        | 0.4%    |
| Deepin          | 16        | 0.31%   |
| GNOME Flashback | 12        | 0.23%   |
| Hyprland        | 7         | 0.13%   |
| GNOME Classic   | 6         | 0.12%   |
| awesome         | 6         | 0.12%   |
| qtile           | 4         | 0.08%   |
| Openbox         | 4         | 0.08%   |
| sway            | 3         | 0.06%   |
| icewm           | 3         | 0.06%   |
| fluxbox         | 3         | 0.06%   |
| DWM             | 3         | 0.06%   |
| trinity         | 2         | 0.04%   |
| xmonad          | 1         | 0.02%   |
| stumpwm         | 1         | 0.02%   |
| ratflow         | 1         | 0.02%   |
| qt5ct           | 1         | 0.02%   |
| jwm             | 1         | 0.02%   |
| GNUstep         | 1         | 0.02%   |
| gnome-xorg      | 1         | 0.02%   |
| BunsenLabs      | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 4014      | 78.46%  |
| Wayland     | 753       | 14.72%  |
| Unknown     | 242       | 4.73%   |
| Tty         | 106       | 2.07%   |
| Unspecified | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2093      | 40.31%  |
| SDDM    | 1282      | 24.69%  |
| GDM     | 548       | 10.55%  |
| GDM3    | 455       | 8.76%   |
| LightDM | 447       | 8.61%   |
| KDM     | 187       | 3.6%    |
| TDM     | 152       | 2.93%   |
| XDM     | 11        | 0.21%   |
| SLiM    | 3         | 0.06%   |
| Ly      | 3         | 0.06%   |
| LXDM    | 3         | 0.06%   |
| SLIMSKI | 2         | 0.04%   |
| NODM    | 2         | 0.04%   |
| MDM     | 2         | 0.04%   |
| SU      | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pl_PL       | 2774      | 53.9%   |
| en_US       | 1352      | 26.27%  |
| Unknown     | 651       | 12.65%  |
| en_GB       | 144       | 2.8%    |
| C           | 96        | 1.87%   |
| ru_RU       | 32        | 0.62%   |
| szl_PL      | 12        | 0.23%   |
| de_DE       | 11        | 0.21%   |
| uk_UA       | 9         | 0.17%   |
| ru_UA       | 9         | 0.17%   |
| en_CA       | 8         | 0.16%   |
| en_IE       | 6         | 0.12%   |
| fr_FR       | 5         | 0.1%    |
| en_DK       | 4         | 0.08%   |
| en_AG       | 4         | 0.08%   |
| POSIX       | 3         | 0.06%   |
| it_IT       | 3         | 0.06%   |
| C.UTF8      | 3         | 0.06%   |
| nl_NL       | 2         | 0.04%   |
| hu_HU       | 2         | 0.04%   |
| en_US.utf-8 | 2         | 0.04%   |
| en_IN       | 2         | 0.04%   |
| sv_SE       | 1         | 0.02%   |
| sk_SK       | 1         | 0.02%   |
| pl_PL.UTF8  | 1         | 0.02%   |
| es_ES       | 1         | 0.02%   |
| es_AR       | 1         | 0.02%   |
| en_US.UTF8  | 1         | 0.02%   |
| en_SE       | 1         | 0.02%   |
| en_AU       | 1         | 0.02%   |
| el_GR       | 1         | 0.02%   |
| de_CH       | 1         | 0.02%   |
| be_BY       | 1         | 0.02%   |
| af_ZA       | 1         | 0.02%   |
| aa_DJ       | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2746      | 54.19%  |
| EFI  | 2321      | 45.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3465      | 67.26%  |
| Overlay  | 711       | 13.8%   |
| Btrfs    | 476       | 9.24%   |
| Unknown  | 299       | 5.8%    |
| Xfs      | 71        | 1.38%   |
| Tmpfs    | 53        | 1.03%   |
| Zfs      | 34        | 0.66%   |
| F2fs     | 20        | 0.39%   |
| Ext2     | 7         | 0.14%   |
| Ext3     | 6         | 0.12%   |
| Rootfs   | 3         | 0.06%   |
| Jfs      | 3         | 0.06%   |
| XXXXX    | 1         | 0.02%   |
| SquXshfs | 1         | 0.02%   |
| Bcachefs | 1         | 0.02%   |
| Aufs     | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2299      | 44.83%  |
| GPT     | 1943      | 37.89%  |
| MBR     | 886       | 17.28%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4128      | 81.21%  |
| Yes       | 955       | 18.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3328      | 65.8%   |
| Yes       | 1730      | 34.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 876       | 17.73%  |
| Dell                    | 788       | 15.95%  |
| ASUSTek Computer        | 745       | 15.08%  |
| Hewlett-Packard         | 608       | 12.31%  |
| Gigabyte Technology     | 430       | 8.7%    |
| MSI                     | 364       | 7.37%   |
| Acer                    | 207       | 4.19%   |
| ASRock                  | 175       | 3.54%   |
| Toshiba                 | 82        | 1.66%   |
| Samsung Electronics     | 82        | 1.66%   |
| Fujitsu                 | 56        | 1.13%   |
| Apple                   | 43        | 0.87%   |
| Sony                    | 37        | 0.75%   |
| Fujitsu Siemens         | 34        | 0.69%   |
| Intel                   | 32        | 0.65%   |
| HUAWEI                  | 31        | 0.63%   |
| Unknown                 | 25        | 0.51%   |
| Raspberry Pi Foundation | 24        | 0.49%   |
| Valve                   | 22        | 0.45%   |
| Google                  | 22        | 0.45%   |
| Packard Bell            | 16        | 0.32%   |
| Notebook                | 15        | 0.3%    |
| Medion                  | 15        | 0.3%    |
| Foxconn                 | 14        | 0.28%   |
| Kiano                   | 12        | 0.24%   |
| eMachines               | 11        | 0.22%   |
| Timi                    | 9         | 0.18%   |
| Inventec                | 9         | 0.18%   |
| AMI                     | 7         | 0.14%   |
| ZOTAC                   | 5         | 0.1%    |
| Supermicro              | 5         | 0.1%    |
| mPTech                  | 5         | 0.1%    |
| Huanan                  | 5         | 0.1%    |
| Kruger&Matz             | 4         | 0.08%   |
| Gateway                 | 4         | 0.08%   |
| ECS                     | 4         | 0.08%   |
| Alienware               | 4         | 0.08%   |
| Xunlong                 | 3         | 0.06%   |
| TUXEDO                  | 3         | 0.06%   |
| Teclast                 | 3         | 0.06%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 50        | 1.01%   |
| ASUS All Series                     | 33        | 0.67%   |
| Dell Inspiron 3451                  | 31        | 0.63%   |
| Valve Jupiter                       | 22        | 0.45%   |
| Gigabyte B450M DS3H                 | 18        | 0.36%   |
| ASUS SABERTOOTH Z77                 | 18        | 0.36%   |
| MSI MS-7B86                         | 17        | 0.34%   |
| Dell Latitude E6400                 | 17        | 0.34%   |
| MSI MS-7817                         | 16        | 0.32%   |
| Dell OptiPlex 780                   | 15        | 0.3%    |
| Dell Latitude E6540                 | 15        | 0.3%    |
| MSI MS-7C02                         | 13        | 0.26%   |
| Lenovo G50-30 80G0                  | 13        | 0.26%   |
| MSI MS-7C37                         | 12        | 0.24%   |
| HP Pavilion dv7                     | 12        | 0.24%   |
| Dell Latitude 5480                  | 12        | 0.24%   |
| Dell OptiPlex 7010                  | 11        | 0.22%   |
| Dell Latitude E6430                 | 11        | 0.22%   |
| Dell Latitude D630                  | 11        | 0.22%   |
| Dell Latitude 5490                  | 11        | 0.22%   |
| ASUS X555LJ                         | 11        | 0.22%   |
| Lenovo Legion Y530-15ICH 81FV       | 10        | 0.2%    |
| Lenovo G580 20150                   | 10        | 0.2%    |
| Gigabyte B450 AORUS ELITE           | 10        | 0.2%    |
| MSI MS-7B79                         | 9         | 0.18%   |
| MSI MS-7721                         | 9         | 0.18%   |
| HP 15                               | 9         | 0.18%   |
| Gigabyte B85M-D3H                   | 9         | 0.18%   |
| Dell OptiPlex 755                   | 9         | 0.18%   |
| Dell Latitude E7440                 | 9         | 0.18%   |
| Dell Latitude E6420                 | 9         | 0.18%   |
| Dell Latitude 5420                  | 9         | 0.18%   |
| ASUS TUF Gaming X570-PLUS           | 9         | 0.18%   |
| MSI MS-7A38                         | 8         | 0.16%   |
| MSI MS-7816                         | 8         | 0.16%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 8         | 0.16%   |
| Lenovo G510 20238                   | 8         | 0.16%   |
| Lenovo G50-80 80E5                  | 8         | 0.16%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 8         | 0.16%   |
| HP Pavilion dv6                     | 8         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 362       | 7.33%   |
| Dell Latitude         | 323       | 6.54%   |
| Dell Inspiron         | 160       | 3.24%   |
| Lenovo IdeaPad        | 157       | 3.18%   |
| Acer Aspire           | 124       | 2.51%   |
| Dell OptiPlex         | 107       | 2.17%   |
| HP EliteBook          | 104       | 2.11%   |
| HP Pavilion           | 102       | 2.06%   |
| HP Compaq             | 71        | 1.44%   |
| HP ProBook            | 69        | 1.4%    |
| ASUS PRIME            | 69        | 1.4%    |
| Dell Precision        | 68        | 1.38%   |
| Toshiba Satellite     | 66        | 1.34%   |
| Lenovo Legion         | 58        | 1.17%   |
| ASUS TUF              | 56        | 1.13%   |
| Unknown               | 50        | 1.01%   |
| ASUS ROG              | 49        | 0.99%   |
| Dell Vostro           | 45        | 0.91%   |
| Lenovo ThinkCentre    | 41        | 0.83%   |
| ASUS VivoBook         | 39        | 0.79%   |
| HP Laptop             | 36        | 0.73%   |
| Dell XPS              | 34        | 0.69%   |
| ASUS All              | 33        | 0.67%   |
| ASUS ASUS             | 29        | 0.59%   |
| Gigabyte B450M        | 26        | 0.53%   |
| RPi Raspberry         | 24        | 0.49%   |
| HP EliteDesk          | 23        | 0.47%   |
| Valve Jupiter         | 22        | 0.45%   |
| Fujitsu LIFEBOOK      | 21        | 0.43%   |
| ASUS SABERTOOTH       | 20        | 0.4%    |
| Lenovo Yoga           | 19        | 0.38%   |
| HP 250                | 19        | 0.38%   |
| Fujitsu ESPRIMO       | 19        | 0.38%   |
| MSI MS-7B86           | 17        | 0.34%   |
| HP ZBook              | 17        | 0.34%   |
| Packard Bell EasyNote | 16        | 0.32%   |
| MSI MS-7817           | 16        | 0.32%   |
| Lenovo ThinkBook      | 15        | 0.3%    |
| Gigabyte B550         | 15        | 0.3%    |
| Acer Extensa          | 15        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 425       | 8.6%    |
| 2012    | 422       | 8.54%   |
| 2013    | 411       | 8.32%   |
| 2019    | 393       | 7.96%   |
| 2020    | 363       | 7.35%   |
| 2011    | 356       | 7.21%   |
| 2014    | 318       | 6.44%   |
| 2017    | 287       | 5.81%   |
| 2015    | 276       | 5.59%   |
| 2008    | 267       | 5.4%    |
| 2021    | 256       | 5.18%   |
| 2010    | 251       | 5.08%   |
| 2009    | 223       | 4.51%   |
| 2016    | 221       | 4.47%   |
| 2007    | 197       | 3.99%   |
| 2022    | 122       | 2.47%   |
| 2006    | 77        | 1.56%   |
| Unknown | 41        | 0.83%   |
| 2023    | 16        | 0.32%   |
| 2005    | 11        | 0.22%   |
| 2004    | 6         | 0.12%   |
| 2001    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 2944      | 59.6%   |
| Desktop        | 1783      | 36.09%  |
| Convertible    | 61        | 1.23%   |
| System on chip | 41        | 0.83%   |
| Mini pc        | 40        | 0.81%   |
| Server         | 26        | 0.53%   |
| All in one     | 20        | 0.4%    |
| Tablet         | 19        | 0.38%   |
| Phone          | 6         | 0.12%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 4675      | 94.03%  |
| Enabled  | 297       | 5.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4915      | 99.49%  |
| Yes  | 25        | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 1052      | 20.83%  |
| 4.01-8.0        | 1041      | 20.61%  |
| 16.01-24.0      | 933       | 18.47%  |
| 8.01-16.0       | 919       | 18.19%  |
| 32.01-64.0      | 527       | 10.43%  |
| 1.01-2.0        | 204       | 4.04%   |
| 2.01-3.0        | 121       | 2.4%    |
| 64.01-256.0     | 117       | 2.32%   |
| 24.01-32.0      | 88        | 1.74%   |
| 0.51-1.0        | 42        | 0.83%   |
| 0.01-0.5        | 4         | 0.08%   |
| More than 256.0 | 3         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 2043      | 36.3%   |
| 2.01-3.0    | 1218      | 21.64%  |
| 4.01-8.0    | 784       | 13.93%  |
| 3.01-4.0    | 656       | 11.66%  |
| 0.51-1.0    | 500       | 8.88%   |
| 8.01-16.0   | 254       | 4.51%   |
| 0.01-0.5    | 96        | 1.71%   |
| 16.01-24.0  | 51        | 0.91%   |
| 24.01-32.0  | 14        | 0.25%   |
| Unknown     | 5         | 0.09%   |
| 32.01-64.0  | 4         | 0.07%   |
| 64.01-256.0 | 3         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 3011      | 58.51%  |
| 2       | 1302      | 25.3%   |
| 3       | 441       | 8.57%   |
| 4       | 174       | 3.38%   |
| 0       | 76        | 1.48%   |
| 5       | 74        | 1.44%   |
| 6       | 33        | 0.64%   |
| 7       | 17        | 0.33%   |
| 8       | 7         | 0.14%   |
| 11      | 3         | 0.06%   |
| 9       | 3         | 0.06%   |
| 10      | 2         | 0.04%   |
| 13      | 1         | 0.02%   |
| 12      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2868      | 57.25%  |
| Yes       | 2142      | 42.75%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4441      | 89.63%  |
| No        | 514       | 10.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3748      | 75.16%  |
| No        | 1239      | 24.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2848      | 56.64%  |
| No        | 2180      | 43.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Poland  | 4940      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 1126      | 20.76%  |
| Krakow                 | 397       | 7.32%   |
| Wroclaw                | 322       | 5.94%   |
| Poznan                 | 273       | 5.03%   |
| Gdansk                 | 178       | 3.28%   |
| Lodz                   | 169       | 3.12%   |
| Katowice               | 143       | 2.64%   |
| Lublin                 | 77        | 1.42%   |
| Gdynia                 | 67        | 1.24%   |
| Szczecin               | 59        | 1.09%   |
| Bialystok              | 52        | 0.96%   |
| Gliwice                | 43        | 0.79%   |
| Częstochowa           | 42        | 0.77%   |
| Rzeszów               | 38        | 0.7%    |
| Torun                  | 37        | 0.68%   |
| Bydgoszcz              | 35        | 0.65%   |
| Bytom                  | 34        | 0.63%   |
| Ruda Śląska          | 33        | 0.61%   |
| Płock                 | 29        | 0.53%   |
| Zabrze                 | 27        | 0.5%    |
| Kielce                 | 27        | 0.5%    |
| Sosnowiec              | 26        | 0.48%   |
| Elblag                 | 26        | 0.48%   |
| Bielsko-Biala          | 25        | 0.46%   |
| Rybnik                 | 24        | 0.44%   |
| Olsztyn                | 23        | 0.42%   |
| Strzyzow               | 21        | 0.39%   |
| Radom                  | 21        | 0.39%   |
| Chorzów               | 21        | 0.39%   |
| Opole                  | 20        | 0.37%   |
| Tarnów                | 19        | 0.35%   |
| Siemianowice Śląskie | 19        | 0.35%   |
| Tychy                  | 18        | 0.33%   |
| Zielona Góra          | 15        | 0.28%   |
| Debica                 | 15        | 0.28%   |
| Cieszyn                | 15        | 0.28%   |
| Piaseczno              | 14        | 0.26%   |
| Legnica                | 14        | 0.26%   |
| Blizniew               | 13        | 0.24%   |
| Wołomin               | 12        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 1017      | 1574   | 13.79%  |
| Samsung Electronics       | 1011      | 1554   | 13.7%   |
| WDC                       | 984       | 1524   | 13.34%  |
| GOODRAM                   | 500       | 747    | 6.78%   |
| Toshiba                   | 452       | 675    | 6.13%   |
| Crucial                   | 282       | 469    | 3.82%   |
| Kingston                  | 280       | 401    | 3.8%    |
| Unknown                   | 275       | 405    | 3.73%   |
| A-DATA Technology         | 275       | 374    | 3.73%   |
| SanDisk                   | 270       | 370    | 3.66%   |
| Hitachi                   | 246       | 363    | 3.33%   |
| Intel                     | 184       | 246    | 2.49%   |
| SK hynix                  | 161       | 210    | 2.18%   |
| Micron Technology         | 110       | 143    | 1.49%   |
| HGST                      | 107       | 139    | 1.45%   |
| Patriot                   | 98        | 128    | 1.33%   |
| SPCC                      | 78        | 125    | 1.06%   |
| Plextor                   | 59        | 78     | 0.8%    |
| PNY                       | 56        | 62     | 0.76%   |
| KIOXIA                    | 52        | 58     | 0.7%    |
| XPG                       | 43        | 62     | 0.58%   |
| Phison                    | 41        | 56     | 0.56%   |
| Fujitsu                   | 41        | 45     | 0.56%   |
| Apacer                    | 38        | 61     | 0.52%   |
| China                     | 36        | 53     | 0.49%   |
| Phison Electronics        | 35        | 48     | 0.47%   |
| OCZ                       | 30        | 33     | 0.41%   |
| Silicon Motion            | 28        | 36     | 0.38%   |
| LITEON                    | 28        | 37     | 0.38%   |
| Transcend                 | 26        | 29     | 0.35%   |
| Corsair                   | 26        | 36     | 0.35%   |
| Maxtor                    | 22        | 22     | 0.3%    |
| Realtek Semiconductor     | 21        | 33     | 0.28%   |
| KIOXIA-EXCERIA            | 20        | 27     | 0.27%   |
| JMicron Technology        | 20        | 24     | 0.27%   |
| Apple                     | 20        | 24     | 0.27%   |
| Micron/Crucial Technology | 19        | 19     | 0.26%   |
| ASMT                      | 19        | 20     | 0.26%   |
| ADATA Technology          | 19        | 23     | 0.26%   |
| Unknown                   | 19        | 22     | 0.26%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                     | 65        | 0.8%    |
| Crucial CT500MX500SSD1 500GB                        | 65        | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 61        | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB                      | 59        | 0.73%   |
| Toshiba HDWD110 1TB                                 | 56        | 0.69%   |
| Samsung SSD 850 EVO 250GB                           | 53        | 0.66%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                    | 52        | 0.64%   |
| GOODRAM SSD 120GB                                   | 51        | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 47        | 0.58%   |
| Crucial CT1000MX500SSD1 1TB                         | 46        | 0.57%   |
| Unknown MMC Card  32GB                              | 43        | 0.53%   |
| Samsung SSD 860 EVO 500GB                           | 42        | 0.52%   |
| Seagate ST500DM002-1BD142 500GB                     | 40        | 0.5%    |
| GOODRAM SSDPR-CX400-512-G2 512GB                    | 40        | 0.5%    |
| GOODRAM SSD 240GB                                   | 40        | 0.5%    |
| Kingston SA400S37240G 240GB SSD                     | 38        | 0.47%   |
| GOODRAM SSDPR-CX400-512 512GB                       | 37        | 0.46%   |
| Unknown MMC Card  64GB                              | 35        | 0.43%   |
| Crucial CT240BX500SSD1 240GB                        | 35        | 0.43%   |
| Toshiba MQ01ABD100 1TB                              | 34        | 0.42%   |
| Kingston SV300S37A120G 120GB SSD                    | 34        | 0.42%   |
| Seagate ST1000DM010-2EP102 1TB                      | 33        | 0.41%   |
| Samsung SSD 980 1TB                                 | 33        | 0.41%   |
| Samsung SSD 860 EVO 250GB                           | 33        | 0.41%   |
| Seagate ST9500325AS 500GB                           | 32        | 0.4%    |
| Samsung NVMe SSD Drive 500GB                        | 32        | 0.4%    |
| A-DATA SU800 256GB SSD                              | 32        | 0.4%    |
| Seagate ST3500418AS 500GB                           | 30        | 0.37%   |
| Patriot Burst 120GB SSD                             | 30        | 0.37%   |
| Seagate ST1000DM003-1ER162 1TB                      | 29        | 0.36%   |
| Samsung NVMe SSD Drive 512GB                        | 28        | 0.35%   |
| GOODRAM SSDPR-CX400-256 256GB                       | 28        | 0.35%   |
| Seagate Expansion 2TB                               | 27        | 0.33%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 27        | 0.33%   |
| Kingston SA400S37480G 480GB SSD                     | 26        | 0.32%   |
| Intel NVMe SSD Drive 512GB                          | 26        | 0.32%   |
| HGST HTS721010A9E630 1TB                            | 26        | 0.32%   |
| GOODRAM SSDPR-CX400-128 128GB                       | 26        | 0.32%   |
| Toshiba MQ01ABF050 500GB                            | 25        | 0.31%   |
| SanDisk SDSSDA240G 240GB                            | 25        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1012      | 1565   | 36.09%  |
| WDC                 | 813       | 1285   | 28.99%  |
| Toshiba             | 345       | 542    | 12.3%   |
| Hitachi             | 246       | 363    | 8.77%   |
| Samsung Electronics | 169       | 241    | 6.03%   |
| HGST                | 107       | 139    | 3.82%   |
| Fujitsu             | 41        | 45     | 1.46%   |
| Maxtor              | 20        | 20     | 0.71%   |
| Unknown             | 9         | 9      | 0.32%   |
| Apple               | 7         | 7      | 0.25%   |
| ASMT                | 5         | 6      | 0.18%   |
| USB3.0              | 3         | 3      | 0.11%   |
| PHD 3.0             | 3         | 3      | 0.11%   |
| ASMedia             | 3         | 3      | 0.11%   |
| WD MediaMax         | 2         | 3      | 0.07%   |
| SAGE                | 2         | 2      | 0.07%   |
| IBM/Hitachi         | 2         | 2      | 0.07%   |
| Unknown             | 2         | 2      | 0.07%   |
| USB                 | 1         | 1      | 0.04%   |
| Synology            | 1         | 1      | 0.04%   |
| StoreJet            | 1         | 1      | 0.04%   |
| MARVELL             | 1         | 1      | 0.04%   |
| LaCie               | 1         | 2      | 0.04%   |
| JMicron Technology  | 1         | 4      | 0.04%   |
| IB-377U3            | 1         | 6      | 0.04%   |
| HPE                 | 1         | 1      | 0.04%   |
| HGST HTS            | 1         | 1      | 0.04%   |
| Hewlett-Packard     | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASUSTOR             | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 1      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| GOODRAM             | 486       | 721    | 17.9%   |
| Samsung Electronics | 438       | 624    | 16.13%  |
| Crucial             | 272       | 457    | 10.02%  |
| A-DATA Technology   | 228       | 308    | 8.4%    |
| Kingston            | 197       | 273    | 7.26%   |
| SanDisk             | 175       | 246    | 6.45%   |
| WDC                 | 93        | 111    | 3.43%   |
| Patriot             | 89        | 119    | 3.28%   |
| SPCC                | 71        | 116    | 2.62%   |
| Intel               | 60        | 72     | 2.21%   |
| Micron Technology   | 55        | 70     | 2.03%   |
| Plextor             | 50        | 69     | 1.84%   |
| Toshiba             | 48        | 53     | 1.77%   |
| SK hynix            | 44        | 53     | 1.62%   |
| PNY                 | 43        | 48     | 1.58%   |
| China               | 35        | 52     | 1.29%   |
| Apacer              | 35        | 58     | 1.29%   |
| OCZ                 | 30        | 33     | 1.1%    |
| LITEON              | 28        | 37     | 1.03%   |
| Transcend           | 25        | 28     | 0.92%   |
| LITEONIT            | 16        | 18     | 0.59%   |
| KIOXIA-EXCERIA      | 16        | 21     | 0.59%   |
| ASMT                | 14        | 14     | 0.52%   |
| JMicron Technology  | 13        | 13     | 0.48%   |
| Apple               | 12        | 12     | 0.44%   |
| Corsair             | 11        | 12     | 0.41%   |
| KingSpec            | 9         | 10     | 0.33%   |
| Team                | 8         | 8      | 0.29%   |
| Intenso             | 8         | 13     | 0.29%   |
| Gigabyte Technology | 7         | 8      | 0.26%   |
| Lexar               | 5         | 5      | 0.18%   |
| BIWIN               | 5         | 5      | 0.18%   |
| POLION              | 4         | 4      | 0.15%   |
| Argon               | 4         | 6      | 0.15%   |
| WDC WDS2            | 3         | 3      | 0.11%   |
| Phison              | 3         | 3      | 0.11%   |
| Kingchuxing         | 3         | 3      | 0.11%   |
| Biostar             | 3         | 3      | 0.11%   |
| 2-Power             | 3         | 3      | 0.11%   |
| Unknown             | 3         | 3      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2389      | 4262   | 36.6%   |
| SSD     | 2341      | 3789   | 35.87%  |
| NVMe    | 1455      | 2213   | 22.29%  |
| MMC     | 258       | 371    | 3.95%   |
| Unknown | 84        | 122    | 1.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3807      | 7842   | 66.05%  |
| NVMe | 1454      | 2205   | 25.23%  |
| MMC  | 258       | 371    | 4.48%   |
| SAS  | 245       | 339    | 4.25%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 3104      | 5134   | 64.47%  |
| 0.51-1.0   | 1259      | 2015   | 26.15%  |
| 1.01-2.0   | 262       | 445    | 5.44%   |
| 3.01-4.0   | 71        | 153    | 1.47%   |
| 2.01-3.0   | 62        | 172    | 1.29%   |
| 4.01-10.0  | 42        | 98     | 0.87%   |
| 10.01-20.0 | 15        | 34     | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1474      | 27.4%   |
| 251-500        | 1012      | 18.81%  |
| 1-20           | 658       | 12.23%  |
| 501-1000       | 626       | 11.64%  |
| 51-100         | 449       | 8.35%   |
| 1001-2000      | 369       | 6.86%   |
| 21-50          | 271       | 5.04%   |
| Unknown        | 234       | 4.35%   |
| More than 3000 | 164       | 3.05%   |
| 2001-3000      | 123       | 2.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2293      | 41.41%  |
| 21-50          | 816       | 14.74%  |
| 101-250        | 673       | 12.15%  |
| 51-100         | 610       | 11.02%  |
| 251-500        | 349       | 6.3%    |
| 501-1000       | 290       | 5.24%   |
| Unknown        | 234       | 4.23%   |
| 1001-2000      | 160       | 2.89%   |
| 2001-3000      | 57        | 1.03%   |
| More than 3000 | 53        | 0.96%   |
| 0              | 2         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 14        | 17     | 1.94%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 11        | 13     | 1.52%   |
| Seagate ST500LT012-9WS142 500GB      | 10        | 29     | 1.38%   |
| Seagate ST3500418AS 500GB            | 9         | 12     | 1.24%   |
| Seagate ST500LT012-1DG142 500GB      | 8         | 11     | 1.11%   |
| Seagate ST500DM002-1BD142 500GB      | 8         | 8      | 1.11%   |
| Seagate ST1000DM003-9YN162 1TB       | 7         | 7      | 0.97%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 6         | 7      | 0.83%   |
| HGST HTS545050A7E680 500GB           | 6         | 6      | 0.83%   |
| Toshiba MQ01ABD100 1TB               | 5         | 6      | 0.69%   |
| Kingston SV300S37A120G 120GB SSD     | 5         | 5      | 0.69%   |
| GOODRAM SSD 120GB                    | 5         | 5      | 0.69%   |
| ASMT 2135 18TB                       | 5         | 5      | 0.69%   |
| WDC WD5000BEVT-22ZAT0 500GB          | 4         | 4      | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 4      | 0.55%   |
| Seagate ST9500420AS 500GB            | 4         | 4      | 0.55%   |
| Seagate ST9320325AS 320GB            | 4         | 4      | 0.55%   |
| Seagate ST92505610AS 250GB           | 4         | 4      | 0.55%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 4         | 4      | 0.55%   |
| Seagate ST3320613AS 320GB            | 4         | 4      | 0.55%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 5      | 0.55%   |
| Seagate ST1000DX001-1CM162 1TB       | 4         | 7      | 0.55%   |
| Kingston SA400S37480G 480GB SSD      | 4         | 4      | 0.55%   |
| Hitachi HTS543225L9SA00 250GB        | 4         | 4      | 0.55%   |
| Hitachi HTS541612J9SA00 120GB        | 4         | 5      | 0.55%   |
| A-DATA Technology SU800 512GB SSD    | 4         | 4      | 0.55%   |
| WDC WD3200BPVT-80ZEST0 320GB         | 3         | 3      | 0.41%   |
| WDC WD10JFCX-68N6GN0 1TB             | 3         | 4      | 0.41%   |
| Toshiba MK3265GSX 320GB              | 3         | 3      | 0.41%   |
| Toshiba MK1637GSX 160GB              | 3         | 3      | 0.41%   |
| Toshiba MK1246GSX 120GB              | 3         | 3      | 0.41%   |
| Seagate ST980811AS 80GB              | 3         | 3      | 0.41%   |
| Seagate ST9250827AS 250GB            | 3         | 4      | 0.41%   |
| Seagate ST9250410AS 250GB            | 3         | 3      | 0.41%   |
| Seagate ST9250315AS 250GB            | 3         | 3      | 0.41%   |
| Seagate ST9160821AS 160GB            | 3         | 4      | 0.41%   |
| Seagate ST3500320AS 500GB            | 3         | 3      | 0.41%   |
| Seagate ST3500312CS 500GB            | 3         | 3      | 0.41%   |
| Seagate ST3320418AS 320GB            | 3         | 3      | 0.41%   |
| Seagate ST3250410AS 250GB            | 3         | 3      | 0.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 202       | 270    | 29.06%  |
| WDC                   | 130       | 188    | 18.71%  |
| Hitachi               | 61        | 76     | 8.78%   |
| Samsung Electronics   | 55        | 63     | 7.91%   |
| Toshiba               | 50        | 61     | 7.19%   |
| A-DATA Technology     | 31        | 34     | 4.46%   |
| SanDisk               | 17        | 20     | 2.45%   |
| HGST                  | 17        | 18     | 2.45%   |
| Kingston              | 15        | 15     | 2.16%   |
| SK hynix              | 14        | 15     | 2.01%   |
| Fujitsu               | 10        | 12     | 1.44%   |
| Intel                 | 8         | 8      | 1.15%   |
| GOODRAM               | 8         | 8      | 1.15%   |
| Micron Technology     | 6         | 6      | 0.86%   |
| LITEON                | 6         | 6      | 0.86%   |
| Crucial               | 6         | 14     | 0.86%   |
| ASMT                  | 6         | 7      | 0.86%   |
| Maxtor                | 5         | 5      | 0.72%   |
| LITEONIT              | 4         | 4      | 0.58%   |
| China                 | 4         | 5      | 0.58%   |
| Apacer                | 4         | 7      | 0.58%   |
| SPCC                  | 3         | 3      | 0.43%   |
| Patriot               | 3         | 5      | 0.43%   |
| OCZ                   | 3         | 3      | 0.43%   |
| Hewlett-Packard       | 3         | 3      | 0.43%   |
| ASMedia               | 3         | 3      | 0.43%   |
| SSSTC                 | 2         | 2      | 0.29%   |
| Apple                 | 2         | 2      | 0.29%   |
| XPG                   | 1         | 1      | 0.14%   |
| WDC WDS2              | 1         | 1      | 0.14%   |
| WD MediaMax           | 1         | 2      | 0.14%   |
| SAGE                  | 1         | 1      | 0.14%   |
| RENICE                | 1         | 1      | 0.14%   |
| Realtek Semiconductor | 1         | 1      | 0.14%   |
| POLION                | 1         | 1      | 0.14%   |
| Plextor               | 1         | 1      | 0.14%   |
| Platinet              | 1         | 1      | 0.14%   |
| Lexar                 | 1         | 1      | 0.14%   |
| Lenovo                | 1         | 1      | 0.14%   |
| KingSpec              | 1         | 1      | 0.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 202       | 270    | 39%     |
| WDC                 | 127       | 184    | 24.52%  |
| Hitachi             | 61        | 76     | 11.78%  |
| Toshiba             | 47        | 58     | 9.07%   |
| Samsung Electronics | 40        | 46     | 7.72%   |
| HGST                | 17        | 18     | 3.28%   |
| Fujitsu             | 10        | 12     | 1.93%   |
| Maxtor              | 5         | 5      | 0.97%   |
| ASMedia             | 2         | 2      | 0.39%   |
| WD MediaMax         | 1         | 2      | 0.19%   |
| SAGE                | 1         | 1      | 0.19%   |
| JMicron Technology  | 1         | 2      | 0.19%   |
| Hewlett-Packard     | 1         | 1      | 0.19%   |
| ASMT                | 1         | 2      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |
| Unknown             | 1         | 1      | 0.19%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 480       | 681    | 73.51%  |
| SSD  | 148       | 174    | 22.66%  |
| NVMe | 25        | 28     | 3.83%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB         | 1         | 1      | 7.69%   |
| WDC WD3200BEVT-22ZCT0 320GB       | 1         | 1      | 7.69%   |
| WDC WD3200BEKT-75PVMT1 320GB      | 1         | 1      | 7.69%   |
| WDC WD2500BEVS-22UST0 250GB       | 1         | 1      | 7.69%   |
| WDC WD1600AAJS-75M0A0 160GB       | 1         | 1      | 7.69%   |
| Toshiba MK3265GSXN 320GB          | 1         | 1      | 7.69%   |
| Toshiba DT01ACA100 1TB            | 1         | 2      | 7.69%   |
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 7.69%   |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 7.69%   |
| Seagate ST31000528AS 1TB          | 1         | 1      | 7.69%   |
| Samsung Electronics HD250HJ 250GB | 1         | 1      | 7.69%   |
| OCZ-AGIL ITY3 64GB SSD            | 1         | 1      | 7.69%   |
| HGST HTS725025A7 250GB            | 1         | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 38.46%  |
| Seagate             | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 3      | 15.38%  |
| Samsung Electronics | 1         | 1      | 7.69%   |
| OCZ-AGIL            | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2511      | 5320   | 46.09%  |
| Works    | 2287      | 4540   | 41.98%  |
| Malfunc  | 637       | 883    | 11.69%  |
| Failed   | 13        | 14     | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3400      | 54.52%  |
| AMD                              | 908       | 14.56%  |
| Samsung Electronics              | 483       | 7.75%   |
| SanDisk                          | 180       | 2.89%   |
| Phison Electronics               | 124       | 1.99%   |
| SK hynix                         | 113       | 1.81%   |
| ASMedia Technology               | 106       | 1.7%    |
| JMicron Technology               | 102       | 1.64%   |
| ADATA Technology                 | 101       | 1.62%   |
| Kingston Technology Company      | 100       | 1.6%    |
| Nvidia                           | 93        | 1.49%   |
| Toshiba America Info Systems     | 62        | 0.99%   |
| KIOXIA                           | 59        | 0.95%   |
| Micron Technology                | 56        | 0.9%    |
| Silicon Motion                   | 51        | 0.82%   |
| Marvell Technology Group         | 49        | 0.79%   |
| Realtek Semiconductor            | 34        | 0.55%   |
| Lite-On Technology               | 29        | 0.47%   |
| Micron/Crucial Technology        | 28        | 0.45%   |
| VIA Technologies                 | 22        | 0.35%   |
| LSI Logic / Symbios Logic        | 19        | 0.3%    |
| Union Memory (Shenzhen)          | 16        | 0.26%   |
| Shenzhen Longsys Electronics     | 16        | 0.26%   |
| Silicon Integrated Systems [SiS] | 11        | 0.18%   |
| Solid State Storage Technology   | 10        | 0.16%   |
| Lenovo                           | 9         | 0.14%   |
| Hewlett-Packard                  | 9         | 0.14%   |
| Silicon Image                    | 8         | 0.13%   |
| Broadcom / LSI                   | 8         | 0.13%   |
| MAXIO Technology (Hangzhou)      | 6         | 0.1%    |
| INNOGRIT                         | 3         | 0.05%   |
| Apple                            | 3         | 0.05%   |
| Yangtze Memory Technologies      | 2         | 0.03%   |
| ULi Electronics                  | 2         | 0.03%   |
| O2 Micro                         | 2         | 0.03%   |
| Integrated Technology Express    | 2         | 0.03%   |
| Adaptec                          | 2         | 0.03%   |
| Tekram Technology                | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| OCZ Technology Group             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 599       | 8.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 249       | 3.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 240       | 3.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 240       | 3.27%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 206       | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 176       | 2.4%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 174       | 2.37%   |
| AMD 400 Series Chipset SATA Controller                                         | 166       | 2.26%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 140       | 1.91%   |
| Samsung NVMe SSD Controller 980                                                | 136       | 1.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 127       | 1.73%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 123       | 1.68%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 115       | 1.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 114       | 1.55%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 107       | 1.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 105       | 1.43%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 105       | 1.43%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 101       | 1.38%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 99        | 1.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 93        | 1.27%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 91        | 1.24%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 91        | 1.24%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 85        | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 84        | 1.14%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 82        | 1.12%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 82        | 1.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 81        | 1.1%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 78        | 1.06%   |
| Intel SSD 660P Series                                                          | 76        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 71        | 0.97%   |
| JMicron JMB363 SATA/IDE Controller                                             | 69        | 0.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 69        | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 66        | 0.9%    |
| Intel SATA Controller [RAID mode]                                              | 62        | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 61        | 0.83%   |
| Phison E12 NVMe Controller                                                     | 59        | 0.8%    |
| AMD 500 Series Chipset SATA Controller                                         | 57        | 0.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 49        | 0.67%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 47        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 47        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 3563      | 56.28%  |
| NVMe | 1470      | 23.22%  |
| IDE  | 886       | 13.99%  |
| RAID | 381       | 6.02%   |
| SAS  | 17        | 0.27%   |
| SCSI | 14        | 0.22%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3715      | 75.2%   |
| AMD          | 1173      | 23.74%  |
| ARM          | 45        | 0.91%   |
| QUALCOMM     | 3         | 0.06%   |
| PowerMac11,2 | 1         | 0.02%   |
| PowerBook6,7 | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |
| AppliedMicro | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 51        | 1.03%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 47        | 0.95%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 45        | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 44        | 0.89%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 44        | 0.89%   |
| AMD Ryzen 5 3600 6-Core Processor             | 43        | 0.87%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 0.81%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 37        | 0.75%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 36        | 0.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 35        | 0.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 34        | 0.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 32        | 0.64%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 32        | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 32        | 0.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 31        | 0.62%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 28        | 0.56%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 28        | 0.56%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 27        | 0.54%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 27        | 0.54%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 27        | 0.54%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 26        | 0.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 25        | 0.5%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.5%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 24        | 0.48%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.46%   |
| Intel Core i5-3570K CPU @ 3.40GHz             | 23        | 0.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.44%   |
| ARM Processor                                 | 22        | 0.44%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 0.44%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 22        | 0.44%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 22        | 0.44%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 22        | 0.44%   |
| AMD Custom APU 0405                           | 22        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.42%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 21        | 0.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 21        | 0.42%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 21        | 0.42%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 20        | 0.4%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1202      | 24.25%  |
| Intel Core i7           | 755       | 15.23%  |
| Intel Core i3           | 345       | 6.96%   |
| AMD Ryzen 5             | 322       | 6.5%    |
| Intel Core 2 Duo        | 316       | 6.38%   |
| Other                   | 261       | 5.27%   |
| Intel Celeron           | 219       | 4.42%   |
| AMD Ryzen 7             | 204       | 4.12%   |
| Intel Pentium           | 138       | 2.78%   |
| Intel Xeon              | 126       | 2.54%   |
| Intel Atom              | 84        | 1.69%   |
| Intel Pentium Dual-Core | 73        | 1.47%   |
| Intel Core 2 Quad       | 69        | 1.39%   |
| AMD Ryzen 9             | 61        | 1.23%   |
| AMD FX                  | 50        | 1.01%   |
| Intel Core 2            | 42        | 0.85%   |
| AMD Phenom II X4        | 40        | 0.81%   |
| AMD A8                  | 39        | 0.79%   |
| AMD A6                  | 39        | 0.79%   |
| AMD Ryzen 3             | 38        | 0.77%   |
| Intel Pentium Dual      | 33        | 0.67%   |
| AMD Athlon 64 X2        | 33        | 0.67%   |
| AMD A10                 | 33        | 0.67%   |
| AMD Athlon II X2        | 29        | 0.59%   |
| AMD Ryzen 7 PRO         | 20        | 0.4%    |
| AMD A4                  | 20        | 0.4%    |
| AMD Athlon II X4        | 19        | 0.38%   |
| Intel Genuine           | 18        | 0.36%   |
| Intel Core i9           | 17        | 0.34%   |
| AMD E                   | 17        | 0.34%   |
| AMD GX                  | 14        | 0.28%   |
| AMD E1                  | 14        | 0.28%   |
| AMD Ryzen 5 PRO         | 13        | 0.26%   |
| ARM BCM                 | 12        | 0.24%   |
| Intel Celeron M         | 11        | 0.22%   |
| AMD Ryzen Threadripper  | 11        | 0.22%   |
| AMD Athlon              | 11        | 0.22%   |
| AMD Athlon X2           | 9         | 0.18%   |
| Intel Pentium Silver    | 8         | 0.16%   |
| Intel Pentium M         | 8         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2120      | 42.66%  |
| 4       | 1708      | 34.37%  |
| 6       | 482       | 9.7%    |
| 8       | 303       | 6.1%    |
| 1       | 110       | 2.21%   |
| 12      | 80        | 1.61%   |
| Unknown | 71        | 1.43%   |
| 16      | 24        | 0.48%   |
| 3       | 23        | 0.46%   |
| 10      | 19        | 0.38%   |
| 14      | 16        | 0.32%   |
| 32      | 3         | 0.06%   |
| 20      | 3         | 0.06%   |
| 24      | 2         | 0.04%   |
| 192     | 1         | 0.02%   |
| 64      | 1         | 0.02%   |
| 48      | 1         | 0.02%   |
| 44      | 1         | 0.02%   |
| 18      | 1         | 0.02%   |
| 5       | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4890      | 98.93%  |
| 2       | 45        | 0.91%   |
| Unknown | 7         | 0.14%   |
| 4       | 1         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3032      | 61.01%  |
| 1       | 1866      | 37.55%  |
| Unknown | 71        | 1.43%   |
| 8       | 1         | 0.02%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4809      | 97.15%  |
| Unknown        | 85        | 1.72%   |
| 32-bit         | 54        | 1.09%   |
| 64-bit         | 2         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1213      | 23.51%  |
| 0x306a9    | 294       | 5.7%    |
| 0x206a7    | 286       | 5.54%   |
| 0x306c3    | 250       | 4.84%   |
| 0x1067a    | 225       | 4.36%   |
| 0x906ea    | 134       | 2.6%    |
| 0x506e3    | 118       | 2.29%   |
| 0x40651    | 109       | 2.11%   |
| 0x806ec    | 92        | 1.78%   |
| 0x20655    | 92        | 1.78%   |
| 0x6fd      | 90        | 1.74%   |
| 0x30678    | 90        | 1.74%   |
| 0x906e9    | 89        | 1.72%   |
| 0x806c1    | 85        | 1.65%   |
| 0x306d4    | 85        | 1.65%   |
| 0x806ea    | 80        | 1.55%   |
| 0x406e3    | 79        | 1.53%   |
| 0x10676    | 77        | 1.49%   |
| 0x806e9    | 68        | 1.32%   |
| 0x0800820d | 67        | 1.3%    |
| 0x08701021 | 63        | 1.22%   |
| 0x010000c8 | 63        | 1.22%   |
| 0x0a50000c | 57        | 1.1%    |
| 0x6fb      | 46        | 0.89%   |
| 0x06001119 | 44        | 0.85%   |
| 0x08600106 | 38        | 0.74%   |
| 0x08108109 | 38        | 0.74%   |
| 0x20652    | 34        | 0.66%   |
| 0xa0652    | 32        | 0.62%   |
| 0x6f6      | 32        | 0.62%   |
| 0x08108102 | 30        | 0.58%   |
| 0x806eb    | 29        | 0.56%   |
| 0x406c4    | 28        | 0.54%   |
| 0x08701013 | 27        | 0.52%   |
| 0x906ed    | 26        | 0.5%    |
| 0xa0653    | 25        | 0.48%   |
| 0x06000852 | 23        | 0.45%   |
| 0x706e5    | 22        | 0.43%   |
| 0x106e5    | 22        | 0.43%   |
| 0x08001138 | 22        | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 690       | 13.92%  |
| Haswell          | 466       | 9.4%    |
| IvyBridge        | 372       | 7.51%   |
| SandyBridge      | 357       | 7.2%    |
| Penryn           | 357       | 7.2%    |
| Skylake          | 261       | 5.27%   |
| Core             | 232       | 4.68%   |
| Zen 2            | 228       | 4.6%    |
| Zen+             | 175       | 3.53%   |
| Silvermont       | 175       | 3.53%   |
| Westmere         | 169       | 3.41%   |
| Unknown          | 163       | 3.29%   |
| Zen 3            | 129       | 2.6%    |
| K10              | 128       | 2.58%   |
| Broadwell        | 124       | 2.5%    |
| TigerLake        | 108       | 2.18%   |
| Zen              | 93        | 1.88%   |
| Piledriver       | 91        | 1.84%   |
| CometLake        | 88        | 1.78%   |
| K8 Hammer        | 65        | 1.31%   |
| IceLake          | 53        | 1.07%   |
| Alderlake Hybrid | 51        | 1.03%   |
| Bobcat           | 46        | 0.93%   |
| Nehalem          | 41        | 0.83%   |
| Goldmont plus    | 35        | 0.71%   |
| Bonnell          | 35        | 0.71%   |
| P6               | 33        | 0.67%   |
| Jaguar           | 28        | 0.56%   |
| Excavator        | 28        | 0.56%   |
| Goldmont         | 25        | 0.5%    |
| Steamroller      | 23        | 0.46%   |
| Puma             | 21        | 0.42%   |
| NetBurst         | 19        | 0.38%   |
| K10 Llano        | 18        | 0.36%   |
| K8 & K10 hybrid  | 16        | 0.32%   |
| Bulldozer        | 12        | 0.24%   |
| Tremont          | 1         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2784      | 47.14%  |
| Nvidia                           | 1766      | 29.9%   |
| AMD                              | 1320      | 22.35%  |
| Matrox Electronics Systems       | 15        | 0.25%   |
| ASPEED Technology                | 8         | 0.14%   |
| VIA Technologies                 | 6         | 0.1%    |
| Silicon Integrated Systems [SiS] | 6         | 0.1%    |
| S3 Graphics                      | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 285       | 4.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 234       | 3.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 137       | 2.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 112       | 1.82%   |
| Intel UHD Graphics 620                                                                   | 111       | 1.81%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 111       | 1.81%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 108       | 1.76%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 1.69%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 104       | 1.69%   |
| Intel HD Graphics 5500                                                                   | 102       | 1.66%   |
| AMD Renoir                                                                               | 102       | 1.66%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 100       | 1.63%   |
| Intel HD Graphics 530                                                                    | 100       | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 97        | 1.58%   |
| Intel Core Processor Integrated Graphics Controller                                      | 94        | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 91        | 1.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 88        | 1.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 84        | 1.37%   |
| Intel HD Graphics 620                                                                    | 84        | 1.37%   |
| Intel HD Graphics 630                                                                    | 76        | 1.24%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 74        | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 74        | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 67        | 1.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 66        | 1.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 54        | 0.88%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 54        | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 47        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 46        | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 44        | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 43        | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 43        | 0.7%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 42        | 0.68%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 42        | 0.68%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 40        | 0.65%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 38        | 0.62%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 35        | 0.57%   |
| Nvidia GT218 [GeForce 210]                                                               | 32        | 0.52%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 32        | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 31        | 0.5%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 30        | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1898      | 38.01%  |
| 1 x Nvidia               | 992       | 19.86%  |
| 1 x AMD                  | 965       | 19.32%  |
| Intel + Nvidia           | 659       | 13.2%   |
| Intel + AMD              | 178       | 3.56%   |
| AMD + Nvidia             | 103       | 2.06%   |
| 2 x AMD                  | 76        | 1.52%   |
| Other                    | 55        | 1.1%    |
| 2 x Intel                | 21        | 0.42%   |
| 1 x Matrox               | 15        | 0.3%    |
| 2 x Nvidia               | 8         | 0.16%   |
| 1 x VIA                  | 6         | 0.12%   |
| 1 x SiS                  | 6         | 0.12%   |
| 1 x ASPEED               | 5         | 0.1%    |
| Nvidia + ASPEED          | 3         | 0.06%   |
| 3 x AMD                  | 2         | 0.04%   |
| 1 x S3 Graphics          | 1         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3952      | 78.38%  |
| Proprietary | 871       | 17.27%  |
| Unknown     | 219       | 4.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2632      | 51.31%  |
| 1.01-2.0   | 668       | 13.02%  |
| 0.01-0.5   | 648       | 12.63%  |
| 0.51-1.0   | 446       | 8.69%   |
| 3.01-4.0   | 344       | 6.71%   |
| 7.01-8.0   | 193       | 3.76%   |
| 5.01-6.0   | 125       | 2.44%   |
| 8.01-16.0  | 47        | 0.92%   |
| 2.01-3.0   | 20        | 0.39%   |
| 16.01-24.0 | 6         | 0.12%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 768       | 14.02%  |
| AU Optronics            | 633       | 11.56%  |
| LG Display              | 530       | 9.68%   |
| BOE                     | 410       | 7.49%   |
| Chimei Innolux          | 377       | 6.88%   |
| Dell                    | 329       | 6.01%   |
| Goldstar                | 300       | 5.48%   |
| Iiyama                  | 186       | 3.4%    |
| Philips                 | 176       | 3.21%   |
| BenQ                    | 139       | 2.54%   |
| Lenovo                  | 138       | 2.52%   |
| Hewlett-Packard         | 134       | 2.45%   |
| Acer                    | 130       | 2.37%   |
| AOC                     | 112       | 2.05%   |
| Chi Mei Optoelectronics | 111       | 2.03%   |
| NEC Computers           | 84        | 1.53%   |
| Eizo                    | 84        | 1.53%   |
| Ancor Communications    | 69        | 1.26%   |
| Sharp                   | 57        | 1.04%   |
| PANDA                   | 46        | 0.84%   |
| LG Philips              | 46        | 0.84%   |
| Sony                    | 41        | 0.75%   |
| Fujitsu Siemens         | 36        | 0.66%   |
| InfoVision              | 35        | 0.64%   |
| LG Electronics          | 33        | 0.6%    |
| Apple                   | 32        | 0.58%   |
| ASUSTek Computer        | 27        | 0.49%   |
| Unknown                 | 22        | 0.4%    |
| Toshiba                 | 18        | 0.33%   |
| MSI                     | 18        | 0.33%   |
| Valve                   | 17        | 0.31%   |
| Idek Iiyama             | 17        | 0.31%   |
| HannStar                | 17        | 0.31%   |
| CPT                     | 15        | 0.27%   |
| ViewSonic               | 14        | 0.26%   |
| Panasonic               | 14        | 0.26%   |
| Gateway                 | 14        | 0.26%   |
| CSO                     | 14        | 0.26%   |
| Belinea                 | 13        | 0.24%   |
| Mi                      | 10        | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 32        | 0.56%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 28        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 28        | 0.49%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 26        | 0.46%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 25        | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 24        | 0.42%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 21        | 0.37%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 20        | 0.35%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 19        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 19        | 0.33%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 18        | 0.32%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 17        | 0.3%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 17        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 16        | 0.28%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 15        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 15        | 0.26%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 15        | 0.26%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 15        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 14        | 0.25%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 14        | 0.25%   |
| Philips 273PQPY PHLC096 1920x1080 597x336mm 27.0-inch                    | 14        | 0.25%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 13        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 13        | 0.23%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 13        | 0.23%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.23%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 13        | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 13        | 0.23%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.23%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 13        | 0.23%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                       | 13        | 0.23%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 12        | 0.21%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 12        | 0.21%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                     | 12        | 0.21%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 12        | 0.21%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 12        | 0.21%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 11        | 0.19%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 11        | 0.19%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2211      | 42.7%   |
| 1366x768 (WXGA)    | 882       | 17.03%  |
| 2560x1440 (QHD)    | 241       | 4.65%   |
| 3840x2160 (4K)     | 237       | 4.58%   |
| 1280x1024 (SXGA)   | 229       | 4.42%   |
| 1600x900 (HD+)     | 226       | 4.36%   |
| 1280x800 (WXGA)    | 193       | 3.73%   |
| 1680x1050 (WSXGA+) | 186       | 3.59%   |
| 1920x1200 (WUXGA)  | 181       | 3.5%    |
| 1440x900 (WXGA+)   | 145       | 2.8%    |
| 3440x1440          | 53        | 1.02%   |
| Unknown            | 52        | 1%      |
| 2560x1080          | 42        | 0.81%   |
| 2560x1600          | 29        | 0.56%   |
| 1024x600           | 27        | 0.52%   |
| 1360x768           | 23        | 0.44%   |
| 1024x768 (XGA)     | 22        | 0.42%   |
| 1600x1200          | 20        | 0.39%   |
| 800x1280           | 18        | 0.35%   |
| 3840x1080          | 16        | 0.31%   |
| 1920x540           | 12        | 0.23%   |
| 3840x2400          | 11        | 0.21%   |
| 2880x1800          | 10        | 0.19%   |
| 2160x1440          | 10        | 0.19%   |
| 2288x1287          | 8         | 0.15%   |
| 3200x1800 (QHD+)   | 7         | 0.14%   |
| 1280x720 (HD)      | 7         | 0.14%   |
| 2048x1152          | 5         | 0.1%    |
| 1280x768           | 5         | 0.1%    |
| 5120x1440          | 4         | 0.08%   |
| 1680x945           | 4         | 0.08%   |
| 1400x1050          | 4         | 0.08%   |
| 1280x960           | 4         | 0.08%   |
| 3840x1600          | 3         | 0.06%   |
| 3840x1200          | 3         | 0.06%   |
| 3286x1080          | 3         | 0.06%   |
| 3200x1080          | 3         | 0.06%   |
| 5760x1080          | 2         | 0.04%   |
| 4480x1440          | 2         | 0.04%   |
| 3600x1080          | 2         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1477      | 26.99%  |
| 24      | 443       | 8.1%    |
| 13      | 426       | 7.79%   |
| 14      | 387       | 7.07%   |
| 23      | 362       | 6.62%   |
| 17      | 344       | 6.29%   |
| 27      | 336       | 6.14%   |
| 21      | 324       | 5.92%   |
| Unknown | 262       | 4.79%   |
| 19      | 195       | 3.56%   |
| 12      | 112       | 2.05%   |
| 22      | 110       | 2.01%   |
| 34      | 88        | 1.61%   |
| 18      | 77        | 1.41%   |
| 31      | 63        | 1.15%   |
| 11      | 52        | 0.95%   |
| 20      | 51        | 0.93%   |
| 25      | 34        | 0.62%   |
| 16      | 33        | 0.6%    |
| 10      | 31        | 0.57%   |
| 84      | 29        | 0.53%   |
| 72      | 29        | 0.53%   |
| 40      | 23        | 0.42%   |
| 32      | 23        | 0.42%   |
| 54      | 18        | 0.33%   |
| 7       | 15        | 0.27%   |
| 48      | 13        | 0.24%   |
| 65      | 11        | 0.2%    |
| 28      | 11        | 0.2%    |
| 46      | 10        | 0.18%   |
| 33      | 10        | 0.18%   |
| 43      | 8         | 0.15%   |
| 42      | 8         | 0.15%   |
| 26      | 8         | 0.15%   |
| 142     | 7         | 0.13%   |
| 37      | 5         | 0.09%   |
| 3       | 5         | 0.09%   |
| 49      | 4         | 0.07%   |
| 39      | 4         | 0.07%   |
| 29      | 4         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2157      | 40.15%  |
| 501-600        | 1086      | 20.22%  |
| 401-500        | 620       | 11.54%  |
| 351-400        | 433       | 8.06%   |
| 201-300        | 382       | 7.11%   |
| Unknown        | 262       | 4.88%   |
| 701-800        | 122       | 2.27%   |
| 601-700        | 104       | 1.94%   |
| 1001-1500      | 68        | 1.27%   |
| 1501-2000      | 59        | 1.1%    |
| 801-900        | 36        | 0.67%   |
| 1-100          | 19        | 0.35%   |
| 901-1000       | 16        | 0.3%    |
| More than 2000 | 7         | 0.13%   |
| 101-200        | 1         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 3508      | 71.34%  |
| 16/10   | 720       | 14.64%  |
| Unknown | 229       | 4.66%   |
| 5/4     | 217       | 4.41%   |
| 21/9    | 95        | 1.93%   |
| 3/2     | 54        | 1.1%    |
| 4/3     | 52        | 1.06%   |
| 0.67    | 15        | 0.31%   |
| 6/5     | 9         | 0.18%   |
| 32/9    | 9         | 0.18%   |
| 1.00    | 7         | 0.14%   |
| 0.62    | 1         | 0.02%   |
| 0.56    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1470      | 27.09%  |
| 201-250        | 960       | 17.69%  |
| 81-90          | 648       | 11.94%  |
| 301-350        | 343       | 6.32%   |
| 151-200        | 322       | 5.93%   |
| Unknown        | 262       | 4.83%   |
| 251-300        | 222       | 4.09%   |
| 121-130        | 201       | 3.7%    |
| 351-500        | 195       | 3.59%   |
| 71-80          | 158       | 2.91%   |
| 141-150        | 155       | 2.86%   |
| More than 1000 | 118       | 2.17%   |
| 61-70          | 107       | 1.97%   |
| 501-1000       | 66        | 1.22%   |
| 51-60          | 52        | 0.96%   |
| 131-140        | 48        | 0.88%   |
| 41-50          | 31        | 0.57%   |
| 111-120        | 27        | 0.5%    |
| 91-100         | 21        | 0.39%   |
| 1-40           | 20        | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1815      | 34.45%  |
| 121-160       | 1446      | 27.44%  |
| 101-120       | 1342      | 25.47%  |
| Unknown       | 262       | 4.97%   |
| 161-240       | 220       | 4.18%   |
| 1-50          | 107       | 2.03%   |
| More than 240 | 77        | 1.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3991      | 78.49%  |
| 2     | 759       | 14.93%  |
| 0     | 205       | 4.03%   |
| 3     | 113       | 2.22%   |
| 4     | 15        | 0.29%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2538      | 33.21%  |
| Intel                                  | 2424      | 31.72%  |
| Qualcomm Atheros                       | 911       | 11.92%  |
| Broadcom                               | 434       | 5.68%   |
| Broadcom Limited                       | 126       | 1.65%   |
| TP-Link                                | 117       | 1.53%   |
| Marvell Technology Group               | 93        | 1.22%   |
| Huawei Technologies                    | 88        | 1.15%   |
| Dell                                   | 82        | 1.07%   |
| MediaTek                               | 80        | 1.05%   |
| Ralink                                 | 72        | 0.94%   |
| Ralink Technology                      | 70        | 0.92%   |
| Nvidia                                 | 65        | 0.85%   |
| Qualcomm Atheros Communications        | 55        | 0.72%   |
| Samsung Electronics                    | 40        | 0.52%   |
| Xiaomi                                 | 34        | 0.44%   |
| Microsoft                              | 34        | 0.44%   |
| Ericsson Business Mobile Networks      | 30        | 0.39%   |
| ASUSTek Computer                       | 29        | 0.38%   |
| Hewlett-Packard                        | 24        | 0.31%   |
| Sierra Wireless                        | 19        | 0.25%   |
| ASIX Electronics                       | 19        | 0.25%   |
| JMicron Technology                     | 17        | 0.22%   |
| Lenovo                                 | 16        | 0.21%   |
| NetGear                                | 12        | 0.16%   |
| Edimax Technology                      | 12        | 0.16%   |
| Aquantia                               | 12        | 0.16%   |
| VIA Technologies                       | 11        | 0.14%   |
| Motorola PCS                           | 11        | 0.14%   |
| Fibocom                                | 11        | 0.14%   |
| DisplayLink                            | 10        | 0.13%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.12%   |
| Qualcomm                               | 9         | 0.12%   |
| D-Link                                 | 9         | 0.12%   |
| ZTE WCDMA Technologies MSM             | 8         | 0.1%    |
| OPPO Electronics                       | 6         | 0.08%   |
| Microchip Technology                   | 6         | 0.08%   |
| HTC (High Tech Computer)               | 6         | 0.08%   |
| Texas Instruments                      | 5         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1832      | 20.46%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 265       | 2.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 242       | 2.7%    |
| Intel Wi-Fi 6 AX200                                               | 172       | 1.92%   |
| Intel Wireless 8265 / 8275                                        | 145       | 1.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 135       | 1.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 121       | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 119       | 1.33%   |
| Intel Wireless 7260                                               | 118       | 1.32%   |
| Intel Wireless 8260                                               | 102       | 1.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 99        | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 98        | 1.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 95        | 1.06%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 93        | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 88        | 0.98%   |
| Intel Wi-Fi 6 AX201                                               | 84        | 0.94%   |
| Intel Wireless 7265                                               | 83        | 0.93%   |
| Intel Ethernet Connection I217-LM                                 | 83        | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 82        | 0.92%   |
| Intel I211 Gigabit Network Connection                             | 82        | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 80        | 0.89%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 75        | 0.84%   |
| Intel Wireless 3160                                               | 68        | 0.76%   |
| Intel Wireless 3165                                               | 65        | 0.73%   |
| Intel Ethernet Connection (2) I219-V                              | 65        | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 61        | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 57        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 57        | 0.64%   |
| Intel 82579V Gigabit Network Connection                           | 55        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 55        | 0.61%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 54        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 53        | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 52        | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 51        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                     | 51        | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 50        | 0.56%   |
| Intel Centrino Ultimate-N 6300                                    | 49        | 0.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48        | 0.54%   |
| Huawei E353/E3131                                                 | 47        | 0.52%   |
| Intel WiFi Link 5100                                              | 46        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1866      | 46.63%  |
| Qualcomm Atheros                  | 692       | 17.29%  |
| Realtek Semiconductor             | 518       | 12.94%  |
| Broadcom                          | 259       | 6.47%   |
| TP-Link                           | 112       | 2.8%    |
| MediaTek                          | 76        | 1.9%    |
| Ralink                            | 72        | 1.8%    |
| Ralink Technology                 | 70        | 1.75%   |
| Broadcom Limited                  | 63        | 1.57%   |
| Qualcomm Atheros Communications   | 55        | 1.37%   |
| Dell                              | 51        | 1.27%   |
| Microsoft                         | 33        | 0.82%   |
| ASUSTek Computer                  | 29        | 0.72%   |
| Sierra Wireless                   | 19        | 0.47%   |
| Edimax Technology                 | 12        | 0.3%    |
| Fibocom                           | 11        | 0.27%   |
| Ericsson Business Mobile Networks | 9         | 0.22%   |
| D-Link                            | 9         | 0.22%   |
| NetGear                           | 8         | 0.2%    |
| Qualcomm                          | 6         | 0.15%   |
| Hewlett-Packard                   | 6         | 0.15%   |
| Sagem                             | 4         | 0.1%    |
| D-Link System                     | 3         | 0.07%   |
| Belkin Components                 | 3         | 0.07%   |
| ZyXEL Communications              | 2         | 0.05%   |
| ZyDAS                             | 2         | 0.05%   |
| Marvell Technology Group          | 2         | 0.05%   |
| Linksys                           | 2         | 0.05%   |
| Z-Com                             | 1         | 0.02%   |
| Wacom                             | 1         | 0.02%   |
| Tenda                             | 1         | 0.02%   |
| Sweex                             | 1         | 0.02%   |
| Ovislink                          | 1         | 0.02%   |
| IMC Networks                      | 1         | 0.02%   |
| AVM                               | 1         | 0.02%   |
| Accton Technology                 | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 172       | 4.29%   |
| Intel Wireless 8265 / 8275                                              | 145       | 3.61%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 135       | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 121       | 3.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 119       | 2.97%   |
| Intel Wireless 7260                                                     | 118       | 2.94%   |
| Intel Wireless 8260                                                     | 102       | 2.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 99        | 2.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 98        | 2.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 93        | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 88        | 2.19%   |
| Intel Wi-Fi 6 AX201                                                     | 84        | 2.09%   |
| Intel Wireless 7265                                                     | 83        | 2.07%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 80        | 1.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 1.87%   |
| Intel Wireless 3160                                                     | 68        | 1.69%   |
| Intel Wireless 3165                                                     | 65        | 1.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 61        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 57        | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 57        | 1.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 54        | 1.35%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 53        | 1.32%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 52        | 1.3%    |
| Broadcom BCM43142 802.11b/g/n                                           | 51        | 1.27%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 50        | 1.25%   |
| Intel Centrino Ultimate-N 6300                                          | 49        | 1.22%   |
| Intel WiFi Link 5100                                                    | 46        | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 46        | 1.15%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 43        | 1.07%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 43        | 1.07%   |
| Qualcomm Atheros AR9271 802.11n                                         | 42        | 1.05%   |
| Intel Wireless-AC 9260                                                  | 42        | 1.05%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 1.02%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 38        | 0.95%   |
| Intel Centrino Advanced-N 6235                                          | 37        | 0.92%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 35        | 0.87%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 0.82%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.82%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 32        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2324      | 49.22%  |
| Intel                                  | 1323      | 28.02%  |
| Qualcomm Atheros                       | 321       | 6.8%    |
| Broadcom                               | 217       | 4.6%    |
| Marvell Technology Group               | 92        | 1.95%   |
| Nvidia                                 | 65        | 1.38%   |
| Broadcom Limited                       | 64        | 1.36%   |
| Huawei Technologies                    | 58        | 1.23%   |
| Samsung Electronics                    | 38        | 0.8%    |
| Xiaomi                                 | 33        | 0.7%    |
| ASIX Electronics                       | 19        | 0.4%    |
| JMicron Technology                     | 17        | 0.36%   |
| Lenovo                                 | 16        | 0.34%   |
| Aquantia                               | 12        | 0.25%   |
| VIA Technologies                       | 11        | 0.23%   |
| Motorola PCS                           | 10        | 0.21%   |
| DisplayLink                            | 10        | 0.21%   |
| Silicon Integrated Systems [SiS]       | 9         | 0.19%   |
| ZTE WCDMA Technologies MSM             | 7         | 0.15%   |
| TP-Link                                | 6         | 0.13%   |
| OPPO Electronics                       | 6         | 0.13%   |
| Microchip Technology                   | 6         | 0.13%   |
| HTC (High Tech Computer)               | 6         | 0.13%   |
| Sony Ericsson Mobile Communications AB | 4         | 0.08%   |
| NetGear                                | 4         | 0.08%   |
| ICS Advent                             | 4         | 0.08%   |
| Hewlett-Packard                        | 4         | 0.08%   |
| Attansic Technology                    | 4         | 0.08%   |
| Qualcomm                               | 3         | 0.06%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.06%   |
| MediaTek                               | 3         | 0.06%   |
| Apple                                  | 3         | 0.06%   |
| Research In Motion                     | 2         | 0.04%   |
| QLogic                                 | 2         | 0.04%   |
| NetXen Incorporated                    | 2         | 0.04%   |
| Google                                 | 2         | 0.04%   |
| 3Com                                   | 2         | 0.04%   |
| QinHeng Electronics                    | 1         | 0.02%   |
| Mellanox Technologies                  | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1832      | 38.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 265       | 5.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 242       | 5.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 95        | 1.98%   |
| Intel Ethernet Connection I217-LM                                 | 83        | 1.73%   |
| Realtek RTL8125 2.5GbE Controller                                 | 82        | 1.71%   |
| Intel I211 Gigabit Network Connection                             | 82        | 1.71%   |
| Intel Ethernet Connection (2) I219-V                              | 65        | 1.36%   |
| Intel 82579V Gigabit Network Connection                           | 55        | 1.15%   |
| Intel 82567LM Gigabit Network Connection                          | 55        | 1.15%   |
| Intel Ethernet Connection (4) I219-LM                             | 51        | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 48        | 1%      |
| Huawei E353/E3131                                                 | 47        | 0.98%   |
| Intel Ethernet Connection I218-LM                                 | 46        | 0.96%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 0.88%   |
| Intel Ethernet Connection (7) I219-V                              | 40        | 0.83%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 40        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 38        | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 37        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 37        | 0.77%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 36        | 0.75%   |
| Intel Ethernet Connection (7) I219-LM                             | 34        | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 32        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 31        | 0.65%   |
| Nvidia MCP61 Ethernet                                             | 30        | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 30        | 0.63%   |
| Intel Ethernet Controller I225-V                                  | 28        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 27        | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 27        | 0.56%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 26        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 24        | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 24        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 24        | 0.5%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 24        | 0.5%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 21        | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 0.44%   |
| Intel Ethernet Connection (2) I218-V                              | 21        | 0.44%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 21        | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4430      | 53.27%  |
| WiFi     | 3746      | 45.05%  |
| Modem    | 126       | 1.52%   |
| Unknown  | 14        | 0.17%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2887      | 57.19%  |
| Ethernet | 2160      | 42.79%  |
| Unknown  | 1         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2900      | 58.43%  |
| 1     | 1863      | 37.54%  |
| 0     | 107       | 2.16%   |
| 3     | 66        | 1.33%   |
| 4     | 13        | 0.26%   |
| 5     | 5         | 0.1%    |
| 6     | 4         | 0.08%   |
| 17    | 1         | 0.02%   |
| 10    | 1         | 0.02%   |
| 9     | 1         | 0.02%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4622      | 92.68%  |
| Yes  | 365       | 7.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1323      | 45.91%  |
| Qualcomm Atheros Communications | 258       | 8.95%   |
| Realtek Semiconductor           | 197       | 6.84%   |
| Broadcom                        | 187       | 6.49%   |
| Cambridge Silicon Radio         | 183       | 6.35%   |
| IMC Networks                    | 130       | 4.51%   |
| ASUSTek Computer                | 97        | 3.37%   |
| Dell                            | 88        | 3.05%   |
| Foxconn / Hon Hai               | 84        | 2.91%   |
| Lite-On Technology              | 73        | 2.53%   |
| Hewlett-Packard                 | 61        | 2.12%   |
| Apple                           | 40        | 1.39%   |
| Toshiba                         | 31        | 1.08%   |
| Ralink                          | 21        | 0.73%   |
| Foxconn International           | 17        | 0.59%   |
| Realtek                         | 14        | 0.49%   |
| TP-Link                         | 11        | 0.38%   |
| MediaTek                        | 11        | 0.38%   |
| Alps Electric                   | 8         | 0.28%   |
| Integrated System Solution      | 7         | 0.24%   |
| Chicony Electronics             | 6         | 0.21%   |
| Taiyo Yuden                     | 5         | 0.17%   |
| Edimax Technology               | 5         | 0.17%   |
| Ralink Technology               | 3         | 0.1%    |
| Conwise Technology              | 3         | 0.1%    |
| Unknown                         | 3         | 0.1%    |
| USI                             | 2         | 0.07%   |
| Opticis                         | 2         | 0.07%   |
| Micro Star International        | 2         | 0.07%   |
| Belkin Components               | 2         | 0.07%   |
| Askey Computer                  | 2         | 0.07%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Marvell Semiconductor           | 1         | 0.03%   |
| Logitech                        | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Creative Technology             | 1         | 0.03%   |
| AboCom Systems                  | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 573       | 19.86%  |
| Intel AX201 Bluetooth                               | 187       | 6.48%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 183       | 6.34%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 168       | 5.82%   |
| Intel AX200 Bluetooth                               | 165       | 5.72%   |
| Realtek Bluetooth Radio                             | 147       | 5.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 110       | 3.81%   |
| Intel Bluetooth Device                              | 79        | 2.74%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 64        | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 57        | 1.98%   |
| IMC Networks Bluetooth Radio                        | 57        | 1.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 53        | 1.84%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 49        | 1.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 39        | 1.35%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 37        | 1.28%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.21%   |
| Dell BCM20702A0 Bluetooth Module                    | 29        | 1.01%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 26        | 0.9%    |
| IMC Networks Wireless_Device                        | 26        | 0.9%    |
| Intel AX210 Bluetooth                               | 25        | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                    | 25        | 0.87%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 0.87%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.83%   |
| Lite-On Bluetooth Device                            | 22        | 0.76%   |
| IMC Networks Bluetooth Device                       | 22        | 0.76%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.73%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 0.69%   |
| Apple Bluetooth Host Controller                     | 19        | 0.66%   |
| Broadcom BCM2070 Bluetooth Device                   | 18        | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.59%   |
| Foxconn International BCM43142A0 Bluetooth module   | 17        | 0.59%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 17        | 0.59%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 16        | 0.55%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 13        | 0.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.45%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 13        | 0.45%   |
| Broadcom BCM2045 Bluetooth                          | 13        | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3564      | 52.31%  |
| AMD                                  | 1359      | 19.95%  |
| Nvidia                               | 1213      | 17.8%   |
| C-Media Electronics                  | 99        | 1.45%   |
| Creative Labs                        | 85        | 1.25%   |
| Creative Technology                  | 50        | 0.73%   |
| Logitech                             | 28        | 0.41%   |
| Realtek Semiconductor                | 25        | 0.37%   |
| JMTek                                | 24        | 0.35%   |
| VIA Technologies                     | 21        | 0.31%   |
| Texas Instruments                    | 20        | 0.29%   |
| Lenovo                               | 19        | 0.28%   |
| Plantronics                          | 18        | 0.26%   |
| SteelSeries ApS                      | 16        | 0.23%   |
| Kingston Technology                  | 16        | 0.23%   |
| GN Netcom                            | 15        | 0.22%   |
| GYROCOM C&C                          | 12        | 0.18%   |
| Generalplus Technology               | 12        | 0.18%   |
| Silicon Integrated Systems [SiS]     | 11        | 0.16%   |
| Dell                                 | 11        | 0.16%   |
| ASUSTek Computer                     | 10        | 0.15%   |
| SAVITECH                             | 9         | 0.13%   |
| Hewlett-Packard                      | 9         | 0.13%   |
| BEHRINGER International              | 8         | 0.12%   |
| Razer USA                            | 7         | 0.1%    |
| Focusrite-Novation                   | 7         | 0.1%    |
| Sony                                 | 6         | 0.09%   |
| Samson Technologies                  | 6         | 0.09%   |
| RODE Microphones                     | 5         | 0.07%   |
| AudioQuest                           | 5         | 0.07%   |
| Valve Software                       | 4         | 0.06%   |
| USB MICROPHONE                       | 4         | 0.06%   |
| Trust                                | 4         | 0.06%   |
| M-Audio                              | 4         | 0.06%   |
| AOKEO                                | 4         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.04%   |
| Sennheiser Communications            | 3         | 0.04%   |
| ROCCAT                               | 3         | 0.04%   |
| PreSonus Audio Electronics           | 3         | 0.04%   |
| Micro Star International             | 3         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 393       | 4.89%   |
| AMD Family 17h/19h HD Audio Controller                                     | 364       | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 309       | 3.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 306       | 3.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 259       | 3.22%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 226       | 2.81%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 209       | 2.6%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 197       | 2.45%   |
| Intel Cannon Lake PCH cAVS                                                 | 196       | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 172       | 2.14%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 169       | 2.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 164       | 2.04%   |
| AMD Starship/Matisse HD Audio Controller                                   | 163       | 2.03%   |
| AMD FCH Azalia Controller                                                  | 158       | 1.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 153       | 1.9%    |
| Intel 8 Series HD Audio Controller                                         | 143       | 1.78%   |
| Intel Haswell-ULT HD Audio Controller                                      | 141       | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 137       | 1.7%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 124       | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                            | 119       | 1.48%   |
| Intel Broadwell-U Audio Controller                                         | 116       | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 116       | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 114       | 1.42%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 108       | 1.34%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 105       | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                              | 94        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 92        | 1.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 85        | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 78        | 0.97%   |
| Nvidia GP106 High Definition Audio Controller                              | 75        | 0.93%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 74        | 0.92%   |
| Intel 200 Series PCH HD Audio                                              | 71        | 0.88%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 65        | 0.81%   |
| Intel CM238 HD Audio Controller                                            | 63        | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 62        | 0.77%   |
| Nvidia High Definition Audio Controller                                    | 58        | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 58        | 0.72%   |
| AMD Kabini HDMI/DP Audio                                                   | 58        | 0.72%   |
| Nvidia GP104 High Definition Audio Controller                              | 57        | 0.71%   |
| Intel Comet Lake PCH-LP cAVS                                               | 56        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 784       | 21.2%   |
| SK hynix                     | 608       | 16.44%  |
| Kingston                     | 488       | 13.2%   |
| Unknown                      | 422       | 11.41%  |
| Micron Technology            | 315       | 8.52%   |
| GOODRAM                      | 230       | 6.22%   |
| Crucial                      | 164       | 4.43%   |
| G.Skill                      | 102       | 2.76%   |
| Corsair                      | 87        | 2.35%   |
| A-DATA Technology            | 79        | 2.14%   |
| Ramaxel Technology           | 71        | 1.92%   |
| Nanya Technology             | 57        | 1.54%   |
| Patriot                      | 56        | 1.51%   |
| Elpida                       | 51        | 1.38%   |
| Unknown                      | 25        | 0.68%   |
| Unknown (ABCD)               | 20        | 0.54%   |
| Wilk                         | 17        | 0.46%   |
| Qimonda                      | 13        | 0.35%   |
| Apacer                       | 12        | 0.32%   |
| Wilk Elektronik              | 10        | 0.27%   |
| GeIL                         | 10        | 0.27%   |
| ASint Technology             | 9         | 0.24%   |
| Silicon Power                | 5         | 0.14%   |
| Patriot Memory (PDP Systems) | 5         | 0.14%   |
| 48spaces                     | 5         | 0.14%   |
| Unifosa                      | 4         | 0.11%   |
| Transcend                    | 4         | 0.11%   |
| Team                         | 4         | 0.11%   |
| fef5                         | 4         | 0.11%   |
| Toshiba                      | 3         | 0.08%   |
| OCZ                          | 3         | 0.08%   |
| SHARETRONIC                  | 2         | 0.05%   |
| PNY                          | 2         | 0.05%   |
| AMD                          | 2         | 0.05%   |
| Aeneon                       | 2         | 0.05%   |
| Unknown (8A02)               | 1         | 0.03%   |
| Unknown (768A)               | 1         | 0.03%   |
| Unknown (0x7FFF)             | 1         | 0.03%   |
| Unknown (0x0702)             | 1         | 0.03%   |
| tigo                         | 1         | 0.03%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 42        | 1.04%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 0.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 36        | 0.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 31        | 0.77%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 29        | 0.72%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 28        | 0.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 28        | 0.69%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.67%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 25        | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 25        | 0.62%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s          | 25        | 0.62%   |
| Unknown                                                          | 25        | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 23        | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.57%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s          | 22        | 0.54%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 21        | 0.52%   |
| Kingston RAM 9905403-559.A00LF 8GB DIMM DDR3 1600MT/s            | 19        | 0.47%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 18        | 0.45%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 17        | 0.42%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 16        | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 16        | 0.4%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.4%    |
| Patriot RAM 3200 C16 Series 16GB DIMM DDR4 3266MT/s              | 16        | 0.4%    |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 16        | 0.4%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 15        | 0.37%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.37%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 15        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 14        | 0.35%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 14        | 0.35%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.35%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 14        | 0.35%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 14        | 0.35%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 14        | 0.35%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 14        | 0.35%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 13        | 0.32%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 13        | 0.32%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 13        | 0.32%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1243      | 39.75%  |
| DDR3    | 1154      | 36.9%   |
| DDR2    | 241       | 7.71%   |
| Unknown | 151       | 4.83%   |
| SDRAM   | 136       | 4.35%   |
| LPDDR4  | 77        | 2.46%   |
| LPDDR3  | 44        | 1.41%   |
| DDR     | 32        | 1.02%   |
| DDR5    | 30        | 0.96%   |
| LPDDR5  | 12        | 0.38%   |
| DRAM    | 7         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1861      | 60.56%  |
| DIMM            | 1075      | 34.98%  |
| Row Of Chips    | 109       | 3.55%   |
| Chip            | 12        | 0.39%   |
| Unknown         | 12        | 0.39%   |
| RIMM            | 2         | 0.07%   |
| Proprietary Car | 1         | 0.03%   |
| FB-DIMM         | 1         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 1092      | 31.63%  |
| 4096    | 948       | 27.46%  |
| 2048    | 578       | 16.74%  |
| 16384   | 479       | 13.88%  |
| 1024    | 207       | 6%      |
| 32768   | 110       | 3.19%   |
| 512     | 27        | 0.78%   |
| Unknown | 4         | 0.12%   |
| 131072  | 2         | 0.06%   |
| 1536    | 2         | 0.06%   |
| 256     | 2         | 0.06%   |
| 64      | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 790       | 23.03%  |
| 2667    | 423       | 12.33%  |
| 3200    | 421       | 12.27%  |
| 1333    | 221       | 6.44%   |
| 2400    | 207       | 6.03%   |
| 1334    | 143       | 4.17%   |
| 2133    | 136       | 3.96%   |
| 667     | 132       | 3.85%   |
| 800     | 125       | 3.64%   |
| 3600    | 80        | 2.33%   |
| Unknown | 80        | 2.33%   |
| 1067    | 57        | 1.66%   |
| 4199    | 43        | 1.25%   |
| 1867    | 42        | 1.22%   |
| 3266    | 33        | 0.96%   |
| 533     | 32        | 0.93%   |
| 3000    | 29        | 0.85%   |
| 1066    | 29        | 0.85%   |
| 2048    | 28        | 0.82%   |
| 975     | 27        | 0.79%   |
| 4800    | 25        | 0.73%   |
| 4267    | 23        | 0.67%   |
| 400     | 22        | 0.64%   |
| 1866    | 20        | 0.58%   |
| 1800    | 20        | 0.58%   |
| 3400    | 19        | 0.55%   |
| 2933    | 18        | 0.52%   |
| 3866    | 15        | 0.44%   |
| 3733    | 15        | 0.44%   |
| 6400    | 13        | 0.38%   |
| 2666    | 12        | 0.35%   |
| 8400    | 11        | 0.32%   |
| 3533    | 11        | 0.32%   |
| 3333    | 10        | 0.29%   |
| 333     | 10        | 0.29%   |
| 3800    | 9         | 0.26%   |
| 4266    | 7         | 0.2%    |
| 3933    | 7         | 0.2%    |
| 2866    | 7         | 0.2%    |
| 3466    | 6         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 52        | 46.43%  |
| Samsung Electronics   | 15        | 13.39%  |
| Brother Industries    | 12        | 10.71%  |
| Canon                 | 10        | 8.93%   |
| Seiko Epson           | 7         | 6.25%   |
| Prolific Technology   | 5         | 4.46%   |
| Zebra                 | 3         | 2.68%   |
| Lexmark International | 3         | 2.68%   |
| Xerox                 | 2         | 1.79%   |
| Minolta               | 1         | 0.89%   |
| MIIIW                 | 1         | 0.89%   |
| Datamax-O'Neil        | 1         | 0.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port           | 5         | 4.39%   |
| HP LaserJet 1020                        | 5         | 4.39%   |
| Samsung M2020 Series                    | 3         | 2.63%   |
| HP LaserJet P2015 series                | 3         | 2.63%   |
| HP LaserJet M14-M17                     | 3         | 2.63%   |
| Canon iP7200 series                     | 3         | 2.63%   |
| Seiko Epson AL-M310DN                   | 2         | 1.75%   |
| Samsung SCX-3400 Series                 | 2         | 1.75%   |
| Samsung ML-216x Series Laser Printer    | 2         | 1.75%   |
| Samsung ML-2010P Mono Laser Printer     | 2         | 1.75%   |
| HP LaserJet P1102                       | 2         | 1.75%   |
| HP Deskjet F4500 series                 | 2         | 1.75%   |
| HP DeskJet F4100 Printer series         | 2         | 1.75%   |
| HP Deskjet F2280 series                 | 2         | 1.75%   |
| HP DeskJet 845c                         | 2         | 1.75%   |
| HP DeskJet 840c                         | 2         | 1.75%   |
| HP DeskJet 4530 series                  | 2         | 1.75%   |
| HP DeskJet 3700 series                  | 2         | 1.75%   |
| HP DeskJet 2600 series                  | 2         | 1.75%   |
| HP Deskjet 2540 series                  | 2         | 1.75%   |
| HP Deskjet 1050 J410                    | 2         | 1.75%   |
| Canon MG5600 series                     | 2         | 1.75%   |
| Canon LiDE 400                          | 2         | 1.75%   |
| Brother DCP-J105                        | 2         | 1.75%   |
| Brother DCP-1610W                       | 2         | 1.75%   |
| Zebra ZTC GX420t                        | 1         | 0.88%   |
| Zebra LP2844 Printer                    | 1         | 0.88%   |
| Zebra LP2824                            | 1         | 0.88%   |
| Xerox WorkCentre PE16                   | 1         | 0.88%   |
| Xerox Phaser 6000B                      | 1         | 0.88%   |
| Seiko Epson Stylus NX230/SX235W Series  | 1         | 0.88%   |
| Seiko Epson L405 Series                 | 1         | 0.88%   |
| Seiko Epson L396 Series                 | 1         | 0.88%   |
| Seiko Epson L1110 Series                | 1         | 0.88%   |
| Seiko Epson ET-2710 Series              | 1         | 0.88%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 0.88%   |
| Samsung SCX-6545 Series                 | 1         | 0.88%   |
| Samsung SCX-4300 Series                 | 1         | 0.88%   |
| Samsung SCX-4200 series                 | 1         | 0.88%   |
| Samsung ML-3050/ML-3051 Laser Printer   | 1         | 0.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 13        | 61.9%   |
| Seiko Epson                 | 2         | 9.52%   |
| Plustek                     | 2         | 9.52%   |
| Ultima Electronics          | 1         | 4.76%   |
| Mustek Systems              | 1         | 4.76%   |
| Microtek International      | 1         | 4.76%   |
| Acer Peripherals (now BenQ) | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                                  | 5         | 23.81%  |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 9.52%   |
| Canon CanoScan LiDE 120                                  | 2         | 9.52%   |
| Canon CanoScan LiDE 110                                  | 2         | 9.52%   |
| Ultima Artec E+ 48U                                      | 1         | 4.76%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]      | 1         | 4.76%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 4.76%   |
| Plustek OpticSlim 1200 Scanner                           | 1         | 4.76%   |
| Plustek OpticPro 1248U Scanner #2                        | 1         | 4.76%   |
| Mustek Systems BearPaw 2448 TA Pro                       | 1         | 4.76%   |
| Microtek International USB1200 Scanner                   | 1         | 4.76%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                   | 1         | 4.76%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U              | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 635       | 22.16%  |
| Microdia                               | 282       | 9.84%   |
| IMC Networks                           | 273       | 9.53%   |
| Realtek Semiconductor                  | 244       | 8.52%   |
| Bison Electronics                      | 167       | 5.83%   |
| Sunplus Innovation Technology          | 144       | 5.03%   |
| Quanta                                 | 131       | 4.57%   |
| Suyin                                  | 117       | 4.08%   |
| Logitech                               | 110       | 3.84%   |
| Cheng Uei Precision Industry (Foxlink) | 90        | 3.14%   |
| Syntek                                 | 84        | 2.93%   |
| Lite-On Technology                     | 62        | 2.16%   |
| Silicon Motion                         | 58        | 2.02%   |
| Acer                                   | 53        | 1.85%   |
| Apple                                  | 41        | 1.43%   |
| Creative Technology                    | 35        | 1.22%   |
| Luxvisions Innotech Limited            | 32        | 1.12%   |
| Alcor Micro                            | 31        | 1.08%   |
| Ricoh                                  | 30        | 1.05%   |
| Lenovo                                 | 28        | 0.98%   |
| Z-Star Microelectronics                | 23        | 0.8%    |
| Samsung Electronics                    | 23        | 0.8%    |
| Microsoft                              | 20        | 0.7%    |
| Sonix Technology                       | 12        | 0.42%   |
| DigiTech                               | 11        | 0.38%   |
| Intel                                  | 10        | 0.35%   |
| Primax Electronics                     | 9         | 0.31%   |
| Generalplus Technology                 | 9         | 0.31%   |
| ALi                                    | 9         | 0.31%   |
| Cubeternet                             | 8         | 0.28%   |
| Hewlett-Packard                        | 7         | 0.24%   |
| Jieli Technology                       | 6         | 0.21%   |
| Importek                               | 5         | 0.17%   |
| Trust                                  | 4         | 0.14%   |
| Sunplus Technology                     | 4         | 0.14%   |
| Razer USA                              | 4         | 0.14%   |
| LG Electronics                         | 4         | 0.14%   |
| GEMBIRD                                | 4         | 0.14%   |
| Aveo Technology                        | 4         | 0.14%   |
| Xiongmai                               | 3         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 123       | 4.28%   |
| Microdia Integrated_Webcam_HD            | 90        | 3.13%   |
| Realtek Integrated_Webcam_HD             | 77        | 2.68%   |
| IMC Networks Integrated Camera           | 74        | 2.57%   |
| IMC Networks USB2.0 HD UVC WebCam        | 67        | 2.33%   |
| Sunplus Integrated_Webcam_HD             | 56        | 1.95%   |
| Chicony Lenovo EasyCamera                | 48        | 1.67%   |
| Microdia Integrated Webcam               | 43        | 1.5%    |
| Bison Integrated Camera                  | 40        | 1.39%   |
| Chicony HD WebCam                        | 39        | 1.36%   |
| Suyin Integrated_Webcam_HD               | 36        | 1.25%   |
| Syntek Integrated Camera                 | 34        | 1.18%   |
| Syntek Lenovo EasyCamera                 | 30        | 1.04%   |
| Realtek Lenovo EasyCamera                | 29        | 1.01%   |
| Acer Lenovo EasyCamera                   | 29        | 1.01%   |
| Quanta HP TrueVision HD Camera           | 28        | 0.97%   |
| Lite-On Integrated Camera                | 26        | 0.9%    |
| Realtek USB Camera                       | 25        | 0.87%   |
| Logitech Webcam C270                     | 25        | 0.87%   |
| Chicony HP HD Camera                     | 25        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam             | 23        | 0.8%    |
| Bison Lenovo Integrated Webcam           | 23        | 0.8%    |
| IMC Networks USB2.0 VGA UVC WebCam       | 22        | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)  | 21        | 0.73%   |
| Bison Lenovo EasyCamera                  | 21        | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 20        | 0.7%    |
| Realtek Integrated Webcam HD             | 20        | 0.7%    |
| Bison SunplusIT Integrated Camera        | 20        | 0.7%    |
| Quanta HD User Facing                    | 19        | 0.66%   |
| Microdia Laptop_Integrated_Webcam_HD     | 19        | 0.66%   |
| Realtek Integrated Webcam                | 18        | 0.63%   |
| Logitech HD Pro Webcam C920              | 18        | 0.63%   |
| Creative Live! Cam Sync HD [VF0770]      | 18        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)  | 18        | 0.63%   |
| IMC Networks Integrated Webcam           | 17        | 0.59%   |
| Chicony USB 2.0 Camera                   | 17        | 0.59%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 17        | 0.59%   |
| Chicony USB2.0 VGA UVC WebCam            | 16        | 0.56%   |
| Sunplus HD WebCam                        | 15        | 0.52%   |
| Lite-On HP HD Camera                     | 15        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 203       | 36.25%  |
| Synaptics                          | 138       | 24.64%  |
| Shenzhen Goodix Technology         | 69        | 12.32%  |
| AuthenTec                          | 62        | 11.07%  |
| Upek                               | 37        | 6.61%   |
| Elan Microelectronics              | 21        | 3.75%   |
| LighTuning Technology              | 15        | 2.68%   |
| STMicroelectronics                 | 14        | 2.5%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.18%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 44        | 7.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 41        | 7.32%   |
| Shenzhen Goodix  Fingerprint Device                                        | 37        | 6.61%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 35        | 6.25%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 28        | 5%      |
| Shenzhen Goodix Fingerprint Reader                                         | 25        | 4.46%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 24        | 4.29%   |
| AuthenTec AES2810                                                          | 24        | 4.29%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 4.11%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 18        | 3.21%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.5%    |
| Validity Sensors Synaptics WBDI                                            | 14        | 2.5%    |
| Synaptics Fingerprint reader [HP G6]                                       | 14        | 2.5%    |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.5%    |
| Validity Sensors VFS491                                                    | 13        | 2.32%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 13        | 2.32%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 12        | 2.14%   |
| Elan ELAN:Fingerprint                                                      | 12        | 2.14%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 11        | 1.96%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.79%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 1.61%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.61%   |
| Synaptics  WBDI                                                            | 9         | 1.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 1.61%   |
| AuthenTec AES1600                                                          | 8         | 1.43%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.25%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.07%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.07%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.89%   |
| Synaptics WBDI                                                             | 5         | 0.89%   |
| Synaptics UWP WBDI                                                         | 5         | 0.89%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.89%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.89%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.71%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.71%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.71%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.71%   |
| Synaptics WBDI Device                                                      | 3         | 0.54%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.36%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 234       | 55.45%  |
| Alcor Micro               | 84        | 19.91%  |
| O2 Micro                  | 45        | 10.66%  |
| Upek                      | 22        | 5.21%   |
| Lenovo                    | 20        | 4.74%   |
| Gemalto (was Gemplus)     | 5         | 1.18%   |
| Advanced Card Systems     | 3         | 0.71%   |
| OmniKey                   | 2         | 0.47%   |
| Clay Logic                | 2         | 0.47%   |
| Cherry                    | 2         | 0.47%   |
| SCM Microsystems          | 1         | 0.24%   |
| Reiner SCT Kartensysteme  | 1         | 0.24%   |
| Aladdin Knowledge Systems | 1         | 0.24%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 81        | 19.19%  |
| Broadcom BCM5880 Secure Applications Processor                               | 73        | 17.3%   |
| Broadcom 58200                                                               | 62        | 14.69%  |
| Broadcom 5880                                                                | 57        | 13.51%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 41        | 9.72%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 38        | 9%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 5.21%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 4.74%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.66%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.71%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.47%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.47%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 0.47%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.47%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.47%   |
| SCM Microsystems SCR333 SmartCard Reader                                     | 1         | 0.24%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.24%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.24%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.24%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.24%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.24%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.24%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.24%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 3441      | 67.74%  |
| 1     | 1269      | 24.98%  |
| 2     | 312       | 6.14%   |
| 3     | 44        | 0.87%   |
| 4     | 7         | 0.14%   |
| 7     | 3         | 0.06%   |
| 6     | 2         | 0.04%   |
| 5     | 2         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 555       | 27.79%  |
| Graphics card            | 492       | 24.64%  |
| Chipcard                 | 375       | 18.78%  |
| Net/wireless             | 170       | 8.51%   |
| Multimedia controller    | 67        | 3.36%   |
| Communication controller | 55        | 2.75%   |
| Bluetooth                | 54        | 2.7%    |
| Storage                  | 51        | 2.55%   |
| Camera                   | 42        | 2.1%    |
| Unassigned class         | 32        | 1.6%    |
| Sound                    | 24        | 1.2%    |
| Card reader              | 19        | 0.95%   |
| Net/ethernet             | 11        | 0.55%   |
| Modem                    | 11        | 0.55%   |
| Network                  | 8         | 0.4%    |
| Firewire controller      | 8         | 0.4%    |
| Storage/ide              | 6         | 0.3%    |
| Dvb card                 | 6         | 0.3%    |
| Storage/raid             | 4         | 0.2%    |
| Flash memory             | 4         | 0.2%    |
| Wireless                 | 1         | 0.05%   |
| Unclassified device      | 1         | 0.05%   |
| Tv card                  | 1         | 0.05%   |

