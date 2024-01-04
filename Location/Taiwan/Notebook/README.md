Linux in Taiwan - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Taiwan.

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

Total: 425

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 430 G2              | [c56ad1ad48](https://linux-hardware.org/?probe=c56ad1ad48) | Jan 02, 2024 |
| Acer          | Aspire SW5-012              | [efc348dbe0](https://linux-hardware.org/?probe=efc348dbe0) | Dec 31, 2023 |
| Google        | Delbin                      | [51a51a978d](https://linux-hardware.org/?probe=51a51a978d) | Dec 31, 2023 |
| Valve         | Galileo                     | [e21296767e](https://linux-hardware.org/?probe=e21296767e) | Dec 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [08e2f4eacc](https://linux-hardware.org/?probe=08e2f4eacc) | Dec 25, 2023 |
| Dynabook      | CS40L-HB                    | [da68e155cd](https://linux-hardware.org/?probe=da68e155cd) | Dec 20, 2023 |
| Acer          | Swift SF314-57G             | [b822161722](https://linux-hardware.org/?probe=b822161722) | Dec 19, 2023 |
| ASUSTek       | X450CC                      | [0af8e99fe6](https://linux-hardware.org/?probe=0af8e99fe6) | Dec 19, 2023 |
| ASUSTek       | X450CC                      | [238d032255](https://linux-hardware.org/?probe=238d032255) | Dec 19, 2023 |
| HP            | Pavilion 15                 | [8ea538629f](https://linux-hardware.org/?probe=8ea538629f) | Dec 17, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [5f19b6ce4f](https://linux-hardware.org/?probe=5f19b6ce4f) | Dec 16, 2023 |
| Acer          | Aspire V5-431               | [6e56833b2a](https://linux-hardware.org/?probe=6e56833b2a) | Dec 09, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [21847052d3](https://linux-hardware.org/?probe=21847052d3) | Dec 07, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [68784031ca](https://linux-hardware.org/?probe=68784031ca) | Dec 05, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [75603d3c20](https://linux-hardware.org/?probe=75603d3c20) | Dec 04, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [b5086b8a65](https://linux-hardware.org/?probe=b5086b8a65) | Dec 01, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [13d2cf2679](https://linux-hardware.org/?probe=13d2cf2679) | Nov 30, 2023 |
| CHIPHD        | NT125D                      | [44dab561a1](https://linux-hardware.org/?probe=44dab561a1) | Nov 21, 2023 |
| Dell          | Latitude 5440               | [107b422b2c](https://linux-hardware.org/?probe=107b422b2c) | Nov 20, 2023 |
| Dell          | Inspiron 7375               | [b72b8abe13](https://linux-hardware.org/?probe=b72b8abe13) | Nov 19, 2023 |
| Dell          | Latitude 5440               | [ed0b97c0a4](https://linux-hardware.org/?probe=ed0b97c0a4) | Nov 19, 2023 |
| Dell          | Latitude 5440               | [1f337ab4b1](https://linux-hardware.org/?probe=1f337ab4b1) | Nov 15, 2023 |
| Acer          | Aspire V3-471G              | [f027c1d470](https://linux-hardware.org/?probe=f027c1d470) | Nov 14, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [51e8be0935](https://linux-hardware.org/?probe=51e8be0935) | Nov 12, 2023 |
| MSI           | GL65 9SD                    | [d831c2e78e](https://linux-hardware.org/?probe=d831c2e78e) | Nov 06, 2023 |
| Acer          | Aspire A514-55              | [b9ad0e270f](https://linux-hardware.org/?probe=b9ad0e270f) | Nov 04, 2023 |
| Acer          | Aspire A514-55              | [985bf8e919](https://linux-hardware.org/?probe=985bf8e919) | Nov 01, 2023 |
| Dell          | G7 7590                     | [90cbef58c2](https://linux-hardware.org/?probe=90cbef58c2) | Oct 27, 2023 |
| Gigabyte      | AORUS 5 SE                  | [bf6473691f](https://linux-hardware.org/?probe=bf6473691f) | Oct 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9403CVA... | [eaffd30f59](https://linux-hardware.org/?probe=eaffd30f59) | Oct 21, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9403CVA... | [aafd893b0d](https://linux-hardware.org/?probe=aafd893b0d) | Oct 21, 2023 |
| MSI           | Alpha 17 C7VG               | [aa9ed0c963](https://linux-hardware.org/?probe=aa9ed0c963) | Oct 13, 2023 |
| MSI           | Alpha 17 C7VG               | [3cf39a38db](https://linux-hardware.org/?probe=3cf39a38db) | Oct 12, 2023 |
| Acer          | Swift SFX14-41G             | [ad1ae13902](https://linux-hardware.org/?probe=ad1ae13902) | Oct 11, 2023 |
| MSI           | GL65 9SD                    | [0e94bdcf1d](https://linux-hardware.org/?probe=0e94bdcf1d) | Oct 05, 2023 |
| MSI           | GL65 9SD                    | [32b5c9a302](https://linux-hardware.org/?probe=32b5c9a302) | Oct 05, 2023 |
| CHIPHD        | NT125D                      | [7e966b32de](https://linux-hardware.org/?probe=7e966b32de) | Sep 26, 2023 |
| Lenovo        | ThinkPad T450 20BV000BUS    | [3959de124c](https://linux-hardware.org/?probe=3959de124c) | Sep 14, 2023 |
| Toshiba       | Satellite L640              | [ac5a264fea](https://linux-hardware.org/?probe=ac5a264fea) | Sep 12, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [55b8608662](https://linux-hardware.org/?probe=55b8608662) | Sep 08, 2023 |
| Gigabyte      | GB-BKi3A-7100               | [40c832efb9](https://linux-hardware.org/?probe=40c832efb9) | Sep 04, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [b132ff749e](https://linux-hardware.org/?probe=b132ff749e) | Sep 01, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [ed4fafcabd](https://linux-hardware.org/?probe=ed4fafcabd) | Aug 31, 2023 |
| Sony          | VGN-C15TP_W                 | [591d0b778e](https://linux-hardware.org/?probe=591d0b778e) | Aug 30, 2023 |
| Sony          | VGN-C15TP_W                 | [a63433e04d](https://linux-hardware.org/?probe=a63433e04d) | Aug 25, 2023 |
| Acer          | Swift SFX14-41G             | [576626db19](https://linux-hardware.org/?probe=576626db19) | Aug 17, 2023 |
| Acer          | Aspire one                  | [47131c09b2](https://linux-hardware.org/?probe=47131c09b2) | Aug 16, 2023 |
| Lenovo        | IdeaPad 300-14ISK 80Q6      | [a94c8dc31f](https://linux-hardware.org/?probe=a94c8dc31f) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [66c997fdec](https://linux-hardware.org/?probe=66c997fdec) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480 20L5S2J200    | [e57e76260c](https://linux-hardware.org/?probe=e57e76260c) | Aug 16, 2023 |
| ASUSTek       | UX31LA                      | [0695e3bb09](https://linux-hardware.org/?probe=0695e3bb09) | Aug 08, 2023 |
| MSI           | GL65 9SD                    | [b3ef4f1363](https://linux-hardware.org/?probe=b3ef4f1363) | Aug 07, 2023 |
| MSI           | GL65 9SD                    | [2539f4ad7a](https://linux-hardware.org/?probe=2539f4ad7a) | Aug 06, 2023 |
| MSI           | PS63 Modern 8M              | [96e7b96787](https://linux-hardware.org/?probe=96e7b96787) | Jul 27, 2023 |
| MSI           | GL65 9SD                    | [a3f9991e22](https://linux-hardware.org/?probe=a3f9991e22) | Jul 23, 2023 |
| MSI           | GL65 9SD                    | [57c6b0a7dd](https://linux-hardware.org/?probe=57c6b0a7dd) | Jul 15, 2023 |
| HP            | 250 G5 Notebook PC          | [030ecef01c](https://linux-hardware.org/?probe=030ecef01c) | Jul 08, 2023 |
| HP            | 250 G5 Notebook PC          | [56683a6866](https://linux-hardware.org/?probe=56683a6866) | Jul 08, 2023 |
| Google        | Cave                        | [cc3b1bb1a3](https://linux-hardware.org/?probe=cc3b1bb1a3) | Jun 24, 2023 |
| Google        | Cave                        | [199eb4826d](https://linux-hardware.org/?probe=199eb4826d) | Jun 24, 2023 |
| Acer          | Aspire A515-53G             | [430cfefc6a](https://linux-hardware.org/?probe=430cfefc6a) | Jun 21, 2023 |
| Lenovo        | ThinkPad X230 2324CD1       | [9ee6ed4144](https://linux-hardware.org/?probe=9ee6ed4144) | Jun 18, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | [dd5aaca858](https://linux-hardware.org/?probe=dd5aaca858) | Jun 15, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [ba129cd52d](https://linux-hardware.org/?probe=ba129cd52d) | Jun 11, 2023 |
| Acidanther... | MacBookPro15,2              | [fb30b2eb35](https://linux-hardware.org/?probe=fb30b2eb35) | Jun 10, 2023 |
| Lenovo        | Z50-70 20354                | [05a473a2be](https://linux-hardware.org/?probe=05a473a2be) | Jun 06, 2023 |
| Apple         | MacBookPro7,1               | [e92db65759](https://linux-hardware.org/?probe=e92db65759) | Jun 05, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a3089228b1](https://linux-hardware.org/?probe=a3089228b1) | Jun 05, 2023 |
| ASUSTek       | UX430UNR                    | [00ab711e0a](https://linux-hardware.org/?probe=00ab711e0a) | Jun 02, 2023 |
| Apple         | MacBookPro7,1               | [47ac3b9c43](https://linux-hardware.org/?probe=47ac3b9c43) | May 28, 2023 |
| Acer          | Swift SF514-54GT            | [dd79b67b18](https://linux-hardware.org/?probe=dd79b67b18) | May 27, 2023 |
| Apple         | MacBookPro7,1               | [324a8d5c88](https://linux-hardware.org/?probe=324a8d5c88) | May 22, 2023 |
| Apple         | MacBookPro7,1               | [88830e9fe8](https://linux-hardware.org/?probe=88830e9fe8) | May 22, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [fb58a4d348](https://linux-hardware.org/?probe=fb58a4d348) | May 14, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | [02fb267cbc](https://linux-hardware.org/?probe=02fb267cbc) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | [e12a1d28ba](https://linux-hardware.org/?probe=e12a1d28ba) | May 06, 2023 |
| HP            | 250 G5 Notebook PC          | [4cb6025c16](https://linux-hardware.org/?probe=4cb6025c16) | May 03, 2023 |
| Apple         | MacBookPro11,1              | [7309ce024f](https://linux-hardware.org/?probe=7309ce024f) | Apr 25, 2023 |
| Valve         | Jupiter                     | [b2a94c7310](https://linux-hardware.org/?probe=b2a94c7310) | Apr 18, 2023 |
| Valve         | Jupiter                     | [965de2bcc4](https://linux-hardware.org/?probe=965de2bcc4) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14IAP7 82S... | [c0901def8d](https://linux-hardware.org/?probe=c0901def8d) | Apr 10, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [c8173d40cd](https://linux-hardware.org/?probe=c8173d40cd) | Apr 09, 2023 |
| Dell          | Latitude 7490               | [01957ea955](https://linux-hardware.org/?probe=01957ea955) | Apr 07, 2023 |
| Toshiba       | Satellite L850              | [2635da1e14](https://linux-hardware.org/?probe=2635da1e14) | Apr 03, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [649b881439](https://linux-hardware.org/?probe=649b881439) | Mar 25, 2023 |
| Insyde        | CherryTrail                 | [9e658f67a2](https://linux-hardware.org/?probe=9e658f67a2) | Mar 25, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [882f82cf2c](https://linux-hardware.org/?probe=882f82cf2c) | Mar 20, 2023 |
| Acer          | Aspire V3-571G              | [6aee8060e9](https://linux-hardware.org/?probe=6aee8060e9) | Mar 17, 2023 |
| Valve         | Jupiter                     | [db30abe51b](https://linux-hardware.org/?probe=db30abe51b) | Mar 13, 2023 |
| Toshiba       | Satellite C665              | [e95e34e3ba](https://linux-hardware.org/?probe=e95e34e3ba) | Mar 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f3075e65e](https://linux-hardware.org/?probe=7f3075e65e) | Mar 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | [2e864ba25e](https://linux-hardware.org/?probe=2e864ba25e) | Mar 08, 2023 |
| Valve         | Jupiter                     | [367bc56a15](https://linux-hardware.org/?probe=367bc56a15) | Mar 05, 2023 |
| Valve         | Jupiter                     | [c329f5f1c1](https://linux-hardware.org/?probe=c329f5f1c1) | Mar 05, 2023 |
| Valve         | Jupiter                     | [2143a36dc5](https://linux-hardware.org/?probe=2143a36dc5) | Feb 28, 2023 |
| Acer          | Swift SF514-54GT            | [dbccc5afa9](https://linux-hardware.org/?probe=dbccc5afa9) | Feb 23, 2023 |
| ASUSTek       | X202E                       | [6627e10e70](https://linux-hardware.org/?probe=6627e10e70) | Feb 19, 2023 |
| Dell          | Latitude E6320              | [467b45072e](https://linux-hardware.org/?probe=467b45072e) | Feb 19, 2023 |
| Lenovo        | ThinkPad X61 7673D13        | [b5399b39de](https://linux-hardware.org/?probe=b5399b39de) | Feb 19, 2023 |
| Acer          | Swift SF514-54GT            | [b7e961dae3](https://linux-hardware.org/?probe=b7e961dae3) | Feb 13, 2023 |
| Valve         | Jupiter                     | [e5f4ad1053](https://linux-hardware.org/?probe=e5f4ad1053) | Feb 12, 2023 |
| ASUSTek       | G73Sw                       | [42e7c32817](https://linux-hardware.org/?probe=42e7c32817) | Feb 06, 2023 |
| HP            | Notebook                    | [41f5c97a09](https://linux-hardware.org/?probe=41f5c97a09) | Feb 06, 2023 |
| AVITA         | NE14A2                      | [c5d9f8e3ac](https://linux-hardware.org/?probe=c5d9f8e3ac) | Feb 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [37059de5b7](https://linux-hardware.org/?probe=37059de5b7) | Jan 27, 2023 |
| MSI           | Alpha 15 B5EEK              | [d815a80782](https://linux-hardware.org/?probe=d815a80782) | Jan 24, 2023 |
| MSI           | Alpha 15 B5EEK              | [d2c9a02f60](https://linux-hardware.org/?probe=d2c9a02f60) | Jan 24, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [335275777a](https://linux-hardware.org/?probe=335275777a) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [e40bb2f01f](https://linux-hardware.org/?probe=e40bb2f01f) | Jan 23, 2023 |
| Dell          | Latitude 7490               | [31789ae630](https://linux-hardware.org/?probe=31789ae630) | Jan 23, 2023 |
| HP            | ProBook 430 G2              | [24a0f33638](https://linux-hardware.org/?probe=24a0f33638) | Jan 22, 2023 |
| HP            | Compaq 6510b (GM108UC#AB... | [45ae9ca3c9](https://linux-hardware.org/?probe=45ae9ca3c9) | Jan 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [958ecc4388](https://linux-hardware.org/?probe=958ecc4388) | Jan 15, 2023 |
| Gigabyte      | GB-BKi3A-7100               | [8263d65b20](https://linux-hardware.org/?probe=8263d65b20) | Jan 08, 2023 |
| Gigabyte      | G5 GE                       | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| System76      | Lemur Pro                   | [36156d9aa7](https://linux-hardware.org/?probe=36156d9aa7) | Jan 07, 2023 |
| Dell          | Inspiron 13 5320            | [0007a36030](https://linux-hardware.org/?probe=0007a36030) | Jan 07, 2023 |
| Timi          | Mi Laptop Pro 15            | [7ea6f8ee94](https://linux-hardware.org/?probe=7ea6f8ee94) | Jan 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [9e535c1e8e](https://linux-hardware.org/?probe=9e535c1e8e) | Jan 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [2abdc57712](https://linux-hardware.org/?probe=2abdc57712) | Dec 31, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [632515014d](https://linux-hardware.org/?probe=632515014d) | Dec 31, 2022 |
| MSI           | Modern 15 A5M               | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| MSI           | Modern 15 A5M               | [1e7182cb70](https://linux-hardware.org/?probe=1e7182cb70) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [ee7b1d707c](https://linux-hardware.org/?probe=ee7b1d707c) | Dec 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [7c8560a87e](https://linux-hardware.org/?probe=7c8560a87e) | Dec 25, 2022 |
| Acer          | Aspire 4750                 | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [9462031346](https://linux-hardware.org/?probe=9462031346) | Dec 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [7eb6658e3a](https://linux-hardware.org/?probe=7eb6658e3a) | Dec 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [7a14c8194f](https://linux-hardware.org/?probe=7a14c8194f) | Dec 20, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a767e0fbf0](https://linux-hardware.org/?probe=a767e0fbf0) | Dec 16, 2022 |
| Lenovo        | ThinkPad W530 243858U       | [9dc4fb1abb](https://linux-hardware.org/?probe=9dc4fb1abb) | Dec 16, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | [44484456f8](https://linux-hardware.org/?probe=44484456f8) | Dec 14, 2022 |
| ASUSTek       | PU403UA                     | [20007b4296](https://linux-hardware.org/?probe=20007b4296) | Dec 05, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [55d95654c4](https://linux-hardware.org/?probe=55d95654c4) | Nov 30, 2022 |
| HP            | ProBook 430 G8 Notebook ... | [8a773e7358](https://linux-hardware.org/?probe=8a773e7358) | Nov 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | [678cfec38b](https://linux-hardware.org/?probe=678cfec38b) | Nov 20, 2022 |
| MSI           | GE62 6QD                    | [3d2dd5419a](https://linux-hardware.org/?probe=3d2dd5419a) | Nov 18, 2022 |
| ASUSTek       | X550VX                      | [8e55592803](https://linux-hardware.org/?probe=8e55592803) | Nov 15, 2022 |
| Acer          | Swift SFX14-41G             | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | U270DX                      | [2a68a6ba02](https://linux-hardware.org/?probe=2a68a6ba02) | Nov 10, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [52080bf6ef](https://linux-hardware.org/?probe=52080bf6ef) | Nov 09, 2022 |
| HP            | EliteBook x360 1030 G4      | [4fa71c1d6d](https://linux-hardware.org/?probe=4fa71c1d6d) | Nov 09, 2022 |
| Dell          | Inspiron 13 5320            | [9ac52708ad](https://linux-hardware.org/?probe=9ac52708ad) | Oct 17, 2022 |
| Intel Clie... | LAPRC710                    | [4a1e71b56a](https://linux-hardware.org/?probe=4a1e71b56a) | Oct 15, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [e940ddf8a7](https://linux-hardware.org/?probe=e940ddf8a7) | Oct 12, 2022 |
| ASUSTek       | PU403UA                     | [8bf4879487](https://linux-hardware.org/?probe=8bf4879487) | Oct 04, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CBA    | [4cad2a770c](https://linux-hardware.org/?probe=4cad2a770c) | Sep 30, 2022 |
| Lenovo        | ThinkPad T480s 20L7001YU... | [929514123f](https://linux-hardware.org/?probe=929514123f) | Sep 30, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c188e2c5b5](https://linux-hardware.org/?probe=c188e2c5b5) | Sep 24, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [5503282548](https://linux-hardware.org/?probe=5503282548) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | [c0b89ea222](https://linux-hardware.org/?probe=c0b89ea222) | Aug 26, 2022 |
| Sony          | SVS15115FWB                 | [6844bd3288](https://linux-hardware.org/?probe=6844bd3288) | Aug 21, 2022 |
| Sony          | SVS15115FWB                 | [2fb1c4ab2d](https://linux-hardware.org/?probe=2fb1c4ab2d) | Aug 20, 2022 |
| Acer          | TravelMate P653-M           | [1e33abf031](https://linux-hardware.org/?probe=1e33abf031) | Aug 17, 2022 |
| Dell          | Inspiron 13 5320            | [cee0d5a717](https://linux-hardware.org/?probe=cee0d5a717) | Aug 14, 2022 |
| Dell          | Vostro 3525                 | [d6630abc3a](https://linux-hardware.org/?probe=d6630abc3a) | Aug 03, 2022 |
| ASUSTek       | K501LX                      | [8ea0c7daa9](https://linux-hardware.org/?probe=8ea0c7daa9) | Jul 30, 2022 |
| Acer          | Aspire A515-57G             | [a44d178033](https://linux-hardware.org/?probe=a44d178033) | Jul 30, 2022 |
| LG Electro... | LE50-5BC6H1                 | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Acer          | Aspire K50-20               | [1f4543c39e](https://linux-hardware.org/?probe=1f4543c39e) | Jul 20, 2022 |
| Acer          | Aspire K50-20               | [3f0e68ecf5](https://linux-hardware.org/?probe=3f0e68ecf5) | Jul 20, 2022 |
| Acer          | TravelMate 8371             | [4af529e1c4](https://linux-hardware.org/?probe=4af529e1c4) | Jul 20, 2022 |
| Acer          | Aspire A515-45              | [4189e96860](https://linux-hardware.org/?probe=4189e96860) | Jul 19, 2022 |
| Dell          | Inspiron 5577               | [54fda2d2bc](https://linux-hardware.org/?probe=54fda2d2bc) | Jul 16, 2022 |
| Acer          | Aspire A515-57G             | [43a9aeb04d](https://linux-hardware.org/?probe=43a9aeb04d) | Jul 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | [5f3670ea60](https://linux-hardware.org/?probe=5f3670ea60) | Jul 12, 2022 |
| Dell          | Vostro 3525                 | [2174c6314a](https://linux-hardware.org/?probe=2174c6314a) | Jul 11, 2022 |
| Dell          | Vostro 3525                 | [ff38c8714c](https://linux-hardware.org/?probe=ff38c8714c) | Jul 11, 2022 |
| Acer          | Swift SF514-54GT            | [554171275d](https://linux-hardware.org/?probe=554171275d) | Jul 07, 2022 |
| Acer          | Aspire A315-55G             | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Dell          | Vostro 5625                 | [0a047126ba](https://linux-hardware.org/?probe=0a047126ba) | Jun 30, 2022 |
| MSI           | PE60 6QE                    | [4c7beba4e2](https://linux-hardware.org/?probe=4c7beba4e2) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [43a27bb2dd](https://linux-hardware.org/?probe=43a27bb2dd) | Jun 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [f993d31672](https://linux-hardware.org/?probe=f993d31672) | Jun 22, 2022 |
| Dell          | Inspiron 14 5425            | [16e98704b5](https://linux-hardware.org/?probe=16e98704b5) | Jun 22, 2022 |
| Acer          | Aspire R7-371T              | [b791797ef3](https://linux-hardware.org/?probe=b791797ef3) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | [d573a80e21](https://linux-hardware.org/?probe=d573a80e21) | Jun 12, 2022 |
| Sony          | SVS15115FWB                 | [da41314683](https://linux-hardware.org/?probe=da41314683) | Jun 09, 2022 |
| Sony          | SVS15115FWB                 | [ab97043dbe](https://linux-hardware.org/?probe=ab97043dbe) | Jun 09, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | [04e81b8b3f](https://linux-hardware.org/?probe=04e81b8b3f) | Jun 04, 2022 |
| Dell          | Latitude 5420               | [fedd7d10fb](https://linux-hardware.org/?probe=fedd7d10fb) | May 25, 2022 |
| Lex           | 3I610DW                     | [145688ea36](https://linux-hardware.org/?probe=145688ea36) | May 17, 2022 |
| Lex           | 3I610DW                     | [8baf27bb6a](https://linux-hardware.org/?probe=8baf27bb6a) | May 17, 2022 |
| Lex           | 3I610DW                     | [6c61eabd7c](https://linux-hardware.org/?probe=6c61eabd7c) | May 17, 2022 |
| Lex           | 3I610DW                     | [8a75530d17](https://linux-hardware.org/?probe=8a75530d17) | May 17, 2022 |
| ASUSTek       | K53SD                       | [0c04c6cb24](https://linux-hardware.org/?probe=0c04c6cb24) | May 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [1863683cb7](https://linux-hardware.org/?probe=1863683cb7) | May 06, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [1c94d4293a](https://linux-hardware.org/?probe=1c94d4293a) | May 02, 2022 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [b61c12247c](https://linux-hardware.org/?probe=b61c12247c) | May 02, 2022 |
| HP            | 15                          | [5d7a22faa6](https://linux-hardware.org/?probe=5d7a22faa6) | Apr 28, 2022 |
| Acer          | Aspire 1410                 | [0399a90ade](https://linux-hardware.org/?probe=0399a90ade) | Apr 23, 2022 |
| HP            | ProBook 430 G7              | [a084a48023](https://linux-hardware.org/?probe=a084a48023) | Apr 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [1a35138280](https://linux-hardware.org/?probe=1a35138280) | Apr 14, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [b6834625e2](https://linux-hardware.org/?probe=b6834625e2) | Apr 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [dccdc2c9f5](https://linux-hardware.org/?probe=dccdc2c9f5) | Apr 12, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [f8c3b429a2](https://linux-hardware.org/?probe=f8c3b429a2) | Apr 09, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | [369aac0795](https://linux-hardware.org/?probe=369aac0795) | Apr 09, 2022 |
| Acer          | Aspire 1410                 | [41ed1dae3d](https://linux-hardware.org/?probe=41ed1dae3d) | Apr 08, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | [46b4d12526](https://linux-hardware.org/?probe=46b4d12526) | Apr 04, 2022 |
| ASUSTek       | X580VD                      | [192125a71f](https://linux-hardware.org/?probe=192125a71f) | Mar 29, 2022 |
| Acer          | Aspire 4750                 | [b89fa9f260](https://linux-hardware.org/?probe=b89fa9f260) | Mar 23, 2022 |
| Acer          | Aspire 4750                 | [ce61872360](https://linux-hardware.org/?probe=ce61872360) | Mar 23, 2022 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | [0228881558](https://linux-hardware.org/?probe=0228881558) | Mar 18, 2022 |
| Acer          | Swift SF514-54GT            | [a170593a67](https://linux-hardware.org/?probe=a170593a67) | Mar 13, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [ea52efd6b6](https://linux-hardware.org/?probe=ea52efd6b6) | Mar 07, 2022 |
| MSI           | GV72 8RC                    | [60382ef4e5](https://linux-hardware.org/?probe=60382ef4e5) | Feb 25, 2022 |
| MSI           | GV72 8RC                    | [9cfacc57c2](https://linux-hardware.org/?probe=9cfacc57c2) | Feb 24, 2022 |
| MSI           | P65 Creator 9SD             | [093c9b9f41](https://linux-hardware.org/?probe=093c9b9f41) | Feb 24, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [076c8f6e01](https://linux-hardware.org/?probe=076c8f6e01) | Feb 23, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [85c09f63f0](https://linux-hardware.org/?probe=85c09f63f0) | Feb 23, 2022 |
| MSI           | P65 Creator 9SD             | [2782f833c9](https://linux-hardware.org/?probe=2782f833c9) | Feb 23, 2022 |
| HP            | DevX                        | [8dc3513586](https://linux-hardware.org/?probe=8dc3513586) | Feb 16, 2022 |
| HP            | DevX                        | [c6f8c8e65b](https://linux-hardware.org/?probe=c6f8c8e65b) | Feb 16, 2022 |
| CJSCOPE       | Z Series                    | [c594abda0a](https://linux-hardware.org/?probe=c594abda0a) | Feb 16, 2022 |
| Dell          | Latitude 5420               | [3c5cf0b4e7](https://linux-hardware.org/?probe=3c5cf0b4e7) | Feb 07, 2022 |
| Dell          | Latitude E7450              | [dd81e34279](https://linux-hardware.org/?probe=dd81e34279) | Feb 07, 2022 |
| Apple         | MacBookPro11,2              | [9d00f74637](https://linux-hardware.org/?probe=9d00f74637) | Feb 05, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| Intel Clie... | LAPBC710                    | [76dff27038](https://linux-hardware.org/?probe=76dff27038) | Feb 02, 2022 |
| Intel Clie... | LAPBC710                    | [a4c71279a4](https://linux-hardware.org/?probe=a4c71279a4) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [0a04b2d1b1](https://linux-hardware.org/?probe=0a04b2d1b1) | Jan 31, 2022 |
| Acer          | Aspire V3-571G              | [43011b8d27](https://linux-hardware.org/?probe=43011b8d27) | Jan 30, 2022 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e6af97e09c](https://linux-hardware.org/?probe=e6af97e09c) | Jan 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f653016830](https://linux-hardware.org/?probe=f653016830) | Jan 28, 2022 |
| ASUSTek       | PU403UA                     | [25ac7ce226](https://linux-hardware.org/?probe=25ac7ce226) | Jan 28, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [40d8a83107](https://linux-hardware.org/?probe=40d8a83107) | Jan 25, 2022 |
| Gigabyte      | P65                         | [4664ba9c41](https://linux-hardware.org/?probe=4664ba9c41) | Jan 17, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [fb4c60c7b1](https://linux-hardware.org/?probe=fb4c60c7b1) | Jan 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [0b302317eb](https://linux-hardware.org/?probe=0b302317eb) | Jan 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [94988f80b6](https://linux-hardware.org/?probe=94988f80b6) | Jan 09, 2022 |
| Dell          | Inspiron 5480               | [217737fa73](https://linux-hardware.org/?probe=217737fa73) | Dec 24, 2021 |
| Dell          | System Vostro 3450          | [482adf74be](https://linux-hardware.org/?probe=482adf74be) | Dec 21, 2021 |
| Dell          | System Vostro 3450          | [965939d30a](https://linux-hardware.org/?probe=965939d30a) | Dec 21, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [041e50f6a8](https://linux-hardware.org/?probe=041e50f6a8) | Dec 20, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [f9fbdf780e](https://linux-hardware.org/?probe=f9fbdf780e) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | [2e9fd50292](https://linux-hardware.org/?probe=2e9fd50292) | Dec 20, 2021 |
| Acer          | Aspire F5-573G              | [452b8c0ac4](https://linux-hardware.org/?probe=452b8c0ac4) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0f6fd49686](https://linux-hardware.org/?probe=0f6fd49686) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [aae6578de1](https://linux-hardware.org/?probe=aae6578de1) | Dec 16, 2021 |
| Unknown       | Unknown                     | [d07ab607e1](https://linux-hardware.org/?probe=d07ab607e1) | Dec 08, 2021 |
| Unknown       | Unknown                     | [8705e3aea1](https://linux-hardware.org/?probe=8705e3aea1) | Dec 07, 2021 |
| Dell          | Vostro 14 5410              | [ef6f4cf593](https://linux-hardware.org/?probe=ef6f4cf593) | Dec 05, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [2965330cf0](https://linux-hardware.org/?probe=2965330cf0) | Dec 02, 2021 |
| Dell          | Vostro 14 5410              | [6ab102bc84](https://linux-hardware.org/?probe=6ab102bc84) | Nov 30, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [a99a51f4e0](https://linux-hardware.org/?probe=a99a51f4e0) | Nov 23, 2021 |
| Acer          | Aspire E5-432G              | [d6fe7992f3](https://linux-hardware.org/?probe=d6fe7992f3) | Nov 21, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [0315115315](https://linux-hardware.org/?probe=0315115315) | Nov 07, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [9ebc122525](https://linux-hardware.org/?probe=9ebc122525) | Nov 02, 2021 |
| HP            | ProBook 455 G7              | [1719b2dc9d](https://linux-hardware.org/?probe=1719b2dc9d) | Oct 30, 2021 |
| Acer          | AS1830                      | [bcef8c44a6](https://linux-hardware.org/?probe=bcef8c44a6) | Oct 26, 2021 |
| Lenovo        | ThinkPad E585 20KVCTO1WW    | [204598f27d](https://linux-hardware.org/?probe=204598f27d) | Oct 26, 2021 |
| Lenovo        | Z50-70 20354                | [22e290b148](https://linux-hardware.org/?probe=22e290b148) | Oct 08, 2021 |
| win elemen... | MBOX WS001                  | [95cb9076bc](https://linux-hardware.org/?probe=95cb9076bc) | Oct 04, 2021 |
| Acer          | TMP645-M                    | [c3daab516f](https://linux-hardware.org/?probe=c3daab516f) | Oct 03, 2021 |
| Toshiba       | PORTEGE R830                | [fbe6b1147d](https://linux-hardware.org/?probe=fbe6b1147d) | Sep 24, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | [6174640bb5](https://linux-hardware.org/?probe=6174640bb5) | Sep 23, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | [97a692e271](https://linux-hardware.org/?probe=97a692e271) | Sep 23, 2021 |
| MSI           | GS76 Stealth 11UH           | [0589c1c238](https://linux-hardware.org/?probe=0589c1c238) | Sep 18, 2021 |
| Lenovo        | ThinkPad X230 2324CD1       | [348eb8e841](https://linux-hardware.org/?probe=348eb8e841) | Sep 18, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [7725289d30](https://linux-hardware.org/?probe=7725289d30) | Sep 17, 2021 |
| Acer          | Swift SF514-55TA            | [b4ff244fa1](https://linux-hardware.org/?probe=b4ff244fa1) | Sep 14, 2021 |
| Acer          | Swift SF514-55TA            | [ca370567d0](https://linux-hardware.org/?probe=ca370567d0) | Sep 14, 2021 |
| Acer          | Swift SF514-55TA            | [c3a4ff2798](https://linux-hardware.org/?probe=c3a4ff2798) | Sep 12, 2021 |
| HP            | Pavilion dv7                | [6ed3caac2b](https://linux-hardware.org/?probe=6ed3caac2b) | Sep 10, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [ddb9671a92](https://linux-hardware.org/?probe=ddb9671a92) | Sep 09, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [b59922b47b](https://linux-hardware.org/?probe=b59922b47b) | Sep 09, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | [1674818018](https://linux-hardware.org/?probe=1674818018) | Aug 23, 2021 |
| MSI           | Modern 14 B11M              | [63c6a56896](https://linux-hardware.org/?probe=63c6a56896) | Aug 22, 2021 |
| MSI           | Modern 14 B11M              | [f73a28166b](https://linux-hardware.org/?probe=f73a28166b) | Aug 22, 2021 |
| ASUSTek       | GL552VW                     | [b48b810fc9](https://linux-hardware.org/?probe=b48b810fc9) | Aug 21, 2021 |
| Acer          | Aspire A515-46              | [ad8f403c6d](https://linux-hardware.org/?probe=ad8f403c6d) | Aug 17, 2021 |
| AVITA         | NE14A2                      | [cd5b403f7b](https://linux-hardware.org/?probe=cd5b403f7b) | Aug 16, 2021 |
| Apple         | MacBookPro10,1              | [a1565d1576](https://linux-hardware.org/?probe=a1565d1576) | Aug 05, 2021 |
| Unknown       | Unknown                     | [d4db86e4ac](https://linux-hardware.org/?probe=d4db86e4ac) | Aug 05, 2021 |
| Unknown       | Unknown                     | [bcb72c9247](https://linux-hardware.org/?probe=bcb72c9247) | Aug 05, 2021 |
| Acer          | Swift SF313-52G             | [cf9d89a2f5](https://linux-hardware.org/?probe=cf9d89a2f5) | Jul 28, 2021 |
| AMI           | Unknown                     | [455466668e](https://linux-hardware.org/?probe=455466668e) | Jul 16, 2021 |
| Lenovo        | ThinkPad T510 4384CJ7       | [744091f92e](https://linux-hardware.org/?probe=744091f92e) | Jul 12, 2021 |
| Lenovo        | ThinkPad T510 4384CJ7       | [9f572c562f](https://linux-hardware.org/?probe=9f572c562f) | Jul 11, 2021 |
| ASUSTek       | E203NA                      | [a4aa015f4e](https://linux-hardware.org/?probe=a4aa015f4e) | Jul 09, 2021 |
| Dell          | Latitude 5420               | [7dc37e8b8c](https://linux-hardware.org/?probe=7dc37e8b8c) | Jul 09, 2021 |
| Dell          | Latitude 5420               | [1c11a8170f](https://linux-hardware.org/?probe=1c11a8170f) | Jul 09, 2021 |
| Acer          | TravelMate P653-M           | [f8509314e3](https://linux-hardware.org/?probe=f8509314e3) | Jun 27, 2021 |
| Toshiba       | Satellite L850              | [4632f9e875](https://linux-hardware.org/?probe=4632f9e875) | Jun 26, 2021 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [0624df0c82](https://linux-hardware.org/?probe=0624df0c82) | Jun 26, 2021 |
| Toshiba       | Satellite L850              | [a1f2e3a8a2](https://linux-hardware.org/?probe=a1f2e3a8a2) | Jun 23, 2021 |
| Acer          | Swift SF514-52T             | [9e0f7fa4a4](https://linux-hardware.org/?probe=9e0f7fa4a4) | Jun 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [6b7a4709ca](https://linux-hardware.org/?probe=6b7a4709ca) | Jun 20, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | [b48bc39bc2](https://linux-hardware.org/?probe=b48bc39bc2) | Jun 20, 2021 |
| HP            | ProBook 430 G6              | [7bf43ae0d0](https://linux-hardware.org/?probe=7bf43ae0d0) | Jun 19, 2021 |
| HP            | ProBook 430 G6              | [9a4e288f49](https://linux-hardware.org/?probe=9a4e288f49) | Jun 19, 2021 |
| AMD           | Celadon-CZN                 | [cfad33c72b](https://linux-hardware.org/?probe=cfad33c72b) | Jun 16, 2021 |
| Lenovo        | ThinkPad T440s 20ARS3RM0... | [cb69a79f5c](https://linux-hardware.org/?probe=cb69a79f5c) | Jun 14, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [5221d99db7](https://linux-hardware.org/?probe=5221d99db7) | Jun 10, 2021 |
| HP            | Unknown                     | [e59d9dcf16](https://linux-hardware.org/?probe=e59d9dcf16) | Jun 08, 2021 |
| MSI           | PE62 8RD                    | [30bb43121d](https://linux-hardware.org/?probe=30bb43121d) | Jun 01, 2021 |
| Lenovo        | V330-15IGM                  | [02894a3c1d](https://linux-hardware.org/?probe=02894a3c1d) | May 26, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d63399b396](https://linux-hardware.org/?probe=d63399b396) | May 19, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [fdbc72ed13](https://linux-hardware.org/?probe=fdbc72ed13) | May 05, 2021 |
| Toshiba       | Satellite L850              | [3f32e7ed1e](https://linux-hardware.org/?probe=3f32e7ed1e) | May 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0c83abd0f8](https://linux-hardware.org/?probe=0c83abd0f8) | Apr 11, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ecbfcfa59d](https://linux-hardware.org/?probe=ecbfcfa59d) | Mar 23, 2021 |
| MSI           | GL65 9SD                    | [e3c6065246](https://linux-hardware.org/?probe=e3c6065246) | Mar 16, 2021 |
| Acer          | Aspire A515-56G             | [8bedf1b6da](https://linux-hardware.org/?probe=8bedf1b6da) | Mar 13, 2021 |
| Dell          | Latitude E7240              | [448e25eb93](https://linux-hardware.org/?probe=448e25eb93) | Mar 04, 2021 |
| ASUSTek       | K53SV                       | [743ce0ed2d](https://linux-hardware.org/?probe=743ce0ed2d) | Mar 03, 2021 |
| Dell          | Latitude E7240              | [adcc4f6449](https://linux-hardware.org/?probe=adcc4f6449) | Feb 25, 2021 |
| Lenovo        | IdeaPad S410 20301          | [90bb71374c](https://linux-hardware.org/?probe=90bb71374c) | Feb 14, 2021 |
| Acer          | Aspire 4755                 | [1ce988a158](https://linux-hardware.org/?probe=1ce988a158) | Jan 30, 2021 |
| Acer          | Aspire 5742G                | [b40787d632](https://linux-hardware.org/?probe=b40787d632) | Jan 24, 2021 |
| Acer          | Aspire 5742G                | [3cd78291fc](https://linux-hardware.org/?probe=3cd78291fc) | Jan 23, 2021 |
| Dell          | Inspiron 5537               | [b6a804b8b9](https://linux-hardware.org/?probe=b6a804b8b9) | Jan 10, 2021 |
| Dell          | Inspiron 5537               | [c88fbbaa7b](https://linux-hardware.org/?probe=c88fbbaa7b) | Jan 10, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4758f7fd48](https://linux-hardware.org/?probe=4758f7fd48) | Jan 07, 2021 |
| HP            | ZBook 15 G6                 | [d4e634a972](https://linux-hardware.org/?probe=d4e634a972) | Dec 20, 2020 |
| ASUSTek       | PU403UA                     | [aee4dc13b7](https://linux-hardware.org/?probe=aee4dc13b7) | Dec 19, 2020 |
| Acer          | Aspire 4720Z                | [88bd8075b2](https://linux-hardware.org/?probe=88bd8075b2) | Dec 16, 2020 |
| Acer          | Aspire 4720Z                | [93cfeab463](https://linux-hardware.org/?probe=93cfeab463) | Dec 16, 2020 |
| Dell          | Inspiron 5437               | [db6ca10333](https://linux-hardware.org/?probe=db6ca10333) | Dec 02, 2020 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [f1f4d46046](https://linux-hardware.org/?probe=f1f4d46046) | Nov 26, 2020 |
| Acer          | Swift SF514-54GT            | [3301702747](https://linux-hardware.org/?probe=3301702747) | Nov 14, 2020 |
| Acer          | Swift SF514-54GT            | [70015c39cf](https://linux-hardware.org/?probe=70015c39cf) | Nov 14, 2020 |
| Acer          | Aspire 4755                 | [5251bda552](https://linux-hardware.org/?probe=5251bda552) | Nov 11, 2020 |
| Lenovo        | XiaoXinAir 15ARE 2021 82... | [2f285baee5](https://linux-hardware.org/?probe=2f285baee5) | Oct 23, 2020 |
| Lenovo        | ThinkPad Edge E531 68853... | [acbd72739e](https://linux-hardware.org/?probe=acbd72739e) | Oct 20, 2020 |
| Lenovo        | XiaoXinAir 15ARE 2021 82... | [d800296611](https://linux-hardware.org/?probe=d800296611) | Oct 16, 2020 |
| Acer          | Aspire A715-71G             | [cd05576b34](https://linux-hardware.org/?probe=cd05576b34) | Oct 04, 2020 |
| HP            | ProBook 455 G7              | [62da42ec3c](https://linux-hardware.org/?probe=62da42ec3c) | Sep 27, 2020 |
| HP            | G62                         | [c9c310542a](https://linux-hardware.org/?probe=c9c310542a) | Sep 27, 2020 |
| ASUSTek       | P2440UA                     | [4c196d17c7](https://linux-hardware.org/?probe=4c196d17c7) | Sep 25, 2020 |
| HP            | ProBook 455 G7              | [b2cdadc21e](https://linux-hardware.org/?probe=b2cdadc21e) | Sep 25, 2020 |
| Acer          | TravelMate P614-51TG        | [e0fbefb33a](https://linux-hardware.org/?probe=e0fbefb33a) | Sep 23, 2020 |
| HP            | Pavilion 11 x360 PC         | [558b4c758d](https://linux-hardware.org/?probe=558b4c758d) | Sep 18, 2020 |
| Acer          | Swift SF514-52T             | [570875f21d](https://linux-hardware.org/?probe=570875f21d) | Sep 12, 2020 |
| ASUSTek       | PU403UA                     | [bdae065e30](https://linux-hardware.org/?probe=bdae065e30) | Sep 11, 2020 |
| Acer          | TravelMate P633-M           | [a7fdf21400](https://linux-hardware.org/?probe=a7fdf21400) | Sep 11, 2020 |
| HP            | Pavilion 11 x360 PC         | [d2b7da6eeb](https://linux-hardware.org/?probe=d2b7da6eeb) | Sep 11, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [72ffc70b7f](https://linux-hardware.org/?probe=72ffc70b7f) | Sep 07, 2020 |
| MSI           | GS63 7RE                    | [e95a9b9d20](https://linux-hardware.org/?probe=e95a9b9d20) | Sep 03, 2020 |
| MSI           | GS63 7RE                    | [c21eb43b7a](https://linux-hardware.org/?probe=c21eb43b7a) | Sep 03, 2020 |
| Acer          | Swift SF314-42              | [bec5ea27a1](https://linux-hardware.org/?probe=bec5ea27a1) | Aug 13, 2020 |
| Dell          | Inspiron 5759               | [6484055ab4](https://linux-hardware.org/?probe=6484055ab4) | Aug 10, 2020 |
| Intel         | JV10_CS                     | [f031e01d35](https://linux-hardware.org/?probe=f031e01d35) | Aug 09, 2020 |
| Dell          | XPS 13 9380                 | [5e3aebe1ec](https://linux-hardware.org/?probe=5e3aebe1ec) | Aug 02, 2020 |
| MSI           | CX62 6QD                    | [7484f1f7b0](https://linux-hardware.org/?probe=7484f1f7b0) | Jul 31, 2020 |
| Acer          | Aspire one                  | [534968996d](https://linux-hardware.org/?probe=534968996d) | Jul 24, 2020 |
| ASUSTek       | E203NA                      | [818318440a](https://linux-hardware.org/?probe=818318440a) | Jul 11, 2020 |
| Lenovo        | ThinkPad T420s 4171A18      | [aba119c0fe](https://linux-hardware.org/?probe=aba119c0fe) | Jul 03, 2020 |
| Lenovo        | ThinkPad T420s 4171A18      | [b23ac2b9df](https://linux-hardware.org/?probe=b23ac2b9df) | Jul 03, 2020 |
| HP            | Pavilion dv7                | [cdb63f485d](https://linux-hardware.org/?probe=cdb63f485d) | Jul 02, 2020 |
| HP            | Pavilion dv7                | [c130b59bb4](https://linux-hardware.org/?probe=c130b59bb4) | Jul 02, 2020 |
| MSI           | GS63 7RE                    | [2fe77551dc](https://linux-hardware.org/?probe=2fe77551dc) | Jun 30, 2020 |
| MSI           | PE72 8RD                    | [f91a312928](https://linux-hardware.org/?probe=f91a312928) | Jun 24, 2020 |
| ASUSTek       | UX30                        | [2b613d2551](https://linux-hardware.org/?probe=2b613d2551) | Jun 20, 2020 |
| MSI           | GS63 7RE                    | [3ddf7394d8](https://linux-hardware.org/?probe=3ddf7394d8) | Jun 18, 2020 |
| Acer          | Aspire E5-553G              | [7ac3604857](https://linux-hardware.org/?probe=7ac3604857) | Jun 14, 2020 |
| MSI           | GS63 7RE                    | [8f4591f672](https://linux-hardware.org/?probe=8f4591f672) | Jun 09, 2020 |
| HP            | ProBook 430 G3              | [208f945a87](https://linux-hardware.org/?probe=208f945a87) | Jun 02, 2020 |
| HUAWEI        | KPRC-WX0                    | [6e02cd7e95](https://linux-hardware.org/?probe=6e02cd7e95) | Jun 01, 2020 |
| HP            | ProBook 430 G3              | [e9ce68b09f](https://linux-hardware.org/?probe=e9ce68b09f) | May 12, 2020 |
| HP            | ProBook 430 G3              | [86b491fad9](https://linux-hardware.org/?probe=86b491fad9) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [74697bc4d6](https://linux-hardware.org/?probe=74697bc4d6) | May 01, 2020 |
| ASUSTek       | X550VC                      | [e783786489](https://linux-hardware.org/?probe=e783786489) | May 01, 2020 |
| ASUSTek       | X550VC                      | [f46665f241](https://linux-hardware.org/?probe=f46665f241) | May 01, 2020 |
| ASUSTek       | X550VC                      | [c1036b76de](https://linux-hardware.org/?probe=c1036b76de) | May 01, 2020 |
| ASUSTek       | ASUSPRO B9440UAM            | [f77e6bd465](https://linux-hardware.org/?probe=f77e6bd465) | Apr 27, 2020 |
| ASUSTek       | ASUSPRO B9440UAM            | [96bb90cb10](https://linux-hardware.org/?probe=96bb90cb10) | Apr 27, 2020 |
| MSI           | GT63 Titan 9SG              | [c521df4d98](https://linux-hardware.org/?probe=c521df4d98) | Apr 25, 2020 |
| ASUSTek       | ZenBook 13 UX331UAL         | [188bcc68c0](https://linux-hardware.org/?probe=188bcc68c0) | Apr 11, 2020 |
| Dell          | Precision 7540              | [9b4e4569fc](https://linux-hardware.org/?probe=9b4e4569fc) | Apr 10, 2020 |
| ASUSTek       | TAICHI31                    | [e942e4a43e](https://linux-hardware.org/?probe=e942e4a43e) | Mar 17, 2020 |
| HP            | 250 G7 Notebook PC          | [d491751516](https://linux-hardware.org/?probe=d491751516) | Mar 09, 2020 |
| Acer          | Aspire one                  | [a956e8a20c](https://linux-hardware.org/?probe=a956e8a20c) | Mar 02, 2020 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c291b5b947](https://linux-hardware.org/?probe=c291b5b947) | Feb 28, 2020 |
| Acer          | Aspire E5-572G              | [1215219438](https://linux-hardware.org/?probe=1215219438) | Feb 24, 2020 |
| Acer          | Aspire V5-591G              | [a3dd0ecbb3](https://linux-hardware.org/?probe=a3dd0ecbb3) | Feb 04, 2020 |
| Acer          | Aspire V5-591G              | [06a759a4a5](https://linux-hardware.org/?probe=06a759a4a5) | Feb 04, 2020 |
| Acer          | Predator PH317-53           | [553a1a04cd](https://linux-hardware.org/?probe=553a1a04cd) | Jan 21, 2020 |
| Acer          | Predator PH317-53           | [c515f18bdf](https://linux-hardware.org/?probe=c515f18bdf) | Jan 21, 2020 |
| ASUSTek       | S551LN                      | [1672f62e6a](https://linux-hardware.org/?probe=1672f62e6a) | Jan 18, 2020 |
| Acer          | Aspire one                  | [e5a2828fc4](https://linux-hardware.org/?probe=e5a2828fc4) | Jan 18, 2020 |
| Acer          | Aspire one                  | [5e43adead0](https://linux-hardware.org/?probe=5e43adead0) | Jan 10, 2020 |
| HP            | ProBook 4310s               | [e835f92f9b](https://linux-hardware.org/?probe=e835f92f9b) | Dec 05, 2019 |
| Vizio         | CT14                        | [2959768de4](https://linux-hardware.org/?probe=2959768de4) | Oct 28, 2019 |
| Vizio         | CT14                        | [83072575a5](https://linux-hardware.org/?probe=83072575a5) | Oct 28, 2019 |
| Acer          | Makalu                      | [00dd5c3407](https://linux-hardware.org/?probe=00dd5c3407) | Oct 19, 2019 |
| Acer          | Aspire 4745G                | [1842d2a0dd](https://linux-hardware.org/?probe=1842d2a0dd) | Oct 17, 2019 |
| Dell          | Inspiron 5437               | [3896fc1c82](https://linux-hardware.org/?probe=3896fc1c82) | Aug 18, 2019 |
| Lenovo        | ThinkPad T410 2537F34       | [25fa16d561](https://linux-hardware.org/?probe=25fa16d561) | Aug 17, 2019 |
| MSI           | GE70 2PE                    | [bba7f1b63c](https://linux-hardware.org/?probe=bba7f1b63c) | Aug 13, 2019 |
| MSI           | GE70 2PE                    | [1363b81c32](https://linux-hardware.org/?probe=1363b81c32) | Aug 11, 2019 |
| Sony          | SVP13229PWB                 | [3aa37419af](https://linux-hardware.org/?probe=3aa37419af) | Jul 23, 2019 |
| Unknown       | Unknown                     | [13f65e01c3](https://linux-hardware.org/?probe=13f65e01c3) | Jul 15, 2019 |
| Unknown       | Unknown                     | [7762bb952e](https://linux-hardware.org/?probe=7762bb952e) | Jul 09, 2019 |
| NEXCOM        | B537-I                      | [ce97b8b28b](https://linux-hardware.org/?probe=ce97b8b28b) | Jun 27, 2019 |
| ASUSTek       | ASUSPRO B9440UAM            | [56aa80a6c4](https://linux-hardware.org/?probe=56aa80a6c4) | Jun 20, 2019 |
| ASUSTek       | N53Jl                       | [0df8ea73f2](https://linux-hardware.org/?probe=0df8ea73f2) | Jun 14, 2019 |
| ASUSTek       | N53Jl                       | [0e4db84a2e](https://linux-hardware.org/?probe=0e4db84a2e) | Jun 14, 2019 |
| Acer          | Aspire E5-553G              | [41e017c4ae](https://linux-hardware.org/?probe=41e017c4ae) | Jun 02, 2019 |
| Sony          | VPCCB15FW                   | [f1c5d4c3c4](https://linux-hardware.org/?probe=f1c5d4c3c4) | May 17, 2019 |
| HP            | Pavilion Notebook           | [4452107fd7](https://linux-hardware.org/?probe=4452107fd7) | Apr 14, 2019 |
| Dell          | Vostro 15-3568              | [417000b97b](https://linux-hardware.org/?probe=417000b97b) | Apr 13, 2019 |
| HP            | Pavilion dv4                | [8f256add2b](https://linux-hardware.org/?probe=8f256add2b) | Apr 08, 2019 |
| HP            | ENVY Sleekbook 6 PC         | [7720ed3668](https://linux-hardware.org/?probe=7720ed3668) | Apr 08, 2019 |
| HP            | Compaq Presario CQ45        | [79588ac19b](https://linux-hardware.org/?probe=79588ac19b) | Apr 05, 2019 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [660901d55e](https://linux-hardware.org/?probe=660901d55e) | Jan 23, 2019 |
| Dell          | Inspiron 5442               | [2a64f0ce54](https://linux-hardware.org/?probe=2a64f0ce54) | Jan 22, 2019 |
| ASUSTek       | X555LB                      | [87f78b7843](https://linux-hardware.org/?probe=87f78b7843) | Dec 18, 2018 |
| ASUSTek       | X555LB                      | [02891bd4ea](https://linux-hardware.org/?probe=02891bd4ea) | Dec 18, 2018 |
| ASUSTek       | X555LB                      | [314622e44e](https://linux-hardware.org/?probe=314622e44e) | Dec 17, 2018 |
| ASUSTek       | X555LB                      | [062f1d59ce](https://linux-hardware.org/?probe=062f1d59ce) | Dec 17, 2018 |
| Dell          | XPS 13 9380                 | [d809782cbd](https://linux-hardware.org/?probe=d809782cbd) | Dec 12, 2018 |
| ASUSTek       | X510UQ                      | [5e508f8f1a](https://linux-hardware.org/?probe=5e508f8f1a) | Nov 09, 2018 |
| ASUSTek       | X510UQ                      | [5a5df173fb](https://linux-hardware.org/?probe=5a5df173fb) | Nov 09, 2018 |
| Acer          | Aspire 3820                 | [664332711f](https://linux-hardware.org/?probe=664332711f) | Nov 09, 2018 |
| Acer          | Aspire 3820                 | [7becdb1438](https://linux-hardware.org/?probe=7becdb1438) | Nov 09, 2018 |
| Dell          | XPS 13 9360                 | [8a7077867f](https://linux-hardware.org/?probe=8a7077867f) | Mar 10, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Ubuntu 20.04                | 41        | 13.62%  |
| Ubuntu 22.04                | 27        | 8.97%   |
| Ubuntu 18.04                | 20        | 6.64%   |
| Arch Rolling                | 16        | 5.32%   |
| Debian 11                   | 11        | 3.65%   |
| Fedora 37                   | 10        | 3.32%   |
| Pop!_OS 20.04               | 5         | 1.66%   |
| OpenMandriva 4.2            | 5         | 1.66%   |
| Ubuntu 19.04                | 4         | 1.33%   |
| SteamOS 3.4.4               | 4         | 1.33%   |
| Pop!_OS 22.04               | 4         | 1.33%   |
| KDE neon 20.04              | 4         | 1.33%   |
| Fedora 38                   | 4         | 1.33%   |
| Fedora 36                   | 4         | 1.33%   |
| Debian 12                   | 4         | 1.33%   |
| Ubuntu 21.04                | 3         | 1%      |
| Ubuntu 19.10                | 3         | 1%      |
| Pop!_OS 21.04               | 3         | 1%      |
| OpenMandriva 4.3            | 3         | 1%      |
| OpenMandriva 23.01          | 3         | 1%      |
| Manjaro                     | 3         | 1%      |
| Linux Mint 21.2             | 3         | 1%      |
| Linux Mint 21.1             | 3         | 1%      |
| Linux Mint 20.3             | 3         | 1%      |
| Kubuntu 22.04               | 3         | 1%      |
| Fedora 34                   | 3         | 1%      |
| EndeavourOS Rolling         | 3         | 1%      |
| Debian Testing              | 3         | 1%      |
| Debian                      | 3         | 1%      |
| Arch                        | 3         | 1%      |
| Ubuntu 22.10                | 2         | 0.66%   |
| Ubuntu 20.10                | 2         | 0.66%   |
| Ubuntu 18.10                | 2         | 0.66%   |
| Ubuntu 16.04                | 2         | 0.66%   |
| SteamOS 3.4.6               | 2         | 0.66%   |
| Pop!_OS 21.10               | 2         | 0.66%   |
| org.kde.Platform 5.15-21.08 | 2         | 0.66%   |
| OpenMandriva 4.50           | 2         | 0.66%   |
| OpenMandriva 23.08          | 2         | 0.66%   |
| OpenMandriva 23.03          | 2         | 0.66%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 104       | 37.28%  |
| Fedora           | 25        | 8.96%   |
| Manjaro          | 22        | 7.89%   |
| Debian           | 19        | 6.81%   |
| Arch             | 19        | 6.81%   |
| OpenMandriva     | 16        | 5.73%   |
| Pop!_OS          | 14        | 5.02%   |
| Linux Mint       | 13        | 4.66%   |
| Kubuntu          | 7         | 2.51%   |
| SteamOS          | 5         | 1.79%   |
| KDE neon         | 5         | 1.79%   |
| Ubuntu MATE      | 3         | 1.08%   |
| Lubuntu          | 3         | 1.08%   |
| Gentoo           | 3         | 1.08%   |
| EndeavourOS      | 3         | 1.08%   |
| Zorin            | 2         | 0.72%   |
| Xubuntu          | 2         | 0.72%   |
| org.kde.Platform | 2         | 0.72%   |
| Endless          | 2         | 0.72%   |
| Ubuntu Unity     | 1         | 0.36%   |
| Ubuntu Studio    | 1         | 0.36%   |
| Ubuntu Budgie    | 1         | 0.36%   |
| Slackware        | 1         | 0.36%   |
| Rocky Linux      | 1         | 0.36%   |
| Nobara           | 1         | 0.36%   |
| Kylin            | 1         | 0.36%   |
| Kali             | 1         | 0.36%   |
| Elementary       | 1         | 0.36%   |
| CentOS           | 1         | 0.36%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 5         | 1.56%   |
| 5.13.0-valve36-1-neptune | 4         | 1.25%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.94%   |
| 5.8.0-7630-generic       | 3         | 0.94%   |
| 5.4.0-42-generic         | 3         | 0.94%   |
| 5.3.0-46-generic         | 3         | 0.94%   |
| 5.3.0-40-generic         | 3         | 0.94%   |
| 5.16.7-desktop-1omv4003  | 3         | 0.94%   |
| 5.15.0-58-generic        | 3         | 0.94%   |
| 5.15.0-40-generic        | 3         | 0.94%   |
| 5.11.0-25-generic        | 3         | 0.94%   |
| 6.5.0-14-generic         | 2         | 0.63%   |
| 6.4.11-desktop-1omv2390  | 2         | 0.63%   |
| 6.2.6-desktop-1omv2390   | 2         | 0.63%   |
| 6.2.6-76060206-generic   | 2         | 0.63%   |
| 6.2.0-32-generic         | 2         | 0.63%   |
| 6.2.0-26-generic         | 2         | 0.63%   |
| 6.1.0-13-amd64           | 2         | 0.63%   |
| 6.0.8-300.fc37.x86_64    | 2         | 0.63%   |
| 5.8.10-arch1-1           | 2         | 0.63%   |
| 5.8.0-53-generic         | 2         | 0.63%   |
| 5.8.0-43-generic         | 2         | 0.63%   |
| 5.4.64-1-MANJARO         | 2         | 0.63%   |
| 5.4.0-84-generic         | 2         | 0.63%   |
| 5.4.0-52-generic         | 2         | 0.63%   |
| 5.4.0-26-generic         | 2         | 0.63%   |
| 5.19.0-46-generic        | 2         | 0.63%   |
| 5.19.0-38-generic        | 2         | 0.63%   |
| 5.19.0-32-generic        | 2         | 0.63%   |
| 5.16.11-2-MANJARO        | 2         | 0.63%   |
| 5.15.0-88-generic        | 2         | 0.63%   |
| 5.15.0-56-generic        | 2         | 0.63%   |
| 5.15.0-53-generic        | 2         | 0.63%   |
| 5.15.0-48-generic        | 2         | 0.63%   |
| 5.13.15-1-MANJARO        | 2         | 0.63%   |
| 5.13.0-30-generic        | 2         | 0.63%   |
| 5.11.0-7620-generic      | 2         | 0.63%   |
| 5.11.0-43-generic        | 2         | 0.63%   |
| 5.11.0-41-generic        | 2         | 0.63%   |
| 5.11.0-27-generic        | 2         | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 26        | 8.39%   |
| 5.4.0   | 25        | 8.06%   |
| 5.13.0  | 15        | 4.84%   |
| 5.10.0  | 14        | 4.52%   |
| 5.8.0   | 13        | 4.19%   |
| 5.11.0  | 13        | 4.19%   |
| 5.19.0  | 10        | 3.23%   |
| 4.18.0  | 10        | 3.23%   |
| 4.15.0  | 9         | 2.9%    |
| 6.2.0   | 8         | 2.58%   |
| 5.3.0   | 7         | 2.26%   |
| 5.0.0   | 7         | 2.26%   |
| 6.1.1   | 6         | 1.94%   |
| 6.1.0   | 6         | 1.94%   |
| 6.5.0   | 5         | 1.61%   |
| 5.10.14 | 5         | 1.61%   |
| 6.2.6   | 4         | 1.29%   |
| 5.14.0  | 4         | 1.29%   |
| 6.0.0   | 3         | 0.97%   |
| 5.16.7  | 3         | 0.97%   |
| 5.16.11 | 3         | 0.97%   |
| 6.6.2   | 2         | 0.65%   |
| 6.5.6   | 2         | 0.65%   |
| 6.4.11  | 2         | 0.65%   |
| 6.2.9   | 2         | 0.65%   |
| 6.1.9   | 2         | 0.65%   |
| 6.1.7   | 2         | 0.65%   |
| 6.0.8   | 2         | 0.65%   |
| 5.8.10  | 2         | 0.65%   |
| 5.7.1   | 2         | 0.65%   |
| 5.7.0   | 2         | 0.65%   |
| 5.4.64  | 2         | 0.65%   |
| 5.18.7  | 2         | 0.65%   |
| 5.17.5  | 2         | 0.65%   |
| 5.16.18 | 2         | 0.65%   |
| 5.15.21 | 2         | 0.65%   |
| 5.15.16 | 2         | 0.65%   |
| 5.13.15 | 2         | 0.65%   |
| 6.6.7   | 1         | 0.32%   |
| 6.6.1   | 1         | 0.32%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 39        | 12.66%  |
| 5.4     | 28        | 9.09%   |
| 5.10    | 24        | 7.79%   |
| 6.1     | 21        | 6.82%   |
| 5.13    | 20        | 6.49%   |
| 6.2     | 18        | 5.84%   |
| 5.8     | 18        | 5.84%   |
| 5.11    | 15        | 4.87%   |
| 5.19    | 14        | 4.55%   |
| 6.0     | 10        | 3.25%   |
| 4.18    | 10        | 3.25%   |
| 6.5     | 9         | 2.92%   |
| 5.16    | 9         | 2.92%   |
| 4.15    | 9         | 2.92%   |
| 5.0     | 8         | 2.6%    |
| 5.7     | 7         | 2.27%   |
| 5.3     | 7         | 2.27%   |
| 5.14    | 6         | 1.95%   |
| 6.6     | 5         | 1.62%   |
| 6.3     | 5         | 1.62%   |
| 5.6     | 4         | 1.3%    |
| 5.17    | 4         | 1.3%    |
| 6.4     | 3         | 0.97%   |
| 5.18    | 3         | 0.97%   |
| 5.12    | 3         | 0.97%   |
| 5.9     | 2         | 0.65%   |
| 5.2     | 1         | 0.32%   |
| 4.4     | 1         | 0.32%   |
| 4.19    | 1         | 0.32%   |
| 4.14    | 1         | 0.32%   |
| 4.13    | 1         | 0.32%   |
| 4.10    | 1         | 0.32%   |
| 3.10    | 1         | 0.32%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 263       | 98.13%  |
| i686   | 5         | 1.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 133       | 47.16%  |
| KDE5            | 55        | 19.5%   |
| Unknown         | 40        | 14.18%  |
| XFCE            | 11        | 3.9%    |
| X-Cinnamon      | 10        | 3.55%   |
| MATE            | 7         | 2.48%   |
| KDE             | 7         | 2.48%   |
| LXQt            | 3         | 1.06%   |
| i3              | 3         | 1.06%   |
| Openbox         | 2         | 0.71%   |
| LXDE            | 2         | 0.71%   |
| GNOME Flashback | 2         | 0.71%   |
| Deepin          | 2         | 0.71%   |
| Unity           | 1         | 0.35%   |
| sway            | 1         | 0.35%   |
| qtile           | 1         | 0.35%   |
| Pantheon        | 1         | 0.35%   |
| Budgie          | 1         | 0.35%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 190       | 68.59%  |
| Wayland | 58        | 20.94%  |
| Unknown | 23        | 8.3%    |
| Tty     | 6         | 2.17%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 110       | 39.15%  |
| SDDM    | 50        | 17.79%  |
| GDM     | 50        | 17.79%  |
| GDM3    | 42        | 14.95%  |
| LightDM | 21        | 7.47%   |
| TDM     | 4         | 1.42%   |
| SLiM    | 2         | 0.71%   |
| XDM     | 1         | 0.36%   |
| LXDM    | 1         | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 137       | 49.46%  |
| zh_TW   | 83        | 29.96%  |
| Unknown | 30        | 10.83%  |
| C       | 6         | 2.17%   |
| zh_CN   | 4         | 1.44%   |
| en_GB   | 4         | 1.44%   |
| ru_RU   | 3         | 1.08%   |
| lzh_TW  | 2         | 0.72%   |
| de_DE   | 2         | 0.72%   |
| zh_SG   | 1         | 0.36%   |
| zh_HK   | 1         | 0.36%   |
| ja_JP   | 1         | 0.36%   |
| en_SG   | 1         | 0.36%   |
| en_IE   | 1         | 0.36%   |
| C.UTF8  | 1         | 0.36%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 166       | 61.03%  |
| BIOS | 106       | 38.97%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 210       | 77.21%  |
| Btrfs   | 27        | 9.93%   |
| Overlay | 15        | 5.51%   |
| Xfs     | 7         | 2.57%   |
| Tmpfs   | 5         | 1.84%   |
| Unknown | 4         | 1.47%   |
| Ext2    | 2         | 0.74%   |
| F2fs    | 1         | 0.37%   |
| Ext3    | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 136       | 50%     |
| Unknown | 111       | 40.81%  |
| MBR     | 25        | 9.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 234       | 86.67%  |
| Yes       | 36        | 13.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 170       | 62.5%   |
| Yes       | 102       | 37.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer                 | 49        | 18.28%  |
| ASUSTek Computer     | 45        | 16.79%  |
| Lenovo               | 43        | 16.04%  |
| Hewlett-Packard      | 32        | 11.94%  |
| Dell                 | 26        | 9.7%    |
| MSI                  | 20        | 7.46%   |
| Valve                | 5         | 1.87%   |
| Toshiba              | 5         | 1.87%   |
| Sony                 | 4         | 1.49%   |
| Gigabyte Technology  | 4         | 1.49%   |
| Apple                | 4         | 1.49%   |
| Unknown              | 3         | 1.12%   |
| Timi                 | 2         | 0.75%   |
| LG Electronics       | 2         | 0.75%   |
| Lex                  | 2         | 0.75%   |
| Intel Client Systems | 2         | 0.75%   |
| HUAWEI               | 2         | 0.75%   |
| Google               | 2         | 0.75%   |
| AVITA                | 2         | 0.75%   |
| win element          | 1         | 0.37%   |
| Vizio                | 1         | 0.37%   |
| System76             | 1         | 0.37%   |
| Samsung Electronics  | 1         | 0.37%   |
| NEXCOM               | 1         | 0.37%   |
| Intel                | 1         | 0.37%   |
| Insyde               | 1         | 0.37%   |
| Framework            | 1         | 0.37%   |
| Dynabook             | 1         | 0.37%   |
| CJSCOPE              | 1         | 0.37%   |
| CHIPHD               | 1         | 0.37%   |
| AMI                  | 1         | 0.37%   |
| AMD                  | 1         | 0.37%   |
| Acidanthera          | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 5         | 1.87%   |
| Valve Jupiter                       | 4         | 1.49%   |
| Acer Swift SFX14-41G                | 3         | 1.12%   |
| Toshiba Satellite L850              | 2         | 0.75%   |
| MSI GS63 7RE                        | 2         | 0.75%   |
| Lex 3I610DW                         | 2         | 0.75%   |
| Lenovo IdeaPad 5 14ALC05 82LM       | 2         | 0.75%   |
| HP ProBook 430 G8 Notebook PC       | 2         | 0.75%   |
| HP Pavilion dv7                     | 2         | 0.75%   |
| Dell XPS 13 9380                    | 2         | 0.75%   |
| AVITA NE14A2                        | 2         | 0.75%   |
| Acer Swift SF514-52T                | 2         | 0.75%   |
| Acer Aspire V3-571G                 | 2         | 0.75%   |
| Acer Aspire one                     | 2         | 0.75%   |
| Acer Aspire 4755                    | 2         | 0.75%   |
| Acer Aspire 4750                    | 2         | 0.75%   |
| win element MBOX                    | 1         | 0.37%   |
| Vizio CT14                          | 1         | 0.37%   |
| Valve Galileo                       | 1         | 0.37%   |
| Toshiba Satellite L640              | 1         | 0.37%   |
| Toshiba Satellite C665              | 1         | 0.37%   |
| Toshiba PORTEGE R830                | 1         | 0.37%   |
| Timi Redmi Book Pro 15 2022         | 1         | 0.37%   |
| Timi Mi Laptop Pro 15               | 1         | 0.37%   |
| System76 Lemur Pro                  | 1         | 0.37%   |
| Sony VPCCB15FW                      | 1         | 0.37%   |
| Sony VGN-C15TP_W                    | 1         | 0.37%   |
| Sony SVS15115FWB                    | 1         | 0.37%   |
| Sony SVP13229PWB                    | 1         | 0.37%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B | 1         | 0.37%   |
| NEXCOM B537-I                       | 1         | 0.37%   |
| MSI U270DX                          | 1         | 0.37%   |
| MSI PS63 Modern 8M                  | 1         | 0.37%   |
| MSI PE72 8RD                        | 1         | 0.37%   |
| MSI PE62 8RD                        | 1         | 0.37%   |
| MSI PE60 6QE                        | 1         | 0.37%   |
| MSI P65 Creator 9SD                 | 1         | 0.37%   |
| MSI Modern 15 A5M                   | 1         | 0.37%   |
| MSI Modern 14 B11M                  | 1         | 0.37%   |
| MSI GV72 8RC                        | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Acer Aspire        | 32        | 11.94%  |
| Lenovo ThinkPad    | 26        | 9.7%    |
| Lenovo IdeaPad     | 10        | 3.73%   |
| Acer Swift         | 10        | 3.73%   |
| HP ProBook         | 9         | 3.36%   |
| Dell Inspiron      | 9         | 3.36%   |
| HP Pavilion        | 8         | 2.99%   |
| ASUS VivoBook      | 7         | 2.61%   |
| Dell Latitude      | 6         | 2.24%   |
| ASUS ROG           | 6         | 2.24%   |
| Dell Vostro        | 5         | 1.87%   |
| Unknown            | 5         | 1.87%   |
| Valve Jupiter      | 4         | 1.49%   |
| Toshiba Satellite  | 4         | 1.49%   |
| ASUS ZenBook       | 4         | 1.49%   |
| ASUS ASUS          | 4         | 1.49%   |
| Acer TravelMate    | 4         | 1.49%   |
| HP EliteBook       | 3         | 1.12%   |
| Dell XPS           | 3         | 1.12%   |
| ASUS ASUSPRO       | 3         | 1.12%   |
| MSI Modern         | 2         | 0.75%   |
| MSI GS63           | 2         | 0.75%   |
| MSI GE70           | 2         | 0.75%   |
| MSI Alpha          | 2         | 0.75%   |
| Lex 3I610DW        | 2         | 0.75%   |
| Lenovo Legion      | 2         | 0.75%   |
| HP Compaq          | 2         | 0.75%   |
| HP 250             | 2         | 0.75%   |
| AVITA NE14A2       | 2         | 0.75%   |
| Apple MacBookPro11 | 2         | 0.75%   |
| win element MBOX   | 1         | 0.37%   |
| Vizio CT14         | 1         | 0.37%   |
| Valve Galileo      | 1         | 0.37%   |
| Toshiba PORTEGE    | 1         | 0.37%   |
| Timi Redmi         | 1         | 0.37%   |
| Timi Mi            | 1         | 0.37%   |
| System76 Lemur     | 1         | 0.37%   |
| Sony VPCCB15FW     | 1         | 0.37%   |
| Sony VGN-C15TP     | 1         | 0.37%   |
| Sony SVS15115FWB   | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 34        | 12.69%  |
| 2022 | 25        | 9.33%   |
| 2019 | 24        | 8.96%   |
| 2020 | 23        | 8.58%   |
| 2018 | 21        | 7.84%   |
| 2012 | 20        | 7.46%   |
| 2017 | 19        | 7.09%   |
| 2014 | 18        | 6.72%   |
| 2011 | 16        | 5.97%   |
| 2015 | 14        | 5.22%   |
| 2016 | 11        | 4.1%    |
| 2013 | 10        | 3.73%   |
| 2010 | 9         | 3.36%   |
| 2023 | 7         | 2.61%   |
| 2009 | 7         | 2.61%   |
| 2008 | 5         | 1.87%   |
| 2007 | 2         | 0.75%   |
| 2006 | 2         | 0.75%   |
| 2004 | 1         | 0.37%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 268       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 241       | 88.93%  |
| Enabled  | 30        | 11.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 265       | 98.88%  |
| Yes  | 3         | 1.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 74        | 27.21%  |
| 16.01-24.0  | 63        | 23.16%  |
| 8.01-16.0   | 50        | 18.38%  |
| 3.01-4.0    | 36        | 13.24%  |
| 32.01-64.0  | 23        | 8.46%   |
| 24.01-32.0  | 9         | 3.31%   |
| 64.01-256.0 | 7         | 2.57%   |
| 1.01-2.0    | 6         | 2.21%   |
| 2.01-3.0    | 3         | 1.1%    |
| 0.51-1.0    | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 83        | 27.85%  |
| 1.01-2.0   | 79        | 26.51%  |
| 4.01-8.0   | 58        | 19.46%  |
| 3.01-4.0   | 45        | 15.1%   |
| 8.01-16.0  | 19        | 6.38%   |
| 0.51-1.0   | 8         | 2.68%   |
| 24.01-32.0 | 2         | 0.67%   |
| 0.01-0.5   | 2         | 0.67%   |
| 32.01-64.0 | 1         | 0.34%   |
| 16.01-24.0 | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 172       | 62.09%  |
| 2      | 83        | 29.96%  |
| 3      | 14        | 5.05%   |
| 0      | 5         | 1.81%   |
| 4      | 2         | 0.72%   |
| 5      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 205       | 76.21%  |
| Yes       | 64        | 23.79%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 201       | 74.72%  |
| No        | 68        | 25.28%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 257       | 95.9%   |
| No        | 11        | 4.1%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 239       | 88.85%  |
| No        | 30        | 11.15%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Taiwan  | 268       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Taipei           | 88        | 29.93%  |
| New Taipei       | 50        | 17.01%  |
| Taoyuan District | 26        | 8.84%   |
| Hsinchu          | 26        | 8.84%   |
| Taichung         | 24        | 8.16%   |
| Kaohsiung City   | 19        | 6.46%   |
| Tainan City      | 8         | 2.72%   |
| Hsinchu County   | 7         | 2.38%   |
| Chang-hua        | 5         | 1.7%    |
| Zhongli District | 4         | 1.36%   |
| Zhudong          | 3         | 1.02%   |
| Yunlin           | 3         | 1.02%   |
| Pingtung City    | 3         | 1.02%   |
| Keelung          | 3         | 1.02%   |
| Zhubei           | 2         | 0.68%   |
| Taoyuan City     | 2         | 0.68%   |
| Shulin District  | 2         | 0.68%   |
| Nantou City      | 2         | 0.68%   |
| Yilan            | 1         | 0.34%   |
| Yangmei District | 1         | 0.34%   |
| Xiawanzi         | 1         | 0.34%   |
| Tuniugou         | 1         | 0.34%   |
| Taichung City    | 1         | 0.34%   |
| Penghu County    | 1         | 0.34%   |
| Neihu            | 1         | 0.34%   |
| Miaoli           | 1         | 0.34%   |
| Lugu             | 1         | 0.34%   |
| Fenjihu          | 1         | 0.34%   |
| Dawan            | 1         | 0.34%   |
| Daan             | 1         | 0.34%   |
| Chiayi County    | 1         | 0.34%   |
| Chenggong        | 1         | 0.34%   |
| Buxin            | 1         | 0.34%   |
| Bao'an           | 1         | 0.34%   |
| Banqiao          | 1         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 37        | 49     | 9.97%   |
| WDC                            | 35        | 45     | 9.43%   |
| Sandisk                        | 27        | 37     | 7.28%   |
| SK hynix                       | 25        | 30     | 6.74%   |
| Seagate                        | 25        | 28     | 6.74%   |
| Crucial                        | 25        | 31     | 6.74%   |
| Kingston                       | 22        | 29     | 5.93%   |
| HGST                           | 22        | 23     | 5.93%   |
| Unknown                        | 20        | 26     | 5.39%   |
| Toshiba                        | 19        | 21     | 5.12%   |
| Micron Technology              | 13        | 14     | 3.5%    |
| Intel                          | 12        | 18     | 3.23%   |
| Hitachi                        | 10        | 11     | 2.7%    |
| Transcend                      | 5         | 6      | 1.35%   |
| Phison Electronics             | 5         | 7      | 1.35%   |
| KIOXIA                         | 5         | 7      | 1.35%   |
| Unknown                        | 5         | 5      | 1.35%   |
| Micron/Crucial Technology      | 4         | 4      | 1.08%   |
| ASMT                           | 4         | 4      | 1.08%   |
| AGI                            | 4         | 4      | 1.08%   |
| JMicron Technology             | 3         | 7      | 0.81%   |
| A-DATA Technology              | 3         | 4      | 0.81%   |
| SPCC                           | 2         | 3      | 0.54%   |
| Silicon Motion                 | 2         | 3      | 0.54%   |
| Realtek Semiconductor          | 2         | 2      | 0.54%   |
| NeoTech                        | 2         | 2      | 0.54%   |
| Kingston Technology Company    | 2         | 2      | 0.54%   |
| ZHITAI                         | 1         | 1      | 0.27%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.27%   |
| XPG                            | 1         | 1      | 0.27%   |
| USB3.2                         | 1         | 1      | 0.27%   |
| USB3.0                         | 1         | 1      | 0.27%   |
| Union Memory                   | 1         | 1      | 0.27%   |
| Toshiba America Info Systems   | 1         | 2      | 0.27%   |
| Team                           | 1         | 1      | 0.27%   |
| StoreJet                       | 1         | 2      | 0.27%   |
| Solid State Storage Technology | 1         | 2      | 0.27%   |
| Plextor                        | 1         | 1      | 0.27%   |
| Pioneer                        | 1         | 1      | 0.27%   |
| Phison                         | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                        | 8         | 2.06%   |
| Crucial CT500MX500SSD1 500GB                    | 7         | 1.8%    |
| Unknown MMC Card  64GB                          | 6         | 1.55%   |
| Crucial CT1000MX500SSD1 1TB                     | 6         | 1.55%   |
| Seagate ST1000LM035-1RK172 1TB                  | 5         | 1.29%   |
| Unknown                                         | 5         | 1.29%   |
| Toshiba MQ04ABF100 1TB                          | 4         | 1.03%   |
| Toshiba MQ01ABD100 1TB                          | 4         | 1.03%   |
| SK hynix HFM512GD3JX016N 512GB                  | 4         | 1.03%   |
| Seagate ST1000LM049-2GH172 1TB                  | 4         | 1.03%   |
| SanDisk NVMe SSD Drive 1TB                      | 4         | 1.03%   |
| Phison PS5013 E13 NVMe Controller 512GB         | 4         | 1.03%   |
| HGST HTS541010A9E680 1TB                        | 4         | 1.03%   |
| Crucial CT240BX500SSD1 240GB                    | 4         | 1.03%   |
| Unknown MMC Card  32GB                          | 3         | 0.77%   |
| SanDisk NVMe SSD Drive 512GB                    | 3         | 0.77%   |
| SanDisk NVMe SSD Drive 256GB                    | 3         | 0.77%   |
| Kingston SA400S37240G 240GB SSD                 | 3         | 0.77%   |
| HGST HTS725050A7E630 500GB                      | 3         | 0.77%   |
| HGST HTS541010B7E610 1TB                        | 3         | 0.77%   |
| Crucial CT500MX500SSD4 500GB                    | 3         | 0.77%   |
| WDC WDS500G3X0C-00SJG0 500GB                    | 2         | 0.52%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                | 2         | 0.52%   |
| WDC WD10SPZX-08Z10 1TB                          | 2         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                        | 2         | 0.52%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB            | 2         | 0.52%   |
| Unknown MMC Card  512GB                         | 2         | 0.52%   |
| Unknown MMC Card  128GB                         | 2         | 0.52%   |
| SPCC Solid State Disk 240GB                     | 2         | 0.52%   |
| SK hynix NVMe SSD Drive 512GB                   | 2         | 0.52%   |
| SK hynix HFM512GD3JX013N 512GB                  | 2         | 0.52%   |
| SK hynix BC711 NVMe 512GB                       | 2         | 0.52%   |
| Seagate ST9500420AS 500GB                       | 2         | 0.52%   |
| Seagate ST1000LM014-1EJ164 1TB                  | 2         | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB              | 2         | 0.52%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 128GB | 2         | 0.52%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 2TB  | 2         | 0.52%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB          | 2         | 0.52%   |
| Samsung NVMe SSD Drive 1024GB                   | 2         | 0.52%   |
| Samsung MZVLW256HEHP-00000 256GB                | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 25        | 27     | 28.41%  |
| HGST               | 22        | 23     | 25%     |
| WDC                | 13        | 16     | 14.77%  |
| Toshiba            | 12        | 14     | 13.64%  |
| Hitachi            | 10        | 11     | 11.36%  |
| NeoTech            | 2         | 2      | 2.27%   |
| Unknown            | 1         | 1      | 1.14%   |
| StoreJet           | 1         | 2      | 1.14%   |
| JMicron Technology | 1         | 4      | 1.14%   |
| External           | 1         | 1      | 1.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 23        | 28     | 20.18%  |
| SanDisk             | 11        | 14     | 9.65%   |
| Kingston            | 11        | 13     | 9.65%   |
| Samsung Electronics | 10        | 12     | 8.77%   |
| WDC                 | 6         | 8      | 5.26%   |
| Transcend           | 5         | 6      | 4.39%   |
| Toshiba             | 5         | 5      | 4.39%   |
| Micron Technology   | 5         | 6      | 4.39%   |
| Intel               | 5         | 10     | 4.39%   |
| ASMT                | 4         | 4      | 3.51%   |
| SK hynix            | 3         | 3      | 2.63%   |
| A-DATA Technology   | 3         | 4      | 2.63%   |
| Unknown             | 3         | 3      | 2.63%   |
| SPCC                | 2         | 3      | 1.75%   |
| AGI                 | 2         | 2      | 1.75%   |
| Team                | 1         | 1      | 0.88%   |
| Plextor             | 1         | 1      | 0.88%   |
| Patriot             | 1         | 1      | 0.88%   |
| OCZ                 | 1         | 1      | 0.88%   |
| NT-512              | 1         | 1      | 0.88%   |
| MyDigitalSSD        | 1         | 1      | 0.88%   |
| MX                  | 1         | 1      | 0.88%   |
| LITEONIT            | 1         | 1      | 0.88%   |
| LITEON              | 1         | 1      | 0.88%   |
| Kingchuxing         | 1         | 1      | 0.88%   |
| JMicron Technology  | 1         | 2      | 0.88%   |
| FORESEE             | 1         | 1      | 0.88%   |
| Aura                | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |
| Apacer              | 1         | 1      | 0.88%   |
| Acer                | 1         | 2      | 0.88%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 127       | 183    | 37.13%  |
| SSD     | 102       | 139    | 29.82%  |
| HDD     | 86        | 101    | 25.15%  |
| MMC     | 19        | 25     | 5.56%   |
| Unknown | 8         | 9      | 2.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 160       | 226    | 49.54%  |
| NVMe | 127       | 183    | 39.32%  |
| MMC  | 19        | 25     | 5.88%   |
| SAS  | 17        | 23     | 5.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 108       | 139    | 56.84%  |
| 0.51-1.0   | 74        | 90     | 38.95%  |
| 1.01-2.0   | 7         | 10     | 3.68%   |
| 4.01-10.0  | 1         | 1      | 0.53%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 83        | 29.43%  |
| 101-250        | 73        | 25.89%  |
| 501-1000       | 46        | 16.31%  |
| 1-20           | 24        | 8.51%   |
| 1001-2000      | 16        | 5.67%   |
| 51-100         | 14        | 4.96%   |
| 21-50          | 13        | 4.61%   |
| Unknown        | 7         | 2.48%   |
| 2001-3000      | 5         | 1.77%   |
| More than 3000 | 1         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 117       | 39.93%  |
| 21-50          | 43        | 14.68%  |
| 101-250        | 41        | 13.99%  |
| 51-100         | 36        | 12.29%  |
| 251-500        | 33        | 11.26%  |
| 501-1000       | 14        | 4.78%   |
| Unknown        | 7         | 2.39%   |
| More than 3000 | 1         | 0.34%   |
| 1001-2000      | 1         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 10%     |
| SK hynix HFS128G39MNC-2300A 128GB SSD          | 1         | 1      | 10%     |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 10%     |
| Samsung Electronics MZVPV256HDGL-00000 256GB   | 1         | 1      | 10%     |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 10%     |
| Hitachi HTS722080K9SA00 80GB                   | 1         | 1      | 10%     |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 10%     |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 10%     |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 10%     |
| ASMT 2115 1TB                                  | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| SK hynix            | 2         | 2      | 20%     |
| Hitachi             | 2         | 2      | 20%     |
| HGST                | 2         | 2      | 20%     |
| Seagate             | 1         | 1      | 10%     |
| Samsung Electronics | 1         | 1      | 10%     |
| Micron Technology   | 1         | 1      | 10%     |
| ASMT                | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 40%     |
| HGST    | 2         | 2      | 40%     |
| Seagate | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 5         | 5      | 50%     |
| SSD  | 3         | 3      | 30%     |
| NVMe | 2         | 2      | 20%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| HGST HTS541010A9E680 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| HGST   | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 143       | 238    | 49.65%  |
| Works    | 134       | 208    | 46.53%  |
| Malfunc  | 10        | 10     | 3.47%   |
| Failed   | 1         | 1      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 180       | 52.94%  |
| Samsung Electronics            | 31        | 9.12%   |
| SanDisk                        | 29        | 8.53%   |
| AMD                            | 24        | 7.06%   |
| SK hynix                       | 22        | 6.47%   |
| Kingston Technology Company    | 12        | 3.53%   |
| Micron Technology              | 9         | 2.65%   |
| Micron/Crucial Technology      | 6         | 1.76%   |
| Toshiba America Info Systems   | 5         | 1.47%   |
| Phison Electronics             | 5         | 1.47%   |
| KIOXIA                         | 3         | 0.88%   |
| Silicon Motion                 | 2         | 0.59%   |
| Realtek Semiconductor          | 2         | 0.59%   |
| Yangtze Memory Technologies    | 1         | 0.29%   |
| Union Memory (Shenzhen)        | 1         | 0.29%   |
| Solidigm                       | 1         | 0.29%   |
| Solid State Storage Technology | 1         | 0.29%   |
| Nvidia                         | 1         | 0.29%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.29%   |
| Marvell Technology Group       | 1         | 0.29%   |
| Lite-On Technology             | 1         | 0.29%   |
| Biwin Storage Technology       | 1         | 0.29%   |
| ADATA Technology               | 1         | 0.29%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 26        | 7.28%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 23        | 6.44%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 19        | 5.32%   |
| Intel Volume Management Device NVMe RAID Controller                            | 18        | 5.04%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 4.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 14        | 3.92%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 13        | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 3.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 3.08%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 9         | 2.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 2.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 9         | 2.52%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 9         | 2.52%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 7         | 1.96%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 6         | 1.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 1.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 1.68%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 5         | 1.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.4%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 4         | 1.12%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 4         | 1.12%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 4         | 1.12%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 4         | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 1.12%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 4         | 1.12%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.84%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 0.84%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 3         | 0.84%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                       | 3         | 0.84%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 3         | 0.84%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 0.84%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.84%   |
| SK hynix BC511 NVMe SSD                                                        | 2         | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.56%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 2         | 0.56%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 2         | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 178       | 52.2%   |
| NVMe | 128       | 37.54%  |
| RAID | 28        | 8.21%   |
| IDE  | 7         | 2.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 217       | 80.97%  |
| AMD    | 51        | 19.03%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 3.36%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 2.61%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 6         | 2.24%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 2.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 6         | 2.24%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 2.24%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 1.87%   |
| Intel 12th Gen Core i5-12500H           | 5         | 1.87%   |
| AMD Custom APU 0405                     | 5         | 1.87%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 4         | 1.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 4         | 1.49%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 4         | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 4         | 1.49%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 4         | 1.49%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 4         | 1.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 4         | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 4         | 1.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 3         | 1.12%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 3         | 1.12%   |
| AMD Ryzen 7 5800U with Radeon Graphics  | 3         | 1.12%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 3         | 1.12%   |
| AMD Ryzen 7 4800HS with Radeon Graphics | 3         | 1.12%   |
| Intel Core i7-8650U CPU @ 1.90GHz       | 2         | 0.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.75%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 2         | 0.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 2         | 0.75%   |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 2         | 0.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz      | 2         | 0.75%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.75%   |
| Intel Core i5-8300H CPU @ 2.30GHz       | 2         | 0.75%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 2         | 0.75%   |
| Intel Core i5-3337U CPU @ 1.80GHz       | 2         | 0.75%   |
| Intel Core i5-3317U CPU @ 1.70GHz       | 2         | 0.75%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 2         | 0.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 2         | 0.75%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz      | 2         | 0.75%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 2         | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 2         | 0.75%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 2         | 0.75%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 0.75%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 73        | 27.24%  |
| Intel Core i7      | 58        | 21.64%  |
| Other              | 42        | 15.67%  |
| AMD Ryzen 7        | 19        | 7.09%   |
| Intel Core i3      | 12        | 4.48%   |
| Intel Celeron      | 10        | 3.73%   |
| AMD Ryzen 5        | 9         | 3.36%   |
| Intel Pentium      | 7         | 2.61%   |
| Intel Core 2 Duo   | 6         | 2.24%   |
| Intel Atom         | 6         | 2.24%   |
| AMD Ryzen 7 PRO    | 5         | 1.87%   |
| AMD Ryzen 9        | 4         | 1.49%   |
| Intel Genuine      | 3         | 1.12%   |
| AMD Ryzen 3        | 3         | 1.12%   |
| Intel Xeon         | 1         | 0.37%   |
| Intel Pentium M    | 1         | 0.37%   |
| Intel Pentium Dual | 1         | 0.37%   |
| Intel Core m7      | 1         | 0.37%   |
| Intel Core 2 Solo  | 1         | 0.37%   |
| Intel Core 2       | 1         | 0.37%   |
| AMD FX             | 1         | 0.37%   |
| AMD Embedded       | 1         | 0.37%   |
| AMD E2             | 1         | 0.37%   |
| AMD Athlon         | 1         | 0.37%   |
| AMD A6             | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 103       | 38.43%  |
| 2      | 96        | 35.82%  |
| 8      | 30        | 11.19%  |
| 6      | 15        | 5.6%    |
| 12     | 10        | 3.73%   |
| 1      | 6         | 2.24%   |
| 10     | 5         | 1.87%   |
| 14     | 2         | 0.75%   |
| 16     | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 268       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 218       | 81.34%  |
| 1      | 50        | 18.66%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 264       | 98.51%  |
| 32-bit         | 3         | 1.12%   |
| Unknown        | 1         | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 82        | 29.29%  |
| 0x306a9    | 15        | 5.36%   |
| 0x806c1    | 13        | 4.64%   |
| 0x206a7    | 13        | 4.64%   |
| 0x40651    | 11        | 3.93%   |
| 0x806ea    | 10        | 3.57%   |
| 0x0a50000c | 10        | 3.57%   |
| 0x806eb    | 8         | 2.86%   |
| 0x906e9    | 7         | 2.5%    |
| 0x806e9    | 7         | 2.5%    |
| 0x406e3    | 7         | 2.5%    |
| 0x806ec    | 6         | 2.14%   |
| 0x306d4    | 6         | 2.14%   |
| 0x20655    | 6         | 2.14%   |
| 0x906ea    | 5         | 1.79%   |
| 0x906a3    | 5         | 1.79%   |
| 0x506e3    | 5         | 1.79%   |
| 0x08600106 | 5         | 1.79%   |
| 0x906a4    | 4         | 1.43%   |
| 0x706e5    | 4         | 1.43%   |
| 0x08608103 | 4         | 1.43%   |
| 0x706a8    | 3         | 1.07%   |
| 0x6fd      | 3         | 1.07%   |
| 0x1067a    | 3         | 1.07%   |
| 0x906ed    | 2         | 0.71%   |
| 0x406c4    | 2         | 0.71%   |
| 0x306c3    | 2         | 0.71%   |
| 0x30678    | 2         | 0.71%   |
| 0x106c2    | 2         | 0.71%   |
| 0x0a601203 | 2         | 0.71%   |
| 0x08600104 | 2         | 0.71%   |
| 0x08108109 | 2         | 0.71%   |
| 0x06006705 | 2         | 0.71%   |
| 0xb06a2    | 1         | 0.36%   |
| 0x806d1    | 1         | 0.36%   |
| 0x706a1    | 1         | 0.36%   |
| 0x506c9    | 1         | 0.36%   |
| 0x406c3    | 1         | 0.36%   |
| 0x40661    | 1         | 0.36%   |
| 0x306a8    | 1         | 0.36%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 60        | 22.39%  |
| Unknown          | 24        | 8.96%   |
| IvyBridge        | 20        | 7.46%   |
| Haswell          | 18        | 6.72%   |
| SandyBridge      | 17        | 6.34%   |
| TigerLake        | 16        | 5.97%   |
| Skylake          | 16        | 5.97%   |
| Zen 3            | 13        | 4.85%   |
| Alderlake Hybrid | 12        | 4.48%   |
| Zen 2            | 11        | 4.1%    |
| Westmere         | 11        | 4.1%    |
| IceLake          | 7         | 2.61%   |
| Silvermont       | 6         | 2.24%   |
| Penryn           | 6         | 2.24%   |
| Broadwell        | 6         | 2.24%   |
| Core             | 5         | 1.87%   |
| Goldmont plus    | 4         | 1.49%   |
| Excavator        | 4         | 1.49%   |
| Zen+             | 3         | 1.12%   |
| Zen              | 2         | 0.75%   |
| Goldmont         | 2         | 0.75%   |
| Bonnell          | 2         | 0.75%   |
| P6               | 1         | 0.37%   |
| Nehalem          | 1         | 0.37%   |
| Bobcat           | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 201       | 53.89%  |
| Nvidia | 98        | 26.27%  |
| AMD    | 74        | 19.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 4.74%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 16        | 4.21%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 3.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 3.68%   |
| Intel UHD Graphics 620                                                                   | 13        | 3.42%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 3.16%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 11        | 2.89%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 10        | 2.63%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 9         | 2.37%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 9         | 2.37%   |
| Intel HD Graphics 630                                                                    | 8         | 2.11%   |
| Intel HD Graphics 620                                                                    | 8         | 2.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.11%   |
| Intel HD Graphics 530                                                                    | 7         | 1.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 1.58%   |
| Intel HD Graphics 5500                                                                   | 6         | 1.58%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.58%   |
| AMD Lucienne                                                                             | 6         | 1.58%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 1.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.32%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.05%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 1.05%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.05%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.05%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 1.05%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 4         | 1.05%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 4         | 1.05%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.79%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 0.79%   |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 0.79%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.79%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.79%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 0.79%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.79%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.79%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 0.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.79%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 3         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 106       | 39.41%  |
| Intel + Nvidia | 80        | 29.74%  |
| 1 x AMD        | 47        | 17.47%  |
| Intel + AMD    | 16        | 5.95%   |
| 1 x Nvidia     | 9         | 3.35%   |
| AMD + Nvidia   | 9         | 3.35%   |
| 2 x AMD        | 2         | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 218       | 79.56%  |
| Proprietary | 50        | 18.25%  |
| Unknown     | 6         | 2.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 167       | 60.95%  |
| 1.01-2.0   | 39        | 14.23%  |
| 0.01-0.5   | 36        | 13.14%  |
| 3.01-4.0   | 12        | 4.38%   |
| 0.51-1.0   | 11        | 4.01%   |
| 5.01-6.0   | 7         | 2.55%   |
| 7.01-8.0   | 2         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 69        | 22.62%  |
| Chimei Innolux          | 46        | 15.08%  |
| BOE                     | 41        | 13.44%  |
| LG Display              | 38        | 12.46%  |
| Samsung Electronics     | 16        | 5.25%   |
| Dell                    | 9         | 2.95%   |
| Ancor Communications    | 9         | 2.95%   |
| BenQ                    | 8         | 2.62%   |
| Sharp                   | 6         | 1.97%   |
| Valve                   | 5         | 1.64%   |
| PANDA                   | 5         | 1.64%   |
| Acer                    | 5         | 1.64%   |
| ViewSonic               | 4         | 1.31%   |
| Philips                 | 4         | 1.31%   |
| Lenovo                  | 4         | 1.31%   |
| Goldstar                | 3         | 0.98%   |
| Eizo                    | 3         | 0.98%   |
| ASUSTek Computer        | 3         | 0.98%   |
| Apple                   | 3         | 0.98%   |
| TMX                     | 2         | 0.66%   |
| NEX                     | 2         | 0.66%   |
| LG Philips              | 2         | 0.66%   |
| InfoVision              | 2         | 0.66%   |
| CSO                     | 2         | 0.66%   |
| AOC                     | 2         | 0.66%   |
| Sony                    | 1         | 0.33%   |
| Panasonic               | 1         | 0.33%   |
| Olevia                  | 1         | 0.33%   |
| MStar                   | 1         | 0.33%   |
| IPS                     | 1         | 0.33%   |
| Envision Peripherals    | 1         | 0.33%   |
| CPT                     | 1         | 0.33%   |
| CHR                     | 1         | 0.33%   |
| Chi Mei Optoelectronics | 1         | 0.33%   |
| BOE Technology Group    | 1         | 0.33%   |
| AVX                     | 1         | 0.33%   |
| AGT                     | 1         | 0.33%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 8         | 2.59%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 4         | 1.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 4         | 1.29%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch        | 4         | 1.29%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 4         | 1.29%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 3         | 0.97%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 0.97%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.97%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 0.97%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 2         | 0.65%   |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch              | 2         | 0.65%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch               | 2         | 0.65%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch               | 2         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.65%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 2         | 0.65%   |
| LG Display LCD Monitor LGD06CA 1920x1080 309x174mm 14.0-inch          | 2         | 0.65%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 2         | 0.65%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch       | 2         | 0.65%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.65%   |
| BOE LCD Monitor BOE08A6 1920x1080 294x165mm 13.3-inch                 | 2         | 0.65%   |
| BenQ GW2470 BNQ78E4 1920x1080 527x296mm 23.8-inch                     | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO332C 1366x768 293x165mm 13.2-inch         | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch         | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO2A3C 1366x768 309x173mm 13.9-inch         | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO253D 1920x1080 309x174mm 14.0-inch        | 2         | 0.65%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch         | 2         | 0.65%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 2         | 0.65%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 520x290mm 23.4-inch | 2         | 0.65%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 1         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 147       | 53.07%  |
| 1366x768 (WXGA)    | 60        | 21.66%  |
| 3840x2160 (4K)     | 9         | 3.25%   |
| 2560x1440 (QHD)    | 9         | 3.25%   |
| 1920x1200 (WUXGA)  | 9         | 3.25%   |
| 1600x900 (HD+)     | 6         | 2.17%   |
| 800x1280           | 5         | 1.81%   |
| 2880x1800          | 5         | 1.81%   |
| 2560x1600          | 5         | 1.81%   |
| 1280x800 (WXGA)    | 4         | 1.44%   |
| 2256x1504          | 2         | 0.72%   |
| 1680x1050 (WSXGA+) | 2         | 0.72%   |
| 1024x600           | 2         | 0.72%   |
| 3840x1080          | 1         | 0.36%   |
| 3200x2000          | 1         | 0.36%   |
| 3200x1800 (QHD+)   | 1         | 0.36%   |
| 2560x1080          | 1         | 0.36%   |
| 2288x1287          | 1         | 0.36%   |
| 2160x1440          | 1         | 0.36%   |
| 2048x1152          | 1         | 0.36%   |
| 1680x945           | 1         | 0.36%   |
| 1440x900 (WXGA+)   | 1         | 0.36%   |
| 1280x720 (HD)      | 1         | 0.36%   |
| 1280x1024 (SXGA)   | 1         | 0.36%   |
| Unknown            | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 87        | 28.43%  |
| 13      | 58        | 18.95%  |
| 14      | 57        | 18.63%  |
| 24      | 17        | 5.56%   |
| 23      | 16        | 5.23%   |
| 27      | 10        | 3.27%   |
| 17      | 10        | 3.27%   |
| 21      | 9         | 2.94%   |
| 12      | 7         | 2.29%   |
| 11      | 7         | 2.29%   |
| 7       | 5         | 1.63%   |
| 18      | 4         | 1.31%   |
| 16      | 4         | 1.31%   |
| 31      | 3         | 0.98%   |
| 22      | 3         | 0.98%   |
| 10      | 2         | 0.65%   |
| Unknown | 2         | 0.65%   |
| 55      | 1         | 0.33%   |
| 52      | 1         | 0.33%   |
| 49      | 1         | 0.33%   |
| 40      | 1         | 0.33%   |
| 34      | 1         | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 175       | 57.38%  |
| 201-300     | 45        | 14.75%  |
| 501-600     | 40        | 13.11%  |
| 401-500     | 16        | 5.25%   |
| 351-400     | 12        | 3.93%   |
| 601-700     | 5         | 1.64%   |
| 1-100       | 5         | 1.64%   |
| 1001-1500   | 3         | 0.98%   |
| Unknown     | 2         | 0.66%   |
| 801-900     | 1         | 0.33%   |
| 701-800     | 1         | 0.33%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 221       | 84.67%  |
| 16/10   | 30        | 11.49%  |
| 0.67    | 4         | 1.53%   |
| 3/2     | 3         | 1.15%   |
| 21/9    | 1         | 0.38%   |
| 0.62    | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 91        | 30.03%  |
| 101-110        | 87        | 28.71%  |
| 201-250        | 36        | 11.88%  |
| 71-80          | 26        | 8.58%   |
| 301-350        | 10        | 3.3%    |
| 121-130        | 10        | 3.3%    |
| 51-60          | 7         | 2.31%   |
| 251-300        | 6         | 1.98%   |
| 61-70          | 5         | 1.65%   |
| 1-40           | 5         | 1.65%   |
| 351-500        | 4         | 1.32%   |
| 141-150        | 4         | 1.32%   |
| 111-120        | 4         | 1.32%   |
| More than 1000 | 3         | 0.99%   |
| 41-50          | 2         | 0.66%   |
| Unknown        | 2         | 0.66%   |
| 501-1000       | 1         | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 131       | 43.52%  |
| 101-120       | 67        | 22.26%  |
| 51-100        | 48        | 15.95%  |
| 161-240       | 39        | 12.96%  |
| More than 240 | 11        | 3.65%   |
| 1-50          | 3         | 1%      |
| Unknown       | 2         | 0.66%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 212       | 77.66%  |
| 2     | 48        | 17.58%  |
| 0     | 8         | 2.93%   |
| 3     | 5         | 1.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 150       | 35.38%  |
| Realtek Semiconductor    | 132       | 31.13%  |
| Qualcomm Atheros         | 61        | 14.39%  |
| Broadcom                 | 25        | 5.9%    |
| MediaTek                 | 14        | 3.3%    |
| Broadcom Limited         | 9         | 2.12%   |
| ASIX Electronics         | 8         | 1.89%   |
| Ralink                   | 4         | 0.94%   |
| TP-Link                  | 3         | 0.71%   |
| Marvell Technology Group | 3         | 0.71%   |
| Qualcomm                 | 2         | 0.47%   |
| OPPO Electronics         | 2         | 0.47%   |
| Edimax Technology        | 2         | 0.47%   |
| D-Link                   | 2         | 0.47%   |
| U-Blox                   | 1         | 0.24%   |
| Ralink Technology        | 1         | 0.24%   |
| Qualcomm Technologies    | 1         | 0.24%   |
| Microchip Technology     | 1         | 0.24%   |
| Lenovo                   | 1         | 0.24%   |
| Google                   | 1         | 0.24%   |
| ASUSTek Computer         | 1         | 0.24%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86        | 17.59%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 3.27%   |
| Intel Wireless 8265 / 8275                                        | 16        | 3.27%   |
| Intel Wi-Fi 6 AX200                                               | 16        | 3.27%   |
| Intel Wi-Fi 6 AX201                                               | 14        | 2.86%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 2.45%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 12        | 2.45%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 9         | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 1.64%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 8         | 1.64%   |
| Intel Wireless 7265                                               | 7         | 1.43%   |
| Intel Wireless 7260                                               | 7         | 1.43%   |
| Intel Wireless 3165                                               | 7         | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 1.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 1.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 1.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 1.23%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 1.23%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 1.23%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 5         | 1.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.02%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.82%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 0.82%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.82%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 4         | 0.82%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 0.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 0.82%   |
| Broadcom BCM43225 802.11b/g/n                                     | 4         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 0.82%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 144       | 54.55%  |
| Qualcomm Atheros      | 42        | 15.91%  |
| Realtek Semiconductor | 28        | 10.61%  |
| Broadcom              | 17        | 6.44%   |
| MediaTek              | 14        | 5.3%    |
| Broadcom Limited      | 6         | 2.27%   |
| Ralink                | 4         | 1.52%   |
| TP-Link               | 2         | 0.76%   |
| Qualcomm              | 2         | 0.76%   |
| D-Link                | 2         | 0.76%   |
| Ralink Technology     | 1         | 0.38%   |
| Edimax Technology     | 1         | 0.38%   |
| ASUSTek Computer      | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                     | 16        | 6.04%   |
| Intel Wi-Fi 6 AX200                                            | 16        | 6.04%   |
| Intel Wi-Fi 6 AX201                                            | 14        | 5.28%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 4.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 9         | 3.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 3.02%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 8         | 3.02%   |
| Intel Wireless 7265                                            | 7         | 2.64%   |
| Intel Wireless 7260                                            | 7         | 2.64%   |
| Intel Wireless 3165                                            | 7         | 2.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 2.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 2.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 2.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.26%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 2.26%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 2.26%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 5         | 1.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 1.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 5         | 1.89%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 1.89%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 1.89%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 1.51%   |
| Broadcom BCM43225 802.11b/g/n                                  | 4         | 1.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 1.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 3         | 1.13%   |
| Intel Wireless 8260                                            | 3         | 1.13%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.13%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 1.13%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 3         | 1.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 0.75%   |
| Realtek 802.11ac NIC                                           | 2         | 0.75%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 0.75%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 2         | 0.75%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 0.75%   |
| Intel Wireless-AC 9260                                         | 2         | 0.75%   |
| Intel Wireless 3160                                            | 2         | 0.75%   |
| Intel WiFi Link 5100                                           | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 117       | 54.42%  |
| Intel                    | 37        | 17.21%  |
| Qualcomm Atheros         | 30        | 13.95%  |
| Broadcom                 | 10        | 4.65%   |
| ASIX Electronics         | 8         | 3.72%   |
| Marvell Technology Group | 3         | 1.4%    |
| Broadcom Limited         | 3         | 1.4%    |
| OPPO Electronics         | 2         | 0.93%   |
| TP-Link                  | 1         | 0.47%   |
| Microchip Technology     | 1         | 0.47%   |
| Lenovo                   | 1         | 0.47%   |
| Google                   | 1         | 0.47%   |
| Edimax Technology        | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 86        | 38.74%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 16        | 7.21%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 5.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 2.7%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 6         | 2.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 2.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.8%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 1.8%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 1.8%    |
| Intel Ethernet Connection I218-LM                                 | 4         | 1.8%    |
| Intel Ethernet Connection (4) I219-V                              | 4         | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.35%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.35%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.9%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.9%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.9%    |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 2         | 0.9%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 2         | 0.9%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.9%    |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 0.9%    |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 2         | 0.9%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.45%   |
| Realtek PCIe GbE Family Controller                                | 1         | 0.45%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.45%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.45%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 1         | 0.45%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.45%   |
| Lenovo USB-C Hub                                                  | 1         | 0.45%   |
| Intel WiMAX Connection 2400m                                      | 1         | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.45%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 257       | 55.87%  |
| Ethernet | 201       | 43.7%   |
| Modem    | 1         | 0.22%   |
| Unknown  | 1         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 209       | 74.11%  |
| Ethernet | 73        | 25.89%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 176       | 65.67%  |
| 1     | 87        | 32.46%  |
| 0     | 3         | 1.12%   |
| 5     | 1         | 0.37%   |
| 3     | 1         | 0.37%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 234       | 86.67%  |
| Yes  | 36        | 13.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 127       | 53.14%  |
| Broadcom                        | 16        | 6.69%   |
| Realtek Semiconductor           | 15        | 6.28%   |
| Qualcomm Atheros Communications | 15        | 6.28%   |
| IMC Networks                    | 15        | 6.28%   |
| Foxconn / Hon Hai               | 15        | 6.28%   |
| Lite-On Technology              | 11        | 4.6%    |
| Apple                           | 4         | 1.67%   |
| Toshiba                         | 3         | 1.26%   |
| Realtek                         | 3         | 1.26%   |
| Ralink                          | 3         | 1.26%   |
| MediaTek                        | 3         | 1.26%   |
| Hewlett-Packard                 | 3         | 1.26%   |
| ASUSTek Computer                | 2         | 0.84%   |
| USI                             | 1         | 0.42%   |
| Opticis                         | 1         | 0.42%   |
| Dell                            | 1         | 0.42%   |
| Alps Electric                   | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 45        | 18.83%  |
| Intel Bluetooth Device                            | 35        | 14.64%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 16        | 6.69%   |
| Intel AX200 Bluetooth                             | 16        | 6.69%   |
| Realtek Bluetooth Radio                           | 14        | 5.86%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 6         | 2.51%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 5         | 2.09%   |
| Intel AX210 Bluetooth                             | 5         | 2.09%   |
| Foxconn / Hon Hai Bluetooth Device                | 5         | 2.09%   |
| Intel Wireless-AC 3168 Bluetooth                  | 4         | 1.67%   |
| IMC Networks 802.11ac WLAN Adapter                | 4         | 1.67%   |
| Apple Bluetooth Host Controller                   | 4         | 1.67%   |
| Realtek Bluetooth Radio                           | 3         | 1.26%   |
| Ralink RT3290 Bluetooth                           | 3         | 1.26%   |
| Qualcomm Atheros  Bluetooth Device                | 3         | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 3         | 1.26%   |
| MediaTek Wireless_Device                          | 3         | 1.26%   |
| Lite-On Wireless_Device                           | 3         | 1.26%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 3         | 1.26%   |
| IMC Networks Bluetooth Device                     | 3         | 1.26%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth       | 3         | 1.26%   |
| Foxconn / Hon Hai Acer Bluetooth module           | 3         | 1.26%   |
| Broadcom BCM2045B (BDC-2.1)                       | 3         | 1.26%   |
| Toshiba Bluetooth USB Host Controller             | 2         | 0.84%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 0.84%   |
| Lite-On Bluetooth Device                          | 2         | 0.84%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 0.84%   |
| IMC Networks Wireless_Device                      | 2         | 0.84%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 2         | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 0.84%   |
| Broadcom Bluetooth                                | 2         | 0.84%   |
| Broadcom BCM20702A0                               | 2         | 0.84%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 0.84%   |
| Broadcom BCM2045 Bluetooth                        | 2         | 0.84%   |
| USI Bluetooth Device                              | 1         | 0.42%   |
| Toshiba Askey Bluetooth Module                    | 1         | 0.42%   |
| Realtek RTL8723B Bluetooth                        | 1         | 0.42%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.42%   |
| Opticis Bluetooth Radio                           | 1         | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 211       | 65.53%  |
| AMD                     | 60        | 18.63%  |
| Nvidia                  | 39        | 12.11%  |
| C-Media Electronics     | 3         | 0.93%   |
| ASUSTek Computer        | 2         | 0.62%   |
| Texas Instruments       | 1         | 0.31%   |
| Realtek Semiconductor   | 1         | 0.31%   |
| Logitech                | 1         | 0.31%   |
| GN Netcom               | 1         | 0.31%   |
| ESS Technology          | 1         | 0.31%   |
| Dell                    | 1         | 0.31%   |
| Cambridge Silicon Radio | 1         | 0.31%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 41        | 10.41%  |
| Intel Sunrise Point-LP HD Audio                                            | 31        | 7.87%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 30        | 7.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 5.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 16        | 4.06%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 16        | 4.06%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 15        | 3.81%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 3.55%   |
| Intel 8 Series HD Audio Controller                                         | 14        | 3.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 13        | 3.3%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 12        | 3.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 2.79%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 10        | 2.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 2.03%   |
| Intel CM238 HD Audio Controller                                            | 7         | 1.78%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 6         | 1.52%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 1.52%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 1.52%   |
| Intel Broadwell-U Audio Controller                                         | 6         | 1.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 1.52%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 1.27%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 1.27%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.02%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.02%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 4         | 1.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 4         | 1.02%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 4         | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 4         | 1.02%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 0.76%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.76%   |
| Nvidia Audio device                                                        | 3         | 0.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 3         | 0.76%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 0.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 0.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.76%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.51%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.51%   |
| Intel USB PnP Sound Device                                                 | 2         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 51        | 23.83%  |
| Samsung Electronics | 45        | 21.03%  |
| Micron Technology   | 30        | 14.02%  |
| Kingston            | 21        | 9.81%   |
| Crucial             | 19        | 8.88%   |
| Transcend           | 10        | 4.67%   |
| Unknown             | 7         | 3.27%   |
| A-DATA Technology   | 6         | 2.8%    |
| Elpida              | 3         | 1.4%    |
| Apacer              | 3         | 1.4%    |
| Unknown (ABCD)      | 2         | 0.93%   |
| Ramaxel Technology  | 2         | 0.93%   |
| Nanya Technology    | 2         | 0.93%   |
| Goldkey             | 2         | 0.93%   |
| G-Alantic           | 2         | 0.93%   |
| Unknown (08AE)      | 1         | 0.47%   |
| Team                | 1         | 0.47%   |
| PNY                 | 1         | 0.47%   |
| Patriot             | 1         | 0.47%   |
| Lexar               | 1         | 0.47%   |
| G.Skill             | 1         | 0.47%   |
| Avant               | 1         | 0.47%   |
| ASint Technology    | 1         | 0.47%   |
| Unknown             | 1         | 0.47%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.75%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 3         | 1.31%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 1.31%   |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s           | 3         | 1.31%   |
| Transcend RAM Module 16GB SODIMM DDR4 3200MT/s                   | 2         | 0.87%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.87%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.87%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.87%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s        | 2         | 0.87%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.87%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.87%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.87%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.87%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.87%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.87%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.87%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.87%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 0.87%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.87%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2667MT/s            | 2         | 0.87%   |
| G-Alantic RAM D4SS12161SH26A-C 4GB SODIMM DDR4 2133MT/s          | 2         | 0.87%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s           | 2         | 0.87%   |
| Crucial RAM CT8G4SFS632A.C4FE 8GB SODIMM DDR4 3200MT/s           | 2         | 0.87%   |
| Crucial RAM CT16G4SFRA32A.C8FE 16GB SODIMM DDR4 3200MT/s         | 2         | 0.87%   |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 0.87%   |
| Crucial RAM CT16G4SFD8266.M16FE 16GB SODIMM DDR4 2667MT/s        | 2         | 0.87%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.44%   |
| Unknown RAM Module 1024MB SODIMM DDR2 800MT/s                    | 1         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.44%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 1         | 0.44%   |
| Unknown (08AE) RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.44%   |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.44%   |
| Transcend RAM TS512MSK64V6N 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 89        | 51.15%  |
| DDR3    | 39        | 22.41%  |
| LPDDR4  | 17        | 9.77%   |
| LPDDR3  | 9         | 5.17%   |
| LPDDR5  | 8         | 4.6%    |
| DDR5    | 5         | 2.87%   |
| DDR2    | 3         | 1.72%   |
| SDRAM   | 2         | 1.15%   |
| Unknown | 2         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 140       | 80.46%  |
| Row Of Chips | 30        | 17.24%  |
| DIMM         | 2         | 1.15%   |
| Chip         | 1         | 0.57%   |
| Unknown      | 1         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 74        | 38.95%  |
| 4096  | 52        | 27.37%  |
| 16384 | 37        | 19.47%  |
| 2048  | 13        | 6.84%   |
| 32768 | 11        | 5.79%   |
| 1024  | 2         | 1.05%   |
| 8072  | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 48        | 26.09%  |
| 2667  | 32        | 17.39%  |
| 1600  | 30        | 16.3%   |
| 2400  | 13        | 7.07%   |
| 2133  | 12        | 6.52%   |
| 1334  | 8         | 4.35%   |
| 6400  | 7         | 3.8%    |
| 4266  | 6         | 3.26%   |
| 4267  | 5         | 2.72%   |
| 5600  | 3         | 1.63%   |
| 4800  | 3         | 1.63%   |
| 1867  | 3         | 1.63%   |
| 533   | 2         | 1.09%   |
| 8400  | 1         | 0.54%   |
| 7500  | 1         | 0.54%   |
| 4199  | 1         | 0.54%   |
| 3733  | 1         | 0.54%   |
| 3266  | 1         | 0.54%   |
| 2666  | 1         | 0.54%   |
| 2000  | 1         | 0.54%   |
| 1333  | 1         | 0.54%   |
| 1067  | 1         | 0.54%   |
| 1066  | 1         | 0.54%   |
| 975   | 1         | 0.54%   |
| 800   | 1         | 0.54%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Seiko Epson L3110 Series | 1         | 100%    |

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
| Chicony Electronics                    | 62        | 27.8%   |
| IMC Networks                           | 30        | 13.45%  |
| Realtek Semiconductor                  | 26        | 11.66%  |
| Bison Electronics                      | 17        | 7.62%   |
| Sunplus Innovation Technology          | 13        | 5.83%   |
| Quanta                                 | 12        | 5.38%   |
| Microdia                               | 10        | 4.48%   |
| Suyin                                  | 8         | 3.59%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.69%   |
| Syntek                                 | 5         | 2.24%   |
| Luxvisions Innotech Limited            | 5         | 2.24%   |
| Apple                                  | 3         | 1.35%   |
| ALi                                    | 3         | 1.35%   |
| Acer                                   | 3         | 1.35%   |
| Sunplus Technology                     | 2         | 0.9%    |
| Sonix Technology                       | 2         | 0.9%    |
| Ricoh                                  | 2         | 0.9%    |
| Lite-On Technology                     | 2         | 0.9%    |
| Lenovo                                 | 2         | 0.9%    |
| Importek                               | 2         | 0.9%    |
| SunplusIT                              | 1         | 0.45%   |
| Silicon Motion                         | 1         | 0.45%   |
| Shinetech                              | 1         | 0.45%   |
| Samsung Electronics                    | 1         | 0.45%   |
| Logitech                               | 1         | 0.45%   |
| Google                                 | 1         | 0.45%   |
| Generalplus Technology                 | 1         | 0.45%   |
| Foxconn / Hon Hai                      | 1         | 0.45%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 14        | 6.25%   |
| Chicony Integrated Camera                                                  | 14        | 6.25%   |
| Chicony HD WebCam                                                          | 9         | 4.02%   |
| Realtek Integrated_Webcam_HD                                               | 8         | 3.57%   |
| Bison HD Webcam                                                            | 8         | 3.57%   |
| Sunplus HD WebCam                                                          | 6         | 2.68%   |
| IMC Networks Integrated Camera                                             | 6         | 2.68%   |
| Chicony HP HD Camera                                                       | 5         | 2.23%   |
| Chicony HD User Facing                                                     | 5         | 2.23%   |
| Realtek USB camera                                                         | 4         | 1.79%   |
| Quanta HD User Facing                                                      | 4         | 1.79%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 1.79%   |
| Chicony USB2.0 HD UVC WebCam                                               | 4         | 1.79%   |
| Chicony Lenovo EasyCamera                                                  | 4         | 1.79%   |
| Syntek Integrated Camera                                                   | 3         | 1.34%   |
| Realtek HD WebCam                                                          | 3         | 1.34%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 1.34%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.34%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.34%   |
| Bison Integrated Camera                                                    | 3         | 1.34%   |
| ALi Gateway Webcam                                                         | 3         | 1.34%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 2         | 0.89%   |
| Suyin 1.3M HD WebCam                                                       | 2         | 0.89%   |
| Sunplus 1.3M HD WebCam                                                     | 2         | 0.89%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.89%   |
| Sunplus Integrated_Webcam_FHD                                              | 2         | 0.89%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 2         | 0.89%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 0.89%   |
| Quanta HP HD Camera                                                        | 2         | 0.89%   |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 0.89%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 0.89%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.89%   |
| IMC Networks UVC VGA Webcam                                                | 2         | 0.89%   |
| IMC Networks USB2.0 UVC HD Webcam                                          | 2         | 0.89%   |
| Chicony Webcam                                                             | 2         | 0.89%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 0.89%   |
| Chicony USB2.0 Camera                                                      | 2         | 0.89%   |
| Chicony USB 2.0 Webcam Device                                              | 2         | 0.89%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 0.89%   |
| Bison SunplusIT Integrated Camera                                          | 2         | 0.89%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 15        | 26.79%  |
| Validity Sensors                   | 10        | 17.86%  |
| LighTuning Technology              | 9         | 16.07%  |
| Shenzhen Goodix Technology         | 8         | 14.29%  |
| Elan Microelectronics              | 6         | 10.71%  |
| Upek                               | 4         | 7.14%   |
| AuthenTec                          | 3         | 5.36%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                             | 5         | 8.93%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 5         | 8.93%   |
| Elan ELAN:Fingerprint                                           | 5         | 8.93%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 7.14%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 3         | 5.36%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 5.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 5.36%   |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 5.36%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 3         | 5.36%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 2         | 3.57%   |
| Validity Sensors VFS Fingerprint sensor                         | 2         | 3.57%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 2         | 3.57%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 2         | 3.57%   |
| Synaptics Fingerprint reader [HP G6]                            | 2         | 3.57%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 1.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 1.79%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.79%   |
| Synaptics WBDI                                                  | 1         | 1.79%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                    | 1         | 1.79%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 1.79%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.79%   |
| LighTuning Fingerprint Reader                                   | 1         | 1.79%   |
| Elan fingerprint sensor [FeinTech FPS00200]                     | 1         | 1.79%   |
| AuthenTec AES2810                                               | 1         | 1.79%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 1         | 1.79%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 1.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 35.71%  |
| Broadcom              | 4         | 28.57%  |
| Upek                  | 2         | 14.29%  |
| SCM Microsystems      | 1         | 7.14%   |
| Lenovo                | 1         | 7.14%   |
| Gemalto (was Gemplus) | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 14.29%  |
| Broadcom 58200                                                               | 2         | 14.29%  |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 7.14%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 7.14%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 7.14%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 167       | 59.86%  |
| 1     | 88        | 31.54%  |
| 2     | 21        | 7.53%   |
| 3     | 2         | 0.72%   |
| 4     | 1         | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 56        | 44.44%  |
| Graphics card            | 27        | 21.43%  |
| Chipcard                 | 10        | 7.94%   |
| Net/wireless             | 8         | 6.35%   |
| Camera                   | 8         | 6.35%   |
| Multimedia controller    | 5         | 3.97%   |
| Bluetooth                | 4         | 3.17%   |
| Card reader              | 3         | 2.38%   |
| Net/ethernet             | 2         | 1.59%   |
| Storage/nvme             | 1         | 0.79%   |
| Sound                    | 1         | 0.79%   |
| Communication controller | 1         | 0.79%   |

