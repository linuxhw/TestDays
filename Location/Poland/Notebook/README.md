Linux in Poland - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Poland.

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

Total: 4697

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Legion Y540-15IRH 81SX      | [1da691596b](https://linux-hardware.org/?probe=1da691596b) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d385d4714c](https://linux-hardware.org/?probe=d385d4714c) | Nov 06, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [d40cc6e0a4](https://linux-hardware.org/?probe=d40cc6e0a4) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| Dell          | XPS 17 9720                 | [39e8a692ae](https://linux-hardware.org/?probe=39e8a692ae) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [fd9594de89](https://linux-hardware.org/?probe=fd9594de89) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [a5a8cf5c09](https://linux-hardware.org/?probe=a5a8cf5c09) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [74099b3a6e](https://linux-hardware.org/?probe=74099b3a6e) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | [bdad71bf99](https://linux-hardware.org/?probe=bdad71bf99) | Nov 05, 2023 |
| HP            | 255 G7 Notebook PC          | [bdd24f60d2](https://linux-hardware.org/?probe=bdd24f60d2) | Nov 05, 2023 |
| Lenovo        | ThinkPad T460 20FMS3YT01    | [89b8df73c1](https://linux-hardware.org/?probe=89b8df73c1) | Nov 04, 2023 |
| Dell          | Inspiron 16 5620            | [04d425d450](https://linux-hardware.org/?probe=04d425d450) | Nov 04, 2023 |
| Lenovo        | 80SY                        | [7c7a6ba82f](https://linux-hardware.org/?probe=7c7a6ba82f) | Nov 04, 2023 |
| Unknown       | Unknown                     | [9999b9fa3d](https://linux-hardware.org/?probe=9999b9fa3d) | Nov 04, 2023 |
| MSI           | GV62 7RE                    | [a6ce21c9de](https://linux-hardware.org/?probe=a6ce21c9de) | Nov 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| Dell          | Latitude E6420              | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [4ccd2ef567](https://linux-hardware.org/?probe=4ccd2ef567) | Nov 03, 2023 |
| Acer          | Aspire V3-771               | [3a0023b4ba](https://linux-hardware.org/?probe=3a0023b4ba) | Nov 03, 2023 |
| Acer          | Nitro AN515-54              | [3ddccb994b](https://linux-hardware.org/?probe=3ddccb994b) | Nov 03, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [027a0a96da](https://linux-hardware.org/?probe=027a0a96da) | Nov 02, 2023 |
| Dell          | Latitude E6420              | [cdef3b5f1c](https://linux-hardware.org/?probe=cdef3b5f1c) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [0c8b2cd660](https://linux-hardware.org/?probe=0c8b2cd660) | Nov 01, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [45d3b00840](https://linux-hardware.org/?probe=45d3b00840) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| HP            | Pavilion g7                 | [157c592b3a](https://linux-hardware.org/?probe=157c592b3a) | Nov 01, 2023 |
| Dell          | Inspiron 13-5368            | [6d00cda16c](https://linux-hardware.org/?probe=6d00cda16c) | Nov 01, 2023 |
| Dell          | Latitude 3190               | [dc68dc55c9](https://linux-hardware.org/?probe=dc68dc55c9) | Oct 31, 2023 |
| HP            | Laptop 15s-eq0xxx           | [1323e3ad04](https://linux-hardware.org/?probe=1323e3ad04) | Oct 31, 2023 |
| Acer          | Aspire V3-771               | [00ffbda72d](https://linux-hardware.org/?probe=00ffbda72d) | Oct 31, 2023 |
| Apple         | MacBookPro14,1              | [12e8c83970](https://linux-hardware.org/?probe=12e8c83970) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Dell          | Precision M6600             | [30e8d1522d](https://linux-hardware.org/?probe=30e8d1522d) | Oct 29, 2023 |
| HUAWEI        | HKD-WXX                     | [101c8c676c](https://linux-hardware.org/?probe=101c8c676c) | Oct 29, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [f78fcbc612](https://linux-hardware.org/?probe=f78fcbc612) | Oct 28, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bbba3e21c7](https://linux-hardware.org/?probe=bbba3e21c7) | Oct 27, 2023 |
| Dell          | Inspiron 1525               | [0a0a08dd5f](https://linux-hardware.org/?probe=0a0a08dd5f) | Oct 26, 2023 |
| MSI           | MS-1688                     | [c3689c0452](https://linux-hardware.org/?probe=c3689c0452) | Oct 26, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [7f10f1b379](https://linux-hardware.org/?probe=7f10f1b379) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [e3c1de1472](https://linux-hardware.org/?probe=e3c1de1472) | Oct 26, 2023 |
| Valve         | Jupiter                     | [38a8824fe8](https://linux-hardware.org/?probe=38a8824fe8) | Oct 25, 2023 |
| HP            | Compaq 610                  | [f449560c8a](https://linux-hardware.org/?probe=f449560c8a) | Oct 25, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [6c88fcef70](https://linux-hardware.org/?probe=6c88fcef70) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| Notebook      | P7xxDM(-G)                  | [bb211b2fb4](https://linux-hardware.org/?probe=bb211b2fb4) | Oct 24, 2023 |
| Dell          | Inspiron 5737               | [06247cab2e](https://linux-hardware.org/?probe=06247cab2e) | Oct 24, 2023 |
| Dell          | Inspiron 11 - 3147          | [7be979fc66](https://linux-hardware.org/?probe=7be979fc66) | Oct 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8da5e9e836](https://linux-hardware.org/?probe=8da5e9e836) | Oct 23, 2023 |
| Lenovo        | ThinkPad A485 20MVS0X62X    | [52661c1969](https://linux-hardware.org/?probe=52661c1969) | Oct 22, 2023 |
| HP            | 250 G8 Notebook PC          | [9538ff99bf](https://linux-hardware.org/?probe=9538ff99bf) | Oct 22, 2023 |
| ASUSTek       | K53SV                       | [66d1164d86](https://linux-hardware.org/?probe=66d1164d86) | Oct 21, 2023 |
| Dell          | Precision 5520              | [79b5c73851](https://linux-hardware.org/?probe=79b5c73851) | Oct 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [dca6ad28b3](https://linux-hardware.org/?probe=dca6ad28b3) | Oct 21, 2023 |
| Lenovo        | G510 20238                  | [d6bd0eda6d](https://linux-hardware.org/?probe=d6bd0eda6d) | Oct 21, 2023 |
| Dell          | Inspiron 5559               | [83811b2a84](https://linux-hardware.org/?probe=83811b2a84) | Oct 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1ff62f5fd7](https://linux-hardware.org/?probe=1ff62f5fd7) | Oct 21, 2023 |
| Dell          | XPS 15 9520                 | [7deca235e3](https://linux-hardware.org/?probe=7deca235e3) | Oct 20, 2023 |
| Dell          | Latitude 5440               | [e3760f51a8](https://linux-hardware.org/?probe=e3760f51a8) | Oct 19, 2023 |
| Dell          | Latitude 5440               | [257850f5d8](https://linux-hardware.org/?probe=257850f5d8) | Oct 18, 2023 |
| Dell          | Latitude 5440               | [2097e4ed5e](https://linux-hardware.org/?probe=2097e4ed5e) | Oct 18, 2023 |
| Unknown       | Unknown                     | [e1751f1726](https://linux-hardware.org/?probe=e1751f1726) | Oct 17, 2023 |
| Dell          | Latitude E6420              | [f703c6bd74](https://linux-hardware.org/?probe=f703c6bd74) | Oct 17, 2023 |
| Acer          | Aspire A315-56              | [9eb823dcdd](https://linux-hardware.org/?probe=9eb823dcdd) | Oct 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7b5cf8abfc](https://linux-hardware.org/?probe=7b5cf8abfc) | Oct 17, 2023 |
| Dell          | Latitude 3190               | [6524dff50f](https://linux-hardware.org/?probe=6524dff50f) | Oct 17, 2023 |
| HP            | ProBook 6560b               | [3567f55849](https://linux-hardware.org/?probe=3567f55849) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [77c1531b00](https://linux-hardware.org/?probe=77c1531b00) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y580 20132          | [2960de2715](https://linux-hardware.org/?probe=2960de2715) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fd52faa27e](https://linux-hardware.org/?probe=fd52faa27e) | Oct 15, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [39d3b3133e](https://linux-hardware.org/?probe=39d3b3133e) | Oct 14, 2023 |
| HP            | ProBook 6560b               | [49ffe8b6c5](https://linux-hardware.org/?probe=49ffe8b6c5) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d68359ee50](https://linux-hardware.org/?probe=d68359ee50) | Oct 14, 2023 |
| HP            | EliteBook 830 13 inch G1... | [e9ced529e2](https://linux-hardware.org/?probe=e9ced529e2) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Lenovo        | ThinkPad T400 64757D7       | [b374e214af](https://linux-hardware.org/?probe=b374e214af) | Oct 13, 2023 |
| MSI           | GE72 6QF                    | [94f1c85d10](https://linux-hardware.org/?probe=94f1c85d10) | Oct 13, 2023 |
| HP            | Grunt                       | [af80cd9bd6](https://linux-hardware.org/?probe=af80cd9bd6) | Oct 13, 2023 |
| ASUSTek       | X510UQ                      | [0494369566](https://linux-hardware.org/?probe=0494369566) | Oct 12, 2023 |
| Lenovo        | IdeaPad P500 20210          | [ba316cb723](https://linux-hardware.org/?probe=ba316cb723) | Oct 12, 2023 |
| Lenovo        | Legion 5 15ARH7 82RE        | [c83831e304](https://linux-hardware.org/?probe=c83831e304) | Oct 11, 2023 |
| MSI           | GL75 9SE                    | [bffc7bdfe6](https://linux-hardware.org/?probe=bffc7bdfe6) | Oct 11, 2023 |
| Dell          | Latitude 5511               | [164cc57420](https://linux-hardware.org/?probe=164cc57420) | Oct 10, 2023 |
| Dell          | Latitude 5511               | [9827df8ea8](https://linux-hardware.org/?probe=9827df8ea8) | Oct 10, 2023 |
| Dell          | XPS 15 9520                 | [04fbcfc11b](https://linux-hardware.org/?probe=04fbcfc11b) | Oct 10, 2023 |
| Dell          | Latitude E5530 non-vPro     | [df4f5f4e21](https://linux-hardware.org/?probe=df4f5f4e21) | Oct 09, 2023 |
| Acer          | Aspire 5755G                | [d4efaf21cb](https://linux-hardware.org/?probe=d4efaf21cb) | Oct 08, 2023 |
| Google        | Sasuke                      | [ea2d350776](https://linux-hardware.org/?probe=ea2d350776) | Oct 08, 2023 |
| HP            | EliteBook 745 G4            | [8a9290f8a1](https://linux-hardware.org/?probe=8a9290f8a1) | Oct 08, 2023 |
| Acer          | Aspire 5755G                | [889b36122b](https://linux-hardware.org/?probe=889b36122b) | Oct 08, 2023 |
| Google        | Lindar                      | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3cfe6c7d0c](https://linux-hardware.org/?probe=3cfe6c7d0c) | Oct 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c0a093d7d2](https://linux-hardware.org/?probe=c0a093d7d2) | Oct 08, 2023 |
| Samsung       | 550P5C/550P7C               | [a95183052c](https://linux-hardware.org/?probe=a95183052c) | Oct 08, 2023 |
| HP            | EliteBook 840 G5            | [3ce37336af](https://linux-hardware.org/?probe=3ce37336af) | Oct 06, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [c07c01c9e6](https://linux-hardware.org/?probe=c07c01c9e6) | Oct 06, 2023 |
| Apple         | MacBookAir5,2               | [6c5a7d30f3](https://linux-hardware.org/?probe=6c5a7d30f3) | Oct 06, 2023 |
| HUAWEI        | KLVL-WXX9                   | [3b01422b2a](https://linux-hardware.org/?probe=3b01422b2a) | Oct 05, 2023 |
| Apple         | MacBookAir5,2               | [7ad16296eb](https://linux-hardware.org/?probe=7ad16296eb) | Oct 05, 2023 |
| HP            | EliteBook 735 G6            | [94ac6e4439](https://linux-hardware.org/?probe=94ac6e4439) | Oct 04, 2023 |
| GPU Compan... | GWTN156-11                  | [8a684c7512](https://linux-hardware.org/?probe=8a684c7512) | Oct 04, 2023 |
| Apple         | MacBookPro4,1               | [e31f443ff9](https://linux-hardware.org/?probe=e31f443ff9) | Oct 04, 2023 |
| HP            | EliteBook 840 G2            | [4161bb4b7f](https://linux-hardware.org/?probe=4161bb4b7f) | Oct 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [c40f80d33a](https://linux-hardware.org/?probe=c40f80d33a) | Oct 03, 2023 |
| Dell          | Latitude 3190               | [21aac15234](https://linux-hardware.org/?probe=21aac15234) | Oct 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [001368f3a9](https://linux-hardware.org/?probe=001368f3a9) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | [880b4780ee](https://linux-hardware.org/?probe=880b4780ee) | Oct 03, 2023 |
| Lenovo        | ThinkPad X390 20Q1S5K400    | [4d9d1bf62a](https://linux-hardware.org/?probe=4d9d1bf62a) | Oct 02, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [09b97f9681](https://linux-hardware.org/?probe=09b97f9681) | Oct 02, 2023 |
| Dell          | Inspiron 13-5368            | [b7463e19f8](https://linux-hardware.org/?probe=b7463e19f8) | Oct 02, 2023 |
| HP            | ProBook 6560b               | [ea59e8557f](https://linux-hardware.org/?probe=ea59e8557f) | Oct 01, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f52bb9587d](https://linux-hardware.org/?probe=f52bb9587d) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [6c314cd812](https://linux-hardware.org/?probe=6c314cd812) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [61a08e5e89](https://linux-hardware.org/?probe=61a08e5e89) | Oct 01, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0a11dba9ac](https://linux-hardware.org/?probe=0a11dba9ac) | Sep 30, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [48ff113276](https://linux-hardware.org/?probe=48ff113276) | Sep 30, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [d180995f93](https://linux-hardware.org/?probe=d180995f93) | Sep 30, 2023 |
| Acer          | Aspire E5-571G              | [b223d9b4f5](https://linux-hardware.org/?probe=b223d9b4f5) | Sep 30, 2023 |
| Dell          | Latitude 5430               | [eee2a34ff5](https://linux-hardware.org/?probe=eee2a34ff5) | Sep 30, 2023 |
| HP            | ProBook 6560b               | [904f0eb2cb](https://linux-hardware.org/?probe=904f0eb2cb) | Sep 30, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a0e4942d9f](https://linux-hardware.org/?probe=a0e4942d9f) | Sep 30, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [702d68e226](https://linux-hardware.org/?probe=702d68e226) | Sep 30, 2023 |
| HP            | Notebook                    | [193ec8deb3](https://linux-hardware.org/?probe=193ec8deb3) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [6e7e482b2d](https://linux-hardware.org/?probe=6e7e482b2d) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [cd9628c344](https://linux-hardware.org/?probe=cd9628c344) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| ASUSTek       | K55VJ                       | [4befa6db63](https://linux-hardware.org/?probe=4befa6db63) | Sep 29, 2023 |
| Lenovo        | IdeaPad Y530                | [83a6d1b19b](https://linux-hardware.org/?probe=83a6d1b19b) | Sep 28, 2023 |
| HP            | 620                         | [1bdfd56638](https://linux-hardware.org/?probe=1bdfd56638) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXX9                   | [5646b6da22](https://linux-hardware.org/?probe=5646b6da22) | Sep 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [4f1f07158b](https://linux-hardware.org/?probe=4f1f07158b) | Sep 26, 2023 |
| Google        | Blorb                       | [efa4ad9e2c](https://linux-hardware.org/?probe=efa4ad9e2c) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | [d4137582b5](https://linux-hardware.org/?probe=d4137582b5) | Sep 26, 2023 |
| Google        | Phaser360                   | [95686db08c](https://linux-hardware.org/?probe=95686db08c) | Sep 26, 2023 |
| Lenovo        | ThinkPad T590 20N5S31U02    | [aa988ac4df](https://linux-hardware.org/?probe=aa988ac4df) | Sep 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S77U1... | [4a3185fd78](https://linux-hardware.org/?probe=4a3185fd78) | Sep 26, 2023 |
| HP            | EliteBook 840 G3            | [5ab77e3f48](https://linux-hardware.org/?probe=5ab77e3f48) | Sep 26, 2023 |
| Dell          | Latitude 3190               | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |
| Dell          | Inspiron 3581               | [11796876dd](https://linux-hardware.org/?probe=11796876dd) | Sep 25, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| Dell          | System Vostro 3750          | [3b050c2582](https://linux-hardware.org/?probe=3b050c2582) | Sep 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [ff891ca545](https://linux-hardware.org/?probe=ff891ca545) | Sep 24, 2023 |
| HP            | 250 G8 Notebook PC          | [6b3c3ce703](https://linux-hardware.org/?probe=6b3c3ce703) | Sep 23, 2023 |
| HP            | 250 G8 Notebook PC          | [e2dd7767f0](https://linux-hardware.org/?probe=e2dd7767f0) | Sep 23, 2023 |
| Dell          | Precision M6600             | [1cef385aec](https://linux-hardware.org/?probe=1cef385aec) | Sep 23, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [4bf358cd4f](https://linux-hardware.org/?probe=4bf358cd4f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [1d9ae81bf1](https://linux-hardware.org/?probe=1d9ae81bf1) | Sep 22, 2023 |
| Dell          | Latitude 5421               | [fd5892945d](https://linux-hardware.org/?probe=fd5892945d) | Sep 21, 2023 |
| Dell          | Latitude 5421               | [50a3d79521](https://linux-hardware.org/?probe=50a3d79521) | Sep 21, 2023 |
| Lenovo        | ThinkPad X270 20HMS0DF00    | [276048d4f4](https://linux-hardware.org/?probe=276048d4f4) | Sep 20, 2023 |
| HP            | ProBook 6560b               | [a7eae64ec7](https://linux-hardware.org/?probe=a7eae64ec7) | Sep 20, 2023 |
| Lenovo        | ThinkPad E580 20KS001RUK    | [9882734ee2](https://linux-hardware.org/?probe=9882734ee2) | Sep 20, 2023 |
| HP            | EliteBook 735 G6            | [0ad032f320](https://linux-hardware.org/?probe=0ad032f320) | Sep 19, 2023 |
| Dell          | Latitude 3190               | [0a698044d8](https://linux-hardware.org/?probe=0a698044d8) | Sep 19, 2023 |
| HP            | Notebook                    | [c41430992d](https://linux-hardware.org/?probe=c41430992d) | Sep 18, 2023 |
| Dell          | Latitude 5490               | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMS    | [13de66f73a](https://linux-hardware.org/?probe=13de66f73a) | Sep 17, 2023 |
| Dell          | Latitude E5420              | [56c6b73d62](https://linux-hardware.org/?probe=56c6b73d62) | Sep 17, 2023 |
| Dell          | Latitude E5420              | [5931b51b00](https://linux-hardware.org/?probe=5931b51b00) | Sep 17, 2023 |
| HP            | G72                         | [b77f2ba361](https://linux-hardware.org/?probe=b77f2ba361) | Sep 17, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [832c9cf416](https://linux-hardware.org/?probe=832c9cf416) | Sep 17, 2023 |
| Lenovo        | Z51-70 80K6                 | [8368825071](https://linux-hardware.org/?probe=8368825071) | Sep 17, 2023 |
| Dell          | Latitude 5421               | [a42c87b953](https://linux-hardware.org/?probe=a42c87b953) | Sep 17, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [ef3516c115](https://linux-hardware.org/?probe=ef3516c115) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | [ba678c25e1](https://linux-hardware.org/?probe=ba678c25e1) | Sep 17, 2023 |
| IGEL Techn... | M330C                       | [b056244ce9](https://linux-hardware.org/?probe=b056244ce9) | Sep 17, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9915642af4](https://linux-hardware.org/?probe=9915642af4) | Sep 16, 2023 |
| Dell          | Latitude 9420               | [35feb16995](https://linux-hardware.org/?probe=35feb16995) | Sep 15, 2023 |
| Dell          | Latitude 9420               | [da407d0553](https://linux-hardware.org/?probe=da407d0553) | Sep 15, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [d321e5cfc8](https://linux-hardware.org/?probe=d321e5cfc8) | Sep 14, 2023 |
| Acer          | Nitro AN515-42              | [96f4c972a0](https://linux-hardware.org/?probe=96f4c972a0) | Sep 14, 2023 |
| ASUSTek       | P553UJ                      | [3463413300](https://linux-hardware.org/?probe=3463413300) | Sep 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [d4e392a0ad](https://linux-hardware.org/?probe=d4e392a0ad) | Sep 12, 2023 |
| Dell          | Latitude E4200              | [ab13ebe930](https://linux-hardware.org/?probe=ab13ebe930) | Sep 12, 2023 |
| Dell          | Latitude 3190               | [a03ec42023](https://linux-hardware.org/?probe=a03ec42023) | Sep 12, 2023 |
| Lenovo        | G565 20071                  | [34149789e7](https://linux-hardware.org/?probe=34149789e7) | Sep 12, 2023 |
| HP            | 620                         | [59577ac122](https://linux-hardware.org/?probe=59577ac122) | Sep 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [27b430aa3f](https://linux-hardware.org/?probe=27b430aa3f) | Sep 11, 2023 |
| Dell          | Precision 5530              | [7e0e7dca27](https://linux-hardware.org/?probe=7e0e7dca27) | Sep 10, 2023 |
| LG Electro... | 15Z990-U.AAS5U1             | [61eed61cd5](https://linux-hardware.org/?probe=61eed61cd5) | Sep 10, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [f01636c129](https://linux-hardware.org/?probe=f01636c129) | Sep 09, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | [e35abd1445](https://linux-hardware.org/?probe=e35abd1445) | Sep 09, 2023 |
| HP            | ProBook 6470b               | [1c8817d025](https://linux-hardware.org/?probe=1c8817d025) | Sep 09, 2023 |
| Acer          | Nitro AN515-44              | [032db27cfa](https://linux-hardware.org/?probe=032db27cfa) | Sep 08, 2023 |
| Lenovo        | G565 20071                  | [786aafb0e9](https://linux-hardware.org/?probe=786aafb0e9) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d3e36fc6ea](https://linux-hardware.org/?probe=d3e36fc6ea) | Sep 05, 2023 |
| Dell          | Precision M4800             | [2e40a27b2e](https://linux-hardware.org/?probe=2e40a27b2e) | Sep 04, 2023 |
| Prestigio     | Smartbook PSB116A           | [d70df77a35](https://linux-hardware.org/?probe=d70df77a35) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [2a24e7410f](https://linux-hardware.org/?probe=2a24e7410f) | Sep 03, 2023 |
| Unknown       | Unknown                     | [8585671bfb](https://linux-hardware.org/?probe=8585671bfb) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [efd96ce796](https://linux-hardware.org/?probe=efd96ce796) | Sep 03, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [5f73c55303](https://linux-hardware.org/?probe=5f73c55303) | Sep 03, 2023 |
| Lenovo        | ThinkPad X280 20KESAA400    | [461a3a9bc9](https://linux-hardware.org/?probe=461a3a9bc9) | Sep 02, 2023 |
| Valve         | Jupiter                     | [fd0297e4e0](https://linux-hardware.org/?probe=fd0297e4e0) | Sep 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [678bbd1366](https://linux-hardware.org/?probe=678bbd1366) | Sep 01, 2023 |
| Lenovo        | ThinkPad X301 2774LEG       | [50f297712d](https://linux-hardware.org/?probe=50f297712d) | Sep 01, 2023 |
| Dell          | Inspiron 13-5368            | [e811db37c5](https://linux-hardware.org/?probe=e811db37c5) | Sep 01, 2023 |
| Lenovo        | ThinkPad S5-S540 20B3006... | [e33b222d6c](https://linux-hardware.org/?probe=e33b222d6c) | Sep 01, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | [b900fd0bc7](https://linux-hardware.org/?probe=b900fd0bc7) | Aug 31, 2023 |
| HP            | ProBook 4530s               | [09fddaab4d](https://linux-hardware.org/?probe=09fddaab4d) | Aug 31, 2023 |
| Dell          | Latitude 7390               | [a9c1ad1756](https://linux-hardware.org/?probe=a9c1ad1756) | Aug 31, 2023 |
| HP            | ProBook 645 G1              | [ca7a99ecd9](https://linux-hardware.org/?probe=ca7a99ecd9) | Aug 31, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [76f095d7c2](https://linux-hardware.org/?probe=76f095d7c2) | Aug 31, 2023 |
| Dell          | Inspiron 7520               | [f3e3f12f08](https://linux-hardware.org/?probe=f3e3f12f08) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [3977e85dce](https://linux-hardware.org/?probe=3977e85dce) | Aug 30, 2023 |
| Dell          | Latitude 5430               | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470p 20J60014P... | [7690eb9089](https://linux-hardware.org/?probe=7690eb9089) | Aug 30, 2023 |
| Lenovo        | G50-80 80E5                 | [5ba6fd6ca3](https://linux-hardware.org/?probe=5ba6fd6ca3) | Aug 30, 2023 |
| Dell          | Latitude E6520              | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| Dell          | Latitude D630               | [d23ff7e118](https://linux-hardware.org/?probe=d23ff7e118) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | [8741a9bb96](https://linux-hardware.org/?probe=8741a9bb96) | Aug 29, 2023 |
| Lenovo        | G570 20079                  | [7efcdba9ef](https://linux-hardware.org/?probe=7efcdba9ef) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Acer          | Acadia V1.45                | [4bc36b4d27](https://linux-hardware.org/?probe=4bc36b4d27) | Aug 29, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [9071631c6d](https://linux-hardware.org/?probe=9071631c6d) | Aug 28, 2023 |
| mPTech        | ARC 11.6 128GB HD           | [4167149587](https://linux-hardware.org/?probe=4167149587) | Aug 26, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [3ee57cbdbe](https://linux-hardware.org/?probe=3ee57cbdbe) | Aug 26, 2023 |
| Lenovo        | ThinkPad E520 1143CWG       | [66d9a31686](https://linux-hardware.org/?probe=66d9a31686) | Aug 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [01ae0852df](https://linux-hardware.org/?probe=01ae0852df) | Aug 25, 2023 |
| Dell          | Latitude E6400              | [4526151015](https://linux-hardware.org/?probe=4526151015) | Aug 25, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [bb854d7896](https://linux-hardware.org/?probe=bb854d7896) | Aug 25, 2023 |
| Dell          | XPS 9320                    | [1ba8e13634](https://linux-hardware.org/?probe=1ba8e13634) | Aug 24, 2023 |
| Dell          | XPS 13 9310                 | [e6c72eb614](https://linux-hardware.org/?probe=e6c72eb614) | Aug 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [12ac0bf5ed](https://linux-hardware.org/?probe=12ac0bf5ed) | Aug 24, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [097bbaf86a](https://linux-hardware.org/?probe=097bbaf86a) | Aug 24, 2023 |
| Dell          | Latitude 3520               | [92ef936c86](https://linux-hardware.org/?probe=92ef936c86) | Aug 24, 2023 |
| Kiano         | Elegance 14.2               | [71ba491330](https://linux-hardware.org/?probe=71ba491330) | Aug 24, 2023 |
| Dell          | XPS 15 9520                 | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| HP            | Compaq nc8430 (EM741AV)     | [02d656a746](https://linux-hardware.org/?probe=02d656a746) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| Dell          | Latitude 3190               | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c080c15699](https://linux-hardware.org/?probe=c080c15699) | Aug 22, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f5751cb101](https://linux-hardware.org/?probe=f5751cb101) | Aug 19, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [800ad97443](https://linux-hardware.org/?probe=800ad97443) | Aug 19, 2023 |
| Lenovo        | ThinkPad L480 20LTS6S904    | [32ded049ec](https://linux-hardware.org/?probe=32ded049ec) | Aug 17, 2023 |
| Valve         | Jupiter                     | [b2c7c5cb9f](https://linux-hardware.org/?probe=b2c7c5cb9f) | Aug 17, 2023 |
| HP            | Laptop 14-df0xxx            | [7d3c3dc329](https://linux-hardware.org/?probe=7d3c3dc329) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
| Samsung       | RF511/RF411/RF711           | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [f3c603341d](https://linux-hardware.org/?probe=f3c603341d) | Aug 16, 2023 |
| Lenovo        | G505s 20255                 | [2486dc323f](https://linux-hardware.org/?probe=2486dc323f) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [ef53482168](https://linux-hardware.org/?probe=ef53482168) | Aug 16, 2023 |
| Lenovo        | ThinkPad T470 20HES07J00    | [32ec341753](https://linux-hardware.org/?probe=32ec341753) | Aug 16, 2023 |
| Gigabyte      | RC14UD                      | [51b04bf027](https://linux-hardware.org/?probe=51b04bf027) | Aug 16, 2023 |
| Samsung       | 530U4E/540U4E               | [7189151ffc](https://linux-hardware.org/?probe=7189151ffc) | Aug 15, 2023 |
| Dell          | XPS 15 9570                 | [ce22773504](https://linux-hardware.org/?probe=ce22773504) | Aug 15, 2023 |
| Lenovo        | G580                        | [ceeee3c405](https://linux-hardware.org/?probe=ceeee3c405) | Aug 15, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [076c807d2d](https://linux-hardware.org/?probe=076c807d2d) | Aug 14, 2023 |
| Samsung       | 530U4E/540U4E               | [6a886e53b9](https://linux-hardware.org/?probe=6a886e53b9) | Aug 14, 2023 |
| HP            | Pavilion dv7                | [8af14f1aaa](https://linux-hardware.org/?probe=8af14f1aaa) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [1d77ac2450](https://linux-hardware.org/?probe=1d77ac2450) | Aug 13, 2023 |
| Acer          | Predator G5-793             | [bb25759563](https://linux-hardware.org/?probe=bb25759563) | Aug 13, 2023 |
| HP            | EliteBook 845 G9            | [cf6dfa50ef](https://linux-hardware.org/?probe=cf6dfa50ef) | Aug 12, 2023 |
| Valve         | Jupiter                     | [b770999baf](https://linux-hardware.org/?probe=b770999baf) | Aug 12, 2023 |
| Lenovo        | G580 20150                  | [b296a33ab3](https://linux-hardware.org/?probe=b296a33ab3) | Aug 12, 2023 |
| Apple         | MacBookPro13,3              | [b43e2738d9](https://linux-hardware.org/?probe=b43e2738d9) | Aug 12, 2023 |
| ASUSTek       | GL552VW                     | [6986ca63da](https://linux-hardware.org/?probe=6986ca63da) | Aug 12, 2023 |
| Fujitsu       | FMVA0800C                   | [1dae7b170b](https://linux-hardware.org/?probe=1dae7b170b) | Aug 12, 2023 |
| HP            | Pavilion dv7                | [7e4a63e58c](https://linux-hardware.org/?probe=7e4a63e58c) | Aug 12, 2023 |
| HP            | Pavilion dv7                | [fc48a936d7](https://linux-hardware.org/?probe=fc48a936d7) | Aug 12, 2023 |
| Lenovo        | ThinkPad T430s 2356LPG      | [97dfe9511b](https://linux-hardware.org/?probe=97dfe9511b) | Aug 10, 2023 |
| Google        | Kip                         | [553df8dcdc](https://linux-hardware.org/?probe=553df8dcdc) | Aug 10, 2023 |
| Dell          | Latitude E6540              | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | EliteBook 845 G9            | [1ff8d81e4e](https://linux-hardware.org/?probe=1ff8d81e4e) | Aug 09, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Acer          | Aspire 5732Z                | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [f6b63d9967](https://linux-hardware.org/?probe=f6b63d9967) | Aug 08, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [9094c29548](https://linux-hardware.org/?probe=9094c29548) | Aug 07, 2023 |
| HP            | ZBook 15 G3                 | [068b8c5a6f](https://linux-hardware.org/?probe=068b8c5a6f) | Aug 07, 2023 |
| Dell          | Vostro 5471                 | [f4beee823e](https://linux-hardware.org/?probe=f4beee823e) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [270c9a3ea0](https://linux-hardware.org/?probe=270c9a3ea0) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [db5a797fc0](https://linux-hardware.org/?probe=db5a797fc0) | Aug 06, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude 5421               | [d01013b679](https://linux-hardware.org/?probe=d01013b679) | Aug 05, 2023 |
| Dell          | Latitude 5421               | [5dfde4e6ac](https://linux-hardware.org/?probe=5dfde4e6ac) | Aug 05, 2023 |
| Gigabyte      | RC14UD                      | [6ad0758102](https://linux-hardware.org/?probe=6ad0758102) | Aug 04, 2023 |
| Lenovo        | G50-45 80E3                 | [34edcb7dae](https://linux-hardware.org/?probe=34edcb7dae) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | [bd994e4cc6](https://linux-hardware.org/?probe=bd994e4cc6) | Aug 04, 2023 |
| Dell          | Vostro 15 3510              | [ab2f3b8c7b](https://linux-hardware.org/?probe=ab2f3b8c7b) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [8036065591](https://linux-hardware.org/?probe=8036065591) | Aug 03, 2023 |
| Dell          | Inspiron 13-5368            | [695e2dec6b](https://linux-hardware.org/?probe=695e2dec6b) | Aug 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c2c27c3268](https://linux-hardware.org/?probe=c2c27c3268) | Aug 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [762d07665a](https://linux-hardware.org/?probe=762d07665a) | Jul 31, 2023 |
| ASUSTek       | E200HA                      | [6ab93e7940](https://linux-hardware.org/?probe=6ab93e7940) | Jul 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [60cfcb00e9](https://linux-hardware.org/?probe=60cfcb00e9) | Jul 30, 2023 |
| Google        | Relm                        | [1c8bd1f9dd](https://linux-hardware.org/?probe=1c8bd1f9dd) | Jul 30, 2023 |
| Lenovo        | ThinkPad A285 20MXS0AE00    | [a6ada51a02](https://linux-hardware.org/?probe=a6ada51a02) | Jul 29, 2023 |
| Dell          | Latitude E7240              | [b794bcdde6](https://linux-hardware.org/?probe=b794bcdde6) | Jul 29, 2023 |
| Dell          | Inspiron 7559               | [fad00d6412](https://linux-hardware.org/?probe=fad00d6412) | Jul 29, 2023 |
| ASUSTek       | X555LJ                      | [690e49362b](https://linux-hardware.org/?probe=690e49362b) | Jul 28, 2023 |
| HP            | Pavilion Gaming Laptop      | [b277fcda26](https://linux-hardware.org/?probe=b277fcda26) | Jul 28, 2023 |
| Toshiba       | Satellite C50D-A-11G        | [b67508b754](https://linux-hardware.org/?probe=b67508b754) | Jul 27, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [e882db39b8](https://linux-hardware.org/?probe=e882db39b8) | Jul 27, 2023 |
| Dell          | Inspiron 3583               | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Latitude 9420               | [03c3ca79c4](https://linux-hardware.org/?probe=03c3ca79c4) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| Apple         | MacBookPro9,2               | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [346055ca33](https://linux-hardware.org/?probe=346055ca33) | Jul 25, 2023 |
| Dell          | Latitude 3190               | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [412bc51f72](https://linux-hardware.org/?probe=412bc51f72) | Jul 24, 2023 |
| Timi          | TM1701                      | [eb1246586e](https://linux-hardware.org/?probe=eb1246586e) | Jul 24, 2023 |
| ASUSTek       | F7E                         | [2aef1cc2c4](https://linux-hardware.org/?probe=2aef1cc2c4) | Jul 24, 2023 |
| Timi          | TM1701                      | [17fefbecba](https://linux-hardware.org/?probe=17fefbecba) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A715-74G             | [b27862dc34](https://linux-hardware.org/?probe=b27862dc34) | Jul 24, 2023 |
| ASUSTek       | X555LD                      | [732fe69d59](https://linux-hardware.org/?probe=732fe69d59) | Jul 23, 2023 |
| HUAWEI        | HVY-WXX9                    | [44958ef86b](https://linux-hardware.org/?probe=44958ef86b) | Jul 23, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [10e8c0d4ad](https://linux-hardware.org/?probe=10e8c0d4ad) | Jul 23, 2023 |
| Google        | Snappy                      | [a3e6774e43](https://linux-hardware.org/?probe=a3e6774e43) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [467cc30f89](https://linux-hardware.org/?probe=467cc30f89) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| Razer         | Blade 15 Base Model (Mid... | [d2d53e7406](https://linux-hardware.org/?probe=d2d53e7406) | Jul 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [fcdb1fdeed](https://linux-hardware.org/?probe=fcdb1fdeed) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [0bd52b9adf](https://linux-hardware.org/?probe=0bd52b9adf) | Jul 20, 2023 |
| Dell          | Latitude 9420               | [750f80b869](https://linux-hardware.org/?probe=750f80b869) | Jul 19, 2023 |
| Dell          | Latitude 9420               | [a4ba4bfde1](https://linux-hardware.org/?probe=a4ba4bfde1) | Jul 19, 2023 |
| Dell          | Latitude E6400              | [7e9ef12f0d](https://linux-hardware.org/?probe=7e9ef12f0d) | Jul 19, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [17c6866da9](https://linux-hardware.org/?probe=17c6866da9) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [35d510901b](https://linux-hardware.org/?probe=35d510901b) | Jul 18, 2023 |
| Teclast       | F6 Pro                      | [d9f3a038e0](https://linux-hardware.org/?probe=d9f3a038e0) | Jul 17, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [18f41b2be6](https://linux-hardware.org/?probe=18f41b2be6) | Jul 17, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | [0c460a8007](https://linux-hardware.org/?probe=0c460a8007) | Jul 17, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [111c0b962d](https://linux-hardware.org/?probe=111c0b962d) | Jul 16, 2023 |
| Dell          | Latitude E6440              | [4e40dc49f3](https://linux-hardware.org/?probe=4e40dc49f3) | Jul 16, 2023 |
| HP            | Pavilion HDX9200            | [d893c8a2d1](https://linux-hardware.org/?probe=d893c8a2d1) | Jul 16, 2023 |
| Dell          | Latitude E6330              | [6adb67344f](https://linux-hardware.org/?probe=6adb67344f) | Jul 15, 2023 |
| Lenovo        | ThinkPad T495 20NKS0T101    | [6154504eac](https://linux-hardware.org/?probe=6154504eac) | Jul 15, 2023 |
| ASUSTek       | 1011PX                      | [d91fe40195](https://linux-hardware.org/?probe=d91fe40195) | Jul 15, 2023 |
| MSI           | GE70 2QD                    | [f8ddf3a3a3](https://linux-hardware.org/?probe=f8ddf3a3a3) | Jul 15, 2023 |
| Lenovo        | ThinkPad X240 20AMS07T00    | [8ce6db48b9](https://linux-hardware.org/?probe=8ce6db48b9) | Jul 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [f416cb06c2](https://linux-hardware.org/?probe=f416cb06c2) | Jul 14, 2023 |
| Acer          | Aspire E5-576G              | [0856b48ae7](https://linux-hardware.org/?probe=0856b48ae7) | Jul 13, 2023 |
| Dell          | Latitude E6330              | [58ec0684cd](https://linux-hardware.org/?probe=58ec0684cd) | Jul 13, 2023 |
| Toshiba       | Satellite S75-B             | [ee71e28c8f](https://linux-hardware.org/?probe=ee71e28c8f) | Jul 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS01A0... | [54e51170a1](https://linux-hardware.org/?probe=54e51170a1) | Jul 11, 2023 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a78428eb21](https://linux-hardware.org/?probe=a78428eb21) | Jul 11, 2023 |
| Dell          | Inspiron 5748               | [ec95cc29fd](https://linux-hardware.org/?probe=ec95cc29fd) | Jul 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [ef1f607a84](https://linux-hardware.org/?probe=ef1f607a84) | Jul 11, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [97f39991c3](https://linux-hardware.org/?probe=97f39991c3) | Jul 11, 2023 |
| Dell          | Latitude 3190               | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [8b9677cc2a](https://linux-hardware.org/?probe=8b9677cc2a) | Jul 10, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [acdd4ea952](https://linux-hardware.org/?probe=acdd4ea952) | Jul 10, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [d4ca6c4f81](https://linux-hardware.org/?probe=d4ca6c4f81) | Jul 10, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [215d2135b3](https://linux-hardware.org/?probe=215d2135b3) | Jul 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [42aaaa0acb](https://linux-hardware.org/?probe=42aaaa0acb) | Jul 09, 2023 |
| HP            | Compaq Presario CQ60        | [60e671ef49](https://linux-hardware.org/?probe=60e671ef49) | Jul 09, 2023 |
| ASUSTek       | X555LJ                      | [2dfec77944](https://linux-hardware.org/?probe=2dfec77944) | Jul 09, 2023 |
| HP            | Laptop 14s-fq0xxx           | [92feea0533](https://linux-hardware.org/?probe=92feea0533) | Jul 08, 2023 |
| HP            | Laptop 14s-fq0xxx           | [2287c62944](https://linux-hardware.org/?probe=2287c62944) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9b8e16f852](https://linux-hardware.org/?probe=9b8e16f852) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | [6a67dec7ab](https://linux-hardware.org/?probe=6a67dec7ab) | Jul 08, 2023 |
| Toshiba       | PORTEGE M700                | [b735ddd9a6](https://linux-hardware.org/?probe=b735ddd9a6) | Jul 08, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [54ac55c49e](https://linux-hardware.org/?probe=54ac55c49e) | Jul 07, 2023 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [296474a1b1](https://linux-hardware.org/?probe=296474a1b1) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [e4bb31a52c](https://linux-hardware.org/?probe=e4bb31a52c) | Jul 07, 2023 |
| HP            | 255 G7 Notebook PC          | [23a6105e01](https://linux-hardware.org/?probe=23a6105e01) | Jul 06, 2023 |
| Dell          | Latitude 7420               | [44c51e8365](https://linux-hardware.org/?probe=44c51e8365) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | [53f8e37edc](https://linux-hardware.org/?probe=53f8e37edc) | Jul 05, 2023 |
| AAEON         | AEC-6637                    | [a105861e1d](https://linux-hardware.org/?probe=a105861e1d) | Jul 05, 2023 |
| Dell          | Latitude 7420               | [9eae2c6ad4](https://linux-hardware.org/?probe=9eae2c6ad4) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3e5dc0c313](https://linux-hardware.org/?probe=3e5dc0c313) | Jul 05, 2023 |
| HP            | 550                         | [f788d05211](https://linux-hardware.org/?probe=f788d05211) | Jul 05, 2023 |
| HP            | 650                         | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | [1a32b23618](https://linux-hardware.org/?probe=1a32b23618) | Jul 04, 2023 |
| Dell          | Latitude 3190               | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [f567c6c550](https://linux-hardware.org/?probe=f567c6c550) | Jul 03, 2023 |
| Google        | Relm                        | [ef72648bb6](https://linux-hardware.org/?probe=ef72648bb6) | Jul 02, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [f923d36676](https://linux-hardware.org/?probe=f923d36676) | Jul 01, 2023 |
| Dell          | Inspiron 7720               | [9d8f40247e](https://linux-hardware.org/?probe=9d8f40247e) | Jul 01, 2023 |
| Packard Be... | EasyNote TSX66HR            | [96253a3da8](https://linux-hardware.org/?probe=96253a3da8) | Jul 01, 2023 |
| HP            | EliteBook 820 G2            | [c99236ef84](https://linux-hardware.org/?probe=c99236ef84) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430s 23554L7      | [501b0860c8](https://linux-hardware.org/?probe=501b0860c8) | Jun 30, 2023 |
| Dell          | Latitude E6540              | [a526c901ee](https://linux-hardware.org/?probe=a526c901ee) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [723de914e2](https://linux-hardware.org/?probe=723de914e2) | Jun 29, 2023 |
| Acer          | Swift SF314-43              | [363067c171](https://linux-hardware.org/?probe=363067c171) | Jun 29, 2023 |
| Dell          | XPS 15 9570                 | [34df27504f](https://linux-hardware.org/?probe=34df27504f) | Jun 28, 2023 |
| Apple         | MacBookPro7,1               | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| Toshiba       | TECRA R950                  | [cab34ec3dc](https://linux-hardware.org/?probe=cab34ec3dc) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| ASUSTek       | K54C                        | [4152d1fcff](https://linux-hardware.org/?probe=4152d1fcff) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| Lenovo        | G500s 20245                 | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| Valve         | Jupiter                     | [0817dd25ff](https://linux-hardware.org/?probe=0817dd25ff) | Jun 27, 2023 |
| Dell          | Latitude 3190               | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| Toshiba       | TECRA R950                  | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| HP            | 255 G5 Notebook PC          | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| eMachines     | eME732ZG                    | [4e1d6873ff](https://linux-hardware.org/?probe=4e1d6873ff) | Jun 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [0ec7fedf29](https://linux-hardware.org/?probe=0ec7fedf29) | Jun 24, 2023 |
| Packard Be... | EasyNote TK85               | [314e344780](https://linux-hardware.org/?probe=314e344780) | Jun 24, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [a8a9689ea6](https://linux-hardware.org/?probe=a8a9689ea6) | Jun 24, 2023 |
| Lenovo        | ThinkPad L390 20NSS04400    | [feced26491](https://linux-hardware.org/?probe=feced26491) | Jun 23, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c75670186a](https://linux-hardware.org/?probe=c75670186a) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | [17db397c48](https://linux-hardware.org/?probe=17db397c48) | Jun 22, 2023 |
| Toshiba       | Satellite Pro C70-B         | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [5de086be7a](https://linux-hardware.org/?probe=5de086be7a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| Notebook      | NV4xPZ                      | [873c70b184](https://linux-hardware.org/?probe=873c70b184) | Jun 21, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Toshiba       | Satellite A300              | [f37d67a18d](https://linux-hardware.org/?probe=f37d67a18d) | Jun 19, 2023 |
| Razer         | Blade Stealth 13 (Early ... | [e3843be450](https://linux-hardware.org/?probe=e3843be450) | Jun 18, 2023 |
| HP            | Pavilion dv2                | [3f3b0104a4](https://linux-hardware.org/?probe=3f3b0104a4) | Jun 18, 2023 |
| HP            | Notebook                    | [60eebb0602](https://linux-hardware.org/?probe=60eebb0602) | Jun 18, 2023 |
| Dell          | Latitude 5420               | [f7c9224ef1](https://linux-hardware.org/?probe=f7c9224ef1) | Jun 17, 2023 |
| Dell          | Latitude 5420               | [f553a4e5e7](https://linux-hardware.org/?probe=f553a4e5e7) | Jun 17, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0d47dc3760](https://linux-hardware.org/?probe=0d47dc3760) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | [9536ebc16b](https://linux-hardware.org/?probe=9536ebc16b) | Jun 16, 2023 |
| Dell          | Latitude E6400              | [7c59595887](https://linux-hardware.org/?probe=7c59595887) | Jun 16, 2023 |
| STONE COMP... | NOTCHA-286                  | [00a14ade70](https://linux-hardware.org/?probe=00a14ade70) | Jun 16, 2023 |
| Valve         | Jupiter                     | [29869b2464](https://linux-hardware.org/?probe=29869b2464) | Jun 15, 2023 |
| Valve         | Jupiter                     | [bdd96d41a7](https://linux-hardware.org/?probe=bdd96d41a7) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [a1c36c44b1](https://linux-hardware.org/?probe=a1c36c44b1) | Jun 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [8d88084588](https://linux-hardware.org/?probe=8d88084588) | Jun 15, 2023 |
| Lenovo        | ThinkPad T490 20N20032US    | [3df7663e0d](https://linux-hardware.org/?probe=3df7663e0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| Lenovo        | G500s 20245                 | [8a04ec65f7](https://linux-hardware.org/?probe=8a04ec65f7) | Jun 15, 2023 |
| Acer          | Nitro AN515-44              | [7670492b40](https://linux-hardware.org/?probe=7670492b40) | Jun 15, 2023 |
| Dell          | Latitude 3190               | [2c8d7ef5b6](https://linux-hardware.org/?probe=2c8d7ef5b6) | Jun 12, 2023 |
| MSI           | GE62 6QC                    | [5581a5c589](https://linux-hardware.org/?probe=5581a5c589) | Jun 12, 2023 |
| Google        | Blorb                       | [0083999b8a](https://linux-hardware.org/?probe=0083999b8a) | Jun 12, 2023 |
| Google        | Blorb                       | [516c0548dc](https://linux-hardware.org/?probe=516c0548dc) | Jun 12, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b88dfc7e5c](https://linux-hardware.org/?probe=b88dfc7e5c) | Jun 11, 2023 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [67867c022f](https://linux-hardware.org/?probe=67867c022f) | Jun 11, 2023 |
| Dell          | Precision 5520              | [bcbd324c4b](https://linux-hardware.org/?probe=bcbd324c4b) | Jun 11, 2023 |
| Dell          | Precision 5520              | [ab408edcbd](https://linux-hardware.org/?probe=ab408edcbd) | Jun 11, 2023 |
| HP            | Laptop 15-dw1xxx            | [bfde2cf63d](https://linux-hardware.org/?probe=bfde2cf63d) | Jun 10, 2023 |
| HP            | Laptop 15-dw1xxx            | [7c79725474](https://linux-hardware.org/?probe=7c79725474) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [5e060b53c2](https://linux-hardware.org/?probe=5e060b53c2) | Jun 10, 2023 |
| Lenovo        | Y50-70 20378                | [0d548e314b](https://linux-hardware.org/?probe=0d548e314b) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| Panasonic     | CF-53ASCZGFG                | [39e04925ee](https://linux-hardware.org/?probe=39e04925ee) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| Fujitsu       | CELSIUS H730                | [a1e397f4a7](https://linux-hardware.org/?probe=a1e397f4a7) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c142d83ce5](https://linux-hardware.org/?probe=c142d83ce5) | Jun 07, 2023 |
| Toshiba       | Satellite L40               | [16c5f74991](https://linux-hardware.org/?probe=16c5f74991) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [83982c1aa9](https://linux-hardware.org/?probe=83982c1aa9) | Jun 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [38882f47af](https://linux-hardware.org/?probe=38882f47af) | Jun 05, 2023 |
| Dell          | Latitude 3190               | [fa8eba55f0](https://linux-hardware.org/?probe=fa8eba55f0) | Jun 05, 2023 |
| Acer          | Swift SF314-43              | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [514b3788ed](https://linux-hardware.org/?probe=514b3788ed) | Jun 04, 2023 |
| Dell          | Latitude D620               | [0e1b7f4320](https://linux-hardware.org/?probe=0e1b7f4320) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| Lenovo        | ThinkPad L490 20Q5002DMH    | [6d42b7647b](https://linux-hardware.org/?probe=6d42b7647b) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| Lenovo        | B50-70 20384                | [5e3a2796a9](https://linux-hardware.org/?probe=5e3a2796a9) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | B51-80 80LM                 | [69429cb044](https://linux-hardware.org/?probe=69429cb044) | Jun 01, 2023 |
| HP            | EliteBook 840 G4            | [46ccbd2d62](https://linux-hardware.org/?probe=46ccbd2d62) | May 31, 2023 |
| HP            | EliteBook 840 G4            | [b90cb27f97](https://linux-hardware.org/?probe=b90cb27f97) | May 31, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [7fed965224](https://linux-hardware.org/?probe=7fed965224) | May 30, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| Dell          | Latitude 3190               | [fe4a8422c8](https://linux-hardware.org/?probe=fe4a8422c8) | May 29, 2023 |
| Dell          | Latitude 7480               | [9eb2396796](https://linux-hardware.org/?probe=9eb2396796) | May 28, 2023 |
| Dell          | Vostro 1015                 | [c51af54d34](https://linux-hardware.org/?probe=c51af54d34) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [c8c8087ee8](https://linux-hardware.org/?probe=c8c8087ee8) | May 27, 2023 |
| ASUSTek       | X555LN                      | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | Latitude E5440              | [4a5501c365](https://linux-hardware.org/?probe=4a5501c365) | May 26, 2023 |
| Notebook      | NV4xPZ                      | [750cb90d83](https://linux-hardware.org/?probe=750cb90d83) | May 26, 2023 |
| ASUSTek       | GL552VW                     | [0466edde83](https://linux-hardware.org/?probe=0466edde83) | May 25, 2023 |
| ASUSTek       | X551MA                      | [d72352c0dc](https://linux-hardware.org/?probe=d72352c0dc) | May 25, 2023 |
| HP            | EliteBook 840 G3            | [06333c9c97](https://linux-hardware.org/?probe=06333c9c97) | May 24, 2023 |
| Lenovo        | G500s 20245                 | [dd15a8197e](https://linux-hardware.org/?probe=dd15a8197e) | May 24, 2023 |
| Acer          | Aspire E5-571G              | [6531b22151](https://linux-hardware.org/?probe=6531b22151) | May 24, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ba72bf9d52](https://linux-hardware.org/?probe=ba72bf9d52) | May 24, 2023 |
| Google        | Snappy                      | [8e9ad9e9d3](https://linux-hardware.org/?probe=8e9ad9e9d3) | May 24, 2023 |
| Lenovo        | Unknown                     | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| HP            | 530                         | [70600de142](https://linux-hardware.org/?probe=70600de142) | May 23, 2023 |
| HP            | EliteBook 840 G5            | [74a0ea4304](https://linux-hardware.org/?probe=74a0ea4304) | May 22, 2023 |
| Dell          | Latitude 3190               | [adf9fc9bdb](https://linux-hardware.org/?probe=adf9fc9bdb) | May 22, 2023 |
| ASUSTek       | K84L                        | [5f14f3b293](https://linux-hardware.org/?probe=5f14f3b293) | May 21, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [03b17bc271](https://linux-hardware.org/?probe=03b17bc271) | May 21, 2023 |
| HP            | Unknown                     | [8894bf0f31](https://linux-hardware.org/?probe=8894bf0f31) | May 21, 2023 |
| Valve         | Jupiter                     | [cf5c419d13](https://linux-hardware.org/?probe=cf5c419d13) | May 20, 2023 |
| Lenovo        | G580 20150                  | [87e60904b9](https://linux-hardware.org/?probe=87e60904b9) | May 20, 2023 |
| Lenovo        | G500s 20245                 | [fc125408b5](https://linux-hardware.org/?probe=fc125408b5) | May 20, 2023 |
| Lenovo        | G580 20150                  | [5acf485cbf](https://linux-hardware.org/?probe=5acf485cbf) | May 20, 2023 |
| Apple         | MacBookAir6,2               | [5a0f8e19ee](https://linux-hardware.org/?probe=5a0f8e19ee) | May 19, 2023 |
| Lenovo        | G500s 20245                 | [8c6b9dc52f](https://linux-hardware.org/?probe=8c6b9dc52f) | May 19, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [26e8deafbf](https://linux-hardware.org/?probe=26e8deafbf) | May 19, 2023 |
| MSI           | GL75 9SE                    | [7fd4d531c9](https://linux-hardware.org/?probe=7fd4d531c9) | May 18, 2023 |
| HP            | EliteBook 820 G2            | [200610da74](https://linux-hardware.org/?probe=200610da74) | May 17, 2023 |
| Google        | Snappy                      | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Google        | Snappy                      | [0c095bb37a](https://linux-hardware.org/?probe=0c095bb37a) | May 17, 2023 |
| Dell          | Latitude 3190               | [1d867407a6](https://linux-hardware.org/?probe=1d867407a6) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [3466945196](https://linux-hardware.org/?probe=3466945196) | May 15, 2023 |
| Lenovo        | B590 20206                  | [70b604bc30](https://linux-hardware.org/?probe=70b604bc30) | May 14, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [5f508efff4](https://linux-hardware.org/?probe=5f508efff4) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [1d3db7b456](https://linux-hardware.org/?probe=1d3db7b456) | May 14, 2023 |
| Fujitsu       | CELSIUS H760                | [5e6faf68dd](https://linux-hardware.org/?probe=5e6faf68dd) | May 14, 2023 |
| Lenovo        | B50-70 20384                | [9459f4eae8](https://linux-hardware.org/?probe=9459f4eae8) | May 14, 2023 |
| Fujitsu       | LIFEBOOK S752               | [97e9f91d90](https://linux-hardware.org/?probe=97e9f91d90) | May 14, 2023 |
| ASUSTek       | K53BR                       | [96a60a2970](https://linux-hardware.org/?probe=96a60a2970) | May 14, 2023 |
| Dell          | Latitude E5530 non-vPro     | [aa5dc9770e](https://linux-hardware.org/?probe=aa5dc9770e) | May 13, 2023 |
| Dell          | Latitude E5530 non-vPro     | [51c66f0f57](https://linux-hardware.org/?probe=51c66f0f57) | May 13, 2023 |
| Lenovo        | G50-30 80G0                 | [31d034ce6e](https://linux-hardware.org/?probe=31d034ce6e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [55abeba9a3](https://linux-hardware.org/?probe=55abeba9a3) | May 13, 2023 |
| Fujitsu       | CELSIUS H760                | [7bb1e2b54e](https://linux-hardware.org/?probe=7bb1e2b54e) | May 13, 2023 |
| Toshiba       | Satellite C55-A-1KZ         | [37c165fa30](https://linux-hardware.org/?probe=37c165fa30) | May 13, 2023 |
| Dell          | Precision 3571              | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| GPU Compan... | GWTN156-11                  | [afb2844cb4](https://linux-hardware.org/?probe=afb2844cb4) | May 13, 2023 |
| Samsung       | RF510/RF410/RF710           | [4820c25349](https://linux-hardware.org/?probe=4820c25349) | May 12, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6950584e4c](https://linux-hardware.org/?probe=6950584e4c) | May 12, 2023 |
| HP            | ProBook 4535s               | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| Dell          | Latitude 7390               | [cbd8c5fdbe](https://linux-hardware.org/?probe=cbd8c5fdbe) | May 12, 2023 |
| Dell          | Latitude 7390               | [5677bfdac5](https://linux-hardware.org/?probe=5677bfdac5) | May 12, 2023 |
| Toshiba       | Satellite L40               | [9945f20a3a](https://linux-hardware.org/?probe=9945f20a3a) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ca3ad7158](https://linux-hardware.org/?probe=4ca3ad7158) | May 11, 2023 |
| Valve         | Jupiter                     | [5bfb32e683](https://linux-hardware.org/?probe=5bfb32e683) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Lenovo        | ThinkPad L470 20J5S01S00    | [8886b2b825](https://linux-hardware.org/?probe=8886b2b825) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | Laptop 15s-eq0xxx           | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | [6272f76b0b](https://linux-hardware.org/?probe=6272f76b0b) | May 09, 2023 |
| HP            | EliteBook 840 14 inch G9... | [a3e5adab46](https://linux-hardware.org/?probe=a3e5adab46) | May 08, 2023 |
| Fujitsu Si... | AMILO Pro Series V3525      | [e3cc11d5e4](https://linux-hardware.org/?probe=e3cc11d5e4) | May 08, 2023 |
| Dell          | Latitude 3190               | [fb4df1325b](https://linux-hardware.org/?probe=fb4df1325b) | May 08, 2023 |
| Valve         | Jupiter                     | [e6397e7f9f](https://linux-hardware.org/?probe=e6397e7f9f) | May 08, 2023 |
| HP            | 15                          | [162a4b16ae](https://linux-hardware.org/?probe=162a4b16ae) | May 08, 2023 |
| Dell          | Latitude 5520               | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| Acer          | TravelMate 6592             | [d655aad3c5](https://linux-hardware.org/?probe=d655aad3c5) | May 07, 2023 |
| Dell          | Latitude 5290               | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [3cf83f50f0](https://linux-hardware.org/?probe=3cf83f50f0) | May 07, 2023 |
| Toshiba       | Satellite L300D             | [0e2dfb1c74](https://linux-hardware.org/?probe=0e2dfb1c74) | May 06, 2023 |
| ASUSTek       | K75DE                       | [d99045be1c](https://linux-hardware.org/?probe=d99045be1c) | May 05, 2023 |
| Dell          | Inspiron 5770               | [c545869ec5](https://linux-hardware.org/?probe=c545869ec5) | May 05, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [51ae873492](https://linux-hardware.org/?probe=51ae873492) | May 04, 2023 |
| HP            | EliteBook 8540p             | [11b0a5baa1](https://linux-hardware.org/?probe=11b0a5baa1) | May 04, 2023 |
| Google        | Meep                        | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | Latitude 5490               | [20c5ad2ee2](https://linux-hardware.org/?probe=20c5ad2ee2) | May 03, 2023 |
| Dell          | Latitude E6410              | [8830853258](https://linux-hardware.org/?probe=8830853258) | May 03, 2023 |
| Packard Be... | EasyNote TE69BM             | [fc905a42fb](https://linux-hardware.org/?probe=fc905a42fb) | May 03, 2023 |
| Lenovo        | G500s 20245                 | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Packard Be... | EasyNote LJ65               | [795672236a](https://linux-hardware.org/?probe=795672236a) | May 02, 2023 |
| Packard Be... | EasyNote LJ65               | [77860cab79](https://linux-hardware.org/?probe=77860cab79) | May 02, 2023 |
| Dell          | Vostro 3550                 | [a644bc676e](https://linux-hardware.org/?probe=a644bc676e) | May 01, 2023 |
| HP            | Compaq 6910p                | [a697e756f5](https://linux-hardware.org/?probe=a697e756f5) | May 01, 2023 |
| Dell          | Latitude 3190               | [59c654b2ec](https://linux-hardware.org/?probe=59c654b2ec) | May 01, 2023 |
| Dell          | XPS 15 9500                 | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| Dell          | Latitude XT2                | [3cfd979c60](https://linux-hardware.org/?probe=3cfd979c60) | Apr 30, 2023 |
| Acer          | AO725                       | [03e5f661fb](https://linux-hardware.org/?probe=03e5f661fb) | Apr 30, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [408aa18a63](https://linux-hardware.org/?probe=408aa18a63) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Dell          | Inspiron MXC061             | [2d1ab773dd](https://linux-hardware.org/?probe=2d1ab773dd) | Apr 30, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [7c378d88a2](https://linux-hardware.org/?probe=7c378d88a2) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f502c40867](https://linux-hardware.org/?probe=f502c40867) | Apr 29, 2023 |
| Acer          | Aspire V5-552G              | [07c58a5169](https://linux-hardware.org/?probe=07c58a5169) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| Acer          | Aspire VX5-591G             | [2461a8058f](https://linux-hardware.org/?probe=2461a8058f) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2474e8e580](https://linux-hardware.org/?probe=2474e8e580) | Apr 27, 2023 |
| HP            | 255 G8 Notebook PC          | [adb8f367ea](https://linux-hardware.org/?probe=adb8f367ea) | Apr 27, 2023 |
| HP            | EliteBook 2560p             | [23b5cbfb33](https://linux-hardware.org/?probe=23b5cbfb33) | Apr 27, 2023 |
| Acer          | Aspire 7250                 | [8e8e082e3d](https://linux-hardware.org/?probe=8e8e082e3d) | Apr 26, 2023 |
| Acer          | Aspire 5737Z                | [121eda50b8](https://linux-hardware.org/?probe=121eda50b8) | Apr 26, 2023 |
| HP            | EliteBook 840 G2            | [a3065a1b59](https://linux-hardware.org/?probe=a3065a1b59) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d8088982c3](https://linux-hardware.org/?probe=d8088982c3) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4cffa55fb1](https://linux-hardware.org/?probe=4cffa55fb1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [e6380a2186](https://linux-hardware.org/?probe=e6380a2186) | Apr 26, 2023 |
| HP            | Laptop 15                   | [34a2ebf6a1](https://linux-hardware.org/?probe=34a2ebf6a1) | Apr 26, 2023 |
| HP            | Laptop 15-db1xxx            | [872138980a](https://linux-hardware.org/?probe=872138980a) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2122bd37a5](https://linux-hardware.org/?probe=2122bd37a5) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [af7b14d259](https://linux-hardware.org/?probe=af7b14d259) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7fbd802154](https://linux-hardware.org/?probe=7fbd802154) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ffe6065419](https://linux-hardware.org/?probe=ffe6065419) | Apr 26, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [94ddc76aae](https://linux-hardware.org/?probe=94ddc76aae) | Apr 26, 2023 |
| Lenovo        | ThinkPad X200 7459KM3       | [cbea785e27](https://linux-hardware.org/?probe=cbea785e27) | Apr 25, 2023 |
| Dell          | Latitude E5470              | [3eb401d939](https://linux-hardware.org/?probe=3eb401d939) | Apr 25, 2023 |
| Dell          | Latitude E5470              | [37fabb89aa](https://linux-hardware.org/?probe=37fabb89aa) | Apr 25, 2023 |
| Lenovo        | G700                        | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [9649423c20](https://linux-hardware.org/?probe=9649423c20) | Apr 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [af486ae4ae](https://linux-hardware.org/?probe=af486ae4ae) | Apr 24, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [de3ad583ab](https://linux-hardware.org/?probe=de3ad583ab) | Apr 24, 2023 |
| Medion        | X681X                       | [d72837ad07](https://linux-hardware.org/?probe=d72837ad07) | Apr 24, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [78686e5784](https://linux-hardware.org/?probe=78686e5784) | Apr 24, 2023 |
| Dell          | Vostro 5402                 | [b6cb9c9140](https://linux-hardware.org/?probe=b6cb9c9140) | Apr 24, 2023 |
| Dell          | Latitude 3190               | [2c21a51932](https://linux-hardware.org/?probe=2c21a51932) | Apr 24, 2023 |
| Samsung       | R510/P510                   | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| Dell          | Inspiron 5559               | [e959cc70fa](https://linux-hardware.org/?probe=e959cc70fa) | Apr 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [bee909cfcd](https://linux-hardware.org/?probe=bee909cfcd) | Apr 23, 2023 |
| Dell          | Venue 11 Pro 7130 vPro      | [c101faa12e](https://linux-hardware.org/?probe=c101faa12e) | Apr 23, 2023 |
| Lenovo        | Z51-70 80K6                 | [3d51a6183c](https://linux-hardware.org/?probe=3d51a6183c) | Apr 23, 2023 |
| Dell          | Precision 7550              | [31830a82c6](https://linux-hardware.org/?probe=31830a82c6) | Apr 22, 2023 |
| Dell          | Latitude D620               | [7b0c5ec6f2](https://linux-hardware.org/?probe=7b0c5ec6f2) | Apr 22, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [510237facd](https://linux-hardware.org/?probe=510237facd) | Apr 22, 2023 |
| Gigabyte      | AORUS 15P XD                | [22925aa0c9](https://linux-hardware.org/?probe=22925aa0c9) | Apr 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c1139db413](https://linux-hardware.org/?probe=c1139db413) | Apr 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [3056a65306](https://linux-hardware.org/?probe=3056a65306) | Apr 22, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [87d3a8b29f](https://linux-hardware.org/?probe=87d3a8b29f) | Apr 20, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b7f138b04c](https://linux-hardware.org/?probe=b7f138b04c) | Apr 20, 2023 |
| Dell          | Precision M6600             | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| ASUSTek       | K50IJ                       | [3b07dc847f](https://linux-hardware.org/?probe=3b07dc847f) | Apr 20, 2023 |
| MSI           | Creator Z17 A12UHST         | [1396746fba](https://linux-hardware.org/?probe=1396746fba) | Apr 20, 2023 |
| HP            | 255 G7 Notebook PC          | [b2f977f4a1](https://linux-hardware.org/?probe=b2f977f4a1) | Apr 19, 2023 |
| Acer          | Aspire A715-71G             | [83b48fff59](https://linux-hardware.org/?probe=83b48fff59) | Apr 19, 2023 |
| Dell          | Latitude 7410               | [36e2aea9ea](https://linux-hardware.org/?probe=36e2aea9ea) | Apr 19, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [09a37b3301](https://linux-hardware.org/?probe=09a37b3301) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Dell          | Precision M6800             | [b39d3f31df](https://linux-hardware.org/?probe=b39d3f31df) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [a0b6c23c0b](https://linux-hardware.org/?probe=a0b6c23c0b) | Apr 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [35ec02005f](https://linux-hardware.org/?probe=35ec02005f) | Apr 17, 2023 |
| Acer          | Swift SFA16-41              | [1232f86e3e](https://linux-hardware.org/?probe=1232f86e3e) | Apr 17, 2023 |
| Dell          | Latitude D830               | [3da091adc2](https://linux-hardware.org/?probe=3da091adc2) | Apr 17, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [7ca92cfada](https://linux-hardware.org/?probe=7ca92cfada) | Apr 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8SF1X0... | [d567c29052](https://linux-hardware.org/?probe=d567c29052) | Apr 17, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [c59c5c0cdf](https://linux-hardware.org/?probe=c59c5c0cdf) | Apr 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [391b43ba8c](https://linux-hardware.org/?probe=391b43ba8c) | Apr 16, 2023 |
| Dell          | Inspiron 5559               | [b74080b280](https://linux-hardware.org/?probe=b74080b280) | Apr 16, 2023 |
| Dell          | Latitude E6330              | [1a75476b96](https://linux-hardware.org/?probe=1a75476b96) | Apr 16, 2023 |
| Acer          | AO722                       | [af4e100c16](https://linux-hardware.org/?probe=af4e100c16) | Apr 15, 2023 |
| Kiano         | Elegance 14.2               | [34062f30df](https://linux-hardware.org/?probe=34062f30df) | Apr 15, 2023 |
| Acer          | Aspire 5336                 | [7613566248](https://linux-hardware.org/?probe=7613566248) | Apr 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9206720811](https://linux-hardware.org/?probe=9206720811) | Apr 14, 2023 |
| Valve         | Jupiter                     | [c1558fbc72](https://linux-hardware.org/?probe=c1558fbc72) | Apr 14, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [9cb53e6d6f](https://linux-hardware.org/?probe=9cb53e6d6f) | Apr 13, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [9341670151](https://linux-hardware.org/?probe=9341670151) | Apr 13, 2023 |
| Lenovo        | ThinkPad X220 4291AY8       | [b2bc70473d](https://linux-hardware.org/?probe=b2bc70473d) | Apr 13, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [be2d8594c3](https://linux-hardware.org/?probe=be2d8594c3) | Apr 13, 2023 |
| Dell          | Latitude E6230              | [a7cce7ebde](https://linux-hardware.org/?probe=a7cce7ebde) | Apr 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3460C... | [f1999ee14e](https://linux-hardware.org/?probe=f1999ee14e) | Apr 11, 2023 |
| Dell          | Latitude 7390               | [9361f06955](https://linux-hardware.org/?probe=9361f06955) | Apr 11, 2023 |
| Lenovo        | ThinkPad T480 20L5S12H00    | [c550410c5b](https://linux-hardware.org/?probe=c550410c5b) | Apr 11, 2023 |
| HP            | Pavilion dv7                | [000c77d7d5](https://linux-hardware.org/?probe=000c77d7d5) | Apr 10, 2023 |
| HP            | Pavilion dv7                | [08e5108cda](https://linux-hardware.org/?probe=08e5108cda) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | ThinkPad X220 4291LR6       | [ea86227d59](https://linux-hardware.org/?probe=ea86227d59) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [6b6b2a8633](https://linux-hardware.org/?probe=6b6b2a8633) | Apr 09, 2023 |
| HUAWEI        | HVY-WXX9                    | [00489240d2](https://linux-hardware.org/?probe=00489240d2) | Apr 09, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [869d7607e9](https://linux-hardware.org/?probe=869d7607e9) | Apr 08, 2023 |
| Acer          | Aspire 5336                 | [6e419f3401](https://linux-hardware.org/?probe=6e419f3401) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [370d1404f2](https://linux-hardware.org/?probe=370d1404f2) | Apr 08, 2023 |
| Lenovo        | G50-70 20351                | [b8dd840f5d](https://linux-hardware.org/?probe=b8dd840f5d) | Apr 08, 2023 |
| Samsung       | 400B4C/400B5C/200B4C/200... | [8026ca606e](https://linux-hardware.org/?probe=8026ca606e) | Apr 07, 2023 |
| Dell          | Inspiron 11-3162            | [accdfd2253](https://linux-hardware.org/?probe=accdfd2253) | Apr 07, 2023 |
| Samsung       | 730U3E/740U3E               | [7d4b6838e2](https://linux-hardware.org/?probe=7d4b6838e2) | Apr 07, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [413528fa5a](https://linux-hardware.org/?probe=413528fa5a) | Apr 07, 2023 |
| MSI           | GP76 Leopard 10UE           | [c7b870bb22](https://linux-hardware.org/?probe=c7b870bb22) | Apr 07, 2023 |
| Toshiba       | Satellite C855-12N          | [69e30b2fd8](https://linux-hardware.org/?probe=69e30b2fd8) | Apr 07, 2023 |
| HP            | 620                         | [2e14b2c046](https://linux-hardware.org/?probe=2e14b2c046) | Apr 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | ProBook 4740s               | [14fb51de44](https://linux-hardware.org/?probe=14fb51de44) | Apr 06, 2023 |
| eMachines     | E720 V1.09                  | [278ca903ac](https://linux-hardware.org/?probe=278ca903ac) | Apr 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Samsung       | 730U3E/740U3E               | [2be8e6430c](https://linux-hardware.org/?probe=2be8e6430c) | Apr 05, 2023 |
| Kruger&Mat... | KM1406                      | [1b536904d4](https://linux-hardware.org/?probe=1b536904d4) | Apr 05, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f1398d5ada](https://linux-hardware.org/?probe=f1398d5ada) | Apr 05, 2023 |
| Toshiba       | Satellite C50-A             | [8e02a6dbed](https://linux-hardware.org/?probe=8e02a6dbed) | Apr 05, 2023 |
| Lenovo        | G50-80 80E5                 | [b469666726](https://linux-hardware.org/?probe=b469666726) | Apr 05, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [56119c4c93](https://linux-hardware.org/?probe=56119c4c93) | Apr 05, 2023 |
| Google        | Cyan                        | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [04afa2e378](https://linux-hardware.org/?probe=04afa2e378) | Apr 04, 2023 |
| Lenovo        | B50-80 80LT                 | [163bfb5525](https://linux-hardware.org/?probe=163bfb5525) | Apr 03, 2023 |
| HP            | Compaq CQ58                 | [f0026163c3](https://linux-hardware.org/?probe=f0026163c3) | Apr 03, 2023 |
| HP            | EliteBook 865 16 inch G9... | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [71a388a292](https://linux-hardware.org/?probe=71a388a292) | Apr 03, 2023 |
| HP            | Compaq CQ58                 | [7c4676c380](https://linux-hardware.org/?probe=7c4676c380) | Apr 03, 2023 |
| HP            | Stream Notebook             | [27610e0a39](https://linux-hardware.org/?probe=27610e0a39) | Apr 03, 2023 |
| Dell          | Latitude 3190               | [a1fa664431](https://linux-hardware.org/?probe=a1fa664431) | Apr 03, 2023 |
| ASUSTek       | TP300LJ                     | [7da5aab332](https://linux-hardware.org/?probe=7da5aab332) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| HP            | ProBook 455 G1              | [869f36fc4c](https://linux-hardware.org/?probe=869f36fc4c) | Apr 01, 2023 |
| Lenovo        | G560 20042                  | [c5a4783dfb](https://linux-hardware.org/?probe=c5a4783dfb) | Apr 01, 2023 |
| HP            | Compaq Presario CQ60        | [e5a729243d](https://linux-hardware.org/?probe=e5a729243d) | Mar 31, 2023 |
| Samsung       | 950XED                      | [c3b37a213a](https://linux-hardware.org/?probe=c3b37a213a) | Mar 31, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e2c6f05595](https://linux-hardware.org/?probe=e2c6f05595) | Mar 31, 2023 |
| HUAWEI        | KPL-W0X                     | [6e93ca4159](https://linux-hardware.org/?probe=6e93ca4159) | Mar 31, 2023 |
| Acer          | TravelMate 8172Z            | [10cc090653](https://linux-hardware.org/?probe=10cc090653) | Mar 31, 2023 |
| Dell          | Latitude D620               | [801ede47a2](https://linux-hardware.org/?probe=801ede47a2) | Mar 31, 2023 |
| ASUSTek       | K53SJ                       | [aa9a729217](https://linux-hardware.org/?probe=aa9a729217) | Mar 30, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [6b9737a62f](https://linux-hardware.org/?probe=6b9737a62f) | Mar 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [f78b6ab8c5](https://linux-hardware.org/?probe=f78b6ab8c5) | Mar 30, 2023 |
| Dell          | Latitude E6530              | [eb7392d1ae](https://linux-hardware.org/?probe=eb7392d1ae) | Mar 29, 2023 |
| Lenovo        | G570 20079                  | [680c7a04ed](https://linux-hardware.org/?probe=680c7a04ed) | Mar 29, 2023 |
| GPD           | G1621-02                    | [2ed8b6c147](https://linux-hardware.org/?probe=2ed8b6c147) | Mar 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fa1a582da6](https://linux-hardware.org/?probe=fa1a582da6) | Mar 29, 2023 |
| HP            | 250 G6 Notebook PC          | [94cdfc44d1](https://linux-hardware.org/?probe=94cdfc44d1) | Mar 28, 2023 |
| Kiano         | Elegance 14.2               | [ea2013b347](https://linux-hardware.org/?probe=ea2013b347) | Mar 28, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0QK0... | [7f5fb11940](https://linux-hardware.org/?probe=7f5fb11940) | Mar 28, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [856b789461](https://linux-hardware.org/?probe=856b789461) | Mar 28, 2023 |
| Dell          | Latitude 7490               | [41d01ead49](https://linux-hardware.org/?probe=41d01ead49) | Mar 28, 2023 |
| Dell          | Inspiron 5735               | [823a6ece98](https://linux-hardware.org/?probe=823a6ece98) | Mar 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS47P00    | [e287203572](https://linux-hardware.org/?probe=e287203572) | Mar 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [60012fd503](https://linux-hardware.org/?probe=60012fd503) | Mar 27, 2023 |
| Dell          | XPS 13 7390                 | [aaeb6059a2](https://linux-hardware.org/?probe=aaeb6059a2) | Mar 27, 2023 |
| Dell          | Precision 7670              | [eece926391](https://linux-hardware.org/?probe=eece926391) | Mar 27, 2023 |
| Dell          | Latitude 3190               | [757f1fc2e7](https://linux-hardware.org/?probe=757f1fc2e7) | Mar 27, 2023 |
| Dell          | Precision 7670              | [5b8f0590ec](https://linux-hardware.org/?probe=5b8f0590ec) | Mar 27, 2023 |
| Lenovo        | ThinkPad T520 4243RP3       | [38fa314d2f](https://linux-hardware.org/?probe=38fa314d2f) | Mar 26, 2023 |
| MSI           | Creator Z16 A11UET          | [0133ab37af](https://linux-hardware.org/?probe=0133ab37af) | Mar 26, 2023 |
| Sony          | VGN-BX61VN                  | [76f62cf9c1](https://linux-hardware.org/?probe=76f62cf9c1) | Mar 26, 2023 |
| Lenovo        | G50-80 80E5                 | [250e0a99d1](https://linux-hardware.org/?probe=250e0a99d1) | Mar 26, 2023 |
| Lenovo        | G510 20238                  | [f406bad420](https://linux-hardware.org/?probe=f406bad420) | Mar 26, 2023 |
| Lenovo        | ThinkPad W520 4282PQ7       | [ff42aa158f](https://linux-hardware.org/?probe=ff42aa158f) | Mar 25, 2023 |
| HP            | Notebook                    | [7c4088912e](https://linux-hardware.org/?probe=7c4088912e) | Mar 25, 2023 |
| Lenovo        | ThinkPad T480s 20L7S0YA0... | [f4cb79dbf8](https://linux-hardware.org/?probe=f4cb79dbf8) | Mar 25, 2023 |
| Valve         | Jupiter                     | [6a7628c31d](https://linux-hardware.org/?probe=6a7628c31d) | Mar 25, 2023 |
| HP            | Pavilion dv6                | [29a94d3d9e](https://linux-hardware.org/?probe=29a94d3d9e) | Mar 25, 2023 |
| HP            | Pavilion dv6                | [c3a6c3f669](https://linux-hardware.org/?probe=c3a6c3f669) | Mar 25, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7f32708bde](https://linux-hardware.org/?probe=7f32708bde) | Mar 24, 2023 |
| HP            | Pavilion Notebook           | [446c510c65](https://linux-hardware.org/?probe=446c510c65) | Mar 24, 2023 |
| Toshiba       | Satellite C855-12N          | [cb9692876c](https://linux-hardware.org/?probe=cb9692876c) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [2fe9003124](https://linux-hardware.org/?probe=2fe9003124) | Mar 24, 2023 |
| Toshiba       | Satellite Pro A50-C         | [95c5c45220](https://linux-hardware.org/?probe=95c5c45220) | Mar 24, 2023 |
| MSI           | Creator Z17 A12UHST         | [47814b01b6](https://linux-hardware.org/?probe=47814b01b6) | Mar 24, 2023 |
| Sony          | SVE1512M6ESI                | [db00c70eb7](https://linux-hardware.org/?probe=db00c70eb7) | Mar 24, 2023 |
| Dell          | Latitude E7450              | [c1e43b6a40](https://linux-hardware.org/?probe=c1e43b6a40) | Mar 23, 2023 |
| Lenovo        | G580                        | [367ed9241a](https://linux-hardware.org/?probe=367ed9241a) | Mar 23, 2023 |
| Lenovo        | G580                        | [6ee526d77a](https://linux-hardware.org/?probe=6ee526d77a) | Mar 22, 2023 |
| Acer          | Aspire VN7-791              | [054efde4e8](https://linux-hardware.org/?probe=054efde4e8) | Mar 22, 2023 |
| Lenovo        | G50-80 80E5                 | [f6ad6626ff](https://linux-hardware.org/?probe=f6ad6626ff) | Mar 22, 2023 |
| HUAWEI        | KPL-W0X                     | [0ae6ab3ff6](https://linux-hardware.org/?probe=0ae6ab3ff6) | Mar 21, 2023 |
| Unknown       | Unknown                     | [31ee1d66d8](https://linux-hardware.org/?probe=31ee1d66d8) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [57663c8d60](https://linux-hardware.org/?probe=57663c8d60) | Mar 21, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [f5cbd1977f](https://linux-hardware.org/?probe=f5cbd1977f) | Mar 20, 2023 |
| Dell          | Latitude 3190               | [f4bea67dcc](https://linux-hardware.org/?probe=f4bea67dcc) | Mar 20, 2023 |
| HP            | EliteBook 830 G5            | [ba804b8e21](https://linux-hardware.org/?probe=ba804b8e21) | Mar 20, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [919ccc204b](https://linux-hardware.org/?probe=919ccc204b) | Mar 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c89c2e1369](https://linux-hardware.org/?probe=c89c2e1369) | Mar 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [31299394e0](https://linux-hardware.org/?probe=31299394e0) | Mar 18, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [2a3bb3e212](https://linux-hardware.org/?probe=2a3bb3e212) | Mar 18, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [56fab2cb17](https://linux-hardware.org/?probe=56fab2cb17) | Mar 18, 2023 |
| Lenovo        | G570 20079                  | [2d7a146140](https://linux-hardware.org/?probe=2d7a146140) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| Dell          | Latitude 5420               | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| Toshiba       | QOSMIO X500                 | [2ce878e92e](https://linux-hardware.org/?probe=2ce878e92e) | Mar 17, 2023 |
| Dell          | G5 5590                     | [9686d438e6](https://linux-hardware.org/?probe=9686d438e6) | Mar 17, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [728c9ad9f5](https://linux-hardware.org/?probe=728c9ad9f5) | Mar 17, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [593bd6b3ac](https://linux-hardware.org/?probe=593bd6b3ac) | Mar 17, 2023 |
| Dell          | Latitude E7440              | [8a6e751b61](https://linux-hardware.org/?probe=8a6e751b61) | Mar 16, 2023 |
| HP            | Laptop 15-bs0xx             | [f53eccbbe9](https://linux-hardware.org/?probe=f53eccbbe9) | Mar 16, 2023 |
| Dell          | Latitude 5511               | [7444a8c723](https://linux-hardware.org/?probe=7444a8c723) | Mar 16, 2023 |
| Dell          | Latitude D620               | [1731735e10](https://linux-hardware.org/?probe=1731735e10) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [eb0beb38eb](https://linux-hardware.org/?probe=eb0beb38eb) | Mar 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [c54f2ca880](https://linux-hardware.org/?probe=c54f2ca880) | Mar 16, 2023 |
| Sony          | VPCEH1S1E                   | [9e8a96156c](https://linux-hardware.org/?probe=9e8a96156c) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [59d7fa9a34](https://linux-hardware.org/?probe=59d7fa9a34) | Mar 15, 2023 |
| Dell          | Latitude 7390               | [7cc6b3a278](https://linux-hardware.org/?probe=7cc6b3a278) | Mar 15, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [97fe8661ed](https://linux-hardware.org/?probe=97fe8661ed) | Mar 14, 2023 |
| Kiano         | Elegance 14.2               | [f9ed050c6a](https://linux-hardware.org/?probe=f9ed050c6a) | Mar 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| HP            | ProBook 450 G3              | [d422d0d291](https://linux-hardware.org/?probe=d422d0d291) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | [7b0df25d34](https://linux-hardware.org/?probe=7b0df25d34) | Mar 14, 2023 |
| Lenovo        | ThinkPad X301 2776LEG       | [65fe38f62e](https://linux-hardware.org/?probe=65fe38f62e) | Mar 14, 2023 |
| Toshiba       | Satellite L40               | [bfc73429bb](https://linux-hardware.org/?probe=bfc73429bb) | Mar 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [6c76af84cb](https://linux-hardware.org/?probe=6c76af84cb) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | [b9cfb4b900](https://linux-hardware.org/?probe=b9cfb4b900) | Mar 13, 2023 |
| Acer          | Aspire A315-24P             | [fba21e619d](https://linux-hardware.org/?probe=fba21e619d) | Mar 13, 2023 |
| HP            | Pavilion dv6                | [f649c78020](https://linux-hardware.org/?probe=f649c78020) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [bc375a2ddd](https://linux-hardware.org/?probe=bc375a2ddd) | Mar 13, 2023 |
| Dell          | Latitude 3190               | [97cc3ffc79](https://linux-hardware.org/?probe=97cc3ffc79) | Mar 13, 2023 |
| ASUSTek       | X551MA                      | [37b002e8ec](https://linux-hardware.org/?probe=37b002e8ec) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| ASUSTek       | N550JK                      | [bb5d069d90](https://linux-hardware.org/?probe=bb5d069d90) | Mar 12, 2023 |
| Google        | Electro                     | [86cbc9d907](https://linux-hardware.org/?probe=86cbc9d907) | Mar 12, 2023 |
| HP            | 250 G6 Notebook PC          | [d173735b81](https://linux-hardware.org/?probe=d173735b81) | Mar 11, 2023 |
| Dell          | Precision M6600             | [9d5e2f1e01](https://linux-hardware.org/?probe=9d5e2f1e01) | Mar 11, 2023 |
| Acer          | Extensa 5620                | [f95239bf35](https://linux-hardware.org/?probe=f95239bf35) | Mar 11, 2023 |
| Kiano         | Elegance 14.2               | [5714b30108](https://linux-hardware.org/?probe=5714b30108) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | [44867c946f](https://linux-hardware.org/?probe=44867c946f) | Mar 10, 2023 |
| Dell          | Latitude E6530              | [70b72984bc](https://linux-hardware.org/?probe=70b72984bc) | Mar 10, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [2d99e047c9](https://linux-hardware.org/?probe=2d99e047c9) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| HP            | Laptop 15s-eq0xxx           | [7a7e8bc855](https://linux-hardware.org/?probe=7a7e8bc855) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| Lenovo        | IdeaPad Y580                | [cc2d7d8a95](https://linux-hardware.org/?probe=cc2d7d8a95) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [b00f44cd46](https://linux-hardware.org/?probe=b00f44cd46) | Mar 09, 2023 |
| Dell          | Latitude E6440              | [3b9229e07a](https://linux-hardware.org/?probe=3b9229e07a) | Mar 09, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [c50daaf3b9](https://linux-hardware.org/?probe=c50daaf3b9) | Mar 09, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [fdc32a6871](https://linux-hardware.org/?probe=fdc32a6871) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| HP            | EliteBook 8570w             | [dfd9b7a9b9](https://linux-hardware.org/?probe=dfd9b7a9b9) | Mar 08, 2023 |
| HP            | ENVY 6                      | [4873f7b85f](https://linux-hardware.org/?probe=4873f7b85f) | Mar 08, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [daf29f1a82](https://linux-hardware.org/?probe=daf29f1a82) | Mar 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [233722f0e1](https://linux-hardware.org/?probe=233722f0e1) | Mar 07, 2023 |
| Dell          | Latitude 7290               | [38f12088b2](https://linux-hardware.org/?probe=38f12088b2) | Mar 07, 2023 |
| HUAWEI        | KPL-W0X                     | [76ebbe553f](https://linux-hardware.org/?probe=76ebbe553f) | Mar 06, 2023 |
| Dell          | Latitude 3190               | [a3a4113ab4](https://linux-hardware.org/?probe=a3a4113ab4) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| ASUSTek       | X551MA                      | [b77e06361b](https://linux-hardware.org/?probe=b77e06361b) | Mar 05, 2023 |
| Lenovo        | ThinkPad T440p 20AWS37F0... | [48677f9f86](https://linux-hardware.org/?probe=48677f9f86) | Mar 05, 2023 |
| IGEL Techn... | H830C                       | [3619b3fcee](https://linux-hardware.org/?probe=3619b3fcee) | Mar 05, 2023 |
| ASUSTek       | N71Vg                       | [4d83fda5ba](https://linux-hardware.org/?probe=4d83fda5ba) | Mar 05, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [8b36c984f8](https://linux-hardware.org/?probe=8b36c984f8) | Mar 05, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [65006682e6](https://linux-hardware.org/?probe=65006682e6) | Mar 05, 2023 |
| HP            | 15                          | [0efd9be7ae](https://linux-hardware.org/?probe=0efd9be7ae) | Mar 04, 2023 |
| HP            | 15                          | [b8a33a3d73](https://linux-hardware.org/?probe=b8a33a3d73) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4177R3U       | [525dd38cf1](https://linux-hardware.org/?probe=525dd38cf1) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [bd108fcfba](https://linux-hardware.org/?probe=bd108fcfba) | Mar 04, 2023 |
| HP            | Notebook                    | [229fbff95c](https://linux-hardware.org/?probe=229fbff95c) | Mar 04, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [afe8ef7318](https://linux-hardware.org/?probe=afe8ef7318) | Mar 04, 2023 |
| HP            | EliteBook 830 G5            | [82acbe37f7](https://linux-hardware.org/?probe=82acbe37f7) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [1bfad93a1e](https://linux-hardware.org/?probe=1bfad93a1e) | Mar 04, 2023 |
| Dell          | Vostro 3350                 | [f782f8e288](https://linux-hardware.org/?probe=f782f8e288) | Mar 04, 2023 |
| Apple         | MacBookPro8,2               | [0b0c5a6895](https://linux-hardware.org/?probe=0b0c5a6895) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| IGEL Techn... | H830C                       | [4625dc0660](https://linux-hardware.org/?probe=4625dc0660) | Mar 04, 2023 |
| Toshiba       | Satellite L40               | [e3f1423c39](https://linux-hardware.org/?probe=e3f1423c39) | Mar 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [0228fd4ab1](https://linux-hardware.org/?probe=0228fd4ab1) | Mar 04, 2023 |
| Dell          | Latitude 5480               | [4679c9328e](https://linux-hardware.org/?probe=4679c9328e) | Mar 03, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9186971572](https://linux-hardware.org/?probe=9186971572) | Mar 03, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [25f45efbc1](https://linux-hardware.org/?probe=25f45efbc1) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | [608c8a42da](https://linux-hardware.org/?probe=608c8a42da) | Mar 03, 2023 |
| ASUSTek       | X551MA                      | [fa55d9fb5c](https://linux-hardware.org/?probe=fa55d9fb5c) | Mar 03, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2B50... | [8268a3bbf3](https://linux-hardware.org/?probe=8268a3bbf3) | Mar 03, 2023 |
| ASUSTek       | N61Vn                       | [9528e36d7b](https://linux-hardware.org/?probe=9528e36d7b) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [726752f23a](https://linux-hardware.org/?probe=726752f23a) | Mar 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a5288ab43b](https://linux-hardware.org/?probe=a5288ab43b) | Mar 02, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | [e87ce2454c](https://linux-hardware.org/?probe=e87ce2454c) | Mar 02, 2023 |
| Dell          | Latitude D830               | [83415c82ac](https://linux-hardware.org/?probe=83415c82ac) | Mar 02, 2023 |
| Acer          | Aspire V3-574G              | [e943ab2cde](https://linux-hardware.org/?probe=e943ab2cde) | Mar 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [9b0d952fa9](https://linux-hardware.org/?probe=9b0d952fa9) | Mar 01, 2023 |
| Notebook      | NS50_70MU                   | [18ff6f22a6](https://linux-hardware.org/?probe=18ff6f22a6) | Mar 01, 2023 |
| Dell          | Latitude 5420               | [0596aff5c4](https://linux-hardware.org/?probe=0596aff5c4) | Feb 28, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | [756e003316](https://linux-hardware.org/?probe=756e003316) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | ThinkPad E560 20EV000UUK    | [7060b60651](https://linux-hardware.org/?probe=7060b60651) | Feb 27, 2023 |
| HP            | ProBook 430 G6              | [a184aa7141](https://linux-hardware.org/?probe=a184aa7141) | Feb 27, 2023 |
| Lenovo        | G50-80 80E5                 | [d7bb021829](https://linux-hardware.org/?probe=d7bb021829) | Feb 27, 2023 |
| ASUSTek       | K75VJ                       | [7fc0fff829](https://linux-hardware.org/?probe=7fc0fff829) | Feb 27, 2023 |
| Dell          | Latitude 7390               | [a2167ae72b](https://linux-hardware.org/?probe=a2167ae72b) | Feb 27, 2023 |
| Schenker      | VISION (E22)                | [498444ca02](https://linux-hardware.org/?probe=498444ca02) | Feb 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [1ce9430009](https://linux-hardware.org/?probe=1ce9430009) | Feb 27, 2023 |
| HP            | Notebook                    | [a1180ad479](https://linux-hardware.org/?probe=a1180ad479) | Feb 27, 2023 |
| HP            | Notebook                    | [ee2645efa8](https://linux-hardware.org/?probe=ee2645efa8) | Feb 27, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d57bb59dee](https://linux-hardware.org/?probe=d57bb59dee) | Feb 27, 2023 |
| ASUSTek       | K52F                        | [fa30ea101a](https://linux-hardware.org/?probe=fa30ea101a) | Feb 27, 2023 |
| Dell          | Latitude 3190               | [279b385865](https://linux-hardware.org/?probe=279b385865) | Feb 27, 2023 |
| HP            | Notebook                    | [0d838134b7](https://linux-hardware.org/?probe=0d838134b7) | Feb 27, 2023 |
| Acer          | Aspire ES1-711              | [8e397cc54f](https://linux-hardware.org/?probe=8e397cc54f) | Feb 26, 2023 |
| Gigabyte      | MMLP5AP-00                  | [eb5ca5bb8d](https://linux-hardware.org/?probe=eb5ca5bb8d) | Feb 26, 2023 |
| Valve         | Jupiter                     | [f7289abeb1](https://linux-hardware.org/?probe=f7289abeb1) | Feb 26, 2023 |
| Dell          | Latitude D630               | [cfdc009ff1](https://linux-hardware.org/?probe=cfdc009ff1) | Feb 26, 2023 |
| Acer          | Aspire E5-571G              | [07fe4333eb](https://linux-hardware.org/?probe=07fe4333eb) | Feb 25, 2023 |
| Sony          | VGN-FZ31M                   | [6b830e36f1](https://linux-hardware.org/?probe=6b830e36f1) | Feb 25, 2023 |
| HP            | ZBook 15u G3                | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| HP            | EliteBook 840 G2            | [f1fa3164f9](https://linux-hardware.org/?probe=f1fa3164f9) | Feb 24, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [a85b9d1452](https://linux-hardware.org/?probe=a85b9d1452) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [e2cdf5625c](https://linux-hardware.org/?probe=e2cdf5625c) | Feb 23, 2023 |
| Dell          | XPS 9320                    | [94e7c2d282](https://linux-hardware.org/?probe=94e7c2d282) | Feb 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [bfbb3aab2c](https://linux-hardware.org/?probe=bfbb3aab2c) | Feb 23, 2023 |
| ASUSTek       | 1215B                       | [970d77d150](https://linux-hardware.org/?probe=970d77d150) | Feb 22, 2023 |
| Notebook      | NS50_70MU                   | [a213ec0ba4](https://linux-hardware.org/?probe=a213ec0ba4) | Feb 22, 2023 |
| Apple         | MacBookPro8,1               | [b7071da133](https://linux-hardware.org/?probe=b7071da133) | Feb 22, 2023 |
| Dell          | Latitude 5491               | [fd68ba9595](https://linux-hardware.org/?probe=fd68ba9595) | Feb 21, 2023 |
| Fujitsu       | LIFEBOOK E744               | [bdcee122d3](https://linux-hardware.org/?probe=bdcee122d3) | Feb 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [88be67bbc1](https://linux-hardware.org/?probe=88be67bbc1) | Feb 21, 2023 |
| Lenovo        | ThinkPad R61 8933W4S        | [fec1a43d91](https://linux-hardware.org/?probe=fec1a43d91) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Lenovo        | ThinkPad T410s 2924W3S      | [24081de7f1](https://linux-hardware.org/?probe=24081de7f1) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [e61bce94ea](https://linux-hardware.org/?probe=e61bce94ea) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | [5fc82de1e4](https://linux-hardware.org/?probe=5fc82de1e4) | Feb 20, 2023 |
| Fujitsu       | LIFEBOOK E559               | [5e4c3607c7](https://linux-hardware.org/?probe=5e4c3607c7) | Feb 20, 2023 |
| Dell          | Latitude 3190               | [c05229588b](https://linux-hardware.org/?probe=c05229588b) | Feb 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [0d1a7d0dbe](https://linux-hardware.org/?probe=0d1a7d0dbe) | Feb 20, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [3ddfaa902f](https://linux-hardware.org/?probe=3ddfaa902f) | Feb 20, 2023 |
| Acer          | Aspire A515-44              | [14e85e829f](https://linux-hardware.org/?probe=14e85e829f) | Feb 20, 2023 |
| Dell          | Latitude E7270              | [4eb17c846c](https://linux-hardware.org/?probe=4eb17c846c) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | [7bc24845b3](https://linux-hardware.org/?probe=7bc24845b3) | Feb 20, 2023 |
| Lenovo        | G510 20238                  | [d6f20de9d5](https://linux-hardware.org/?probe=d6f20de9d5) | Feb 19, 2023 |
| Dell          | Vostro 5502                 | [49252b4695](https://linux-hardware.org/?probe=49252b4695) | Feb 19, 2023 |
| HP            | Unknown                     | [69b276cb01](https://linux-hardware.org/?probe=69b276cb01) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5300c136fd](https://linux-hardware.org/?probe=5300c136fd) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [5ff3cab69f](https://linux-hardware.org/?probe=5ff3cab69f) | Feb 19, 2023 |
| Apple         | MacBookAir6,1               | [5cade7cfc3](https://linux-hardware.org/?probe=5cade7cfc3) | Feb 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [238f636180](https://linux-hardware.org/?probe=238f636180) | Feb 18, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9b53b2b842](https://linux-hardware.org/?probe=9b53b2b842) | Feb 18, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [cdfcc639d3](https://linux-hardware.org/?probe=cdfcc639d3) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [cbf0e3814c](https://linux-hardware.org/?probe=cbf0e3814c) | Feb 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a424b3aa47](https://linux-hardware.org/?probe=a424b3aa47) | Feb 18, 2023 |
| Dell          | Latitude 3520               | [8df8f4c6fc](https://linux-hardware.org/?probe=8df8f4c6fc) | Feb 18, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [27958da7cc](https://linux-hardware.org/?probe=27958da7cc) | Feb 18, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [2f3a14eeaa](https://linux-hardware.org/?probe=2f3a14eeaa) | Feb 18, 2023 |
| MSI           | GL65 9SD                    | [a702514760](https://linux-hardware.org/?probe=a702514760) | Feb 17, 2023 |
| Dell          | Inspiron 5570               | [be29883368](https://linux-hardware.org/?probe=be29883368) | Feb 17, 2023 |
| Dell          | Latitude 5491               | [8a3298cdff](https://linux-hardware.org/?probe=8a3298cdff) | Feb 17, 2023 |
| Dell          | Latitude 5511               | [5c3a80271b](https://linux-hardware.org/?probe=5c3a80271b) | Feb 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4a5c7432ae](https://linux-hardware.org/?probe=4a5c7432ae) | Feb 17, 2023 |
| HP            | ZBook Studio G3             | [af86e6cb72](https://linux-hardware.org/?probe=af86e6cb72) | Feb 17, 2023 |
| Lenovo        | ThinkPad T61 7661BM5        | [c829d5ed74](https://linux-hardware.org/?probe=c829d5ed74) | Feb 16, 2023 |
| Apple         | MacBookAir6,1               | [c96e404e3f](https://linux-hardware.org/?probe=c96e404e3f) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| MSI           | Creator Z17 A12UHST         | [a70040c510](https://linux-hardware.org/?probe=a70040c510) | Feb 16, 2023 |
| RTD Embedd... | CMA34CR                     | [dd8527bd65](https://linux-hardware.org/?probe=dd8527bd65) | Feb 16, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [73787e9141](https://linux-hardware.org/?probe=73787e9141) | Feb 16, 2023 |
| Dell          | Latitude 5480               | [ee1b786fd9](https://linux-hardware.org/?probe=ee1b786fd9) | Feb 15, 2023 |
| Lenovo        | Y50-70 20378                | [09301690c5](https://linux-hardware.org/?probe=09301690c5) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [b53cdde5a7](https://linux-hardware.org/?probe=b53cdde5a7) | Feb 15, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [2be1a08ef2](https://linux-hardware.org/?probe=2be1a08ef2) | Feb 15, 2023 |
| GPU Compan... | GWTN141-4                   | [1492f5c475](https://linux-hardware.org/?probe=1492f5c475) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [65a5587c6d](https://linux-hardware.org/?probe=65a5587c6d) | Feb 14, 2023 |
| Acer          | Aspire A315-35              | [971fa91888](https://linux-hardware.org/?probe=971fa91888) | Feb 14, 2023 |
| Google        | Lillipup                    | [af7451beff](https://linux-hardware.org/?probe=af7451beff) | Feb 14, 2023 |
| Unknown       | Unknown                     | [1f80b65b37](https://linux-hardware.org/?probe=1f80b65b37) | Feb 13, 2023 |
| Unknown       | Unknown                     | [8b28eb095c](https://linux-hardware.org/?probe=8b28eb095c) | Feb 13, 2023 |
| Medion        | Akoya THE TOUCH 10          | [ec6afad108](https://linux-hardware.org/?probe=ec6afad108) | Feb 13, 2023 |
| Timi          | TM1613                      | [ce33c5c02e](https://linux-hardware.org/?probe=ce33c5c02e) | Feb 13, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5511               | [161095d97a](https://linux-hardware.org/?probe=161095d97a) | Feb 13, 2023 |
| TrekStor      | Surfbook W2                 | [f43f606f80](https://linux-hardware.org/?probe=f43f606f80) | Feb 13, 2023 |
| Dell          | Latitude 3190               | [f2fd97186c](https://linux-hardware.org/?probe=f2fd97186c) | Feb 13, 2023 |
| Dell          | Latitude E6420              | [6ffa1ea310](https://linux-hardware.org/?probe=6ffa1ea310) | Feb 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [04cfa15383](https://linux-hardware.org/?probe=04cfa15383) | Feb 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1LM0... | [8ee6dd00d1](https://linux-hardware.org/?probe=8ee6dd00d1) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [40116058d1](https://linux-hardware.org/?probe=40116058d1) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [8e00bdf032](https://linux-hardware.org/?probe=8e00bdf032) | Feb 11, 2023 |
| Apple         | MacBookAir5,2               | [4f99163f99](https://linux-hardware.org/?probe=4f99163f99) | Feb 11, 2023 |
| Lenovo        | ThinkPad T430 2347BS4       | [682be07637](https://linux-hardware.org/?probe=682be07637) | Feb 11, 2023 |
| Valve         | Jupiter                     | [081d9e5294](https://linux-hardware.org/?probe=081d9e5294) | Feb 11, 2023 |
| HP            | ProBook 430 G3              | [e995a466a1](https://linux-hardware.org/?probe=e995a466a1) | Feb 10, 2023 |
| Toshiba       | Satellite L750              | [b6239c152e](https://linux-hardware.org/?probe=b6239c152e) | Feb 10, 2023 |
| Acer          | Aspire ES1-111M             | [82eea49fcd](https://linux-hardware.org/?probe=82eea49fcd) | Feb 09, 2023 |
| Acer          | Aspire ES1-111M             | [accbac47d5](https://linux-hardware.org/?probe=accbac47d5) | Feb 09, 2023 |
| Lenovo        | ThinkPad T530 2429MY2       | [9b5ffc7c58](https://linux-hardware.org/?probe=9b5ffc7c58) | Feb 09, 2023 |
| MSI           | Creator Z17 A12UHST         | [8885828bb8](https://linux-hardware.org/?probe=8885828bb8) | Feb 09, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [467c3e9149](https://linux-hardware.org/?probe=467c3e9149) | Feb 09, 2023 |
| Valve         | Jupiter                     | [26cb195bab](https://linux-hardware.org/?probe=26cb195bab) | Feb 08, 2023 |
| Dell          | Latitude 3570               | [dc460632ef](https://linux-hardware.org/?probe=dc460632ef) | Feb 08, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [842956e023](https://linux-hardware.org/?probe=842956e023) | Feb 08, 2023 |
| Dell          | Latitude E6520              | [c9c89084e8](https://linux-hardware.org/?probe=c9c89084e8) | Feb 07, 2023 |
| Dell          | Latitude E4300              | [aaad0477e4](https://linux-hardware.org/?probe=aaad0477e4) | Feb 07, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [307d491fc8](https://linux-hardware.org/?probe=307d491fc8) | Feb 07, 2023 |
| Dell          | Latitude 3520               | [d7569fa081](https://linux-hardware.org/?probe=d7569fa081) | Feb 06, 2023 |
| Valve         | Jupiter                     | [edc8beac1f](https://linux-hardware.org/?probe=edc8beac1f) | Feb 06, 2023 |
| Dell          | Latitude 5511               | [57e8ce4f20](https://linux-hardware.org/?probe=57e8ce4f20) | Feb 06, 2023 |
| Dell          | Latitude 3190               | [eafbc050e8](https://linux-hardware.org/?probe=eafbc050e8) | Feb 06, 2023 |
| HP            | EliteBook 820 G2            | [e8c0f3b7de](https://linux-hardware.org/?probe=e8c0f3b7de) | Feb 05, 2023 |
| HP            | EliteBook 820 G2            | [eb5a23a73b](https://linux-hardware.org/?probe=eb5a23a73b) | Feb 05, 2023 |
| Lenovo        | IdeaPad Y580                | [30d8845f10](https://linux-hardware.org/?probe=30d8845f10) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [dbef2c679a](https://linux-hardware.org/?probe=dbef2c679a) | Feb 05, 2023 |
| Dell          | Inspiron 5570               | [eb399b4ffa](https://linux-hardware.org/?probe=eb399b4ffa) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | [14fb68ece0](https://linux-hardware.org/?probe=14fb68ece0) | Feb 05, 2023 |
| Apple         | MacBookPro8,1               | [d6adca1255](https://linux-hardware.org/?probe=d6adca1255) | Feb 04, 2023 |
| Dell          | Inspiron 5570               | [6e8ab1a5cb](https://linux-hardware.org/?probe=6e8ab1a5cb) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| Dell          | Vostro 3550                 | [4f1125bc93](https://linux-hardware.org/?probe=4f1125bc93) | Feb 04, 2023 |
| Lenovo        | G510 20238                  | [a385ff6f36](https://linux-hardware.org/?probe=a385ff6f36) | Feb 04, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [c6dae92093](https://linux-hardware.org/?probe=c6dae92093) | Feb 03, 2023 |
| ASUSTek       | 1101HA                      | [28cb433eb0](https://linux-hardware.org/?probe=28cb433eb0) | Feb 03, 2023 |
| Dell          | Latitude 5480               | [da9f98059c](https://linux-hardware.org/?probe=da9f98059c) | Feb 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9c5cfbc1a1](https://linux-hardware.org/?probe=9c5cfbc1a1) | Feb 03, 2023 |
| HP            | Unknown                     | [4b28efe30c](https://linux-hardware.org/?probe=4b28efe30c) | Feb 03, 2023 |
| Samsung       | 530U3C/530U4C/532U3C        | [4b1dc3d64b](https://linux-hardware.org/?probe=4b1dc3d64b) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [1c6ed7ede6](https://linux-hardware.org/?probe=1c6ed7ede6) | Feb 02, 2023 |
| Dell          | Vostro 3580                 | [7efc294bac](https://linux-hardware.org/?probe=7efc294bac) | Feb 02, 2023 |
| MSI           | GV62 7RD                    | [c22fffb4e9](https://linux-hardware.org/?probe=c22fffb4e9) | Feb 02, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [ac6a930ffc](https://linux-hardware.org/?probe=ac6a930ffc) | Feb 02, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [62f941075c](https://linux-hardware.org/?probe=62f941075c) | Jan 31, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [70310e25d1](https://linux-hardware.org/?probe=70310e25d1) | Jan 31, 2023 |
| Dell          | Latitude 5410               | [717012530d](https://linux-hardware.org/?probe=717012530d) | Jan 31, 2023 |
| Unknown       | Unknown                     | [e6c824b966](https://linux-hardware.org/?probe=e6c824b966) | Jan 31, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [aaaa563786](https://linux-hardware.org/?probe=aaaa563786) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | ProBook 650 G1              | [fc09442b7c](https://linux-hardware.org/?probe=fc09442b7c) | Jan 30, 2023 |
| HP            | ProBook 650 G1              | [b78602c91d](https://linux-hardware.org/?probe=b78602c91d) | Jan 30, 2023 |
| Dell          | Latitude E5430 non-vPro     | [d1e99e3f04](https://linux-hardware.org/?probe=d1e99e3f04) | Jan 30, 2023 |
| Toshiba       | Satellite P750              | [1cc0f342b5](https://linux-hardware.org/?probe=1cc0f342b5) | Jan 30, 2023 |
| Apple         | MacBookPro5,2               | [4cb11c2a78](https://linux-hardware.org/?probe=4cb11c2a78) | Jan 30, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603ZX... | [7442c84b55](https://linux-hardware.org/?probe=7442c84b55) | Jan 30, 2023 |
| Dell          | Inspiron 5758               | [de58233dca](https://linux-hardware.org/?probe=de58233dca) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Poland/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 348       | 10.19%  |
| Ubuntu 22.04                 | 191       | 5.59%   |
| OpenMandriva 4.2             | 187       | 5.48%   |
| Ubuntu 18.04                 | 166       | 4.86%   |
| OpenMandriva 4.3             | 111       | 3.25%   |
| Debian 11                    | 99        | 2.9%    |
| Arch Rolling                 | 73        | 2.14%   |
| OpenMandriva 23.03           | 65        | 1.9%    |
| OpenMandriva 23.01           | 56        | 1.64%   |
| Linux Mint 21.1              | 55        | 1.61%   |
| ROSA R10                     | 50        | 1.46%   |
| Linux Mint 20.3              | 46        | 1.35%   |
| Zorin 16                     | 44        | 1.29%   |
| Fedora 38                    | 43        | 1.26%   |
| Linux Mint 20.1              | 42        | 1.23%   |
| Arch                         | 42        | 1.23%   |
| Fedora 37                    | 41        | 1.2%    |
| KDE neon 20.04               | 40        | 1.17%   |
| ROSA R9                      | 39        | 1.14%   |
| Manjaro                      | 38        | 1.11%   |
| ROSA R11.1                   | 36        | 1.05%   |
| Fedora 36                    | 36        | 1.05%   |
| Pop!_OS 22.04                | 34        | 1%      |
| Ubuntu 20.10                 | 33        | 0.97%   |
| Linux Mint 20.2              | 33        | 0.97%   |
| Ubuntu 21.04                 | 32        | 0.94%   |
| Linux Mint 19.3              | 32        | 0.94%   |
| Ubuntu 22.10                 | 31        | 0.91%   |
| ROSA R11                     | 29        | 0.85%   |
| openSUSE Tumbleweed-XXXXXXXX | 28        | 0.82%   |
| Zorin 15                     | 27        | 0.79%   |
| Ubuntu 19.10                 | 27        | 0.79%   |
| Linux Mint 21                | 27        | 0.79%   |
| Linux Mint 20                | 27        | 0.79%   |
| Ubuntu 21.10                 | 26        | 0.76%   |
| Debian 12                    | 26        | 0.76%   |
| Xubuntu 20.04                | 25        | 0.73%   |
| ROSA R8                      | 25        | 0.73%   |
| Fedora 33                    | 25        | 0.73%   |
| Fedora 32                    | 24        | 0.7%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 871       | 27.24%  |
| OpenMandriva  | 441       | 13.79%  |
| Linux Mint    | 278       | 8.7%    |
| Fedora        | 224       | 7.01%   |
| ROSA          | 187       | 5.85%   |
| Debian        | 168       | 5.25%   |
| Manjaro       | 117       | 3.66%   |
| Arch          | 111       | 3.47%   |
| Pop!_OS       | 87        | 2.72%   |
| Zorin         | 74        | 2.31%   |
| Kubuntu       | 63        | 1.97%   |
| KDE neon      | 59        | 1.85%   |
| Xubuntu       | 51        | 1.6%    |
| Kali          | 42        | 1.31%   |
| openSUSE      | 35        | 1.09%   |
| Lubuntu       | 28        | 0.88%   |
| SteamOS       | 26        | 0.81%   |
| Elementary    | 25        | 0.78%   |
| LMDE          | 24        | 0.75%   |
| Endless       | 24        | 0.75%   |
| Gentoo        | 23        | 0.72%   |
| ArcoLinux     | 23        | 0.72%   |
| EndeavourOS   | 20        | 0.63%   |
| Nobara        | 13        | 0.41%   |
| Clear Linux   | 13        | 0.41%   |
| MX            | 12        | 0.38%   |
| Garuda Linux  | 12        | 0.38%   |
| Ubuntu Unity  | 11        | 0.34%   |
| Ubuntu MATE   | 11        | 0.34%   |
| Xero          | 10        | 0.31%   |
| Ubuntu Budgie | 9         | 0.28%   |
| LinuxFX       | 8         | 0.25%   |
| Peppermint    | 7         | 0.22%   |
| BlackPanther  | 7         | 0.22%   |
| CentOS        | 5         | 0.16%   |
| Parrot        | 4         | 0.13%   |
| NixOS         | 4         | 0.13%   |
| Linux Lite    | 4         | 0.13%   |
| EuroLinux     | 4         | 0.13%   |
| Artix         | 4         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 177       | 4.73%   |
| 5.16.7-desktop-1omv4003         | 108       | 2.89%   |
| 6.2.6-desktop-1omv2390          | 63        | 1.68%   |
| 6.1.1-desktop-1omv2290          | 53        | 1.42%   |
| 5.4.0-42-generic                | 44        | 1.18%   |
| 5.15.0-56-generic               | 43        | 1.15%   |
| 5.15.0-58-generic               | 27        | 0.72%   |
| 4.9.20-nrj-desktop-1rosa-x86_64 | 26        | 0.7%    |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 24        | 0.64%   |
| 5.4.0-52-generic                | 22        | 0.59%   |
| 5.4.0-48-generic                | 22        | 0.59%   |
| 5.15.0-43-generic               | 22        | 0.59%   |
| 5.19.0-35-generic               | 21        | 0.56%   |
| 5.15.0-52-generic               | 21        | 0.56%   |
| 5.4.0-29-generic                | 20        | 0.53%   |
| 5.4.0-58-generic                | 19        | 0.51%   |
| 5.4.0-26-generic                | 19        | 0.51%   |
| 5.3.0-46-generic                | 18        | 0.48%   |
| 5.19.0-32-generic               | 18        | 0.48%   |
| 5.15.0-53-generic               | 18        | 0.48%   |
| 5.4.0-33-generic                | 17        | 0.45%   |
| 5.11.0-37-generic               | 17        | 0.45%   |
| 5.0.0-37-generic                | 17        | 0.45%   |
| 5.8.0-43-generic                | 16        | 0.43%   |
| 5.4.0-54-generic                | 16        | 0.43%   |
| 5.15.0-48-generic               | 16        | 0.43%   |
| 4.15.0-desktop-45.1rosa-x86_64  | 16        | 0.43%   |
| 4.1.34-nrj-desktop-2rosa-x86_64 | 16        | 0.43%   |
| 5.4.0-40-generic                | 14        | 0.37%   |
| 5.4.0-37-generic                | 14        | 0.37%   |
| 5.3.0-40-generic                | 14        | 0.37%   |
| 6.4.11-desktop-1omv2390         | 13        | 0.35%   |
| 5.4.0-91-generic                | 13        | 0.35%   |
| 5.3.0-42-generic                | 13        | 0.35%   |
| 5.15.0-60-generic               | 13        | 0.35%   |
| 5.15.0-47-generic               | 13        | 0.35%   |
| 5.13.0-39-generic               | 13        | 0.35%   |
| 5.13.0-27-generic               | 13        | 0.35%   |
| 5.11.0-43-generic               | 13        | 0.35%   |
| 5.11.0-27-generic               | 13        | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 449       | 12.63%  |
| 5.15.0  | 299       | 8.41%   |
| 5.10.14 | 178       | 5.01%   |
| 4.15.0  | 150       | 4.22%   |
| 5.11.0  | 144       | 4.05%   |
| 5.8.0   | 129       | 3.63%   |
| 5.13.0  | 126       | 3.55%   |
| 5.10.0  | 117       | 3.29%   |
| 5.16.7  | 109       | 3.07%   |
| 5.19.0  | 108       | 3.04%   |
| 5.3.0   | 103       | 2.9%    |
| 6.2.6   | 78        | 2.19%   |
| 5.0.0   | 61        | 1.72%   |
| 6.2.0   | 59        | 1.66%   |
| 4.18.0  | 59        | 1.66%   |
| 6.1.1   | 54        | 1.52%   |
| 6.1.0   | 42        | 1.18%   |
| 4.9.20  | 35        | 0.98%   |
| 4.9.60  | 32        | 0.9%    |
| 4.19.0  | 31        | 0.87%   |
| 5.14.0  | 30        | 0.84%   |
| 4.1.34  | 22        | 0.62%   |
| 6.0.0   | 18        | 0.51%   |
| 6.4.11  | 16        | 0.45%   |
| 5.11.12 | 14        | 0.39%   |
| 4.1.38  | 14        | 0.39%   |
| 5.17.0  | 12        | 0.34%   |
| 6.0.7   | 11        | 0.31%   |
| 5.9.0   | 11        | 0.31%   |
| 5.4.32  | 11        | 0.31%   |
| 5.17.5  | 11        | 0.31%   |
| 6.5.5   | 10        | 0.28%   |
| 6.5.0   | 9         | 0.25%   |
| 6.3.5   | 9         | 0.25%   |
| 6.2.11  | 9         | 0.25%   |
| 5.16.0  | 9         | 0.25%   |
| 6.4.12  | 8         | 0.23%   |
| 5.5.0   | 8         | 0.23%   |
| 5.4.83  | 8         | 0.23%   |
| 4.9.76  | 8         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 508       | 14.59%  |
| 5.15    | 365       | 10.49%  |
| 5.10    | 349       | 10.03%  |
| 6.2     | 188       | 5.4%    |
| 5.11    | 182       | 5.23%   |
| 6.1     | 164       | 4.71%   |
| 5.16    | 164       | 4.71%   |
| 5.8     | 160       | 4.6%    |
| 4.15    | 150       | 4.31%   |
| 5.19    | 144       | 4.14%   |
| 5.13    | 143       | 4.11%   |
| 5.3     | 116       | 3.33%   |
| 4.9     | 101       | 2.9%    |
| 6.0     | 74        | 2.13%   |
| 5.0     | 67        | 1.92%   |
| 5.14    | 65        | 1.87%   |
| 4.18    | 62        | 1.78%   |
| 6.4     | 51        | 1.47%   |
| 5.17    | 50        | 1.44%   |
| 6.5     | 43        | 1.24%   |
| 5.9     | 42        | 1.21%   |
| 5.6     | 42        | 1.21%   |
| 5.18    | 40        | 1.15%   |
| 6.3     | 38        | 1.09%   |
| 4.19    | 37        | 1.06%   |
| 4.1     | 35        | 1.01%   |
| 5.12    | 25        | 0.72%   |
| 5.5     | 23        | 0.66%   |
| 5.7     | 20        | 0.57%   |
| 4.4     | 8         | 0.23%   |
| 5.1     | 6         | 0.17%   |
| 5.2     | 4         | 0.11%   |
| 3.10    | 4         | 0.11%   |
| 4.20    | 2         | 0.06%   |
| 4.13    | 2         | 0.06%   |
| 4.10    | 2         | 0.06%   |
| 6.6     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.14    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 2955      | 96.41%  |
| i686    | 109       | 3.56%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1208      | 37.46%  |
| KDE5            | 826       | 25.61%  |
| Unknown         | 265       | 8.22%   |
| XFCE            | 227       | 7.04%   |
| X-Cinnamon      | 200       | 6.2%    |
| KDE4            | 98        | 3.04%   |
| MATE            | 75        | 2.33%   |
| KDE             | 71        | 2.2%    |
| LXQt            | 51        | 1.58%   |
| Cinnamon        | 45        | 1.4%    |
| LXDE            | 37        | 1.15%   |
| Pantheon        | 24        | 0.74%   |
| i3              | 17        | 0.53%   |
| Budgie          | 17        | 0.53%   |
| Unity           | 13        | 0.4%    |
| Deepin          | 9         | 0.28%   |
| GNOME Flashback | 8         | 0.25%   |
| Hyprland        | 6         | 0.19%   |
| sway            | 4         | 0.12%   |
| awesome         | 4         | 0.12%   |
| GNOME Classic   | 3         | 0.09%   |
| Trinity         | 2         | 0.06%   |
| qtile           | 2         | 0.06%   |
| icewm           | 2         | 0.06%   |
| Fluxbox         | 2         | 0.06%   |
| DWM             | 2         | 0.06%   |
| stumpwm         | 1         | 0.03%   |
| ratflow         | 1         | 0.03%   |
| qt5ct           | 1         | 0.03%   |
| openbox         | 1         | 0.03%   |
| GNUstep         | 1         | 0.03%   |
| Endless:GNOME   | 1         | 0.03%   |
| BunsenLabs      | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 2438      | 76.96%  |
| Wayland     | 562       | 17.74%  |
| Unknown     | 131       | 4.14%   |
| Tty         | 36        | 1.14%   |
| Unspecified | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1225      | 38.14%  |
| SDDM    | 771       | 24%     |
| GDM     | 379       | 11.8%   |
| GDM3    | 332       | 10.34%  |
| LightDM | 294       | 9.15%   |
| KDM     | 100       | 3.11%   |
| TDM     | 95        | 2.96%   |
| XDM     | 6         | 0.19%   |
| Ly      | 3         | 0.09%   |
| NODM    | 2         | 0.06%   |
| SU      | 1         | 0.03%   |
| SLIMSKI | 1         | 0.03%   |
| SLiM    | 1         | 0.03%   |
| MDM     | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| pl_PL       | 1674      | 52.84%  |
| en_US       | 892       | 28.16%  |
| Unknown     | 373       | 11.77%  |
| en_GB       | 85        | 2.68%   |
| C           | 61        | 1.93%   |
| ru_RU       | 24        | 0.76%   |
| szl_PL      | 9         | 0.28%   |
| uk_UA       | 7         | 0.22%   |
| de_DE       | 7         | 0.22%   |
| ru_UA       | 5         | 0.16%   |
| en_IE       | 4         | 0.13%   |
| fr_FR       | 3         | 0.09%   |
| POSIX       | 2         | 0.06%   |
| nl_NL       | 2         | 0.06%   |
| it_IT       | 2         | 0.06%   |
| hu_HU       | 2         | 0.06%   |
| en_DK       | 2         | 0.06%   |
| C.UTF8      | 2         | 0.06%   |
| sk_SK       | 1         | 0.03%   |
| es_ES       | 1         | 0.03%   |
| es_AR       | 1         | 0.03%   |
| en_US.utf-8 | 1         | 0.03%   |
| en_IN       | 1         | 0.03%   |
| en_CA       | 1         | 0.03%   |
| en_AU       | 1         | 0.03%   |
| en_AG       | 1         | 0.03%   |
| Default     | 1         | 0.03%   |
| be_BY       | 1         | 0.03%   |
| af_ZA       | 1         | 0.03%   |
| aa_DJ       | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1571      | 50.1%   |
| EFI  | 1565      | 49.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 2164      | 68.07%  |
| Overlay  | 402       | 12.65%  |
| Btrfs    | 301       | 9.47%   |
| Unknown  | 173       | 5.44%   |
| Tmpfs    | 48        | 1.51%   |
| Xfs      | 47        | 1.48%   |
| Zfs      | 23        | 0.72%   |
| F2fs     | 9         | 0.28%   |
| Rootfs   | 3         | 0.09%   |
| Ext3     | 3         | 0.09%   |
| Ext2     | 3         | 0.09%   |
| XXXXX    | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| Bcachefs | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1365      | 43.24%  |
| GPT     | 1290      | 40.86%  |
| MBR     | 502       | 15.9%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2658      | 84.7%   |
| Yes       | 480       | 15.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2109      | 67.62%  |
| Yes       | 1010      | 32.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 809       | 26.43%  |
| Dell                | 633       | 20.68%  |
| Hewlett-Packard     | 474       | 15.49%  |
| ASUSTek Computer    | 356       | 11.63%  |
| Acer                | 194       | 6.34%   |
| Toshiba             | 82        | 2.68%   |
| Samsung Electronics | 82        | 2.68%   |
| MSI                 | 67        | 2.19%   |
| Sony                | 37        | 1.21%   |
| HUAWEI              | 35        | 1.14%   |
| Apple               | 30        | 0.98%   |
| Fujitsu             | 25        | 0.82%   |
| Google              | 24        | 0.78%   |
| Valve               | 23        | 0.75%   |
| Fujitsu Siemens     | 22        | 0.72%   |
| Packard Bell        | 16        | 0.52%   |
| Notebook            | 16        | 0.52%   |
| Kiano               | 11        | 0.36%   |
| eMachines           | 11        | 0.36%   |
| Timi                | 9         | 0.29%   |
| Medion              | 9         | 0.29%   |
| Gigabyte Technology | 7         | 0.23%   |
| Unknown             | 7         | 0.23%   |
| mPTech              | 4         | 0.13%   |
| Kruger&Matz         | 4         | 0.13%   |
| GPU Company         | 4         | 0.13%   |
| Alienware           | 4         | 0.13%   |
| TUXEDO              | 3         | 0.1%    |
| Teclast             | 3         | 0.1%    |
| Panasonic           | 3         | 0.1%    |
| Clevo               | 3         | 0.1%    |
| Chuwi               | 3         | 0.1%    |
| XIAOMI              | 2         | 0.07%   |
| TrekStor            | 2         | 0.07%   |
| System76            | 2         | 0.07%   |
| Star Labs           | 2         | 0.07%   |
| Schenker            | 2         | 0.07%   |
| Razer               | 2         | 0.07%   |
| MODECOM             | 2         | 0.07%   |
| MAXDATA             | 2         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Dell Inspiron 3451                  | 31        | 1.01%   |
| Unknown                             | 30        | 0.98%   |
| Valve Jupiter                       | 23        | 0.75%   |
| Dell Latitude E6400                 | 17        | 0.56%   |
| Dell Latitude E6540                 | 15        | 0.49%   |
| Lenovo G50-30 80G0                  | 13        | 0.42%   |
| HP Pavilion dv7                     | 12        | 0.39%   |
| Dell Latitude 5480                  | 12        | 0.39%   |
| Dell Latitude E6430                 | 11        | 0.36%   |
| Dell Latitude D630                  | 11        | 0.36%   |
| Dell Latitude 5490                  | 11        | 0.36%   |
| ASUS X555LJ                         | 11        | 0.36%   |
| Lenovo Legion Y530-15ICH 81FV       | 10        | 0.33%   |
| Lenovo G580 20150                   | 10        | 0.33%   |
| Dell Latitude E6420                 | 10        | 0.33%   |
| Lenovo G510 20238                   | 9         | 0.29%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 9         | 0.29%   |
| HP Notebook                         | 9         | 0.29%   |
| HP 15                               | 9         | 0.29%   |
| Dell Latitude E7440                 | 9         | 0.29%   |
| Dell Latitude 5420                  | 9         | 0.29%   |
| Lenovo Legion Y540-15IRH 81SX       | 8         | 0.26%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 8         | 0.26%   |
| Lenovo G50-80 80E5                  | 8         | 0.26%   |
| HP Pavilion dv6                     | 8         | 0.26%   |
| Dell Latitude E6330                 | 8         | 0.26%   |
| Dell Latitude 5511                  | 8         | 0.26%   |
| Toshiba Satellite A300              | 7         | 0.23%   |
| Samsung 550P5C/550P7C               | 7         | 0.23%   |
| Lenovo Z51-70 80K6                  | 7         | 0.23%   |
| Lenovo Legion 5 15ARH05 82B5        | 7         | 0.23%   |
| Lenovo IdeaPad 100-15IBD 80QQ       | 7         | 0.23%   |
| HUAWEI HVY-WXX9                     | 7         | 0.23%   |
| HP Laptop 15-db1xxx                 | 7         | 0.23%   |
| HP EliteBook 840 G3                 | 7         | 0.23%   |
| HP EliteBook 6930p                  | 7         | 0.23%   |
| HP 255 G7 Notebook PC               | 7         | 0.23%   |
| HP 250 G6 Notebook PC               | 7         | 0.23%   |
| Dell Latitude E7450                 | 7         | 0.23%   |
| Dell Latitude E6440                 | 7         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 365       | 11.92%  |
| Dell Latitude         | 328       | 10.72%  |
| Lenovo IdeaPad        | 165       | 5.39%   |
| Dell Inspiron         | 161       | 5.26%   |
| Acer Aspire           | 122       | 3.99%   |
| HP EliteBook          | 106       | 3.46%   |
| HP Pavilion           | 103       | 3.36%   |
| HP ProBook            | 70        | 2.29%   |
| Toshiba Satellite     | 66        | 2.16%   |
| Lenovo Legion         | 62        | 2.03%   |
| Dell Precision        | 44        | 1.44%   |
| ASUS VivoBook         | 41        | 1.34%   |
| HP Laptop             | 37        | 1.21%   |
| Dell XPS              | 35        | 1.14%   |
| Dell Vostro           | 34        | 1.11%   |
| Unknown               | 30        | 0.98%   |
| ASUS ASUS             | 27        | 0.88%   |
| HP Compaq             | 25        | 0.82%   |
| Valve Jupiter         | 23        | 0.75%   |
| HP 250                | 21        | 0.69%   |
| Fujitsu LIFEBOOK      | 21        | 0.69%   |
| ASUS TUF              | 21        | 0.69%   |
| ASUS ROG              | 20        | 0.65%   |
| HP ZBook              | 17        | 0.56%   |
| Packard Bell EasyNote | 16        | 0.52%   |
| Lenovo ThinkBook      | 15        | 0.49%   |
| Acer Extensa          | 15        | 0.49%   |
| Acer Nitro            | 14        | 0.46%   |
| Lenovo G50-30         | 13        | 0.42%   |
| HP OMEN               | 13        | 0.42%   |
| Lenovo Yoga           | 12        | 0.39%   |
| Lenovo G580           | 12        | 0.39%   |
| ASUS Zenbook          | 12        | 0.39%   |
| Acer TravelMate       | 12        | 0.39%   |
| Acer Swift            | 12        | 0.39%   |
| HP 255                | 11        | 0.36%   |
| ASUS X555LJ           | 11        | 0.36%   |
| Lenovo G50-80         | 10        | 0.33%   |
| Fujitsu Siemens AMILO | 10        | 0.33%   |
| Lenovo G510           | 9         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 258       | 8.43%   |
| 2019    | 257       | 8.4%    |
| 2020    | 251       | 8.2%    |
| 2013    | 247       | 8.07%   |
| 2011    | 245       | 8%      |
| 2018    | 216       | 7.06%   |
| 2014    | 203       | 6.63%   |
| 2008    | 187       | 6.11%   |
| 2021    | 186       | 6.08%   |
| 2015    | 185       | 6.04%   |
| 2017    | 168       | 5.49%   |
| 2010    | 152       | 4.97%   |
| 2016    | 136       | 4.44%   |
| 2007    | 108       | 3.53%   |
| 2009    | 104       | 3.4%    |
| 2022    | 94        | 3.07%   |
| 2006    | 36        | 1.18%   |
| 2023    | 21        | 0.69%   |
| 2005    | 3         | 0.1%    |
| 2004    | 2         | 0.07%   |
| Unknown | 2         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3061      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2828      | 91.58%  |
| Enabled  | 260       | 8.42%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3034      | 99.12%  |
| Yes  | 27        | 0.88%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 756       | 24.33%  |
| 3.01-4.0    | 745       | 23.98%  |
| 8.01-16.0   | 526       | 16.93%  |
| 16.01-24.0  | 503       | 16.19%  |
| 32.01-64.0  | 265       | 8.53%   |
| 1.01-2.0    | 130       | 4.18%   |
| 2.01-3.0    | 92        | 2.96%   |
| 24.01-32.0  | 37        | 1.19%   |
| 64.01-256.0 | 31        | 1%      |
| 0.51-1.0    | 22        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1231      | 35.86%  |
| 2.01-3.0   | 789       | 22.98%  |
| 4.01-8.0   | 498       | 14.51%  |
| 3.01-4.0   | 433       | 12.61%  |
| 0.51-1.0   | 267       | 7.78%   |
| 8.01-16.0  | 158       | 4.6%    |
| 0.01-0.5   | 30        | 0.87%   |
| 16.01-24.0 | 20        | 0.58%   |
| 24.01-32.0 | 7         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 2277      | 72.52%  |
| 2       | 724       | 23.06%  |
| 3       | 85        | 2.71%   |
| 0       | 39        | 1.24%   |
| 4       | 11        | 0.35%   |
| 5       | 3         | 0.1%    |
| Unknown | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1867      | 60.42%  |
| Yes       | 1223      | 39.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2634      | 85.63%  |
| No        | 442       | 14.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3017      | 98.47%  |
| No        | 47        | 1.53%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2382      | 76.47%  |
| No        | 733       | 23.53%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Poland  | 3061      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Warsaw                 | 737       | 22.09%  |
| Krakow                 | 262       | 7.85%   |
| Wroclaw                | 199       | 5.97%   |
| Poznan                 | 187       | 5.61%   |
| Lodz                   | 116       | 3.48%   |
| Gdansk                 | 113       | 3.39%   |
| Katowice               | 88        | 2.64%   |
| Lublin                 | 47        | 1.41%   |
| Gdynia                 | 39        | 1.17%   |
| Szczecin               | 37        | 1.11%   |
| Bialystok              | 28        | 0.84%   |
| Bydgoszcz              | 26        | 0.78%   |
| Rzeszów               | 25        | 0.75%   |
| Ruda Śląska          | 24        | 0.72%   |
| Torun                  | 23        | 0.69%   |
| Gliwice                | 23        | 0.69%   |
| Częstochowa           | 23        | 0.69%   |
| Elblag                 | 19        | 0.57%   |
| Zabrze                 | 18        | 0.54%   |
| Płock                 | 18        | 0.54%   |
| Bytom                  | 18        | 0.54%   |
| Olsztyn                | 17        | 0.51%   |
| Sosnowiec              | 16        | 0.48%   |
| Opole                  | 16        | 0.48%   |
| Kielce                 | 15        | 0.45%   |
| Chorzów               | 14        | 0.42%   |
| Tarnów                | 12        | 0.36%   |
| Siemianowice Śląskie | 11        | 0.33%   |
| Blizniew               | 11        | 0.33%   |
| Bielsko-Biala          | 11        | 0.33%   |
| Rybnik                 | 10        | 0.3%    |
| Pruszków              | 10        | 0.3%    |
| Chorzele               | 10        | 0.3%    |
| Tychy                  | 9         | 0.27%   |
| Skierniewice           | 9         | 0.27%   |
| Piaseczno              | 9         | 0.27%   |
| Zielona Góra          | 8         | 0.24%   |
| Wejherowo              | 8         | 0.24%   |
| Tarnowskie Gory        | 8         | 0.24%   |
| Skawina                | 8         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 558       | 743    | 14.5%   |
| Seagate                     | 433       | 538    | 11.25%  |
| WDC                         | 399       | 495    | 10.37%  |
| Toshiba                     | 247       | 305    | 6.42%   |
| Goodram                     | 241       | 309    | 6.26%   |
| Unknown                     | 187       | 241    | 4.86%   |
| SanDisk                     | 175       | 218    | 4.55%   |
| SK hynix                    | 151       | 187    | 3.92%   |
| Hitachi                     | 146       | 172    | 3.79%   |
| Kingston                    | 140       | 194    | 3.64%   |
| Intel                       | 140       | 180    | 3.64%   |
| A-DATA Technology           | 138       | 166    | 3.59%   |
| Crucial                     | 127       | 193    | 3.3%    |
| Micron Technology           | 91        | 117    | 2.36%   |
| HGST                        | 77        | 95     | 2%      |
| KIOXIA                      | 44        | 49     | 1.14%   |
| Patriot                     | 36        | 44     | 0.94%   |
| SPCC                        | 35        | 41     | 0.91%   |
| PNY                         | 29        | 30     | 0.75%   |
| Plextor                     | 26        | 39     | 0.68%   |
| Fujitsu                     | 24        | 25     | 0.62%   |
| Phison Electronics          | 21        | 21     | 0.55%   |
| LITEON                      | 21        | 25     | 0.55%   |
| Transcend                   | 19        | 23     | 0.49%   |
| Phison                      | 18        | 24     | 0.47%   |
| China                       | 16        | 22     | 0.42%   |
| Silicon Motion              | 14        | 18     | 0.36%   |
| Apacer                      | 14        | 23     | 0.36%   |
| LITEONIT                    | 13        | 15     | 0.34%   |
| Unknown                     | 13        | 16     | 0.34%   |
| KIOXIA-EXCERIA              | 12        | 13     | 0.31%   |
| Apple                       | 12        | 15     | 0.31%   |
| Lenovo                      | 9         | 11     | 0.23%   |
| JMicron Technology          | 9         | 9      | 0.23%   |
| ADATA Technology            | 9         | 13     | 0.23%   |
| OCZ                         | 8         | 8      | 0.21%   |
| Lexar                       | 8         | 8      | 0.21%   |
| Kingston Technology Company | 8         | 8      | 0.21%   |
| Gigabyte Technology         | 8         | 9      | 0.21%   |
| Micron/Crucial Technology   | 7         | 7      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST500LT012-1DG142 500GB                   | 58        | 1.46%   |
| Seagate ST1000LM035-1RK172 1TB                    | 49        | 1.23%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 49        | 1.23%   |
| GOODRAM SSDPR-CX400-256-G2 256GB                  | 32        | 0.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 31        | 0.78%   |
| Unknown MMC Card  32GB                            | 30        | 0.75%   |
| Crucial CT500MX500SSD1 500GB                      | 26        | 0.65%   |
| Intel NVMe SSD Drive 512GB                        | 25        | 0.63%   |
| Toshiba MQ01ABD100 1TB                            | 24        | 0.6%    |
| Seagate ST9500325AS 500GB                         | 24        | 0.6%    |
| Kingston SA400S37240G 240GB SSD                   | 23        | 0.58%   |
| GOODRAM SSD 120GB                                 | 23        | 0.58%   |
| HGST HTS721010A9E630 1TB                          | 22        | 0.55%   |
| Unknown MMC Card  64GB                            | 21        | 0.53%   |
| Toshiba MQ01ABF050 500GB                          | 21        | 0.53%   |
| Samsung NVMe SSD Drive 512GB                      | 21        | 0.53%   |
| Crucial CT1000MX500SSD1 1TB                       | 20        | 0.5%    |
| Samsung SSD 860 EVO 500GB                         | 19        | 0.48%   |
| Samsung SSD 850 EVO 250GB                         | 19        | 0.48%   |
| Intel SSDPEKNW512G8H 512GB                        | 19        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB                      | 18        | 0.45%   |
| GOODRAM SSD 240GB                                 | 18        | 0.45%   |
| Unknown MMC Card  128GB                           | 17        | 0.43%   |
| Samsung SSD 980 1TB                               | 17        | 0.43%   |
| HGST HTS725050A7E630 500GB                        | 16        | 0.4%    |
| GOODRAM SSDPR-CX400-512-G2 512GB                  | 16        | 0.4%    |
| GOODRAM SSDPR-CX400-512 512GB                     | 16        | 0.4%    |
| Crucial CT240BX500SSD1 240GB                      | 16        | 0.4%    |
| WDC WD10JPCX-24UE4T0 1TB                          | 15        | 0.38%   |
| Seagate Expansion 1TB                             | 15        | 0.38%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 15        | 0.38%   |
| A-DATA SU800 256GB SSD                            | 15        | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB                          | 14        | 0.35%   |
| Patriot Burst 120GB SSD                           | 14        | 0.35%   |
| GOODRAM SSDPR-CX400-256 256GB                     | 14        | 0.35%   |
| Seagate ST1000LM014-SSHD-8GB                      | 13        | 0.33%   |
| Samsung SSD 980 500GB                             | 13        | 0.33%   |
| Phison PS5013 E13 NVMe Controller 256GB           | 13        | 0.33%   |
| Unknown                                           | 13        | 0.33%   |
| SK hynix NVMe SSD Drive 512GB                     | 12        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 428       | 531    | 36.9%   |
| WDC                 | 269       | 325    | 23.19%  |
| Toshiba             | 163       | 201    | 14.05%  |
| Hitachi             | 146       | 172    | 12.59%  |
| HGST                | 77        | 95     | 6.64%   |
| Samsung Electronics | 34        | 36     | 2.93%   |
| Fujitsu             | 24        | 25     | 2.07%   |
| Unknown             | 5         | 5      | 0.43%   |
| ASMT                | 4         | 4      | 0.34%   |
| USB3.0              | 3         | 3      | 0.26%   |
| USB                 | 1         | 1      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |
| SAGE                | 1         | 1      | 0.09%   |
| LaCie               | 1         | 2      | 0.09%   |
| IBM/Hitachi         | 1         | 1      | 0.09%   |
| ASMedia             | 1         | 1      | 0.09%   |
| Apple               | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 241       | 314    | 16.83%  |
| GOODRAM             | 233       | 301    | 16.27%  |
| Crucial             | 123       | 188    | 8.59%   |
| A-DATA Technology   | 118       | 144    | 8.24%   |
| Kingston            | 105       | 141    | 7.33%   |
| SanDisk             | 102       | 129    | 7.12%   |
| WDC                 | 58        | 69     | 4.05%   |
| SK hynix            | 41        | 50     | 2.86%   |
| Micron Technology   | 39        | 48     | 2.72%   |
| Intel               | 38        | 44     | 2.65%   |
| Patriot             | 34        | 42     | 2.37%   |
| Toshiba             | 33        | 36     | 2.3%    |
| SPCC                | 33        | 39     | 2.3%    |
| Plextor             | 23        | 36     | 1.61%   |
| PNY                 | 22        | 23     | 1.54%   |
| LITEON              | 21        | 25     | 1.47%   |
| Transcend           | 18        | 22     | 1.26%   |
| China               | 16        | 22     | 1.12%   |
| LITEONIT            | 13        | 15     | 0.91%   |
| KIOXIA-EXCERIA      | 11        | 12     | 0.77%   |
| Apacer              | 11        | 19     | 0.77%   |
| OCZ                 | 8         | 8      | 0.56%   |
| Apple               | 7         | 7      | 0.49%   |
| KingSpec            | 6         | 7      | 0.42%   |
| Team                | 5         | 5      | 0.35%   |
| Gigabyte Technology | 5         | 6      | 0.35%   |
| POLION              | 3         | 3      | 0.21%   |
| Corsair             | 3         | 3      | 0.21%   |
| Biostar             | 3         | 3      | 0.21%   |
| 2-Power             | 3         | 3      | 0.21%   |
| Unknown             | 3         | 3      | 0.21%   |
| Union Memory        | 2         | 3      | 0.14%   |
| Ramaxel Technology  | 2         | 3      | 0.14%   |
| Phison              | 2         | 2      | 0.14%   |
| OWC                 | 2         | 2      | 0.14%   |
| Netac               | 2         | 3      | 0.14%   |
| Micron_1            | 2         | 2      | 0.14%   |
| Intenso             | 2         | 2      | 0.14%   |
| HS-SSD-C100         | 2         | 4      | 0.14%   |
| BIWIN               | 2         | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1308      | 1828   | 36.24%  |
| HDD     | 1113      | 1405   | 30.84%  |
| NVMe    | 963       | 1346   | 26.68%  |
| MMC     | 184       | 234    | 5.1%    |
| Unknown | 41        | 52     | 1.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2156      | 3139   | 62.91%  |
| NVMe | 958       | 1327   | 27.95%  |
| MMC  | 184       | 234    | 5.37%   |
| SAS  | 129       | 165    | 3.76%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1739      | 2376   | 72.85%  |
| 0.51-1.0   | 586       | 781    | 24.55%  |
| 1.01-2.0   | 49        | 60     | 2.05%   |
| 3.01-4.0   | 6         | 6      | 0.25%   |
| 2.01-3.0   | 3         | 6      | 0.13%   |
| 4.01-10.0  | 3         | 3      | 0.13%   |
| 10.01-20.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 982       | 29.87%  |
| 251-500        | 731       | 22.23%  |
| 1-20           | 415       | 12.62%  |
| 501-1000       | 357       | 10.86%  |
| 51-100         | 286       | 8.7%    |
| 1001-2000      | 160       | 4.87%   |
| 21-50          | 152       | 4.62%   |
| Unknown        | 119       | 3.62%   |
| 2001-3000      | 47        | 1.43%   |
| More than 3000 | 39        | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1458      | 42.81%  |
| 21-50          | 543       | 15.94%  |
| 101-250        | 454       | 13.33%  |
| 51-100         | 434       | 12.74%  |
| 251-500        | 194       | 5.7%    |
| 501-1000       | 128       | 3.76%   |
| Unknown        | 119       | 3.49%   |
| 1001-2000      | 55        | 1.61%   |
| 2001-3000      | 12        | 0.35%   |
| More than 3000 | 7         | 0.21%   |
| 0              | 2         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                      | 9         | 9      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 10     | 2.63%   |
| Seagate ST500LT012-9WS142 500GB                | 8         | 27     | 2.34%   |
| SK hynix PC711 HFS512GDE9X073N 512GB           | 6         | 7      | 1.75%   |
| Seagate ST500LT012-1DG142 500GB                | 6         | 9      | 1.75%   |
| HGST HTS545050A7E680 500GB                     | 5         | 5      | 1.46%   |
| WDC WD5000BEVT-22ZAT0 500GB                    | 4         | 4      | 1.17%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 4         | 4      | 1.17%   |
| Seagate ST1000LM014-SSHD-8GB                   | 4         | 4      | 1.17%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 4         | 5      | 1.17%   |
| Hitachi HTS543225L9SA00 250GB                  | 4         | 4      | 1.17%   |
| Hitachi HTS541612J9SA00 120GB                  | 4         | 5      | 1.17%   |
| WDC WD3200BPVT-80ZEST0 320GB                   | 3         | 3      | 0.88%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 4      | 0.88%   |
| Toshiba MK1246GSX 120GB                        | 3         | 3      | 0.88%   |
| Seagate ST980811AS 80GB                        | 3         | 3      | 0.88%   |
| Seagate ST9500420AS 500GB                      | 3         | 3      | 0.88%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 0.88%   |
| Seagate ST9250827AS 250GB                      | 3         | 4      | 0.88%   |
| Seagate ST9250410AS 250GB                      | 3         | 3      | 0.88%   |
| Seagate ST320LT020-9YG142 320GB                | 3         | 3      | 0.88%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD            | 3         | 3      | 0.88%   |
| Hitachi HTS543232A7A384 320GB                  | 3         | 4      | 0.88%   |
| WDC WD7500BPKT-22PK4T0 752GB                   | 2         | 2      | 0.58%   |
| WDC WD3200BEVT-80A0RT0 320GB                   | 2         | 2      | 0.58%   |
| WDC WD1600BEVT-75A23T0 160GB                   | 2         | 2      | 0.58%   |
| WDC WD1600BEVT-22A23T0 160GB                   | 2         | 2      | 0.58%   |
| Toshiba MK5075GSX 500GB                        | 2         | 2      | 0.58%   |
| Toshiba MK3265GSX 320GB                        | 2         | 2      | 0.58%   |
| Toshiba MK1637GSX 160GB                        | 2         | 2      | 0.58%   |
| SK hynix BC711 HFM512GD3JX013N 512GB           | 2         | 2      | 0.58%   |
| Seagate ST9250410ASG 250GB                     | 2         | 2      | 0.58%   |
| Seagate ST9250315AS 250GB                      | 2         | 2      | 0.58%   |
| Seagate ST9160821AS 160GB                      | 2         | 3      | 0.58%   |
| Seagate ST9120822AS 120GB                      | 2         | 2      | 0.58%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.58%   |
| Seagate ST1000LM035-1RK172 1TB                 | 2         | 2      | 0.58%   |
| Samsung Electronics HM250HI 250GB              | 2         | 2      | 0.58%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 2         | 2      | 0.58%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD          | 2         | 2      | 0.58%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 117    | 25.51%  |
| Hitachi             | 42        | 47     | 12.32%  |
| WDC                 | 41        | 42     | 12.02%  |
| Toshiba             | 37        | 47     | 10.85%  |
| A-DATA Technology   | 19        | 21     | 5.57%   |
| Samsung Electronics | 18        | 20     | 5.28%   |
| SK hynix            | 16        | 17     | 4.69%   |
| HGST                | 15        | 16     | 4.4%    |
| SanDisk             | 9         | 10     | 2.64%   |
| Micron Technology   | 7         | 7      | 2.05%   |
| Kingston            | 7         | 7      | 2.05%   |
| Intel               | 6         | 6      | 1.76%   |
| Fujitsu             | 6         | 6      | 1.76%   |
| Crucial             | 5         | 14     | 1.47%   |
| LITEONIT            | 3         | 3      | 0.88%   |
| LITEON              | 3         | 3      | 0.88%   |
| ASMedia             | 3         | 3      | 0.88%   |
| Patriot             | 2         | 4      | 0.59%   |
| OCZ                 | 2         | 2      | 0.59%   |
| China               | 2         | 3      | 0.59%   |
| SPCC                | 1         | 1      | 0.29%   |
| RENICE              | 1         | 1      | 0.29%   |
| POLION              | 1         | 1      | 0.29%   |
| Plextor             | 1         | 1      | 0.29%   |
| Platinet            | 1         | 1      | 0.29%   |
| OWC                 | 1         | 1      | 0.29%   |
| Lexar               | 1         | 1      | 0.29%   |
| Lenovo              | 1         | 1      | 0.29%   |
| KingSpec            | 1         | 1      | 0.29%   |
| Apple               | 1         | 1      | 0.29%   |
| Apacer              | 1         | 1      | 0.29%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 87        | 117    | 37.18%  |
| Hitachi             | 42        | 47     | 17.95%  |
| WDC                 | 39        | 40     | 16.67%  |
| Toshiba             | 34        | 44     | 14.53%  |
| HGST                | 15        | 16     | 6.41%   |
| Samsung Electronics | 10        | 10     | 4.27%   |
| Fujitsu             | 6         | 6      | 2.56%   |
| ASMedia             | 1         | 1      | 0.43%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 228       | 281    | 68.67%  |
| SSD  | 84        | 102    | 25.3%   |
| NVMe | 20        | 23     | 6.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD800BEVS-75RST0 80GB       | 1         | 1      | 20%     |
| WDC WD3200BEKT-75PVMT1 320GB    | 1         | 1      | 20%     |
| WDC WD2500BEVS-22UST0 250GB     | 1         | 1      | 20%     |
| Toshiba MK3265GSXN 320GB        | 1         | 1      | 20%     |
| Seagate ST320LT020-9YG142 320GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 60%     |
| Toshiba | 1         | 1      | 20%     |
| Seagate | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1514      | 2398   | 46.19%  |
| Works    | 1432      | 2056   | 43.69%  |
| Malfunc  | 327       | 406    | 9.98%   |
| Failed   | 5         | 5      | 0.15%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2288      | 64.05%  |
| AMD                              | 302       | 8.45%   |
| Samsung Electronics              | 297       | 8.31%   |
| SanDisk                          | 138       | 3.86%   |
| SK hynix                         | 110       | 3.08%   |
| Phison Electronics               | 57        | 1.6%    |
| Toshiba America Info Systems     | 56        | 1.57%   |
| Micron Technology                | 52        | 1.46%   |
| KIOXIA                           | 45        | 1.26%   |
| Kingston Technology Company      | 42        | 1.18%   |
| ADATA Technology                 | 30        | 0.84%   |
| Silicon Motion                   | 26        | 0.73%   |
| Nvidia                           | 22        | 0.62%   |
| Union Memory (Shenzhen)          | 14        | 0.39%   |
| Silicon Integrated Systems [SiS] | 11        | 0.31%   |
| Micron/Crucial Technology        | 11        | 0.31%   |
| Shenzhen Longsys Electronics     | 9         | 0.25%   |
| Lite-On Technology               | 9         | 0.25%   |
| Solid State Storage Technology   | 8         | 0.22%   |
| Realtek Semiconductor            | 8         | 0.22%   |
| Lenovo                           | 8         | 0.22%   |
| VIA Technologies                 | 7         | 0.2%    |
| JMicron Technology               | 5         | 0.14%   |
| MAXIO Technology (Hangzhou)      | 4         | 0.11%   |
| Apple                            | 3         | 0.08%   |
| Yangtze Memory Technologies      | 2         | 0.06%   |
| O2 Micro                         | 2         | 0.06%   |
| Marvell Technology Group         | 2         | 0.06%   |
| Silicon Image                    | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |
| Unknown                          | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 253       | 6.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 252       | 6.43%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 209       | 5.34%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 181       | 4.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 174       | 4.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 142       | 3.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 130       | 3.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 124       | 3.17%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 110       | 2.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 108       | 2.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 105       | 2.68%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 101       | 2.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 92        | 2.35%   |
| Intel Volume Management Device NVMe RAID Controller                            | 89        | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 82        | 2.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 79        | 2.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 77        | 1.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 71        | 1.81%   |
| Intel SSD 660P Series                                                          | 66        | 1.68%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 57        | 1.46%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 50        | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 40        | 1.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 38        | 0.97%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 37        | 0.94%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 33        | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 32        | 0.82%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 31        | 0.79%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 30        | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                            | 30        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 29        | 0.74%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 28        | 0.71%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 27        | 0.69%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 26        | 0.66%   |
| SK hynix BC511 NVMe SSD                                                        | 25        | 0.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 24        | 0.61%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 24        | 0.61%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 22        | 0.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 22        | 0.56%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 21        | 0.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 21        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2154      | 57.89%  |
| NVMe | 963       | 25.88%  |
| IDE  | 329       | 8.84%   |
| RAID | 275       | 7.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2555      | 83.47%  |
| AMD          | 503       | 16.43%  |
| CentaurHauls | 2         | 0.07%   |
| QUALCOMM     | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 51        | 1.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 47        | 1.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 44        | 1.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 43        | 1.4%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 42        | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 1.31%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 38        | 1.24%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 36        | 1.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 36        | 1.17%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 34        | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 33        | 1.08%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 32        | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 32        | 1.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 30        | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 30        | 0.98%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.95%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 28        | 0.91%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 28        | 0.91%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 26        | 0.85%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 25        | 0.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 23        | 0.75%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.75%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 23        | 0.75%   |
| AMD Custom APU 0405                           | 23        | 0.75%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 22        | 0.72%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 22        | 0.72%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 20        | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.65%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 20        | 0.65%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 20        | 0.65%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 19        | 0.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 19        | 0.62%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 19        | 0.62%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 18        | 0.59%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.59%   |
| Intel Core i5-3340M CPU @ 2.70GHz             | 18        | 0.59%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 18        | 0.59%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 18        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 855       | 27.91%  |
| Intel Core i7                  | 567       | 18.51%  |
| Intel Core i3                  | 239       | 7.8%    |
| Intel Core 2 Duo               | 235       | 7.67%   |
| Other                          | 202       | 6.59%   |
| Intel Celeron                  | 171       | 5.58%   |
| AMD Ryzen 5                    | 151       | 4.93%   |
| AMD Ryzen 7                    | 110       | 3.59%   |
| Intel Pentium                  | 97        | 3.17%   |
| Intel Atom                     | 56        | 1.83%   |
| Intel Pentium Dual-Core        | 40        | 1.31%   |
| AMD A6                         | 28        | 0.91%   |
| Intel Core 2                   | 22        | 0.72%   |
| AMD A8                         | 21        | 0.69%   |
| AMD Ryzen 7 PRO                | 20        | 0.65%   |
| Intel Pentium Dual             | 17        | 0.56%   |
| Intel Genuine                  | 16        | 0.52%   |
| AMD A4                         | 14        | 0.46%   |
| AMD E1                         | 13        | 0.42%   |
| AMD E                          | 13        | 0.42%   |
| AMD A10                        | 12        | 0.39%   |
| Intel Xeon                     | 11        | 0.36%   |
| Intel Celeron M                | 11        | 0.36%   |
| AMD Ryzen 9                    | 11        | 0.36%   |
| Intel Pentium M                | 8         | 0.26%   |
| AMD Ryzen 3                    | 8         | 0.26%   |
| AMD E2                         | 8         | 0.26%   |
| AMD Athlon X2                  | 8         | 0.26%   |
| Intel Core Duo                 | 7         | 0.23%   |
| AMD Turion 64 X2 Mobile        | 7         | 0.23%   |
| AMD Ryzen 5 PRO                | 7         | 0.23%   |
| AMD C-60                       | 6         | 0.2%    |
| Intel Celeron Dual-Core        | 5         | 0.16%   |
| AMD Athlon II                  | 5         | 0.16%   |
| Intel Pentium Silver           | 4         | 0.13%   |
| Intel Core i9                  | 4         | 0.13%   |
| AMD Turion X2 Dual-Core Mobile | 4         | 0.13%   |
| AMD Phenom II                  | 4         | 0.13%   |
| Intel Core m3                  | 3         | 0.1%    |
| Intel Core M                   | 3         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1671      | 54.5%   |
| 4       | 890       | 29.03%  |
| 6       | 209       | 6.82%   |
| 8       | 151       | 4.92%   |
| 1       | 73        | 2.38%   |
| Unknown | 21        | 0.68%   |
| 14      | 17        | 0.55%   |
| 12      | 14        | 0.46%   |
| 10      | 14        | 0.46%   |
| 16      | 2         | 0.07%   |
| 3       | 2         | 0.07%   |
| 192     | 1         | 0.03%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 3058      | 99.9%   |
| Unknown | 2         | 0.07%   |
| 2       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2171      | 70.69%  |
| 1       | 877       | 28.56%  |
| Unknown | 21        | 0.68%   |
| 8       | 1         | 0.03%   |
| 4       | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2978      | 97.13%  |
| 32-bit         | 48        | 1.57%   |
| Unknown        | 39        | 1.27%   |
| 64-bit         | 1         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 764       | 23.96%  |
| 0x206a7    | 202       | 6.34%   |
| 0x306a9    | 196       | 6.15%   |
| 0x1067a    | 117       | 3.67%   |
| 0x40651    | 104       | 3.26%   |
| 0x306c3    | 88        | 2.76%   |
| 0x20655    | 88        | 2.76%   |
| 0x906ea    | 87        | 2.73%   |
| 0x806ec    | 86        | 2.7%    |
| 0x306d4    | 84        | 2.63%   |
| 0x806c1    | 82        | 2.57%   |
| 0x30678    | 81        | 2.54%   |
| 0x406e3    | 78        | 2.45%   |
| 0x806ea    | 75        | 2.35%   |
| 0x6fd      | 71        | 2.23%   |
| 0x806e9    | 63        | 1.98%   |
| 0x506e3    | 54        | 1.69%   |
| 0x10676    | 52        | 1.63%   |
| 0x0a50000c | 48        | 1.51%   |
| 0x906e9    | 44        | 1.38%   |
| 0x08600106 | 39        | 1.22%   |
| 0xa0652    | 33        | 1.04%   |
| 0x20652    | 32        | 1%      |
| 0x08108102 | 28        | 0.88%   |
| 0x08108109 | 27        | 0.85%   |
| 0x806eb    | 25        | 0.78%   |
| 0x706e5    | 22        | 0.69%   |
| 0x08600103 | 20        | 0.63%   |
| 0x6fb      | 19        | 0.6%    |
| 0x08600104 | 19        | 0.6%    |
| 0x906ed    | 18        | 0.56%   |
| 0x906a3    | 18        | 0.56%   |
| 0x806d1    | 18        | 0.56%   |
| 0x6f6      | 18        | 0.56%   |
| 0x06001119 | 18        | 0.56%   |
| 0x506c9    | 16        | 0.5%    |
| 0x406c4    | 16        | 0.5%    |
| 0x106ca    | 16        | 0.5%    |
| 0x406c3    | 15        | 0.47%   |
| 0x106c2    | 14        | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 521       | 17.01%  |
| SandyBridge      | 252       | 8.23%   |
| Haswell          | 251       | 8.19%   |
| IvyBridge        | 249       | 8.13%   |
| Penryn           | 195       | 6.37%   |
| Skylake          | 176       | 5.75%   |
| Core             | 149       | 4.86%   |
| Westmere         | 140       | 4.57%   |
| Silvermont       | 136       | 4.44%   |
| Broadwell        | 115       | 3.75%   |
| Zen 2            | 107       | 3.49%   |
| TigerLake        | 107       | 3.49%   |
| Unknown          | 84        | 2.74%   |
| Zen+             | 70        | 2.29%   |
| Zen 3            | 70        | 2.29%   |
| CometLake        | 46        | 1.5%    |
| IceLake          | 44        | 1.44%   |
| Alderlake Hybrid | 40        | 1.31%   |
| Bobcat           | 35        | 1.14%   |
| Bonnell          | 34        | 1.11%   |
| P6               | 32        | 1.04%   |
| Piledriver       | 25        | 0.82%   |
| Goldmont plus    | 24        | 0.78%   |
| Zen              | 23        | 0.75%   |
| Goldmont         | 21        | 0.69%   |
| Excavator        | 21        | 0.69%   |
| Puma             | 16        | 0.52%   |
| K8 & K10 hybrid  | 16        | 0.52%   |
| K8 Hammer        | 14        | 0.46%   |
| K10              | 13        | 0.42%   |
| K10 Llano        | 12        | 0.39%   |
| Jaguar           | 12        | 0.39%   |
| Nehalem          | 7         | 0.23%   |
| Steamroller      | 4         | 0.13%   |
| Tremont          | 2         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2286      | 57.42%  |
| Nvidia                           | 948       | 23.81%  |
| AMD                              | 734       | 18.44%  |
| VIA Technologies                 | 7         | 0.18%   |
| Silicon Integrated Systems [SiS] | 6         | 0.15%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 240       | 5.78%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 233       | 5.62%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 133       | 3.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 114       | 2.75%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 113       | 2.72%   |
| Intel UHD Graphics 620                                                                   | 106       | 2.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 104       | 2.51%   |
| Intel HD Graphics 5500                                                                   | 102       | 2.46%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 100       | 2.41%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 98        | 2.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 97        | 2.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 95        | 2.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 95        | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 81        | 1.95%   |
| Intel HD Graphics 620                                                                    | 79        | 1.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 75        | 1.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 75        | 1.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 71        | 1.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 59        | 1.42%   |
| Intel HD Graphics 530                                                                    | 59        | 1.42%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 58        | 1.4%    |
| Intel HD Graphics 630                                                                    | 56        | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 54        | 1.3%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 50        | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 47        | 1.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 43        | 1.04%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 41        | 0.99%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 40        | 0.96%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 39        | 0.94%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 35        | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 32        | 0.77%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 28        | 0.67%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 28        | 0.67%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 27        | 0.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 26        | 0.63%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 25        | 0.6%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 25        | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 24        | 0.58%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 24        | 0.58%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 23        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1447      | 47.04%  |
| Intel + Nvidia           | 652       | 21.2%   |
| 1 x AMD                  | 418       | 13.59%  |
| 1 x Nvidia               | 202       | 6.57%   |
| Intel + AMD              | 171       | 5.56%   |
| AMD + Nvidia             | 93        | 3.02%   |
| 2 x AMD                  | 50        | 1.63%   |
| 2 x Intel                | 21        | 0.68%   |
| Other                    | 7         | 0.23%   |
| 1 x VIA                  | 7         | 0.23%   |
| 1 x SiS                  | 6         | 0.2%    |
| 2 x Nvidia               | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2592      | 83.48%  |
| Proprietary | 433       | 13.95%  |
| Unknown     | 80        | 2.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1877      | 59.72%  |
| 1.01-2.0   | 404       | 12.85%  |
| 0.01-0.5   | 400       | 12.73%  |
| 0.51-1.0   | 194       | 6.17%   |
| 3.01-4.0   | 188       | 5.98%   |
| 5.01-6.0   | 52        | 1.65%   |
| 7.01-8.0   | 19        | 0.6%    |
| 2.01-3.0   | 5         | 0.16%   |
| 8.01-16.0  | 4         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 630       | 17.87%  |
| LG Display              | 540       | 15.32%  |
| Samsung Electronics     | 435       | 12.34%  |
| BOE                     | 422       | 11.97%  |
| Chimei Innolux          | 386       | 10.95%  |
| Dell                    | 130       | 3.69%   |
| Chi Mei Optoelectronics | 112       | 3.18%   |
| Lenovo                  | 103       | 2.92%   |
| Goldstar                | 69        | 1.96%   |
| Iiyama                  | 63        | 1.79%   |
| Sharp                   | 56        | 1.59%   |
| PANDA                   | 48        | 1.36%   |
| LG Philips              | 47        | 1.33%   |
| Philips                 | 36        | 1.02%   |
| BenQ                    | 36        | 1.02%   |
| InfoVision              | 33        | 0.94%   |
| AOC                     | 28        | 0.79%   |
| Apple                   | 26        | 0.74%   |
| Acer                    | 25        | 0.71%   |
| Hewlett-Packard         | 24        | 0.68%   |
| NEC Computers           | 21        | 0.6%    |
| Ancor Communications    | 17        | 0.48%   |
| Valve                   | 16        | 0.45%   |
| HannStar                | 16        | 0.45%   |
| CSO                     | 16        | 0.45%   |
| CPT                     | 16        | 0.45%   |
| Eizo                    | 15        | 0.43%   |
| Toshiba                 | 9         | 0.26%   |
| Mi                      | 9         | 0.26%   |
| LGD                     | 9         | 0.26%   |
| ASUSTek Computer        | 9         | 0.26%   |
| TMX                     | 8         | 0.23%   |
| Sony                    | 8         | 0.23%   |
| Seiko/Epson             | 8         | 0.23%   |
| MSI                     | 8         | 0.23%   |
| Panasonic               | 6         | 0.17%   |
| InnoLux Display         | 6         | 0.17%   |
| Fujitsu Siemens         | 6         | 0.17%   |
| IBM                     | 5         | 0.14%   |
| Vestel Elektronik       | 4         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 32        | 0.89%   |
| BOE LCD Monitor BOE0629 1366x768 309x173mm 13.9-inch                     | 31        | 0.86%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 28        | 0.78%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 26        | 0.72%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 26        | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 25        | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 25        | 0.69%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 20        | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 19        | 0.53%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 17        | 0.47%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 17        | 0.47%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 17        | 0.47%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 16        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 16        | 0.44%   |
| BOE LCD Monitor BOE06FB 1920x1080 344x194mm 15.5-inch                    | 16        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 15        | 0.42%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 15        | 0.42%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 14        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 14        | 0.39%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 14        | 0.39%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 13        | 0.36%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 13        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 13        | 0.36%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 13        | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 13        | 0.36%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 12        | 0.33%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 12        | 0.33%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 12        | 0.33%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 11        | 0.31%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 11        | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 11        | 0.31%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 10        | 0.28%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 10        | 0.28%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 10        | 0.28%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 10        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 10        | 0.28%   |
| BOE LCD Monitor BOE06E2 1920x1080 309x173mm 13.9-inch                    | 10        | 0.28%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch           | 10        | 0.28%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 10        | 0.28%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1358      | 41.54%  |
| 1366x768 (WXGA)    | 862       | 26.37%  |
| 1600x900 (HD+)     | 220       | 6.73%   |
| 1280x800 (WXGA)    | 193       | 5.9%    |
| 3840x2160 (4K)     | 100       | 3.06%   |
| 2560x1440 (QHD)    | 97        | 2.97%   |
| 1920x1200 (WUXGA)  | 81        | 2.48%   |
| 1440x900 (WXGA+)   | 72        | 2.2%    |
| 1680x1050 (WSXGA+) | 52        | 1.59%   |
| 1024x600           | 27        | 0.83%   |
| 2560x1600          | 25        | 0.76%   |
| 3440x1440          | 23        | 0.7%    |
| 1280x1024 (SXGA)   | 22        | 0.67%   |
| 800x1280           | 19        | 0.58%   |
| 2560x1080          | 12        | 0.37%   |
| 2160x1440          | 12        | 0.37%   |
| 3840x2400          | 11        | 0.34%   |
| 2880x1800          | 11        | 0.34%   |
| Unknown            | 10        | 0.31%   |
| 1024x768 (XGA)     | 7         | 0.21%   |
| 3200x1800 (QHD+)   | 5         | 0.15%   |
| 3840x1080          | 4         | 0.12%   |
| 3200x2000          | 4         | 0.12%   |
| 1680x945           | 4         | 0.12%   |
| 3286x1080          | 3         | 0.09%   |
| 2288x1287          | 3         | 0.09%   |
| 1400x1050          | 3         | 0.09%   |
| 1280x768           | 3         | 0.09%   |
| 3840x1600          | 2         | 0.06%   |
| 3456x2160          | 2         | 0.06%   |
| 3000x2000          | 2         | 0.06%   |
| 2520x1680          | 2         | 0.06%   |
| 2256x1504          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 1920x540           | 2         | 0.06%   |
| 1600x1200          | 2         | 0.06%   |
| 1360x768           | 2         | 0.06%   |
| 1280x720 (HD)      | 2         | 0.06%   |
| 6400x1600          | 1         | 0.03%   |
| 5120x1600          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1499      | 42.46%  |
| 13      | 415       | 11.76%  |
| 14      | 388       | 10.99%  |
| 17      | 268       | 7.59%   |
| 24      | 151       | 4.28%   |
| 23      | 115       | 3.26%   |
| 12      | 109       | 3.09%   |
| 27      | 106       | 3%      |
| 21      | 74        | 2.1%    |
| Unknown | 56        | 1.59%   |
| 11      | 51        | 1.44%   |
| 34      | 38        | 1.08%   |
| 16      | 34        | 0.96%   |
| 10      | 29        | 0.82%   |
| 19      | 25        | 0.71%   |
| 22      | 24        | 0.68%   |
| 18      | 24        | 0.68%   |
| 31      | 18        | 0.51%   |
| 7       | 16        | 0.45%   |
| 25      | 11        | 0.31%   |
| 48      | 10        | 0.28%   |
| 20      | 10        | 0.28%   |
| 40      | 9         | 0.25%   |
| 84      | 8         | 0.23%   |
| 72      | 5         | 0.14%   |
| 32      | 5         | 0.14%   |
| 3       | 5         | 0.14%   |
| 43      | 4         | 0.11%   |
| 37      | 3         | 0.08%   |
| 28      | 3         | 0.08%   |
| 142     | 2         | 0.06%   |
| 65      | 2         | 0.06%   |
| 46      | 2         | 0.06%   |
| 26      | 2         | 0.06%   |
| 86      | 1         | 0.03%   |
| 60      | 1         | 0.03%   |
| 54      | 1         | 0.03%   |
| 52      | 1         | 0.03%   |
| 49      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2096      | 60.2%   |
| 201-300        | 364       | 10.45%  |
| 501-600        | 348       | 9.99%   |
| 351-400        | 329       | 9.45%   |
| 401-500        | 142       | 4.08%   |
| Unknown        | 56        | 1.61%   |
| 701-800        | 44        | 1.26%   |
| 601-700        | 31        | 0.89%   |
| 1-100          | 20        | 0.57%   |
| 1001-1500      | 19        | 0.55%   |
| 801-900        | 13        | 0.37%   |
| 1501-2000      | 13        | 0.37%   |
| 901-1000       | 4         | 0.11%   |
| More than 2000 | 2         | 0.06%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2472      | 79.84%  |
| 16/10   | 435       | 14.05%  |
| Unknown | 46        | 1.49%   |
| 21/9    | 40        | 1.29%   |
| 3/2     | 37        | 1.2%    |
| 5/4     | 24        | 0.78%   |
| 0.67    | 16        | 0.52%   |
| 4/3     | 14        | 0.45%   |
| 6/5     | 5         | 0.16%   |
| 32/9    | 3         | 0.1%    |
| 1.00    | 2         | 0.06%   |
| 0.62    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1496      | 42.57%  |
| 81-90          | 655       | 18.64%  |
| 201-250        | 279       | 7.94%   |
| 121-130        | 212       | 6.03%   |
| 71-80          | 139       | 3.96%   |
| 61-70          | 108       | 3.07%   |
| 301-350        | 108       | 3.07%   |
| 251-300        | 75        | 2.13%   |
| 351-500        | 63        | 1.79%   |
| Unknown        | 56        | 1.59%   |
| 51-60          | 51        | 1.45%   |
| 131-140        | 50        | 1.42%   |
| 151-200        | 47        | 1.34%   |
| 141-150        | 31        | 0.88%   |
| More than 1000 | 29        | 0.83%   |
| 41-50          | 29        | 0.83%   |
| 111-120        | 24        | 0.68%   |
| 1-40           | 21        | 0.6%    |
| 501-1000       | 21        | 0.6%    |
| 91-100         | 20        | 0.57%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1425      | 41.32%  |
| 101-120       | 998       | 28.94%  |
| 51-100        | 679       | 19.69%  |
| 161-240       | 187       | 5.42%   |
| More than 240 | 77        | 2.23%   |
| Unknown       | 56        | 1.62%   |
| 1-50          | 27        | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2485      | 78.64%  |
| 2     | 517       | 16.36%  |
| 3     | 74        | 2.34%   |
| 0     | 73        | 2.31%   |
| 4     | 9         | 0.28%   |
| 6     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1766      | 35.14%  |
| Realtek Semiconductor             | 1447      | 28.79%  |
| Qualcomm Atheros                  | 732       | 14.56%  |
| Broadcom                          | 339       | 6.74%   |
| Broadcom Limited                  | 100       | 1.99%   |
| Dell                              | 83        | 1.65%   |
| Marvell Technology Group          | 69        | 1.37%   |
| Huawei Technologies               | 61        | 1.21%   |
| MediaTek                          | 57        | 1.13%   |
| Ralink                            | 38        | 0.76%   |
| TP-Link                           | 32        | 0.64%   |
| Ericsson Business Mobile Networks | 31        | 0.62%   |
| Samsung Electronics               | 25        | 0.5%    |
| Hewlett-Packard                   | 24        | 0.48%   |
| Sierra Wireless                   | 19        | 0.38%   |
| Xiaomi                            | 18        | 0.36%   |
| ASIX Electronics                  | 18        | 0.36%   |
| JMicron Technology                | 17        | 0.34%   |
| Lenovo                            | 14        | 0.28%   |
| Ralink Technology                 | 12        | 0.24%   |
| Nvidia                            | 12        | 0.24%   |
| Qualcomm Atheros Communications   | 10        | 0.2%    |
| Fibocom                           | 10        | 0.2%    |
| DisplayLink                       | 10        | 0.2%    |
| Silicon Integrated Systems [SiS]  | 9         | 0.18%   |
| Qualcomm                          | 8         | 0.16%   |
| ASUSTek Computer                  | 8         | 0.16%   |
| ZTE WCDMA Technologies MSM        | 7         | 0.14%   |
| VIA Technologies                  | 5         | 0.1%    |
| NetGear                           | 5         | 0.1%    |
| Motorola PCS                      | 5         | 0.1%    |
| Attansic Technology               | 4         | 0.08%   |
| Microsoft                         | 3         | 0.06%   |
| HTC (High Tech Computer)          | 3         | 0.06%   |
| Sigma Designs                     | 2         | 0.04%   |
| Edimax Technology                 | 2         | 0.04%   |
| Unknown                           | 2         | 0.04%   |
| Uniden                            | 1         | 0.02%   |
| Toshiba                           | 1         | 0.02%   |
| Texas Instruments                 | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 943       | 15.47%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 249       | 4.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 166       | 2.72%   |
| Intel Wireless 8265 / 8275                                              | 136       | 2.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 129       | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 122       | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 118       | 1.94%   |
| Intel Wi-Fi 6 AX200                                                     | 114       | 1.87%   |
| Intel Wireless 7260                                                     | 105       | 1.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 104       | 1.71%   |
| Intel Wireless 8260                                                     | 96        | 1.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 89        | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 1.41%   |
| Intel Wi-Fi 6 AX201                                                     | 84        | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 84        | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 83        | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 81        | 1.33%   |
| Intel Wireless 7265                                                     | 75        | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 1.23%   |
| Intel Wireless 3160                                                     | 67        | 1.1%    |
| Intel Wireless 3165                                                     | 58        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 57        | 0.94%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 56        | 0.92%   |
| Intel 82567LM Gigabit Network Connection                                | 56        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 54        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 51        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                                   | 50        | 0.82%   |
| Intel Centrino Ultimate-N 6300                                          | 50        | 0.82%   |
| Intel WiFi Link 5100                                                    | 46        | 0.75%   |
| Intel Ethernet Connection I218-LM                                       | 46        | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 45        | 0.74%   |
| Intel Ethernet Connection I217-LM                                       | 42        | 0.69%   |
| Intel 82577LM Gigabit Network Connection                                | 42        | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 41        | 0.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 41        | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 40        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 40        | 0.66%   |
| Intel Centrino Advanced-N 6235                                          | 38        | 0.62%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 37        | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1681      | 52.27%  |
| Qualcomm Atheros                  | 610       | 18.97%  |
| Realtek Semiconductor             | 366       | 11.38%  |
| Broadcom                          | 237       | 7.37%   |
| Broadcom Limited                  | 56        | 1.74%   |
| MediaTek                          | 54        | 1.68%   |
| Dell                              | 52        | 1.62%   |
| Ralink                            | 38        | 1.18%   |
| TP-Link                           | 28        | 0.87%   |
| Sierra Wireless                   | 19        | 0.59%   |
| Ralink Technology                 | 12        | 0.37%   |
| Qualcomm Atheros Communications   | 10        | 0.31%   |
| Fibocom                           | 10        | 0.31%   |
| Ericsson Business Mobile Networks | 9         | 0.28%   |
| ASUSTek Computer                  | 8         | 0.25%   |
| Qualcomm                          | 6         | 0.19%   |
| Hewlett-Packard                   | 6         | 0.19%   |
| Microsoft                         | 3         | 0.09%   |
| NetGear                           | 2         | 0.06%   |
| Edimax Technology                 | 2         | 0.06%   |
| Unknown                           | 2         | 0.06%   |
| Tenda                             | 1         | 0.03%   |
| Sweex                             | 1         | 0.03%   |
| Sagem                             | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| Belkin Components                 | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 136       | 4.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 129       | 4.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 122       | 3.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 118       | 3.66%   |
| Intel Wi-Fi 6 AX200                                                     | 114       | 3.54%   |
| Intel Wireless 7260                                                     | 105       | 3.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 104       | 3.23%   |
| Intel Wireless 8260                                                     | 96        | 2.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 89        | 2.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 86        | 2.67%   |
| Intel Wi-Fi 6 AX201                                                     | 84        | 2.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 84        | 2.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 81        | 2.52%   |
| Intel Wireless 7265                                                     | 75        | 2.33%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 75        | 2.33%   |
| Intel Wireless 3160                                                     | 67        | 2.08%   |
| Intel Wireless 3165                                                     | 58        | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 57        | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 56        | 1.74%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 54        | 1.68%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 51        | 1.58%   |
| Intel Centrino Ultimate-N 6300                                          | 50        | 1.55%   |
| Intel WiFi Link 5100                                                    | 46        | 1.43%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 45        | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 41        | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 41        | 1.27%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 40        | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 40        | 1.24%   |
| Intel Centrino Advanced-N 6235                                          | 38        | 1.18%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 37        | 1.15%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 36        | 1.12%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 1.02%   |
| Intel Centrino Advanced-N 6200                                          | 33        | 1.02%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 31        | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 31        | 0.96%   |
| Intel Centrino Wireless-N 2230                                          | 29        | 0.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 24        | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 24        | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 22        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1302      | 47.36%  |
| Intel                            | 766       | 27.86%  |
| Qualcomm Atheros                 | 219       | 7.97%   |
| Broadcom                         | 141       | 5.13%   |
| Marvell Technology Group         | 69        | 2.51%   |
| Broadcom Limited                 | 45        | 1.64%   |
| Huawei Technologies              | 43        | 1.56%   |
| Samsung Electronics              | 23        | 0.84%   |
| ASIX Electronics                 | 18        | 0.65%   |
| Xiaomi                           | 17        | 0.62%   |
| JMicron Technology               | 17        | 0.62%   |
| Lenovo                           | 14        | 0.51%   |
| Nvidia                           | 12        | 0.44%   |
| DisplayLink                      | 10        | 0.36%   |
| Silicon Integrated Systems [SiS] | 9         | 0.33%   |
| ZTE WCDMA Technologies MSM       | 6         | 0.22%   |
| VIA Technologies                 | 5         | 0.18%   |
| Motorola PCS                     | 5         | 0.18%   |
| TP-Link                          | 4         | 0.15%   |
| Hewlett-Packard                  | 4         | 0.15%   |
| Attansic Technology              | 4         | 0.15%   |
| NetGear                          | 3         | 0.11%   |
| HTC (High Tech Computer)         | 3         | 0.11%   |
| Qualcomm                         | 2         | 0.07%   |
| MediaTek                         | 2         | 0.07%   |
| QinHeng Electronics              | 1         | 0.04%   |
| OPPO Electronics                 | 1         | 0.04%   |
| LG Electronics                   | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 943       | 34.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 249       | 9%      |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 166       | 6%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 83        | 3%      |
| Intel 82567LM Gigabit Network Connection                          | 56        | 2.02%   |
| Intel Ethernet Connection (4) I219-LM                             | 50        | 1.81%   |
| Intel Ethernet Connection I218-LM                                 | 46        | 1.66%   |
| Intel Ethernet Connection I217-LM                                 | 42        | 1.52%   |
| Intel 82577LM Gigabit Network Connection                          | 42        | 1.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 37        | 1.34%   |
| Huawei E353/E3131                                                 | 37        | 1.34%   |
| Intel Ethernet Connection I219-LM                                 | 32        | 1.16%   |
| Intel Ethernet Connection (6) I219-V                              | 32        | 1.16%   |
| Intel Ethernet Connection (3) I218-LM                             | 31        | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 26        | 0.94%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 25        | 0.9%    |
| Intel Ethernet Connection (4) I219-V                              | 24        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 0.83%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 22        | 0.8%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 0.76%   |
| Intel 82579V Gigabit Network Connection                           | 20        | 0.72%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 17        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 17        | 0.61%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 17        | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 16        | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 16        | 0.58%   |
| Intel Ethernet Connection I219-V                                  | 16        | 0.58%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 15        | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.54%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 14        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 14        | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 14        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 14        | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 14        | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                             | 14        | 0.51%   |
| Intel Ethernet Connection (11) I219-LM                            | 14        | 0.51%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14        | 0.51%   |
| Intel 82566MM Gigabit Network Connection                          | 13        | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3018      | 52.44%  |
| Ethernet | 2630      | 45.7%   |
| Modem    | 100       | 1.74%   |
| Unknown  | 7         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2480      | 77.84%  |
| Ethernet | 706       | 22.16%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2459      | 80.23%  |
| 1     | 557       | 18.17%  |
| 0     | 38        | 1.24%   |
| 3     | 11        | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2846      | 92.07%  |
| Yes  | 245       | 7.93%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1140      | 47.48%  |
| Qualcomm Atheros Communications | 250       | 10.41%  |
| Realtek Semiconductor           | 184       | 7.66%   |
| Broadcom                        | 174       | 7.25%   |
| IMC Networks                    | 131       | 5.46%   |
| Dell                            | 89        | 3.71%   |
| Foxconn / Hon Hai               | 83        | 3.46%   |
| Lite-On Technology              | 74        | 3.08%   |
| Hewlett-Packard                 | 63        | 2.62%   |
| Toshiba                         | 31        | 1.29%   |
| ASUSTek Computer                | 31        | 1.29%   |
| Cambridge Silicon Radio         | 28        | 1.17%   |
| Apple                           | 25        | 1.04%   |
| Ralink                          | 21        | 0.87%   |
| Foxconn International           | 18        | 0.75%   |
| Realtek                         | 15        | 0.62%   |
| Alps Electric                   | 8         | 0.33%   |
| Chicony Electronics             | 6         | 0.25%   |
| Taiyo Yuden                     | 5         | 0.21%   |
| MediaTek                        | 5         | 0.21%   |
| Ralink Technology               | 3         | 0.12%   |
| Integrated System Solution      | 3         | 0.12%   |
| USI                             | 2         | 0.08%   |
| Opticis                         | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| Askey Computer                  | 2         | 0.08%   |
| TP-Link                         | 1         | 0.04%   |
| Fujitsu                         | 1         | 0.04%   |
| Edimax Technology               | 1         | 0.04%   |
| Creative Technology             | 1         | 0.04%   |
| AboCom Systems                  | 1         | 0.04%   |
| Unknown                         | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 528       | 21.98%  |
| Intel AX201 Bluetooth                               | 177       | 7.37%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 148       | 6.16%   |
| Realtek Bluetooth Radio                             | 117       | 4.87%   |
| Qualcomm Atheros  Bluetooth Device                  | 110       | 4.58%   |
| Intel AX200 Bluetooth                               | 108       | 4.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 64        | 2.66%   |
| Intel Bluetooth Device                              | 57        | 2.37%   |
| IMC Networks Bluetooth Radio                        | 57        | 2.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 56        | 2.33%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 43        | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 1.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 37        | 1.54%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 35        | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 1.29%   |
| Dell BCM20702A0 Bluetooth Module                    | 29        | 1.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 28        | 1.17%   |
| HP Broadcom 2070 Bluetooth Combo                    | 27        | 1.12%   |
| Dell DW375 Bluetooth Module                         | 25        | 1.04%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 25        | 1.04%   |
| IMC Networks Wireless_Device                        | 24        | 1%      |
| IMC Networks Bluetooth Device                       | 24        | 1%      |
| Lite-On Bluetooth Device                            | 22        | 0.92%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.87%   |
| Realtek RTL8723B Bluetooth                          | 20        | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 0.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 0.79%   |
| Foxconn International BCM43142A0 Bluetooth module   | 18        | 0.75%   |
| Broadcom BCM2070 Bluetooth Device                   | 18        | 0.75%   |
| Lite-On Atheros AR3012 Bluetooth                    | 17        | 0.71%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 16        | 0.67%   |
| Realtek Bluetooth Radio                             | 15        | 0.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 0.62%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 0.62%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 14        | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 13        | 0.54%   |
| Intel AX210 Bluetooth                               | 13        | 0.54%   |
| Broadcom HP Portable SoftSailing                    | 13        | 0.54%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 13        | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 2506      | 66.38%  |
| AMD                                          | 562       | 14.89%  |
| Nvidia                                       | 480       | 12.72%  |
| C-Media Electronics                          | 24        | 0.64%   |
| Lenovo                                       | 18        | 0.48%   |
| Creative Technology                          | 18        | 0.48%   |
| Realtek Semiconductor                        | 17        | 0.45%   |
| Logitech                                     | 13        | 0.34%   |
| GN Netcom                                    | 13        | 0.34%   |
| Plantronics                                  | 12        | 0.32%   |
| Silicon Integrated Systems [SiS]             | 11        | 0.29%   |
| Hewlett-Packard                              | 9         | 0.24%   |
| VIA Technologies                             | 7         | 0.19%   |
| SteelSeries ApS                              | 6         | 0.16%   |
| JMTek                                        | 6         | 0.16%   |
| Generalplus Technology                       | 6         | 0.16%   |
| Dell                                         | 6         | 0.16%   |
| Texas Instruments                            | 5         | 0.13%   |
| Focusrite-Novation                           | 4         | 0.11%   |
| Sennheiser Communications                    | 3         | 0.08%   |
| Samson Technologies                          | 3         | 0.08%   |
| Kingston Technology                          | 3         | 0.08%   |
| BEHRINGER International                      | 3         | 0.08%   |
| ASUSTek Computer                             | 3         | 0.08%   |
| TTGK Technology                              | 2         | 0.05%   |
| Sony                                         | 2         | 0.05%   |
| M-Audio                                      | 2         | 0.05%   |
| DSEA A/S                                     | 2         | 0.05%   |
| DCMT Technology                              | 2         | 0.05%   |
| AudioQuest                                   | 2         | 0.05%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.03%   |
| Yamaha                                       | 1         | 0.03%   |
| Turtle Beach                                 | 1         | 0.03%   |
| THX                                          | 1         | 0.03%   |
| Thesycon Systemsoftware & Consulting         | 1         | 0.03%   |
| Silicon Motion                               | 1         | 0.03%   |
| SAVITECH                                     | 1         | 0.03%   |
| RODE Microphones                             | 1         | 0.03%   |
| Razer USA                                    | 1         | 0.03%   |
| OS AS700 USB                                 | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 301       | 6.67%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 298       | 6.61%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 292       | 6.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 207       | 4.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 181       | 4.01%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 147       | 3.26%   |
| Intel 8 Series HD Audio Controller                                                                | 139       | 3.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 138       | 3.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 138       | 3.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 137       | 3.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 117       | 2.59%   |
| Intel Broadwell-U Audio Controller                                                                | 115       | 2.55%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 114       | 2.53%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 113       | 2.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 107       | 2.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 102       | 2.26%   |
| AMD FCH Azalia Controller                                                                         | 87        | 1.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 85        | 1.88%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 82        | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 78        | 1.73%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 74        | 1.64%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 74        | 1.64%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 65        | 1.44%   |
| Intel CM238 HD Audio Controller                                                                   | 63        | 1.4%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 57        | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 49        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 47        | 1.04%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 47        | 1.04%   |
| Intel Comet Lake PCH cAVS                                                                         | 44        | 0.98%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 41        | 0.91%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 38        | 0.84%   |
| AMD Kabini HDMI/DP Audio                                                                          | 35        | 0.78%   |
| AMD Wrestler HDMI Audio                                                                           | 33        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 30        | 0.67%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 28        | 0.62%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 27        | 0.6%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 27        | 0.6%    |
| Nvidia GT216 HDMI Audio Controller                                                                | 26        | 0.58%   |
| Nvidia Audio device                                                                               | 26        | 0.58%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 25        | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 689       | 28.3%   |
| SK hynix                     | 504       | 20.7%   |
| Micron Technology            | 273       | 11.21%  |
| Kingston                     | 246       | 10.1%   |
| Unknown                      | 172       | 7.06%   |
| GOODRAM                      | 124       | 5.09%   |
| Crucial                      | 99        | 4.07%   |
| Ramaxel Technology           | 64        | 2.63%   |
| A-DATA Technology            | 52        | 2.14%   |
| Nanya Technology             | 41        | 1.68%   |
| Elpida                       | 40        | 1.64%   |
| Patriot                      | 18        | 0.74%   |
| Unknown                      | 15        | 0.62%   |
| Unknown (ABCD)               | 14        | 0.57%   |
| Corsair                      | 11        | 0.45%   |
| Qimonda                      | 10        | 0.41%   |
| Wilk                         | 9         | 0.37%   |
| ASint Technology             | 7         | 0.29%   |
| G.Skill                      | 5         | 0.21%   |
| fef5                         | 4         | 0.16%   |
| 48spaces                     | 4         | 0.16%   |
| Unifosa                      | 3         | 0.12%   |
| Transcend                    | 3         | 0.12%   |
| Apacer                       | 3         | 0.12%   |
| Toshiba                      | 2         | 0.08%   |
| SHARETRONIC                  | 2         | 0.08%   |
| Patriot Memory (PDP Systems) | 2         | 0.08%   |
| ff                           | 2         | 0.08%   |
| ChangXin Memory              | 2         | 0.08%   |
| 4ea5                         | 2         | 0.08%   |
| Unknown (8A02)               | 1         | 0.04%   |
| Unknown (768A)               | 1         | 0.04%   |
| Team                         | 1         | 0.04%   |
| Swissbit                     | 1         | 0.04%   |
| Smart                        | 1         | 0.04%   |
| Silicon Power                | 1         | 0.04%   |
| PUSKILL                      | 1         | 0.04%   |
| PNY                          | 1         | 0.04%   |
| Lexar                        | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 1.42%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 37        | 1.42%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 31        | 1.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 30        | 1.15%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 29        | 1.11%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 1.07%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 1.03%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 26        | 1%      |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 1%      |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 26        | 1%      |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 0.92%   |
| GOODRAM RAM GR2666S464L19/16G 16GB SODIMM DDR4 2667MT/s          | 24        | 0.92%   |
| GOODRAM RAM GR3200S464L22/16G 16GB SODIMM DDR4 3200MT/s          | 22        | 0.84%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 21        | 0.8%    |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 21        | 0.8%    |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 17        | 0.65%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 17        | 0.65%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 0.65%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 16        | 0.61%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.61%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 16        | 0.61%   |
| Kingston RAM KHX1600C9S3L/8G 8GB SODIMM DDR3 1600MT/s            | 16        | 0.61%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 15        | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 15        | 0.57%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 15        | 0.57%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 15        | 0.57%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 15        | 0.57%   |
| Unknown                                                          | 15        | 0.57%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.54%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.54%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 14        | 0.54%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 13        | 0.5%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 13        | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 13        | 0.5%    |
| Samsung RAM M471B5273EB0-CK0 4GB SODIMM DDR3 4199MT/s            | 13        | 0.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 12        | 0.46%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 12        | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.46%   |
| Kingston RAM KHX2400C14S4/16G 16GB SODIMM DDR4 2667MT/s          | 12        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 797       | 39.85%  |
| DDR3    | 772       | 38.6%   |
| DDR2    | 170       | 8.5%    |
| SDRAM   | 81        | 4.05%   |
| LPDDR4  | 72        | 3.6%    |
| LPDDR3  | 38        | 1.9%    |
| DDR5    | 20        | 1%      |
| Unknown | 18        | 0.9%    |
| LPDDR5  | 16        | 0.8%    |
| DDR     | 11        | 0.55%   |
| DRAM    | 5         | 0.25%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1823      | 92.82%  |
| Row Of Chips    | 107       | 5.45%   |
| Unknown         | 13        | 0.66%   |
| Chip            | 11        | 0.56%   |
| DIMM            | 9         | 0.46%   |
| Proprietary Car | 1         | 0.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 715       | 32.37%  |
| 4096    | 653       | 29.56%  |
| 2048    | 335       | 15.17%  |
| 16384   | 323       | 14.62%  |
| 1024    | 120       | 5.43%   |
| 32768   | 46        | 2.08%   |
| 512     | 10        | 0.45%   |
| Unknown | 4         | 0.18%   |
| 131072  | 1         | 0.05%   |
| 1536    | 1         | 0.05%   |
| 256     | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 563       | 25.79%  |
| 2667    | 381       | 17.45%  |
| 3200    | 325       | 14.89%  |
| 1334    | 138       | 6.32%   |
| 2400    | 123       | 5.63%   |
| 2133    | 95        | 4.35%   |
| 667     | 84        | 3.85%   |
| 1333    | 75        | 3.44%   |
| Unknown | 55        | 2.52%   |
| 4199    | 46        | 2.11%   |
| 1067    | 41        | 1.88%   |
| 800     | 39        | 1.79%   |
| 2048    | 28        | 1.28%   |
| 975     | 28        | 1.28%   |
| 533     | 23        | 1.05%   |
| 4267    | 22        | 1.01%   |
| 4800    | 20        | 0.92%   |
| 6400    | 16        | 0.73%   |
| 3266    | 16        | 0.73%   |
| 1867    | 14        | 0.64%   |
| 8400    | 11        | 0.5%    |
| 1066    | 10        | 0.46%   |
| 4266    | 7         | 0.32%   |
| 3733    | 6         | 0.27%   |
| 400     | 4         | 0.18%   |
| 333     | 4         | 0.18%   |
| 2933    | 3         | 0.14%   |
| 5600    | 1         | 0.05%   |
| 2134    | 1         | 0.05%   |
| 1777    | 1         | 0.05%   |
| 1776    | 1         | 0.05%   |
| 1639    | 1         | 0.05%   |
| 933     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 44%     |
| Samsung Electronics   | 5         | 20%     |
| Canon                 | 3         | 12%     |
| Seiko Epson           | 2         | 8%      |
| Zebra                 | 1         | 4%      |
| Xerox                 | 1         | 4%      |
| Lexmark International | 1         | 4%      |
| Brother Industries    | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung M2020 Series                    | 2         | 8%      |
| HP Deskjet F2280 series                 | 2         | 8%      |
| Zebra ZTC GX420t                        | 1         | 4%      |
| Xerox Phaser 6000B                      | 1         | 4%      |
| Seiko Epson ET-2600 Series              | 1         | 4%      |
| Seiko Epson AL-M310DN                   | 1         | 4%      |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4%      |
| Samsung SCX-6545 Series                 | 1         | 4%      |
| Samsung SCX-3400 Series                 | 1         | 4%      |
| Lexmark International E260dn            | 1         | 4%      |
| HP LaserJet P1102                       | 1         | 4%      |
| HP LaserJet P1005                       | 1         | 4%      |
| HP LaserJet 1020                        | 1         | 4%      |
| HP LaserJet 1018                        | 1         | 4%      |
| HP Ink Tank Wireless 410 series         | 1         | 4%      |
| HP Deskjet Ink Advant K209a-z           | 1         | 4%      |
| HP Deskjet D1500 series                 | 1         | 4%      |
| HP Deskjet 3540 series                  | 1         | 4%      |
| HP Deskjet 2540 series                  | 1         | 4%      |
| Canon PIXMA MG5600 Series               | 1         | 4%      |
| Canon PIXMA MG3000 series               | 1         | 4%      |
| Canon LiDE 400                          | 1         | 4%      |
| Brother DCP-1610W                       | 1         | 4%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Canon                  | 2         | 50%     |
| Plustek                | 1         | 25%     |
| Microtek International | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Plustek OpticSlim 1200 Scanner         | 1         | 25%     |
| Microtek International USB1200 Scanner | 1         | 25%     |
| Canon CanoScan N670U/N676U/LiDE 20     | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30          | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 641       | 24.23%  |
| IMC Networks                           | 271       | 10.25%  |
| Microdia                               | 259       | 9.79%   |
| Realtek Semiconductor                  | 244       | 9.22%   |
| Bison Electronics                      | 183       | 6.92%   |
| Sunplus Innovation Technology          | 145       | 5.48%   |
| Quanta                                 | 128       | 4.84%   |
| Suyin                                  | 118       | 4.46%   |
| Cheng Uei Precision Industry (Foxlink) | 90        | 3.4%    |
| Syntek                                 | 86        | 3.25%   |
| Silicon Motion                         | 60        | 2.27%   |
| Lite-On Technology                     | 59        | 2.23%   |
| Acer                                   | 42        | 1.59%   |
| Ricoh                                  | 32        | 1.21%   |
| Luxvisions Innotech Limited            | 32        | 1.21%   |
| Logitech                               | 30        | 1.13%   |
| Apple                                  | 29        | 1.1%    |
| Lenovo                                 | 28        | 1.06%   |
| Alcor Micro                            | 28        | 1.06%   |
| Z-Star Microelectronics                | 15        | 0.57%   |
| Sonix Technology                       | 14        | 0.53%   |
| Intel                                  | 11        | 0.42%   |
| DigiTech                               | 11        | 0.42%   |
| Primax Electronics                     | 10        | 0.38%   |
| Creative Technology                    | 10        | 0.38%   |
| Samsung Electronics                    | 9         | 0.34%   |
| ALi                                    | 9         | 0.34%   |
| SunplusIT                              | 5         | 0.19%   |
| Microsoft                              | 5         | 0.19%   |
| Importek                               | 5         | 0.19%   |
| Generalplus Technology                 | 5         | 0.19%   |
| Sunplus Technology                     | 3         | 0.11%   |
| Alpha Imaging Technology               | 3         | 0.11%   |
| OmniVision Technologies                | 2         | 0.08%   |
| MacroSilicon                           | 2         | 0.08%   |
| Foxconn / Hon Hai                      | 2         | 0.08%   |
| Cubeternet                             | 2         | 0.08%   |
| Xiaomi                                 | 1         | 0.04%   |
| WaveRider Communications               | 1         | 0.04%   |
| Trust                                  | 1         | 0.04%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 130       | 4.9%    |
| Microdia Integrated_Webcam_HD            | 93        | 3.5%    |
| Realtek Integrated_Webcam_HD             | 77        | 2.9%    |
| IMC Networks Integrated Camera           | 73        | 2.75%   |
| IMC Networks USB2.0 HD UVC WebCam        | 67        | 2.52%   |
| Sunplus Integrated_Webcam_HD             | 56        | 2.11%   |
| Chicony Lenovo EasyCamera                | 48        | 1.81%   |
| Microdia Integrated Webcam               | 43        | 1.62%   |
| Bison Lenovo EasyCamera                  | 42        | 1.58%   |
| Chicony HD WebCam                        | 41        | 1.54%   |
| Suyin Integrated_Webcam_HD               | 36        | 1.36%   |
| Bison Integrated Camera                  | 36        | 1.36%   |
| Syntek Integrated Camera                 | 34        | 1.28%   |
| Syntek Lenovo EasyCamera                 | 32        | 1.21%   |
| Realtek Lenovo EasyCamera                | 29        | 1.09%   |
| Lite-On Integrated Camera                | 28        | 1.06%   |
| Chicony HP HD Camera                     | 28        | 1.06%   |
| Quanta HP TrueVision HD Camera           | 27        | 1.02%   |
| Bison Lenovo Integrated Webcam           | 25        | 0.94%   |
| Realtek USB Camera                       | 23        | 0.87%   |
| Realtek Integrated Webcam HD             | 23        | 0.87%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 23        | 0.87%   |
| Chicony USB2.0 HD UVC WebCam             | 21        | 0.79%   |
| Bison SunplusIT Integrated Camera        | 21        | 0.79%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 20        | 0.75%   |
| Quanta HD User Facing                    | 20        | 0.75%   |
| Microdia Laptop_Integrated_Webcam_HD     | 20        | 0.75%   |
| Realtek Integrated Webcam                | 18        | 0.68%   |
| Chicony USB2.0 VGA UVC WebCam            | 18        | 0.68%   |
| Chicony Integrated Camera (1280x720@30)  | 18        | 0.68%   |
| IMC Networks Integrated Webcam           | 17        | 0.64%   |
| Sunplus HD WebCam                        | 16        | 0.6%    |
| Lite-On HP HD Camera                     | 15        | 0.57%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 15        | 0.57%   |
| Chicony USB 2.0 Camera                   | 14        | 0.53%   |
| Sonix USB2.0 HD UVC WebCam               | 13        | 0.49%   |
| IMC Networks UVC VGA Webcam              | 13        | 0.49%   |
| Chicony VGA WebCam                       | 13        | 0.49%   |
| Chicony TOSHIBA Web Camera - HD          | 13        | 0.49%   |
| Chicony HP HD Webcam [Fixed]             | 13        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 202       | 36.93%  |
| Synaptics                          | 124       | 22.67%  |
| Shenzhen Goodix Technology         | 69        | 12.61%  |
| AuthenTec                          | 62        | 11.33%  |
| Upek                               | 38        | 6.95%   |
| Elan Microelectronics              | 21        | 3.84%   |
| LighTuning Technology              | 16        | 2.93%   |
| STMicroelectronics                 | 13        | 2.38%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.37%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 43        | 7.86%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 7.68%   |
| Shenzhen Goodix  Fingerprint Device                                        | 41        | 7.5%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 36        | 6.58%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 30        | 5.48%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 26        | 4.75%   |
| AuthenTec AES2810                                                          | 25        | 4.57%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 24        | 4.39%   |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 3.84%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 18        | 3.29%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 2.56%   |
| Validity Sensors VFS491                                                    | 13        | 2.38%   |
| Synaptics Fingerprint reader [HP G6]                                       | 13        | 2.38%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 2.38%   |
| Elan ELAN:Fingerprint                                                      | 13        | 2.38%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 12        | 2.19%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 11        | 2.01%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.01%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 2.01%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.83%   |
| Validity Sensors Fingerprint scanner                                       | 10        | 1.83%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 9         | 1.65%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 8         | 1.46%   |
| Elan ELAN:ARM-M4                                                           | 8         | 1.46%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.28%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 1.28%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.28%   |
| AuthenTec AES1600                                                          | 7         | 1.28%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.91%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 0.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 0.91%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.73%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 0.73%   |
| Synaptics WBDI                                                             | 4         | 0.73%   |
| Synaptics  WBDI                                                            | 4         | 0.73%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.73%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 0.73%   |
| Synaptics WBDI Device                                                      | 3         | 0.55%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.37%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 235       | 57.04%  |
| Alcor Micro               | 84        | 20.39%  |
| O2 Micro                  | 45        | 10.92%  |
| Upek                      | 22        | 5.34%   |
| Lenovo                    | 20        | 4.85%   |
| Gemalto (was Gemplus)     | 4         | 0.97%   |
| Clay Logic                | 1         | 0.24%   |
| Aladdin Knowledge Systems | 1         | 0.24%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 82        | 19.9%   |
| Broadcom BCM5880 Secure Applications Processor                               | 74        | 17.96%  |
| Broadcom 58200                                                               | 61        | 14.81%  |
| Broadcom 5880                                                                | 57        | 13.83%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 42        | 10.19%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 38        | 9.22%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 22        | 5.34%   |
| Lenovo Integrated Smart Card Reader                                          | 20        | 4.85%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 1.7%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.73%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.24%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.24%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.24%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.24%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.24%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.24%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1808      | 57.43%  |
| 1     | 1040      | 33.04%  |
| 2     | 254       | 8.07%   |
| 3     | 38        | 1.21%   |
| 4     | 3         | 0.1%    |
| 7     | 2         | 0.06%   |
| 5     | 2         | 0.06%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 540       | 33.05%  |
| Chipcard                 | 372       | 22.77%  |
| Graphics card            | 342       | 20.93%  |
| Net/wireless             | 105       | 6.43%   |
| Multimedia controller    | 54        | 3.3%    |
| Storage                  | 52        | 3.18%   |
| Bluetooth                | 46        | 2.82%   |
| Camera                   | 33        | 2.02%   |
| Communication controller | 27        | 1.65%   |
| Card reader              | 17        | 1.04%   |
| Sound                    | 12        | 0.73%   |
| Modem                    | 9         | 0.55%   |
| Net/ethernet             | 6         | 0.37%   |
| Firewire controller      | 5         | 0.31%   |
| Flash memory             | 4         | 0.24%   |
| Dvb card                 | 3         | 0.18%   |
| Network                  | 2         | 0.12%   |
| Wireless                 | 1         | 0.06%   |
| Unclassified device      | 1         | 0.06%   |
| Tv card                  | 1         | 0.06%   |
| Storage/raid             | 1         | 0.06%   |
| Storage/ide              | 1         | 0.06%   |

