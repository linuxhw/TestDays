OpenMandriva 24.07 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for OpenMandriva 24.07.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/OpenMandriva_24.07/Desktop/README.md) and [notebooks](/Dist/OpenMandriva_24.07/Notebook/README.md).

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

Total: 1373

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | PORTEGE R930                | Notebook    | [c424552903](https://linux-hardware.org/?probe=c424552903) | Dec 31, 2025 |
| ASUSTek       | UL30A                       | Notebook    | [f53a318199](https://linux-hardware.org/?probe=f53a318199) | Dec 30, 2025 |
| Dell          | System Inspiron N7110       | Notebook    | [c5c2861973](https://linux-hardware.org/?probe=c5c2861973) | Dec 27, 2025 |
| Medion        | Akoya E1317T                | Notebook    | [b27563db99](https://linux-hardware.org/?probe=b27563db99) | Dec 24, 2025 |
| Lenovo        | ThinkPad X220 4291CF3       | Notebook    | [3dbf7f1b45](https://linux-hardware.org/?probe=3dbf7f1b45) | Dec 03, 2025 |
| Apple         | Mac-F2268CC8                | All in one  | [00a9425fb5](https://linux-hardware.org/?probe=00a9425fb5) | Nov 15, 2025 |
| Intel         | B75                         | Desktop     | [f2db8ec2de](https://linux-hardware.org/?probe=f2db8ec2de) | Nov 12, 2025 |
| Apple         | Mac-F2218FC8                | All in one  | [1160a15057](https://linux-hardware.org/?probe=1160a15057) | Oct 28, 2025 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [1c5ef6c390](https://linux-hardware.org/?probe=1c5ef6c390) | Oct 27, 2025 |
| MSI           | MPG Z490 GAMING PLUS        | Desktop     | [f09e9a7b63](https://linux-hardware.org/?probe=f09e9a7b63) | Oct 22, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | Notebook    | [da6c2342bc](https://linux-hardware.org/?probe=da6c2342bc) | Oct 04, 2025 |
| Sony          | VGN-CR260FE                 | Notebook    | [ad507d5c9b](https://linux-hardware.org/?probe=ad507d5c9b) | Sep 29, 2025 |
| Toshiba       | QOSMIO X505                 | Notebook    | [4f200a13ce](https://linux-hardware.org/?probe=4f200a13ce) | Sep 12, 2025 |
| HP            | Compaq Presario C700        | Notebook    | [37ccee051c](https://linux-hardware.org/?probe=37ccee051c) | Sep 04, 2025 |
| Gigabyte      | nForce                      | Desktop     | [8ea3cf2201](https://linux-hardware.org/?probe=8ea3cf2201) | Aug 31, 2025 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [42af17a2b8](https://linux-hardware.org/?probe=42af17a2b8) | Aug 30, 2025 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [8499ae4538](https://linux-hardware.org/?probe=8499ae4538) | Aug 27, 2025 |
| Lenovo        | B575e 36852DG               | Notebook    | [4459e655aa](https://linux-hardware.org/?probe=4459e655aa) | Aug 18, 2025 |
| Samsung       | 550XED                      | Notebook    | [9f5414b8d1](https://linux-hardware.org/?probe=9f5414b8d1) | Aug 17, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [03a39913e3](https://linux-hardware.org/?probe=03a39913e3) | Aug 16, 2025 |
| Dell          | Inspiron 3520               | Notebook    | [18da1c823c](https://linux-hardware.org/?probe=18da1c823c) | Aug 14, 2025 |
| Gigabyte      | GA-G41M-ES2L                | Desktop     | [837ac6f4db](https://linux-hardware.org/?probe=837ac6f4db) | Aug 12, 2025 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [7dcedd1751](https://linux-hardware.org/?probe=7dcedd1751) | Aug 10, 2025 |
| MSI           | B550M-A PRO                 | Desktop     | [4c0f276180](https://linux-hardware.org/?probe=4c0f276180) | Aug 06, 2025 |
| Toshiba       | Satellite A505              | Notebook    | [92e88e3d4b](https://linux-hardware.org/?probe=92e88e3d4b) | Aug 03, 2025 |
| HP            | ProBook 6475b               | Notebook    | [dcf341be09](https://linux-hardware.org/?probe=dcf341be09) | Aug 02, 2025 |
| Dell          | Latitude E5550              | Notebook    | [8fedc01826](https://linux-hardware.org/?probe=8fedc01826) | Jul 28, 2025 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [bd0842b62f](https://linux-hardware.org/?probe=bd0842b62f) | Jul 25, 2025 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [af126a92ca](https://linux-hardware.org/?probe=af126a92ca) | Jul 20, 2025 |
| AZW           | MINI S                      | Desktop     | [ae0563af05](https://linux-hardware.org/?probe=ae0563af05) | Jul 19, 2025 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9dc6bf9b38](https://linux-hardware.org/?probe=9dc6bf9b38) | Jul 13, 2025 |
| Gigabyte      | B760 DS3H AX DDR4           | Desktop     | [2461a88a30](https://linux-hardware.org/?probe=2461a88a30) | Jul 13, 2025 |
| HP            | ProBook 4510s               | Notebook    | [9ac1f88828](https://linux-hardware.org/?probe=9ac1f88828) | Jul 11, 2025 |
| Ramsta        | RS-A320MP Ver:1.00          | Desktop     | [9a20e1a883](https://linux-hardware.org/?probe=9a20e1a883) | Jul 10, 2025 |
| ADVAN         | 1701                        | Notebook    | [2bd256412d](https://linux-hardware.org/?probe=2bd256412d) | Jul 03, 2025 |
| ASUSTek       | M3A                         | Desktop     | [775e16752c](https://linux-hardware.org/?probe=775e16752c) | Jul 01, 2025 |
| Dell          | Latitude 3350               | Notebook    | [b90cb489b8](https://linux-hardware.org/?probe=b90cb489b8) | Jun 28, 2025 |
| Microsoft     | Surface Pro                 | Tablet      | [18780e5c30](https://linux-hardware.org/?probe=18780e5c30) | Jun 21, 2025 |
| ASUSTek       | B85M-G                      | Desktop     | [28ed8d29bb](https://linux-hardware.org/?probe=28ed8d29bb) | Jun 05, 2025 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [0082c0231d](https://linux-hardware.org/?probe=0082c0231d) | Jun 03, 2025 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [19eb9ed495](https://linux-hardware.org/?probe=19eb9ed495) | Jun 03, 2025 |
| Unknown       | Unknown                     | Desktop     | [adf51a98ae](https://linux-hardware.org/?probe=adf51a98ae) | Jun 01, 2025 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [992927a2d8](https://linux-hardware.org/?probe=992927a2d8) | May 31, 2025 |
| Lenovo        | 3000 N200 0769AL3           | Notebook    | [1cc8a86b76](https://linux-hardware.org/?probe=1cc8a86b76) | May 29, 2025 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [b44f3f41a0](https://linux-hardware.org/?probe=b44f3f41a0) | May 28, 2025 |
| MSI           | CR420                       | Notebook    | [81e0b6440d](https://linux-hardware.org/?probe=81e0b6440d) | May 27, 2025 |
| ASRock        | AM1B-MH                     | Desktop     | [231846ed0e](https://linux-hardware.org/?probe=231846ed0e) | May 26, 2025 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b9bf8b478c](https://linux-hardware.org/?probe=b9bf8b478c) | May 25, 2025 |
| Dell          | Studio 1558                 | Notebook    | [754114fb85](https://linux-hardware.org/?probe=754114fb85) | May 20, 2025 |
| HP            | Notebook                    | Notebook    | [6c92df3ba8](https://linux-hardware.org/?probe=6c92df3ba8) | May 18, 2025 |
| Toshiba       | Satellite L350              | Notebook    | [5dd08a2183](https://linux-hardware.org/?probe=5dd08a2183) | May 18, 2025 |
| HP            | Pavilion dv5000 (EP420UA... | Notebook    | [319bce7241](https://linux-hardware.org/?probe=319bce7241) | May 14, 2025 |
| HP            | 1497                        | Desktop     | [1aa53c4113](https://linux-hardware.org/?probe=1aa53c4113) | May 08, 2025 |
| ASUSTek       | M52AD_M12AD_A_F_K31AD       | Desktop     | [2257cd6ecd](https://linux-hardware.org/?probe=2257cd6ecd) | May 07, 2025 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [21471345fb](https://linux-hardware.org/?probe=21471345fb) | May 05, 2025 |
| ASRock        | X870E Nova WiFi             | Desktop     | [303deef8fc](https://linux-hardware.org/?probe=303deef8fc) | May 04, 2025 |
| Acer          | Aspire E1-531G              | Notebook    | [324de60ab6](https://linux-hardware.org/?probe=324de60ab6) | May 02, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [008cb36a15](https://linux-hardware.org/?probe=008cb36a15) | Apr 29, 2025 |
| Gigabyte      | H55M-USB3                   | Desktop     | [4e62ff3ea2](https://linux-hardware.org/?probe=4e62ff3ea2) | Apr 28, 2025 |
| ASUSTek       | P8H77-I                     | Desktop     | [ed5929ee7b](https://linux-hardware.org/?probe=ed5929ee7b) | Apr 26, 2025 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [79ed7c1999](https://linux-hardware.org/?probe=79ed7c1999) | Apr 26, 2025 |
| ASUSTek       | Rampage IV BLACK EDITION    | Desktop     | [43b82fc07a](https://linux-hardware.org/?probe=43b82fc07a) | Apr 25, 2025 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [06db4aa634](https://linux-hardware.org/?probe=06db4aa634) | Apr 23, 2025 |
| Acer          | Aspire R3-131T              | Notebook    | [a1db17949f](https://linux-hardware.org/?probe=a1db17949f) | Apr 20, 2025 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [e26e0cbcb0](https://linux-hardware.org/?probe=e26e0cbcb0) | Apr 20, 2025 |
| BESSTAR Te... | HM80                        | Desktop     | [099f76e1c7](https://linux-hardware.org/?probe=099f76e1c7) | Apr 16, 2025 |
| Intel         | DH55TC AAE70932-206         | Desktop     | [608d37fe3e](https://linux-hardware.org/?probe=608d37fe3e) | Apr 14, 2025 |
| ASUSTek       | K52JT                       | Notebook    | [3a3eb9d804](https://linux-hardware.org/?probe=3a3eb9d804) | Apr 08, 2025 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ba46e9c49e](https://linux-hardware.org/?probe=ba46e9c49e) | Apr 05, 2025 |
| HP            | 246                         | Notebook    | [61f81892b6](https://linux-hardware.org/?probe=61f81892b6) | Mar 31, 2025 |
| ZOTAC         | ZBOX-PI225                  | Mini pc     | [ffd2c22f00](https://linux-hardware.org/?probe=ffd2c22f00) | Mar 29, 2025 |
| Lenovo        | IdeaPad Slim 3 14IAH8 83... | Notebook    | [2dfc01251f](https://linux-hardware.org/?probe=2dfc01251f) | Mar 29, 2025 |
| Lenovo        | ThinkPad Edge 32597AU       | Notebook    | [af33317fc3](https://linux-hardware.org/?probe=af33317fc3) | Mar 27, 2025 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [002a8d7441](https://linux-hardware.org/?probe=002a8d7441) | Mar 27, 2025 |
| ASRock        | A320M Pro4                  | Desktop     | [923a4211f9](https://linux-hardware.org/?probe=923a4211f9) | Mar 18, 2025 |
| MSI           | Z87-G45 GAMING              | Desktop     | [2f5f30dd2c](https://linux-hardware.org/?probe=2f5f30dd2c) | Mar 15, 2025 |
| Dell          | Inspiron 3585               | Notebook    | [5bd9576c9e](https://linux-hardware.org/?probe=5bd9576c9e) | Mar 13, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cd024baa40](https://linux-hardware.org/?probe=cd024baa40) | Mar 10, 2025 |
| Panasonic     | CFXZ6-1                     | Tablet      | [d63e9ededb](https://linux-hardware.org/?probe=d63e9ededb) | Mar 10, 2025 |
| Toshiba       | Satellite S45-A             | Notebook    | [e8f5280666](https://linux-hardware.org/?probe=e8f5280666) | Mar 02, 2025 |
| Acer          | Aspire V3-771               | Notebook    | [e360a517f2](https://linux-hardware.org/?probe=e360a517f2) | Feb 27, 2025 |
| Lenovo        | ThinkPad Edge E530 3259H... | Notebook    | [d282936889](https://linux-hardware.org/?probe=d282936889) | Feb 26, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [903afa9561](https://linux-hardware.org/?probe=903afa9561) | Feb 23, 2025 |
| MSI           | A520M-A PRO                 | Desktop     | [b0f12bdf92](https://linux-hardware.org/?probe=b0f12bdf92) | Feb 21, 2025 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cc6b35c39b](https://linux-hardware.org/?probe=cc6b35c39b) | Feb 20, 2025 |
| Dell          | Inspiron 1764               | Notebook    | [ee1147d849](https://linux-hardware.org/?probe=ee1147d849) | Feb 20, 2025 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8bf2ff9347](https://linux-hardware.org/?probe=8bf2ff9347) | Feb 19, 2025 |
| ASRock        | Z87 Extreme4                | Desktop     | [6df653a3a2](https://linux-hardware.org/?probe=6df653a3a2) | Feb 19, 2025 |
| ASUSTek       | A7U                         | Notebook    | [ad4ef35c3a](https://linux-hardware.org/?probe=ad4ef35c3a) | Feb 13, 2025 |
| Dell          | Inspiron 5520               | Notebook    | [7f66df86bd](https://linux-hardware.org/?probe=7f66df86bd) | Feb 10, 2025 |
| MSI           | E350IA-E45                  | Desktop     | [f21478cbb7](https://linux-hardware.org/?probe=f21478cbb7) | Feb 08, 2025 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [dbecb935af](https://linux-hardware.org/?probe=dbecb935af) | Feb 04, 2025 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [ea27ad03d5](https://linux-hardware.org/?probe=ea27ad03d5) | Feb 03, 2025 |
| Haier         | U1520HD                     | Notebook    | [fed3f845d0](https://linux-hardware.org/?probe=fed3f845d0) | Feb 02, 2025 |
| ASRock        | X670E PG Lightning          | Desktop     | [7c62104a80](https://linux-hardware.org/?probe=7c62104a80) | Feb 01, 2025 |
| Lenovo        | 3308 SDK0T76538 WIN 3556... | Mini pc     | [b361d272dc](https://linux-hardware.org/?probe=b361d272dc) | Jan 27, 2025 |
| ASUSTek       | P5Q3                        | Desktop     | [fb60fc8b28](https://linux-hardware.org/?probe=fb60fc8b28) | Jan 24, 2025 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [16eb2d304a](https://linux-hardware.org/?probe=16eb2d304a) | Jan 24, 2025 |
| MSI           | B550M-A PRO                 | Desktop     | [e6ae4099b5](https://linux-hardware.org/?probe=e6ae4099b5) | Jan 24, 2025 |
| HP            | 8265                        | Desktop     | [1a3578bed8](https://linux-hardware.org/?probe=1a3578bed8) | Jan 21, 2025 |
| Shenzhen M... | HPBSD                       | Mini pc     | [d7cab4c787](https://linux-hardware.org/?probe=d7cab4c787) | Jan 18, 2025 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [c563f0f3c9](https://linux-hardware.org/?probe=c563f0f3c9) | Jan 17, 2025 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [fb088c26c9](https://linux-hardware.org/?probe=fb088c26c9) | Jan 16, 2025 |
| HP            | 213D A01                    | Desktop     | [4ef5f5c77b](https://linux-hardware.org/?probe=4ef5f5c77b) | Jan 14, 2025 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [a3139f8204](https://linux-hardware.org/?probe=a3139f8204) | Jan 14, 2025 |
| PCChips       | A45G                        | Desktop     | [80806534be](https://linux-hardware.org/?probe=80806534be) | Jan 12, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [195b1e2d7e](https://linux-hardware.org/?probe=195b1e2d7e) | Jan 07, 2025 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [963fcdd477](https://linux-hardware.org/?probe=963fcdd477) | Jan 06, 2025 |
| HP            | ProBook 640 G1              | Notebook    | [f901f7b9aa](https://linux-hardware.org/?probe=f901f7b9aa) | Jan 03, 2025 |
| Dell          | Latitude 5300               | Notebook    | [d3d6e520f5](https://linux-hardware.org/?probe=d3d6e520f5) | Jan 03, 2025 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [e6075adfc0](https://linux-hardware.org/?probe=e6075adfc0) | Jan 02, 2025 |
| Gigabyte      | GA-MA785GT-UD3H             | Desktop     | [bf30d86827](https://linux-hardware.org/?probe=bf30d86827) | Jan 01, 2025 |
| Infinix       | Y3 Plus                     | Notebook    | [a5d0c097a5](https://linux-hardware.org/?probe=a5d0c097a5) | Dec 30, 2024 |
| Lenovo        | IdeaPad 330-17AST 81D7      | Notebook    | [145b300a77](https://linux-hardware.org/?probe=145b300a77) | Dec 26, 2024 |
| Unknown       | Unknown                     | Desktop     | [9dc841041f](https://linux-hardware.org/?probe=9dc841041f) | Dec 25, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [cd4f5695b9](https://linux-hardware.org/?probe=cd4f5695b9) | Dec 22, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [0219cb33b6](https://linux-hardware.org/?probe=0219cb33b6) | Dec 20, 2024 |
| MSI           | B75MA-P45                   | Desktop     | [da146c44f0](https://linux-hardware.org/?probe=da146c44f0) | Dec 19, 2024 |
| ASUSTek       | S451LA                      | Notebook    | [a766d0caae](https://linux-hardware.org/?probe=a766d0caae) | Dec 19, 2024 |
| Sony          | VPCEH39FJ                   | Notebook    | [f0627de40e](https://linux-hardware.org/?probe=f0627de40e) | Dec 16, 2024 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [0d17c2a875](https://linux-hardware.org/?probe=0d17c2a875) | Dec 15, 2024 |
| Positivo      | POS-PIB150DT 11132270       | Desktop     | [c3a85ea71c](https://linux-hardware.org/?probe=c3a85ea71c) | Dec 15, 2024 |
| Dell          | Latitude E6500              | Notebook    | [1c4c62551f](https://linux-hardware.org/?probe=1c4c62551f) | Dec 14, 2024 |
| ASUSTek       | G60JX                       | Notebook    | [b1cc4820a3](https://linux-hardware.org/?probe=b1cc4820a3) | Dec 13, 2024 |
| MSI           | Z97 GAMING 5                | Desktop     | [e41e77f484](https://linux-hardware.org/?probe=e41e77f484) | Dec 12, 2024 |
| HP            | 620                         | Notebook    | [152ec63b24](https://linux-hardware.org/?probe=152ec63b24) | Dec 12, 2024 |
| Sony          | VPCEJ2E1E                   | Notebook    | [11625e4a3c](https://linux-hardware.org/?probe=11625e4a3c) | Dec 12, 2024 |
| Dell          | 09M47G A00                  | Desktop     | [c3b1e4864a](https://linux-hardware.org/?probe=c3b1e4864a) | Dec 12, 2024 |
| Unknown       | Unknown                     | Desktop     | [ed65661387](https://linux-hardware.org/?probe=ed65661387) | Dec 12, 2024 |
| Dell          | Latitude E6440              | Notebook    | [c3aebd55c6](https://linux-hardware.org/?probe=c3aebd55c6) | Dec 11, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [4a452b8790](https://linux-hardware.org/?probe=4a452b8790) | Dec 11, 2024 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [c5d5aaca89](https://linux-hardware.org/?probe=c5d5aaca89) | Dec 11, 2024 |
| ASUSTek       | X550JX                      | Notebook    | [825a9b88c3](https://linux-hardware.org/?probe=825a9b88c3) | Dec 11, 2024 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [3730405110](https://linux-hardware.org/?probe=3730405110) | Dec 11, 2024 |
| HP            | ProBook 4530s               | Notebook    | [e8e3959577](https://linux-hardware.org/?probe=e8e3959577) | Dec 11, 2024 |
| Notebook      | 14M2                        | Notebook    | [30b428ea7b](https://linux-hardware.org/?probe=30b428ea7b) | Dec 11, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [986d807d00](https://linux-hardware.org/?probe=986d807d00) | Dec 10, 2024 |
| Dell          | 0F6X5P A00                  | Desktop     | [680aead333](https://linux-hardware.org/?probe=680aead333) | Dec 10, 2024 |
| Dell          | Inspiron 15 3515            | Notebook    | [a073fbc9bc](https://linux-hardware.org/?probe=a073fbc9bc) | Dec 10, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [a632326872](https://linux-hardware.org/?probe=a632326872) | Dec 09, 2024 |
| HP            | EliteBook 820 G4            | Notebook    | [180e325043](https://linux-hardware.org/?probe=180e325043) | Dec 09, 2024 |
| ASUSTek       | Z450LA                      | Notebook    | [2281fa41ae](https://linux-hardware.org/?probe=2281fa41ae) | Dec 08, 2024 |
| Lenovo        | MAHOBAY Win8 MM DPK IPG     | Desktop     | [e885620f20](https://linux-hardware.org/?probe=e885620f20) | Dec 06, 2024 |
| MSI           | H61M-P23                    | Desktop     | [4e730504db](https://linux-hardware.org/?probe=4e730504db) | Dec 06, 2024 |
| Lenovo        | ThinkPad T410 2537K96       | Notebook    | [ae6d2e915b](https://linux-hardware.org/?probe=ae6d2e915b) | Dec 06, 2024 |
| MSI           | A88XI AC V2                 | Desktop     | [3bd43ba035](https://linux-hardware.org/?probe=3bd43ba035) | Dec 06, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cdb9d074c0](https://linux-hardware.org/?probe=cdb9d074c0) | Dec 06, 2024 |
| Dell          | 0CWR57 A01                  | Desktop     | [38bea64860](https://linux-hardware.org/?probe=38bea64860) | Dec 06, 2024 |
| HP            | Unknown                     | Notebook    | [c5d5bb8ffc](https://linux-hardware.org/?probe=c5d5bb8ffc) | Dec 06, 2024 |
| ASUSTek       | X550CC                      | Notebook    | [c395078c21](https://linux-hardware.org/?probe=c395078c21) | Dec 05, 2024 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [dd80673855](https://linux-hardware.org/?probe=dd80673855) | Dec 05, 2024 |
| Lenovo        | ThinkPad T480s 20L8SF100... | Notebook    | [e33bd93e90](https://linux-hardware.org/?probe=e33bd93e90) | Dec 04, 2024 |
| Gigabyte      | G31M-S2L                    | Desktop     | [a8795f3981](https://linux-hardware.org/?probe=a8795f3981) | Dec 04, 2024 |
| HP            | EliteBook 850 G6            | Notebook    | [af2a2b7059](https://linux-hardware.org/?probe=af2a2b7059) | Dec 04, 2024 |
| ASUSTek       | K52JK                       | Notebook    | [1e978f8201](https://linux-hardware.org/?probe=1e978f8201) | Dec 03, 2024 |
| ASUSTek       | Z87-PRO                     | Desktop     | [029f1c1e1b](https://linux-hardware.org/?probe=029f1c1e1b) | Dec 03, 2024 |
| Toshiba       | Satellite S70-A             | Notebook    | [fdbc12af06](https://linux-hardware.org/?probe=fdbc12af06) | Dec 03, 2024 |
| HP            | Pavilion dv6                | Notebook    | [f72bd7ca67](https://linux-hardware.org/?probe=f72bd7ca67) | Dec 03, 2024 |
| Fujitsu       | FMVA42MW2                   | Notebook    | [a5a7a4a6f1](https://linux-hardware.org/?probe=a5a7a4a6f1) | Dec 03, 2024 |
| Acer          | Nitro ANV15-51              | Notebook    | [ac43db5c18](https://linux-hardware.org/?probe=ac43db5c18) | Dec 02, 2024 |
| Unknown       | Unknown                     | Desktop     | [3405878ab6](https://linux-hardware.org/?probe=3405878ab6) | Dec 01, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [83800e0dd2](https://linux-hardware.org/?probe=83800e0dd2) | Dec 01, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [ba38d6b924](https://linux-hardware.org/?probe=ba38d6b924) | Dec 01, 2024 |
| Dell          | 0VNP2H A00                  | Desktop     | [d1a2135f92](https://linux-hardware.org/?probe=d1a2135f92) | Nov 30, 2024 |
| HP            | EliteBook 850 G5            | Notebook    | [39d29e9e31](https://linux-hardware.org/?probe=39d29e9e31) | Nov 30, 2024 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | Notebook    | [c7fb17104d](https://linux-hardware.org/?probe=c7fb17104d) | Nov 29, 2024 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ce0e3b2719](https://linux-hardware.org/?probe=ce0e3b2719) | Nov 29, 2024 |
| BESSTAR Te... | UM700                       | Desktop     | [5c18419477](https://linux-hardware.org/?probe=5c18419477) | Nov 29, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [6c4c6577ac](https://linux-hardware.org/?probe=6c4c6577ac) | Nov 29, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [7e2cca4ada](https://linux-hardware.org/?probe=7e2cca4ada) | Nov 28, 2024 |
| Gigabyte      | H81M-D2W                    | Desktop     | [c0db894e36](https://linux-hardware.org/?probe=c0db894e36) | Nov 28, 2024 |
| Acer          | Aspire A315-34              | Notebook    | [16257c3b4b](https://linux-hardware.org/?probe=16257c3b4b) | Nov 27, 2024 |
| Lenovo        | 36C7 SDK0J40697 WIN 3305... | Desktop     | [d113defbe8](https://linux-hardware.org/?probe=d113defbe8) | Nov 27, 2024 |
| HP            | 18E7                        | Desktop     | [6dbb855fd6](https://linux-hardware.org/?probe=6dbb855fd6) | Nov 26, 2024 |
| Acer          | Aspire ES1-512              | Notebook    | [dfc7a551d9](https://linux-hardware.org/?probe=dfc7a551d9) | Nov 26, 2024 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [2e121a8a35](https://linux-hardware.org/?probe=2e121a8a35) | Nov 26, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [07ef34a01f](https://linux-hardware.org/?probe=07ef34a01f) | Nov 25, 2024 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [d208c8829e](https://linux-hardware.org/?probe=d208c8829e) | Nov 24, 2024 |
| Microsoft     | Surface Pro                 | Tablet      | [e30f026fac](https://linux-hardware.org/?probe=e30f026fac) | Nov 24, 2024 |
| Intel         | B75                         | Desktop     | [b8e4743721](https://linux-hardware.org/?probe=b8e4743721) | Nov 24, 2024 |
| ASUSTek       | TP203NAH                    | Convertible | [0b2979ca7f](https://linux-hardware.org/?probe=0b2979ca7f) | Nov 24, 2024 |
| Lenovo        | 31900058 STD                | Desktop     | [dfea5f8644](https://linux-hardware.org/?probe=dfea5f8644) | Nov 24, 2024 |
| Google        | Lillipup rev3               | Notebook    | [26051de0da](https://linux-hardware.org/?probe=26051de0da) | Nov 24, 2024 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [db71db68e5](https://linux-hardware.org/?probe=db71db68e5) | Nov 23, 2024 |
| Gigabyte      | H510M H V2                  | Desktop     | [a9d59f6f5f](https://linux-hardware.org/?probe=a9d59f6f5f) | Nov 23, 2024 |
| ASUSTek       | Pro B550M-C                 | Desktop     | [e532c8a2c5](https://linux-hardware.org/?probe=e532c8a2c5) | Nov 23, 2024 |
| ASUSTek       | B75M-A                      | Desktop     | [e7f193654c](https://linux-hardware.org/?probe=e7f193654c) | Nov 23, 2024 |
| Intel         | D945GCCR AAD78647-300       | Desktop     | [1b7eecc546](https://linux-hardware.org/?probe=1b7eecc546) | Nov 22, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [bdad4ccabe](https://linux-hardware.org/?probe=bdad4ccabe) | Nov 22, 2024 |
| Dell          | Latitude D630               | Notebook    | [135fedf2cd](https://linux-hardware.org/?probe=135fedf2cd) | Nov 22, 2024 |
| HP            | 240 G8 Notebook PC          | Notebook    | [33374fdc29](https://linux-hardware.org/?probe=33374fdc29) | Nov 22, 2024 |
| BANGHO        | Suma 1025                   | Tablet      | [c3a82ec7e7](https://linux-hardware.org/?probe=c3a82ec7e7) | Nov 21, 2024 |
| Itautec       | Infoway                     | Notebook    | [466651a218](https://linux-hardware.org/?probe=466651a218) | Nov 21, 2024 |
| Unknown       | AX16PRO                     | Notebook    | [97a667e749](https://linux-hardware.org/?probe=97a667e749) | Nov 21, 2024 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [00fc7a8d8b](https://linux-hardware.org/?probe=00fc7a8d8b) | Nov 21, 2024 |
| Dell          | 0FR6WH A01                  | Desktop     | [8ea0baf186](https://linux-hardware.org/?probe=8ea0baf186) | Nov 21, 2024 |
| Dell          | Latitude 5490               | Notebook    | [50f3de2c58](https://linux-hardware.org/?probe=50f3de2c58) | Nov 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b3d142c510](https://linux-hardware.org/?probe=b3d142c510) | Nov 21, 2024 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [69a4d1cdc5](https://linux-hardware.org/?probe=69a4d1cdc5) | Nov 21, 2024 |
| Acer          | Aspire A515-48M             | Notebook    | [7e76e833e3](https://linux-hardware.org/?probe=7e76e833e3) | Nov 20, 2024 |
| HP            | 8055                        | Desktop     | [25559cfc60](https://linux-hardware.org/?probe=25559cfc60) | Nov 20, 2024 |
| HP            | Laptop 15g-br1xx            | Notebook    | [f51b7c2e9d](https://linux-hardware.org/?probe=f51b7c2e9d) | Nov 20, 2024 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [0d1e9eec2d](https://linux-hardware.org/?probe=0d1e9eec2d) | Nov 20, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [9dfd49751f](https://linux-hardware.org/?probe=9dfd49751f) | Nov 19, 2024 |
| Lenovo        | ThinkPad X61 7675CTO        | Notebook    | [772ab308c2](https://linux-hardware.org/?probe=772ab308c2) | Nov 19, 2024 |
| HP            | 8954                        | Desktop     | [58001c585c](https://linux-hardware.org/?probe=58001c585c) | Nov 19, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [eb0ca23199](https://linux-hardware.org/?probe=eb0ca23199) | Nov 19, 2024 |
| Teclast       | X80 Pro                     | Tablet      | [27c9721007](https://linux-hardware.org/?probe=27c9721007) | Nov 18, 2024 |
| Toshiba       | Satellite U845t             | Notebook    | [a73248a89d](https://linux-hardware.org/?probe=a73248a89d) | Nov 18, 2024 |
| Shenzhen M... | F7BFC                       | Desktop     | [4a79811e5e](https://linux-hardware.org/?probe=4a79811e5e) | Nov 17, 2024 |
| Dell          | Latitude 3420               | Notebook    | [9db39167d7](https://linux-hardware.org/?probe=9db39167d7) | Nov 17, 2024 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [06da77f5c0](https://linux-hardware.org/?probe=06da77f5c0) | Nov 16, 2024 |
| Dell          | 0MN1TX A00                  | Desktop     | [bc63ab4bf3](https://linux-hardware.org/?probe=bc63ab4bf3) | Nov 15, 2024 |
| ASUSTek       | F2A85-M2                    | Desktop     | [b6e3dbb57a](https://linux-hardware.org/?probe=b6e3dbb57a) | Nov 15, 2024 |
| HP            | EliteBook 2730p             | Notebook    | [5ce55a50da](https://linux-hardware.org/?probe=5ce55a50da) | Nov 15, 2024 |
| Foxconn       | 2ADA                        | Desktop     | [f3b302e1d7](https://linux-hardware.org/?probe=f3b302e1d7) | Nov 15, 2024 |
| Dell          | 0200DY A02                  | Desktop     | [7a85e1e310](https://linux-hardware.org/?probe=7a85e1e310) | Nov 15, 2024 |
| Microsoft     | Surface Go 2                | Tablet      | [b5609df256](https://linux-hardware.org/?probe=b5609df256) | Nov 15, 2024 |
| MSI           | B365M PRO-VH                | Desktop     | [b2796a7151](https://linux-hardware.org/?probe=b2796a7151) | Nov 14, 2024 |
| Dell          | Inspiron 3505               | Notebook    | [42bed8b241](https://linux-hardware.org/?probe=42bed8b241) | Nov 14, 2024 |
| ASUSTek       | 1018P                       | Notebook    | [eef1555906](https://linux-hardware.org/?probe=eef1555906) | Nov 13, 2024 |
| Dell          | Precision M6700             | Notebook    | [81ed3cc9db](https://linux-hardware.org/?probe=81ed3cc9db) | Nov 13, 2024 |
| Acer          | Aspire 5742G                | Notebook    | [46d5cbc974](https://linux-hardware.org/?probe=46d5cbc974) | Nov 13, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [280fdbebe9](https://linux-hardware.org/?probe=280fdbebe9) | Nov 13, 2024 |
| Acer          | Aspire 5250                 | Notebook    | [6afaf552dd](https://linux-hardware.org/?probe=6afaf552dd) | Nov 13, 2024 |
| HP            | 18E7                        | Desktop     | [e6421394f6](https://linux-hardware.org/?probe=e6421394f6) | Nov 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M370... | Notebook    | [d655b85ff6](https://linux-hardware.org/?probe=d655b85ff6) | Nov 12, 2024 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [f3b250b116](https://linux-hardware.org/?probe=f3b250b116) | Nov 12, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [60400093d0](https://linux-hardware.org/?probe=60400093d0) | Nov 12, 2024 |
| Samsung       | R510/P510                   | Notebook    | [45941aa5d5](https://linux-hardware.org/?probe=45941aa5d5) | Nov 11, 2024 |
| Gigabyte      | B75M-HD3                    | Desktop     | [c594c0e00c](https://linux-hardware.org/?probe=c594c0e00c) | Nov 11, 2024 |
| Dell          | Vostro 1310                 | Notebook    | [add2298606](https://linux-hardware.org/?probe=add2298606) | Nov 11, 2024 |
| Fujitsu       | FMVC07003                   | Notebook    | [9fe5e42140](https://linux-hardware.org/?probe=9fe5e42140) | Nov 10, 2024 |
| Lenovo        | ThinkPad L440 20ASS11T00    | Notebook    | [9e63659c87](https://linux-hardware.org/?probe=9e63659c87) | Nov 09, 2024 |
| Apple         | MacBookPro6,1               | Notebook    | [24c0858a39](https://linux-hardware.org/?probe=24c0858a39) | Nov 09, 2024 |
| HP            | 1497                        | Desktop     | [b4fe73ae99](https://linux-hardware.org/?probe=b4fe73ae99) | Nov 09, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [bd81a29143](https://linux-hardware.org/?probe=bd81a29143) | Nov 09, 2024 |
| Microsoft     | Surface Pro 2               | Tablet      | [c8aeb37a97](https://linux-hardware.org/?probe=c8aeb37a97) | Nov 09, 2024 |
| Dell          | Inspiron 3520               | Notebook    | [e129134b01](https://linux-hardware.org/?probe=e129134b01) | Nov 08, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [9de1e927a9](https://linux-hardware.org/?probe=9de1e927a9) | Nov 07, 2024 |
| ASUSTek       | E202SA                      | Notebook    | [18a63b065d](https://linux-hardware.org/?probe=18a63b065d) | Nov 07, 2024 |
| Acer          | Swift SF314-43              | Notebook    | [c55af0c24c](https://linux-hardware.org/?probe=c55af0c24c) | Nov 07, 2024 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [083567b242](https://linux-hardware.org/?probe=083567b242) | Nov 07, 2024 |
| Lenovo        | ThinkPad L420 7829GH2       | Notebook    | [33efc8a835](https://linux-hardware.org/?probe=33efc8a835) | Nov 07, 2024 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ce1c922dc4](https://linux-hardware.org/?probe=ce1c922dc4) | Nov 07, 2024 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [f573142825](https://linux-hardware.org/?probe=f573142825) | Nov 07, 2024 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [b0ca914a02](https://linux-hardware.org/?probe=b0ca914a02) | Nov 06, 2024 |
| Positivo      | C14CU51                     | Notebook    | [910164dc5c](https://linux-hardware.org/?probe=910164dc5c) | Nov 06, 2024 |
| HP            | 1495                        | Desktop     | [b362515be5](https://linux-hardware.org/?probe=b362515be5) | Nov 06, 2024 |
| HP            | Pavilion g4                 | Notebook    | [2f7cb31cab](https://linux-hardware.org/?probe=2f7cb31cab) | Nov 06, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [689c7827b7](https://linux-hardware.org/?probe=689c7827b7) | Nov 06, 2024 |
| ASRock        | Z790 Riptide WiFi           | Desktop     | [f7330298cd](https://linux-hardware.org/?probe=f7330298cd) | Nov 05, 2024 |
| Gigabyte      | H61M-S1                     | Desktop     | [4583180173](https://linux-hardware.org/?probe=4583180173) | Nov 04, 2024 |
| Lenovo        | ThinkPad T420 4180CC4       | Notebook    | [f3899bf09d](https://linux-hardware.org/?probe=f3899bf09d) | Nov 04, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [4cab1133bf](https://linux-hardware.org/?probe=4cab1133bf) | Nov 04, 2024 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [02f10cb27c](https://linux-hardware.org/?probe=02f10cb27c) | Nov 04, 2024 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [40b8d362ea](https://linux-hardware.org/?probe=40b8d362ea) | Nov 03, 2024 |
| Dell          | 0JP3NX A01                  | Desktop     | [dc2c04bda9](https://linux-hardware.org/?probe=dc2c04bda9) | Nov 03, 2024 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [a800edd9fc](https://linux-hardware.org/?probe=a800edd9fc) | Nov 03, 2024 |
| Lenovo        | ThinkPad X230 23256V1       | Notebook    | [08af8a55a1](https://linux-hardware.org/?probe=08af8a55a1) | Nov 03, 2024 |
| Fujitsu       | LIFEBOOK E743               | Notebook    | [be7c6d7a43](https://linux-hardware.org/?probe=be7c6d7a43) | Nov 03, 2024 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [5f720cc296](https://linux-hardware.org/?probe=5f720cc296) | Nov 02, 2024 |
| Gigabyte      | P75-D3                      | Desktop     | [7ba3b8a5aa](https://linux-hardware.org/?probe=7ba3b8a5aa) | Nov 02, 2024 |
| Toshiba       | TECRA A10                   | Notebook    | [f7cfa0f796](https://linux-hardware.org/?probe=f7cfa0f796) | Nov 02, 2024 |
| Acer          | EG43M                       | Desktop     | [481ae677a2](https://linux-hardware.org/?probe=481ae677a2) | Nov 02, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [bed04a9e0f](https://linux-hardware.org/?probe=bed04a9e0f) | Nov 01, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [480e9ee913](https://linux-hardware.org/?probe=480e9ee913) | Nov 01, 2024 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [860ef2c633](https://linux-hardware.org/?probe=860ef2c633) | Nov 01, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [5c2dacf3d8](https://linux-hardware.org/?probe=5c2dacf3d8) | Nov 01, 2024 |
| Acer          | Aspire 7736                 | Notebook    | [9426ed7aff](https://linux-hardware.org/?probe=9426ed7aff) | Nov 01, 2024 |
| ASUSTek       | H81M-A                      | Desktop     | [04eef716a6](https://linux-hardware.org/?probe=04eef716a6) | Nov 01, 2024 |
| Lenovo        | IdeaPad Y400 20192          | Notebook    | [af8c167505](https://linux-hardware.org/?probe=af8c167505) | Oct 31, 2024 |
| Sony          | SVF1521G6EW                 | Notebook    | [5b4ce22a73](https://linux-hardware.org/?probe=5b4ce22a73) | Oct 31, 2024 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [53e1cfff12](https://linux-hardware.org/?probe=53e1cfff12) | Oct 31, 2024 |
| Gigabyte      | P31-ES3G                    | Desktop     | [cecda20fcc](https://linux-hardware.org/?probe=cecda20fcc) | Oct 31, 2024 |
| Intel         | B75                         | Desktop     | [c48a602eae](https://linux-hardware.org/?probe=c48a602eae) | Oct 31, 2024 |
| ASRock        | H81M-HDS                    | Desktop     | [aef95abb88](https://linux-hardware.org/?probe=aef95abb88) | Oct 31, 2024 |
| ASUSTek       | P5Q                         | Desktop     | [da83835b83](https://linux-hardware.org/?probe=da83835b83) | Oct 30, 2024 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [67af4a9e08](https://linux-hardware.org/?probe=67af4a9e08) | Oct 29, 2024 |
| HP            | EliteBook 660 16 inch G1... | Notebook    | [7de8e9c733](https://linux-hardware.org/?probe=7de8e9c733) | Oct 29, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [ef0b873549](https://linux-hardware.org/?probe=ef0b873549) | Oct 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | Notebook    | [a8f6e54a85](https://linux-hardware.org/?probe=a8f6e54a85) | Oct 29, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [046f64be70](https://linux-hardware.org/?probe=046f64be70) | Oct 28, 2024 |
| HP            | 0B4Ch D                     | Desktop     | [4488b0b5e6](https://linux-hardware.org/?probe=4488b0b5e6) | Oct 28, 2024 |
| OEM           | X79G                        | Desktop     | [3ae4c25ee7](https://linux-hardware.org/?probe=3ae4c25ee7) | Oct 28, 2024 |
| ASUSTek       | X553MA                      | Notebook    | [ea7d1235b1](https://linux-hardware.org/?probe=ea7d1235b1) | Oct 28, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [862c7cc007](https://linux-hardware.org/?probe=862c7cc007) | Oct 27, 2024 |
| HP            | Unknown                     | Notebook    | [f8c7a5f55f](https://linux-hardware.org/?probe=f8c7a5f55f) | Oct 27, 2024 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [b4a0691988](https://linux-hardware.org/?probe=b4a0691988) | Oct 27, 2024 |
| ASUSTek       | A88X-PRO                    | Desktop     | [5e1dd8eae1](https://linux-hardware.org/?probe=5e1dd8eae1) | Oct 27, 2024 |
| Gigabyte      | B75M-D3H                    | Desktop     | [98e2047b3e](https://linux-hardware.org/?probe=98e2047b3e) | Oct 27, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [30df458d10](https://linux-hardware.org/?probe=30df458d10) | Oct 26, 2024 |
| MSI           | CSM-H81M-P32                | Desktop     | [375a0a6487](https://linux-hardware.org/?probe=375a0a6487) | Oct 26, 2024 |
| Fujitsu       | D3227-A1 S26361-D3227-A1    | Desktop     | [4edc7c0869](https://linux-hardware.org/?probe=4edc7c0869) | Oct 26, 2024 |
| Lenovo        | ThinkPad E16 Gen 2 21M5C... | Notebook    | [5a31a97e2b](https://linux-hardware.org/?probe=5a31a97e2b) | Oct 26, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [0801976824](https://linux-hardware.org/?probe=0801976824) | Oct 26, 2024 |
| Acer          | TravelMate Spin B118-G2-... | Convertible | [961e873e35](https://linux-hardware.org/?probe=961e873e35) | Oct 26, 2024 |
| Biostar       | A10N-8800E                  | Desktop     | [5710a05f5f](https://linux-hardware.org/?probe=5710a05f5f) | Oct 26, 2024 |
| Gigabyte      | H55M-S2H                    | Desktop     | [08aa1a4721](https://linux-hardware.org/?probe=08aa1a4721) | Oct 25, 2024 |
| HP            | 15                          | Notebook    | [6a2e246381](https://linux-hardware.org/?probe=6a2e246381) | Oct 25, 2024 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [61d6f4f9da](https://linux-hardware.org/?probe=61d6f4f9da) | Oct 25, 2024 |
| Intel         | DP45SG AAE27733-402         | Desktop     | [80022aa1fa](https://linux-hardware.org/?probe=80022aa1fa) | Oct 24, 2024 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [8cf1a27cdd](https://linux-hardware.org/?probe=8cf1a27cdd) | Oct 24, 2024 |
| Lenovo        | ThinkPad P51 20HJS52P00     | Notebook    | [ab7bfcceb7](https://linux-hardware.org/?probe=ab7bfcceb7) | Oct 24, 2024 |
| Acer          | Aspire 7736                 | Notebook    | [213995eb9a](https://linux-hardware.org/?probe=213995eb9a) | Oct 24, 2024 |
| Lenovo        | G50-80 80E5                 | Notebook    | [38f6fb752d](https://linux-hardware.org/?probe=38f6fb752d) | Oct 23, 2024 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [e459f477ce](https://linux-hardware.org/?probe=e459f477ce) | Oct 23, 2024 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [15b278bc6b](https://linux-hardware.org/?probe=15b278bc6b) | Oct 23, 2024 |
| HP            | Pavilion 17                 | Notebook    | [fe2ac723ed](https://linux-hardware.org/?probe=fe2ac723ed) | Oct 23, 2024 |
| Intel         | DG31PR AAE58249-306         | Desktop     | [29d5c95cb2](https://linux-hardware.org/?probe=29d5c95cb2) | Oct 22, 2024 |
| Toshiba       | Satellite L55-B             | Notebook    | [e3b609b13a](https://linux-hardware.org/?probe=e3b609b13a) | Oct 22, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [053292a4a6](https://linux-hardware.org/?probe=053292a4a6) | Oct 21, 2024 |
| Intel         | JSL MRD                     | Desktop     | [77928ce492](https://linux-hardware.org/?probe=77928ce492) | Oct 21, 2024 |
| MSI           | G41TM-P31                   | Desktop     | [4a0f7d5481](https://linux-hardware.org/?probe=4a0f7d5481) | Oct 21, 2024 |
| Lenovo        | Unknown                     | Notebook    | [0c10558175](https://linux-hardware.org/?probe=0c10558175) | Oct 21, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1c9e79aeac](https://linux-hardware.org/?probe=1c9e79aeac) | Oct 20, 2024 |
| Fujitsu       | D3222-B1 S26361-D3222-B1    | Desktop     | [29167809af](https://linux-hardware.org/?probe=29167809af) | Oct 20, 2024 |
| Dell          | 02YRK5 A02                  | Desktop     | [b1ba54be2e](https://linux-hardware.org/?probe=b1ba54be2e) | Oct 20, 2024 |
| HP            | Presario CQ61               | Notebook    | [87aea4a07b](https://linux-hardware.org/?probe=87aea4a07b) | Oct 20, 2024 |
| Lenovo        | B50-10 80QR                 | Notebook    | [6b27d730b2](https://linux-hardware.org/?probe=6b27d730b2) | Oct 20, 2024 |
| ASUSTek       | H61M-K                      | Desktop     | [50de29919f](https://linux-hardware.org/?probe=50de29919f) | Oct 19, 2024 |
| HP            | 212A                        | Desktop     | [5af12ae426](https://linux-hardware.org/?probe=5af12ae426) | Oct 19, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [74bfaad70a](https://linux-hardware.org/?probe=74bfaad70a) | Oct 18, 2024 |
| Dell          | Venue 8 Pro 5855            | Notebook    | [305bc7f736](https://linux-hardware.org/?probe=305bc7f736) | Oct 17, 2024 |
| Acer          | Aspire A515-44              | Notebook    | [6a2f0efb2e](https://linux-hardware.org/?probe=6a2f0efb2e) | Oct 17, 2024 |
| Intel         | JSL MRD                     | Desktop     | [3e4834107b](https://linux-hardware.org/?probe=3e4834107b) | Oct 17, 2024 |
| Intel         | H61                         | Desktop     | [a4dc63e432](https://linux-hardware.org/?probe=a4dc63e432) | Oct 16, 2024 |
| MSI           | Z490-A PRO                  | Desktop     | [4a31262892](https://linux-hardware.org/?probe=4a31262892) | Oct 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [5a3c293945](https://linux-hardware.org/?probe=5a3c293945) | Oct 15, 2024 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [bf8a04a93c](https://linux-hardware.org/?probe=bf8a04a93c) | Oct 15, 2024 |
| Pegatron      | Benicia                     | Desktop     | [cd156adfd2](https://linux-hardware.org/?probe=cd156adfd2) | Oct 14, 2024 |
| ASUSTek       | UL80VT                      | Notebook    | [c6cc761721](https://linux-hardware.org/?probe=c6cc761721) | Oct 13, 2024 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [af7ced3aff](https://linux-hardware.org/?probe=af7ced3aff) | Oct 12, 2024 |
| ZOTAC         | ZBOX-CI327NANO-GS-01        | Mini pc     | [ba0b41d87c](https://linux-hardware.org/?probe=ba0b41d87c) | Oct 12, 2024 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [1e12bb1b07](https://linux-hardware.org/?probe=1e12bb1b07) | Oct 12, 2024 |
| AMD           | A88                         | Desktop     | [3442c71c38](https://linux-hardware.org/?probe=3442c71c38) | Oct 12, 2024 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [bd4f53dc99](https://linux-hardware.org/?probe=bd4f53dc99) | Oct 12, 2024 |
| Dell          | Latitude 7280               | Notebook    | [82d8484f17](https://linux-hardware.org/?probe=82d8484f17) | Oct 12, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [8126af742f](https://linux-hardware.org/?probe=8126af742f) | Oct 11, 2024 |
| Biostar       | G41D3C                      | Desktop     | [3301adecfb](https://linux-hardware.org/?probe=3301adecfb) | Oct 11, 2024 |
| Lenovo        | ThinkPad 20BHS18200         | Notebook    | [c576999dfa](https://linux-hardware.org/?probe=c576999dfa) | Oct 11, 2024 |
| ASUSTek       | K95VJ                       | Notebook    | [a3388fefc3](https://linux-hardware.org/?probe=a3388fefc3) | Oct 11, 2024 |
| Acer          | Aspire E5-772G              | Notebook    | [972163fef5](https://linux-hardware.org/?probe=972163fef5) | Oct 11, 2024 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [27e0df94ae](https://linux-hardware.org/?probe=27e0df94ae) | Oct 10, 2024 |
| MACHINIST     | X99 PR9-H                   | Desktop     | [a0ead70204](https://linux-hardware.org/?probe=a0ead70204) | Oct 09, 2024 |
| ASUSTek       | Q170M-C                     | Desktop     | [a8eab7ba48](https://linux-hardware.org/?probe=a8eab7ba48) | Oct 08, 2024 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [298822d4c4](https://linux-hardware.org/?probe=298822d4c4) | Oct 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [243cf71860](https://linux-hardware.org/?probe=243cf71860) | Oct 08, 2024 |
| Fujitsu       | LIFEBOOK N532               | Notebook    | [4b20b9cc8e](https://linux-hardware.org/?probe=4b20b9cc8e) | Oct 08, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [09ec6297c1](https://linux-hardware.org/?probe=09ec6297c1) | Oct 08, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [c405b895c9](https://linux-hardware.org/?probe=c405b895c9) | Oct 08, 2024 |
| Firebat_Co... | T8_Plus                     | Desktop     | [7b0c62125c](https://linux-hardware.org/?probe=7b0c62125c) | Oct 07, 2024 |
| ASUSTek       | P5K                         | Desktop     | [3c9825ba0b](https://linux-hardware.org/?probe=3c9825ba0b) | Oct 07, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [22a99a1444](https://linux-hardware.org/?probe=22a99a1444) | Oct 06, 2024 |
| ASUSTek       | A55BM-K                     | Desktop     | [a10e7e5307](https://linux-hardware.org/?probe=a10e7e5307) | Oct 06, 2024 |
| Acer          | Aspire 4738                 | Notebook    | [d7bd115a64](https://linux-hardware.org/?probe=d7bd115a64) | Oct 05, 2024 |
| Dell          | Latitude 5420               | Notebook    | [e65d154af3](https://linux-hardware.org/?probe=e65d154af3) | Oct 05, 2024 |
| MACHINIST     | X99 PR9-H                   | Desktop     | [79d889bb1d](https://linux-hardware.org/?probe=79d889bb1d) | Oct 04, 2024 |
| Biostar       | A960D+                      | Desktop     | [10e003ed0a](https://linux-hardware.org/?probe=10e003ed0a) | Oct 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [57602cd2d9](https://linux-hardware.org/?probe=57602cd2d9) | Oct 04, 2024 |
| Unknown       | Unknown                     | Notebook    | [5b967ea1be](https://linux-hardware.org/?probe=5b967ea1be) | Oct 04, 2024 |
| ASUSTek       | K53E                        | Notebook    | [62915aba3a](https://linux-hardware.org/?probe=62915aba3a) | Oct 03, 2024 |
| MSI           | Z790 GAMING PLUS WIFI       | Desktop     | [7258a3f215](https://linux-hardware.org/?probe=7258a3f215) | Oct 03, 2024 |
| ASRock        | X570 Phantom Gaming 4 Wi... | Desktop     | [b057221ffa](https://linux-hardware.org/?probe=b057221ffa) | Oct 03, 2024 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [9d076b194d](https://linux-hardware.org/?probe=9d076b194d) | Oct 02, 2024 |
| HP            | 8767 A                      | Desktop     | [8243a00195](https://linux-hardware.org/?probe=8243a00195) | Oct 02, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [dfea07d14a](https://linux-hardware.org/?probe=dfea07d14a) | Oct 02, 2024 |
| ASUSTek       | F2A55-M LK PLUS             | Desktop     | [2fdfd4a0ca](https://linux-hardware.org/?probe=2fdfd4a0ca) | Oct 01, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d9813a1e38](https://linux-hardware.org/?probe=d9813a1e38) | Oct 01, 2024 |
| Dell          | Inspiron N5040              | Notebook    | [d09e43e3e6](https://linux-hardware.org/?probe=d09e43e3e6) | Oct 01, 2024 |
| Acer          | Aspire ES1-531              | Notebook    | [16c5519c67](https://linux-hardware.org/?probe=16c5519c67) | Sep 30, 2024 |
| Positivo      | R516512AI-15                | Notebook    | [ea6017ef32](https://linux-hardware.org/?probe=ea6017ef32) | Sep 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [36174c650c](https://linux-hardware.org/?probe=36174c650c) | Sep 30, 2024 |
| HP            | Laptop 17-cp2xxx            | Notebook    | [8d69c2070e](https://linux-hardware.org/?probe=8d69c2070e) | Sep 29, 2024 |
| Medion        | Akoya P7632                 | Notebook    | [4a73c4ece4](https://linux-hardware.org/?probe=4a73c4ece4) | Sep 29, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [205dba9239](https://linux-hardware.org/?probe=205dba9239) | Sep 29, 2024 |
| Gigabyte      | B450 AORUS ELITE V2         | Desktop     | [d68ba4aa7a](https://linux-hardware.org/?probe=d68ba4aa7a) | Sep 29, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M370... | Notebook    | [b94dbc9df1](https://linux-hardware.org/?probe=b94dbc9df1) | Sep 28, 2024 |
| Unknown       | AX15                        | Notebook    | [cdbf528af6](https://linux-hardware.org/?probe=cdbf528af6) | Sep 28, 2024 |
| Medion        | P17619                      | Notebook    | [42d84ccf7c](https://linux-hardware.org/?probe=42d84ccf7c) | Sep 27, 2024 |
| Gigabyte      | X58A-UD5                    | Desktop     | [a6c2b82581](https://linux-hardware.org/?probe=a6c2b82581) | Sep 27, 2024 |
| ASUSTek       | M5A88-M                     | Desktop     | [5725f8c2e1](https://linux-hardware.org/?probe=5725f8c2e1) | Sep 26, 2024 |
| HP            | EliteBook 725 G3            | Notebook    | [59140deeed](https://linux-hardware.org/?probe=59140deeed) | Sep 26, 2024 |
| Lenovo        | ThinkPad X13 Gen 4 21EXS... | Notebook    | [9cec35ca8e](https://linux-hardware.org/?probe=9cec35ca8e) | Sep 26, 2024 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | Notebook    | [f7c17077ac](https://linux-hardware.org/?probe=f7c17077ac) | Sep 26, 2024 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3ebe7fc112](https://linux-hardware.org/?probe=3ebe7fc112) | Sep 26, 2024 |
| Colorful T... | C.A68HM PRO V14             | Desktop     | [524b75af5e](https://linux-hardware.org/?probe=524b75af5e) | Sep 25, 2024 |
| Acer          | Aspire 2920                 | Notebook    | [bf3d0d6e64](https://linux-hardware.org/?probe=bf3d0d6e64) | Sep 24, 2024 |
| Dell          | System XPS L321X            | Notebook    | [461ff95992](https://linux-hardware.org/?probe=461ff95992) | Sep 24, 2024 |
| HP            | ProBook 4445s               | Notebook    | [64c920edf6](https://linux-hardware.org/?probe=64c920edf6) | Sep 24, 2024 |
| Acer          | FIH57                       | Desktop     | [d281d08f5b](https://linux-hardware.org/?probe=d281d08f5b) | Sep 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [ecb482f9a9](https://linux-hardware.org/?probe=ecb482f9a9) | Sep 24, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1738960295](https://linux-hardware.org/?probe=1738960295) | Sep 24, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [9d54da4f94](https://linux-hardware.org/?probe=9d54da4f94) | Sep 23, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c2b79a6905](https://linux-hardware.org/?probe=c2b79a6905) | Sep 23, 2024 |
| ASUSTek       | T101HA                      | Tablet      | [09ebca352a](https://linux-hardware.org/?probe=09ebca352a) | Sep 23, 2024 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [262e1993ad](https://linux-hardware.org/?probe=262e1993ad) | Sep 23, 2024 |
| HP            | Compaq 2510p                | Notebook    | [d0b68bbc55](https://linux-hardware.org/?probe=d0b68bbc55) | Sep 23, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [e9f25fa551](https://linux-hardware.org/?probe=e9f25fa551) | Sep 23, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [ae87bd81f4](https://linux-hardware.org/?probe=ae87bd81f4) | Sep 23, 2024 |
| Gigabyte      | H55M-USB3                   | Desktop     | [ddffc54d59](https://linux-hardware.org/?probe=ddffc54d59) | Sep 22, 2024 |
| ASUSTek       | M50Vn                       | Notebook    | [2e22fd3bd2](https://linux-hardware.org/?probe=2e22fd3bd2) | Sep 22, 2024 |
| ASUSTek       | X555LJ                      | Notebook    | [9dc481d73a](https://linux-hardware.org/?probe=9dc481d73a) | Sep 22, 2024 |
| Dell          | Latitude E5520m             | Notebook    | [a2933b9960](https://linux-hardware.org/?probe=a2933b9960) | Sep 22, 2024 |
| JGINYUE       | H81M VH PLUS V1.1           | Desktop     | [15128e9c08](https://linux-hardware.org/?probe=15128e9c08) | Sep 22, 2024 |
| Toshiba       | Satellite C645              | Notebook    | [1a789a141f](https://linux-hardware.org/?probe=1a789a141f) | Sep 21, 2024 |
| Acer          | Aspire A315-24P             | Notebook    | [8cd51dbb86](https://linux-hardware.org/?probe=8cd51dbb86) | Sep 21, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [a8d9d98b2e](https://linux-hardware.org/?probe=a8d9d98b2e) | Sep 20, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [55c567c63a](https://linux-hardware.org/?probe=55c567c63a) | Sep 20, 2024 |
| ATOPNUC       | MA90                        | Mini pc     | [a3dbfe6a67](https://linux-hardware.org/?probe=a3dbfe6a67) | Sep 20, 2024 |
| Dell          | 0D28YY A00                  | Desktop     | [6002c0cb97](https://linux-hardware.org/?probe=6002c0cb97) | Sep 19, 2024 |
| Lenovo        | V15 G2 IJL 82QY             | Notebook    | [8b47709edb](https://linux-hardware.org/?probe=8b47709edb) | Sep 19, 2024 |
| Gigabyte      | H310N                       | Desktop     | [d1452d296c](https://linux-hardware.org/?probe=d1452d296c) | Sep 19, 2024 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [02501a0d37](https://linux-hardware.org/?probe=02501a0d37) | Sep 18, 2024 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [cc853b4c1a](https://linux-hardware.org/?probe=cc853b4c1a) | Sep 17, 2024 |
| Positivo      | EC10IS1                     | Notebook    | [e715b4c073](https://linux-hardware.org/?probe=e715b4c073) | Sep 16, 2024 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [3bbcc1fdfa](https://linux-hardware.org/?probe=3bbcc1fdfa) | Sep 16, 2024 |
| Shenzhen M... | F7BAA                       | Desktop     | [0e7cb8c966](https://linux-hardware.org/?probe=0e7cb8c966) | Sep 16, 2024 |
| Dell          | 088DT1 A01                  | Desktop     | [4121f94162](https://linux-hardware.org/?probe=4121f94162) | Sep 15, 2024 |
| AZW           | SER V1                      | Desktop     | [2a711515ce](https://linux-hardware.org/?probe=2a711515ce) | Sep 15, 2024 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [833d4acd21](https://linux-hardware.org/?probe=833d4acd21) | Sep 15, 2024 |
| ZOTAC         | NM10                        | Desktop     | [d75d2e7290](https://linux-hardware.org/?probe=d75d2e7290) | Sep 15, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [6819a810d2](https://linux-hardware.org/?probe=6819a810d2) | Sep 14, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [5ea056f887](https://linux-hardware.org/?probe=5ea056f887) | Sep 14, 2024 |
| Gigabyte      | P110-D3-CF                  | Desktop     | [11179fcd4d](https://linux-hardware.org/?probe=11179fcd4d) | Sep 13, 2024 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [661cd77af8](https://linux-hardware.org/?probe=661cd77af8) | Sep 13, 2024 |
| Acer          | Aspire A315-22              | Notebook    | [b2466dce41](https://linux-hardware.org/?probe=b2466dce41) | Sep 13, 2024 |
| Intel         | B75                         | Desktop     | [3fffe506e7](https://linux-hardware.org/?probe=3fffe506e7) | Sep 13, 2024 |
| MACHINIST     | H97M-PRO V1.1               | Desktop     | [e4e066a84a](https://linux-hardware.org/?probe=e4e066a84a) | Sep 12, 2024 |
| ASUSTek       | X55U                        | Notebook    | [ce77419d34](https://linux-hardware.org/?probe=ce77419d34) | Sep 12, 2024 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [6759b6dbf3](https://linux-hardware.org/?probe=6759b6dbf3) | Sep 11, 2024 |
| Gigabyte      | B360M DS3H                  | Desktop     | [6318508130](https://linux-hardware.org/?probe=6318508130) | Sep 11, 2024 |
| Lenovo        | Annapurna CRB NOK           | Desktop     | [b4e8188de1](https://linux-hardware.org/?probe=b4e8188de1) | Sep 11, 2024 |
| Dell          | 07N90W A01                  | Desktop     | [11eb8aa4dc](https://linux-hardware.org/?probe=11eb8aa4dc) | Sep 11, 2024 |
| Positivo      | POS-EINM70CS POSITIVO       | Desktop     | [f593400ff4](https://linux-hardware.org/?probe=f593400ff4) | Sep 10, 2024 |
| Lenovo        | IdeaPad Y580                | Notebook    | [885fa56235](https://linux-hardware.org/?probe=885fa56235) | Sep 10, 2024 |
| Positivo      | R78256AI-15                 | Notebook    | [c848ae7984](https://linux-hardware.org/?probe=c848ae7984) | Sep 10, 2024 |
| HP            | 8265                        | Desktop     | [43b7b19d0e](https://linux-hardware.org/?probe=43b7b19d0e) | Sep 09, 2024 |
| Gigabyte X... | 56547AHJ29 1167789          | Desktop     | [01030238e9](https://linux-hardware.org/?probe=01030238e9) | Sep 08, 2024 |
| HP            | EliteBook 6930p             | Notebook    | [7559a6af2d](https://linux-hardware.org/?probe=7559a6af2d) | Sep 08, 2024 |
| Dell          | Inspiron 3585               | Notebook    | [16ca949774](https://linux-hardware.org/?probe=16ca949774) | Sep 07, 2024 |
| Biostar       | B550M-SILVER                | Desktop     | [78c5e356b9](https://linux-hardware.org/?probe=78c5e356b9) | Sep 07, 2024 |
| ASUSTek       | H97-PLUS                    | Desktop     | [1c314094d5](https://linux-hardware.org/?probe=1c314094d5) | Sep 07, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [0fd5cb15da](https://linux-hardware.org/?probe=0fd5cb15da) | Sep 07, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e91782f4a9](https://linux-hardware.org/?probe=e91782f4a9) | Sep 07, 2024 |
| HP            | ZBook 17 G5                 | Notebook    | [1a6e1fc880](https://linux-hardware.org/?probe=1a6e1fc880) | Sep 06, 2024 |
| ASUSTek       | H61M-K                      | Desktop     | [994c8510c9](https://linux-hardware.org/?probe=994c8510c9) | Sep 06, 2024 |
| Acer          | Aspire M3970                | Desktop     | [5c1577174f](https://linux-hardware.org/?probe=5c1577174f) | Sep 06, 2024 |
| Lenovo        | ThinkPad T430 2347AY1       | Notebook    | [2f46f3ae95](https://linux-hardware.org/?probe=2f46f3ae95) | Sep 06, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [bc89477644](https://linux-hardware.org/?probe=bc89477644) | Sep 06, 2024 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [5a7048fbe0](https://linux-hardware.org/?probe=5a7048fbe0) | Sep 06, 2024 |
| Samsung       | R530/R730                   | Notebook    | [ca05ca0a68](https://linux-hardware.org/?probe=ca05ca0a68) | Sep 06, 2024 |
| Acer          | Aspire 7250                 | Notebook    | [fcf41d5a9d](https://linux-hardware.org/?probe=fcf41d5a9d) | Sep 05, 2024 |
| Acer          | Peppy                       | Notebook    | [e797f3ccb1](https://linux-hardware.org/?probe=e797f3ccb1) | Sep 05, 2024 |
| Acer          | Aspire A315-21G             | Notebook    | [1bd863c2c2](https://linux-hardware.org/?probe=1bd863c2c2) | Sep 05, 2024 |
| ASRock        | A520M Pro4                  | Desktop     | [2a716a1e08](https://linux-hardware.org/?probe=2a716a1e08) | Sep 05, 2024 |
| Dell          | Latitude E7450              | Notebook    | [c8f4f19e88](https://linux-hardware.org/?probe=c8f4f19e88) | Sep 05, 2024 |
| HP            | EliteBook 840 G1            | Notebook    | [453cbe339f](https://linux-hardware.org/?probe=453cbe339f) | Sep 05, 2024 |
| Dell          | Latitude 5580               | Notebook    | [dc0f01dc48](https://linux-hardware.org/?probe=dc0f01dc48) | Sep 04, 2024 |
| Philco        | 14H                         | Notebook    | [77e51c14b8](https://linux-hardware.org/?probe=77e51c14b8) | Sep 04, 2024 |
| Quanta        | QL3 TBD                     | Notebook    | [f3a35430d8](https://linux-hardware.org/?probe=f3a35430d8) | Sep 04, 2024 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [7ff9eab924](https://linux-hardware.org/?probe=7ff9eab924) | Sep 03, 2024 |
| Gigabyte      | A520I AC                    | Desktop     | [5351be60b3](https://linux-hardware.org/?probe=5351be60b3) | Sep 03, 2024 |
| ASRock        | H67M                        | Desktop     | [755733f8ee](https://linux-hardware.org/?probe=755733f8ee) | Sep 03, 2024 |
| Dell          | Inspiron N5110              | Notebook    | [118508fdea](https://linux-hardware.org/?probe=118508fdea) | Sep 03, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [27131910d0](https://linux-hardware.org/?probe=27131910d0) | Sep 03, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [fd045954b3](https://linux-hardware.org/?probe=fd045954b3) | Sep 03, 2024 |
| Dell          | Studio 1749                 | Notebook    | [d74513a21f](https://linux-hardware.org/?probe=d74513a21f) | Sep 03, 2024 |
| HP            | 212B                        | Desktop     | [1d3fb28940](https://linux-hardware.org/?probe=1d3fb28940) | Sep 03, 2024 |
| Intel         | DH67BL AAG10189-213         | Desktop     | [e151ff7acf](https://linux-hardware.org/?probe=e151ff7acf) | Sep 02, 2024 |
| Lenovo        | IdeaPad Slim 5 16IMH9 83... | Notebook    | [ad77d695dc](https://linux-hardware.org/?probe=ad77d695dc) | Sep 02, 2024 |
| ASUSTek       | N53SN                       | Notebook    | [ebce5d0691](https://linux-hardware.org/?probe=ebce5d0691) | Sep 02, 2024 |
| ASUSTek       | K72F                        | Notebook    | [972b65066a](https://linux-hardware.org/?probe=972b65066a) | Sep 02, 2024 |
| Positivo      | S14BW01                     | Notebook    | [436d9031f2](https://linux-hardware.org/?probe=436d9031f2) | Sep 02, 2024 |
| Google        | Auron_Paine                 | Notebook    | [1b6d737594](https://linux-hardware.org/?probe=1b6d737594) | Sep 02, 2024 |
| HP            | Pavilion dv6700             | Notebook    | [d9b6ec66bd](https://linux-hardware.org/?probe=d9b6ec66bd) | Sep 02, 2024 |
| Acer          | Swift SFG16-71              | Notebook    | [99dba8223c](https://linux-hardware.org/?probe=99dba8223c) | Sep 02, 2024 |
| HP            | EliteBook 2170p             | Notebook    | [8b5d0ed681](https://linux-hardware.org/?probe=8b5d0ed681) | Sep 02, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [4519bc4d0b](https://linux-hardware.org/?probe=4519bc4d0b) | Sep 01, 2024 |
| HP            | EliteBook 2170p             | Notebook    | [84a821b49c](https://linux-hardware.org/?probe=84a821b49c) | Sep 01, 2024 |
| ASUSTek       | N3050T                      | Desktop     | [9c852a30a0](https://linux-hardware.org/?probe=9c852a30a0) | Sep 01, 2024 |
| ASUSTek       | K53TA                       | Notebook    | [97e98f408d](https://linux-hardware.org/?probe=97e98f408d) | Sep 01, 2024 |
| ASUSTek       | H87M-E                      | Desktop     | [d96d545feb](https://linux-hardware.org/?probe=d96d545feb) | Aug 31, 2024 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [4439caab2a](https://linux-hardware.org/?probe=4439caab2a) | Aug 31, 2024 |
| Fujitsu       | D3219-A1 S26361-D3219-A1    | Desktop     | [f67aa32eca](https://linux-hardware.org/?probe=f67aa32eca) | Aug 31, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [d1faa56159](https://linux-hardware.org/?probe=d1faa56159) | Aug 30, 2024 |
| Acer          | Swift SFE16-44              | Notebook    | [bce51aa43e](https://linux-hardware.org/?probe=bce51aa43e) | Aug 30, 2024 |
| ASRock        | H81M-VG4                    | Desktop     | [5a4c31c811](https://linux-hardware.org/?probe=5a4c31c811) | Aug 30, 2024 |
| JP.ik         | T304                        | Notebook    | [bf5d965733](https://linux-hardware.org/?probe=bf5d965733) | Aug 30, 2024 |
| Compaq        | Presario CQ-21              | Notebook    | [4c41e71d5a](https://linux-hardware.org/?probe=4c41e71d5a) | Aug 30, 2024 |
| Pegatron      | JESSE                       | Desktop     | [1e3f996dc4](https://linux-hardware.org/?probe=1e3f996dc4) | Aug 30, 2024 |
| HP            | Presario CQ58               | Notebook    | [5ab969b08b](https://linux-hardware.org/?probe=5ab969b08b) | Aug 29, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [8962b342ad](https://linux-hardware.org/?probe=8962b342ad) | Aug 29, 2024 |
| HP            | ENVY x360 Convertible 15... | Convertible | [84f2c54d89](https://linux-hardware.org/?probe=84f2c54d89) | Aug 29, 2024 |
| HP            | 8648                        | Desktop     | [cd449a247f](https://linux-hardware.org/?probe=cd449a247f) | Aug 29, 2024 |
| ASUSTek       | Pro H610M-C D4              | Desktop     | [1b20c180f0](https://linux-hardware.org/?probe=1b20c180f0) | Aug 29, 2024 |
| Dell          | 07N90W A02                  | Desktop     | [678eed9a97](https://linux-hardware.org/?probe=678eed9a97) | Aug 28, 2024 |
| Medion        | E6214                       | Notebook    | [255b7c37ae](https://linux-hardware.org/?probe=255b7c37ae) | Aug 28, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [223cfb4921](https://linux-hardware.org/?probe=223cfb4921) | Aug 28, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [91228a363f](https://linux-hardware.org/?probe=91228a363f) | Aug 28, 2024 |
| Intel         | H61 V1.5                    | Desktop     | [ca29674330](https://linux-hardware.org/?probe=ca29674330) | Aug 28, 2024 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [06c70b0344](https://linux-hardware.org/?probe=06c70b0344) | Aug 28, 2024 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | Notebook    | [fc08bf5897](https://linux-hardware.org/?probe=fc08bf5897) | Aug 28, 2024 |
| MSI           | H61M-P21                    | Desktop     | [b492068c78](https://linux-hardware.org/?probe=b492068c78) | Aug 28, 2024 |
| Lenovo        | ThinkPad X130e 0629A12      | Notebook    | [c751cc848d](https://linux-hardware.org/?probe=c751cc848d) | Aug 28, 2024 |
| Acer          | Aspire R3-131T              | Notebook    | [210b362894](https://linux-hardware.org/?probe=210b362894) | Aug 28, 2024 |
| Dell          | Latitude E7470              | Notebook    | [cd0b24759b](https://linux-hardware.org/?probe=cd0b24759b) | Aug 27, 2024 |
| Dell          | Inspiron 3481               | Notebook    | [eb002a3b83](https://linux-hardware.org/?probe=eb002a3b83) | Aug 27, 2024 |
| ASRock        | A320M Pro4                  | Desktop     | [537d144744](https://linux-hardware.org/?probe=537d144744) | Aug 27, 2024 |
| ASRock        | H61M-S                      | Desktop     | [6f46ff8666](https://linux-hardware.org/?probe=6f46ff8666) | Aug 27, 2024 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [c65444e5a7](https://linux-hardware.org/?probe=c65444e5a7) | Aug 27, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [be116bc4fe](https://linux-hardware.org/?probe=be116bc4fe) | Aug 27, 2024 |
| HP            | EliteBook 840 G5            | Notebook    | [1ef6676af1](https://linux-hardware.org/?probe=1ef6676af1) | Aug 27, 2024 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [bf763401f5](https://linux-hardware.org/?probe=bf763401f5) | Aug 27, 2024 |
| Toshiba       | Satellite A505              | Notebook    | [61aa2bba95](https://linux-hardware.org/?probe=61aa2bba95) | Aug 26, 2024 |
| ASUSTek       | H110M-K                     | Desktop     | [7a42e68f76](https://linux-hardware.org/?probe=7a42e68f76) | Aug 26, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [9dcdd198a6](https://linux-hardware.org/?probe=9dcdd198a6) | Aug 26, 2024 |
| HP            | 8618                        | Desktop     | [6f804c5758](https://linux-hardware.org/?probe=6f804c5758) | Aug 26, 2024 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | Notebook    | [ce456c4a98](https://linux-hardware.org/?probe=ce456c4a98) | Aug 26, 2024 |
| Lenovo        | 3168 SDK0J40697 WIN 3305... | Desktop     | [19683c12d7](https://linux-hardware.org/?probe=19683c12d7) | Aug 26, 2024 |
| Dell          | 0M5DCD A00                  | Desktop     | [35eab4446f](https://linux-hardware.org/?probe=35eab4446f) | Aug 26, 2024 |
| Apple         | MacBook5,1                  | Notebook    | [69ab889544](https://linux-hardware.org/?probe=69ab889544) | Aug 26, 2024 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [2437ded49b](https://linux-hardware.org/?probe=2437ded49b) | Aug 26, 2024 |
| Dell          | Inspiron 3541               | Notebook    | [27ed9be416](https://linux-hardware.org/?probe=27ed9be416) | Aug 26, 2024 |
| Lenovo        | G70-70 80HW                 | Notebook    | [b801955e87](https://linux-hardware.org/?probe=b801955e87) | Aug 26, 2024 |
| Toshiba       | Satellite C845              | Notebook    | [e043e1d64a](https://linux-hardware.org/?probe=e043e1d64a) | Aug 25, 2024 |
| Fujitsu       | LIFEBOOK A555               | Notebook    | [0e7587f9eb](https://linux-hardware.org/?probe=0e7587f9eb) | Aug 25, 2024 |
| ASUSTek       | P5Q SE                      | Desktop     | [1e40e4bbc4](https://linux-hardware.org/?probe=1e40e4bbc4) | Aug 25, 2024 |
| Dynabook      | TECRA A40-G                 | Notebook    | [3ac4ac4f7a](https://linux-hardware.org/?probe=3ac4ac4f7a) | Aug 24, 2024 |
| ASRock        | FM2A75M-HD+                 | Desktop     | [cc00bdf2f2](https://linux-hardware.org/?probe=cc00bdf2f2) | Aug 24, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [18c81a5d40](https://linux-hardware.org/?probe=18c81a5d40) | Aug 24, 2024 |
| Dell          | 0DR845                      | Desktop     | [479d25843a](https://linux-hardware.org/?probe=479d25843a) | Aug 24, 2024 |
| Shenzhen M... | F7BSD                       | Mini pc     | [4c1e770e79](https://linux-hardware.org/?probe=4c1e770e79) | Aug 23, 2024 |
| ASUSTek       | CM1730,CM1830               | Desktop     | [ceb044885e](https://linux-hardware.org/?probe=ceb044885e) | Aug 23, 2024 |
| Red Hat       | RHEL RHEL-9.4.0 PC          | Desktop     | [e5b92fc048](https://linux-hardware.org/?probe=e5b92fc048) | Aug 23, 2024 |
| AMI           | Intel                       | Notebook    | [fb6e4c51ed](https://linux-hardware.org/?probe=fb6e4c51ed) | Aug 23, 2024 |
| HP            | 304Ah                       | Desktop     | [4d2c7bc8b2](https://linux-hardware.org/?probe=4d2c7bc8b2) | Aug 23, 2024 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [ebc8f6a03b](https://linux-hardware.org/?probe=ebc8f6a03b) | Aug 23, 2024 |
| Acer          | Aspire E1-570               | Notebook    | [d5cfa10750](https://linux-hardware.org/?probe=d5cfa10750) | Aug 22, 2024 |
| Dell          | 0VRWRC A00                  | Desktop     | [1cc469a71c](https://linux-hardware.org/?probe=1cc469a71c) | Aug 22, 2024 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [67ebefbd7c](https://linux-hardware.org/?probe=67ebefbd7c) | Aug 22, 2024 |
| Foxconn       | 17A0                        | Desktop     | [34e71b0b28](https://linux-hardware.org/?probe=34e71b0b28) | Aug 22, 2024 |
| Gigabyte      | AERO 16 XE4                 | Notebook    | [491d0f5415](https://linux-hardware.org/?probe=491d0f5415) | Aug 22, 2024 |
| MSI           | Bravo 15 B5DD               | Notebook    | [7e7ea801a9](https://linux-hardware.org/?probe=7e7ea801a9) | Aug 22, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0cd831a254](https://linux-hardware.org/?probe=0cd831a254) | Aug 22, 2024 |
| ASUSTek       | P8H67                       | Desktop     | [54e766f338](https://linux-hardware.org/?probe=54e766f338) | Aug 21, 2024 |
| Dell          | Inspiron 15-3565            | Notebook    | [c90ce327f2](https://linux-hardware.org/?probe=c90ce327f2) | Aug 21, 2024 |
| Gigabyte      | H310M DS2 x.x               | Desktop     | [bb51e6272b](https://linux-hardware.org/?probe=bb51e6272b) | Aug 21, 2024 |
| Gigabyte      | A520M S2H                   | Desktop     | [4013b39348](https://linux-hardware.org/?probe=4013b39348) | Aug 21, 2024 |
| ASRock        | Z97 Anniversary             | Desktop     | [9255d13688](https://linux-hardware.org/?probe=9255d13688) | Aug 20, 2024 |
| Dell          | 0TX755 A02                  | Desktop     | [782d19f6d0](https://linux-hardware.org/?probe=782d19f6d0) | Aug 20, 2024 |
| HP            | 1998                        | Desktop     | [7884402051](https://linux-hardware.org/?probe=7884402051) | Aug 20, 2024 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [24bb07bee7](https://linux-hardware.org/?probe=24bb07bee7) | Aug 19, 2024 |
| Dell          | Inspiron 1525               | Notebook    | [29292480d1](https://linux-hardware.org/?probe=29292480d1) | Aug 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | Notebook    | [080d34db04](https://linux-hardware.org/?probe=080d34db04) | Aug 19, 2024 |
| Dell          | 0773VG A02                  | Desktop     | [56a9b6f7e6](https://linux-hardware.org/?probe=56a9b6f7e6) | Aug 19, 2024 |
| HP            | 1497                        | Desktop     | [34025b9702](https://linux-hardware.org/?probe=34025b9702) | Aug 18, 2024 |
| ZOTAC         | NM10                        | Desktop     | [4244e8bb97](https://linux-hardware.org/?probe=4244e8bb97) | Aug 18, 2024 |
| Acer          | F690GVM                     | Desktop     | [f9f5665863](https://linux-hardware.org/?probe=f9f5665863) | Aug 18, 2024 |
| HP            | 2B34                        | Desktop     | [e440f003bd](https://linux-hardware.org/?probe=e440f003bd) | Aug 18, 2024 |
| Acer          | Aspire E5-571               | Notebook    | [e804efc22d](https://linux-hardware.org/?probe=e804efc22d) | Aug 18, 2024 |
| ASUSTek       | X551MA                      | Notebook    | [b113e06e29](https://linux-hardware.org/?probe=b113e06e29) | Aug 18, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [5a2f8eb128](https://linux-hardware.org/?probe=5a2f8eb128) | Aug 18, 2024 |
| Intel         | H55                         | Desktop     | [31b6348c05](https://linux-hardware.org/?probe=31b6348c05) | Aug 17, 2024 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [6bf836b973](https://linux-hardware.org/?probe=6bf836b973) | Aug 17, 2024 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [33cfb16c35](https://linux-hardware.org/?probe=33cfb16c35) | Aug 16, 2024 |
| ASRock        | X300M-STX                   | Desktop     | [39611ab403](https://linux-hardware.org/?probe=39611ab403) | Aug 16, 2024 |
| Unknown       | DeeQ                        | Notebook    | [4edc858d59](https://linux-hardware.org/?probe=4edc858d59) | Aug 15, 2024 |
| ASRock        | AB350M-HDV                  | Desktop     | [ad2f980ddf](https://linux-hardware.org/?probe=ad2f980ddf) | Aug 15, 2024 |
| Acer          | Extensa 5220                | Notebook    | [26093b3071](https://linux-hardware.org/?probe=26093b3071) | Aug 15, 2024 |
| Dell          | Inspiron 15 5510            | Notebook    | [7fd5e88801](https://linux-hardware.org/?probe=7fd5e88801) | Aug 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [252054bbbb](https://linux-hardware.org/?probe=252054bbbb) | Aug 14, 2024 |
| Acer          | Aspire A114-33              | Notebook    | [2a74f324ac](https://linux-hardware.org/?probe=2a74f324ac) | Aug 14, 2024 |
| ASUSTek       | X55SV                       | Notebook    | [4b41f17fba](https://linux-hardware.org/?probe=4b41f17fba) | Aug 14, 2024 |
| ASRock        | B85M-DGS                    | Desktop     | [70fd24795c](https://linux-hardware.org/?probe=70fd24795c) | Aug 14, 2024 |
| ASUSTek       | X541NA                      | Notebook    | [0d55582f37](https://linux-hardware.org/?probe=0d55582f37) | Aug 14, 2024 |
| Gigabyte      | B365M DS3H                  | Desktop     | [43968b561a](https://linux-hardware.org/?probe=43968b561a) | Aug 14, 2024 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [4b7514c640](https://linux-hardware.org/?probe=4b7514c640) | Aug 14, 2024 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [259992a3f9](https://linux-hardware.org/?probe=259992a3f9) | Aug 14, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [500702385c](https://linux-hardware.org/?probe=500702385c) | Aug 14, 2024 |
| HP            | EliteBook 830 G5            | Notebook    | [a091b4e48d](https://linux-hardware.org/?probe=a091b4e48d) | Aug 14, 2024 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [5a00bfee31](https://linux-hardware.org/?probe=5a00bfee31) | Aug 14, 2024 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [ba18c5a60e](https://linux-hardware.org/?probe=ba18c5a60e) | Aug 14, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3b88a5d126](https://linux-hardware.org/?probe=3b88a5d126) | Aug 14, 2024 |
| Positivo      | N1103                       | Notebook    | [299d981b42](https://linux-hardware.org/?probe=299d981b42) | Aug 14, 2024 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [009462564a](https://linux-hardware.org/?probe=009462564a) | Aug 13, 2024 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [a8e5c14cab](https://linux-hardware.org/?probe=a8e5c14cab) | Aug 13, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [140ac24212](https://linux-hardware.org/?probe=140ac24212) | Aug 13, 2024 |
| AZW           | MINI S 10                   | Desktop     | [ad35290a2c](https://linux-hardware.org/?probe=ad35290a2c) | Aug 13, 2024 |
| Gigabyte      | H610M K DDR4                | Desktop     | [513a80a2df](https://linux-hardware.org/?probe=513a80a2df) | Aug 13, 2024 |
| Dell          | Latitude E4200              | Notebook    | [320805a7cd](https://linux-hardware.org/?probe=320805a7cd) | Aug 13, 2024 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [ecf1f5843f](https://linux-hardware.org/?probe=ecf1f5843f) | Aug 13, 2024 |
| MSI           | GS70 2OD                    | Notebook    | [eb85cc42f6](https://linux-hardware.org/?probe=eb85cc42f6) | Aug 13, 2024 |
| Unknown       | Unknown                     | Notebook    | [0468a241e4](https://linux-hardware.org/?probe=0468a241e4) | Aug 13, 2024 |
| ASRock        | FM2A55M-DGS                 | Desktop     | [a5fa87c0d6](https://linux-hardware.org/?probe=a5fa87c0d6) | Aug 13, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [948de2035b](https://linux-hardware.org/?probe=948de2035b) | Aug 13, 2024 |
| Acer          | Extensa 5220                | Notebook    | [69c707d263](https://linux-hardware.org/?probe=69c707d263) | Aug 13, 2024 |
| HP            | 15                          | Notebook    | [a1f14f42dc](https://linux-hardware.org/?probe=a1f14f42dc) | Aug 12, 2024 |
| Dell          | Vostro 1700                 | Notebook    | [f8337e3827](https://linux-hardware.org/?probe=f8337e3827) | Aug 12, 2024 |
| HP            | Pavilion dv6                | Notebook    | [032f5f2535](https://linux-hardware.org/?probe=032f5f2535) | Aug 12, 2024 |
| LG Electro... | 14T90R-K.AA77A1             | Convertible | [1fdd013acc](https://linux-hardware.org/?probe=1fdd013acc) | Aug 12, 2024 |
| Dell          | 0N4YC8 A00                  | Desktop     | [065d3d77f8](https://linux-hardware.org/?probe=065d3d77f8) | Aug 12, 2024 |
| HP            | 3397                        | Desktop     | [da2b320cd5](https://linux-hardware.org/?probe=da2b320cd5) | Aug 12, 2024 |
| MSI           | PRO A620M-E                 | Desktop     | [89b83dcdb0](https://linux-hardware.org/?probe=89b83dcdb0) | Aug 12, 2024 |
| ASUSTek       | K53SM                       | Notebook    | [b3f8198314](https://linux-hardware.org/?probe=b3f8198314) | Aug 12, 2024 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [061482f47f](https://linux-hardware.org/?probe=061482f47f) | Aug 12, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [e867eec20b](https://linux-hardware.org/?probe=e867eec20b) | Aug 12, 2024 |
| VIT           | P2400                       | Notebook    | [b103ea6da4](https://linux-hardware.org/?probe=b103ea6da4) | Aug 12, 2024 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [26690c5356](https://linux-hardware.org/?probe=26690c5356) | Aug 12, 2024 |
| Samsung       | RC530/RC730                 | Notebook    | [04e7201341](https://linux-hardware.org/?probe=04e7201341) | Aug 11, 2024 |
| ASUSTek       | X750LA                      | Notebook    | [798b53356b](https://linux-hardware.org/?probe=798b53356b) | Aug 11, 2024 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [d089d7d1d3](https://linux-hardware.org/?probe=d089d7d1d3) | Aug 11, 2024 |
| Sony          | SVE14A25CFP                 | Notebook    | [35a1034271](https://linux-hardware.org/?probe=35a1034271) | Aug 11, 2024 |
| Dell          | Latitude 7390               | Notebook    | [1f851389e7](https://linux-hardware.org/?probe=1f851389e7) | Aug 11, 2024 |
| Chuwi         | LarkBox X                   | Mini pc     | [22da240cea](https://linux-hardware.org/?probe=22da240cea) | Aug 11, 2024 |
| Packard Be... | EasyNote TK11BZ             | Notebook    | [105ff99feb](https://linux-hardware.org/?probe=105ff99feb) | Aug 11, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [4fb9d317dd](https://linux-hardware.org/?probe=4fb9d317dd) | Aug 11, 2024 |
| Acer          | Extensa 215-22              | Notebook    | [a4cb78601b](https://linux-hardware.org/?probe=a4cb78601b) | Aug 11, 2024 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [051e8de774](https://linux-hardware.org/?probe=051e8de774) | Aug 11, 2024 |
| HP            | 198E                        | Desktop     | [21d03f44b1](https://linux-hardware.org/?probe=21d03f44b1) | Aug 11, 2024 |
| Acer          | Aspire V5-471PG             | Notebook    | [cffec3a7cb](https://linux-hardware.org/?probe=cffec3a7cb) | Aug 11, 2024 |
| Intel         | DZ77SL-50K AAG55115-300     | Desktop     | [c65f2e86cd](https://linux-hardware.org/?probe=c65f2e86cd) | Aug 11, 2024 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [aca5a2c925](https://linux-hardware.org/?probe=aca5a2c925) | Aug 10, 2024 |
| HP            | Unknown                     | Notebook    | [13b4b0bc1c](https://linux-hardware.org/?probe=13b4b0bc1c) | Aug 10, 2024 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [aa056d901f](https://linux-hardware.org/?probe=aa056d901f) | Aug 10, 2024 |
| HP            | Pavilion dv4                | Notebook    | [884ea6b76d](https://linux-hardware.org/?probe=884ea6b76d) | Aug 10, 2024 |
| Dell          | Latitude 7480               | Notebook    | [4b3df98ff0](https://linux-hardware.org/?probe=4b3df98ff0) | Aug 09, 2024 |
| Toshiba       | Satellite C75D-B            | Notebook    | [5be070a7d0](https://linux-hardware.org/?probe=5be070a7d0) | Aug 09, 2024 |
| HP            | EliteBook 650 15.6 inch ... | Notebook    | [a832b68002](https://linux-hardware.org/?probe=a832b68002) | Aug 09, 2024 |
| Intel         | H61                         | Desktop     | [1fe94737e9](https://linux-hardware.org/?probe=1fe94737e9) | Aug 09, 2024 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | Notebook    | [13fcfc23c2](https://linux-hardware.org/?probe=13fcfc23c2) | Aug 08, 2024 |
| MSI           | MAG B460M MORTAR            | Desktop     | [ae8fdae6ed](https://linux-hardware.org/?probe=ae8fdae6ed) | Aug 08, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | Notebook    | [6b4b54be9c](https://linux-hardware.org/?probe=6b4b54be9c) | Aug 08, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [7d0bd59b78](https://linux-hardware.org/?probe=7d0bd59b78) | Aug 08, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [ed48c84db2](https://linux-hardware.org/?probe=ed48c84db2) | Aug 08, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [46039bc018](https://linux-hardware.org/?probe=46039bc018) | Aug 08, 2024 |
| ASRock        | B450M Steel Legend          | Desktop     | [8f925bc665](https://linux-hardware.org/?probe=8f925bc665) | Aug 08, 2024 |
| Lenovo        | G570 20079                  | Notebook    | [e9ceb63ac4](https://linux-hardware.org/?probe=e9ceb63ac4) | Aug 08, 2024 |
| ASUSTek       | F2A85-M LE                  | Desktop     | [1e20eab5b3](https://linux-hardware.org/?probe=1e20eab5b3) | Aug 08, 2024 |
| Gigabyte      | B450M H                     | Desktop     | [4608705c1b](https://linux-hardware.org/?probe=4608705c1b) | Aug 08, 2024 |
| ASUSTek       | N56VM                       | Notebook    | [c30ce9231a](https://linux-hardware.org/?probe=c30ce9231a) | Aug 08, 2024 |
| Unknown       | Unknown                     | Desktop     | [ca2d1b6863](https://linux-hardware.org/?probe=ca2d1b6863) | Aug 08, 2024 |
| Fujitsu       | LIFEBOOK SH531/GFX          | Other       | [c8d15f3581](https://linux-hardware.org/?probe=c8d15f3581) | Aug 08, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [6923eb858a](https://linux-hardware.org/?probe=6923eb858a) | Aug 08, 2024 |
| Matsushita... | CF-30FTSAZBG                | Notebook    | [4d1cfe156e](https://linux-hardware.org/?probe=4d1cfe156e) | Aug 07, 2024 |
| Packard Be... | EasyNote LJ71               | Notebook    | [4b758953f5](https://linux-hardware.org/?probe=4b758953f5) | Aug 07, 2024 |
| Lenovo        | ThinkPad T450 20BUA13XPB    | Notebook    | [5df0222220](https://linux-hardware.org/?probe=5df0222220) | Aug 07, 2024 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [ddc4fa1063](https://linux-hardware.org/?probe=ddc4fa1063) | Aug 07, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [8ef861a7c1](https://linux-hardware.org/?probe=8ef861a7c1) | Aug 07, 2024 |
| HUAWEI        | BC11SPSC0 V100R005          | Server      | [87d330be7f](https://linux-hardware.org/?probe=87d330be7f) | Aug 07, 2024 |
| Lenovo        | ThinkPad X230 2325L19       | Notebook    | [c3a54deca3](https://linux-hardware.org/?probe=c3a54deca3) | Aug 07, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [655bb3c7f9](https://linux-hardware.org/?probe=655bb3c7f9) | Aug 07, 2024 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [79efba5905](https://linux-hardware.org/?probe=79efba5905) | Aug 07, 2024 |
| Lenovo        | G70-80 80FF                 | Notebook    | [98e7b18535](https://linux-hardware.org/?probe=98e7b18535) | Aug 07, 2024 |
| AVITA         | NS12T5                      | Tablet      | [baac229086](https://linux-hardware.org/?probe=baac229086) | Aug 07, 2024 |
| AZW           | U59                         | Desktop     | [086e42624a](https://linux-hardware.org/?probe=086e42624a) | Aug 07, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [801fc7231c](https://linux-hardware.org/?probe=801fc7231c) | Aug 07, 2024 |
| ASUSTek       | X401U                       | Notebook    | [ea3228e385](https://linux-hardware.org/?probe=ea3228e385) | Aug 07, 2024 |
| Philco        | 10D                         | Desktop     | [133e541e61](https://linux-hardware.org/?probe=133e541e61) | Aug 07, 2024 |
| MACHINIST     | X99 PR9-H                   | Desktop     | [0cdafef2f4](https://linux-hardware.org/?probe=0cdafef2f4) | Aug 07, 2024 |
| HP            | Pavilion dv4                | Notebook    | [9d3424e152](https://linux-hardware.org/?probe=9d3424e152) | Aug 07, 2024 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [0188b1f00f](https://linux-hardware.org/?probe=0188b1f00f) | Aug 07, 2024 |
| Lenovo        | ThinkPad X301 4057WSQ       | Notebook    | [49d51f4fe2](https://linux-hardware.org/?probe=49d51f4fe2) | Aug 06, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9ba8f17a6e](https://linux-hardware.org/?probe=9ba8f17a6e) | Aug 06, 2024 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [1ed225ce94](https://linux-hardware.org/?probe=1ed225ce94) | Aug 06, 2024 |
| Supermicro    | X9DAi                       | Desktop     | [c3897b940a](https://linux-hardware.org/?probe=c3897b940a) | Aug 06, 2024 |
| GEEKOM        | XT12 Pro                    | Server      | [7adae02df5](https://linux-hardware.org/?probe=7adae02df5) | Aug 06, 2024 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [476a7f88c7](https://linux-hardware.org/?probe=476a7f88c7) | Aug 06, 2024 |
| MSI           | 760GM-P23                   | Desktop     | [0933c9d67f](https://linux-hardware.org/?probe=0933c9d67f) | Aug 06, 2024 |
| ASRock        | B650M Pro RS WiFi           | Desktop     | [0d84feef29](https://linux-hardware.org/?probe=0d84feef29) | Aug 06, 2024 |
| Acer          | Aspire V5-573G              | Notebook    | [15e763080f](https://linux-hardware.org/?probe=15e763080f) | Aug 06, 2024 |
| Lenovo        | Flex 2-14 20404             | Notebook    | [e61443fbcd](https://linux-hardware.org/?probe=e61443fbcd) | Aug 06, 2024 |
| ASUSTek       | H87M-E                      | Desktop     | [4b50217825](https://linux-hardware.org/?probe=4b50217825) | Aug 06, 2024 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [d9d47580bb](https://linux-hardware.org/?probe=d9d47580bb) | Aug 06, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e9a6c51c04](https://linux-hardware.org/?probe=e9a6c51c04) | Aug 06, 2024 |
| HP            | EliteBook Folio 9470m       | Notebook    | [1dad4cc854](https://linux-hardware.org/?probe=1dad4cc854) | Aug 06, 2024 |
| Dell          | Latitude E5520              | Notebook    | [fd2e8fc100](https://linux-hardware.org/?probe=fd2e8fc100) | Aug 06, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [6a38f3c326](https://linux-hardware.org/?probe=6a38f3c326) | Aug 06, 2024 |
| Acer          | Chapala                     | Notebook    | [06e1fcaa92](https://linux-hardware.org/?probe=06e1fcaa92) | Aug 06, 2024 |
| MSI           | X470 GAMING PLUS            | Desktop     | [25e07e9c51](https://linux-hardware.org/?probe=25e07e9c51) | Aug 05, 2024 |
| Dell          | Latitude E7250              | Notebook    | [7b85835719](https://linux-hardware.org/?probe=7b85835719) | Aug 05, 2024 |
| ASRock        | X570 Taichi                 | Desktop     | [70797c7bcc](https://linux-hardware.org/?probe=70797c7bcc) | Aug 05, 2024 |
| Apple         | Mac-F221BEC8                | Desktop     | [c5d08d410b](https://linux-hardware.org/?probe=c5d08d410b) | Aug 05, 2024 |
| Lenovo        | G710 20252                  | Notebook    | [47543598c1](https://linux-hardware.org/?probe=47543598c1) | Aug 05, 2024 |
| HP            | 3031h                       | Desktop     | [aedf79b471](https://linux-hardware.org/?probe=aedf79b471) | Aug 05, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [dbaab84f85](https://linux-hardware.org/?probe=dbaab84f85) | Aug 05, 2024 |
| Timi          | Redmi G 2022                | Notebook    | [bd14ac1c75](https://linux-hardware.org/?probe=bd14ac1c75) | Aug 05, 2024 |
| Lenovo        | IdeaPad Z580                | Notebook    | [cb672c1d21](https://linux-hardware.org/?probe=cb672c1d21) | Aug 05, 2024 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [0e789558e1](https://linux-hardware.org/?probe=0e789558e1) | Aug 05, 2024 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [308a21f570](https://linux-hardware.org/?probe=308a21f570) | Aug 05, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [01720c5ec4](https://linux-hardware.org/?probe=01720c5ec4) | Aug 05, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [ea27aaf797](https://linux-hardware.org/?probe=ea27aaf797) | Aug 05, 2024 |
| HP            | 620                         | Notebook    | [b5047e656c](https://linux-hardware.org/?probe=b5047e656c) | Aug 05, 2024 |
| Gigabyte      | EP43T-UD3L                  | Desktop     | [94df9b5c30](https://linux-hardware.org/?probe=94df9b5c30) | Aug 05, 2024 |
| HP            | 15                          | Notebook    | [a8346ebc6c](https://linux-hardware.org/?probe=a8346ebc6c) | Aug 04, 2024 |
| Gigabyte      | B85M-D3H                    | Desktop     | [db311c05ec](https://linux-hardware.org/?probe=db311c05ec) | Aug 04, 2024 |
| ASRock        | H81M-HDS                    | Desktop     | [eb80d08b53](https://linux-hardware.org/?probe=eb80d08b53) | Aug 04, 2024 |
| HP            | 89B4 A                      | Desktop     | [56591c9375](https://linux-hardware.org/?probe=56591c9375) | Aug 04, 2024 |
| GPU Compan... | GWTN156-11                  | Notebook    | [98f2badc5a](https://linux-hardware.org/?probe=98f2badc5a) | Aug 04, 2024 |
| Sony          | SVE14118FXW                 | Notebook    | [a8a2ecde8e](https://linux-hardware.org/?probe=a8a2ecde8e) | Aug 04, 2024 |
| ASUSTek       | K72F                        | Notebook    | [49b3023981](https://linux-hardware.org/?probe=49b3023981) | Aug 04, 2024 |
| Acer          | Aspire F5-571G              | Notebook    | [c6894a9467](https://linux-hardware.org/?probe=c6894a9467) | Aug 04, 2024 |
| HP            | Sona                        | Notebook    | [e88aa4fb3a](https://linux-hardware.org/?probe=e88aa4fb3a) | Aug 04, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [29f5ed3f5d](https://linux-hardware.org/?probe=29f5ed3f5d) | Aug 04, 2024 |
| HP            | G62                         | Notebook    | [a4d69df472](https://linux-hardware.org/?probe=a4d69df472) | Aug 04, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [ac57850733](https://linux-hardware.org/?probe=ac57850733) | Aug 04, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e89575b9ca](https://linux-hardware.org/?probe=e89575b9ca) | Aug 04, 2024 |
| HP            | 82B4                        | Desktop     | [529d7bc55e](https://linux-hardware.org/?probe=529d7bc55e) | Aug 04, 2024 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [e4cccb1fad](https://linux-hardware.org/?probe=e4cccb1fad) | Aug 04, 2024 |
| Acer          | Aspire XC-603               | Desktop     | [23210e4d9f](https://linux-hardware.org/?probe=23210e4d9f) | Aug 04, 2024 |
| Acer          | Aspire E5-553G              | Notebook    | [672e3df75a](https://linux-hardware.org/?probe=672e3df75a) | Aug 04, 2024 |
| Lenovo        | ThinkPad T61 7659CA1        | Notebook    | [8c59adcf60](https://linux-hardware.org/?probe=8c59adcf60) | Aug 04, 2024 |
| MSI           | 760GM-P23                   | Desktop     | [f6db289464](https://linux-hardware.org/?probe=f6db289464) | Aug 04, 2024 |
| Packard Be... | EasyNote TS44HR             | Notebook    | [8365b8e869](https://linux-hardware.org/?probe=8365b8e869) | Aug 03, 2024 |
| Intel         | H110 Series                 | Desktop     | [ba2023d022](https://linux-hardware.org/?probe=ba2023d022) | Aug 03, 2024 |
| Lenovo        | B50-45 20388                | Notebook    | [f21309b152](https://linux-hardware.org/?probe=f21309b152) | Aug 03, 2024 |
| ASUSTek       | P5G41C-M LX                 | Desktop     | [d4c3ba8890](https://linux-hardware.org/?probe=d4c3ba8890) | Aug 03, 2024 |
| Lenovo        | ThinkCentre M81 0267A38     | Desktop     | [88a07e7d3e](https://linux-hardware.org/?probe=88a07e7d3e) | Aug 03, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [20f39c9571](https://linux-hardware.org/?probe=20f39c9571) | Aug 03, 2024 |
| HP            | 8158 A01                    | Mini pc     | [5d4fdf1891](https://linux-hardware.org/?probe=5d4fdf1891) | Aug 03, 2024 |
| Lenovo        | ThinkPad X250 20CLS4PA00    | Notebook    | [56c7ccb272](https://linux-hardware.org/?probe=56c7ccb272) | Aug 03, 2024 |
| ASUSTek       | M11BB                       | Desktop     | [e592af72e7](https://linux-hardware.org/?probe=e592af72e7) | Aug 03, 2024 |
| ASUSTek       | X540LJ                      | Notebook    | [8034e44b49](https://linux-hardware.org/?probe=8034e44b49) | Aug 03, 2024 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [d203ea4b82](https://linux-hardware.org/?probe=d203ea4b82) | Aug 03, 2024 |
| Intel         | Thurley                     | Desktop     | [9b879619e7](https://linux-hardware.org/?probe=9b879619e7) | Aug 03, 2024 |
| Dell          | 0FDY5C A00                  | Desktop     | [f494d1f180](https://linux-hardware.org/?probe=f494d1f180) | Aug 03, 2024 |
| Dell          | 0YXT71 A01                  | Desktop     | [afd697799b](https://linux-hardware.org/?probe=afd697799b) | Aug 03, 2024 |
| ASUSTek       | X200MA                      | Notebook    | [fd40aa906e](https://linux-hardware.org/?probe=fd40aa906e) | Aug 02, 2024 |
| ASUSTek       | CM1735                      | Desktop     | [4422341690](https://linux-hardware.org/?probe=4422341690) | Aug 02, 2024 |
| Lenovo        | ThinkCentre M90 3246B8G     | Desktop     | [876613311e](https://linux-hardware.org/?probe=876613311e) | Aug 02, 2024 |
| Acer          | Aspire E5-532               | Notebook    | [f999845c79](https://linux-hardware.org/?probe=f999845c79) | Aug 02, 2024 |
| MSI           | J1800I                      | Desktop     | [2d0100f3d6](https://linux-hardware.org/?probe=2d0100f3d6) | Aug 02, 2024 |
| Lenovo        | ThinkPad X61s 76693KG       | Notebook    | [26fdf1c09d](https://linux-hardware.org/?probe=26fdf1c09d) | Aug 02, 2024 |
| MSI           | PRO B760-P WIFI             | Desktop     | [779bbdd8d5](https://linux-hardware.org/?probe=779bbdd8d5) | Aug 02, 2024 |
| MSI           | A68HM-P33 V2                | Desktop     | [fb213fe215](https://linux-hardware.org/?probe=fb213fe215) | Aug 02, 2024 |
| HP            | Laptop 15-da0xxx            | Notebook    | [3ee11f2047](https://linux-hardware.org/?probe=3ee11f2047) | Aug 02, 2024 |
| HP            | 859B                        | Desktop     | [172155a762](https://linux-hardware.org/?probe=172155a762) | Aug 01, 2024 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [8c20c8ffdd](https://linux-hardware.org/?probe=8c20c8ffdd) | Aug 01, 2024 |
| Lenovo        | ThinkPad X200 7459LK9       | Notebook    | [4d3053ad8f](https://linux-hardware.org/?probe=4d3053ad8f) | Aug 01, 2024 |
| Lenovo        | NO DPK                      | Desktop     | [6cdf96758d](https://linux-hardware.org/?probe=6cdf96758d) | Aug 01, 2024 |
| MSI           | 760GMA-P34                  | Desktop     | [59404bc1cb](https://linux-hardware.org/?probe=59404bc1cb) | Aug 01, 2024 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | Notebook    | [6abf02ed98](https://linux-hardware.org/?probe=6abf02ed98) | Aug 01, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [c10e613a60](https://linux-hardware.org/?probe=c10e613a60) | Aug 01, 2024 |
| ASUSTek       | P8H67-M EVO                 | Desktop     | [3340aefac7](https://linux-hardware.org/?probe=3340aefac7) | Aug 01, 2024 |
| Lenovo        | ThinkCentre M58p 6234CL2    | Desktop     | [024bb5ea7e](https://linux-hardware.org/?probe=024bb5ea7e) | Aug 01, 2024 |
| Lenovo        | ThinkCentre A70z 0401B7P    | Desktop     | [7501905c61](https://linux-hardware.org/?probe=7501905c61) | Aug 01, 2024 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [babb217959](https://linux-hardware.org/?probe=babb217959) | Aug 01, 2024 |
| MSI           | MAG B560M BAZOOKA           | Desktop     | [b48e017338](https://linux-hardware.org/?probe=b48e017338) | Aug 01, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [b71c134022](https://linux-hardware.org/?probe=b71c134022) | Aug 01, 2024 |
| HP            | Laptop 14-bs0xx             | Notebook    | [f994ec5854](https://linux-hardware.org/?probe=f994ec5854) | Aug 01, 2024 |
| HP            | 255 G5 Notebook PC          | Notebook    | [2a13961522](https://linux-hardware.org/?probe=2a13961522) | Aug 01, 2024 |
| Unknown       | Unknown                     | Desktop     | [216b38851e](https://linux-hardware.org/?probe=216b38851e) | Aug 01, 2024 |
| HP            | Laptop 15-rb0xx             | Notebook    | [c1316462ab](https://linux-hardware.org/?probe=c1316462ab) | Aug 01, 2024 |
| Lenovo        | ThinkPad T450 20BUS04U00    | Notebook    | [720b525240](https://linux-hardware.org/?probe=720b525240) | Jul 31, 2024 |
| Dell          | Latitude E6510              | Notebook    | [3ee852d371](https://linux-hardware.org/?probe=3ee852d371) | Jul 31, 2024 |
| Acer          | Aspire ES1-132              | Notebook    | [0539a9e223](https://linux-hardware.org/?probe=0539a9e223) | Jul 31, 2024 |
| Acer          | F690GVM                     | Desktop     | [5fd27036dc](https://linux-hardware.org/?probe=5fd27036dc) | Jul 31, 2024 |
| ASUSTek       | P5S800-VM                   | Desktop     | [e6528399e7](https://linux-hardware.org/?probe=e6528399e7) | Jul 31, 2024 |
| HP            | 8906 SMVB                   | Desktop     | [8071be19f2](https://linux-hardware.org/?probe=8071be19f2) | Jul 31, 2024 |
| Dell          | Inspiron 7400               | Notebook    | [8e52b6d214](https://linux-hardware.org/?probe=8e52b6d214) | Jul 31, 2024 |
| HP            | 843B                        | Desktop     | [84ed801133](https://linux-hardware.org/?probe=84ed801133) | Jul 31, 2024 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [8fa3c3f741](https://linux-hardware.org/?probe=8fa3c3f741) | Jul 31, 2024 |
| AZW           | SER V2.0                    | Mini pc     | [8abdd19040](https://linux-hardware.org/?probe=8abdd19040) | Jul 31, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [20184a147c](https://linux-hardware.org/?probe=20184a147c) | Jul 31, 2024 |
| Medion        | TJ4125                      | Desktop     | [1322129a3e](https://linux-hardware.org/?probe=1322129a3e) | Jul 31, 2024 |
| Lenovo        | ThinkPad T400 276552G       | Notebook    | [4311887bdf](https://linux-hardware.org/?probe=4311887bdf) | Jul 31, 2024 |
| Acer          | Aspire A315-41G             | Notebook    | [0f89433c33](https://linux-hardware.org/?probe=0f89433c33) | Jul 31, 2024 |
| Dell          | Precision M4500             | Notebook    | [0204ade296](https://linux-hardware.org/?probe=0204ade296) | Jul 31, 2024 |
| LG Electro... | 17Z90Q-G.AD78B              | Notebook    | [1f16333414](https://linux-hardware.org/?probe=1f16333414) | Jul 31, 2024 |
| Biostar       | H61MLB                      | Desktop     | [10f695fe18](https://linux-hardware.org/?probe=10f695fe18) | Jul 31, 2024 |
| LG Electro... | 16Z90S-H.ADB9U1             | Notebook    | [12d15d7d6f](https://linux-hardware.org/?probe=12d15d7d6f) | Jul 31, 2024 |
| Lenovo        | IdeaPad Y460                | Notebook    | [3addb65842](https://linux-hardware.org/?probe=3addb65842) | Jul 31, 2024 |
| Pegatron      | 2AE4                        | Desktop     | [db698b9ba0](https://linux-hardware.org/?probe=db698b9ba0) | Jul 31, 2024 |
| ASRock        | H97 Anniversary             | Desktop     | [ec56437f32](https://linux-hardware.org/?probe=ec56437f32) | Jul 31, 2024 |
| TUXEDO        | Unknown                     | Notebook    | [d64cec791c](https://linux-hardware.org/?probe=d64cec791c) | Jul 30, 2024 |
| HP            | 2AF7                        | Desktop     | [ff064ef8a1](https://linux-hardware.org/?probe=ff064ef8a1) | Jul 30, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [3c25ad374a](https://linux-hardware.org/?probe=3c25ad374a) | Jul 30, 2024 |
| Acer          | Aspire 5720                 | Notebook    | [8992cd5c88](https://linux-hardware.org/?probe=8992cd5c88) | Jul 30, 2024 |
| BESSTAR Te... | HM80                        | Desktop     | [221169cf71](https://linux-hardware.org/?probe=221169cf71) | Jul 30, 2024 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [2432557e37](https://linux-hardware.org/?probe=2432557e37) | Jul 30, 2024 |
| Sony          | VPCEJ1E1E                   | Notebook    | [d4f667801b](https://linux-hardware.org/?probe=d4f667801b) | Jul 30, 2024 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [ce44067016](https://linux-hardware.org/?probe=ce44067016) | Jul 30, 2024 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [7cae6fbf9a](https://linux-hardware.org/?probe=7cae6fbf9a) | Jul 30, 2024 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [d996c69b4e](https://linux-hardware.org/?probe=d996c69b4e) | Jul 30, 2024 |
| HP            | Pavilion Laptop 13-an0xx... | Notebook    | [1b74560bae](https://linux-hardware.org/?probe=1b74560bae) | Jul 30, 2024 |
| Dell          | Inspiron 15-3573            | Notebook    | [4eb1fa267c](https://linux-hardware.org/?probe=4eb1fa267c) | Jul 30, 2024 |
| HP            | 250 G2                      | Notebook    | [056a1d00e3](https://linux-hardware.org/?probe=056a1d00e3) | Jul 30, 2024 |
| Packard Be... | ENLE11BZ                    | Notebook    | [ecf5210a02](https://linux-hardware.org/?probe=ecf5210a02) | Jul 30, 2024 |
| HP            | ProBook 4530s               | Notebook    | [e89d3446a9](https://linux-hardware.org/?probe=e89d3446a9) | Jul 30, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [6c6387e423](https://linux-hardware.org/?probe=6c6387e423) | Jul 30, 2024 |
| HP            | Pavilion 17                 | Notebook    | [abce85daa2](https://linux-hardware.org/?probe=abce85daa2) | Jul 30, 2024 |
| Acer          | Aspire M5-583P              | Notebook    | [330749cccb](https://linux-hardware.org/?probe=330749cccb) | Jul 30, 2024 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [3015220143](https://linux-hardware.org/?probe=3015220143) | Jul 30, 2024 |
| Apple         | Mac-F2238AC8                | All in one  | [8c4b297032](https://linux-hardware.org/?probe=8c4b297032) | Jul 29, 2024 |
| HP            | 15                          | Notebook    | [dabb43e3d4](https://linux-hardware.org/?probe=dabb43e3d4) | Jul 29, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [a8ee53866e](https://linux-hardware.org/?probe=a8ee53866e) | Jul 29, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [9a1c33177c](https://linux-hardware.org/?probe=9a1c33177c) | Jul 29, 2024 |
| HP            | G70                         | Notebook    | [62cb43930d](https://linux-hardware.org/?probe=62cb43930d) | Jul 29, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [7374902608](https://linux-hardware.org/?probe=7374902608) | Jul 29, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [9c7a6479d0](https://linux-hardware.org/?probe=9c7a6479d0) | Jul 29, 2024 |
| Dell          | XPS 15 9530                 | Notebook    | [33f7d2da39](https://linux-hardware.org/?probe=33f7d2da39) | Jul 29, 2024 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [36182a6143](https://linux-hardware.org/?probe=36182a6143) | Jul 29, 2024 |
| ASUSTek       | P5Q-E                       | Desktop     | [38d1f56d89](https://linux-hardware.org/?probe=38d1f56d89) | Jul 29, 2024 |
| eMachines     | E725                        | Notebook    | [6f99103190](https://linux-hardware.org/?probe=6f99103190) | Jul 29, 2024 |
| HP            | Notebook                    | Notebook    | [5dcd24bbc1](https://linux-hardware.org/?probe=5dcd24bbc1) | Jul 29, 2024 |
| Biostar       | H61MGC                      | Desktop     | [e7b535b056](https://linux-hardware.org/?probe=e7b535b056) | Jul 29, 2024 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [a9d4f562c5](https://linux-hardware.org/?probe=a9d4f562c5) | Jul 29, 2024 |
| ECS           | H81M-C2H                    | Desktop     | [12a60ad494](https://linux-hardware.org/?probe=12a60ad494) | Jul 29, 2024 |
| ASRock        | X670E Steel Legend          | Desktop     | [0d8fe63707](https://linux-hardware.org/?probe=0d8fe63707) | Jul 29, 2024 |
| HP            | 0AE4h C                     | Desktop     | [56930a37ee](https://linux-hardware.org/?probe=56930a37ee) | Jul 29, 2024 |
| HP            | ProBook 6570b               | Notebook    | [de1d8f4d47](https://linux-hardware.org/?probe=de1d8f4d47) | Jul 29, 2024 |
| Lenovo        | ThinkPad X230 2325KZ5       | Notebook    | [0c86e846cb](https://linux-hardware.org/?probe=0c86e846cb) | Jul 29, 2024 |
| HONOR         | BMH-WDX9                    | Notebook    | [34156676c7](https://linux-hardware.org/?probe=34156676c7) | Jul 28, 2024 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [06c22e8fac](https://linux-hardware.org/?probe=06c22e8fac) | Jul 28, 2024 |
| Intel         | B75                         | Desktop     | [5bc0fa4295](https://linux-hardware.org/?probe=5bc0fa4295) | Jul 28, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [400a375f95](https://linux-hardware.org/?probe=400a375f95) | Jul 28, 2024 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [aaa1ceac14](https://linux-hardware.org/?probe=aaa1ceac14) | Jul 28, 2024 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF       | Desktop     | [90b84331bc](https://linux-hardware.org/?probe=90b84331bc) | Jul 28, 2024 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [eeb99aca23](https://linux-hardware.org/?probe=eeb99aca23) | Jul 28, 2024 |
| HP            | 829D                        | Desktop     | [5f82ac1818](https://linux-hardware.org/?probe=5f82ac1818) | Jul 28, 2024 |
| ASUSTek       | F3L                         | Notebook    | [1a3fd6736d](https://linux-hardware.org/?probe=1a3fd6736d) | Jul 28, 2024 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [9b0b51426a](https://linux-hardware.org/?probe=9b0b51426a) | Jul 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [6f233277df](https://linux-hardware.org/?probe=6f233277df) | Jul 28, 2024 |
| Acer          | Aspire A515-58M             | Notebook    | [eacf7d3932](https://linux-hardware.org/?probe=eacf7d3932) | Jul 28, 2024 |
| Pegatron      | 2AF0                        | Desktop     | [92b0828da2](https://linux-hardware.org/?probe=92b0828da2) | Jul 28, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5ccfa4d635](https://linux-hardware.org/?probe=5ccfa4d635) | Jul 28, 2024 |
| HP            | Laptop 14s-fq1xxx           | Notebook    | [aaa0951afb](https://linux-hardware.org/?probe=aaa0951afb) | Jul 28, 2024 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [0f18c465ca](https://linux-hardware.org/?probe=0f18c465ca) | Jul 28, 2024 |
| Dell          | 0GDG8Y A00                  | Desktop     | [01a7bfd3d6](https://linux-hardware.org/?probe=01a7bfd3d6) | Jul 28, 2024 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [1f2770be0f](https://linux-hardware.org/?probe=1f2770be0f) | Jul 28, 2024 |
| HP            | 18E5                        | Desktop     | [12198bdc99](https://linux-hardware.org/?probe=12198bdc99) | Jul 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [14e87e23b4](https://linux-hardware.org/?probe=14e87e23b4) | Jul 28, 2024 |
| Acer          | Aspire Z3170                | All in one  | [f24c44b389](https://linux-hardware.org/?probe=f24c44b389) | Jul 28, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [cea9613aba](https://linux-hardware.org/?probe=cea9613aba) | Jul 28, 2024 |
| ASUSTek       | N3050I-C                    | Desktop     | [2a6d292b88](https://linux-hardware.org/?probe=2a6d292b88) | Jul 28, 2024 |
| HP            | EliteBook 745 G6            | Notebook    | [d4583a12a6](https://linux-hardware.org/?probe=d4583a12a6) | Jul 27, 2024 |
| HP            | 89B4 A                      | Desktop     | [f64a4f1aa1](https://linux-hardware.org/?probe=f64a4f1aa1) | Jul 27, 2024 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [490e339872](https://linux-hardware.org/?probe=490e339872) | Jul 27, 2024 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [e5c379682b](https://linux-hardware.org/?probe=e5c379682b) | Jul 27, 2024 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0d3c21b355](https://linux-hardware.org/?probe=0d3c21b355) | Jul 27, 2024 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [f407127565](https://linux-hardware.org/?probe=f407127565) | Jul 27, 2024 |
| Dell          | 0T10XW A01                  | Desktop     | [e37e6d3743](https://linux-hardware.org/?probe=e37e6d3743) | Jul 27, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [c6b8951769](https://linux-hardware.org/?probe=c6b8951769) | Jul 27, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [55c7359f80](https://linux-hardware.org/?probe=55c7359f80) | Jul 27, 2024 |
| ASRock        | X300M-STX                   | Desktop     | [c4a916c82e](https://linux-hardware.org/?probe=c4a916c82e) | Jul 27, 2024 |
| HP            | Compaq CQ58                 | Notebook    | [5a0573bdb0](https://linux-hardware.org/?probe=5a0573bdb0) | Jul 27, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [7cc7a40e85](https://linux-hardware.org/?probe=7cc7a40e85) | Jul 27, 2024 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [723eb360ba](https://linux-hardware.org/?probe=723eb360ba) | Jul 27, 2024 |
| Apple         | MacBook6,1                  | Notebook    | [d172ade2ae](https://linux-hardware.org/?probe=d172ade2ae) | Jul 27, 2024 |
| HP            | Laptop 17-ak0xx             | Notebook    | [d039ad143d](https://linux-hardware.org/?probe=d039ad143d) | Jul 27, 2024 |
| ASRock        | B250 Pro4                   | Desktop     | [9c5d7ededd](https://linux-hardware.org/?probe=9c5d7ededd) | Jul 27, 2024 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [e70ef4ad50](https://linux-hardware.org/?probe=e70ef4ad50) | Jul 27, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e8db251f9e](https://linux-hardware.org/?probe=e8db251f9e) | Jul 27, 2024 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [be08e81120](https://linux-hardware.org/?probe=be08e81120) | Jul 27, 2024 |
| HASEE Comp... | K590P                       | Notebook    | [6bae6674d2](https://linux-hardware.org/?probe=6bae6674d2) | Jul 27, 2024 |
| HP            | 81BB                        | All in one  | [529409e450](https://linux-hardware.org/?probe=529409e450) | Jul 27, 2024 |
| Unknown       | M15S                        | Notebook    | [9cdf0f110e](https://linux-hardware.org/?probe=9cdf0f110e) | Jul 27, 2024 |
| MSI           | B85M-E45                    | Desktop     | [b1c5a5abb6](https://linux-hardware.org/?probe=b1c5a5abb6) | Jul 27, 2024 |
| ASRock        | B760M-C                     | Desktop     | [39b34fc090](https://linux-hardware.org/?probe=39b34fc090) | Jul 27, 2024 |
| ASUSTek       | X75A1                       | Notebook    | [d5b8f20d0f](https://linux-hardware.org/?probe=d5b8f20d0f) | Jul 27, 2024 |
| MSI           | Katana 15 B13VEK            | Notebook    | [c8c421d5c3](https://linux-hardware.org/?probe=c8c421d5c3) | Jul 26, 2024 |
| Medion        | Crawler E30                 | Notebook    | [5b75756a90](https://linux-hardware.org/?probe=5b75756a90) | Jul 26, 2024 |
| ASUSTek       | P8Z77-V LE PLUS             | Desktop     | [846aef9e97](https://linux-hardware.org/?probe=846aef9e97) | Jul 26, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [be9b63de88](https://linux-hardware.org/?probe=be9b63de88) | Jul 26, 2024 |
| Dell          | Inspiron 3582               | Notebook    | [3f49954088](https://linux-hardware.org/?probe=3f49954088) | Jul 26, 2024 |
| HP            | 18E4                        | Desktop     | [8e7d36557d](https://linux-hardware.org/?probe=8e7d36557d) | Jul 26, 2024 |
| Pegatron      | 3580                        | Desktop     | [5ddaaa65f5](https://linux-hardware.org/?probe=5ddaaa65f5) | Jul 26, 2024 |
| Medion        | A17                         | Notebook    | [b8cfeb8572](https://linux-hardware.org/?probe=b8cfeb8572) | Jul 26, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [eaab2b6733](https://linux-hardware.org/?probe=eaab2b6733) | Jul 26, 2024 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [b7ff387235](https://linux-hardware.org/?probe=b7ff387235) | Jul 26, 2024 |
| ASUSTek       | ROG Strix G713QR_G713QR     | Notebook    | [fb831802d5](https://linux-hardware.org/?probe=fb831802d5) | Jul 26, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [8333b31ce7](https://linux-hardware.org/?probe=8333b31ce7) | Jul 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [75ea2b1938](https://linux-hardware.org/?probe=75ea2b1938) | Jul 26, 2024 |
| HP            | 8653 A                      | Desktop     | [b320ae12d2](https://linux-hardware.org/?probe=b320ae12d2) | Jul 26, 2024 |
| Lenovo        | 30C9 SDK0J40697 WIN 3305... | Desktop     | [93a8017aa7](https://linux-hardware.org/?probe=93a8017aa7) | Jul 26, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [9ca37a4776](https://linux-hardware.org/?probe=9ca37a4776) | Jul 26, 2024 |
| ASUSTek       | M5A88-M                     | Desktop     | [5d3d3f7de7](https://linux-hardware.org/?probe=5d3d3f7de7) | Jul 26, 2024 |
| HP            | Notebook                    | Notebook    | [d223891862](https://linux-hardware.org/?probe=d223891862) | Jul 26, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [18bbac33d1](https://linux-hardware.org/?probe=18bbac33d1) | Jul 26, 2024 |
| HP            | OMEN Transcend Gaming La... | Notebook    | [f9b83b0d11](https://linux-hardware.org/?probe=f9b83b0d11) | Jul 26, 2024 |
| Biostar       | A68MD PRO                   | Desktop     | [2d33bbdbd9](https://linux-hardware.org/?probe=2d33bbdbd9) | Jul 25, 2024 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [b4cc76793d](https://linux-hardware.org/?probe=b4cc76793d) | Jul 25, 2024 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [2d1bd9d543](https://linux-hardware.org/?probe=2d1bd9d543) | Jul 25, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [ba90eed6e2](https://linux-hardware.org/?probe=ba90eed6e2) | Jul 25, 2024 |
| Dell          | Latitude E5550              | Notebook    | [5a773c0eae](https://linux-hardware.org/?probe=5a773c0eae) | Jul 25, 2024 |
| ASUSTek       | K53SD                       | Notebook    | [ae42160a71](https://linux-hardware.org/?probe=ae42160a71) | Jul 25, 2024 |
| Toshiba       | PORTEGE Z930                | Notebook    | [0818704a46](https://linux-hardware.org/?probe=0818704a46) | Jul 25, 2024 |
| ASUSTek       | H81M-K                      | Desktop     | [c7efb5f986](https://linux-hardware.org/?probe=c7efb5f986) | Jul 25, 2024 |
| HP            | 255 G5                      | Notebook    | [738dcbcc7b](https://linux-hardware.org/?probe=738dcbcc7b) | Jul 25, 2024 |
| Maibenben     | MaiBook M                   | Notebook    | [45264e3652](https://linux-hardware.org/?probe=45264e3652) | Jul 25, 2024 |
| HP            | Laptop 17-by0xxx            | Notebook    | [29acbbfa9a](https://linux-hardware.org/?probe=29acbbfa9a) | Jul 25, 2024 |
| ASRock        | Q1900M                      | Desktop     | [a91507fe3f](https://linux-hardware.org/?probe=a91507fe3f) | Jul 25, 2024 |
| Gigabyte      | G41M-Combo                  | Desktop     | [10adb31c02](https://linux-hardware.org/?probe=10adb31c02) | Jul 25, 2024 |
| Dell          | 042P49 A02                  | Desktop     | [46ca46385a](https://linux-hardware.org/?probe=46ca46385a) | Jul 25, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [2c7aa20c2a](https://linux-hardware.org/?probe=2c7aa20c2a) | Jul 25, 2024 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [4e32c4d0df](https://linux-hardware.org/?probe=4e32c4d0df) | Jul 25, 2024 |
| Lenovo        | ThinkPad P53 20QQS74W00     | Notebook    | [11359334f2](https://linux-hardware.org/?probe=11359334f2) | Jul 25, 2024 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [ebc0fc9568](https://linux-hardware.org/?probe=ebc0fc9568) | Jul 25, 2024 |
| Dell          | Inspiron 5542               | Notebook    | [058371d745](https://linux-hardware.org/?probe=058371d745) | Jul 25, 2024 |
| ASUSTek       | A88XM-E/USB                 | Desktop     | [9cc6e54448](https://linux-hardware.org/?probe=9cc6e54448) | Jul 25, 2024 |
| HP            | 8767 A                      | Desktop     | [6e6335bf04](https://linux-hardware.org/?probe=6e6335bf04) | Jul 25, 2024 |
| Lenovo        | 36ED SDK0J40700 WIN 3258... | All in one  | [c6b2db5f7b](https://linux-hardware.org/?probe=c6b2db5f7b) | Jul 25, 2024 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [40787275bb](https://linux-hardware.org/?probe=40787275bb) | Jul 25, 2024 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [7623e32d5d](https://linux-hardware.org/?probe=7623e32d5d) | Jul 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [c3d85476a7](https://linux-hardware.org/?probe=c3d85476a7) | Jul 25, 2024 |
| Intel         | H61/B75                     | Desktop     | [316cf38c13](https://linux-hardware.org/?probe=316cf38c13) | Jul 25, 2024 |
| ASUSTek       | K53U                        | Notebook    | [811341b025](https://linux-hardware.org/?probe=811341b025) | Jul 25, 2024 |
| Acer          | Aspire Z3730                | All in one  | [6a55579055](https://linux-hardware.org/?probe=6a55579055) | Jul 25, 2024 |
| Intel         | NUC8BEB J72693-307          | Mini pc     | [f63af4c386](https://linux-hardware.org/?probe=f63af4c386) | Jul 25, 2024 |
| Fujitsu       | FMVNFA40J                   | Notebook    | [0dc6a87a7e](https://linux-hardware.org/?probe=0dc6a87a7e) | Jul 25, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [ecdd3b7cd2](https://linux-hardware.org/?probe=ecdd3b7cd2) | Jul 25, 2024 |
| Dell          | 0VHWTR A02                  | Desktop     | [6073fdcc24](https://linux-hardware.org/?probe=6073fdcc24) | Jul 25, 2024 |
| ASRock        | B450 Pro4                   | Desktop     | [48e164aa4e](https://linux-hardware.org/?probe=48e164aa4e) | Jul 25, 2024 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [b3488f2839](https://linux-hardware.org/?probe=b3488f2839) | Jul 25, 2024 |
| ASUSTek       | B85M-G                      | Desktop     | [e34ef3a83c](https://linux-hardware.org/?probe=e34ef3a83c) | Jul 25, 2024 |
| MSI           | B350M GAMING PRO            | Desktop     | [2de872ecab](https://linux-hardware.org/?probe=2de872ecab) | Jul 24, 2024 |
| Dell          | 0YJPT1 A00                  | Desktop     | [e704325fc3](https://linux-hardware.org/?probe=e704325fc3) | Jul 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [37186edbaa](https://linux-hardware.org/?probe=37186edbaa) | Jul 24, 2024 |
| HP            | 255 G7 Notebook PC          | Notebook    | [19a51f93c3](https://linux-hardware.org/?probe=19a51f93c3) | Jul 24, 2024 |
| Dell          | 0X4H68 A00                  | Desktop     | [b0434de75f](https://linux-hardware.org/?probe=b0434de75f) | Jul 24, 2024 |
| Dell          | Latitude E5410              | Notebook    | [57cc1db63b](https://linux-hardware.org/?probe=57cc1db63b) | Jul 24, 2024 |
| Acer          | Aspire 7535                 | Notebook    | [a5f61a888d](https://linux-hardware.org/?probe=a5f61a888d) | Jul 24, 2024 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [de715b8bd7](https://linux-hardware.org/?probe=de715b8bd7) | Jul 24, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [f077989509](https://linux-hardware.org/?probe=f077989509) | Jul 24, 2024 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [e8584d4bd8](https://linux-hardware.org/?probe=e8584d4bd8) | Jul 24, 2024 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [b2afe39e6f](https://linux-hardware.org/?probe=b2afe39e6f) | Jul 24, 2024 |
| ASUSTek       | 1225B                       | Notebook    | [e7d5e1e2c4](https://linux-hardware.org/?probe=e7d5e1e2c4) | Jul 24, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [12a4c743fc](https://linux-hardware.org/?probe=12a4c743fc) | Jul 24, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [4ac934318c](https://linux-hardware.org/?probe=4ac934318c) | Jul 24, 2024 |
| Gigabyte      | H55M-S2H                    | Desktop     | [bc9baba360](https://linux-hardware.org/?probe=bc9baba360) | Jul 24, 2024 |
| Acer          | Aspire A315-41              | Notebook    | [05c607b799](https://linux-hardware.org/?probe=05c607b799) | Jul 24, 2024 |
| Gigabyte      | Z97M-D3H                    | Desktop     | [d14ff2b99b](https://linux-hardware.org/?probe=d14ff2b99b) | Jul 24, 2024 |
| Lenovo        | G510 20238                  | Notebook    | [38180e0cf9](https://linux-hardware.org/?probe=38180e0cf9) | Jul 24, 2024 |
| HP            | 82FE 11                     | Desktop     | [fe0843fe27](https://linux-hardware.org/?probe=fe0843fe27) | Jul 24, 2024 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [776835c3f3](https://linux-hardware.org/?probe=776835c3f3) | Jul 24, 2024 |
| MSI           | H61M-P21                    | Desktop     | [4e1acb5744](https://linux-hardware.org/?probe=4e1acb5744) | Jul 24, 2024 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [91a2df7676](https://linux-hardware.org/?probe=91a2df7676) | Jul 24, 2024 |
| Dell          | Latitude E5520              | Notebook    | [94532288fa](https://linux-hardware.org/?probe=94532288fa) | Jul 24, 2024 |
| ASUSTek       | K50IN                       | Notebook    | [707377026f](https://linux-hardware.org/?probe=707377026f) | Jul 24, 2024 |
| Win Elemen... | S500+                       | Desktop     | [3aa986ddc3](https://linux-hardware.org/?probe=3aa986ddc3) | Jul 24, 2024 |
| HP            | Victus by Gaming Laptop     | Notebook    | [b307a07177](https://linux-hardware.org/?probe=b307a07177) | Jul 24, 2024 |
| ASRock        | B550M Pro4                  | Desktop     | [4e06715a28](https://linux-hardware.org/?probe=4e06715a28) | Jul 24, 2024 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a8ee725733](https://linux-hardware.org/?probe=a8ee725733) | Jul 24, 2024 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8266881b34](https://linux-hardware.org/?probe=8266881b34) | Jul 24, 2024 |
| MSI           | B350 PC MATE                | Desktop     | [0b80ce71a7](https://linux-hardware.org/?probe=0b80ce71a7) | Jul 24, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [1382964de9](https://linux-hardware.org/?probe=1382964de9) | Jul 24, 2024 |
| Foxconn       | G41S/G41S-K                 | Desktop     | [23e38e3c70](https://linux-hardware.org/?probe=23e38e3c70) | Jul 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [bd05285887](https://linux-hardware.org/?probe=bd05285887) | Jul 24, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [187ba51872](https://linux-hardware.org/?probe=187ba51872) | Jul 24, 2024 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [74820c3666](https://linux-hardware.org/?probe=74820c3666) | Jul 23, 2024 |
| AMI           | Intel                       | Desktop     | [3a2452931b](https://linux-hardware.org/?probe=3a2452931b) | Jul 23, 2024 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [a912787dd0](https://linux-hardware.org/?probe=a912787dd0) | Jul 23, 2024 |
| Lenovo        | B50-50 80S2                 | Notebook    | [905eac1e60](https://linux-hardware.org/?probe=905eac1e60) | Jul 23, 2024 |
| Dell          | Inspiron N4010              | Notebook    | [d91c98d5f4](https://linux-hardware.org/?probe=d91c98d5f4) | Jul 23, 2024 |
| ASUSTek       | PRIME H610M-D D4            | Desktop     | [5952505694](https://linux-hardware.org/?probe=5952505694) | Jul 23, 2024 |
| HP            | 2000                        | Notebook    | [d1ecc9c39e](https://linux-hardware.org/?probe=d1ecc9c39e) | Jul 23, 2024 |
| Sony          | VPCEB3F4E                   | Notebook    | [5b1e21f008](https://linux-hardware.org/?probe=5b1e21f008) | Jul 23, 2024 |
| Toshiba       | dynabook R734/M             | Notebook    | [74f02e03a1](https://linux-hardware.org/?probe=74f02e03a1) | Jul 23, 2024 |
| Gateway       | DX4380G                     | Desktop     | [c55a9746c1](https://linux-hardware.org/?probe=c55a9746c1) | Jul 23, 2024 |
| Dell          | System Inspiron N7110       | Notebook    | [9eca86601c](https://linux-hardware.org/?probe=9eca86601c) | Jul 23, 2024 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [559f53d88c](https://linux-hardware.org/?probe=559f53d88c) | Jul 23, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [1c42d3aa40](https://linux-hardware.org/?probe=1c42d3aa40) | Jul 23, 2024 |
| Medion        | E11201                      | Notebook    | [603f2caffa](https://linux-hardware.org/?probe=603f2caffa) | Jul 23, 2024 |
| Dell          | 0HN7XN A01                  | Desktop     | [2e8b1aeb7b](https://linux-hardware.org/?probe=2e8b1aeb7b) | Jul 23, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | Notebook    | [2a1301a1d4](https://linux-hardware.org/?probe=2a1301a1d4) | Jul 23, 2024 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [13e48f4585](https://linux-hardware.org/?probe=13e48f4585) | Jul 23, 2024 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [c6b7f59209](https://linux-hardware.org/?probe=c6b7f59209) | Jul 23, 2024 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [06ec7cb14f](https://linux-hardware.org/?probe=06ec7cb14f) | Jul 23, 2024 |
| Sony          | VPCYB3V1E                   | Notebook    | [e34ef837a0](https://linux-hardware.org/?probe=e34ef837a0) | Jul 23, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [ab92abc5df](https://linux-hardware.org/?probe=ab92abc5df) | Jul 23, 2024 |
| Acer          | Aspire 7720Z                | Notebook    | [22b713dcde](https://linux-hardware.org/?probe=22b713dcde) | Jul 23, 2024 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [ef8ec22b50](https://linux-hardware.org/?probe=ef8ec22b50) | Jul 23, 2024 |
| MSI           | 3664h                       | Desktop     | [176f9547b9](https://linux-hardware.org/?probe=176f9547b9) | Jul 23, 2024 |
| Dell          | 0J3C2F A02                  | Desktop     | [f92c77dcff](https://linux-hardware.org/?probe=f92c77dcff) | Jul 23, 2024 |
| Lenovo        | ThinkPad Edge E531 68856... | Notebook    | [37fc2e067d](https://linux-hardware.org/?probe=37fc2e067d) | Jul 23, 2024 |
| ALLDOCUBE     | i1506S                      | Notebook    | [86c70fe18b](https://linux-hardware.org/?probe=86c70fe18b) | Jul 23, 2024 |
| HP            | G72                         | Notebook    | [d1b4f722ff](https://linux-hardware.org/?probe=d1b4f722ff) | Jul 23, 2024 |
| Dell          | 500                         | Notebook    | [81a9db8d87](https://linux-hardware.org/?probe=81a9db8d87) | Jul 23, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5d2efc60c2](https://linux-hardware.org/?probe=5d2efc60c2) | Jul 23, 2024 |
| ASUSTek       | TUF Z390-PLUS GAMING        | Desktop     | [bde1d0c7b3](https://linux-hardware.org/?probe=bde1d0c7b3) | Jul 23, 2024 |
| HP            | ENVY dv6                    | Notebook    | [90cb34453c](https://linux-hardware.org/?probe=90cb34453c) | Jul 23, 2024 |
| Medion        | P2A4-EM                     | Desktop     | [c57d57693a](https://linux-hardware.org/?probe=c57d57693a) | Jul 23, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [4e3f61c287](https://linux-hardware.org/?probe=4e3f61c287) | Jul 23, 2024 |
| Infinix       | INBOOK X3 Plus              | Notebook    | [bf04bfec39](https://linux-hardware.org/?probe=bf04bfec39) | Jul 23, 2024 |
| Gigabyte      | B650I AX                    | Desktop     | [37196d5c35](https://linux-hardware.org/?probe=37196d5c35) | Jul 23, 2024 |
| Lenovo        | ThinkPad R500 2718Y21       | Notebook    | [527c6d0299](https://linux-hardware.org/?probe=527c6d0299) | Jul 23, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [46748aee2e](https://linux-hardware.org/?probe=46748aee2e) | Jul 23, 2024 |
| Acer          | Aspire A515-43              | Notebook    | [edd3820814](https://linux-hardware.org/?probe=edd3820814) | Jul 23, 2024 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [604aa7f1d9](https://linux-hardware.org/?probe=604aa7f1d9) | Jul 23, 2024 |
| ASRock        | Q1900B-ITX                  | Desktop     | [56c6b1769a](https://linux-hardware.org/?probe=56c6b1769a) | Jul 23, 2024 |
| Acer          | Aspire E5-573G              | Notebook    | [063c27b460](https://linux-hardware.org/?probe=063c27b460) | Jul 23, 2024 |
| MSI           | B550 GAMING GEN3            | Desktop     | [f0ac757384](https://linux-hardware.org/?probe=f0ac757384) | Jul 23, 2024 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [7a88a3f633](https://linux-hardware.org/?probe=7a88a3f633) | Jul 23, 2024 |
| Dell          | 0Y2K8N A00                  | Desktop     | [0a62fbdca2](https://linux-hardware.org/?probe=0a62fbdca2) | Jul 23, 2024 |
| Dell          | 03PYWR A00                  | All in one  | [5a7898e291](https://linux-hardware.org/?probe=5a7898e291) | Jul 23, 2024 |
| HP            | ProBook 470 G5              | Notebook    | [894e4a3a29](https://linux-hardware.org/?probe=894e4a3a29) | Jul 22, 2024 |
| HP            | Pavilion dv6                | Notebook    | [2a996d810e](https://linux-hardware.org/?probe=2a996d810e) | Jul 22, 2024 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [bccf1b55f8](https://linux-hardware.org/?probe=bccf1b55f8) | Jul 22, 2024 |
| OEM           | B75 Ver:1.41                | Desktop     | [3b478b5479](https://linux-hardware.org/?probe=3b478b5479) | Jul 22, 2024 |
| HP            | Laptop 15-bw0xx             | Notebook    | [e09128a4ab](https://linux-hardware.org/?probe=e09128a4ab) | Jul 22, 2024 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [c872b62918](https://linux-hardware.org/?probe=c872b62918) | Jul 22, 2024 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/OpenMandriva_24.07/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.10.0-desktop-1omv2490       | 1011      | 74.72%  |
| 6.9.7-desktop-1omv2490        | 281       | 20.77%  |
| 6.10.1-desktop-1omv2490       | 53        | 3.92%   |
| 6.9.9-desktop-1omv2490        | 3         | 0.22%   |
| 6.11.0-desktop-2omv2490       | 2         | 0.15%   |
| 6.12.9-desktop-1omv2490       | 1         | 0.07%   |
| 6.10.0-desktop-gcc-1omv2490   | 1         | 0.07%   |
| 6.10.0-desktop-0.rc5.1omv2490 | 1         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.10.0  | 1013      | 74.87%  |
| 6.9.7   | 281       | 20.77%  |
| 6.10.1  | 53        | 3.92%   |
| 6.9.9   | 3         | 0.22%   |
| 6.11.0  | 2         | 0.15%   |
| 6.12.9  | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.10    | 1066      | 78.79%  |
| 6.9     | 284       | 20.99%  |
| 6.11    | 2         | 0.15%   |
| 6.12    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1352      | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 850       | 62.45%  |
| LXQt    | 223       | 16.39%  |
| KDE6    | 135       | 9.92%   |
| GNOME   | 113       | 8.3%    |
| KDE5    | 37        | 2.72%   |
| XFCE    | 2         | 0.15%   |
| Budgie  | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 754       | 55.73%  |
| Wayland | 598       | 44.2%   |
| Unknown | 1         | 0.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1238      | 91.5%   |
| GDM     | 112       | 8.28%   |
| LightDM | 2         | 0.15%   |
| Unknown | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 737       | 54.39%  |
| de_DE | 88        | 6.49%   |
| ru_RU | 75        | 5.54%   |
| pl_PL | 70        | 5.17%   |
| fr_FR | 62        | 4.58%   |
| en_GB | 48        | 3.54%   |
| it_IT | 42        | 3.1%    |
| pt_BR | 40        | 2.95%   |
| es_MX | 26        | 1.92%   |
| es_ES | 26        | 1.92%   |
| es_AR | 19        | 1.4%    |
| cs_CZ | 15        | 1.11%   |
| en_CA | 12        | 0.89%   |
| hu_HU | 10        | 0.74%   |
| es_CO | 6         | 0.44%   |
| en_IN | 6         | 0.44%   |
| en_AU | 6         | 0.44%   |
| nl_NL | 5         | 0.37%   |
| es_PE | 5         | 0.37%   |
| de_AT | 5         | 0.37%   |
| tr_TR | 4         | 0.3%    |
| nl_BE | 4         | 0.3%    |
| es_GT | 4         | 0.3%    |
| fr_CH | 3         | 0.22%   |
| fr_CA | 3         | 0.22%   |
| es_VE | 3         | 0.22%   |
| en_NZ | 3         | 0.22%   |
| de_CH | 3         | 0.22%   |
| uk_UA | 2         | 0.15%   |
| pt_PT | 2         | 0.15%   |
| fr_BE | 2         | 0.15%   |
| es_PA | 2         | 0.15%   |
| es_CL | 2         | 0.15%   |
| en_PH | 2         | 0.15%   |
| en_HK | 2         | 0.15%   |
| ru_UA | 1         | 0.07%   |
| ro_RO | 1         | 0.07%   |
| fr_LU | 1         | 0.07%   |
| fi_FI | 1         | 0.07%   |
| es_US | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 812       | 60.06%  |
| BIOS | 540       | 39.94%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Overlay | 888       | 65.54%  |
| Ext4    | 412       | 30.41%  |
| Btrfs   | 37        | 2.73%   |
| Xfs     | 10        | 0.74%   |
| F2fs    | 7         | 0.52%   |
| Ext3    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 1076      | 79.53%  |
| MBR  | 277       | 20.47%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 710       | 52.44%  |
| No        | 644       | 47.56%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 787       | 58.12%  |
| Yes       | 567       | 41.88%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 241       | 17.83%  |
| Hewlett-Packard                      | 188       | 13.91%  |
| Lenovo                               | 174       | 12.87%  |
| Dell                                 | 136       | 10.06%  |
| Gigabyte Technology                  | 92        | 6.8%    |
| Acer                                 | 78        | 5.77%   |
| MSI                                  | 75        | 5.55%   |
| ASRock                               | 54        | 3.99%   |
| Intel                                | 31        | 2.29%   |
| Toshiba                              | 25        | 1.85%   |
| Fujitsu                              | 21        | 1.55%   |
| Apple                                | 21        | 1.55%   |
| Unknown                              | 21        | 1.55%   |
| Sony                                 | 14        | 1.04%   |
| Medion                               | 12        | 0.89%   |
| Shenzhen Meigao Electronic Equipment | 11        | 0.81%   |
| Samsung Electronics                  | 11        | 0.81%   |
| Positivo                             | 11        | 0.81%   |
| AZW                                  | 11        | 0.81%   |
| Packard Bell                         | 9         | 0.67%   |
| Foxconn                              | 9         | 0.67%   |
| Microsoft                            | 8         | 0.59%   |
| Biostar                              | 8         | 0.59%   |
| Pegatron                             | 7         | 0.52%   |
| MACHINIST                            | 6         | 0.44%   |
| ZOTAC                                | 5         | 0.37%   |
| HUAWEI                               | 5         | 0.37%   |
| Google                               | 4         | 0.3%    |
| OEM                                  | 3         | 0.22%   |
| LG Electronics                       | 3         | 0.22%   |
| AMI                                  | 3         | 0.22%   |
| Philco                               | 2         | 0.15%   |
| Panasonic                            | 2         | 0.15%   |
| Notebook                             | 2         | 0.15%   |
| Infinix                              | 2         | 0.15%   |
| GPU Company                          | 2         | 0.15%   |
| Gateway                              | 2         | 0.15%   |
| Fujitsu Siemens                      | 2         | 0.15%   |
| Chuwi                                | 2         | 0.15%   |
| BESSTAR Tech                         | 2         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 26        | 1.92%   |
| ASUS All Series                                   | 18        | 1.33%   |
| AZW SER                                           | 7         | 0.52%   |
| ASUS TUF Gaming X570-PLUS                         | 6         | 0.44%   |
| ASUS PRIME A320M-K                                | 6         | 0.44%   |
| MSI MS-7C56                                       | 5         | 0.37%   |
| Intel B75                                         | 4         | 0.3%    |
| HP Pavilion dv6                                   | 4         | 0.3%    |
| HP Notebook                                       | 4         | 0.3%    |
| HP 15                                             | 4         | 0.3%    |
| Dell OptiPlex 7010                                | 4         | 0.3%    |
| ASUS PRIME B450M-A II                             | 4         | 0.3%    |
| Shenzhen Meigao Electronic Equipment Venus series | 3         | 0.22%   |
| MSI MS-7C96                                       | 3         | 0.22%   |
| MSI MS-7C91                                       | 3         | 0.22%   |
| MSI MS-7C02                                       | 3         | 0.22%   |
| MSI MS-7A38                                       | 3         | 0.22%   |
| MSI MS-7A34                                       | 3         | 0.22%   |
| MSI MS-7680                                       | 3         | 0.22%   |
| MSI MS-7641                                       | 3         | 0.22%   |
| MACHINIST X99 PR9-H                               | 3         | 0.22%   |
| Lenovo IdeaPad 3 15ALC6 82MF                      | 3         | 0.22%   |
| HP Z400 Workstation                               | 3         | 0.22%   |
| HP Laptop 17-ca1xxx                               | 3         | 0.22%   |
| Gigabyte X570 AORUS ELITE                         | 3         | 0.22%   |
| Gigabyte B550 AORUS ELITE V2                      | 3         | 0.22%   |
| Gigabyte B450 AORUS ELITE                         | 3         | 0.22%   |
| Gigabyte AB350M-DS3H V2                           | 3         | 0.22%   |
| Dell OptiPlex 3020                                | 3         | 0.22%   |
| Dell OptiPlex 3010                                | 3         | 0.22%   |
| Dell Latitude E7440                               | 3         | 0.22%   |
| AZW MINI S                                        | 3         | 0.22%   |
| ASUS VivoBook_ASUSLaptop E410MAB_E410MA           | 3         | 0.22%   |
| ASUS PRIME B550-PLUS                              | 3         | 0.22%   |
| AMI Intel                                         | 3         | 0.22%   |
| ZOTAC NM10                                        | 2         | 0.15%   |
| Toshiba TECRA A10                                 | 2         | 0.15%   |
| Sony VGN-SZ1XP_C                                  | 2         | 0.15%   |
| Shenzhen Meigao Electronic Equipment UM690        | 2         | 0.15%   |
| Positivo C14CU51                                  | 2         | 0.15%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 62        | 4.59%   |
| Lenovo ThinkPad       | 60        | 4.44%   |
| Lenovo IdeaPad        | 43        | 3.18%   |
| Dell Latitude         | 40        | 2.96%   |
| Dell Inspiron         | 37        | 2.74%   |
| ASUS PRIME            | 34        | 2.51%   |
| Dell OptiPlex         | 32        | 2.37%   |
| HP Laptop             | 29        | 2.14%   |
| Lenovo ThinkCentre    | 26        | 1.92%   |
| Unknown               | 26        | 1.92%   |
| HP Pavilion           | 25        | 1.85%   |
| HP EliteBook          | 22        | 1.63%   |
| ASUS TUF              | 22        | 1.63%   |
| HP Compaq             | 19        | 1.41%   |
| ASUS VivoBook         | 19        | 1.41%   |
| ASUS ROG              | 19        | 1.41%   |
| Toshiba Satellite     | 18        | 1.33%   |
| ASUS All              | 18        | 1.33%   |
| HP ProBook            | 11        | 0.81%   |
| HP EliteDesk          | 10        | 0.74%   |
| Fujitsu LIFEBOOK      | 9         | 0.67%   |
| Dell Precision        | 9         | 0.67%   |
| Microsoft Surface     | 8         | 0.59%   |
| HP ProDesk            | 8         | 0.59%   |
| Packard Bell EasyNote | 7         | 0.52%   |
| Gigabyte B450         | 7         | 0.52%   |
| AZW SER               | 7         | 0.52%   |
| HP 255                | 6         | 0.44%   |
| HP 15                 | 6         | 0.44%   |
| Gigabyte X570         | 6         | 0.44%   |
| Gigabyte B450M        | 6         | 0.44%   |
| MSI MS-7C56           | 5         | 0.37%   |
| HP ENVY               | 5         | 0.37%   |
| Fujitsu ESPRIMO       | 5         | 0.37%   |
| ASUS M5A78L-M         | 5         | 0.37%   |
| ASRock X570           | 5         | 0.37%   |
| Medion Akoya          | 4         | 0.3%    |
| MACHINIST X99         | 4         | 0.3%    |
| Lenovo IdeaPadFlex    | 4         | 0.3%    |
| Lenovo IdeaCentre     | 4         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2012 | 124       | 9.17%   |
| 2013 | 113       | 8.36%   |
| 2011 | 108       | 7.99%   |
| 2014 | 99        | 7.32%   |
| 2020 | 88        | 6.51%   |
| 2021 | 87        | 6.43%   |
| 2019 | 84        | 6.21%   |
| 2023 | 78        | 5.77%   |
| 2022 | 78        | 5.77%   |
| 2018 | 76        | 5.62%   |
| 2017 | 71        | 5.25%   |
| 2010 | 66        | 4.88%   |
| 2015 | 58        | 4.29%   |
| 2009 | 57        | 4.22%   |
| 2008 | 52        | 3.85%   |
| 2007 | 40        | 2.96%   |
| 2024 | 34        | 2.51%   |
| 2016 | 32        | 2.37%   |
| 2006 | 4         | 0.3%    |
| 2025 | 1         | 0.07%   |
| 2005 | 1         | 0.07%   |
| 2003 | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 643       | 47.56%  |
| Desktop     | 634       | 46.89%  |
| Mini pc     | 34        | 2.51%   |
| Tablet      | 13        | 0.96%   |
| All in one  | 13        | 0.96%   |
| Convertible | 11        | 0.81%   |
| Other       | 3         | 0.22%   |
| Server      | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1352      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1343      | 99.33%  |
| Yes  | 9         | 0.67%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 324       | 23.93%  |
| 3.01-4.0        | 291       | 21.49%  |
| 8.01-16.0       | 263       | 19.42%  |
| 16.01-24.0      | 234       | 17.28%  |
| 32.01-64.0      | 120       | 8.86%   |
| 24.01-32.0      | 37        | 2.73%   |
| 64.01-256.0     | 32        | 2.36%   |
| 1.01-2.0        | 32        | 2.36%   |
| 2.01-3.0        | 17        | 1.26%   |
| 0.51-1.0        | 3         | 0.22%   |
| More than 256.0 | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 806       | 59.26%  |
| 2.01-3.0  | 281       | 20.66%  |
| 0.51-1.0  | 171       | 12.57%  |
| 3.01-4.0  | 46        | 3.38%   |
| 0.01-0.5  | 30        | 2.21%   |
| 4.01-8.0  | 25        | 1.84%   |
| 8.01-16.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 760       | 55.96%  |
| 2      | 330       | 24.3%   |
| 3      | 127       | 9.35%   |
| 4      | 58        | 4.27%   |
| 5      | 25        | 1.84%   |
| 0      | 24        | 1.77%   |
| 6      | 18        | 1.33%   |
| 7      | 11        | 0.81%   |
| 8      | 3         | 0.22%   |
| 9      | 2         | 0.15%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 792       | 58.58%  |
| Yes       | 560       | 41.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1217      | 90.01%  |
| No        | 135       | 9.99%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 953       | 70.38%  |
| No        | 401       | 29.62%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 766       | 56.57%  |
| No        | 588       | 43.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 197       | 14.57%  |
| Germany      | 127       | 9.39%   |
| Poland       | 100       | 7.4%    |
| Russia       | 96        | 7.1%    |
| Brazil       | 76        | 5.62%   |
| France       | 74        | 5.47%   |
| Italy        | 66        | 4.88%   |
| UK           | 51        | 3.77%   |
| Spain        | 44        | 3.25%   |
| Mexico       | 35        | 2.59%   |
| Canada       | 34        | 2.51%   |
| India        | 21        | 1.55%   |
| Czechia      | 21        | 1.55%   |
| Australia    | 21        | 1.55%   |
| Argentina    | 20        | 1.48%   |
| Japan        | 18        | 1.33%   |
| Netherlands  | 17        | 1.26%   |
| Hungary      | 16        | 1.18%   |
| Belgium      | 16        | 1.18%   |
| Romania      | 14        | 1.04%   |
| Sweden       | 13        | 0.96%   |
| Indonesia    | 13        | 0.96%   |
| Austria      | 12        | 0.89%   |
| Greece       | 11        | 0.81%   |
| Turkey       | 10        | 0.74%   |
| Ukraine      | 9         | 0.67%   |
| Switzerland  | 9         | 0.67%   |
| Kazakhstan   | 9         | 0.67%   |
| Peru         | 8         | 0.59%   |
| Norway       | 8         | 0.59%   |
| Iran         | 8         | 0.59%   |
| China        | 8         | 0.59%   |
| Bulgaria     | 8         | 0.59%   |
| South Africa | 7         | 0.52%   |
| Slovakia     | 7         | 0.52%   |
| Philippines  | 7         | 0.52%   |
| Lithuania    | 7         | 0.52%   |
| Finland      | 7         | 0.52%   |
| Colombia     | 7         | 0.52%   |
| Belarus      | 7         | 0.52%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Moscow         | 16        | 1.18%   |
| St Petersburg  | 12        | 0.88%   |
| Warsaw         | 11        | 0.81%   |
| Berlin         | 10        | 0.74%   |
| Paris          | 9         | 0.66%   |
| Vienna         | 8         | 0.59%   |
| Milan          | 8         | 0.59%   |
| Hamburg        | 8         | 0.59%   |
| Szczecin       | 7         | 0.52%   |
| Melbourne      | 7         | 0.52%   |
| Krakow         | 7         | 0.52%   |
| Turin          | 6         | 0.44%   |
| Prague         | 6         | 0.44%   |
| Madrid         | 6         | 0.44%   |
| Herentals      | 6         | 0.44%   |
| Buenos Aires   | 6         | 0.44%   |
| Budapest       | 6         | 0.44%   |
| Bengaluru      | 6         | 0.44%   |
| Tokyo          | 5         | 0.37%   |
| Sydney         | 5         | 0.37%   |
| Stuttgart      | 5         | 0.37%   |
| Rome           | 5         | 0.37%   |
| Poznan         | 5         | 0.37%   |
| Guatemala City | 5         | 0.37%   |
| Gdansk         | 5         | 0.37%   |
| Düsseldorf    | 5         | 0.37%   |
| Belgrade       | 5         | 0.37%   |
| Thessaloniki   | 4         | 0.29%   |
| Singapore      | 4         | 0.29%   |
| Shiraz         | 4         | 0.29%   |
| Sao Paulo      | 4         | 0.29%   |
| Rio de Janeiro | 4         | 0.29%   |
| Minsk          | 4         | 0.29%   |
| Johannesburg   | 4         | 0.29%   |
| Hyderabad      | 4         | 0.29%   |
| Essen          | 4         | 0.29%   |
| Athens         | 4         | 0.29%   |
| Zielona Góra  | 3         | 0.22%   |
| Uberlândia    | 3         | 0.22%   |
| Toronto        | 3         | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 247       | 288    | 11.8%   |
| WDC                          | 246       | 289    | 11.75%  |
| Samsung Electronics          | 234       | 281    | 11.18%  |
| SanDisk                      | 142       | 155    | 6.78%   |
| Kingston                     | 119       | 135    | 5.69%   |
| Toshiba                      | 116       | 127    | 5.54%   |
| Unknown                      | 72        | 87     | 3.44%   |
| Crucial                      | 67        | 78     | 3.2%    |
| Hitachi                      | 58        | 59     | 2.77%   |
| China                        | 51        | 56     | 2.44%   |
| SK hynix                     | 41        | 46     | 1.96%   |
| Phison Electronics           | 33        | 37     | 1.58%   |
| Intel                        | 29        | 33     | 1.39%   |
| A-DATA Technology            | 29        | 31     | 1.39%   |
| HGST                         | 28        | 28     | 1.34%   |
| Kingston Technology Company  | 26        | 27     | 1.24%   |
| Micron/Crucial Technology    | 24        | 28     | 1.15%   |
| Micron Technology            | 24        | 25     | 1.15%   |
| Patriot                      | 22        | 22     | 1.05%   |
| MAXIO Technology (Hangzhou)  | 22        | 28     | 1.05%   |
| SPCC                         | 20        | 22     | 0.96%   |
| ADATA Technology             | 20        | 22     | 0.96%   |
| GOODRAM                      | 19        | 23     | 0.91%   |
| Intenso                      | 18        | 22     | 0.86%   |
| Unknown                      | 17        | 18     | 0.81%   |
| Silicon Motion               | 15        | 17     | 0.72%   |
| PNY                          | 15        | 18     | 0.72%   |
| Apacer                       | 13        | 13     | 0.62%   |
| Realtek Semiconductor        | 12        | 12     | 0.57%   |
| JMicron Technology           | 12        | 12     | 0.57%   |
| Team                         | 11        | 12     | 0.53%   |
| Shenzhen Longsys Electronics | 11        | 12     | 0.53%   |
| Realtek                      | 11        | 11     | 0.53%   |
| Maxtor                       | 11        | 11     | 0.53%   |
| KIOXIA                       | 10        | 10     | 0.48%   |
| Transcend                    | 9         | 10     | 0.43%   |
| Lexar                        | 9         | 9      | 0.43%   |
| USB                          | 8         | 8      | 0.38%   |
| LITEON                       | 7         | 7      | 0.33%   |
| Fanxiang                     | 7         | 7      | 0.33%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 34        | 1.51%   |
| Kingston SA400S37240G 240GB SSD                       | 31        | 1.37%   |
| Kingston SA400S37480G 480GB SSD                       | 25        | 1.11%   |
| Seagate ST500DM002-1BD142 500GB                       | 19        | 0.84%   |
| Unknown MMC Card  64GB                                | 17        | 0.75%   |
| Unknown                                               | 17        | 0.75%   |
| Kingston SA400S37120G 120GB SSD                       | 16        | 0.71%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                   | 15        | 0.66%   |
| Toshiba MQ01ABF050 500GB                              | 14        | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 512GB | 14        | 0.62%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 2TB      | 13        | 0.58%   |
| Toshiba DT01ACA100 1TB                                | 12        | 0.53%   |
| Seagate ST1000DM010-2EP102 1TB                        | 12        | 0.53%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB      | 12        | 0.53%   |
| Samsung SSD 850 EVO 250GB                             | 12        | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 12        | 0.53%   |
| Crucial CT500MX500SSD1 500GB                          | 12        | 0.53%   |
| Unknown MMC Card  32GB                                | 11        | 0.49%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                 | 11        | 0.49%   |
| Crucial CT1000MX500SSD1 1TB                           | 11        | 0.49%   |
| WDC WD10EZEX-08WN4A0 1TB                              | 10        | 0.44%   |
| Unknown MMC Card  128GB                               | 10        | 0.44%   |
| Seagate ST9500325AS 500GB                             | 10        | 0.44%   |
| Samsung SSD 850 EVO 500GB                             | 10        | 0.44%   |
| Phison PS5013 E13 NVMe Controller 500GB               | 10        | 0.44%   |
| Phison E12 NVMe Controller 1TB                        | 10        | 0.44%   |
| Sandisk WD Blue SN570 1TB                             | 9         | 0.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 9         | 0.4%    |
| China SSD 256GB                                       | 9         | 0.4%    |
| Unknown SD/MMC/MS PRO 2GB                             | 8         | 0.35%   |
| Seagate ST500LT012-1DG142 500GB                       | 8         | 0.35%   |
| Seagate ST3500418AS 500GB                             | 8         | 0.35%   |
| SanDisk SSD PLUS 480GB                                | 8         | 0.35%   |
| SanDisk SSD PLUS 240GB                                | 8         | 0.35%   |
| Samsung SSD 860 EVO 500GB                             | 8         | 0.35%   |
| Samsung SSD 860 EVO 250GB                             | 8         | 0.35%   |
| Kingston Company SNV2S1000G 1TB                       | 8         | 0.35%   |
| JMicron Generic 320GB                                 | 8         | 0.35%   |
| HGST HTS545050A7E680 500GB                            | 8         | 0.35%   |
| GOODRAM SSDPR-CX400-512-G2 512GB                      | 8         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 240       | 277    | 32.48%  |
| WDC                 | 217       | 248    | 29.36%  |
| Toshiba             | 99        | 110    | 13.4%   |
| Hitachi             | 58        | 59     | 7.85%   |
| Samsung Electronics | 34        | 39     | 4.6%    |
| HGST                | 28        | 28     | 3.79%   |
| Maxtor              | 11        | 11     | 1.49%   |
| Unknown             | 9         | 9      | 1.22%   |
| JMicron Technology  | 8         | 8      | 1.08%   |
| Fujitsu             | 6         | 6      | 0.81%   |
| ASMT                | 4         | 5      | 0.54%   |
| Apple               | 4         | 4      | 0.54%   |
| USB3.0              | 3         | 3      | 0.41%   |
| USB                 | 3         | 3      | 0.41%   |
| TO Exter            | 2         | 2      | 0.27%   |
| KESU                | 2         | 2      | 0.27%   |
| WD MediaMax         | 1         | 1      | 0.14%   |
| SAGE                | 1         | 1      | 0.14%   |
| PRO-T5              | 1         | 1      | 0.14%   |
| Maxone              | 1         | 1      | 0.14%   |
| Intenso             | 1         | 2      | 0.14%   |
| Inateck             | 1         | 1      | 0.14%   |
| HGST HTS            | 1         | 1      | 0.14%   |
| Fantom              | 1         | 1      | 0.14%   |
| External            | 1         | 1      | 0.14%   |
| Esmart              | 1         | 1      | 0.14%   |
| CIRAGO              | 1         | 1      | 0.14%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 131       | 144    | 16.11%  |
| Kingston            | 98        | 110    | 12.05%  |
| Crucial             | 67        | 78     | 8.24%   |
| SanDisk             | 63        | 65     | 7.75%   |
| China               | 51        | 56     | 6.27%   |
| WDC                 | 37        | 41     | 4.55%   |
| A-DATA Technology   | 29        | 30     | 3.57%   |
| Patriot             | 21        | 21     | 2.58%   |
| SPCC                | 20        | 22     | 2.46%   |
| GOODRAM             | 19        | 23     | 2.34%   |
| Intenso             | 17        | 20     | 2.09%   |
| PNY                 | 15        | 18     | 1.85%   |
| Unknown             | 14        | 15     | 1.72%   |
| Apacer              | 13        | 13     | 1.6%    |
| Team                | 11        | 12     | 1.35%   |
| Transcend           | 9         | 10     | 1.11%   |
| Lexar               | 9         | 9      | 1.11%   |
| SK hynix            | 8         | 8      | 0.98%   |
| Intel               | 8         | 8      | 0.98%   |
| Toshiba             | 7         | 7      | 0.86%   |
| LITEON              | 7         | 7      | 0.86%   |
| Corsair             | 7         | 7      | 0.86%   |
| Netac               | 6         | 7      | 0.74%   |
| LITEONIT            | 6         | 6      | 0.74%   |
| Plextor             | 5         | 5      | 0.62%   |
| OCZ                 | 5         | 5      | 0.62%   |
| Micron Technology   | 5         | 5      | 0.62%   |
| KingSpec            | 5         | 5      | 0.62%   |
| Verbatim            | 4         | 4      | 0.49%   |
| Seagate             | 3         | 4      | 0.37%   |
| SABRENT             | 3         | 3      | 0.37%   |
| Mushkin             | 3         | 3      | 0.37%   |
| Leven               | 3         | 3      | 0.37%   |
| HS-SSD-E100         | 3         | 3      | 0.37%   |
| Gigabyte Technology | 3         | 3      | 0.37%   |
| Fanxiang            | 3         | 3      | 0.37%   |
| ASMT                | 3         | 3      | 0.37%   |
| Apple               | 3         | 3      | 0.37%   |
| XrayDisk            | 2         | 2      | 0.25%   |
| walram              | 2         | 2      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 663       | 880    | 37.33%  |
| HDD     | 615       | 826    | 34.63%  |
| NVMe    | 409       | 537    | 23.03%  |
| MMC     | 56        | 61     | 3.15%   |
| Unknown | 33        | 44     | 1.86%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1049      | 1602   | 63.77%  |
| NVMe | 404       | 520    | 24.56%  |
| SAS  | 136       | 165    | 8.27%   |
| MMC  | 56        | 61     | 3.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 802       | 1070   | 59.9%   |
| 0.51-1.0   | 376       | 441    | 28.08%  |
| 1.01-2.0   | 99        | 116    | 7.39%   |
| 3.01-4.0   | 28        | 35     | 2.09%   |
| 2.01-3.0   | 15        | 17     | 1.12%   |
| 4.01-10.0  | 14        | 21     | 1.05%   |
| 10.01-20.0 | 4         | 5      | 0.3%    |
| 20.01-50.0 | 1         | 1      | 0.07%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 584       | 43%     |
| 101-250        | 236       | 17.38%  |
| 251-500        | 179       | 13.18%  |
| 501-1000       | 87        | 6.41%   |
| Unknown        | 75        | 5.52%   |
| 51-100         | 58        | 4.27%   |
| 21-50          | 48        | 3.53%   |
| 1001-2000      | 41        | 3.02%   |
| More than 3000 | 26        | 1.91%   |
| 2001-3000      | 24        | 1.77%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1036      | 76.34%  |
| Unknown        | 75        | 5.53%   |
| 0              | 61        | 4.5%    |
| 21-50          | 59        | 4.35%   |
| 101-250        | 39        | 2.87%   |
| 51-100         | 36        | 2.65%   |
| 501-1000       | 22        | 1.62%   |
| 251-500        | 18        | 1.33%   |
| 1001-2000      | 7         | 0.52%   |
| More than 3000 | 4         | 0.29%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 9         | 9      | 2.65%   |
| Seagate ST9500325AS 500GB             | 6         | 6      | 1.76%   |
| Toshiba MQ01ABF050 500GB              | 5         | 6      | 1.47%   |
| Seagate ST3500418AS 500GB             | 5         | 5      | 1.47%   |
| Seagate ST1000LM035-1RK172 1TB        | 5         | 5      | 1.47%   |
| WDC WD Green 2.5 240GB                | 4         | 4      | 1.18%   |
| Samsung Electronics HD161HJ 160GB     | 4         | 4      | 1.18%   |
| Samsung Electronics HD103SI 1TB       | 4         | 4      | 1.18%   |
| HGST HTS545050A7E680 500GB            | 4         | 4      | 1.18%   |
| WDC WD5000AAKX-60U6AA0 500GB          | 3         | 3      | 0.88%   |
| WDC WD5000AAKX-00ERMA0 500GB          | 3         | 3      | 0.88%   |
| WDC WD5000AAKS-00A7B2 500GB           | 3         | 3      | 0.88%   |
| WDC WD10EZEX-08WN4A0 1TB              | 3         | 3      | 0.88%   |
| WDC WD10EARS-00Y5B1 1TB               | 3         | 3      | 0.88%   |
| Seagate ST500LT012-1DG142 500GB       | 3         | 3      | 0.88%   |
| Seagate ST3500413AS 500GB             | 3         | 3      | 0.88%   |
| Seagate ST1000DM010-2EP102 1TB        | 3         | 4      | 0.88%   |
| Seagate ST1000DM003-9YN162 1TB        | 3         | 3      | 0.88%   |
| Hitachi HTS545032B9A300 320GB         | 3         | 3      | 0.88%   |
| Crucial CT525MX300SSD1 528GB          | 3         | 3      | 0.88%   |
| WDC WD5000AAKX-75U6AA0 500GB          | 2         | 2      | 0.59%   |
| WDC WD5000AAKX-221CA1 500GB           | 2         | 3      | 0.59%   |
| WDC WD5000AAKX-083CA1 500GB           | 2         | 2      | 0.59%   |
| WDC WD10JPVX-60JC3T1 1TB              | 2         | 2      | 0.59%   |
| WDC WD10EZEX-00BN5A0 1TB              | 2         | 2      | 0.59%   |
| Toshiba MK3265GSX 320GB               | 2         | 2      | 0.59%   |
| SK hynix PC711 HFS512GDE9X073N 512GB  | 2         | 2      | 0.59%   |
| SK hynix HFS256G3AMNB-2200A 256GB SSD | 2         | 2      | 0.59%   |
| Seagate ST9160412AS 160GB             | 2         | 2      | 0.59%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 2      | 0.59%   |
| Seagate ST3750640NS 752GB             | 2         | 2      | 0.59%   |
| Seagate ST320LT012-9WS14C 320GB       | 2         | 2      | 0.59%   |
| Seagate ST320LT007-9ZV142 320GB       | 2         | 2      | 0.59%   |
| Seagate ST320LM001 HN-M320MBB 320GB   | 2         | 2      | 0.59%   |
| Seagate ST2000LM007-1R8174 2TB        | 2         | 2      | 0.59%   |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 2      | 0.59%   |
| SanDisk SSD PLUS 480GB                | 2         | 2      | 0.59%   |
| SanDisk SSD PLUS 240GB                | 2         | 2      | 0.59%   |
| Samsung Electronics HD642JJ 640GB     | 2         | 2      | 0.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 88        | 94     | 26.43%  |
| WDC                         | 74        | 78     | 22.22%  |
| Toshiba                     | 27        | 28     | 8.11%   |
| Samsung Electronics         | 27        | 29     | 8.11%   |
| Hitachi                     | 25        | 26     | 7.51%   |
| HGST                        | 10        | 10     | 3%      |
| SanDisk                     | 8         | 8      | 2.4%    |
| Maxtor                      | 7         | 7      | 2.1%    |
| A-DATA Technology           | 7         | 7      | 2.1%    |
| Kingston                    | 6         | 6      | 1.8%    |
| SK hynix                    | 5         | 5      | 1.5%    |
| Crucial                     | 5         | 5      | 1.5%    |
| Fujitsu                     | 4         | 4      | 1.2%    |
| China                       | 4         | 4      | 1.2%    |
| Realtek Semiconductor       | 3         | 3      | 0.9%    |
| Netac                       | 3         | 3      | 0.9%    |
| Intel                       | 3         | 3      | 0.9%    |
| SSSTC                       | 2         | 2      | 0.6%    |
| Patriot                     | 2         | 2      | 0.6%    |
| LITEONIT                    | 2         | 2      | 0.6%    |
| Corsair                     | 2         | 2      | 0.6%    |
| Apple                       | 2         | 2      | 0.6%    |
| WD MediaMax                 | 1         | 1      | 0.3%    |
| T-FORCE                     | 1         | 1      | 0.3%    |
| SPCC                        | 1         | 1      | 0.3%    |
| sk600                       | 1         | 1      | 0.3%    |
| OCZ                         | 1         | 1      | 0.3%    |
| Micron/Crucial Technology   | 1         | 1      | 0.3%    |
| Micron Technology           | 1         | 1      | 0.3%    |
| MCTECH                      | 1         | 1      | 0.3%    |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.3%    |
| HGST HTS                    | 1         | 1      | 0.3%    |
| GLOWAY                      | 1         | 1      | 0.3%    |
| faspeed                     | 1         | 1      | 0.3%    |
| Drevo                       | 1         | 1      | 0.3%    |
| ASMT                        | 1         | 1      | 0.3%    |
| ADATA Technology            | 1         | 1      | 0.3%    |
| Acer                        | 1         | 1      | 0.3%    |
| Unknown                     | 1         | 1      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 88        | 94     | 34.92%  |
| WDC                 | 68        | 72     | 26.98%  |
| Toshiba             | 27        | 28     | 10.71%  |
| Hitachi             | 25        | 26     | 9.92%   |
| Samsung Electronics | 19        | 20     | 7.54%   |
| HGST                | 10        | 10     | 3.97%   |
| Maxtor              | 7         | 7      | 2.78%   |
| Fujitsu             | 4         | 4      | 1.59%   |
| WD MediaMax         | 1         | 1      | 0.4%    |
| HGST HTS            | 1         | 1      | 0.4%    |
| ASMT                | 1         | 1      | 0.4%    |
| Apple               | 1         | 1      | 0.4%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 234       | 265    | 74.52%  |
| SSD  | 70        | 72     | 22.29%  |
| NVMe | 10        | 10     | 3.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD1600AAJS-00L7A0 160GB                      | 1         | 1      | 20%     |
| WDC WD10EZEX-08WN4A0 1TB                         | 1         | 1      | 20%     |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 20%     |
| Samsung Electronics HM250HI 250GB                | 1         | 1      | 20%     |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Samsung Electronics | 2         | 2      | 40%     |
| HGST                | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1113      | 1804   | 70.27%  |
| Malfunc  | 307       | 347    | 19.38%  |
| Detected | 159       | 192    | 10.04%  |
| Failed   | 5         | 5      | 0.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 843       | 48.73%  |
| AMD                              | 362       | 20.92%  |
| Samsung Electronics              | 85        | 4.91%   |
| SanDisk                          | 82        | 4.74%   |
| Kingston Technology Company      | 50        | 2.89%   |
| Phison Electronics               | 34        | 1.97%   |
| SK hynix                         | 33        | 1.91%   |
| Micron/Crucial Technology        | 24        | 1.39%   |
| ASMedia Technology               | 23        | 1.33%   |
| MAXIO Technology (Hangzhou)      | 22        | 1.27%   |
| ADATA Technology                 | 21        | 1.21%   |
| Micron Technology                | 19        | 1.1%    |
| Marvell Technology Group         | 19        | 1.1%    |
| Silicon Motion                   | 15        | 0.87%   |
| Nvidia                           | 13        | 0.75%   |
| JMicron Technology               | 13        | 0.75%   |
| Realtek Semiconductor            | 12        | 0.69%   |
| Shenzhen Longsys Electronics     | 11        | 0.64%   |
| Toshiba America Info Systems     | 10        | 0.58%   |
| KIOXIA                           | 10        | 0.58%   |
| Solid State Storage Technology   | 5         | 0.29%   |
| Union Memory (Shenzhen)          | 4         | 0.23%   |
| INNOGRIT                         | 3         | 0.17%   |
| VIA Technologies                 | 2         | 0.12%   |
| Solidigm                         | 2         | 0.12%   |
| Hosin Global Electronics         | 2         | 0.12%   |
| Sony                             | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Silicon Image                    | 1         | 0.06%   |
| Seagate Technology               | 1         | 0.06%   |
| LSI Logic / Symbios Logic        | 1         | 0.06%   |
| Lenovo                           | 1         | 0.06%   |
| Integrated Technology Express    | 1         | 0.06%   |
| Broadcom / LSI                   | 1         | 0.06%   |
| Biwin Storage Technology         | 1         | 0.06%   |
| Artop Electronic                 | 1         | 0.06%   |
| Unknown                          | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 222       | 11.17%  |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 81        | 4.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 77        | 3.88%   |
| AMD 500 Series Chipset SATA Controller                                                  | 46        | 2.32%   |
| AMD 400 Series Chipset SATA Controller                                                  | 45        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 43        | 2.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 39        | 1.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 34        | 1.71%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 34        | 1.71%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 31        | 1.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 31        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 31        | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 30        | 1.51%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 30        | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 28        | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 28        | 1.41%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 27        | 1.36%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 25        | 1.26%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 25        | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 24        | 1.21%   |
| Intel SATA Controller [RAID mode]                                                       | 23        | 1.16%   |
| AMD 600 Series Chipset SATA Controller                                                  | 23        | 1.16%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 22        | 1.11%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 21        | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 21        | 1.06%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 20        | 1.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 19        | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 18        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 16        | 0.81%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 16        | 0.81%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 15        | 0.75%   |
| AMD 300 Series Chipset SATA Controller                                                  | 15        | 0.75%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 14        | 0.7%    |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                            | 14        | 0.7%    |
| Intel Volume Management Device NVMe RAID Controller                                     | 14        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 14        | 0.7%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 14        | 0.7%    |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                                | 13        | 0.65%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD [E18]                                    | 13        | 0.65%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1057      | 61.67%  |
| NVMe | 404       | 23.57%  |
| IDE  | 177       | 10.33%  |
| RAID | 71        | 4.14%   |
| SCSI | 3         | 0.18%   |
| SAS  | 2         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 910       | 67.31%  |
| AMD    | 442       | 32.69%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| AMD Ryzen 5 5500U with Radeon Graphics | 16        | 1.18%   |
| Intel Core i5-3470 CPU @ 3.20GHz       | 15        | 1.11%   |
| AMD Ryzen 5 5600X 6-Core Processor     | 14        | 1.04%   |
| AMD Ryzen 5 5600G with Radeon Graphics | 14        | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz      | 11        | 0.81%   |
| AMD Ryzen 7 5700G with Radeon Graphics | 11        | 0.81%   |
| Intel Core i3-2120 CPU @ 3.30GHz       | 10        | 0.74%   |
| Intel Celeron CPU N2840 @ 2.16GHz      | 10        | 0.74%   |
| AMD Ryzen 5 3600 6-Core Processor      | 10        | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz      | 9         | 0.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz      | 9         | 0.67%   |
| Intel Celeron N4020 CPU @ 1.10GHz      | 9         | 0.67%   |
| Intel Core i7-4790 CPU @ 3.60GHz       | 8         | 0.59%   |
| Intel Core i5-5300U CPU @ 2.30GHz      | 8         | 0.59%   |
| Intel Core i5-4570 CPU @ 3.20GHz       | 8         | 0.59%   |
| Intel Core i5-3320M CPU @ 2.60GHz      | 8         | 0.59%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz   | 8         | 0.59%   |
| Intel Celeron N4000 CPU @ 1.10GHz      | 8         | 0.59%   |
| AMD Ryzen 9 5900X 12-Core Processor    | 8         | 0.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics | 8         | 0.59%   |
| AMD Ryzen 7 2700X Eight-Core Processor | 8         | 0.59%   |
| Intel Core i5-4300U CPU @ 1.90GHz      | 7         | 0.52%   |
| Intel Core i3-3220 CPU @ 3.30GHz       | 7         | 0.52%   |
| Intel Celeron CPU N3060 @ 1.60GHz      | 7         | 0.52%   |
| Intel 12th Gen Core i5-1235U           | 7         | 0.52%   |
| Intel N100                             | 6         | 0.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz      | 6         | 0.44%   |
| Intel Core i5-4460 CPU @ 3.20GHz       | 6         | 0.44%   |
| Intel Core i3-2350M CPU @ 2.30GHz      | 6         | 0.44%   |
| Intel Core i3-2310M CPU @ 2.10GHz      | 6         | 0.44%   |
| Intel Core i3-2100 CPU @ 3.10GHz       | 6         | 0.44%   |
| Intel Celeron J4125 CPU @ 2.00GHz      | 6         | 0.44%   |
| Intel Core i5-7300U CPU @ 2.60GHz      | 5         | 0.37%   |
| Intel Core i5-5200U CPU @ 2.20GHz      | 5         | 0.37%   |
| Intel Core i5-3230M CPU @ 2.60GHz      | 5         | 0.37%   |
| Intel Core i5-2400 CPU @ 3.10GHz       | 5         | 0.37%   |
| Intel Core i5-10400F CPU @ 2.90GHz     | 5         | 0.37%   |
| Intel Core i5 CPU M 520 @ 2.40GHz      | 5         | 0.37%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz   | 5         | 0.37%   |
| Intel Celeron CPU N3350 @ 1.10GHz      | 5         | 0.37%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 244       | 18.05%  |
| AMD Ryzen 5             | 126       | 9.32%   |
| Intel Core i3           | 120       | 8.88%   |
| Intel Celeron           | 119       | 8.8%    |
| Intel Core i7           | 109       | 8.06%   |
| Other                   | 97        | 7.17%   |
| AMD Ryzen 7             | 93        | 6.88%   |
| Intel Core 2 Duo        | 67        | 4.96%   |
| Intel Pentium           | 48        | 3.55%   |
| Intel Xeon              | 29        | 2.14%   |
| AMD Ryzen 9             | 28        | 2.07%   |
| AMD Ryzen 3             | 25        | 1.85%   |
| Intel Pentium Dual-Core | 19        | 1.41%   |
| Intel Core 2 Quad       | 15        | 1.11%   |
| AMD A8                  | 15        | 1.11%   |
| AMD A10                 | 15        | 1.11%   |
| Intel Atom              | 14        | 1.04%   |
| AMD FX                  | 14        | 1.04%   |
| AMD A4                  | 13        | 0.96%   |
| AMD A6                  | 11        | 0.81%   |
| Intel Pentium Dual      | 10        | 0.74%   |
| AMD Athlon              | 9         | 0.67%   |
| AMD E1                  | 8         | 0.59%   |
| AMD E                   | 8         | 0.59%   |
| AMD Ryzen 5 PRO         | 7         | 0.52%   |
| AMD E2                  | 7         | 0.52%   |
| AMD Athlon II X2        | 7         | 0.52%   |
| Intel Pentium Gold      | 6         | 0.44%   |
| Intel Pentium Silver    | 5         | 0.37%   |
| Intel Core              | 5         | 0.37%   |
| AMD Phenom II X4        | 5         | 0.37%   |
| Intel Genuine           | 4         | 0.3%    |
| Intel Core 2            | 4         | 0.3%    |
| Intel Core i9           | 3         | 0.22%   |
| AMD Turion 64 X2 Mobile | 3         | 0.22%   |
| AMD Athlon X4           | 3         | 0.22%   |
| AMD Athlon II X3        | 3         | 0.22%   |
| AMD Athlon 64 X2        | 3         | 0.22%   |
| Intel Pentium D         | 2         | 0.15%   |
| AMD Sempron             | 2         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 593       | 43.86%  |
| 4      | 395       | 29.22%  |
| 6      | 149       | 11.02%  |
| 8      | 118       | 8.73%   |
| 12     | 27        | 2%      |
| 16     | 19        | 1.41%   |
| 10     | 19        | 1.41%   |
| 1      | 15        | 1.11%   |
| 14     | 7         | 0.52%   |
| 24     | 6         | 0.44%   |
| 3      | 3         | 0.22%   |
| 20     | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1328      | 98.22%  |
| 2      | 22        | 1.63%   |
| 4      | 2         | 0.15%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 764       | 56.51%  |
| 1      | 588       | 43.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1352      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1352      | 100%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Haswell           | 139       | 10.28%  |
| IvyBridge         | 123       | 9.1%    |
| SandyBridge       | 104       | 7.69%   |
| Zen 3             | 97        | 7.17%   |
| Penryn            | 84        | 6.21%   |
| KabyLake          | 80        | 5.92%   |
| Unknown           | 77        | 5.7%    |
| Alderlake Hybrid  | 58        | 4.29%   |
| Zen+              | 55        | 4.07%   |
| Westmere          | 55        | 4.07%   |
| Silvermont        | 51        | 3.77%   |
| Zen 2             | 45        | 3.33%   |
| Core              | 42        | 3.11%   |
| Goldmont plus     | 33        | 2.44%   |
| Broadwell         | 33        | 2.44%   |
| Piledriver        | 30        | 2.22%   |
| Excavator         | 29        | 2.14%   |
| Zen               | 25        | 1.85%   |
| K10               | 23        | 1.7%    |
| Bobcat            | 19        | 1.41%   |
| TigerLake         | 16        | 1.18%   |
| Puma              | 14        | 1.04%   |
| Skylake           | 12        | 0.89%   |
| Gracemont         | 12        | 0.89%   |
| Goldmont          | 12        | 0.89%   |
| CometLake         | 12        | 0.89%   |
| Tremont           | 10        | 0.74%   |
| Steamroller       | 10        | 0.74%   |
| Bonnell           | 10        | 0.74%   |
| Nehalem           | 9         | 0.67%   |
| K8 Hammer         | 9         | 0.67%   |
| Jaguar            | 7         | 0.52%   |
| K10 Llano         | 5         | 0.37%   |
| NetBurst          | 4         | 0.3%    |
| Meteorlake Hybrid | 4         | 0.3%    |
| Bulldozer         | 2         | 0.15%   |
| K8 & K10 hybrid   | 1         | 0.07%   |
| IceLake           | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 717       | 48.22%  |
| AMD                              | 453       | 30.46%  |
| Nvidia                           | 314       | 21.12%  |
| Silicon Integrated Systems [SiS] | 1         | 0.07%   |
| Red Hat                          | 1         | 0.07%   |
| Huawei Technologies              | 1         | 0.07%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 88        | 5.67%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 64        | 4.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 41        | 2.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 39        | 2.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 37        | 2.38%   |
| Intel Core Processor Integrated Graphics Controller                                      | 35        | 2.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 35        | 2.26%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 29        | 1.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 29        | 1.87%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 28        | 1.8%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 1.8%    |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 26        | 1.68%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 24        | 1.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 24        | 1.55%   |
| AMD Lucienne                                                                             | 22        | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 21        | 1.35%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 19        | 1.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 18        | 1.16%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 18        | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.1%    |
| Nvidia GP108 [GeForce GT 1030]                                                           | 15        | 0.97%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 15        | 0.97%   |
| AMD Raphael                                                                              | 15        | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 14        | 0.9%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 14        | 0.9%    |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 13        | 0.84%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 13        | 0.84%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 12        | 0.77%   |
| Intel Alder Lake-N [UHD Graphics]                                                        | 12        | 0.77%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 0.71%   |
| AMD Rembrandt [Radeon 680M]                                                              | 11        | 0.71%   |
| AMD Phoenix1                                                                             | 11        | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 10        | 0.64%   |
| Intel JasperLake [UHD Graphics]                                                          | 10        | 0.64%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 10        | 0.64%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 10        | 0.64%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 9         | 0.58%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 9         | 0.58%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 9         | 0.58%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 9         | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 535       | 39.57%  |
| 1 x AMD                 | 367       | 27.14%  |
| 1 x Nvidia              | 203       | 15.01%  |
| Intel + Nvidia          | 86        | 6.36%   |
| 2 x Intel               | 69        | 5.1%    |
| 2 x AMD                 | 37        | 2.74%   |
| Intel + AMD             | 27        | 2%      |
| AMD + Nvidia            | 22        | 1.63%   |
| 2 x Nvidia              | 3         | 0.22%   |
| 1 x SiS                 | 1         | 0.07%   |
| 1 x Red Hat             | 1         | 0.07%   |
| 1 x Huawei Technologies | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1241      | 91.79%  |
| Unknown     | 101       | 7.47%   |
| Proprietary | 10        | 0.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 636       | 47.04%  |
| 0.01-0.5   | 202       | 14.94%  |
| 1.01-2.0   | 155       | 11.46%  |
| 0.51-1.0   | 121       | 8.95%   |
| 3.01-4.0   | 94        | 6.95%   |
| 7.01-8.0   | 75        | 5.55%   |
| 8.01-16.0  | 28        | 2.07%   |
| 5.01-6.0   | 19        | 1.41%   |
| 2.01-3.0   | 13        | 0.96%   |
| 16.01-24.0 | 8         | 0.59%   |
| 4.01-5.0   | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 205       | 15.1%   |
| AU Optronics            | 149       | 10.97%  |
| LG Display              | 113       | 8.32%   |
| BOE                     | 102       | 7.51%   |
| Chimei Innolux          | 94        | 6.92%   |
| Goldstar                | 68        | 5.01%   |
| Dell                    | 65        | 4.79%   |
| Hewlett-Packard         | 56        | 4.12%   |
| Acer                    | 51        | 3.76%   |
| AOC                     | 42        | 3.09%   |
| Philips                 | 38        | 2.8%    |
| Lenovo                  | 30        | 2.21%   |
| Ancor Communications    | 28        | 2.06%   |
| Iiyama                  | 23        | 1.69%   |
| BenQ                    | 22        | 1.62%   |
| Apple                   | 17        | 1.25%   |
| ASUSTek Computer        | 16        | 1.18%   |
| ViewSonic               | 15        | 1.1%    |
| InfoVision              | 14        | 1.03%   |
| Chi Mei Optoelectronics | 14        | 1.03%   |
| LG Philips              | 11        | 0.81%   |
| Toshiba                 | 10        | 0.74%   |
| Sharp                   | 9         | 0.66%   |
| NEC Computers           | 9         | 0.66%   |
| Sony                    | 8         | 0.59%   |
| MSI                     | 8         | 0.59%   |
| PANDA                   | 7         | 0.52%   |
| Eizo                    | 7         | 0.52%   |
| RTK                     | 6         | 0.44%   |
| InnoLux Display         | 6         | 0.44%   |
| Hitachi                 | 6         | 0.44%   |
| Gigabyte Technology     | 6         | 0.44%   |
| Medion                  | 4         | 0.29%   |
| Fujitsu Siemens         | 4         | 0.29%   |
| CSO                     | 4         | 0.29%   |
| Belinea                 | 4         | 0.29%   |
| Unknown (XXX)           | 3         | 0.22%   |
| Unknown                 | 3         | 0.22%   |
| Sceptre Tech            | 3         | 0.22%   |
| OEM                     | 3         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 7         | 0.51%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 7         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 6         | 0.44%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 6         | 0.44%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 5         | 0.36%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 5         | 0.36%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch | 4         | 0.29%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch | 4         | 0.29%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch      | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 4         | 0.29%   |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 4         | 0.29%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch        | 4         | 0.29%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                   | 4         | 0.29%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 3         | 0.22%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch | 3         | 0.22%   |
| Samsung Electronics C27F390 SAM0D33 1920x1080 598x336mm 27.0-inch    | 3         | 0.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3         | 0.22%   |
| Philips PHL 221V8 PHLC211 1920x1080 477x268mm 21.5-inch              | 3         | 0.22%   |
| OEM 32W_LCD_TV OEM3700 1920x540                                      | 3         | 0.22%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch          | 3         | 0.22%   |
| LG Display LCD Monitor LGD01CA 1600x900 382x215mm 17.3-inch          | 3         | 0.22%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch         | 3         | 0.22%   |
| Iiyama PLT2254 IVM5656 1920x1080 480x270mm 21.7-inch                 | 3         | 0.22%   |
| Hitachi HISENSE HEC0030 3840x2160 1872x1053mm 84.6-inch              | 3         | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 3         | 0.22%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 0.22%   |
| Goldstar E1940 GSM4BD6 1360x768 406x229mm 18.4-inch                  | 3         | 0.22%   |
| Goldstar 32inch FHD GSM76F5 1920x1080 698x392mm 31.5-inch            | 3         | 0.22%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch               | 3         | 0.22%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 597x336mm 27.0-inch       | 3         | 0.22%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 3         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1745 1600x900 382x214mm 17.2-inch      | 3         | 0.22%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 3         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 530       | 39.64%  |
| 1366x768 (WXGA)    | 308       | 23.04%  |
| 1600x900 (HD+)     | 77        | 5.76%   |
| 3840x2160 (4K)     | 75        | 5.61%   |
| 2560x1440 (QHD)    | 62        | 4.64%   |
| 1920x1200 (WUXGA)  | 48        | 3.59%   |
| 1280x1024 (SXGA)   | 41        | 3.07%   |
| 1440x900 (WXGA+)   | 39        | 2.92%   |
| 1280x800 (WXGA)    | 33        | 2.47%   |
| 1680x1050 (WSXGA+) | 31        | 2.32%   |
| 3440x1440          | 15        | 1.12%   |
| 1360x768           | 12        | 0.9%    |
| 2560x1600          | 8         | 0.6%    |
| 2560x1080          | 6         | 0.45%   |
| 2880x1800          | 5         | 0.37%   |
| 1920x540           | 5         | 0.37%   |
| 3200x2000          | 4         | 0.3%    |
| 2160x1440          | 4         | 0.3%    |
| 1600x1200          | 4         | 0.3%    |
| 3840x1080          | 3         | 0.22%   |
| 3200x1800 (QHD+)   | 3         | 0.22%   |
| 2288x1287          | 3         | 0.22%   |
| 1024x600           | 3         | 0.22%   |
| 3840x2400          | 2         | 0.15%   |
| 2880x1920          | 2         | 0.15%   |
| 1920x1280          | 2         | 0.15%   |
| 3840x2560          | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2736x1824          | 1         | 0.07%   |
| 2560x1397          | 1         | 0.07%   |
| 2520x1680          | 1         | 0.07%   |
| 2256x1504          | 1         | 0.07%   |
| 1920x1440          | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |
| 1280x720 (HD)      | 1         | 0.07%   |
| 1152x864           | 1         | 0.07%   |
| 1024x768 (XGA)     | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 319       | 23.34%  |
| 27      | 121       | 8.85%   |
| 24      | 109       | 7.97%   |
| 14      | 100       | 7.32%   |
| 23      | 95        | 6.95%   |
| 21      | 94        | 6.88%   |
| 17      | 85        | 6.22%   |
| 13      | 68        | 4.97%   |
| 19      | 50        | 3.66%   |
| 18      | 44        | 3.22%   |
| 31      | 36        | 2.63%   |
| 20      | 28        | 2.05%   |
| 16      | 24        | 1.76%   |
| 12      | 24        | 1.76%   |
| 11      | 24        | 1.76%   |
| 22      | 20        | 1.46%   |
| 34      | 17        | 1.24%   |
| 32      | 14        | 1.02%   |
| 84      | 11        | 0.8%    |
| 72      | 9         | 0.66%   |
| 54      | 9         | 0.66%   |
| 10      | 7         | 0.51%   |
| 52      | 6         | 0.44%   |
| 25      | 6         | 0.44%   |
| 40      | 5         | 0.37%   |
| 29      | 5         | 0.37%   |
| Unknown | 5         | 0.37%   |
| 65      | 4         | 0.29%   |
| 28      | 4         | 0.29%   |
| 63      | 3         | 0.22%   |
| 142     | 2         | 0.15%   |
| 49      | 2         | 0.15%   |
| 48      | 2         | 0.15%   |
| 46      | 2         | 0.15%   |
| 42      | 2         | 0.15%   |
| 37      | 2         | 0.15%   |
| 77      | 1         | 0.07%   |
| 74      | 1         | 0.07%   |
| 58      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 480       | 35.35%  |
| 501-600        | 314       | 23.12%  |
| 401-500        | 213       | 15.68%  |
| 351-400        | 108       | 7.95%   |
| 201-300        | 87        | 6.41%   |
| 601-700        | 53        | 3.9%    |
| 701-800        | 33        | 2.43%   |
| 1001-1500      | 31        | 2.28%   |
| 1501-2000      | 22        | 1.62%   |
| 801-900        | 8         | 0.59%   |
| Unknown        | 5         | 0.37%   |
| More than 2000 | 2         | 0.15%   |
| 901-1000       | 2         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 1046      | 79.97%  |
| 16/10 | 170       | 13%     |
| 5/4   | 39        | 2.98%   |
| 21/9  | 21        | 1.61%   |
| 3/2   | 13        | 0.99%   |
| 4/3   | 11        | 0.84%   |
| 32/9  | 4         | 0.31%   |
| 1.00  | 2         | 0.15%   |
| 3.20  | 1         | 0.08%   |
| 2.00  | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 320       | 23.55%  |
| 201-250        | 242       | 17.81%  |
| 81-90          | 140       | 10.3%   |
| 301-350        | 125       | 9.2%    |
| 151-200        | 107       | 7.87%   |
| 351-500        | 72        | 5.3%    |
| 141-150        | 56        | 4.12%   |
| 121-130        | 56        | 4.12%   |
| 251-300        | 54        | 3.97%   |
| More than 1000 | 46        | 3.38%   |
| 71-80          | 27        | 1.99%   |
| 51-60          | 26        | 1.91%   |
| 61-70          | 23        | 1.69%   |
| 111-120        | 21        | 1.55%   |
| 501-1000       | 18        | 1.32%   |
| 131-140        | 14        | 1.03%   |
| 41-50          | 5         | 0.37%   |
| Unknown        | 5         | 0.37%   |
| 91-100         | 2         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 542       | 40.54%  |
| 101-120       | 435       | 32.54%  |
| 121-160       | 253       | 18.92%  |
| 161-240       | 52        | 3.89%   |
| 1-50          | 36        | 2.69%   |
| More than 240 | 14        | 1.05%   |
| Unknown       | 5         | 0.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1205      | 89.06%  |
| 2     | 101       | 7.46%   |
| 0     | 42        | 3.1%    |
| 3     | 5         | 0.37%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 851       | 43.35%  |
| Intel                                  | 519       | 26.44%  |
| Qualcomm Atheros                       | 231       | 11.77%  |
| Broadcom                               | 103       | 5.25%   |
| MediaTek                               | 49        | 2.5%    |
| Ralink Technology                      | 23        | 1.17%   |
| Marvell Technology Group               | 23        | 1.17%   |
| TP-Link                                | 20        | 1.02%   |
| Ralink                                 | 17        | 0.87%   |
| Broadcom Limited                       | 16        | 0.82%   |
| ASIX Electronics                       | 16        | 0.82%   |
| Nvidia                                 | 9         | 0.46%   |
| Microsoft                              | 7         | 0.36%   |
| Ericsson Business Mobile Networks      | 6         | 0.31%   |
| Sierra Wireless                        | 5         | 0.25%   |
| NetGear                                | 4         | 0.2%    |
| JMicron Technology                     | 4         | 0.2%    |
| Xiaomi                                 | 3         | 0.15%   |
| VIA Technologies                       | 3         | 0.15%   |
| Qualcomm Atheros Communications        | 3         | 0.15%   |
| Qualcomm                               | 3         | 0.15%   |
| Hewlett-Packard                        | 3         | 0.15%   |
| Edimax Technology                      | 3         | 0.15%   |
| Dell                                   | 3         | 0.15%   |
| Belkin Components                      | 3         | 0.15%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.1%    |
| Samsung Electronics                    | 2         | 0.1%    |
| OPPO Electronics                       | 2         | 0.1%    |
| Mercucys                               | 2         | 0.1%    |
| LG Electronics                         | 2         | 0.1%    |
| ICS Advent                             | 2         | 0.1%    |
| ASUSTek Computer                       | 2         | 0.1%    |
| Accton Technology                      | 2         | 0.1%    |
| Toshiba                                | 1         | 0.05%   |
| Tenda                                  | 1         | 0.05%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.05%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.05%   |
| STMicroelectronics                     | 1         | 0.05%   |
| ROCCAT                                 | 1         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 562       | 24.28%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 108       | 4.67%   |
| Realtek RTL8125 2.5GbE Controller                                      | 52        | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 49        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 46        | 1.99%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 44        | 1.9%    |
| Intel Wi-Fi 6 AX200                                                    | 41        | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 40        | 1.73%   |
| Intel Wireless 7260                                                    | 32        | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 29        | 1.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 28        | 1.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 24        | 1.04%   |
| Intel Wireless 8265 / 8275                                             | 24        | 1.04%   |
| Intel I211 Gigabit Network Connection                                  | 24        | 1.04%   |
| Intel Ethernet Controller I225-V                                       | 24        | 1.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 24        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 23        | 0.99%   |
| Intel Ethernet Connection I217-LM                                      | 22        | 0.95%   |
| Intel Wireless 7265                                                    | 21        | 0.91%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 20        | 0.86%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 18        | 0.78%   |
| Realtek 802.11ac NIC                                                   | 17        | 0.73%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 17        | 0.73%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 16        | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 16        | 0.69%   |
| Intel Wireless 3165                                                    | 16        | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 15        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                          | 15        | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 14        | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 14        | 0.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 14        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                             | 13        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                        | 13        | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 13        | 0.56%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 12        | 0.52%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 12        | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 12        | 0.52%   |
| Intel Wireless 3160                                                    | 12        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 357       | 36.06%  |
| Realtek Semiconductor                 | 236       | 23.84%  |
| Qualcomm Atheros                      | 183       | 18.48%  |
| Broadcom                              | 57        | 5.76%   |
| MediaTek                              | 47        | 4.75%   |
| Ralink Technology                     | 23        | 2.32%   |
| TP-Link                               | 19        | 1.92%   |
| Ralink                                | 17        | 1.72%   |
| Broadcom Limited                      | 9         | 0.91%   |
| Sierra Wireless                       | 5         | 0.51%   |
| Marvell Technology Group              | 5         | 0.51%   |
| NetGear                               | 4         | 0.4%    |
| Qualcomm Atheros Communications       | 3         | 0.3%    |
| Qualcomm                              | 3         | 0.3%    |
| Microsoft                             | 3         | 0.3%    |
| Edimax Technology                     | 3         | 0.3%    |
| Dell                                  | 3         | 0.3%    |
| Belkin Components                     | 3         | 0.3%    |
| Mercucys                              | 2         | 0.2%    |
| ASUSTek Computer                      | 2         | 0.2%    |
| Tenda                                 | 1         | 0.1%    |
| IMC Networks                          | 1         | 0.1%    |
| Ericsson Business Mobile Networks     | 1         | 0.1%    |
| AVM                                   | 1         | 0.1%    |
| Accton Technology                     | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 46        | 4.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 44        | 4.43%   |
| Intel Wi-Fi 6 AX200                                                     | 41        | 4.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 4.02%   |
| Intel Wireless 7260                                                     | 32        | 3.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 29        | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 2.82%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 24        | 2.41%   |
| Intel Wireless 8265 / 8275                                              | 24        | 2.41%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 24        | 2.41%   |
| Intel Wireless 7265                                                     | 21        | 2.11%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 20        | 2.01%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 18        | 1.81%   |
| Realtek 802.11ac NIC                                                    | 17        | 1.71%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 17        | 1.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 16        | 1.61%   |
| Intel Wireless 3165                                                     | 16        | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 15        | 1.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 15        | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 14        | 1.41%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 13        | 1.31%   |
| Ralink MT7601U Wireless Adapter                                         | 13        | 1.31%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 13        | 1.31%   |
| Intel Wireless 3160                                                     | 12        | 1.21%   |
| Intel Wi-Fi 6 AX201                                                     | 12        | 1.21%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 12        | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 11        | 1.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                 | 10        | 1.01%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 10        | 1.01%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 9         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 9         | 0.91%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 8         | 0.8%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 0.8%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 0.8%    |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.8%    |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.8%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 7         | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 753       | 58.87%  |
| Intel                                  | 306       | 23.92%  |
| Qualcomm Atheros                       | 79        | 6.18%   |
| Broadcom                               | 54        | 4.22%   |
| Marvell Technology Group               | 18        | 1.41%   |
| ASIX Electronics                       | 16        | 1.25%   |
| Nvidia                                 | 9         | 0.7%    |
| Broadcom Limited                       | 8         | 0.63%   |
| JMicron Technology                     | 4         | 0.31%   |
| Xiaomi                                 | 3         | 0.23%   |
| VIA Technologies                       | 3         | 0.23%   |
| Microsoft                              | 3         | 0.23%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.16%   |
| Samsung Electronics                    | 2         | 0.16%   |
| OPPO Electronics                       | 2         | 0.16%   |
| MediaTek                               | 2         | 0.16%   |
| LG Electronics                         | 2         | 0.16%   |
| ICS Advent                             | 2         | 0.16%   |
| TP-Link                                | 1         | 0.08%   |
| Suzhou Motorcomm Electronic Technology | 1         | 0.08%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.08%   |
| Huawei Technologies                    | 1         | 0.08%   |
| Hewlett-Packard                        | 1         | 0.08%   |
| DisplayLink                            | 1         | 0.08%   |
| Aquantia                               | 1         | 0.08%   |
| Apple                                  | 1         | 0.08%   |
| ADMtek                                 | 1         | 0.08%   |
| Accton Technology                      | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 562       | 43.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 108       | 8.28%   |
| Realtek RTL8125 2.5GbE Controller                                      | 52        | 3.98%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 49        | 3.75%   |
| Intel I211 Gigabit Network Connection                                  | 24        | 1.84%   |
| Intel Ethernet Controller I225-V                                       | 24        | 1.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 23        | 1.76%   |
| Intel Ethernet Connection I217-LM                                      | 22        | 1.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 16        | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                          | 15        | 1.15%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 1%      |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 12        | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 12        | 0.92%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 12        | 0.92%   |
| Intel Ethernet Connection I218-LM                                      | 11        | 0.84%   |
| Intel Ethernet Connection (4) I219-LM                                  | 11        | 0.84%   |
| Intel 82567LM Gigabit Network Connection                               | 10        | 0.77%   |
| Intel Ethernet Connection I217-V                                       | 9         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 0.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 8         | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 7         | 0.54%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 7         | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 7         | 0.54%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                  | 6         | 0.46%   |
| Intel Ethernet Connection (5) I219-LM                                  | 6         | 0.46%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.46%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 6         | 0.46%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 5         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 5         | 0.38%   |
| Intel Ethernet Controller I226-V                                       | 5         | 0.38%   |
| Intel Ethernet Connection (6) I219-V                                   | 5         | 0.38%   |
| Intel Ethernet Connection (3) I218-V                                   | 5         | 0.38%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5         | 0.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.31%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 4         | 0.31%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 4         | 0.31%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 4         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1216      | 55.63%  |
| WiFi     | 954       | 43.64%  |
| Modem    | 12        | 0.55%   |
| Unknown  | 4         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 714       | 53.56%  |
| WiFi     | 619       | 46.44%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 722       | 53.36%  |
| 1     | 589       | 43.53%  |
| 3     | 26        | 1.92%   |
| 0     | 14        | 1.03%   |
| 5     | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 864       | 63.72%  |
| Yes  | 492       | 36.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 280       | 36.36%  |
| Realtek Semiconductor           | 127       | 16.49%  |
| Cambridge Silicon Radio         | 51        | 6.62%   |
| Qualcomm Atheros Communications | 49        | 6.36%   |
| Broadcom                        | 43        | 5.58%   |
| IMC Networks                    | 40        | 5.19%   |
| Foxconn / Hon Hai               | 37        | 4.81%   |
| Lite-On Technology              | 26        | 3.38%   |
| Apple                           | 20        | 2.6%    |
| MediaTek                        | 17        | 2.21%   |
| ASUSTek Computer                | 16        | 2.08%   |
| Dell                            | 13        | 1.69%   |
| Toshiba                         | 12        | 1.56%   |
| Hewlett-Packard                 | 8         | 1.04%   |
| Marvell Semiconductor           | 6         | 0.78%   |
| Realtek                         | 4         | 0.52%   |
| TP-Link                         | 3         | 0.39%   |
| Alps Electric                   | 3         | 0.39%   |
| USI                             | 2         | 0.26%   |
| Chicony Electronics             | 2         | 0.26%   |
| Actions                         | 2         | 0.26%   |
| Ralink Technology               | 1         | 0.13%   |
| Ralink                          | 1         | 0.13%   |
| Qcom                            | 1         | 0.13%   |
| Integrated System Solution      | 1         | 0.13%   |
| Fujitsu                         | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |
| Edimax Technology               | 1         | 0.13%   |
| Dynex                           | 1         | 0.13%   |
| Conwise Technology              | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 104       | 13.49%  |
| Realtek Bluetooth Radio                             | 86        | 11.15%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 51        | 6.61%   |
| Intel AX200 Bluetooth                               | 38        | 4.93%   |
| Realtek  Bluetooth 4.2 Adapter                      | 28        | 3.63%   |
| Intel Bluetooth Device                              | 27        | 3.5%    |
| Intel AX201 Bluetooth                               | 25        | 3.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 21        | 2.72%   |
| Intel AX210 Bluetooth                               | 21        | 2.72%   |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 2.46%   |
| MediaTek Wireless_Device                            | 17        | 2.2%    |
| IMC Networks Bluetooth Radio                        | 17        | 2.2%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 1.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 14        | 1.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 12        | 1.56%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 1.43%   |
| Intel Wireless-AC 3168 Bluetooth                    | 11        | 1.43%   |
| IMC Networks Wireless_Device                        | 11        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 1.43%   |
| Apple Bluetooth Host Controller                     | 9         | 1.17%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 1.04%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.91%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 7         | 0.91%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.91%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 7         | 0.91%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.91%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.91%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 7         | 0.91%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.78%   |
| IMC Networks Bluetooth Device                       | 6         | 0.78%   |
| Broadcom BCM2045B (BDC-2.1)                         | 6         | 0.78%   |
| Realtek RTL8821A Bluetooth                          | 5         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 5         | 0.65%   |
| Lite-On Bluetooth Device                            | 5         | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.65%   |
| ASUS ASUS USB-BT500                                 | 5         | 0.65%   |
| Toshiba Integrated Bluetooth HCI                    | 4         | 0.52%   |
| Realtek Bluetooth Radio                             | 4         | 0.52%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.52%   |
| Foxconn / Hon Hai BCM20702A0                        | 4         | 0.52%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 890       | 49.44%  |
| AMD                                          | 506       | 28.11%  |
| Nvidia                                       | 264       | 14.67%  |
| C-Media Electronics                          | 19        | 1.06%   |
| Creative Labs                                | 15        | 0.83%   |
| Creative Technology                          | 10        | 0.56%   |
| Generalplus Technology                       | 9         | 0.5%    |
| Zoran Co. Personal Media Division (Nogatech) | 8         | 0.44%   |
| Logitech                                     | 8         | 0.44%   |
| ASUSTek Computer                             | 7         | 0.39%   |
| JMTek                                        | 6         | 0.33%   |
| SteelSeries ApS                              | 4         | 0.22%   |
| Thesycon Systemsoftware & Consulting         | 3         | 0.17%   |
| Tenx Technology                              | 3         | 0.17%   |
| PreSonus Audio Electronics                   | 3         | 0.17%   |
| Micro Star International                     | 3         | 0.17%   |
| KTMicro                                      | 3         | 0.17%   |
| Walmart                                      | 2         | 0.11%   |
| VIA Technologies                             | 2         | 0.11%   |
| Texas Instruments                            | 2         | 0.11%   |
| Kingston Technology                          | 2         | 0.11%   |
| Hewlett-Packard                              | 2         | 0.11%   |
| GYROCOM C&C                                  | 2         | 0.11%   |
| ESI Audiotechnik                             | 2         | 0.11%   |
| Dell                                         | 2         | 0.11%   |
| XMOS                                         | 1         | 0.06%   |
| Valve Software                               | 1         | 0.06%   |
| Universal Audio                              | 1         | 0.06%   |
| Soundprese                                   | 1         | 0.06%   |
| Silicon Integrated Systems [SiS]             | 1         | 0.06%   |
| Philips (or NXP)                             | 1         | 0.06%   |
| Nordic Semiconductor ASA                     | 1         | 0.06%   |
| Microsoft                                    | 1         | 0.06%   |
| M-Audio                                      | 1         | 0.06%   |
| Jieli Technology                             | 1         | 0.06%   |
| HECATE G4 TE GAMING HEADSET                  | 1         | 0.06%   |
| Harman                                       | 1         | 0.06%   |
| Goldvish                                     | 1         | 0.06%   |
| GN Netcom                                    | 1         | 0.06%   |
| FIFINE Microphones                           | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 193       | 8.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 117       | 5.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 101       | 4.41%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 99        | 4.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 89        | 3.89%   |
| AMD FCH Azalia Controller                                                                         | 62        | 2.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 60        | 2.62%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 58        | 2.53%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 57        | 2.49%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 49        | 2.14%   |
| AMD Radeon High Definition Audio Controller                                                       | 45        | 1.97%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 44        | 1.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 40        | 1.75%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 37        | 1.62%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 37        | 1.62%   |
| Intel 8 Series HD Audio Controller                                                                | 37        | 1.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 36        | 1.57%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 33        | 1.44%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 33        | 1.44%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 30        | 1.31%   |
| Intel Broadwell-U Audio Controller                                                                | 30        | 1.31%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 30        | 1.31%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 30        | 1.31%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 29        | 1.27%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 29        | 1.27%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 28        | 1.22%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 27        | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 22        | 0.96%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 20        | 0.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 19        | 0.83%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 19        | 0.83%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 19        | 0.83%   |
| Nvidia High Definition Audio Controller                                                           | 18        | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 18        | 0.79%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 18        | 0.79%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 18        | 0.79%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 18        | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 0.74%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 16        | 0.7%    |
| Intel 200 Series PCH HD Audio                                                                     | 16        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 296       | 18.31%  |
| SK hynix                     | 258       | 15.96%  |
| Kingston                     | 217       | 13.42%  |
| Unknown                      | 169       | 10.45%  |
| Micron Technology            | 133       | 8.23%   |
| Crucial                      | 91        | 5.63%   |
| Corsair                      | 67        | 4.14%   |
| G.Skill                      | 63        | 3.9%    |
| Unknown                      | 40        | 2.47%   |
| A-DATA Technology            | 35        | 2.16%   |
| Ramaxel Technology           | 34        | 2.1%    |
| Elpida                       | 27        | 1.67%   |
| Nanya Technology             | 26        | 1.61%   |
| Team                         | 18        | 1.11%   |
| Unknown (ABCD)               | 12        | 0.74%   |
| Transcend                    | 10        | 0.62%   |
| Smart                        | 10        | 0.62%   |
| Patriot                      | 9         | 0.56%   |
| GOODRAM                      | 8         | 0.49%   |
| AMD                          | 8         | 0.49%   |
| Apacer                       | 6         | 0.37%   |
| Timetec                      | 5         | 0.31%   |
| Qimonda                      | 5         | 0.31%   |
| PNY                          | 4         | 0.25%   |
| Patriot Memory (PDP Systems) | 3         | 0.19%   |
| Patriot Memory               | 3         | 0.19%   |
| Lexar Co Limited             | 3         | 0.19%   |
| Kingmax                      | 3         | 0.19%   |
| ASint Technology             | 3         | 0.19%   |
| Unknown (0x5846)             | 2         | 0.12%   |
| Unknown (0x2C0C)             | 2         | 0.12%   |
| Thermaltake                  | 2         | 0.12%   |
| Teikon                       | 2         | 0.12%   |
| Smart Brazil                 | 2         | 0.12%   |
| Lexar                        | 2         | 0.12%   |
| Kllisre                      | 2         | 0.12%   |
| Wodposit                     | 1         | 0.06%   |
| Wilk                         | 1         | 0.06%   |
| Unknown (0x8001)             | 1         | 0.06%   |
| Unknown (0x7F7F7F94FFFFFFFF) | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 40        | 2.27%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 1.14%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 16        | 0.91%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 12        | 0.68%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 2667MT/s           | 12        | 0.68%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.63%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.57%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.57%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 10        | 0.57%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 9         | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 9         | 0.51%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 8         | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.45%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 7         | 0.4%    |
| Unknown RAM Module 4GB DIMM 1600MT/s                             | 7         | 0.4%    |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2133MT/s   | 7         | 0.4%    |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 7         | 0.4%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.4%    |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3                       | 7         | 0.4%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 2133MT/s              | 7         | 0.4%    |
| Unknown RAM Module 4GB SODIMM DDR3                               | 6         | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 6         | 0.34%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 6         | 0.34%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 6         | 0.34%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 6         | 0.34%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 6         | 0.34%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 6         | 0.34%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.34%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 6         | 0.34%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 6         | 0.34%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 5         | 0.28%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 5         | 0.28%   |
| Unknown RAM Module 2GB SODIMM DDR2 800MT/s                       | 5         | 0.28%   |
| Unknown RAM Module 2GB DIMM DDR2 667MT/s                         | 5         | 0.28%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.28%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.28%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.28%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 588       | 43.2%   |
| DDR4    | 465       | 34.17%  |
| DDR2    | 86        | 6.32%   |
| DDR5    | 58        | 4.26%   |
| SDRAM   | 53        | 3.89%   |
| Unknown | 36        | 2.65%   |
| LPDDR4  | 29        | 2.13%   |
| LPDDR5  | 28        | 2.06%   |
| LPDDR3  | 9         | 0.66%   |
| DDR     | 7         | 0.51%   |
| RAM     | 1         | 0.07%   |
| DRAM    | 1         | 0.07%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 684       | 51.16%  |
| DIMM         | 583       | 43.61%  |
| Row Of Chips | 61        | 4.56%   |
| Unknown      | 6         | 0.45%   |
| Chip         | 2         | 0.15%   |
| FB-DIMM      | 1         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 503       | 33.25%  |
| 4096  | 482       | 31.86%  |
| 2048  | 248       | 16.39%  |
| 16384 | 171       | 11.3%   |
| 32768 | 50        | 3.3%    |
| 1024  | 49        | 3.24%   |
| 512   | 5         | 0.33%   |
| 3072  | 2         | 0.13%   |
| 24576 | 1         | 0.07%   |
| 12288 | 1         | 0.07%   |
| 16    | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 402       | 26.57%  |
| 3200    | 178       | 11.76%  |
| 1333    | 127       | 8.39%   |
| 2667    | 114       | 7.53%   |
| 2400    | 96        | 6.35%   |
| 667     | 53        | 3.5%    |
| 3600    | 52        | 3.44%   |
| 1334    | 45        | 2.97%   |
| 2133    | 40        | 2.64%   |
| 800     | 40        | 2.64%   |
| 6400    | 24        | 1.59%   |
| 1067    | 24        | 1.59%   |
| Unknown | 23        | 1.52%   |
| 1867    | 21        | 1.39%   |
| 5600    | 19        | 1.26%   |
| 4800    | 17        | 1.12%   |
| 1866    | 17        | 1.12%   |
| 1066    | 14        | 0.93%   |
| 4199    | 13        | 0.86%   |
| 3800    | 13        | 0.86%   |
| 3733    | 12        | 0.79%   |
| 2666    | 11        | 0.73%   |
| 2048    | 11        | 0.73%   |
| 1800    | 11        | 0.73%   |
| 3266    | 10        | 0.66%   |
| 6000    | 9         | 0.59%   |
| 4000    | 8         | 0.53%   |
| 3400    | 8         | 0.53%   |
| 533     | 8         | 0.53%   |
| 3466    | 7         | 0.46%   |
| 4267    | 6         | 0.4%    |
| 975     | 6         | 0.4%    |
| 2933    | 5         | 0.33%   |
| 400     | 5         | 0.33%   |
| 5200    | 4         | 0.26%   |
| 4266    | 4         | 0.26%   |
| 8400    | 3         | 0.2%    |
| 6200    | 3         | 0.2%    |
| 4333    | 3         | 0.2%    |
| 3333    | 3         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 12        | 30%     |
| Hewlett-Packard     | 11        | 27.5%   |
| Seiko Epson         | 6         | 15%     |
| Canon               | 6         | 15%     |
| Samsung Electronics | 2         | 5%      |
| Prolific Technology | 2         | 5%      |
| Dymo-CoStar         | 1         | 2.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port          | 2         | 5%      |
| Seiko Epson XP-2100 Series             | 1         | 2.5%    |
| Seiko Epson Printer                    | 1         | 2.5%    |
| Seiko Epson L3560 Series               | 1         | 2.5%    |
| Seiko Epson ET-2850 Series             | 1         | 2.5%    |
| Seiko Epson ET-2710 Series             | 1         | 2.5%    |
| Seiko Epson EPSON L132 Series          | 1         | 2.5%    |
| Samsung ML-1610 Mono Laser Printer     | 1         | 2.5%    |
| Samsung C1810 Series                   | 1         | 2.5%    |
| HP Smart Tank 750 series               | 1         | 2.5%    |
| HP LaserJet 1020                       | 1         | 2.5%    |
| HP LaserJet 1000                       | 1         | 2.5%    |
| HP DeskJet 930c                        | 1         | 2.5%    |
| HP DeskJet 6940 series                 | 1         | 2.5%    |
| HP DeskJet 4530 series                 | 1         | 2.5%    |
| HP DeskJet 4100 series                 | 1         | 2.5%    |
| HP DeskJet 3630 series                 | 1         | 2.5%    |
| HP DeskJet 2600 series                 | 1         | 2.5%    |
| HP DeskJet 1110 series                 | 1         | 2.5%    |
| HP Deskjet 1000 J110 series            | 1         | 2.5%    |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 2.5%    |
| Canon TS5300 series                    | 1         | 2.5%    |
| Canon TS3400 series                    | 1         | 2.5%    |
| Canon TS3100 series                    | 1         | 2.5%    |
| Canon PIXMA MX370 Series               | 1         | 2.5%    |
| Canon MF210 Series                     | 1         | 2.5%    |
| Canon G3010 series                     | 1         | 2.5%    |
| Brother MFC-L2710DW series             | 1         | 2.5%    |
| Brother MFC-L2710DN series             | 1         | 2.5%    |
| Brother MFC-J4340DW                    | 1         | 2.5%    |
| Brother MFC-J1010DW                    | 1         | 2.5%    |
| Brother HL-L2370DW series              | 1         | 2.5%    |
| Brother HL-L2305 series                | 1         | 2.5%    |
| Brother HL-B2080DW series              | 1         | 2.5%    |
| Brother HL-2270DW Laser Printer        | 1         | 2.5%    |
| Brother HL-2140 series                 | 1         | 2.5%    |
| Brother HL-1210W series                | 1         | 2.5%    |
| Brother DCP-L2550DW series             | 1         | 2.5%    |
| Brother DCP-L2530DW series             | 1         | 2.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 75%     |
| Seiko Epson | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                  | 2         | 50%     |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 25%     |
| Canon CanoScan LiDE 200                                 | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 164       | 24.81%  |
| IMC Networks                           | 56        | 8.47%   |
| Sunplus Innovation Technology          | 46        | 6.96%   |
| Realtek Semiconductor                  | 45        | 6.81%   |
| Microdia                               | 41        | 6.2%    |
| Quanta                                 | 37        | 5.6%    |
| Bison Electronics                      | 37        | 5.6%    |
| Logitech                               | 27        | 4.08%   |
| Suyin                                  | 24        | 3.63%   |
| Luxvisions Innotech Limited            | 20        | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 18        | 2.72%   |
| Apple                                  | 17        | 2.57%   |
| Syntek                                 | 11        | 1.66%   |
| Silicon Motion                         | 10        | 1.51%   |
| Alcor Micro                            | 9         | 1.36%   |
| Ricoh                                  | 8         | 1.21%   |
| Microsoft                              | 8         | 1.21%   |
| Lenovo                                 | 7         | 1.06%   |
| Acer                                   | 7         | 1.06%   |
| Z-Star Microelectronics                | 6         | 0.91%   |
| Lite-On Technology                     | 6         | 0.91%   |
| ShineTech                              | 5         | 0.76%   |
| SunplusIT                              | 3         | 0.45%   |
| OmniVision Technologies                | 3         | 0.45%   |
| KYE Systems (Mouse Systems)            | 3         | 0.45%   |
| Importek                               | 3         | 0.45%   |
| Unknown                                | 3         | 0.45%   |
| WaveRider Communications               | 2         | 0.3%    |
| Sonix Technology                       | 2         | 0.3%    |
| Shine-optics                           | 2         | 0.3%    |
| Samsung Electronics                    | 2         | 0.3%    |
| Jieli Technology                       | 2         | 0.3%    |
| Genesys Logic                          | 2         | 0.3%    |
| Generalplus Technology                 | 2         | 0.3%    |
| Aveo Technology                        | 2         | 0.3%    |
| Y Media                                | 1         | 0.15%   |
| Xiongmai                               | 1         | 0.15%   |
| webcamvendor                           | 1         | 0.15%   |
| Valve Software                         | 1         | 0.15%   |
| Trust                                  | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 26        | 3.92%   |
| IMC Networks Integrated Camera                                 | 17        | 2.56%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 15        | 2.26%   |
| Chicony HD WebCam                                              | 13        | 1.96%   |
| Microdia Integrated_Webcam_HD                                  | 10        | 1.51%   |
| Apple Built-in iSight                                          | 10        | 1.51%   |
| Sunplus HD WebCam                                              | 8         | 1.21%   |
| Realtek Integrated_Webcam_HD                                   | 8         | 1.21%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 8         | 1.21%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 8         | 1.21%   |
| Chicony TOSHIBA Web Camera - HD                                | 8         | 1.21%   |
| Chicony HP TrueVision HD Camera                                | 8         | 1.21%   |
| Syntek Integrated Camera                                       | 7         | 1.06%   |
| Sunplus Integrated_Webcam_HD                                   | 7         | 1.06%   |
| Realtek USB Camera                                             | 7         | 1.06%   |
| IMC Networks UVC VGA Webcam                                    | 7         | 1.06%   |
| Chicony FJ Camera                                              | 7         | 1.06%   |
| Bison Lenovo EasyCamera                                        | 7         | 1.06%   |
| Sunplus Laptop Integrated Webcam HD                            | 6         | 0.9%    |
| Quanta HP TrueVision HD Camera                                 | 6         | 0.9%    |
| Microdia Integrated Webcam                                     | 6         | 0.9%    |
| Quanta HP Wide Vision HD Camera                                | 5         | 0.75%   |
| Quanta HP Webcam                                               | 5         | 0.75%   |
| Microdia USB 2.0 Camera                                        | 5         | 0.75%   |
| Luxvisions Innotech Limited Integrated Camera                  | 5         | 0.75%   |
| Logitech Webcam C270                                           | 5         | 0.75%   |
| IMC Networks Integrated Webcam                                 | 5         | 0.75%   |
| Chicony VGA WebCam                                             | 5         | 0.75%   |
| Chicony USB2.0 HD UVC WebCam                                   | 5         | 0.75%   |
| Chicony HP Webcam                                              | 5         | 0.75%   |
| Bison Integrated Camera                                        | 5         | 0.75%   |
| Acer Integrated Camera                                         | 5         | 0.75%   |
| Silicon Motion WebCam SC-0311139N                              | 4         | 0.6%    |
| Quanta HD Webcam                                               | 4         | 0.6%    |
| Microdia Laptop_Integrated_Webcam_HD                           | 4         | 0.6%    |
| Chicony HP TrueVision HD                                       | 4         | 0.6%    |
| Chicony HD User Facing                                         | 4         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.6%    |
| Z-Star A4 TECH USB2.0 PC Camera E                              | 3         | 0.45%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 3         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 27        | 34.62%  |
| AuthenTec                          | 16        | 20.51%  |
| Synaptics                          | 13        | 16.67%  |
| Shenzhen Goodix Technology         | 7         | 8.97%   |
| Elan Microelectronics              | 7         | 8.97%   |
| Upek                               | 5         | 6.41%   |
| STMicroelectronics                 | 1         | 1.28%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.28%   |
| Focal-systems.Corp                 | 1         | 1.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 8.97%   |
| Elan ELAN:ARM-M4                                                           | 6         | 7.69%   |
| AuthenTec AES2810                                                          | 6         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 6.41%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 6.41%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 5.13%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 5.13%   |
| Validity Sensors VFS491                                                    | 4         | 5.13%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 5.13%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 3.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 3.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 2.56%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 2.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.56%   |
| AuthenTec AES1600                                                          | 2         | 2.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 1.28%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.28%   |
| Synaptics TouchPad                                                         | 1         | 1.28%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 1.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.28%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.28%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1.28%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.28%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.28%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 1.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 21        | 46.67%  |
| Alcor Micro           | 10        | 22.22%  |
| Lenovo                | 5         | 11.11%  |
| O2 Micro              | 4         | 8.89%   |
| Upek                  | 3         | 6.67%   |
| Realtek Semiconductor | 1         | 2.22%   |
| Aktiv                 | 1         | 2.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 28.89%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 22.22%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 11.11%  |
| Broadcom 5880                                                                | 5         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 8.89%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.67%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.22%   |
| Aktiv Rutoken lite                                                           | 1         | 2.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1112      | 82.19%  |
| 1     | 211       | 15.59%  |
| 2     | 27        | 2%      |
| 3     | 2         | 0.15%   |
| 5     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 102       | 38.06%  |
| Fingerprint reader       | 78        | 29.1%   |
| Chipcard                 | 43        | 16.04%  |
| Net/wireless             | 18        | 6.72%   |
| Communication controller | 6         | 2.24%   |
| Storage                  | 5         | 1.87%   |
| Unassigned class         | 4         | 1.49%   |
| Camera                   | 4         | 1.49%   |
| Multimedia controller    | 3         | 1.12%   |
| Tv card                  | 1         | 0.37%   |
| Net/ethernet             | 1         | 0.37%   |
| Modem                    | 1         | 0.37%   |
| Card reader              | 1         | 0.37%   |
| Bluetooth                | 1         | 0.37%   |

