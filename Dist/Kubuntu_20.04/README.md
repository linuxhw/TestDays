Kubuntu 20.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 20.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_20.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_20.04/Notebook/README.md).

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

Total: 1934

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Radxa         | ROCK 5B                     | Soc         | [d864d2a31b](https://linux-hardware.org/?probe=d864d2a31b) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | Z170 PRO GAMING/AURA        | Desktop     | [87e8ae1350](https://linux-hardware.org/?probe=87e8ae1350) | Dec 29, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [742c9ebcca](https://linux-hardware.org/?probe=742c9ebcca) | Dec 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e95c7e7c7](https://linux-hardware.org/?probe=9e95c7e7c7) | Dec 28, 2022 |
| Dell          | Inspiron 5775               | Notebook    | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | Notebook    | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [895bd1b0b2](https://linux-hardware.org/?probe=895bd1b0b2) | Dec 13, 2022 |
| Acer          | Aspire A515-44              | Notebook    | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [3892b54ac4](https://linux-hardware.org/?probe=3892b54ac4) | Dec 08, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [eced972f80](https://linux-hardware.org/?probe=eced972f80) | Dec 05, 2022 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [d37c93af89](https://linux-hardware.org/?probe=d37c93af89) | Dec 05, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [db7e5686f3](https://linux-hardware.org/?probe=db7e5686f3) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [1b361e2f17](https://linux-hardware.org/?probe=1b361e2f17) | Dec 02, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [9866b7f07f](https://linux-hardware.org/?probe=9866b7f07f) | Dec 01, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [92afc95831](https://linux-hardware.org/?probe=92afc95831) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Dell          | Latitude E6440              | Notebook    | [348f786878](https://linux-hardware.org/?probe=348f786878) | Nov 26, 2022 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [e4514feafe](https://linux-hardware.org/?probe=e4514feafe) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| ASUSTek       | TUF Z270 MARK 1             | Desktop     | [dc1aa01b01](https://linux-hardware.org/?probe=dc1aa01b01) | Nov 17, 2022 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [6f1cef8a17](https://linux-hardware.org/?probe=6f1cef8a17) | Nov 15, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [e0edc946f9](https://linux-hardware.org/?probe=e0edc946f9) | Nov 13, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [518979e264](https://linux-hardware.org/?probe=518979e264) | Nov 11, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [a9a0e77be4](https://linux-hardware.org/?probe=a9a0e77be4) | Nov 11, 2022 |
| HP            | Laptop 17-ca2xxx            | Notebook    | [a31e9f30cc](https://linux-hardware.org/?probe=a31e9f30cc) | Nov 09, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [a734aa34bf](https://linux-hardware.org/?probe=a734aa34bf) | Nov 07, 2022 |
| Sony          | VGN-FW21E                   | Notebook    | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [8afc3da46d](https://linux-hardware.org/?probe=8afc3da46d) | Oct 28, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| Dell          | 0RW199                      | Desktop     | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ddc08ffe48](https://linux-hardware.org/?probe=ddc08ffe48) | Oct 22, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [7c58857f43](https://linux-hardware.org/?probe=7c58857f43) | Oct 11, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [7a11da121e](https://linux-hardware.org/?probe=7a11da121e) | Oct 11, 2022 |
| Medion        | H110H4-EM2                  | Desktop     | [7bd38709d3](https://linux-hardware.org/?probe=7bd38709d3) | Oct 09, 2022 |
| LG Electro... | 16T90P-K.ADB9U1             | Convertible | [7242c5df58](https://linux-hardware.org/?probe=7242c5df58) | Oct 09, 2022 |
| ASRock        | A75M                        | Desktop     | [b3df324d02](https://linux-hardware.org/?probe=b3df324d02) | Oct 08, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [8a89e7f4da](https://linux-hardware.org/?probe=8a89e7f4da) | Oct 06, 2022 |
| Dell          | 0C27VV A00                  | Desktop     | [0866f99d43](https://linux-hardware.org/?probe=0866f99d43) | Oct 06, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [84ba2e1db1](https://linux-hardware.org/?probe=84ba2e1db1) | Oct 05, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [bc05c332e6](https://linux-hardware.org/?probe=bc05c332e6) | Oct 04, 2022 |
| LG Electro... | 16T90P-K.ADB9U1             | Convertible | [d5bbcb7c9b](https://linux-hardware.org/?probe=d5bbcb7c9b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [76709f5d09](https://linux-hardware.org/?probe=76709f5d09) | Oct 04, 2022 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [6e0ea7e989](https://linux-hardware.org/?probe=6e0ea7e989) | Oct 03, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [2b78a7c7f1](https://linux-hardware.org/?probe=2b78a7c7f1) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [4b198e87aa](https://linux-hardware.org/?probe=4b198e87aa) | Sep 28, 2022 |
| Dell          | Latitude E5400              | Notebook    | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| HP            | Pavilion 14                 | Notebook    | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [97b748d5d3](https://linux-hardware.org/?probe=97b748d5d3) | Sep 16, 2022 |
| Dell          | Latitude 7430               | Notebook    | [4fdf1a303c](https://linux-hardware.org/?probe=4fdf1a303c) | Sep 15, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [eb49db3a8c](https://linux-hardware.org/?probe=eb49db3a8c) | Sep 14, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [1634db2e78](https://linux-hardware.org/?probe=1634db2e78) | Sep 11, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| Dell          | Precision M4800             | Notebook    | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0789b27bdb](https://linux-hardware.org/?probe=0789b27bdb) | Sep 02, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [676e223d96](https://linux-hardware.org/?probe=676e223d96) | Aug 25, 2022 |
| HP            | ProBook 4540s               | Notebook    | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | Notebook    | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [348dc86c64](https://linux-hardware.org/?probe=348dc86c64) | Aug 23, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [83e175bed9](https://linux-hardware.org/?probe=83e175bed9) | Aug 23, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [30820abfa2](https://linux-hardware.org/?probe=30820abfa2) | Aug 14, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [b2e805c687](https://linux-hardware.org/?probe=b2e805c687) | Aug 07, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23905636a4](https://linux-hardware.org/?probe=23905636a4) | Aug 06, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| Dell          | Precision 7530              | Notebook    | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [3a73f1ffdd](https://linux-hardware.org/?probe=3a73f1ffdd) | Aug 03, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [83e4b444ae](https://linux-hardware.org/?probe=83e4b444ae) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [4e335cb7ce](https://linux-hardware.org/?probe=4e335cb7ce) | Aug 01, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Dell          | 0F8098                      | Desktop     | [4e6058685a](https://linux-hardware.org/?probe=4e6058685a) | Jul 30, 2022 |
| HP            | 158A                        | Desktop     | [788844c3df](https://linux-hardware.org/?probe=788844c3df) | Jul 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [1b47c32e5d](https://linux-hardware.org/?probe=1b47c32e5d) | Jul 29, 2022 |
| HP            | 8754                        | Mini pc     | [1b0ae59d1f](https://linux-hardware.org/?probe=1b0ae59d1f) | Jul 28, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2d3706b78b](https://linux-hardware.org/?probe=2d3706b78b) | Jul 28, 2022 |
| HP            | 86E9 A                      | Desktop     | [6634eaee32](https://linux-hardware.org/?probe=6634eaee32) | Jul 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [379da1a196](https://linux-hardware.org/?probe=379da1a196) | Jul 21, 2022 |
| HP            | 8054                        | Desktop     | [466d7f5591](https://linux-hardware.org/?probe=466d7f5591) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | Notebook    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| HP            | 1790                        | Desktop     | [ff91b0d921](https://linux-hardware.org/?probe=ff91b0d921) | Jul 15, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [02a5205d57](https://linux-hardware.org/?probe=02a5205d57) | Jul 14, 2022 |
| ASRock        | J4105M                      | Desktop     | [509b122b9b](https://linux-hardware.org/?probe=509b122b9b) | Jul 12, 2022 |
| HP            | G42                         | Notebook    | [4a57fd54c6](https://linux-hardware.org/?probe=4a57fd54c6) | Jul 06, 2022 |
| Sony          | VPCSA3M9E                   | Notebook    | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [91408af847](https://linux-hardware.org/?probe=91408af847) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [530c44caa8](https://linux-hardware.org/?probe=530c44caa8) | Jun 30, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [554ba1726f](https://linux-hardware.org/?probe=554ba1726f) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3dffa312da](https://linux-hardware.org/?probe=3dffa312da) | Jun 24, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [ba64ef130a](https://linux-hardware.org/?probe=ba64ef130a) | Jun 23, 2022 |
| Dell          | Precision 5540              | Notebook    | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [13a04a66d8](https://linux-hardware.org/?probe=13a04a66d8) | Jun 12, 2022 |
| HP            | 0A98h                       | Desktop     | [d3c54ab2d6](https://linux-hardware.org/?probe=d3c54ab2d6) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [54a2c4fa94](https://linux-hardware.org/?probe=54a2c4fa94) | Jun 08, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [eb62d09265](https://linux-hardware.org/?probe=eb62d09265) | Jun 05, 2022 |
| Dell          | Latitude E5470              | Notebook    | [e858488f6f](https://linux-hardware.org/?probe=e858488f6f) | Jun 03, 2022 |
| Dell          | G7 7588                     | Notebook    | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [b450673fc0](https://linux-hardware.org/?probe=b450673fc0) | May 31, 2022 |
| Dell          | Precision 7710              | Notebook    | [f24e29d104](https://linux-hardware.org/?probe=f24e29d104) | May 30, 2022 |
| Dell          | Precision 7710              | Notebook    | [1bae5a0bf0](https://linux-hardware.org/?probe=1bae5a0bf0) | May 30, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [57e0b15d17](https://linux-hardware.org/?probe=57e0b15d17) | May 30, 2022 |
| Medion        | S6445 MD61489               | Notebook    | [a933286b06](https://linux-hardware.org/?probe=a933286b06) | May 29, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [326c7a11e6](https://linux-hardware.org/?probe=326c7a11e6) | May 28, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [765d22e752](https://linux-hardware.org/?probe=765d22e752) | May 23, 2022 |
| HP            | 15                          | Notebook    | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [dfa1010543](https://linux-hardware.org/?probe=dfa1010543) | May 21, 2022 |
| MSI           | 2AE0                        | Desktop     | [d99294cadc](https://linux-hardware.org/?probe=d99294cadc) | May 21, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b098eb44db](https://linux-hardware.org/?probe=b098eb44db) | May 18, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [ee6e90c751](https://linux-hardware.org/?probe=ee6e90c751) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [78fe695a2f](https://linux-hardware.org/?probe=78fe695a2f) | May 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [cd20eb0809](https://linux-hardware.org/?probe=cd20eb0809) | May 14, 2022 |
| Dell          | Latitude E6540              | Notebook    | [a5bb9f2b58](https://linux-hardware.org/?probe=a5bb9f2b58) | May 10, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [dc9b228486](https://linux-hardware.org/?probe=dc9b228486) | May 08, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [f1d427d32b](https://linux-hardware.org/?probe=f1d427d32b) | May 06, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [aefe7a52e0](https://linux-hardware.org/?probe=aefe7a52e0) | May 06, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [71c0c4f257](https://linux-hardware.org/?probe=71c0c4f257) | May 05, 2022 |
| HP            | ProBook 6450b               | Notebook    | [0c23a5cbc2](https://linux-hardware.org/?probe=0c23a5cbc2) | May 04, 2022 |
| HP            | Pavilion dv7                | Notebook    | [978f98cef3](https://linux-hardware.org/?probe=978f98cef3) | May 04, 2022 |
| Alienware     | 17                          | Notebook    | [1a4cd056f8](https://linux-hardware.org/?probe=1a4cd056f8) | May 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e126640b3b](https://linux-hardware.org/?probe=e126640b3b) | May 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [9f7923bcd2](https://linux-hardware.org/?probe=9f7923bcd2) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [12a0105da3](https://linux-hardware.org/?probe=12a0105da3) | Apr 29, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [3206e0f075](https://linux-hardware.org/?probe=3206e0f075) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [e77a313003](https://linux-hardware.org/?probe=e77a313003) | Apr 27, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e466d79804](https://linux-hardware.org/?probe=e466d79804) | Apr 26, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [82c13f2b01](https://linux-hardware.org/?probe=82c13f2b01) | Apr 25, 2022 |
| Dell          | Studio 1558                 | Notebook    | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [9877ddeaf6](https://linux-hardware.org/?probe=9877ddeaf6) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [848b9d8f5c](https://linux-hardware.org/?probe=848b9d8f5c) | Apr 22, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [da630d58cf](https://linux-hardware.org/?probe=da630d58cf) | Apr 22, 2022 |
| ASRock        | Z87 Pro4                    | Desktop     | [0c4cc8712f](https://linux-hardware.org/?probe=0c4cc8712f) | Apr 22, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b925b403ca](https://linux-hardware.org/?probe=b925b403ca) | Apr 20, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f8e7d70919](https://linux-hardware.org/?probe=f8e7d70919) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Dell          | Latitude 7410               | Notebook    | [da82f8bba8](https://linux-hardware.org/?probe=da82f8bba8) | Apr 15, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [2ee68b5f38](https://linux-hardware.org/?probe=2ee68b5f38) | Apr 14, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [e172be90b8](https://linux-hardware.org/?probe=e172be90b8) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [3e09de906e](https://linux-hardware.org/?probe=3e09de906e) | Apr 14, 2022 |
| Lenovo        | ThinkPad P51 20HH000AUS     | Notebook    | [b7365a4abd](https://linux-hardware.org/?probe=b7365a4abd) | Apr 14, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [bd5a2f5943](https://linux-hardware.org/?probe=bd5a2f5943) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [479b8d48fc](https://linux-hardware.org/?probe=479b8d48fc) | Apr 13, 2022 |
| MSI           | Z270 SLI PLUS               | Desktop     | [fa00f6ccd6](https://linux-hardware.org/?probe=fa00f6ccd6) | Apr 13, 2022 |
| Dell          | Latitude 5591               | Notebook    | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Dell          | Latitude 7400               | Notebook    | [2c32d69a57](https://linux-hardware.org/?probe=2c32d69a57) | Apr 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [44035cfa83](https://linux-hardware.org/?probe=44035cfa83) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [db6bf8f1b9](https://linux-hardware.org/?probe=db6bf8f1b9) | Apr 13, 2022 |
| Lenovo        | ThinkPad T430 2349T2A       | Notebook    | [344710cc3a](https://linux-hardware.org/?probe=344710cc3a) | Apr 12, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Lenovo        | IdeaPad Z585                | Notebook    | [5f84c70657](https://linux-hardware.org/?probe=5f84c70657) | Apr 10, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [13dff6f000](https://linux-hardware.org/?probe=13dff6f000) | Apr 10, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [848a486145](https://linux-hardware.org/?probe=848a486145) | Apr 10, 2022 |
| eMachines     | G525                        | Notebook    | [6ba45c519c](https://linux-hardware.org/?probe=6ba45c519c) | Apr 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [272c9f107a](https://linux-hardware.org/?probe=272c9f107a) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Positivo      | N1250                       | Notebook    | [c64a47d6fc](https://linux-hardware.org/?probe=c64a47d6fc) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [dea231bf61](https://linux-hardware.org/?probe=dea231bf61) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b02ac7d8ce](https://linux-hardware.org/?probe=b02ac7d8ce) | Apr 07, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f98a0cf73b](https://linux-hardware.org/?probe=f98a0cf73b) | Apr 05, 2022 |
| Dell          | Latitude E6530              | Notebook    | [a63f363043](https://linux-hardware.org/?probe=a63f363043) | Apr 04, 2022 |
| HP            | 805D                        | Desktop     | [709488e1da](https://linux-hardware.org/?probe=709488e1da) | Mar 31, 2022 |
| Lenovo        | ThinkPad T540p 20BEA00FR... | Notebook    | [c9323a9c40](https://linux-hardware.org/?probe=c9323a9c40) | Mar 31, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [946628cb20](https://linux-hardware.org/?probe=946628cb20) | Mar 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [b61b3e31e7](https://linux-hardware.org/?probe=b61b3e31e7) | Mar 30, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [f47336bbed](https://linux-hardware.org/?probe=f47336bbed) | Mar 30, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f398041b40](https://linux-hardware.org/?probe=f398041b40) | Mar 29, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [5dae1dd2a5](https://linux-hardware.org/?probe=5dae1dd2a5) | Mar 28, 2022 |
| HP            | Pavilion 14                 | Notebook    | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| HP            | Stream Notebook PC 14       | Notebook    | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [fe29ba6b10](https://linux-hardware.org/?probe=fe29ba6b10) | Mar 27, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [dc2a2c1054](https://linux-hardware.org/?probe=dc2a2c1054) | Mar 25, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [f0a08eb35b](https://linux-hardware.org/?probe=f0a08eb35b) | Mar 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [eef252e4f2](https://linux-hardware.org/?probe=eef252e4f2) | Mar 25, 2022 |
| Avell High... | B.ON                        | Notebook    | [19b689aa12](https://linux-hardware.org/?probe=19b689aa12) | Mar 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [713ff9dcb8](https://linux-hardware.org/?probe=713ff9dcb8) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [e5fe628a7b](https://linux-hardware.org/?probe=e5fe628a7b) | Mar 23, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d3b1757cf5](https://linux-hardware.org/?probe=d3b1757cf5) | Mar 21, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0e4992c717](https://linux-hardware.org/?probe=0e4992c717) | Mar 20, 2022 |
| HP            | 1589                        | Desktop     | [998f465bfc](https://linux-hardware.org/?probe=998f465bfc) | Mar 19, 2022 |
| Panasonic     | FZ-M1CC-51BE                | Notebook    | [94e014ee40](https://linux-hardware.org/?probe=94e014ee40) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [df958219ab](https://linux-hardware.org/?probe=df958219ab) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [d46b854bd5](https://linux-hardware.org/?probe=d46b854bd5) | Mar 18, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [acdee8aa65](https://linux-hardware.org/?probe=acdee8aa65) | Mar 15, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [c8809e0561](https://linux-hardware.org/?probe=c8809e0561) | Mar 15, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [96b413780f](https://linux-hardware.org/?probe=96b413780f) | Mar 13, 2022 |
| ASRock        | B360 Gaming K4              | Desktop     | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| HP            | 82F1                        | Desktop     | [390462d20a](https://linux-hardware.org/?probe=390462d20a) | Mar 10, 2022 |
| HP            | 82F1                        | Desktop     | [63273af14a](https://linux-hardware.org/?probe=63273af14a) | Mar 10, 2022 |
| MSI           | PRESTIGE X570 CREATION      | Desktop     | [2032fbba77](https://linux-hardware.org/?probe=2032fbba77) | Mar 09, 2022 |
| Medion        | E2292 MD63390               | Convertible | [6f0eb8e6d7](https://linux-hardware.org/?probe=6f0eb8e6d7) | Mar 07, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [456b0dd391](https://linux-hardware.org/?probe=456b0dd391) | Mar 06, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [19c66b47da](https://linux-hardware.org/?probe=19c66b47da) | Mar 06, 2022 |
| HP            | 8266                        | Desktop     | [e0991ef205](https://linux-hardware.org/?probe=e0991ef205) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| Unknown       | KN12A                       | Notebook    | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [7d46bb8f25](https://linux-hardware.org/?probe=7d46bb8f25) | Mar 03, 2022 |
| Dell          | Latitude E6530              | Notebook    | [f13c84346e](https://linux-hardware.org/?probe=f13c84346e) | Mar 02, 2022 |
| ASUSTek       | K55N                        | Notebook    | [6143b27a96](https://linux-hardware.org/?probe=6143b27a96) | Mar 02, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| MSI           | H81M-E34                    | Desktop     | [563e906e47](https://linux-hardware.org/?probe=563e906e47) | Mar 01, 2022 |
| Schenker      | VIA 15                      | Notebook    | [c84aacc342](https://linux-hardware.org/?probe=c84aacc342) | Feb 28, 2022 |
| Dell          | 042P49 A01                  | Desktop     | [25c0e14020](https://linux-hardware.org/?probe=25c0e14020) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | Notebook    | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [c7db8c9806](https://linux-hardware.org/?probe=c7db8c9806) | Feb 27, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [2e06b2fed8](https://linux-hardware.org/?probe=2e06b2fed8) | Feb 27, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [83dec4f285](https://linux-hardware.org/?probe=83dec4f285) | Feb 26, 2022 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [3f97cefeb4](https://linux-hardware.org/?probe=3f97cefeb4) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [fb4c469104](https://linux-hardware.org/?probe=fb4c469104) | Feb 26, 2022 |
| Biostar       | B450MH                      | Desktop     | [40f413ddcb](https://linux-hardware.org/?probe=40f413ddcb) | Feb 26, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [8e648c583a](https://linux-hardware.org/?probe=8e648c583a) | Feb 25, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | Notebook    | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Unknown       | TB-4000                     | Desktop     | [70155eb876](https://linux-hardware.org/?probe=70155eb876) | Feb 24, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [9d9c4fe241](https://linux-hardware.org/?probe=9d9c4fe241) | Feb 23, 2022 |
| Fujitsu       | D3164-C2 S26361-D3164-C2    | Desktop     | [84b8eefa6d](https://linux-hardware.org/?probe=84b8eefa6d) | Feb 23, 2022 |
| Supermicro    | X10DAI                      | Desktop     | [4de85d4700](https://linux-hardware.org/?probe=4de85d4700) | Feb 23, 2022 |
| Lenovo        | ThinkPad T430 23495P8       | Notebook    | [03266eea0a](https://linux-hardware.org/?probe=03266eea0a) | Feb 23, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [259dd8bc78](https://linux-hardware.org/?probe=259dd8bc78) | Feb 19, 2022 |
| Lenovo        | ThinkPad L430 2468CTO       | Notebook    | [9244a0f8f9](https://linux-hardware.org/?probe=9244a0f8f9) | Feb 18, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES2... | Convertible | [83a05f5d1e](https://linux-hardware.org/?probe=83a05f5d1e) | Feb 18, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [ffb9eb537e](https://linux-hardware.org/?probe=ffb9eb537e) | Feb 17, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [9628754bf4](https://linux-hardware.org/?probe=9628754bf4) | Feb 17, 2022 |
| Dell          | 0J8G6F A03                  | Desktop     | [c4314fa1c4](https://linux-hardware.org/?probe=c4314fa1c4) | Feb 17, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [9773bc9c72](https://linux-hardware.org/?probe=9773bc9c72) | Feb 16, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [88c9f0db96](https://linux-hardware.org/?probe=88c9f0db96) | Feb 16, 2022 |
| Gateway       | IPISB-VR                    | Desktop     | [af56b8d361](https://linux-hardware.org/?probe=af56b8d361) | Feb 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [4e3b8bfbb1](https://linux-hardware.org/?probe=4e3b8bfbb1) | Feb 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [3db88acec8](https://linux-hardware.org/?probe=3db88acec8) | Feb 15, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [b4db24332b](https://linux-hardware.org/?probe=b4db24332b) | Feb 14, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [5768ab0770](https://linux-hardware.org/?probe=5768ab0770) | Feb 13, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a98c8db3ad](https://linux-hardware.org/?probe=a98c8db3ad) | Feb 12, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [5795d9b341](https://linux-hardware.org/?probe=5795d9b341) | Feb 12, 2022 |
| ASUSTek       | X540NA                      | Notebook    | [a9271fbd9f](https://linux-hardware.org/?probe=a9271fbd9f) | Feb 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | Desktop     | [ed39168e58](https://linux-hardware.org/?probe=ed39168e58) | Feb 12, 2022 |
| Dell          | Latitude 5580               | Notebook    | [77466f0d8f](https://linux-hardware.org/?probe=77466f0d8f) | Feb 11, 2022 |
| Dell          | Latitude 5580               | Notebook    | [8d65e0f7c7](https://linux-hardware.org/?probe=8d65e0f7c7) | Feb 11, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [2885a7e3ed](https://linux-hardware.org/?probe=2885a7e3ed) | Feb 11, 2022 |
| MSI           | Prestige 14 A10RB           | Notebook    | [7195cacd54](https://linux-hardware.org/?probe=7195cacd54) | Feb 10, 2022 |
| MSI           | MAG B550M MORTAR            | Desktop     | [5e071a1807](https://linux-hardware.org/?probe=5e071a1807) | Feb 09, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9c3722a690](https://linux-hardware.org/?probe=9c3722a690) | Feb 07, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [784b1b0c3b](https://linux-hardware.org/?probe=784b1b0c3b) | Feb 06, 2022 |
| Dell          | System XPS L502X            | Notebook    | [c2a3b5d930](https://linux-hardware.org/?probe=c2a3b5d930) | Feb 05, 2022 |
| Medion        | E4241 MD60996               | Notebook    | [d89f5e4089](https://linux-hardware.org/?probe=d89f5e4089) | Feb 05, 2022 |
| Lenovo        | G710 20252                  | Notebook    | [ffc1b2ca5a](https://linux-hardware.org/?probe=ffc1b2ca5a) | Feb 04, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3e8a21888f](https://linux-hardware.org/?probe=3e8a21888f) | Feb 04, 2022 |
| Lenovo        | V580c 20160                 | Notebook    | [8b9e72e0ed](https://linux-hardware.org/?probe=8b9e72e0ed) | Feb 03, 2022 |
| HP            | Laptop 15g-br1xx            | Notebook    | [092ea39c7e](https://linux-hardware.org/?probe=092ea39c7e) | Feb 03, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [df711c6514](https://linux-hardware.org/?probe=df711c6514) | Feb 03, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [4c55c42084](https://linux-hardware.org/?probe=4c55c42084) | Feb 03, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [a2fbd7d84e](https://linux-hardware.org/?probe=a2fbd7d84e) | Feb 03, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [ba1cbdf586](https://linux-hardware.org/?probe=ba1cbdf586) | Feb 03, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [3df622872c](https://linux-hardware.org/?probe=3df622872c) | Feb 03, 2022 |
| HP            | Pavilion dv6                | Notebook    | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [3035fdad91](https://linux-hardware.org/?probe=3035fdad91) | Feb 03, 2022 |
| ASUSTek       | Q87M-E                      | Desktop     | [99abdcb1fe](https://linux-hardware.org/?probe=99abdcb1fe) | Feb 02, 2022 |
| ASUSTek       | WS-C621E-SAGE Series        | Server      | [46a851b841](https://linux-hardware.org/?probe=46a851b841) | Feb 02, 2022 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [0404256996](https://linux-hardware.org/?probe=0404256996) | Feb 01, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [8f83ae693d](https://linux-hardware.org/?probe=8f83ae693d) | Jan 31, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [be02f0bd97](https://linux-hardware.org/?probe=be02f0bd97) | Jan 31, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [e8b6865345](https://linux-hardware.org/?probe=e8b6865345) | Jan 31, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | Desktop     | [1c6777fb1a](https://linux-hardware.org/?probe=1c6777fb1a) | Jan 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [cd876e95b9](https://linux-hardware.org/?probe=cd876e95b9) | Jan 29, 2022 |
| System76      | Serval WS                   | Notebook    | [a6e447aa98](https://linux-hardware.org/?probe=a6e447aa98) | Jan 28, 2022 |
| System76      | Serval WS                   | Notebook    | [371fbc5a98](https://linux-hardware.org/?probe=371fbc5a98) | Jan 28, 2022 |
| Dell          | G5 5500                     | Notebook    | [4917524046](https://linux-hardware.org/?probe=4917524046) | Jan 28, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [7daa77d5ba](https://linux-hardware.org/?probe=7daa77d5ba) | Jan 27, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [311e85f0cb](https://linux-hardware.org/?probe=311e85f0cb) | Jan 27, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [a23be61a14](https://linux-hardware.org/?probe=a23be61a14) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [3e03426280](https://linux-hardware.org/?probe=3e03426280) | Jan 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [4283316d8a](https://linux-hardware.org/?probe=4283316d8a) | Jan 26, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [12d652c14a](https://linux-hardware.org/?probe=12d652c14a) | Jan 23, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [bd43e4b748](https://linux-hardware.org/?probe=bd43e4b748) | Jan 22, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [fec419577b](https://linux-hardware.org/?probe=fec419577b) | Jan 22, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [bdf7199e93](https://linux-hardware.org/?probe=bdf7199e93) | Jan 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [24c10d9f2d](https://linux-hardware.org/?probe=24c10d9f2d) | Jan 20, 2022 |
| Toshiba       | Satellite S55-C             | Notebook    | [8821f2145e](https://linux-hardware.org/?probe=8821f2145e) | Jan 20, 2022 |
| Dell          | Latitude 7490               | Notebook    | [66984a4e2b](https://linux-hardware.org/?probe=66984a4e2b) | Jan 18, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [1f699a9a4d](https://linux-hardware.org/?probe=1f699a9a4d) | Jan 17, 2022 |
| HP            | G60                         | Notebook    | [0c45a490c6](https://linux-hardware.org/?probe=0c45a490c6) | Jan 17, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [bc00e00b3d](https://linux-hardware.org/?probe=bc00e00b3d) | Jan 15, 2022 |
| MSI           | B85I                        | Desktop     | [dc1862e477](https://linux-hardware.org/?probe=dc1862e477) | Jan 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d19a03f3b4](https://linux-hardware.org/?probe=d19a03f3b4) | Jan 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [31cd8dd167](https://linux-hardware.org/?probe=31cd8dd167) | Jan 14, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ef391b2ba](https://linux-hardware.org/?probe=8ef391b2ba) | Jan 13, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [232d1f1cb4](https://linux-hardware.org/?probe=232d1f1cb4) | Jan 12, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [20cc8ef2ea](https://linux-hardware.org/?probe=20cc8ef2ea) | Jan 11, 2022 |
| Gigabyte      | GA-990X-Gaming SLI-CF       | Desktop     | [a7be44496a](https://linux-hardware.org/?probe=a7be44496a) | Jan 11, 2022 |
| Lenovo        | ThinkPad E595 20NF0000GE    | Notebook    | [c78518f0ac](https://linux-hardware.org/?probe=c78518f0ac) | Jan 10, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [c09f135f63](https://linux-hardware.org/?probe=c09f135f63) | Jan 09, 2022 |
| Dell          | 0DR845                      | Desktop     | [daa833f06d](https://linux-hardware.org/?probe=daa833f06d) | Jan 08, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [c4d40f6344](https://linux-hardware.org/?probe=c4d40f6344) | Jan 08, 2022 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [82aa762a97](https://linux-hardware.org/?probe=82aa762a97) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [13c6bafd04](https://linux-hardware.org/?probe=13c6bafd04) | Jan 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [e50bae67a6](https://linux-hardware.org/?probe=e50bae67a6) | Jan 08, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [5cd2548a30](https://linux-hardware.org/?probe=5cd2548a30) | Jan 07, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [5e77633e52](https://linux-hardware.org/?probe=5e77633e52) | Jan 07, 2022 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [b44e84f8a6](https://linux-hardware.org/?probe=b44e84f8a6) | Jan 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [bab91e3b63](https://linux-hardware.org/?probe=bab91e3b63) | Jan 06, 2022 |
| ASRock        | B75 Pro3-M                  | Desktop     | [2daf055722](https://linux-hardware.org/?probe=2daf055722) | Jan 05, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [c3ddad9a30](https://linux-hardware.org/?probe=c3ddad9a30) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [85f4fcc0b6](https://linux-hardware.org/?probe=85f4fcc0b6) | Jan 03, 2022 |
| Sony          | VPCCA35FA                   | Notebook    | [f69299cbfb](https://linux-hardware.org/?probe=f69299cbfb) | Jan 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c8e2178f07](https://linux-hardware.org/?probe=c8e2178f07) | Jan 02, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b3a76ceb99](https://linux-hardware.org/?probe=b3a76ceb99) | Dec 31, 2021 |
| Dell          | Latitude 3420               | Notebook    | [a248c25326](https://linux-hardware.org/?probe=a248c25326) | Dec 31, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [8d56c47c8d](https://linux-hardware.org/?probe=8d56c47c8d) | Dec 31, 2021 |
| Lenovo        | V580c 20160                 | Notebook    | [9f9fe096db](https://linux-hardware.org/?probe=9f9fe096db) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6324598512](https://linux-hardware.org/?probe=6324598512) | Dec 30, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [38dda4af6b](https://linux-hardware.org/?probe=38dda4af6b) | Dec 30, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [b93b965f55](https://linux-hardware.org/?probe=b93b965f55) | Dec 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d39214a966](https://linux-hardware.org/?probe=d39214a966) | Dec 29, 2021 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [6f2dc843e9](https://linux-hardware.org/?probe=6f2dc843e9) | Dec 27, 2021 |
| ASRock        | Z87 Pro4                    | Desktop     | [8459ac43a8](https://linux-hardware.org/?probe=8459ac43a8) | Dec 27, 2021 |
| Acer          | Aspire T3-605               | Desktop     | [7acbb546e6](https://linux-hardware.org/?probe=7acbb546e6) | Dec 26, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [961341534c](https://linux-hardware.org/?probe=961341534c) | Dec 26, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [2a7c56982c](https://linux-hardware.org/?probe=2a7c56982c) | Dec 26, 2021 |
| ASUSTek       | ROG Strix G712LU_G712LU     | Notebook    | [4e4cc2bfb3](https://linux-hardware.org/?probe=4e4cc2bfb3) | Dec 26, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [dc6fd4bfc7](https://linux-hardware.org/?probe=dc6fd4bfc7) | Dec 25, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [6c56118d24](https://linux-hardware.org/?probe=6c56118d24) | Dec 25, 2021 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [8fdab6dc11](https://linux-hardware.org/?probe=8fdab6dc11) | Dec 23, 2021 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [c72566a702](https://linux-hardware.org/?probe=c72566a702) | Dec 21, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [1d27772094](https://linux-hardware.org/?probe=1d27772094) | Dec 21, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [992c6c4350](https://linux-hardware.org/?probe=992c6c4350) | Dec 21, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | Notebook    | [5c05fe22a6](https://linux-hardware.org/?probe=5c05fe22a6) | Dec 20, 2021 |
| Lenovo        | G505 20240                  | Notebook    | [e29df1e2a0](https://linux-hardware.org/?probe=e29df1e2a0) | Dec 19, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f68d8e194a](https://linux-hardware.org/?probe=f68d8e194a) | Dec 18, 2021 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [c4b9060346](https://linux-hardware.org/?probe=c4b9060346) | Dec 18, 2021 |
| Unknown       | Unknown                     | Notebook    | [1892cdff8d](https://linux-hardware.org/?probe=1892cdff8d) | Dec 17, 2021 |
| Lenovo        | Unknown                     | Desktop     | [64951d70ab](https://linux-hardware.org/?probe=64951d70ab) | Dec 16, 2021 |
| Dell          | Latitude 5590               | Notebook    | [db16174d3a](https://linux-hardware.org/?probe=db16174d3a) | Dec 16, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [9ed21194f5](https://linux-hardware.org/?probe=9ed21194f5) | Dec 15, 2021 |
| HP            | Pavilion g6                 | Notebook    | [a39e3fe72e](https://linux-hardware.org/?probe=a39e3fe72e) | Dec 13, 2021 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [463119e0f9](https://linux-hardware.org/?probe=463119e0f9) | Dec 09, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6ad7a31369](https://linux-hardware.org/?probe=6ad7a31369) | Dec 08, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [8473dd1cc0](https://linux-hardware.org/?probe=8473dd1cc0) | Dec 08, 2021 |
| HP            | 8750                        | Desktop     | [b6c8c71af0](https://linux-hardware.org/?probe=b6c8c71af0) | Dec 07, 2021 |
| HP            | 8750                        | Desktop     | [5c912921e0](https://linux-hardware.org/?probe=5c912921e0) | Dec 07, 2021 |
| Lenovo        | IdeaPad C340-14IML 81TK     | Convertible | [0114082cf9](https://linux-hardware.org/?probe=0114082cf9) | Dec 07, 2021 |
| HP            | Presario CQ57               | Notebook    | [38f630bbc9](https://linux-hardware.org/?probe=38f630bbc9) | Dec 06, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [10bd6955bd](https://linux-hardware.org/?probe=10bd6955bd) | Dec 04, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Chuwi         | GemiBook                    | Notebook    | [1e8e0ca774](https://linux-hardware.org/?probe=1e8e0ca774) | Dec 03, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [dfc664e15c](https://linux-hardware.org/?probe=dfc664e15c) | Dec 03, 2021 |
| Acer          | Aspire VN7-572TG            | Notebook    | [b930282529](https://linux-hardware.org/?probe=b930282529) | Dec 02, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [fc34582970](https://linux-hardware.org/?probe=fc34582970) | Nov 29, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [5e81a55ce3](https://linux-hardware.org/?probe=5e81a55ce3) | Nov 28, 2021 |
| Dell          | 0N4YC8 A00                  | Desktop     | [6960aecc48](https://linux-hardware.org/?probe=6960aecc48) | Nov 28, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [4aefcd6dd3](https://linux-hardware.org/?probe=4aefcd6dd3) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | Notebook    | [d63786632f](https://linux-hardware.org/?probe=d63786632f) | Nov 26, 2021 |
| MSI           | B460M PRO-VDH               | Desktop     | [4c7d18cb37](https://linux-hardware.org/?probe=4c7d18cb37) | Nov 26, 2021 |
| HP            | 212B                        | Desktop     | [0377d5dc76](https://linux-hardware.org/?probe=0377d5dc76) | Nov 23, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [d49eff3d64](https://linux-hardware.org/?probe=d49eff3d64) | Nov 21, 2021 |
| HP            | 304Ah                       | Desktop     | [ff34cb9fb8](https://linux-hardware.org/?probe=ff34cb9fb8) | Nov 20, 2021 |
| Lenovo        | V155-15API 81V5             | Notebook    | [2fa6ddfb10](https://linux-hardware.org/?probe=2fa6ddfb10) | Nov 20, 2021 |
| ASUSTek       | PRIME B560M-K               | Desktop     | [571e7e5de4](https://linux-hardware.org/?probe=571e7e5de4) | Nov 19, 2021 |
| HP            | 8599                        | Desktop     | [4103117abb](https://linux-hardware.org/?probe=4103117abb) | Nov 18, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [4b7026b949](https://linux-hardware.org/?probe=4b7026b949) | Nov 18, 2021 |
| Google        | Soraka                      | Tablet      | [72ccad3aa6](https://linux-hardware.org/?probe=72ccad3aa6) | Nov 18, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [70cffc5595](https://linux-hardware.org/?probe=70cffc5595) | Nov 16, 2021 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [941a3ff2ca](https://linux-hardware.org/?probe=941a3ff2ca) | Nov 15, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [140e781aa9](https://linux-hardware.org/?probe=140e781aa9) | Nov 14, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b7cdb93074](https://linux-hardware.org/?probe=b7cdb93074) | Nov 14, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [8394f01b73](https://linux-hardware.org/?probe=8394f01b73) | Nov 13, 2021 |
| ASUSTek       | S451LB                      | Notebook    | [996eef15cb](https://linux-hardware.org/?probe=996eef15cb) | Nov 11, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [eb66540889](https://linux-hardware.org/?probe=eb66540889) | Nov 10, 2021 |
| Dell          | Latitude E7250              | Notebook    | [5c22b9ed65](https://linux-hardware.org/?probe=5c22b9ed65) | Nov 10, 2021 |
| Fujitsu       | D3433-S2 S26361-D3433-S2    | Desktop     | [a9a66b59f1](https://linux-hardware.org/?probe=a9a66b59f1) | Nov 09, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [292992ce5a](https://linux-hardware.org/?probe=292992ce5a) | Nov 07, 2021 |
| Sony          | VPCF236FM                   | Notebook    | [dda9f712f8](https://linux-hardware.org/?probe=dda9f712f8) | Nov 07, 2021 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [e05f9fb40e](https://linux-hardware.org/?probe=e05f9fb40e) | Nov 06, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | Notebook    | [056c5c6007](https://linux-hardware.org/?probe=056c5c6007) | Nov 06, 2021 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [44642a2fa4](https://linux-hardware.org/?probe=44642a2fa4) | Nov 06, 2021 |
| Dell          | Latitude 5300 2-in-1        | Convertible | [73cf10090b](https://linux-hardware.org/?probe=73cf10090b) | Nov 06, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [8e3176012c](https://linux-hardware.org/?probe=8e3176012c) | Nov 05, 2021 |
| HP            | Spectre x360 Convertible    | Convertible | [43d9b0df9e](https://linux-hardware.org/?probe=43d9b0df9e) | Nov 05, 2021 |
| Biostar       | A68MD PRO                   | Desktop     | [19a6612e0a](https://linux-hardware.org/?probe=19a6612e0a) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RDCTO1WW     | Notebook    | [d7c67d8ce7](https://linux-hardware.org/?probe=d7c67d8ce7) | Nov 02, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [6376d7464b](https://linux-hardware.org/?probe=6376d7464b) | Nov 02, 2021 |
| Biostar       | A68MD PRO                   | Desktop     | [417cbcba6a](https://linux-hardware.org/?probe=417cbcba6a) | Nov 02, 2021 |
| Dell          | Inspiron 14 5410            | Notebook    | [6a3d844d87](https://linux-hardware.org/?probe=6a3d844d87) | Oct 30, 2021 |
| Dell          | Inspiron 14 5410            | Notebook    | [2a7532fb18](https://linux-hardware.org/?probe=2a7532fb18) | Oct 30, 2021 |
| Lenovo        | ThinkPad X230 2325L19       | Notebook    | [a120083d3c](https://linux-hardware.org/?probe=a120083d3c) | Oct 30, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [73f2c9ee59](https://linux-hardware.org/?probe=73f2c9ee59) | Oct 30, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [a01e524a66](https://linux-hardware.org/?probe=a01e524a66) | Oct 29, 2021 |
| HP            | 212B                        | Desktop     | [9d2a807f08](https://linux-hardware.org/?probe=9d2a807f08) | Oct 29, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [03af7df5b2](https://linux-hardware.org/?probe=03af7df5b2) | Oct 28, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [e07abb010e](https://linux-hardware.org/?probe=e07abb010e) | Oct 27, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e6d67ebc2e](https://linux-hardware.org/?probe=e6d67ebc2e) | Oct 27, 2021 |
| Lenovo        | ThinkCentre M71e 3157RV2    | Desktop     | [6d4dc3e8af](https://linux-hardware.org/?probe=6d4dc3e8af) | Oct 26, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [f20f2bfc32](https://linux-hardware.org/?probe=f20f2bfc32) | Oct 26, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [633fc31d82](https://linux-hardware.org/?probe=633fc31d82) | Oct 26, 2021 |
| HP            | 212B                        | Desktop     | [b72e4a7240](https://linux-hardware.org/?probe=b72e4a7240) | Oct 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [111b26a250](https://linux-hardware.org/?probe=111b26a250) | Oct 25, 2021 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | Desktop     | [afbb381cf3](https://linux-hardware.org/?probe=afbb381cf3) | Oct 25, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [3134454d4f](https://linux-hardware.org/?probe=3134454d4f) | Oct 24, 2021 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [eb97afcaa6](https://linux-hardware.org/?probe=eb97afcaa6) | Oct 24, 2021 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [0d0aa3b82b](https://linux-hardware.org/?probe=0d0aa3b82b) | Oct 24, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [51162ce3fb](https://linux-hardware.org/?probe=51162ce3fb) | Oct 22, 2021 |
| HP            | ProBook 5320m               | Notebook    | [c3f92d48e5](https://linux-hardware.org/?probe=c3f92d48e5) | Oct 21, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [273a5ff27d](https://linux-hardware.org/?probe=273a5ff27d) | Oct 20, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [6214c9eb86](https://linux-hardware.org/?probe=6214c9eb86) | Oct 20, 2021 |
| Notebook      | PB50_70RF,RD,RC             | Notebook    | [ec41eeb7c0](https://linux-hardware.org/?probe=ec41eeb7c0) | Oct 20, 2021 |
| Acer          | Aspire V5-571PG             | Notebook    | [7302dc6be1](https://linux-hardware.org/?probe=7302dc6be1) | Oct 19, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [57ee9bd872](https://linux-hardware.org/?probe=57ee9bd872) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| Intel         | D54250WYK H13922-303        | Desktop     | [21b715e26a](https://linux-hardware.org/?probe=21b715e26a) | Oct 17, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4c643fc684](https://linux-hardware.org/?probe=4c643fc684) | Oct 17, 2021 |
| Timi          | A35                         | Notebook    | [318b31ee5d](https://linux-hardware.org/?probe=318b31ee5d) | Oct 17, 2021 |
| Timi          | A34                         | Notebook    | [e2fbec93e6](https://linux-hardware.org/?probe=e2fbec93e6) | Oct 17, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [8b87eef23f](https://linux-hardware.org/?probe=8b87eef23f) | Oct 16, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [4603126532](https://linux-hardware.org/?probe=4603126532) | Oct 15, 2021 |
| Notebook      | P775DM3(-G)                 | Notebook    | [9403539acc](https://linux-hardware.org/?probe=9403539acc) | Oct 15, 2021 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [0a048a009d](https://linux-hardware.org/?probe=0a048a009d) | Oct 15, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [831fff897a](https://linux-hardware.org/?probe=831fff897a) | Oct 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0b5ca0df4e](https://linux-hardware.org/?probe=0b5ca0df4e) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [e5391d41e0](https://linux-hardware.org/?probe=e5391d41e0) | Oct 14, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [3f6e406107](https://linux-hardware.org/?probe=3f6e406107) | Oct 14, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [a0c897a604](https://linux-hardware.org/?probe=a0c897a604) | Oct 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [6559ae09ed](https://linux-hardware.org/?probe=6559ae09ed) | Oct 13, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [edd8f01f22](https://linux-hardware.org/?probe=edd8f01f22) | Oct 12, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9dc8d76ce0](https://linux-hardware.org/?probe=9dc8d76ce0) | Oct 12, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [138c57899f](https://linux-hardware.org/?probe=138c57899f) | Oct 11, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [f4cbdf70ef](https://linux-hardware.org/?probe=f4cbdf70ef) | Oct 11, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [0b1f6a34ce](https://linux-hardware.org/?probe=0b1f6a34ce) | Oct 10, 2021 |
| Dell          | Latitude 7490               | Notebook    | [8462c89ad6](https://linux-hardware.org/?probe=8462c89ad6) | Oct 10, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [b00a9b9ff3](https://linux-hardware.org/?probe=b00a9b9ff3) | Oct 09, 2021 |
| HP            | Notebook                    | Notebook    | [8051753f57](https://linux-hardware.org/?probe=8051753f57) | Oct 09, 2021 |
| HP            | ProBook 4530s               | Notebook    | [1e0b067117](https://linux-hardware.org/?probe=1e0b067117) | Oct 07, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [bc7f078524](https://linux-hardware.org/?probe=bc7f078524) | Oct 07, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [07b92ffa9f](https://linux-hardware.org/?probe=07b92ffa9f) | Oct 06, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [90c1b2e414](https://linux-hardware.org/?probe=90c1b2e414) | Oct 06, 2021 |
| Dell          | Precision M6800             | Notebook    | [24e7a40a7a](https://linux-hardware.org/?probe=24e7a40a7a) | Oct 06, 2021 |
| Intel         | DH67CL AAG10212-206         | Desktop     | [459d0f2e53](https://linux-hardware.org/?probe=459d0f2e53) | Oct 04, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [29322bf1de](https://linux-hardware.org/?probe=29322bf1de) | Oct 04, 2021 |
| Lenovo        | 0x36A017AA SDK0J40709 WI... | Desktop     | [a667195cd1](https://linux-hardware.org/?probe=a667195cd1) | Oct 03, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [cdb8dd9b53](https://linux-hardware.org/?probe=cdb8dd9b53) | Oct 03, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bea39ba8be](https://linux-hardware.org/?probe=bea39ba8be) | Oct 03, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [6b9d5f5444](https://linux-hardware.org/?probe=6b9d5f5444) | Oct 02, 2021 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [fbc7a613a6](https://linux-hardware.org/?probe=fbc7a613a6) | Sep 29, 2021 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [8366a7edd1](https://linux-hardware.org/?probe=8366a7edd1) | Sep 29, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [8641901755](https://linux-hardware.org/?probe=8641901755) | Sep 27, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [c91a5b0d8d](https://linux-hardware.org/?probe=c91a5b0d8d) | Sep 25, 2021 |
| Lenovo        | ThinkPad X61s 7667DE3       | Notebook    | [9d3daab4b3](https://linux-hardware.org/?probe=9d3daab4b3) | Sep 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e4c16022ab](https://linux-hardware.org/?probe=e4c16022ab) | Sep 24, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [0a2987d902](https://linux-hardware.org/?probe=0a2987d902) | Sep 24, 2021 |
| Lenovo        | ThinkPad T580 20L90026RT    | Notebook    | [227465cf98](https://linux-hardware.org/?probe=227465cf98) | Sep 23, 2021 |
| Dell          | Inspiron 3531               | Notebook    | [43e74b0bbb](https://linux-hardware.org/?probe=43e74b0bbb) | Sep 23, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [abdedf857f](https://linux-hardware.org/?probe=abdedf857f) | Sep 23, 2021 |
| Positivo      | CHT12CP                     | Notebook    | [1473ddbea8](https://linux-hardware.org/?probe=1473ddbea8) | Sep 22, 2021 |
| Intel         | Eaglelake Fab D             | Desktop     | [acd05f91f6](https://linux-hardware.org/?probe=acd05f91f6) | Sep 21, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c1b1b6661d](https://linux-hardware.org/?probe=c1b1b6661d) | Sep 20, 2021 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [d8df9a881c](https://linux-hardware.org/?probe=d8df9a881c) | Sep 20, 2021 |
| Lenovo        | ThinkBook 14s-IML 20RS      | Notebook    | [f93df3c890](https://linux-hardware.org/?probe=f93df3c890) | Sep 19, 2021 |
| Acer          | Aspire XC-830               | Desktop     | [c2479661bc](https://linux-hardware.org/?probe=c2479661bc) | Sep 18, 2021 |
| ASUSTek       | P8P67                       | Desktop     | [8c1582c3ed](https://linux-hardware.org/?probe=8c1582c3ed) | Sep 18, 2021 |
| ASUSTek       | TP500LN                     | Notebook    | [5e377590c7](https://linux-hardware.org/?probe=5e377590c7) | Sep 16, 2021 |
| Unknown       | Unknown                     | Notebook    | [d7b86e803f](https://linux-hardware.org/?probe=d7b86e803f) | Sep 16, 2021 |
| Gigabyte      | X99-UD3-CF                  | Desktop     | [c70024afd4](https://linux-hardware.org/?probe=c70024afd4) | Sep 16, 2021 |
| Dell          | 0J8H4R A00                  | Desktop     | [d482d475f7](https://linux-hardware.org/?probe=d482d475f7) | Sep 15, 2021 |
| HP            | ProBook x360 435 G7         | Convertible | [2e48186431](https://linux-hardware.org/?probe=2e48186431) | Sep 14, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [15fa98aa93](https://linux-hardware.org/?probe=15fa98aa93) | Sep 14, 2021 |
| HP            | 0AECh D                     | Desktop     | [42d762e479](https://linux-hardware.org/?probe=42d762e479) | Sep 12, 2021 |
| ASUSTek       | TUF Gaming FA506IV_TUF56... | Notebook    | [9cdec29684](https://linux-hardware.org/?probe=9cdec29684) | Sep 12, 2021 |
| Lenovo        | ThinkPad T550 20CJS03300    | Notebook    | [2b53cd0d2d](https://linux-hardware.org/?probe=2b53cd0d2d) | Sep 11, 2021 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [fb3c4b683c](https://linux-hardware.org/?probe=fb3c4b683c) | Sep 08, 2021 |
| HP            | 0AECh D                     | Desktop     | [be336df1da](https://linux-hardware.org/?probe=be336df1da) | Sep 08, 2021 |
| Microsoft     | Surface Laptop Go           | Tablet      | [846ba30d43](https://linux-hardware.org/?probe=846ba30d43) | Sep 07, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [014c8bb745](https://linux-hardware.org/?probe=014c8bb745) | Sep 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [99898b4c58](https://linux-hardware.org/?probe=99898b4c58) | Sep 07, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [922e1625b6](https://linux-hardware.org/?probe=922e1625b6) | Sep 07, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [07db84c018](https://linux-hardware.org/?probe=07db84c018) | Sep 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [aad125e760](https://linux-hardware.org/?probe=aad125e760) | Sep 07, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [0ab8136443](https://linux-hardware.org/?probe=0ab8136443) | Sep 07, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [48a05b1697](https://linux-hardware.org/?probe=48a05b1697) | Sep 07, 2021 |
| Dell          | Latitude 7490               | Notebook    | [5a238ecfcc](https://linux-hardware.org/?probe=5a238ecfcc) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c5fbf3298a](https://linux-hardware.org/?probe=c5fbf3298a) | Sep 06, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [889fd56c8b](https://linux-hardware.org/?probe=889fd56c8b) | Sep 05, 2021 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [10f34cd263](https://linux-hardware.org/?probe=10f34cd263) | Sep 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fe1d6870db](https://linux-hardware.org/?probe=fe1d6870db) | Sep 05, 2021 |
| ASUSTek       | TUF Gaming FA506IV_TUF56... | Notebook    | [7366162a3e](https://linux-hardware.org/?probe=7366162a3e) | Sep 05, 2021 |
| MSI           | GS63 7RE                    | Notebook    | [db1e9a9bd4](https://linux-hardware.org/?probe=db1e9a9bd4) | Sep 04, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | Notebook    | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| Lenovo        | ThinkPad E14 20RA004YUS     | Notebook    | [2eed4a9229](https://linux-hardware.org/?probe=2eed4a9229) | Sep 01, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [0a38ee6028](https://linux-hardware.org/?probe=0a38ee6028) | Sep 01, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [b409334e94](https://linux-hardware.org/?probe=b409334e94) | Aug 30, 2021 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [e0a78bb2e5](https://linux-hardware.org/?probe=e0a78bb2e5) | Aug 30, 2021 |
| Lenovo        | 3098 SDK0J40705 WIN 3425... | Desktop     | [d532b9c69c](https://linux-hardware.org/?probe=d532b9c69c) | Aug 30, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [c56901e13e](https://linux-hardware.org/?probe=c56901e13e) | Aug 30, 2021 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [d2ce2247c6](https://linux-hardware.org/?probe=d2ce2247c6) | Aug 30, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [7b8f7d0fb9](https://linux-hardware.org/?probe=7b8f7d0fb9) | Aug 29, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [a113806a4a](https://linux-hardware.org/?probe=a113806a4a) | Aug 29, 2021 |
| Gigabyte      | B75M-D3V                    | Desktop     | [7f53bb7787](https://linux-hardware.org/?probe=7f53bb7787) | Aug 28, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [5374669067](https://linux-hardware.org/?probe=5374669067) | Aug 26, 2021 |
| HP            | Pavilion g7                 | Notebook    | [bd69b29a21](https://linux-hardware.org/?probe=bd69b29a21) | Aug 24, 2021 |
| Google        | Cyan                        | Notebook    | [b8b9ee3f4b](https://linux-hardware.org/?probe=b8b9ee3f4b) | Aug 24, 2021 |
| Dell          | Latitude E6510              | Notebook    | [79b48c22ef](https://linux-hardware.org/?probe=79b48c22ef) | Aug 23, 2021 |
| ASUSTek       | H61-PLUS                    | Desktop     | [806118d8b3](https://linux-hardware.org/?probe=806118d8b3) | Aug 22, 2021 |
| Dell          | Latitude E6400              | Notebook    | [89bdf7b44a](https://linux-hardware.org/?probe=89bdf7b44a) | Aug 21, 2021 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [d9a6f9c739](https://linux-hardware.org/?probe=d9a6f9c739) | Aug 21, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [6f08d0dd20](https://linux-hardware.org/?probe=6f08d0dd20) | Aug 20, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [b708963e17](https://linux-hardware.org/?probe=b708963e17) | Aug 20, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [82ff6985ce](https://linux-hardware.org/?probe=82ff6985ce) | Aug 18, 2021 |
| ASUSTek       | Z170-WS                     | Desktop     | [ac73f29c0f](https://linux-hardware.org/?probe=ac73f29c0f) | Aug 18, 2021 |
| PC Special... | N130BU                      | Notebook    | [5fee63c283](https://linux-hardware.org/?probe=5fee63c283) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325V1K       | Notebook    | [7d414b5aee](https://linux-hardware.org/?probe=7d414b5aee) | Aug 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [05e4a8bcb2](https://linux-hardware.org/?probe=05e4a8bcb2) | Aug 16, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [56d35bbff9](https://linux-hardware.org/?probe=56d35bbff9) | Aug 16, 2021 |
| HP            | Pavilion g7                 | Notebook    | [1767745263](https://linux-hardware.org/?probe=1767745263) | Aug 15, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [599f91ad85](https://linux-hardware.org/?probe=599f91ad85) | Aug 14, 2021 |
| HP            | 8653 A                      | Desktop     | [7ba975c504](https://linux-hardware.org/?probe=7ba975c504) | Aug 13, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [3e73238fc6](https://linux-hardware.org/?probe=3e73238fc6) | Aug 13, 2021 |
| SYWZ          | S210H Series                | Desktop     | [72d2c9aafc](https://linux-hardware.org/?probe=72d2c9aafc) | Aug 13, 2021 |
| ASUSTek       | UX21E                       | Notebook    | [d334eaddee](https://linux-hardware.org/?probe=d334eaddee) | Aug 13, 2021 |
| ASUSTek       | M4A87TD                     | Desktop     | [c5c19a5f46](https://linux-hardware.org/?probe=c5c19a5f46) | Aug 11, 2021 |
| MSI           | B450M GAMING PLUS           | Desktop     | [18ff34f941](https://linux-hardware.org/?probe=18ff34f941) | Aug 10, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [e3508d3cd3](https://linux-hardware.org/?probe=e3508d3cd3) | Aug 10, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f2c3f335f8](https://linux-hardware.org/?probe=f2c3f335f8) | Aug 09, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [761bc4f353](https://linux-hardware.org/?probe=761bc4f353) | Aug 09, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [02bdf9e250](https://linux-hardware.org/?probe=02bdf9e250) | Aug 08, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [31891cbc13](https://linux-hardware.org/?probe=31891cbc13) | Aug 08, 2021 |
| ASUSTek       | FX503VD                     | Notebook    | [7c2b153867](https://linux-hardware.org/?probe=7c2b153867) | Aug 08, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [bd0ee7aa7f](https://linux-hardware.org/?probe=bd0ee7aa7f) | Aug 08, 2021 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [c98a94e99c](https://linux-hardware.org/?probe=c98a94e99c) | Aug 06, 2021 |
| Gigabyte      | H310M M.2                   | Desktop     | [9218549ef6](https://linux-hardware.org/?probe=9218549ef6) | Aug 06, 2021 |
| Gigabyte      | H310M M.2                   | Desktop     | [1f289dd5ed](https://linux-hardware.org/?probe=1f289dd5ed) | Aug 06, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [3edfb9b561](https://linux-hardware.org/?probe=3edfb9b561) | Aug 06, 2021 |
| Unknown       | Unknown                     | Notebook    | [608425d791](https://linux-hardware.org/?probe=608425d791) | Aug 05, 2021 |
| MSI           | B85M-E45                    | Desktop     | [85f98480a8](https://linux-hardware.org/?probe=85f98480a8) | Aug 05, 2021 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [aa28a89c93](https://linux-hardware.org/?probe=aa28a89c93) | Aug 05, 2021 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [4c65635b12](https://linux-hardware.org/?probe=4c65635b12) | Aug 04, 2021 |
| ASUSTek       | G55VW                       | Notebook    | [9e7dc8e8cf](https://linux-hardware.org/?probe=9e7dc8e8cf) | Aug 03, 2021 |
| HP            | ENVY TS m7                  | Notebook    | [8418d1a788](https://linux-hardware.org/?probe=8418d1a788) | Aug 03, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [b1d019f3cd](https://linux-hardware.org/?probe=b1d019f3cd) | Aug 01, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| Lenovo        | G400s VILG1                 | Notebook    | [48553f1ff1](https://linux-hardware.org/?probe=48553f1ff1) | Jul 30, 2021 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [7c3d5f062e](https://linux-hardware.org/?probe=7c3d5f062e) | Jul 30, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [30e4889c5a](https://linux-hardware.org/?probe=30e4889c5a) | Jul 30, 2021 |
| Alienware     | 17 R2                       | Notebook    | [897bcbbe33](https://linux-hardware.org/?probe=897bcbbe33) | Jul 30, 2021 |
| HP            | Notebook                    | Notebook    | [79da18091b](https://linux-hardware.org/?probe=79da18091b) | Jul 30, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [4b49f7026f](https://linux-hardware.org/?probe=4b49f7026f) | Jul 27, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [2bd8f0dd2e](https://linux-hardware.org/?probe=2bd8f0dd2e) | Jul 27, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [7c880b70f2](https://linux-hardware.org/?probe=7c880b70f2) | Jul 27, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [6df63b2eac](https://linux-hardware.org/?probe=6df63b2eac) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [54207766a6](https://linux-hardware.org/?probe=54207766a6) | Jul 26, 2021 |
| MSI           | B85M-E45                    | Desktop     | [d06bc5e141](https://linux-hardware.org/?probe=d06bc5e141) | Jul 26, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [021f8f6a56](https://linux-hardware.org/?probe=021f8f6a56) | Jul 25, 2021 |
| HP            | Pavilion g6                 | Notebook    | [41b431df89](https://linux-hardware.org/?probe=41b431df89) | Jul 25, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4ae6eba2f6](https://linux-hardware.org/?probe=4ae6eba2f6) | Jul 25, 2021 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [abb23e508c](https://linux-hardware.org/?probe=abb23e508c) | Jul 25, 2021 |
| Google        | Cyan                        | Notebook    | [46266a438c](https://linux-hardware.org/?probe=46266a438c) | Jul 24, 2021 |
| Fujitsu       | FMVS03004                   | Notebook    | [0182178989](https://linux-hardware.org/?probe=0182178989) | Jul 24, 2021 |
| Dell          | Precision 7530              | Notebook    | [ae6bf75479](https://linux-hardware.org/?probe=ae6bf75479) | Jul 23, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6c1a9d102e](https://linux-hardware.org/?probe=6c1a9d102e) | Jul 23, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [c1463a2843](https://linux-hardware.org/?probe=c1463a2843) | Jul 23, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [b40b338aac](https://linux-hardware.org/?probe=b40b338aac) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [13bcd06d5f](https://linux-hardware.org/?probe=13bcd06d5f) | Jul 23, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [e05ed6b947](https://linux-hardware.org/?probe=e05ed6b947) | Jul 23, 2021 |
| Foxconn       | ELA01                       | Desktop     | [a73982649a](https://linux-hardware.org/?probe=a73982649a) | Jul 22, 2021 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [09f145783b](https://linux-hardware.org/?probe=09f145783b) | Jul 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [0814f9bb87](https://linux-hardware.org/?probe=0814f9bb87) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | Notebook    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Dell          | Inspiron 15 5510            | Notebook    | [49660ef55a](https://linux-hardware.org/?probe=49660ef55a) | Jul 21, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [696645fa69](https://linux-hardware.org/?probe=696645fa69) | Jul 17, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [40d1ea391b](https://linux-hardware.org/?probe=40d1ea391b) | Jul 17, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [fc0d0dfa77](https://linux-hardware.org/?probe=fc0d0dfa77) | Jul 16, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [1c944ecf6b](https://linux-hardware.org/?probe=1c944ecf6b) | Jul 16, 2021 |
| Lenovo        | ThinkPad L390 20NR001EGE    | Notebook    | [b808df1ed1](https://linux-hardware.org/?probe=b808df1ed1) | Jul 16, 2021 |
| Dell          | G3 3579                     | Notebook    | [04e1e60c32](https://linux-hardware.org/?probe=04e1e60c32) | Jul 16, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [380f5c41bf](https://linux-hardware.org/?probe=380f5c41bf) | Jul 12, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [b0ed7c660f](https://linux-hardware.org/?probe=b0ed7c660f) | Jul 12, 2021 |
| Notebook      | P65_P67RGRERA               | Notebook    | [447e30ec88](https://linux-hardware.org/?probe=447e30ec88) | Jul 12, 2021 |
| Purism        | Librem 15 v3                | Notebook    | [1f97243626](https://linux-hardware.org/?probe=1f97243626) | Jul 11, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [72f5d673d9](https://linux-hardware.org/?probe=72f5d673d9) | Jul 11, 2021 |
| ASRock        | 760GM-HDV                   | Desktop     | [f58961af45](https://linux-hardware.org/?probe=f58961af45) | Jul 11, 2021 |
| Dell          | G3 3579                     | Notebook    | [d5f51334ef](https://linux-hardware.org/?probe=d5f51334ef) | Jul 09, 2021 |
| Dell          | G3 3579                     | Notebook    | [8a7d8d5919](https://linux-hardware.org/?probe=8a7d8d5919) | Jul 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [7e2f0e6a10](https://linux-hardware.org/?probe=7e2f0e6a10) | Jul 06, 2021 |
| Entroware     | Apollo                      | Notebook    | [e707e4f502](https://linux-hardware.org/?probe=e707e4f502) | Jul 06, 2021 |
| Dell          | Latitude 5320               | Notebook    | [460e8274ff](https://linux-hardware.org/?probe=460e8274ff) | Jul 05, 2021 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [abf5e04bd3](https://linux-hardware.org/?probe=abf5e04bd3) | Jul 05, 2021 |
| Dell          | Inspiron 7306 2n1           | Convertible | [f4d326f499](https://linux-hardware.org/?probe=f4d326f499) | Jul 05, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [d37ee6f754](https://linux-hardware.org/?probe=d37ee6f754) | Jul 04, 2021 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [2d6120fa61](https://linux-hardware.org/?probe=2d6120fa61) | Jul 04, 2021 |
| PC Special... | N550RN                      | Notebook    | [dc21c20be8](https://linux-hardware.org/?probe=dc21c20be8) | Jul 04, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [1039b9c2f5](https://linux-hardware.org/?probe=1039b9c2f5) | Jul 04, 2021 |
| MSI           | MPG B460I GAMING EDGE WI... | Desktop     | [1567387500](https://linux-hardware.org/?probe=1567387500) | Jul 04, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [c198cbd693](https://linux-hardware.org/?probe=c198cbd693) | Jul 02, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [d1fef5f2de](https://linux-hardware.org/?probe=d1fef5f2de) | Jul 02, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [f23be94d69](https://linux-hardware.org/?probe=f23be94d69) | Jul 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e42003e8ce](https://linux-hardware.org/?probe=e42003e8ce) | Jul 01, 2021 |
| HP            | 17E2                        | Mini pc     | [e53c1d5e09](https://linux-hardware.org/?probe=e53c1d5e09) | Jul 01, 2021 |
| Toshiba       | QOSMIO X70-A                | Notebook    | [e214ce4b74](https://linux-hardware.org/?probe=e214ce4b74) | Jun 30, 2021 |
| Biostar       | TA790GXB A2+                | Desktop     | [9fb8b9219e](https://linux-hardware.org/?probe=9fb8b9219e) | Jun 30, 2021 |
| Lenovo        | ThinkPad T470p 20J60042M... | Notebook    | [6ce76d671e](https://linux-hardware.org/?probe=6ce76d671e) | Jun 29, 2021 |
| ASRock        | N68-S3 UCC                  | Desktop     | [da689c7012](https://linux-hardware.org/?probe=da689c7012) | Jun 26, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [dfa95a4efd](https://linux-hardware.org/?probe=dfa95a4efd) | Jun 26, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a26c01da62](https://linux-hardware.org/?probe=a26c01da62) | Jun 26, 2021 |
| Dell          | Latitude 5580               | Notebook    | [da9c2daba5](https://linux-hardware.org/?probe=da9c2daba5) | Jun 26, 2021 |
| Dell          | Latitude 5580               | Notebook    | [0464095111](https://linux-hardware.org/?probe=0464095111) | Jun 25, 2021 |
| Fujitsu       | LIFEBOOK T901               | Notebook    | [fac68d6d96](https://linux-hardware.org/?probe=fac68d6d96) | Jun 23, 2021 |
| Dell          | Latitude 5501               | Notebook    | [93207f51d2](https://linux-hardware.org/?probe=93207f51d2) | Jun 22, 2021 |
| Dell          | Latitude 5501               | Notebook    | [40a42a978d](https://linux-hardware.org/?probe=40a42a978d) | Jun 22, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [fca4787959](https://linux-hardware.org/?probe=fca4787959) | Jun 22, 2021 |
| Intel         | X99                         | Desktop     | [436dda258b](https://linux-hardware.org/?probe=436dda258b) | Jun 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [98be9faa06](https://linux-hardware.org/?probe=98be9faa06) | Jun 21, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [ffd6111ce0](https://linux-hardware.org/?probe=ffd6111ce0) | Jun 21, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [5cdcacb2f2](https://linux-hardware.org/?probe=5cdcacb2f2) | Jun 20, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [6c9f9a3c6f](https://linux-hardware.org/?probe=6c9f9a3c6f) | Jun 20, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [270961254a](https://linux-hardware.org/?probe=270961254a) | Jun 20, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [441c0bb81f](https://linux-hardware.org/?probe=441c0bb81f) | Jun 19, 2021 |
| Dell          | 0X2MKR A00                  | All in one  | [41fa85048c](https://linux-hardware.org/?probe=41fa85048c) | Jun 19, 2021 |
| Dell          | 0X2MKR A00                  | All in one  | [0050574359](https://linux-hardware.org/?probe=0050574359) | Jun 18, 2021 |
| Apple         | MacBookPro14,1              | Notebook    | [a69ed7dfd9](https://linux-hardware.org/?probe=a69ed7dfd9) | Jun 18, 2021 |
| System76      | Kudu Professional           | Notebook    | [3efac330f0](https://linux-hardware.org/?probe=3efac330f0) | Jun 18, 2021 |
| Dell          | Latitude E6520              | Notebook    | [718e90b724](https://linux-hardware.org/?probe=718e90b724) | Jun 17, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [acd35c74b5](https://linux-hardware.org/?probe=acd35c74b5) | Jun 17, 2021 |
| HP            | ProBook 450 G7              | Notebook    | [dac3d6b5f5](https://linux-hardware.org/?probe=dac3d6b5f5) | Jun 17, 2021 |
| Acer          | Aspire E5-572G              | Notebook    | [073ee459eb](https://linux-hardware.org/?probe=073ee459eb) | Jun 16, 2021 |
| Intel         | H55                         | Desktop     | [c6c7036ebd](https://linux-hardware.org/?probe=c6c7036ebd) | Jun 16, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [3eb01e93e5](https://linux-hardware.org/?probe=3eb01e93e5) | Jun 16, 2021 |
| Intel         | ChiefRiver                  | Notebook    | [72aa2e75fc](https://linux-hardware.org/?probe=72aa2e75fc) | Jun 15, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [85c3988842](https://linux-hardware.org/?probe=85c3988842) | Jun 15, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [75e4118519](https://linux-hardware.org/?probe=75e4118519) | Jun 15, 2021 |
| Dell          | Latitude 5590               | Notebook    | [ddf8c05b96](https://linux-hardware.org/?probe=ddf8c05b96) | Jun 15, 2021 |
| Acer          | Extensa 2540                | Notebook    | [505cc98c20](https://linux-hardware.org/?probe=505cc98c20) | Jun 14, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [b90af008d3](https://linux-hardware.org/?probe=b90af008d3) | Jun 14, 2021 |
| HP            | 198E                        | Desktop     | [4d38d777c3](https://linux-hardware.org/?probe=4d38d777c3) | Jun 13, 2021 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [d99f5ee668](https://linux-hardware.org/?probe=d99f5ee668) | Jun 12, 2021 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [cfa0cf242c](https://linux-hardware.org/?probe=cfa0cf242c) | Jun 11, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [174ef2fee6](https://linux-hardware.org/?probe=174ef2fee6) | Jun 11, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [955f2768da](https://linux-hardware.org/?probe=955f2768da) | Jun 11, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [442ebaf444](https://linux-hardware.org/?probe=442ebaf444) | Jun 10, 2021 |
| HP            | 198E                        | Desktop     | [683e970f55](https://linux-hardware.org/?probe=683e970f55) | Jun 10, 2021 |
| Lenovo        | IdeaPad D330-10IGM 81H3     | Tablet      | [851f20cb74](https://linux-hardware.org/?probe=851f20cb74) | Jun 09, 2021 |
| HP            | EliteBook 850 G1            | Notebook    | [4c0ae26777](https://linux-hardware.org/?probe=4c0ae26777) | Jun 08, 2021 |
| Lenovo        | Tilapia CRB                 | Desktop     | [1b9acc3bdf](https://linux-hardware.org/?probe=1b9acc3bdf) | Jun 08, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [cfc0aceaf9](https://linux-hardware.org/?probe=cfc0aceaf9) | Jun 08, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [5e73374bbc](https://linux-hardware.org/?probe=5e73374bbc) | Jun 06, 2021 |
| ASRock        | Z390 Taichi Ultimate        | Desktop     | [fa126d0d5f](https://linux-hardware.org/?probe=fa126d0d5f) | Jun 05, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [dcae361982](https://linux-hardware.org/?probe=dcae361982) | Jun 05, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a580ef9f5c](https://linux-hardware.org/?probe=a580ef9f5c) | Jun 04, 2021 |
| HP            | 304Bh                       | Desktop     | [4f331fec6f](https://linux-hardware.org/?probe=4f331fec6f) | Jun 04, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [fe8cc5a05e](https://linux-hardware.org/?probe=fe8cc5a05e) | Jun 04, 2021 |
| Dell          | Latitude E6330              | Notebook    | [eaef8796a5](https://linux-hardware.org/?probe=eaef8796a5) | Jun 04, 2021 |
| HP            | 304Bh                       | Desktop     | [a41a097984](https://linux-hardware.org/?probe=a41a097984) | Jun 04, 2021 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [0d2cfdc2d8](https://linux-hardware.org/?probe=0d2cfdc2d8) | Jun 04, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c540bad35d](https://linux-hardware.org/?probe=c540bad35d) | Jun 03, 2021 |
| Dell          | Latitude E6330              | Notebook    | [4a51b670ac](https://linux-hardware.org/?probe=4a51b670ac) | Jun 03, 2021 |
| Dell          | Latitude E6410              | Notebook    | [dd2824f257](https://linux-hardware.org/?probe=dd2824f257) | Jun 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3a001e377](https://linux-hardware.org/?probe=d3a001e377) | Jun 01, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a4d00095a1](https://linux-hardware.org/?probe=a4d00095a1) | Jun 01, 2021 |
| Huanan        | X99-TF                      | Desktop     | [b92f4485e6](https://linux-hardware.org/?probe=b92f4485e6) | May 31, 2021 |
| HP            | ENVY TS 14 Sleekbook        | Notebook    | [f52091e51e](https://linux-hardware.org/?probe=f52091e51e) | May 31, 2021 |
| HP            | ENVY TS 15                  | Notebook    | [8369c42ce2](https://linux-hardware.org/?probe=8369c42ce2) | May 31, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d71af3d423](https://linux-hardware.org/?probe=d71af3d423) | May 31, 2021 |
| Cube          | SurfTab twin 11.6           | Convertible | [1866d29174](https://linux-hardware.org/?probe=1866d29174) | May 30, 2021 |
| Acer          | AO722                       | Notebook    | [8a6d18ebad](https://linux-hardware.org/?probe=8a6d18ebad) | May 30, 2021 |
| Acer          | AO722                       | Notebook    | [bc3de3323b](https://linux-hardware.org/?probe=bc3de3323b) | May 30, 2021 |
| Gigabyte      | Z270X-UD3-CF                | Desktop     | [834a7ae73b](https://linux-hardware.org/?probe=834a7ae73b) | May 30, 2021 |
| ASRock        | B550M Steel Legend          | Desktop     | [f39108e22f](https://linux-hardware.org/?probe=f39108e22f) | May 29, 2021 |
| MSI           | 970 GAMING                  | Desktop     | [d0fd1ce0e8](https://linux-hardware.org/?probe=d0fd1ce0e8) | May 28, 2021 |
| Unknown       | Unknown                     | Notebook    | [f36322ada4](https://linux-hardware.org/?probe=f36322ada4) | May 27, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [849be7da3e](https://linux-hardware.org/?probe=849be7da3e) | May 26, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [3ff174d668](https://linux-hardware.org/?probe=3ff174d668) | May 26, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [57ffe115ac](https://linux-hardware.org/?probe=57ffe115ac) | May 26, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [3de199f8f3](https://linux-hardware.org/?probe=3de199f8f3) | May 26, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [98f9559b42](https://linux-hardware.org/?probe=98f9559b42) | May 25, 2021 |
| Dell          | 0D28YY A01                  | Desktop     | [4bd51e385d](https://linux-hardware.org/?probe=4bd51e385d) | May 25, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [da566f34dd](https://linux-hardware.org/?probe=da566f34dd) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [e034d1b339](https://linux-hardware.org/?probe=e034d1b339) | May 23, 2021 |
| Intel         | NUC7i7BNB J31145-309        | Mini pc     | [1bc6e7aca3](https://linux-hardware.org/?probe=1bc6e7aca3) | May 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [de75ca92a2](https://linux-hardware.org/?probe=de75ca92a2) | May 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [292fe218cd](https://linux-hardware.org/?probe=292fe218cd) | May 23, 2021 |
| HP            | 158B                        | Desktop     | [e7d78d4e6c](https://linux-hardware.org/?probe=e7d78d4e6c) | May 21, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [fc4a208720](https://linux-hardware.org/?probe=fc4a208720) | May 20, 2021 |
| Samsung       | 530U3C/530U4C               | Notebook    | [a7aa09da10](https://linux-hardware.org/?probe=a7aa09da10) | May 20, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [bc4cdd85ce](https://linux-hardware.org/?probe=bc4cdd85ce) | May 20, 2021 |
| Sony          | VGN-FW510F                  | Notebook    | [1a9761824e](https://linux-hardware.org/?probe=1a9761824e) | May 20, 2021 |
| MSI           | H81M-E34                    | Desktop     | [ea9b132e77](https://linux-hardware.org/?probe=ea9b132e77) | May 19, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [54a21bec35](https://linux-hardware.org/?probe=54a21bec35) | May 19, 2021 |
| MSI           | Z170A GAMING M5             | Desktop     | [7493d31acb](https://linux-hardware.org/?probe=7493d31acb) | May 18, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [f12c26f48d](https://linux-hardware.org/?probe=f12c26f48d) | May 18, 2021 |
| HP            | 21B4 A01                    | Desktop     | [45752d3232](https://linux-hardware.org/?probe=45752d3232) | May 18, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [426ecdf62e](https://linux-hardware.org/?probe=426ecdf62e) | May 17, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [d01af38384](https://linux-hardware.org/?probe=d01af38384) | May 17, 2021 |
| Supermicro    | H8QG6                       | Server      | [d5563e325c](https://linux-hardware.org/?probe=d5563e325c) | May 17, 2021 |
| Intel         | DX79SI AAG28808-600         | Desktop     | [4d5e452411](https://linux-hardware.org/?probe=4d5e452411) | May 16, 2021 |
| Toshiba       | Satellite L850-1C9          | Notebook    | [1c040e75dd](https://linux-hardware.org/?probe=1c040e75dd) | May 16, 2021 |
| ASRock        | A320M-DGS                   | Desktop     | [e5a3726b96](https://linux-hardware.org/?probe=e5a3726b96) | May 16, 2021 |
| Foxconn       | 2ABF                        | Desktop     | [6e96a8df5f](https://linux-hardware.org/?probe=6e96a8df5f) | May 16, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [57b918a36e](https://linux-hardware.org/?probe=57b918a36e) | May 15, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [22b412f033](https://linux-hardware.org/?probe=22b412f033) | May 15, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [2c5c989a79](https://linux-hardware.org/?probe=2c5c989a79) | May 14, 2021 |
| Lenovo        | ThinkPad E550 20DF00CPFR    | Notebook    | [0afb5fd49d](https://linux-hardware.org/?probe=0afb5fd49d) | May 14, 2021 |
| Lenovo        | ThinkPad E550 20DF00CPFR    | Notebook    | [af28d9b401](https://linux-hardware.org/?probe=af28d9b401) | May 14, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [609b25a62b](https://linux-hardware.org/?probe=609b25a62b) | May 13, 2021 |
| Dell          | Latitude 5590               | Notebook    | [9b726ce28d](https://linux-hardware.org/?probe=9b726ce28d) | May 13, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [29ad7fb8e1](https://linux-hardware.org/?probe=29ad7fb8e1) | May 12, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [3fd70c5b87](https://linux-hardware.org/?probe=3fd70c5b87) | May 12, 2021 |
| HP            | Pavilion dm4                | Notebook    | [12873cce8e](https://linux-hardware.org/?probe=12873cce8e) | May 12, 2021 |
| Dell          | 088DT1 A01                  | Desktop     | [3a544adcc9](https://linux-hardware.org/?probe=3a544adcc9) | May 11, 2021 |
| ASUSTek       | GL752VW                     | Notebook    | [6ca916356b](https://linux-hardware.org/?probe=6ca916356b) | May 09, 2021 |
| ECS           | A320AM4-M3D/3.x/5.x         | Desktop     | [9ad8acccaa](https://linux-hardware.org/?probe=9ad8acccaa) | May 08, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [6300246c13](https://linux-hardware.org/?probe=6300246c13) | May 07, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [d4cf6a320b](https://linux-hardware.org/?probe=d4cf6a320b) | May 07, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [86167086f7](https://linux-hardware.org/?probe=86167086f7) | May 06, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [6367a7db0a](https://linux-hardware.org/?probe=6367a7db0a) | May 06, 2021 |
| Lenovo        | Yoga 510-15IKB 80VC         | Convertible | [a4d6f3cce4](https://linux-hardware.org/?probe=a4d6f3cce4) | May 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [0a82b79706](https://linux-hardware.org/?probe=0a82b79706) | May 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [4c91d3d2b0](https://linux-hardware.org/?probe=4c91d3d2b0) | May 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [735f58d176](https://linux-hardware.org/?probe=735f58d176) | May 04, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [1e8acae283](https://linux-hardware.org/?probe=1e8acae283) | May 01, 2021 |
| HP            | Pavilion 15                 | Notebook    | [882223f1be](https://linux-hardware.org/?probe=882223f1be) | May 01, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [7de0627698](https://linux-hardware.org/?probe=7de0627698) | May 01, 2021 |
| Dell          | Precision M4700             | Notebook    | [908638c5f1](https://linux-hardware.org/?probe=908638c5f1) | May 01, 2021 |
| Dell          | 0M858N A01                  | Desktop     | [5cf29d108d](https://linux-hardware.org/?probe=5cf29d108d) | Apr 29, 2021 |
| Dell          | 0M858N A01                  | Desktop     | [6db1d18e09](https://linux-hardware.org/?probe=6db1d18e09) | Apr 29, 2021 |
| Dell          | 0N13T1 A01                  | Desktop     | [7c02e11615](https://linux-hardware.org/?probe=7c02e11615) | Apr 28, 2021 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [0113cc8ad1](https://linux-hardware.org/?probe=0113cc8ad1) | Apr 26, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [48953fbb84](https://linux-hardware.org/?probe=48953fbb84) | Apr 26, 2021 |
| LG Electro... | A410-K.BE43P1               | Notebook    | [e909bbda9e](https://linux-hardware.org/?probe=e909bbda9e) | Apr 26, 2021 |
| ASUSTek       | X555YI                      | Notebook    | [66780ed1f3](https://linux-hardware.org/?probe=66780ed1f3) | Apr 25, 2021 |
| HP            | ENVY 17                     | Notebook    | [d1edd93e74](https://linux-hardware.org/?probe=d1edd93e74) | Apr 25, 2021 |
| Lenovo        | IdeaPad C340-14IWL 81RL     | Convertible | [00e650f868](https://linux-hardware.org/?probe=00e650f868) | Apr 25, 2021 |
| Gigabyte      | Z170X-Gaming 5              | Desktop     | [54a619054a](https://linux-hardware.org/?probe=54a619054a) | Apr 24, 2021 |
| Lenovo        | ThinkPad T440s 20ARS45U0... | Notebook    | [4316a83fc7](https://linux-hardware.org/?probe=4316a83fc7) | Apr 24, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [8ed2b2284e](https://linux-hardware.org/?probe=8ed2b2284e) | Apr 24, 2021 |
| ASUSTek       | K53E                        | Notebook    | [54fb711c08](https://linux-hardware.org/?probe=54fb711c08) | Apr 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS1G70A    | Notebook    | [101cc9e3ae](https://linux-hardware.org/?probe=101cc9e3ae) | Apr 23, 2021 |
| HP            | 1497                        | Desktop     | [cfa3220a15](https://linux-hardware.org/?probe=cfa3220a15) | Apr 23, 2021 |
| HP            | 1497                        | Desktop     | [6d68a38b71](https://linux-hardware.org/?probe=6d68a38b71) | Apr 23, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [092f84c945](https://linux-hardware.org/?probe=092f84c945) | Apr 23, 2021 |
| HP            | 3397                        | Desktop     | [cbbaaa3476](https://linux-hardware.org/?probe=cbbaaa3476) | Apr 23, 2021 |
| Gigabyte      | F2A88X-D3HP                 | Desktop     | [9f418e1758](https://linux-hardware.org/?probe=9f418e1758) | Apr 23, 2021 |
| Gigabyte      | F2A88X-D3HP                 | Desktop     | [f05632d235](https://linux-hardware.org/?probe=f05632d235) | Apr 23, 2021 |
| Alienware     | 17 R2                       | Notebook    | [494e22b607](https://linux-hardware.org/?probe=494e22b607) | Apr 22, 2021 |
| HP            | 21B4 A01                    | Desktop     | [399b0bbaf6](https://linux-hardware.org/?probe=399b0bbaf6) | Apr 22, 2021 |
| ASUSTek       | X401U                       | Notebook    | [c2a6402a22](https://linux-hardware.org/?probe=c2a6402a22) | Apr 22, 2021 |
| Dell          | Latitude 5590               | Notebook    | [ae217762e2](https://linux-hardware.org/?probe=ae217762e2) | Apr 21, 2021 |
| Unknown       | Unknown                     | Desktop     | [39a0744819](https://linux-hardware.org/?probe=39a0744819) | Apr 20, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [ddf7e5250e](https://linux-hardware.org/?probe=ddf7e5250e) | Apr 19, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [6558dfd5fd](https://linux-hardware.org/?probe=6558dfd5fd) | Apr 19, 2021 |
| Dell          | 0G7W4R A00                  | Desktop     | [477ba6a2a6](https://linux-hardware.org/?probe=477ba6a2a6) | Apr 19, 2021 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [5bf2da0f2e](https://linux-hardware.org/?probe=5bf2da0f2e) | Apr 19, 2021 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [9bb274bf17](https://linux-hardware.org/?probe=9bb274bf17) | Apr 19, 2021 |
| Acer          | Aspire A514-53              | Notebook    | [2a5c4baa8f](https://linux-hardware.org/?probe=2a5c4baa8f) | Apr 18, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [93f314efa4](https://linux-hardware.org/?probe=93f314efa4) | Apr 18, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [28c95d7c77](https://linux-hardware.org/?probe=28c95d7c77) | Apr 17, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1bd86cbcae](https://linux-hardware.org/?probe=1bd86cbcae) | Apr 17, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [f77abb46a7](https://linux-hardware.org/?probe=f77abb46a7) | Apr 16, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [1749421eaa](https://linux-hardware.org/?probe=1749421eaa) | Apr 16, 2021 |
| MSI           | B350 TOMAHAWK               | Desktop     | [382673d3f6](https://linux-hardware.org/?probe=382673d3f6) | Apr 15, 2021 |
| MSI           | GX60 3CC                    | Notebook    | [0725dd67d5](https://linux-hardware.org/?probe=0725dd67d5) | Apr 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [5ed47267b8](https://linux-hardware.org/?probe=5ed47267b8) | Apr 13, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [346db366ae](https://linux-hardware.org/?probe=346db366ae) | Apr 13, 2021 |
| HP            | 255 G1                      | Notebook    | [0244337bdd](https://linux-hardware.org/?probe=0244337bdd) | Apr 12, 2021 |
| HP            | 255 G1                      | Notebook    | [df0d528c9c](https://linux-hardware.org/?probe=df0d528c9c) | Apr 12, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [834cdeef2d](https://linux-hardware.org/?probe=834cdeef2d) | Apr 12, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [bf5944a98e](https://linux-hardware.org/?probe=bf5944a98e) | Apr 12, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [312edcd189](https://linux-hardware.org/?probe=312edcd189) | Apr 12, 2021 |
| HP            | ENVY 17                     | Notebook    | [d548035b69](https://linux-hardware.org/?probe=d548035b69) | Apr 11, 2021 |
| HP            | ENVY 17                     | Notebook    | [a4ee48d831](https://linux-hardware.org/?probe=a4ee48d831) | Apr 11, 2021 |
| Toshiba       | Satellite C850-BLK          | Notebook    | [9c4c8a260c](https://linux-hardware.org/?probe=9c4c8a260c) | Apr 11, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [850e9ad783](https://linux-hardware.org/?probe=850e9ad783) | Apr 10, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [9fec121fac](https://linux-hardware.org/?probe=9fec121fac) | Apr 10, 2021 |
| MSI           | PH67S-C43                   | Desktop     | [bf84a891cc](https://linux-hardware.org/?probe=bf84a891cc) | Apr 10, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [88c4aeb7cb](https://linux-hardware.org/?probe=88c4aeb7cb) | Apr 10, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [cc2dcd8258](https://linux-hardware.org/?probe=cc2dcd8258) | Apr 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c367f0f682](https://linux-hardware.org/?probe=c367f0f682) | Apr 10, 2021 |
| HP            | 15                          | Notebook    | [27bcfc6f15](https://linux-hardware.org/?probe=27bcfc6f15) | Apr 10, 2021 |
| HP            | 15                          | Notebook    | [aebfb75282](https://linux-hardware.org/?probe=aebfb75282) | Apr 10, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [59cb82d24c](https://linux-hardware.org/?probe=59cb82d24c) | Apr 09, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9a9c3c8d26](https://linux-hardware.org/?probe=9a9c3c8d26) | Apr 09, 2021 |
| Acer          | Aspire A515-54              | Notebook    | [a1f4d1a0e6](https://linux-hardware.org/?probe=a1f4d1a0e6) | Apr 09, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [97ea0f0897](https://linux-hardware.org/?probe=97ea0f0897) | Apr 08, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [035b6fca1d](https://linux-hardware.org/?probe=035b6fca1d) | Apr 08, 2021 |
| Lenovo        | ThinkPad T470 20HES18S03    | Notebook    | [8b6474986c](https://linux-hardware.org/?probe=8b6474986c) | Apr 08, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [60168d5b6d](https://linux-hardware.org/?probe=60168d5b6d) | Apr 07, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [37a29de2c0](https://linux-hardware.org/?probe=37a29de2c0) | Apr 07, 2021 |
| Hampoo        | Cherry Trail CR V200        | Notebook    | [fcbaa285ef](https://linux-hardware.org/?probe=fcbaa285ef) | Apr 07, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [8f3bd77b70](https://linux-hardware.org/?probe=8f3bd77b70) | Apr 06, 2021 |
| Lenovo        | ThinkPad T590 20N4CTO1WW    | Notebook    | [c55d72e928](https://linux-hardware.org/?probe=c55d72e928) | Apr 06, 2021 |
| HP            | 86F0 11000                  | All in one  | [5fd801909f](https://linux-hardware.org/?probe=5fd801909f) | Apr 05, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [b7ca2f4a18](https://linux-hardware.org/?probe=b7ca2f4a18) | Apr 04, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [bc92089206](https://linux-hardware.org/?probe=bc92089206) | Apr 04, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [0b31a00f14](https://linux-hardware.org/?probe=0b31a00f14) | Apr 04, 2021 |
| Unknown       | Unknown                     | Desktop     | [831b3f8c68](https://linux-hardware.org/?probe=831b3f8c68) | Apr 04, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2ca16685f0](https://linux-hardware.org/?probe=2ca16685f0) | Apr 03, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [0eaf54f4f5](https://linux-hardware.org/?probe=0eaf54f4f5) | Apr 03, 2021 |
| ASUSTek       | M4N68T-M LE                 | Desktop     | [819d6e7ad3](https://linux-hardware.org/?probe=819d6e7ad3) | Apr 03, 2021 |
| Dell          | 0M5DCD A00                  | Desktop     | [51543dbb4d](https://linux-hardware.org/?probe=51543dbb4d) | Apr 03, 2021 |
| ASUSTek       | H110M-C                     | Desktop     | [5809742ae4](https://linux-hardware.org/?probe=5809742ae4) | Apr 02, 2021 |
| ASRock        | Z270 Gaming-ITX/ac          | Desktop     | [c4b61cff94](https://linux-hardware.org/?probe=c4b61cff94) | Apr 02, 2021 |
| Dell          | Studio 1747                 | Notebook    | [31c1b6a828](https://linux-hardware.org/?probe=31c1b6a828) | Apr 01, 2021 |
| Dell          | XPS 15 9570                 | Notebook    | [f74fdee693](https://linux-hardware.org/?probe=f74fdee693) | Apr 01, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [4080e1b43f](https://linux-hardware.org/?probe=4080e1b43f) | Apr 01, 2021 |
| HP            | 8299                        | Desktop     | [12120a16f6](https://linux-hardware.org/?probe=12120a16f6) | Mar 30, 2021 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [d4f182e3de](https://linux-hardware.org/?probe=d4f182e3de) | Mar 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [07ad242a41](https://linux-hardware.org/?probe=07ad242a41) | Mar 30, 2021 |
| Dell          | Precision 5550              | Notebook    | [76fb436ef0](https://linux-hardware.org/?probe=76fb436ef0) | Mar 29, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [4caff5f0c4](https://linux-hardware.org/?probe=4caff5f0c4) | Mar 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [26427e6d23](https://linux-hardware.org/?probe=26427e6d23) | Mar 29, 2021 |
| HP            | Pavilion g6                 | Notebook    | [4bbe96d0c3](https://linux-hardware.org/?probe=4bbe96d0c3) | Mar 29, 2021 |
| HP            | Pavilion g6                 | Notebook    | [509c863d2e](https://linux-hardware.org/?probe=509c863d2e) | Mar 29, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [262c2c82c1](https://linux-hardware.org/?probe=262c2c82c1) | Mar 29, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [4d05114173](https://linux-hardware.org/?probe=4d05114173) | Mar 28, 2021 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [9e88c8329e](https://linux-hardware.org/?probe=9e88c8329e) | Mar 28, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | Notebook    | [39d2fcc25c](https://linux-hardware.org/?probe=39d2fcc25c) | Mar 28, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [8253b82c52](https://linux-hardware.org/?probe=8253b82c52) | Mar 28, 2021 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [c849cdad45](https://linux-hardware.org/?probe=c849cdad45) | Mar 27, 2021 |
| Dell          | Latitude E4310              | Notebook    | [9e4e10b6ac](https://linux-hardware.org/?probe=9e4e10b6ac) | Mar 25, 2021 |
| Notebook      | W65_67SF                    | Notebook    | [18494a4239](https://linux-hardware.org/?probe=18494a4239) | Mar 25, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [bb2ba9b142](https://linux-hardware.org/?probe=bb2ba9b142) | Mar 24, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [973d60c63e](https://linux-hardware.org/?probe=973d60c63e) | Mar 24, 2021 |
| Acer          | FIH57                       | Desktop     | [ddb03d82a0](https://linux-hardware.org/?probe=ddb03d82a0) | Mar 24, 2021 |
| Acer          | Aspire A515-44G             | Notebook    | [cee95b2125](https://linux-hardware.org/?probe=cee95b2125) | Mar 23, 2021 |
| MSI           | B365M PRO-VDH               | Desktop     | [85eae8241f](https://linux-hardware.org/?probe=85eae8241f) | Mar 22, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [b139612360](https://linux-hardware.org/?probe=b139612360) | Mar 21, 2021 |
| Positivo      | C14CR01                     | Notebook    | [80a20c54ab](https://linux-hardware.org/?probe=80a20c54ab) | Mar 21, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6270efa573](https://linux-hardware.org/?probe=6270efa573) | Mar 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [af1f2a3c0d](https://linux-hardware.org/?probe=af1f2a3c0d) | Mar 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e2f4d3b86f](https://linux-hardware.org/?probe=e2f4d3b86f) | Mar 20, 2021 |
| Seco          | C40 C                       | Desktop     | [70a92f2d8a](https://linux-hardware.org/?probe=70a92f2d8a) | Mar 19, 2021 |
| Gigabyte      | Z170X-UD5-CF                | Desktop     | [edac373896](https://linux-hardware.org/?probe=edac373896) | Mar 19, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [4c78db6d10](https://linux-hardware.org/?probe=4c78db6d10) | Mar 18, 2021 |
| ASUSTek       | Maximus IV Extreme          | Desktop     | [42afab4523](https://linux-hardware.org/?probe=42afab4523) | Mar 18, 2021 |
| ASRock        | H67DE3                      | Desktop     | [14e5916050](https://linux-hardware.org/?probe=14e5916050) | Mar 18, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [b39a7d0921](https://linux-hardware.org/?probe=b39a7d0921) | Mar 17, 2021 |
| Gigabyte      | Z87-HD3                     | Desktop     | [ff76102e23](https://linux-hardware.org/?probe=ff76102e23) | Mar 17, 2021 |
| Dell          | Latitude 5501               | Notebook    | [ec0cbf54dd](https://linux-hardware.org/?probe=ec0cbf54dd) | Mar 17, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4d8d7a3551](https://linux-hardware.org/?probe=4d8d7a3551) | Mar 17, 2021 |
| HP            | ProBook 4730s               | Notebook    | [5809a45a9a](https://linux-hardware.org/?probe=5809a45a9a) | Mar 17, 2021 |
| ASUSTek       | N551JM                      | Notebook    | [7faf90e652](https://linux-hardware.org/?probe=7faf90e652) | Mar 17, 2021 |
| ASRock        | G41C-VS                     | Desktop     | [6ef4d0ea12](https://linux-hardware.org/?probe=6ef4d0ea12) | Mar 16, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [ac92ab9404](https://linux-hardware.org/?probe=ac92ab9404) | Mar 15, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [402cbaf164](https://linux-hardware.org/?probe=402cbaf164) | Mar 15, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [fe4bf0f1bb](https://linux-hardware.org/?probe=fe4bf0f1bb) | Mar 15, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [3bf2664982](https://linux-hardware.org/?probe=3bf2664982) | Mar 14, 2021 |
| MSI           | MPG Z490M GAMING EDGE WI... | Desktop     | [b8d7e8ae57](https://linux-hardware.org/?probe=b8d7e8ae57) | Mar 14, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [50735eb518](https://linux-hardware.org/?probe=50735eb518) | Mar 13, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [08501b7f5a](https://linux-hardware.org/?probe=08501b7f5a) | Mar 13, 2021 |
| Lenovo        | ThinkPad T440 20B7S2SM00    | Notebook    | [f784781973](https://linux-hardware.org/?probe=f784781973) | Mar 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [640a0a3857](https://linux-hardware.org/?probe=640a0a3857) | Mar 13, 2021 |
| Dell          | 0KRC95 A02                  | Desktop     | [ced325be18](https://linux-hardware.org/?probe=ced325be18) | Mar 12, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [8e8f1a2dee](https://linux-hardware.org/?probe=8e8f1a2dee) | Mar 12, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [8027a5eab2](https://linux-hardware.org/?probe=8027a5eab2) | Mar 12, 2021 |
| MSI           | Modern 15 A10M              | Notebook    | [d0b9267af6](https://linux-hardware.org/?probe=d0b9267af6) | Mar 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [66de852009](https://linux-hardware.org/?probe=66de852009) | Mar 11, 2021 |
| Dell          | Latitude 5590               | Notebook    | [d2b562137b](https://linux-hardware.org/?probe=d2b562137b) | Mar 11, 2021 |
| Notebook      | W54_55_94_95_97AU,AUQ       | Notebook    | [1a4c02ee0c](https://linux-hardware.org/?probe=1a4c02ee0c) | Mar 08, 2021 |
| HP            | Stream Notebook PC 14       | Notebook    | [72a34a3dd4](https://linux-hardware.org/?probe=72a34a3dd4) | Mar 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ad1380deaa](https://linux-hardware.org/?probe=ad1380deaa) | Mar 05, 2021 |
| Samsung       | 370E4K                      | Notebook    | [5f1f92fd09](https://linux-hardware.org/?probe=5f1f92fd09) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| Dell          | XPS M1530                   | Notebook    | [9f9d1a39f5](https://linux-hardware.org/?probe=9f9d1a39f5) | Mar 03, 2021 |
| Gigabyte      | GA-970-Gaming SLI-CF        | Desktop     | [e3f7effc1c](https://linux-hardware.org/?probe=e3f7effc1c) | Mar 03, 2021 |
| Acer          | Aspire X3400                | Desktop     | [37dca6b989](https://linux-hardware.org/?probe=37dca6b989) | Mar 03, 2021 |
| HP            | 8299                        | Desktop     | [e8e31dfc6e](https://linux-hardware.org/?probe=e8e31dfc6e) | Mar 01, 2021 |
| HP            | Pavilion 15                 | Notebook    | [7899110cfa](https://linux-hardware.org/?probe=7899110cfa) | Mar 01, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [94f5daf626](https://linux-hardware.org/?probe=94f5daf626) | Feb 28, 2021 |
| HP            | 15                          | Notebook    | [3d3d11173c](https://linux-hardware.org/?probe=3d3d11173c) | Feb 27, 2021 |
| Dell          | 0XPDFK A01                  | Desktop     | [88dfa8bfe4](https://linux-hardware.org/?probe=88dfa8bfe4) | Feb 27, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0560c0ea42](https://linux-hardware.org/?probe=0560c0ea42) | Feb 27, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [12ac027d4a](https://linux-hardware.org/?probe=12ac027d4a) | Feb 26, 2021 |
| Dell          | G5 5500                     | Notebook    | [786bdf5cec](https://linux-hardware.org/?probe=786bdf5cec) | Feb 25, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | Notebook    | [7c9fd9dde4](https://linux-hardware.org/?probe=7c9fd9dde4) | Feb 24, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [08723d28a4](https://linux-hardware.org/?probe=08723d28a4) | Feb 24, 2021 |
| Dell          | Latitude E6430s             | Notebook    | [cb9032f7b7](https://linux-hardware.org/?probe=cb9032f7b7) | Feb 24, 2021 |
| HP            | EliteBook 2570p             | Notebook    | [f3e1294a65](https://linux-hardware.org/?probe=f3e1294a65) | Feb 23, 2021 |
| Sony          | VGN-TZ150N                  | Notebook    | [213e5e739e](https://linux-hardware.org/?probe=213e5e739e) | Feb 22, 2021 |
| HP            | 1589                        | Desktop     | [8784e0d9ad](https://linux-hardware.org/?probe=8784e0d9ad) | Feb 22, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [9493316900](https://linux-hardware.org/?probe=9493316900) | Feb 22, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e6bcb06746](https://linux-hardware.org/?probe=e6bcb06746) | Feb 20, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [80bebb61bc](https://linux-hardware.org/?probe=80bebb61bc) | Feb 20, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [25a2434de6](https://linux-hardware.org/?probe=25a2434de6) | Feb 19, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [cc6c16c095](https://linux-hardware.org/?probe=cc6c16c095) | Feb 19, 2021 |
| Gigabyte      | EP45-UD3P                   | Desktop     | [2caf18393e](https://linux-hardware.org/?probe=2caf18393e) | Feb 18, 2021 |
| Gigabyte      | F2A88X-D3H                  | Desktop     | [ea95229d12](https://linux-hardware.org/?probe=ea95229d12) | Feb 18, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [acdf8601fd](https://linux-hardware.org/?probe=acdf8601fd) | Feb 18, 2021 |
| MSI           | X470 GAMING PLUS            | Desktop     | [51e50d143a](https://linux-hardware.org/?probe=51e50d143a) | Feb 18, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [4275f330af](https://linux-hardware.org/?probe=4275f330af) | Feb 18, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Notebook      | W65_67SJ                    | Notebook    | [27f2a581af](https://linux-hardware.org/?probe=27f2a581af) | Feb 17, 2021 |
| Notebook      | W65_67SJ                    | Notebook    | [d9841ed6c0](https://linux-hardware.org/?probe=d9841ed6c0) | Feb 17, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [65b32aa4a5](https://linux-hardware.org/?probe=65b32aa4a5) | Feb 16, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [fb6179a8ee](https://linux-hardware.org/?probe=fb6179a8ee) | Feb 16, 2021 |
| Dell          | 0HN7XN A01                  | Desktop     | [848bce680c](https://linux-hardware.org/?probe=848bce680c) | Feb 15, 2021 |
| JINGSHA       | Unknown                     | Desktop     | [8f0c5a3c20](https://linux-hardware.org/?probe=8f0c5a3c20) | Feb 14, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [22f56fdeda](https://linux-hardware.org/?probe=22f56fdeda) | Feb 14, 2021 |
| Lenovo        | ThinkCentre M90p 5498PK8    | Desktop     | [df39a8847b](https://linux-hardware.org/?probe=df39a8847b) | Feb 14, 2021 |
| Acer          | Aspire 5732Z                | Notebook    | [7ad83acc43](https://linux-hardware.org/?probe=7ad83acc43) | Feb 13, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [99b31bd894](https://linux-hardware.org/?probe=99b31bd894) | Feb 13, 2021 |
| MSI           | B85M-E45                    | Desktop     | [16c99d1061](https://linux-hardware.org/?probe=16c99d1061) | Feb 13, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [0b9e39df3d](https://linux-hardware.org/?probe=0b9e39df3d) | Feb 12, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [13d6b7a012](https://linux-hardware.org/?probe=13d6b7a012) | Feb 12, 2021 |
| ASRock        | X570 Extreme4               | Desktop     | [3f2929b8fd](https://linux-hardware.org/?probe=3f2929b8fd) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d993271043](https://linux-hardware.org/?probe=d993271043) | Feb 11, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ab8c311c17](https://linux-hardware.org/?probe=ab8c311c17) | Feb 11, 2021 |
| Dell          | Precision M4700             | Notebook    | [fb357e9f90](https://linux-hardware.org/?probe=fb357e9f90) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [4f0639f7c9](https://linux-hardware.org/?probe=4f0639f7c9) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | Notebook    | [e3d953f88d](https://linux-hardware.org/?probe=e3d953f88d) | Feb 10, 2021 |
| MSI           | GE66 Raider 10SF            | Notebook    | [a9bc0b88b6](https://linux-hardware.org/?probe=a9bc0b88b6) | Feb 10, 2021 |
| Dell          | 0F896N A03                  | Desktop     | [2dd5786964](https://linux-hardware.org/?probe=2dd5786964) | Feb 10, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [6679a796a7](https://linux-hardware.org/?probe=6679a796a7) | Feb 09, 2021 |
| Dell          | Precision M4700             | Notebook    | [f674f91052](https://linux-hardware.org/?probe=f674f91052) | Feb 08, 2021 |
| AZW           | Gemini M                    | Desktop     | [a610efb6d7](https://linux-hardware.org/?probe=a610efb6d7) | Feb 08, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [dd9e4c1dde](https://linux-hardware.org/?probe=dd9e4c1dde) | Feb 07, 2021 |
| Dell          | Inspiron 17-7779            | Notebook    | [f579f7a11c](https://linux-hardware.org/?probe=f579f7a11c) | Feb 06, 2021 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [1835552ae4](https://linux-hardware.org/?probe=1835552ae4) | Feb 06, 2021 |
| HP            | 2000                        | Notebook    | [cd28e0c1a6](https://linux-hardware.org/?probe=cd28e0c1a6) | Feb 06, 2021 |
| Intel         | D33217GKE G76540-205        | Desktop     | [acd358e227](https://linux-hardware.org/?probe=acd358e227) | Feb 06, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [c40d5bfeff](https://linux-hardware.org/?probe=c40d5bfeff) | Feb 05, 2021 |
| Dell          | Inspiron 17-7779            | Notebook    | [e146e67342](https://linux-hardware.org/?probe=e146e67342) | Feb 05, 2021 |
| ASRock        | A300M-STX                   | Desktop     | [ceda1f734f](https://linux-hardware.org/?probe=ceda1f734f) | Feb 04, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [42eea1df17](https://linux-hardware.org/?probe=42eea1df17) | Feb 04, 2021 |
| Gigabyte      | GA-790XT-USB3               | Desktop     | [d14e71b6b4](https://linux-hardware.org/?probe=d14e71b6b4) | Feb 03, 2021 |
| Dell          | Latitude 5480               | Notebook    | [d4927a9f76](https://linux-hardware.org/?probe=d4927a9f76) | Feb 02, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [d88bfb96f9](https://linux-hardware.org/?probe=d88bfb96f9) | Feb 01, 2021 |
| MSI           | Z170A SLI PLUS              | Desktop     | [2e49a21374](https://linux-hardware.org/?probe=2e49a21374) | Feb 01, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1292b81dfa](https://linux-hardware.org/?probe=1292b81dfa) | Feb 01, 2021 |
| HP            | 8299                        | Desktop     | [16e50ec1cd](https://linux-hardware.org/?probe=16e50ec1cd) | Jan 31, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [d0cfe35dee](https://linux-hardware.org/?probe=d0cfe35dee) | Jan 31, 2021 |
| ASRock        | Z170 Extreme7+              | Desktop     | [8f8b3ad8e1](https://linux-hardware.org/?probe=8f8b3ad8e1) | Jan 31, 2021 |
| ASUSTek       | N56JN                       | Notebook    | [02008fdd48](https://linux-hardware.org/?probe=02008fdd48) | Jan 31, 2021 |
| ASRock        | E350M1/USB3                 | Desktop     | [fc0abf0e10](https://linux-hardware.org/?probe=fc0abf0e10) | Jan 30, 2021 |
| Dell          | Latitude E7240              | Notebook    | [27236969c7](https://linux-hardware.org/?probe=27236969c7) | Jan 29, 2021 |
| ASUSTek       | UX331UA                     | Notebook    | [6360711ded](https://linux-hardware.org/?probe=6360711ded) | Jan 28, 2021 |
| HP            | 250 G3                      | Notebook    | [19a1d2d008](https://linux-hardware.org/?probe=19a1d2d008) | Jan 28, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [77c2137bbd](https://linux-hardware.org/?probe=77c2137bbd) | Jan 28, 2021 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [81b93f4513](https://linux-hardware.org/?probe=81b93f4513) | Jan 27, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [eac34165b9](https://linux-hardware.org/?probe=eac34165b9) | Jan 27, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [f8f1db15da](https://linux-hardware.org/?probe=f8f1db15da) | Jan 26, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8c7c26863a](https://linux-hardware.org/?probe=8c7c26863a) | Jan 26, 2021 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [1a3802ce22](https://linux-hardware.org/?probe=1a3802ce22) | Jan 26, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [e576c1b644](https://linux-hardware.org/?probe=e576c1b644) | Jan 26, 2021 |
| Intel         | HuronRiver Platform         | Notebook    | [1ace53e871](https://linux-hardware.org/?probe=1ace53e871) | Jan 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [4cacca5cdf](https://linux-hardware.org/?probe=4cacca5cdf) | Jan 25, 2021 |
| Sony          | SVE1711V1RB                 | Notebook    | [47cc12535d](https://linux-hardware.org/?probe=47cc12535d) | Jan 24, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [f44186ef76](https://linux-hardware.org/?probe=f44186ef76) | Jan 24, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_20.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 89        | 5.73%   |
| 5.4.0-52-generic  | 59        | 3.8%    |
| 5.4.0-48-generic  | 56        | 3.61%   |
| 5.4.0-58-generic  | 54        | 3.48%   |
| 5.4.0-40-generic  | 47        | 3.03%   |
| 5.4.0-47-generic  | 35        | 2.26%   |
| 5.4.0-37-generic  | 33        | 2.13%   |
| 5.4.0-29-generic  | 33        | 2.13%   |
| 5.4.0-65-generic  | 31        | 2%      |
| 5.4.0-45-generic  | 30        | 1.93%   |
| 5.4.0-54-generic  | 25        | 1.61%   |
| 5.4.0-26-generic  | 25        | 1.61%   |
| 5.13.0-39-generic | 25        | 1.61%   |
| 5.13.0-28-generic | 23        | 1.48%   |
| 5.8.0-48-generic  | 22        | 1.42%   |
| 5.4.0-56-generic  | 22        | 1.42%   |
| 5.4.0-33-generic  | 22        | 1.42%   |
| 5.11.0-37-generic | 22        | 1.42%   |
| 5.11.0-27-generic | 22        | 1.42%   |
| 5.4.0-31-generic  | 21        | 1.35%   |
| 5.8.0-50-generic  | 20        | 1.29%   |
| 5.13.0-30-generic | 18        | 1.16%   |
| 5.8.0-55-generic  | 17        | 1.1%    |
| 5.4.0-73-generic  | 17        | 1.1%    |
| 5.4.0-66-generic  | 17        | 1.1%    |
| 5.8.0-43-generic  | 16        | 1.03%   |
| 5.8.0-63-generic  | 15        | 0.97%   |
| 5.8.0-59-generic  | 14        | 0.9%    |
| 5.8.0-53-generic  | 14        | 0.9%    |
| 5.4.0-74-generic  | 14        | 0.9%    |
| 5.4.0-70-generic  | 14        | 0.9%    |
| 5.4.0-39-generic  | 14        | 0.9%    |
| 5.11.0-43-generic | 14        | 0.9%    |
| 5.11.0-38-generic | 14        | 0.9%    |
| 5.4.0-91-generic  | 13        | 0.84%   |
| 5.4.0-81-generic  | 13        | 0.84%   |
| 5.8.0-45-generic  | 12        | 0.77%   |
| 5.4.0-72-generic  | 12        | 0.77%   |
| 5.4.0-59-generic  | 12        | 0.77%   |
| 5.4.0-53-generic  | 12        | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 855       | 60.21%  |
| 5.8.0   | 168       | 11.83%  |
| 5.11.0  | 127       | 8.94%   |
| 5.13.0  | 114       | 8.03%   |
| 5.15.0  | 46        | 3.24%   |
| 5.6.0   | 14        | 0.99%   |
| 5.10.0  | 10        | 0.7%    |
| 5.3.0   | 5         | 0.35%   |
| 5.7.0   | 4         | 0.28%   |
| 5.14.0  | 4         | 0.28%   |
| 5.9.0   | 3         | 0.21%   |
| 5.9.10  | 2         | 0.14%   |
| 5.8.2   | 2         | 0.14%   |
| 5.8.18  | 2         | 0.14%   |
| 5.8.12  | 2         | 0.14%   |
| 5.7.10  | 2         | 0.14%   |
| 5.7.1   | 2         | 0.14%   |
| 5.17.0  | 2         | 0.14%   |
| 5.12.6  | 2         | 0.14%   |
| 5.11.15 | 2         | 0.14%   |
| 5.11.12 | 2         | 0.14%   |
| 5.9.6   | 1         | 0.07%   |
| 5.9.16  | 1         | 0.07%   |
| 5.9.1   | 1         | 0.07%   |
| 5.8.5   | 1         | 0.07%   |
| 5.8.14  | 1         | 0.07%   |
| 5.8.13  | 1         | 0.07%   |
| 5.8.11  | 1         | 0.07%   |
| 5.8.1   | 1         | 0.07%   |
| 5.7.6   | 1         | 0.07%   |
| 5.7.19  | 1         | 0.07%   |
| 5.7.15  | 1         | 0.07%   |
| 5.6.7   | 1         | 0.07%   |
| 5.6.17  | 1         | 0.07%   |
| 5.6.15  | 1         | 0.07%   |
| 5.6.11  | 1         | 0.07%   |
| 5.5.0   | 1         | 0.07%   |
| 5.4.78  | 1         | 0.07%   |
| 5.4.72  | 1         | 0.07%   |
| 5.4.63  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 859       | 60.58%  |
| 5.8     | 179       | 12.62%  |
| 5.11    | 133       | 9.38%   |
| 5.13    | 117       | 8.25%   |
| 5.15    | 50        | 3.53%   |
| 5.6     | 18        | 1.27%   |
| 5.10    | 16        | 1.13%   |
| 5.7     | 11        | 0.78%   |
| 5.9     | 8         | 0.56%   |
| 5.14    | 7         | 0.49%   |
| 5.3     | 5         | 0.35%   |
| 5.12    | 5         | 0.35%   |
| 5.17    | 3         | 0.21%   |
| 5.18    | 2         | 0.14%   |
| 5.16    | 2         | 0.14%   |
| 5.5     | 1         | 0.07%   |
| 5.19    | 1         | 0.07%   |
| 5.0     | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1379      | 99.93%  |
| aarch64 | 1         | 0.07%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| KDE5     | 900       | 64.19%  |
| KDE      | 477       | 34.02%  |
| GNOME    | 8         | 0.57%   |
| Cinnamon | 7         | 0.5%    |
| Budgie   | 6         | 0.43%   |
| XFCE     | 2         | 0.14%   |
| MATE     | 1         | 0.07%   |
| LXQt     | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1339      | 96.82%  |
| Wayland | 22        | 1.59%   |
| Tty     | 22        | 1.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 807       | 57.6%   |
| Unknown | 483       | 34.48%  |
| GDM     | 76        | 5.42%   |
| LightDM | 15        | 1.07%   |
| GDM3    | 10        | 0.71%   |
| TDM     | 9         | 0.64%   |
| SLiM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 589       | 42.47%  |
| de_DE   | 100       | 7.21%   |
| ru_RU   | 86        | 6.2%    |
| pt_BR   | 80        | 5.77%   |
| en_GB   | 67        | 4.83%   |
| fr_FR   | 64        | 4.61%   |
| it_IT   | 53        | 3.82%   |
| es_ES   | 31        | 2.24%   |
| en_CA   | 28        | 2.02%   |
| pl_PL   | 26        | 1.87%   |
| en_IN   | 23        | 1.66%   |
| en_AU   | 19        | 1.37%   |
| ru_UA   | 11        | 0.79%   |
| hu_HU   | 11        | 0.79%   |
| es_MX   | 11        | 0.79%   |
| cs_CZ   | 11        | 0.79%   |
| es_AR   | 10        | 0.72%   |
| nl_NL   | 9         | 0.65%   |
| en_ZA   | 9         | 0.65%   |
| el_GR   | 8         | 0.58%   |
| es_CO   | 7         | 0.5%    |
| en_NZ   | 7         | 0.5%    |
| C       | 7         | 0.5%    |
| es_VE   | 6         | 0.43%   |
| zh_CN   | 5         | 0.36%   |
| tr_TR   | 5         | 0.36%   |
| sv_SE   | 5         | 0.36%   |
| nl_BE   | 5         | 0.36%   |
| en_IL   | 5         | 0.36%   |
| de_CH   | 5         | 0.36%   |
| Unknown | 5         | 0.36%   |
| uk_UA   | 4         | 0.29%   |
| pt_PT   | 4         | 0.29%   |
| ja_JP   | 4         | 0.29%   |
| es_PE   | 4         | 0.29%   |
| es_CL   | 4         | 0.29%   |
| de_AT   | 4         | 0.29%   |
| zh_TW   | 3         | 0.22%   |
| ro_RO   | 3         | 0.22%   |
| fr_CH   | 3         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 863       | 61.91%  |
| BIOS | 531       | 38.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1264      | 91.26%  |
| Btrfs   | 63        | 4.55%   |
| Overlay | 22        | 1.59%   |
| Xfs     | 21        | 1.52%   |
| Zfs     | 8         | 0.58%   |
| Ext2    | 3         | 0.22%   |
| Ext3    | 2         | 0.14%   |
| XXXX    | 1         | 0.07%   |
| Jfs     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 644       | 46.13%  |
| Unknown | 557       | 39.9%   |
| MBR     | 195       | 13.97%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1183      | 84.99%  |
| Yes       | 209       | 15.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 808       | 58.26%  |
| Yes       | 579       | 41.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell                   | 235       | 17.03%  |
| ASUSTek Computer       | 215       | 15.58%  |
| Hewlett-Packard        | 189       | 13.7%   |
| Lenovo                 | 181       | 13.12%  |
| Gigabyte Technology    | 124       | 8.99%   |
| MSI                    | 101       | 7.32%   |
| ASRock                 | 61        | 4.42%   |
| Acer                   | 49        | 3.55%   |
| Samsung Electronics    | 22        | 1.59%   |
| Intel                  | 20        | 1.45%   |
| HUAWEI                 | 10        | 0.72%   |
| Apple                  | 10        | 0.72%   |
| TUXEDO                 | 9         | 0.65%   |
| Sony                   | 9         | 0.65%   |
| Unknown                | 9         | 0.65%   |
| Notebook               | 8         | 0.58%   |
| Pegatron               | 7         | 0.51%   |
| Fujitsu                | 7         | 0.51%   |
| ZOTAC                  | 6         | 0.43%   |
| Toshiba                | 6         | 0.43%   |
| Positivo               | 6         | 0.43%   |
| PC Specialist          | 5         | 0.36%   |
| Packard Bell           | 5         | 0.36%   |
| Medion                 | 5         | 0.36%   |
| Google                 | 5         | 0.36%   |
| Foxconn                | 5         | 0.36%   |
| Biostar                | 5         | 0.36%   |
| Alienware              | 5         | 0.36%   |
| Timi                   | 4         | 0.29%   |
| LG Electronics         | 4         | 0.29%   |
| Huanan                 | 4         | 0.29%   |
| ECS                    | 4         | 0.29%   |
| Chuwi                  | 4         | 0.29%   |
| System76               | 3         | 0.22%   |
| Avell High Performance | 3         | 0.22%   |
| Supermicro             | 2         | 0.14%   |
| Schenker               | 2         | 0.14%   |
| Gateway                | 2         | 0.14%   |
| BANGHO                 | 2         | 0.14%   |
| WeiBu                  | 1         | 0.07%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                   | Computers | Percent |
|----------------------------------------|-----------|---------|
| ASUS All Series                        | 16        | 1.16%   |
| Unknown                                | 16        | 1.16%   |
| Gigabyte 970A-DS3P                     | 6         | 0.43%   |
| HP Pavilion g6                         | 5         | 0.36%   |
| Gigabyte A320M-S2H                     | 5         | 0.36%   |
| Dell XPS 15 9560                       | 5         | 0.36%   |
| MSI MS-7A34                            | 4         | 0.29%   |
| MSI MS-7817                            | 4         | 0.29%   |
| HP Notebook                            | 4         | 0.29%   |
| HP 15                                  | 4         | 0.29%   |
| Gigabyte B450M DS3H                    | 4         | 0.29%   |
| Dell XPS 15 9570                       | 4         | 0.29%   |
| Dell XPS 15 9500                       | 4         | 0.29%   |
| Dell OptiPlex 9020                     | 4         | 0.29%   |
| Dell Latitude 5580                     | 4         | 0.29%   |
| Dell Inspiron 7559                     | 4         | 0.29%   |
| ASUS PRIME B450M-A                     | 4         | 0.29%   |
| ZOTAC ZBOX-CI620/CI640/CI660           | 3         | 0.22%   |
| MSI MS-7C91                            | 3         | 0.22%   |
| MSI MS-7C52                            | 3         | 0.22%   |
| MSI MS-7C37                            | 3         | 0.22%   |
| MSI MS-7996                            | 3         | 0.22%   |
| Lenovo G50-70 20351                    | 3         | 0.22%   |
| HP ProBook 450 G7                      | 3         | 0.22%   |
| HP ProBook 450 G3                      | 3         | 0.22%   |
| HP Pavilion x360 Convertible 14-dh0xxx | 3         | 0.22%   |
| HP Pavilion Gaming Laptop 15-cx0xxx    | 3         | 0.22%   |
| HP Pavilion dv6                        | 3         | 0.22%   |
| HP Laptop 17-ca0xxx                    | 3         | 0.22%   |
| HP EliteBook 840 G5                    | 3         | 0.22%   |
| HP EliteBook 840 G3                    | 3         | 0.22%   |
| Google Cyan                            | 3         | 0.22%   |
| Gigabyte X570 AORUS ELITE              | 3         | 0.22%   |
| Gigabyte B550 AORUS ELITE              | 3         | 0.22%   |
| Gigabyte A320M-H                       | 3         | 0.22%   |
| Dell XPS 15 7590                       | 3         | 0.22%   |
| Dell Vostro 5481                       | 3         | 0.22%   |
| Dell OptiPlex 780                      | 3         | 0.22%   |
| Dell OptiPlex 7010                     | 3         | 0.22%   |
| Dell Latitude E7440                    | 3         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 88        | 6.38%   |
| Dell Latitude      | 67        | 4.86%   |
| Dell Inspiron      | 64        | 4.64%   |
| HP Pavilion        | 43        | 3.12%   |
| Acer Aspire        | 35        | 2.54%   |
| Dell XPS           | 30        | 2.17%   |
| Lenovo IdeaPad     | 29        | 2.1%    |
| ASUS PRIME         | 29        | 2.1%    |
| HP ProBook         | 25        | 1.81%   |
| Dell OptiPlex      | 24        | 1.74%   |
| Dell Precision     | 22        | 1.59%   |
| ASUS ROG           | 22        | 1.59%   |
| HP EliteBook       | 20        | 1.45%   |
| ASUS TUF           | 19        | 1.38%   |
| HP Laptop          | 17        | 1.23%   |
| ASUS VivoBook      | 16        | 1.16%   |
| ASUS All           | 16        | 1.16%   |
| Unknown            | 16        | 1.16%   |
| Lenovo ThinkCentre | 14        | 1.01%   |
| HP Compaq          | 13        | 0.94%   |
| Dell Vostro        | 13        | 0.94%   |
| HP ENVY            | 8         | 0.58%   |
| Gigabyte X570      | 8         | 0.58%   |
| ASUS ASUS          | 8         | 0.58%   |
| Lenovo Yoga        | 7         | 0.51%   |
| Gigabyte B450M     | 6         | 0.43%   |
| Gigabyte A320M-S2H | 6         | 0.43%   |
| Gigabyte 970A-DS3P | 6         | 0.43%   |
| Acer Nitro         | 6         | 0.43%   |
| Toshiba Satellite  | 5         | 0.36%   |
| Lenovo ThinkBook   | 5         | 0.36%   |
| Lenovo Legion      | 5         | 0.36%   |
| Gigabyte B550      | 5         | 0.36%   |
| Dell System        | 5         | 0.36%   |
| ASUS SABERTOOTH    | 5         | 0.36%   |
| MSI MS-7A34        | 4         | 0.29%   |
| MSI MS-7817        | 4         | 0.29%   |
| HP OMEN            | 4         | 0.29%   |
| HP Notebook        | 4         | 0.29%   |
| HP EliteDesk       | 4         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 206       | 14.93%  |
| 2018    | 180       | 13.04%  |
| 2020    | 138       | 10%     |
| 2017    | 126       | 9.13%   |
| 2013    | 125       | 9.06%   |
| 2012    | 105       | 7.61%   |
| 2011    | 91        | 6.59%   |
| 2015    | 76        | 5.51%   |
| 2014    | 76        | 5.51%   |
| 2016    | 64        | 4.64%   |
| 2021    | 53        | 3.84%   |
| 2010    | 51        | 3.7%    |
| 2008    | 35        | 2.54%   |
| 2009    | 32        | 2.32%   |
| 2007    | 13        | 0.94%   |
| 2006    | 3         | 0.22%   |
| 2022    | 2         | 0.14%   |
| 2005    | 2         | 0.14%   |
| Unknown | 2         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 729       | 52.83%  |
| Desktop        | 571       | 41.38%  |
| Convertible    | 36        | 2.61%   |
| Mini pc        | 19        | 1.38%   |
| All in one     | 12        | 0.87%   |
| Tablet         | 7         | 0.51%   |
| Server         | 5         | 0.36%   |
| System on chip | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1280      | 92.29%  |
| Enabled  | 107       | 7.71%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1372      | 99.42%  |
| Yes  | 8         | 0.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 388       | 27.95%  |
| 4.01-8.0    | 292       | 21.04%  |
| 8.01-16.0   | 264       | 19.02%  |
| 32.01-64.0  | 185       | 13.33%  |
| 3.01-4.0    | 167       | 12.03%  |
| 64.01-256.0 | 34        | 2.45%   |
| 24.01-32.0  | 29        | 2.09%   |
| 1.01-2.0    | 24        | 1.73%   |
| 2.01-3.0    | 5         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 384       | 25.88%  |
| 4.01-8.0   | 352       | 23.72%  |
| 1.01-2.0   | 343       | 23.11%  |
| 3.01-4.0   | 227       | 15.3%   |
| 8.01-16.0  | 117       | 7.88%   |
| 0.51-1.0   | 38        | 2.56%   |
| 16.01-24.0 | 14        | 0.94%   |
| 24.01-32.0 | 4         | 0.27%   |
| 0.01-0.5   | 4         | 0.27%   |
| 32.01-64.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 720       | 50.88%  |
| 2      | 395       | 27.92%  |
| 3      | 147       | 10.39%  |
| 4      | 78        | 5.51%   |
| 5      | 37        | 2.61%   |
| 6      | 19        | 1.34%   |
| 7      | 9         | 0.64%   |
| 8      | 3         | 0.21%   |
| 0      | 3         | 0.21%   |
| 9      | 2         | 0.14%   |
| 11     | 1         | 0.07%   |
| 10     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 903       | 65.06%  |
| Yes       | 485       | 34.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1224      | 88.63%  |
| No        | 157       | 11.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1007      | 72.71%  |
| No        | 378       | 27.29%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 876       | 63.29%  |
| No        | 508       | 36.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 252       | 18.21%  |
| Germany      | 139       | 10.04%  |
| Russia       | 115       | 8.31%   |
| Brazil       | 101       | 7.3%    |
| France       | 82        | 5.92%   |
| Italy        | 66        | 4.77%   |
| UK           | 56        | 4.05%   |
| Spain        | 43        | 3.11%   |
| Netherlands  | 37        | 2.67%   |
| Poland       | 34        | 2.46%   |
| Ukraine      | 32        | 2.31%   |
| Canada       | 29        | 2.1%    |
| India        | 24        | 1.73%   |
| Mexico       | 20        | 1.45%   |
| Hungary      | 20        | 1.45%   |
| Czechia      | 17        | 1.23%   |
| Australia    | 17        | 1.23%   |
| Argentina    | 16        | 1.16%   |
| Switzerland  | 15        | 1.08%   |
| Greece       | 14        | 1.01%   |
| Bulgaria     | 12        | 0.87%   |
| Belgium      | 12        | 0.87%   |
| South Africa | 10        | 0.72%   |
| Turkey       | 9         | 0.65%   |
| Indonesia    | 9         | 0.65%   |
| Colombia     | 9         | 0.65%   |
| Belarus      | 9         | 0.65%   |
| Sweden       | 8         | 0.58%   |
| Romania      | 8         | 0.58%   |
| New Zealand  | 7         | 0.51%   |
| Israel       | 7         | 0.51%   |
| Finland      | 7         | 0.51%   |
| Estonia      | 7         | 0.51%   |
| Austria      | 7         | 0.51%   |
| Venezuela    | 6         | 0.43%   |
| Serbia       | 6         | 0.43%   |
| Norway       | 6         | 0.43%   |
| Denmark      | 6         | 0.43%   |
| Chile        | 6         | 0.43%   |
| Slovenia     | 5         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 27        | 1.89%   |
| Paris             | 16        | 1.12%   |
| Berlin            | 15        | 1.05%   |
| St Petersburg     | 13        | 0.91%   |
| Sao Paulo         | 13        | 0.91%   |
| Hamburg           | 13        | 0.91%   |
| Warsaw            | 12        | 0.84%   |
| Milan             | 11        | 0.77%   |
| Kyiv              | 11        | 0.77%   |
| Budapest          | 10        | 0.7%    |
| Rome              | 9         | 0.63%   |
| Madrid            | 9         | 0.63%   |
| Athens            | 9         | 0.63%   |
| Novosibirsk       | 8         | 0.56%   |
| Minsk             | 8         | 0.56%   |
| Frankfurt am Main | 8         | 0.56%   |
| Zurich            | 7         | 0.49%   |
| Sydney            | 7         | 0.49%   |
| Sofia             | 7         | 0.49%   |
| Munich            | 7         | 0.49%   |
| London            | 6         | 0.42%   |
| Amsterdam         | 6         | 0.42%   |
| Prague            | 5         | 0.35%   |
| Phoenix           | 5         | 0.35%   |
| Melbourne         | 5         | 0.35%   |
| Marseille         | 5         | 0.35%   |
| Los Angeles       | 5         | 0.35%   |
| Curitiba          | 5         | 0.35%   |
| Cologne           | 5         | 0.35%   |
| Bogotá           | 5         | 0.35%   |
| Auckland          | 5         | 0.35%   |
| Tel Aviv          | 4         | 0.28%   |
| St Louis          | 4         | 0.28%   |
| Seattle           | 4         | 0.28%   |
| San Jose          | 4         | 0.28%   |
| Rio de Janeiro    | 4         | 0.28%   |
| Montreal          | 4         | 0.28%   |
| Lima              | 4         | 0.28%   |
| Jakarta           | 4         | 0.28%   |
| Dallas            | 4         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 420       | 598    | 19%     |
| WDC                 | 352       | 563    | 15.93%  |
| Seagate             | 324       | 449    | 14.66%  |
| Toshiba             | 140       | 183    | 6.33%   |
| Kingston            | 136       | 164    | 6.15%   |
| SanDisk             | 108       | 121    | 4.89%   |
| Crucial             | 95        | 114    | 4.3%    |
| Unknown             | 75        | 93     | 3.39%   |
| Hitachi             | 61        | 72     | 2.76%   |
| Intel               | 57        | 83     | 2.58%   |
| SK hynix            | 48        | 54     | 2.17%   |
| HGST                | 38        | 47     | 1.72%   |
| A-DATA Technology   | 37        | 37     | 1.67%   |
| Micron Technology   | 27        | 30     | 1.22%   |
| Phison              | 18        | 26     | 0.81%   |
| Silicon Motion      | 13        | 15     | 0.59%   |
| OCZ                 | 13        | 15     | 0.59%   |
| KIOXIA              | 12        | 13     | 0.54%   |
| PNY                 | 10        | 10     | 0.45%   |
| Intenso             | 10        | 10     | 0.45%   |
| Corsair             | 10        | 19     | 0.45%   |
| Transcend           | 9         | 9      | 0.41%   |
| Patriot             | 9         | 11     | 0.41%   |
| Maxtor              | 9         | 9      | 0.41%   |
| LITEON              | 9         | 11     | 0.41%   |
| China               | 9         | 10     | 0.41%   |
| Apple               | 9         | 10     | 0.41%   |
| XPG                 | 8         | 8      | 0.36%   |
| SPCC                | 8         | 11     | 0.36%   |
| Goodram             | 8         | 18     | 0.36%   |
| Team                | 7         | 8      | 0.32%   |
| KingSpec            | 6         | 6      | 0.27%   |
| LITEONIT            | 5         | 5      | 0.23%   |
| JMicron Technology  | 5         | 5      | 0.23%   |
| Apacer              | 5         | 5      | 0.23%   |
| Mushkin             | 4         | 4      | 0.18%   |
| LDLC                | 4         | 12     | 0.18%   |
| Gigabyte Technology | 4         | 4      | 0.18%   |
| Fujitsu             | 4         | 4      | 0.18%   |
| Verbatim            | 3         | 3      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 33        | 1.33%   |
| Samsung SSD 850 EVO 250GB          | 21        | 0.85%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 20        | 0.81%   |
| Samsung SSD 850 EVO 500GB          | 19        | 0.76%   |
| Samsung NVMe SSD Drive 512GB       | 19        | 0.76%   |
| Kingston SA400S37240G 240GB SSD    | 19        | 0.76%   |
| Samsung NVMe SSD Drive 1TB         | 18        | 0.72%   |
| Kingston SA400S37480G 480GB SSD    | 18        | 0.72%   |
| Samsung SSD 860 EVO 1TB            | 17        | 0.68%   |
| Unknown MMC Card  32GB             | 16        | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB     | 15        | 0.6%    |
| Seagate ST1000DM003-1ER162 1TB     | 14        | 0.56%   |
| Samsung NVMe SSD Drive 500GB       | 14        | 0.56%   |
| Crucial CT1000MX500SSD1 1TB        | 14        | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB       | 13        | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB     | 12        | 0.48%   |
| Seagate ST1000DM003-1CH162 1TB     | 12        | 0.48%   |
| Samsung SSD 860 EVO 250GB          | 12        | 0.48%   |
| Toshiba MQ04ABF100 1TB             | 11        | 0.44%   |
| Samsung SSD 970 EVO Plus 500GB     | 11        | 0.44%   |
| Kingston SA400S37120G 120GB SSD    | 11        | 0.44%   |
| HGST HTS721010A9E630 1TB           | 11        | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 10        | 0.4%    |
| Toshiba HDWD110 1TB                | 10        | 0.4%    |
| Seagate ST500LT012-1DG142 500GB    | 10        | 0.4%    |
| Seagate ST500DM002-1BD142 500GB    | 10        | 0.4%    |
| Seagate ST2000DM001-1ER164 2TB     | 10        | 0.4%    |
| Seagate Expansion 4TB              | 10        | 0.4%    |
| SanDisk SSD PLUS 480GB             | 10        | 0.4%    |
| Samsung SSD 860 EVO M.2 500GB      | 10        | 0.4%    |
| Kingston SV300S37A240G 240GB SSD   | 10        | 0.4%    |
| WDC WD20EARX-00PASB0 2TB           | 9         | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB           | 9         | 0.36%   |
| Unknown SD/MMC/MS PRO 64GB         | 9         | 0.36%   |
| Toshiba MQ01ABF050 500GB           | 9         | 0.36%   |
| Toshiba MQ01ABD100 1TB             | 9         | 0.36%   |
| Toshiba DT01ACA200 2TB             | 9         | 0.36%   |
| Toshiba DT01ACA100 1TB             | 9         | 0.36%   |
| SanDisk SSD PLUS 240GB             | 9         | 0.36%   |
| SanDisk NVMe SSD Drive 512GB       | 9         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 319       | 438    | 36.42%  |
| WDC                 | 268       | 449    | 30.59%  |
| Toshiba             | 101       | 136    | 11.53%  |
| Hitachi             | 61        | 72     | 6.96%   |
| Samsung Electronics | 49        | 76     | 5.59%   |
| HGST                | 38        | 47     | 4.34%   |
| Unknown             | 14        | 15     | 1.6%    |
| Maxtor              | 9         | 9      | 1.03%   |
| Apple               | 5         | 5      | 0.57%   |
| Fujitsu             | 4         | 4      | 0.46%   |
| ASMT                | 2         | 3      | 0.23%   |
| WD MediaMax         | 1         | 1      | 0.11%   |
| USB                 | 1         | 1      | 0.11%   |
| Magnetic Data       | 1         | 2      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| JMicron Technology  | 1         | 1      | 0.11%   |
| Hewlett-Packard     | 1         | 2      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 228       | 295    | 29.23%  |
| Kingston            | 105       | 128    | 13.46%  |
| Crucial             | 82        | 100    | 10.51%  |
| SanDisk             | 74        | 83     | 9.49%   |
| WDC                 | 43        | 52     | 5.51%   |
| A-DATA Technology   | 22        | 22     | 2.82%   |
| Toshiba             | 18        | 23     | 2.31%   |
| Intel               | 18        | 24     | 2.31%   |
| Micron Technology   | 15        | 17     | 1.92%   |
| OCZ                 | 13        | 15     | 1.67%   |
| Intenso             | 10        | 10     | 1.28%   |
| SK hynix            | 9         | 10     | 1.15%   |
| Patriot             | 9         | 11     | 1.15%   |
| China               | 9         | 10     | 1.15%   |
| SPCC                | 8         | 10     | 1.03%   |
| PNY                 | 8         | 8      | 1.03%   |
| GOODRAM             | 8         | 18     | 1.03%   |
| Corsair             | 8         | 17     | 1.03%   |
| Transcend           | 7         | 7      | 0.9%    |
| LITEON              | 7         | 8      | 0.9%    |
| Team                | 6         | 6      | 0.77%   |
| KingSpec            | 6         | 6      | 0.77%   |
| LITEONIT            | 5         | 5      | 0.64%   |
| Apacer              | 5         | 5      | 0.64%   |
| Verbatim            | 3         | 3      | 0.38%   |
| Mushkin             | 3         | 3      | 0.38%   |
| JMicron Technology  | 3         | 3      | 0.38%   |
| Zheino              | 2         | 4      | 0.26%   |
| VENO                | 2         | 4      | 0.26%   |
| TO Exter            | 2         | 2      | 0.26%   |
| Seagate             | 2         | 7      | 0.26%   |
| Netac               | 2         | 2      | 0.26%   |
| Leven               | 2         | 3      | 0.26%   |
| LDLC                | 2         | 2      | 0.26%   |
| Gigabyte Technology | 2         | 2      | 0.26%   |
| Emtec               | 2         | 2      | 0.26%   |
| Dogfish             | 2         | 2      | 0.26%   |
| Apple               | 2         | 2      | 0.26%   |
| Unknown             | 1         | 1      | 0.13%   |
| TCSUNBOW            | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 708       | 1262   | 36.2%   |
| SSD     | 673       | 962    | 34.41%  |
| NVMe    | 488       | 627    | 24.95%  |
| MMC     | 58        | 73     | 2.97%   |
| Unknown | 29        | 45     | 1.48%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1058      | 2164   | 62.64%  |
| NVMe | 487       | 622    | 28.83%  |
| SAS  | 86        | 110    | 5.09%   |
| MMC  | 58        | 73     | 3.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 733       | 1108   | 49.43%  |
| 0.51-1.0   | 470       | 683    | 31.69%  |
| 1.01-2.0   | 150       | 240    | 10.11%  |
| 3.01-4.0   | 62        | 99     | 4.18%   |
| 2.01-3.0   | 33        | 42     | 2.23%   |
| 4.01-10.0  | 31        | 46     | 2.09%   |
| 10.01-20.0 | 4         | 6      | 0.27%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 353       | 25%     |
| 101-250        | 342       | 24.22%  |
| 501-1000       | 263       | 18.63%  |
| 1001-2000      | 136       | 9.63%   |
| More than 3000 | 124       | 8.78%   |
| 51-100         | 64        | 4.53%   |
| 2001-3000      | 62        | 4.39%   |
| 21-50          | 32        | 2.27%   |
| 1-20           | 31        | 2.2%    |
| Unknown        | 5         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 312       | 21.5%   |
| 101-250        | 260       | 17.92%  |
| 51-100         | 209       | 14.4%   |
| 21-50          | 204       | 14.06%  |
| 251-500        | 174       | 11.99%  |
| 501-1000       | 124       | 8.55%   |
| 1001-2000      | 72        | 4.96%   |
| More than 3000 | 63        | 4.34%   |
| 2001-3000      | 28        | 1.93%   |
| Unknown        | 5         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB     | 4         | 4      | 2.16%   |
| Seagate ST1000LM048-2E7172 1TB     | 3         | 3      | 1.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.62%   |
| Seagate ST1000DM003-1CH162 1TB     | 3         | 4      | 1.62%   |
| Kingston SV300S37A120G 120GB SSD   | 3         | 3      | 1.62%   |
| WDC WD5000AAKS-00V1A0 500GB        | 2         | 3      | 1.08%   |
| WDC WD5000AAKS-00A7B0 500GB        | 2         | 2      | 1.08%   |
| WDC WD30EZRX-00MMMB0 3TB           | 2         | 2      | 1.08%   |
| Seagate ST500LT012-9WS142 500GB    | 2         | 2      | 1.08%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 1.08%   |
| Seagate ST31000528AS 1TB           | 2         | 2      | 1.08%   |
| SanDisk SSD PLUS 240 GB            | 2         | 2      | 1.08%   |
| Intel SSDSA2M080G2GC 80GB          | 2         | 2      | 1.08%   |
| Hitachi HTS547575A9E384 752GB      | 2         | 2      | 1.08%   |
| Hitachi HTS541010A9E680 1TB        | 2         | 2      | 1.08%   |
| HGST HTS721010A9E630 1TB           | 2         | 3      | 1.08%   |
| Crucial CT275MX300SSD1 275GB       | 2         | 3      | 1.08%   |
| Zheino CHN mSATA02M 256 256GB SSD  | 1         | 2      | 0.54%   |
| WDC WD6400BEVT-00A0RT0 640GB       | 1         | 1      | 0.54%   |
| WDC WD5000LPVX-75V0TT0 500GB       | 1         | 1      | 0.54%   |
| WDC WD5000LPVX-60V0TT0 500GB       | 1         | 1      | 0.54%   |
| WDC WD5000LPVX-55V0TT0 500GB       | 1         | 1      | 0.54%   |
| WDC WD5000LPVT-24G33T1 500GB       | 1         | 1      | 0.54%   |
| WDC WD5000LPVT-22G33T0 500GB       | 1         | 1      | 0.54%   |
| WDC WD5000LPLX-00ZNTT0 500GB       | 1         | 1      | 0.54%   |
| WDC WD5000AAKS-00UU3A0 500GB       | 1         | 2      | 0.54%   |
| WDC WD5000AADS-56S9B1 500GB        | 1         | 1      | 0.54%   |
| WDC WD40EZRZ-00GXCB0 4TB           | 1         | 1      | 0.54%   |
| WDC WD40EZRX-00SPEB0 4TB           | 1         | 1      | 0.54%   |
| WDC WD40EFRX-68N32N0 4TB           | 1         | 2      | 0.54%   |
| WDC WD4003FZEX-00Z4SA0 4TB         | 1         | 2      | 0.54%   |
| WDC WD3200AAKX-001CA0 320GB        | 1         | 1      | 0.54%   |
| WDC WD30EZRX-00DC0B0 3TB           | 1         | 1      | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB           | 1         | 1      | 0.54%   |
| WDC WD2500AAJS-00B4A0 250GB        | 1         | 1      | 0.54%   |
| WDC WD20EARX-00PASB0 2TB           | 1         | 1      | 0.54%   |
| WDC WD1600BJKT-75F4T0 160GB        | 1         | 1      | 0.54%   |
| WDC WD1600AAJS-22L7A0 160GB        | 1         | 1      | 0.54%   |
| WDC WD15EARS-00Z5B1 1TB            | 1         | 1      | 0.54%   |
| WDC WD10JPVX-60JC3T1 1TB           | 1         | 1      | 0.54%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 45        | 51     | 24.46%  |
| Seagate             | 38        | 42     | 20.65%  |
| Toshiba             | 20        | 22     | 10.87%  |
| Samsung Electronics | 18        | 19     | 9.78%   |
| Hitachi             | 13        | 13     | 7.07%   |
| Crucial             | 8         | 10     | 4.35%   |
| SanDisk             | 7         | 7      | 3.8%    |
| Kingston            | 7         | 7      | 3.8%    |
| HGST                | 6         | 7      | 3.26%   |
| Intel               | 5         | 5      | 2.72%   |
| SK hynix            | 3         | 3      | 1.63%   |
| A-DATA Technology   | 3         | 3      | 1.63%   |
| OCZ                 | 2         | 2      | 1.09%   |
| Apple               | 2         | 2      | 1.09%   |
| Zheino              | 1         | 2      | 0.54%   |
| VENO                | 1         | 1      | 0.54%   |
| SPCC                | 1         | 1      | 0.54%   |
| Mushkin             | 1         | 1      | 0.54%   |
| Micron Technology   | 1         | 1      | 0.54%   |
| Maxtor              | 1         | 1      | 0.54%   |
| Drevo               | 1         | 1      | 0.54%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 44        | 50     | 33.33%  |
| Seagate             | 38        | 42     | 28.79%  |
| Toshiba             | 17        | 19     | 12.88%  |
| Hitachi             | 13        | 13     | 9.85%   |
| Samsung Electronics | 11        | 12     | 8.33%   |
| HGST                | 6         | 7      | 4.55%   |
| Apple               | 2         | 2      | 1.52%   |
| Maxtor              | 1         | 1      | 0.76%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 125       | 146    | 70.62%  |
| SSD  | 44        | 47     | 24.86%  |
| NVMe | 8         | 8      | 4.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                    | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| OCZ VERTEX460A 480GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| OCZ    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 779       | 1347   | 49.43%  |
| Detected | 624       | 1420   | 39.59%  |
| Malfunc  | 172       | 201    | 10.91%  |
| Failed   | 1         | 1      | 0.06%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 915       | 50.81%  |
| AMD                              | 315       | 17.49%  |
| Samsung Electronics              | 181       | 10.05%  |
| SanDisk                          | 83        | 4.61%   |
| SK hynix                         | 38        | 2.11%   |
| ASMedia Technology               | 33        | 1.83%   |
| Kingston Technology Company      | 32        | 1.78%   |
| Phison Electronics               | 25        | 1.39%   |
| Toshiba America Info Systems     | 24        | 1.33%   |
| Silicon Motion                   | 20        | 1.11%   |
| Nvidia                           | 19        | 1.05%   |
| ADATA Technology                 | 19        | 1.05%   |
| Marvell Technology Group         | 14        | 0.78%   |
| Micron/Crucial Technology        | 13        | 0.72%   |
| Micron Technology                | 13        | 0.72%   |
| JMicron Technology               | 13        | 0.72%   |
| KIOXIA                           | 11        | 0.61%   |
| Realtek Semiconductor            | 9         | 0.5%    |
| Broadcom / LSI                   | 7         | 0.39%   |
| VIA Technologies                 | 3         | 0.17%   |
| Lenovo                           | 3         | 0.17%   |
| Silicon Image                    | 2         | 0.11%   |
| Lite-On Technology               | 2         | 0.11%   |
| Union Memory (Shenzhen)          | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| LSI Logic / Symbios Logic        | 1         | 0.06%   |
| INNOGRIT                         | 1         | 0.06%   |
| Apple                            | 1         | 0.06%   |
| Adaptec                          | 1         | 0.06%   |
| 3ware                            | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 232       | 11.31%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 127       | 6.19%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 86        | 4.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 70        | 3.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 69        | 3.36%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 53        | 2.58%   |
| AMD 400 Series Chipset SATA Controller                                         | 46        | 2.24%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 45        | 2.19%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 42        | 2.05%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 42        | 2.05%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 40        | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 34        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 33        | 1.61%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 30        | 1.46%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 29        | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 28        | 1.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 27        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 27        | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                          | 25        | 1.22%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 1.17%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 23        | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 23        | 1.12%   |
| Intel SSD 660P Series                                                          | 23        | 1.12%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 23        | 1.12%   |
| AMD 500 Series Chipset SATA Controller                                         | 23        | 1.12%   |
| Samsung NVMe SSD Controller 980                                                | 22        | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 22        | 1.07%   |
| AMD FCH SATA Controller D                                                      | 21        | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 20        | 0.97%   |
| Intel SATA Controller [RAID mode]                                              | 19        | 0.93%   |
| AMD 300 Series Chipset SATA Controller                                         | 19        | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                | 17        | 0.83%   |
| Intel Volume Management Device NVMe RAID Controller                            | 16        | 0.78%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 16        | 0.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 16        | 0.78%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 16        | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 15        | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 15        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 15        | 0.73%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 15        | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1064      | 58.72%  |
| NVMe | 485       | 26.77%  |
| IDE  | 128       | 7.06%   |
| RAID | 124       | 6.84%   |
| SAS  | 8         | 0.44%   |
| SCSI | 3         | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1015      | 73.55%  |
| AMD    | 364       | 26.38%  |
| ARM    | 1         | 0.07%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 24        | 1.74%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 22        | 1.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 21        | 1.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 20        | 1.45%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 20        | 1.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 19        | 1.37%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 19        | 1.37%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 18        | 1.3%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 18        | 1.3%    |
| AMD Ryzen 5 3600 6-Core Processor             | 18        | 1.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 15        | 1.08%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 14        | 1.01%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 0.94%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 13        | 0.94%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 11        | 0.8%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 11        | 0.8%    |
| AMD Ryzen 5 2600 Six-Core Processor           | 11        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 10        | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 9         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 9         | 0.65%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 9         | 0.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 9         | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 0.65%   |
| AMD FX-8350 Eight-Core Processor              | 9         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.58%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 8         | 0.58%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 8         | 0.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.58%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 8         | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.58%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 8         | 0.58%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 7         | 0.51%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 7         | 0.51%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 0.51%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.51%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 7         | 0.51%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 7         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 356       | 25.74%  |
| Intel Core i7           | 346       | 25.02%  |
| AMD Ryzen 5             | 101       | 7.3%    |
| Intel Core i3           | 83        | 6%      |
| AMD Ryzen 7             | 73        | 5.28%   |
| Other                   | 44        | 3.18%   |
| Intel Celeron           | 40        | 2.89%   |
| Intel Xeon              | 36        | 2.6%    |
| Intel Core 2 Duo        | 30        | 2.17%   |
| AMD Ryzen 9             | 25        | 1.81%   |
| AMD FX                  | 25        | 1.81%   |
| AMD Ryzen 3             | 21        | 1.52%   |
| Intel Pentium           | 20        | 1.45%   |
| AMD A10                 | 16        | 1.16%   |
| Intel Atom              | 13        | 0.94%   |
| Intel Core i9           | 12        | 0.87%   |
| Intel Pentium Dual-Core | 11        | 0.8%    |
| AMD Phenom II X4        | 11        | 0.8%    |
| AMD A8                  | 10        | 0.72%   |
| Intel Core 2 Quad       | 9         | 0.65%   |
| AMD Ryzen 7 PRO         | 8         | 0.58%   |
| AMD A6                  | 8         | 0.58%   |
| Intel Pentium Silver    | 7         | 0.51%   |
| AMD Athlon II X4        | 7         | 0.51%   |
| AMD E2                  | 5         | 0.36%   |
| AMD Athlon              | 5         | 0.36%   |
| AMD A4                  | 5         | 0.36%   |
| AMD Ryzen Threadripper  | 4         | 0.29%   |
| AMD E1                  | 4         | 0.29%   |
| AMD Athlon 64 X2        | 4         | 0.29%   |
| AMD Sempron             | 3         | 0.22%   |
| AMD Phenom II X6        | 3         | 0.22%   |
| AMD Phenom II X2        | 3         | 0.22%   |
| AMD A12                 | 3         | 0.22%   |
| Intel Pentium Dual      | 2         | 0.14%   |
| Intel Pentium D         | 2         | 0.14%   |
| Intel Pentium 4         | 2         | 0.14%   |
| Intel Celeron Dual-Core | 2         | 0.14%   |
| AMD Phenom              | 2         | 0.14%   |
| AMD C-50                | 2         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 591       | 42.76%  |
| 2      | 456       | 33%     |
| 6      | 172       | 12.45%  |
| 8      | 107       | 7.74%   |
| 12     | 27        | 1.95%   |
| 1      | 12        | 0.87%   |
| 16     | 8         | 0.58%   |
| 3      | 3         | 0.22%   |
| 24     | 2         | 0.14%   |
| 32     | 1         | 0.07%   |
| 20     | 1         | 0.07%   |
| 18     | 1         | 0.07%   |
| 10     | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1366      | 98.99%  |
| 2      | 12        | 0.87%   |
| 4      | 1         | 0.07%   |
| 3      | 1         | 0.07%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1018      | 73.71%  |
| 1      | 363       | 26.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1380      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 162       | 11.52%  |
| 0x306a9    | 90        | 6.4%    |
| 0x206a7    | 85        | 6.05%   |
| 0x306c3    | 83        | 5.9%    |
| 0x906ea    | 56        | 3.98%   |
| 0x806ec    | 55        | 3.91%   |
| 0x906e9    | 45        | 3.2%    |
| 0x08701021 | 44        | 3.13%   |
| 0x40651    | 43        | 3.06%   |
| 0x806ea    | 42        | 2.99%   |
| 0x1067a    | 39        | 2.77%   |
| 0x806e9    | 37        | 2.63%   |
| 0x506e3    | 37        | 2.63%   |
| 0x0800820d | 29        | 2.06%   |
| 0x406e3    | 27        | 1.92%   |
| 0x08108109 | 26        | 1.85%   |
| 0x806c1    | 24        | 1.71%   |
| 0x08701013 | 24        | 1.71%   |
| 0x08108102 | 24        | 1.71%   |
| 0x306d4    | 23        | 1.64%   |
| 0x06000852 | 21        | 1.49%   |
| 0x806eb    | 19        | 1.35%   |
| 0x706e5    | 18        | 1.28%   |
| 0x906ed    | 17        | 1.21%   |
| 0xa0652    | 16        | 1.14%   |
| 0x706a1    | 15        | 1.07%   |
| 0x010000c8 | 14        | 1%      |
| 0x406c4    | 13        | 0.92%   |
| 0x08600106 | 13        | 0.92%   |
| 0x06001119 | 11        | 0.78%   |
| 0x0810100b | 10        | 0.71%   |
| 0x20655    | 9         | 0.64%   |
| 0x10676    | 9         | 0.64%   |
| 0x010000db | 9         | 0.64%   |
| 0x306f2    | 8         | 0.57%   |
| 0x106e5    | 8         | 0.57%   |
| 0x0700010f | 8         | 0.57%   |
| 0xa0653    | 7         | 0.5%    |
| 0x20652    | 7         | 0.5%    |
| 0x106a5    | 7         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 317       | 22.94%  |
| Haswell          | 148       | 10.71%  |
| Zen 2            | 101       | 7.31%   |
| IvyBridge        | 101       | 7.31%   |
| SandyBridge      | 97        | 7.02%   |
| Zen+             | 86        | 6.22%   |
| Skylake          | 73        | 5.28%   |
| Penryn           | 51        | 3.69%   |
| Piledriver       | 37        | 2.68%   |
| CometLake        | 36        | 2.6%    |
| Zen              | 31        | 2.24%   |
| K10              | 30        | 2.17%   |
| TigerLake        | 29        | 2.1%    |
| Icelake          | 27        | 1.95%   |
| Broadwell        | 26        | 1.88%   |
| Silvermont       | 23        | 1.66%   |
| Westmere         | 22        | 1.59%   |
| Goldmont plus    | 21        | 1.52%   |
| Nehalem          | 17        | 1.23%   |
| Zen 3            | 16        | 1.16%   |
| Excavator        | 15        | 1.09%   |
| Core             | 11        | 0.8%    |
| Jaguar           | 9         | 0.65%   |
| Steamroller      | 8         | 0.58%   |
| K8 Hammer        | 8         | 0.58%   |
| Puma             | 7         | 0.51%   |
| K10 Llano        | 7         | 0.51%   |
| Goldmont         | 6         | 0.43%   |
| Bobcat           | 6         | 0.43%   |
| Unknown          | 5         | 0.36%   |
| NetBurst         | 4         | 0.29%   |
| Bonnell          | 3         | 0.22%   |
| Tremont          | 1         | 0.07%   |
| K8 & K10 hybrid  | 1         | 0.07%   |
| Bulldozer        | 1         | 0.07%   |
| Alderlake Hybrid | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 772       | 46.26%  |
| Nvidia                           | 522       | 31.28%  |
| AMD                              | 369       | 22.11%  |
| ASPEED Technology                | 3         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Matrox Electronics Systems       | 1         | 0.06%   |
| ATI Technologies                 | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 66        | 3.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 55        | 3.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 50        | 2.93%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 50        | 2.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 46        | 2.7%    |
| Intel UHD Graphics 620                                                                   | 46        | 2.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 45        | 2.64%   |
| Intel HD Graphics 620                                                                    | 38        | 2.23%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 36        | 2.11%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 34        | 1.99%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 1.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 28        | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 1.64%   |
| Intel HD Graphics 630                                                                    | 28        | 1.64%   |
| AMD Renoir                                                                               | 28        | 1.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 27        | 1.58%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 22        | 1.29%   |
| Intel HD Graphics 5500                                                                   | 22        | 1.29%   |
| Intel HD Graphics 530                                                                    | 22        | 1.29%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 1.17%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 18        | 1.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 18        | 1.06%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 17        | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 1%      |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 15        | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 15        | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14        | 0.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 0.76%   |
| Intel Core Processor Integrated Graphics Controller                                      | 13        | 0.76%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 13        | 0.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 11        | 0.64%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 10        | 0.59%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 10        | 0.59%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 0.59%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 9         | 0.53%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 9         | 0.53%   |
| Intel Iris Plus Graphics G7                                                              | 9         | 0.53%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 9         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 509       | 36.7%   |
| 1 x AMD         | 288       | 20.76%  |
| 1 x Nvidia      | 282       | 20.33%  |
| Intel + Nvidia  | 210       | 15.14%  |
| Intel + AMD     | 41        | 2.96%   |
| 2 x AMD         | 23        | 1.66%   |
| AMD + Nvidia    | 20        | 1.44%   |
| 2 x Nvidia      | 7         | 0.5%    |
| 1 x ASPEED      | 2         | 0.14%   |
| Other           | 1         | 0.07%   |
| 3 x Nvidia      | 1         | 0.07%   |
| 1 x SiS         | 1         | 0.07%   |
| Nvidia + ASPEED | 1         | 0.07%   |
| 1 x Matrox      | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 978       | 69.86%  |
| Proprietary | 394       | 28.14%  |
| Unknown     | 28        | 2%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 663       | 47.26%  |
| 1.01-2.0   | 202       | 14.4%   |
| 3.01-4.0   | 129       | 9.19%   |
| 0.01-0.5   | 119       | 8.48%   |
| 0.51-1.0   | 116       | 8.27%   |
| 7.01-8.0   | 87        | 6.2%    |
| 5.01-6.0   | 52        | 3.71%   |
| 2.01-3.0   | 18        | 1.28%   |
| 8.01-16.0  | 15        | 1.07%   |
| 32.01-64.0 | 1         | 0.07%   |
| 4.01-5.0   | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 210       | 12.78%  |
| AU Optronics            | 168       | 10.23%  |
| LG Display              | 147       | 8.95%   |
| Chimei Innolux          | 130       | 7.91%   |
| Dell                    | 122       | 7.43%   |
| BOE                     | 121       | 7.36%   |
| Goldstar                | 107       | 6.51%   |
| Acer                    | 73        | 4.44%   |
| Hewlett-Packard         | 59        | 3.59%   |
| BenQ                    | 49        | 2.98%   |
| Ancor Communications    | 49        | 2.98%   |
| AOC                     | 40        | 2.43%   |
| Sharp                   | 37        | 2.25%   |
| Philips                 | 36        | 2.19%   |
| ViewSonic               | 28        | 1.7%    |
| PANDA                   | 22        | 1.34%   |
| Lenovo                  | 18        | 1.1%    |
| Iiyama                  | 17        | 1.03%   |
| LG Electronics          | 16        | 0.97%   |
| Chi Mei Optoelectronics | 15        | 0.91%   |
| ASUSTek Computer        | 14        | 0.85%   |
| Unknown                 | 12        | 0.73%   |
| Sony                    | 9         | 0.55%   |
| Panasonic               | 7         | 0.43%   |
| Apple                   | 7         | 0.43%   |
| InfoVision              | 6         | 0.37%   |
| NEC Computers           | 5         | 0.3%    |
| Medion                  | 5         | 0.3%    |
| Eizo                    | 5         | 0.3%    |
| HannStar                | 4         | 0.24%   |
| Gateway                 | 4         | 0.24%   |
| Vizio                   | 3         | 0.18%   |
| Viotek                  | 3         | 0.18%   |
| LG Philips              | 3         | 0.18%   |
| Idek Iiyama             | 3         | 0.18%   |
| HPN                     | 3         | 0.18%   |
| DENON                   | 3         | 0.18%   |
| Vestel Elektronik       | 2         | 0.12%   |
| Unknown (XXX)           | 2         | 0.12%   |
| Seiko/Epson             | 2         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.52%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch              | 8         | 0.46%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 8         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 7         | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 7         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.41%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 7         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 6         | 0.35%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                 | 6         | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch     | 5         | 0.29%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 5         | 0.29%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 5         | 0.29%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 5         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 5         | 0.29%   |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                     | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 5         | 0.29%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 5         | 0.29%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 4         | 0.23%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 4         | 0.23%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 4         | 0.23%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 4         | 0.23%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.23%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.23%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 4         | 0.23%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 4         | 0.23%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 4         | 0.23%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                     | 4         | 0.23%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.23%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch      | 4         | 0.23%   |
| BOE LCD Monitor BOE0852 1920x1080 344x194mm 15.5-inch                 | 4         | 0.23%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 4         | 0.23%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 4         | 0.23%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 4         | 0.23%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.23%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                 | 3         | 0.17%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 3         | 0.17%   |
| Samsung Electronics S34J55x SAM0F71 3440x1440 800x330mm 34.1-inch     | 3         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 758       | 49.13%  |
| 1366x768 (WXGA)    | 225       | 14.58%  |
| 3840x2160 (4K)     | 107       | 6.93%   |
| 2560x1440 (QHD)    | 76        | 4.93%   |
| 1600x900 (HD+)     | 55        | 3.56%   |
| 1280x1024 (SXGA)   | 42        | 2.72%   |
| 1920x1200 (WUXGA)  | 41        | 2.66%   |
| 1680x1050 (WSXGA+) | 38        | 2.46%   |
| Unknown            | 31        | 2.01%   |
| 1440x900 (WXGA+)   | 23        | 1.49%   |
| 2560x1080          | 22        | 1.43%   |
| 3440x1440          | 16        | 1.04%   |
| 1280x800 (WXGA)    | 11        | 0.71%   |
| 3840x1080          | 10        | 0.65%   |
| 1360x768           | 9         | 0.58%   |
| 2560x1600          | 7         | 0.45%   |
| 3840x2400          | 6         | 0.39%   |
| 1920x540           | 6         | 0.39%   |
| 1600x1200          | 5         | 0.32%   |
| 1024x768 (XGA)     | 5         | 0.32%   |
| 2160x1440          | 4         | 0.26%   |
| 5760x1080          | 3         | 0.19%   |
| 4480x1440          | 3         | 0.19%   |
| 3840x1600          | 3         | 0.19%   |
| 3600x1080          | 3         | 0.19%   |
| 3200x1800 (QHD+)   | 3         | 0.19%   |
| 1920x1280          | 3         | 0.19%   |
| 3840x1200          | 2         | 0.13%   |
| 3456x2160          | 2         | 0.13%   |
| 3200x1080          | 2         | 0.13%   |
| 2880x1800          | 2         | 0.13%   |
| 1280x720 (HD)      | 2         | 0.13%   |
| 7680x2160          | 1         | 0.06%   |
| 6400x2160          | 1         | 0.06%   |
| 4480x1600          | 1         | 0.06%   |
| 4480x1080          | 1         | 0.06%   |
| 3840x1920          | 1         | 0.06%   |
| 3600x1200          | 1         | 0.06%   |
| 3360x1080          | 1         | 0.06%   |
| 3000x1920          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 396       | 24.13%  |
| 27      | 147       | 8.96%   |
| 24      | 136       | 8.29%   |
| 13      | 128       | 7.8%    |
| 23      | 127       | 7.74%   |
| Unknown | 115       | 7.01%   |
| 21      | 103       | 6.28%   |
| 14      | 98        | 5.97%   |
| 17      | 91        | 5.55%   |
| 19      | 43        | 2.62%   |
| 31      | 35        | 2.13%   |
| 34      | 33        | 2.01%   |
| 22      | 27        | 1.65%   |
| 20      | 27        | 1.65%   |
| 12      | 25        | 1.52%   |
| 18      | 16        | 0.98%   |
| 25      | 11        | 0.67%   |
| 11      | 11        | 0.67%   |
| 84      | 10        | 0.61%   |
| 54      | 6         | 0.37%   |
| 32      | 6         | 0.37%   |
| 16      | 6         | 0.37%   |
| 72      | 4         | 0.24%   |
| 47      | 4         | 0.24%   |
| 37      | 4         | 0.24%   |
| 43      | 3         | 0.18%   |
| 40      | 3         | 0.18%   |
| 26      | 3         | 0.18%   |
| 52      | 2         | 0.12%   |
| 48      | 2         | 0.12%   |
| 46      | 2         | 0.12%   |
| 42      | 2         | 0.12%   |
| 39      | 2         | 0.12%   |
| 28      | 2         | 0.12%   |
| 74      | 1         | 0.06%   |
| 65      | 1         | 0.06%   |
| 61      | 1         | 0.06%   |
| 60      | 1         | 0.06%   |
| 57      | 1         | 0.06%   |
| 55      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 581       | 36.56%  |
| 501-600     | 368       | 23.16%  |
| 401-500     | 182       | 11.45%  |
| Unknown     | 115       | 7.24%   |
| 351-400     | 109       | 6.86%   |
| 201-300     | 87        | 5.48%   |
| 601-700     | 56        | 3.52%   |
| 701-800     | 39        | 2.45%   |
| 1001-1500   | 21        | 1.32%   |
| 1501-2000   | 15        | 0.94%   |
| 801-900     | 9         | 0.57%   |
| 901-1000    | 5         | 0.31%   |
| 101-200     | 1         | 0.06%   |
| 1-100       | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1090      | 75.8%   |
| 16/10   | 133       | 9.25%   |
| Unknown | 100       | 6.95%   |
| 5/4     | 43        | 2.99%   |
| 21/9    | 37        | 2.57%   |
| 4/3     | 13        | 0.9%    |
| 3/2     | 12        | 0.83%   |
| 32/9    | 5         | 0.35%   |
| 6/5     | 2         | 0.14%   |
| 1.96    | 2         | 0.14%   |
| 0.62    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 396       | 24.57%  |
| 201-250        | 298       | 18.49%  |
| 81-90          | 178       | 11.04%  |
| 301-350        | 148       | 9.18%   |
| Unknown        | 115       | 7.13%   |
| 151-200        | 95        | 5.89%   |
| 351-500        | 77        | 4.78%   |
| 121-130        | 66        | 4.09%   |
| 251-300        | 60        | 3.72%   |
| 71-80          | 54        | 3.35%   |
| 141-150        | 33        | 2.05%   |
| More than 1000 | 27        | 1.67%   |
| 501-1000       | 21        | 1.3%    |
| 61-70          | 19        | 1.18%   |
| 51-60          | 11        | 0.68%   |
| 131-140        | 5         | 0.31%   |
| 111-120        | 4         | 0.25%   |
| 1-40           | 2         | 0.12%   |
| 91-100         | 2         | 0.12%   |
| 41-50          | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 522       | 33.35%  |
| 121-160       | 431       | 27.54%  |
| 101-120       | 362       | 23.13%  |
| Unknown       | 115       | 7.35%   |
| 161-240       | 70        | 4.47%   |
| More than 240 | 41        | 2.62%   |
| 1-50          | 24        | 1.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1026      | 73.13%  |
| 2     | 305       | 21.74%  |
| 3     | 39        | 2.78%   |
| 0     | 31        | 2.21%   |
| 4     | 2         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 789       | 38.23%  |
| Intel                             | 720       | 34.88%  |
| Qualcomm Atheros                  | 227       | 11%     |
| Broadcom                          | 73        | 3.54%   |
| Ralink Technology                 | 29        | 1.41%   |
| TP-Link                           | 23        | 1.11%   |
| Ralink                            | 20        | 0.97%   |
| Nvidia                            | 16        | 0.78%   |
| Broadcom Limited                  | 14        | 0.68%   |
| Microsoft                         | 10        | 0.48%   |
| Marvell Technology Group          | 10        | 0.48%   |
| MediaTek                          | 8         | 0.39%   |
| Aquantia                          | 8         | 0.39%   |
| Xiaomi                            | 7         | 0.34%   |
| Samsung Electronics               | 7         | 0.34%   |
| ASIX Electronics                  | 7         | 0.34%   |
| DisplayLink                       | 6         | 0.29%   |
| Dell                              | 6         | 0.29%   |
| Qualcomm Atheros Communications   | 5         | 0.24%   |
| Qualcomm                          | 5         | 0.24%   |
| NetGear                           | 5         | 0.24%   |
| D-Link                            | 5         | 0.24%   |
| Sierra Wireless                   | 4         | 0.19%   |
| JMicron Technology                | 4         | 0.19%   |
| D-Link System                     | 4         | 0.19%   |
| Lenovo                            | 3         | 0.15%   |
| Huawei Technologies               | 3         | 0.15%   |
| Fibocom                           | 3         | 0.15%   |
| Apple                             | 3         | 0.15%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.1%    |
| Wacom                             | 2         | 0.1%    |
| T & A Mobile Phones               | 2         | 0.1%    |
| STMicroelectronics                | 2         | 0.1%    |
| Linksys                           | 2         | 0.1%    |
| Hewlett-Packard                   | 2         | 0.1%    |
| Ericsson Business Mobile Networks | 2         | 0.1%    |
| Edimax Technology                 | 2         | 0.1%    |
| Belkin Components                 | 2         | 0.1%    |
| ZyDAS                             | 1         | 0.05%   |
| Wilocity                          | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 570       | 23.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 89        | 3.66%   |
| Intel Wi-Fi 6 AX200                                               | 79        | 3.25%   |
| Intel I211 Gigabit Network Connection                             | 56        | 2.3%    |
| Intel Wireless 8265 / 8275                                        | 54        | 2.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 2.18%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 50        | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 44        | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 38        | 1.56%   |
| Intel Wireless 7260                                               | 37        | 1.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 33        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 33        | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 32        | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 30        | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 29        | 1.19%   |
| Intel Ethernet Connection (2) I219-V                              | 27        | 1.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 27        | 1.11%   |
| Intel Wireless 7265                                               | 26        | 1.07%   |
| Intel Wireless-AC 9260                                            | 23        | 0.94%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 23        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 0.9%    |
| Intel Wireless 3165                                               | 21        | 0.86%   |
| Intel Wi-Fi 6 AX201                                               | 21        | 0.86%   |
| Intel Wireless 8260                                               | 20        | 0.82%   |
| Intel Ethernet Connection (7) I219-V                              | 19        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 19        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 0.74%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 17        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 17        | 0.7%    |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 15        | 0.62%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 14        | 0.58%   |
| Ralink MT7601U Wireless Adapter                                   | 13        | 0.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 12        | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11        | 0.45%   |
| Broadcom BCM43142 802.11b/g/n                                     | 11        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 532       | 49.95%  |
| Qualcomm Atheros                      | 180       | 16.9%   |
| Realtek Semiconductor                 | 162       | 15.21%  |
| Broadcom                              | 47        | 4.41%   |
| Ralink Technology                     | 29        | 2.72%   |
| TP-Link                               | 21        | 1.97%   |
| Ralink                                | 20        | 1.88%   |
| Broadcom Limited                      | 12        | 1.13%   |
| Microsoft                             | 10        | 0.94%   |
| Qualcomm Atheros Communications       | 5         | 0.47%   |
| NetGear                               | 5         | 0.47%   |
| MediaTek                              | 5         | 0.47%   |
| D-Link                                | 5         | 0.47%   |
| Sierra Wireless                       | 4         | 0.38%   |
| Dell                                  | 4         | 0.38%   |
| Fibocom                               | 3         | 0.28%   |
| Wacom                                 | 2         | 0.19%   |
| Qualcomm                              | 2         | 0.19%   |
| Linksys                               | 2         | 0.19%   |
| Edimax Technology                     | 2         | 0.19%   |
| D-Link System                         | 2         | 0.19%   |
| Belkin Components                     | 2         | 0.19%   |
| ZyDAS                                 | 1         | 0.09%   |
| Wilocity                              | 1         | 0.09%   |
| Micro Star International              | 1         | 0.09%   |
| Mercucys                              | 1         | 0.09%   |
| Gemtek                                | 1         | 0.09%   |
| AVM                                   | 1         | 0.09%   |
| AirTies Wireless Networks             | 1         | 0.09%   |
| Accton Technology                     | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 79        | 7.36%   |
| Intel Wireless 8265 / 8275                                     | 54        | 5.03%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 44        | 4.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 38        | 3.54%   |
| Intel Wireless 7260                                            | 37        | 3.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 33        | 3.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 33        | 3.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 32        | 2.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 30        | 2.79%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 29        | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 27        | 2.51%   |
| Intel Wireless 7265                                            | 26        | 2.42%   |
| Intel Wireless-AC 9260                                         | 23        | 2.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 23        | 2.14%   |
| Intel Wireless 3165                                            | 21        | 1.96%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 1.96%   |
| Intel Wireless 8260                                            | 20        | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 19        | 1.77%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 17        | 1.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 1.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 1.3%    |
| Ralink MT7601U Wireless Adapter                                | 13        | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 1.21%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 1.12%   |
| Broadcom BCM43142 802.11b/g/n                                  | 11        | 1.02%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 10        | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 0.84%   |
| Realtek 802.11ac NIC                                           | 9         | 0.84%   |
| Intel Wireless 3160                                            | 9         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                 | 9         | 0.84%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 8         | 0.74%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 8         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 0.65%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 7         | 0.65%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 6         | 0.56%   |
| Microsoft Xbox 360 Wireless Adapter                            | 6         | 0.56%   |
| Intel WiFi Link 5100                                           | 6         | 0.56%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 6         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 737       | 56.35%  |
| Intel                            | 374       | 28.59%  |
| Qualcomm Atheros                 | 66        | 5.05%   |
| Broadcom                         | 30        | 2.29%   |
| Nvidia                           | 16        | 1.22%   |
| Marvell Technology Group         | 10        | 0.76%   |
| Aquantia                         | 8         | 0.61%   |
| Xiaomi                           | 7         | 0.54%   |
| Samsung Electronics              | 7         | 0.54%   |
| ASIX Electronics                 | 7         | 0.54%   |
| DisplayLink                      | 6         | 0.46%   |
| JMicron Technology               | 4         | 0.31%   |
| Qualcomm                         | 3         | 0.23%   |
| MediaTek                         | 3         | 0.23%   |
| Lenovo                           | 3         | 0.23%   |
| Broadcom Limited                 | 3         | 0.23%   |
| Apple                            | 3         | 0.23%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.15%   |
| TP-Link                          | 2         | 0.15%   |
| T & A Mobile Phones              | 2         | 0.15%   |
| Huawei Technologies              | 2         | 0.15%   |
| D-Link System                    | 2         | 0.15%   |
| VIA Technologies                 | 1         | 0.08%   |
| Silicon Integrated Systems [SiS] | 1         | 0.08%   |
| QNAP System                      | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)    | 1         | 0.08%   |
| Motorola BCS                     | 1         | 0.08%   |
| Mellanox Technologies            | 1         | 0.08%   |
| HMD Global                       | 1         | 0.08%   |
| Hewlett-Packard                  | 1         | 0.08%   |
| Elecom                           | 1         | 0.08%   |
| Davicom Semiconductor            | 1         | 0.08%   |
| 3Com                             | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 570       | 42.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 89        | 6.6%    |
| Intel I211 Gigabit Network Connection                             | 56        | 4.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 53        | 3.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 50        | 3.71%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 2.37%   |
| Intel Ethernet Connection (2) I219-V                              | 27        | 2%      |
| Intel Ethernet Connection I217-LM                                 | 22        | 1.63%   |
| Intel Ethernet Connection (7) I219-V                              | 19        | 1.41%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 1.33%   |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 1.26%   |
| Intel Ethernet Connection I218-LM                                 | 15        | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11        | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 10        | 0.74%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 0.74%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.74%   |
| Intel I210 Gigabit Network Connection                             | 9         | 0.67%   |
| Intel Ethernet Connection I217-V                                  | 9         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 9         | 0.67%   |
| Intel Ethernet Connection (2) I218-V                              | 9         | 0.67%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 8         | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 8         | 0.59%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8         | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 7         | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.52%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 7         | 0.52%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.44%   |
| Intel Ethernet Controller I225-V                                  | 6         | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 0.44%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 6         | 0.44%   |
| Nvidia MCP61 Ethernet                                             | 5         | 0.37%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 5         | 0.37%   |
| Intel Ethernet Connection I219-V                                  | 5         | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 5         | 0.37%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1224      | 54.57%  |
| WiFi     | 1008      | 44.94%  |
| Modem    | 11        | 0.49%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 792       | 54.02%  |
| Ethernet | 674       | 45.98%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 747       | 54.09%  |
| 1     | 584       | 42.29%  |
| 3     | 31        | 2.24%   |
| 0     | 13        | 0.94%   |
| 4     | 5         | 0.36%   |
| 6     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1230      | 88.11%  |
| Yes  | 166       | 11.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 455       | 51.18%  |
| Qualcomm Atheros Communications | 94        | 10.57%  |
| Realtek Semiconductor           | 84        | 9.45%   |
| Cambridge Silicon Radio         | 70        | 7.87%   |
| Broadcom                        | 46        | 5.17%   |
| IMC Networks                    | 29        | 3.26%   |
| Lite-On Technology              | 28        | 3.15%   |
| Foxconn / Hon Hai               | 13        | 1.46%   |
| Dell                            | 12        | 1.35%   |
| ASUSTek Computer                | 11        | 1.24%   |
| Apple                           | 9         | 1.01%   |
| Ralink                          | 8         | 0.9%    |
| Toshiba                         | 5         | 0.56%   |
| Realtek                         | 5         | 0.56%   |
| Hewlett-Packard                 | 3         | 0.34%   |
| Foxconn International           | 3         | 0.34%   |
| Unknown                         | 2         | 0.22%   |
| Ralink Technology               | 2         | 0.22%   |
| Belkin Components               | 2         | 0.22%   |
| Alps Electric                   | 2         | 0.22%   |
| TP-Link                         | 1         | 0.11%   |
| Micro Star International        | 1         | 0.11%   |
| Integrated System Solution      | 1         | 0.11%   |
| Dynex                           | 1         | 0.11%   |
| Creative Technology             | 1         | 0.11%   |
| AboCom Systems                  | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 161       | 18.07%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 78        | 8.75%   |
| Intel AX200 Bluetooth                               | 77        | 8.64%   |
| Intel AX201 Bluetooth                               | 72        | 8.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 70        | 7.86%   |
| Qualcomm Atheros  Bluetooth Device                  | 51        | 5.72%   |
| Realtek Bluetooth Radio                             | 43        | 4.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 34        | 3.82%   |
| Intel Wireless-AC 3168 Bluetooth                    | 23        | 2.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 21        | 2.36%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 14        | 1.57%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 1.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 13        | 1.46%   |
| Lite-On Bluetooth Device                            | 13        | 1.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 13        | 1.46%   |
| IMC Networks Bluetooth Radio                        | 10        | 1.12%   |
| Ralink RT3290 Bluetooth                             | 8         | 0.9%    |
| Qualcomm Atheros AR9462 Bluetooth                   | 8         | 0.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 0.9%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 7         | 0.79%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.79%   |
| IMC Networks Bluetooth Device                       | 6         | 0.67%   |
| Dell BCM20702A0 Bluetooth Module                    | 6         | 0.67%   |
| ASUS Bluetooth Device                               | 6         | 0.67%   |
| Realtek RTL8723B Bluetooth                          | 5         | 0.56%   |
| Realtek Bluetooth Radio                             | 5         | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 0.56%   |
| IMC Networks Bluetooth USB Host Controller          | 5         | 0.56%   |
| Lite-On Bluetooth Radio                             | 4         | 0.45%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.45%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.45%   |
| Lite-On Atheros AR3012 Bluetooth                    | 3         | 0.34%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.34%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.34%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.34%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.34%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 3         | 0.34%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 0.34%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.34%   |
| Apple Bluetooth Host Controller                     | 3         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 991       | 48.99%  |
| AMD                     | 433       | 21.4%   |
| Nvidia                  | 369       | 18.24%  |
| C-Media Electronics     | 38        | 1.88%   |
| Logitech                | 17        | 0.84%   |
| Realtek Semiconductor   | 15        | 0.74%   |
| GN Netcom               | 15        | 0.74%   |
| Creative Labs           | 13        | 0.64%   |
| JMTek                   | 11        | 0.54%   |
| Plantronics             | 9         | 0.44%   |
| Texas Instruments       | 7         | 0.35%   |
| Corsair                 | 7         | 0.35%   |
| Razer USA               | 6         | 0.3%    |
| Creative Technology     | 5         | 0.25%   |
| ASUSTek Computer        | 5         | 0.25%   |
| SAVITECH                | 4         | 0.2%    |
| Lenovo                  | 4         | 0.2%    |
| Kingston Technology     | 4         | 0.2%    |
| Hewlett-Packard         | 4         | 0.2%    |
| Generalplus Technology  | 4         | 0.2%    |
| Focusrite-Novation      | 4         | 0.2%    |
| Tenx Technology         | 3         | 0.15%   |
| RODE Microphones        | 3         | 0.15%   |
| Yamaha                  | 2         | 0.1%    |
| XMOS                    | 2         | 0.1%    |
| VIA Technologies        | 2         | 0.1%    |
| Trust                   | 2         | 0.1%    |
| SteelSeries ApS         | 2         | 0.1%    |
| Sony                    | 2         | 0.1%    |
| Samson Technologies     | 2         | 0.1%    |
| ONN                     | 2         | 0.1%    |
| Native Instruments      | 2         | 0.1%    |
| GYROCOM C&C             | 2         | 0.1%    |
| Fry's Electronics       | 2         | 0.1%    |
| Conexant Systems        | 2         | 0.1%    |
| CMX Systems             | 2         | 0.1%    |
| Bose                    | 2         | 0.1%    |
| BEHRINGER International | 2         | 0.1%    |
| Valve Software          | 1         | 0.05%   |
| USB MICROPHONE          | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 117       | 4.88%   |
| AMD Family 17h/19h HD Audio Controller                                     | 103       | 4.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 95        | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 89        | 3.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 85        | 3.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 79        | 3.3%    |
| AMD Starship/Matisse HD Audio Controller                                   | 79        | 3.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 61        | 2.54%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 59        | 2.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 52        | 2.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 50        | 2.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50        | 2.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 47        | 1.96%   |
| Intel Haswell-ULT HD Audio Controller                                      | 46        | 1.92%   |
| Intel 8 Series HD Audio Controller                                         | 46        | 1.92%   |
| Nvidia GP107GL High Definition Audio Controller                            | 45        | 1.88%   |
| AMD FCH Azalia Controller                                                  | 44        | 1.84%   |
| Intel Comet Lake PCH-LP cAVS                                               | 38        | 1.59%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 38        | 1.59%   |
| Nvidia GP106 High Definition Audio Controller                              | 32        | 1.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 32        | 1.34%   |
| Nvidia TU116 High Definition Audio Controller                              | 30        | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 29        | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 28        | 1.17%   |
| Intel 200 Series PCH HD Audio                                              | 28        | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 27        | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 26        | 1.08%   |
| Intel Broadwell-U Audio Controller                                         | 25        | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 24        | 1%      |
| Intel Comet Lake PCH cAVS                                                  | 24        | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 23        | 0.96%   |
| Intel CM238 HD Audio Controller                                            | 22        | 0.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 22        | 0.92%   |
| Nvidia TU106 High Definition Audio Controller                              | 21        | 0.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 21        | 0.88%   |
| AMD Kabini HDMI/DP Audio                                                   | 21        | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 19        | 0.79%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 19        | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 19        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                              | 18        | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 221       | 19.89%  |
| SK hynix            | 170       | 15.3%   |
| Kingston            | 162       | 14.58%  |
| Micron Technology   | 106       | 9.54%   |
| Crucial             | 91        | 8.19%   |
| Unknown             | 84        | 7.56%   |
| Corsair             | 74        | 6.66%   |
| G.Skill             | 50        | 4.5%    |
| A-DATA Technology   | 21        | 1.89%   |
| Ramaxel Technology  | 20        | 1.8%    |
| Elpida              | 14        | 1.26%   |
| Nanya Technology    | 13        | 1.17%   |
| Unknown (ABCD)      | 9         | 0.81%   |
| Transcend           | 8         | 0.72%   |
| Team                | 8         | 0.72%   |
| Patriot             | 8         | 0.72%   |
| Smart               | 6         | 0.54%   |
| Smart Brazil        | 4         | 0.36%   |
| GOODRAM             | 4         | 0.36%   |
| Apacer              | 4         | 0.36%   |
| Teikon              | 3         | 0.27%   |
| Silicon Power       | 3         | 0.27%   |
| AMD                 | 3         | 0.27%   |
| Kllisre             | 2         | 0.18%   |
| Avant               | 2         | 0.18%   |
| ASint Technology    | 2         | 0.18%   |
| Unknown             | 2         | 0.18%   |
| V-GeN               | 1         | 0.09%   |
| Unknown (82B5)      | 1         | 0.09%   |
| Unknown (08AE)      | 1         | 0.09%   |
| Unifosa             | 1         | 0.09%   |
| SHARETRONIC         | 1         | 0.09%   |
| Reboto              | 1         | 0.09%   |
| PUSKILL             | 1         | 0.09%   |
| Magnum Tech         | 1         | 0.09%   |
| KingFast            | 1         | 0.09%   |
| Hewlett-Packard     | 1         | 0.09%   |
| Goldkey             | 1         | 0.09%   |
| GeIL                | 1         | 0.09%   |
| Centon              | 1         | 0.09%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 1.24%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 14        | 1.16%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.91%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 0.83%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 10        | 0.83%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 9         | 0.74%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 8         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.66%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 8         | 0.66%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 8         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.58%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.58%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 6         | 0.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.5%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.5%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.5%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 6         | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 6         | 0.5%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 6         | 0.5%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.41%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 5         | 0.41%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.41%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 5         | 0.41%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s          | 5         | 0.41%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 5         | 0.41%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 4         | 0.33%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s  | 4         | 0.33%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.33%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 4         | 0.33%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.33%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.33%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.33%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.33%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 4         | 0.33%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 2400MT/s              | 4         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 520       | 54.45%  |
| DDR3    | 313       | 32.77%  |
| LPDDR4  | 28        | 2.93%   |
| DDR2    | 28        | 2.93%   |
| Unknown | 24        | 2.51%   |
| LPDDR3  | 21        | 2.2%    |
| SDRAM   | 17        | 1.78%   |
| DDR     | 3         | 0.31%   |
| DRAM    | 1         | 0.1%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 533       | 56.11%  |
| DIMM         | 368       | 38.74%  |
| Row Of Chips | 40        | 4.21%   |
| Chip         | 5         | 0.53%   |
| FB-DIMM      | 2         | 0.21%   |
| Unknown      | 2         | 0.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 438       | 41.79%  |
| 4096  | 276       | 26.34%  |
| 16384 | 194       | 18.51%  |
| 2048  | 104       | 9.92%   |
| 32768 | 20        | 1.91%   |
| 1024  | 15        | 1.43%   |
| 128   | 1         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 213       | 20.31%  |
| 2667    | 211       | 20.11%  |
| 3200    | 118       | 11.25%  |
| 2400    | 95        | 9.06%   |
| 1333    | 66        | 6.29%   |
| 2133    | 60        | 5.72%   |
| 3600    | 38        | 3.62%   |
| 1334    | 27        | 2.57%   |
| 800     | 24        | 2.29%   |
| 667     | 15        | 1.43%   |
| 3400    | 12        | 1.14%   |
| 2666    | 12        | 1.14%   |
| Unknown | 12        | 1.14%   |
| 4267    | 11        | 1.05%   |
| 3000    | 11        | 1.05%   |
| 1867    | 11        | 1.05%   |
| 1067    | 10        | 0.95%   |
| 8400    | 9         | 0.86%   |
| 3733    | 9         | 0.86%   |
| 3266    | 9         | 0.86%   |
| 1866    | 8         | 0.76%   |
| 3800    | 7         | 0.67%   |
| 1066    | 7         | 0.67%   |
| 3466    | 6         | 0.57%   |
| 2933    | 6         | 0.57%   |
| 4199    | 5         | 0.48%   |
| 3866    | 3         | 0.29%   |
| 3151    | 3         | 0.29%   |
| 2800    | 3         | 0.29%   |
| 2048    | 3         | 0.29%   |
| 1800    | 3         | 0.29%   |
| 400     | 3         | 0.29%   |
| 3333    | 2         | 0.19%   |
| 2132    | 2         | 0.19%   |
| 2000    | 2         | 0.19%   |
| 49926   | 1         | 0.1%    |
| 3467    | 1         | 0.1%    |
| 3334    | 1         | 0.1%    |
| 3066    | 1         | 0.1%    |
| 2866    | 1         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 20        | 42.55%  |
| Brother Industries     | 15        | 31.91%  |
| Seiko Epson            | 3         | 6.38%   |
| Samsung Electronics    | 3         | 6.38%   |
| Canon                  | 2         | 4.26%   |
| SAT                    | 1         | 2.13%   |
| Prolific Technology    | 1         | 2.13%   |
| Pantum                 | 1         | 2.13%   |
| Panasonic (Matsushita) | 1         | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Seiko Epson Printer                     | 1         | 2.08%   |
| Seiko Epson L3150 Series                | 1         | 2.08%   |
| Seiko Epson L120 Series                 | 1         | 2.08%   |
| SAT SAT38TUSE                           | 1         | 2.08%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 2.08%   |
| Samsung ML-216x Series Laser Printer    | 1         | 2.08%   |
| Samsung CLX-3180 Series                 | 1         | 2.08%   |
| Prolific PL2305 Parallel Port           | 1         | 2.08%   |
| Pantum P2200 series                     | 1         | 2.08%   |
| Panasonic (Matsushita) KX-MB1500RU      | 1         | 2.08%   |
| HP OfficeJet Pro 9010 series            | 1         | 2.08%   |
| HP Officejet 4630 series                | 1         | 2.08%   |
| HP OfficeJet 3830 series                | 1         | 2.08%   |
| HP LaserJet Pro M202dw                  | 1         | 2.08%   |
| HP LaserJet P2035                       | 1         | 2.08%   |
| HP LaserJet P2015 series                | 1         | 2.08%   |
| HP LaserJet P1102                       | 1         | 2.08%   |
| HP LaserJet M101-M106                   | 1         | 2.08%   |
| HP LaserJet CP1025nw                    | 1         | 2.08%   |
| HP LaserJet 200 color M251nw            | 1         | 2.08%   |
| HP LaserJet 1022                        | 1         | 2.08%   |
| HP LaserJet 1020                        | 1         | 2.08%   |
| HP LaserJet 1018                        | 1         | 2.08%   |
| HP LaserJet 1010                        | 1         | 2.08%   |
| HP ENVY 4500 series                     | 1         | 2.08%   |
| HP Deskjet F4500 series                 | 1         | 2.08%   |
| HP DeskJet F300 series                  | 1         | 2.08%   |
| HP DeskJet 930c                         | 1         | 2.08%   |
| HP DeskJet 2700 series                  | 1         | 2.08%   |
| HP DeskJet 2620 All-in-One Printer      | 1         | 2.08%   |
| HP Deskjet 2540 series                  | 1         | 2.08%   |
| Canon PIXMA MP495                       | 1         | 2.08%   |
| Canon PIXMA MG2500 Series               | 1         | 2.08%   |
| Brother MFC-L3770CDW series             | 1         | 2.08%   |
| Brother MFC-L2710DW series              | 1         | 2.08%   |
| Brother MFC-J805DW                      | 1         | 2.08%   |
| Brother MFC-J491DW                      | 1         | 2.08%   |
| Brother MFC-J4340DW                     | 1         | 2.08%   |
| Brother MFC-9330CDW                     | 1         | 2.08%   |
| Brother MFC-7460DN                      | 1         | 2.08%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 50%     |
| Seiko Epson     | 2         | 33.33%  |
| Hewlett-Packard | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 16.67%  |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 16.67%  |
| HP ScanJet G4010                                        | 1         | 16.67%  |
| Canon CanoScan LiDE 220                                 | 1         | 16.67%  |
| Canon CanoScan LiDE 120                                 | 1         | 16.67%  |
| Canon CanoScan LiDE 110                                 | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 160       | 17.66%  |
| Microdia                               | 96        | 10.6%   |
| IMC Networks                           | 77        | 8.5%    |
| Realtek Semiconductor                  | 75        | 8.28%   |
| Logitech                               | 74        | 8.17%   |
| Acer                                   | 68        | 7.51%   |
| Sunplus Innovation Technology          | 57        | 6.29%   |
| Cheng Uei Precision Industry (Foxlink) | 43        | 4.75%   |
| Quanta                                 | 33        | 3.64%   |
| Silicon Motion                         | 24        | 2.65%   |
| Suyin                                  | 21        | 2.32%   |
| Lite-On Technology                     | 16        | 1.77%   |
| Samsung Electronics                    | 14        | 1.55%   |
| Alcor Micro                            | 13        | 1.43%   |
| Syntek                                 | 12        | 1.32%   |
| Microsoft                              | 12        | 1.32%   |
| Ricoh                                  | 11        | 1.21%   |
| Apple                                  | 11        | 1.21%   |
| Luxvisions Innotech Limited            | 7         | 0.77%   |
| Generalplus Technology                 | 7         | 0.77%   |
| KYE Systems (Mouse Systems)            | 6         | 0.66%   |
| Z-Star Microelectronics                | 5         | 0.55%   |
| MacroSilicon                           | 5         | 0.55%   |
| Lenovo                                 | 5         | 0.55%   |
| ARC International                      | 5         | 0.55%   |
| Genesys Logic                          | 4         | 0.44%   |
| Sonix Technology                       | 3         | 0.33%   |
| Intel                                  | 3         | 0.33%   |
| Unknown                                | 2         | 0.22%   |
| Sunplus Technology                     | 2         | 0.22%   |
| Razer USA                              | 2         | 0.22%   |
| Huawei Technologies                    | 2         | 0.22%   |
| Cubeternet                             | 2         | 0.22%   |
| Creative Technology                    | 2         | 0.22%   |
| Arkmicro Technologies                  | 2         | 0.22%   |
| A4Tech                                 | 2         | 0.22%   |
| Yealink Network Technology             | 1         | 0.11%   |
| Y Media                                | 1         | 0.11%   |
| Xiongmai                               | 1         | 0.11%   |
| Valve Software                         | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 41        | 4.48%   |
| Microdia Integrated_Webcam_HD                                              | 41        | 4.48%   |
| Chicony Integrated Camera                                                  | 34        | 3.72%   |
| Sunplus Integrated_Webcam_HD                                               | 26        | 2.84%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 26        | 2.84%   |
| IMC Networks Integrated Camera                                             | 20        | 2.19%   |
| Acer Integrated Camera                                                     | 19        | 2.08%   |
| Logitech Webcam C270                                                       | 17        | 1.86%   |
| Logitech HD Pro Webcam C920                                                | 16        | 1.75%   |
| Microdia Integrated Webcam                                                 | 15        | 1.64%   |
| Chicony USB2.0 Camera                                                      | 14        | 1.53%   |
| Chicony HD Webcam                                                          | 14        | 1.53%   |
| Samsung Galaxy A5 (MTP)                                                    | 13        | 1.42%   |
| Acer Lenovo EasyCamera                                                     | 13        | 1.42%   |
| Acer HD Webcam                                                             | 10        | 1.09%   |
| Microdia USB 2.0 Camera                                                    | 8         | 0.87%   |
| Chicony HP Truevision HD                                                   | 8         | 0.87%   |
| Chicony HP HD Camera                                                       | 8         | 0.87%   |
| Chicony HD User Facing                                                     | 8         | 0.87%   |
| Microsoft LifeCam HD-3000                                                  | 7         | 0.77%   |
| Microdia Webcam Vitade AF                                                  | 7         | 0.77%   |
| Logitech HD Webcam C615                                                    | 7         | 0.77%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 7         | 0.77%   |
| Chicony Integrated Camera (1280x720@30)                                    | 7         | 0.77%   |
| Chicony HP Wide Vision HD Camera                                           | 7         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 7         | 0.77%   |
| Apple iPhone5/5C/5S/6                                                      | 7         | 0.77%   |
| Syntek Integrated Camera                                                   | 6         | 0.66%   |
| Realtek Integrated Webcam                                                  | 6         | 0.66%   |
| Lite-On Integrated Camera                                                  | 6         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                           | 6         | 0.66%   |
| Alcor Micro USB 2.0 Camera                                                 | 6         | 0.66%   |
| Sunplus HD WebCam                                                          | 5         | 0.55%   |
| Ricoh USB2.0 Camera                                                        | 5         | 0.55%   |
| Quanta HP HD Camera                                                        | 5         | 0.55%   |
| MacroSilicon USB Video                                                     | 5         | 0.55%   |
| Logitech Webcam Pro 9000                                                   | 5         | 0.55%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 5         | 0.55%   |
| Chicony USB 2.0 Camera                                                     | 5         | 0.55%   |
| Chicony HP TrueVision HD Camera                                            | 5         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 62        | 36.26%  |
| Validity Sensors           | 50        | 29.24%  |
| Shenzhen Goodix Technology | 28        | 16.37%  |
| Elan Microelectronics      | 8         | 4.68%   |
| LighTuning Technology      | 7         | 4.09%   |
| AuthenTec                  | 7         | 4.09%   |
| Upek                       | 5         | 2.92%   |
| STMicroelectronics         | 3         | 1.75%   |
| DigitalPersona             | 1         | 0.58%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 25        | 14.62%  |
| Unknown                                                                    | 15        | 8.77%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 6.43%   |
| Shenzhen Goodix FingerPrint                                                | 9         | 5.26%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 4.68%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 4.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 4.09%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 4.09%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.51%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 3.51%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 2.92%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 2.92%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.34%   |
| Synaptics  WBDI                                                            | 4         | 2.34%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.34%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.34%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 2.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.75%   |
| Validity Sensors VFS491                                                    | 3         | 1.75%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 1.75%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 1.75%   |
| STMicroelectronics Fingerprint Reader                                      | 3         | 1.75%   |
| AuthenTec AES2810                                                          | 3         | 1.75%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.17%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.17%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.17%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.58%   |
| Synaptics WBDI Device                                                      | 1         | 0.58%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.58%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.58%   |
| DigitalPersona Fingerprint Reader                                          | 1         | 0.58%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.58%   |
| AuthenTec AES3500 TruePrint Sensor                                         | 1         | 0.58%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.58%   |
| AuthenTec AES1600                                                          | 1         | 0.58%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 48        | 47.52%  |
| Alcor Micro              | 24        | 23.76%  |
| Upek                     | 5         | 4.95%   |
| O2 Micro                 | 5         | 4.95%   |
| SCM Microsystems         | 2         | 1.98%   |
| Reiner SCT Kartensysteme | 2         | 1.98%   |
| Realtek Semiconductor    | 2         | 1.98%   |
| OmniKey                  | 2         | 1.98%   |
| Lenovo                   | 2         | 1.98%   |
| Advanced Card Systems    | 2         | 1.98%   |
| Yubico.com               | 1         | 0.99%   |
| In Focus Systems         | 1         | 0.99%   |
| Giesecke & Devrient      | 1         | 0.99%   |
| Gemalto (was Gemplus)    | 1         | 0.99%   |
| Chicony Electronics      | 1         | 0.99%   |
| Aladdin R.D.             | 1         | 0.99%   |
| Aktiv                    | 1         | 0.99%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 23        | 22.77%  |
| Broadcom 5880                                                                | 15        | 14.85%  |
| Broadcom BCM5880 Secure Applications Processor                               | 11        | 10.89%  |
| Broadcom 58200                                                               | 11        | 10.89%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 8.91%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.95%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.95%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.98%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 1.98%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.98%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 1.98%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.99%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.99%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.99%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.99%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.99%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.99%   |
| OmniKey CardMan 1021                                                         | 1         | 0.99%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.99%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.99%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.99%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.99%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.99%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.99%   |
| Aktiv Rutoken lite                                                           | 1         | 0.99%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 981       | 69.77%  |
| 1     | 339       | 24.11%  |
| 2     | 69        | 4.91%   |
| 3     | 7         | 0.5%    |
| 4     | 5         | 0.36%   |
| 7     | 3         | 0.21%   |
| 6     | 2         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 169       | 32.13%  |
| Graphics card            | 97        | 18.44%  |
| Chipcard                 | 86        | 16.35%  |
| Net/wireless             | 53        | 10.08%  |
| Camera                   | 22        | 4.18%   |
| Bluetooth                | 20        | 3.8%    |
| Sound                    | 17        | 3.23%   |
| Communication controller | 17        | 3.23%   |
| Unassigned class         | 12        | 2.28%   |
| Card reader              | 10        | 1.9%    |
| Multimedia controller    | 7         | 1.33%   |
| Storage                  | 6         | 1.14%   |
| Net/ethernet             | 3         | 0.57%   |
| Network                  | 2         | 0.38%   |
| Modem                    | 2         | 0.38%   |
| Firewire controller      | 2         | 0.38%   |
| Storage/ide              | 1         | 0.19%   |

