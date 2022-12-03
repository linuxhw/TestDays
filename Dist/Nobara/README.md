Nobara - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Nobara/Desktop/README.md) and [notebooks](/Dist/Nobara/Notebook/README.md).

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

Total: 240

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [ae30b95cd8](https://linux-hardware.org/?probe=ae30b95cd8) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | Desktop     | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| Dell          | Studio 1737                 | Notebook    | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | Desktop     | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| HP            | 2000                        | Notebook    | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| HP            | 1998                        | Desktop     | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | Notebook    | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| HP            | 2000                        | Notebook    | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [062910424d](https://linux-hardware.org/?probe=062910424d) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [a205e0ea70](https://linux-hardware.org/?probe=a205e0ea70) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel         | B75                         | Desktop     | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d31088804f](https://linux-hardware.org/?probe=d31088804f) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gateway       | NE56R                       | Notebook    | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP            | 8594                        | Desktop     | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Alienware     | Area-51m R2 A00             | Notebook    | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | Notebook    | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | Notebook    | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | Notebook    | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | Notebook    | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| AZW           | SER                         | Mini pc     | [92460ed2a6](https://linux-hardware.org/?probe=92460ed2a6) | Aug 29, 2022 |
| ASUSTek       | TP500LA                     | Notebook    | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| Dell          | G15 5511                    | Notebook    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP            | 8054                        | Desktop     | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [5f2025770d](https://linux-hardware.org/?probe=5f2025770d) | Aug 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| Razer         | Blade                       | Notebook    | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | Desktop     | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines     | EL1870                      | Desktop     | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Nobara 36 | 187       | 100%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 187       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 5.19.14-201.fsync.fc36.x86_64 | 24        | 12.37%  |
| 5.19.9-201.fsync.fc36.x86_64  | 16        | 8.25%   |
| 5.19.7-204.fsync.fc36.x86_64  | 15        | 7.73%   |
| 6.0.7-201.fsync.fc36.x86_64   | 12        | 6.19%   |
| 5.19.16-201.fsync.fc36.x86_64 | 11        | 5.67%   |
| 5.18.13-201.fsync.fc36.x86_64 | 11        | 5.67%   |
| 6.0.5-201.fsync.fc36.x86_64   | 10        | 5.15%   |
| 6.0.9-201.fc36.x86_64         | 9         | 4.64%   |
| 5.19.12-201.fsync.fc36.x86_64 | 8         | 4.12%   |
| 5.19.10-201.fsync.fc36.x86_64 | 8         | 4.12%   |
| 5.19.4-201.fsync.fc36.x86_64  | 7         | 3.61%   |
| 5.18.16-201.fsync.fc36.x86_64 | 7         | 3.61%   |
| 5.19.15-202.fsync.fc36.x86_64 | 6         | 3.09%   |
| 5.19.11-201.fsync.fc36.x86_64 | 6         | 3.09%   |
| 5.18.17-201.fsync.fc36.x86_64 | 6         | 3.09%   |
| 6.0.10-201.fc36.x86_64        | 5         | 2.58%   |
| 6.0.9-202.fc36.x86_64         | 4         | 2.06%   |
| 6.0.8-201.fsync.fc36.x86_64   | 4         | 2.06%   |
| 6.0.7-202.fsync.fc36.x86_64   | 4         | 2.06%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 2.06%   |
| 5.18.19-201.fsync.fc36.x86_64 | 4         | 2.06%   |
| 5.18.11-201.fsync.fc36.x86_64 | 3         | 1.55%   |
| 5.19.7-203.fsync.fc36.x86_64  | 2         | 1.03%   |
| 5.19.13-202.fsync.fc36.x86_64 | 2         | 1.03%   |
| 5.18.18-201.fsync.fc36.x86_64 | 2         | 1.03%   |
| 6.0.2-xm1.0.fc36.x86_64       | 1         | 0.52%   |
| 5.19.2-602.inttf.fc36.x86_64  | 1         | 0.52%   |
| 5.19.13-201.fsync.fc36.x86_64 | 1         | 0.52%   |
| 5.18.9-201.fsync.fc36.x86_64  | 1         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.14 | 24        | 12.37%  |
| 5.19.7  | 17        | 8.76%   |
| 6.0.7   | 16        | 8.25%   |
| 5.19.9  | 16        | 8.25%   |
| 6.0.9   | 13        | 6.7%    |
| 5.19.16 | 11        | 5.67%   |
| 5.18.13 | 11        | 5.67%   |
| 6.0.5   | 10        | 5.15%   |
| 5.19.12 | 8         | 4.12%   |
| 5.19.10 | 8         | 4.12%   |
| 5.19.4  | 7         | 3.61%   |
| 5.18.16 | 7         | 3.61%   |
| 5.19.15 | 6         | 3.09%   |
| 5.19.11 | 6         | 3.09%   |
| 5.18.17 | 6         | 3.09%   |
| 6.0.10  | 5         | 2.58%   |
| 6.0.8   | 4         | 2.06%   |
| 5.19.8  | 4         | 2.06%   |
| 5.18.19 | 4         | 2.06%   |
| 5.19.13 | 3         | 1.55%   |
| 5.18.11 | 3         | 1.55%   |
| 5.18.18 | 2         | 1.03%   |
| 6.0.2   | 1         | 0.52%   |
| 5.19.2  | 1         | 0.52%   |
| 5.18.9  | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 111       | 57.22%  |
| 6.0     | 49        | 25.26%  |
| 5.18    | 34        | 17.53%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 187       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 136       | 72.34%  |
| KDE5       | 47        | 25%     |
| Unknown    | 4         | 2.13%   |
| X-Cinnamon | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 148       | 77.08%  |
| X11     | 40        | 20.83%  |
| Unknown | 4         | 2.08%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 158       | 83.6%   |
| GDM     | 16        | 8.47%   |
| SDDM    | 14        | 7.41%   |
| LightDM | 1         | 0.53%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 104       | 55.03%  |
| en_GB   | 11        | 5.82%   |
| es_ES   | 7         | 3.7%    |
| es_AR   | 7         | 3.7%    |
| es_MX   | 5         | 2.65%   |
| de_DE   | 5         | 2.65%   |
| pl_PL   | 4         | 2.12%   |
| en_CA   | 4         | 2.12%   |
| ru_RU   | 3         | 1.59%   |
| pt_PT   | 3         | 1.59%   |
| it_IT   | 3         | 1.59%   |
| en_IN   | 3         | 1.59%   |
| en_AU   | 3         | 1.59%   |
| Unknown | 3         | 1.59%   |
| pt_BR   | 2         | 1.06%   |
| nl_NL   | 2         | 1.06%   |
| fr_FR   | 2         | 1.06%   |
| es_CO   | 2         | 1.06%   |
| en_NZ   | 2         | 1.06%   |
| de_AT   | 2         | 1.06%   |
| sv_SE   | 1         | 0.53%   |
| sk_SK   | 1         | 0.53%   |
| hu_HU   | 1         | 0.53%   |
| hr_HR   | 1         | 0.53%   |
| fi_FI   | 1         | 0.53%   |
| es_GT   | 1         | 0.53%   |
| es_EC   | 1         | 0.53%   |
| es_CR   | 1         | 0.53%   |
| es_CL   | 1         | 0.53%   |
| en_ZA   | 1         | 0.53%   |
| cs_CZ   | 1         | 0.53%   |
| C       | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 142       | 75.53%  |
| BIOS | 46        | 24.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Ext4  | 104       | 55.61%  |
| Btrfs | 82        | 43.85%  |
| Xfs   | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 155       | 81.58%  |
| GPT     | 30        | 15.79%  |
| MBR     | 5         | 2.63%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 177       | 94.15%  |
| Yes       | 11        | 5.85%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 169       | 90.37%  |
| Yes       | 18        | 9.63%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 44        | 23.53%  |
| Lenovo              | 23        | 12.3%   |
| MSI                 | 21        | 11.23%  |
| Hewlett-Packard     | 20        | 10.7%   |
| Gigabyte Technology | 17        | 9.09%   |
| Dell                | 15        | 8.02%   |
| ASRock              | 11        | 5.88%   |
| Apple               | 6         | 3.21%   |
| Acer                | 4         | 2.14%   |
| Toshiba             | 3         | 1.6%    |
| Intel               | 3         | 1.6%    |
| Alienware           | 3         | 1.6%    |
| ZOTAC               | 1         | 0.53%   |
| Valve               | 1         | 0.53%   |
| Razer               | 1         | 0.53%   |
| Positivo            | 1         | 0.53%   |
| OEM                 | 1         | 0.53%   |
| Notebook            | 1         | 0.53%   |
| HUAWEI              | 1         | 0.53%   |
| Gateway             | 1         | 0.53%   |
| Fujitsu             | 1         | 0.53%   |
| EVOO                | 1         | 0.53%   |
| eMachines           | 1         | 0.53%   |
| ECS                 | 1         | 0.53%   |
| Coradir             | 1         | 0.53%   |
| Casper              | 1         | 0.53%   |
| Biostar             | 1         | 0.53%   |
| AZW                 | 1         | 0.53%   |
| Unknown             | 1         | 0.53%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS PRIME A320M-K                    | 3         | 1.6%    |
| Unknown                               | 3         | 1.6%    |
| MSI MS-7C37                           | 2         | 1.07%   |
| MSI MS-7C02                           | 2         | 1.07%   |
| MSI MS-7B86                           | 2         | 1.07%   |
| MSI MS-7693                           | 2         | 1.07%   |
| Lenovo IdeaPad Y700-15ISK 80NV        | 2         | 1.07%   |
| Gigabyte Z590I VISION D               | 2         | 1.07%   |
| Gigabyte B450M DS3H                   | 2         | 1.07%   |
| Dell OptiPlex 390                     | 2         | 1.07%   |
| ZOTAC ZBOX-CI320NANO series           | 1         | 0.53%   |
| Valve Jupiter                         | 1         | 0.53%   |
| Toshiba TECRA A50-A                   | 1         | 0.53%   |
| Toshiba Satellite L850                | 1         | 0.53%   |
| Toshiba Satellite L650                | 1         | 0.53%   |
| Razer Blade                           | 1         | 0.53%   |
| Positivo N1250                        | 1         | 0.53%   |
| OEM SHARKBAY                          | 1         | 0.53%   |
| Notebook P7xxDM2(-G)                  | 1         | 0.53%   |
| MSI Pulse GL76 12UEK                  | 1         | 0.53%   |
| MSI MS-7D53                           | 1         | 0.53%   |
| MSI MS-7D25                           | 1         | 0.53%   |
| MSI MS-7C91                           | 1         | 0.53%   |
| MSI MS-7C84                           | 1         | 0.53%   |
| MSI MS-7C35                           | 1         | 0.53%   |
| MSI MS-7B51                           | 1         | 0.53%   |
| MSI MS-7B17                           | 1         | 0.53%   |
| MSI MS-7A34                           | 1         | 0.53%   |
| MSI MS-7811                           | 1         | 0.53%   |
| MSI MS-7721                           | 1         | 0.53%   |
| MSI MS-7597                           | 1         | 0.53%   |
| MSI GE60 0NC/GE60 0ND                 | 1         | 0.53%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 OD 82NK | 1         | 0.53%   |
| Lenovo V330-15IKB 81AX                | 1         | 0.53%   |
| Lenovo V14-IIL 82C4                   | 1         | 0.53%   |
| Lenovo ThinkPad X240 20AMA0LTAU       | 1         | 0.53%   |
| Lenovo ThinkPad P1 20MD0020US         | 1         | 0.53%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW  | 1         | 0.53%   |
| Lenovo ThinkCentre M92p 3238E5U       | 1         | 0.53%   |
| Lenovo ThinkCentre M920q 10RS0030MX   | 1         | 0.53%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| ASUS PRIME           | 9         | 4.81%   |
| Lenovo IdeaPad       | 7         | 3.74%   |
| ASUS ROG             | 7         | 3.74%   |
| ASUS TUF             | 6         | 3.21%   |
| Dell Precision       | 4         | 2.14%   |
| Dell OptiPlex        | 4         | 2.14%   |
| ASUS VivoBook        | 4         | 2.14%   |
| Lenovo ThinkPad      | 3         | 1.6%    |
| Lenovo Legion        | 3         | 1.6%    |
| HP Pavilion          | 3         | 1.6%    |
| HP EliteDesk         | 3         | 1.6%    |
| Unknown              | 3         | 1.6%    |
| Toshiba Satellite    | 2         | 1.07%   |
| MSI MS-7C37          | 2         | 1.07%   |
| MSI MS-7C02          | 2         | 1.07%   |
| MSI MS-7B86          | 2         | 1.07%   |
| MSI MS-7693          | 2         | 1.07%   |
| Lenovo ThinkCentre   | 2         | 1.07%   |
| Lenovo G580          | 2         | 1.07%   |
| HP ZBook             | 2         | 1.07%   |
| HP OMEN              | 2         | 1.07%   |
| HP EliteBook         | 2         | 1.07%   |
| Gigabyte Z590I       | 2         | 1.07%   |
| Gigabyte X570        | 2         | 1.07%   |
| Gigabyte B450M       | 2         | 1.07%   |
| ASUS ASUS            | 2         | 1.07%   |
| Acer Aspire          | 2         | 1.07%   |
| ZOTAC ZBOX-CI320NANO | 1         | 0.53%   |
| Valve Jupiter        | 1         | 0.53%   |
| Toshiba TECRA        | 1         | 0.53%   |
| Razer Blade          | 1         | 0.53%   |
| Positivo N1250       | 1         | 0.53%   |
| OEM SHARKBAY         | 1         | 0.53%   |
| Notebook P7xxDM2(-G) | 1         | 0.53%   |
| MSI Pulse            | 1         | 0.53%   |
| MSI MS-7D53          | 1         | 0.53%   |
| MSI MS-7D25          | 1         | 0.53%   |
| MSI MS-7C91          | 1         | 0.53%   |
| MSI MS-7C84          | 1         | 0.53%   |
| MSI MS-7C35          | 1         | 0.53%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 29        | 15.51%  |
| 2019 | 29        | 15.51%  |
| 2018 | 18        | 9.63%   |
| 2020 | 16        | 8.56%   |
| 2013 | 16        | 8.56%   |
| 2014 | 15        | 8.02%   |
| 2017 | 14        | 7.49%   |
| 2012 | 11        | 5.88%   |
| 2016 | 9         | 4.81%   |
| 2022 | 8         | 4.28%   |
| 2015 | 7         | 3.74%   |
| 2011 | 7         | 3.74%   |
| 2009 | 3         | 1.6%    |
| 2008 | 3         | 1.6%    |
| 2010 | 2         | 1.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 96        | 51.34%  |
| Notebook    | 85        | 45.45%  |
| Mini pc     | 3         | 1.6%    |
| Tablet      | 1         | 0.53%   |
| Convertible | 1         | 0.53%   |
| All in one  | 1         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 187       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 187       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 53        | 28.34%  |
| 8.01-16.0   | 42        | 22.46%  |
| 4.01-8.0    | 34        | 18.18%  |
| 32.01-64.0  | 30        | 16.04%  |
| 3.01-4.0    | 22        | 11.76%  |
| 24.01-32.0  | 3         | 1.6%    |
| 64.01-256.0 | 2         | 1.07%   |
| 1.01-2.0    | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 88        | 45.6%   |
| 3.01-4.0   | 47        | 24.35%  |
| 2.01-3.0   | 36        | 18.65%  |
| 8.01-16.0  | 15        | 7.77%   |
| 1.01-2.0   | 4         | 2.07%   |
| 16.01-24.0 | 2         | 1.04%   |
| 24.01-32.0 | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 92        | 48.68%  |
| 2      | 52        | 27.51%  |
| 3      | 27        | 14.29%  |
| 5      | 9         | 4.76%   |
| 4      | 6         | 3.17%   |
| 10     | 1         | 0.53%   |
| 7      | 1         | 0.53%   |
| 6      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 146       | 78.07%  |
| Yes       | 41        | 21.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 88.83%  |
| No        | 21        | 11.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 76.47%  |
| No        | 44        | 23.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 123       | 65.43%  |
| No        | 65        | 34.57%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 61        | 32.62%  |
| Germany      | 9         | 4.81%   |
| Argentina    | 8         | 4.28%   |
| UK           | 6         | 3.21%   |
| Mexico       | 6         | 3.21%   |
| Canada       | 6         | 3.21%   |
| Poland       | 5         | 2.67%   |
| France       | 5         | 2.67%   |
| Spain        | 4         | 2.14%   |
| Russia       | 4         | 2.14%   |
| Portugal     | 4         | 2.14%   |
| India        | 4         | 2.14%   |
| Chile        | 4         | 2.14%   |
| Brazil       | 4         | 2.14%   |
| Serbia       | 3         | 1.6%    |
| Philippines  | 3         | 1.6%    |
| Netherlands  | 3         | 1.6%    |
| Italy        | 3         | 1.6%    |
| Croatia      | 3         | 1.6%    |
| Colombia     | 3         | 1.6%    |
| Austria      | 3         | 1.6%    |
| Australia    | 3         | 1.6%    |
| Vietnam      | 2         | 1.07%   |
| South Africa | 2         | 1.07%   |
| Norway       | 2         | 1.07%   |
| New Zealand  | 2         | 1.07%   |
| Hungary      | 2         | 1.07%   |
| Czechia      | 2         | 1.07%   |
| Belgium      | 2         | 1.07%   |
| Venezuela    | 1         | 0.53%   |
| Taiwan       | 1         | 0.53%   |
| Sweden       | 1         | 0.53%   |
| South Korea  | 1         | 0.53%   |
| Slovakia     | 1         | 0.53%   |
| Singapore    | 1         | 0.53%   |
| Romania      | 1         | 0.53%   |
| Pakistan     | 1         | 0.53%   |
| Morocco      | 1         | 0.53%   |
| Lithuania    | 1         | 0.53%   |
| Kenya        | 1         | 0.53%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| Atlanta       | 3         | 1.57%   |
| Wasilla       | 2         | 1.05%   |
| Villa Nueva   | 2         | 1.05%   |
| Schmalkalden  | 2         | 1.05%   |
| San Jose      | 2         | 1.05%   |
| San Antonio   | 2         | 1.05%   |
| Rotterdam     | 2         | 1.05%   |
| Poznan        | 2         | 1.05%   |
| Philadelphia  | 2         | 1.05%   |
| Ochsenfurt    | 2         | 1.05%   |
| Melbourne     | 2         | 1.05%   |
| Johannesburg  | 2         | 1.05%   |
| Guadalajara   | 2         | 1.05%   |
| Buenos Aires  | 2         | 1.05%   |
| Belgrade      | 2         | 1.05%   |
| Zamora        | 1         | 0.52%   |
| Zagreb        | 1         | 0.52%   |
| Zadar         | 1         | 0.52%   |
| Wooster       | 1         | 0.52%   |
| Wiesbaden     | 1         | 0.52%   |
| Wesley Chapel | 1         | 0.52%   |
| Wellington    | 1         | 0.52%   |
| Wayne         | 1         | 0.52%   |
| Warsaw        | 1         | 0.52%   |
| Waldorf       | 1         | 0.52%   |
| Wabrzezno     | 1         | 0.52%   |
| Vineland      | 1         | 0.52%   |
| Vilnius       | 1         | 0.52%   |
| Villarrica    | 1         | 0.52%   |
| Vienna        | 1         | 0.52%   |
| Veszprém     | 1         | 0.52%   |
| Varaždin     | 1         | 0.52%   |
| Valledupar    | 1         | 0.52%   |
| Vagos         | 1         | 0.52%   |
| Tulsa         | 1         | 0.52%   |
| Tomah         | 1         | 0.52%   |
| Tenna         | 1         | 0.52%   |
| Tamworth      | 1         | 0.52%   |
| Szeged        | 1         | 0.52%   |
| Smolensk      | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 57        | 82     | 17.81%  |
| WDC                          | 50        | 66     | 15.63%  |
| Seagate                      | 36        | 46     | 11.25%  |
| Toshiba                      | 24        | 24     | 7.5%    |
| Crucial                      | 20        | 24     | 6.25%   |
| Sandisk                      | 18        | 19     | 5.63%   |
| Kingston                     | 18        | 20     | 5.63%   |
| Intel                        | 8         | 11     | 2.5%    |
| SK hynix                     | 7         | 7      | 2.19%   |
| Phison Electronics           | 6         | 6      | 1.88%   |
| Hitachi                      | 6         | 7      | 1.88%   |
| PNY                          | 5         | 8      | 1.56%   |
| Phison                       | 5         | 6      | 1.56%   |
| Micron Technology            | 5         | 5      | 1.56%   |
| China                        | 5         | 5      | 1.56%   |
| Micron/Crucial Technology    | 4         | 4      | 1.25%   |
| Apple                        | 4         | 5      | 1.25%   |
| Unknown                      | 3         | 3      | 0.94%   |
| KIOXIA                       | 3         | 3      | 0.94%   |
| A-DATA Technology            | 3         | 3      | 0.94%   |
| Unknown                      | 3         | 4      | 0.94%   |
| Transcend                    | 2         | 2      | 0.63%   |
| Team                         | 2         | 2      | 0.63%   |
| Realtek Semiconductor        | 2         | 2      | 0.63%   |
| LITEON                       | 2         | 2      | 0.63%   |
| HGST                         | 2         | 2      | 0.63%   |
| ADATA Technology             | 2         | 2      | 0.63%   |
| XPG                          | 1         | 1      | 0.31%   |
| Verbatim                     | 1         | 1      | 0.31%   |
| SuperSSpeed                  | 1         | 1      | 0.31%   |
| SPCC                         | 1         | 1      | 0.31%   |
| Solid State Storage          | 1         | 1      | 0.31%   |
| Silicon Motion               | 1         | 1      | 0.31%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.31%   |
| Ramsta                       | 1         | 1      | 0.31%   |
| OCZ                          | 1         | 1      | 0.31%   |
| MyDigitalSSD                 | 1         | 1      | 0.31%   |
| Mushkin                      | 1         | 1      | 0.31%   |
| LITEONIT                     | 1         | 1      | 0.31%   |
| KIOXIA-EXCERIA               | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 8         | 2.2%    |
| Toshiba HDWD110 1TB                                  | 5         | 1.37%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 4         | 1.1%    |
| Phison E12 NVMe Controller 2TB                       | 4         | 1.1%    |
| Kingston SA400S37240G 240GB SSD                      | 4         | 1.1%    |
| Intel SSD 660P Series 512GB                          | 4         | 1.1%    |
| WDC WDBNCE5000PNC 500GB SSD                          | 3         | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB                             | 3         | 0.82%   |
| Toshiba MQ04ABF100 1TB                               | 3         | 0.82%   |
| Toshiba DT01ACA100 1TB                               | 3         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 0.82%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB    | 3         | 0.82%   |
| Samsung SSD 860 EVO 500GB                            | 3         | 0.82%   |
| Samsung SSD 850 EVO 500GB                            | 3         | 0.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 250GB | 3         | 0.82%   |
| Micron/Crucial P2 NVMe PCIe SSD 250GB                | 3         | 0.82%   |
| Crucial CT1000MX500SSD1 1TB                          | 3         | 0.82%   |
| Crucial CT1000BX500SSD1 1TB                          | 3         | 0.82%   |
| Unknown                                              | 3         | 0.82%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                     | 2         | 0.55%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 2         | 0.55%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                       | 2         | 0.55%   |
| WDC WD5000BEVT-75ZAT0 500GB                          | 2         | 0.55%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 2         | 0.55%   |
| WDC WD10EZEX-00BN5A0 1TB                             | 2         | 0.55%   |
| Toshiba MQ01ABF050 500GB                             | 2         | 0.55%   |
| Seagate ST3500418AS 500GB                            | 2         | 0.55%   |
| Seagate ST3500414CS 500GB                            | 2         | 0.55%   |
| Seagate ST2000DX002-2DV164 2TB                       | 2         | 0.55%   |
| Seagate ST2000DM008-2FR102 2TB                       | 2         | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB                       | 2         | 0.55%   |
| Seagate BUP Portable 5TB                             | 2         | 0.55%   |
| Sandisk WD Black SN850 256GB                         | 2         | 0.55%   |
| SanDisk SSD PLUS 240GB                               | 2         | 0.55%   |
| Samsung SSD 980 500GB                                | 2         | 0.55%   |
| Samsung SSD 980 1TB                                  | 2         | 0.55%   |
| Samsung SSD 860 EVO 1TB                              | 2         | 0.55%   |
| Samsung SSD 850 EVO 250GB                            | 2         | 0.55%   |
| Samsung NVMe SSD Drive 1TB                           | 2         | 0.55%   |
| Samsung NVMe SSD Drive 1024GB                        | 2         | 0.55%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 37        | 48     | 33.04%  |
| Seagate             | 36        | 44     | 32.14%  |
| Toshiba             | 20        | 20     | 17.86%  |
| Samsung Electronics | 6         | 8      | 5.36%   |
| Hitachi             | 6         | 7      | 5.36%   |
| HGST                | 2         | 2      | 1.79%   |
| Apple               | 2         | 2      | 1.79%   |
| Unknown             | 1         | 1      | 0.89%   |
| HGST HTS            | 1         | 1      | 0.89%   |
| Fujitsu             | 1         | 1      | 0.89%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 25        | 30     | 22.12%  |
| Crucial             | 20        | 24     | 17.7%   |
| WDC                 | 11        | 12     | 9.73%   |
| Kingston            | 10        | 12     | 8.85%   |
| SanDisk             | 8         | 8      | 7.08%   |
| PNY                 | 5         | 8      | 4.42%   |
| China               | 5         | 5      | 4.42%   |
| A-DATA Technology   | 3         | 3      | 2.65%   |
| Transcend           | 2         | 2      | 1.77%   |
| Toshiba             | 2         | 2      | 1.77%   |
| LITEON              | 2         | 2      | 1.77%   |
| Intel               | 2         | 2      | 1.77%   |
| Verbatim            | 1         | 1      | 0.88%   |
| Team                | 1         | 1      | 0.88%   |
| SuperSSpeed         | 1         | 1      | 0.88%   |
| SPCC                | 1         | 1      | 0.88%   |
| SK hynix            | 1         | 1      | 0.88%   |
| Seagate             | 1         | 1      | 0.88%   |
| Ramsta              | 1         | 1      | 0.88%   |
| OCZ                 | 1         | 1      | 0.88%   |
| MyDigitalSSD        | 1         | 1      | 0.88%   |
| Mushkin             | 1         | 1      | 0.88%   |
| Micron Technology   | 1         | 1      | 0.88%   |
| LITEONIT            | 1         | 1      | 0.88%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.88%   |
| KingFast            | 1         | 1      | 0.88%   |
| JMicron Technology  | 1         | 1      | 0.88%   |
| Foxline             | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |
| Unknown             | 1         | 2      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 93        | 129    | 33.7%   |
| HDD     | 92        | 134    | 33.33%  |
| NVMe    | 86        | 120    | 31.16%  |
| Unknown | 3         | 3      | 1.09%   |
| MMC     | 2         | 2      | 0.72%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 140       | 255    | 58.58%  |
| NVMe | 86        | 120    | 35.98%  |
| SAS  | 11        | 11     | 4.6%    |
| MMC  | 2         | 2      | 0.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 100       | 128    | 48.31%  |
| 0.51-1.0   | 73        | 94     | 35.27%  |
| 1.01-2.0   | 19        | 26     | 9.18%   |
| 3.01-4.0   | 5         | 5      | 2.42%   |
| 2.01-3.0   | 4         | 4      | 1.93%   |
| 4.01-10.0  | 4         | 4      | 1.93%   |
| 10.01-20.0 | 2         | 2      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 57        | 30.16%  |
| 251-500        | 45        | 23.81%  |
| 501-1000       | 36        | 19.05%  |
| 1001-2000      | 20        | 10.58%  |
| More than 3000 | 10        | 5.29%   |
| 51-100         | 8         | 4.23%   |
| Unknown        | 5         | 2.65%   |
| 2001-3000      | 4         | 2.12%   |
| 21-50          | 3         | 1.59%   |
| 1-20           | 1         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 56        | 28.87%  |
| 21-50          | 50        | 25.77%  |
| 101-250        | 23        | 11.86%  |
| 51-100         | 23        | 11.86%  |
| 251-500        | 14        | 7.22%   |
| 501-1000       | 14        | 7.22%   |
| 2001-3000      | 5         | 2.58%   |
| Unknown        | 5         | 2.58%   |
| 1001-2000      | 3         | 1.55%   |
| More than 3000 | 1         | 0.52%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2         | 2      | 18.18%  |
| WDC WD20EURS-63S48Y0 2TB                       | 1         | 1      | 9.09%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1         | 1      | 9.09%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1         | 1      | 9.09%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 9.09%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 9.09%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 9.09%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 9.09%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 9.09%   |
| Hitachi HTS54323 320GB                         | 1         | 1      | 9.09%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 36.36%  |
| Seagate             | 2         | 2      | 18.18%  |
| Samsung Electronics | 2         | 2      | 18.18%  |
| Ramsta              | 1         | 1      | 9.09%   |
| Micron Technology   | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 4         | 4      | 50%     |
| Seagate             | 2         | 2      | 25%     |
| Samsung Electronics | 1         | 1      | 12.5%   |
| Hitachi             | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 8      | 72.73%  |
| SSD  | 2         | 2      | 18.18%  |
| NVMe | 1         | 1      | 9.09%   |

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
| Detected | 158       | 308    | 77.83%  |
| Works    | 34        | 68     | 16.75%  |
| Malfunc  | 10        | 11     | 4.93%   |
| Limited  | 1         | 1      | 0.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 107       | 38.21%  |
| AMD                            | 63        | 22.5%   |
| Samsung Electronics            | 34        | 12.14%  |
| SanDisk                        | 14        | 5%      |
| Phison Electronics             | 11        | 3.93%   |
| Kingston Technology Company    | 8         | 2.86%   |
| SK hynix                       | 6         | 2.14%   |
| ASMedia Technology             | 6         | 2.14%   |
| Micron/Crucial Technology      | 4         | 1.43%   |
| Micron Technology              | 4         | 1.43%   |
| Realtek Semiconductor          | 3         | 1.07%   |
| Nvidia                         | 3         | 1.07%   |
| Marvell Technology Group       | 3         | 1.07%   |
| KIOXIA                         | 3         | 1.07%   |
| Toshiba America Info Systems   | 2         | 0.71%   |
| JMicron Technology             | 2         | 0.71%   |
| ADATA Technology               | 2         | 0.71%   |
| Solid State Storage Technology | 1         | 0.36%   |
| Silicon Motion                 | 1         | 0.36%   |
| Silicon Image                  | 1         | 0.36%   |
| Shenzhen Longsys Electronics   | 1         | 0.36%   |
| Apple                          | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 46        | 14.7%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 4.79%   |
| AMD 400 Series Chipset SATA Controller                                         | 12        | 3.83%   |
| Samsung NVMe SSD Controller 980                                                | 11        | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 9         | 2.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 2.56%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 7         | 2.24%   |
| Intel SATA Controller [RAID mode]                                              | 6         | 1.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 1.92%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 6         | 1.92%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 6         | 1.92%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 6         | 1.92%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 1.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 1.6%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.6%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.28%   |
| Phison E12 NVMe Controller                                                     | 4         | 1.28%   |
| Micron Non-Volatile memory controller                                          | 4         | 1.28%   |
| Kingston Company A2000 NVMe SSD                                                | 4         | 1.28%   |
| Intel SSD 660P Series                                                          | 4         | 1.28%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 4         | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 1.28%   |
| AMD FCH SATA Controller D                                                      | 4         | 1.28%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 0.96%   |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 0.96%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.96%   |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.96%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 3         | 0.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 0.96%   |
| AMD 500 Series Chipset SATA Controller                                         | 3         | 0.96%   |
| AMD 300 Series Chipset SATA Controller                                         | 3         | 0.96%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 2         | 0.64%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.64%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 2         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 150       | 56.6%   |
| NVMe | 86        | 32.45%  |
| RAID | 17        | 6.42%   |
| IDE  | 12        | 4.53%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 112       | 59.89%  |
| AMD    | 75        | 40.11%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD FX-8350 Eight-Core Processor            | 5         | 2.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 4         | 2.14%   |
| AMD Ryzen 5 3600 6-Core Processor           | 4         | 2.14%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4         | 2.14%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 3         | 1.6%    |
| Intel Core i5-9400F CPU @ 2.90GHz           | 3         | 1.6%    |
| Intel Core i5-10300H CPU @ 2.50GHz          | 3         | 1.6%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 3         | 1.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 1.6%    |
| AMD Ryzen 5 4600H with Radeon Graphics      | 3         | 1.6%    |
| AMD FX-6300 Six-Core Processor              | 3         | 1.6%    |
| Intel Pentium CPU B960 @ 2.20GHz            | 2         | 1.07%   |
| Intel Core i9-9900K CPU @ 3.60GHz           | 2         | 1.07%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 2         | 1.07%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 1.07%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 2         | 1.07%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 2         | 1.07%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 2         | 1.07%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 2         | 1.07%   |
| Intel Core i3-3240 CPU @ 3.40GHz            | 2         | 1.07%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 2         | 1.07%   |
| Intel 12th Gen Core i7-12700H               | 2         | 1.07%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz     | 2         | 1.07%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 2         | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 1.07%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 2         | 1.07%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 2         | 1.07%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 2         | 1.07%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 2         | 1.07%   |
| Intel Xeon CPU W3530 @ 2.80GHz              | 1         | 0.53%   |
| Intel Xeon CPU E5-2667 0 @ 2.90GHz          | 1         | 0.53%   |
| Intel Xeon CPU E3-1240 V2 @ 3.40GHz         | 1         | 0.53%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.53%   |
| Intel Pentium CPU G640 @ 2.80GHz            | 1         | 0.53%   |
| Intel Core m7-6Y75 CPU @ 1.20GHz            | 1         | 0.53%   |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.53%   |
| Intel Core i7-8700T CPU @ 2.40GHz           | 1         | 0.53%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.53%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 1         | 0.53%   |
| Intel Core i7-7700 CPU @ 3.60GHz            | 1         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i7        | 38        | 20.32%  |
| Intel Core i5        | 29        | 15.51%  |
| AMD Ryzen 5          | 29        | 15.51%  |
| AMD Ryzen 7          | 17        | 9.09%   |
| Intel Core i3        | 13        | 6.95%   |
| Other                | 11        | 5.88%   |
| AMD Ryzen 9          | 9         | 4.81%   |
| AMD FX               | 8         | 4.28%   |
| Intel Celeron        | 5         | 2.67%   |
| Intel Pentium        | 4         | 2.14%   |
| Intel Core 2 Duo     | 4         | 2.14%   |
| Intel Xeon           | 3         | 1.6%    |
| AMD Ryzen 3          | 3         | 1.6%    |
| Intel Core i9        | 2         | 1.07%   |
| Intel Atom           | 2         | 1.07%   |
| AMD A6               | 2         | 1.07%   |
| Intel Core m7        | 1         | 0.53%   |
| Intel Core 2 Extreme | 1         | 0.53%   |
| AMD Phenom II X6     | 1         | 0.53%   |
| AMD Phenom II X4     | 1         | 0.53%   |
| AMD E                | 1         | 0.53%   |
| AMD Athlon X4        | 1         | 0.53%   |
| AMD Athlon Dual Core | 1         | 0.53%   |
| AMD A10              | 1         | 0.53%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 66        | 35.29%  |
| 2      | 45        | 24.06%  |
| 6      | 39        | 20.86%  |
| 8      | 24        | 12.83%  |
| 12     | 5         | 2.67%   |
| 3      | 3         | 1.6%    |
| 14     | 2         | 1.07%   |
| 16     | 1         | 0.53%   |
| 10     | 1         | 0.53%   |
| 1      | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 187       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 150       | 80.21%  |
| 1      | 37        | 19.79%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 187       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x306c3    | 12        | 6.38%   |
| 0x306a9    | 12        | 6.38%   |
| 0x08701021 | 11        | 5.85%   |
| 0x206a7    | 9         | 4.79%   |
| 0x0a50000c | 9         | 4.79%   |
| Unknown    | 9         | 4.79%   |
| 0x906ea    | 8         | 4.26%   |
| 0x906e9    | 7         | 3.72%   |
| 0x506e3    | 7         | 3.72%   |
| 0x06000822 | 7         | 3.72%   |
| 0x40651    | 6         | 3.19%   |
| 0x08108109 | 6         | 3.19%   |
| 0x0a201016 | 5         | 2.66%   |
| 0x0800820d | 5         | 2.66%   |
| 0x08001138 | 5         | 2.66%   |
| 0x806e9    | 4         | 2.13%   |
| 0xa0655    | 3         | 1.6%    |
| 0xa0652    | 3         | 1.6%    |
| 0x806c1    | 3         | 1.6%    |
| 0x30678    | 3         | 1.6%    |
| 0x1067a    | 3         | 1.6%    |
| 0x08608103 | 3         | 1.6%    |
| 0x08600106 | 3         | 1.6%    |
| 0x08600104 | 3         | 1.6%    |
| 0xa0653    | 2         | 1.06%   |
| 0x906ed    | 2         | 1.06%   |
| 0x906ec    | 2         | 1.06%   |
| 0x906a3    | 2         | 1.06%   |
| 0x806d1    | 2         | 1.06%   |
| 0x706e5    | 2         | 1.06%   |
| 0x10676    | 2         | 1.06%   |
| 0x0a50000d | 2         | 1.06%   |
| 0x0a201204 | 2         | 1.06%   |
| 0x08108102 | 2         | 1.06%   |
| 0x06003106 | 2         | 1.06%   |
| 0xa0671    | 1         | 0.53%   |
| 0x90672    | 1         | 0.53%   |
| 0x806ec    | 1         | 0.53%   |
| 0x806ea    | 1         | 0.53%   |
| 0x506c9    | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 26        | 13.9%   |
| Zen 3            | 19        | 10.16%  |
| Haswell          | 19        | 10.16%  |
| Zen 2            | 17        | 9.09%   |
| Zen+             | 13        | 6.95%   |
| IvyBridge        | 12        | 6.42%   |
| SandyBridge      | 11        | 5.88%   |
| Piledriver       | 9         | 4.81%   |
| CometLake        | 9         | 4.81%   |
| Skylake          | 8         | 4.28%   |
| Zen              | 6         | 3.21%   |
| Penryn           | 5         | 2.67%   |
| Icelake          | 5         | 2.67%   |
| Unknown          | 5         | 2.67%   |
| Silvermont       | 4         | 2.14%   |
| TigerLake        | 3         | 1.6%    |
| Alderlake Hybrid | 3         | 1.6%    |
| Steamroller      | 2         | 1.07%   |
| K10              | 2         | 1.07%   |
| Westmere         | 1         | 0.53%   |
| Puma             | 1         | 0.53%   |
| Nehalem          | 1         | 0.53%   |
| K8 Hammer        | 1         | 0.53%   |
| Goldmont plus    | 1         | 0.53%   |
| Goldmont         | 1         | 0.53%   |
| Broadwell        | 1         | 0.53%   |
| Bonnell          | 1         | 0.53%   |
| Bobcat           | 1         | 0.53%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 88        | 37.61%  |
| AMD    | 74        | 31.62%  |
| Intel  | 72        | 30.77%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 11        | 4.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 9         | 3.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 7         | 2.9%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 6         | 2.49%   |
| Intel HD Graphics 530                                                       | 5         | 2.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 5         | 2.07%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 5         | 2.07%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 5         | 2.07%   |
| AMD Renoir                                                                  | 5         | 2.07%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 4         | 1.66%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 4         | 1.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 4         | 1.66%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4         | 1.66%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                        | 4         | 1.66%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 4         | 1.66%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 3         | 1.24%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 3         | 1.24%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 3         | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 3         | 1.24%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 1.24%   |
| Intel HD Graphics 630                                                       | 3         | 1.24%   |
| Intel HD Graphics 620                                                       | 3         | 1.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 3         | 1.24%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3         | 1.24%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                | 3         | 1.24%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 3         | 1.24%   |
| AMD Lucienne                                                                | 3         | 1.24%   |
| Nvidia TU117M [GeForce MX450]                                               | 2         | 0.83%   |
| Nvidia TU117M                                                               | 2         | 0.83%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 2         | 0.83%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2         | 0.83%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                     | 2         | 0.83%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 2         | 0.83%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2         | 0.83%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 2         | 0.83%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 2         | 0.83%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 2         | 0.83%   |
| Nvidia GM107M [GeForce GTX 960M]                                            | 2         | 0.83%   |
| Nvidia GM107M [GeForce GTX 860M]                                            | 2         | 0.83%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 2         | 0.83%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x AMD        | 53        | 28.34%  |
| 1 x Nvidia     | 50        | 26.74%  |
| 1 x Intel      | 35        | 18.72%  |
| Intel + Nvidia | 26        | 13.9%   |
| AMD + Nvidia   | 10        | 5.35%   |
| Intel + AMD    | 6         | 3.21%   |
| 2 x AMD        | 5         | 2.67%   |
| 2 x Nvidia     | 2         | 1.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 117       | 62.23%  |
| Proprietary | 70        | 37.23%  |
| Unknown     | 1         | 0.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 43.68%  |
| 1.01-2.0   | 23        | 12.11%  |
| 7.01-8.0   | 21        | 11.05%  |
| 0.01-0.5   | 21        | 11.05%  |
| 3.01-4.0   | 16        | 8.42%   |
| 0.51-1.0   | 11        | 5.79%   |
| 8.01-16.0  | 9         | 4.74%   |
| 5.01-6.0   | 4         | 2.11%   |
| 2.01-3.0   | 1         | 0.53%   |
| 16.01-24.0 | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 25        | 12.32%  |
| AU Optronics            | 22        | 10.84%  |
| Goldstar                | 15        | 7.39%   |
| BOE                     | 13        | 6.4%    |
| LG Display              | 10        | 4.93%   |
| Chimei Innolux          | 10        | 4.93%   |
| Dell                    | 9         | 4.43%   |
| Acer                    | 9         | 4.43%   |
| PANDA                   | 7         | 3.45%   |
| Vizio                   | 6         | 2.96%   |
| Hewlett-Packard         | 6         | 2.96%   |
| Apple                   | 6         | 2.96%   |
| AOC                     | 6         | 2.96%   |
| Ancor Communications    | 6         | 2.96%   |
| Sony                    | 5         | 2.46%   |
| Sharp                   | 5         | 2.46%   |
| BenQ                    | 5         | 2.46%   |
| ASUSTek Computer        | 5         | 2.46%   |
| Philips                 | 4         | 1.97%   |
| MSI                     | 4         | 1.97%   |
| Lenovo                  | 4         | 1.97%   |
| ViewSonic               | 3         | 1.48%   |
| Sceptre Tech            | 2         | 0.99%   |
| InfoVision              | 2         | 0.99%   |
| ___                     | 1         | 0.49%   |
| Valve                   | 1         | 0.49%   |
| Unknown                 | 1         | 0.49%   |
| Toshiba                 | 1         | 0.49%   |
| SNC                     | 1         | 0.49%   |
| SFX                     | 1         | 0.49%   |
| NPC                     | 1         | 0.49%   |
| MStar                   | 1         | 0.49%   |
| MLT                     | 1         | 0.49%   |
| HUAWEI                  | 1         | 0.49%   |
| Hitachi                 | 1         | 0.49%   |
| Gigabyte Technology     | 1         | 0.49%   |
| GDH                     | 1         | 0.49%   |
| Chi Mei Optoelectronics | 1         | 0.49%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.94%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 2         | 0.94%   |
| Lenovo LT2252p Wide LEN0A0C 1680x1050 474x296mm 22.0-inch            | 2         | 0.94%   |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch             | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 2         | 0.94%   |
| ASUSTek Computer PA278QV AUS2700 2560x1440 597x336mm 27.0-inch       | 2         | 0.94%   |
| ___ LCD TV ___9000 1360x768                                          | 1         | 0.47%   |
| Vizio VX42L HDTV10A VIZ0030 1280x720 930x523mm 42.0-inch             | 1         | 0.47%   |
| Vizio V585x-H1 VIZ1039 3840x2160 941x529mm 42.5-inch                 | 1         | 0.47%   |
| Vizio E500i-A0 VIZ0092 1920x1080 1096x616mm 49.5-inch                | 1         | 0.47%   |
| Vizio E50-C1 VIZ1004 1920x1080 1095x616mm 49.5-inch                  | 1         | 0.47%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                 | 1         | 0.47%   |
| Vizio D24h-G9 VIZ1028 1366x768 521x293mm 23.5-inch                   | 1         | 0.47%   |
| ViewSonic VX3218-PC-mhd VSCEB3A 1920x1080 609x348mm 27.6-inch        | 1         | 0.47%   |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 597x336mm 27.0-inch           | 1         | 0.47%   |
| ViewSonic LCD Monitor VSCBB31 1920x1080 530x300mm 24.0-inch          | 1         | 0.47%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.47%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                     | 1         | 0.47%   |
| Toshiba LCD-MONITOR LCDE980 1440x900 408x255mm 18.9-inch             | 1         | 0.47%   |
| Sony TV SNYEB01 1360x768                                             | 1         | 0.47%   |
| Sony TV SNY8F03 1360x768                                             | 1         | 0.47%   |
| Sony TV SNY1B02 1360x768                                             | 1         | 0.47%   |
| Sony TV *02 SNY9403 1920x1080 1218x685mm 55.0-inch                   | 1         | 0.47%   |
| Sony TV *00 SNYF303 1920x1080 1218x685mm 55.0-inch                   | 1         | 0.47%   |
| SNC SKP_E20-32 SNC3200 1920x1080 477x268mm 21.5-inch                 | 1         | 0.47%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch              | 1         | 0.47%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch              | 1         | 0.47%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch              | 1         | 0.47%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.47%   |
| Sharp LCD Monitor SHP143D 3840x2160 276x156mm 12.5-inch              | 1         | 0.47%   |
| SFX HDMI2.0 KVM SFX0100 1920x1080 708x398mm 32.0-inch                | 1         | 0.47%   |
| Sceptre Tech Sceptre Y40 SPT0FCD 2560x1440 852x480mm 38.5-inch       | 1         | 0.47%   |
| Sceptre Tech Sceptre P30 SPT0BCC 2560x1080 690x291mm 29.5-inch       | 1         | 0.47%   |
| Sceptre Tech Sceptre M27 SPT0ACD 1920x1080 598x336mm 27.0-inch       | 1         | 0.47%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch    | 1         | 0.47%   |
| Samsung Electronics U28D590 SAM0B80 3840x2160 607x345mm 27.5-inch    | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0422 1920x1200 518x324mm 24.1-inch | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM0168 1280x1024 338x270mm 17.0-inch | 1         | 0.47%   |
| Samsung Electronics SMB2030N SAM0634 1600x900 443x249mm 20.0-inch    | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 96        | 48.48%  |
| 3840x2160 (4K)     | 23        | 11.62%  |
| 1366x768 (WXGA)    | 22        | 11.11%  |
| 2560x1440 (QHD)    | 18        | 9.09%   |
| 1440x900 (WXGA+)   | 6         | 3.03%   |
| 1680x1050 (WSXGA+) | 5         | 2.53%   |
| 2880x1800          | 4         | 2.02%   |
| 2560x1080          | 4         | 2.02%   |
| 1360x768           | 4         | 2.02%   |
| 1920x1200 (WUXGA)  | 3         | 1.52%   |
| 1600x900 (HD+)     | 3         | 1.52%   |
| 3440x1440          | 2         | 1.01%   |
| 800x1280           | 1         | 0.51%   |
| 3840x2560          | 1         | 0.51%   |
| 3840x1600          | 1         | 0.51%   |
| 3200x1800 (QHD+)   | 1         | 0.51%   |
| 2560x1600          | 1         | 0.51%   |
| 2520x1680          | 1         | 0.51%   |
| 1280x800 (WXGA)    | 1         | 0.51%   |
| 1280x1024 (SXGA)   | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 53        | 25.48%  |
| 27      | 25        | 12.02%  |
| 23      | 16        | 7.69%   |
| 21      | 14        | 6.73%   |
| 31      | 12        | 5.77%   |
| 24      | 10        | 4.81%   |
| 17      | 10        | 4.81%   |
| 13      | 8         | 3.85%   |
| 14      | 7         | 3.37%   |
| 72      | 4         | 1.92%   |
| 34      | 4         | 1.92%   |
| 19      | 4         | 1.92%   |
| 84      | 3         | 1.44%   |
| 22      | 3         | 1.44%   |
| 20      | 3         | 1.44%   |
| 52      | 2         | 0.96%   |
| 42      | 2         | 0.96%   |
| 38      | 2         | 0.96%   |
| 28      | 2         | 0.96%   |
| 26      | 2         | 0.96%   |
| 18      | 2         | 0.96%   |
| 16      | 2         | 0.96%   |
| 12      | 2         | 0.96%   |
| Unknown | 2         | 0.96%   |
| 75      | 1         | 0.48%   |
| 69      | 1         | 0.48%   |
| 60      | 1         | 0.48%   |
| 58      | 1         | 0.48%   |
| 55      | 1         | 0.48%   |
| 54      | 1         | 0.48%   |
| 49      | 1         | 0.48%   |
| 48      | 1         | 0.48%   |
| 37      | 1         | 0.48%   |
| 33      | 1         | 0.48%   |
| 32      | 1         | 0.48%   |
| 29      | 1         | 0.48%   |
| 10      | 1         | 0.48%   |
| 7       | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 33.5%   |
| 501-600     | 47        | 23.15%  |
| 401-500     | 26        | 12.81%  |
| 601-700     | 16        | 7.88%   |
| 351-400     | 9         | 4.43%   |
| 1501-2000   | 9         | 4.43%   |
| 1001-1500   | 8         | 3.94%   |
| 701-800     | 6         | 2.96%   |
| 201-300     | 6         | 2.96%   |
| 801-900     | 3         | 1.48%   |
| 901-1000    | 2         | 0.99%   |
| Unknown     | 2         | 0.99%   |
| 1-100       | 1         | 0.49%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 146       | 82.49%  |
| 16/10 | 20        | 11.3%   |
| 21/9  | 7         | 3.95%   |
| 3/2   | 2         | 1.13%   |
| 5/4   | 1         | 0.56%   |
| 0.67  | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 25.73%  |
| 201-250        | 35        | 16.99%  |
| 301-350        | 26        | 12.62%  |
| 351-500        | 19        | 9.22%   |
| More than 1000 | 17        | 8.25%   |
| 81-90          | 14        | 6.8%    |
| 151-200        | 12        | 5.83%   |
| 121-130        | 7         | 3.4%    |
| 251-300        | 5         | 2.43%   |
| 501-1000       | 5         | 2.43%   |
| 61-70          | 2         | 0.97%   |
| 141-150        | 2         | 0.97%   |
| 131-140        | 2         | 0.97%   |
| 111-120        | 2         | 0.97%   |
| Unknown        | 2         | 0.97%   |
| 71-80          | 1         | 0.49%   |
| 41-50          | 1         | 0.49%   |
| 1-40           | 1         | 0.49%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 69        | 34.67%  |
| 121-160       | 52        | 26.13%  |
| 101-120       | 46        | 23.12%  |
| 1-50          | 14        | 7.04%   |
| 161-240       | 9         | 4.52%   |
| More than 240 | 7         | 3.52%   |
| Unknown       | 2         | 1.01%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 141       | 75.4%   |
| 2     | 34        | 18.18%  |
| 0     | 7         | 3.74%   |
| 3     | 4         | 2.14%   |
| 4     | 1         | 0.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 113       | 39.51%  |
| Intel                           | 89        | 31.12%  |
| Qualcomm Atheros                | 25        | 8.74%   |
| Broadcom                        | 14        | 4.9%    |
| MediaTek                        | 9         | 3.15%   |
| TP-Link                         | 8         | 2.8%    |
| Broadcom Limited                | 4         | 1.4%    |
| ASIX Electronics                | 3         | 1.05%   |
| Xiaomi                          | 2         | 0.7%    |
| Ralink                          | 2         | 0.7%    |
| Qualcomm                        | 2         | 0.7%    |
| Microsoft                       | 2         | 0.7%    |
| ASUSTek Computer                | 2         | 0.7%    |
| Wacom                           | 1         | 0.35%   |
| T & A Mobile Phones             | 1         | 0.35%   |
| Ralink Technology               | 1         | 0.35%   |
| Qualcomm Atheros Communications | 1         | 0.35%   |
| Nvidia                          | 1         | 0.35%   |
| Linksys                         | 1         | 0.35%   |
| ICS Advent                      | 1         | 0.35%   |
| Holtek Semiconductor            | 1         | 0.35%   |
| Google                          | 1         | 0.35%   |
| D-Link                          | 1         | 0.35%   |
| Afatech                         | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 26.67%  |
| Intel Wi-Fi 6 AX200                                               | 21        | 6.36%   |
| Intel I211 Gigabit Network Connection                             | 10        | 3.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 7         | 2.12%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.52%   |
| Intel Wireless 7260                                               | 5         | 1.52%   |
| Intel Ethernet Controller I225-V                                  | 5         | 1.52%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 1.21%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 1.21%   |
| Intel Wireless 8260                                               | 4         | 1.21%   |
| Intel Wireless 7265                                               | 4         | 1.21%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.21%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 1.21%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.21%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.21%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 0.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.91%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.91%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 3         | 0.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.91%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.91%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 0.91%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 2         | 0.61%   |
| TP-Link 802.11ac NIC                                              | 2         | 0.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.61%   |
| Realtek 802.11n                                                   | 2         | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.61%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 0.61%   |
| Intel Wireless-AC 9260                                            | 2         | 0.61%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.61%   |
| Intel Wireless 3160                                               | 2         | 0.61%   |
| Intel WiFi Link 5100                                              | 2         | 0.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 2         | 0.61%   |
| Intel Wi-Fi 6 AX201                                               | 2         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 43.62%  |
| Realtek Semiconductor           | 29        | 19.46%  |
| Qualcomm Atheros                | 15        | 10.07%  |
| Broadcom                        | 11        | 7.38%   |
| MediaTek                        | 9         | 6.04%   |
| TP-Link                         | 7         | 4.7%    |
| Ralink                          | 2         | 1.34%   |
| Microsoft                       | 2         | 1.34%   |
| Broadcom Limited                | 2         | 1.34%   |
| ASUSTek Computer                | 2         | 1.34%   |
| Wacom                           | 1         | 0.67%   |
| Ralink Technology               | 1         | 0.67%   |
| Qualcomm Atheros Communications | 1         | 0.67%   |
| Linksys                         | 1         | 0.67%   |
| D-Link                          | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 21        | 14.09%  |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 7         | 4.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 6         | 4.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 5         | 3.36%   |
| Intel Wireless 7260                                           | 5         | 3.36%   |
| Intel Wireless 8260                                           | 4         | 2.68%   |
| Intel Wireless 7265                                           | 4         | 2.68%   |
| Intel Comet Lake PCH CNVi WiFi                                | 4         | 2.68%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 4         | 2.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 3         | 2.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 3         | 2.01%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 3         | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 3         | 2.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 3         | 2.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 2.01%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 3         | 2.01%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 3         | 2.01%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2         | 1.34%   |
| TP-Link 802.11ac NIC                                          | 2         | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 2         | 1.34%   |
| Realtek 802.11n                                               | 2         | 1.34%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 2         | 1.34%   |
| Intel Wireless-AC 9260                                        | 2         | 1.34%   |
| Intel Wireless 8265 / 8275                                    | 2         | 1.34%   |
| Intel Wireless 3160                                           | 2         | 1.34%   |
| Intel WiFi Link 5100                                          | 2         | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 2         | 1.34%   |
| Intel Wi-Fi 6 AX201                                           | 2         | 1.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 2         | 1.34%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 2         | 1.34%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 2         | 1.34%   |
| Wacom ACK-40401 [Wireless Accessory Kit]                      | 1         | 0.67%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 1         | 0.67%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1         | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                  | 1         | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1         | 0.67%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter       | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 103       | 58.19%  |
| Intel                 | 43        | 24.29%  |
| Qualcomm Atheros      | 12        | 6.78%   |
| Broadcom              | 5         | 2.82%   |
| ASIX Electronics      | 3         | 1.69%   |
| Xiaomi                | 2         | 1.13%   |
| Qualcomm              | 2         | 1.13%   |
| Broadcom Limited      | 2         | 1.13%   |
| TP-Link               | 1         | 0.56%   |
| T & A Mobile Phones   | 1         | 0.56%   |
| Nvidia                | 1         | 0.56%   |
| ICS Advent            | 1         | 0.56%   |
| Google                | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 88        | 49.16%  |
| Intel I211 Gigabit Network Connection                             | 10        | 5.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 8         | 4.47%   |
| Intel Ethernet Controller I225-V                                  | 5         | 2.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 2.23%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 2.23%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 2.23%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.12%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.12%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.12%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.12%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.12%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.12%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.12%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.56%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.56%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1         | 0.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 1         | 0.56%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.56%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.56%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.56%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.56%   |
| Qualcomm Redmi Note 8                                             | 1         | 0.56%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.56%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.56%   |
| Qualcomm Android                                                  | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.56%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.56%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1         | 0.56%   |
| ICS Advent 10/100M LAN                                            | 1         | 0.56%   |
| Google Pixel 7                                                    | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 167       | 53.53%  |
| WiFi     | 143       | 45.83%  |
| Unknown  | 2         | 0.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 51.53%  |
| Ethernet | 95        | 48.47%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 101       | 54.01%  |
| 1     | 84        | 44.92%  |
| 3     | 1         | 0.53%   |
| 0     | 1         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 128       | 67.37%  |
| Yes  | 62        | 32.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 49.59%  |
| Realtek Semiconductor           | 12        | 9.76%   |
| Cambridge Silicon Radio         | 9         | 7.32%   |
| IMC Networks                    | 7         | 5.69%   |
| Foxconn / Hon Hai               | 6         | 4.88%   |
| Qualcomm Atheros Communications | 5         | 4.07%   |
| Lite-On Technology              | 5         | 4.07%   |
| Broadcom                        | 4         | 3.25%   |
| Apple                           | 4         | 3.25%   |
| MediaTek                        | 2         | 1.63%   |
| ASUSTek Computer                | 2         | 1.63%   |
| TP-Link                         | 1         | 0.81%   |
| Toshiba                         | 1         | 0.81%   |
| Realtek                         | 1         | 0.81%   |
| Ralink                          | 1         | 0.81%   |
| Dell                            | 1         | 0.81%   |
| Unknown                         | 1         | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 21        | 17.07%  |
| Intel AX200 Bluetooth                               | 21        | 17.07%  |
| Realtek Bluetooth Radio                             | 11        | 8.94%   |
| Intel AX201 Bluetooth                               | 10        | 8.13%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 9         | 7.32%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 3.25%   |
| IMC Networks Wireless_Device                        | 3         | 2.44%   |
| IMC Networks Bluetooth Radio                        | 3         | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 1.63%   |
| MediaTek Wireless_Device                            | 2         | 1.63%   |
| Lite-On Bluetooth Device                            | 2         | 1.63%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.63%   |
| Intel AX210 Bluetooth                               | 2         | 1.63%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.63%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 2         | 1.63%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.63%   |
| ASUS ASUS USB-BT500                                 | 2         | 1.63%   |
| Apple Bluetooth Host Controller                     | 2         | 1.63%   |
| TP-Link UB500 Adapter                               | 1         | 0.81%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.81%   |
| Realtek  Bluetooth 4.2 Adapter                      | 1         | 0.81%   |
| Realtek Bluetooth Radio                             | 1         | 0.81%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.81%   |
| Qualcomm Atheros  Bluetooth Device                  | 1         | 0.81%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.81%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.81%   |
| Lite-On Wireless_Device                             | 1         | 0.81%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.81%   |
| Lite-On Bluetooth Radio                             | 1         | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.81%   |
| IMC Networks Bluetooth Device                       | 1         | 0.81%   |
| Foxconn / Hon Hai BT                                | 1         | 0.81%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.81%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.81%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.81%   |
| Broadcom Bluetooth Device                           | 1         | 0.81%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1         | 0.81%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.81%   |
| Unknown                                             | 1         | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 109       | 33.96%  |
| AMD                      | 92        | 28.66%  |
| Nvidia                   | 70        | 21.81%  |
| C-Media Electronics      | 10        | 3.12%   |
| Razer USA                | 4         | 1.25%   |
| Plantronics              | 3         | 0.93%   |
| Logitech                 | 3         | 0.93%   |
| JMTek                    | 3         | 0.93%   |
| SteelSeries ApS          | 2         | 0.62%   |
| Samson Technologies      | 2         | 0.62%   |
| Kingston Technology      | 2         | 0.62%   |
| Generalplus Technology   | 2         | 0.62%   |
| Focusrite-Novation       | 2         | 0.62%   |
| Creative Technology      | 2         | 0.62%   |
| Creative Labs            | 2         | 0.62%   |
| Blue Microphones         | 2         | 0.62%   |
| Sony                     | 1         | 0.31%   |
| ROCCAT                   | 1         | 0.31%   |
| Realtek Semiconductor    | 1         | 0.31%   |
| Positive Grid            | 1         | 0.31%   |
| Micro Star International | 1         | 0.31%   |
| Giga-Byte Technology     | 1         | 0.31%   |
| Elgato Systems           | 1         | 0.31%   |
| Corsair                  | 1         | 0.31%   |
| Audio-Technica           | 1         | 0.31%   |
| ASUSTek Computer         | 1         | 0.31%   |
| Asahi Kasei Microsystems | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 28        | 7.2%    |
| AMD Starship/Matisse HD Audio Controller                                   | 19        | 4.88%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 17        | 4.37%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 12        | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 2.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 11        | 2.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 2.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 2.57%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 2.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 2.31%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 2.31%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 1.8%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.8%    |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 1.54%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.54%   |
| Nvidia GA106 High Definition Audio Controller                              | 6         | 1.54%   |
| Intel Sunrise Point-LP HD Audio                                            | 6         | 1.54%   |
| Intel 8 Series HD Audio Controller                                         | 6         | 1.54%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 1.29%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.29%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.29%   |
| AMD FCH Azalia Controller                                                  | 5         | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.03%   |
| Nvidia GP104 High Definition Audio Controller                              | 4         | 1.03%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.03%   |
| C-Media Electronics USB Audio Device                                       | 4         | 1.03%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 4         | 1.03%   |
| AMD Navi 10 HDMI Audio                                                     | 4         | 1.03%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 4         | 1.03%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 0.77%   |
| JMTek USB PnP Audio Device                                                 | 3         | 0.77%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 3         | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.77%   |
| Intel Audio device                                                         | 3         | 0.77%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 0.77%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 3         | 0.77%   |
| Intel 200 Series PCH HD Audio                                              | 3         | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 14        | 29.17%  |
| SK hynix            | 7         | 14.58%  |
| Micron Technology   | 5         | 10.42%  |
| Corsair             | 5         | 10.42%  |
| Kingston            | 4         | 8.33%   |
| G.Skill             | 3         | 6.25%   |
| Unknown             | 2         | 4.17%   |
| Crucial             | 2         | 4.17%   |
| Unknown (ABCD)      | 1         | 2.08%   |
| Transcend           | 1         | 2.08%   |
| Team                | 1         | 2.08%   |
| Ramaxel Technology  | 1         | 2.08%   |
| Nanya Technology    | 1         | 2.08%   |
| Asgard              | 1         | 2.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 3.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.92%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 3.92%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 3.92%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 3.92%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.96%   |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s           | 1         | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.96%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 1.96%   |
| Team RAM TEAMGROUP-UD3 8GB DIMM DDR3 1600MT/s                    | 1         | 1.96%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.96%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.96%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.96%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.96%   |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Samsung RAM M471A5143EB0-CPB 4096MB SODIMM DDR4 2133MT/s         | 1         | 1.96%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.96%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 1         | 1.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.96%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR2 975MT/s            | 1         | 1.96%   |
| Samsung RAM M3 78T2863QZS-CF7 1GB DIMM DDR2 800MT/s              | 1         | 1.96%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 1.96%   |
| Ramaxel RAM RMR5030ED58E8W1600 2GB DIMM DDR3 1600MT/s            | 1         | 1.96%   |
| Nanya RAM M2S4G64CB8HG4N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.96%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 1.96%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8192MB SODIMM DDR4 2400MT/s          | 1         | 1.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.96%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 1.96%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s          | 1         | 1.96%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3200MT/s            | 1         | 1.96%   |
| Kingston RAM ACR16D3LS1KNG/8G 8GB DIMM DDR3 1600MT/s             | 1         | 1.96%   |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s             | 1         | 1.96%   |
| G.Skill RAM F4-3600C14-8GTZNB 8GB DIMM DDR4 3600MT/s             | 1         | 1.96%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 1         | 1.96%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s            | 1         | 1.96%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 26        | 66.67%  |
| DDR3   | 9         | 23.08%  |
| LPDDR4 | 2         | 5.13%   |
| SDRAM  | 1         | 2.56%   |
| DDR2   | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 48.78%  |
| DIMM         | 17        | 41.46%  |
| Row Of Chips | 4         | 9.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 26        | 59.09%  |
| 4096  | 6         | 13.64%  |
| 16384 | 5         | 11.36%  |
| 2048  | 4         | 9.09%   |
| 32768 | 2         | 4.55%   |
| 1024  | 1         | 2.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 12        | 27.91%  |
| 1600  | 7         | 16.28%  |
| 2400  | 5         | 11.63%  |
| 3600  | 4         | 9.3%    |
| 2667  | 4         | 9.3%    |
| 2133  | 2         | 4.65%   |
| 4266  | 1         | 2.33%   |
| 3866  | 1         | 2.33%   |
| 3800  | 1         | 2.33%   |
| 3466  | 1         | 2.33%   |
| 2933  | 1         | 2.33%   |
| 1333  | 1         | 2.33%   |
| 1066  | 1         | 2.33%   |
| 975   | 1         | 2.33%   |
| 800   | 1         | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model               | Computers | Percent |
|---------------------|-----------|---------|
| Canon TR4500 series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 14        | 14.14%  |
| IMC Networks                           | 13        | 13.13%  |
| Logitech                               | 11        | 11.11%  |
| Microdia                               | 7         | 7.07%   |
| Apple                                  | 7         | 7.07%   |
| Acer                                   | 7         | 7.07%   |
| Realtek Semiconductor                  | 6         | 6.06%   |
| Syntek                                 | 4         | 4.04%   |
| Sunplus Innovation Technology          | 4         | 4.04%   |
| Quanta                                 | 4         | 4.04%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.03%   |
| Suyin                                  | 2         | 2.02%   |
| Sonix Technology                       | 2         | 2.02%   |
| Samsung Electronics                    | 2         | 2.02%   |
| Microsoft                              | 2         | 2.02%   |
| Hewlett-Packard                        | 2         | 2.02%   |
| Tobii Technology AB                    | 1         | 1.01%   |
| SunplusIT                              | 1         | 1.01%   |
| Luxvisions Innotech Limited            | 1         | 1.01%   |
| Lite-On Technology                     | 1         | 1.01%   |
| Lenovo                                 | 1         | 1.01%   |
| Intel                                  | 1         | 1.01%   |
| Importek                               | 1         | 1.01%   |
| Goodong Industry                       | 1         | 1.01%   |
| DJKANA19IDX53W                         | 1         | 1.01%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 7         | 7%      |
| Syntek Integrated Camera                            | 3         | 3%      |
| Realtek USB Camera                                  | 3         | 3%      |
| Microdia Integrated_Webcam_HD                       | 3         | 3%      |
| Logitech Webcam C270                                | 3         | 3%      |
| Logitech C922 Pro Stream Webcam                     | 3         | 3%      |
| Chicony Integrated Camera                           | 3         | 3%      |
| Apple iPhone 5/5C/5S/6/SE                           | 3         | 3%      |
| Acer Integrated Camera                              | 3         | 3%      |
| Sunplus Integrated_Webcam_HD                        | 2         | 2%      |
| Sonix USB2.0 HD UVC WebCam                          | 2         | 2%      |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 2%      |
| Realtek Integrated_Webcam_HD                        | 2         | 2%      |
| Microdia Integrated Camera                          | 2         | 2%      |
| Logitech HD Pro Webcam C920                         | 2         | 2%      |
| IMC Networks Integrated Camera                      | 2         | 2%      |
| Chicony USB 2.0 Camera                              | 2         | 2%      |
| Acer Lenovo Integrated Webcam                       | 2         | 2%      |
| Acer HD Webcam                                      | 2         | 2%      |
| Tobii AB EyeChip                                    | 1         | 1%      |
| Syntek EasyCamera                                   | 1         | 1%      |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 1%      |
| Suyin HP TrueVision Full HD                         | 1         | 1%      |
| SunplusIT MTD camera                                | 1         | 1%      |
| Sunplus HD WebCam                                   | 1         | 1%      |
| Sunplus Asus Webcam                                 | 1         | 1%      |
| Realtek HP Truevision HD integrated webcam          | 1         | 1%      |
| Quanta VGA WebCam                                   | 1         | 1%      |
| Quanta USB2.0 VGA UVC WebCam                        | 1         | 1%      |
| Quanta USB HD Webcam                                | 1         | 1%      |
| Quanta HD Webcam                                    | 1         | 1%      |
| Microsoft Xbox NUI Camera                           | 1         | 1%      |
| Microsoft LifeCam Cinema                            | 1         | 1%      |
| Microdia Lenovo EasyCamera                          | 1         | 1%      |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 1%      |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1%      |
| Logitech StreamCam                                  | 1         | 1%      |
| Logitech QuickCam Pro 9000                          | 1         | 1%      |
| Logitech QuickCam Communicate MP/S5500              | 1         | 1%      |
| Lite-On HP HD Webcam                                | 1         | 1%      |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 4         | 30.77%  |
| Synaptics                  | 4         | 30.77%  |
| Shenzhen Goodix Technology | 3         | 23.08%  |
| Elan Microelectronics      | 2         | 15.38%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                 | 3         | 23.08%  |
| Shenzhen Goodix  Fingerprint Device                        | 3         | 23.08%  |
| Validity Sensors VFS 5011 fingerprint sensor               | 1         | 7.69%   |
| Synaptics WBDI Device                                      | 1         | 7.69%   |
| Synaptics  WBDI                                            | 1         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 7.69%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 1         | 7.69%   |
| Elan ELAN:Fingerprint                                      | 1         | 7.69%   |
| Elan ELAN:ARM-M4                                           | 1         | 7.69%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 50%     |
| Broadcom              | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 50%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 146       | 77.25%  |
| 1     | 35        | 18.52%  |
| 2     | 8         | 4.23%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 13        | 25.49%  |
| Graphics card            | 12        | 23.53%  |
| Net/wireless             | 11        | 21.57%  |
| Multimedia controller    | 9         | 17.65%  |
| Bluetooth                | 2         | 3.92%   |
| Sound                    | 1         | 1.96%   |
| Modem                    | 1         | 1.96%   |
| Communication controller | 1         | 1.96%   |
| Chipcard                 | 1         | 1.96%   |

