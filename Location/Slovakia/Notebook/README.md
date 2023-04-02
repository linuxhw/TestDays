Linux in Slovakia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Slovakia.

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

Total: 593

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 250 G7 Notebook PC          | [fcb8359930](https://linux-hardware.org/?probe=fcb8359930) | Mar 28, 2023 |
| HP            | 250 G7 Notebook PC          | [2558605a4b](https://linux-hardware.org/?probe=2558605a4b) | Mar 28, 2023 |
| Toshiba       | Satellite C855-1TT          | [ac8e41d993](https://linux-hardware.org/?probe=ac8e41d993) | Mar 27, 2023 |
| Valve         | Jupiter                     | [3ad7937aaf](https://linux-hardware.org/?probe=3ad7937aaf) | Mar 26, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c17f20a679](https://linux-hardware.org/?probe=c17f20a679) | Mar 23, 2023 |
| HP            | ProBook 6470b               | [dd23ab1a2e](https://linux-hardware.org/?probe=dd23ab1a2e) | Mar 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [1ca9befb7a](https://linux-hardware.org/?probe=1ca9befb7a) | Mar 18, 2023 |
| HP            | Pavilion dv6                | [9c24401930](https://linux-hardware.org/?probe=9c24401930) | Mar 18, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | [c145898fae](https://linux-hardware.org/?probe=c145898fae) | Mar 17, 2023 |
| Lenovo        | ThinkPad T590 20N4000DXS    | [293fe8b4ab](https://linux-hardware.org/?probe=293fe8b4ab) | Mar 17, 2023 |
| HP            | EliteBook 2570p             | [374bab39d7](https://linux-hardware.org/?probe=374bab39d7) | Mar 17, 2023 |
| MSI           | CR500                       | [28eeb3bd71](https://linux-hardware.org/?probe=28eeb3bd71) | Mar 16, 2023 |
| Dell          | Latitude 5580               | [819b5d8dc2](https://linux-hardware.org/?probe=819b5d8dc2) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| Acer          | Aspire VN7-791              | [ca10594901](https://linux-hardware.org/?probe=ca10594901) | Mar 12, 2023 |
| ASUSTek       | X541SA                      | [4adcb5ab0f](https://linux-hardware.org/?probe=4adcb5ab0f) | Mar 08, 2023 |
| Acer          | Aspire VN7-792G             | [3b4a3b74a1](https://linux-hardware.org/?probe=3b4a3b74a1) | Mar 07, 2023 |
| Lenovo        | G505s 20255                 | [b338e704d9](https://linux-hardware.org/?probe=b338e704d9) | Mar 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [925e02d1dc](https://linux-hardware.org/?probe=925e02d1dc) | Mar 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [7d9acf8639](https://linux-hardware.org/?probe=7d9acf8639) | Mar 04, 2023 |
| HP            | 255 G8 Notebook PC          | [0c76255503](https://linux-hardware.org/?probe=0c76255503) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Google        | Voxel                       | [ce917fe8ec](https://linux-hardware.org/?probe=ce917fe8ec) | Feb 25, 2023 |
| Google        | Voxel                       | [93ea143f69](https://linux-hardware.org/?probe=93ea143f69) | Feb 25, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [faeee1c46c](https://linux-hardware.org/?probe=faeee1c46c) | Feb 24, 2023 |
| HP            | ProBook 4540s               | [cc3e78f73f](https://linux-hardware.org/?probe=cc3e78f73f) | Feb 18, 2023 |
| Medion        | P651x series                | [23b3fb7ce5](https://linux-hardware.org/?probe=23b3fb7ce5) | Feb 16, 2023 |
| HP            | Pavilion 11 x360 PC         | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| HP            | ProBook 4340s               | [caed0e9f2d](https://linux-hardware.org/?probe=caed0e9f2d) | Feb 13, 2023 |
| Lenovo        | IdeaPad Y580                | [f396fdb21f](https://linux-hardware.org/?probe=f396fdb21f) | Feb 05, 2023 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [bac184b151](https://linux-hardware.org/?probe=bac184b151) | Feb 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1S    | [3f3e5b3a1e](https://linux-hardware.org/?probe=3f3e5b3a1e) | Feb 03, 2023 |
| Dell          | Vostro 5481                 | [40bc04540d](https://linux-hardware.org/?probe=40bc04540d) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1cfa73407d](https://linux-hardware.org/?probe=1cfa73407d) | Jan 31, 2023 |
| HP            | 255 G8 Notebook PC          | [d8e161e2b0](https://linux-hardware.org/?probe=d8e161e2b0) | Jan 25, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [e589b4bd78](https://linux-hardware.org/?probe=e589b4bd78) | Jan 25, 2023 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [92a3e34781](https://linux-hardware.org/?probe=92a3e34781) | Jan 24, 2023 |
| Acer          | Aspire E3-111               | [fde7baf9e8](https://linux-hardware.org/?probe=fde7baf9e8) | Jan 19, 2023 |
| Dell          | Inspiron 5770               | [64976ae263](https://linux-hardware.org/?probe=64976ae263) | Jan 19, 2023 |
| PC Special... | Recoil II RTX               | [33850c8810](https://linux-hardware.org/?probe=33850c8810) | Jan 16, 2023 |
| Dell          | Precision 7520              | [c57fdfbe1e](https://linux-hardware.org/?probe=c57fdfbe1e) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Dell          | Latitude E6410              | [a11818f59a](https://linux-hardware.org/?probe=a11818f59a) | Jan 13, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D60... | [22d0c82134](https://linux-hardware.org/?probe=22d0c82134) | Jan 12, 2023 |
| ASUSTek       | G53SX                       | [ef2d9747e2](https://linux-hardware.org/?probe=ef2d9747e2) | Jan 12, 2023 |
| HP            | ProBook 6450b               | [0ae783d261](https://linux-hardware.org/?probe=0ae783d261) | Jan 11, 2023 |
| Dell          | XPS 15 9570                 | [8032d8e1be](https://linux-hardware.org/?probe=8032d8e1be) | Jan 07, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Google        | Voxel                       | [430244f188](https://linux-hardware.org/?probe=430244f188) | Dec 28, 2022 |
| ASUSTek       | K52Je                       | [28cac9b262](https://linux-hardware.org/?probe=28cac9b262) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| Dell          | Latitude 3510               | [ac931934de](https://linux-hardware.org/?probe=ac931934de) | Dec 27, 2022 |
| Dell          | Latitude 3510               | [5db1cf6cb6](https://linux-hardware.org/?probe=5db1cf6cb6) | Dec 27, 2022 |
| Samsung       | 270E5G/270E5U               | [705baed85a](https://linux-hardware.org/?probe=705baed85a) | Dec 26, 2022 |
| ASUSTek       | K52Je                       | [dc13c122ed](https://linux-hardware.org/?probe=dc13c122ed) | Dec 26, 2022 |
| HP            | Pavilion g6                 | [71d7947da6](https://linux-hardware.org/?probe=71d7947da6) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [30c3f8d777](https://linux-hardware.org/?probe=30c3f8d777) | Dec 21, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [0d273375d6](https://linux-hardware.org/?probe=0d273375d6) | Dec 18, 2022 |
| HP            | Pavilion g6                 | [b5662e5fec](https://linux-hardware.org/?probe=b5662e5fec) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c715acf0ea](https://linux-hardware.org/?probe=c715acf0ea) | Dec 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [18b2579f75](https://linux-hardware.org/?probe=18b2579f75) | Dec 09, 2022 |
| HP            | Pavilion g6                 | [d2b43c2803](https://linux-hardware.org/?probe=d2b43c2803) | Dec 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | [fa46f1d34a](https://linux-hardware.org/?probe=fa46f1d34a) | Dec 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c0f7c4b788](https://linux-hardware.org/?probe=c0f7c4b788) | Dec 03, 2022 |
| Google        | Voxel                       | [b64ebf7db7](https://linux-hardware.org/?probe=b64ebf7db7) | Dec 03, 2022 |
| HP            | 620                         | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [af7d162434](https://linux-hardware.org/?probe=af7d162434) | Nov 28, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d7992855ba](https://linux-hardware.org/?probe=d7992855ba) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8e17476123](https://linux-hardware.org/?probe=8e17476123) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f48e29fef2](https://linux-hardware.org/?probe=f48e29fef2) | Nov 16, 2022 |
| Acer          | Aspire VN7-791              | [736c2f5664](https://linux-hardware.org/?probe=736c2f5664) | Nov 14, 2022 |
| Lenovo        | V14-IIL 82C4                | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [4f40815737](https://linux-hardware.org/?probe=4f40815737) | Nov 12, 2022 |
| GPD           | G1619-04                    | [cf4cb47a12](https://linux-hardware.org/?probe=cf4cb47a12) | Nov 09, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [87cfe8ed2e](https://linux-hardware.org/?probe=87cfe8ed2e) | Oct 11, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | [52658eb393](https://linux-hardware.org/?probe=52658eb393) | Oct 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19c7d98b00](https://linux-hardware.org/?probe=19c7d98b00) | Oct 06, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [97d1b5e6c5](https://linux-hardware.org/?probe=97d1b5e6c5) | Sep 30, 2022 |
| Dell          | Vostro 5391                 | [61a25cdb83](https://linux-hardware.org/?probe=61a25cdb83) | Sep 28, 2022 |
| ASUSTek       | K55VJ                       | [8e87d041c3](https://linux-hardware.org/?probe=8e87d041c3) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [afd66066bc](https://linux-hardware.org/?probe=afd66066bc) | Sep 21, 2022 |
| Lenovo        | G780                        | [04f924450d](https://linux-hardware.org/?probe=04f924450d) | Sep 17, 2022 |
| Valve         | Jupiter                     | [1dc4620833](https://linux-hardware.org/?probe=1dc4620833) | Sep 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [ecaa040ba1](https://linux-hardware.org/?probe=ecaa040ba1) | Sep 04, 2022 |
| Dell          | Latitude 3510               | [9477575b26](https://linux-hardware.org/?probe=9477575b26) | Sep 03, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [6a2cb26049](https://linux-hardware.org/?probe=6a2cb26049) | Sep 02, 2022 |
| Toshiba       | TECRA S5                    | [121c8e110b](https://linux-hardware.org/?probe=121c8e110b) | Aug 31, 2022 |
| Toshiba       | TECRA S5                    | [6ec2bd9539](https://linux-hardware.org/?probe=6ec2bd9539) | Aug 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [4b56f15871](https://linux-hardware.org/?probe=4b56f15871) | Aug 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dd415db306](https://linux-hardware.org/?probe=dd415db306) | Aug 28, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [8756581baa](https://linux-hardware.org/?probe=8756581baa) | Aug 21, 2022 |
| Samsung       | NC210/NC110                 | [3dcdc1dc6a](https://linux-hardware.org/?probe=3dcdc1dc6a) | Aug 15, 2022 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | [1bcc13e6b4](https://linux-hardware.org/?probe=1bcc13e6b4) | Aug 15, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9a06c0c10c](https://linux-hardware.org/?probe=9a06c0c10c) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7e5a0c0004](https://linux-hardware.org/?probe=7e5a0c0004) | Aug 06, 2022 |
| Acer          | Aspire VN7-791G             | [3e72040097](https://linux-hardware.org/?probe=3e72040097) | Jul 31, 2022 |
| Dell          | XPS 15 9570                 | [e7f56631b1](https://linux-hardware.org/?probe=e7f56631b1) | Jul 27, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b4a9542143](https://linux-hardware.org/?probe=b4a9542143) | Jul 27, 2022 |
| Dell          | XPS 15 9570                 | [f3972b3a7d](https://linux-hardware.org/?probe=f3972b3a7d) | Jul 26, 2022 |
| HP            | ProBook 440 G3              | [04b2ed9273](https://linux-hardware.org/?probe=04b2ed9273) | Jul 19, 2022 |
| UMAX          | VisionBook-N12R             | [9ccb1f57ab](https://linux-hardware.org/?probe=9ccb1f57ab) | Jul 16, 2022 |
| HP            | ProBook 440 G3              | [c546e3b537](https://linux-hardware.org/?probe=c546e3b537) | Jul 13, 2022 |
| ASUSTek       | N550JK                      | [bc0c9431e1](https://linux-hardware.org/?probe=bc0c9431e1) | Jul 04, 2022 |
| ASUSTek       | N550JK                      | [539ce50149](https://linux-hardware.org/?probe=539ce50149) | Jul 04, 2022 |
| MSI           | EX705                       | [d85dfacff5](https://linux-hardware.org/?probe=d85dfacff5) | Jun 30, 2022 |
| MSI           | EX705                       | [3de108279f](https://linux-hardware.org/?probe=3de108279f) | Jun 30, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| HP            | ZBook 15 G6                 | [2e4663e8c3](https://linux-hardware.org/?probe=2e4663e8c3) | Jun 22, 2022 |
| HP            | Pavilion dv6                | [1ba5e6c491](https://linux-hardware.org/?probe=1ba5e6c491) | Jun 18, 2022 |
| Dell          | Latitude 3510               | [4b6e3aeb9e](https://linux-hardware.org/?probe=4b6e3aeb9e) | Jun 16, 2022 |
| Dell          | Latitude E5570              | [ce4d3bb373](https://linux-hardware.org/?probe=ce4d3bb373) | Jun 09, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [fdda1deb12](https://linux-hardware.org/?probe=fdda1deb12) | Jun 07, 2022 |
| Valve         | Jupiter                     | [cc0a20bb93](https://linux-hardware.org/?probe=cc0a20bb93) | Jun 06, 2022 |
| Dell          | Latitude E6440              | [dd05b883a6](https://linux-hardware.org/?probe=dd05b883a6) | Jun 04, 2022 |
| Dell          | Vostro 5515                 | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| MSI           | GT60 2OC/2OD                | [c3b5eb704d](https://linux-hardware.org/?probe=c3b5eb704d) | May 22, 2022 |
| MSI           | GT60 2OC/2OD                | [96f6fda5d5](https://linux-hardware.org/?probe=96f6fda5d5) | May 22, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [0793a5608a](https://linux-hardware.org/?probe=0793a5608a) | May 15, 2022 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [d8361f7895](https://linux-hardware.org/?probe=d8361f7895) | May 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3ba9de57d1](https://linux-hardware.org/?probe=3ba9de57d1) | May 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [96be9cb5e7](https://linux-hardware.org/?probe=96be9cb5e7) | May 12, 2022 |
| Acer          | Aspire E5-575G              | [71e7f1c760](https://linux-hardware.org/?probe=71e7f1c760) | May 09, 2022 |
| MSI           | GT60 2OC/2OD                | [21f08dbab6](https://linux-hardware.org/?probe=21f08dbab6) | May 06, 2022 |
| Dell          | Inspiron 3576               | [85901f28cb](https://linux-hardware.org/?probe=85901f28cb) | May 05, 2022 |
| Acer          | Extensa 5635G               | [6e69a86d63](https://linux-hardware.org/?probe=6e69a86d63) | Apr 28, 2022 |
| HP            | ProBook 4540s               | [17272efb83](https://linux-hardware.org/?probe=17272efb83) | Apr 22, 2022 |
| Dell          | G3 3579                     | [a85e01d9d0](https://linux-hardware.org/?probe=a85e01d9d0) | Apr 20, 2022 |
| Dell          | Latitude E6520              | [33502900d8](https://linux-hardware.org/?probe=33502900d8) | Apr 19, 2022 |
| Fujitsu       | LIFEBOOK E751               | [54de39efb5](https://linux-hardware.org/?probe=54de39efb5) | Apr 12, 2022 |
| HP            | 15                          | [443dd5b9e8](https://linux-hardware.org/?probe=443dd5b9e8) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| ASUSTek       | X555LF                      | [35cceb0f0a](https://linux-hardware.org/?probe=35cceb0f0a) | Mar 31, 2022 |
| Fujitsu Si... | AMILO Pi 3525               | [b77907b9b6](https://linux-hardware.org/?probe=b77907b9b6) | Mar 31, 2022 |
| HP            | ProBook 4340s               | [787443949a](https://linux-hardware.org/?probe=787443949a) | Mar 27, 2022 |
| Lenovo        | ThinkPad T420 42364F2       | [d82acaba71](https://linux-hardware.org/?probe=d82acaba71) | Mar 23, 2022 |
| HP            | EliteBook 8740w             | [3ae23e0d6b](https://linux-hardware.org/?probe=3ae23e0d6b) | Mar 22, 2022 |
| ASUSTek       | K50IN                       | [02326ae250](https://linux-hardware.org/?probe=02326ae250) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| Dell          | Latitude 3510               | [f24ba2791e](https://linux-hardware.org/?probe=f24ba2791e) | Mar 19, 2022 |
| ASUSTek       | N53SN                       | [f335baa4a4](https://linux-hardware.org/?probe=f335baa4a4) | Mar 18, 2022 |
| Lenovo        | B580 20144                  | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| HP            | ProBook 4340s               | [01af2dee98](https://linux-hardware.org/?probe=01af2dee98) | Mar 13, 2022 |
| HP            | EliteBook 8470p             | [76e54baafe](https://linux-hardware.org/?probe=76e54baafe) | Mar 09, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Dell          | Vostro 5515                 | [7707d7dc14](https://linux-hardware.org/?probe=7707d7dc14) | Feb 23, 2022 |
| Sony          | VPCEH3S6E                   | [334451b6e7](https://linux-hardware.org/?probe=334451b6e7) | Feb 23, 2022 |
| UMAX          | VisionBook 14Wr Plus        | [2e2c2de75c](https://linux-hardware.org/?probe=2e2c2de75c) | Feb 20, 2022 |
| ASUSTek       | K56CM                       | [c6e3cad977](https://linux-hardware.org/?probe=c6e3cad977) | Feb 19, 2022 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [9df089b1ef](https://linux-hardware.org/?probe=9df089b1ef) | Feb 19, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c9b5c461da](https://linux-hardware.org/?probe=c9b5c461da) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [b4d07e8ab1](https://linux-hardware.org/?probe=b4d07e8ab1) | Feb 15, 2022 |
| Dell          | Latitude E6500              | [4b35cc763b](https://linux-hardware.org/?probe=4b35cc763b) | Feb 11, 2022 |
| Dell          | Latitude E6500              | [097664c430](https://linux-hardware.org/?probe=097664c430) | Feb 11, 2022 |
| HP            | EliteBook 840 G3            | [383572d5be](https://linux-hardware.org/?probe=383572d5be) | Feb 08, 2022 |
| Toshiba       | Satellite C855-1TT          | [87eacffdb8](https://linux-hardware.org/?probe=87eacffdb8) | Feb 07, 2022 |
| MSI           | VR201                       | [5d514ac721](https://linux-hardware.org/?probe=5d514ac721) | Feb 01, 2022 |
| HP            | ProBook 450 G5              | [39511f4010](https://linux-hardware.org/?probe=39511f4010) | Jan 29, 2022 |
| ASUSTek       | K50C                        | [a285a1e873](https://linux-hardware.org/?probe=a285a1e873) | Jan 27, 2022 |
| Dell          | Latitude E5570              | [7b6a4470d6](https://linux-hardware.org/?probe=7b6a4470d6) | Jan 27, 2022 |
| Acer          | Swift SF314-43              | [11f5908f13](https://linux-hardware.org/?probe=11f5908f13) | Jan 26, 2022 |
| Lenovo        | ThinkPad 20TDZMS            | [143bc3f79b](https://linux-hardware.org/?probe=143bc3f79b) | Jan 23, 2022 |
| MSI           | MS-163B Ver                 | [2e2d0c47bd](https://linux-hardware.org/?probe=2e2d0c47bd) | Jan 23, 2022 |
| Dell          | Latitude 3510               | [47793faf9f](https://linux-hardware.org/?probe=47793faf9f) | Jan 18, 2022 |
| MSI           | EX705                       | [bf23179311](https://linux-hardware.org/?probe=bf23179311) | Jan 17, 2022 |
| ASUSTek       | X553MA                      | [a1f88f8fc7](https://linux-hardware.org/?probe=a1f88f8fc7) | Jan 15, 2022 |
| HP            | Pavilion Gaming Laptop-c... | [bc679e8ef6](https://linux-hardware.org/?probe=bc679e8ef6) | Jan 14, 2022 |
| ASUSTek       | X553MA                      | [3260495670](https://linux-hardware.org/?probe=3260495670) | Jan 13, 2022 |
| HP            | ZBook 15 G3                 | [e91280cb30](https://linux-hardware.org/?probe=e91280cb30) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [b5709d8fd1](https://linux-hardware.org/?probe=b5709d8fd1) | Dec 31, 2021 |
| Lenovo        | Yoga Slim 9 14ITL5 82D1     | [b79036063e](https://linux-hardware.org/?probe=b79036063e) | Dec 31, 2021 |
| ASUSTek       | G751JY                      | [e7a5fad002](https://linux-hardware.org/?probe=e7a5fad002) | Dec 29, 2021 |
| HP            | ZBook 15 G3                 | [a2a0923008](https://linux-hardware.org/?probe=a2a0923008) | Dec 20, 2021 |
| HP            | ZBook 15 G3                 | [0cba25aac5](https://linux-hardware.org/?probe=0cba25aac5) | Dec 20, 2021 |
| Lenovo        | G505 20240                  | [e29df1e2a0](https://linux-hardware.org/?probe=e29df1e2a0) | Dec 19, 2021 |
| ASUSTek       | X555BP                      | [770e3752e6](https://linux-hardware.org/?probe=770e3752e6) | Dec 18, 2021 |
| Dell          | Latitude E6430              | [5d4005ae4c](https://linux-hardware.org/?probe=5d4005ae4c) | Dec 13, 2021 |
| Dell          | Latitude 3510               | [e2834c5ef6](https://linux-hardware.org/?probe=e2834c5ef6) | Dec 08, 2021 |
| Dell          | Latitude 5401               | [796c461b16](https://linux-hardware.org/?probe=796c461b16) | Dec 01, 2021 |
| Dell          | Latitude D630               | [6044bc3e07](https://linux-hardware.org/?probe=6044bc3e07) | Nov 28, 2021 |
| Apple         | MacBookPro14,1              | [795a9ffd0f](https://linux-hardware.org/?probe=795a9ffd0f) | Nov 27, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [e1827cbbc6](https://linux-hardware.org/?probe=e1827cbbc6) | Nov 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| Dell          | Latitude 5590               | [d8b69c36bd](https://linux-hardware.org/?probe=d8b69c36bd) | Nov 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6189028e3d](https://linux-hardware.org/?probe=6189028e3d) | Nov 23, 2021 |
| Toshiba       | Satellite Pro C850-1D5      | [22ed560714](https://linux-hardware.org/?probe=22ed560714) | Nov 21, 2021 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [55384cc552](https://linux-hardware.org/?probe=55384cc552) | Nov 18, 2021 |
| Lenovo        | Z50-70 20354                | [4c1c718d65](https://linux-hardware.org/?probe=4c1c718d65) | Nov 14, 2021 |
| Toshiba       | Satellite L500              | [82d6b16382](https://linux-hardware.org/?probe=82d6b16382) | Nov 08, 2021 |
| Toshiba       | Satellite L500              | [70e2057cff](https://linux-hardware.org/?probe=70e2057cff) | Nov 07, 2021 |
| Toshiba       | Satellite U400              | [7b2364e53a](https://linux-hardware.org/?probe=7b2364e53a) | Nov 04, 2021 |
| HP            | Presario CQ57               | [8e3ceb5db9](https://linux-hardware.org/?probe=8e3ceb5db9) | Oct 23, 2021 |
| HP            | Presario CQ57               | [78828b2790](https://linux-hardware.org/?probe=78828b2790) | Oct 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [644553839a](https://linux-hardware.org/?probe=644553839a) | Oct 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [ee6fdf4608](https://linux-hardware.org/?probe=ee6fdf4608) | Oct 18, 2021 |
| ASUSTek       | K50C                        | [02e59a3759](https://linux-hardware.org/?probe=02e59a3759) | Oct 16, 2021 |
| ASUSTek       | K50C                        | [c47941a383](https://linux-hardware.org/?probe=c47941a383) | Oct 16, 2021 |
| HP            | Pavilion dv6                | [dbfa388218](https://linux-hardware.org/?probe=dbfa388218) | Oct 10, 2021 |
| HP            | 15                          | [6974f988e3](https://linux-hardware.org/?probe=6974f988e3) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [e54daea8f9](https://linux-hardware.org/?probe=e54daea8f9) | Oct 06, 2021 |
| Dell          | Studio XPS 1340             | [ed56dc2a85](https://linux-hardware.org/?probe=ed56dc2a85) | Oct 06, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [0540c800c7](https://linux-hardware.org/?probe=0540c800c7) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a508d7f60d](https://linux-hardware.org/?probe=a508d7f60d) | Oct 02, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [1e0f7c12ef](https://linux-hardware.org/?probe=1e0f7c12ef) | Oct 01, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [7efbe48343](https://linux-hardware.org/?probe=7efbe48343) | Oct 01, 2021 |
| Dell          | Latitude E6440              | [14a1218871](https://linux-hardware.org/?probe=14a1218871) | Sep 26, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [fd875fbe8c](https://linux-hardware.org/?probe=fd875fbe8c) | Sep 24, 2021 |
| Lenovo        | G580                        | [d7e35103d9](https://linux-hardware.org/?probe=d7e35103d9) | Sep 20, 2021 |
| HP            | Pavilion Notebook           | [835f183d57](https://linux-hardware.org/?probe=835f183d57) | Sep 17, 2021 |
| Toshiba       | Satellite C660              | [b2f55e8760](https://linux-hardware.org/?probe=b2f55e8760) | Sep 16, 2021 |
| Lenovo        | ThinkPad T450 20BV003SMS    | [352b2b53b8](https://linux-hardware.org/?probe=352b2b53b8) | Sep 14, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Dell          | Latitude 3510               | [797c9c49c9](https://linux-hardware.org/?probe=797c9c49c9) | Sep 02, 2021 |
| HP            | Pavilion dv6700             | [48ef40abbf](https://linux-hardware.org/?probe=48ef40abbf) | Sep 02, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [05d2b6e067](https://linux-hardware.org/?probe=05d2b6e067) | Sep 01, 2021 |
| Dell          | Latitude E5570              | [7e6202db9d](https://linux-hardware.org/?probe=7e6202db9d) | Aug 31, 2021 |
| Dell          | Latitude E5570              | [95667a8c8f](https://linux-hardware.org/?probe=95667a8c8f) | Aug 31, 2021 |
| HP            | EliteBook 745 G6            | [71e3489cd9](https://linux-hardware.org/?probe=71e3489cd9) | Aug 18, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| ASUSTek       | X51R                        | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Teclast       | F15S                        | [49f33bd674](https://linux-hardware.org/?probe=49f33bd674) | Jul 28, 2021 |
| ASUSTek       | N551JM                      | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| Dell          | Latitude E5470              | [f26e3c7b39](https://linux-hardware.org/?probe=f26e3c7b39) | Jul 26, 2021 |
| Timi          | TM1701                      | [2d44d6cccb](https://linux-hardware.org/?probe=2d44d6cccb) | Jul 23, 2021 |
| HP            | Presario CQ57               | [3726c1e8c4](https://linux-hardware.org/?probe=3726c1e8c4) | Jul 15, 2021 |
| HP            | Pavilion dv6                | [4ffd108654](https://linux-hardware.org/?probe=4ffd108654) | Jul 15, 2021 |
| Lenovo        | ThinkPad L560 20F10029MC    | [a96e4cc1a5](https://linux-hardware.org/?probe=a96e4cc1a5) | Jul 12, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [8ed58d00f1](https://linux-hardware.org/?probe=8ed58d00f1) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | [8d86cdfbad](https://linux-hardware.org/?probe=8d86cdfbad) | Jun 19, 2021 |
| Lenovo        | ThinkPad L540 20AUS0DW00    | [a3e83938c3](https://linux-hardware.org/?probe=a3e83938c3) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | [44b174fec2](https://linux-hardware.org/?probe=44b174fec2) | Jun 18, 2021 |
| Unknown       | Unknown                     | [001462994e](https://linux-hardware.org/?probe=001462994e) | Jun 18, 2021 |
| Unknown       | Unknown                     | [049e5221b4](https://linux-hardware.org/?probe=049e5221b4) | Jun 18, 2021 |
| HP            | Pavilion dv6700             | [56342fd485](https://linux-hardware.org/?probe=56342fd485) | Jun 17, 2021 |
| Dell          | Precision 7530              | [3e5d3c4292](https://linux-hardware.org/?probe=3e5d3c4292) | Jun 15, 2021 |
| Sony          | VPCEB3L1E                   | [9048edb5d2](https://linux-hardware.org/?probe=9048edb5d2) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | [93557b8c32](https://linux-hardware.org/?probe=93557b8c32) | Jun 13, 2021 |
| Sony          | VPCEB3L1E                   | [b90e553e8e](https://linux-hardware.org/?probe=b90e553e8e) | Jun 11, 2021 |
| Sony          | VPCEB3L1E                   | [bc3c3b537b](https://linux-hardware.org/?probe=bc3c3b537b) | Jun 06, 2021 |
| ASUSTek       | K54C                        | [dcdfadb154](https://linux-hardware.org/?probe=dcdfadb154) | May 31, 2021 |
| ASUSTek       | K54C                        | [252cf3ef89](https://linux-hardware.org/?probe=252cf3ef89) | May 31, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [07b30926e1](https://linux-hardware.org/?probe=07b30926e1) | May 29, 2021 |
| ASUSTek       | F3M                         | [05d9306fcc](https://linux-hardware.org/?probe=05d9306fcc) | May 28, 2021 |
| eMachines     | E725                        | [f573488bda](https://linux-hardware.org/?probe=f573488bda) | May 25, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [95b045c1a1](https://linux-hardware.org/?probe=95b045c1a1) | May 25, 2021 |
| ASUSTek       | X550CC                      | [26f506ff94](https://linux-hardware.org/?probe=26f506ff94) | May 23, 2021 |
| HP            | Unknown                     | [3584a13ae5](https://linux-hardware.org/?probe=3584a13ae5) | May 22, 2021 |
| HP            | Laptop 15-bw0xx             | [535d153c75](https://linux-hardware.org/?probe=535d153c75) | May 21, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [01af2920f0](https://linux-hardware.org/?probe=01af2920f0) | May 19, 2021 |
| Acer          | Nitro AN515-54              | [c8ac6c4b93](https://linux-hardware.org/?probe=c8ac6c4b93) | May 16, 2021 |
| Lenovo        | ThinkPad T490 20N20048GE    | [7c9dbf982e](https://linux-hardware.org/?probe=7c9dbf982e) | May 14, 2021 |
| Toshiba       | Satellite L735              | [177d534fdc](https://linux-hardware.org/?probe=177d534fdc) | May 11, 2021 |
| HP            | Pavilion dv6                | [63656472a4](https://linux-hardware.org/?probe=63656472a4) | May 10, 2021 |
| Toshiba       | Satellite L735              | [52e1221ae0](https://linux-hardware.org/?probe=52e1221ae0) | May 09, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| Dell          | Latitude 5401               | [660bb28d6a](https://linux-hardware.org/?probe=660bb28d6a) | May 04, 2021 |
| Lenovo        | ThinkPad X200T 7449FWG      | [2d8d1beca4](https://linux-hardware.org/?probe=2d8d1beca4) | May 03, 2021 |
| Lenovo        | V110-15IAP 80TG             | [d4307627a7](https://linux-hardware.org/?probe=d4307627a7) | May 01, 2021 |
| Dell          | Latitude 5520               | [d339546263](https://linux-hardware.org/?probe=d339546263) | Apr 30, 2021 |
| Acer          | Aspire 3690                 | [96bd8e49db](https://linux-hardware.org/?probe=96bd8e49db) | Apr 27, 2021 |
| Lenovo        | V110-15IAP 80TG             | [530bf24d20](https://linux-hardware.org/?probe=530bf24d20) | Apr 25, 2021 |
| ASUSTek       | X550CA                      | [103cc770c2](https://linux-hardware.org/?probe=103cc770c2) | Apr 18, 2021 |
| Dell          | System XPS L702X            | [6752a255ca](https://linux-hardware.org/?probe=6752a255ca) | Apr 18, 2021 |
| Dell          | System XPS L702X            | [20c39630ac](https://linux-hardware.org/?probe=20c39630ac) | Apr 18, 2021 |
| HP            | Pavilion 11 x360 PC         | [8aab148f59](https://linux-hardware.org/?probe=8aab148f59) | Apr 17, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [1b8f927465](https://linux-hardware.org/?probe=1b8f927465) | Apr 16, 2021 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | [7878f15fa6](https://linux-hardware.org/?probe=7878f15fa6) | Apr 15, 2021 |
| Dell          | Latitude 5490               | [bb7e4cf726](https://linux-hardware.org/?probe=bb7e4cf726) | Apr 13, 2021 |
| Sony          | VGN-FW31ZJ                  | [b1bc398f58](https://linux-hardware.org/?probe=b1bc398f58) | Apr 10, 2021 |
| HP            | EliteBook 840 G1            | [c6fc94dd62](https://linux-hardware.org/?probe=c6fc94dd62) | Apr 08, 2021 |
| Sony          | VGN-FW31ZJ                  | [9de66e685f](https://linux-hardware.org/?probe=9de66e685f) | Apr 05, 2021 |
| HP            | ProBook 650 G1              | [051017604f](https://linux-hardware.org/?probe=051017604f) | Apr 04, 2021 |
| Dell          | Latitude E6400              | [f4e375c3e4](https://linux-hardware.org/?probe=f4e375c3e4) | Apr 01, 2021 |
| Dell          | Latitude E5440              | [757746e097](https://linux-hardware.org/?probe=757746e097) | Apr 01, 2021 |
| ASUSTek       | X550CL                      | [72ec76771c](https://linux-hardware.org/?probe=72ec76771c) | Mar 24, 2021 |
| Toshiba       | Satellite C850-13Z          | [f8b44b58ee](https://linux-hardware.org/?probe=f8b44b58ee) | Mar 21, 2021 |
| ASUSTek       | X550CC                      | [67ef60c8b1](https://linux-hardware.org/?probe=67ef60c8b1) | Mar 20, 2021 |
| HP            | Pavilion dv5                | [f84bed8734](https://linux-hardware.org/?probe=f84bed8734) | Mar 19, 2021 |
| ASUSTek       | X550CC                      | [2f2bf700ae](https://linux-hardware.org/?probe=2f2bf700ae) | Mar 18, 2021 |
| ASUSTek       | X550CC                      | [0f7e04c439](https://linux-hardware.org/?probe=0f7e04c439) | Mar 17, 2021 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [60ad7c7aec](https://linux-hardware.org/?probe=60ad7c7aec) | Mar 17, 2021 |
| Dell          | Latitude 3510               | [24bc2a77b2](https://linux-hardware.org/?probe=24bc2a77b2) | Mar 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [fbebe98252](https://linux-hardware.org/?probe=fbebe98252) | Mar 13, 2021 |
| HP            | Pavilion dv6500             | [4aae1e6d26](https://linux-hardware.org/?probe=4aae1e6d26) | Mar 11, 2021 |
| HP            | Laptop 15-db1xxx            | [3d4aacd619](https://linux-hardware.org/?probe=3d4aacd619) | Mar 05, 2021 |
| HP            | Pavilion dv6                | [c26d9748f4](https://linux-hardware.org/?probe=c26d9748f4) | Mar 05, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [aedc60a146](https://linux-hardware.org/?probe=aedc60a146) | Mar 04, 2021 |
| Lenovo        | ThinkPad SL 2746AEG         | [4591f5d5af](https://linux-hardware.org/?probe=4591f5d5af) | Mar 03, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | [5f75eafa25](https://linux-hardware.org/?probe=5f75eafa25) | Feb 28, 2021 |
| Google        | Gnawty                      | [252bc4cb46](https://linux-hardware.org/?probe=252bc4cb46) | Feb 25, 2021 |
| Dell          | Inspiron 5559               | [eca76d9f64](https://linux-hardware.org/?probe=eca76d9f64) | Feb 25, 2021 |
| Dell          | Latitude D430               | [63906404d0](https://linux-hardware.org/?probe=63906404d0) | Feb 25, 2021 |
| ASUSTek       | X101CH                      | [7897616bb0](https://linux-hardware.org/?probe=7897616bb0) | Feb 25, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [b91a419a64](https://linux-hardware.org/?probe=b91a419a64) | Feb 25, 2021 |
| ASUSTek       | X200CA                      | [2817beb96d](https://linux-hardware.org/?probe=2817beb96d) | Feb 25, 2021 |
| Dell          | Latitude 3510               | [8a6676e538](https://linux-hardware.org/?probe=8a6676e538) | Feb 25, 2021 |
| Acer          | Extensa 5235                | [48868a0c5e](https://linux-hardware.org/?probe=48868a0c5e) | Feb 24, 2021 |
| ASUSTek       | K52F                        | [1492b277a3](https://linux-hardware.org/?probe=1492b277a3) | Feb 24, 2021 |
| ASUSTek       | K52F                        | [0369d16c88](https://linux-hardware.org/?probe=0369d16c88) | Feb 24, 2021 |
| Lenovo        | ThinkPad T540p 20BFS14A0... | [3103f52c54](https://linux-hardware.org/?probe=3103f52c54) | Feb 24, 2021 |
| Dell          | Inspiron 5559               | [08723d28a4](https://linux-hardware.org/?probe=08723d28a4) | Feb 24, 2021 |
| HP            | Pavilion g6                 | [f23e85a87a](https://linux-hardware.org/?probe=f23e85a87a) | Feb 23, 2021 |
| Google        | Gnawty                      | [7614a9a19c](https://linux-hardware.org/?probe=7614a9a19c) | Feb 23, 2021 |
| eMachines     | eM350                       | [7826551972](https://linux-hardware.org/?probe=7826551972) | Feb 20, 2021 |
| Dell          | Inspiron 5559               | [cc6c16c095](https://linux-hardware.org/?probe=cc6c16c095) | Feb 19, 2021 |
| Dell          | Inspiron 7559               | [4d4377253f](https://linux-hardware.org/?probe=4d4377253f) | Feb 15, 2021 |
| Lenovo        | IdeaPad Z460 20059          | [b0b1eb3196](https://linux-hardware.org/?probe=b0b1eb3196) | Feb 14, 2021 |
| Lenovo        | IdeaPad Z460 20059          | [68fdda8114](https://linux-hardware.org/?probe=68fdda8114) | Feb 14, 2021 |
| Dell          | Inspiron 5559               | [4f0639f7c9](https://linux-hardware.org/?probe=4f0639f7c9) | Feb 10, 2021 |
| Dell          | Inspiron 5559               | [e3d953f88d](https://linux-hardware.org/?probe=e3d953f88d) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | [9d9da95c79](https://linux-hardware.org/?probe=9d9da95c79) | Feb 10, 2021 |
| Dell          | XPS 13 7390                 | [4b6ec0748c](https://linux-hardware.org/?probe=4b6ec0748c) | Feb 10, 2021 |
| Lenovo        | G500 20236                  | [bef7d62361](https://linux-hardware.org/?probe=bef7d62361) | Feb 03, 2021 |
| Dell          | Latitude D620               | [8f4c2819b9](https://linux-hardware.org/?probe=8f4c2819b9) | Feb 01, 2021 |
| HP            | ProBook 4545s               | [9c55ad844b](https://linux-hardware.org/?probe=9c55ad844b) | Jan 28, 2021 |
| HP            | Laptop 15-db1xxx            | [b38aa1a092](https://linux-hardware.org/?probe=b38aa1a092) | Jan 25, 2021 |
| HP            | Laptop 15-db1xxx            | [7a321f0327](https://linux-hardware.org/?probe=7a321f0327) | Jan 25, 2021 |
| HP            | Presario CQ57               | [7dcbdb9d0d](https://linux-hardware.org/?probe=7dcbdb9d0d) | Jan 25, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | [1469bc5f96](https://linux-hardware.org/?probe=1469bc5f96) | Jan 21, 2021 |
| Toshiba       | Satellite L850-1HP          | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Lenovo        | IdeaPad 120S-14IAP          | [ce71ff03d7](https://linux-hardware.org/?probe=ce71ff03d7) | Jan 16, 2021 |
| HP            | Pavilion g6                 | [c4b4831246](https://linux-hardware.org/?probe=c4b4831246) | Jan 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [989e87e18e](https://linux-hardware.org/?probe=989e87e18e) | Jan 15, 2021 |
| ASUSTek       | X101CH                      | [3dfb714393](https://linux-hardware.org/?probe=3dfb714393) | Jan 15, 2021 |
| Google        | Gnawty                      | [b110360fd0](https://linux-hardware.org/?probe=b110360fd0) | Jan 15, 2021 |
| MSI           | CR500                       | [ff982a100f](https://linux-hardware.org/?probe=ff982a100f) | Jan 14, 2021 |
| MSI           | CR500                       | [509fd7cfd1](https://linux-hardware.org/?probe=509fd7cfd1) | Jan 14, 2021 |
| Dell          | Latitude D430               | [874d8f3925](https://linux-hardware.org/?probe=874d8f3925) | Jan 14, 2021 |
| ASUSTek       | X556UQK                     | [f70c845b60](https://linux-hardware.org/?probe=f70c845b60) | Jan 13, 2021 |
| HP            | ProBook 455 G6              | [da3110fdce](https://linux-hardware.org/?probe=da3110fdce) | Jan 11, 2021 |
| ASUSTek       | X550CC                      | [95a034c1f0](https://linux-hardware.org/?probe=95a034c1f0) | Jan 10, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [77af1025e7](https://linux-hardware.org/?probe=77af1025e7) | Jan 08, 2021 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [f3d55068a4](https://linux-hardware.org/?probe=f3d55068a4) | Jan 06, 2021 |
| HP            | EliteBook 8730w (VQ683EA... | [9650848634](https://linux-hardware.org/?probe=9650848634) | Jan 05, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [70b6c077a6](https://linux-hardware.org/?probe=70b6c077a6) | Jan 05, 2021 |
| Acer          | Swift sf514-54t             | [f56b772338](https://linux-hardware.org/?probe=f56b772338) | Jan 05, 2021 |
| HP            | ProBook 4540s               | [03c94ff635](https://linux-hardware.org/?probe=03c94ff635) | Jan 04, 2021 |
| HP            | ProBook 4540s               | [eb99a077b0](https://linux-hardware.org/?probe=eb99a077b0) | Jan 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [caa3d1d91f](https://linux-hardware.org/?probe=caa3d1d91f) | Jan 03, 2021 |
| MSI           | MS-163B Ver                 | [2406d3e9a2](https://linux-hardware.org/?probe=2406d3e9a2) | Jan 02, 2021 |
| Acer          | Aspire A515-51G             | [0440c76ce6](https://linux-hardware.org/?probe=0440c76ce6) | Jan 01, 2021 |
| MSI           | MS-163B Ver                 | [d3f6e8b5b6](https://linux-hardware.org/?probe=d3f6e8b5b6) | Dec 30, 2020 |
| Acer          | Extensa 5635G               | [a089e8fb2a](https://linux-hardware.org/?probe=a089e8fb2a) | Dec 27, 2020 |
| HP            | ProBook 450 G5              | [183d05951e](https://linux-hardware.org/?probe=183d05951e) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [bab0eb442f](https://linux-hardware.org/?probe=bab0eb442f) | Dec 22, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [e59a36ff39](https://linux-hardware.org/?probe=e59a36ff39) | Dec 22, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [d239275c54](https://linux-hardware.org/?probe=d239275c54) | Dec 21, 2020 |
| Lenovo        | IdeaPad U260 20067          | [f8b68b1481](https://linux-hardware.org/?probe=f8b68b1481) | Dec 19, 2020 |
| ASUSTek       | X200MA                      | [662934e08a](https://linux-hardware.org/?probe=662934e08a) | Dec 18, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | [a30ab2cb96](https://linux-hardware.org/?probe=a30ab2cb96) | Dec 16, 2020 |
| Fujitsu       | CELSIUS H760                | [bf6b408b8a](https://linux-hardware.org/?probe=bf6b408b8a) | Dec 15, 2020 |
| Toshiba       | Satellite P300              | [207e6367f2](https://linux-hardware.org/?probe=207e6367f2) | Dec 13, 2020 |
| Toshiba       | Satellite P300              | [3c0a54f9df](https://linux-hardware.org/?probe=3c0a54f9df) | Dec 11, 2020 |
| HP            | ProBook 4330s               | [22a64b85be](https://linux-hardware.org/?probe=22a64b85be) | Dec 06, 2020 |
| Dell          | Precision 7530              | [0d9da6571f](https://linux-hardware.org/?probe=0d9da6571f) | Dec 04, 2020 |
| HP            | ProBook 4330s               | [d7d25ffae4](https://linux-hardware.org/?probe=d7d25ffae4) | Dec 03, 2020 |
| Dell          | Precision 7530              | [2ea7f280b2](https://linux-hardware.org/?probe=2ea7f280b2) | Dec 02, 2020 |
| Acer          | Aspire 5742G                | [c17b4a5c87](https://linux-hardware.org/?probe=c17b4a5c87) | Nov 29, 2020 |
| ASUSTek       | ROG Zephyrus S17 GX701LW... | [f0b41bab99](https://linux-hardware.org/?probe=f0b41bab99) | Nov 28, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [e89b91cab1](https://linux-hardware.org/?probe=e89b91cab1) | Nov 25, 2020 |
| Dell          | Vostro 5370                 | [653a970a7e](https://linux-hardware.org/?probe=653a970a7e) | Nov 22, 2020 |
| ASUSTek       | X550CC                      | [0d8cea2372](https://linux-hardware.org/?probe=0d8cea2372) | Nov 21, 2020 |
| HP            | Presario CQ57               | [43ffcec233](https://linux-hardware.org/?probe=43ffcec233) | Nov 18, 2020 |
| HP            | Presario CQ57               | [ff87b0c6d6](https://linux-hardware.org/?probe=ff87b0c6d6) | Nov 16, 2020 |
| HP            | ProBook 4330s               | [c9597f3a0d](https://linux-hardware.org/?probe=c9597f3a0d) | Nov 15, 2020 |
| Acer          | Swift SF315-41              | [43d05784be](https://linux-hardware.org/?probe=43d05784be) | Nov 12, 2020 |
| Dell          | Latitude E6540              | [33d4c9409a](https://linux-hardware.org/?probe=33d4c9409a) | Nov 11, 2020 |
| Lenovo        | G780                        | [145d3ccb54](https://linux-hardware.org/?probe=145d3ccb54) | Nov 08, 2020 |
| Lenovo        | G780                        | [56faed1607](https://linux-hardware.org/?probe=56faed1607) | Nov 06, 2020 |
| Dell          | Latitude 5411               | [e880b200a0](https://linux-hardware.org/?probe=e880b200a0) | Nov 06, 2020 |
| ASUSTek       | K75VJ                       | [aa4d1aabd8](https://linux-hardware.org/?probe=aa4d1aabd8) | Nov 03, 2020 |
| MSI           | EX705                       | [4307aff155](https://linux-hardware.org/?probe=4307aff155) | Nov 02, 2020 |
| MSI           | EX705                       | [c93a29a4ec](https://linux-hardware.org/?probe=c93a29a4ec) | Nov 02, 2020 |
| HP            | 15                          | [8d582da744](https://linux-hardware.org/?probe=8d582da744) | Nov 01, 2020 |
| HP            | 15                          | [0f0be86a64](https://linux-hardware.org/?probe=0f0be86a64) | Nov 01, 2020 |
| ASUSTek       | F5GL                        | [03675a2262](https://linux-hardware.org/?probe=03675a2262) | Oct 31, 2020 |
| Packard Be... | EasyNote TK85               | [544a018464](https://linux-hardware.org/?probe=544a018464) | Oct 30, 2020 |
| Dell          | G7 7790                     | [7dd8ac2676](https://linux-hardware.org/?probe=7dd8ac2676) | Oct 30, 2020 |
| ASUSTek       | UX32VD                      | [6c9095c4b8](https://linux-hardware.org/?probe=6c9095c4b8) | Oct 30, 2020 |
| Packard Be... | EasyNote TK85               | [0d1db60c39](https://linux-hardware.org/?probe=0d1db60c39) | Oct 24, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | [782fe456b2](https://linux-hardware.org/?probe=782fe456b2) | Oct 16, 2020 |
| Lenovo        | ThinkPad T480 20L50006XS    | [51a31505c0](https://linux-hardware.org/?probe=51a31505c0) | Oct 16, 2020 |
| HP            | Presario CQ57               | [d2883f7a48](https://linux-hardware.org/?probe=d2883f7a48) | Oct 14, 2020 |
| HP            | Presario CQ57               | [3646e51370](https://linux-hardware.org/?probe=3646e51370) | Oct 13, 2020 |
| HP            | ProBook 4540s               | [095196f795](https://linux-hardware.org/?probe=095196f795) | Oct 09, 2020 |
| HP            | ProBook 4540s               | [0272418c87](https://linux-hardware.org/?probe=0272418c87) | Oct 09, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dd1a01df40](https://linux-hardware.org/?probe=dd1a01df40) | Oct 09, 2020 |
| HP            | EliteBook 8470p             | [51aeeb5a22](https://linux-hardware.org/?probe=51aeeb5a22) | Oct 07, 2020 |
| HP            | EliteBook 8470p             | [6bd0eacb71](https://linux-hardware.org/?probe=6bd0eacb71) | Oct 07, 2020 |
| Toshiba       | Satellite P770              | [9a6b14ab65](https://linux-hardware.org/?probe=9a6b14ab65) | Oct 07, 2020 |
| Fujitsu Si... | LIFEBOOK S6420              | [cea718db3d](https://linux-hardware.org/?probe=cea718db3d) | Sep 30, 2020 |
| Dell          | XPS 13 9380                 | [1bcd88fae1](https://linux-hardware.org/?probe=1bcd88fae1) | Sep 30, 2020 |
| HP            | ProBook 6570b               | [c36d7a3815](https://linux-hardware.org/?probe=c36d7a3815) | Sep 27, 2020 |
| Lenovo        | ThinkPad T460s 20F9003SG... | [5ee1f4ba42](https://linux-hardware.org/?probe=5ee1f4ba42) | Sep 21, 2020 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [25a18b6913](https://linux-hardware.org/?probe=25a18b6913) | Sep 20, 2020 |
| Lenovo        | IdeaPad U260 20067          | [c7ee126272](https://linux-hardware.org/?probe=c7ee126272) | Sep 18, 2020 |
| Lenovo        | G710 20252                  | [bda90e6285](https://linux-hardware.org/?probe=bda90e6285) | Sep 16, 2020 |
| MSI           | Prestige 15 A10SC           | [f9c109d38a](https://linux-hardware.org/?probe=f9c109d38a) | Sep 14, 2020 |
| Lenovo        | B590 20206                  | [241a96fabe](https://linux-hardware.org/?probe=241a96fabe) | Sep 13, 2020 |
| Lenovo        | B590 20206                  | [68c8013cac](https://linux-hardware.org/?probe=68c8013cac) | Sep 13, 2020 |
| ASUSTek       | X550CC                      | [c28899f07f](https://linux-hardware.org/?probe=c28899f07f) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | [3a6d68dfe1](https://linux-hardware.org/?probe=3a6d68dfe1) | Sep 10, 2020 |
| ASUSTek       | X550CC                      | [654281ba17](https://linux-hardware.org/?probe=654281ba17) | Sep 02, 2020 |
| Dell          | Inspiron 7577               | [9243047fd5](https://linux-hardware.org/?probe=9243047fd5) | Aug 30, 2020 |
| ASUSTek       | X550CC                      | [92266759e0](https://linux-hardware.org/?probe=92266759e0) | Aug 29, 2020 |
| ASUSTek       | X550CC                      | [93baa51bda](https://linux-hardware.org/?probe=93baa51bda) | Aug 29, 2020 |
| Acer          | Swift SF314-58              | [3aa1021468](https://linux-hardware.org/?probe=3aa1021468) | Aug 28, 2020 |
| Toshiba       | Satellite C855-1TT          | [7a5dc01f13](https://linux-hardware.org/?probe=7a5dc01f13) | Aug 22, 2020 |
| Toshiba       | Satellite C855-1TT          | [98b59c7ddf](https://linux-hardware.org/?probe=98b59c7ddf) | Aug 21, 2020 |
| Lenovo        | G580                        | [e6435f1530](https://linux-hardware.org/?probe=e6435f1530) | Aug 13, 2020 |
| Sony          | VPCEH1S1E                   | [10c3c1d9d0](https://linux-hardware.org/?probe=10c3c1d9d0) | Aug 13, 2020 |
| MSI           | CR500                       | [6b04b72ba8](https://linux-hardware.org/?probe=6b04b72ba8) | Aug 06, 2020 |
| Lenovo        | ThinkPad T61 7659AB7        | [371a42eb7e](https://linux-hardware.org/?probe=371a42eb7e) | Jul 26, 2020 |
| Acer          | Aspire ES1-523              | [030cf77080](https://linux-hardware.org/?probe=030cf77080) | Jul 20, 2020 |
| Acer          | Aspire ES1-523              | [4d9339959a](https://linux-hardware.org/?probe=4d9339959a) | Jul 20, 2020 |
| HP            | Presario CQ57               | [680685ed32](https://linux-hardware.org/?probe=680685ed32) | Jul 19, 2020 |
| Dell          | Vostro 5370                 | [f8487e0c66](https://linux-hardware.org/?probe=f8487e0c66) | Jul 13, 2020 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [51d0966405](https://linux-hardware.org/?probe=51d0966405) | Jul 07, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| Fujitsu       | LIFEBOOK U904               | [57ca2c447b](https://linux-hardware.org/?probe=57ca2c447b) | Jul 06, 2020 |
| Lenovo        | IdeaPad Z500 20202          | [dc66cb5caf](https://linux-hardware.org/?probe=dc66cb5caf) | Jun 25, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [a50a75e674](https://linux-hardware.org/?probe=a50a75e674) | Jun 21, 2020 |
| HP            | ProBook 6570b               | [f2370339d5](https://linux-hardware.org/?probe=f2370339d5) | Jun 21, 2020 |
| HP            | ProBook 6570b               | [c477dc5d5b](https://linux-hardware.org/?probe=c477dc5d5b) | Jun 18, 2020 |
| HP            | ProBook 6570b               | [d1f562df2f](https://linux-hardware.org/?probe=d1f562df2f) | Jun 18, 2020 |
| Sony          | VPCEH1L8E                   | [3b8814bf8e](https://linux-hardware.org/?probe=3b8814bf8e) | Jun 15, 2020 |
| Acer          | Aspire 5100                 | [481320cdb6](https://linux-hardware.org/?probe=481320cdb6) | Jun 09, 2020 |
| Acer          | Aspire 5100                 | [0e89938085](https://linux-hardware.org/?probe=0e89938085) | Jun 09, 2020 |
| ASUSTek       | X550CC                      | [d832045294](https://linux-hardware.org/?probe=d832045294) | Jun 06, 2020 |
| Lenovo        | ThinkPad Edge E220s 5038... | [e37f8c0d24](https://linux-hardware.org/?probe=e37f8c0d24) | Jun 05, 2020 |
| Lenovo        | IdeaPad 300-17ISK 80QH      | [a570720ce6](https://linux-hardware.org/?probe=a570720ce6) | May 26, 2020 |
| ASUSTek       | X550CC                      | [82c8b62b02](https://linux-hardware.org/?probe=82c8b62b02) | May 24, 2020 |
| ASUSTek       | X550CC                      | [8ebd135c78](https://linux-hardware.org/?probe=8ebd135c78) | May 23, 2020 |
| HP            | EliteBook 745 G3            | [1d082fe95a](https://linux-hardware.org/?probe=1d082fe95a) | May 14, 2020 |
| Lenovo        | IdeaPad 720S-15IKB 81AC     | [b8dfa98b13](https://linux-hardware.org/?probe=b8dfa98b13) | May 10, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [31d9941f79](https://linux-hardware.org/?probe=31d9941f79) | May 05, 2020 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [ddfe727f57](https://linux-hardware.org/?probe=ddfe727f57) | May 04, 2020 |
| HP            | EliteBook 850 G5            | [3e455caa1a](https://linux-hardware.org/?probe=3e455caa1a) | Apr 25, 2020 |
| HP            | Presario CQ57               | [0ba9cb0077](https://linux-hardware.org/?probe=0ba9cb0077) | Apr 25, 2020 |
| Acer          | Swift SF314-41              | [00dcbaa8f0](https://linux-hardware.org/?probe=00dcbaa8f0) | Apr 24, 2020 |
| Lenovo        | Z710 20250                  | [cf3d4e04cc](https://linux-hardware.org/?probe=cf3d4e04cc) | Apr 19, 2020 |
| ASUSTek       | T100TA                      | [ba03f5b5dd](https://linux-hardware.org/?probe=ba03f5b5dd) | Apr 19, 2020 |
| Dell          | Latitude E6540              | [0a2c664d30](https://linux-hardware.org/?probe=0a2c664d30) | Apr 19, 2020 |
| Lenovo        | B51-80 80LM                 | [b54cb44723](https://linux-hardware.org/?probe=b54cb44723) | Apr 17, 2020 |
| HP            | EliteBook 2760p             | [6631b4c0f1](https://linux-hardware.org/?probe=6631b4c0f1) | Apr 17, 2020 |
| HP            | Presario CQ57               | [9e1ad378a1](https://linux-hardware.org/?probe=9e1ad378a1) | Apr 13, 2020 |
| Lenovo        | B51-80 80LM                 | [054456ab1e](https://linux-hardware.org/?probe=054456ab1e) | Apr 12, 2020 |
| Dell          | Latitude E6540              | [1daf9c5f1a](https://linux-hardware.org/?probe=1daf9c5f1a) | Apr 10, 2020 |
| HP            | ProBook 450 G4              | [9c62a9edc6](https://linux-hardware.org/?probe=9c62a9edc6) | Apr 09, 2020 |
| Lenovo        | ThinkPad Edge E531 6885B... | [9dd9a20b65](https://linux-hardware.org/?probe=9dd9a20b65) | Apr 05, 2020 |
| Toshiba       | Satellite L450              | [b18b01a081](https://linux-hardware.org/?probe=b18b01a081) | Apr 04, 2020 |
| Lenovo        | Z710 20250                  | [0f9b8a8fc0](https://linux-hardware.org/?probe=0f9b8a8fc0) | Mar 31, 2020 |
| HP            | EliteBook 850 G6            | [f638a70ec4](https://linux-hardware.org/?probe=f638a70ec4) | Mar 30, 2020 |
| HP            | 530 Notebook PC(KD080AA#... | [aec394a418](https://linux-hardware.org/?probe=aec394a418) | Mar 27, 2020 |
| Packard Be... | EasyNote TE11BZ             | [5aaa403dee](https://linux-hardware.org/?probe=5aaa403dee) | Mar 26, 2020 |
| ASUSTek       | A6Km                        | [2c47a900f8](https://linux-hardware.org/?probe=2c47a900f8) | Mar 25, 2020 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [3f0773955d](https://linux-hardware.org/?probe=3f0773955d) | Mar 25, 2020 |
| ASUSTek       | A6Km                        | [3183eb860e](https://linux-hardware.org/?probe=3183eb860e) | Mar 24, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [56566f3fbb](https://linux-hardware.org/?probe=56566f3fbb) | Mar 23, 2020 |
| Toshiba       | Satellite P300              | [e51afe4271](https://linux-hardware.org/?probe=e51afe4271) | Mar 23, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [d5242f2534](https://linux-hardware.org/?probe=d5242f2534) | Mar 15, 2020 |
| ASUSTek       | X51L                        | [3ce2f3c47e](https://linux-hardware.org/?probe=3ce2f3c47e) | Mar 11, 2020 |
| Lenovo        | 3000 V100 07635CG           | [8c9c933a22](https://linux-hardware.org/?probe=8c9c933a22) | Mar 07, 2020 |
| Dell          | Latitude 5490               | [ab3da12d55](https://linux-hardware.org/?probe=ab3da12d55) | Feb 22, 2020 |
| Dell          | Latitude 5490               | [6b43e4ae7f](https://linux-hardware.org/?probe=6b43e4ae7f) | Feb 22, 2020 |
| ASUSTek       | F3Ke                        | [f1eaad7ea4](https://linux-hardware.org/?probe=f1eaad7ea4) | Feb 22, 2020 |
| Toshiba       | Satellite P300              | [f4642d40d8](https://linux-hardware.org/?probe=f4642d40d8) | Feb 11, 2020 |
| Google        | Gnawty                      | [4a2e211ce1](https://linux-hardware.org/?probe=4a2e211ce1) | Feb 08, 2020 |
| Toshiba       | EQUIUM A300D                | [f77888b435](https://linux-hardware.org/?probe=f77888b435) | Feb 07, 2020 |
| HP            | 635                         | [e1ed2f20e6](https://linux-hardware.org/?probe=e1ed2f20e6) | Feb 07, 2020 |
| HP            | 635                         | [0dbde497ec](https://linux-hardware.org/?probe=0dbde497ec) | Feb 06, 2020 |
| HP            | 635                         | [17396458ac](https://linux-hardware.org/?probe=17396458ac) | Feb 06, 2020 |
| HP            | 635                         | [2b47dfbcac](https://linux-hardware.org/?probe=2b47dfbcac) | Feb 06, 2020 |
| HP            | 635                         | [d980853d87](https://linux-hardware.org/?probe=d980853d87) | Feb 06, 2020 |
| HP            | 250 G3                      | [bdaa75d7d9](https://linux-hardware.org/?probe=bdaa75d7d9) | Feb 04, 2020 |
| HP            | 250 G3                      | [1a62acba2c](https://linux-hardware.org/?probe=1a62acba2c) | Feb 04, 2020 |
| HP            | ProBook 650 G1              | [897b50b880](https://linux-hardware.org/?probe=897b50b880) | Feb 03, 2020 |
| Lenovo        | ThinkPad T490 20N2S2UH00    | [693c5998b1](https://linux-hardware.org/?probe=693c5998b1) | Jan 31, 2020 |
| Timi          | TM1701                      | [921a36a46c](https://linux-hardware.org/?probe=921a36a46c) | Jan 31, 2020 |
| HP            | Pavilion Notebook           | [b677c3926c](https://linux-hardware.org/?probe=b677c3926c) | Jan 29, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e5af1f2975](https://linux-hardware.org/?probe=e5af1f2975) | Jan 27, 2020 |
| Toshiba       | Satellite C50-A             | [fb518d95db](https://linux-hardware.org/?probe=fb518d95db) | Jan 27, 2020 |
| Toshiba       | Satellite C50-A             | [a4a37c8c40](https://linux-hardware.org/?probe=a4a37c8c40) | Jan 27, 2020 |
| Dell          | Latitude E5470              | [6fb212c97d](https://linux-hardware.org/?probe=6fb212c97d) | Jan 24, 2020 |
| Dell          | Vostro 3700                 | [bb0ea1ffd5](https://linux-hardware.org/?probe=bb0ea1ffd5) | Jan 19, 2020 |
| Acer          | Aspire 3610                 | [93dae491f3](https://linux-hardware.org/?probe=93dae491f3) | Jan 18, 2020 |
| Acer          | Aspire 3610                 | [33bbdb19d0](https://linux-hardware.org/?probe=33bbdb19d0) | Jan 18, 2020 |
| ASUSTek       | N73SV                       | [bafe93eacb](https://linux-hardware.org/?probe=bafe93eacb) | Jan 15, 2020 |
| Dell          | XPS M1530                   | [8ab2f0c35b](https://linux-hardware.org/?probe=8ab2f0c35b) | Jan 05, 2020 |
| ASUSTek       | K50IJ                       | [78b35a3d1d](https://linux-hardware.org/?probe=78b35a3d1d) | Jan 05, 2020 |
| Dell          | Vostro V130                 | [aae8826349](https://linux-hardware.org/?probe=aae8826349) | Jan 03, 2020 |
| Lenovo        | G575 20081                  | [bfd443284d](https://linux-hardware.org/?probe=bfd443284d) | Jan 01, 2020 |
| Lenovo        | G575 20081                  | [ec00d77a1a](https://linux-hardware.org/?probe=ec00d77a1a) | Jan 01, 2020 |
| Dell          | Studio 1535                 | [67d4b75167](https://linux-hardware.org/?probe=67d4b75167) | Dec 29, 2019 |
| Lenovo        | Z710 20250                  | [9ddb10548b](https://linux-hardware.org/?probe=9ddb10548b) | Dec 27, 2019 |
| Acer          | Extensa 5620                | [ba9eff4f3b](https://linux-hardware.org/?probe=ba9eff4f3b) | Dec 26, 2019 |
| Toshiba       | Satellite Pro C660          | [a36fc6a447](https://linux-hardware.org/?probe=a36fc6a447) | Dec 26, 2019 |
| Toshiba       | Satellite P300              | [6108b0c47e](https://linux-hardware.org/?probe=6108b0c47e) | Dec 25, 2019 |
| Google        | Gnawty                      | [2332ed0dd8](https://linux-hardware.org/?probe=2332ed0dd8) | Dec 23, 2019 |
| HP            | Pavilion g6                 | [9c722b6763](https://linux-hardware.org/?probe=9c722b6763) | Dec 21, 2019 |
| Acer          | Aspire 3610                 | [77353d6c03](https://linux-hardware.org/?probe=77353d6c03) | Dec 14, 2019 |
| Sony          | VPCEE2M1E                   | [9afef9e3e5](https://linux-hardware.org/?probe=9afef9e3e5) | Nov 24, 2019 |
| Sony          | SVE1713F1EW                 | [a1de0ea6f8](https://linux-hardware.org/?probe=a1de0ea6f8) | Nov 24, 2019 |
| Acer          | Crane II                    | [50122b9e8e](https://linux-hardware.org/?probe=50122b9e8e) | Nov 22, 2019 |
| Lenovo        | IdeaPad U260 20067          | [f592337622](https://linux-hardware.org/?probe=f592337622) | Nov 17, 2019 |
| eMachines     | E627                        | [874a5386c1](https://linux-hardware.org/?probe=874a5386c1) | Nov 16, 2019 |
| Medion        | E6435 MD60939               | [012a12549f](https://linux-hardware.org/?probe=012a12549f) | Nov 13, 2019 |
| eMachines     | E627                        | [55ba59c740](https://linux-hardware.org/?probe=55ba59c740) | Nov 13, 2019 |
| eMachines     | E627                        | [f984c92be5](https://linux-hardware.org/?probe=f984c92be5) | Nov 09, 2019 |
| Acer          | Crane II                    | [eba60f8297](https://linux-hardware.org/?probe=eba60f8297) | Nov 08, 2019 |
| Acer          | Crane II                    | [6c2e93de66](https://linux-hardware.org/?probe=6c2e93de66) | Nov 08, 2019 |
| eMachines     | E627                        | [0b1acfd5a2](https://linux-hardware.org/?probe=0b1acfd5a2) | Nov 06, 2019 |
| Dell          | Vostro 3700                 | [dc6f95878c](https://linux-hardware.org/?probe=dc6f95878c) | Nov 05, 2019 |
| Lenovo        | ThinkPad X230 2324HZ9       | [faddcc4f2b](https://linux-hardware.org/?probe=faddcc4f2b) | Nov 04, 2019 |
| HP            | Pavilion dv7                | [ff9ced6ef0](https://linux-hardware.org/?probe=ff9ced6ef0) | Nov 04, 2019 |
| ASUSTek       | X101CH                      | [b17de4dbad](https://linux-hardware.org/?probe=b17de4dbad) | Nov 04, 2019 |
| HP            | Notebook                    | [df94931018](https://linux-hardware.org/?probe=df94931018) | Nov 03, 2019 |
| HP            | Notebook                    | [cd5f971a86](https://linux-hardware.org/?probe=cd5f971a86) | Nov 03, 2019 |
| Lenovo        | IdeaPad Y560                | [6ca3597271](https://linux-hardware.org/?probe=6ca3597271) | Nov 03, 2019 |
| HP            | Pavilion g6                 | [2cb09606ed](https://linux-hardware.org/?probe=2cb09606ed) | Nov 01, 2019 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | [cb80682975](https://linux-hardware.org/?probe=cb80682975) | Oct 20, 2019 |
| HP            | Pavilion g6                 | [6bde777445](https://linux-hardware.org/?probe=6bde777445) | Oct 20, 2019 |
| Google        | Gnawty                      | [c0b7f226f9](https://linux-hardware.org/?probe=c0b7f226f9) | Oct 20, 2019 |
| Dell          | Vostro 5370                 | [f2c990d6ba](https://linux-hardware.org/?probe=f2c990d6ba) | Oct 12, 2019 |
| Lenovo        | ThinkPad X220 42914BG       | [edfe201446](https://linux-hardware.org/?probe=edfe201446) | Oct 08, 2019 |
| Acer          | Aspire V5-531G              | [396cfb8284](https://linux-hardware.org/?probe=396cfb8284) | Oct 06, 2019 |
| ASUSTek       | X505BA                      | [85cb3c5515](https://linux-hardware.org/?probe=85cb3c5515) | Oct 05, 2019 |
| Lenovo        | ThinkPad X200 Tablet 745... | [fb6e962768](https://linux-hardware.org/?probe=fb6e962768) | Sep 27, 2019 |
| Lenovo        | ThinkPad T430 2349U2B       | [b6b8e23a2d](https://linux-hardware.org/?probe=b6b8e23a2d) | Sep 15, 2019 |
| Lenovo        | ThinkPad T430 2349U2B       | [72825d26f3](https://linux-hardware.org/?probe=72825d26f3) | Sep 15, 2019 |
| ASUSTek       | 1000H                       | [7d83011877](https://linux-hardware.org/?probe=7d83011877) | Aug 31, 2019 |
| ASUSTek       | B400VC                      | [3f5a088240](https://linux-hardware.org/?probe=3f5a088240) | Aug 29, 2019 |
| Sony          | SVE1713F1EW                 | [d5c33713cb](https://linux-hardware.org/?probe=d5c33713cb) | Aug 22, 2019 |
| Sony          | SVE1713F1EW                 | [2aa9a3f6a0](https://linux-hardware.org/?probe=2aa9a3f6a0) | Aug 20, 2019 |
| ASUSTek       | K52Jc                       | [4570331fe2](https://linux-hardware.org/?probe=4570331fe2) | Aug 15, 2019 |
| Apple         | MacBook1,1                  | [c13279cf0f](https://linux-hardware.org/?probe=c13279cf0f) | Aug 14, 2019 |
| Lenovo        | ThinkPad T570 20H90017MC    | [e51b525663](https://linux-hardware.org/?probe=e51b525663) | Aug 10, 2019 |
| Lenovo        | ThinkPad X250 20CLS23500    | [8a4778de5b](https://linux-hardware.org/?probe=8a4778de5b) | Aug 01, 2019 |
| Lenovo        | ThinkPad L470 20J4003TXS    | [6c4dc05e0c](https://linux-hardware.org/?probe=6c4dc05e0c) | Jul 09, 2019 |
| Acer          | Aspire E1-531               | [a396fdf6c6](https://linux-hardware.org/?probe=a396fdf6c6) | Jun 29, 2019 |
| Acer          | Aspire E1-531               | [dbb78eb76e](https://linux-hardware.org/?probe=dbb78eb76e) | Jun 24, 2019 |
| HP            | ProBook 4730s               | [cb342b6572](https://linux-hardware.org/?probe=cb342b6572) | Jun 05, 2019 |
| HP            | Pavilion Notebook           | [5048eb8853](https://linux-hardware.org/?probe=5048eb8853) | May 17, 2019 |
| Acer          | AOD257                      | [d95215116b](https://linux-hardware.org/?probe=d95215116b) | May 06, 2019 |
| Acer          | AOD257                      | [589983c598](https://linux-hardware.org/?probe=589983c598) | May 05, 2019 |
| Sony          | SVE1713F1EW                 | [67b367b96f](https://linux-hardware.org/?probe=67b367b96f) | Apr 23, 2019 |
| ASUSTek       | E200HA                      | [c4e22bb515](https://linux-hardware.org/?probe=c4e22bb515) | Apr 11, 2019 |
| HP            | 510 Notebook PC (RU963AA... | [87f8ef65ae](https://linux-hardware.org/?probe=87f8ef65ae) | Apr 08, 2019 |
| MSI           | GX630/GX633                 | [12132d4ebd](https://linux-hardware.org/?probe=12132d4ebd) | Mar 26, 2019 |
| Lenovo        | ThinkPad T440p 20AW0047M... | [243988734d](https://linux-hardware.org/?probe=243988734d) | Mar 25, 2019 |
| Dell          | Vostro 3700                 | [459c56742e](https://linux-hardware.org/?probe=459c56742e) | Mar 10, 2019 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [d5472dae8e](https://linux-hardware.org/?probe=d5472dae8e) | Feb 21, 2019 |
| Lenovo        | IdeaPad Yoga 11S 20246      | [f422d122fa](https://linux-hardware.org/?probe=f422d122fa) | Feb 16, 2019 |
| HP            | Compaq Presario CQ50        | [7a5481cc61](https://linux-hardware.org/?probe=7a5481cc61) | Feb 11, 2019 |
| ASUSTek       | X51R                        | [67c7bfe084](https://linux-hardware.org/?probe=67c7bfe084) | Jan 30, 2019 |
| ASUSTek       | X51R                        | [c746805402](https://linux-hardware.org/?probe=c746805402) | Jan 30, 2019 |
| HP            | ProBook 4540s               | [e7d5fe03ba](https://linux-hardware.org/?probe=e7d5fe03ba) | Jan 26, 2019 |
| MSI           | GX630/GX633                 | [42e7957235](https://linux-hardware.org/?probe=42e7957235) | Jan 22, 2019 |
| HP            | ProBook 4540s               | [2f0dc95a92](https://linux-hardware.org/?probe=2f0dc95a92) | Dec 27, 2018 |
| Lenovo        | ThinkPad L430 24655K5       | [27aaa085bb](https://linux-hardware.org/?probe=27aaa085bb) | Dec 25, 2018 |
| HP            | Compaq 6720s                | [d7475ab15e](https://linux-hardware.org/?probe=d7475ab15e) | Dec 20, 2018 |
| HP            | Compaq 6720s                | [e5cdafcee2](https://linux-hardware.org/?probe=e5cdafcee2) | Dec 20, 2018 |
| HP            | Compaq 6720s                | [83a7e31dd4](https://linux-hardware.org/?probe=83a7e31dd4) | Dec 20, 2018 |
| Lenovo        | ThinkPad T430 2349Y12       | [27f3486119](https://linux-hardware.org/?probe=27f3486119) | Dec 14, 2018 |
| Lenovo        | ThinkPad T430 2349Y12       | [94d298a37a](https://linux-hardware.org/?probe=94d298a37a) | Dec 14, 2018 |
| ASUSTek       | N55SF                       | [8b49ac8515](https://linux-hardware.org/?probe=8b49ac8515) | Nov 30, 2018 |
| Acer          | Aspire V5-572P              | [46820db730](https://linux-hardware.org/?probe=46820db730) | Nov 08, 2018 |
| Sony          | VGN-NR21J_S                 | [4cce581173](https://linux-hardware.org/?probe=4cce581173) | Oct 31, 2018 |
| Lenovo        | ThinkPad E520 1143ENG       | [107f78f681](https://linux-hardware.org/?probe=107f78f681) | Oct 30, 2018 |
| Lenovo        | ThinkPad E520 1143ENG       | [bfb0367c84](https://linux-hardware.org/?probe=bfb0367c84) | Oct 30, 2018 |
| HP            | ProBook 4330s               | [4ce0dfe7c0](https://linux-hardware.org/?probe=4ce0dfe7c0) | Oct 28, 2018 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d5c9be9ec4](https://linux-hardware.org/?probe=d5c9be9ec4) | Oct 27, 2018 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [49aacee5b4](https://linux-hardware.org/?probe=49aacee5b4) | Oct 27, 2018 |
| ASUSTek       | X550VB                      | [931d58d353](https://linux-hardware.org/?probe=931d58d353) | Oct 21, 2018 |
| Dell          | Inspiron 7566               | [6682a76496](https://linux-hardware.org/?probe=6682a76496) | Aug 27, 2018 |
| HP            | ProBook 4545s               | [4598e67cd6](https://linux-hardware.org/?probe=4598e67cd6) | Jul 19, 2018 |
| HP            | ProBook 430 G2              | [d62a1df5c6](https://linux-hardware.org/?probe=d62a1df5c6) | May 29, 2018 |
| HP            | ProBook 430 G2              | [80ba1f23b5](https://linux-hardware.org/?probe=80ba1f23b5) | May 19, 2018 |
| Fujitsu Si... | LIFEBOOK S7220              | [d834a892f8](https://linux-hardware.org/?probe=d834a892f8) | Apr 17, 2018 |
| Toshiba       | Satellite P300              | [977054f744](https://linux-hardware.org/?probe=977054f744) | Dec 07, 2017 |
| Lenovo        | IdeaPad 305-15ABM 80NL      | [51938564c0](https://linux-hardware.org/?probe=51938564c0) | Nov 22, 2017 |
| ASUSTek       | X51L                        | [cd24ea4640](https://linux-hardware.org/?probe=cd24ea4640) | May 31, 2017 |
| Lenovo        | IdeaPad 305-15ABM 80NL      | [2524f15422](https://linux-hardware.org/?probe=2524f15422) | Mar 18, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Slovakia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 51        | 12.47%  |
| Ubuntu 18.04       | 38        | 9.29%   |
| BlackPanther 18.1  | 29        | 7.09%   |
| OpenMandriva 4.3   | 15        | 3.67%   |
| OpenMandriva 4.2   | 12        | 2.93%   |
| Ubuntu 22.04       | 10        | 2.44%   |
| Linux Mint 19.3    | 9         | 2.2%    |
| ROSA R10           | 8         | 1.96%   |
| Linux Mint 20.3    | 8         | 1.96%   |
| Linux Mint 20.1    | 8         | 1.96%   |
| OpenMandriva 23.01 | 7         | 1.71%   |
| Linux Mint 21.1    | 7         | 1.71%   |
| Linux Mint 21      | 7         | 1.71%   |
| Fedora 34          | 7         | 1.71%   |
| Arch Rolling       | 7         | 1.71%   |
| Xubuntu 18.04      | 6         | 1.47%   |
| Ubuntu 19.04       | 6         | 1.47%   |
| MX 19              | 6         | 1.47%   |
| Fedora 37          | 6         | 1.47%   |
| Ubuntu 20.10       | 5         | 1.22%   |
| Pop!_OS 20.10      | 5         | 1.22%   |
| Linux Mint 20.2    | 5         | 1.22%   |
| Zorin 15           | 4         | 0.98%   |
| ROSA R11.1         | 4         | 0.98%   |
| Pop!_OS 22.04      | 4         | 0.98%   |
| Pop!_OS 21.10      | 4         | 0.98%   |
| Manjaro            | 4         | 0.98%   |
| Linux Mint 19.1    | 4         | 0.98%   |
| Kubuntu 22.10      | 4         | 0.98%   |
| KDE neon 20.04     | 4         | 0.98%   |
| Fedora 32          | 4         | 0.98%   |
| Fedora 31          | 4         | 0.98%   |
| Debian 11          | 4         | 0.98%   |
| Debian 10          | 4         | 0.98%   |
| Arch               | 4         | 0.98%   |
| Xubuntu 20.04      | 3         | 0.73%   |
| Linux Mint 19.2    | 3         | 0.73%   |
| Fedora 36          | 3         | 0.73%   |
| Fedora 33          | 3         | 0.73%   |
| Zorin 16           | 2         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 117       | 30.15%  |
| Linux Mint   | 46        | 11.86%  |
| OpenMandriva | 33        | 8.51%   |
| Fedora       | 30        | 7.73%   |
| BlackPanther | 30        | 7.73%   |
| ROSA         | 15        | 3.87%   |
| Pop!_OS      | 14        | 3.61%   |
| Kubuntu      | 12        | 3.09%   |
| Xubuntu      | 11        | 2.84%   |
| Arch         | 11        | 2.84%   |
| Manjaro      | 9         | 2.32%   |
| Debian       | 9         | 2.32%   |
| Zorin        | 8         | 2.06%   |
| MX           | 7         | 1.8%    |
| KDE neon     | 5         | 1.29%   |
| Endless      | 4         | 1.03%   |
| Ubuntu Unity | 3         | 0.77%   |
| SteamOS      | 3         | 0.77%   |
| Gentoo       | 3         | 0.77%   |
| Ubuntu MATE  | 2         | 0.52%   |
| openSUSE     | 2         | 0.52%   |
| ArcoLinux    | 2         | 0.52%   |
| Rocky Linux  | 1         | 0.26%   |
| Lubuntu      | 1         | 0.26%   |
| Linux Lite   | 1         | 0.26%   |
| Kaisen       | 1         | 0.26%   |
| GNOME OS     | 1         | 0.26%   |
| GalliumOS    | 1         | 0.26%   |
| EndeavourOS  | 1         | 0.26%   |
| Elementary   | 1         | 0.26%   |
| Devuan       | 1         | 0.26%   |
| Clear Linux  | 1         | 0.26%   |
| CentOS       | 1         | 0.26%   |
| Alpine       | 1         | 0.26%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 4.18.16-desktop-1bP              | 22        | 5.07%   |
| 5.16.7-desktop-1omv4003          | 14        | 3.23%   |
| 5.10.14-desktop-1omv4002         | 12        | 2.76%   |
| 5.6.14-desktop-2bP               | 10        | 2.3%    |
| 5.15.0-56-generic                | 9         | 2.07%   |
| 5.4.0-58-generic                 | 8         | 1.84%   |
| 6.1.1-desktop-1omv2290           | 7         | 1.61%   |
| 5.4.0-42-generic                 | 7         | 1.61%   |
| 5.4.0-52-generic                 | 5         | 1.15%   |
| 5.15.0-58-generic                | 5         | 1.15%   |
| 5.11.0-27-generic                | 5         | 1.15%   |
| 5.8.0-43-generic                 | 4         | 0.92%   |
| 5.4.0-73-generic                 | 4         | 0.92%   |
| 5.4.0-47-generic                 | 4         | 0.92%   |
| 5.19.0-35-generic                | 4         | 0.92%   |
| 5.15.0-67-generic                | 4         | 0.92%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 4         | 0.92%   |
| 4.15.0-66-generic                | 4         | 0.92%   |
| 5.8.0-50-generic                 | 3         | 0.69%   |
| 5.8.0-29-generic                 | 3         | 0.69%   |
| 5.4.0-91-generic                 | 3         | 0.69%   |
| 5.4.0-88-generic                 | 3         | 0.69%   |
| 5.3.0-40-generic                 | 3         | 0.69%   |
| 5.3.0-26-generic                 | 3         | 0.69%   |
| 5.15.0-47-generic                | 3         | 0.69%   |
| 5.13.0-40-generic                | 3         | 0.69%   |
| 5.13.0-35-generic                | 3         | 0.69%   |
| 5.0.0-25-generic                 | 3         | 0.69%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 3         | 0.69%   |
| 4.19.0-13-amd64                  | 3         | 0.69%   |
| 4.15.0-55-generic                | 3         | 0.69%   |
| 5.9.16-200.fc33.x86_64           | 2         | 0.46%   |
| 5.8.0-7630-generic               | 2         | 0.46%   |
| 5.8.0-7625-generic               | 2         | 0.46%   |
| 5.4.83-generic-2rosa-x86_64      | 2         | 0.46%   |
| 5.4.0-96-generic                 | 2         | 0.46%   |
| 5.4.0-65-generic                 | 2         | 0.46%   |
| 5.4.0-48-generic                 | 2         | 0.46%   |
| 5.4.0-29-generic                 | 2         | 0.46%   |
| 5.4.0-26-generic                 | 2         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 66        | 16.02%  |
| 4.15.0  | 35        | 8.5%    |
| 5.15.0  | 27        | 6.55%   |
| 5.8.0   | 23        | 5.58%   |
| 4.18.16 | 22        | 5.34%   |
| 5.13.0  | 18        | 4.37%   |
| 5.3.0   | 17        | 4.13%   |
| 5.11.0  | 16        | 3.88%   |
| 5.0.0   | 15        | 3.64%   |
| 5.16.7  | 14        | 3.4%    |
| 5.10.14 | 12        | 2.91%   |
| 5.6.14  | 10        | 2.43%   |
| 5.19.0  | 10        | 2.43%   |
| 6.1.1   | 7         | 1.7%    |
| 5.10.0  | 7         | 1.7%    |
| 4.19.0  | 7         | 1.7%    |
| 4.18.0  | 7         | 1.7%    |
| 4.9.60  | 4         | 0.97%   |
| 5.9.16  | 3         | 0.73%   |
| 5.17.5  | 3         | 0.73%   |
| 5.11.11 | 3         | 0.73%   |
| 4.9.124 | 3         | 0.73%   |
| 5.4.83  | 2         | 0.49%   |
| 5.17.1  | 2         | 0.49%   |
| 5.15.75 | 2         | 0.49%   |
| 5.11.3  | 2         | 0.49%   |
| 4.9.20  | 2         | 0.49%   |
| 4.4.0   | 2         | 0.49%   |
| 6.2.8   | 1         | 0.24%   |
| 6.2.6   | 1         | 0.24%   |
| 6.1.7   | 1         | 0.24%   |
| 6.1.5   | 1         | 0.24%   |
| 6.1.14  | 1         | 0.24%   |
| 6.0.9   | 1         | 0.24%   |
| 6.0.6   | 1         | 0.24%   |
| 6.0.11  | 1         | 0.24%   |
| 6.0.10  | 1         | 0.24%   |
| 5.9.4   | 1         | 0.24%   |
| 5.8.9   | 1         | 0.24%   |
| 5.7.19  | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 70        | 17.03%  |
| 5.15    | 39        | 9.49%   |
| 4.15    | 35        | 8.52%   |
| 4.18    | 29        | 7.06%   |
| 5.10    | 27        | 6.57%   |
| 5.8     | 24        | 5.84%   |
| 5.11    | 22        | 5.35%   |
| 5.13    | 21        | 5.11%   |
| 5.3     | 19        | 4.62%   |
| 5.16    | 17        | 4.14%   |
| 5.0     | 17        | 4.14%   |
| 5.6     | 13        | 3.16%   |
| 5.19    | 13        | 3.16%   |
| 4.9     | 11        | 2.68%   |
| 6.1     | 10        | 2.43%   |
| 4.19    | 8         | 1.95%   |
| 5.17    | 7         | 1.7%    |
| 5.5     | 5         | 1.22%   |
| 6.0     | 4         | 0.97%   |
| 5.9     | 4         | 0.97%   |
| 5.12    | 3         | 0.73%   |
| 6.2     | 2         | 0.49%   |
| 5.7     | 2         | 0.49%   |
| 5.18    | 2         | 0.49%   |
| 4.4     | 2         | 0.49%   |
| 5.2     | 1         | 0.24%   |
| 4.17    | 1         | 0.24%   |
| 4.16    | 1         | 0.24%   |
| 4.12    | 1         | 0.24%   |
| 4.1     | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 350       | 92.35%  |
| i686   | 29        | 7.65%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 137       | 35.22%  |
| KDE5            | 99        | 25.45%  |
| Unknown         | 48        | 12.34%  |
| X-Cinnamon      | 37        | 9.51%   |
| XFCE            | 35        | 9%      |
| KDE4            | 8         | 2.06%   |
| MATE            | 7         | 1.8%    |
| KDE             | 7         | 1.8%    |
| Unity           | 3         | 0.77%   |
| Cinnamon        | 3         | 0.77%   |
| LXDE            | 2         | 0.51%   |
| Pantheon        | 1         | 0.26%   |
| GNOME Flashback | 1         | 0.26%   |
| awesome         | 1         | 0.26%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 313       | 81.72%  |
| Wayland     | 46        | 12.01%  |
| Unknown     | 20        | 5.22%   |
| Tty         | 3         | 0.78%   |
| Unspecified | 1         | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 192       | 49.74%  |
| SDDM    | 83        | 21.5%   |
| GDM     | 34        | 8.81%   |
| LightDM | 30        | 7.77%   |
| GDM3    | 27        | 6.99%   |
| TDM     | 11        | 2.85%   |
| KDM     | 8         | 2.07%   |
| XDM     | 1         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 163       | 41.58%  |
| sk_SK   | 107       | 27.3%   |
| Unknown | 89        | 22.7%   |
| cs_CZ   | 11        | 2.81%   |
| hu_HU   | 7         | 1.79%   |
| C       | 6         | 1.53%   |
| en_GB   | 4         | 1.02%   |
| ru_UA   | 1         | 0.26%   |
| ru_RU   | 1         | 0.26%   |
| it_IT   | 1         | 0.26%   |
| en_US  | 1         | 0.26%   |
| C.UTF8  | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 217       | 56.07%  |
| EFI  | 170       | 43.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 266       | 68.38%  |
| Overlay | 67        | 17.22%  |
| Btrfs   | 26        | 6.68%   |
| Unknown | 16        | 4.11%   |
| Zfs     | 5         | 1.29%   |
| Xfs     | 4         | 1.03%   |
| Ext3    | 2         | 0.51%   |
| Ext2    | 2         | 0.51%   |
| Tmpfs   | 1         | 0.26%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 208       | 53.75%  |
| GPT     | 105       | 27.13%  |
| MBR     | 74        | 19.12%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 324       | 83.72%  |
| Yes       | 63        | 16.28%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 255       | 66.75%  |
| Yes       | 127       | 33.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 98        | 25.93%  |
| Hewlett-Packard     | 70        | 18.52%  |
| ASUSTek Computer    | 63        | 16.67%  |
| Dell                | 51        | 13.49%  |
| Acer                | 27        | 7.14%   |
| Toshiba             | 16        | 4.23%   |
| MSI                 | 9         | 2.38%   |
| Sony                | 8         | 2.12%   |
| UMAX                | 4         | 1.06%   |
| Fujitsu Siemens     | 4         | 1.06%   |
| Fujitsu             | 4         | 1.06%   |
| Valve               | 3         | 0.79%   |
| Samsung Electronics | 3         | 0.79%   |
| eMachines           | 3         | 0.79%   |
| Packard Bell        | 2         | 0.53%   |
| Medion              | 2         | 0.53%   |
| HUAWEI              | 2         | 0.53%   |
| Google              | 2         | 0.53%   |
| Apple               | 2         | 0.53%   |
| Timi                | 1         | 0.26%   |
| Teclast             | 1         | 0.26%   |
| PC Specialist       | 1         | 0.26%   |
| GPD                 | 1         | 0.26%   |
| Unknown             | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| ASUS X550CC                            | 4         | 1.06%   |
| Valve Jupiter                          | 3         | 0.79%   |
| HP ProBook 4540s                       | 3         | 0.79%   |
| HP Pavilion g6                         | 3         | 0.79%   |
| HP Pavilion dv6                        | 3         | 0.79%   |
| UMAX VisionBook 14Wr Plus              | 2         | 0.53%   |
| Toshiba Satellite P300                 | 2         | 0.53%   |
| MSI VR610                              | 2         | 0.53%   |
| Lenovo Yoga Slim 7 Pro 14ITL5 82FX     | 2         | 0.53%   |
| Lenovo IdeaPad Z500 20202              | 2         | 0.53%   |
| Lenovo IdeaPad U260 20067              | 2         | 0.53%   |
| Lenovo IdeaPad S145-14AST 81ST         | 2         | 0.53%   |
| Lenovo G580                            | 2         | 0.53%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.53%   |
| HP ProBook 6570b                       | 2         | 0.53%   |
| HP ProBook 650 G1                      | 2         | 0.53%   |
| HP ProBook 4545s                       | 2         | 0.53%   |
| HP ProBook 450 G5                      | 2         | 0.53%   |
| HP ProBook 4340s                       | 2         | 0.53%   |
| HP ProBook 4330s                       | 2         | 0.53%   |
| HP Pavilion 11 x360 PC                 | 2         | 0.53%   |
| HP EliteBook 8470p                     | 2         | 0.53%   |
| Dell XPS 15 9570                       | 2         | 0.53%   |
| Dell Precision 7530                    | 2         | 0.53%   |
| Dell Latitude E6540                    | 2         | 0.53%   |
| Dell Latitude 5490                     | 2         | 0.53%   |
| Dell Latitude 5401                     | 2         | 0.53%   |
| ASUS X51R                              | 2         | 0.53%   |
| ASUS X51L                              | 2         | 0.53%   |
| ASUS VivoBook_ASUSLaptop X509DJ_D509DJ | 2         | 0.53%   |
| ASUS K50C                              | 2         | 0.53%   |
| Acer Swift SF314-43                    | 2         | 0.53%   |
| Acer Extensa 5635G                     | 2         | 0.53%   |
| Unknown                                | 2         | 0.53%   |
| UMAX VisionBook-N12R                   | 1         | 0.26%   |
| UMAX VisionBook 14Wg Pro               | 1         | 0.26%   |
| Toshiba TECRA S5                       | 1         | 0.26%   |
| Toshiba Satellite U400                 | 1         | 0.26%   |
| Toshiba Satellite Pro C850-1D5         | 1         | 0.26%   |
| Toshiba Satellite Pro C660             | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 45        | 11.9%   |
| Lenovo IdeaPad           | 29        | 7.67%   |
| Dell Latitude            | 24        | 6.35%   |
| HP ProBook               | 23        | 6.08%   |
| Toshiba Satellite        | 14        | 3.7%    |
| HP Pavilion              | 14        | 3.7%    |
| Acer Aspire              | 14        | 3.7%    |
| HP EliteBook             | 13        | 3.44%   |
| Dell XPS                 | 7         | 1.85%   |
| Dell Vostro              | 6         | 1.59%   |
| Dell Inspiron            | 6         | 1.59%   |
| ASUS VivoBook            | 6         | 1.59%   |
| Acer Swift               | 6         | 1.59%   |
| ASUS ROG                 | 5         | 1.32%   |
| ASUS X550CC              | 4         | 1.06%   |
| Acer Extensa             | 4         | 1.06%   |
| Valve Jupiter            | 3         | 0.79%   |
| UMAX VisionBook          | 3         | 0.79%   |
| Lenovo Yoga              | 3         | 0.79%   |
| Lenovo Legion            | 3         | 0.79%   |
| HP ZBook                 | 3         | 0.79%   |
| HP Laptop                | 3         | 0.79%   |
| Fujitsu LIFEBOOK         | 3         | 0.79%   |
| Dell Precision           | 3         | 0.79%   |
| ASUS ZenBook             | 3         | 0.79%   |
| Packard Bell EasyNote    | 2         | 0.53%   |
| MSI VR610                | 2         | 0.53%   |
| MSI Prestige             | 2         | 0.53%   |
| Lenovo G580              | 2         | 0.53%   |
| HUAWEI KLVL-WXX9         | 2         | 0.53%   |
| HP Compaq                | 2         | 0.53%   |
| HP 250                   | 2         | 0.53%   |
| Fujitsu Siemens LIFEBOOK | 2         | 0.53%   |
| Dell Studio              | 2         | 0.53%   |
| ASUS X51R                | 2         | 0.53%   |
| ASUS X51L                | 2         | 0.53%   |
| ASUS K50C                | 2         | 0.53%   |
| Unknown                  | 2         | 0.53%   |
| UMAX VisionBook-N12R     | 1         | 0.26%   |
| Toshiba TECRA            | 1         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 40        | 10.58%  |
| 2013 | 37        | 9.79%   |
| 2019 | 32        | 8.47%   |
| 2011 | 30        | 7.94%   |
| 2008 | 25        | 6.61%   |
| 2021 | 24        | 6.35%   |
| 2018 | 23        | 6.08%   |
| 2017 | 23        | 6.08%   |
| 2020 | 22        | 5.82%   |
| 2010 | 22        | 5.82%   |
| 2016 | 19        | 5.03%   |
| 2007 | 18        | 4.76%   |
| 2009 | 17        | 4.5%    |
| 2015 | 15        | 3.97%   |
| 2014 | 15        | 3.97%   |
| 2022 | 8         | 2.12%   |
| 2006 | 7         | 1.85%   |
| 2005 | 1         | 0.26%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 378       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 341       | 89.74%  |
| Enabled  | 39        | 10.26%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 376       | 99.47%  |
| Yes  | 2         | 0.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 103       | 27.03%  |
| 4.01-8.0    | 100       | 26.25%  |
| 8.01-16.0   | 58        | 15.22%  |
| 16.01-24.0  | 56        | 14.7%   |
| 1.01-2.0    | 28        | 7.35%   |
| 32.01-64.0  | 15        | 3.94%   |
| 2.01-3.0    | 11        | 2.89%   |
| 0.51-1.0    | 5         | 1.31%   |
| 64.01-256.0 | 3         | 0.79%   |
| 24.01-32.0  | 2         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 157       | 38.39%  |
| 2.01-3.0  | 85        | 20.78%  |
| 0.51-1.0  | 60        | 14.67%  |
| 3.01-4.0  | 42        | 10.27%  |
| 4.01-8.0  | 40        | 9.78%   |
| 8.01-16.0 | 16        | 3.91%   |
| 0.01-0.5  | 9         | 2.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 276       | 69.87%  |
| 2      | 97        | 24.56%  |
| 3      | 15        | 3.8%    |
| 0      | 7         | 1.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 212       | 55.94%  |
| Yes       | 167       | 44.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 322       | 84.96%  |
| No        | 57        | 15.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 374       | 98.94%  |
| No        | 4         | 1.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 280       | 73.3%   |
| No        | 102       | 26.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Slovakia | 378       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Bratislava             | 149       | 36.17%  |
| Košice                | 19        | 4.61%   |
| Banská Bystrica       | 19        | 4.61%   |
| Nitra                  | 18        | 4.37%   |
| Prešov                | 8         | 1.94%   |
| Martin                 | 7         | 1.7%    |
| Humenné               | 7         | 1.7%    |
| Trnava                 | 6         | 1.46%   |
| Žilina                | 5         | 1.21%   |
| Zvolen                 | 4         | 0.97%   |
| Trenčín              | 4         | 0.97%   |
| Topoľčany            | 4         | 0.97%   |
| Soblahov               | 4         | 0.97%   |
| Nové Zámky           | 4         | 0.97%   |
| Levice                 | 4         | 0.97%   |
| Bardejov               | 4         | 0.97%   |
| Tornaľa               | 3         | 0.73%   |
| Senec                  | 3         | 0.73%   |
| Poprad                 | 3         | 0.73%   |
| Námestovo             | 3         | 0.73%   |
| Lučenec               | 3         | 0.73%   |
| Kysucké Nové Mesto   | 3         | 0.73%   |
| Dunajská Streda       | 3         | 0.73%   |
| Voderady               | 2         | 0.49%   |
| Vlkova                 | 2         | 0.49%   |
| Štúrovo              | 2         | 0.49%   |
| Stara Tura             | 2         | 0.49%   |
| Skalica                | 2         | 0.49%   |
| Ružomberok            | 2         | 0.49%   |
| Rožňava              | 2         | 0.49%   |
| Rohoznik               | 2         | 0.49%   |
| Revúca                | 2         | 0.49%   |
| Podhradie              | 2         | 0.49%   |
| Nové Mesto nad Váhom | 2         | 0.49%   |
| Most pri Bratislave    | 2         | 0.49%   |
| Modra                  | 2         | 0.49%   |
| Maly Lipnik            | 2         | 0.49%   |
| Liptovský Mikuláš   | 2         | 0.49%   |
| Krupina                | 2         | 0.49%   |
| Galanta                | 2         | 0.49%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 68        | 79     | 14.02%  |
| Seagate                     | 65        | 76     | 13.4%   |
| Samsung Electronics         | 60        | 72     | 12.37%  |
| Toshiba                     | 36        | 50     | 7.42%   |
| Kingston                    | 30        | 41     | 6.19%   |
| Unknown                     | 27        | 43     | 5.57%   |
| SanDisk                     | 27        | 31     | 5.57%   |
| Intel                       | 20        | 25     | 4.12%   |
| Patriot                     | 17        | 25     | 3.51%   |
| Hitachi                     | 17        | 17     | 3.51%   |
| Micron Technology           | 14        | 17     | 2.89%   |
| SK hynix                    | 13        | 17     | 2.68%   |
| HGST                        | 13        | 17     | 2.68%   |
| Crucial                     | 13        | 16     | 2.68%   |
| A-DATA Technology           | 12        | 19     | 2.47%   |
| Fujitsu                     | 5         | 5      | 1.03%   |
| KIOXIA                      | 4         | 14     | 0.82%   |
| Apacer                      | 4         | 4      | 0.82%   |
| Unknown                     | 4         | 4      | 0.82%   |
| Verbatim                    | 3         | 4      | 0.62%   |
| LITEON                      | 3         | 3      | 0.62%   |
| Union Memory                | 2         | 2      | 0.41%   |
| Transcend                   | 2         | 2      | 0.41%   |
| Phison                      | 2         | 2      | 0.41%   |
| OCZ                         | 2         | 2      | 0.41%   |
| LITEONIT                    | 2         | 2      | 0.41%   |
| ZTE                         | 1         | 1      | 0.21%   |
| WDC WDS2                    | 1         | 1      | 0.21%   |
| Solid State Storage         | 1         | 1      | 0.21%   |
| Phison Electronics          | 1         | 1      | 0.21%   |
| Lenovo                      | 1         | 1      | 0.21%   |
| Kingston Technology Company | 1         | 1      | 0.21%   |
| KingSpec                    | 1         | 1      | 0.21%   |
| KingDian                    | 1         | 3      | 0.21%   |
| JMicron Technology          | 1         | 1      | 0.21%   |
| Intenso                     | 1         | 1      | 0.21%   |
| IM3D                        | 1         | 1      | 0.21%   |
| IBM/Hitachi                 | 1         | 1      | 0.21%   |
| HUAWEI                      | 1         | 1      | 0.21%   |
| HS-SSD-E100                 | 1         | 1      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Patriot Burst 240GB SSD                | 10        | 1.97%   |
| Samsung SSD 860 EVO 500GB              | 9         | 1.77%   |
| Patriot Burst 480GB SSD                | 7         | 1.38%   |
| Unknown MMC Card  64GB                 | 6         | 1.18%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 5         | 0.98%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 5         | 0.98%   |
| Seagate ST9500420AS 500GB              | 5         | 0.98%   |
| Seagate ST9500325AS 500GB              | 5         | 0.98%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 5         | 0.98%   |
| SanDisk NVMe SSD Drive 1024GB          | 5         | 0.98%   |
| Samsung SSD 850 EVO 500GB              | 5         | 0.98%   |
| Kingston SV300S37A120G 120GB SSD       | 5         | 0.98%   |
| Kingston SA400S37240G 240GB SSD        | 5         | 0.98%   |
| Kingston SA400S37120G 120GB SSD        | 5         | 0.98%   |
| Unknown MMC Card  1GB                  | 4         | 0.79%   |
| SanDisk NVMe SSD Drive 512GB           | 4         | 0.79%   |
| HGST HTS725050A7E630 500GB             | 4         | 0.79%   |
| Crucial CT120BX500SSD1 120GB           | 4         | 0.79%   |
| Unknown                                | 4         | 0.79%   |
| Unknown MMC Card  32GB                 | 3         | 0.59%   |
| Unknown MMC Card  16GB                 | 3         | 0.59%   |
| Toshiba NVMe SSD Drive 512GB           | 3         | 0.59%   |
| Toshiba MQ01ABF050 500GB               | 3         | 0.59%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 0.59%   |
| SK hynix NVMe SSD Drive 512GB          | 3         | 0.59%   |
| Seagate ST9750420AS 752GB              | 3         | 0.59%   |
| Seagate ST9250827AS 250GB              | 3         | 0.59%   |
| Seagate ST9250315AS 250GB              | 3         | 0.59%   |
| Seagate ST500LT012-9WS142 500GB        | 3         | 0.59%   |
| Seagate ST500LM000-1EJ162 500GB        | 3         | 0.59%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.59%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.59%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 3         | 0.59%   |
| Samsung NVMe SSD Drive 512GB           | 3         | 0.59%   |
| Kingston SA400S37480G 480GB SSD        | 3         | 0.59%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.59%   |
| HGST HTS545050A7E380 500GB             | 3         | 0.59%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.39%   |
| WDC WD3200BPVT-22ZEST0 320GB           | 2         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 65        | 76     | 38.24%  |
| WDC                 | 44        | 51     | 25.88%  |
| Toshiba             | 24        | 38     | 14.12%  |
| Hitachi             | 17        | 17     | 10%     |
| HGST                | 13        | 17     | 7.65%   |
| Fujitsu             | 5         | 5      | 2.94%   |
| Samsung Electronics | 1         | 2      | 0.59%   |
| IBM/Hitachi         | 1         | 1      | 0.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 40     | 20%     |
| Kingston            | 26        | 37     | 14.44%  |
| Patriot             | 16        | 24     | 8.89%   |
| WDC                 | 15        | 18     | 8.33%   |
| Crucial             | 13        | 16     | 7.22%   |
| SanDisk             | 12        | 15     | 6.67%   |
| Intel               | 11        | 15     | 6.11%   |
| A-DATA Technology   | 11        | 18     | 6.11%   |
| Micron Technology   | 6         | 8      | 3.33%   |
| Toshiba             | 5         | 5      | 2.78%   |
| Apacer              | 4         | 4      | 2.22%   |
| LITEON              | 3         | 3      | 1.67%   |
| Verbatim            | 2         | 2      | 1.11%   |
| Union Memory        | 2         | 2      | 1.11%   |
| Transcend           | 2         | 2      | 1.11%   |
| SK hynix            | 2         | 2      | 1.11%   |
| OCZ                 | 2         | 2      | 1.11%   |
| LITEONIT            | 2         | 2      | 1.11%   |
| WDC WDS2            | 1         | 1      | 0.56%   |
| KingSpec            | 1         | 1      | 0.56%   |
| KingDian            | 1         | 3      | 0.56%   |
| Intenso             | 1         | 1      | 0.56%   |
| IM3D                | 1         | 1      | 0.56%   |
| HS-SSD-E100         | 1         | 1      | 0.56%   |
| Hewlett-Packard     | 1         | 1      | 0.56%   |
| Faspeed             | 1         | 1      | 0.56%   |
| China               | 1         | 2      | 0.56%   |
| 2.5                 | 1         | 1      | 0.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 162       | 207    | 35.76%  |
| SSD     | 159       | 228    | 35.1%   |
| NVMe    | 96        | 125    | 21.19%  |
| MMC     | 31        | 47     | 6.84%   |
| Unknown | 5         | 6      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 282       | 425    | 66.51%  |
| NVMe | 96        | 125    | 22.64%  |
| MMC  | 31        | 47     | 7.31%   |
| SAS  | 15        | 16     | 3.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 232       | 339    | 75.57%  |
| 0.51-1.0   | 67        | 84     | 21.82%  |
| 1.01-2.0   | 8         | 12     | 2.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 107       | 26.49%  |
| 251-500        | 82        | 20.3%   |
| 501-1000       | 51        | 12.62%  |
| 1-20           | 46        | 11.39%  |
| 51-100         | 34        | 8.42%   |
| Unknown        | 33        | 8.17%   |
| 21-50          | 25        | 6.19%   |
| 1001-2000      | 19        | 4.7%    |
| More than 3000 | 4         | 0.99%   |
| 2001-3000      | 3         | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 170       | 41.98%  |
| 21-50          | 62        | 15.31%  |
| 101-250        | 49        | 12.1%   |
| 51-100         | 46        | 11.36%  |
| Unknown        | 33        | 8.15%   |
| 251-500        | 27        | 6.67%   |
| 501-1000       | 11        | 2.72%   |
| 1001-2000      | 5         | 1.23%   |
| More than 3000 | 2         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Toshiba MK7575GSX 752GB                        | 2         | 3      | 4.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 1         | 1      | 2.38%   |
| WDC WD7500BPVT-80HXZT3 752GB                   | 1         | 1      | 2.38%   |
| WDC WD5000LPVT-24G33T1 500GB                   | 1         | 1      | 2.38%   |
| WDC WD5000BPVT-00HXZT1 500GB                   | 1         | 1      | 2.38%   |
| WDC WD3200BEVT-75ZCT2 320GB                    | 1         | 1      | 2.38%   |
| WDC WD10JPLX-00MBPT0 1TB                       | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD075 752GB                       | 1         | 1      | 2.38%   |
| Toshiba MK5056GSY 500GB                        | 1         | 1      | 2.38%   |
| Toshiba MK1646GSX 160GB                        | 1         | 2      | 2.38%   |
| Toshiba MK1637GSX 160GB                        | 1         | 1      | 2.38%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB        | 1         | 1      | 2.38%   |
| Seagate ST980811AS 80GB                        | 1         | 1      | 2.38%   |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 2.38%   |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 2.38%   |
| Seagate ST9250315AS 250GB                      | 1         | 1      | 2.38%   |
| Seagate ST9120823ASG 120GB                     | 1         | 1      | 2.38%   |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 2.38%   |
| Seagate ST500LM000-1EJ162 500GB                | 1         | 2      | 2.38%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 2      | 2.38%   |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 2.38%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 2.38%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD            | 1         | 1      | 2.38%   |
| SanDisk iSSD P4 8GB                            | 1         | 2      | 2.38%   |
| Samsung Electronics SSD 960 EVO 500GB          | 1         | 1      | 2.38%   |
| Samsung Electronics HS122JC 120GB              | 1         | 2      | 2.38%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 2.38%   |
| Micron Technology 1100 SATA 256GB SSD          | 1         | 1      | 2.38%   |
| Lenovo LENSE30256GMSP34MEAT3TA 256GB           | 1         | 1      | 2.38%   |
| Intel SSDSC2CW060A3 64GB                       | 1         | 1      | 2.38%   |
| Intel SSDSC2BF240A5L 240GB                     | 1         | 1      | 2.38%   |
| IM3D L06B B0KB 120GB SSD                       | 1         | 1      | 2.38%   |
| Hitachi HTS723216L9A360 160GB                  | 1         | 1      | 2.38%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 2.38%   |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 2.38%   |
| Hitachi HTS543232A7A384 320GB                  | 1         | 1      | 2.38%   |
| Hitachi HTS543225L9SA00 250GB                  | 1         | 1      | 2.38%   |
| Hitachi HTS543216L9SA02 160GB                  | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 26.19%  |
| Toshiba             | 7         | 9      | 16.67%  |
| WDC                 | 6         | 6      | 14.29%  |
| Hitachi             | 6         | 6      | 14.29%  |
| SanDisk             | 2         | 3      | 4.76%   |
| Samsung Electronics | 2         | 3      | 4.76%   |
| Micron Technology   | 2         | 2      | 4.76%   |
| Intel               | 2         | 2      | 4.76%   |
| SK hynix            | 1         | 1      | 2.38%   |
| Lenovo              | 1         | 1      | 2.38%   |
| IM3D                | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 13     | 35.48%  |
| Toshiba             | 7         | 9      | 22.58%  |
| Hitachi             | 6         | 6      | 19.35%  |
| WDC                 | 5         | 5      | 16.13%  |
| Samsung Electronics | 1         | 2      | 3.23%   |
| HGST                | 1         | 1      | 3.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 36     | 73.17%  |
| SSD  | 8         | 9      | 19.51%  |
| NVMe | 3         | 3      | 7.32%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9320325AS 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 228       | 335    | 56.02%  |
| Works    | 137       | 229    | 33.66%  |
| Malfunc  | 41        | 48     | 10.07%  |
| Failed   | 1         | 1      | 0.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 267       | 63.27%  |
| AMD                              | 50        | 11.85%  |
| Samsung Electronics              | 27        | 6.4%    |
| SanDisk                          | 24        | 5.69%   |
| SK hynix                         | 11        | 2.61%   |
| Micron Technology                | 8         | 1.9%    |
| Toshiba America Info Systems     | 7         | 1.66%   |
| Nvidia                           | 7         | 1.66%   |
| Kingston Technology Company      | 5         | 1.18%   |
| Phison Electronics               | 4         | 0.95%   |
| KIOXIA                           | 4         | 0.95%   |
| Silicon Integrated Systems [SiS] | 3         | 0.71%   |
| Solid State Storage Technology   | 1         | 0.24%   |
| Silicon Image                    | 1         | 0.24%   |
| Lenovo                           | 1         | 0.24%   |
| Apple                            | 1         | 0.24%   |
| ADATA Technology                 | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 47        | 9.89%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 34        | 7.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 23        | 4.84%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 21        | 4.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 17        | 3.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 16        | 3.37%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 16        | 3.37%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 15        | 3.16%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 15        | 3.16%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 2.95%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 10        | 2.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 2.11%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 10        | 2.11%   |
| Micron NVMe Storage Controller                                                 | 8         | 1.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 1.68%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 7         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 1.47%   |
| SanDisk NVMe Controller                                                        | 6         | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 6         | 1.26%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 1.26%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                | 6         | 1.26%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                | 6         | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 1.26%   |
| AMD SB600 Non-Raid-5 SATA                                                      | 6         | 1.26%   |
| AMD SB600 IDE                                                                  | 6         | 1.26%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.05%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.05%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 1.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 1.05%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 4         | 0.84%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 0.84%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 4         | 0.84%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 0.84%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 0.84%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 4         | 0.84%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 4         | 0.84%   |
| Intel Volume Management Device NVMe RAID Controller                            | 4         | 0.84%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 4         | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 0.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 4         | 0.84%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 271       | 60.22%  |
| NVMe | 97        | 21.56%  |
| IDE  | 60        | 13.33%  |
| RAID | 22        | 4.89%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 305       | 80.69%  |
| AMD    | 73        | 19.31%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 2.12%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 1.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.59%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 6         | 1.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 6         | 1.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.32%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.32%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 1.06%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 4         | 1.06%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 4         | 1.06%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 4         | 1.06%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.06%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 3         | 0.79%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 3         | 0.79%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 3         | 0.79%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.79%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 3         | 0.79%   |
| Intel Pentium CPU 2117U @ 1.80GHz             | 3         | 0.79%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 3         | 0.79%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 0.79%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 3         | 0.79%   |
| Intel Core i7-2630QM CPU @ 2.00GHz            | 3         | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 3         | 0.79%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.79%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 0.79%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 3         | 0.79%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 3         | 0.79%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 3         | 0.79%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 3         | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 0.79%   |
| Intel Core i3 CPU U 380 @ 1.33GHz             | 3         | 0.79%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 3         | 0.79%   |
| Intel Core 2 Duo CPU T5250 @ 1.50GHz          | 3         | 0.79%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 0.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 0.79%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.79%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.79%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 87        | 23.02%  |
| Intel Core i7                        | 65        | 17.2%   |
| Intel Core i3                        | 35        | 9.26%   |
| Intel Pentium                        | 26        | 6.88%   |
| Intel Core 2 Duo                     | 26        | 6.88%   |
| Intel Celeron                        | 19        | 5.03%   |
| Other                                | 17        | 4.5%    |
| AMD Ryzen 5                          | 13        | 3.44%   |
| AMD Ryzen 7                          | 10        | 2.65%   |
| Intel Pentium Dual                   | 8         | 2.12%   |
| Intel Atom                           | 7         | 1.85%   |
| Intel Pentium Dual-Core              | 4         | 1.06%   |
| Intel Celeron M                      | 4         | 1.06%   |
| AMD Ryzen 7 PRO                      | 4         | 1.06%   |
| AMD E                                | 4         | 1.06%   |
| AMD A8                               | 4         | 1.06%   |
| AMD A6                               | 4         | 1.06%   |
| Intel Core 2                         | 3         | 0.79%   |
| Intel Celeron Dual-Core              | 3         | 0.79%   |
| AMD Ryzen 9                          | 3         | 0.79%   |
| AMD Ryzen 3                          | 3         | 0.79%   |
| AMD Athlon 64 X2                     | 3         | 0.79%   |
| Intel Pentium M                      | 2         | 0.53%   |
| Intel Genuine                        | 2         | 0.53%   |
| AMD Turion 64 Mobile                 | 2         | 0.53%   |
| AMD Ryzen 5 PRO                      | 2         | 0.53%   |
| AMD E1                               | 2         | 0.53%   |
| AMD Athlon II                        | 2         | 0.53%   |
| AMD Athlon                           | 2         | 0.53%   |
| AMD A4                               | 2         | 0.53%   |
| AMD A10                              | 2         | 0.53%   |
| Intel Pentium Silver                 | 1         | 0.26%   |
| Intel Core 2 Quad                    | 1         | 0.26%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.26%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.26%   |
| AMD Turion 64 X2 Mobile              | 1         | 0.26%   |
| AMD PRO A10                          | 1         | 0.26%   |
| AMD Mobile Sempron                   | 1         | 0.26%   |
| AMD E2                               | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 217       | 57.41%  |
| 4       | 102       | 26.98%  |
| 6       | 23        | 6.08%   |
| 8       | 17        | 4.5%    |
| 1       | 17        | 4.5%    |
| 16      | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 378       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 241       | 63.76%  |
| 1       | 135       | 35.71%  |
| 4       | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 365       | 95.55%  |
| Unknown        | 9         | 2.36%   |
| 32-bit         | 8         | 2.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 17.05%  |
| 0x306a9    | 39        | 10.08%  |
| 0x206a7    | 29        | 7.49%   |
| 0x1067a    | 18        | 4.65%   |
| 0x806ea    | 14        | 3.62%   |
| 0x6fd      | 12        | 3.1%    |
| 0x306c3    | 12        | 3.1%    |
| 0x906ea    | 11        | 2.84%   |
| 0x20655    | 11        | 2.84%   |
| 0x406e3    | 10        | 2.58%   |
| 0x806e9    | 9         | 2.33%   |
| 0x806c1    | 9         | 2.33%   |
| 0x10676    | 9         | 2.33%   |
| 0x806ec    | 8         | 2.07%   |
| 0x506e3    | 7         | 1.81%   |
| 0x40651    | 6         | 1.55%   |
| 0x30678    | 6         | 1.55%   |
| 0x20652    | 5         | 1.29%   |
| 0x0a50000c | 5         | 1.29%   |
| 0x08608103 | 5         | 1.29%   |
| 0x506c9    | 4         | 1.03%   |
| 0x306d4    | 4         | 1.03%   |
| 0x08600106 | 4         | 1.03%   |
| 0x08108109 | 4         | 1.03%   |
| 0x08108102 | 4         | 1.03%   |
| 0x07030105 | 4         | 1.03%   |
| 0x06006705 | 4         | 1.03%   |
| 0xa0652    | 3         | 0.78%   |
| 0x906ed    | 3         | 0.78%   |
| 0x906e9    | 3         | 0.78%   |
| 0x706a8    | 3         | 0.78%   |
| 0x706a1    | 3         | 0.78%   |
| 0x6d8      | 3         | 0.78%   |
| 0x406c3    | 3         | 0.78%   |
| 0x106ca    | 3         | 0.78%   |
| 0x05000119 | 3         | 0.78%   |
| 0x6fb      | 2         | 0.52%   |
| 0x6f6      | 2         | 0.52%   |
| 0x6f2      | 2         | 0.52%   |
| 0x6ec      | 2         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 58        | 15.34%  |
| IvyBridge       | 44        | 11.64%  |
| SandyBridge     | 32        | 8.47%   |
| Penryn          | 27        | 7.14%   |
| Haswell         | 24        | 6.35%   |
| Core            | 22        | 5.82%   |
| Westmere        | 19        | 5.03%   |
| Skylake         | 19        | 5.03%   |
| Unknown         | 14        | 3.7%    |
| Silvermont      | 13        | 3.44%   |
| TigerLake       | 10        | 2.65%   |
| Zen+            | 8         | 2.12%   |
| Zen 3           | 8         | 2.12%   |
| K8 Hammer       | 8         | 2.12%   |
| Excavator       | 8         | 2.12%   |
| Zen 2           | 7         | 1.85%   |
| P6              | 7         | 1.85%   |
| Goldmont plus   | 6         | 1.59%   |
| Broadwell       | 6         | 1.59%   |
| Bonnell         | 5         | 1.32%   |
| Puma            | 4         | 1.06%   |
| Piledriver      | 4         | 1.06%   |
| Goldmont        | 4         | 1.06%   |
| CometLake       | 4         | 1.06%   |
| Bobcat          | 4         | 1.06%   |
| K8 & K10 hybrid | 3         | 0.79%   |
| IceLake         | 3         | 0.79%   |
| Zen             | 2         | 0.53%   |
| K10             | 2         | 0.53%   |
| Nehalem         | 1         | 0.26%   |
| K10 Llano       | 1         | 0.26%   |
| Jaguar          | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 262       | 55.27%  |
| Nvidia                           | 113       | 23.84%  |
| AMD                              | 97        | 20.46%  |
| Silicon Integrated Systems [SiS] | 2         | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 41        | 8.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 27        | 5.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 3%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 15        | 3%      |
| Intel UHD Graphics 620                                                                   | 14        | 2.8%    |
| Intel Core Processor Integrated Graphics Controller                                      | 14        | 2.8%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 2.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 10        | 2%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 10        | 2%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 1.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 9         | 1.8%    |
| Intel HD Graphics 620                                                                    | 9         | 1.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 1.6%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 1.6%    |
| AMD Lucienne                                                                             | 8         | 1.6%    |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 1.4%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 1.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.4%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 7         | 1.4%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 1.2%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 6         | 1.2%    |
| Intel HD Graphics 5500                                                                   | 6         | 1.2%    |
| Intel HD Graphics 530                                                                    | 6         | 1.2%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 6         | 1.2%    |
| AMD Renoir                                                                               | 6         | 1.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.2%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1%      |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 1%      |
| Nvidia GK208M [GeForce GT 720M]                                                          | 4         | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.8%    |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 4         | 0.8%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.6%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.6%    |
| Nvidia GF108M [GeForce GT 635M]                                                          | 3         | 0.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.6%    |
| Intel HD Graphics 630                                                                    | 3         | 0.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 176       | 46.07%  |
| Intel + Nvidia | 73        | 19.11%  |
| 1 x AMD        | 65        | 17.02%  |
| 1 x Nvidia     | 34        | 8.9%    |
| Intel + AMD    | 17        | 4.45%   |
| 2 x AMD        | 9         | 2.36%   |
| AMD + Nvidia   | 6         | 1.57%   |
| 1 x SiS        | 2         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 330       | 86.61%  |
| Proprietary | 41        | 10.76%  |
| Unknown     | 10        | 2.62%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 194       | 50.13%  |
| 0.01-0.5   | 74        | 19.12%  |
| 1.01-2.0   | 64        | 16.54%  |
| 0.51-1.0   | 26        | 6.72%   |
| 3.01-4.0   | 20        | 5.17%   |
| 2.01-3.0   | 4         | 1.03%   |
| 5.01-6.0   | 3         | 0.78%   |
| 7.01-8.0   | 1         | 0.26%   |
| 8.01-16.0  | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 77        | 18.16%  |
| LG Display              | 67        | 15.8%   |
| Samsung Electronics     | 58        | 13.68%  |
| Chimei Innolux          | 50        | 11.79%  |
| BOE                     | 45        | 10.61%  |
| Chi Mei Optoelectronics | 24        | 5.66%   |
| Dell                    | 14        | 3.3%    |
| Lenovo                  | 13        | 3.07%   |
| Philips                 | 9         | 2.12%   |
| Sharp                   | 7         | 1.65%   |
| PANDA                   | 7         | 1.65%   |
| LG Philips              | 7         | 1.65%   |
| Hewlett-Packard         | 5         | 1.18%   |
| Apple                   | 5         | 1.18%   |
| CSO                     | 4         | 0.94%   |
| Acer                    | 4         | 0.94%   |
| Goldstar                | 3         | 0.71%   |
| AOC                     | 3         | 0.71%   |
| HannStar                | 2         | 0.47%   |
| CPT                     | 2         | 0.47%   |
| ViewSonic               | 1         | 0.24%   |
| Valve                   | 1         | 0.24%   |
| Toshiba                 | 1         | 0.24%   |
| TMX                     | 1         | 0.24%   |
| Sony                    | 1         | 0.24%   |
| Seiko/Epson             | 1         | 0.24%   |
| Quanta Display          | 1         | 0.24%   |
| Plain Tree Systems      | 1         | 0.24%   |
| Panasonic               | 1         | 0.24%   |
| LGD                     | 1         | 0.24%   |
| JDI                     | 1         | 0.24%   |
| InnoLux Display         | 1         | 0.24%   |
| InfoVision              | 1         | 0.24%   |
| Iiyama                  | 1         | 0.24%   |
| Fujitsu Siemens         | 1         | 0.24%   |
| BenQ                    | 1         | 0.24%   |
| ASUSTek Computer        | 1         | 0.24%   |
| Ancor Communications    | 1         | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 1.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 1.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.17%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 4         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 4         | 0.93%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 4         | 0.93%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 3         | 0.7%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch           | 3         | 0.7%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 3         | 0.7%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3859 1366x768 293x165mm 13.2-inch     | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC314C 1920x1080 344x194mm 15.5-inch    | 2         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3051 1600x900 398x232mm 18.1-inch     | 2         | 0.47%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 2         | 0.47%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch              | 2         | 0.47%   |
| LG Philips LCD Monitor LPLA101 1440x900 367x230mm 17.1-inch              | 2         | 0.47%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch              | 2         | 0.47%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 2         | 0.47%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.47%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.47%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.47%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.47%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.47%   |
| LG Display LCD Monitor LGD0258 1600x900 345x194mm 15.6-inch              | 2         | 0.47%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch              | 2         | 0.47%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch                 | 2         | 0.47%   |
| Lenovo LCD Monitor LEN40E0 1366x768 277x156mm 12.5-inch                  | 2         | 0.47%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 2         | 0.47%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.47%   |
| Dell U2414H DELA0A4 1920x1080 527x296mm 23.8-inch                        | 2         | 0.47%   |
| CSO LCD Monitor CSO1402 2880x1800 302x188mm 14.0-inch                    | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 2         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 2         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 147       | 36.66%  |
| 1366x768 (WXGA)    | 128       | 31.92%  |
| 1280x800 (WXGA)    | 32        | 7.98%   |
| 1600x900 (HD+)     | 21        | 5.24%   |
| 2560x1440 (QHD)    | 13        | 3.24%   |
| 1440x900 (WXGA+)   | 12        | 2.99%   |
| 3840x2160 (4K)     | 10        | 2.49%   |
| 1920x1200 (WUXGA)  | 7         | 1.75%   |
| 1680x1050 (WSXGA+) | 7         | 1.75%   |
| 1024x600           | 4         | 1%      |
| 3440x1440          | 3         | 0.75%   |
| 2880x1800          | 3         | 0.75%   |
| 2560x1600          | 2         | 0.5%    |
| 2160x1440          | 2         | 0.5%    |
| 1280x1024 (SXGA)   | 2         | 0.5%    |
| 800x1280           | 1         | 0.25%   |
| 3840x2400          | 1         | 0.25%   |
| 3200x1800 (QHD+)   | 1         | 0.25%   |
| 2560x1080          | 1         | 0.25%   |
| 2256x1504          | 1         | 0.25%   |
| 1680x945           | 1         | 0.25%   |
| 1280x720 (HD)      | 1         | 0.25%   |
| 1024x768 (XGA)     | 1         | 0.25%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 199       | 46.82%  |
| 14      | 48        | 11.29%  |
| 13      | 47        | 11.06%  |
| 17      | 22        | 5.18%   |
| 24      | 16        | 3.76%   |
| 12      | 12        | 2.82%   |
| 23      | 11        | 2.59%   |
| 27      | 10        | 2.35%   |
| 11      | 10        | 2.35%   |
| 18      | 7         | 1.65%   |
| 22      | 6         | 1.41%   |
| 21      | 5         | 1.18%   |
| 34      | 4         | 0.94%   |
| 10      | 4         | 0.94%   |
| Unknown | 4         | 0.94%   |
| 31      | 3         | 0.71%   |
| 19      | 3         | 0.71%   |
| 20      | 2         | 0.47%   |
| 16      | 2         | 0.47%   |
| 84      | 1         | 0.24%   |
| 58      | 1         | 0.24%   |
| 54      | 1         | 0.24%   |
| 50      | 1         | 0.24%   |
| 40      | 1         | 0.24%   |
| 33      | 1         | 0.24%   |
| 32      | 1         | 0.24%   |
| 26      | 1         | 0.24%   |
| 25      | 1         | 0.24%   |
| 7       | 1         | 0.24%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 268       | 63.66%  |
| 201-300     | 49        | 11.64%  |
| 501-600     | 33        | 7.84%   |
| 351-400     | 28        | 6.65%   |
| 401-500     | 22        | 5.23%   |
| 701-800     | 6         | 1.43%   |
| 601-700     | 5         | 1.19%   |
| Unknown     | 4         | 0.95%   |
| 1001-1500   | 3         | 0.71%   |
| 801-900     | 1         | 0.24%   |
| 1501-2000   | 1         | 0.24%   |
| 1-100       | 1         | 0.24%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 303       | 79.32%  |
| 16/10   | 63        | 16.49%  |
| 3/2     | 5         | 1.31%   |
| 21/9    | 4         | 1.05%   |
| Unknown | 3         | 0.79%   |
| 4/3     | 2         | 0.52%   |
| 5/4     | 1         | 0.26%   |
| 0.67    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 197       | 46.68%  |
| 81-90          | 77        | 18.25%  |
| 201-250        | 31        | 7.35%   |
| 71-80          | 18        | 4.27%   |
| 121-130        | 15        | 3.55%   |
| 61-70          | 12        | 2.84%   |
| 301-350        | 11        | 2.61%   |
| 51-60          | 10        | 2.37%   |
| 351-500        | 9         | 2.13%   |
| 141-150        | 7         | 1.66%   |
| 151-200        | 6         | 1.42%   |
| 131-140        | 6         | 1.42%   |
| 251-300        | 5         | 1.18%   |
| More than 1000 | 4         | 0.95%   |
| 41-50          | 4         | 0.95%   |
| Unknown        | 4         | 0.95%   |
| 111-120        | 2         | 0.47%   |
| 91-100         | 2         | 0.47%   |
| 1-40           | 1         | 0.24%   |
| 501-1000       | 1         | 0.24%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 156       | 37.41%  |
| 101-120       | 125       | 29.98%  |
| 51-100        | 99        | 23.74%  |
| 161-240       | 17        | 4.08%   |
| More than 240 | 11        | 2.64%   |
| 1-50          | 5         | 1.2%    |
| Unknown       | 4         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 302       | 79.27%  |
| 2     | 65        | 17.06%  |
| 0     | 10        | 2.62%   |
| 3     | 4         | 1.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 192       | 30.48%  |
| Intel                             | 191       | 30.32%  |
| Qualcomm Atheros                  | 111       | 17.62%  |
| Broadcom                          | 42        | 6.67%   |
| Ralink                            | 13        | 2.06%   |
| Marvell Technology Group          | 13        | 2.06%   |
| Broadcom Limited                  | 10        | 1.59%   |
| Nvidia                            | 6         | 0.95%   |
| MediaTek                          | 6         | 0.95%   |
| TP-Link                           | 4         | 0.63%   |
| Hewlett-Packard                   | 4         | 0.63%   |
| Xiaomi                            | 3         | 0.48%   |
| Sierra Wireless                   | 3         | 0.48%   |
| Ralink Technology                 | 3         | 0.48%   |
| Qualcomm Atheros Communications   | 3         | 0.48%   |
| JMicron Technology                | 3         | 0.48%   |
| Ericsson Business Mobile Networks | 3         | 0.48%   |
| DisplayLink                       | 3         | 0.48%   |
| Lenovo                            | 2         | 0.32%   |
| Huawei Technologies               | 2         | 0.32%   |
| Fibocom                           | 2         | 0.32%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.16%   |
| T & A Mobile Phones               | 1         | 0.16%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.16%   |
| Sigma Sport                       | 1         | 0.16%   |
| Samsung Electronics               | 1         | 0.16%   |
| Nokia Mobile Phones               | 1         | 0.16%   |
| ICS Advent                        | 1         | 0.16%   |
| Dell                              | 1         | 0.16%   |
| D-Link                            | 1         | 0.16%   |
| Attansic Technology               | 1         | 0.16%   |
| ASIX Electronics                  | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 113       | 15.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 41        | 5.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 3.89%   |
| Intel Wireless 8265 / 8275                                              | 20        | 2.68%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 17        | 2.28%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 12        | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 1.48%   |
| Intel Wireless 7260                                                     | 11        | 1.48%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 1.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 1.34%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 1.21%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 1.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.07%   |
| Intel Wireless 8260                                                     | 8         | 1.07%   |
| Intel Wireless 3165                                                     | 8         | 1.07%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.07%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 0.94%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 7         | 0.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 0.94%   |
| Intel Wireless 7265                                                     | 7         | 0.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 0.94%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 0.94%   |
| Intel Wireless-AC 9260                                                  | 6         | 0.81%   |
| Intel WiFi Link 5100                                                    | 6         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                                   | 6         | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.67%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 0.67%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.67%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 0.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 5         | 0.67%   |
| Intel Ethernet Connection I217-LM                                       | 5         | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                                   | 5         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 0.67%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.67%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 177       | 45.5%   |
| Qualcomm Atheros                | 93        | 23.91%  |
| Realtek Semiconductor           | 46        | 11.83%  |
| Broadcom                        | 30        | 7.71%   |
| Ralink                          | 13        | 3.34%   |
| Broadcom Limited                | 8         | 2.06%   |
| MediaTek                        | 6         | 1.54%   |
| TP-Link                         | 4         | 1.03%   |
| Sierra Wireless                 | 3         | 0.77%   |
| Ralink Technology               | 3         | 0.77%   |
| Qualcomm Atheros Communications | 3         | 0.77%   |
| FIBOCOM                         | 2         | 0.51%   |
| D-Link                          | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 29        | 7.4%    |
| Intel Wireless 8265 / 8275                                              | 20        | 5.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 15        | 3.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 3.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 11        | 2.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 2.81%   |
| Intel Wireless 7260                                                     | 11        | 2.81%   |
| Intel Wi-Fi 6 AX200                                                     | 11        | 2.81%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 2.55%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 9         | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.04%   |
| Intel Wireless 8260                                                     | 8         | 2.04%   |
| Intel Wireless 3165                                                     | 8         | 2.04%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 2.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 1.79%   |
| Intel Wireless 7265                                                     | 7         | 1.79%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.79%   |
| Intel Centrino Wireless-N 2230                                          | 7         | 1.79%   |
| Intel Wireless-AC 9260                                                  | 6         | 1.53%   |
| Intel WiFi Link 5100                                                    | 6         | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.53%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.28%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 1.28%   |
| Intel Centrino Ultimate-N 6300                                          | 5         | 1.28%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.28%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 5         | 1.28%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.02%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 4         | 1.02%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.02%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.77%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 3         | 0.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.77%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 3         | 0.77%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 174       | 51.94%  |
| Intel                    | 80        | 23.88%  |
| Qualcomm Atheros         | 28        | 8.36%   |
| Broadcom                 | 14        | 4.18%   |
| Marvell Technology Group | 13        | 3.88%   |
| Nvidia                   | 6         | 1.79%   |
| Xiaomi                   | 3         | 0.9%    |
| JMicron Technology       | 3         | 0.9%    |
| DisplayLink              | 3         | 0.9%    |
| Lenovo                   | 2         | 0.6%    |
| Broadcom Limited         | 2         | 0.6%    |
| T & A Mobile Phones      | 1         | 0.3%    |
| Samsung Electronics      | 1         | 0.3%    |
| Nokia Mobile Phones      | 1         | 0.3%    |
| ICS Advent               | 1         | 0.3%    |
| Huawei Technologies      | 1         | 0.3%    |
| Attansic Technology      | 1         | 0.3%    |
| ASIX Electronics         | 1         | 0.3%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 113       | 33.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 12.13%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 17        | 5.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 12        | 3.55%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 7         | 2.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 6         | 1.78%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 1.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 1.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 5         | 1.48%   |
| Intel Ethernet Connection I217-LM                                 | 5         | 1.48%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.48%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.48%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller             | 4         | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 4         | 1.18%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.18%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.89%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 3         | 0.89%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.89%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.89%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.89%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.89%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.89%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.89%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.89%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.89%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 3         | 0.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.59%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.59%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.59%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.59%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.59%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.59%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.59%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.59%   |
| DisplayLink USB-C Hybrid UHD Video Dock                           | 2         | 0.59%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express           | 2         | 0.59%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 2         | 0.59%   |
| T & A Mobile Phones A509DL                                        | 1         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 374       | 52.6%   |
| Ethernet | 322       | 45.29%  |
| Modem    | 15        | 2.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 310       | 77.89%  |
| Ethernet | 88        | 22.11%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 302       | 79.89%  |
| 1     | 68        | 17.99%  |
| 0     | 6         | 1.59%   |
| 3     | 2         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 358       | 94.46%  |
| Yes  | 21        | 5.54%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 111       | 39.22%  |
| Qualcomm Atheros Communications | 26        | 9.19%   |
| IMC Networks                    | 25        | 8.83%   |
| Realtek Semiconductor           | 21        | 7.42%   |
| Broadcom                        | 21        | 7.42%   |
| Lite-On Technology              | 14        | 4.95%   |
| Foxconn / Hon Hai               | 11        | 3.89%   |
| Ralink                          | 9         | 3.18%   |
| Hewlett-Packard                 | 8         | 2.83%   |
| Dell                            | 7         | 2.47%   |
| ASUSTek Computer                | 7         | 2.47%   |
| Toshiba                         | 5         | 1.77%   |
| Cambridge Silicon Radio         | 5         | 1.77%   |
| Foxconn International           | 3         | 1.06%   |
| Apple                           | 3         | 1.06%   |
| Taiyo Yuden                     | 2         | 0.71%   |
| Realtek                         | 2         | 0.71%   |
| Micro Star International        | 1         | 0.35%   |
| Fujitsu                         | 1         | 0.35%   |
| Alps Electric                   | 1         | 0.35%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 53        | 18.73%  |
| Intel AX201 Bluetooth                               | 17        | 6.01%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 4.95%   |
| Realtek Bluetooth Radio                             | 12        | 4.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 12        | 4.24%   |
| Intel AX200 Bluetooth                               | 11        | 3.89%   |
| Ralink RT3290 Bluetooth                             | 9         | 3.18%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 9         | 3.18%   |
| IMC Networks Bluetooth Radio                        | 7         | 2.47%   |
| IMC Networks Bluetooth Device                       | 7         | 2.47%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 2.47%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.12%   |
| Lite-On Bluetooth Device                            | 6         | 2.12%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.77%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 5         | 1.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 5         | 1.77%   |
| Broadcom HP Portable SoftSailing                    | 5         | 1.77%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 5         | 1.77%   |
| Realtek RTL8821A Bluetooth                          | 4         | 1.41%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 1.41%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 4         | 1.41%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.06%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 1.06%   |
| Intel AX210 Bluetooth                               | 3         | 1.06%   |
| IMC Networks Wireless_Device                        | 3         | 1.06%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.06%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.06%   |
| Dell Wireless 370 Bluetooth Mini-card               | 3         | 1.06%   |
| Toshiba Integrated Bluetooth HCI                    | 2         | 0.71%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 2         | 0.71%   |
| Realtek Bluetooth Radio                             | 2         | 0.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.71%   |
| Lite-On Wireless_Device                             | 2         | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.71%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.71%   |
| Broadcom HP Portable Bumble Bee                     | 2         | 0.71%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.71%   |
| Apple Bluetooth Host Controller                     | 2         | 0.71%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.35%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 295       | 63.99%  |
| AMD                              | 85        | 18.44%  |
| Nvidia                           | 51        | 11.06%  |
| GN Netcom                        | 5         | 1.08%   |
| C-Media Electronics              | 4         | 0.87%   |
| Silicon Integrated Systems [SiS] | 3         | 0.65%   |
| Lenovo                           | 3         | 0.65%   |
| Samson Technologies              | 2         | 0.43%   |
| JMTek                            | 2         | 0.43%   |
| Trust                            | 1         | 0.22%   |
| Textech International            | 1         | 0.22%   |
| Texas Instruments                | 1         | 0.22%   |
| Realtek Semiconductor            | 1         | 0.22%   |
| Plantronics                      | 1         | 0.22%   |
| Logitech                         | 1         | 0.22%   |
| Hewlett-Packard                  | 1         | 0.22%   |
| Focusrite-Novation               | 1         | 0.22%   |
| DCMT Technology                  | 1         | 0.22%   |
| Behringer.......                 | 1         | 0.22%   |
| AKAI Professional M.I.           | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 52        | 9.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 36        | 6.62%   |
| AMD Family 17h/19h HD Audio Controller                                     | 33        | 6.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 4.41%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 21        | 3.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 21        | 3.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 20        | 3.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 18        | 3.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 17        | 3.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 15        | 2.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 2.57%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 13        | 2.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 11        | 2.02%   |
| AMD FCH Azalia Controller                                                  | 11        | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.84%   |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 1.47%   |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 8         | 1.47%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 8         | 1.47%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 1.47%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 1.29%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 1.29%   |
| AMD High Definition Audio Controller                                       | 7         | 1.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.1%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 1.1%    |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.1%    |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 1.1%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 0.92%   |
| Nvidia MCP79 High Definition Audio                                         | 4         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4         | 0.74%   |
| Intel CM238 HD Audio Controller                                            | 4         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 0.74%   |
| AMD Trinity HDMI Audio Controller                                          | 4         | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.55%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.55%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.55%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.55%   |
| Intel Comet Lake PCH cAVS                                                  | 3         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 61        | 24.11%  |
| Samsung Electronics | 61        | 24.11%  |
| Micron Technology   | 30        | 11.86%  |
| Kingston            | 30        | 11.86%  |
| Unknown             | 26        | 10.28%  |
| Ramaxel Technology  | 7         | 2.77%   |
| Elpida              | 7         | 2.77%   |
| Crucial             | 7         | 2.77%   |
| Unknown (ABCD)      | 4         | 1.58%   |
| Patriot             | 4         | 1.58%   |
| Corsair             | 4         | 1.58%   |
| Nanya Technology    | 3         | 1.19%   |
| A-DATA Technology   | 3         | 1.19%   |
| Unigen              | 1         | 0.4%    |
| SHARETRONIC         | 1         | 0.4%    |
| Atermiter           | 1         | 0.4%    |
| ASint Technology    | 1         | 0.4%    |
| Apacer              | 1         | 0.4%    |
| 48spaces            | 1         | 0.4%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 6         | 2.2%    |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 4         | 1.47%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 4         | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.47%   |
| Micron RAM MT8KTF51264HZ-1G6 4GB SODIMM DDR3 1600MT/s            | 4         | 1.47%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.1%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.1%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.1%    |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 3         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.1%    |
| Patriot RAM PSD34G16002S 4GB SODIMM DDR3 1600MT/s                | 3         | 1.1%    |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 1.1%    |
| Kingston RAM KHX1866C11S3L/8G 8GB SODIMM DDR3 1867MT/s           | 3         | 1.1%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.73%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 2         | 0.73%   |
| Unknown RAM Module 2GB SODIMM 800MT/s                            | 2         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.73%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.73%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.73%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.73%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.73%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM DDR3 4199MT/s            | 2         | 0.73%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.73%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.73%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 2         | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.73%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.73%   |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.73%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.73%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.73%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.73%   |
| Micron RAM 16JSF25664HZ-1G1F1 2GB SODIMM 1067MT/s                | 2         | 0.73%   |
| Micron RAM 16ATF1G64HZ-2G1B1 8GB SODIMM DDR4 2133MT/s            | 2         | 0.73%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 78        | 38.42%  |
| DDR4    | 70        | 34.48%  |
| DDR2    | 19        | 9.36%   |
| LPDDR4  | 12        | 5.91%   |
| SDRAM   | 11        | 5.42%   |
| Unknown | 5         | 2.46%   |
| LPDDR3  | 4         | 1.97%   |
| DDR     | 2         | 0.99%   |
| DRAM    | 1         | 0.49%   |
| DDR5    | 1         | 0.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 187       | 92.57%  |
| Row Of Chips | 12        | 5.94%   |
| Chip         | 3         | 1.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 72        | 31.3%   |
| 8192  | 68        | 29.57%  |
| 2048  | 44        | 19.13%  |
| 16384 | 24        | 10.43%  |
| 1024  | 16        | 6.96%   |
| 32768 | 4         | 1.74%   |
| 512   | 2         | 0.87%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 57        | 25.33%  |
| 2667    | 36        | 16%     |
| 3200    | 23        | 10.22%  |
| 667     | 15        | 6.67%   |
| 2400    | 13        | 5.78%   |
| 2133    | 12        | 5.33%   |
| 1334    | 11        | 4.89%   |
| 1333    | 9         | 4%      |
| Unknown | 8         | 3.56%   |
| 4199    | 6         | 2.67%   |
| 2048    | 5         | 2.22%   |
| 800     | 5         | 2.22%   |
| 1067    | 4         | 1.78%   |
| 4267    | 3         | 1.33%   |
| 4266    | 3         | 1.33%   |
| 1867    | 3         | 1.33%   |
| 8400    | 2         | 0.89%   |
| 4800    | 2         | 0.89%   |
| 3266    | 2         | 0.89%   |
| 533     | 2         | 0.89%   |
| 1639    | 1         | 0.44%   |
| 1066    | 1         | 0.44%   |
| 975     | 1         | 0.44%   |
| 333     | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 1         | 33.33%  |
| Lexmark International | 1         | 33.33%  |
| Hewlett-Packard       | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Samsung M2070 Series              | 1         | 33.33%  |
| Lexmark International 2600 Series | 1         | 33.33%  |
| HP LaserJet CP 1025               | 1         | 33.33%  |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 108       | 33.64%  |
| IMC Networks                           | 34        | 10.59%  |
| Realtek Semiconductor                  | 26        | 8.1%    |
| Acer                                   | 26        | 8.1%    |
| Microdia                               | 24        | 7.48%   |
| Sunplus Innovation Technology          | 18        | 5.61%   |
| Suyin                                  | 14        | 4.36%   |
| Syntek                                 | 11        | 3.43%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 3.12%   |
| Quanta                                 | 9         | 2.8%    |
| Lite-On Technology                     | 6         | 1.87%   |
| Bison Electronics                      | 4         | 1.25%   |
| Silicon Motion                         | 3         | 0.93%   |
| Ricoh                                  | 3         | 0.93%   |
| Logitech                               | 3         | 0.93%   |
| Alcor Micro                            | 3         | 0.93%   |
| Samsung Electronics                    | 2         | 0.62%   |
| Luxvisions Innotech Limited            | 2         | 0.62%   |
| GEMBIRD                                | 2         | 0.62%   |
| Apple                                  | 2         | 0.62%   |
| Z-Star Microelectronics                | 1         | 0.31%   |
| USB Camera                             | 1         | 0.31%   |
| Tripath Technology                     | 1         | 0.31%   |
| SN0002                                 | 1         | 0.31%   |
| Primax Electronics                     | 1         | 0.31%   |
| OmniVision Technologies                | 1         | 0.31%   |
| LG Electronics                         | 1         | 0.31%   |
| Lenovo                                 | 1         | 0.31%   |
| Importek                               | 1         | 0.31%   |
| Elecom                                 | 1         | 0.31%   |
| ALi                                    | 1         | 0.31%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 25        | 7.74%   |
| Microdia Integrated_Webcam_HD            | 13        | 4.02%   |
| Chicony HD WebCam                        | 9         | 2.79%   |
| IMC Networks Integrated Camera           | 8         | 2.48%   |
| Chicony HP HD Webcam [Fixed]             | 8         | 2.48%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 7         | 2.17%   |
| Sunplus Integrated_Webcam_HD             | 6         | 1.86%   |
| Realtek USB2.0 HD UVC WebCam             | 6         | 1.86%   |
| Realtek Integrated_Webcam_HD             | 6         | 1.86%   |
| Acer Lenovo EasyCamera                   | 6         | 1.86%   |
| Acer EasyCamera                          | 6         | 1.86%   |
| Syntek Integrated Camera                 | 5         | 1.55%   |
| IMC Networks USB2.0 HD UVC WebCam        | 5         | 1.55%   |
| Sunplus HP HD Webcam [Fixed]             | 4         | 1.24%   |
| Quanta HP HD Camera                      | 4         | 1.24%   |
| Microdia Integrated Webcam               | 4         | 1.24%   |
| Lite-On HP HD Camera                     | 4         | 1.24%   |
| IMC Networks Integrated Webcam           | 4         | 1.24%   |
| Chicony USB2.0 VGA UVC WebCam            | 4         | 1.24%   |
| Chicony USB 2.0 Camera                   | 4         | 1.24%   |
| Chicony Lenovo EasyCamera                | 4         | 1.24%   |
| Acer Lenovo Integrated Webcam            | 4         | 1.24%   |
| Syntek Lenovo EasyCamera                 | 3         | 0.93%   |
| Suyin HP Webcam                          | 3         | 0.93%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 3         | 0.93%   |
| Chicony USB2.0 HD UVC WebCam             | 3         | 0.93%   |
| Chicony USB2.0 0.3M UVC WebCam           | 3         | 0.93%   |
| Chicony TOSHIBA Web Camera - HD          | 3         | 0.93%   |
| Chicony Thinkpad T430 camera             | 3         | 0.93%   |
| Chicony Integrated Camera (1280x720@30)  | 3         | 0.93%   |
| Chicony HP TrueVision HD Camera          | 3         | 0.93%   |
| Chicony HP HD Camera                     | 3         | 0.93%   |
| Chicony CNF9055 Toshiba Webcam           | 3         | 0.93%   |
| Chicony 2.0M UVC Webcam / CNF7129        | 3         | 0.93%   |
| Acer Integrated Camera                   | 3         | 0.93%   |
| Syntek EasyCamera                        | 2         | 0.62%   |
| Suyin Sony Visual Communication Camera   | 2         | 0.62%   |
| Sunplus HD WebCam                        | 2         | 0.62%   |
| Sunplus ASUS Webcam                      | 2         | 0.62%   |
| Samsung Galaxy A5 (MTP)                  | 2         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 38        | 47.5%   |
| Synaptics                  | 20        | 25%     |
| AuthenTec                  | 8         | 10%     |
| Shenzhen Goodix Technology | 5         | 6.25%   |
| LighTuning Technology      | 4         | 5%      |
| STMicroelectronics         | 2         | 2.5%    |
| Elan Microelectronics      | 2         | 2.5%    |
| Upek                       | 1         | 1.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 12.5%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 10%     |
| Validity Sensors VFS491                                                    | 5         | 6.25%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 5%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 5%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 5%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 3.75%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 3.75%   |
| Shenzhen Goodix  Fingerprint Device                                        | 3         | 3.75%   |
| AuthenTec AES2810                                                          | 3         | 3.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.5%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2.5%    |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.5%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 2.5%    |
| Synaptics  WBDI                                                            | 2         | 2.5%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 2.5%    |
| STMicroelectronics Fingerprint Reader                                      | 2         | 2.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.5%    |
| Elan ELAN:Fingerprint                                                      | 2         | 2.5%    |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 1.25%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.25%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.25%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.25%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 1.25%   |
| AuthenTec AES1600                                                          | 1         | 1.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 42.11%  |
| Alcor Micro | 13        | 34.21%  |
| O2 Micro    | 5         | 13.16%  |
| Lenovo      | 2         | 5.26%   |
| BIT4ID      | 2         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 34.21%  |
| Broadcom 5880                                                                | 6         | 15.79%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 13.16%  |
| Broadcom 58200                                                               | 4         | 10.53%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 7.89%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 5.26%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.26%   |
| BIT4ID miniLector EVO                                                        | 2         | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 213       | 55.04%  |
| 1     | 139       | 35.92%  |
| 2     | 29        | 7.49%   |
| 3     | 5         | 1.29%   |
| 4     | 1         | 0.26%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 80        | 38.1%   |
| Graphics card            | 35        | 16.67%  |
| Chipcard                 | 31        | 14.76%  |
| Bluetooth                | 11        | 5.24%   |
| Net/wireless             | 10        | 4.76%   |
| Storage                  | 8         | 3.81%   |
| Multimedia controller    | 8         | 3.81%   |
| Modem                    | 6         | 2.86%   |
| Communication controller | 6         | 2.86%   |
| Card reader              | 5         | 2.38%   |
| Camera                   | 4         | 1.9%    |
| Network                  | 2         | 0.95%   |
| Flash memory             | 2         | 0.95%   |
| Storage/ide              | 1         | 0.48%   |
| Sound                    | 1         | 0.48%   |

