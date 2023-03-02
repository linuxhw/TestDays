Nobara - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 186

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 330-15ICH 81FK      | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| Sony          | SVF1521N6EW                 | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Dell          | G3 3590                     | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | ENVY 15                     | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| HP            | EliteBook Revolve 810 G1    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| Dell          | Inspiron 5555               | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| Acer          | TravelMate P256-M           | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | K52Jc                       | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | Katana GF76 11UD            | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| Apple         | MacBook5,1                  | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| Medion        | GUARDIAN X10                | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | EliteBook 8570p             | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dynabook      | PORTEGE X30L-K              | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| Lenovo        | Z50-70 20354                | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| HP            | Laptop 14-cm1xxx            | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Coradir       | Coradir/ES10IS5             | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Dell          | Studio 1737                 | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Acer          | Swift SFX14-41G             | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASUSTek       | GL753VD                     | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| ASUSTek       | GL502VMK                    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Toshiba       | Satellite L850              | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP            | 2000                        | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| Apple         | MacBookPro5,5               | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| HP            | 2000                        | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| Acer          | Aspire VX5-591G             | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Dell          | Inspiron 3542               | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| Gateway       | NE56R                       | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Alienware     | Area-51m R2 A00             | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| ASUSTek       | TP500LA                     | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| Dell          | G15 5511                    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| Notebook      | P7xxDM2(-G)                 | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Apple         | MacBookPro14,2              | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| Razer         | Blade                       | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Nobara 36 | 108       | 73.47%  |
| Nobara 37 | 39        | 26.53%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Nobara | 146       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64        | 19        | 12.75%  |
| 5.19.14-201.fsync.fc36.x86_64 | 16        | 10.74%  |
| 6.1.4-203.fsync.fc37.x86_64   | 8         | 5.37%   |
| 6.1.9-200.fsync.fc37.x86_64   | 7         | 4.7%    |
| 5.19.9-201.fsync.fc36.x86_64  | 7         | 4.7%    |
| 5.19.7-204.fsync.fc36.x86_64  | 7         | 4.7%    |
| 6.0.7-201.fsync.fc36.x86_64   | 6         | 4.03%   |
| 6.1.11-201.fsync.fc37.x86_64  | 5         | 3.36%   |
| 6.0.5-201.fsync.fc36.x86_64   | 5         | 3.36%   |
| 6.0.16-301.fsync.fc37.x86_64  | 5         | 3.36%   |
| 6.0.14-201.fsync.fc36.x86_64  | 5         | 3.36%   |
| 5.19.12-201.fsync.fc36.x86_64 | 5         | 3.36%   |
| 6.1.8-202.fsync.fc37.x86_64   | 4         | 2.68%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 2.68%   |
| 5.19.16-201.fsync.fc36.x86_64 | 4         | 2.68%   |
| 5.19.11-201.fsync.fc36.x86_64 | 4         | 2.68%   |
| 6.1.6-203.fsync.fc37.x86_64   | 3         | 2.01%   |
| 6.0.9-202.fc36.x86_64         | 3         | 2.01%   |
| 6.0.9-201.fc36.x86_64         | 3         | 2.01%   |
| 5.18.16-201.fsync.fc36.x86_64 | 3         | 2.01%   |
| 5.18.13-201.fsync.fc36.x86_64 | 3         | 2.01%   |
| 6.1.6-202.fsync.fc37.x86_64   | 2         | 1.34%   |
| 6.1.6-201.fsync.fc37.x86_64   | 2         | 1.34%   |
| 6.0.8-201.fsync.fc36.x86_64   | 2         | 1.34%   |
| 5.19.4-201.fsync.fc36.x86_64  | 2         | 1.34%   |
| 5.19.15-202.fsync.fc36.x86_64 | 2         | 1.34%   |
| 5.18.17-201.fsync.fc36.x86_64 | 2         | 1.34%   |
| 6.1.8-201.fsync.fc37.x86_64   | 1         | 0.67%   |
| 6.1.8-200.fsync.fc37.x86_64   | 1         | 0.67%   |
| 6.0.7-202.fsync.fc36.x86_64   | 1         | 0.67%   |
| 6.0.2-xm1.0.fc36.x86_64       | 1         | 0.67%   |
| 6.0.15-301.fsync.fc37.x86_64  | 1         | 0.67%   |
| 6.0.13-201.fsync.fc36.x86_64  | 1         | 0.67%   |
| 5.19.7-203.fsync.fc36.x86_64  | 1         | 0.67%   |
| 5.19.13-202.fsync.fc36.x86_64 | 1         | 0.67%   |
| 5.19.10-201.fsync.fc36.x86_64 | 1         | 0.67%   |
| 5.18.19-201.fsync.fc36.x86_64 | 1         | 0.67%   |
| 5.18.18-201.fsync.fc36.x86_64 | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.10  | 19        | 12.75%  |
| 5.19.14 | 16        | 10.74%  |
| 6.1.4   | 8         | 5.37%   |
| 5.19.7  | 8         | 5.37%   |
| 6.1.9   | 7         | 4.7%    |
| 6.1.6   | 7         | 4.7%    |
| 6.0.7   | 7         | 4.7%    |
| 5.19.9  | 7         | 4.7%    |
| 6.1.8   | 6         | 4.03%   |
| 6.0.9   | 6         | 4.03%   |
| 6.1.11  | 5         | 3.36%   |
| 6.0.5   | 5         | 3.36%   |
| 6.0.16  | 5         | 3.36%   |
| 6.0.14  | 5         | 3.36%   |
| 5.19.12 | 5         | 3.36%   |
| 5.19.8  | 4         | 2.68%   |
| 5.19.16 | 4         | 2.68%   |
| 5.19.11 | 4         | 2.68%   |
| 5.18.16 | 3         | 2.01%   |
| 5.18.13 | 3         | 2.01%   |
| 6.0.8   | 2         | 1.34%   |
| 5.19.4  | 2         | 1.34%   |
| 5.19.15 | 2         | 1.34%   |
| 5.18.17 | 2         | 1.34%   |
| 6.0.2   | 1         | 0.67%   |
| 6.0.15  | 1         | 0.67%   |
| 6.0.13  | 1         | 0.67%   |
| 5.19.13 | 1         | 0.67%   |
| 5.19.10 | 1         | 0.67%   |
| 5.18.19 | 1         | 0.67%   |
| 5.18.18 | 1         | 0.67%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19    | 54        | 36.24%  |
| 6.0     | 52        | 34.9%   |
| 6.1     | 33        | 22.15%  |
| 5.18    | 10        | 6.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 146       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 103       | 70.07%  |
| KDE5    | 40        | 27.21%  |
| Unknown | 4         | 2.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 115       | 77.7%   |
| X11     | 28        | 18.92%  |
| Unknown | 4         | 2.7%    |
| Tty     | 1         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 120       | 81.08%  |
| GDM     | 15        | 10.14%  |
| SDDM    | 12        | 8.11%   |
| LightDM | 1         | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 81        | 55.1%   |
| es_ES   | 7         | 4.76%   |
| pl_PL   | 6         | 4.08%   |
| en_GB   | 6         | 4.08%   |
| it_IT   | 4         | 2.72%   |
| es_MX   | 4         | 2.72%   |
| en_IN   | 4         | 2.72%   |
| pt_PT   | 3         | 2.04%   |
| pt_BR   | 3         | 2.04%   |
| es_AR   | 3         | 2.04%   |
| en_NZ   | 3         | 2.04%   |
| de_DE   | 3         | 2.04%   |
| ru_RU   | 2         | 1.36%   |
| en_CA   | 2         | 1.36%   |
| Unknown | 2         | 1.36%   |
| tr_TR   | 1         | 0.68%   |
| sv_SE   | 1         | 0.68%   |
| nb_NO   | 1         | 0.68%   |
| hu_HU   | 1         | 0.68%   |
| hr_HR   | 1         | 0.68%   |
| fr_FR   | 1         | 0.68%   |
| fi_FI   | 1         | 0.68%   |
| es_CR   | 1         | 0.68%   |
| es_CO   | 1         | 0.68%   |
| es_CL   | 1         | 0.68%   |
| en_ZA   | 1         | 0.68%   |
| en_IE   | 1         | 0.68%   |
| en_AU   | 1         | 0.68%   |
| de_AT   | 1         | 0.68%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 122       | 82.99%  |
| BIOS | 25        | 17.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 90        | 61.64%  |
| Ext4  | 55        | 37.67%  |
| Xfs   | 1         | 0.68%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 118       | 79.19%  |
| GPT     | 28        | 18.79%  |
| MBR     | 3         | 2.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 139       | 94.56%  |
| Yes       | 8         | 5.44%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 129       | 88.36%  |
| Yes       | 17        | 11.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 35        | 23.97%  |
| ASUSTek Computer    | 29        | 19.86%  |
| Hewlett-Packard     | 27        | 18.49%  |
| Dell                | 11        | 7.53%   |
| Apple               | 8         | 5.48%   |
| Acer                | 8         | 5.48%   |
| MSI                 | 5         | 3.42%   |
| Toshiba             | 3         | 2.05%   |
| Positivo            | 2         | 1.37%   |
| Notebook            | 2         | 1.37%   |
| Gigabyte Technology | 2         | 1.37%   |
| Valve               | 1         | 0.68%   |
| Sony                | 1         | 0.68%   |
| Samsung Electronics | 1         | 0.68%   |
| Razer               | 1         | 0.68%   |
| Monster             | 1         | 0.68%   |
| Medion              | 1         | 0.68%   |
| HUAWEI              | 1         | 0.68%   |
| Gateway             | 1         | 0.68%   |
| EVOO                | 1         | 0.68%   |
| Dynabook            | 1         | 0.68%   |
| Coradir             | 1         | 0.68%   |
| Casper              | 1         | 0.68%   |
| ASRock              | 1         | 0.68%   |
| Alienware           | 1         | 0.68%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                     | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Lenovo Legion 5 15ARH05 82B5                             | 2         | 1.37%   |
| Lenovo IdeaPad Y700-15ISK 80NV                           | 2         | 1.37%   |
| HP ZBook 15u G3                                          | 2         | 1.37%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                      | 2         | 1.37%   |
| Unknown                                                  | 2         | 1.37%   |
| Valve Jupiter                                            | 1         | 0.68%   |
| Toshiba TECRA A50-A                                      | 1         | 0.68%   |
| Toshiba Satellite L850                                   | 1         | 0.68%   |
| Toshiba Satellite L650                                   | 1         | 0.68%   |
| Sony SVF1521N6EW                                         | 1         | 0.68%   |
| Samsung R520/R522/R620                                   | 1         | 0.68%   |
| Razer Blade                                              | 1         | 0.68%   |
| Positivo N1250                                           | 1         | 0.68%   |
| Positivo N1240                                           | 1         | 0.68%   |
| Notebook P7xxDM2(-G)                                     | 1         | 0.68%   |
| Notebook NP5x_NP6x_NP7xHP                                | 1         | 0.68%   |
| MSI Pulse GL76 12UEK                                     | 1         | 0.68%   |
| MSI Katana GF76 11UD                                     | 1         | 0.68%   |
| MSI GT680R/GX680R/GT683R/GT683DXR/GT685R/GT687R/GX660DXR | 1         | 0.68%   |
| MSI GF63 Thin 10SC                                       | 1         | 0.68%   |
| MSI GE60 0NC/GE60 0ND                                    | 1         | 0.68%   |
| Monster ABRA A7 V12.1                                    | 1         | 0.68%   |
| Medion GUARDIAN X10                                      | 1         | 0.68%   |
| Lenovo Z50-70 20354                                      | 1         | 0.68%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 OD 82NK                    | 1         | 0.68%   |
| Lenovo V330-15IKB 81AX                                   | 1         | 0.68%   |
| Lenovo V14-IIL 82C4                                      | 1         | 0.68%   |
| Lenovo ThinkPad X240 20AMA0LTAU                          | 1         | 0.68%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK0047US              | 1         | 0.68%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWS0ME00               | 1         | 0.68%   |
| Lenovo ThinkPad T460 20FMS79000                          | 1         | 0.68%   |
| Lenovo ThinkPad P51 20HJS02H00                           | 1         | 0.68%   |
| Lenovo ThinkPad P14s Gen 1 20S4001NUS                    | 1         | 0.68%   |
| Lenovo ThinkPad P1 20MD0020US                            | 1         | 0.68%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW                     | 1         | 0.68%   |
| Lenovo ThinkBook 15 G3 ACL 21A4                          | 1         | 0.68%   |
| Lenovo Legion S7 15ACH6 82K8                             | 1         | 0.68%   |
| Lenovo Legion 5 Pro 16IAH7H 82RF                         | 1         | 0.68%   |
| Lenovo Legion 5 17ACH6H 82JY                             | 1         | 0.68%   |
| Lenovo Legion 5 15ACH6H 82JU                             | 1         | 0.68%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo IdeaPad       | 12        | 8.22%   |
| ASUS ROG             | 9         | 6.16%   |
| Lenovo ThinkPad      | 8         | 5.48%   |
| Lenovo Legion        | 6         | 4.11%   |
| HP EliteBook         | 6         | 4.11%   |
| ASUS VivoBook        | 6         | 4.11%   |
| HP Pavilion          | 5         | 3.42%   |
| HP ZBook             | 4         | 2.74%   |
| ASUS ASUS            | 4         | 2.74%   |
| Acer Aspire          | 4         | 2.74%   |
| Dell Precision       | 3         | 2.05%   |
| ASUS TUF             | 3         | 2.05%   |
| Toshiba Satellite    | 2         | 1.37%   |
| Lenovo G580          | 2         | 1.37%   |
| HP OMEN              | 2         | 1.37%   |
| HP Laptop            | 2         | 1.37%   |
| HP ENVY              | 2         | 1.37%   |
| Dell Inspiron        | 2         | 1.37%   |
| Dell G15             | 2         | 1.37%   |
| Apple MacBookPro8    | 2         | 1.37%   |
| Acer Swift           | 2         | 1.37%   |
| Unknown              | 2         | 1.37%   |
| Valve Jupiter        | 1         | 0.68%   |
| Toshiba TECRA        | 1         | 0.68%   |
| Sony SVF1521N6EW     | 1         | 0.68%   |
| Samsung R520         | 1         | 0.68%   |
| Razer Blade          | 1         | 0.68%   |
| Positivo N1250       | 1         | 0.68%   |
| Positivo N1240       | 1         | 0.68%   |
| Notebook P7xxDM2(-G) | 1         | 0.68%   |
| Notebook NP5x        | 1         | 0.68%   |
| MSI Pulse            | 1         | 0.68%   |
| MSI Katana           | 1         | 0.68%   |
| MSI GT680R           | 1         | 0.68%   |
| MSI GF63             | 1         | 0.68%   |
| MSI GE60             | 1         | 0.68%   |
| Monster ABRA         | 1         | 0.68%   |
| Medion GUARDIAN      | 1         | 0.68%   |
| Lenovo Z50-70        | 1         | 0.68%   |
| Lenovo Yoga          | 1         | 0.68%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 26        | 17.81%  |
| 2020 | 22        | 15.07%  |
| 2022 | 14        | 9.59%   |
| 2019 | 13        | 8.9%    |
| 2018 | 11        | 7.53%   |
| 2014 | 10        | 6.85%   |
| 2013 | 10        | 6.85%   |
| 2012 | 9         | 6.16%   |
| 2017 | 7         | 4.79%   |
| 2016 | 7         | 4.79%   |
| 2015 | 6         | 4.11%   |
| 2009 | 4         | 2.74%   |
| 2011 | 3         | 2.05%   |
| 2010 | 3         | 2.05%   |
| 2008 | 1         | 0.68%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 146       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 146       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 146       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 40        | 27.4%   |
| 8.01-16.0  | 36        | 24.66%  |
| 16.01-24.0 | 30        | 20.55%  |
| 3.01-4.0   | 20        | 13.7%   |
| 32.01-64.0 | 15        | 10.27%  |
| 24.01-32.0 | 4         | 2.74%   |
| 1.01-2.0   | 1         | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 66        | 44.59%  |
| 2.01-3.0  | 41        | 27.7%   |
| 3.01-4.0  | 31        | 20.95%  |
| 8.01-16.0 | 9         | 6.08%   |
| 1.01-2.0  | 1         | 0.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 72.6%   |
| 2      | 36        | 24.66%  |
| 3      | 4         | 2.74%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 115       | 78.77%  |
| Yes       | 31        | 21.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 80.82%  |
| No        | 28        | 19.18%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 143       | 97.95%  |
| No        | 3         | 2.05%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 128       | 87.67%  |
| No        | 18        | 12.33%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 43        | 29.45%  |
| Poland       | 11        | 7.53%   |
| Spain        | 7         | 4.79%   |
| Germany      | 7         | 4.79%   |
| India        | 6         | 4.11%   |
| Mexico       | 5         | 3.42%   |
| Italy        | 5         | 3.42%   |
| Brazil       | 5         | 3.42%   |
| UK           | 3         | 2.05%   |
| Romania      | 3         | 2.05%   |
| Portugal     | 3         | 2.05%   |
| New Zealand  | 3         | 2.05%   |
| Chile        | 3         | 2.05%   |
| Argentina    | 3         | 2.05%   |
| Vietnam      | 2         | 1.37%   |
| Sweden       | 2         | 1.37%   |
| Russia       | 2         | 1.37%   |
| Philippines  | 2         | 1.37%   |
| Indonesia    | 2         | 1.37%   |
| Egypt        | 2         | 1.37%   |
| Croatia      | 2         | 1.37%   |
| Colombia     | 2         | 1.37%   |
| Canada       | 2         | 1.37%   |
| Austria      | 2         | 1.37%   |
| Turkey       | 1         | 0.68%   |
| Taiwan       | 1         | 0.68%   |
| South Africa | 1         | 0.68%   |
| Serbia       | 1         | 0.68%   |
| Panama       | 1         | 0.68%   |
| Pakistan     | 1         | 0.68%   |
| Norway       | 1         | 0.68%   |
| Morocco      | 1         | 0.68%   |
| Kenya        | 1         | 0.68%   |
| Ireland      | 1         | 0.68%   |
| Hungary      | 1         | 0.68%   |
| France       | 1         | 0.68%   |
| Finland      | 1         | 0.68%   |
| Czechia      | 1         | 0.68%   |
| Cyprus       | 1         | 0.68%   |
| Costa Rica   | 1         | 0.68%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Wroclaw             | 3         | 2.01%   |
| Auckland            | 3         | 2.01%   |
| Wasilla             | 2         | 1.34%   |
| Warsaw              | 2         | 1.34%   |
| Schmalkalden        | 2         | 1.34%   |
| Poznan              | 2         | 1.34%   |
| Panama City         | 2         | 1.34%   |
| Ochsenfurt          | 2         | 1.34%   |
| Mumbai              | 2         | 1.34%   |
| Milan               | 2         | 1.34%   |
| Madrid              | 2         | 1.34%   |
| Guadalajara         | 2         | 1.34%   |
| Fortaleza           | 2         | 1.34%   |
| Bucharest           | 2         | 1.34%   |
| Zamora              | 1         | 0.67%   |
| Zadar               | 1         | 0.67%   |
| Wesley Chapel       | 1         | 0.67%   |
| Wayne               | 1         | 0.67%   |
| Wabrzezno           | 1         | 0.67%   |
| Vladivostok         | 1         | 0.67%   |
| Villarrica          | 1         | 0.67%   |
| Villa Nueva         | 1         | 0.67%   |
| Vienna              | 1         | 0.67%   |
| Veszprém           | 1         | 0.67%   |
| Varaždin           | 1         | 0.67%   |
| Valladolid          | 1         | 0.67%   |
| Vagos               | 1         | 0.67%   |
| Ulm                 | 1         | 0.67%   |
| Uhldingen-Muhlhofen | 1         | 0.67%   |
| Tulsa               | 1         | 0.67%   |
| Tomah               | 1         | 0.67%   |
| Tenna               | 1         | 0.67%   |
| Temuco              | 1         | 0.67%   |
| Tampa               | 1         | 0.67%   |
| Sunnyvale           | 1         | 0.67%   |
| Stockholm           | 1         | 0.67%   |
| Sosnowiec           | 1         | 0.67%   |
| Sofia               | 1         | 0.67%   |
| Slawa               | 1         | 0.67%   |
| Silves              | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 39        | 45     | 21.08%  |
| WDC                          | 13        | 14     | 7.03%   |
| Kingston                     | 13        | 13     | 7.03%   |
| Toshiba                      | 12        | 13     | 6.49%   |
| Seagate                      | 12        | 12     | 6.49%   |
| Sandisk                      | 12        | 12     | 6.49%   |
| Intel                        | 11        | 11     | 5.95%   |
| SK hynix                     | 10        | 10     | 5.41%   |
| Micron Technology            | 8         | 8      | 4.32%   |
| Crucial                      | 7         | 7      | 3.78%   |
| Phison Electronics           | 5         | 5      | 2.7%    |
| Micron/Crucial Technology    | 5         | 5      | 2.7%    |
| Hitachi                      | 4         | 5      | 2.16%   |
| HGST                         | 4         | 4      | 2.16%   |
| China                        | 4         | 4      | 2.16%   |
| Apple                        | 4         | 5      | 2.16%   |
| LITEON                       | 2         | 2      | 1.08%   |
| KIOXIA                       | 2         | 2      | 1.08%   |
| HS-SSD-C100                  | 2         | 2      | 1.08%   |
| Unknown                      | 2         | 2      | 1.08%   |
| Unknown                      | 1         | 1      | 0.54%   |
| Union Memory                 | 1         | 1      | 0.54%   |
| T-FORCE                      | 1         | 1      | 0.54%   |
| Solid State Storage          | 1         | 1      | 0.54%   |
| Silicon Motion               | 1         | 1      | 0.54%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.54%   |
| Ramsta                       | 1         | 1      | 0.54%   |
| PNY                          | 1         | 1      | 0.54%   |
| Mushkin                      | 1         | 1      | 0.54%   |
| HGST HTS                     | 1         | 1      | 0.54%   |
| Fujitsu                      | 1         | 1      | 0.54%   |
| Emtec                        | 1         | 1      | 0.54%   |
| ADATA Technology             | 1         | 1      | 0.54%   |
| A-DATA Technology            | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 7         | 3.65%   |
| Kingston SA400S37240G 240GB SSD                      | 5         | 2.6%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 4         | 2.08%   |
| SK hynix BC511 512GB                                 | 3         | 1.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 3         | 1.56%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 3         | 1.56%   |
| Samsung SSD 980 1TB                                  | 3         | 1.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 3         | 1.56%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                  | 3         | 1.56%   |
| Intel SSDPEKNU512GZ 512GB                            | 3         | 1.56%   |
| Toshiba MQ04ABF100 1TB                               | 2         | 1.04%   |
| Toshiba MQ01ABF050 500GB                             | 2         | 1.04%   |
| Toshiba MQ01ABD100 1TB                               | 2         | 1.04%   |
| Samsung SSD 850 EVO 250GB                            | 2         | 1.04%   |
| Samsung NVMe SSD Drive 1024GB                        | 2         | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 512GB  | 2         | 1.04%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB        | 2         | 1.04%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 2         | 1.04%   |
| Phison PS5013 E13 NVMe Controller 500GB              | 2         | 1.04%   |
| Phison E12 NVMe Controller 1024GB                    | 2         | 1.04%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                        | 2         | 1.04%   |
| Micron 2210_MTFDHBA512QFD 512GB                      | 2         | 1.04%   |
| Kingston NVMe SSD Drive 512GB                        | 2         | 1.04%   |
| Intel SSD 660P Series 1024GB                         | 2         | 1.04%   |
| HS-SSD-C100 120G                                     | 2         | 1.04%   |
| Hitachi HTS547575A9E384 752GB                        | 2         | 1.04%   |
| Crucial CT500MX500SSD1 500GB                         | 2         | 1.04%   |
| China SATA SSD 120GB                                 | 2         | 1.04%   |
| Unknown                                              | 2         | 1.04%   |
| WDC WDS500G3X0C-00SJG0 500GB                         | 1         | 0.52%   |
| WDC WDS100T2B0C-00PXH0 1TB                           | 1         | 0.52%   |
| WDC WD5000LPCX-24VHAT0 500GB                         | 1         | 0.52%   |
| WDC WD5000LPCX-00VHAT0 500GB                         | 1         | 0.52%   |
| WDC WD3200BEVT-22A0RT0 320GB                         | 1         | 0.52%   |
| WDC WD20EZRX-00DC0B0 2TB                             | 1         | 0.52%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 1         | 0.52%   |
| WDC WD10SPCX-24HWST1 1TB                             | 1         | 0.52%   |
| WDC WD10JPVT-22A1YT0 1TB                             | 1         | 0.52%   |
| WDC WD10JPCX-24UE4T0 1TB                             | 1         | 0.52%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                 | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 12        | 12     | 29.27%  |
| Toshiba  | 9         | 9      | 21.95%  |
| WDC      | 8         | 9      | 19.51%  |
| Hitachi  | 4         | 5      | 9.76%   |
| HGST     | 4         | 4      | 9.76%   |
| Unknown  | 1         | 1      | 2.44%   |
| HGST HTS | 1         | 1      | 2.44%   |
| Fujitsu  | 1         | 1      | 2.44%   |
| Apple    | 1         | 1      | 2.44%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 23.91%  |
| Kingston            | 7         | 7      | 15.22%  |
| Crucial             | 6         | 6      | 13.04%  |
| China               | 4         | 4      | 8.7%    |
| SanDisk             | 3         | 3      | 6.52%   |
| Micron Technology   | 2         | 2      | 4.35%   |
| LITEON              | 2         | 2      | 4.35%   |
| Intel               | 2         | 2      | 4.35%   |
| Apple               | 2         | 2      | 4.35%   |
| Toshiba             | 1         | 1      | 2.17%   |
| SK hynix            | 1         | 1      | 2.17%   |
| Ramsta              | 1         | 1      | 2.17%   |
| PNY                 | 1         | 1      | 2.17%   |
| Mushkin             | 1         | 1      | 2.17%   |
| Emtec               | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 80        | 100    | 47.06%  |
| SSD     | 45        | 47     | 26.47%  |
| HDD     | 40        | 43     | 23.53%  |
| Unknown | 5         | 5      | 2.94%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 80        | 100    | 48.19%  |
| SATA | 80        | 89     | 48.19%  |
| SAS  | 6         | 6      | 3.61%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 52        | 55     | 60.47%  |
| 0.51-1.0   | 31        | 32     | 36.05%  |
| 1.01-2.0   | 2         | 2      | 2.33%   |
| 4.01-10.0  | 1         | 1      | 1.16%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 39        | 26.35%  |
| 251-500        | 35        | 23.65%  |
| 501-1000       | 35        | 23.65%  |
| 1001-2000      | 15        | 10.14%  |
| Unknown        | 7         | 4.73%   |
| More than 3000 | 5         | 3.38%   |
| 51-100         | 5         | 3.38%   |
| 21-50          | 4         | 2.7%    |
| 2001-3000      | 2         | 1.35%   |
| 1-20           | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 47        | 31.54%  |
| 1-20           | 36        | 24.16%  |
| 101-250        | 18        | 12.08%  |
| 251-500        | 15        | 10.07%  |
| 51-100         | 15        | 10.07%  |
| 501-1000       | 7         | 4.7%    |
| Unknown        | 7         | 4.7%    |
| 1001-2000      | 2         | 1.34%   |
| More than 3000 | 1         | 0.67%   |
| 2001-3000      | 1         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                  | Notebooks | Drives | Percent |
|------------------------|-----------|--------|---------|
| Ramsta SSD S800 240GB  | 1         | 1      | 50%     |
| Hitachi HTS54323 320GB | 1         | 1      | 50%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Ramsta  | 1         | 1      | 50%     |
| Hitachi | 1         | 1      | 50%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 1         | 1      | 50%     |
| HDD  | 1         | 1      | 50%     |

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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 120       | 152    | 78.43%  |
| Works    | 31        | 41     | 20.26%  |
| Malfunc  | 2         | 2      | 1.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 89        | 43.63%  |
| Samsung Electronics            | 30        | 14.71%  |
| AMD                            | 27        | 13.24%  |
| SanDisk                        | 13        | 6.37%   |
| SK hynix                       | 9         | 4.41%   |
| Micron/Crucial Technology      | 6         | 2.94%   |
| Micron Technology              | 6         | 2.94%   |
| Kingston Technology Company    | 6         | 2.94%   |
| Phison Electronics             | 5         | 2.45%   |
| Toshiba America Info Systems   | 2         | 0.98%   |
| Nvidia                         | 2         | 0.98%   |
| KIOXIA                         | 2         | 0.98%   |
| Union Memory (Shenzhen)        | 1         | 0.49%   |
| Solid State Storage Technology | 1         | 0.49%   |
| Silicon Motion                 | 1         | 0.49%   |
| Shenzhen Longsys Electronics   | 1         | 0.49%   |
| Marvell Technology Group       | 1         | 0.49%   |
| Apple                          | 1         | 0.49%   |
| ADATA Technology               | 1         | 0.49%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 27        | 12.56%  |
| Samsung NVMe SSD Controller 980                                                | 12        | 5.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 4.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 10        | 4.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 4.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 3.72%   |
| Micron Non-Volatile memory controller                                          | 6         | 2.79%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 2.79%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 2.79%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 2.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 2.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 2.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 2.33%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.86%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.86%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.86%   |
| Intel Non-Volatile memory controller                                           | 4         | 1.86%   |
| SK hynix BC511                                                                 | 3         | 1.4%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 1.4%    |
| Intel SSD 660P Series                                                          | 3         | 1.4%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.4%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.93%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 2         | 0.93%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.93%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.93%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.93%   |
| Micron/Crucial Non-Volatile memory controller                                  | 2         | 0.93%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.93%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.93%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.93%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.93%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 0.93%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 102       | 51.52%  |
| NVMe | 80        | 40.4%   |
| RAID | 15        | 7.58%   |
| IDE  | 1         | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 103       | 70.55%  |
| AMD    | 43        | 29.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-10300H CPU @ 2.50GHz              | 5         | 3.42%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 5         | 3.42%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 4         | 2.74%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 4         | 2.74%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 4         | 2.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 3         | 2.05%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 3         | 2.05%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 3         | 2.05%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 3         | 2.05%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 2         | 1.37%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 2         | 1.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 1.37%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 2         | 1.37%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 2         | 1.37%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.37%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 2         | 1.37%   |
| Intel 12th Gen Core i7-12700H                   | 2         | 1.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.37%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz         | 2         | 1.37%   |
| AMD Ryzen 9 5900HS with Radeon Graphics         | 2         | 1.37%   |
| AMD Ryzen 7 6800H with Radeon Graphics          | 2         | 1.37%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.37%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 2         | 1.37%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 2         | 1.37%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 2         | 1.37%   |
| AMD A10-8700P Radeon R6, 10 Compute Cores 4C+6G | 2         | 1.37%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 0.68%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 1         | 0.68%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.68%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.68%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz              | 1         | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 0.68%   |
| Intel Core i7-7567U CPU @ 3.50GHz               | 1         | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.68%   |
| Intel Core i7-6920HQ CPU @ 2.90GHz              | 1         | 0.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.68%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.68%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 1         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 42        | 28.77%  |
| Intel Core i5           | 25        | 17.12%  |
| AMD Ryzen 7             | 16        | 10.96%  |
| AMD Ryzen 5             | 16        | 10.96%  |
| Other                   | 15        | 10.27%  |
| Intel Core i3           | 8         | 5.48%   |
| Intel Celeron           | 5         | 3.42%   |
| AMD Ryzen 9             | 4         | 2.74%   |
| Intel Pentium           | 3         | 2.05%   |
| Intel Core 2 Duo        | 3         | 2.05%   |
| AMD A10                 | 2         | 1.37%   |
| Intel Pentium Dual-Core | 1         | 0.68%   |
| Intel Core 2 Extreme    | 1         | 0.68%   |
| Intel Atom              | 1         | 0.68%   |
| AMD Ryzen 3             | 1         | 0.68%   |
| AMD FX                  | 1         | 0.68%   |
| AMD E                   | 1         | 0.68%   |
| AMD A6                  | 1         | 0.68%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 51        | 34.93%  |
| 4      | 46        | 31.51%  |
| 8      | 24        | 16.44%  |
| 6      | 20        | 13.7%   |
| 14     | 2         | 1.37%   |
| 12     | 2         | 1.37%   |
| 10     | 1         | 0.68%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 146       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 131       | 89.73%  |
| 1      | 15        | 10.27%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 146       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0xa0652    | 12        | 8.16%   |
| 0x40651    | 10        | 6.8%    |
| 0x0a50000c | 10        | 6.8%    |
| 0x306a9    | 8         | 5.44%   |
| 0x206a7    | 7         | 4.76%   |
| Unknown    | 7         | 4.76%   |
| 0x906e9    | 6         | 4.08%   |
| 0x906ea    | 5         | 3.4%    |
| 0x906a3    | 5         | 3.4%    |
| 0x806c1    | 5         | 3.4%    |
| 0x08608103 | 5         | 3.4%    |
| 0x806d1    | 4         | 2.72%   |
| 0x506e3    | 4         | 2.72%   |
| 0x406e3    | 4         | 2.72%   |
| 0x306c3    | 4         | 2.72%   |
| 0x08600106 | 4         | 2.72%   |
| 0x08600104 | 4         | 2.72%   |
| 0x806e9    | 3         | 2.04%   |
| 0x10676    | 3         | 2.04%   |
| 0x08108109 | 3         | 2.04%   |
| 0x806ec    | 2         | 1.36%   |
| 0x806ea    | 2         | 1.36%   |
| 0x706e5    | 2         | 1.36%   |
| 0x306d4    | 2         | 1.36%   |
| 0x30678    | 2         | 1.36%   |
| 0x1067a    | 2         | 1.36%   |
| 0x0a50000d | 2         | 1.36%   |
| 0x0a404101 | 2         | 1.36%   |
| 0x08108102 | 2         | 1.36%   |
| 0x06006110 | 2         | 1.36%   |
| 0xa0655    | 1         | 0.68%   |
| 0x906ed    | 1         | 0.68%   |
| 0x706a1    | 1         | 0.68%   |
| 0x506c9    | 1         | 0.68%   |
| 0x30661    | 1         | 0.68%   |
| 0x20655    | 1         | 0.68%   |
| 0x20652    | 1         | 0.68%   |
| 0x0a404102 | 1         | 0.68%   |
| 0x08900201 | 1         | 0.68%   |
| 0x08101007 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 20        | 13.7%   |
| Haswell          | 16        | 10.96%  |
| CometLake        | 13        | 8.9%    |
| Zen 3            | 12        | 8.22%   |
| Zen 2            | 9         | 6.16%   |
| Unknown          | 9         | 6.16%   |
| Skylake          | 8         | 5.48%   |
| IvyBridge        | 8         | 5.48%   |
| SandyBridge      | 7         | 4.79%   |
| IceLake          | 6         | 4.11%   |
| Zen+             | 5         | 3.42%   |
| TigerLake        | 5         | 3.42%   |
| Penryn           | 5         | 3.42%   |
| Alderlake Hybrid | 5         | 3.42%   |
| Zen              | 3         | 2.05%   |
| Westmere         | 2         | 1.37%   |
| Silvermont       | 2         | 1.37%   |
| Goldmont plus    | 2         | 1.37%   |
| Excavator        | 2         | 1.37%   |
| Broadwell        | 2         | 1.37%   |
| Steamroller      | 1         | 0.68%   |
| Puma             | 1         | 0.68%   |
| Goldmont         | 1         | 0.68%   |
| Bonnell          | 1         | 0.68%   |
| Bobcat           | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 89        | 40.27%  |
| Nvidia | 77        | 34.84%  |
| AMD    | 55        | 24.89%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 11        | 4.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 11        | 4.82%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 10        | 4.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 8         | 3.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 7         | 3.07%   |
| AMD Renoir                                                                    | 7         | 3.07%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 6         | 2.63%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 2.63%   |
| Nvidia TU117M                                                                 | 5         | 2.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 2.19%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 2.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 5         | 2.19%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 5         | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 5         | 2.19%   |
| AMD Lucienne                                                                  | 5         | 2.19%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 1.75%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 4         | 1.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 4         | 1.75%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.75%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 4         | 1.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 3         | 1.32%   |
| Intel HD Graphics 630                                                         | 3         | 1.32%   |
| Intel HD Graphics 530                                                         | 3         | 1.32%   |
| AMD Rembrandt [Radeon 680M]                                                   | 3         | 1.32%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                       | 3         | 1.32%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 2         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 2         | 0.88%   |
| Nvidia C79 [GeForce 9400M]                                                    | 2         | 0.88%   |
| Intel UHD Graphics 620                                                        | 2         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 0.88%   |
| Intel HD Graphics 620                                                         | 2         | 0.88%   |
| Intel HD Graphics 5500                                                        | 2         | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 0.88%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.88%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 2         | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 0.88%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 0.88%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                 | 2         | 0.88%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]           | 2         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 48        | 32.88%  |
| 1 x Intel          | 31        | 21.23%  |
| 1 x AMD            | 24        | 16.44%  |
| AMD + Nvidia       | 17        | 11.64%  |
| 1 x Nvidia         | 11        | 7.53%   |
| Intel + AMD        | 8         | 5.48%   |
| 2 x AMD            | 6         | 4.11%   |
| Intel + 2 x Nvidia | 1         | 0.68%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 86        | 58.5%   |
| Proprietary | 60        | 40.82%  |
| Unknown     | 1         | 0.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 78        | 52.7%   |
| 0.01-0.5   | 27        | 18.24%  |
| 1.01-2.0   | 15        | 10.14%  |
| 0.51-1.0   | 12        | 8.11%   |
| 7.01-8.0   | 5         | 3.38%   |
| 3.01-4.0   | 5         | 3.38%   |
| 5.01-6.0   | 4         | 2.7%    |
| 8.01-16.0  | 2         | 1.35%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 38        | 22.89%  |
| Chimei Innolux          | 21        | 12.65%  |
| BOE                     | 20        | 12.05%  |
| LG Display              | 19        | 11.45%  |
| Samsung Electronics     | 15        | 9.04%   |
| PANDA                   | 10        | 6.02%   |
| Apple                   | 7         | 4.22%   |
| Sharp                   | 6         | 3.61%   |
| Goldstar                | 4         | 2.41%   |
| ViewSonic               | 3         | 1.81%   |
| Dell                    | 3         | 1.81%   |
| MSI                     | 2         | 1.2%    |
| InfoVision              | 2         | 1.2%    |
| Eizo                    | 2         | 1.2%    |
| Chi Mei Optoelectronics | 2         | 1.2%    |
| Acer                    | 2         | 1.2%    |
| ___                     | 1         | 0.6%    |
| Vizio                   | 1         | 0.6%    |
| Valve                   | 1         | 0.6%    |
| Unknown                 | 1         | 0.6%    |
| Sony                    | 1         | 0.6%    |
| MLT                     | 1         | 0.6%    |
| Hewlett-Packard         | 1         | 0.6%    |
| CSO                     | 1         | 0.6%    |
| CPT                     | 1         | 0.6%    |
| AOC                     | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 4         | 2.41%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 3         | 1.81%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 3         | 1.81%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 3         | 1.81%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch          | 3         | 1.81%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch           | 2         | 1.2%    |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                     | 2         | 1.2%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch        | 2         | 1.2%    |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                  | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch         | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 2         | 1.2%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 2         | 1.2%    |
| ___ LCD TV ___9000 1360x768                                            | 1         | 0.6%    |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                   | 1         | 0.6%    |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 597x336mm 27.0-inch             | 1         | 0.6%    |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch          | 1         | 0.6%    |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch          | 1         | 0.6%    |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                    | 1         | 0.6%    |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                       | 1         | 0.6%    |
| Sony TV SNY1B02 1360x768                                               | 1         | 0.6%    |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch                | 1         | 0.6%    |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                | 1         | 0.6%    |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.6%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch      | 1         | 0.6%    |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch      | 1         | 0.6%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch      | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4152 2880x1800 302x189mm 14.0-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch  | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM105F 1366x768 575x323mm 26.0-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1         | 0.6%    |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch                | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 82        | 53.59%  |
| 1366x768 (WXGA)    | 35        | 22.88%  |
| 3840x2160 (4K)     | 5         | 3.27%   |
| 2880x1800          | 4         | 2.61%   |
| 2560x1440 (QHD)    | 4         | 2.61%   |
| 1920x1200 (WUXGA)  | 4         | 2.61%   |
| 1440x900 (WXGA+)   | 4         | 2.61%   |
| 2560x1600          | 3         | 1.96%   |
| 1280x800 (WXGA)    | 3         | 1.96%   |
| 1360x768           | 2         | 1.31%   |
| 800x1280           | 1         | 0.65%   |
| 3200x1800 (QHD+)   | 1         | 0.65%   |
| 2560x1080          | 1         | 0.65%   |
| 2520x1680          | 1         | 0.65%   |
| 2240x1400          | 1         | 0.65%   |
| 1680x1050 (WSXGA+) | 1         | 0.65%   |
| 1600x900 (HD+)     | 1         | 0.65%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 87        | 52.41%  |
| 13      | 17        | 10.24%  |
| 17      | 15        | 9.04%   |
| 14      | 12        | 7.23%   |
| 23      | 8         | 4.82%   |
| 31      | 4         | 2.41%   |
| 27      | 4         | 2.41%   |
| 16      | 3         | 1.81%   |
| 72      | 2         | 1.2%    |
| 24      | 2         | 1.2%    |
| 18      | 2         | 1.2%    |
| 48      | 1         | 0.6%    |
| 34      | 1         | 0.6%    |
| 26      | 1         | 0.6%    |
| 21      | 1         | 0.6%    |
| 20      | 1         | 0.6%    |
| 12      | 1         | 0.6%    |
| 11      | 1         | 0.6%    |
| 10      | 1         | 0.6%    |
| 7       | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 111       | 67.27%  |
| 351-400     | 15        | 9.09%   |
| 501-600     | 13        | 7.88%   |
| 201-300     | 11        | 6.67%   |
| 601-700     | 5         | 3.03%   |
| 401-500     | 4         | 2.42%   |
| 1501-2000   | 2         | 1.21%   |
| 701-800     | 1         | 0.61%   |
| 1001-1500   | 1         | 0.61%   |
| 1-100       | 1         | 0.61%   |
| Unknown     | 1         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 123       | 85.42%  |
| 16/10 | 18        | 12.5%   |
| 3/2   | 1         | 0.69%   |
| 21/9  | 1         | 0.69%   |
| 0.67  | 1         | 0.69%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 52.73%  |
| 81-90          | 25        | 15.15%  |
| 121-130        | 13        | 7.88%   |
| 201-250        | 9         | 5.45%   |
| 351-500        | 5         | 3.03%   |
| 71-80          | 4         | 2.42%   |
| 301-350        | 4         | 2.42%   |
| More than 1000 | 3         | 1.82%   |
| 111-120        | 3         | 1.82%   |
| 251-300        | 2         | 1.21%   |
| 141-150        | 2         | 1.21%   |
| 131-140        | 2         | 1.21%   |
| 61-70          | 1         | 0.61%   |
| 51-60          | 1         | 0.61%   |
| 41-50          | 1         | 0.61%   |
| 1-40           | 1         | 0.61%   |
| 151-200        | 1         | 0.61%   |
| Unknown        | 1         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 83        | 51.23%  |
| 101-120       | 35        | 21.6%   |
| 51-100        | 22        | 13.58%  |
| 161-240       | 11        | 6.79%   |
| More than 240 | 7         | 4.32%   |
| 1-50          | 3         | 1.85%   |
| Unknown       | 1         | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 118       | 80.82%  |
| 2     | 20        | 13.7%   |
| 0     | 5         | 3.42%   |
| 3     | 3         | 2.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 85        | 35.86%  |
| Intel                    | 76        | 32.07%  |
| Qualcomm Atheros         | 25        | 10.55%  |
| Broadcom                 | 18        | 7.59%   |
| MediaTek                 | 9         | 3.8%    |
| Samsung Electronics      | 3         | 1.27%   |
| Broadcom Limited         | 3         | 1.27%   |
| ASIX Electronics         | 3         | 1.27%   |
| Xiaomi                   | 2         | 0.84%   |
| Qualcomm                 | 2         | 0.84%   |
| Nvidia                   | 2         | 0.84%   |
| Sierra Wireless          | 1         | 0.42%   |
| Ralink                   | 1         | 0.42%   |
| Panasonic (Matsushita)   | 1         | 0.42%   |
| Motorola PCS             | 1         | 0.42%   |
| Marvell Technology Group | 1         | 0.42%   |
| JMicron Technology       | 1         | 0.42%   |
| Google                   | 1         | 0.42%   |
| ASUSTek Computer         | 1         | 0.42%   |
| Afatech                  | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 23.19%  |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 4.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 3.62%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 3.62%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.54%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 2.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.17%   |
| Intel Wireless 8260                                               | 6         | 2.17%   |
| Intel Wireless 7260                                               | 6         | 2.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 1.81%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 1.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 1.81%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.45%   |
| Intel Wireless 8265 / 8275                                        | 4         | 1.45%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 4         | 1.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 4         | 1.45%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.09%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.09%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.72%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.72%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.72%   |
| Intel Wireless-AC 9260                                            | 2         | 0.72%   |
| Intel Wireless 7265                                               | 2         | 0.72%   |
| Intel Wireless 3160                                               | 2         | 0.72%   |
| Intel WiFi Link 5100                                              | 2         | 0.72%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.72%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.72%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.72%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 2         | 0.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 2         | 0.72%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 2         | 0.72%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 74        | 50.68%  |
| Realtek Semiconductor  | 24        | 16.44%  |
| Qualcomm Atheros       | 20        | 13.7%   |
| Broadcom               | 15        | 10.27%  |
| MediaTek               | 7         | 4.79%   |
| Broadcom Limited       | 2         | 1.37%   |
| Sierra Wireless        | 1         | 0.68%   |
| Ralink                 | 1         | 0.68%   |
| Panasonic (Matsushita) | 1         | 0.68%   |
| ASUSTek Computer       | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 8.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 6.85%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 6.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 4.11%   |
| Intel Wireless 8260                                                     | 6         | 4.11%   |
| Intel Wireless 7260                                                     | 6         | 4.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 5         | 3.42%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 3.42%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 3.42%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 2.74%   |
| Intel Wireless 8265 / 8275                                              | 4         | 2.74%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 2.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 4         | 2.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 2.05%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 2.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.37%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.37%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.37%   |
| Intel Wireless 7265                                                     | 2         | 1.37%   |
| Intel Wireless 3160                                                     | 2         | 1.37%   |
| Intel WiFi Link 5100                                                    | 2         | 1.37%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.37%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.37%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.37%   |
| Sierra Wireless EM7455                                                  | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.68%   |
| Realtek Realtek Network controller                                      | 1         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.68%   |
| Panasonic (Matsushita) DY-WL10 802.11abgn Adapter [Broadcom BCM4323]    | 1         | 0.68%   |
| MediaTek WLAN controller                                                | 1         | 0.68%   |
| MediaTek MT7630e 802.11bgn Wireless Network Adapter                     | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 77        | 60.63%  |
| Intel                    | 20        | 15.75%  |
| Qualcomm Atheros         | 7         | 5.51%   |
| Broadcom                 | 5         | 3.94%   |
| ASIX Electronics         | 3         | 2.36%   |
| Xiaomi                   | 2         | 1.57%   |
| Samsung Electronics      | 2         | 1.57%   |
| Qualcomm                 | 2         | 1.57%   |
| Nvidia                   | 2         | 1.57%   |
| MediaTek                 | 2         | 1.57%   |
| Motorola PCS             | 1         | 0.79%   |
| Marvell Technology Group | 1         | 0.79%   |
| JMicron Technology       | 1         | 0.79%   |
| Google                   | 1         | 0.79%   |
| Broadcom Limited         | 1         | 0.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 5.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.34%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.34%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.56%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.56%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.56%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.56%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.78%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.78%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.78%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.78%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.78%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.78%   |
| Qualcomm Redmi 9T                                                 | 1         | 0.78%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.78%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.78%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.78%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.78%   |
| Qualcomm Android                                                  | 1         | 0.78%   |
| Motorola PCS moto g(8) plus                                       | 1         | 0.78%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.78%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.78%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.78%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.78%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.78%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.78%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.78%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.78%   |
| Google Pixel 6a                                                   | 1         | 0.78%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 143       | 54.17%  |
| Ethernet | 119       | 45.08%  |
| Modem    | 1         | 0.38%   |
| Unknown  | 1         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 116       | 76.32%  |
| Ethernet | 36        | 23.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 110       | 75.34%  |
| 1     | 34        | 23.29%  |
| 0     | 2         | 1.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 106       | 72.11%  |
| Yes  | 41        | 27.89%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 54.69%  |
| Realtek Semiconductor           | 15        | 11.72%  |
| IMC Networks                    | 8         | 6.25%   |
| Qualcomm Atheros Communications | 7         | 5.47%   |
| Lite-On Technology              | 7         | 5.47%   |
| Foxconn / Hon Hai               | 6         | 4.69%   |
| Apple                           | 6         | 4.69%   |
| Broadcom                        | 5         | 3.91%   |
| Toshiba                         | 1         | 0.78%   |
| Realtek                         | 1         | 0.78%   |
| Ralink                          | 1         | 0.78%   |
| Foxconn International           | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 25        | 19.53%  |
| Intel AX201 Bluetooth                             | 21        | 16.41%  |
| Realtek Bluetooth Radio                           | 13        | 10.16%  |
| Intel AX200 Bluetooth                             | 10        | 7.81%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 5         | 3.91%   |
| Apple Bluetooth Host Controller                   | 5         | 3.91%   |
| IMC Networks Wireless_Device                      | 4         | 3.13%   |
| Qualcomm Atheros  Bluetooth Device                | 3         | 2.34%   |
| Intel Bluetooth Device                            | 3         | 2.34%   |
| IMC Networks Bluetooth Radio                      | 3         | 2.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 1.56%   |
| Lite-On Bluetooth Device                          | 2         | 1.56%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 1.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 1.56%   |
| Foxconn / Hon Hai Wireless_Device                 | 2         | 1.56%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 2         | 1.56%   |
| Toshiba Askey Bluetooth Module                    | 1         | 0.78%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 1         | 0.78%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 0.78%   |
| Realtek 802.11ac WLAN Adapter                     | 1         | 0.78%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.78%   |
| Lite-On Wireless_Device                           | 1         | 0.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 1         | 0.78%   |
| Lite-On Bluetooth Radio                           | 1         | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                  | 1         | 0.78%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.78%   |
| Intel AX210 Bluetooth                             | 1         | 0.78%   |
| IMC Networks Bluetooth Device                     | 1         | 0.78%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.78%   |
| Foxconn / Hon Hai BT                              | 1         | 0.78%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth   | 1         | 0.78%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.78%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 0.78%   |
| Broadcom BCM43142A0 Bluetooth Device              | 1         | 0.78%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 1         | 0.78%   |
| Broadcom BCM2070 Bluetooth Device                 | 1         | 0.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI              | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 101       | 46.76%  |
| AMD                    | 51        | 23.61%  |
| Nvidia                 | 49        | 22.69%  |
| C-Media Electronics    | 3         | 1.39%   |
| TTGK Technology        | 2         | 0.93%   |
| Sony                   | 2         | 0.93%   |
| SteelSeries ApS        | 1         | 0.46%   |
| Samsung Electronics    | 1         | 0.46%   |
| Logitech               | 1         | 0.46%   |
| Hewlett-Packard        | 1         | 0.46%   |
| Generalplus Technology | 1         | 0.46%   |
| Corsair                | 1         | 0.46%   |
| Blue Microphones       | 1         | 0.46%   |
| ASUSTek Computer       | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 35        | 13.16%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 18        | 6.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 4.89%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 4.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 4.14%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 4.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 3.76%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 3.38%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 3.01%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 1.88%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.88%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.5%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 4         | 1.5%    |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.13%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 1.13%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.13%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.13%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 1.13%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 1.13%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 1.13%   |
| AMD FCH Azalia Controller                                                  | 3         | 1.13%   |
| TTGK Technology Audio                                                      | 2         | 0.75%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.75%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.75%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.75%   |
| Nvidia Audio device                                                        | 2         | 0.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.75%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.75%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2         | 0.75%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 18        | 42.86%  |
| Micron Technology   | 9         | 21.43%  |
| SK hynix            | 8         | 19.05%  |
| Unknown (ABCD)      | 2         | 4.76%   |
| Transcend           | 1         | 2.38%   |
| Nanya Technology    | 1         | 2.38%   |
| Kingston            | 1         | 2.38%   |
| Elpida              | 1         | 2.38%   |
| Crucial             | 1         | 2.38%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 6.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 4.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 4.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 4.55%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 2.27%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 2.27%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 2.27%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 2.27%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 2.27%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.27%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 2.27%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 2.27%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.27%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 2.27%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 2.27%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 2.27%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 2.27%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 2.27%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 2.27%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.27%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 1         | 2.27%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 2.27%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 2.27%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 2.27%   |
| Nanya RAM M2S4G64CB8HG4N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 2.27%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 1         | 2.27%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 2.27%   |
| Micron RAM Module 2GB Row Of Chips 6400MT/s                      | 1         | 2.27%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.27%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.27%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 2.27%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 2.27%   |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s             | 1         | 2.27%   |
| Elpida RAM EBJ40UG8EFU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 1         | 2.27%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s            | 1         | 2.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 20        | 60.61%  |
| DDR3    | 5         | 15.15%  |
| LPDDR4  | 4         | 12.12%  |
| DDR5    | 2         | 6.06%   |
| DDR2    | 1         | 3.03%   |
| Unknown | 1         | 3.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 29        | 82.86%  |
| Row Of Chips | 6         | 17.14%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 22        | 61.11%  |
| 4096  | 7         | 19.44%  |
| 16384 | 3         | 8.33%   |
| 2048  | 3         | 8.33%   |
| 32768 | 1         | 2.78%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 14        | 40%     |
| 2667  | 6         | 17.14%  |
| 1600  | 4         | 11.43%  |
| 4800  | 2         | 5.71%   |
| 2400  | 2         | 5.71%   |
| 6400  | 1         | 2.86%   |
| 4267  | 1         | 2.86%   |
| 4266  | 1         | 2.86%   |
| 3266  | 1         | 2.86%   |
| 2133  | 1         | 2.86%   |
| 1333  | 1         | 2.86%   |
| 975   | 1         | 2.86%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

Zero info for selected period =(

Scanner Model
-------------

Scanner device models

Zero info for selected period =(

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 28        | 21.54%  |
| IMC Networks                           | 21        | 16.15%  |
| Acer                                   | 12        | 9.23%   |
| Realtek Semiconductor                  | 7         | 5.38%   |
| Microdia                               | 7         | 5.38%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.38%   |
| Sunplus Innovation Technology          | 6         | 4.62%   |
| Apple                                  | 6         | 4.62%   |
| Syntek                                 | 5         | 3.85%   |
| Quanta                                 | 5         | 3.85%   |
| Suyin                                  | 4         | 3.08%   |
| Sonix Technology                       | 4         | 3.08%   |
| Luxvisions Innotech Limited            | 4         | 3.08%   |
| Logitech                               | 3         | 2.31%   |
| Lite-On Technology                     | 3         | 2.31%   |
| Z-Star Microelectronics                | 1         | 0.77%   |
| Tobii Technology AB                    | 1         | 0.77%   |
| SunplusIT                              | 1         | 0.77%   |
| Silicon Motion                         | 1         | 0.77%   |
| Samsung Electronics                    | 1         | 0.77%   |
| Intel                                  | 1         | 0.77%   |
| Importek                               | 1         | 0.77%   |
| Goodong Industry                       | 1         | 0.77%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 11        | 8.4%    |
| Chicony Integrated Camera                           | 7         | 5.34%   |
| Syntek Integrated Camera                            | 4         | 3.05%   |
| Microdia Integrated_Webcam_HD                       | 4         | 3.05%   |
| IMC Networks Integrated Camera                      | 4         | 3.05%   |
| Acer Integrated Camera                              | 4         | 3.05%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 2.29%   |
| Realtek USB Camera                                  | 3         | 2.29%   |
| Chicony HP Truevision HD                            | 3         | 2.29%   |
| Chicony HD WebCam                                   | 3         | 2.29%   |
| Acer HD Webcam                                      | 3         | 2.29%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.53%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.53%   |
| Lite-On HP HD Camera                                | 2         | 1.53%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 2         | 1.53%   |
| Chicony USB2.0 Camera                               | 2         | 1.53%   |
| Chicony USB 2.0 Camera                              | 2         | 1.53%   |
| Chicony EasyCamera                                  | 2         | 1.53%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 1.53%   |
| Apple FaceTime HD Camera                            | 2         | 1.53%   |
| Apple Built-in iSight                               | 2         | 1.53%   |
| Acer Lenovo Integrated Webcam                       | 2         | 1.53%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.76%   |
| Tobii AB EyeChip                                    | 1         | 0.76%   |
| Syntek EasyCamera                                   | 1         | 0.76%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.76%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.76%   |
| Suyin HP Truevision HD                              | 1         | 0.76%   |
| Suyin HP TrueVision Full HD                         | 1         | 0.76%   |
| SunplusIT MTD camera                                | 1         | 0.76%   |
| Sunplus Laptop Integrated WebCam HD                 | 1         | 0.76%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.76%   |
| Sunplus HD WebCam                                   | 1         | 0.76%   |
| Sunplus Asus Webcam                                 | 1         | 0.76%   |
| Sonix USB2.0 FHD UVC WebCam                         | 1         | 0.76%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 0.76%   |
| Samsung Galaxy A5 (MTP)                             | 1         | 0.76%   |
| Realtek HP Truevision HD integrated webcam          | 1         | 0.76%   |
| Realtek EasyCamera                                  | 1         | 0.76%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 9         | 42.86%  |
| Synaptics                          | 6         | 28.57%  |
| Shenzhen Goodix Technology         | 3         | 14.29%  |
| Elan Microelectronics              | 2         | 9.52%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 4.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 23.81%  |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 14.29%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 9.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 9.52%   |
| Elan ELAN:ARM-M4                                                | 2         | 9.52%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 4.76%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 4.76%   |
| Synaptics WBDI Device                                           | 1         | 4.76%   |
| Synaptics  WBDI                                                 | 1         | 4.76%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 4.76%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 4.76%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 4.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 1         | 50%     |
| Alcor Micro | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 50%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 98        | 66.22%  |
| 1     | 38        | 25.68%  |
| 2     | 12        | 8.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 21        | 34.43%  |
| Graphics card         | 15        | 24.59%  |
| Multimedia controller | 14        | 22.95%  |
| Net/wireless          | 7         | 11.48%  |
| Bluetooth             | 2         | 3.28%   |
| Modem                 | 1         | 1.64%   |
| Chipcard              | 1         | 1.64%   |

