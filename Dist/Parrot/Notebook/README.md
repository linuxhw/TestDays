Parrot - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 263

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Modern 15 A5M               | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ASUSTek       | X540SAA                     | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Toshiba       | Satellite L775D             | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | X75VC                       | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| Apple         | MacBookPro11,4              | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| Dell          | Latitude XT2                | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Jumper        | EZbook                      | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Samsung       | 550P5C/550P7C               | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Toshiba       | Satellite C75D-B            | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Dell          | Inspiron N5110              | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Dell          | Latitude 7480               | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| HP            | EliteBook 8470p             | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| Lenovo        | IdeaPad Y580                | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Toxic         | GM7MQ8P                     | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| Toshiba       | Satellite L655              | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| HP            | Pavilion g7                 | [d27bb0d31e](https://linux-hardware.org/?probe=d27bb0d31e) | Oct 31, 2021 |
| Lenovo        | B50-80 80EW                 | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| HP            | Pavilion g7                 | [b386e97faa](https://linux-hardware.org/?probe=b386e97faa) | Oct 25, 2021 |
| Dell          | Latitude E7450              | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| MSI           | GT60 2OC/2OD                | [5347580c37](https://linux-hardware.org/?probe=5347580c37) | Oct 08, 2021 |
| HP            | EliteBook 840 G3            | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| MSI           | GS66 Stealth 10UG           | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Lenovo        | B50-80 80EW                 | [e3fd336b60](https://linux-hardware.org/?probe=e3fd336b60) | Aug 24, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| HP            | Pavilion dv6700             | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| HP            | Pavilion dv7                | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ASUSTek       | G74Sx                       | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| Dell          | Latitude E7440              | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| ASUSTek       | X450EA                      | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| MSI           | GE73 Raider RGB 8RE         | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Apple         | MacBookPro11,1              | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Quanta        | 3610D                       | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| Quanta        | 3610D                       | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| Acer          | Aspire E1-571G              | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Dell          | Inspiron 5420               | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| HP            | ENVY 15                     | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Dell          | Latitude 7390               | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Toshiba       | Satellite L750              | [4846d22260](https://linux-hardware.org/?probe=4846d22260) | Dec 08, 2020 |
| Dell          | Latitude E5440              | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| Acer          | Aspire 5250                 | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [7db1dd5f36](https://linux-hardware.org/?probe=7db1dd5f36) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | X540YA                      | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Toshiba       | Satellite L750              | [06fc27b7e0](https://linux-hardware.org/?probe=06fc27b7e0) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| Toshiba       | Satellite L750              | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Alienware     | 17 R4                       | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Toshiba       | Satellite L750              | [04b3b93310](https://linux-hardware.org/?probe=04b3b93310) | Sep 13, 2020 |
| Dell          | Latitude 3400               | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| Dell          | Latitude 3400               | [1b631bdd99](https://linux-hardware.org/?probe=1b631bdd99) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | [078297eea5](https://linux-hardware.org/?probe=078297eea5) | Sep 10, 2020 |
| Dell          | Latitude 3400               | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | Inspiron N7110              | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | Inspiron N7110              | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Dell          | G7 7790                     | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Google        | Celes                       | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | [304bcdfae3](https://linux-hardware.org/?probe=304bcdfae3) | May 22, 2020 |
| Google        | Celes                       | [f0ba91b9f6](https://linux-hardware.org/?probe=f0ba91b9f6) | May 22, 2020 |
| Google        | Celes                       | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |
| Fujitsu       | LIFEBOOK A532               | [96ec25db7c](https://linux-hardware.org/?probe=96ec25db7c) | May 21, 2020 |
| Fujitsu       | LIFEBOOK A532               | [b2ecb833ba](https://linux-hardware.org/?probe=b2ecb833ba) | May 21, 2020 |
| Dell          | Inspiron MM061              | [a6bb0bfd0b](https://linux-hardware.org/?probe=a6bb0bfd0b) | May 21, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Dell          | Inspiron MM061              | [0d48c76bfd](https://linux-hardware.org/?probe=0d48c76bfd) | May 11, 2020 |
| Lenovo        | V110-15ISK 80TL             | [d64b4a56e0](https://linux-hardware.org/?probe=d64b4a56e0) | May 08, 2020 |
| ASUSTek       | X442URR                     | [7595f05acd](https://linux-hardware.org/?probe=7595f05acd) | May 04, 2020 |
| HP            | ProBook 6475b               | [c9ee4e6614](https://linux-hardware.org/?probe=c9ee4e6614) | May 03, 2020 |
| HP            | ProBook 6475b               | [06da2207cd](https://linux-hardware.org/?probe=06da2207cd) | May 02, 2020 |
| HP            | ProBook 6475b               | [b2ff4072ce](https://linux-hardware.org/?probe=b2ff4072ce) | May 02, 2020 |
| Toshiba       | Satellite L300D             | [5a320c4b78](https://linux-hardware.org/?probe=5a320c4b78) | May 02, 2020 |
| Dell          | Latitude E6420              | [ae3ade27d7](https://linux-hardware.org/?probe=ae3ade27d7) | Apr 29, 2020 |
| Dell          | Latitude E6420              | [83380135bc](https://linux-hardware.org/?probe=83380135bc) | Apr 27, 2020 |
| Dell          | Latitude E6420              | [12c77f16d5](https://linux-hardware.org/?probe=12c77f16d5) | Apr 27, 2020 |
| Dell          | XPS 12-9Q33                 | [f831495ef5](https://linux-hardware.org/?probe=f831495ef5) | Apr 25, 2020 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [6bf9d537a8](https://linux-hardware.org/?probe=6bf9d537a8) | Apr 21, 2020 |
| Lenovo        | V110-15ISK 80TL             | [2dec0ef690](https://linux-hardware.org/?probe=2dec0ef690) | Apr 18, 2020 |
| HP            | Pavilion g6                 | [c54d518ca7](https://linux-hardware.org/?probe=c54d518ca7) | Apr 15, 2020 |
| Acer          | Aspire 5250                 | [100d4bacdc](https://linux-hardware.org/?probe=100d4bacdc) | Apr 14, 2020 |
| Dell          | Inspiron 5721               | [23d5dff3bd](https://linux-hardware.org/?probe=23d5dff3bd) | Apr 11, 2020 |
| Dell          | Inspiron 3458               | [d9c91be81b](https://linux-hardware.org/?probe=d9c91be81b) | Apr 06, 2020 |
| Dell          | Inspiron 3458               | [a10080482e](https://linux-hardware.org/?probe=a10080482e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [98fdaa9d0e](https://linux-hardware.org/?probe=98fdaa9d0e) | Apr 05, 2020 |
| Dell          | Inspiron 3458               | [cfb5a6d57c](https://linux-hardware.org/?probe=cfb5a6d57c) | Apr 05, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| Samsung       | RV415/RV515                 | [3b9248b95f](https://linux-hardware.org/?probe=3b9248b95f) | Mar 31, 2020 |
| Lenovo        | ThinkPad T440s 20ARS01C0... | [aa9f421079](https://linux-hardware.org/?probe=aa9f421079) | Mar 23, 2020 |
| HP            | Laptop 17-by0xxx            | [21c7ac4323](https://linux-hardware.org/?probe=21c7ac4323) | Feb 17, 2020 |
| Lenovo        | ThinkPad E14 20RA0016GE     | [dd543cf29b](https://linux-hardware.org/?probe=dd543cf29b) | Feb 09, 2020 |
| Notebook      | W510TU                      | [987d9232fe](https://linux-hardware.org/?probe=987d9232fe) | Jan 31, 2020 |
| Notebook      | W510TU                      | [40cd6b0ccd](https://linux-hardware.org/?probe=40cd6b0ccd) | Jan 31, 2020 |
| Notebook      | W510TU                      | [4556eb747b](https://linux-hardware.org/?probe=4556eb747b) | Jan 31, 2020 |
| HP            | EliteBook 8460p             | [8b7c621317](https://linux-hardware.org/?probe=8b7c621317) | Jan 26, 2020 |
| HUAWEI        | WRT-WX9                     | [375040e90b](https://linux-hardware.org/?probe=375040e90b) | Jan 05, 2020 |
| Notebook      | W510TU                      | [aa2e59fd60](https://linux-hardware.org/?probe=aa2e59fd60) | Dec 25, 2019 |
| Apple         | MacBookAir7,2               | [1a26d7b485](https://linux-hardware.org/?probe=1a26d7b485) | Dec 21, 2019 |
| Notebook      | W510TU                      | [f2102dfe5b](https://linux-hardware.org/?probe=f2102dfe5b) | Dec 09, 2019 |
| Apple         | MacBookAir7,2               | [73a28279bc](https://linux-hardware.org/?probe=73a28279bc) | Dec 05, 2019 |
| HP            | Pavilion Laptop 15-cs0xx... | [7bc298d7af](https://linux-hardware.org/?probe=7bc298d7af) | Nov 10, 2019 |
| HP            | 630                         | [687ccfe3b1](https://linux-hardware.org/?probe=687ccfe3b1) | Sep 28, 2019 |
| Acer          | Aspire E5-475               | [3e3fad10fe](https://linux-hardware.org/?probe=3e3fad10fe) | Aug 18, 2019 |
| Gateway       | NE-522                      | [d562b598e5](https://linux-hardware.org/?probe=d562b598e5) | Aug 10, 2019 |
| Lenovo        | Y50-70 Touch 20349          | [c0c73d01ba](https://linux-hardware.org/?probe=c0c73d01ba) | Jun 08, 2019 |
| Apple         | MacBookPro11,4              | [49a28f87b9](https://linux-hardware.org/?probe=49a28f87b9) | May 21, 2019 |
| Acer          | Swift SF314-54              | [89013e65ec](https://linux-hardware.org/?probe=89013e65ec) | Apr 26, 2019 |
| ASUSTek       | X510UQ                      | [74e81c78ab](https://linux-hardware.org/?probe=74e81c78ab) | Feb 16, 2019 |
| ASUSTek       | X510UQ                      | [50fc8650ad](https://linux-hardware.org/?probe=50fc8650ad) | Feb 16, 2019 |
| Dell          | Latitude E7440              | [ce392df9c0](https://linux-hardware.org/?probe=ce392df9c0) | Dec 26, 2018 |
| HP            | Pavilion 15                 | [921bec751d](https://linux-hardware.org/?probe=921bec751d) | Oct 13, 2018 |
| Digma         | CITI E401 ET4007EW          | [597e65c2a4](https://linux-hardware.org/?probe=597e65c2a4) | Jan 07, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Parrot 4.11  | 57        | 30.98%  |
| Parrot 4.10  | 44        | 23.91%  |
| Parrot 5.0   | 39        | 21.2%   |
| Parrot 4.8   | 15        | 8.15%   |
| Parrot 4.9   | 13        | 7.07%   |
| Parrot 4.7   | 10        | 5.43%   |
| Parrot 4.6   | 2         | 1.09%   |
| Parrot 4.5   | 1         | 0.54%   |
| Parrot 4.4   | 1         | 0.54%   |
| Parrot 4.2.2 | 1         | 0.54%   |
| Parrot 3.10  | 1         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Parrot | 174       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.14.0-9parrot1-amd64    | 28        | 14.89%  |
| 5.7.0-2parrot2-amd64     | 26        | 13.83%  |
| 5.10.0-6parrot1-amd64    | 22        | 11.7%   |
| 5.10.0-8parrot1-amd64    | 13        | 6.91%   |
| 5.5.0-1parrot1-amd64     | 12        | 6.38%   |
| 5.4.0-4parrot1-amd64     | 11        | 5.85%   |
| 5.16.0-12parrot1-amd64   | 10        | 5.32%   |
| 5.6.0-2parrot1-amd64     | 9         | 4.79%   |
| 5.14.0-2parrot1-amd64    | 8         | 4.26%   |
| 5.9.0-2parrot1-amd64     | 7         | 3.72%   |
| 5.15.0-15parrot1-amd64   | 5         | 2.66%   |
| 5.8.0-2parrot1-amd64     | 3         | 1.6%    |
| 5.4.0-2parrot1-amd64     | 3         | 1.6%    |
| 5.2.0-2parrot1-amd64     | 3         | 1.6%    |
| 5.10.0-5parrot1-amd64    | 3         | 1.6%    |
| 5.10.0-3parrot1-amd64    | 3         | 1.6%    |
| 4.19.0-parrot4-28t-amd64 | 3         | 1.6%    |
| 5.8.0-1parrot1-amd64     | 2         | 1.06%   |
| 5.4.0-3parrot1-amd64     | 2         | 1.06%   |
| 4.18.0-parrot10-amd64    | 2         | 1.06%   |
| 5.7.0-rc6-galliumos      | 1         | 0.53%   |
| 5.4.0-2parrot1-686-pae   | 1         | 0.53%   |
| 5.4.0-1parrot1-amd64     | 1         | 0.53%   |
| 5.3.0-3parrot3-amd64     | 1         | 0.53%   |
| 5.3.0-3parrot3-686-pae   | 1         | 0.53%   |
| 5.3.0-1parrot1-amd64     | 1         | 0.53%   |
| 5.15.0-5parrot1-amd64    | 1         | 0.53%   |
| 5.10.0-kali6-amd64       | 1         | 0.53%   |
| 5.10.0-6parrot1-rt-amd64 | 1         | 0.53%   |
| 5.1.0-parrot1-3t-amd64   | 1         | 0.53%   |
| 4.19.0-parrot1-13t-amd64 | 1         | 0.53%   |
| 4.14.0-parrot7-amd64     | 1         | 0.53%   |
| Unknown                  | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10.0  | 43        | 22.99%  |
| 5.14.0  | 35        | 18.72%  |
| 5.7.0   | 27        | 14.44%  |
| 5.4.0   | 18        | 9.63%   |
| 5.5.0   | 12        | 6.42%   |
| 5.16.0  | 10        | 5.35%   |
| 5.6.0   | 9         | 4.81%   |
| 5.9.0   | 7         | 3.74%   |
| 5.15.0  | 6         | 3.21%   |
| 5.8.0   | 5         | 2.67%   |
| 4.19.0  | 4         | 2.14%   |
| 5.3.0   | 3         | 1.6%    |
| 5.2.0   | 3         | 1.6%    |
| 4.18.0  | 2         | 1.07%   |
| 5.1.0   | 1         | 0.53%   |
| 4.14.0  | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 43        | 22.99%  |
| 5.14    | 35        | 18.72%  |
| 5.7     | 27        | 14.44%  |
| 5.4     | 18        | 9.63%   |
| 5.5     | 12        | 6.42%   |
| 5.16    | 10        | 5.35%   |
| 5.6     | 9         | 4.81%   |
| 5.9     | 7         | 3.74%   |
| 5.15    | 6         | 3.21%   |
| 5.8     | 5         | 2.67%   |
| 4.19    | 4         | 2.14%   |
| 5.3     | 3         | 1.6%    |
| 5.2     | 3         | 1.6%    |
| 4.18    | 2         | 1.07%   |
| 5.1     | 1         | 0.53%   |
| 4.14    | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 173       | 99.43%  |
| i686   | 1         | 0.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| MATE          | 110       | 62.15%  |
| KDE5          | 32        | 18.08%  |
| Unknown       | 16        | 9.04%   |
| KDE           | 13        | 7.34%   |
| XFCE          | 4         | 2.26%   |
| LXDE          | 1         | 0.56%   |
| GNOME Classic | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 173       | 99.43%  |
| Unknown | 1         | 0.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 72        | 40.22%  |
| TDM     | 50        | 27.93%  |
| LightDM | 50        | 27.93%  |
| GDM     | 5         | 2.79%   |
| SDDM    | 2         | 1.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 89        | 50.86%  |
| en_GB   | 18        | 10.29%  |
| Unknown | 14        | 8%      |
| fr_FR   | 8         | 4.57%   |
| ru_RU   | 7         | 4%      |
| de_DE   | 6         | 3.43%   |
| pl_PL   | 5         | 2.86%   |
| pt_BR   | 4         | 2.29%   |
| es_ES   | 4         | 2.29%   |
| en_IN   | 3         | 1.71%   |
| en_AU   | 3         | 1.71%   |
| tr_TR   | 1         | 0.57%   |
| nl_BE   | 1         | 0.57%   |
| it_IT   | 1         | 0.57%   |
| id_ID   | 1         | 0.57%   |
| fr_CA   | 1         | 0.57%   |
| es_MX   | 1         | 0.57%   |
| es_CO   | 1         | 0.57%   |
| es_CL   | 1         | 0.57%   |
| en_ZA   | 1         | 0.57%   |
| en_NZ   | 1         | 0.57%   |
| en_NG   | 1         | 0.57%   |
| en_DK   | 1         | 0.57%   |
| cs_CZ   | 1         | 0.57%   |
| C       | 1         | 0.57%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 116       | 65.91%  |
| EFI  | 60        | 34.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 122       | 68.54%  |
| Ext4    | 38        | 21.35%  |
| Xfs     | 8         | 4.49%   |
| Unknown | 7         | 3.93%   |
| Overlay | 3         | 1.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 80        | 45.45%  |
| GPT     | 56        | 31.82%  |
| MBR     | 40        | 22.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 152       | 86.86%  |
| Yes       | 23        | 13.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 122       | 69.71%  |
| Yes       | 53        | 30.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 35        | 20.11%  |
| Lenovo                | 29        | 16.67%  |
| Dell                  | 28        | 16.09%  |
| ASUSTek Computer      | 17        | 9.77%   |
| Acer                  | 13        | 7.47%   |
| MSI                   | 8         | 4.6%    |
| Apple                 | 8         | 4.6%    |
| Toshiba               | 6         | 3.45%   |
| Samsung Electronics   | 4         | 2.3%    |
| Sony                  | 2         | 1.15%   |
| Razer                 | 2         | 1.15%   |
| Gateway               | 2         | 1.15%   |
| Fujitsu               | 2         | 1.15%   |
| Alienware             | 2         | 1.15%   |
| Wortmann AG           | 1         | 0.57%   |
| Toxic                 | 1         | 0.57%   |
| System76              | 1         | 0.57%   |
| Quanta                | 1         | 0.57%   |
| Positivo Bahia - VAIO | 1         | 0.57%   |
| Positivo              | 1         | 0.57%   |
| Notebook              | 1         | 0.57%   |
| Metabox               | 1         | 0.57%   |
| Jumper                | 1         | 0.57%   |
| HUAWEI                | 1         | 0.57%   |
| GPU Company           | 1         | 0.57%   |
| Google                | 1         | 0.57%   |
| eMachines             | 1         | 0.57%   |
| Eluktronics           | 1         | 0.57%   |
| Digma                 | 1         | 0.57%   |
| Chuwi                 | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                               | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| MSI Modern 15 A5M                                  | 3         | 1.72%   |
| HP Notebook                                        | 3         | 1.72%   |
| HP ProBook 650 G1                                  | 2         | 1.15%   |
| HP Pavilion 15                                     | 2         | 1.15%   |
| HP EliteBook 8470p                                 | 2         | 1.15%   |
| Dell Latitude E7440                                | 2         | 1.15%   |
| Dell Latitude E6420                                | 2         | 1.15%   |
| Dell Latitude E6410                                | 2         | 1.15%   |
| Dell Inspiron MM061                                | 2         | 1.15%   |
| ASUS Q524UQ                                        | 2         | 1.15%   |
| Apple MacBookPro8,1                                | 2         | 1.15%   |
| Acer Nitro AN515-54                                | 2         | 1.15%   |
| Wortmann AG TERRA_MOBILE_1542                      | 1         | 0.57%   |
| Toxic GM7MQ8P                                      | 1         | 0.57%   |
| Toshiba Satellite L775D                            | 1         | 0.57%   |
| Toshiba Satellite L750                             | 1         | 0.57%   |
| Toshiba Satellite L655                             | 1         | 0.57%   |
| Toshiba Satellite L300D                            | 1         | 0.57%   |
| Toshiba Satellite Click 2 L35W-B                   | 1         | 0.57%   |
| Toshiba Satellite C75D-B                           | 1         | 0.57%   |
| System76 Gazelle                                   | 1         | 0.57%   |
| Sony VPCCB15FG                                     | 1         | 0.57%   |
| Sony SVP1321L1EBI                                  | 1         | 0.57%   |
| Samsung RV415/RV515                                | 1         | 0.57%   |
| Samsung 550P5C/550P7C                              | 1         | 0.57%   |
| Samsung 350V5C/351V5C/3540VC/3440VC                | 1         | 0.57%   |
| Samsung 300E4C/300E5C/300E7C                       | 1         | 0.57%   |
| Razer Blade Stealth                                | 1         | 0.57%   |
| Razer Blade 15 Base Model (Early 2020) - RZ09-0328 | 1         | 0.57%   |
| Quanta HDX PREMIUM SERIES                          | 1         | 0.57%   |
| Positivo Q232A                                     | 1         | 0.57%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H            | 1         | 0.57%   |
| Notebook W510TU                                    | 1         | 0.57%   |
| MSI GT60 2OC/2OD                                   | 1         | 0.57%   |
| MSI GS66 Stealth 10UG                              | 1         | 0.57%   |
| MSI GE75 Raider 10SF                               | 1         | 0.57%   |
| MSI GE73 Raider RGB 8RE                            | 1         | 0.57%   |
| MSI GE63 Raider RGB 8RE                            | 1         | 0.57%   |
| Metabox Edge-Pro NS50MU                            | 1         | 0.57%   |
| Lenovo Yoga S740-14IIL 81RS                        | 1         | 0.57%   |
| Lenovo Y520-15IKBN 80WK                            | 1         | 0.57%   |
| Lenovo Y50-70 Touch 20349                          | 1         | 0.57%   |
| Lenovo V110-15ISK 80TL                             | 1         | 0.57%   |
| Lenovo ThinkPad X260 20F5S5QT00                    | 1         | 0.57%   |
| Lenovo ThinkPad X250 20CL001GZA                    | 1         | 0.57%   |
| Lenovo ThinkPad X240 20AMS4MH00                    | 1         | 0.57%   |
| Lenovo ThinkPad X220 42912XG                       | 1         | 0.57%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001GUS        | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon 5th 20HRCTO1WW           | 1         | 0.57%   |
| Lenovo ThinkPad T490 20N2S04000                    | 1         | 0.57%   |
| Lenovo ThinkPad T480 20L6SCYP00                    | 1         | 0.57%   |
| Lenovo ThinkPad T440s 20ARS01C02                   | 1         | 0.57%   |
| Lenovo ThinkPad T420s 4174W2P                      | 1         | 0.57%   |
| Lenovo ThinkPad S1 Yoga 12 20DKS09J00              | 1         | 0.57%   |
| Lenovo ThinkPad E595 20NFCTO1WW                    | 1         | 0.57%   |
| Lenovo ThinkPad E15 20RD0086UE                     | 1         | 0.57%   |
| Lenovo ThinkPad E14 20RA0016GE                     | 1         | 0.57%   |
| Lenovo IdeaPad Y700-15ISK 80NV                     | 1         | 0.57%   |
| Lenovo IdeaPad Y580                                | 1         | 0.57%   |
| Lenovo IdeaPad L340-17API 81LY                     | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 14        | 8.05%   |
| HP Pavilion                             | 12        | 6.9%    |
| Dell Latitude                           | 12        | 6.9%    |
| Dell Inspiron                           | 11        | 6.32%   |
| Lenovo IdeaPad                          | 8         | 4.6%    |
| Toshiba Satellite                       | 6         | 3.45%   |
| HP EliteBook                            | 6         | 3.45%   |
| Acer Aspire                             | 6         | 3.45%   |
| HP Laptop                               | 5         | 2.87%   |
| HP ProBook                              | 4         | 2.3%    |
| ASUS VivoBook                           | 4         | 2.3%    |
| MSI Modern                              | 3         | 1.72%   |
| HP Notebook                             | 3         | 1.72%   |
| Acer Nitro                              | 3         | 1.72%   |
| Razer Blade                             | 2         | 1.15%   |
| Fujitsu LIFEBOOK                        | 2         | 1.15%   |
| Dell Precision                          | 2         | 1.15%   |
| ASUS Q524UQ                             | 2         | 1.15%   |
| Apple MacBookPro8                       | 2         | 1.15%   |
| Apple MacBookPro11                      | 2         | 1.15%   |
| Acer Swift                              | 2         | 1.15%   |
| Wortmann AG TERRA                       | 1         | 0.57%   |
| Toxic GM7MQ8P                           | 1         | 0.57%   |
| System76 Gazelle                        | 1         | 0.57%   |
| Sony VPCCB15FG                          | 1         | 0.57%   |
| Sony SVP1321L1EBI                       | 1         | 0.57%   |
| Samsung RV415                           | 1         | 0.57%   |
| Samsung 550P5C                          | 1         | 0.57%   |
| Samsung 350V5C                          | 1         | 0.57%   |
| Samsung 300E4C                          | 1         | 0.57%   |
| Quanta HDX                              | 1         | 0.57%   |
| Positivo Q232A                          | 1         | 0.57%   |
| Positivo Bahia - VAIO VJFE51F11X-B0111H | 1         | 0.57%   |
| Notebook W510TU                         | 1         | 0.57%   |
| MSI GT60                                | 1         | 0.57%   |
| MSI GS66                                | 1         | 0.57%   |
| MSI GE75                                | 1         | 0.57%   |
| MSI GE73                                | 1         | 0.57%   |
| MSI GE63                                | 1         | 0.57%   |
| Metabox Edge-Pro                        | 1         | 0.57%   |
| Lenovo Yoga                             | 1         | 0.57%   |
| Lenovo Y520-15IKBN                      | 1         | 0.57%   |
| Lenovo Y50-70                           | 1         | 0.57%   |
| Lenovo V110-15ISK                       | 1         | 0.57%   |
| Lenovo G480                             | 1         | 0.57%   |
| Lenovo E41-25                           | 1         | 0.57%   |
| Lenovo B50-80                           | 1         | 0.57%   |
| Jumper EZbook                           | 1         | 0.57%   |
| HUAWEI WRT-WX9                          | 1         | 0.57%   |
| HP ZBook                                | 1         | 0.57%   |
| HP ENVY                                 | 1         | 0.57%   |
| HP Compaq                               | 1         | 0.57%   |
| HP 630                                  | 1         | 0.57%   |
| HP 250                                  | 1         | 0.57%   |
| GPU Company GWTN141-10                  | 1         | 0.57%   |
| Google Celes                            | 1         | 0.57%   |
| Gateway NE-522                          | 1         | 0.57%   |
| Gateway MP8708                          | 1         | 0.57%   |
| eMachines eME728                        | 1         | 0.57%   |
| Eluktronics MAG-15u                     | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2011 | 24        | 13.79%  |
| 2019 | 23        | 13.22%  |
| 2018 | 17        | 9.77%   |
| 2014 | 15        | 8.62%   |
| 2013 | 15        | 8.62%   |
| 2016 | 14        | 8.05%   |
| 2020 | 13        | 7.47%   |
| 2021 | 10        | 5.75%   |
| 2012 | 10        | 5.75%   |
| 2017 | 8         | 4.6%    |
| 2010 | 8         | 4.6%    |
| 2015 | 5         | 2.87%   |
| 2008 | 4         | 2.3%    |
| 2007 | 3         | 1.72%   |
| 2006 | 3         | 1.72%   |
| 2009 | 2         | 1.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 174       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 174       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 173       | 99.43%  |
| Yes  | 1         | 0.57%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 42        | 24.14%  |
| 8.01-16.0   | 42        | 24.14%  |
| 3.01-4.0    | 36        | 20.69%  |
| 16.01-24.0  | 29        | 16.67%  |
| 32.01-64.0  | 9         | 5.17%   |
| 1.01-2.0    | 7         | 4.02%   |
| 64.01-256.0 | 5         | 2.87%   |
| 2.01-3.0    | 3         | 1.72%   |
| 24.01-32.0  | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 62        | 33.51%  |
| 2.01-3.0  | 61        | 32.97%  |
| 3.01-4.0  | 31        | 16.76%  |
| 4.01-8.0  | 17        | 9.19%   |
| 0.51-1.0  | 9         | 4.86%   |
| 8.01-16.0 | 4         | 2.16%   |
| 0.01-0.5  | 1         | 0.54%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 114       | 65.14%  |
| 2      | 53        | 30.29%  |
| 3      | 8         | 4.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 60.92%  |
| Yes       | 68        | 39.08%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 144       | 82.76%  |
| No        | 30        | 17.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 98.85%  |
| No        | 2         | 1.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 78.09%  |
| No        | 39        | 21.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 57        | 32.2%   |
| Germany      | 12        | 6.78%   |
| France       | 10        | 5.65%   |
| UK           | 9         | 5.08%   |
| Spain        | 7         | 3.95%   |
| Netherlands  | 7         | 3.95%   |
| Russia       | 6         | 3.39%   |
| Brazil       | 6         | 3.39%   |
| India        | 5         | 2.82%   |
| Indonesia    | 4         | 2.26%   |
| Sweden       | 3         | 1.69%   |
| Poland       | 3         | 1.69%   |
| Kenya        | 3         | 1.69%   |
| Iraq         | 3         | 1.69%   |
| Denmark      | 3         | 1.69%   |
| Australia    | 3         | 1.69%   |
| Turkey       | 2         | 1.13%   |
| South Africa | 2         | 1.13%   |
| Mexico       | 2         | 1.13%   |
| Italy        | 2         | 1.13%   |
| Canada       | 2         | 1.13%   |
| Bangladesh   | 2         | 1.13%   |
| Switzerland  | 1         | 0.56%   |
| Puerto Rico  | 1         | 0.56%   |
| Portugal     | 1         | 0.56%   |
| Pakistan     | 1         | 0.56%   |
| Nigeria      | 1         | 0.56%   |
| New Zealand  | 1         | 0.56%   |
| Myanmar      | 1         | 0.56%   |
| Morocco      | 1         | 0.56%   |
| Latvia       | 1         | 0.56%   |
| Hungary      | 1         | 0.56%   |
| Greece       | 1         | 0.56%   |
| Georgia      | 1         | 0.56%   |
| Finland      | 1         | 0.56%   |
| Czechia      | 1         | 0.56%   |
| Croatia      | 1         | 0.56%   |
| Costa Rica   | 1         | 0.56%   |
| Colombia     | 1         | 0.56%   |
| Chile        | 1         | 0.56%   |
| Belgium      | 1         | 0.56%   |
| Belarus      | 1         | 0.56%   |
| Azerbaijan   | 1         | 0.56%   |
| Austria      | 1         | 0.56%   |
| Algeria      | 1         | 0.56%   |
| Unknown      | 1         | 0.56%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Amsterdam           | 4         | 2.2%    |
| Paris               | 3         | 1.65%   |
| Nairobi             | 3         | 1.65%   |
| Secaucus            | 2         | 1.1%    |
| Seattle             | 2         | 1.1%    |
| Sao Paulo           | 2         | 1.1%    |
| Mostoles            | 2         | 1.1%    |
| Houston             | 2         | 1.1%    |
| Dhaka               | 2         | 1.1%    |
| Dallas              | 2         | 1.1%    |
| Chicago             | 2         | 1.1%    |
| Camden              | 2         | 1.1%    |
| Berlin              | 2         | 1.1%    |
| Baghdad             | 2         | 1.1%    |
| Zurich              | 1         | 0.55%   |
| Zagreb              | 1         | 0.55%   |
| Yangon              | 1         | 0.55%   |
| Witbank             | 1         | 0.55%   |
| Wichita             | 1         | 0.55%   |
| West Jordan         | 1         | 0.55%   |
| West Islip          | 1         | 0.55%   |
| Waveland            | 1         | 0.55%   |
| Washington          | 1         | 0.55%   |
| Volgograd           | 1         | 0.55%   |
| Visalia             | 1         | 0.55%   |
| Vienna              | 1         | 0.55%   |
| Tulare              | 1         | 0.55%   |
| Ts'khinvali         | 1         | 0.55%   |
| Tottenham           | 1         | 0.55%   |
| Tempe               | 1         | 0.55%   |
| Tangier             | 1         | 0.55%   |
| Sydney              | 1         | 0.55%   |
| Surabaya            | 1         | 0.55%   |
| Sun City Center     | 1         | 0.55%   |
| Stockholm           | 1         | 0.55%   |
| St Petersburg       | 1         | 0.55%   |
| Spotsylvania        | 1         | 0.55%   |
| South Hamilton      | 1         | 0.55%   |
| Soro                | 1         | 0.55%   |
| Skive               | 1         | 0.55%   |
| Sinntal             | 1         | 0.55%   |
| Sheffield           | 1         | 0.55%   |
| Scotts Valley       | 1         | 0.55%   |
| Santo AndrГ©      | 1         | 0.55%   |
| Santa Monica        | 1         | 0.55%   |
| Sannois             | 1         | 0.55%   |
| San Marcos          | 1         | 0.55%   |
| Saint Clair         | 1         | 0.55%   |
| Ruskin              | 1         | 0.55%   |
| Rome                | 1         | 0.55%   |
| Romans-sur-IsГЁre | 1         | 0.55%   |
| Rio Bueno           | 1         | 0.55%   |
| Riga                | 1         | 0.55%   |
| Richmond            | 1         | 0.55%   |
| Regensburg          | 1         | 0.55%   |
| Reading             | 1         | 0.55%   |
| Puntarenas          | 1         | 0.55%   |
| Pretoria            | 1         | 0.55%   |
| Prague              | 1         | 0.55%   |
| Ponce               | 1         | 0.55%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 35        | 39     | 15.28%  |
| Samsung Electronics | 30        | 36     | 13.1%   |
| WDC                 | 28        | 34     | 12.23%  |
| Seagate             | 20        | 20     | 8.73%   |
| Unknown             | 19        | 20     | 8.3%    |
| Kingston            | 16        | 16     | 6.99%   |
| SanDisk             | 10        | 12     | 4.37%   |
| Crucial             | 10        | 15     | 4.37%   |
| Hitachi             | 8         | 10     | 3.49%   |
| HGST                | 6         | 8      | 2.62%   |
| Micron Technology   | 5         | 5      | 2.18%   |
| Apple               | 5         | 5      | 2.18%   |
| SK Hynix            | 4         | 4      | 1.75%   |
| China               | 4         | 4      | 1.75%   |
| A-DATA Technology   | 4         | 4      | 1.75%   |
| Intel               | 3         | 3      | 1.31%   |
| LITEON              | 2         | 2      | 0.87%   |
| KIOXIA              | 2         | 2      | 0.87%   |
| HUAWEI              | 2         | 2      | 0.87%   |
| W800SH              | 1         | 1      | 0.44%   |
| Transcend           | 1         | 1      | 0.44%   |
| Team                | 1         | 1      | 0.44%   |
| Silicon Motion      | 1         | 1      | 0.44%   |
| PNY                 | 1         | 1      | 0.44%   |
| Phison              | 1         | 1      | 0.44%   |
| Patriot             | 1         | 1      | 0.44%   |
| Netac               | 1         | 1      | 0.44%   |
| LITEONIT            | 1         | 1      | 0.44%   |
| Lexar               | 1         | 1      | 0.44%   |
| KingSpec            | 1         | 2      | 0.44%   |
| Intenso             | 1         | 2      | 0.44%   |
| Fujitsu             | 1         | 1      | 0.44%   |
| Corsair             | 1         | 2      | 0.44%   |
| BHT                 | 1         | 1      | 0.44%   |
| ASMedia             | 1         | 1      | 0.44%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB               | 8         | 3.36%   |
| Toshiba MQ01ABF050 500GB             | 6         | 2.52%   |
| Toshiba MQ01ABD100 1TB               | 4         | 1.68%   |
| Samsung SSD 860 EVO 500GB            | 4         | 1.68%   |
| Unknown MMC Card  32GB               | 3         | 1.26%   |
| Toshiba MQ01ABD075 752GB             | 3         | 1.26%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 3         | 1.26%   |
| Seagate ST1000LM035-1RK172 1TB       | 3         | 1.26%   |
| SanDisk SSD PLUS 1000GB              | 3         | 1.26%   |
| Kingston NVMe SSD Drive 512GB        | 3         | 1.26%   |
| HGST HTS541010A9E680 1TB             | 3         | 1.26%   |
| WDC WD5000LPCX-24C6HT0 500GB         | 2         | 0.84%   |
| WDC WD10SPZX-75Z10T2 1TB             | 2         | 0.84%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 0.84%   |
| Seagate ST9250315AS 250GB            | 2         | 0.84%   |
| Seagate ST320LT007-9ZV142 320GB      | 2         | 0.84%   |
| Sandisk NVMe SSD Drive 256GB         | 2         | 0.84%   |
| Samsung SSD 980 1TB                  | 2         | 0.84%   |
| Samsung SSD 850 EVO 250GB            | 2         | 0.84%   |
| Samsung HM500JI 500GB                | 2         | 0.84%   |
| Kingston SV300S37A240G 240GB SSD     | 2         | 0.84%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.84%   |
| Kingston SA400S37240G 240GB SSD      | 2         | 0.84%   |
| HGST HTS721010A9E630 1TB             | 2         | 0.84%   |
| Crucial CT500MX500SSD1 500GB         | 2         | 0.84%   |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.84%   |
| Apple SSD SM0256G 256GB              | 2         | 0.84%   |
| WDC WDS500G2B0A-00SM50 500GB SSD     | 1         | 0.42%   |
| WDC WDS100T2B0C-00PXH0 1TB           | 1         | 0.42%   |
| WDC WDS100T2B0B-00YS70 1TB SSD       | 1         | 0.42%   |
| WDC WDBNCE2500PNC 250GB SSD          | 1         | 0.42%   |
| WDC WD800BEVS-22RST0 80GB            | 1         | 0.42%   |
| WDC WD7500BPVX-22JC3T0 752GB         | 1         | 0.42%   |
| WDC WD6400BPVT-75HXZT1 640GB         | 1         | 0.42%   |
| WDC WD5000LPVT-16G33T0 500GB         | 1         | 0.42%   |
| WDC WD5000LPLX-08ZNTT0 500GB         | 1         | 0.42%   |
| WDC WD5000LPCX-24VHAT0 500GB         | 1         | 0.42%   |
| WDC WD3200LPVX-00V0TT0 320GB         | 1         | 0.42%   |
| WDC WD3200BPVT-22JJ5T0 320GB         | 1         | 0.42%   |
| WDC WD3200BPVT-00HXZT1 320GB         | 1         | 0.42%   |
| WDC WD3200BEVT-60A23T0 320GB         | 1         | 0.42%   |
| WDC WD2500BPVT-00JJ5T0 250GB         | 1         | 0.42%   |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 0.42%   |
| WDC WD10SPZX-21Z 1TB                 | 1         | 0.42%   |
| WDC WD10SPZX-17Z10T1 1TB             | 1         | 0.42%   |
| WDC WD10SPZX-08Z10 1TB               | 1         | 0.42%   |
| WDC WD10SPCX-24HWST1 1TB             | 1         | 0.42%   |
| WDC WD10S21X-24R1BT0-SSHD-8GB        | 1         | 0.42%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB | 1         | 0.42%   |
| WDC PC SN730 SDBPNTY-512G-1032 512GB | 1         | 0.42%   |
| WDC PC SN720 SDAPNTW-512G-1014 512GB | 1         | 0.42%   |
| W800SH 512GB SSD                     | 1         | 0.42%   |
| Unknown Y016B  16GB                  | 1         | 0.42%   |
| Unknown xD/SD/M.S.                   | 1         | 0.42%   |
| Unknown SS16G  16GB                  | 1         | 0.42%   |
| Unknown SS08G  8GB                   | 1         | 0.42%   |
| Unknown SDU1  64GB                   | 1         | 0.42%   |
| Unknown SD64G  64GB                  | 1         | 0.42%   |
| Unknown SD/MMC/MS PRO 394GB          | 1         | 0.42%   |
| Unknown SD  4GB                      | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 29        | 32     | 31.18%  |
| WDC                 | 23        | 27     | 24.73%  |
| Seagate             | 20        | 20     | 21.51%  |
| Hitachi             | 8         | 10     | 8.6%    |
| HGST                | 6         | 8      | 6.45%   |
| Samsung Electronics | 4         | 4      | 4.3%    |
| Unknown             | 1         | 1      | 1.08%   |
| Fujitsu             | 1         | 1      | 1.08%   |
| ASMedia             | 1         | 1      | 1.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 16        | 19     | 21.05%  |
| Kingston            | 9         | 9      | 11.84%  |
| Crucial             | 9         | 14     | 11.84%  |
| SanDisk             | 6         | 7      | 7.89%   |
| Toshiba             | 4         | 5      | 5.26%   |
| China               | 4         | 4      | 5.26%   |
| Apple               | 4         | 4      | 5.26%   |
| WDC                 | 3         | 3      | 3.95%   |
| Micron Technology   | 3         | 3      | 3.95%   |
| LITEON              | 2         | 2      | 2.63%   |
| Intel               | 2         | 2      | 2.63%   |
| A-DATA Technology   | 2         | 2      | 2.63%   |
| W800SH              | 1         | 1      | 1.32%   |
| Unknown             | 1         | 1      | 1.32%   |
| Transcend           | 1         | 1      | 1.32%   |
| Team                | 1         | 1      | 1.32%   |
| PNY                 | 1         | 1      | 1.32%   |
| Patriot             | 1         | 1      | 1.32%   |
| Netac               | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| KingSpec            | 1         | 2      | 1.32%   |
| Intenso             | 1         | 2      | 1.32%   |
| Corsair             | 1         | 2      | 1.32%   |
| BHT                 | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 91        | 104    | 41.55%  |
| SSD     | 69        | 89     | 31.51%  |
| NVMe    | 40        | 46     | 18.26%  |
| MMC     | 16        | 18     | 7.31%   |
| Unknown | 3         | 3      | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 143       | 185    | 68.42%  |
| NVMe | 40        | 46     | 19.14%  |
| MMC  | 16        | 18     | 7.66%   |
| SAS  | 10        | 11     | 4.78%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 98        | 124    | 60.87%  |
| 0.51-1.0   | 57        | 62     | 35.4%   |
| 1.01-2.0   | 6         | 7      | 3.73%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 44        | 25.14%  |
| 101-250        | 40        | 22.86%  |
| 501-1000       | 26        | 14.86%  |
| 1001-2000      | 21        | 12%     |
| 21-50          | 12        | 6.86%   |
| Unknown        | 12        | 6.86%   |
| 51-100         | 11        | 6.29%   |
| 2001-3000      | 4         | 2.29%   |
| More than 3000 | 3         | 1.71%   |
| 1-20           | 2         | 1.14%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 53        | 29.28%  |
| 51-100         | 37        | 20.44%  |
| 1-20           | 31        | 17.13%  |
| 251-500        | 20        | 11.05%  |
| 101-250        | 20        | 11.05%  |
| Unknown        | 12        | 6.63%   |
| 501-1000       | 6         | 3.31%   |
| More than 3000 | 1         | 0.55%   |
| 1001-2000      | 1         | 0.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB                   | 2         | 2      | 11.11%  |
| WDC WD2500BEVT-22A23T0 250GB                        | 1         | 1      | 5.56%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 5.56%   |
| Toshiba MK3265GSXF 320GB                            | 1         | 1      | 5.56%   |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 5.56%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 5.56%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 5.56%   |
| Samsung Electronics HM160HI 160GB                   | 1         | 1      | 5.56%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 5.56%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 5.56%   |
| Hitachi HTS725050A9A360 500GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 5.56%   |
| Hitachi HTS542512K9SA00 120GB                       | 1         | 1      | 5.56%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 5.56%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 5.56%   |
| A-DATA Technology SX6000LNP 1TB                     | 1         | 1      | 5.56%   |
| A-DATA Technology SU700 120GB SSD                   | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 22.22%  |
| Hitachi             | 3         | 3      | 16.67%  |
| Toshiba             | 2         | 2      | 11.11%  |
| Seagate             | 2         | 2      | 11.11%  |
| A-DATA Technology   | 2         | 2      | 11.11%  |
| WDC                 | 1         | 1      | 5.56%   |
| Micron Technology   | 1         | 1      | 5.56%   |
| LITEON              | 1         | 1      | 5.56%   |
| HGST                | 1         | 1      | 5.56%   |
| Fujitsu             | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 23.08%  |
| Hitachi             | 3         | 3      | 23.08%  |
| Toshiba             | 2         | 2      | 15.38%  |
| Seagate             | 2         | 2      | 15.38%  |
| WDC                 | 1         | 1      | 7.69%   |
| HGST                | 1         | 1      | 7.69%   |
| Fujitsu             | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 72.22%  |
| SSD  | 4         | 4      | 22.22%  |
| NVMe | 1         | 1      | 5.56%   |

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
| Detected | 91        | 138    | 47.64%  |
| Works    | 83        | 104    | 43.46%  |
| Malfunc  | 17        | 18     | 8.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 130       | 65.99%  |
| AMD                          | 21        | 10.66%  |
| Samsung Electronics          | 13        | 6.6%    |
| Sandisk                      | 7         | 3.55%   |
| Kingston Technology Company  | 7         | 3.55%   |
| SK Hynix                     | 4         | 2.03%   |
| Toshiba America Info Systems | 2         | 1.02%   |
| Silicon Motion               | 2         | 1.02%   |
| Nvidia                       | 2         | 1.02%   |
| Micron Technology            | 2         | 1.02%   |
| KIOXIA                       | 2         | 1.02%   |
| Realtek Semiconductor        | 1         | 0.51%   |
| Phison Electronics           | 1         | 0.51%   |
| Micron/Crucial Technology    | 1         | 0.51%   |
| Apple                        | 1         | 0.51%   |
| ADATA Technology             | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 17        | 7.98%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 16        | 7.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 15        | 7.04%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 14        | 6.57%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 12        | 5.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 4.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 9         | 4.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 8         | 3.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 3.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 4         | 1.88%   |
| SK Hynix BC511                                                                         | 3         | 1.41%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 3         | 1.41%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 1.41%   |
| Kingston Company Company Non-Volatile memory controller                                | 3         | 1.41%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.41%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 3         | 1.41%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 3         | 1.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 3         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.41%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 2         | 0.94%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 0.94%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 2         | 0.94%   |
| Samsung Electronics SATA controller                                                    | 2         | 0.94%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.94%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.94%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 2         | 0.94%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.94%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 2         | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.94%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 0.94%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 2         | 0.94%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 2         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 2         | 0.94%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 2         | 0.94%   |
| SK Hynix Gold P31 SSD                                                                  | 1         | 0.47%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 1         | 0.47%   |
| Sandisk PC SN520 NVMe SSD                                                              | 1         | 0.47%   |
| Sandisk Non-Volatile memory controller                                                 | 1         | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.47%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 0.47%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 1         | 0.47%   |
| Phison E12 NVMe Controller                                                             | 1         | 0.47%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.47%   |
| Nvidia MCP89 SATA Controller                                                           | 1         | 0.47%   |
| Micron/Crucial NVMe Controller                                                         | 1         | 0.47%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 1         | 0.47%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 1         | 0.47%   |
| Intel SSD 600P Series                                                                  | 1         | 0.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 1         | 0.47%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 1         | 0.47%   |
| Intel Comet Lake PCH-H RAID                                                            | 1         | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.47%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.47%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 127       | 62.56%  |
| NVMe | 40        | 19.7%   |
| RAID | 19        | 9.36%   |
| IDE  | 17        | 8.37%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 148       | 85.06%  |
| AMD    | 26        | 14.94%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 2.87%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 5         | 2.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.3%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 2.3%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 1.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 1.72%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 1.72%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.72%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.72%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 3         | 1.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.72%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 3         | 1.72%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.15%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.15%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 1.15%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 1.15%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 1.15%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 2         | 1.15%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 1.15%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 2         | 1.15%   |
| Intel Core i5-4310U CPU @ 2.00GHz             | 2         | 1.15%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 1.15%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 2         | 1.15%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.15%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 2         | 1.15%   |
| Intel Core 2 CPU T5600 @ 1.83GHz              | 2         | 1.15%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 2         | 1.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.15%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.15%   |
| AMD E1-2500 APU with Radeon HD Graphics       | 2         | 1.15%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.57%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.57%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.57%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 1         | 0.57%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.57%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.57%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 1         | 0.57%   |
| Intel Core i7-4770HQ CPU @ 2.20GHz            | 1         | 0.57%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.57%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 1         | 0.57%   |
| Intel Core i7-4558U CPU @ 2.80GHz             | 1         | 0.57%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 1         | 0.57%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 1         | 0.57%   |
| Intel Core i7-2720QM CPU @ 2.20GHz            | 1         | 0.57%   |
| Intel Core i7-10875H CPU @ 2.30GHz            | 1         | 0.57%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 1         | 0.57%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.57%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 1         | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 55        | 31.61%  |
| Intel Core i7           | 48        | 27.59%  |
| Intel Core i3           | 14        | 8.05%   |
| Intel Celeron           | 8         | 4.6%    |
| Other                   | 7         | 4.02%   |
| AMD Ryzen 7             | 7         | 4.02%   |
| Intel Core 2 Duo        | 6         | 3.45%   |
| AMD A6                  | 5         | 2.87%   |
| Intel Core 2            | 3         | 1.72%   |
| AMD E1                  | 3         | 1.72%   |
| Intel Pentium Silver    | 2         | 1.15%   |
| Intel Pentium           | 2         | 1.15%   |
| Intel Atom              | 2         | 1.15%   |
| AMD Ryzen 3             | 2         | 1.15%   |
| AMD A4                  | 2         | 1.15%   |
| Intel Pentium Dual-Core | 1         | 0.57%   |
| Intel Core 2 Quad       | 1         | 0.57%   |
| Intel Core 2 Extreme    | 1         | 0.57%   |
| AMD Ryzen 5             | 1         | 0.57%   |
| AMD E2                  | 1         | 0.57%   |
| AMD E                   | 1         | 0.57%   |
| AMD C-50                | 1         | 0.57%   |
| AMD Athlon X2           | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 57.47%  |
| 4      | 51        | 29.31%  |
| 6      | 13        | 7.47%   |
| 8      | 8         | 4.6%    |
| 1      | 2         | 1.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 174       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 130       | 74.71%  |
| 1      | 44        | 25.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 169       | 97.13%  |
| Unknown        | 5         | 2.87%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 46.63%  |
| 0x206a7    | 13        | 7.3%    |
| 0x906ea    | 7         | 3.93%   |
| 0x306a9    | 7         | 3.93%   |
| 0x806e9    | 6         | 3.37%   |
| 0xa0652    | 5         | 2.81%   |
| 0x806ea    | 5         | 2.81%   |
| 0x806ec    | 4         | 2.25%   |
| 0x1067a    | 4         | 2.25%   |
| 0x806c1    | 3         | 1.69%   |
| 0x6f6      | 3         | 1.69%   |
| 0x40651    | 3         | 1.69%   |
| 0x306c3    | 3         | 1.69%   |
| 0x07030105 | 3         | 1.69%   |
| 0x706e5    | 2         | 1.12%   |
| 0x706a8    | 2         | 1.12%   |
| 0x406e3    | 2         | 1.12%   |
| 0x406c4    | 2         | 1.12%   |
| 0x306d4    | 2         | 1.12%   |
| 0x06006705 | 2         | 1.12%   |
| 0x03000027 | 2         | 1.12%   |
| 0x906ed    | 1         | 0.56%   |
| 0x906e9    | 1         | 0.56%   |
| 0x806d1    | 1         | 0.56%   |
| 0x706a1    | 1         | 0.56%   |
| 0x6fd      | 1         | 0.56%   |
| 0x506e3    | 1         | 0.56%   |
| 0x506c9    | 1         | 0.56%   |
| 0x40661    | 1         | 0.56%   |
| 0x20655    | 1         | 0.56%   |
| 0x08600106 | 1         | 0.56%   |
| 0x08108109 | 1         | 0.56%   |
| 0x08108102 | 1         | 0.56%   |
| 0x0810100b | 1         | 0.56%   |
| 0x06001119 | 1         | 0.56%   |
| 0x05000029 | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 35        | 20.11%  |
| SandyBridge     | 19        | 10.92%  |
| Haswell         | 17        | 9.77%   |
| IvyBridge       | 14        | 8.05%   |
| Broadwell       | 10        | 5.75%   |
| Skylake         | 9         | 5.17%   |
| Silvermont      | 8         | 4.6%    |
| Penryn          | 8         | 4.6%    |
| CometLake       | 7         | 4.02%   |
| Core            | 5         | 2.87%   |
| Zen+            | 4         | 2.3%    |
| Westmere        | 4         | 2.3%    |
| TigerLake       | 4         | 2.3%    |
| IceLake         | 4         | 2.3%    |
| Excavator       | 4         | 2.3%    |
| Puma            | 3         | 1.72%   |
| Jaguar          | 3         | 1.72%   |
| Goldmont plus   | 3         | 1.72%   |
| Unknown         | 3         | 1.72%   |
| K10 Llano       | 2         | 1.15%   |
| Bobcat          | 2         | 1.15%   |
| Zen 3           | 1         | 0.57%   |
| Zen 2           | 1         | 0.57%   |
| Zen             | 1         | 0.57%   |
| Piledriver      | 1         | 0.57%   |
| K8 & K10 hybrid | 1         | 0.57%   |
| Goldmont        | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 136       | 59.39%  |
| Nvidia | 53        | 23.14%  |
| AMD    | 40        | 17.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 6.84%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 5.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 12        | 5.13%   |
| Intel HD Graphics 5500                                                                   | 9         | 3.85%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 3.85%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 2.99%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.99%   |
| Intel HD Graphics 620                                                                    | 7         | 2.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 2.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 2.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 2.14%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 2.14%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 1.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.71%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.71%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.71%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.71%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 3         | 1.28%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.28%   |
| AMD Lucienne                                                                             | 3         | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.85%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.85%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.85%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.85%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.85%   |
| Nvidia GK107M [GeForce GT 650M]                                                          | 2         | 0.85%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 2         | 0.85%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.85%   |
| Intel HD Graphics 530                                                                    | 2         | 0.85%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 0.85%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 2         | 0.85%   |
| AMD Sumo [Radeon HD 6520G]                                                               | 2         | 0.85%   |
| AMD RV515/M54 [Mobility Radeon X1400]                                                    | 2         | 0.85%   |
| AMD Kabini [Radeon HD 8240 / R3 Series]                                                  | 2         | 0.85%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.43%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.43%   |
| Nvidia TU117M                                                                            | 1         | 0.43%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 1         | 0.43%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 1         | 0.43%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 1         | 0.43%   |
| Nvidia GT218M [GeForce 315M]                                                             | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.43%   |
| Nvidia GP108M [GeForce MX230]                                                            | 1         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 0.43%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.43%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.43%   |
| Nvidia GM108M [GeForce MX130]                                                            | 1         | 0.43%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 1         | 0.43%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.43%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.43%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 1         | 0.43%   |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 1         | 0.43%   |
| Nvidia GM107M [GeForce GTX 850M]                                                         | 1         | 0.43%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.43%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 82        | 47.13%  |
| Intel + Nvidia | 45        | 25.86%  |
| 1 x AMD        | 29        | 16.67%  |
| Intel + AMD    | 9         | 5.17%   |
| 1 x Nvidia     | 7         | 4.02%   |
| 2 x AMD        | 1         | 0.57%   |
| AMD + Nvidia   | 1         | 0.57%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 163       | 93.68%  |
| Proprietary | 11        | 6.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 75.57%  |
| 1.01-2.0   | 14        | 7.95%   |
| 0.01-0.5   | 11        | 6.25%   |
| 0.51-1.0   | 8         | 4.55%   |
| 3.01-4.0   | 6         | 3.41%   |
| 5.01-6.0   | 2         | 1.14%   |
| 7.01-8.0   | 1         | 0.57%   |
| 2.01-3.0   | 1         | 0.57%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 44        | 23.28%  |
| LG Display              | 35        | 18.52%  |
| Chimei Innolux          | 28        | 14.81%  |
| BOE                     | 24        | 12.7%   |
| Samsung Electronics     | 17        | 8.99%   |
| Apple                   | 9         | 4.76%   |
| Chi Mei Optoelectronics | 7         | 3.7%    |
| PANDA                   | 3         | 1.59%   |
| Dell                    | 3         | 1.59%   |
| Acer                    | 3         | 1.59%   |
| Sharp                   | 2         | 1.06%   |
| Lenovo                  | 2         | 1.06%   |
| Ancor Communications    | 2         | 1.06%   |
| Unknown (AAA)           | 1         | 0.53%   |
| STA                     | 1         | 0.53%   |
| Sanyo                   | 1         | 0.53%   |
| Philips                 | 1         | 0.53%   |
| Panasonic               | 1         | 0.53%   |
| ONN                     | 1         | 0.53%   |
| Kogan                   | 1         | 0.53%   |
| Eizo                    | 1         | 0.53%   |
| CSO                     | 1         | 0.53%   |
| BenQ                    | 1         | 0.53%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 1.59%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 1.59%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 2         | 1.06%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch  | 2         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch  | 2         | 1.06%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1.06%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch          | 2         | 1.06%   |
| LG Display LCD Monitor LGD0390 1600x900 382x215mm 17.3-inch           | 2         | 1.06%   |
| LG Display LCD Monitor LGD01E9 1920x1080 345x194mm 15.6-inch          | 2         | 1.06%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch      | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 2         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 2         | 1.06%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                 | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 1.06%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 2         | 1.06%   |
| Unknown (AAA) LCDTV AAA0042 1360x768 890x500mm 40.2-inch              | 1         | 0.53%   |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                    | 1         | 0.53%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.53%   |
| Sharp LCD Monitor SHP143A 3840x2160 346x194mm 15.6-inch               | 1         | 0.53%   |
| Sanyo LCD SAN0B51 1920x540                                            | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0589 1920x1080 521x293mm 23.5-inch  | 1         | 0.53%   |
| Samsung Electronics S27E510 SAM0C5F 1920x1080 600x340mm 27.2-inch     | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 353x198mm 15.9-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3942 1366x768 309x174mm 14.0-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC314A 1920x1080 408x230mm 18.4-inch | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC3652 1366x768 344x194mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SAM0F3D 1366x768 522x293mm 23.6-inch  | 1         | 0.53%   |
| Philips PHL 276E9Q PHLC17B 1920x1080 598x336mm 27.0-inch              | 1         | 0.53%   |
| PANDA LCD Monitor NCP004B 1920x1080 344x194mm 15.5-inch               | 1         | 0.53%   |
| Panasonic LCD Monitor MEI96A2 2880x1620 344x193mm 15.5-inch           | 1         | 0.53%   |
| ONN ONA18HO015 ONN0101 1920x1080 698x393mm 31.5-inch                  | 1         | 0.53%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 1         | 0.53%   |
| LG Display LP154WX4-TLCC LGD0242 1280x800 331x207mm 15.4-inch         | 1         | 0.53%   |
| LG Display LCD Monitor LGD0690 2560x1440 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD05D2 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0589 1920x1080 294x165mm 13.3-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0557 1920x1080 309x174mm 14.0-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD0503 1366x768 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD04FA 1366x768 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD045A 1366x768 293x165mm 13.2-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD03FD 1920x1080 276x156mm 12.5-inch          | 1         | 0.53%   |
| LG Display LCD Monitor LGD03F8 1366x768 345x194mm 15.6-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD03E5 1366x768 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD0353 1366x768 345x194mm 15.6-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch           | 1         | 0.53%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 72        | 39.78%  |
| 1366x768 (WXGA)    | 65        | 35.91%  |
| 1600x900 (HD+)     | 15        | 8.29%   |
| 1280x800 (WXGA)    | 10        | 5.52%   |
| 3840x2160 (4K)     | 3         | 1.66%   |
| 1680x1050 (WSXGA+) | 3         | 1.66%   |
| 1440x900 (WXGA+)   | 3         | 1.66%   |
| 2880x1800          | 2         | 1.1%    |
| 2160x1440          | 2         | 1.1%    |
| 2560x1600          | 1         | 0.55%   |
| 2560x1440 (QHD)    | 1         | 0.55%   |
| 1920x540           | 1         | 0.55%   |
| 1920x1200 (WUXGA)  | 1         | 0.55%   |
| 1280x1024 (SXGA)   | 1         | 0.55%   |
| 1024x768 (XGA)     | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 79        | 42.25%  |
| 13      | 27        | 14.44%  |
| 14      | 26        | 13.9%   |
| 17      | 22        | 11.76%  |
| 12      | 8         | 4.28%   |
| 27      | 4         | 2.14%   |
| 11      | 4         | 2.14%   |
| 22      | 3         | 1.6%    |
| 21      | 3         | 1.6%    |
| 31      | 2         | 1.07%   |
| 24      | 2         | 1.07%   |
| 23      | 2         | 1.07%   |
| 18      | 2         | 1.07%   |
| 40      | 1         | 0.53%   |
| 19      | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 122       | 65.59%  |
| 351-400     | 24        | 12.9%   |
| 201-300     | 21        | 11.29%  |
| 501-600     | 8         | 4.3%    |
| 401-500     | 7         | 3.76%   |
| 601-700     | 2         | 1.08%   |
| 801-900     | 1         | 0.54%   |
| Unknown     | 1         | 0.54%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 152       | 85.88%  |
| 16/10 | 20        | 11.3%   |
| 3/2   | 2         | 1.13%   |
| 6/5   | 1         | 0.56%   |
| 4/3   | 1         | 0.56%   |
| 32/9  | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 79        | 42.25%  |
| 81-90          | 46        | 24.6%   |
| 121-130        | 19        | 10.16%  |
| 201-250        | 10        | 5.35%   |
| 61-70          | 8         | 4.28%   |
| 71-80          | 7         | 3.74%   |
| 51-60          | 4         | 2.14%   |
| 301-350        | 4         | 2.14%   |
| 131-140        | 3         | 1.6%    |
| 351-500        | 2         | 1.07%   |
| 141-150        | 2         | 1.07%   |
| 151-200        | 1         | 0.53%   |
| 501-1000       | 1         | 0.53%   |
| Unknown        | 1         | 0.53%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 77        | 41.4%   |
| 101-120       | 69        | 37.1%   |
| 51-100        | 24        | 12.9%   |
| 161-240       | 10        | 5.38%   |
| More than 240 | 3         | 1.61%   |
| 1-50          | 2         | 1.08%   |
| Unknown       | 1         | 0.54%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 154       | 88%     |
| 2     | 19        | 10.86%  |
| 3     | 2         | 1.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 93        | 31.42%  |
| Intel                                  | 93        | 31.42%  |
| Qualcomm Atheros                       | 41        | 13.85%  |
| Broadcom                               | 22        | 7.43%   |
| Broadcom Limited                       | 7         | 2.36%   |
| Samsung Electronics                    | 5         | 1.69%   |
| MEDIATEK                               | 5         | 1.69%   |
| Huawei Technologies                    | 4         | 1.35%   |
| Xiaomi                                 | 3         | 1.01%   |
| Ralink Technology                      | 3         | 1.01%   |
| Qualcomm Atheros Communications        | 3         | 1.01%   |
| TP-Link                                | 2         | 0.68%   |
| NetGear                                | 2         | 0.68%   |
| ASUSTek Computer                       | 2         | 0.68%   |
| ASIX Electronics                       | 2         | 0.68%   |
| ZyXEL Communications                   | 1         | 0.34%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.34%   |
| Sagem                                  | 1         | 0.34%   |
| Ralink                                 | 1         | 0.34%   |
| Nvidia                                 | 1         | 0.34%   |
| Linksys                                | 1         | 0.34%   |
| Ericsson Business Mobile Networks      | 1         | 0.34%   |
| Arduino SA                             | 1         | 0.34%   |
| Apple                                  | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 47        | 13.02%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 25        | 6.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.94%   |
| Intel Wireless 7265                                                     | 7         | 1.94%   |
| Intel Wireless 7260                                                     | 7         | 1.94%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 1.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 1.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.66%   |
| Intel Wireless 8265 / 8275                                              | 6         | 1.66%   |
| Intel Ethernet Connection I218-LM                                       | 6         | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller               | 5         | 1.39%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.39%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 4         | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 4         | 1.11%   |
| Intel Wireless 3165                                                     | 4         | 1.11%   |
| Intel Wireless 3160                                                     | 4         | 1.11%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.11%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.11%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.11%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 0.83%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.83%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 0.83%   |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                           | 3         | 0.83%   |
| Intel Wireless 8260                                                     | 3         | 0.83%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 0.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 2         | 0.55%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.55%   |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.55%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 2         | 0.55%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 2         | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.55%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 2         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 2         | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.55%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.55%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                   | 2         | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 0.55%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.55%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 0.55%   |
| Intel Centrino Advanced-N 6235                                          | 2         | 0.55%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 89        | 44.5%   |
| Realtek Semiconductor           | 36        | 18%     |
| Qualcomm Atheros                | 30        | 15%     |
| Broadcom                        | 19        | 9.5%    |
| Broadcom Limited                | 6         | 3%      |
| MEDIATEK                        | 4         | 2%      |
| Ralink Technology               | 3         | 1.5%    |
| Qualcomm Atheros Communications | 3         | 1.5%    |
| TP-Link                         | 2         | 1%      |
| NetGear                         | 2         | 1%      |
| ASUSTek Computer                | 2         | 1%      |
| ZyXEL Communications            | 1         | 0.5%    |
| Sagem                           | 1         | 0.5%    |
| Ralink                          | 1         | 0.5%    |
| Linksys                         | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 3.5%    |
| Intel Wireless 7265                                                     | 7         | 3.5%    |
| Intel Wireless 7260                                                     | 7         | 3.5%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 7         | 3.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 7         | 3.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 3%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3%      |
| Intel Wireless 8265 / 8275                                              | 6         | 3%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.5%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.5%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 2.5%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 2%      |
| Intel Wireless 3165                                                     | 4         | 2%      |
| Intel Wireless 3160                                                     | 4         | 2%      |
| Intel Wi-Fi 6 AX201                                                     | 4         | 2%      |
| Intel Wi-Fi 6 AX200                                                     | 4         | 2%      |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 2%      |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                 | 3         | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 3         | 1.5%    |
| Realtek 802.11ac NIC                                                    | 3         | 1.5%    |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 1.5%    |
| MEDIATEK RZ608 Wi-Fi 6E 80MHz                                           | 3         | 1.5%    |
| Intel Wireless 8260                                                     | 3         | 1.5%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.5%    |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.5%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.5%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1%      |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 1%      |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                         | 2         | 1%      |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 1%      |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1%      |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 1%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1%      |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 1%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1%      |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2         | 1%      |
| Intel Centrino Wireless-N 2230                                          | 2         | 1%      |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 2         | 1%      |
| Intel Centrino Advanced-N 6235                                          | 2         | 1%      |
| Intel Centrino Advanced-N 6200                                          | 2         | 1%      |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 1%      |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1%      |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 1%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 2         | 1%      |
| ZyXEL NWD2205 802.11n Wireless N Adapter [Realtek RTL8192CU]            | 1         | 0.5%    |
| Sagem XG-76NA 802.11bg                                                  | 1         | 0.5%    |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1         | 0.5%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.5%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                     | 1         | 0.5%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 1         | 0.5%    |
| Realtek RTL8187 Wireless Adapter                                        | 1         | 0.5%    |
| Ralink RT5372 Wireless Adapter                                          | 1         | 0.5%    |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 1         | 0.5%    |
| Ralink MT7610U ("Archer T2U" 2.4G+5G WLAN Adapter                       | 1         | 0.5%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 1         | 0.5%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 82        | 53.95%  |
| Intel                 | 31        | 20.39%  |
| Qualcomm Atheros      | 17        | 11.18%  |
| Broadcom              | 7         | 4.61%   |
| Samsung Electronics   | 5         | 3.29%   |
| Xiaomi                | 3         | 1.97%   |
| ASIX Electronics      | 2         | 1.32%   |
| Nvidia                | 1         | 0.66%   |
| MediaTek              | 1         | 0.66%   |
| Huawei Technologies   | 1         | 0.66%   |
| Broadcom Limited      | 1         | 0.66%   |
| Apple                 | 1         | 0.66%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 30.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 25        | 16.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 4.52%   |
| Intel Ethernet Connection I218-LM                                 | 6         | 3.87%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 5         | 3.23%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 4         | 2.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 2.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.29%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 1.29%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.29%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.29%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 1.29%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.29%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.29%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 1.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.29%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 1.29%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.65%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.65%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.65%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.65%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.65%   |
| MediaTek B140DL                                                   | 1         | 0.65%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.65%   |
| Intel Ethernet controller                                         | 1         | 0.65%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.65%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 1         | 0.65%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.65%   |
| Huawei JAT-LX1                                                    | 1         | 0.65%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 1         | 0.65%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.65%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe         | 1         | 0.65%   |
| ASIX AX88772A Fast Ethernet                                       | 1         | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1         | 0.65%   |
| Apple T2 Controller                                               | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 173       | 53.73%  |
| Ethernet | 143       | 44.41%  |
| Modem    | 5         | 1.55%   |
| Unknown  | 1         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 150       | 68.49%  |
| Ethernet | 68        | 31.05%  |
| Unknown  | 1         | 0.46%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 129       | 74.14%  |
| 1     | 41        | 23.56%  |
| 3     | 2         | 1.15%   |
| 0     | 2         | 1.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 151       | 85.31%  |
| Yes     | 25        | 14.12%  |
| Unknown | 1         | 0.56%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 67        | 48.2%   |
| Realtek Semiconductor           | 14        | 10.07%  |
| Qualcomm Atheros Communications | 14        | 10.07%  |
| Broadcom                        | 12        | 8.63%   |
| Lite-On Technology              | 6         | 4.32%   |
| Foxconn / Hon Hai               | 6         | 4.32%   |
| Apple                           | 6         | 4.32%   |
| MediaTek                        | 3         | 2.16%   |
| IMC Networks                    | 3         | 2.16%   |
| Cambridge Silicon Radio         | 3         | 2.16%   |
| Dell                            | 2         | 1.44%   |
| Toshiba                         | 1         | 0.72%   |
| Ralink                          | 1         | 0.72%   |
| Dynex                           | 1         | 0.72%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 30        | 21.58%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 9.35%   |
| Intel Bluetooth Device                                                              | 12        | 8.63%   |
| Realtek Bluetooth Radio                                                             | 6         | 4.32%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 4.32%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 3.6%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 4         | 2.88%   |
| Intel AX200 Bluetooth                                                               | 4         | 2.88%   |
| Apple Bluetooth Host Controller                                                     | 4         | 2.88%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 3         | 2.16%   |
| MediaTek Wireless_Device                                                            | 3         | 2.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 2.16%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 2.16%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 2.16%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.44%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.44%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 1.44%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.44%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.44%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 2         | 1.44%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 1.44%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.44%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.44%   |
| Apple Bluetooth USB Host Controller                                                 | 2         | 1.44%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.72%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.72%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.72%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.72%   |
| Lite-On Wireless_Device                                                             | 1         | 0.72%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.72%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.72%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.72%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.72%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.72%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.72%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.72%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.72%   |
| Dynex BCM20702A0                                                                    | 1         | 0.72%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.72%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.72%   |
| Broadcom BCM20702A0                                                                 | 1         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.72%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor    | Notebooks | Percent |
|-----------|-----------|---------|
| Intel     | 143       | 69.76%  |
| Nvidia    | 30        | 14.63%  |
| AMD       | 29        | 14.15%  |
| Guillemot | 1         | 0.49%   |
| GN Netcom | 1         | 0.49%   |
| Apple     | 1         | 0.49%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 21        | 8.2%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 7.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 14        | 5.47%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 12        | 4.69%   |
| Intel 8 Series HD Audio Controller                                                                | 12        | 4.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 3.91%   |
| Intel Cannon Lake PCH cAVS                                                                        | 10        | 3.91%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 3.91%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 10        | 3.91%   |
| AMD FCH Azalia Controller                                                                         | 9         | 3.52%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 2.73%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 2.73%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 2.34%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 1.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.95%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.56%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.56%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 4         | 1.56%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.56%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.56%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3         | 1.17%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.17%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 3         | 1.17%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.17%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.78%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.78%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 2         | 0.78%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 2         | 0.78%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.78%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 0.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.78%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 2         | 0.78%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.78%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.39%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.39%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.39%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 1         | 0.39%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.39%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 1         | 0.39%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.39%   |
| Nvidia Audio device                                                                               | 1         | 0.39%   |
| Intel USB PnP Sound Device                                                                        | 1         | 0.39%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 1         | 0.39%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.39%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.39%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.39%   |
| Guillemot DJ Control Air                                                                          | 1         | 0.39%   |
| GN Netcom Jabra Evolve 65                                                                         | 1         | 0.39%   |
| Apple Audio Device                                                                                | 1         | 0.39%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.39%   |
| AMD Trinity HDMI Audio Controller                                                                 | 1         | 0.39%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 42        | 32.56%  |
| SK Hynix            | 22        | 17.05%  |
| Micron Technology   | 20        | 15.5%   |
| Crucial             | 8         | 6.2%    |
| Unknown             | 7         | 5.43%   |
| Kingston            | 7         | 5.43%   |
| Elpida              | 6         | 4.65%   |
| Ramaxel Technology  | 5         | 3.88%   |
| Corsair             | 3         | 2.33%   |
| Unknown (ABCD)      | 2         | 1.55%   |
| Nanya Technology    | 2         | 1.55%   |
| G.Skill             | 2         | 1.55%   |
| A-DATA Technology   | 2         | 1.55%   |
| Team                | 1         | 0.78%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 4.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 4.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 3         | 2.22%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 3         | 2.22%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.48%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 1.48%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 2         | 1.48%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 1.48%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 2         | 1.48%   |
| Samsung RAM M4 70T2953CZ3-CE6 1024MB SODIMM DDR 667MT/s             | 2         | 1.48%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 2         | 1.48%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s              | 2         | 1.48%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s              | 2         | 1.48%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 2         | 1.48%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                         | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 1         | 0.74%   |
| Unknown RAM Module 4096MB SODIMM 1066MT/s                           | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR3                                  | 1         | 0.74%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                       | 1         | 0.74%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.74%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 1         | 0.74%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s                | 1         | 0.74%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1066MT/s                     | 1         | 0.74%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1066MT/s                        | 1         | 0.74%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4096MB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK Hynix RAM HMT851S6AMR6A-PB 4096MB Chip DDR3 1600MT/s             | 1         | 0.74%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.74%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s             | 1         | 0.74%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.74%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 1         | 0.74%   |
| SK Hynix RAM H9HCNNNBKMALHR-NEE 4096MB Row Of Chips LPDDR4 4267MT/s | 1         | 0.74%   |
| Samsung RAM Module 2GB SODIMM LPDDR4 2400MT/s                       | 1         | 0.74%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1333MT/s                      | 1         | 0.74%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 1         | 0.74%   |
| Samsung RAM M474A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.74%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s               | 1         | 0.74%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s               | 1         | 0.74%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.74%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 1         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s            | 1         | 0.74%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 1         | 0.74%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s              | 1         | 0.74%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 0.74%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 1         | 0.74%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 1         | 0.74%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 1         | 0.74%   |
| Samsung RAM M471A1K43BB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 0.74%   |
| Samsung RAM M378B2873CZ0-CF7 1GB SODIMM DDR3 800MT/s                | 1         | 0.74%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s        | 1         | 0.74%   |
| Samsung RAM K4EBE304EB-EGCF 8GB Row Of Chips LPDDR3 1867MT/s        | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 49        | 44.95%  |
| DDR4    | 43        | 39.45%  |
| LPDDR4  | 7         | 6.42%   |
| LPDDR3  | 4         | 3.67%   |
| DDR2    | 4         | 3.67%   |
| DDR     | 1         | 0.92%   |
| Unknown | 1         | 0.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 92.59%  |
| Row Of Chips | 6         | 5.56%   |
| Chip         | 1         | 0.93%   |
| Unknown      | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 50        | 42.02%  |
| 8192  | 35        | 29.41%  |
| 16384 | 12        | 10.08%  |
| 2048  | 12        | 10.08%  |
| 1024  | 7         | 5.88%   |
| 32768 | 3         | 2.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 31        | 25.83%  |
| 2667    | 30        | 25%     |
| 1334    | 13        | 10.83%  |
| 3200    | 9         | 7.5%    |
| 2400    | 9         | 7.5%    |
| 2133    | 5         | 4.17%   |
| 1333    | 4         | 3.33%   |
| 3266    | 3         | 2.5%    |
| 1067    | 3         | 2.5%    |
| 1066    | 3         | 2.5%    |
| 667     | 3         | 2.5%    |
| Unknown | 2         | 1.67%   |
| 4267    | 1         | 0.83%   |
| 1867    | 1         | 0.83%   |
| 1866    | 1         | 0.83%   |
| 800     | 1         | 0.83%   |
| 533     | 1         | 0.83%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Brother HL-1210W series | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 49        | 30.63%  |
| Acer                                   | 20        | 12.5%   |
| Microdia                               | 15        | 9.38%   |
| IMC Networks                           | 13        | 8.13%   |
| Sunplus Innovation Technology          | 11        | 6.88%   |
| Realtek Semiconductor                  | 7         | 4.38%   |
| Apple                                  | 7         | 4.38%   |
| Quanta                                 | 6         | 3.75%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 3.75%   |
| Ricoh                                  | 5         | 3.13%   |
| Suyin                                  | 3         | 1.88%   |
| Silicon Motion                         | 3         | 1.88%   |
| Samsung Electronics                    | 3         | 1.88%   |
| Alcor Micro                            | 3         | 1.88%   |
| Luxvisions Innotech Limited            | 2         | 1.25%   |
| Lite-On Technology                     | 2         | 1.25%   |
| Syntek                                 | 1         | 0.63%   |
| LG Electronics                         | 1         | 0.63%   |
| Importek                               | 1         | 0.63%   |
| Goertek Electronics                    | 1         | 0.63%   |
| ALi                                    | 1         | 0.63%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 7         | 4.38%   |
| Acer HD Webcam                                      | 6         | 3.75%   |
| Chicony HD Webcam                                   | 5         | 3.13%   |
| Realtek Integrated_Webcam_HD                        | 4         | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 2.5%    |
| Chicony HP TrueVision HD                            | 4         | 2.5%    |
| Chicony HD User Facing                              | 4         | 2.5%    |
| Acer EasyCamera                                     | 4         | 2.5%    |
| Sunplus Integrated_Webcam_HD                        | 3         | 1.88%   |
| Samsung Galaxy A5 (MTP)                             | 3         | 1.88%   |
| Microdia Webcam Vitade AF                           | 3         | 1.88%   |
| IMC Networks Integrated Camera                      | 3         | 1.88%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.88%   |
| Chicony USB2.0 Camera                               | 3         | 1.88%   |
| Alcor Micro USB 2.0 Web Camera                      | 3         | 1.88%   |
| Sunplus HD WebCam                                   | 2         | 1.25%   |
| Realtek Integrated Webcam                           | 2         | 1.25%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.25%   |
| Microdia PC Microscope camera                       | 2         | 1.25%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.25%   |
| Microdia Integrated Webcam                          | 2         | 1.25%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.25%   |
| Lite-On HP Wide Vision HD Camera                    | 2         | 1.25%   |
| Chicony USB2.0 VGA UVC WebCam                       | 2         | 1.25%   |
| Chicony Integrated HP HD Webcam                     | 2         | 1.25%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 1.25%   |
| Chicony HP HD Webcam [Fixed]                        | 2         | 1.25%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.25%   |
| Apple FaceTime HD Camera                            | 2         | 1.25%   |
| Acer SunplusIT Integrated Camera                    | 2         | 1.25%   |
| Acer Lenovo EasyCamera                              | 2         | 1.25%   |
| Acer Integrated Camera                              | 2         | 1.25%   |
| Syntek Integrated Camera                            | 1         | 0.63%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.63%   |
| Suyin HP Truevision HD                              | 1         | 0.63%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.63%   |
| Sunplus Laptop_Integrated_Webcam_FHD                | 1         | 0.63%   |
| Sunplus Laptop Integrated Webcam FHD                | 1         | 0.63%   |
| Sunplus Integrated Camera                           | 1         | 0.63%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.63%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.63%   |
| Silicon Motion WebCam SCB-0385N                     | 1         | 0.63%   |
| Silicon Motion WebCam SC-13HDL11939N                | 1         | 0.63%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.63%   |
| Ricoh USB2.0 Camera                                 | 1         | 0.63%   |
| Ricoh Pavilion Webcam                               | 1         | 0.63%   |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 1         | 0.63%   |
| Ricoh Integrated Webcam                             | 1         | 0.63%   |
| Ricoh HD Webcam                                     | 1         | 0.63%   |
| Realtek Integrated Webcam HD                        | 1         | 0.63%   |
| Quanta VGA WebCam                                   | 1         | 0.63%   |
| Quanta HP Webcam                                    | 1         | 0.63%   |
| Quanta HD WebCam                                    | 1         | 0.63%   |
| Quanta HD User Facing                               | 1         | 0.63%   |
| Microdia WebCam SC-13HDL12639P                      | 1         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_HD                | 1         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 0.63%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 0.63%   |
| Microdia Integrated Webcam HD                       | 1         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 14        | 60.87%  |
| Synaptics             | 4         | 17.39%  |
| LighTuning Technology | 2         | 8.7%    |
| Elan Microelectronics | 2         | 8.7%    |
| AuthenTec             | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 13.04%  |
| Validity Sensors VFS491                                                    | 2         | 8.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 8.7%    |
| Validity Sensors Fingerprint scanner                                       | 2         | 8.7%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 8.7%    |
| Elan ELAN:Fingerprint                                                      | 2         | 8.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 4.35%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 4.35%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 4.35%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 4.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4.35%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 4.35%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 4.35%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 4.35%   |
| Unknown                                                                    | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 8         | 61.54%  |
| Alcor Micro | 3         | 23.08%  |
| OmniKey     | 1         | 7.69%   |
| O2 Micro    | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 38.46%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 23.08%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 15.38%  |
| OmniKey CardMan Smart@Link                                                   | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Broadcom 5880                                                                | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 103       | 57.87%  |
| 1     | 60        | 33.71%  |
| 2     | 14        | 7.87%   |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 24        | 27.91%  |
| Graphics card         | 14        | 16.28%  |
| Chipcard              | 12        | 13.95%  |
| Net/wireless          | 11        | 12.79%  |
| Multimedia controller | 9         | 10.47%  |
| Camera                | 6         | 6.98%   |
| Storage               | 4         | 4.65%   |
| Network               | 2         | 2.33%   |
| Bluetooth             | 2         | 2.33%   |
| Modem                 | 1         | 1.16%   |
| Card reader           | 1         | 1.16%   |

