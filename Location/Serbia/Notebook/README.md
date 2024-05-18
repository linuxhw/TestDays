Linux in Serbia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Serbia.

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

Total: 714

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | AOD270                      | [af6b765474](https://linux-hardware.org/?probe=af6b765474) | May 05, 2024 |
| HP            | ProBook 430 G1              | [7aa4826b7e](https://linux-hardware.org/?probe=7aa4826b7e) | May 03, 2024 |
| Lenovo        | B50-45 20388                | [49ad9c2e0e](https://linux-hardware.org/?probe=49ad9c2e0e) | May 03, 2024 |
| Acer          | Aspire A515-44              | [d580243e57](https://linux-hardware.org/?probe=d580243e57) | Apr 30, 2024 |
| HP            | ProBook 440 G3              | [27ac0cda6c](https://linux-hardware.org/?probe=27ac0cda6c) | Apr 29, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | [1361feafda](https://linux-hardware.org/?probe=1361feafda) | Apr 28, 2024 |
| HP            | Laptop 15-da0xxx            | [a0fcbd666f](https://linux-hardware.org/?probe=a0fcbd666f) | Apr 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [3989576cd6](https://linux-hardware.org/?probe=3989576cd6) | Apr 28, 2024 |
| Dixonsxp      | Crestline & ICH8M Chipse... | [a9e235a9db](https://linux-hardware.org/?probe=a9e235a9db) | Apr 27, 2024 |
| Acer          | TravelMate P215-53          | [00d58edb3b](https://linux-hardware.org/?probe=00d58edb3b) | Apr 27, 2024 |
| HP            | ProBook 430 G1              | [9230399ac5](https://linux-hardware.org/?probe=9230399ac5) | Apr 25, 2024 |
| HP            | EliteBook 8460p             | [d8ad825d7c](https://linux-hardware.org/?probe=d8ad825d7c) | Apr 25, 2024 |
| HP            | EliteBook 8460p             | [7dab54dc06](https://linux-hardware.org/?probe=7dab54dc06) | Apr 24, 2024 |
| Lenovo        | G505s 20255                 | [b7d2ec7d4d](https://linux-hardware.org/?probe=b7d2ec7d4d) | Apr 24, 2024 |
| Toshiba       | Satellite Pro L650          | [5a4eb9f755](https://linux-hardware.org/?probe=5a4eb9f755) | Apr 24, 2024 |
| SLIMBOOK      | Executive                   | [bdaee49e30](https://linux-hardware.org/?probe=bdaee49e30) | Apr 19, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [7e7a28ef89](https://linux-hardware.org/?probe=7e7a28ef89) | Apr 18, 2024 |
| HP            | ProBook 470 G1              | [a400b6efad](https://linux-hardware.org/?probe=a400b6efad) | Apr 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [7597455fe9](https://linux-hardware.org/?probe=7597455fe9) | Apr 16, 2024 |
| Dell          | Inspiron 1521               | [0eae25d659](https://linux-hardware.org/?probe=0eae25d659) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [b40a1b3e44](https://linux-hardware.org/?probe=b40a1b3e44) | Apr 12, 2024 |
| Lenovo        | ThinkPad X201 3680A44       | [db6aadf372](https://linux-hardware.org/?probe=db6aadf372) | Apr 10, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [0ca999c16b](https://linux-hardware.org/?probe=0ca999c16b) | Apr 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [5d0259d7a1](https://linux-hardware.org/?probe=5d0259d7a1) | Apr 06, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [47c56bd4ee](https://linux-hardware.org/?probe=47c56bd4ee) | Apr 05, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [a9490d11d7](https://linux-hardware.org/?probe=a9490d11d7) | Apr 04, 2024 |
| Acer          | Aspire A515-44              | [4b51c98fb6](https://linux-hardware.org/?probe=4b51c98fb6) | Apr 04, 2024 |
| Dell          | Latitude E7440              | [81be6cf5c3](https://linux-hardware.org/?probe=81be6cf5c3) | Apr 02, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [1d1e0bf9da](https://linux-hardware.org/?probe=1d1e0bf9da) | Apr 01, 2024 |
| Acer          | Aspire V3-331               | [0b74c17835](https://linux-hardware.org/?probe=0b74c17835) | Apr 01, 2024 |
| Dell          | Vostro 3520                 | [233178d530](https://linux-hardware.org/?probe=233178d530) | Mar 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [eb3211feaf](https://linux-hardware.org/?probe=eb3211feaf) | Mar 20, 2024 |
| HP            | EliteBook 840 Aero G8 No... | [ad05f2ffb7](https://linux-hardware.org/?probe=ad05f2ffb7) | Mar 18, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [0e826ebda8](https://linux-hardware.org/?probe=0e826ebda8) | Mar 17, 2024 |
| Framework     | Laptop 16 (AMD Ryzen 704... | [aaab952c4c](https://linux-hardware.org/?probe=aaab952c4c) | Mar 14, 2024 |
| HP            | Pavilion dm3                | [2ae7a34348](https://linux-hardware.org/?probe=2ae7a34348) | Mar 13, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [4832f2d4f3](https://linux-hardware.org/?probe=4832f2d4f3) | Mar 09, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [3908a94356](https://linux-hardware.org/?probe=3908a94356) | Mar 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [829d14a64a](https://linux-hardware.org/?probe=829d14a64a) | Mar 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [30b8f48fa3](https://linux-hardware.org/?probe=30b8f48fa3) | Mar 05, 2024 |
| HP            | OMEN by Laptop 17-ck1xxx    | [3fac30b86d](https://linux-hardware.org/?probe=3fac30b86d) | Mar 04, 2024 |
| HUAWEI        | HKD-WXX                     | [ec838546ec](https://linux-hardware.org/?probe=ec838546ec) | Feb 29, 2024 |
| HP            | EliteBook 840 G5            | [2c00c513d3](https://linux-hardware.org/?probe=2c00c513d3) | Feb 26, 2024 |
| HP            | EliteBook 840 G5            | [60b6b91372](https://linux-hardware.org/?probe=60b6b91372) | Feb 26, 2024 |
| Lenovo        | Unknown                     | [a51f2dad65](https://linux-hardware.org/?probe=a51f2dad65) | Feb 15, 2024 |
| HP            | Laptop 15-db0xxx            | [31bafcc0cc](https://linux-hardware.org/?probe=31bafcc0cc) | Feb 13, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [f2003839e0](https://linux-hardware.org/?probe=f2003839e0) | Feb 01, 2024 |
| HP            | EliteBook 840 G3            | [84264495d3](https://linux-hardware.org/?probe=84264495d3) | Jan 27, 2024 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [594794b707](https://linux-hardware.org/?probe=594794b707) | Jan 23, 2024 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [aca7a5c7c5](https://linux-hardware.org/?probe=aca7a5c7c5) | Jan 19, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [8906f7de53](https://linux-hardware.org/?probe=8906f7de53) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [e2058a8b66](https://linux-hardware.org/?probe=e2058a8b66) | Jan 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [301f2ec339](https://linux-hardware.org/?probe=301f2ec339) | Jan 12, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [84d67dfe96](https://linux-hardware.org/?probe=84d67dfe96) | Jan 12, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a32866554a](https://linux-hardware.org/?probe=a32866554a) | Dec 26, 2023 |
| Lenovo        | Legion Pro 7 16IRX8H 82W... | [97f532d3c8](https://linux-hardware.org/?probe=97f532d3c8) | Dec 26, 2023 |
| Dell          | Inspiron 3521               | [a109a64bdd](https://linux-hardware.org/?probe=a109a64bdd) | Dec 24, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [dc5e6d8ad5](https://linux-hardware.org/?probe=dc5e6d8ad5) | Dec 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [0121e6cb47](https://linux-hardware.org/?probe=0121e6cb47) | Dec 15, 2023 |
| HUAWEI        | CREFG-XX                    | [ee1bdd536f](https://linux-hardware.org/?probe=ee1bdd536f) | Dec 15, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [cda15a71e9](https://linux-hardware.org/?probe=cda15a71e9) | Dec 14, 2023 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [371f238337](https://linux-hardware.org/?probe=371f238337) | Dec 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [1c72ad4560](https://linux-hardware.org/?probe=1c72ad4560) | Dec 04, 2023 |
| eMachines     | eME440                      | [a622dddd66](https://linux-hardware.org/?probe=a622dddd66) | Nov 29, 2023 |
| Dell          | Precision M4500             | [044aca6d38](https://linux-hardware.org/?probe=044aca6d38) | Nov 27, 2023 |
| HP            | EliteBook 840 G3            | [7a52012e4f](https://linux-hardware.org/?probe=7a52012e4f) | Nov 23, 2023 |
| Purism        | Librem 13 v4                | [0fdc9f6ef8](https://linux-hardware.org/?probe=0fdc9f6ef8) | Nov 23, 2023 |
| Purism        | Librem 13 v4                | [83c0da5aab](https://linux-hardware.org/?probe=83c0da5aab) | Nov 23, 2023 |
| HP            | EliteBook 840 G3            | [a286df39d9](https://linux-hardware.org/?probe=a286df39d9) | Nov 20, 2023 |
| HP            | Laptop 15-da0xxx            | [666f76f4e9](https://linux-hardware.org/?probe=666f76f4e9) | Nov 18, 2023 |
| HP            | EliteBook 840 G3            | [827e0f3b54](https://linux-hardware.org/?probe=827e0f3b54) | Nov 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8e6ebc6d70](https://linux-hardware.org/?probe=8e6ebc6d70) | Nov 15, 2023 |
| HP            | Laptop 15-da0xxx            | [3f0b4a0bfe](https://linux-hardware.org/?probe=3f0b4a0bfe) | Nov 15, 2023 |
| Toshiba       | Satellite C55t-A            | [22d791cf19](https://linux-hardware.org/?probe=22d791cf19) | Nov 12, 2023 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [99fde80a79](https://linux-hardware.org/?probe=99fde80a79) | Nov 11, 2023 |
| HP            | 250 G8 Notebook PC          | [fda2670cc5](https://linux-hardware.org/?probe=fda2670cc5) | Nov 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [e736653169](https://linux-hardware.org/?probe=e736653169) | Nov 08, 2023 |
| HP            | 250 G8 Notebook PC          | [38b21b9f64](https://linux-hardware.org/?probe=38b21b9f64) | Nov 08, 2023 |
| HP            | 655                         | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | [d1d65399a0](https://linux-hardware.org/?probe=d1d65399a0) | Nov 03, 2023 |
| Dell          | Inspiron 3542               | [87ec116ea6](https://linux-hardware.org/?probe=87ec116ea6) | Nov 01, 2023 |
| HP            | 250 G8 Notebook PC          | [cd1abadd3a](https://linux-hardware.org/?probe=cd1abadd3a) | Oct 25, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [4312e9a007](https://linux-hardware.org/?probe=4312e9a007) | Oct 19, 2023 |
| HP            | 250 G8 Notebook PC          | [916bfc1646](https://linux-hardware.org/?probe=916bfc1646) | Oct 11, 2023 |
| HP            | EliteBook 820 G3            | [c474599b04](https://linux-hardware.org/?probe=c474599b04) | Oct 03, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4f7948d877](https://linux-hardware.org/?probe=4f7948d877) | Oct 02, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a8b35a2b8f](https://linux-hardware.org/?probe=a8b35a2b8f) | Sep 19, 2023 |
| Dell          | Vostro 15 3515              | [1929f30e86](https://linux-hardware.org/?probe=1929f30e86) | Sep 18, 2023 |
| HP            | Laptop 15-da0xxx            | [d66a3d9329](https://linux-hardware.org/?probe=d66a3d9329) | Sep 18, 2023 |
| ASUSTek       | K52JT                       | [5cf28fa81f](https://linux-hardware.org/?probe=5cf28fa81f) | Sep 16, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [2085bafc62](https://linux-hardware.org/?probe=2085bafc62) | Sep 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [797e19424f](https://linux-hardware.org/?probe=797e19424f) | Sep 16, 2023 |
| ASUSTek       | K54C                        | [23a000c4d4](https://linux-hardware.org/?probe=23a000c4d4) | Sep 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS5260... | [43ff008024](https://linux-hardware.org/?probe=43ff008024) | Sep 14, 2023 |
| Dell          | Latitude E7250              | [44983ff513](https://linux-hardware.org/?probe=44983ff513) | Sep 11, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [740fa4fb21](https://linux-hardware.org/?probe=740fa4fb21) | Sep 11, 2023 |
| HUAWEI        | HKD-WXX                     | [3b97b2d662](https://linux-hardware.org/?probe=3b97b2d662) | Sep 09, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ee1a881e82](https://linux-hardware.org/?probe=ee1a881e82) | Sep 04, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [8f29742c47](https://linux-hardware.org/?probe=8f29742c47) | Sep 02, 2023 |
| ASUSTek       | UX303LN                     | [43e624c0b4](https://linux-hardware.org/?probe=43e624c0b4) | Aug 30, 2023 |
| HP            | EliteBook 835 G7 Noteboo... | [fec29a37b2](https://linux-hardware.org/?probe=fec29a37b2) | Aug 27, 2023 |
| MSI           | GP76 Leopard 11UG           | [5de726089b](https://linux-hardware.org/?probe=5de726089b) | Aug 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e0d5cce513](https://linux-hardware.org/?probe=e0d5cce513) | Aug 23, 2023 |
| Apple         | MacBookPro8,2               | [2c42cc3ebb](https://linux-hardware.org/?probe=2c42cc3ebb) | Aug 18, 2023 |
| Lenovo        | ThinkPad T61 7661ZSF        | [2a461c159d](https://linux-hardware.org/?probe=2a461c159d) | Aug 18, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [fb2095ddea](https://linux-hardware.org/?probe=fb2095ddea) | Aug 17, 2023 |
| HP            | EliteBook 8560w             | [dfdde7225d](https://linux-hardware.org/?probe=dfdde7225d) | Aug 13, 2023 |
| Lenovo        | ThinkPad Edge 03193VG       | [abb370836a](https://linux-hardware.org/?probe=abb370836a) | Aug 10, 2023 |
| HP            | EliteBook 8560w             | [ea34946fbd](https://linux-hardware.org/?probe=ea34946fbd) | Aug 09, 2023 |
| Alienware     | 14                          | [192b13997d](https://linux-hardware.org/?probe=192b13997d) | Aug 09, 2023 |
| Dell          | Latitude E7450              | [a426887b24](https://linux-hardware.org/?probe=a426887b24) | Aug 08, 2023 |
| HP            | EliteBook 8560w             | [b2177d3c55](https://linux-hardware.org/?probe=b2177d3c55) | Aug 06, 2023 |
| Dell          | Inspiron 5521               | [21063bc0bb](https://linux-hardware.org/?probe=21063bc0bb) | Aug 05, 2023 |
| Apple         | MacBookPro8,2               | [573e7f6ad0](https://linux-hardware.org/?probe=573e7f6ad0) | Aug 03, 2023 |
| Acer          | Aspire ES1-520              | [437e15fae7](https://linux-hardware.org/?probe=437e15fae7) | Aug 03, 2023 |
| Acer          | Aspire 5733                 | [f09853c0ed](https://linux-hardware.org/?probe=f09853c0ed) | Aug 03, 2023 |
| Acer          | Aspire ES1-520              | [1cf260b959](https://linux-hardware.org/?probe=1cf260b959) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [f75ea8cfef](https://linux-hardware.org/?probe=f75ea8cfef) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Lenovo        | V15-IGL 82C3                | [6c0a6fff0a](https://linux-hardware.org/?probe=6c0a6fff0a) | Jul 31, 2023 |
| HP            | EliteBook 840 G5            | [875ac8e861](https://linux-hardware.org/?probe=875ac8e861) | Jul 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [19b6ecf591](https://linux-hardware.org/?probe=19b6ecf591) | Jul 29, 2023 |
| Apple         | MacBookPro8,2               | [10db13c772](https://linux-hardware.org/?probe=10db13c772) | Jul 26, 2023 |
| Synology      | DS923+                      | [4e023a4222](https://linux-hardware.org/?probe=4e023a4222) | Jul 21, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [31c0d94d23](https://linux-hardware.org/?probe=31c0d94d23) | Jul 18, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d4a4fec7c0](https://linux-hardware.org/?probe=d4a4fec7c0) | Jul 17, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [6130474cb1](https://linux-hardware.org/?probe=6130474cb1) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b1ceb90106](https://linux-hardware.org/?probe=b1ceb90106) | Jul 12, 2023 |
| Lenovo        | ThinkPad T460 20FMS43Q00    | [3f0c520d07](https://linux-hardware.org/?probe=3f0c520d07) | Jul 10, 2023 |
| HP            | EliteBook 830 G6            | [7a29f3d086](https://linux-hardware.org/?probe=7a29f3d086) | Jun 20, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [8550e224ec](https://linux-hardware.org/?probe=8550e224ec) | Jun 20, 2023 |
| Lenovo        | G550 20023                  | [a1eac5da7c](https://linux-hardware.org/?probe=a1eac5da7c) | Jun 18, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9529a983b8](https://linux-hardware.org/?probe=9529a983b8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X201 3680Y4F       | [7823148e7d](https://linux-hardware.org/?probe=7823148e7d) | Jun 07, 2023 |
| Acer          | Aspire A315-31              | [d5da1b4b30](https://linux-hardware.org/?probe=d5da1b4b30) | Jun 06, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Nitro AN517-54              | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| Dell          | Latitude 5440               | [9ed4f0e7ac](https://linux-hardware.org/?probe=9ed4f0e7ac) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| HP            | EliteBook 820 G1            | [1498cf091b](https://linux-hardware.org/?probe=1498cf091b) | May 26, 2023 |
| HP            | EliteBook 820 G1            | [46a6988c7a](https://linux-hardware.org/?probe=46a6988c7a) | May 25, 2023 |
| Dell          | Latitude 5440               | [5a27bd40e7](https://linux-hardware.org/?probe=5a27bd40e7) | May 25, 2023 |
| HP            | 250 G8 Notebook PC          | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Acer          | Aspire A715-42G             | [39bb190ac7](https://linux-hardware.org/?probe=39bb190ac7) | May 22, 2023 |
| Apple         | MacBookPro16,2              | [e4adcd71f1](https://linux-hardware.org/?probe=e4adcd71f1) | May 21, 2023 |
| Apple         | MacBookPro16,2              | [09f37f2540](https://linux-hardware.org/?probe=09f37f2540) | May 21, 2023 |
| ASUSTek       | X540SC                      | [240bb6c246](https://linux-hardware.org/?probe=240bb6c246) | May 21, 2023 |
| HP            | EliteBook 820 G1            | [386869568d](https://linux-hardware.org/?probe=386869568d) | May 17, 2023 |
| HP            | 250 G8 Notebook PC          | [47430a463a](https://linux-hardware.org/?probe=47430a463a) | May 15, 2023 |
| HP            | EliteBook 820 G1            | [e50adfaff9](https://linux-hardware.org/?probe=e50adfaff9) | May 15, 2023 |
| Acer          | Aspire A715-42G             | [b43ec1363a](https://linux-hardware.org/?probe=b43ec1363a) | May 14, 2023 |
| Acer          | Aspire A715-42G             | [b80a472c1a](https://linux-hardware.org/?probe=b80a472c1a) | May 14, 2023 |
| Dell          | Precision M4500             | [315cccc082](https://linux-hardware.org/?probe=315cccc082) | May 14, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [d01779a93b](https://linux-hardware.org/?probe=d01779a93b) | May 09, 2023 |
| Lenovo        | G550 20023                  | [33cc483e77](https://linux-hardware.org/?probe=33cc483e77) | May 09, 2023 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [a9fe0fdf88](https://linux-hardware.org/?probe=a9fe0fdf88) | May 07, 2023 |
| Apple         | MacBookPro6,2               | [3e154e4ccc](https://linux-hardware.org/?probe=3e154e4ccc) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [2628c3040f](https://linux-hardware.org/?probe=2628c3040f) | Apr 28, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3c104a89ef](https://linux-hardware.org/?probe=3c104a89ef) | Apr 26, 2023 |
| Dell          | Vostro 15 3510              | [81cae0ba77](https://linux-hardware.org/?probe=81cae0ba77) | Apr 26, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [167000be9b](https://linux-hardware.org/?probe=167000be9b) | Apr 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [258a5bb354](https://linux-hardware.org/?probe=258a5bb354) | Apr 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [889301578c](https://linux-hardware.org/?probe=889301578c) | Apr 18, 2023 |
| Acer          | Aspire 5336                 | [ddf5053ffa](https://linux-hardware.org/?probe=ddf5053ffa) | Apr 18, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [55a12acf3a](https://linux-hardware.org/?probe=55a12acf3a) | Apr 12, 2023 |
| Lenovo        | V570 1066EDG                | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| ASUSTek       | E200HA                      | [5dfef9c764](https://linux-hardware.org/?probe=5dfef9c764) | Mar 26, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [178936b7f4](https://linux-hardware.org/?probe=178936b7f4) | Mar 24, 2023 |
| HP            | EliteBook 2530p             | [06ad8714ea](https://linux-hardware.org/?probe=06ad8714ea) | Mar 22, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Lenovo        | G550 20023                  | [6296457407](https://linux-hardware.org/?probe=6296457407) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | [f5bd764775](https://linux-hardware.org/?probe=f5bd764775) | Mar 18, 2023 |
| Lenovo        | G550 20023                  | [c356d98a54](https://linux-hardware.org/?probe=c356d98a54) | Mar 17, 2023 |
| ASUSTek       | K93SV                       | [aa66f39ad6](https://linux-hardware.org/?probe=aa66f39ad6) | Mar 13, 2023 |
| ASUSTek       | E200HA                      | [46a16afb4b](https://linux-hardware.org/?probe=46a16afb4b) | Mar 03, 2023 |
| Lenovo        | V570 1066EDG                | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| Lenovo        | ThinkPad T495s 20QJS0GG0... | [6186149a54](https://linux-hardware.org/?probe=6186149a54) | Feb 24, 2023 |
| HONOR         | NBR-WAX9                    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | [18f60be847](https://linux-hardware.org/?probe=18f60be847) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f721ad33a](https://linux-hardware.org/?probe=2f721ad33a) | Feb 10, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | [da12318597](https://linux-hardware.org/?probe=da12318597) | Feb 10, 2023 |
| Dell          | Inspiron 3558               | [310425ba43](https://linux-hardware.org/?probe=310425ba43) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| TWC           | Unknown                     | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [fcd4f7a01a](https://linux-hardware.org/?probe=fcd4f7a01a) | Feb 06, 2023 |
| HP            | 250 G5 Notebook PC          | [d389ca29d1](https://linux-hardware.org/?probe=d389ca29d1) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Dell          | XPS 15 9550                 | [200495d065](https://linux-hardware.org/?probe=200495d065) | Feb 04, 2023 |
| Dell          | Vostro 15 3515              | [357d14774f](https://linux-hardware.org/?probe=357d14774f) | Jan 30, 2023 |
| ASUSTek       | K55A                        | [e3088b45e1](https://linux-hardware.org/?probe=e3088b45e1) | Jan 29, 2023 |
| ASUSTek       | K93SV                       | [3b4dd13d9f](https://linux-hardware.org/?probe=3b4dd13d9f) | Jan 29, 2023 |
| Toshiba       | Satellite C870-17H          | [8fe4718795](https://linux-hardware.org/?probe=8fe4718795) | Jan 28, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [d825caa85e](https://linux-hardware.org/?probe=d825caa85e) | Jan 27, 2023 |
| Dell          | Precision 3550              | [4c42615cef](https://linux-hardware.org/?probe=4c42615cef) | Jan 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b871955b27](https://linux-hardware.org/?probe=b871955b27) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [2194886c52](https://linux-hardware.org/?probe=2194886c52) | Jan 23, 2023 |
| Acer          | Aspire 5755G                | [1bf0fe4342](https://linux-hardware.org/?probe=1bf0fe4342) | Jan 22, 2023 |
| Apple         | MacBookPro5,3               | [2375f407c7](https://linux-hardware.org/?probe=2375f407c7) | Jan 22, 2023 |
| ASUSTek       | X453MA                      | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| ASUSTek       | X201EP                      | [def6593908](https://linux-hardware.org/?probe=def6593908) | Jan 16, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [295ef21c8b](https://linux-hardware.org/?probe=295ef21c8b) | Jan 15, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [fceb17b32c](https://linux-hardware.org/?probe=fceb17b32c) | Jan 10, 2023 |
| Lenovo        | ThinkPad T430 2349JN0       | [04a54f4c2f](https://linux-hardware.org/?probe=04a54f4c2f) | Jan 09, 2023 |
| Dell          | Inspiron 3537               | [234580243d](https://linux-hardware.org/?probe=234580243d) | Jan 08, 2023 |
| Lenovo        | ThinkPad W500 4061WFA       | [4850dba7c8](https://linux-hardware.org/?probe=4850dba7c8) | Jan 08, 2023 |
| ASUSTek       | E200HA                      | [f84fb1bab3](https://linux-hardware.org/?probe=f84fb1bab3) | Jan 08, 2023 |
| eMachines     | E725                        | [0655d63f70](https://linux-hardware.org/?probe=0655d63f70) | Jan 06, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| ASUSTek       | K52JT                       | [77abcf7aee](https://linux-hardware.org/?probe=77abcf7aee) | Jan 05, 2023 |
| HP            | 255 G8 Notebook PC          | [05209e0503](https://linux-hardware.org/?probe=05209e0503) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Acer          | Aspire 5741                 | [1c41b5afb0](https://linux-hardware.org/?probe=1c41b5afb0) | Dec 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [a48a2f6362](https://linux-hardware.org/?probe=a48a2f6362) | Dec 24, 2022 |
| Lenovo        | Legion 7 16IAX7 82TD        | [46e5d4fe56](https://linux-hardware.org/?probe=46e5d4fe56) | Dec 20, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [e8b0c03cb9](https://linux-hardware.org/?probe=e8b0c03cb9) | Dec 15, 2022 |
| Acer          | Nitro AN517-51              | [6b5fd6a48c](https://linux-hardware.org/?probe=6b5fd6a48c) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [937053920b](https://linux-hardware.org/?probe=937053920b) | Dec 04, 2022 |
| Dell          | Inspiron N5050              | [c6bca6efa8](https://linux-hardware.org/?probe=c6bca6efa8) | Dec 03, 2022 |
| Dell          | Inspiron N5050              | [e4c533a89b](https://linux-hardware.org/?probe=e4c533a89b) | Nov 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34601... | [ed678da106](https://linux-hardware.org/?probe=ed678da106) | Nov 26, 2022 |
| HP            | ProBook 445 14 inch G9 N... | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| HP            | Pavilion dv7                | [839266e415](https://linux-hardware.org/?probe=839266e415) | Nov 19, 2022 |
| HP            | Notebook                    | [2721a90e68](https://linux-hardware.org/?probe=2721a90e68) | Nov 19, 2022 |
| Dell          | Inspiron 3584               | [c3fde80859](https://linux-hardware.org/?probe=c3fde80859) | Nov 14, 2022 |
| Dell          | Inspiron 3584               | [c8e8add499](https://linux-hardware.org/?probe=c8e8add499) | Nov 14, 2022 |
| ASUSTek       | K93SV                       | [8511ee86ad](https://linux-hardware.org/?probe=8511ee86ad) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [db62973b36](https://linux-hardware.org/?probe=db62973b36) | Nov 06, 2022 |
| Acer          | Aspire V3-571G              | [3d642bde4b](https://linux-hardware.org/?probe=3d642bde4b) | Nov 05, 2022 |
| Timi          | RedmiBook 14 II             | [374be77f36](https://linux-hardware.org/?probe=374be77f36) | Nov 05, 2022 |
| ASUSTek       | X751LB                      | [b9f1ea7699](https://linux-hardware.org/?probe=b9f1ea7699) | Nov 04, 2022 |
| ASUSTek       | X751LB                      | [e7334f33eb](https://linux-hardware.org/?probe=e7334f33eb) | Nov 04, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7d6d6c3c3a](https://linux-hardware.org/?probe=7d6d6c3c3a) | Nov 04, 2022 |
| Acer          | Aspire V3-571G              | [990a38ea87](https://linux-hardware.org/?probe=990a38ea87) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [491477817a](https://linux-hardware.org/?probe=491477817a) | Oct 25, 2022 |
| ASUSTek       | N750JK                      | [341d4b53b1](https://linux-hardware.org/?probe=341d4b53b1) | Oct 20, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d928c22430](https://linux-hardware.org/?probe=d928c22430) | Oct 14, 2022 |
| MSI           | GP66 Leopard 10UG           | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| Lenovo        | B50-45 20388                | [c5f81be3fd](https://linux-hardware.org/?probe=c5f81be3fd) | Oct 02, 2022 |
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Dell          | Precision M4800             | [d4142adadc](https://linux-hardware.org/?probe=d4142adadc) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [9fbedd972e](https://linux-hardware.org/?probe=9fbedd972e) | Sep 24, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [641ad27b06](https://linux-hardware.org/?probe=641ad27b06) | Sep 22, 2022 |
| HP            | ProBook 6560b               | [743f401352](https://linux-hardware.org/?probe=743f401352) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [d0d43b3cc5](https://linux-hardware.org/?probe=d0d43b3cc5) | Sep 14, 2022 |
| Dell          | Inspiron N5050              | [131f5046db](https://linux-hardware.org/?probe=131f5046db) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| LG Electro... | 17Z990-R.AAS8U1             | [2df5aeabed](https://linux-hardware.org/?probe=2df5aeabed) | Sep 08, 2022 |
| Dell          | Inspiron 3593               | [fd6ab0c9e5](https://linux-hardware.org/?probe=fd6ab0c9e5) | Sep 07, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [beec88b95c](https://linux-hardware.org/?probe=beec88b95c) | Sep 04, 2022 |
| Apple         | MacBookPro5,1               | [4c90105342](https://linux-hardware.org/?probe=4c90105342) | Sep 01, 2022 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [e3c7cd81e8](https://linux-hardware.org/?probe=e3c7cd81e8) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [f945f778b2](https://linux-hardware.org/?probe=f945f778b2) | Aug 26, 2022 |
| Apple         | MacBookPro5,1               | [6efab17b42](https://linux-hardware.org/?probe=6efab17b42) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [255a1cdf9a](https://linux-hardware.org/?probe=255a1cdf9a) | Aug 24, 2022 |
| ASUSTek       | X542BA                      | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| ASUSTek       | K54C                        | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| Dell          | Inspiron 3521               | [ebf974be3e](https://linux-hardware.org/?probe=ebf974be3e) | Aug 13, 2022 |
| Dell          | Inspiron 3521               | [6dd71dbcf3](https://linux-hardware.org/?probe=6dd71dbcf3) | Aug 12, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [fa9cdcd977](https://linux-hardware.org/?probe=fa9cdcd977) | Aug 12, 2022 |
| Apple         | MacBookPro5,1               | [ab09f2f44b](https://linux-hardware.org/?probe=ab09f2f44b) | Aug 11, 2022 |
| Sony          | VPCZ12M9E                   | [75f1c2f156](https://linux-hardware.org/?probe=75f1c2f156) | Aug 02, 2022 |
| Sony          | VPCEE23FX                   | [b4108910d3](https://linux-hardware.org/?probe=b4108910d3) | Jul 25, 2022 |
| Acer          | Nitro AN515-55              | [b121274e4f](https://linux-hardware.org/?probe=b121274e4f) | Jul 23, 2022 |
| Apple         | MacBookPro5,1               | [4bae560f04](https://linux-hardware.org/?probe=4bae560f04) | Jul 22, 2022 |
| Apple         | MacBookPro5,1               | [8a81341ecd](https://linux-hardware.org/?probe=8a81341ecd) | Jul 18, 2022 |
| HP            | Compaq nx7300 (RU373ES#A... | [3004f1d2b9](https://linux-hardware.org/?probe=3004f1d2b9) | Jul 16, 2022 |
| Gigabyte      | AERO 17 KC                  | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [fdc339a6b0](https://linux-hardware.org/?probe=fdc339a6b0) | Jul 09, 2022 |
| Lenovo        | ThinkPad X280 20KES8D400    | [7d2b04b0ce](https://linux-hardware.org/?probe=7d2b04b0ce) | Jul 09, 2022 |
| Dell          | Vostro 15 3515              | [c6e9a42a66](https://linux-hardware.org/?probe=c6e9a42a66) | Jul 08, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c01cf9f7fc](https://linux-hardware.org/?probe=c01cf9f7fc) | Jul 05, 2022 |
| HP            | 250 G4                      | [3d629889b2](https://linux-hardware.org/?probe=3d629889b2) | Jul 05, 2022 |
| HP            | 250 G4                      | [e19f8a8485](https://linux-hardware.org/?probe=e19f8a8485) | Jul 05, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [be7fd47ea1](https://linux-hardware.org/?probe=be7fd47ea1) | Jul 04, 2022 |
| Timi          | TM1613                      | [6d3f245289](https://linux-hardware.org/?probe=6d3f245289) | Jul 04, 2022 |
| Timi          | TM1613                      | [38d9919cfd](https://linux-hardware.org/?probe=38d9919cfd) | Jul 03, 2022 |
| Dell          | Inspiron 3593               | [5b091180ec](https://linux-hardware.org/?probe=5b091180ec) | Jun 28, 2022 |
| Lenovo        | ThinkPad T560 20FJS1KE00    | [f0cd91b4d2](https://linux-hardware.org/?probe=f0cd91b4d2) | Jun 21, 2022 |
| Lenovo        | Unknown                     | [cd2f32d91c](https://linux-hardware.org/?probe=cd2f32d91c) | Jun 16, 2022 |
| HP            | Pavilion Notebook           | [06c982ad14](https://linux-hardware.org/?probe=06c982ad14) | Jun 16, 2022 |
| Lenovo        | ThinkPad T60 2007FUG        | [2c1a306677](https://linux-hardware.org/?probe=2c1a306677) | Jun 16, 2022 |
| ASUSTek       | K55VD                       | [7fa5d36a45](https://linux-hardware.org/?probe=7fa5d36a45) | Jun 04, 2022 |
| HP            | ProBook 470 G1              | [ef73457d51](https://linux-hardware.org/?probe=ef73457d51) | May 31, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [9ebff03a43](https://linux-hardware.org/?probe=9ebff03a43) | May 26, 2022 |
| Lenovo        | ThinkPad T490 20N2000LMZ    | [cc80808aea](https://linux-hardware.org/?probe=cc80808aea) | May 26, 2022 |
| Lenovo        | ThinkPad T61 6463Y3W        | [065aa2538b](https://linux-hardware.org/?probe=065aa2538b) | May 18, 2022 |
| HP            | Laptop 15-db1xxx            | [f6262ce7f2](https://linux-hardware.org/?probe=f6262ce7f2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e90b6752ba](https://linux-hardware.org/?probe=e90b6752ba) | May 12, 2022 |
| HP            | ProBook 450 G2              | [2c2a15aab2](https://linux-hardware.org/?probe=2c2a15aab2) | May 12, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d18df271fd](https://linux-hardware.org/?probe=d18df271fd) | May 09, 2022 |
| Medion        | X781X/X782X                 | [fbe630f91c](https://linux-hardware.org/?probe=fbe630f91c) | May 07, 2022 |
| Lenovo        | IdeaPad Z370                | [be37f3c962](https://linux-hardware.org/?probe=be37f3c962) | May 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [633bddd44b](https://linux-hardware.org/?probe=633bddd44b) | Apr 30, 2022 |
| Acer          | Nitro AN517-51              | [81d7fd8d2e](https://linux-hardware.org/?probe=81d7fd8d2e) | Apr 30, 2022 |
| Dell          | Latitude 7280               | [e64ba65609](https://linux-hardware.org/?probe=e64ba65609) | Apr 22, 2022 |
| Lenovo        | Unknown                     | [6e1760aed0](https://linux-hardware.org/?probe=6e1760aed0) | Apr 17, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [b888c78ed6](https://linux-hardware.org/?probe=b888c78ed6) | Apr 12, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [45dad76f04](https://linux-hardware.org/?probe=45dad76f04) | Apr 12, 2022 |
| HP            | Notebook                    | [4ffd4d11a5](https://linux-hardware.org/?probe=4ffd4d11a5) | Apr 09, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [0dbb9e7eb0](https://linux-hardware.org/?probe=0dbb9e7eb0) | Apr 09, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [950a436db3](https://linux-hardware.org/?probe=950a436db3) | Apr 06, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [906de71a65](https://linux-hardware.org/?probe=906de71a65) | Apr 02, 2022 |
| Lenovo        | V330-15IKB 81AX             | [8a881c75f4](https://linux-hardware.org/?probe=8a881c75f4) | Mar 29, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f92c8b77dc](https://linux-hardware.org/?probe=f92c8b77dc) | Mar 25, 2022 |
| Fujitsu Si... | AMILO Li3710                | [ab84e23108](https://linux-hardware.org/?probe=ab84e23108) | Mar 24, 2022 |
| Dell          | Inspiron 3542               | [6a8c31fa33](https://linux-hardware.org/?probe=6a8c31fa33) | Mar 21, 2022 |
| Apple         | MacBookPro8,1               | [f55145f34a](https://linux-hardware.org/?probe=f55145f34a) | Mar 16, 2022 |
| Toshiba       | Satellite C870-17H          | [0169bf05d7](https://linux-hardware.org/?probe=0169bf05d7) | Mar 10, 2022 |
| Fujitsu Si... | AMILO Li3710                | [7a4a682f45](https://linux-hardware.org/?probe=7a4a682f45) | Mar 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [2c44722344](https://linux-hardware.org/?probe=2c44722344) | Mar 03, 2022 |
| ASUSTek       | E200HA                      | [69ec87e43a](https://linux-hardware.org/?probe=69ec87e43a) | Mar 02, 2022 |
| HP            | Laptop 15s-fq0xxx           | [9acf95b26b](https://linux-hardware.org/?probe=9acf95b26b) | Feb 28, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [03a49e64cf](https://linux-hardware.org/?probe=03a49e64cf) | Feb 28, 2022 |
| Gigabyte      | AERO 17 KC                  | [08b488b969](https://linux-hardware.org/?probe=08b488b969) | Feb 27, 2022 |
| Dell          | Latitude 7490               | [003b6b4a95](https://linux-hardware.org/?probe=003b6b4a95) | Feb 21, 2022 |
| Dell          | Inspiron 3581               | [0ae0e53b53](https://linux-hardware.org/?probe=0ae0e53b53) | Feb 20, 2022 |
| HP            | Notebook                    | [a1f9f76ed0](https://linux-hardware.org/?probe=a1f9f76ed0) | Feb 19, 2022 |
| Toshiba       | Satellite C55-A             | [19133950aa](https://linux-hardware.org/?probe=19133950aa) | Feb 15, 2022 |
| ASUSTek       | X55A                        | [c6b17158ac](https://linux-hardware.org/?probe=c6b17158ac) | Feb 14, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [4f80537faf](https://linux-hardware.org/?probe=4f80537faf) | Feb 06, 2022 |
| Toshiba       | Satellite C55-C             | [379d3b37b1](https://linux-hardware.org/?probe=379d3b37b1) | Feb 05, 2022 |
| BenQ          | Joybook Lite U121           | [28f254dd8d](https://linux-hardware.org/?probe=28f254dd8d) | Feb 02, 2022 |
| Dell          | Vostro 3500                 | [729abacd12](https://linux-hardware.org/?probe=729abacd12) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5e9f8a1c0d](https://linux-hardware.org/?probe=5e9f8a1c0d) | Jan 29, 2022 |
| Dell          | Latitude E6510              | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [37ec4f5294](https://linux-hardware.org/?probe=37ec4f5294) | Jan 25, 2022 |
| ASUSTek       | E200HA                      | [2c53d21746](https://linux-hardware.org/?probe=2c53d21746) | Jan 22, 2022 |
| ASUSTek       | E200HA                      | [02be439ac8](https://linux-hardware.org/?probe=02be439ac8) | Jan 22, 2022 |
| HP            | EliteBook 1050 G1           | [1bb5cb826f](https://linux-hardware.org/?probe=1bb5cb826f) | Jan 19, 2022 |
| TWC           | Unknown                     | [85a8fd2cf1](https://linux-hardware.org/?probe=85a8fd2cf1) | Jan 18, 2022 |
| TWC           | Unknown                     | [d4cc69cea7](https://linux-hardware.org/?probe=d4cc69cea7) | Jan 16, 2022 |
| Fujitsu       | LIFEBOOK A3510              | [b673072fbb](https://linux-hardware.org/?probe=b673072fbb) | Jan 11, 2022 |
| Dell          | Vostro 5402                 | [f586d10ee6](https://linux-hardware.org/?probe=f586d10ee6) | Jan 05, 2022 |
| MSI           | GT70 2PC                    | [61a5023d6a](https://linux-hardware.org/?probe=61a5023d6a) | Jan 03, 2022 |
| Dell          | Latitude 7490               | [2d6469644a](https://linux-hardware.org/?probe=2d6469644a) | Jan 02, 2022 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Dell          | Latitude 7490               | [4e350048ed](https://linux-hardware.org/?probe=4e350048ed) | Dec 27, 2021 |
| Fujitsu Si... | AMILO Li3710                | [183a47572f](https://linux-hardware.org/?probe=183a47572f) | Dec 27, 2021 |
| ASUSTek       | X580VD                      | [fe350107e3](https://linux-hardware.org/?probe=fe350107e3) | Dec 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [74591e1700](https://linux-hardware.org/?probe=74591e1700) | Dec 12, 2021 |
| Toshiba       | Satellite Pro L650          | [fd40a9d639](https://linux-hardware.org/?probe=fd40a9d639) | Dec 07, 2021 |
| HP            | Laptop 15s-eq1xxx           | [a61a3df5f9](https://linux-hardware.org/?probe=a61a3df5f9) | Dec 04, 2021 |
| Dell          | Vostro 3500                 | [3df309c91c](https://linux-hardware.org/?probe=3df309c91c) | Dec 03, 2021 |
| Fujitsu Si... | AMILO Li3910                | [6f355c1c73](https://linux-hardware.org/?probe=6f355c1c73) | Dec 01, 2021 |
| HP            | Laptop 14-ck0xxx            | [60a074698a](https://linux-hardware.org/?probe=60a074698a) | Dec 01, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [440d34a6b0](https://linux-hardware.org/?probe=440d34a6b0) | Nov 28, 2021 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [bb7b625409](https://linux-hardware.org/?probe=bb7b625409) | Nov 28, 2021 |
| ASUSTek       | N53SN                       | [67d66feb3e](https://linux-hardware.org/?probe=67d66feb3e) | Nov 20, 2021 |
| Acer          | Aspire ES1-533              | [14a4c57e27](https://linux-hardware.org/?probe=14a4c57e27) | Nov 05, 2021 |
| Lenovo        | G500 20236                  | [7708d61566](https://linux-hardware.org/?probe=7708d61566) | Nov 05, 2021 |
| eMachines     | eME440                      | [1427ebffb0](https://linux-hardware.org/?probe=1427ebffb0) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [d180cf6efc](https://linux-hardware.org/?probe=d180cf6efc) | Oct 23, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [cb8bcc4d2d](https://linux-hardware.org/?probe=cb8bcc4d2d) | Oct 22, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| HP            | EliteBook 840 G3            | [650c91f4db](https://linux-hardware.org/?probe=650c91f4db) | Oct 18, 2021 |
| HP            | EliteBook 840 G3            | [5e28e542c2](https://linux-hardware.org/?probe=5e28e542c2) | Oct 17, 2021 |
| Dell          | Inspiron 3520               | [7eafd054fc](https://linux-hardware.org/?probe=7eafd054fc) | Oct 17, 2021 |
| HP            | Laptop 15s-eq2xxx           | [2e7ac4731f](https://linux-hardware.org/?probe=2e7ac4731f) | Oct 16, 2021 |
| Lenovo        | G555 0873                   | [a38f52851a](https://linux-hardware.org/?probe=a38f52851a) | Oct 05, 2021 |
| ASUSTek       | 1005PE                      | [bd2044749b](https://linux-hardware.org/?probe=bd2044749b) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | [b9fcdffa50](https://linux-hardware.org/?probe=b9fcdffa50) | Sep 22, 2021 |
| ASUSTek       | 1005PE                      | [02ccb36302](https://linux-hardware.org/?probe=02ccb36302) | Sep 21, 2021 |
| ASUSTek       | 1005PE                      | [081e791398](https://linux-hardware.org/?probe=081e791398) | Sep 19, 2021 |
| Toshiba       | Satellite C55-B             | [59a0efda89](https://linux-hardware.org/?probe=59a0efda89) | Sep 18, 2021 |
| ASUSTek       | 1005PE                      | [a3adf0356c](https://linux-hardware.org/?probe=a3adf0356c) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | [cedbbde363](https://linux-hardware.org/?probe=cedbbde363) | Sep 13, 2021 |
| Lenovo        | G500 20236                  | [f77883b614](https://linux-hardware.org/?probe=f77883b614) | Sep 07, 2021 |
| HP            | ProBook 4730s               | [36834479ab](https://linux-hardware.org/?probe=36834479ab) | Sep 03, 2021 |
| Apple         | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| Dell          | Inspiron 3537               | [cad80329d8](https://linux-hardware.org/?probe=cad80329d8) | Aug 31, 2021 |
| Lenovo        | G500 20236                  | [60f43f8815](https://linux-hardware.org/?probe=60f43f8815) | Aug 29, 2021 |
| Dell          | Inspiron 5593               | [ebac51e403](https://linux-hardware.org/?probe=ebac51e403) | Aug 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62c96ffa5b](https://linux-hardware.org/?probe=62c96ffa5b) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [516b9ff2ed](https://linux-hardware.org/?probe=516b9ff2ed) | Aug 25, 2021 |
| Dell          | Inspiron 7520               | [056e1c0825](https://linux-hardware.org/?probe=056e1c0825) | Aug 21, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [79051f2400](https://linux-hardware.org/?probe=79051f2400) | Aug 19, 2021 |
| HP            | EliteBook 840 G5            | [4c196e1abd](https://linux-hardware.org/?probe=4c196e1abd) | Aug 18, 2021 |
| HP            | G62                         | [b6eeeba9d1](https://linux-hardware.org/?probe=b6eeeba9d1) | Aug 15, 2021 |
| HP            | G62                         | [4adea9bed4](https://linux-hardware.org/?probe=4adea9bed4) | Aug 14, 2021 |
| HP            | Pavilion g6                 | [df95184640](https://linux-hardware.org/?probe=df95184640) | Aug 02, 2021 |
| HP            | Pavilion g6                 | [0e0aaaac98](https://linux-hardware.org/?probe=0e0aaaac98) | Aug 02, 2021 |
| Toshiba       | Satellite Pro L650          | [10e8624257](https://linux-hardware.org/?probe=10e8624257) | Jul 27, 2021 |
| Toshiba       | Satellite C55-B             | [c703c827c6](https://linux-hardware.org/?probe=c703c827c6) | Jul 21, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b44e9be41b](https://linux-hardware.org/?probe=b44e9be41b) | Jul 19, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56faa89619](https://linux-hardware.org/?probe=56faa89619) | Jul 16, 2021 |
| Lenovo        | V330-15IKB 81AX             | [70128f07ea](https://linux-hardware.org/?probe=70128f07ea) | Jul 13, 2021 |
| HP            | Compaq nx7400 (RU429EA#A... | [ce0542775b](https://linux-hardware.org/?probe=ce0542775b) | Jun 22, 2021 |
| Lenovo        | ThinkPad X201 Tablet 298... | [d04705eaef](https://linux-hardware.org/?probe=d04705eaef) | Jun 20, 2021 |
| ASUSTek       | G551JK                      | [aace05a48f](https://linux-hardware.org/?probe=aace05a48f) | Jun 17, 2021 |
| ASUSTek       | G551JK                      | [2947ae8fc2](https://linux-hardware.org/?probe=2947ae8fc2) | Jun 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [80b26a6c37](https://linux-hardware.org/?probe=80b26a6c37) | Jun 16, 2021 |
| Dell          | Inspiron 15-3567            | [8487e42c1e](https://linux-hardware.org/?probe=8487e42c1e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [18fd922adc](https://linux-hardware.org/?probe=18fd922adc) | Jun 10, 2021 |
| Dell          | Latitude 5520               | [45b3e7c2af](https://linux-hardware.org/?probe=45b3e7c2af) | Jun 06, 2021 |
| Dell          | Vostro 5402                 | [ec4c7c0192](https://linux-hardware.org/?probe=ec4c7c0192) | Jun 04, 2021 |
| MSI           | CR500                       | [76d2d77034](https://linux-hardware.org/?probe=76d2d77034) | Jun 03, 2021 |
| MSI           | CR500                       | [93f6fd0ae4](https://linux-hardware.org/?probe=93f6fd0ae4) | Jun 02, 2021 |
| MSI           | CR500                       | [b1d00d1444](https://linux-hardware.org/?probe=b1d00d1444) | May 30, 2021 |
| HP            | Notebook                    | [f60121b761](https://linux-hardware.org/?probe=f60121b761) | May 30, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| Apple         | MacBookPro1,1               | [cc14c7fa2e](https://linux-hardware.org/?probe=cc14c7fa2e) | May 16, 2021 |
| HP            | ProBook 4530s               | [3d5a77511e](https://linux-hardware.org/?probe=3d5a77511e) | May 12, 2021 |
| Dell          | Vostro 5402                 | [03aa94f52f](https://linux-hardware.org/?probe=03aa94f52f) | May 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [b57920ccda](https://linux-hardware.org/?probe=b57920ccda) | May 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [19bf5a98df](https://linux-hardware.org/?probe=19bf5a98df) | May 10, 2021 |
| ASUSTek       | K53E                        | [314e6bbbd2](https://linux-hardware.org/?probe=314e6bbbd2) | May 04, 2021 |
| ASUSTek       | K53E                        | [9a34eba18a](https://linux-hardware.org/?probe=9a34eba18a) | May 03, 2021 |
| Fujitsu Si... | AMILO Pi 2512               | [bc0294a996](https://linux-hardware.org/?probe=bc0294a996) | May 03, 2021 |
| HP            | EliteBook 2540p             | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3B00... | [fa546522c1](https://linux-hardware.org/?probe=fa546522c1) | May 02, 2021 |
| Medion        | P6812                       | [a45bd7fc22](https://linux-hardware.org/?probe=a45bd7fc22) | Apr 19, 2021 |
| Acer          | Aspire A315-31              | [2b821447d2](https://linux-hardware.org/?probe=2b821447d2) | Apr 14, 2021 |
| Acer          | Aspire A315-31              | [e7a7c4b64f](https://linux-hardware.org/?probe=e7a7c4b64f) | Apr 14, 2021 |
| Acer          | Aspire A315-23              | [c7a0c1bf24](https://linux-hardware.org/?probe=c7a0c1bf24) | Apr 13, 2021 |
| HP            | Pavilion 15                 | [88ca55e5af](https://linux-hardware.org/?probe=88ca55e5af) | Apr 08, 2021 |
| Acer          | Aspire A515-51G             | [97f260c7d5](https://linux-hardware.org/?probe=97f260c7d5) | Mar 31, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [084a69a05a](https://linux-hardware.org/?probe=084a69a05a) | Mar 30, 2021 |
| Dell          | G5 5587                     | [862386a9b4](https://linux-hardware.org/?probe=862386a9b4) | Mar 27, 2021 |
| HP            | Laptop 15-db1xxx            | [59fb434d97](https://linux-hardware.org/?probe=59fb434d97) | Mar 21, 2021 |
| HP            | Laptop 15-db1xxx            | [aab4f11f05](https://linux-hardware.org/?probe=aab4f11f05) | Mar 21, 2021 |
| Dell          | Inspiron 3542               | [517406f8b6](https://linux-hardware.org/?probe=517406f8b6) | Mar 21, 2021 |
| HP            | ZBook 15 G3                 | [4ab4d49018](https://linux-hardware.org/?probe=4ab4d49018) | Mar 17, 2021 |
| HP            | Laptop 15-da1xxx            | [ed4ddd6238](https://linux-hardware.org/?probe=ed4ddd6238) | Mar 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [640a0a3857](https://linux-hardware.org/?probe=640a0a3857) | Mar 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [66de852009](https://linux-hardware.org/?probe=66de852009) | Mar 11, 2021 |
| Acer          | Aspire 5742G                | [659f9d690c](https://linux-hardware.org/?probe=659f9d690c) | Mar 10, 2021 |
| Dell          | Latitude E6320              | [a69653a323](https://linux-hardware.org/?probe=a69653a323) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7d5313fdad](https://linux-hardware.org/?probe=7d5313fdad) | Mar 06, 2021 |
| Toshiba       | Satellite L20               | [875478a51a](https://linux-hardware.org/?probe=875478a51a) | Mar 06, 2021 |
| HP            | ProBook 650 G1              | [e21aaf16e3](https://linux-hardware.org/?probe=e21aaf16e3) | Mar 03, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a94321f4aa](https://linux-hardware.org/?probe=a94321f4aa) | Feb 27, 2021 |
| Dell          | Inspiron 7520               | [4611155200](https://linux-hardware.org/?probe=4611155200) | Feb 20, 2021 |
| HP            | ProBook 470 G3              | [12ef122267](https://linux-hardware.org/?probe=12ef122267) | Feb 19, 2021 |
| Dell          | Inspiron 3542               | [d77d8a8749](https://linux-hardware.org/?probe=d77d8a8749) | Feb 18, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5843b21ecd](https://linux-hardware.org/?probe=5843b21ecd) | Feb 14, 2021 |
| HP            | ProBook 650 G1              | [2dcb1a408a](https://linux-hardware.org/?probe=2dcb1a408a) | Feb 13, 2021 |
| HP            | ProBook 650 G1              | [1d63d4f78d](https://linux-hardware.org/?probe=1d63d4f78d) | Feb 10, 2021 |
| Dell          | Latitude E5470              | [ac140ada48](https://linux-hardware.org/?probe=ac140ada48) | Feb 09, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [e80a31db39](https://linux-hardware.org/?probe=e80a31db39) | Feb 03, 2021 |
| Dell          | Latitude E5470              | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| Dell          | Latitude E6430              | [b7f8906f0f](https://linux-hardware.org/?probe=b7f8906f0f) | Jan 27, 2021 |
| Lenovo        | IdeaPad Y570 20091          | [68fdde328b](https://linux-hardware.org/?probe=68fdde328b) | Jan 27, 2021 |
| HP            | EliteBook 8560p             | [875db98e08](https://linux-hardware.org/?probe=875db98e08) | Jan 23, 2021 |
| Acer          | Aspire 5736Z                | [6bb8df4de2](https://linux-hardware.org/?probe=6bb8df4de2) | Jan 21, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [9f77ea6e17](https://linux-hardware.org/?probe=9f77ea6e17) | Jan 14, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [ab2decc440](https://linux-hardware.org/?probe=ab2decc440) | Jan 12, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote TS11HR             | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7e0f5ef3ce](https://linux-hardware.org/?probe=7e0f5ef3ce) | Jan 04, 2021 |
| Toshiba       | Satellite C650              | [da33e577bf](https://linux-hardware.org/?probe=da33e577bf) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| Toshiba       | Satellite C650              | [3ccf619144](https://linux-hardware.org/?probe=3ccf619144) | Dec 31, 2020 |
| ASUSTek       | X541NA                      | [ce08535027](https://linux-hardware.org/?probe=ce08535027) | Dec 25, 2020 |
| ASUSTek       | X541NA                      | [a026c30d04](https://linux-hardware.org/?probe=a026c30d04) | Dec 25, 2020 |
| HP            | Laptop 15-db0xxx            | [87ecbeb3f9](https://linux-hardware.org/?probe=87ecbeb3f9) | Dec 22, 2020 |
| Lenovo        | V330-15IKB 81AX             | [7bbfaa08a2](https://linux-hardware.org/?probe=7bbfaa08a2) | Dec 19, 2020 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [a3f26b77de](https://linux-hardware.org/?probe=a3f26b77de) | Dec 17, 2020 |
| Acer          | Aspire A315-31              | [3d19374493](https://linux-hardware.org/?probe=3d19374493) | Dec 17, 2020 |
| Dell          | XPS 13 9380                 | [1eae71a2dd](https://linux-hardware.org/?probe=1eae71a2dd) | Dec 14, 2020 |
| Acer          | Aspire A315-31              | [630a5fce15](https://linux-hardware.org/?probe=630a5fce15) | Dec 11, 2020 |
| Acer          | Aspire A715-75G             | [9c6b3be687](https://linux-hardware.org/?probe=9c6b3be687) | Dec 10, 2020 |
| Acer          | Aspire A717-71G             | [f355a859fe](https://linux-hardware.org/?probe=f355a859fe) | Dec 05, 2020 |
| Acer          | Aspire A717-71G             | [e0144299e5](https://linux-hardware.org/?probe=e0144299e5) | Dec 05, 2020 |
| Acer          | Aspire A715-75G             | [4d6f15896a](https://linux-hardware.org/?probe=4d6f15896a) | Dec 01, 2020 |
| Acer          | Aspire A715-75G             | [cea1efd2f4](https://linux-hardware.org/?probe=cea1efd2f4) | Dec 01, 2020 |
| Acer          | Aspire ES1-533              | [e20dc3c4e4](https://linux-hardware.org/?probe=e20dc3c4e4) | Nov 26, 2020 |
| Acer          | Aspire ES1-533              | [1ff481eb22](https://linux-hardware.org/?probe=1ff481eb22) | Nov 26, 2020 |
| Lenovo        | V15-ADA 82C7                | [c25d3746ee](https://linux-hardware.org/?probe=c25d3746ee) | Nov 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [b59cef94de](https://linux-hardware.org/?probe=b59cef94de) | Nov 22, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [cb540754ed](https://linux-hardware.org/?probe=cb540754ed) | Nov 22, 2020 |
| MSI           | CR610                       | [8e7bf69342](https://linux-hardware.org/?probe=8e7bf69342) | Nov 22, 2020 |
| MSI           | CR610                       | [ba50d62533](https://linux-hardware.org/?probe=ba50d62533) | Nov 22, 2020 |
| Dell          | Inspiron 3541               | [f10a3f7947](https://linux-hardware.org/?probe=f10a3f7947) | Nov 21, 2020 |
| Dell          | Inspiron 3541               | [28a2250b7c](https://linux-hardware.org/?probe=28a2250b7c) | Nov 21, 2020 |
| Lenovo        | V130-14IGM 81HM             | [e282aa9ff3](https://linux-hardware.org/?probe=e282aa9ff3) | Nov 20, 2020 |
| Lenovo        | V15-ADA 82C7                | [aa224b81ef](https://linux-hardware.org/?probe=aa224b81ef) | Nov 18, 2020 |
| HP            | Laptop 15-da0xxx            | [2cc03df5d0](https://linux-hardware.org/?probe=2cc03df5d0) | Nov 16, 2020 |
| HP            | Pavilion Notebook           | [c68070f9b3](https://linux-hardware.org/?probe=c68070f9b3) | Nov 10, 2020 |
| HP            | Pavilion Notebook           | [99e25d58ad](https://linux-hardware.org/?probe=99e25d58ad) | Nov 10, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [9555e785bb](https://linux-hardware.org/?probe=9555e785bb) | Nov 09, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [0de6c928a4](https://linux-hardware.org/?probe=0de6c928a4) | Nov 09, 2020 |
| Lenovo        | V130-14IGM 81HM             | [23fd9c7140](https://linux-hardware.org/?probe=23fd9c7140) | Nov 09, 2020 |
| Dell          | Inspiron 1720               | [d2018981ad](https://linux-hardware.org/?probe=d2018981ad) | Nov 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | [c6872a9a60](https://linux-hardware.org/?probe=c6872a9a60) | Nov 03, 2020 |
| ASUSTek       | X541NA                      | [a3067761af](https://linux-hardware.org/?probe=a3067761af) | Oct 18, 2020 |
| ASUSTek       | X541NA                      | [baf94800b6](https://linux-hardware.org/?probe=baf94800b6) | Oct 18, 2020 |
| Lenovo        | 3000 N200 0769BNG           | [233a47535c](https://linux-hardware.org/?probe=233a47535c) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [9356879a60](https://linux-hardware.org/?probe=9356879a60) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ccef20bb6](https://linux-hardware.org/?probe=4ccef20bb6) | Oct 13, 2020 |
| Lenovo        | 3000 N200 0769BNG           | [8ea03b6d29](https://linux-hardware.org/?probe=8ea03b6d29) | Oct 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [43c0586dbe](https://linux-hardware.org/?probe=43c0586dbe) | Oct 12, 2020 |
| Acer          | Aspire A315-31              | [00686fcd7b](https://linux-hardware.org/?probe=00686fcd7b) | Oct 12, 2020 |
| Dell          | Latitude E5470              | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| Acer          | Aspire A515-55              | [d88d774f7f](https://linux-hardware.org/?probe=d88d774f7f) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | [c25c3ef2d8](https://linux-hardware.org/?probe=c25c3ef2d8) | Oct 05, 2020 |
| Lenovo        | B50-45 20388                | [e3d174f961](https://linux-hardware.org/?probe=e3d174f961) | Oct 05, 2020 |
| Lenovo        | V330-15IKB 81AX             | [cb2c394f1a](https://linux-hardware.org/?probe=cb2c394f1a) | Oct 02, 2020 |
| HP            | Notebook                    | [9fcfc67d9c](https://linux-hardware.org/?probe=9fcfc67d9c) | Sep 29, 2020 |
| Lenovo        | V330-15IKB 81AX             | [1734ca75eb](https://linux-hardware.org/?probe=1734ca75eb) | Sep 29, 2020 |
| Lenovo        | ThinkPad T440p 20AWS0KK0... | [d231920967](https://linux-hardware.org/?probe=d231920967) | Sep 28, 2020 |
| HP            | 355 G2                      | [07981744ab](https://linux-hardware.org/?probe=07981744ab) | Sep 27, 2020 |
| HP            | 355 G2                      | [08e4ab3c53](https://linux-hardware.org/?probe=08e4ab3c53) | Sep 26, 2020 |
| Lenovo        | V330-15IKB 81AX             | [a34c376304](https://linux-hardware.org/?probe=a34c376304) | Sep 18, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [20c5e9395d](https://linux-hardware.org/?probe=20c5e9395d) | Sep 16, 2020 |
| Toshiba       | QOSMIO F50                  | [b60fe2f9e5](https://linux-hardware.org/?probe=b60fe2f9e5) | Sep 16, 2020 |
| HP            | Laptop 17-by2xxx            | [d3fcaecf43](https://linux-hardware.org/?probe=d3fcaecf43) | Sep 12, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [eea494974a](https://linux-hardware.org/?probe=eea494974a) | Sep 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [00956078a0](https://linux-hardware.org/?probe=00956078a0) | Sep 03, 2020 |
| Acer          | AOA150                      | [d7397a31d7](https://linux-hardware.org/?probe=d7397a31d7) | Aug 31, 2020 |
| Dell          | Inspiron 3593               | [2c97a34461](https://linux-hardware.org/?probe=2c97a34461) | Aug 20, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| Lenovo        | ThinkPad T480 20L6S43212    | [e408e4045b](https://linux-hardware.org/?probe=e408e4045b) | Aug 16, 2020 |
| Dell          | Inspiron 5577               | [f10ef91563](https://linux-hardware.org/?probe=f10ef91563) | Aug 06, 2020 |
| MSI           | CR500                       | [a347574891](https://linux-hardware.org/?probe=a347574891) | Aug 03, 2020 |
| MSI           | CR500                       | [21b1264f8c](https://linux-hardware.org/?probe=21b1264f8c) | Aug 03, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [a2dd413553](https://linux-hardware.org/?probe=a2dd413553) | Jul 26, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e1073052d4](https://linux-hardware.org/?probe=e1073052d4) | Jul 26, 2020 |
| HP            | ProBook 450 G1              | [8db5efa1fc](https://linux-hardware.org/?probe=8db5efa1fc) | Jul 22, 2020 |
| Acer          | Aspire A315-42              | [b5aacd7b39](https://linux-hardware.org/?probe=b5aacd7b39) | Jul 12, 2020 |
| Acer          | Aspire A315-42              | [88afcfbe5b](https://linux-hardware.org/?probe=88afcfbe5b) | Jul 11, 2020 |
| Lenovo        | V110-15AST 80TD             | [6a86c949a2](https://linux-hardware.org/?probe=6a86c949a2) | Jul 10, 2020 |
| Acer          | Aspire A315-31              | [3ab4bed99e](https://linux-hardware.org/?probe=3ab4bed99e) | Jul 05, 2020 |
| Acer          | Aspire E1-531               | [7baad79bd7](https://linux-hardware.org/?probe=7baad79bd7) | Jul 04, 2020 |
| Lenovo        | V110-15AST 80TD             | [16211b52a1](https://linux-hardware.org/?probe=16211b52a1) | Jun 25, 2020 |
| Sony          | VPCZ21X9E                   | [72e4be4ea5](https://linux-hardware.org/?probe=72e4be4ea5) | Jun 12, 2020 |
| Sony          | VPCZ21X9E                   | [26affa7385](https://linux-hardware.org/?probe=26affa7385) | Jun 12, 2020 |
| Apple         | MacBook5,1                  | [099f5faf14](https://linux-hardware.org/?probe=099f5faf14) | Jun 02, 2020 |
| ASUSTek       | N550JX                      | [99693da42c](https://linux-hardware.org/?probe=99693da42c) | May 31, 2020 |
| Dell          | Inspiron 5559               | [3eee5b1f3d](https://linux-hardware.org/?probe=3eee5b1f3d) | May 31, 2020 |
| HP            | 250 G5 Notebook PC          | [1a72632c64](https://linux-hardware.org/?probe=1a72632c64) | May 27, 2020 |
| Lenovo        | V330-15IKB 81AX             | [c4087d6c6a](https://linux-hardware.org/?probe=c4087d6c6a) | May 21, 2020 |
| ASUSTek       | K50AB                       | [96ccf326a8](https://linux-hardware.org/?probe=96ccf326a8) | May 19, 2020 |
| Dell          | Inspiron N5010              | [f1e4f13c21](https://linux-hardware.org/?probe=f1e4f13c21) | May 18, 2020 |
| Lenovo        | V310-15ISK 80SY             | [a608769eb0](https://linux-hardware.org/?probe=a608769eb0) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [92e676e189](https://linux-hardware.org/?probe=92e676e189) | May 15, 2020 |
| Lenovo        | ThinkPad T460 20FNS0KT00    | [b7fd9a70e0](https://linux-hardware.org/?probe=b7fd9a70e0) | May 15, 2020 |
| ASUSTek       | G551JK                      | [1d29493d79](https://linux-hardware.org/?probe=1d29493d79) | May 14, 2020 |
| ASUSTek       | G551JK                      | [2aa55f08d0](https://linux-hardware.org/?probe=2aa55f08d0) | May 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [03ba757adf](https://linux-hardware.org/?probe=03ba757adf) | May 13, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [dadd9d2790](https://linux-hardware.org/?probe=dadd9d2790) | May 12, 2020 |
| HP            | ZBook 15 G3                 | [3474070eb8](https://linux-hardware.org/?probe=3474070eb8) | May 10, 2020 |
| Lenovo        | G50-30 80G0                 | [4ac3289ec9](https://linux-hardware.org/?probe=4ac3289ec9) | May 09, 2020 |
| ASUSTek       | K54C                        | [3188c4843a](https://linux-hardware.org/?probe=3188c4843a) | May 08, 2020 |
| Dell          | Inspiron 5567               | [099e174bf4](https://linux-hardware.org/?probe=099e174bf4) | May 07, 2020 |
| Lenovo        | ThinkPad L470 20J5S4RS00    | [b646e36068](https://linux-hardware.org/?probe=b646e36068) | May 04, 2020 |
| Dell          | Inspiron 3537               | [a26c6f5812](https://linux-hardware.org/?probe=a26c6f5812) | Apr 21, 2020 |
| HP            | 250 G5 Notebook PC          | [01f3f0f185](https://linux-hardware.org/?probe=01f3f0f185) | Apr 14, 2020 |
| Lenovo        | ThinkPad E560 20EV003EMS    | [0b978ac786](https://linux-hardware.org/?probe=0b978ac786) | Apr 14, 2020 |
| HP            | ZBook 15 G3                 | [16ee557e51](https://linux-hardware.org/?probe=16ee557e51) | Apr 12, 2020 |
| HP            | Mini 110-3100               | [a32c0db8bb](https://linux-hardware.org/?probe=a32c0db8bb) | Apr 11, 2020 |
| Acer          | Aspire 7520G                | [d5bc992097](https://linux-hardware.org/?probe=d5bc992097) | Apr 04, 2020 |
| Toshiba       | TECRA Z50-A                 | [889a5aa1a6](https://linux-hardware.org/?probe=889a5aa1a6) | Apr 02, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [cb84e8c9af](https://linux-hardware.org/?probe=cb84e8c9af) | Mar 23, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [8670fa919e](https://linux-hardware.org/?probe=8670fa919e) | Mar 23, 2020 |
| ASUSTek       | X541NC                      | [63b197a2c0](https://linux-hardware.org/?probe=63b197a2c0) | Mar 21, 2020 |
| Fujitsu Si... | AMILO Li3710                | [11ebf93798](https://linux-hardware.org/?probe=11ebf93798) | Mar 18, 2020 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b19ba42878](https://linux-hardware.org/?probe=b19ba42878) | Mar 17, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [334884c294](https://linux-hardware.org/?probe=334884c294) | Mar 10, 2020 |
| HP            | 250 G1                      | [7a7e2dfcee](https://linux-hardware.org/?probe=7a7e2dfcee) | Mar 10, 2020 |
| HP            | 250 G4                      | [d8b2caab0f](https://linux-hardware.org/?probe=d8b2caab0f) | Mar 08, 2020 |
| Acer          | Aspire A315-41              | [5870ecc433](https://linux-hardware.org/?probe=5870ecc433) | Mar 08, 2020 |
| Acer          | Aspire E3-112               | [62041aa7fa](https://linux-hardware.org/?probe=62041aa7fa) | Mar 08, 2020 |
| Lenovo        | ThinkPad T500 2056W2J       | [1923e28174](https://linux-hardware.org/?probe=1923e28174) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bda2f29230](https://linux-hardware.org/?probe=bda2f29230) | Feb 24, 2020 |
| Fujitsu       | LIFEBOOK AH530              | [5d93dd0911](https://linux-hardware.org/?probe=5d93dd0911) | Feb 20, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [eb55029938](https://linux-hardware.org/?probe=eb55029938) | Feb 18, 2020 |
| ASUSTek       | X551MA                      | [530fb26de2](https://linux-hardware.org/?probe=530fb26de2) | Feb 16, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4d942fa22c](https://linux-hardware.org/?probe=4d942fa22c) | Feb 10, 2020 |
| ASUSTek       | X541UVK                     | [9e44db3513](https://linux-hardware.org/?probe=9e44db3513) | Feb 06, 2020 |
| Lenovo        | G505 20240                  | [3208a023bf](https://linux-hardware.org/?probe=3208a023bf) | Feb 04, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [91bdd7eccf](https://linux-hardware.org/?probe=91bdd7eccf) | Feb 01, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a4a64dfa74](https://linux-hardware.org/?probe=a4a64dfa74) | Feb 01, 2020 |
| Acer          | Aspire E1-530               | [0e64af354b](https://linux-hardware.org/?probe=0e64af354b) | Jan 30, 2020 |
| Acer          | Swift SF314-56              | [303332d310](https://linux-hardware.org/?probe=303332d310) | Jan 29, 2020 |
| Toshiba       | Satellite C50-B             | [06c487df1d](https://linux-hardware.org/?probe=06c487df1d) | Jan 28, 2020 |
| Acer          | Aspire A315-31              | [b482e7ef86](https://linux-hardware.org/?probe=b482e7ef86) | Jan 25, 2020 |
| Lenovo        | ThinkPad T520 42406AG       | [7de4fdce8d](https://linux-hardware.org/?probe=7de4fdce8d) | Jan 23, 2020 |
| Lenovo        | V330-15IKB 81AX             | [b0d2c5611e](https://linux-hardware.org/?probe=b0d2c5611e) | Jan 22, 2020 |
| HP            | Compaq nc6320 (RU381ES#A... | [d3a7e386ae](https://linux-hardware.org/?probe=d3a7e386ae) | Jan 16, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [84bf577e7d](https://linux-hardware.org/?probe=84bf577e7d) | Jan 16, 2020 |
| Acer          | Aspire A315-31              | [36dcda44ba](https://linux-hardware.org/?probe=36dcda44ba) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [cc4a9ba559](https://linux-hardware.org/?probe=cc4a9ba559) | Jan 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [72f2c4c12a](https://linux-hardware.org/?probe=72f2c4c12a) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b5d63aec77](https://linux-hardware.org/?probe=b5d63aec77) | Jan 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d389b1fcb](https://linux-hardware.org/?probe=7d389b1fcb) | Jan 15, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [b2c0da1b44](https://linux-hardware.org/?probe=b2c0da1b44) | Jan 12, 2020 |
| HP            | ProBook 650 G1              | [224d2a830f](https://linux-hardware.org/?probe=224d2a830f) | Jan 08, 2020 |
| ASUSTek       | X55A                        | [3482727e9f](https://linux-hardware.org/?probe=3482727e9f) | Jan 03, 2020 |
| Lenovo        | ThinkPad P50 20EQS1AC00     | [0767220809](https://linux-hardware.org/?probe=0767220809) | Jan 03, 2020 |
| Dell          | Inspiron 3558               | [63be3850f8](https://linux-hardware.org/?probe=63be3850f8) | Dec 31, 2019 |
| Acer          | Aspire A315-51              | [fb858f1586](https://linux-hardware.org/?probe=fb858f1586) | Dec 30, 2019 |
| Acer          | Aspire A315-51              | [0dfa591b1c](https://linux-hardware.org/?probe=0dfa591b1c) | Dec 30, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [dfac3d950c](https://linux-hardware.org/?probe=dfac3d950c) | Dec 29, 2019 |
| Samsung       | N250P/N145P                 | [708195d4f1](https://linux-hardware.org/?probe=708195d4f1) | Dec 27, 2019 |
| Toshiba       | Satellite C850-1H6          | [a0ffb29c6c](https://linux-hardware.org/?probe=a0ffb29c6c) | Dec 18, 2019 |
| HP            | ProBook 640 G1              | [0813940da0](https://linux-hardware.org/?probe=0813940da0) | Dec 09, 2019 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3193d44169](https://linux-hardware.org/?probe=3193d44169) | Dec 04, 2019 |
| ASUSTek       | X550MJ                      | [3fde87c7b4](https://linux-hardware.org/?probe=3fde87c7b4) | Dec 04, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8a33af729e](https://linux-hardware.org/?probe=8a33af729e) | Dec 03, 2019 |
| Acer          | Aspire A315-51              | [77affe222c](https://linux-hardware.org/?probe=77affe222c) | Nov 16, 2019 |
| HP            | Notebook                    | [8df47391f9](https://linux-hardware.org/?probe=8df47391f9) | Nov 15, 2019 |
| Acer          | Aspire A315-31              | [3812d4729c](https://linux-hardware.org/?probe=3812d4729c) | Nov 14, 2019 |
| HP            | Notebook                    | [fe0316d8bb](https://linux-hardware.org/?probe=fe0316d8bb) | Nov 14, 2019 |
| Lenovo        | ThinkPad T420s 4174BB2      | [53037be14e](https://linux-hardware.org/?probe=53037be14e) | Nov 03, 2019 |
| Lenovo        | ThinkPad Edge E330 33544... | [c27afaa8d2](https://linux-hardware.org/?probe=c27afaa8d2) | Oct 20, 2019 |
| Acer          | Aspire 5350                 | [bfca910110](https://linux-hardware.org/?probe=bfca910110) | Oct 20, 2019 |
| Lenovo        | ThinkPad Edge E330 33544... | [0e391bc5f7](https://linux-hardware.org/?probe=0e391bc5f7) | Oct 20, 2019 |
| HP            | ProBook 650 G1              | [4886df0de1](https://linux-hardware.org/?probe=4886df0de1) | Oct 20, 2019 |
| Acer          | Aspire 5350                 | [6c1a1b4cd5](https://linux-hardware.org/?probe=6c1a1b4cd5) | Oct 19, 2019 |
| Dell          | Latitude 5580               | [e2d5fd3182](https://linux-hardware.org/?probe=e2d5fd3182) | Oct 18, 2019 |
| Dell          | Latitude 5580               | [fbb2c68803](https://linux-hardware.org/?probe=fbb2c68803) | Oct 18, 2019 |
| Dell          | Latitude 5580               | [4ba29dd71c](https://linux-hardware.org/?probe=4ba29dd71c) | Oct 18, 2019 |
| Acer          | Aspire A315-31              | [2ab608ac7e](https://linux-hardware.org/?probe=2ab608ac7e) | Oct 13, 2019 |
| HP            | Pavilion Notebook           | [dffd6ce6cb](https://linux-hardware.org/?probe=dffd6ce6cb) | Oct 13, 2019 |
| Lenovo        | IdeaPad S540-14API 81NH     | [d0671b5d7f](https://linux-hardware.org/?probe=d0671b5d7f) | Oct 12, 2019 |
| Acer          | Aspire A717-71G             | [4bad7bd17c](https://linux-hardware.org/?probe=4bad7bd17c) | Sep 21, 2019 |
| Lenovo        | ThinkPad T520 42406AG       | [3e835a3fea](https://linux-hardware.org/?probe=3e835a3fea) | Sep 15, 2019 |
| Razer         | Blade                       | [da397f901b](https://linux-hardware.org/?probe=da397f901b) | Sep 10, 2019 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [655aa5059b](https://linux-hardware.org/?probe=655aa5059b) | Sep 04, 2019 |
| HP            | Laptop 15-ra0xx             | [2e41137334](https://linux-hardware.org/?probe=2e41137334) | Sep 03, 2019 |
| HP            | Laptop 15-ra0xx             | [8aadf9c34a](https://linux-hardware.org/?probe=8aadf9c34a) | Sep 02, 2019 |
| HP            | Laptop 15-ra0xx             | [96e535cece](https://linux-hardware.org/?probe=96e535cece) | Sep 02, 2019 |
| Acer          | Aspire A315-31              | [9d8698e977](https://linux-hardware.org/?probe=9d8698e977) | Aug 28, 2019 |
| Acer          | Aspire A315-31              | [95dba17d9a](https://linux-hardware.org/?probe=95dba17d9a) | Aug 17, 2019 |
| Dell          | Precision 7730              | [b9281326d7](https://linux-hardware.org/?probe=b9281326d7) | Jul 25, 2019 |
| ASUSTek       | X201EP                      | [a1a1f1965a](https://linux-hardware.org/?probe=a1a1f1965a) | Jul 22, 2019 |
| Dell          | Latitude E5440              | [f40c3d18fb](https://linux-hardware.org/?probe=f40c3d18fb) | Jul 19, 2019 |
| Lenovo        | ThinkPad P51 20HHS04800     | [4013dc5bc1](https://linux-hardware.org/?probe=4013dc5bc1) | Jul 16, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1613715663](https://linux-hardware.org/?probe=1613715663) | Jul 15, 2019 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62ebee4d1f](https://linux-hardware.org/?probe=62ebee4d1f) | Jul 15, 2019 |
| ASUSTek       | X541NA                      | [5fdb751780](https://linux-hardware.org/?probe=5fdb751780) | Jul 11, 2019 |
| ASUSTek       | X541NA                      | [8676bfc466](https://linux-hardware.org/?probe=8676bfc466) | Jul 11, 2019 |
| HP            | Laptop 15-ra0xx             | [f28399b983](https://linux-hardware.org/?probe=f28399b983) | Jul 09, 2019 |
| Toshiba       | Satellite L755              | [e2413cea5d](https://linux-hardware.org/?probe=e2413cea5d) | Jul 06, 2019 |
| HP            | 250 G6 Notebook PC          | [7d8551e612](https://linux-hardware.org/?probe=7d8551e612) | Jun 29, 2019 |
| Lenovo        | G500 20236                  | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| HP            | Laptop 15-db0xxx            | [df6f074dbd](https://linux-hardware.org/?probe=df6f074dbd) | Jun 11, 2019 |
| IBM           | ThinkPad R52p 1847W5R       | [1dc1d8e6f2](https://linux-hardware.org/?probe=1dc1d8e6f2) | Jun 09, 2019 |
| HP            | Unknown                     | [cf3a7ad203](https://linux-hardware.org/?probe=cf3a7ad203) | Jun 05, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f1a85fe5ba](https://linux-hardware.org/?probe=f1a85fe5ba) | Jun 05, 2019 |
| HP            | Pavilion Notebook           | [ad610739b6](https://linux-hardware.org/?probe=ad610739b6) | Jun 01, 2019 |
| HP            | Pavilion Notebook           | [476f3cfb4a](https://linux-hardware.org/?probe=476f3cfb4a) | May 26, 2019 |
| Acer          | Aspire A717-71G             | [882e32aaf7](https://linux-hardware.org/?probe=882e32aaf7) | May 21, 2019 |
| Dell          | Inspiron 5567               | [29fadee02e](https://linux-hardware.org/?probe=29fadee02e) | May 19, 2019 |
| Lenovo        | V330-15IKB 81AX             | [8f1cfe4955](https://linux-hardware.org/?probe=8f1cfe4955) | May 17, 2019 |
| HP            | 250 G1                      | [4550b3fdf6](https://linux-hardware.org/?probe=4550b3fdf6) | May 17, 2019 |
| HP            | 250 G1                      | [7dda48b144](https://linux-hardware.org/?probe=7dda48b144) | May 17, 2019 |
| ASUSTek       | X541SA                      | [dff8b29714](https://linux-hardware.org/?probe=dff8b29714) | May 10, 2019 |
| ASUSTek       | X541SA                      | [308cc99aee](https://linux-hardware.org/?probe=308cc99aee) | May 10, 2019 |
| ASUSTek       | X541SA                      | [f03f0840fb](https://linux-hardware.org/?probe=f03f0840fb) | May 10, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [8195906a99](https://linux-hardware.org/?probe=8195906a99) | May 06, 2019 |
| Acer          | Aspire E1-530               | [e5658355fa](https://linux-hardware.org/?probe=e5658355fa) | May 03, 2019 |
| LG Electro... | LW70-JJKG                   | [76f306de39](https://linux-hardware.org/?probe=76f306de39) | Apr 27, 2019 |
| Dell          | G3 3779                     | [8407de048a](https://linux-hardware.org/?probe=8407de048a) | Apr 26, 2019 |
| Acer          | Aspire A717-71G             | [7385402cb8](https://linux-hardware.org/?probe=7385402cb8) | Apr 25, 2019 |
| ASUSTek       | X541NC                      | [50aeeec380](https://linux-hardware.org/?probe=50aeeec380) | Apr 19, 2019 |
| ASUSTek       | X541NC                      | [5278c50f95](https://linux-hardware.org/?probe=5278c50f95) | Apr 13, 2019 |
| Fujitsu Si... | AMILO PRO V3515             | [1d96b8f60d](https://linux-hardware.org/?probe=1d96b8f60d) | Apr 11, 2019 |
| ASUSTek       | X541NA                      | [b94a9e24c1](https://linux-hardware.org/?probe=b94a9e24c1) | Apr 07, 2019 |
| Toshiba       | Satellite C870-17H          | [dc2ce35421](https://linux-hardware.org/?probe=dc2ce35421) | Apr 06, 2019 |
| Acer          | Aspire A717-71G             | [600ac82384](https://linux-hardware.org/?probe=600ac82384) | Mar 30, 2019 |
| Acer          | Aspire 6935                 | [d8a5d80999](https://linux-hardware.org/?probe=d8a5d80999) | Mar 23, 2019 |
| Dell          | Inspiron N5110              | [5137b5b274](https://linux-hardware.org/?probe=5137b5b274) | Mar 21, 2019 |
| HP            | Pavilion dv5                | [3f857e2920](https://linux-hardware.org/?probe=3f857e2920) | Mar 18, 2019 |
| ASUSTek       | X550MD                      | [4e37ad043d](https://linux-hardware.org/?probe=4e37ad043d) | Mar 14, 2019 |
| Sony          | VGN-FE31Z                   | [860dcaf74d](https://linux-hardware.org/?probe=860dcaf74d) | Feb 16, 2019 |
| Dell          | Precision M4600             | [6f6a52607b](https://linux-hardware.org/?probe=6f6a52607b) | Feb 14, 2019 |
| ASUSTek       | X540LA                      | [03ab6a3cd8](https://linux-hardware.org/?probe=03ab6a3cd8) | Feb 11, 2019 |
| Acer          | Aspire A315-21              | [b28972ad25](https://linux-hardware.org/?probe=b28972ad25) | Feb 10, 2019 |
| MSI           | MS-16Y1                     | [a676d0126f](https://linux-hardware.org/?probe=a676d0126f) | Feb 07, 2019 |
| ASUSTek       | X540LA                      | [a7cb02a6fb](https://linux-hardware.org/?probe=a7cb02a6fb) | Feb 02, 2019 |
| ASUSTek       | X540LA                      | [18752af5af](https://linux-hardware.org/?probe=18752af5af) | Jan 31, 2019 |
| ASUSTek       | X540LA                      | [dea612f99d](https://linux-hardware.org/?probe=dea612f99d) | Jan 31, 2019 |
| ASUSTek       | X541NA                      | [d66eb82eac](https://linux-hardware.org/?probe=d66eb82eac) | Jan 23, 2019 |
| ASUSTek       | K55DR                       | [13a17add51](https://linux-hardware.org/?probe=13a17add51) | Jan 22, 2019 |
| Acer          | Aspire ES1-532G             | [af17a54207](https://linux-hardware.org/?probe=af17a54207) | Jan 12, 2019 |
| ASUSTek       | X541NA                      | [53fba97f8a](https://linux-hardware.org/?probe=53fba97f8a) | Jan 04, 2019 |
| ASUSTek       | X541NA                      | [a0cb966487](https://linux-hardware.org/?probe=a0cb966487) | Jan 04, 2019 |
| Acer          | Aspire A717-71G             | [c3edad77d8](https://linux-hardware.org/?probe=c3edad77d8) | Dec 24, 2018 |
| Acer          | Aspire A315-21              | [9289091c83](https://linux-hardware.org/?probe=9289091c83) | Nov 28, 2018 |
| Acer          | Aspire A717-71G             | [3c22bb7c43](https://linux-hardware.org/?probe=3c22bb7c43) | Nov 04, 2018 |
| Acer          | Aspire A717-71G             | [65968eaade](https://linux-hardware.org/?probe=65968eaade) | Nov 01, 2018 |
| HP            | 15                          | [a6c00a0fde](https://linux-hardware.org/?probe=a6c00a0fde) | Jul 08, 2018 |
| HP            | 250 G5 Notebook PC          | [24f9e4ee20](https://linux-hardware.org/?probe=24f9e4ee20) | Jun 24, 2018 |
| HP            | Pavilion dv7                | [566fa1aed1](https://linux-hardware.org/?probe=566fa1aed1) | Feb 24, 2018 |
| HP            | ProBook 650 G1              | [b0a5c81710](https://linux-hardware.org/?probe=b0a5c81710) | Jan 24, 2018 |
| HP            | 250 G5 Notebook PC          | [c939de9629](https://linux-hardware.org/?probe=c939de9629) | Dec 17, 2017 |
| Toshiba       | Satellite C50-A-1G3         | [4d2b35494b](https://linux-hardware.org/?probe=4d2b35494b) | Dec 16, 2017 |
| HP            | 15                          | [93985df093](https://linux-hardware.org/?probe=93985df093) | Sep 26, 2017 |
| Dell          | Inspiron 7520               | [3b5516e47b](https://linux-hardware.org/?probe=3b5516e47b) | Aug 27, 2017 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [5ab0f522c2](https://linux-hardware.org/?probe=5ab0f522c2) | Aug 19, 2017 |
| Lenovo        | G560 20042                  | [6f5d9b39bb](https://linux-hardware.org/?probe=6f5d9b39bb) | May 09, 2017 |
| ASUSTek       | K55VD                       | [5fecb30529](https://linux-hardware.org/?probe=5fecb30529) | Jan 08, 2017 |
| ASUSTek       | K55VD                       | [f9af076683](https://linux-hardware.org/?probe=f9af076683) | Jan 07, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Serbia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 46        | 8.8%    |
| Ubuntu 22.04                 | 33        | 6.31%   |
| Ubuntu 18.04                 | 33        | 6.31%   |
| Pop!_OS 22.04                | 16        | 3.06%   |
| OpenMandriva 4.3             | 11        | 2.1%    |
| Zorin 15                     | 9         | 1.72%   |
| BlackPanther 18.1            | 9         | 1.72%   |
| ROSA R11                     | 8         | 1.53%   |
| Arch                         | 8         | 1.53%   |
| Zorin 16                     | 7         | 1.34%   |
| Ubuntu 19.10                 | 7         | 1.34%   |
| openSUSE Tumbleweed-XXXXXXXX | 7         | 1.34%   |
| OpenMandriva 23.01           | 7         | 1.34%   |
| Linux Mint 19.3              | 7         | 1.34%   |
| Fedora 39                    | 7         | 1.34%   |
| Arch Rolling                 | 7         | 1.34%   |
| OpenMandriva 4.2             | 6         | 1.15%   |
| Linux Mint 20.3              | 6         | 1.15%   |
| Kubuntu 22.04                | 6         | 1.15%   |
| Fedora 37                    | 6         | 1.15%   |
| ArcoLinux Rolling            | 6         | 1.15%   |
| Ubuntu 21.10                 | 5         | 0.96%   |
| Ubuntu 18.10                 | 5         | 0.96%   |
| ROSA R10                     | 5         | 0.96%   |
| Linux Mint 21.2              | 5         | 0.96%   |
| KDE neon 20.04               | 5         | 0.96%   |
| Xubuntu 20.04                | 4         | 0.76%   |
| Ubuntu 23.10                 | 4         | 0.76%   |
| Ubuntu 23.04                 | 4         | 0.76%   |
| ROSA R11.1                   | 4         | 0.76%   |
| Pop!_OS 21.04                | 4         | 0.76%   |
| MX 21                        | 4         | 0.76%   |
| Manjaro                      | 4         | 0.76%   |
| Linux Mint 21.1              | 4         | 0.76%   |
| Fedora 38                    | 4         | 0.76%   |
| Fedora 34                    | 4         | 0.76%   |
| EndeavourOS Rolling          | 4         | 0.76%   |
| Debian 12                    | 4         | 0.76%   |
| Ubuntu 21.04                 | 3         | 0.57%   |
| Ubuntu 19.04                 | 3         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 146       | 30.17%  |
| OpenMandriva  | 34        | 7.02%   |
| Linux Mint    | 32        | 6.61%   |
| Fedora        | 32        | 6.61%   |
| Endless       | 31        | 6.4%    |
| Pop!_OS       | 24        | 4.96%   |
| ROSA          | 22        | 4.55%   |
| Zorin         | 18        | 3.72%   |
| Manjaro       | 17        | 3.51%   |
| Arch          | 15        | 3.1%    |
| openSUSE      | 11        | 2.27%   |
| Kubuntu       | 11        | 2.27%   |
| KDE neon      | 10        | 2.07%   |
| BlackPanther  | 10        | 2.07%   |
| Xubuntu       | 8         | 1.65%   |
| Debian        | 7         | 1.45%   |
| MX            | 6         | 1.24%   |
| Kali          | 6         | 1.24%   |
| ArcoLinux     | 6         | 1.24%   |
| Ubuntu MATE   | 4         | 0.83%   |
| Lubuntu       | 4         | 0.83%   |
| EndeavourOS   | 4         | 0.83%   |
| Elementary    | 3         | 0.62%   |
| Garuda Linux  | 2         | 0.41%   |
| Void Linux    | 1         | 0.21%   |
| UbuntuDDE     | 1         | 0.21%   |
| Ubuntu Unity  | 1         | 0.21%   |
| Ubuntu Budgie | 1         | 0.21%   |
| Slackware     | 1         | 0.21%   |
| PureOS        | 1         | 0.21%   |
| Peppermint    | 1         | 0.21%   |
| Nobara        | 1         | 0.21%   |
| NixOS         | 1         | 0.21%   |
| LMDE          | 1         | 0.21%   |
| Linux Lite    | 1         | 0.21%   |
| LFS           | 1         | 0.21%   |
| GNOME OS      | 1         | 0.21%   |
| Gentoo        | 1         | 0.21%   |
| Generic       | 1         | 0.21%   |
| Devuan        | 1         | 0.21%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Notebooks | Percent |
|------------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003            | 11        | 1.95%   |
| 6.1.1-desktop-1omv2290             | 7         | 1.24%   |
| 5.8.0-14-generic                   | 7         | 1.24%   |
| 4.18.16-desktop-1bP                | 7         | 1.24%   |
| 5.3.0-40-generic                   | 6         | 1.07%   |
| 5.15.0-48-generic                  | 6         | 1.07%   |
| 5.10.14-desktop-1omv4002           | 6         | 1.07%   |
| 4.18.0-15-generic                  | 6         | 1.07%   |
| 5.15.0-56-generic                  | 5         | 0.89%   |
| 5.15.0-46-generic                  | 5         | 0.89%   |
| 5.11.0-27-generic                  | 5         | 0.89%   |
| 6.4.6-76060406-generic             | 4         | 0.71%   |
| 6.4.11-desktop-1omv2390            | 4         | 0.71%   |
| 6.2.0-26-generic                   | 4         | 0.71%   |
| 5.4.0-47-generic                   | 4         | 0.71%   |
| 5.4.0-42-generic                   | 4         | 0.71%   |
| 5.3.0-23-generic                   | 4         | 0.71%   |
| 5.15.0-52-generic                  | 4         | 0.71%   |
| 4.18.0-25-generic                  | 4         | 0.71%   |
| 4.18.0-12-generic                  | 4         | 0.71%   |
| 4.15.0-15-generic                  | 4         | 0.71%   |
| 6.5.0-27-generic                   | 3         | 0.53%   |
| 6.5.0-21-generic                   | 3         | 0.53%   |
| 6.1.0-18-amd64                     | 3         | 0.53%   |
| 5.4.0-58-generic                   | 3         | 0.53%   |
| 5.4.0-52-generic                   | 3         | 0.53%   |
| 5.4.0-48-generic                   | 3         | 0.53%   |
| 5.4.0-19-generic                   | 3         | 0.53%   |
| 5.4.0-150-generic                  | 3         | 0.53%   |
| 5.3.0-51-generic                   | 3         | 0.53%   |
| 5.3.0-29-generic                   | 3         | 0.53%   |
| 5.3.0-28-generic                   | 3         | 0.53%   |
| 5.15.0-78-generic                  | 3         | 0.53%   |
| 5.15.0-76-generic                  | 3         | 0.53%   |
| 5.15.0-58-generic                  | 3         | 0.53%   |
| 5.15.0-40-generic                  | 3         | 0.53%   |
| 5.13.0-30-generic                  | 3         | 0.53%   |
| 5.11.0-35-generic                  | 3         | 0.53%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3         | 0.53%   |
| 5.0.0-31-generic                   | 3         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 59        | 11.09%  |
| 5.15.0  | 48        | 9.02%   |
| 4.15.0  | 29        | 5.45%   |
| 5.3.0   | 27        | 5.08%   |
| 5.11.0  | 22        | 4.14%   |
| 4.18.0  | 22        | 4.14%   |
| 5.8.0   | 21        | 3.95%   |
| 5.13.0  | 17        | 3.2%    |
| 5.0.0   | 17        | 3.2%    |
| 6.5.0   | 14        | 2.63%   |
| 5.19.0  | 14        | 2.63%   |
| 5.16.7  | 11        | 2.07%   |
| 5.10.0  | 9         | 1.69%   |
| 6.1.1   | 8         | 1.5%    |
| 6.2.0   | 7         | 1.32%   |
| 6.1.0   | 7         | 1.32%   |
| 4.18.16 | 7         | 1.32%   |
| 5.10.14 | 6         | 1.13%   |
| 6.4.6   | 5         | 0.94%   |
| 6.4.11  | 5         | 0.94%   |
| 6.2.6   | 4         | 0.75%   |
| 4.9.20  | 4         | 0.75%   |
| 5.8.11  | 3         | 0.56%   |
| 5.14.21 | 3         | 0.56%   |
| 5.10.74 | 3         | 0.56%   |
| 6.7.9   | 2         | 0.38%   |
| 6.7.0   | 2         | 0.38%   |
| 6.6.13  | 2         | 0.38%   |
| 6.5.7   | 2         | 0.38%   |
| 6.5.11  | 2         | 0.38%   |
| 6.4.12  | 2         | 0.38%   |
| 6.2.9   | 2         | 0.38%   |
| 6.1.9   | 2         | 0.38%   |
| 6.1.8   | 2         | 0.38%   |
| 6.1.7   | 2         | 0.38%   |
| 6.0.12  | 2         | 0.38%   |
| 6.0.10  | 2         | 0.38%   |
| 5.6.14  | 2         | 0.38%   |
| 5.19.7  | 2         | 0.38%   |
| 5.18.10 | 2         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 68        | 12.95%  |
| 5.15    | 58        | 11.05%  |
| 4.18    | 29        | 5.52%   |
| 4.15    | 29        | 5.52%   |
| 5.3     | 28        | 5.33%   |
| 5.11    | 28        | 5.33%   |
| 6.1     | 26        | 4.95%   |
| 5.8     | 25        | 4.76%   |
| 5.10    | 23        | 4.38%   |
| 6.5     | 22        | 4.19%   |
| 5.19    | 20        | 3.81%   |
| 5.13    | 19        | 3.62%   |
| 5.0     | 19        | 3.62%   |
| 6.4     | 15        | 2.86%   |
| 5.16    | 15        | 2.86%   |
| 6.2     | 14        | 2.67%   |
| 6.6     | 11        | 2.1%    |
| 4.9     | 11        | 2.1%    |
| 6.0     | 10        | 1.9%    |
| 6.8     | 6         | 1.14%   |
| 6.7     | 5         | 0.95%   |
| 6.3     | 5         | 0.95%   |
| 5.18    | 5         | 0.95%   |
| 5.12    | 5         | 0.95%   |
| 5.6     | 4         | 0.76%   |
| 5.17    | 4         | 0.76%   |
| 5.14    | 4         | 0.76%   |
| 5.9     | 2         | 0.38%   |
| 5.7     | 2         | 0.38%   |
| 5.1     | 2         | 0.38%   |
| 4.19    | 2         | 0.38%   |
| 4.13    | 2         | 0.38%   |
| 4.1     | 2         | 0.38%   |
| 5.5     | 1         | 0.19%   |
| 4.4     | 1         | 0.19%   |
| 4.17    | 1         | 0.19%   |
| 4.12    | 1         | 0.19%   |
| 4.10    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 451       | 96.99%  |
| i686   | 14        | 3.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 205       | 41.84%  |
| KDE5            | 97        | 19.8%   |
| Unknown         | 59        | 12.04%  |
| XFCE            | 41        | 8.37%   |
| X-Cinnamon      | 27        | 5.51%   |
| KDE4            | 12        | 2.45%   |
| MATE            | 7         | 1.43%   |
| KDE             | 6         | 1.22%   |
| i3              | 6         | 1.22%   |
| Cinnamon        | 6         | 1.22%   |
| LXQt            | 5         | 1.02%   |
| Pantheon        | 3         | 0.61%   |
| qtile           | 2         | 0.41%   |
| LXDE            | 2         | 0.41%   |
| KDE6            | 2         | 0.41%   |
| GNOME Flashback | 2         | 0.41%   |
| Deepin          | 2         | 0.41%   |
| Unity           | 1         | 0.2%    |
| Hyprland        | 1         | 0.2%    |
| DWM             | 1         | 0.2%    |
| BunsenLabs      | 1         | 0.2%    |
| Budgie          | 1         | 0.2%    |
| awesome         | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 356       | 73.1%   |
| Wayland | 91        | 18.69%  |
| Unknown | 34        | 6.98%   |
| Tty     | 6         | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 220       | 45.55%  |
| SDDM    | 85        | 17.6%   |
| GDM3    | 62        | 12.84%  |
| LightDM | 47        | 9.73%   |
| GDM     | 45        | 9.32%   |
| KDM     | 12        | 2.48%   |
| TDM     | 9         | 1.86%   |
| XDM     | 1         | 0.21%   |
| Ly      | 1         | 0.21%   |
| LXDM    | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 335       | 68.51%  |
| Unknown     | 77        | 15.75%  |
| sr_RS       | 22        | 4.5%    |
| en_GB       | 16        | 3.27%   |
| sr_RS@latin | 14        | 2.86%   |
| C           | 9         | 1.84%   |
| ru_RU       | 4         | 0.82%   |
| de_DE       | 4         | 0.82%   |
| hu_HU       | 3         | 0.61%   |
| nl_NL       | 1         | 0.2%    |
| hr_HR       | 1         | 0.2%    |
| en_IE       | 1         | 0.2%    |
| en_DK       | 1         | 0.2%    |
| en_AU       | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 262       | 54.93%  |
| BIOS | 215       | 45.07%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 347       | 72.14%  |
| Overlay | 44        | 9.15%   |
| Btrfs   | 41        | 8.52%   |
| Unknown | 26        | 5.41%   |
| Tmpfs   | 19        | 3.95%   |
| Zfs     | 2         | 0.42%   |
| Xfs     | 2         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 225       | 46.68%  |
| GPT     | 185       | 38.38%  |
| MBR     | 72        | 14.94%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 412       | 87.47%  |
| Yes       | 59        | 12.53%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 351       | 74.21%  |
| Yes       | 122       | 25.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 127       | 27.43%  |
| Hewlett-Packard     | 86        | 18.57%  |
| ASUSTek Computer    | 71        | 15.33%  |
| Dell                | 62        | 13.39%  |
| Acer                | 45        | 9.72%   |
| Toshiba             | 14        | 3.02%   |
| Apple               | 9         | 1.94%   |
| MSI                 | 7         | 1.51%   |
| Fujitsu Siemens     | 6         | 1.3%    |
| Sony                | 4         | 0.86%   |
| HUAWEI              | 4         | 0.86%   |
| Timi                | 3         | 0.65%   |
| Samsung Electronics | 3         | 0.65%   |
| Fujitsu             | 3         | 0.65%   |
| Medion              | 2         | 0.43%   |
| LG Electronics      | 2         | 0.43%   |
| eMachines           | 2         | 0.43%   |
| TWC                 | 1         | 0.22%   |
| Synology            | 1         | 0.22%   |
| SLIMBOOK            | 1         | 0.22%   |
| Razer               | 1         | 0.22%   |
| Purism              | 1         | 0.22%   |
| Packard Bell        | 1         | 0.22%   |
| IBM                 | 1         | 0.22%   |
| HONOR               | 1         | 0.22%   |
| Gigabyte Technology | 1         | 0.22%   |
| Framework           | 1         | 0.22%   |
| Dixonsxp            | 1         | 0.22%   |
| BenQ                | 1         | 0.22%   |
| Alienware           | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Acer Aspire A315-31            | 7         | 1.51%   |
| HP Notebook                    | 5         | 1.08%   |
| Lenovo V330-15IKB 81AX         | 4         | 0.86%   |
| Lenovo IdeaPad 5 14ARE05 81YM  | 3         | 0.65%   |
| Lenovo IdeaPad 5 14ALC05 82LM  | 3         | 0.65%   |
| Lenovo IdeaPad 330-15IKB 81DE  | 3         | 0.65%   |
| Lenovo IdeaPad 3 15IIL05 81WE  | 3         | 0.65%   |
| Lenovo IdeaPad 110-15IBR 80T7  | 3         | 0.65%   |
| Lenovo B50-45 20388            | 3         | 0.65%   |
| HP Laptop 15-db0xxx            | 3         | 0.65%   |
| HP Laptop 15-da0xxx            | 3         | 0.65%   |
| HP EliteBook 840 G5            | 3         | 0.65%   |
| HP 250 G5 Notebook PC          | 3         | 0.65%   |
| Dell Vostro 15 3515            | 3         | 0.65%   |
| Dell Inspiron 3593             | 3         | 0.65%   |
| Dell Inspiron 3542             | 3         | 0.65%   |
| ASUS X541NA                    | 3         | 0.65%   |
| Unknown                        | 3         | 0.65%   |
| MSI CR500                      | 2         | 0.43%   |
| Lenovo Legion Y530-15ICH 81FV  | 2         | 0.43%   |
| Lenovo Legion 5 15ARH05H 82B1  | 2         | 0.43%   |
| Lenovo IdeaPad S540-14API 81NH | 2         | 0.43%   |
| Lenovo IdeaPad L340-15API 81LW | 2         | 0.43%   |
| Lenovo G500 20236              | 2         | 0.43%   |
| HP ProBook 470 G1              | 2         | 0.43%   |
| HP Pavilion Notebook           | 2         | 0.43%   |
| HP Pavilion dv7                | 2         | 0.43%   |
| HP Laptop 15-ra0xx             | 2         | 0.43%   |
| HP Laptop 15-db1xxx            | 2         | 0.43%   |
| HP G62                         | 2         | 0.43%   |
| HP EliteBook 840 G3            | 2         | 0.43%   |
| Fujitsu Siemens AMILO Li3710   | 2         | 0.43%   |
| Dell Vostro 3500               | 2         | 0.43%   |
| Dell Latitude E5470            | 2         | 0.43%   |
| Dell Latitude 7490             | 2         | 0.43%   |
| Dell Inspiron 3558             | 2         | 0.43%   |
| Dell Inspiron 3537             | 2         | 0.43%   |
| Dell Inspiron 3521             | 2         | 0.43%   |
| ASUS X55A                      | 2         | 0.43%   |
| ASUS X541NC                    | 2         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 47        | 10.15%  |
| Lenovo IdeaPad        | 42        | 9.07%   |
| Acer Aspire           | 38        | 8.21%   |
| Dell Inspiron         | 29        | 6.26%   |
| ASUS VivoBook         | 25        | 5.4%    |
| HP Laptop             | 17        | 3.67%   |
| HP EliteBook          | 17        | 3.67%   |
| Dell Latitude         | 16        | 3.46%   |
| HP ProBook            | 13        | 2.81%   |
| Toshiba Satellite     | 12        | 2.59%   |
| Lenovo Legion         | 9         | 1.94%   |
| HP Pavilion           | 9         | 1.94%   |
| Dell Vostro           | 8         | 1.73%   |
| HP 250                | 7         | 1.51%   |
| Lenovo ThinkBook      | 5         | 1.08%   |
| HP Notebook           | 5         | 1.08%   |
| Fujitsu Siemens AMILO | 5         | 1.08%   |
| Dell Precision        | 5         | 1.08%   |
| Lenovo V330-15IKB     | 4         | 0.86%   |
| ASUS ROG              | 4         | 0.86%   |
| Lenovo B50-45         | 3         | 0.65%   |
| HP OMEN               | 3         | 0.65%   |
| HP Compaq             | 3         | 0.65%   |
| Fujitsu LIFEBOOK      | 3         | 0.65%   |
| ASUS ZenBook          | 3         | 0.65%   |
| ASUS X541NA           | 3         | 0.65%   |
| Apple MacBookPro8     | 3         | 0.65%   |
| Acer Nitro            | 3         | 0.65%   |
| Unknown               | 3         | 0.65%   |
| MSI CR500             | 2         | 0.43%   |
| Lenovo G500           | 2         | 0.43%   |
| HP G62                | 2         | 0.43%   |
| HP 255                | 2         | 0.43%   |
| Dell XPS              | 2         | 0.43%   |
| ASUS X55A             | 2         | 0.43%   |
| ASUS X541NC           | 2         | 0.43%   |
| ASUS TUF              | 2         | 0.43%   |
| ASUS K54C             | 2         | 0.43%   |
| Apple MacBookPro5     | 2         | 0.43%   |
| Toshiba TECRA         | 1         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 47        | 10.15%  |
| 2020 | 43        | 9.29%   |
| 2019 | 37        | 7.99%   |
| 2011 | 35        | 7.56%   |
| 2017 | 32        | 6.91%   |
| 2013 | 31        | 6.7%    |
| 2016 | 30        | 6.48%   |
| 2012 | 30        | 6.48%   |
| 2021 | 27        | 5.83%   |
| 2014 | 24        | 5.18%   |
| 2010 | 24        | 5.18%   |
| 2022 | 22        | 4.75%   |
| 2015 | 22        | 4.75%   |
| 2008 | 16        | 3.46%   |
| 2009 | 13        | 2.81%   |
| 2023 | 10        | 2.16%   |
| 2007 | 10        | 2.16%   |
| 2006 | 6         | 1.3%    |
| 2024 | 2         | 0.43%   |
| 2005 | 2         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 463       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 424       | 90.41%  |
| Enabled  | 45        | 9.59%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 462       | 99.78%  |
| Yes  | 1         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 129       | 27.33%  |
| 4.01-8.0    | 127       | 26.91%  |
| 8.01-16.0   | 84        | 17.8%   |
| 16.01-24.0  | 66        | 13.98%  |
| 32.01-64.0  | 27        | 5.72%   |
| 1.01-2.0    | 21        | 4.45%   |
| 2.01-3.0    | 12        | 2.54%   |
| 24.01-32.0  | 4         | 0.85%   |
| 64.01-256.0 | 1         | 0.21%   |
| 0.51-1.0    | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 175       | 33.85%  |
| 2.01-3.0   | 125       | 24.18%  |
| 3.01-4.0   | 77        | 14.89%  |
| 4.01-8.0   | 63        | 12.19%  |
| 0.51-1.0   | 50        | 9.67%   |
| 8.01-16.0  | 24        | 4.64%   |
| 0.01-0.5   | 2         | 0.39%   |
| 16.01-24.0 | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 366       | 76.89%  |
| 2      | 92        | 19.33%  |
| 3      | 10        | 2.1%    |
| 0      | 8         | 1.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 293       | 62.74%  |
| Yes       | 174       | 37.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 396       | 85.53%  |
| No        | 67        | 14.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 462       | 99.57%  |
| No        | 2         | 0.43%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 386       | 81.95%  |
| No        | 85        | 18.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Serbia  | 463       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Belgrade          | 299       | 60.28%  |
| Novi Sad          | 45        | 9.07%   |
| Niš              | 27        | 5.44%   |
| Zrenjanin         | 7         | 1.41%   |
| Subotica          | 7         | 1.41%   |
| Pančevo          | 5         | 1.01%   |
| Kragujevac        | 5         | 1.01%   |
| Čačak           | 5         | 1.01%   |
| Savski Venac      | 4         | 0.81%   |
| Novi Belgrade     | 4         | 0.81%   |
| Leskovac          | 4         | 0.81%   |
| Senta             | 3         | 0.6%    |
| Novi Karlovci     | 3         | 0.6%    |
| Lozovik           | 3         | 0.6%    |
| Kovin             | 3         | 0.6%    |
| Jagodina          | 3         | 0.6%    |
| Backa Topola      | 3         | 0.6%    |
| Vršac            | 2         | 0.4%    |
| Vranje            | 2         | 0.4%    |
| Varvarin          | 2         | 0.4%    |
| Valjevo           | 2         | 0.4%    |
| Užice            | 2         | 0.4%    |
| Trstenik          | 2         | 0.4%    |
| Stara Pazova      | 2         | 0.4%    |
| Semlin            | 2         | 0.4%    |
| Sabac             | 2         | 0.4%    |
| Požarevac        | 2         | 0.4%    |
| Palanka           | 2         | 0.4%    |
| New Belgrade      | 2         | 0.4%    |
| Mladenovac        | 2         | 0.4%    |
| Lazarevac         | 2         | 0.4%    |
| Doljevac          | 2         | 0.4%    |
| Branicevo         | 2         | 0.4%    |
| Bor               | 2         | 0.4%    |
| Becej             | 2         | 0.4%    |
| UÅ¾ice          | 1         | 0.2%    |
| Stari Grad        | 1         | 0.2%    |
| Stara Moravica    | 1         | 0.2%    |
| Sremska Mitrovica | 1         | 0.2%    |
| Sombor            | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 79        | 97     | 14.44%  |
| WDC                          | 68        | 99     | 12.43%  |
| Seagate                      | 64        | 75     | 11.7%   |
| Toshiba                      | 57        | 72     | 10.42%  |
| Kingston                     | 31        | 35     | 5.67%   |
| SanDisk                      | 30        | 39     | 5.48%   |
| SK hynix                     | 27        | 32     | 4.94%   |
| Hitachi                      | 24        | 27     | 4.39%   |
| Micron Technology            | 21        | 26     | 3.84%   |
| Intel                        | 19        | 30     | 3.47%   |
| Unknown                      | 17        | 23     | 3.11%   |
| HGST                         | 16        | 25     | 2.93%   |
| SPCC                         | 10        | 17     | 1.83%   |
| Patriot                      | 10        | 13     | 1.83%   |
| KIOXIA                       | 7         | 8      | 1.28%   |
| Fujitsu                      | 6         | 6      | 1.1%    |
| GeIL                         | 5         | 6      | 0.91%   |
| A-DATA Technology            | 5         | 5      | 0.91%   |
| Transcend                    | 4         | 4      | 0.73%   |
| LITEON                       | 4         | 5      | 0.73%   |
| Gigabyte Technology          | 4         | 4      | 0.73%   |
| Crucial                      | 4         | 6      | 0.73%   |
| Kingston Technology Company  | 3         | 4      | 0.55%   |
| Unknown                      | 3         | 3      | 0.55%   |
| Union Memory                 | 2         | 2      | 0.37%   |
| Phison                       | 2         | 3      | 0.37%   |
| Netac                        | 2         | 2      | 0.37%   |
| Biostar                      | 2         | 2      | 0.37%   |
| AMD                          | 2         | 2      | 0.37%   |
| ADATA Technology             | 2         | 2      | 0.37%   |
| Verbatim                     | 1         | 1      | 0.18%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.18%   |
| TO Exter                     | 1         | 1      | 0.18%   |
| SSSTC                        | 1         | 1      | 0.18%   |
| Solid State Storage          | 1         | 1      | 0.18%   |
| Silicon Motion               | 1         | 1      | 0.18%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.18%   |
| Realtek Semiconductor        | 1         | 4      | 0.18%   |
| PNY                          | 1         | 1      | 0.18%   |
| PHD 3.0                      | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                     | 18        | 3.25%   |
| Toshiba MQ01ABF050 500GB                           | 15        | 2.71%   |
| Seagate ST500LT012-1DG142 500GB                    | 8         | 1.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 7         | 1.26%   |
| Kingston SA400S37240G 240GB SSD                    | 7         | 1.26%   |
| WDC WDS500G2B0A 500GB SSD                          | 6         | 1.08%   |
| Toshiba MQ01ABD100 1TB                             | 6         | 1.08%   |
| Seagate ST500LT012-9WS142 500GB                    | 6         | 1.08%   |
| Toshiba MQ04ABF100 1TB                             | 5         | 0.9%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 5         | 0.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 5         | 0.9%    |
| Samsung MZALQ512HALU-000L2 512GB                   | 5         | 0.9%    |
| Kingston SA400S37120G 120GB SSD                    | 5         | 0.9%    |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB               | 4         | 0.72%   |
| Kingston SA400S37480G 480GB SSD                    | 4         | 0.72%   |
| Hitachi HTS545050A7E380 500GB                      | 4         | 0.72%   |
| HGST HTS545050A7E680 500GB                         | 4         | 0.72%   |
| HGST HTS545050A7E380 500GB                         | 4         | 0.72%   |
| WDC WD5000LPCX-24VHAT0 500GB                       | 3         | 0.54%   |
| WDC WD3200BEVT-22ZCT0 320GB                        | 3         | 0.54%   |
| Unknown NVMe SSD Drive 512GB                       | 3         | 0.54%   |
| SPCC Solid State Disk 256GB                        | 3         | 0.54%   |
| SPCC Solid State Disk 120GB                        | 3         | 0.54%   |
| SK hynix NVMe SSD Drive 256GB                      | 3         | 0.54%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 3         | 0.54%   |
| SanDisk NVMe SSD Drive 256GB                       | 3         | 0.54%   |
| Samsung SSD 850 EVO 250GB                          | 3         | 0.54%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 0.54%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 3         | 0.54%   |
| Kingston RBUSC180DS37256GJ 256GB SSD               | 3         | 0.54%   |
| Hitachi HTS547575A9E384 752GB                      | 3         | 0.54%   |
| Hitachi HTS545032B9A300 320GB                      | 3         | 0.54%   |
| HGST HTS721010A9E630 1TB                           | 3         | 0.54%   |
| GeIL R3_128GB                                      | 3         | 0.54%   |
| Unknown                                            | 3         | 0.54%   |
| WDC WD5000LPVX-75V0TT0 500GB                       | 2         | 0.36%   |
| WDC WD5000LPCX-80VHAT1 500GB                       | 2         | 0.36%   |
| WDC WD5000LPCX-60VHAT0 500GB                       | 2         | 0.36%   |
| WDC WD3200BEVT-22A23T0 320GB                       | 2         | 0.36%   |
| WDC WD2500BEVS-22UST0 250GB                        | 2         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 63        | 74     | 30.29%  |
| WDC                 | 47        | 74     | 22.6%   |
| Toshiba             | 47        | 58     | 22.6%   |
| Hitachi             | 24        | 27     | 11.54%  |
| HGST                | 16        | 25     | 7.69%   |
| Fujitsu             | 6         | 6      | 2.88%   |
| Unknown             | 1         | 1      | 0.48%   |
| TO Exter            | 1         | 1      | 0.48%   |
| Samsung Electronics | 1         | 2      | 0.48%   |
| JMicron Technology  | 1         | 1      | 0.48%   |
| IBM/Hitachi         | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 33        | 40     | 21.57%  |
| Kingston            | 26        | 29     | 16.99%  |
| SPCC                | 10        | 17     | 6.54%   |
| Patriot             | 10        | 13     | 6.54%   |
| SanDisk             | 9         | 13     | 5.88%   |
| WDC                 | 8         | 10     | 5.23%   |
| Micron Technology   | 6         | 8      | 3.92%   |
| Toshiba             | 5         | 6      | 3.27%   |
| Intel               | 5         | 6      | 3.27%   |
| GeIL                | 5         | 6      | 3.27%   |
| Transcend           | 4         | 4      | 2.61%   |
| LITEON              | 4         | 5      | 2.61%   |
| Crucial             | 4         | 6      | 2.61%   |
| A-DATA Technology   | 4         | 4      | 2.61%   |
| SK hynix            | 3         | 3      | 1.96%   |
| Netac               | 2         | 2      | 1.31%   |
| Gigabyte Technology | 2         | 2      | 1.31%   |
| Biostar             | 2         | 2      | 1.31%   |
| AMD                 | 2         | 2      | 1.31%   |
| Unknown             | 2         | 2      | 1.31%   |
| Verbatim            | 1         | 1      | 0.65%   |
| SSSTC               | 1         | 1      | 0.65%   |
| PNY                 | 1         | 1      | 0.65%   |
| PHD 3.0             | 1         | 1      | 0.65%   |
| LITEONIT            | 1         | 1      | 0.65%   |
| China               | 1         | 1      | 0.65%   |
| Apacer              | 1         | 1      | 0.65%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 206       | 270    | 39.16%  |
| NVMe    | 161       | 217    | 30.61%  |
| SSD     | 144       | 187    | 27.38%  |
| MMC     | 13        | 18     | 2.47%   |
| Unknown | 2         | 2      | 0.38%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 311       | 448    | 63.08%  |
| NVMe | 161       | 217    | 32.66%  |
| MMC  | 13        | 18     | 2.64%   |
| SAS  | 8         | 11     | 1.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 252       | 334    | 74.78%  |
| 0.51-1.0   | 79        | 107    | 23.44%  |
| 1.01-2.0   | 5         | 13     | 1.48%   |
| 4.01-10.0  | 1         | 3      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 145       | 28.88%  |
| 251-500        | 138       | 27.49%  |
| 501-1000       | 59        | 11.75%  |
| 1-20           | 52        | 10.36%  |
| 51-100         | 31        | 6.18%   |
| 21-50          | 21        | 4.18%   |
| Unknown        | 20        | 3.98%   |
| 1001-2000      | 18        | 3.59%   |
| 2001-3000      | 10        | 1.99%   |
| More than 3000 | 8         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 207       | 39.88%  |
| 21-50     | 97        | 18.69%  |
| 101-250   | 74        | 14.26%  |
| 51-100    | 64        | 12.33%  |
| 251-500   | 34        | 6.55%   |
| Unknown   | 20        | 3.85%   |
| 501-1000  | 15        | 2.89%   |
| 1001-2000 | 6         | 1.16%   |
| 2001-3000 | 2         | 0.39%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Notebooks | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                | 5         | 5      | 11.9%   |
| Seagate ST500LT012-9WS142 500GB         | 2         | 2      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB          | 2         | 2      | 4.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 2         | 2      | 4.76%   |
| Hitachi HTS545050A7E380 500GB           | 2         | 2      | 4.76%   |
| HGST HTS725050A7E630 500GB              | 2         | 6      | 4.76%   |
| WDC WD5000BEVT-24A0RT0 500GB            | 1         | 1      | 2.38%   |
| WDC WD3200BEVT-22ZCT0 320GB             | 1         | 1      | 2.38%   |
| WDC WD3200BEKX-75B7WT0 320GB            | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD032 320GB                | 1         | 1      | 2.38%   |
| Toshiba MK5061GSYN 500GB                | 1         | 1      | 2.38%   |
| Toshiba MK1652GSX 160GB                 | 1         | 1      | 2.38%   |
| Toshiba MK1637GSX 160GB                 | 1         | 1      | 2.38%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 1         | 1      | 2.38%   |
| SPCC Solid State DiskB27 32GB           | 1         | 1      | 2.38%   |
| Seagate ST980813AS 80GB                 | 1         | 1      | 2.38%   |
| Seagate ST9500420AS 500GB               | 1         | 1      | 2.38%   |
| Seagate ST9250827AS 250GB               | 1         | 1      | 2.38%   |
| Seagate ST9120822AS 120GB               | 1         | 1      | 2.38%   |
| Seagate ST750LM022 HN-M750MBB 752GB     | 1         | 1      | 2.38%   |
| Seagate ST500LT012-1DG142 500GB         | 1         | 2      | 2.38%   |
| Seagate ST1000LM048-2E7172 1TB          | 1         | 1      | 2.38%   |
| Samsung Electronics HM120JI 120GB       | 1         | 2      | 2.38%   |
| Kingston SA400S37480G 480GB SSD         | 1         | 1      | 2.38%   |
| Hitachi HTS723216L9SA60 160GB           | 1         | 1      | 2.38%   |
| Hitachi HTS722080K9A300 80GB            | 1         | 1      | 2.38%   |
| Hitachi HTS541616J9SA00 160GB           | 1         | 1      | 2.38%   |
| Hitachi HTS541612J9SA00 120GB           | 1         | 1      | 2.38%   |
| HGST HTS721010A9E630 1TB                | 1         | 2      | 2.38%   |
| HGST HTS545050A7E380 500GB              | 1         | 1      | 2.38%   |
| Fujitsu MHZ2160BH G1 160GB              | 1         | 1      | 2.38%   |
| Fujitsu MHW2160BH PL 160GB              | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 30.95%  |
| Toshiba             | 11        | 11     | 26.19%  |
| Hitachi             | 6         | 6      | 14.29%  |
| HGST                | 4         | 9      | 9.52%   |
| WDC                 | 3         | 3      | 7.14%   |
| Fujitsu             | 2         | 2      | 4.76%   |
| SPCC                | 1         | 1      | 2.38%   |
| Samsung Electronics | 1         | 2      | 2.38%   |
| Kingston            | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 13        | 14     | 33.33%  |
| Toshiba             | 10        | 10     | 25.64%  |
| Hitachi             | 6         | 6      | 15.38%  |
| HGST                | 4         | 9      | 10.26%  |
| WDC                 | 3         | 3      | 7.69%   |
| Fujitsu             | 2         | 2      | 5.13%   |
| Samsung Electronics | 1         | 2      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 46     | 92.68%  |
| SSD  | 3         | 3      | 7.32%   |

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
| Detected | 260       | 412    | 53.83%  |
| Works    | 182       | 233    | 37.68%  |
| Malfunc  | 41        | 49     | 8.49%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 321       | 57.53%  |
| AMD                            | 65        | 11.65%  |
| Samsung Electronics            | 50        | 8.96%   |
| SanDisk                        | 33        | 5.91%   |
| SK hynix                       | 24        | 4.3%    |
| Micron Technology              | 15        | 2.69%   |
| Kingston Technology Company    | 8         | 1.43%   |
| KIOXIA                         | 7         | 1.25%   |
| Toshiba America Info Systems   | 6         | 1.08%   |
| Nvidia                         | 6         | 1.08%   |
| Phison Electronics             | 4         | 0.72%   |
| Union Memory (Shenzhen)        | 3         | 0.54%   |
| ADATA Technology               | 3         | 0.54%   |
| Solidigm                       | 2         | 0.36%   |
| JMicron Technology             | 2         | 0.36%   |
| VIA Technologies               | 1         | 0.18%   |
| Solid State Storage Technology | 1         | 0.18%   |
| Silicon Motion                 | 1         | 0.18%   |
| Silicon Image                  | 1         | 0.18%   |
| Shenzhen Longsys Electronics   | 1         | 0.18%   |
| Realtek Semiconductor          | 1         | 0.18%   |
| ASMedia Technology             | 1         | 0.18%   |
| Apple                          | 1         | 0.18%   |
| Unknown                        | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 54        | 9.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 38        | 6.37%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 30        | 5.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 30        | 5.03%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 25        | 4.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 18        | 3.02%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 15        | 2.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 2.35%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 14        | 2.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 2.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 2.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 12        | 2.01%   |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 1.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 11        | 1.84%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 10        | 1.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 10        | 1.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 9         | 1.51%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 9         | 1.51%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 1.34%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 1.34%   |
| SK hynix BC511 NVMe SSD                                                          | 7         | 1.17%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 7         | 1.17%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 7         | 1.17%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 1.17%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 1.17%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 7         | 1.17%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 6         | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.01%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 5         | 0.84%   |
| Nvidia MCP79 AHCI Controller                                                     | 5         | 0.84%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 5         | 0.84%   |
| Intel SSD 660P Series                                                            | 5         | 0.84%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 0.84%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 0.67%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 4         | 0.67%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 4         | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 339       | 58.75%  |
| NVMe | 165       | 28.6%   |
| RAID | 40        | 6.93%   |
| IDE  | 33        | 5.72%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 363       | 78.4%   |
| AMD    | 100       | 21.6%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 1.73%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.51%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 1.3%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.3%    |
| Intel Core i3-6006U CPU @ 2.00GHz             | 6         | 1.3%    |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 1.3%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 6         | 1.3%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 1.3%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 6         | 1.3%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 5         | 1.08%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 1.08%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.08%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 5         | 1.08%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 5         | 1.08%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 1.08%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 4         | 0.86%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 4         | 0.86%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 4         | 0.86%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 4         | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.86%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.86%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 0.86%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 4         | 0.86%   |
| Intel Celeron CPU 1000M @ 1.80GHz             | 4         | 0.86%   |
| Intel Pentium M processor 1.86GHz             | 3         | 0.65%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 3         | 0.65%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 3         | 0.65%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 3         | 0.65%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.65%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz            | 3         | 0.65%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.65%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 0.65%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 3         | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 87        | 18.79%  |
| Intel Core i5           | 83        | 17.93%  |
| Intel Core i3           | 43        | 9.29%   |
| AMD Ryzen 5             | 38        | 8.21%   |
| Intel Celeron           | 34        | 7.34%   |
| Other                   | 33        | 7.13%   |
| Intel Pentium           | 33        | 7.13%   |
| AMD Ryzen 7             | 21        | 4.54%   |
| Intel Core 2 Duo        | 19        | 4.1%    |
| Intel Atom              | 8         | 1.73%   |
| Intel Pentium Silver    | 6         | 1.3%    |
| AMD A8                  | 5         | 1.08%   |
| Intel Core 2            | 4         | 0.86%   |
| AMD Ryzen 3             | 4         | 0.86%   |
| Intel Pentium M         | 3         | 0.65%   |
| Intel Pentium Dual-Core | 3         | 0.65%   |
| Intel Pentium Dual      | 3         | 0.65%   |
| AMD Ryzen 9             | 3         | 0.65%   |
| AMD E2                  | 3         | 0.65%   |
| AMD A4                  | 3         | 0.65%   |
| Intel Genuine           | 2         | 0.43%   |
| AMD Ryzen 5 PRO         | 2         | 0.43%   |
| AMD Phenom II           | 2         | 0.43%   |
| AMD E1                  | 2         | 0.43%   |
| AMD Athlon X2           | 2         | 0.43%   |
| AMD Athlon II Dual-Core | 2         | 0.43%   |
| AMD Athlon II           | 2         | 0.43%   |
| AMD A6                  | 2         | 0.43%   |
| Intel Pentium Gold      | 1         | 0.22%   |
| Intel Core M            | 1         | 0.22%   |
| Intel Core Duo          | 1         | 0.22%   |
| Intel Celeron M         | 1         | 0.22%   |
| AMD V120                | 1         | 0.22%   |
| AMD Turion 64 X2 Mobile | 1         | 0.22%   |
| AMD Ryzen Embedded      | 1         | 0.22%   |
| AMD Ryzen 7 PRO         | 1         | 0.22%   |
| AMD Ryzen 3 PRO         | 1         | 0.22%   |
| AMD Athlon II Neo       | 1         | 0.22%   |
| AMD Athlon 64 X2        | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 222       | 47.95%  |
| 4      | 156       | 33.69%  |
| 6      | 36        | 7.78%   |
| 8      | 21        | 4.54%   |
| 1      | 15        | 3.24%   |
| 14     | 7         | 1.51%   |
| 10     | 3         | 0.65%   |
| 24     | 1         | 0.22%   |
| 16     | 1         | 0.22%   |
| 12     | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 463       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 317       | 68.47%  |
| 1      | 146       | 31.53%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 444       | 95.69%  |
| Unknown        | 11        | 2.37%   |
| 32-bit         | 9         | 1.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 126       | 26.03%  |
| 0x206a7    | 34        | 7.02%   |
| 0x406e3    | 20        | 4.13%   |
| 0x306a9    | 20        | 4.13%   |
| 0x806ea    | 17        | 3.51%   |
| 0x506c9    | 12        | 2.48%   |
| 0x40651    | 11        | 2.27%   |
| 0x906ea    | 10        | 2.07%   |
| 0x806e9    | 10        | 2.07%   |
| 0x706e5    | 10        | 2.07%   |
| 0x1067a    | 10        | 2.07%   |
| 0x306d4    | 9         | 1.86%   |
| 0x806ec    | 8         | 1.65%   |
| 0x806c1    | 8         | 1.65%   |
| 0x306c3    | 8         | 1.65%   |
| 0x6fd      | 7         | 1.45%   |
| 0x0a50000c | 7         | 1.45%   |
| 0x08600106 | 7         | 1.45%   |
| 0x08108109 | 7         | 1.45%   |
| 0x08108102 | 7         | 1.45%   |
| 0x906e9    | 6         | 1.24%   |
| 0x806eb    | 6         | 1.24%   |
| 0x506e3    | 6         | 1.24%   |
| 0x406c4    | 6         | 1.24%   |
| 0x30678    | 6         | 1.24%   |
| 0x20655    | 6         | 1.24%   |
| 0xa0652    | 5         | 1.03%   |
| 0x706a8    | 5         | 1.03%   |
| 0x20652    | 5         | 1.03%   |
| 0x10676    | 5         | 1.03%   |
| 0x08608103 | 5         | 1.03%   |
| 0x706a1    | 4         | 0.83%   |
| 0x0a50000d | 4         | 0.83%   |
| 0x08600104 | 4         | 0.83%   |
| 0x010000c8 | 4         | 0.83%   |
| 0x6d8      | 3         | 0.62%   |
| 0x406c3    | 3         | 0.62%   |
| 0x30673    | 3         | 0.62%   |
| 0x106ca    | 3         | 0.62%   |
| 0x0810100b | 3         | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 67        | 14.47%  |
| SandyBridge      | 40        | 8.64%   |
| Haswell          | 30        | 6.48%   |
| Skylake          | 28        | 6.05%   |
| IvyBridge        | 24        | 5.18%   |
| Silvermont       | 21        | 4.54%   |
| Zen+             | 19        | 4.1%    |
| Unknown          | 18        | 3.89%   |
| Westmere         | 17        | 3.67%   |
| Zen 3            | 16        | 3.46%   |
| TigerLake        | 16        | 3.46%   |
| Core             | 16        | 3.46%   |
| Penryn           | 15        | 3.24%   |
| Broadwell        | 15        | 3.24%   |
| Zen 2            | 14        | 3.02%   |
| IceLake          | 14        | 3.02%   |
| Goldmont         | 14        | 3.02%   |
| Alderlake Hybrid | 12        | 2.59%   |
| Goldmont plus    | 10        | 2.16%   |
| Zen              | 9         | 1.94%   |
| K10              | 8         | 1.73%   |
| P6               | 7         | 1.51%   |
| CometLake        | 6         | 1.3%    |
| Bonnell          | 6         | 1.3%    |
| Puma             | 5         | 1.08%   |
| Excavator        | 4         | 0.86%   |
| Piledriver       | 3         | 0.65%   |
| K8 Hammer        | 2         | 0.43%   |
| K8 & K10 hybrid  | 2         | 0.43%   |
| Jaguar           | 2         | 0.43%   |
| Bobcat           | 2         | 0.43%   |
| Nehalem          | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 330       | 55.65%  |
| AMD              | 138       | 23.27%  |
| Nvidia           | 124       | 20.91%  |
| VIA Technologies | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 36        | 5.83%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 3.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 3.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 3.07%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 16        | 2.59%   |
| Intel UHD Graphics 620                                                                   | 15        | 2.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 14        | 2.27%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 2.27%   |
| Intel HD Graphics 620                                                                    | 13        | 2.1%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 13        | 2.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 1.94%   |
| Intel HD Graphics 5500                                                                   | 12        | 1.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 1.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 1.78%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 10        | 1.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 9         | 1.46%   |
| Intel HD Graphics 500                                                                    | 9         | 1.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.46%   |
| AMD Lucienne                                                                             | 9         | 1.46%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 1.29%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 8         | 1.29%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 8         | 1.29%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 8         | 1.29%   |
| AMD Barcelo                                                                              | 8         | 1.29%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 6         | 0.97%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 6         | 0.97%   |
| Intel HD Graphics 530                                                                    | 6         | 0.97%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 6         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.81%   |
| Intel HD Graphics 630                                                                    | 5         | 0.81%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.81%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.81%   |
| Intel Apollo Lake [HD Graphics 505]                                                      | 5         | 0.81%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.65%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 213       | 45.71%  |
| Intel + Nvidia | 89        | 19.1%   |
| 1 x AMD        | 84        | 18.03%  |
| Intel + AMD    | 30        | 6.44%   |
| 1 x Nvidia     | 21        | 4.51%   |
| 2 x AMD        | 12        | 2.58%   |
| AMD + Nvidia   | 12        | 2.58%   |
| 2 x Nvidia     | 2         | 0.43%   |
| Other          | 1         | 0.21%   |
| 2 x Intel      | 1         | 0.21%   |
| 1 x VIA        | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 399       | 85.07%  |
| Proprietary | 57        | 12.15%  |
| Unknown     | 13        | 2.77%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 286       | 59.71%  |
| 0.01-0.5   | 68        | 14.2%   |
| 1.01-2.0   | 67        | 13.99%  |
| 3.01-4.0   | 30        | 6.26%   |
| 0.51-1.0   | 24        | 5.01%   |
| 7.01-8.0   | 2         | 0.42%   |
| 5.01-6.0   | 1         | 0.21%   |
| 8.01-16.0  | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 102       | 19.35%  |
| BOE                     | 81        | 15.37%  |
| LG Display              | 75        | 14.23%  |
| Chimei Innolux          | 74        | 14.04%  |
| Samsung Electronics     | 52        | 9.87%   |
| Lenovo                  | 16        | 3.04%   |
| Dell                    | 16        | 3.04%   |
| Chi Mei Optoelectronics | 15        | 2.85%   |
| PANDA                   | 11        | 2.09%   |
| Apple                   | 9         | 1.71%   |
| Sharp                   | 8         | 1.52%   |
| Goldstar                | 7         | 1.33%   |
| Philips                 | 6         | 1.14%   |
| LG Philips              | 6         | 1.14%   |
| Hewlett-Packard         | 5         | 0.95%   |
| Sony                    | 4         | 0.76%   |
| CPT                     | 4         | 0.76%   |
| BenQ                    | 4         | 0.76%   |
| Toshiba                 | 3         | 0.57%   |
| InfoVision              | 3         | 0.57%   |
| CSO                     | 3         | 0.57%   |
| ASUSTek Computer        | 3         | 0.57%   |
| AOC                     | 3         | 0.57%   |
| Unknown                 | 2         | 0.38%   |
| CHD                     | 2         | 0.38%   |
| Ancor Communications    | 2         | 0.38%   |
| ViewSonic               | 1         | 0.19%   |
| TSL                     | 1         | 0.19%   |
| TMX                     | 1         | 0.19%   |
| SKY                     | 1         | 0.19%   |
| Seiko/Epson             | 1         | 0.19%   |
| LPL                     | 1         | 0.19%   |
| InnoLux Display         | 1         | 0.19%   |
| Iiyama                  | 1         | 0.19%   |
| Hitachi                 | 1         | 0.19%   |
| HannStar                | 1         | 0.19%   |
| Gigabyte Technology     | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 17        | 3.2%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 1.88%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 9         | 1.69%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 7         | 1.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 5         | 0.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.94%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 5         | 0.94%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.94%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 4         | 0.75%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.75%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                 | 4         | 0.75%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 4         | 0.75%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 4         | 0.75%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 4         | 0.75%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch  | 3         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.56%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch         | 3         | 0.56%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.56%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 3         | 0.56%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch           | 3         | 0.56%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch               | 3         | 0.56%   |
| Dell P2417H DELA0DC 1920x1080 527x296mm 23.8-inch                     | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15BF 1366x768 344x194mm 15.5-inch       | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch       | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch      | 3         | 0.56%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE07A3 1920x1080 344x193mm 15.5-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch         | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch         | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 3         | 0.56%   |
| AOC Q32G2WG3 AOC3202 2560x1440 697x392mm 31.5-inch                    | 3         | 0.56%   |
| Sony Nvidia Defaul t Flat Panel SNY06FA 1600x900 360x200mm 16.2-inch  | 2         | 0.38%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch               | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch  | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 225       | 45.64%  |
| 1366x768 (WXGA)    | 156       | 31.64%  |
| 1280x800 (WXGA)    | 19        | 3.85%   |
| 1600x900 (HD+)     | 14        | 2.84%   |
| 3840x2160 (4K)     | 11        | 2.23%   |
| 1920x1200 (WUXGA)  | 10        | 2.03%   |
| 2560x1600          | 9         | 1.83%   |
| 2560x1440 (QHD)    | 9         | 1.83%   |
| 1440x900 (WXGA+)   | 7         | 1.42%   |
| 2880x1800          | 5         | 1.01%   |
| 1680x1050 (WSXGA+) | 4         | 0.81%   |
| 1360x768           | 4         | 0.81%   |
| 1024x600           | 4         | 0.81%   |
| 2520x1680          | 3         | 0.61%   |
| 1280x1024 (SXGA)   | 2         | 0.41%   |
| 1024x768 (XGA)     | 2         | 0.41%   |
| Unknown            | 2         | 0.41%   |
| 3360x1200          | 1         | 0.2%    |
| 3280x1080          | 1         | 0.2%    |
| 2160x1350          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1680x945           | 1         | 0.2%    |
| 1400x1050          | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 274       | 52.09%  |
| 13      | 51        | 9.7%    |
| 14      | 42        | 7.98%   |
| 17      | 29        | 5.51%   |
| 24      | 25        | 4.75%   |
| 23      | 15        | 2.85%   |
| 12      | 15        | 2.85%   |
| 16      | 14        | 2.66%   |
| 31      | 9         | 1.71%   |
| 21      | 9         | 1.71%   |
| Unknown | 8         | 1.52%   |
| 27      | 7         | 1.33%   |
| 11      | 5         | 0.95%   |
| 72      | 3         | 0.57%   |
| 18      | 3         | 0.57%   |
| 10      | 3         | 0.57%   |
| 40      | 2         | 0.38%   |
| 22      | 2         | 0.38%   |
| 19      | 2         | 0.38%   |
| 86      | 1         | 0.19%   |
| 84      | 1         | 0.19%   |
| 54      | 1         | 0.19%   |
| 46      | 1         | 0.19%   |
| 43      | 1         | 0.19%   |
| 32      | 1         | 0.19%   |
| 20      | 1         | 0.19%   |
| 8       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 355       | 67.88%  |
| 501-600     | 45        | 8.6%    |
| 201-300     | 43        | 8.22%   |
| 351-400     | 35        | 6.69%   |
| 401-500     | 16        | 3.06%   |
| 601-700     | 9         | 1.72%   |
| Unknown     | 8         | 1.53%   |
| 1501-2000   | 4         | 0.76%   |
| 1001-1500   | 3         | 0.57%   |
| 801-900     | 2         | 0.38%   |
| 701-800     | 1         | 0.19%   |
| 101-200     | 1         | 0.19%   |
| 901-1000    | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 394       | 85.65%  |
| 16/10   | 48        | 10.43%  |
| 3/2     | 8         | 1.74%   |
| Unknown | 4         | 0.87%   |
| 4/3     | 3         | 0.65%   |
| 5/4     | 2         | 0.43%   |
| 0.56    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 273       | 52%     |
| 81-90          | 75        | 14.29%  |
| 201-250        | 43        | 8.19%   |
| 121-130        | 29        | 5.52%   |
| 71-80          | 17        | 3.24%   |
| 61-70          | 14        | 2.67%   |
| 111-120        | 13        | 2.48%   |
| 351-500        | 10        | 1.9%    |
| Unknown        | 8         | 1.52%   |
| 301-350        | 7         | 1.33%   |
| 251-300        | 7         | 1.33%   |
| More than 1000 | 6         | 1.14%   |
| 51-60          | 5         | 0.95%   |
| 501-1000       | 4         | 0.76%   |
| 41-50          | 3         | 0.57%   |
| 151-200        | 3         | 0.57%   |
| 141-150        | 3         | 0.57%   |
| 91-100         | 3         | 0.57%   |
| 1-40           | 1         | 0.19%   |
| 131-140        | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 220       | 42.88%  |
| 101-120       | 165       | 32.16%  |
| 51-100        | 77        | 15.01%  |
| 161-240       | 30        | 5.85%   |
| Unknown       | 8         | 1.56%   |
| More than 240 | 7         | 1.36%   |
| 1-50          | 6         | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 382       | 79.75%  |
| 2     | 73        | 15.24%  |
| 0     | 13        | 2.71%   |
| 3     | 11        | 2.3%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 266       | 34.91%  |
| Intel                             | 213       | 27.95%  |
| Qualcomm Atheros                  | 127       | 16.67%  |
| Broadcom                          | 56        | 7.35%   |
| MediaTek                          | 18        | 2.36%   |
| Broadcom Limited                  | 11        | 1.44%   |
| Ralink                            | 10        | 1.31%   |
| Dell                              | 7         | 0.92%   |
| Nvidia                            | 6         | 0.79%   |
| Marvell Technology Group          | 6         | 0.79%   |
| Ralink Technology                 | 5         | 0.66%   |
| TP-Link                           | 4         | 0.52%   |
| Sierra Wireless                   | 4         | 0.52%   |
| Ericsson Business Mobile Networks | 4         | 0.52%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.39%   |
| Huawei Technologies               | 3         | 0.39%   |
| Samsung Electronics               | 2         | 0.26%   |
| Qualcomm Atheros Communications   | 2         | 0.26%   |
| JMicron Technology                | 2         | 0.26%   |
| Hewlett-Packard                   | 2         | 0.26%   |
| D-Link                            | 2         | 0.26%   |
| Xiaomi                            | 1         | 0.13%   |
| VIA Technologies                  | 1         | 0.13%   |
| Linksys                           | 1         | 0.13%   |
| Lenovo                            | 1         | 0.13%   |
| IMC Networks                      | 1         | 0.13%   |
| ICS Advent                        | 1         | 0.13%   |
| ASIX Electronics                  | 1         | 0.13%   |
| Arduino SA                        | 1         | 0.13%   |
| Apple                             | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 156       | 17.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 67        | 7.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 3.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 2.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 2.54%   |
| Intel Wireless 8265 / 8275                                              | 22        | 2.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.55%   |
| Intel Wireless 8260                                                     | 14        | 1.55%   |
| Intel Wireless 7260                                                     | 14        | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 1.44%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 1.44%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 11        | 1.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 1.1%    |
| Intel Wi-Fi 6 AX201                                                     | 10        | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.88%   |
| Intel Wireless 3165                                                     | 8         | 0.88%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 0.88%   |
| Intel Ethernet Connection I219-LM                                       | 8         | 0.88%   |
| Intel Ethernet Connection (4) I219-LM                                   | 8         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.77%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 0.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.77%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.66%   |
| Realtek RTL8125 2.5GbE Controller                                       | 6         | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.66%   |
| Intel 82577LM Gigabit Network Connection                                | 6         | 0.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 6         | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.55%   |
| Nvidia MCP79 Ethernet                                                   | 5         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 201       | 41.44%  |
| Qualcomm Atheros                | 111       | 22.89%  |
| Realtek Semiconductor           | 75        | 15.46%  |
| Broadcom                        | 43        | 8.87%   |
| MediaTek                        | 18        | 3.71%   |
| Ralink                          | 10        | 2.06%   |
| Ralink Technology               | 5         | 1.03%   |
| Sierra Wireless                 | 4         | 0.82%   |
| Dell                            | 4         | 0.82%   |
| TP-Link                         | 3         | 0.62%   |
| Broadcom Limited                | 3         | 0.62%   |
| Qualcomm Atheros Communications | 2         | 0.41%   |
| Hewlett-Packard                 | 2         | 0.41%   |
| D-Link                          | 2         | 0.41%   |
| Linksys                         | 1         | 0.21%   |
| IMC Networks                    | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 31        | 6.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 27        | 5.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 23        | 4.73%   |
| Intel Wireless 8265 / 8275                                              | 22        | 4.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 14        | 2.88%   |
| Intel Wireless 8260                                                     | 14        | 2.88%   |
| Intel Wireless 7260                                                     | 14        | 2.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 2.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 13        | 2.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 2.67%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 2.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 2.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.06%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 2.06%   |
| Intel Wi-Fi 6 AX201                                                     | 10        | 2.06%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 1.65%   |
| Intel Wireless 3165                                                     | 8         | 1.65%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 8         | 1.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 8         | 1.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 1.44%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 1.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 5         | 1.03%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.03%   |
| Intel Wireless 7265                                                     | 5         | 1.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 5         | 1.03%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.82%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.82%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 4         | 0.82%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.82%   |
| Intel Wireless 3160                                                     | 4         | 0.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 4         | 0.82%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 243       | 60.15%  |
| Intel                      | 80        | 19.8%   |
| Qualcomm Atheros           | 26        | 6.44%   |
| Broadcom                   | 19        | 4.7%    |
| Broadcom Limited           | 8         | 1.98%   |
| Nvidia                     | 6         | 1.49%   |
| Marvell Technology Group   | 6         | 1.49%   |
| ZTE WCDMA Technologies MSM | 3         | 0.74%   |
| Samsung Electronics        | 2         | 0.5%    |
| JMicron Technology         | 2         | 0.5%    |
| Xiaomi                     | 1         | 0.25%   |
| VIA Technologies           | 1         | 0.25%   |
| TP-Link                    | 1         | 0.25%   |
| MediaTek                   | 1         | 0.25%   |
| Lenovo                     | 1         | 0.25%   |
| ICS Advent                 | 1         | 0.25%   |
| Huawei Technologies        | 1         | 0.25%   |
| ASIX Electronics           | 1         | 0.25%   |
| Apple                      | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 156       | 38.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 67        | 16.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 11        | 2.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 2.46%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 1.97%   |
| Intel Ethernet Connection (4) I219-LM                                  | 8         | 1.97%   |
| Realtek RTL8125 2.5GbE Controller                                      | 6         | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6         | 1.47%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 1.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 6         | 1.47%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 5         | 1.23%   |
| Nvidia MCP79 Ethernet                                                  | 5         | 1.23%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 1.23%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.98%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.98%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                  | 3         | 0.74%   |
| Intel Ethernet Connection (13) I219-V                                  | 3         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.74%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 3         | 0.74%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 3         | 0.74%   |
| ZTE WCDMA MSM DEMO Mobile Boardband                                    | 2         | 0.49%   |
| Realtek Killer E2600 GbE Controller                                    | 2         | 0.49%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.49%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 2         | 0.49%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.49%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.49%   |
| Intel Ethernet Connection I217-V                                       | 2         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.49%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.49%   |
| Intel Ethernet Connection (5) I219-LM                                  | 2         | 0.49%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.49%   |
| Intel 82566MM Gigabit Network Connection                               | 2         | 0.49%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                 | 2         | 0.49%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 2         | 0.49%   |
| ZTE WCDMA MSM Unisoc Phone                                             | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 462       | 53.1%   |
| Ethernet | 396       | 45.52%  |
| Modem    | 12        | 1.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 383       | 78.32%  |
| Ethernet | 106       | 21.68%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 374       | 80.6%   |
| 1     | 89        | 19.18%  |
| 3     | 1         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 454       | 97.42%  |
| Yes  | 12        | 2.58%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 150       | 38.86%  |
| Realtek Semiconductor           | 59        | 15.28%  |
| Qualcomm Atheros Communications | 43        | 11.14%  |
| Lite-On Technology              | 27        | 6.99%   |
| IMC Networks                    | 26        | 6.74%   |
| Broadcom                        | 22        | 5.7%    |
| Foxconn / Hon Hai               | 16        | 4.15%   |
| Hewlett-Packard                 | 7         | 1.81%   |
| Apple                           | 7         | 1.81%   |
| Toshiba                         | 6         | 1.55%   |
| Dell                            | 5         | 1.3%    |
| Ralink                          | 4         | 1.04%   |
| Foxconn International           | 3         | 0.78%   |
| USI                             | 2         | 0.52%   |
| Ralink Technology               | 2         | 0.52%   |
| Cambridge Silicon Radio         | 2         | 0.52%   |
| Realtek                         | 1         | 0.26%   |
| Opticis                         | 1         | 0.26%   |
| MediaTek                        | 1         | 0.26%   |
| Askey Computer                  | 1         | 0.26%   |
| Alps Electric                   | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                 | 33        | 8.55%   |
| Intel Bluetooth Device                             | 31        | 8.03%   |
| Realtek Bluetooth Radio                            | 28        | 7.25%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)     | 28        | 7.25%   |
| Intel AX201 Bluetooth                              | 21        | 5.44%   |
| Qualcomm Atheros  Bluetooth Device                 | 18        | 4.66%   |
| Realtek  Bluetooth 4.2 Adapter                     | 14        | 3.63%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth         | 13        | 3.37%   |
| Intel AX200 Bluetooth                              | 12        | 3.11%   |
| IMC Networks Wireless_Device                       | 9         | 2.33%   |
| Intel AX211 Bluetooth                              | 8         | 2.07%   |
| Lite-On Bluetooth Device                           | 7         | 1.81%   |
| IMC Networks Bluetooth Radio                       | 7         | 1.81%   |
| Realtek 802.11ac WLAN Adapter                      | 6         | 1.55%   |
| Qualcomm Atheros AR9462 Bluetooth                  | 6         | 1.55%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0              | 6         | 1.55%   |
| Apple Bluetooth Host Controller                    | 6         | 1.55%   |
| Realtek RTL8821A Bluetooth                         | 5         | 1.3%    |
| Qualcomm Atheros AR3011 Bluetooth                  | 5         | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver      | 5         | 1.3%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter       | 5         | 1.3%    |
| Foxconn / Hon Hai Bluetooth Device                 | 5         | 1.3%    |
| Realtek RTL8723B Bluetooth                         | 4         | 1.04%   |
| Ralink RT3290 Bluetooth                            | 4         | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0             | 4         | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth                  | 4         | 1.04%   |
| Intel AX210 Bluetooth                              | 4         | 1.04%   |
| IMC Networks Bluetooth Device                      | 4         | 1.04%   |
| HP Broadcom 2070 Bluetooth Combo                   | 4         | 1.04%   |
| Dell DW375 Bluetooth Module                        | 4         | 1.04%   |
| Broadcom BCM43142A0 Bluetooth 4.0                  | 4         | 1.04%   |
| Lite-On Atheros AR3012 Bluetooth                   | 3         | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                   | 3         | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter   | 3         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter  | 3         | 0.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]      | 3         | 0.78%   |
| Foxconn International BCM43142A0 Bluetooth module  | 3         | 0.78%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR               | 3         | 0.78%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller] | 3         | 0.78%   |
| USI Bluetooth Module BCM92070                      | 2         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 353       | 64.77%  |
| AMD                         | 106       | 19.45%  |
| Nvidia                      | 65        | 11.93%  |
| Logitech                    | 3         | 0.55%   |
| Hewlett-Packard             | 3         | 0.55%   |
| Microsoft                   | 2         | 0.37%   |
| GN Netcom                   | 2         | 0.37%   |
| C-Media Electronics         | 2         | 0.37%   |
| Apple                       | 2         | 0.37%   |
| VIA Technologies            | 1         | 0.18%   |
| Tenx Technology             | 1         | 0.18%   |
| Plantronics                 | 1         | 0.18%   |
| Native Instruments          | 1         | 0.18%   |
| Kingston Technology         | 1         | 0.18%   |
| Focusrite-Novation          | 1         | 0.18%   |
| FiiO Electronics Technology | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 72        | 10.6%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 52        | 7.66%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 36        | 5.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 33        | 4.86%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 31        | 4.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 26        | 3.83%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 17        | 2.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 2.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 16        | 2.36%   |
| Intel 8 Series HD Audio Controller                                                                | 16        | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 2.21%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 2.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 2.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.91%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 1.77%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 1.77%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.77%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 11        | 1.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.62%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 9         | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 1.18%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.03%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 6         | 0.88%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 6         | 0.88%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 0.88%   |
| Intel CM238 HD Audio Controller                                                                   | 6         | 0.88%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 6         | 0.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 0.88%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 6         | 0.88%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 5         | 0.74%   |
| Nvidia Audio device                                                                               | 5         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 89        | 27.73%  |
| SK hynix            | 75        | 23.36%  |
| Micron Technology   | 49        | 15.26%  |
| Kingston            | 36        | 11.21%  |
| Unknown             | 18        | 5.61%   |
| Ramaxel Technology  | 14        | 4.36%   |
| Transcend           | 8         | 2.49%   |
| Elpida              | 5         | 1.56%   |
| Crucial             | 5         | 1.56%   |
| A-DATA Technology   | 5         | 1.56%   |
| Patriot             | 3         | 0.93%   |
| Nanya Technology    | 2         | 0.62%   |
| Corsair             | 2         | 0.62%   |
| Apacer              | 2         | 0.62%   |
| Unknown             | 2         | 0.62%   |
| Unknown (06F1)      | 1         | 0.31%   |
| SHARETRONIC         | 1         | 0.31%   |
| PNY                 | 1         | 0.31%   |
| CSX                 | 1         | 0.31%   |
| AMD                 | 1         | 0.31%   |
| 48spaces            | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                    | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s    | 7         | 2.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s   | 6         | 1.73%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s    | 6         | 1.73%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s     | 6         | 1.73%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s   | 5         | 1.45%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s    | 5         | 1.45%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 4         | 1.16%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s    | 4         | 1.16%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s    | 4         | 1.16%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s | 4         | 1.16%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s    | 4         | 1.16%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s    | 4         | 1.16%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s     | 4         | 1.16%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s  | 4         | 1.16%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s   | 3         | 0.87%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s   | 3         | 0.87%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s    | 3         | 0.87%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s    | 3         | 0.87%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s    | 3         | 0.87%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s    | 3         | 0.87%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s    | 3         | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s    | 3         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s    | 3         | 0.87%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s  | 3         | 0.87%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s     | 3         | 0.87%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s    | 3         | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s               | 2         | 0.58%   |
| Unknown RAM Module 1024MB SODIMM DDR                     | 2         | 0.58%   |
| Transcend RAM JM3200HSG-8G 8GB SODIMM DDR4 3200MT/s      | 2         | 0.58%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM SDRAM        | 2         | 0.58%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s   | 2         | 0.58%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s   | 2         | 0.58%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s   | 2         | 0.58%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM 1334MT/s     | 2         | 0.58%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s   | 2         | 0.58%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s   | 2         | 0.58%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s   | 2         | 0.58%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s   | 2         | 0.58%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s   | 2         | 0.58%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 124       | 47.51%  |
| DDR3    | 85        | 32.57%  |
| DDR2    | 13        | 4.98%   |
| DDR5    | 10        | 3.83%   |
| SDRAM   | 8         | 3.07%   |
| LPDDR4  | 8         | 3.07%   |
| LPDDR5  | 5         | 1.92%   |
| LPDDR3  | 3         | 1.15%   |
| Unknown | 3         | 1.15%   |
| DDR     | 2         | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 234       | 90%     |
| Row Of Chips | 23        | 8.85%   |
| Chip         | 3         | 1.15%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 104       | 37.01%  |
| 4096  | 92        | 32.74%  |
| 2048  | 38        | 13.52%  |
| 16384 | 29        | 10.32%  |
| 1024  | 11        | 3.91%   |
| 32768 | 6         | 2.14%   |
| 512   | 1         | 0.36%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 63        | 21.8%   |
| 1600    | 63        | 21.8%   |
| 2667    | 51        | 17.65%  |
| 2400    | 21        | 7.27%   |
| 1334    | 16        | 5.54%   |
| 1067    | 10        | 3.46%   |
| 2133    | 8         | 2.77%   |
| 667     | 8         | 2.77%   |
| 4800    | 6         | 2.08%   |
| Unknown | 6         | 2.08%   |
| 4199    | 5         | 1.73%   |
| 1333    | 5         | 1.73%   |
| 6400    | 4         | 1.38%   |
| 5600    | 4         | 1.38%   |
| 3266    | 4         | 1.38%   |
| 4267    | 3         | 1.04%   |
| 2048    | 3         | 1.04%   |
| 800     | 3         | 1.04%   |
| 975     | 2         | 0.69%   |
| 533     | 2         | 0.69%   |
| 7467    | 1         | 0.35%   |
| 2933    | 1         | 0.35%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 5         | 50%     |
| Canon                 | 2         | 20%     |
| Seiko Epson           | 1         | 10%     |
| Samsung Electronics   | 1         | 10%     |
| Lexmark International | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| HP LaserJet 1018                      | 2         | 20%     |
| Seiko Epson L365 Series               | 1         | 10%     |
| Samsung M2070 Series                  | 1         | 10%     |
| Lexmark International Lexmark MS312dn | 1         | 10%     |
| HP LaserJet 1020                      | 1         | 10%     |
| HP HP LaserJet M14-M17                | 1         | 10%     |
| HP DeskJet 845c                       | 1         | 10%     |
| Canon LBP6030w/6018w                  | 1         | 10%     |
| Canon iP7200 series                   | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 4         | 66.67%  |
| Ultima Electronics | 1         | 16.67%  |
| Seiko Epson        | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 2         | 33.33%  |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 16.67%  |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 1         | 16.67%  |
| Canon CanoScan LIDE 25                                                                | 1         | 16.67%  |
| Canon CanoScan LiDE 210                                                               | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 107       | 25.18%  |
| IMC Networks                           | 55        | 12.94%  |
| Realtek Semiconductor                  | 33        | 7.76%   |
| Microdia                               | 32        | 7.53%   |
| Quanta                                 | 25        | 5.88%   |
| Cheng Uei Precision Industry (Foxlink) | 22        | 5.18%   |
| Bison Electronics                      | 20        | 4.71%   |
| Sunplus Innovation Technology          | 19        | 4.47%   |
| Syntek                                 | 17        | 4%      |
| Suyin                                  | 17        | 4%      |
| Acer                                   | 15        | 3.53%   |
| Lite-On Technology                     | 9         | 2.12%   |
| Apple                                  | 8         | 1.88%   |
| Luxvisions Innotech Limited            | 7         | 1.65%   |
| Silicon Motion                         | 4         | 0.94%   |
| ShineTech                              | 4         | 0.94%   |
| Logitech                               | 4         | 0.94%   |
| Lenovo                                 | 4         | 0.94%   |
| Importek                               | 4         | 0.94%   |
| ALi                                    | 3         | 0.71%   |
| Alcor Micro                            | 3         | 0.71%   |
| Sonix Technology                       | 2         | 0.47%   |
| OmniVision Technologies                | 2         | 0.47%   |
| Z-Star Microelectronics                | 1         | 0.24%   |
| SunplusIT                              | 1         | 0.24%   |
| Samsung Electronics                    | 1         | 0.24%   |
| Ricoh                                  | 1         | 0.24%   |
| Primax Electronics                     | 1         | 0.24%   |
| KYE Systems (Mouse Systems)            | 1         | 0.24%   |
| Genesys Logic                          | 1         | 0.24%   |
| Generalplus Technology                 | 1         | 0.24%   |
| DigiTech                               | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 24        | 5.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 19        | 4.46%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 14        | 3.29%   |
| Syntek Integrated Camera                                       | 12        | 2.82%   |
| Realtek Integrated_Webcam_HD                                   | 12        | 2.82%   |
| Microdia Integrated_Webcam_HD                                  | 12        | 2.82%   |
| Bison Integrated Camera                                        | 11        | 2.58%   |
| Quanta VGA WebCam                                              | 9         | 2.11%   |
| IMC Networks Integrated Camera                                 | 9         | 2.11%   |
| Sunplus Integrated_Webcam_HD                                   | 8         | 1.88%   |
| Realtek USB Camera                                             | 6         | 1.41%   |
| Chicony VGA Webcam                                             | 6         | 1.41%   |
| Chicony HP Webcam                                              | 6         | 1.41%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 5         | 1.17%   |
| Realtek Lenovo EasyCamera                                      | 5         | 1.17%   |
| Microdia Integrated Webcam                                     | 5         | 1.17%   |
| Chicony TOSHIBA Web Camera - HD                                | 5         | 1.17%   |
| Chicony Integrated Camera (1280x720@30)                        | 5         | 1.17%   |
| Chicony HD WebCam                                              | 5         | 1.17%   |
| Chicony EasyCamera                                             | 5         | 1.17%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 5         | 1.17%   |
| Acer Integrated Camera                                         | 5         | 1.17%   |
| Syntek EasyCamera                                              | 4         | 0.94%   |
| ShineTech USB2.0 HD UVC WebCam                                 | 4         | 0.94%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 0.94%   |
| Quanta HD User Facing                                          | 4         | 0.94%   |
| IMC Networks EasyCamera                                        | 4         | 0.94%   |
| Chicony HP HD Camera                                           | 4         | 0.94%   |
| Chicony HD User Facing                                         | 4         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 4         | 0.94%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.94%   |
| Apple Built-in iSight                                          | 4         | 0.94%   |
| Acer Lenovo EasyCamera                                         | 4         | 0.94%   |
| Sunplus Asus Webcam                                            | 3         | 0.7%    |
| Realtek Integrated Webcam HD                                   | 3         | 0.7%    |
| Microdia Dell Laptop Integrated Webcam HD                      | 3         | 0.7%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 3         | 0.7%    |
| Lite-On HP HD Webcam                                           | 3         | 0.7%    |
| Lenovo Integrated Webcam                                       | 3         | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam                                  | 3         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 29        | 38.16%  |
| Synaptics                          | 16        | 21.05%  |
| Shenzhen Goodix Technology         | 12        | 15.79%  |
| Upek                               | 6         | 7.89%   |
| AuthenTec                          | 6         | 7.89%   |
| Elan Microelectronics              | 3         | 3.95%   |
| LighTuning Technology              | 2         | 2.63%   |
| STMicroelectronics                 | 1         | 1.32%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.32%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 10        | 13.16%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 9.21%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 6.58%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 6.58%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 5.26%   |
| Synaptics  WBDI                                                            | 4         | 5.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 3.95%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.95%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 3.95%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.63%   |
| Synaptics WBDI                                                             | 2         | 2.63%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.63%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.63%   |
| AuthenTec AES2810                                                          | 2         | 2.63%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.32%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.32%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.32%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.32%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 1.32%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.32%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.32%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.32%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.32%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.32%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.32%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.32%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 15        | 37.5%   |
| Alcor Micro               | 14        | 35%     |
| Upek                      | 2         | 5%      |
| OmniKey                   | 2         | 5%      |
| O2 Micro                  | 2         | 5%      |
| Lenovo                    | 2         | 5%      |
| Yubico.com                | 1         | 2.5%    |
| Gemalto (was Gemplus)     | 1         | 2.5%    |
| Fujitsu Siemens Computers | 1         | 2.5%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 35%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 10%     |
| Broadcom 5880                                                                | 4         | 10%     |
| Broadcom 58200                                                               | 3         | 7.5%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 5%      |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5%      |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 2.5%    |
| OmniKey CardMan 4321                                                         | 1         | 2.5%    |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 2.5%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.5%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 2.5%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 295       | 61.59%  |
| 1     | 145       | 30.27%  |
| 2     | 30        | 6.26%   |
| 3     | 5         | 1.04%   |
| 4     | 3         | 0.63%   |
| 8     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 76        | 33.04%  |
| Graphics card            | 51        | 22.17%  |
| Chipcard                 | 36        | 15.65%  |
| Net/wireless             | 24        | 10.43%  |
| Multimedia controller    | 12        | 5.22%   |
| Bluetooth                | 9         | 3.91%   |
| Sound                    | 5         | 2.17%   |
| Communication controller | 5         | 2.17%   |
| Camera                   | 4         | 1.74%   |
| Net/ethernet             | 3         | 1.3%    |
| Card reader              | 3         | 1.3%    |
| Storage                  | 1         | 0.43%   |
| Modem                    | 1         | 0.43%   |

