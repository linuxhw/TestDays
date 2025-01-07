Linux in Japan - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Japan.

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

Total: 1122

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Sword 15 A11UD              | [d0dce2f4fe](https://linux-hardware.org/?probe=d0dce2f4fe) | Jan 06, 2025 |
| Panasonic     | CF-NX2AWLCS                 | [e3ead6c710](https://linux-hardware.org/?probe=e3ead6c710) | Jan 05, 2025 |
| Lenovo        | IdeaPad Slim 5 14IMH9 83... | [455af071a7](https://linux-hardware.org/?probe=455af071a7) | Jan 04, 2025 |
| Dell          | Latitude 5300               | [d3d6e520f5](https://linux-hardware.org/?probe=d3d6e520f5) | Jan 03, 2025 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [06b6bc85d9](https://linux-hardware.org/?probe=06b6bc85d9) | Dec 29, 2024 |
| MSI           | Prestige 13 AI+ Evo A2VM... | [c973dc57a1](https://linux-hardware.org/?probe=c973dc57a1) | Dec 28, 2024 |
| NEC Comput... | PC-LL750MSW                 | [55d20a7230](https://linux-hardware.org/?probe=55d20a7230) | Dec 27, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ    | [39f2b622bf](https://linux-hardware.org/?probe=39f2b622bf) | Dec 26, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [b163061b61](https://linux-hardware.org/?probe=b163061b61) | Dec 25, 2024 |
| Valve         | Jupiter                     | [61b4cfc7d9](https://linux-hardware.org/?probe=61b4cfc7d9) | Dec 24, 2024 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [32f125d899](https://linux-hardware.org/?probe=32f125d899) | Dec 22, 2024 |
| NEC Comput... | PC-VK15EBZCG                | [cda3177d46](https://linux-hardware.org/?probe=cda3177d46) | Dec 22, 2024 |
| NEC Comput... | PC-VJ22MAN5HJR9             | [7b6a88a981](https://linux-hardware.org/?probe=7b6a88a981) | Dec 21, 2024 |
| Sony          | VPCEH39FJ                   | [f0627de40e](https://linux-hardware.org/?probe=f0627de40e) | Dec 16, 2024 |
| Panasonic     | CFLX5-3L                    | [a63e171786](https://linux-hardware.org/?probe=a63e171786) | Dec 15, 2024 |
| Fujitsu       | FMVA30DN                    | [b859d288a9](https://linux-hardware.org/?probe=b859d288a9) | Dec 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [43ae490d8a](https://linux-hardware.org/?probe=43ae490d8a) | Dec 07, 2024 |
| NEC Comput... | PC-GN174FAAU                | [c90b112e13](https://linux-hardware.org/?probe=c90b112e13) | Dec 06, 2024 |
| Fujitsu       | FMVA42MW2                   | [a5a7a4a6f1](https://linux-hardware.org/?probe=a5a7a4a6f1) | Dec 03, 2024 |
| Lenovo        | ThinkBook 14 G6+ AHP 21L... | [481811d3d1](https://linux-hardware.org/?probe=481811d3d1) | Dec 02, 2024 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [42386d1cbc](https://linux-hardware.org/?probe=42386d1cbc) | Dec 01, 2024 |
| Timi          | RedmiBook Pro 14S           | [6512821d69](https://linux-hardware.org/?probe=6512821d69) | Nov 29, 2024 |
| Panasonic     | CF-W8FWDAJS                 | [b07a63717b](https://linux-hardware.org/?probe=b07a63717b) | Nov 28, 2024 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [15258f1ad9](https://linux-hardware.org/?probe=15258f1ad9) | Nov 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4da22094eb](https://linux-hardware.org/?probe=4da22094eb) | Nov 25, 2024 |
| Apple         | MacBookPro8,1               | [5a3f525db9](https://linux-hardware.org/?probe=5a3f525db9) | Nov 21, 2024 |
| Acer          | Aspire A315-51              | [291ffae1d7](https://linux-hardware.org/?probe=291ffae1d7) | Nov 20, 2024 |
| Acer          | Predator PHN16-71           | [6bcd55ded7](https://linux-hardware.org/?probe=6bcd55ded7) | Nov 18, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [b3e2e79950](https://linux-hardware.org/?probe=b3e2e79950) | Nov 15, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [e89ff25201](https://linux-hardware.org/?probe=e89ff25201) | Nov 13, 2024 |
| Apple         | MacBook10,1                 | [ec28f65d6a](https://linux-hardware.org/?probe=ec28f65d6a) | Nov 13, 2024 |
| Lenovo        | Yoga Pro 14s ASP9 83HN      | [59d0ece152](https://linux-hardware.org/?probe=59d0ece152) | Nov 11, 2024 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [7a8258de47](https://linux-hardware.org/?probe=7a8258de47) | Nov 10, 2024 |
| Fujitsu       | FMVC07003                   | [9fe5e42140](https://linux-hardware.org/?probe=9fe5e42140) | Nov 10, 2024 |
| Dell          | XPS 13 9380                 | [a4c9bc1cdc](https://linux-hardware.org/?probe=a4c9bc1cdc) | Nov 02, 2024 |
| HUAWEI        | HKFG-XX                     | [af1fb5aee3](https://linux-hardware.org/?probe=af1fb5aee3) | Nov 02, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [212b448485](https://linux-hardware.org/?probe=212b448485) | Nov 01, 2024 |
| Dell          | Precision M4600             | [80d81a4a86](https://linux-hardware.org/?probe=80d81a4a86) | Oct 30, 2024 |
| Dell          | Inspiron 13-7378            | [bef26cea2c](https://linux-hardware.org/?probe=bef26cea2c) | Oct 29, 2024 |
| Dynabook      | B65/ER                      | [8febbfeb09](https://linux-hardware.org/?probe=8febbfeb09) | Oct 29, 2024 |
| Lenovo        | LOQ 15IRX9 83DV             | [f64e78ab22](https://linux-hardware.org/?probe=f64e78ab22) | Oct 27, 2024 |
| Lenovo        | ThinkPad X240 20ALA0NCJP    | [da905b3fdf](https://linux-hardware.org/?probe=da905b3fdf) | Oct 25, 2024 |
| Lenovo        | ThinkPad X240 20ALA0NCJP    | [ca3a28a903](https://linux-hardware.org/?probe=ca3a28a903) | Oct 23, 2024 |
| HP            | ProBook 4525s               | [1d0a0e4c65](https://linux-hardware.org/?probe=1d0a0e4c65) | Oct 22, 2024 |
| Lenovo        | ThinkPad X260 20F5A13P00    | [4ac4d50f73](https://linux-hardware.org/?probe=4ac4d50f73) | Oct 17, 2024 |
| Dell          | Inspiron 14 5420            | [d8efb3a203](https://linux-hardware.org/?probe=d8efb3a203) | Oct 07, 2024 |
| Dynabook      | B65/ER                      | [bd458a3336](https://linux-hardware.org/?probe=bd458a3336) | Oct 05, 2024 |
| Dell          | Inspiron 5409               | [4ba6e16ff2](https://linux-hardware.org/?probe=4ba6e16ff2) | Oct 04, 2024 |
| Fujitsu       | FMVA12001                   | [fda024f87c](https://linux-hardware.org/?probe=fda024f87c) | Oct 02, 2024 |
| MSI           | Prestige 13 AI+ Evo A2VM... | [f8edffb3f0](https://linux-hardware.org/?probe=f8edffb3f0) | Oct 01, 2024 |
| MSI           | Prestige 13 AI+ Evo A2VM... | [9be89b2454](https://linux-hardware.org/?probe=9be89b2454) | Sep 30, 2024 |
| MSI           | Prestige 13 AI+ Evo A2VM... | [6c955086d2](https://linux-hardware.org/?probe=6c955086d2) | Sep 30, 2024 |
| Toshiba       | dynabook T552/36HR          | [89711f38a1](https://linux-hardware.org/?probe=89711f38a1) | Sep 30, 2024 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [cffa867b9e](https://linux-hardware.org/?probe=cffa867b9e) | Sep 29, 2024 |
| Toshiba       | dynabook T451/46DB          | [f6a932816b](https://linux-hardware.org/?probe=f6a932816b) | Sep 29, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | [ce28e0de6c](https://linux-hardware.org/?probe=ce28e0de6c) | Sep 27, 2024 |
| Lenovo        | ThinkPad L570 20J8S01L00    | [4dc13bc8ce](https://linux-hardware.org/?probe=4dc13bc8ce) | Sep 25, 2024 |
| Toshiba       | dynabook T451/46DB          | [e07c4b3693](https://linux-hardware.org/?probe=e07c4b3693) | Sep 25, 2024 |
| Dell          | Latitude E6520              | [7bc7db0af4](https://linux-hardware.org/?probe=7bc7db0af4) | Sep 25, 2024 |
| Lenovo        | ThinkPad X201 3249MJJ       | [04987f2d0e](https://linux-hardware.org/?probe=04987f2d0e) | Sep 23, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | [4c04674392](https://linux-hardware.org/?probe=4c04674392) | Sep 23, 2024 |
| Dell          | Inspiron 5767               | [79a423c743](https://linux-hardware.org/?probe=79a423c743) | Sep 22, 2024 |
| MouseCompu... | W110ER                      | [8ec07c61c5](https://linux-hardware.org/?probe=8ec07c61c5) | Sep 22, 2024 |
| Fujitsu       | FARR01002                   | [496acfd8d9](https://linux-hardware.org/?probe=496acfd8d9) | Sep 17, 2024 |
| Acer          | Aspire 5750                 | [d030037b8b](https://linux-hardware.org/?probe=d030037b8b) | Sep 14, 2024 |
| ASUSTek       | UX390UAK                    | [470d1f4a43](https://linux-hardware.org/?probe=470d1f4a43) | Sep 12, 2024 |
| ASUSTek       | UX390UAK                    | [284c1bc958](https://linux-hardware.org/?probe=284c1bc958) | Sep 12, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [e12ee6b7f5](https://linux-hardware.org/?probe=e12ee6b7f5) | Sep 10, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA60... | [b8ad436c0d](https://linux-hardware.org/?probe=b8ad436c0d) | Sep 10, 2024 |
| HP            | EliteBook 2170p             | [8b5d0ed681](https://linux-hardware.org/?probe=8b5d0ed681) | Sep 02, 2024 |
| Valve         | Jupiter                     | [60fa984831](https://linux-hardware.org/?probe=60fa984831) | Sep 01, 2024 |
| NEC Comput... | PC-LL750MG                  | [474e27a830](https://linux-hardware.org/?probe=474e27a830) | Sep 01, 2024 |
| Lenovo        | ThinkPad X390 20Q1S4E300    | [4e8088ef1a](https://linux-hardware.org/?probe=4e8088ef1a) | Sep 01, 2024 |
| ShenZhen Z... | NA08H                       | [9b814ce223](https://linux-hardware.org/?probe=9b814ce223) | Aug 26, 2024 |
| Toshiba       | dynabook TX/66JBL           | [ee2b9fdb4c](https://linux-hardware.org/?probe=ee2b9fdb4c) | Aug 20, 2024 |
| Toshiba       | dynabook TX/66JBL           | [167feb9699](https://linux-hardware.org/?probe=167feb9699) | Aug 19, 2024 |
| Apple         | MacBookAir7,2               | [ba6e6e37a9](https://linux-hardware.org/?probe=ba6e6e37a9) | Aug 16, 2024 |
| Toshiba       | dynabook Satellite B654/... | [67a37011ca](https://linux-hardware.org/?probe=67a37011ca) | Aug 15, 2024 |
| Lenovo        | ThinkPad T14 Gen 1 20UDA... | [2d97d245a2](https://linux-hardware.org/?probe=2d97d245a2) | Aug 10, 2024 |
| HP            | Pavilion Laptop 15-eh1xx... | [9465561e04](https://linux-hardware.org/?probe=9465561e04) | Aug 08, 2024 |
| NEC Comput... | PC-VK19SGZDF                | [1a1c85aa6c](https://linux-hardware.org/?probe=1a1c85aa6c) | Aug 04, 2024 |
| Lenovo        | ThinkPad E14 Gen 5 21JRC... | [b3dc8b802c](https://linux-hardware.org/?probe=b3dc8b802c) | Aug 04, 2024 |
| UNICOMPUTE    | UltiBook 14 i044            | [7655465774](https://linux-hardware.org/?probe=7655465774) | Aug 03, 2024 |
| Google        | Cyan                        | [58bc969283](https://linux-hardware.org/?probe=58bc969283) | Aug 02, 2024 |
| Lenovo        | Yoga Pro 14s ARH7 82TL      | [c6cbaa3a37](https://linux-hardware.org/?probe=c6cbaa3a37) | Aug 02, 2024 |
| Fujitsu       | FMVNFA40J                   | [0dc6a87a7e](https://linux-hardware.org/?probe=0dc6a87a7e) | Jul 25, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7ddcc47c13](https://linux-hardware.org/?probe=7ddcc47c13) | Jul 24, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [4c5754c4b3](https://linux-hardware.org/?probe=4c5754c4b3) | Jul 24, 2024 |
| Toshiba       | dynabook R734/M             | [74f02e03a1](https://linux-hardware.org/?probe=74f02e03a1) | Jul 23, 2024 |
| Sony          | VPCEH29FJ                   | [5ddbf63438](https://linux-hardware.org/?probe=5ddbf63438) | Jul 22, 2024 |
| Lenovo        | ThinkPad L13 20R4S2F900     | [02b2e03991](https://linux-hardware.org/?probe=02b2e03991) | Jul 20, 2024 |
| Acer          | Predator PH16-71            | [edc46c2a54](https://linux-hardware.org/?probe=edc46c2a54) | Jul 20, 2024 |
| Fujitsu       | FMVA42CW                    | [5ee0019cae](https://linux-hardware.org/?probe=5ee0019cae) | Jul 18, 2024 |
| Lenovo        | Legion Y7000 81FW           | [828ea2e910](https://linux-hardware.org/?probe=828ea2e910) | Jul 13, 2024 |
| Toshiba       | dynabook B25/24TB           | [cf2fb6e9e0](https://linux-hardware.org/?probe=cf2fb6e9e0) | Jul 09, 2024 |
| Toshiba       | dynabook R732/G             | [192a335e2c](https://linux-hardware.org/?probe=192a335e2c) | Jul 07, 2024 |
| HP            | EliteBook 840 14 inch G1... | [c8da56a38d](https://linux-hardware.org/?probe=c8da56a38d) | Jul 06, 2024 |
| HONOR         | HYM-WXX                     | [ed3de23258](https://linux-hardware.org/?probe=ed3de23258) | Jul 04, 2024 |
| HONOR         | HYM-WXX                     | [351857a4f4](https://linux-hardware.org/?probe=351857a4f4) | Jul 04, 2024 |
| NEC Comput... | PC-VY10ACZ75                | [076287df6c](https://linux-hardware.org/?probe=076287df6c) | Jul 03, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2d6c568d03](https://linux-hardware.org/?probe=2d6c568d03) | Jun 27, 2024 |
| RWC           | DA-T118-SR                  | [05f141e671](https://linux-hardware.org/?probe=05f141e671) | Jun 26, 2024 |
| NEC Comput... | PC-VJ26MBZCF                | [8ba01f3c6c](https://linux-hardware.org/?probe=8ba01f3c6c) | Jun 25, 2024 |
| Valve         | Jupiter                     | [ae5ea1127e](https://linux-hardware.org/?probe=ae5ea1127e) | Jun 22, 2024 |
| Valve         | Jupiter                     | [cc34802c81](https://linux-hardware.org/?probe=cc34802c81) | Jun 19, 2024 |
| Alienware     | m18 R2                      | [8045c4dbfa](https://linux-hardware.org/?probe=8045c4dbfa) | Jun 17, 2024 |
| Fujitsu       | LIFEBOOK U7510              | [740b1dcc5b](https://linux-hardware.org/?probe=740b1dcc5b) | Jun 16, 2024 |
| Alienware     | m18 R2                      | [a53ab85d27](https://linux-hardware.org/?probe=a53ab85d27) | Jun 16, 2024 |
| Panasonic     | CF-SX2LDHTS                 | [1881299053](https://linux-hardware.org/?probe=1881299053) | Jun 10, 2024 |
| Panasonic     | CFSZ6-2                     | [ed31738fc4](https://linux-hardware.org/?probe=ed31738fc4) | Jun 10, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [2dfed2a45a](https://linux-hardware.org/?probe=2dfed2a45a) | Jun 03, 2024 |
| MouseCompu... | MPro-NB391                  | [2bc650d69e](https://linux-hardware.org/?probe=2bc650d69e) | May 28, 2024 |
| MouseCompu... | MPro-NB391                  | [d2353efdcc](https://linux-hardware.org/?probe=d2353efdcc) | May 24, 2024 |
| Dell          | Inspiron 13 5330            | [bf22ef091a](https://linux-hardware.org/?probe=bf22ef091a) | May 23, 2024 |
| Sony          | VPCEE47FJ                   | [33e7fc3dcf](https://linux-hardware.org/?probe=33e7fc3dcf) | May 22, 2024 |
| Apple         | MacBook10,1                 | [a682dc5b4c](https://linux-hardware.org/?probe=a682dc5b4c) | May 22, 2024 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [05cb61a4e3](https://linux-hardware.org/?probe=05cb61a4e3) | May 19, 2024 |
| Toshiba       | dynabook T451/34DW          | [87ede60d59](https://linux-hardware.org/?probe=87ede60d59) | May 10, 2024 |
| Dynabook      | G83/HS                      | [df87d8cd42](https://linux-hardware.org/?probe=df87d8cd42) | May 09, 2024 |
| Dell          | Inspiron 14-3467            | [0a3d23b4a1](https://linux-hardware.org/?probe=0a3d23b4a1) | May 09, 2024 |
| Dell          | Inspiron N5040              | [5fae884a07](https://linux-hardware.org/?probe=5fae884a07) | May 08, 2024 |
| Intel         | STCK1A32WFC H67490-302      | [51c75f3848](https://linux-hardware.org/?probe=51c75f3848) | May 08, 2024 |
| Apple         | MacBookPro11,2              | [0ff911f7ac](https://linux-hardware.org/?probe=0ff911f7ac) | May 08, 2024 |
| Fujitsu       | FMVNR1PE                    | [95504ca73e](https://linux-hardware.org/?probe=95504ca73e) | May 08, 2024 |
| NEC Comput... | PC-LS350SSB                 | [530b3713dd](https://linux-hardware.org/?probe=530b3713dd) | May 08, 2024 |
| Apple         | MacBookPro16,2              | [fe05b165fb](https://linux-hardware.org/?probe=fe05b165fb) | May 04, 2024 |
| Google        | Elemi                       | [a6ea033cf0](https://linux-hardware.org/?probe=a6ea033cf0) | May 03, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [8cd1bfd7aa](https://linux-hardware.org/?probe=8cd1bfd7aa) | Apr 30, 2024 |
| Lenovo        | ThinkPad T16 Gen 2 21K7C... | [29f2579a02](https://linux-hardware.org/?probe=29f2579a02) | Apr 27, 2024 |
| NEC Comput... | PC-LS350SSW                 | [a0abb6c6a6](https://linux-hardware.org/?probe=a0abb6c6a6) | Apr 24, 2024 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [334a6f0385](https://linux-hardware.org/?probe=334a6f0385) | Apr 24, 2024 |
| Fujitsu       | FMVA40B1RJ                  | [b0d3f0b365](https://linux-hardware.org/?probe=b0d3f0b365) | Apr 20, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [59aceeb367](https://linux-hardware.org/?probe=59aceeb367) | Apr 18, 2024 |
| Dell          | Latitude E5470              | [f286256e09](https://linux-hardware.org/?probe=f286256e09) | Apr 17, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8d0c1cd8eb](https://linux-hardware.org/?probe=8d0c1cd8eb) | Apr 12, 2024 |
| Lenovo        | G510 20238                  | [db4d2ebd4f](https://linux-hardware.org/?probe=db4d2ebd4f) | Apr 12, 2024 |
| Apple         | MacBookPro11,5              | [d48fd50ca7](https://linux-hardware.org/?probe=d48fd50ca7) | Apr 11, 2024 |
| Dell          | Latitude 3190               | [4f2b2351b3](https://linux-hardware.org/?probe=4f2b2351b3) | Apr 09, 2024 |
| Toshiba       | dynabook T554/45LB          | [da72e21681](https://linux-hardware.org/?probe=da72e21681) | Apr 07, 2024 |
| MSI           | Prestige 16 AI Studio B1... | [03e388324a](https://linux-hardware.org/?probe=03e388324a) | Apr 07, 2024 |
| HP            | Notebook                    | [7ed4d5435b](https://linux-hardware.org/?probe=7ed4d5435b) | Apr 03, 2024 |
| HP            | Notebook                    | [cefd396a65](https://linux-hardware.org/?probe=cefd396a65) | Apr 02, 2024 |
| ASUSTek       | K53TA                       | [d27da7dcab](https://linux-hardware.org/?probe=d27da7dcab) | Apr 01, 2024 |
| Toshiba       | dynabook R63/F              | [953540775e](https://linux-hardware.org/?probe=953540775e) | Mar 29, 2024 |
| Apple         | MacBookPro9,2               | [fdfc1584b0](https://linux-hardware.org/?probe=fdfc1584b0) | Mar 23, 2024 |
| NEC Comput... | PC-LE150C2                  | [3cbfa07c97](https://linux-hardware.org/?probe=3cbfa07c97) | Mar 21, 2024 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [fe203f4b3c](https://linux-hardware.org/?probe=fe203f4b3c) | Mar 20, 2024 |
| HUAWEI        | CREM-WXX9                   | [38269c9b67](https://linux-hardware.org/?probe=38269c9b67) | Mar 20, 2024 |
| HP            | ProBook 430 G7              | [05be2ac277](https://linux-hardware.org/?probe=05be2ac277) | Mar 17, 2024 |
| NEC Comput... | PC-VK23LBZDU                | [24b87183b2](https://linux-hardware.org/?probe=24b87183b2) | Mar 16, 2024 |
| Fujitsu       | FARQ10003                   | [85d8b675fc](https://linux-hardware.org/?probe=85d8b675fc) | Mar 14, 2024 |
| Toshiba       | dynabook T552/36GB          | [9da00148f4](https://linux-hardware.org/?probe=9da00148f4) | Mar 14, 2024 |
| Fujitsu       | FARQ10003                   | [c65688098c](https://linux-hardware.org/?probe=c65688098c) | Mar 13, 2024 |
| Lenovo        | ThinkPad L540 20AVA05CJP    | [ac69dd4e65](https://linux-hardware.org/?probe=ac69dd4e65) | Mar 12, 2024 |
| Panasonic ... | FZ55-3                      | [f26a0e6fd3](https://linux-hardware.org/?probe=f26a0e6fd3) | Mar 12, 2024 |
| Lenovo        | ThinkPad L540 20AVA05CJP    | [b38dfb0116](https://linux-hardware.org/?probe=b38dfb0116) | Mar 11, 2024 |
| HP            | 2133                        | [262c68f9a7](https://linux-hardware.org/?probe=262c68f9a7) | Mar 08, 2024 |
| HP            | EliteBook 845 G8 Noteboo... | [599ee90001](https://linux-hardware.org/?probe=599ee90001) | Mar 01, 2024 |
| NEC Comput... | PC-VK19SGZDF                | [ac1b71e600](https://linux-hardware.org/?probe=ac1b71e600) | Feb 24, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [65fb12c93f](https://linux-hardware.org/?probe=65fb12c93f) | Feb 22, 2024 |
| MouseCompu... | IStNX3-15HP038              | [84f30f4e97](https://linux-hardware.org/?probe=84f30f4e97) | Feb 17, 2024 |
| ASUSTek       | K95VJ                       | [c82a491d01](https://linux-hardware.org/?probe=c82a491d01) | Feb 16, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [32f752641f](https://linux-hardware.org/?probe=32f752641f) | Feb 14, 2024 |
| Toshiba       | dynabook EX/45CW            | [15397b8cd4](https://linux-hardware.org/?probe=15397b8cd4) | Feb 14, 2024 |
| Toshiba       | dynabook R730/B             | [5de02dedf5](https://linux-hardware.org/?probe=5de02dedf5) | Feb 12, 2024 |
| Lenovo        | ThinkBook 14 G6 ABP 21KJ    | [09aed6b1df](https://linux-hardware.org/?probe=09aed6b1df) | Feb 12, 2024 |
| Google        | Lindar                      | [e3a071ae43](https://linux-hardware.org/?probe=e3a071ae43) | Feb 10, 2024 |
| Sony          | VPCEB38FJ                   | [25e917a912](https://linux-hardware.org/?probe=25e917a912) | Feb 07, 2024 |
| Apple         | MacBookAir9,1               | [8aec869c33](https://linux-hardware.org/?probe=8aec869c33) | Feb 05, 2024 |
| Fujitsu       | FMVMG70WNV                  | [0b1aa48770](https://linux-hardware.org/?probe=0b1aa48770) | Feb 04, 2024 |
| Apple         | MacBookAir4,2               | [2952e00ccb](https://linux-hardware.org/?probe=2952e00ccb) | Feb 02, 2024 |
| Apple         | MacBookAir4,2               | [3173c9ba14](https://linux-hardware.org/?probe=3173c9ba14) | Feb 02, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [8689e993e3](https://linux-hardware.org/?probe=8689e993e3) | Feb 01, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [01332b7a24](https://linux-hardware.org/?probe=01332b7a24) | Feb 01, 2024 |
| Toshiba       | dynabook Satellite B552/... | [9c1f52e62f](https://linux-hardware.org/?probe=9c1f52e62f) | Jan 29, 2024 |
| Fujitsu       | FMVWG2U47                   | [3d23440c14](https://linux-hardware.org/?probe=3d23440c14) | Jan 23, 2024 |
| Lenovo        | ThinkPad T430 2347A81       | [7209687602](https://linux-hardware.org/?probe=7209687602) | Jan 22, 2024 |
| HP            | ProBook 4340s               | [45354af236](https://linux-hardware.org/?probe=45354af236) | Jan 14, 2024 |
| HP            | ProBook 4340s               | [aea3678636](https://linux-hardware.org/?probe=aea3678636) | Jan 14, 2024 |
| Valve         | Jupiter                     | [4b71896940](https://linux-hardware.org/?probe=4b71896940) | Jan 13, 2024 |
| Sony          | VPCS12AFJ                   | [b46e630517](https://linux-hardware.org/?probe=b46e630517) | Jan 05, 2024 |
| Dell          | Inspiron 5583               | [1c3475390d](https://linux-hardware.org/?probe=1c3475390d) | Jan 04, 2024 |
| NEC Comput... | PC-VK26TXZCJ                | [3e752c1012](https://linux-hardware.org/?probe=3e752c1012) | Jan 04, 2024 |
| NEC Comput... | PC-VY10ACZ75                | [0a50a9d9ad](https://linux-hardware.org/?probe=0a50a9d9ad) | Jan 03, 2024 |
| MouseCompu... | EGPN711R307                 | [fc34633537](https://linux-hardware.org/?probe=fc34633537) | Jan 02, 2024 |
| Apple         | MacBookAir9,1               | [5a511e238e](https://linux-hardware.org/?probe=5a511e238e) | Jan 01, 2024 |
| Lenovo        | ThinkPad P1 20MDCTO1WW      | [b66d7c38c1](https://linux-hardware.org/?probe=b66d7c38c1) | Dec 31, 2023 |
| Thirdwave     | Prime Series                | [dc3d167b01](https://linux-hardware.org/?probe=dc3d167b01) | Dec 31, 2023 |
| NEC Comput... | PC-VK19SGZDF                | [aa9f420488](https://linux-hardware.org/?probe=aa9f420488) | Dec 31, 2023 |
| Chuwi         | GemiBook Plus               | [acb06bb39a](https://linux-hardware.org/?probe=acb06bb39a) | Dec 29, 2023 |
| Toshiba       | dynabook Satellite B552/... | [544ae58a40](https://linux-hardware.org/?probe=544ae58a40) | Dec 27, 2023 |
| Panasonic     | CFSZ5-3                     | [73265b056e](https://linux-hardware.org/?probe=73265b056e) | Dec 19, 2023 |
| Fujitsu       | FMVNF70W                    | [cbeca4d4e8](https://linux-hardware.org/?probe=cbeca4d4e8) | Dec 19, 2023 |
| Dell          | Inspiron 3580               | [1daafa6278](https://linux-hardware.org/?probe=1daafa6278) | Dec 17, 2023 |
| Lenovo        | Legion Y7000 81FW           | [71c27a1bf6](https://linux-hardware.org/?probe=71c27a1bf6) | Dec 17, 2023 |
| Apple         | MacBookAir9,1               | [73f451cbe0](https://linux-hardware.org/?probe=73f451cbe0) | Dec 17, 2023 |
| Dell          | Inspiron 3580               | [16097eb9c4](https://linux-hardware.org/?probe=16097eb9c4) | Dec 17, 2023 |
| Lenovo        | ThinkPad X260 20F5A0XWJP    | [7aede5c549](https://linux-hardware.org/?probe=7aede5c549) | Dec 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e7ca2f3a6e](https://linux-hardware.org/?probe=e7ca2f3a6e) | Dec 14, 2023 |
| Dell          | Inspiron 1501               | [c4103f9e5c](https://linux-hardware.org/?probe=c4103f9e5c) | Dec 13, 2023 |
| Dell          | Inspiron 3580               | [47f1e44c7d](https://linux-hardware.org/?probe=47f1e44c7d) | Dec 09, 2023 |
| ASUSTek       | B121                        | [25eda5a74a](https://linux-hardware.org/?probe=25eda5a74a) | Dec 04, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [3316107191](https://linux-hardware.org/?probe=3316107191) | Dec 02, 2023 |
| Sony          | VJS153C11N                  | [eb8f061cb3](https://linux-hardware.org/?probe=eb8f061cb3) | Dec 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [20ad6cbe8e](https://linux-hardware.org/?probe=20ad6cbe8e) | Dec 01, 2023 |
| NEC Comput... | PC-LS150BS6R                | [ffb64219bf](https://linux-hardware.org/?probe=ffb64219bf) | Dec 01, 2023 |
| Toshiba       | dynabook T552/36HR          | [1e3171aa0a](https://linux-hardware.org/?probe=1e3171aa0a) | Nov 30, 2023 |
| Fujitsu       | FMVNS6HE                    | [df459431eb](https://linux-hardware.org/?probe=df459431eb) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [c37b719fb5](https://linux-hardware.org/?probe=c37b719fb5) | Nov 27, 2023 |
| NEC Comput... | PC-NS100C1W-P2              | [10175626ab](https://linux-hardware.org/?probe=10175626ab) | Nov 23, 2023 |
| HP            | ENVY dv6                    | [f86a52da6d](https://linux-hardware.org/?probe=f86a52da6d) | Nov 14, 2023 |
| Acer          | Aspire 5740                 | [7deb21f5d9](https://linux-hardware.org/?probe=7deb21f5d9) | Nov 13, 2023 |
| NEC Comput... | PC-NS100C1W-P2              | [3f3c22657c](https://linux-hardware.org/?probe=3f3c22657c) | Nov 12, 2023 |
| NEC Comput... | PC-NS100C1W-P2              | [d1ccec297d](https://linux-hardware.org/?probe=d1ccec297d) | Nov 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [594257aca2](https://linux-hardware.org/?probe=594257aca2) | Nov 03, 2023 |
| Toshiba       | dynabook T350/56ARK         | [802dacc8cc](https://linux-hardware.org/?probe=802dacc8cc) | Oct 27, 2023 |
| HP            | Pavilion dv7                | [15526c62b8](https://linux-hardware.org/?probe=15526c62b8) | Oct 26, 2023 |
| NEC Comput... | PC-VJ22LFWZHSRF             | [b229c83a28](https://linux-hardware.org/?probe=b229c83a28) | Oct 25, 2023 |
| Dell          | Inspiron 15 3511            | [8d2894b3d1](https://linux-hardware.org/?probe=8d2894b3d1) | Oct 24, 2023 |
| Acer          | Aspire 5740                 | [78702b9deb](https://linux-hardware.org/?probe=78702b9deb) | Oct 23, 2023 |
| Panasonic     | CFSZ5-3                     | [a70e21055d](https://linux-hardware.org/?probe=a70e21055d) | Oct 23, 2023 |
| Dell          | G15 5515                    | [16754901cb](https://linux-hardware.org/?probe=16754901cb) | Oct 23, 2023 |
| NEC Comput... | PC-VK26TLNZ39ZJ             | [86f3d9bdbe](https://linux-hardware.org/?probe=86f3d9bdbe) | Oct 19, 2023 |
| GMKtec        | NucBox5                     | [4b4319490d](https://linux-hardware.org/?probe=4b4319490d) | Oct 17, 2023 |
| MouseCompu... | GTN83G15H19C                | [39e86c5be4](https://linux-hardware.org/?probe=39e86c5be4) | Oct 17, 2023 |
| NEC Comput... | PC-VK27MDZDN                | [052e2dbcc2](https://linux-hardware.org/?probe=052e2dbcc2) | Oct 16, 2023 |
| GLM           | 14-Z8350-C                  | [2db6571799](https://linux-hardware.org/?probe=2db6571799) | Oct 15, 2023 |
| Dynabook      | B65/ER                      | [2bda5e79a4](https://linux-hardware.org/?probe=2bda5e79a4) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | [4bc1c4e1b6](https://linux-hardware.org/?probe=4bc1c4e1b6) | Oct 14, 2023 |
| Fujitsu       | FMVNS7HE                    | [2408a69be7](https://linux-hardware.org/?probe=2408a69be7) | Oct 13, 2023 |
| Toshiba       | dynabook B452/22F           | [61777cd92a](https://linux-hardware.org/?probe=61777cd92a) | Oct 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d739639932](https://linux-hardware.org/?probe=d739639932) | Oct 09, 2023 |
| Dell          | System Vostro 3750          | [1cbdc082a8](https://linux-hardware.org/?probe=1cbdc082a8) | Oct 08, 2023 |
| Fujitsu       | FMVA05007                   | [265b66f904](https://linux-hardware.org/?probe=265b66f904) | Oct 05, 2023 |
| Timi          | A30                         | [36d352fb7f](https://linux-hardware.org/?probe=36d352fb7f) | Oct 04, 2023 |
| Panasonic     | CFSZ5-3                     | [9d0b849593](https://linux-hardware.org/?probe=9d0b849593) | Oct 01, 2023 |
| Panasonic     | CFSZ5-3                     | [f2c369cb00](https://linux-hardware.org/?probe=f2c369cb00) | Oct 01, 2023 |
| Dell          | Latitude 7390               | [93e22b6fc4](https://linux-hardware.org/?probe=93e22b6fc4) | Sep 27, 2023 |
| Dell          | Latitude 7390               | [a7bfa2e285](https://linux-hardware.org/?probe=a7bfa2e285) | Sep 27, 2023 |
| Fujitsu       | FMVA42CW                    | [48a8e36d5f](https://linux-hardware.org/?probe=48a8e36d5f) | Sep 25, 2023 |
| Fujitsu       | FMVA42CW                    | [8427efde7d](https://linux-hardware.org/?probe=8427efde7d) | Sep 25, 2023 |
| Toshiba       | dynabook Satellite B552/... | [7aea90703a](https://linux-hardware.org/?probe=7aea90703a) | Sep 24, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [be07169f5c](https://linux-hardware.org/?probe=be07169f5c) | Sep 22, 2023 |
| ASUSTek       | X551CAP                     | [b90045e0f9](https://linux-hardware.org/?probe=b90045e0f9) | Sep 22, 2023 |
| ASUSTek       | TP550LAB                    | [3e07304aa5](https://linux-hardware.org/?probe=3e07304aa5) | Sep 20, 2023 |
| Dell          | Latitude 3540               | [3f1c99de44](https://linux-hardware.org/?probe=3f1c99de44) | Sep 20, 2023 |
| Lenovo        | ThinkPad X240 20AMA1S702    | [5be3b8fc11](https://linux-hardware.org/?probe=5be3b8fc11) | Sep 19, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c26fb8a8da](https://linux-hardware.org/?probe=c26fb8a8da) | Sep 18, 2023 |
| Acer          | Aspire E5-575G              | [0f0607d7e4](https://linux-hardware.org/?probe=0f0607d7e4) | Sep 18, 2023 |
| Apple         | MacBookAir4,2               | [1e61961aef](https://linux-hardware.org/?probe=1e61961aef) | Sep 17, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [1a5acc2c10](https://linux-hardware.org/?probe=1a5acc2c10) | Sep 17, 2023 |
| NEC Comput... | PC-VK15EBZDG                | [83d74c1e9d](https://linux-hardware.org/?probe=83d74c1e9d) | Sep 17, 2023 |
| HP            | Pavilion dv2                | [ee227b3d35](https://linux-hardware.org/?probe=ee227b3d35) | Sep 16, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [8c529cfaa8](https://linux-hardware.org/?probe=8c529cfaa8) | Sep 11, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [586c1fab43](https://linux-hardware.org/?probe=586c1fab43) | Sep 06, 2023 |
| ASUSTek       | K53TA                       | [b173b156f9](https://linux-hardware.org/?probe=b173b156f9) | Sep 04, 2023 |
| Dynabook      | G83/HS                      | [9db149b715](https://linux-hardware.org/?probe=9db149b715) | Sep 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1211fca3e2](https://linux-hardware.org/?probe=1211fca3e2) | Sep 03, 2023 |
| Toshiba       | dynabook R73/J              | [c63c97e4a8](https://linux-hardware.org/?probe=c63c97e4a8) | Sep 03, 2023 |
| Dell          | Inspiron 3585               | [a8bdd5bcca](https://linux-hardware.org/?probe=a8bdd5bcca) | Sep 02, 2023 |
| Lenovo        | G570 4334                   | [60c351e038](https://linux-hardware.org/?probe=60c351e038) | Sep 01, 2023 |
| Lenovo        | ThinkPad X61 76753BJ        | [f90ed18892](https://linux-hardware.org/?probe=f90ed18892) | Sep 01, 2023 |
| Lenovo        | G550 2958                   | [033a5ccf76](https://linux-hardware.org/?probe=033a5ccf76) | Sep 01, 2023 |
| System76      | Lemur Pro                   | [c04af9751f](https://linux-hardware.org/?probe=c04af9751f) | Aug 31, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [fab320d1d5](https://linux-hardware.org/?probe=fab320d1d5) | Aug 31, 2023 |
| Intel Clie... | LAPAC71H                    | [67d6ffca34](https://linux-hardware.org/?probe=67d6ffca34) | Aug 30, 2023 |
| Intel Clie... | LAPAC71H                    | [e5a008be38](https://linux-hardware.org/?probe=e5a008be38) | Aug 30, 2023 |
| Apple         | MacBookPro15,2              | [3bee4c1b45](https://linux-hardware.org/?probe=3bee4c1b45) | Aug 30, 2023 |
| Apple         | MacBookPro11,5              | [643e8194ea](https://linux-hardware.org/?probe=643e8194ea) | Aug 30, 2023 |
| Dell          | Inspiron 3580               | [0cda85fdd1](https://linux-hardware.org/?probe=0cda85fdd1) | Aug 28, 2023 |
| Timi          | A35                         | [50e380e876](https://linux-hardware.org/?probe=50e380e876) | Aug 24, 2023 |
| HP            | ProBook 430 G7              | [b8a468626b](https://linux-hardware.org/?probe=b8a468626b) | Aug 24, 2023 |
| Dell          | Inspiron 5559               | [310e1f561c](https://linux-hardware.org/?probe=310e1f561c) | Aug 22, 2023 |
| Toshiba       | dynabook B350/22A           | [80ad4cd1ff](https://linux-hardware.org/?probe=80ad4cd1ff) | Aug 21, 2023 |
| Alienware     | 17                          | [9e7015d530](https://linux-hardware.org/?probe=9e7015d530) | Aug 20, 2023 |
| HP            | EliteBook 865 16 inch G9... | [5ed6b3612a](https://linux-hardware.org/?probe=5ed6b3612a) | Aug 17, 2023 |
| MSI           | Stealth 14Studio A13VG      | [a8035775f2](https://linux-hardware.org/?probe=a8035775f2) | Aug 14, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [9a680df78d](https://linux-hardware.org/?probe=9a680df78d) | Aug 14, 2023 |
| Fujitsu       | FMVA42CW                    | [453329dbff](https://linux-hardware.org/?probe=453329dbff) | Aug 12, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [8abafe1b65](https://linux-hardware.org/?probe=8abafe1b65) | Aug 12, 2023 |
| Gateway       | MD7309U                     | [18dbacfdab](https://linux-hardware.org/?probe=18dbacfdab) | Aug 10, 2023 |
| Fujitsu       | FMVA42CW                    | [ffb5c4343b](https://linux-hardware.org/?probe=ffb5c4343b) | Aug 10, 2023 |
| NEC Comput... | PC-GN246W3A5                | [2f37664ebd](https://linux-hardware.org/?probe=2f37664ebd) | Aug 10, 2023 |
| Sony          | VJF151                      | [b2768a0abf](https://linux-hardware.org/?probe=b2768a0abf) | Aug 09, 2023 |
| Fujitsu       | FMVA42CW                    | [83d5950b7a](https://linux-hardware.org/?probe=83d5950b7a) | Aug 08, 2023 |
| Lenovo        | ThinkPad X230 2324BV7       | [e1f092d38b](https://linux-hardware.org/?probe=e1f092d38b) | Aug 08, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [4bd753037a](https://linux-hardware.org/?probe=4bd753037a) | Aug 06, 2023 |
| Dell          | Latitude 5290 2-in-1        | [b4cc5c436c](https://linux-hardware.org/?probe=b4cc5c436c) | Aug 06, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [4d0d3b78e7](https://linux-hardware.org/?probe=4d0d3b78e7) | Aug 02, 2023 |
| Apple         | MacBookAir9,1               | [2e59618067](https://linux-hardware.org/?probe=2e59618067) | Aug 01, 2023 |
| NEC Comput... | PC-VY22GXZCA                | [180d6cf97d](https://linux-hardware.org/?probe=180d6cf97d) | Jul 31, 2023 |
| Dell          | XPS 15 9500                 | [151b7d8d31](https://linux-hardware.org/?probe=151b7d8d31) | Jul 29, 2023 |
| Dell          | Inspiron 15-3565            | [3d41743a5d](https://linux-hardware.org/?probe=3d41743a5d) | Jul 23, 2023 |
| Lenovo        | ThinkPad X13 Gen 4 21EXC... | [5777fd52c6](https://linux-hardware.org/?probe=5777fd52c6) | Jul 22, 2023 |
| Sony          | VPCEB48FJ                   | [95cab43ae1](https://linux-hardware.org/?probe=95cab43ae1) | Jul 21, 2023 |
| Panasonic     | CFSZ5-3                     | [9eb560d292](https://linux-hardware.org/?probe=9eb560d292) | Jul 20, 2023 |
| HP            | Laptop 14s-dk0xxx           | [3cf00d1f89](https://linux-hardware.org/?probe=3cf00d1f89) | Jul 16, 2023 |
| Dell          | Inspiron 3580               | [e46543841d](https://linux-hardware.org/?probe=e46543841d) | Jul 16, 2023 |
| Lenovo        | G50-70 20351                | [46a3598028](https://linux-hardware.org/?probe=46a3598028) | Jul 16, 2023 |
| Apple         | MacBookPro15,1              | [cf0f0d0820](https://linux-hardware.org/?probe=cf0f0d0820) | Jul 15, 2023 |
| Lenovo        | ThinkPad Edge E535 3260C... | [9ff1a61e2a](https://linux-hardware.org/?probe=9ff1a61e2a) | Jul 14, 2023 |
| MSI           | GF63 Thin 9SCSR             | [835e924f6d](https://linux-hardware.org/?probe=835e924f6d) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | [7bf81133fc](https://linux-hardware.org/?probe=7bf81133fc) | Jul 12, 2023 |
| Apple         | MacBookAir9,1               | [c952cab7d7](https://linux-hardware.org/?probe=c952cab7d7) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| Apple         | MacBookAir9,1               | [703f4fd012](https://linux-hardware.org/?probe=703f4fd012) | Jul 10, 2023 |
| Lenovo        | G50-70 20351                | [2349cf550c](https://linux-hardware.org/?probe=2349cf550c) | Jul 08, 2023 |
| Lenovo        | G50-70 20351                | [a5267b5818](https://linux-hardware.org/?probe=a5267b5818) | Jul 08, 2023 |
| Toshiba       | dynabook R73/Y              | [37e3897f65](https://linux-hardware.org/?probe=37e3897f65) | Jul 08, 2023 |
| Toshiba       | dynabook Satellite B552/... | [f459621198](https://linux-hardware.org/?probe=f459621198) | Jul 06, 2023 |
| Dell          | Inspiron 15-3565            | [69d01e9a98](https://linux-hardware.org/?probe=69d01e9a98) | Jul 05, 2023 |
| Gigabyte      | AERO 16 OLED BSF            | [1148bd3952](https://linux-hardware.org/?probe=1148bd3952) | Jul 04, 2023 |
| Lenovo        | ThinkPad L520 5015A12       | [0cb85712d9](https://linux-hardware.org/?probe=0cb85712d9) | Jul 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [b025249305](https://linux-hardware.org/?probe=b025249305) | Jul 03, 2023 |
| Dynabook      | B65/ER                      | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a77c825995](https://linux-hardware.org/?probe=a77c825995) | Jun 29, 2023 |
| Lenovo        | ThinkPad L520 50153CJ       | [1793064ee5](https://linux-hardware.org/?probe=1793064ee5) | Jun 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7497c404d4](https://linux-hardware.org/?probe=7497c404d4) | Jun 27, 2023 |
| Sony          | VGN-AR74DB                  | [c51cc05c0a](https://linux-hardware.org/?probe=c51cc05c0a) | Jun 25, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [fa79d9b26d](https://linux-hardware.org/?probe=fa79d9b26d) | Jun 17, 2023 |
| Fujitsu       | FMVA42CW                    | [673cf6831d](https://linux-hardware.org/?probe=673cf6831d) | Jun 16, 2023 |
| Acer          | Aspire V3-571               | [75c2da2c37](https://linux-hardware.org/?probe=75c2da2c37) | Jun 15, 2023 |
| Dell          | Inspiron 15-3565            | [32069bc39d](https://linux-hardware.org/?probe=32069bc39d) | Jun 13, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7a081b66af](https://linux-hardware.org/?probe=7a081b66af) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Toshiba       | dynabook Satellite B552/... | [46c70e6e33](https://linux-hardware.org/?probe=46c70e6e33) | Jun 10, 2023 |
| Apple         | MacBookAir9,1               | [de1d4d9d23](https://linux-hardware.org/?probe=de1d4d9d23) | Jun 05, 2023 |
| Valve         | Jupiter                     | [3aa6cf6780](https://linux-hardware.org/?probe=3aa6cf6780) | Jun 03, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [2bcfc48199](https://linux-hardware.org/?probe=2bcfc48199) | Jun 02, 2023 |
| Apple         | MacBookAir9,1               | [b3e3a95a06](https://linux-hardware.org/?probe=b3e3a95a06) | Jun 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8002face48](https://linux-hardware.org/?probe=8002face48) | May 30, 2023 |
| Apple         | MacBookAir8,1               | [47b2ee3c0d](https://linux-hardware.org/?probe=47b2ee3c0d) | May 28, 2023 |
| Samsung       | 270E5G/270E5U               | [affdf49716](https://linux-hardware.org/?probe=affdf49716) | May 27, 2023 |
| Samsung       | 270E5G/270E5U               | [106bd355da](https://linux-hardware.org/?probe=106bd355da) | May 27, 2023 |
| Fujitsu       | FMVA42ERKS                  | [91fa73184c](https://linux-hardware.org/?probe=91fa73184c) | May 26, 2023 |
| Intel Clie... | LAPBC510                    | [fe45f8ba3c](https://linux-hardware.org/?probe=fe45f8ba3c) | May 26, 2023 |
| HUAWEI        | BOHB-WAX9                   | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| Lenovo        | YangTian V340-15-IML 81V... | [cedb6136dc](https://linux-hardware.org/?probe=cedb6136dc) | May 12, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d567c1f954](https://linux-hardware.org/?probe=d567c1f954) | May 10, 2023 |
| Fujitsu       | FMVA0500TP                  | [61061bd78d](https://linux-hardware.org/?probe=61061bd78d) | May 09, 2023 |
| Apple         | MacBookPro11,4              | [83f86e5727](https://linux-hardware.org/?probe=83f86e5727) | May 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [cbafd29abc](https://linux-hardware.org/?probe=cbafd29abc) | May 08, 2023 |
| Apple         | MacBookAir9,1               | [a0073c6ff3](https://linux-hardware.org/?probe=a0073c6ff3) | May 08, 2023 |
| ASUSTek       | X202E                       | [6039408aaf](https://linux-hardware.org/?probe=6039408aaf) | May 08, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [4229be0afa](https://linux-hardware.org/?probe=4229be0afa) | May 07, 2023 |
| Fujitsu       | FMVA42CW                    | [893d6b37e8](https://linux-hardware.org/?probe=893d6b37e8) | May 05, 2023 |
| Fujitsu       | FMVA705ABS                  | [99cb877cba](https://linux-hardware.org/?probe=99cb877cba) | May 04, 2023 |
| Toshiba       | dynabook SS M42 210E/3W     | [ad7f7da4e4](https://linux-hardware.org/?probe=ad7f7da4e4) | May 04, 2023 |
| Lenovo        | 4068AGJ                     | [6a2c3207b5](https://linux-hardware.org/?probe=6a2c3207b5) | May 01, 2023 |
| NEC Comput... | PC-LE150C2                  | [a8e48f9686](https://linux-hardware.org/?probe=a8e48f9686) | Apr 27, 2023 |
| Lenovo        | ThinkPad L512 4444PS9       | [78cf80b13b](https://linux-hardware.org/?probe=78cf80b13b) | Apr 26, 2023 |
| Fujitsu       | FMVA05004                   | [c494a8453d](https://linux-hardware.org/?probe=c494a8453d) | Apr 26, 2023 |
| Toshiba       | dynabook TV/68KBL           | [19c59e3701](https://linux-hardware.org/?probe=19c59e3701) | Apr 26, 2023 |
| Lenovo        | ThinkPad SL500 2746CTO      | [7283a0f4d9](https://linux-hardware.org/?probe=7283a0f4d9) | Apr 25, 2023 |
| Dell          | XPS 15 9500                 | [861431db35](https://linux-hardware.org/?probe=861431db35) | Apr 25, 2023 |
| Toshiba       | dynabook BX/67TG            | [5349d462cd](https://linux-hardware.org/?probe=5349d462cd) | Apr 23, 2023 |
| Fujitsu       | FMVA42CW                    | [4fb1ab7ab8](https://linux-hardware.org/?probe=4fb1ab7ab8) | Apr 22, 2023 |
| HP            | Pavilion dv6                | [b3613186fa](https://linux-hardware.org/?probe=b3613186fa) | Apr 21, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [da51714544](https://linux-hardware.org/?probe=da51714544) | Apr 21, 2023 |
| Toshiba       | dynabook T451/46EW          | [e45702b9aa](https://linux-hardware.org/?probe=e45702b9aa) | Apr 20, 2023 |
| Apple         | MacBookPro8,1               | [4e95dc284c](https://linux-hardware.org/?probe=4e95dc284c) | Apr 19, 2023 |
| Fujitsu       | FMVNA6HE                    | [609572e6f7](https://linux-hardware.org/?probe=609572e6f7) | Apr 18, 2023 |
| LG Electro... | P530-KE6BK                  | [b1f0863c79](https://linux-hardware.org/?probe=b1f0863c79) | Apr 17, 2023 |
| HP            | Laptop 15s-eq3xxx           | [3455570853](https://linux-hardware.org/?probe=3455570853) | Apr 16, 2023 |
| MSI           | Stealth 14Studio A13VF      | [b6cd64a19b](https://linux-hardware.org/?probe=b6cd64a19b) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [63035ef97f](https://linux-hardware.org/?probe=63035ef97f) | Apr 12, 2023 |
| Dell          | G7 7700                     | [9552c2ecc0](https://linux-hardware.org/?probe=9552c2ecc0) | Apr 09, 2023 |
| Toshiba       | dynabook R732/H             | [ff99abe105](https://linux-hardware.org/?probe=ff99abe105) | Apr 08, 2023 |
| Lenovo        | 3000 N200 0769DQJ           | [db1539e64a](https://linux-hardware.org/?probe=db1539e64a) | Apr 06, 2023 |
| MSI           | Delta 15 A5EFK              | [d3066bb3d4](https://linux-hardware.org/?probe=d3066bb3d4) | Apr 06, 2023 |
| Fujitsu       | FMVA45MRP2                  | [80b1f5983b](https://linux-hardware.org/?probe=80b1f5983b) | Apr 05, 2023 |
| Lenovo        | G500 20236                  | [4bbe18183a](https://linux-hardware.org/?probe=4bbe18183a) | Apr 04, 2023 |
| Toshiba       | dynabook T653/46JR          | [7f0e2d07b5](https://linux-hardware.org/?probe=7f0e2d07b5) | Apr 01, 2023 |
| Dell          | Vostro 15 3515              | [eea311b1bb](https://linux-hardware.org/?probe=eea311b1bb) | Apr 01, 2023 |
| Acer          | Aspire 1410                 | [58be80ea51](https://linux-hardware.org/?probe=58be80ea51) | Mar 31, 2023 |
| Toshiba       | dynabook T653/46JR          | [94a37d865e](https://linux-hardware.org/?probe=94a37d865e) | Mar 30, 2023 |
| MSI           | GT70 2PE                    | [be727f6f39](https://linux-hardware.org/?probe=be727f6f39) | Mar 27, 2023 |
| Apple         | MacBookPro16,2              | [cf7ab8adb4](https://linux-hardware.org/?probe=cf7ab8adb4) | Mar 26, 2023 |
| Lenovo        | ThinkPad X230 2306A44       | [e948a25ef6](https://linux-hardware.org/?probe=e948a25ef6) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | [f8fc6c74da](https://linux-hardware.org/?probe=f8fc6c74da) | Mar 25, 2023 |
| MSI           | Alpha 15 B5EEK              | [03f3f846eb](https://linux-hardware.org/?probe=03f3f846eb) | Mar 24, 2023 |
| Dell          | Inspiron 3442               | [33137a049e](https://linux-hardware.org/?probe=33137a049e) | Mar 20, 2023 |
| HUAWEI        | FRD-WX9                     | [b5a517c552](https://linux-hardware.org/?probe=b5a517c552) | Mar 20, 2023 |
| ASUSTek       | X55U                        | [b06bd51348](https://linux-hardware.org/?probe=b06bd51348) | Mar 11, 2023 |
| Google        | Bobba                       | [01d8f57c7e](https://linux-hardware.org/?probe=01d8f57c7e) | Mar 08, 2023 |
| Dell          | Inspiron 14 5420            | [cb6ec54195](https://linux-hardware.org/?probe=cb6ec54195) | Mar 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ca566e314e](https://linux-hardware.org/?probe=ca566e314e) | Mar 05, 2023 |
| Dell          | XPS 15 9500                 | [47df9846bb](https://linux-hardware.org/?probe=47df9846bb) | Mar 04, 2023 |
| Dell          | Latitude 5300               | [a77b29e10d](https://linux-hardware.org/?probe=a77b29e10d) | Mar 04, 2023 |
| Toshiba       | dynabook R73/BN             | [1d81bb5f08](https://linux-hardware.org/?probe=1d81bb5f08) | Mar 03, 2023 |
| HP            | EliteBook 2740p             | [dee37a9bd9](https://linux-hardware.org/?probe=dee37a9bd9) | Mar 01, 2023 |
| Acer          | Aspire 5740                 | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| Lenovo        | G500 20236                  | [93f09b28d6](https://linux-hardware.org/?probe=93f09b28d6) | Feb 26, 2023 |
| Lenovo        | G500 20236                  | [51bd5c9f21](https://linux-hardware.org/?probe=51bd5c9f21) | Feb 26, 2023 |
| Toshiba       | dynabook T653/46JR          | [ac156d2c80](https://linux-hardware.org/?probe=ac156d2c80) | Feb 22, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [5d62c279d2](https://linux-hardware.org/?probe=5d62c279d2) | Feb 21, 2023 |
| HUAWEI        | KPR-WX9                     | [1f44fd5a86](https://linux-hardware.org/?probe=1f44fd5a86) | Feb 18, 2023 |
| Dell          | Latitude 5300               | [371d693177](https://linux-hardware.org/?probe=371d693177) | Feb 17, 2023 |
| Dell          | Latitude 5300               | [323f21bb1e](https://linux-hardware.org/?probe=323f21bb1e) | Feb 17, 2023 |
| Dell          | Latitude 5300               | [ca02606bea](https://linux-hardware.org/?probe=ca02606bea) | Feb 17, 2023 |
| Toshiba       | dynabook R73/BN             | [df7e69c5c4](https://linux-hardware.org/?probe=df7e69c5c4) | Feb 16, 2023 |
| EPSON DIRE... | Endeavor NY2200S            | [2be0a1a8a0](https://linux-hardware.org/?probe=2be0a1a8a0) | Feb 14, 2023 |
| EPSON DIRE... | Endeavor NY2200S            | [29b669f143](https://linux-hardware.org/?probe=29b669f143) | Feb 14, 2023 |
| Dell          | Inspiron 14 5420            | [7fc3c03910](https://linux-hardware.org/?probe=7fc3c03910) | Feb 13, 2023 |
| Compaq        | 420                         | [2028e7c97c](https://linux-hardware.org/?probe=2028e7c97c) | Feb 12, 2023 |
| Lenovo        | ThinkPad L512 4444PV3       | [8965eee02f](https://linux-hardware.org/?probe=8965eee02f) | Feb 09, 2023 |
| Lenovo        | ThinkPad T440p 20AWA1MDJ... | [cc5f5375d2](https://linux-hardware.org/?probe=cc5f5375d2) | Feb 09, 2023 |
| Toshiba       | dynabook T653/46JR          | [2422c70d2e](https://linux-hardware.org/?probe=2422c70d2e) | Feb 09, 2023 |
| HP            | Notebook                    | [7d4a89adea](https://linux-hardware.org/?probe=7d4a89adea) | Feb 08, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c5bdedaf17](https://linux-hardware.org/?probe=c5bdedaf17) | Feb 04, 2023 |
| Toshiba       | dynabook T653/46JR          | [6c1119bb00](https://linux-hardware.org/?probe=6c1119bb00) | Feb 04, 2023 |
| Unknown       | Unknown                     | [5505a27d5e](https://linux-hardware.org/?probe=5505a27d5e) | Feb 03, 2023 |
| Dell          | Inspiron 14 5420            | [deec906907](https://linux-hardware.org/?probe=deec906907) | Feb 02, 2023 |
| Fujitsu       | LIFEBOOK E744               | [b048f7d3e1](https://linux-hardware.org/?probe=b048f7d3e1) | Feb 01, 2023 |
| Unknown       | Unknown                     | [d780984cf9](https://linux-hardware.org/?probe=d780984cf9) | Jan 30, 2023 |
| Valve         | Jupiter                     | [935a50bce1](https://linux-hardware.org/?probe=935a50bce1) | Jan 30, 2023 |
| Google        | Helios                      | [c8b5d0660b](https://linux-hardware.org/?probe=c8b5d0660b) | Jan 28, 2023 |
| HUAWEI        | KLVL-WXXW                   | [f20e47b9d7](https://linux-hardware.org/?probe=f20e47b9d7) | Jan 28, 2023 |
| NEC Comput... | PC-NS350AAR-KS              | [c4aa0da6f4](https://linux-hardware.org/?probe=c4aa0da6f4) | Jan 27, 2023 |
| HP            | ProBook 440 G5              | [af59cf3cd3](https://linux-hardware.org/?probe=af59cf3cd3) | Jan 26, 2023 |
| Toshiba       | dynabook T653/46JR          | [00cabfbb97](https://linux-hardware.org/?probe=00cabfbb97) | Jan 24, 2023 |
| Purism        | Librem 15 v3                | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [d999192dbf](https://linux-hardware.org/?probe=d999192dbf) | Jan 22, 2023 |
| Toshiba       | dynabook T653/46JR          | [1acfabc208](https://linux-hardware.org/?probe=1acfabc208) | Jan 22, 2023 |
| Dell          | Inspiron 3585               | [9790dcdef4](https://linux-hardware.org/?probe=9790dcdef4) | Jan 19, 2023 |
| Lenovo        | G550 2958                   | [7b255b7fe7](https://linux-hardware.org/?probe=7b255b7fe7) | Jan 18, 2023 |
| Dell          | XPS 9320                    | [bd7346b7c2](https://linux-hardware.org/?probe=bd7346b7c2) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Latitude 3540               | [01688be251](https://linux-hardware.org/?probe=01688be251) | Jan 15, 2023 |
| Acer          | Aspire 5349                 | [c52d3b2b2f](https://linux-hardware.org/?probe=c52d3b2b2f) | Jan 15, 2023 |
| Fujitsu       | FMVNF70YX                   | [2817102c87](https://linux-hardware.org/?probe=2817102c87) | Jan 14, 2023 |
| HONOR         | HLYL-WXX9                   | [e5b02d94cd](https://linux-hardware.org/?probe=e5b02d94cd) | Jan 14, 2023 |
| Panasonic     | CF-SX2JDHYS                 | [fa1ebc0951](https://linux-hardware.org/?probe=fa1ebc0951) | Jan 14, 2023 |
| Apple         | MacBookPro9,2               | [4d89e9dec4](https://linux-hardware.org/?probe=4d89e9dec4) | Jan 14, 2023 |
| Panasonic     | CFSZ6-2                     | [7a9f534294](https://linux-hardware.org/?probe=7a9f534294) | Jan 13, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [05744a666a](https://linux-hardware.org/?probe=05744a666a) | Jan 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | [b2965791cb](https://linux-hardware.org/?probe=b2965791cb) | Jan 13, 2023 |
| Lenovo        | ThinkPad X13 Gen 2i 20WL... | [093e5ffc06](https://linux-hardware.org/?probe=093e5ffc06) | Jan 13, 2023 |
| ASUSTek       | E200HA                      | [4d9f4512a6](https://linux-hardware.org/?probe=4d9f4512a6) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| Dell          | Inspiron 1545               | [20bc38b554](https://linux-hardware.org/?probe=20bc38b554) | Jan 11, 2023 |
| HP            | Pavilion dv6                | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| Dell          | Inspiron 14 5420            | [9aaef76c2c](https://linux-hardware.org/?probe=9aaef76c2c) | Jan 09, 2023 |
| Lenovo        | IdeaPadFlex 10 20324        | [1d0cd9b040](https://linux-hardware.org/?probe=1d0cd9b040) | Jan 09, 2023 |
| HP            | ZHAN 66 Pro G1              | [76e588ab0a](https://linux-hardware.org/?probe=76e588ab0a) | Jan 08, 2023 |
| Valve         | Jupiter                     | [73e8740cb9](https://linux-hardware.org/?probe=73e8740cb9) | Jan 08, 2023 |
| Toshiba       | dynabook T653/46JR          | [8fe8187a9e](https://linux-hardware.org/?probe=8fe8187a9e) | Jan 08, 2023 |
| Valve         | Jupiter                     | [75cabfba4d](https://linux-hardware.org/?probe=75cabfba4d) | Jan 03, 2023 |
| Valve         | Jupiter                     | [70b2e771b7](https://linux-hardware.org/?probe=70b2e771b7) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| ASUSTek       | ZenBook UX333FN_U3300FN     | [750a40a3cc](https://linux-hardware.org/?probe=750a40a3cc) | Jan 02, 2023 |
| Toshiba       | dynabook T653/46JR          | [cac689a705](https://linux-hardware.org/?probe=cac689a705) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| Dell          | XPS 9320                    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| Unknown       | Unknown                     | [86dcc5a2ff](https://linux-hardware.org/?probe=86dcc5a2ff) | Dec 30, 2022 |
| Toshiba       | dynabook T653/46JR          | [a1f59f6ff9](https://linux-hardware.org/?probe=a1f59f6ff9) | Dec 29, 2022 |
| Apple         | MacBookPro15,2              | [e5a7b5b5be](https://linux-hardware.org/?probe=e5a7b5b5be) | Dec 28, 2022 |
| Lenovo        | ThinkPad T480 20L50000UK    | [f19e16b1ac](https://linux-hardware.org/?probe=f19e16b1ac) | Dec 28, 2022 |
| Dell          | Inspiron 5370               | [e08cfee8e8](https://linux-hardware.org/?probe=e08cfee8e8) | Dec 27, 2022 |
| Dell          | Inspiron 5370               | [071ff79fc2](https://linux-hardware.org/?probe=071ff79fc2) | Dec 27, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [0069729ebe](https://linux-hardware.org/?probe=0069729ebe) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [985e965dec](https://linux-hardware.org/?probe=985e965dec) | Dec 25, 2022 |
| Apple         | MacBookPro9,2               | [ef194165fc](https://linux-hardware.org/?probe=ef194165fc) | Dec 24, 2022 |
| Toshiba       | dynabook T653/46JR          | [1f10cd2a64](https://linux-hardware.org/?probe=1f10cd2a64) | Dec 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [4a1e660e7d](https://linux-hardware.org/?probe=4a1e660e7d) | Dec 21, 2022 |
| Sony          | VJZ13A                      | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Toshiba       | dynabook T653/46JR          | [5a05dc8c43](https://linux-hardware.org/?probe=5a05dc8c43) | Dec 17, 2022 |
| Fujitsu       | FMVNS6C3                    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Fujitsu       | FMVNS6C3                    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| Unknown       | Unknown                     | [2a7d6d1541](https://linux-hardware.org/?probe=2a7d6d1541) | Dec 08, 2022 |
| Fujitsu       | FMVNS6C3                    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| HP            | Laptop 15-bs0xx             | [81576caeb1](https://linux-hardware.org/?probe=81576caeb1) | Dec 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [601575b385](https://linux-hardware.org/?probe=601575b385) | Dec 03, 2022 |
| Lenovo        | ThinkPad R500 2716AZJ       | [ecf18761e4](https://linux-hardware.org/?probe=ecf18761e4) | Nov 22, 2022 |
| HP            | Laptop 17-by0xxx            | [4d903aa73b](https://linux-hardware.org/?probe=4d903aa73b) | Nov 21, 2022 |
| Fujitsu       | FMVNQL7PM                   | [28ee68da79](https://linux-hardware.org/?probe=28ee68da79) | Nov 19, 2022 |
| NEC Comput... | PC-VK27MCZDM                | [fce4afe996](https://linux-hardware.org/?probe=fce4afe996) | Nov 19, 2022 |
| KOUZIRO       | KOUZIRONB                   | [5802e3e5d6](https://linux-hardware.org/?probe=5802e3e5d6) | Nov 17, 2022 |
| NEC Comput... | NEC VERSA M160              | [a49b4b95b9](https://linux-hardware.org/?probe=a49b4b95b9) | Nov 17, 2022 |
| Toshiba       | dynabook T653/46JR          | [09569f3154](https://linux-hardware.org/?probe=09569f3154) | Nov 17, 2022 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [69f54ed610](https://linux-hardware.org/?probe=69f54ed610) | Nov 16, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | [96db8793b2](https://linux-hardware.org/?probe=96db8793b2) | Nov 15, 2022 |
| Lenovo        | ThinkPad P52 20MAS70500     | [c576805c81](https://linux-hardware.org/?probe=c576805c81) | Nov 15, 2022 |
| HP            | Laptop 17-by0xxx            | [ecdad4661a](https://linux-hardware.org/?probe=ecdad4661a) | Nov 15, 2022 |
| Toshiba       | dynabook T653/46JR          | [69d4f912f9](https://linux-hardware.org/?probe=69d4f912f9) | Nov 15, 2022 |
| KOUZIRO       | KOUZIRONB                   | [16bf4c059c](https://linux-hardware.org/?probe=16bf4c059c) | Nov 11, 2022 |
| Toshiba       | dynabook T653/46JR          | [dfa4a8aa7f](https://linux-hardware.org/?probe=dfa4a8aa7f) | Nov 10, 2022 |
| Fujitsu       | FMVXN4MN2Z                  | [7a08a94b1e](https://linux-hardware.org/?probe=7a08a94b1e) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [972094820e](https://linux-hardware.org/?probe=972094820e) | Nov 07, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [d87e75abbf](https://linux-hardware.org/?probe=d87e75abbf) | Nov 04, 2022 |
| Dell          | Vostro 2520                 | [16239dbee4](https://linux-hardware.org/?probe=16239dbee4) | Oct 17, 2022 |
| Lenovo        | ThinkPad L560 20F1000TJP    | [e9b7a4ffc2](https://linux-hardware.org/?probe=e9b7a4ffc2) | Oct 15, 2022 |
| Lenovo        | G50-70 20351                | [9a17926acb](https://linux-hardware.org/?probe=9a17926acb) | Oct 15, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| Lenovo        | ThinkPad X220 42873LJ       | [b96b26c09b](https://linux-hardware.org/?probe=b96b26c09b) | Oct 11, 2022 |
| Toshiba       | dynabook T653/46JR          | [d5f7a80d34](https://linux-hardware.org/?probe=d5f7a80d34) | Oct 06, 2022 |
| GPU Compan... | GWTC116-2                   | [68a9782e38](https://linux-hardware.org/?probe=68a9782e38) | Oct 06, 2022 |
| GPU Compan... | GWTC116-2                   | [53516b2a9d](https://linux-hardware.org/?probe=53516b2a9d) | Oct 06, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [be11beaedd](https://linux-hardware.org/?probe=be11beaedd) | Oct 02, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Dell          | Inspiron 11-3162            | [8cd15b2f0c](https://linux-hardware.org/?probe=8cd15b2f0c) | Sep 30, 2022 |
| NEC Comput... | PC-VRL21FB6S3R7             | [2001e2e28e](https://linux-hardware.org/?probe=2001e2e28e) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [d1b6a74f84](https://linux-hardware.org/?probe=d1b6a74f84) | Sep 29, 2022 |
| Toshiba       | dynabook T653/46JR          | [9a613eaf66](https://linux-hardware.org/?probe=9a613eaf66) | Sep 28, 2022 |
| Fujitsu       | FMVA1200G                   | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Toshiba       | dynabook T653/46JR          | [ee93820bdf](https://linux-hardware.org/?probe=ee93820bdf) | Sep 21, 2022 |
| NEC Comput... | PC-VK26MXZCE                | [db8f5e4181](https://linux-hardware.org/?probe=db8f5e4181) | Sep 18, 2022 |
| Toshiba       | dynabook T653/46JR          | [7f9cf09305](https://linux-hardware.org/?probe=7f9cf09305) | Sep 17, 2022 |
| EPSON DIRE... | Endeavor NJ3100E            | [47cb342ecf](https://linux-hardware.org/?probe=47cb342ecf) | Sep 16, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [9497f1e17f](https://linux-hardware.org/?probe=9497f1e17f) | Sep 16, 2022 |
| System76      | Lemur Pro                   | [d6682a260a](https://linux-hardware.org/?probe=d6682a260a) | Sep 14, 2022 |
| Dell          | Latitude 7420               | [211c7ab44c](https://linux-hardware.org/?probe=211c7ab44c) | Sep 12, 2022 |
| HUAWEI        | MACHD-WXX9                  | [ba1f911067](https://linux-hardware.org/?probe=ba1f911067) | Sep 10, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [c34e343671](https://linux-hardware.org/?probe=c34e343671) | Sep 05, 2022 |
| Panasonic     | CFSV9-1                     | [c21f59dee9](https://linux-hardware.org/?probe=c21f59dee9) | Sep 04, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [a0b2975bf7](https://linux-hardware.org/?probe=a0b2975bf7) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [adfeeb4193](https://linux-hardware.org/?probe=adfeeb4193) | Sep 04, 2022 |
| Toshiba       | dynabook T653/46JR          | [b97366daa0](https://linux-hardware.org/?probe=b97366daa0) | Aug 27, 2022 |
| MSI           | GE70 0NC/GE70 0ND           | [a7c9d17455](https://linux-hardware.org/?probe=a7c9d17455) | Aug 25, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Fujitsu       | FMVA42CW                    | [f50babde6a](https://linux-hardware.org/?probe=f50babde6a) | Aug 23, 2022 |
| Toshiba       | dynabook T653/46JR          | [decfecaa20](https://linux-hardware.org/?probe=decfecaa20) | Aug 18, 2022 |
| MSI           | Delta 15 A5EFK              | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| Toshiba       | dynabook T75/RW             | [ff35aa835d](https://linux-hardware.org/?probe=ff35aa835d) | Aug 15, 2022 |
| HP            | EliteBook 845 14 inch G9... | [4e05ac232c](https://linux-hardware.org/?probe=4e05ac232c) | Aug 15, 2022 |
| System76      | Oryx Pro                    | [87b38f5a99](https://linux-hardware.org/?probe=87b38f5a99) | Aug 12, 2022 |
| Dell          | XPS 15 9500                 | [d8486d3371](https://linux-hardware.org/?probe=d8486d3371) | Aug 07, 2022 |
| Toshiba       | dynabook R732/G             | [82ef8736b3](https://linux-hardware.org/?probe=82ef8736b3) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [7151e1746a](https://linux-hardware.org/?probe=7151e1746a) | Aug 05, 2022 |
| Toshiba       | dynabook T653/46JR          | [ea8bb6486b](https://linux-hardware.org/?probe=ea8bb6486b) | Jul 30, 2022 |
| Toshiba       | dynabook B350/22A           | [7a5344db19](https://linux-hardware.org/?probe=7a5344db19) | Jul 28, 2022 |
| Toshiba       | dynabook R734/K             | [a5e7d4c919](https://linux-hardware.org/?probe=a5e7d4c919) | Jul 26, 2022 |
| NEC Comput... | U2                          | [22314f4475](https://linux-hardware.org/?probe=22314f4475) | Jul 25, 2022 |
| Dell          | Latitude 7320               | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Apple         | MacBookAir9,1               | [cf4d815653](https://linux-hardware.org/?probe=cf4d815653) | Jul 24, 2022 |
| Alienware     | m17                         | [e14db26b9b](https://linux-hardware.org/?probe=e14db26b9b) | Jul 23, 2022 |
| NEC Comput... | PC-VJ24LLZCB                | [9b0955cfe2](https://linux-hardware.org/?probe=9b0955cfe2) | Jul 23, 2022 |
| Apple         | MacBookPro9,2               | [2ba1ac3ec9](https://linux-hardware.org/?probe=2ba1ac3ec9) | Jul 23, 2022 |
| MouseCompu... | L140MU                      | [5206d679a2](https://linux-hardware.org/?probe=5206d679a2) | Jul 22, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [8505a7d575](https://linux-hardware.org/?probe=8505a7d575) | Jul 21, 2022 |
| Panasonic     | CF-S10EYADR                 | [1990cd2a08](https://linux-hardware.org/?probe=1990cd2a08) | Jul 13, 2022 |
| Apple         | MacBookPro15,1              | [42d81e0803](https://linux-hardware.org/?probe=42d81e0803) | Jul 13, 2022 |
| Lenovo        | G575 4383                   | [8bd6296a3e](https://linux-hardware.org/?probe=8bd6296a3e) | Jul 12, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [de4d640168](https://linux-hardware.org/?probe=de4d640168) | Jul 10, 2022 |
| Apple         | MacBookPro14,1              | [aad648ac8d](https://linux-hardware.org/?probe=aad648ac8d) | Jul 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [fc3e083086](https://linux-hardware.org/?probe=fc3e083086) | Jun 26, 2022 |
| Panasonic     | CFSV9-1                     | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [fcbbdaf844](https://linux-hardware.org/?probe=fcbbdaf844) | Jun 18, 2022 |
| ASUSTek       | T100HAN                     | [20105d0e64](https://linux-hardware.org/?probe=20105d0e64) | Jun 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [cbf5603095](https://linux-hardware.org/?probe=cbf5603095) | Jun 13, 2022 |
| Dell          | XPS 15 9500                 | [197482fd83](https://linux-hardware.org/?probe=197482fd83) | Jun 13, 2022 |
| ASUSTek       | T100HAN                     | [9a5b9400a1](https://linux-hardware.org/?probe=9a5b9400a1) | Jun 12, 2022 |
| Sony          | VGN-Z71JB                   | [95a370d4e4](https://linux-hardware.org/?probe=95a370d4e4) | Jun 08, 2022 |
| Alienware     | 13 R3                       | [1431b0b659](https://linux-hardware.org/?probe=1431b0b659) | Jun 06, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| MSI           | Delta 15 A5EFK              | [1679888c2c](https://linux-hardware.org/?probe=1679888c2c) | May 29, 2022 |
| ASUSTek       | 900                         | [e50c30c38d](https://linux-hardware.org/?probe=e50c30c38d) | May 28, 2022 |
| ASUSTek       | 900                         | [dfd6af657c](https://linux-hardware.org/?probe=dfd6af657c) | May 28, 2022 |
| Gateway       | NV57H                       | [75c484ec74](https://linux-hardware.org/?probe=75c484ec74) | May 26, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| MouseCompu... | B5-R5RENASW11               | [35eae81eca](https://linux-hardware.org/?probe=35eae81eca) | May 25, 2022 |
| ASUSTek       | 900                         | [082b51aa29](https://linux-hardware.org/?probe=082b51aa29) | May 21, 2022 |
| HP            | ProBook 430 G7              | [04a6359630](https://linux-hardware.org/?probe=04a6359630) | May 21, 2022 |
| Lenovo        | G550 2958                   | [af5cc85e39](https://linux-hardware.org/?probe=af5cc85e39) | May 20, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| Dell          | XPS 15 9500                 | [671279f960](https://linux-hardware.org/?probe=671279f960) | May 18, 2022 |
| TUXEDO        | P95_HR                      | [05d8136964](https://linux-hardware.org/?probe=05d8136964) | May 15, 2022 |
| Dell          | Inspiron 11-3162            | [d1e811474c](https://linux-hardware.org/?probe=d1e811474c) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Alienware     | 17                          | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| Toshiba       | PORTEGE Z930                | [fff817aea6](https://linux-hardware.org/?probe=fff817aea6) | May 10, 2022 |
| Thirdwave     | DX-T7                       | [b90ec1bf3a](https://linux-hardware.org/?probe=b90ec1bf3a) | May 10, 2022 |
| Fujitsu       | FMVNTCAKB                   | [66083f4e27](https://linux-hardware.org/?probe=66083f4e27) | May 09, 2022 |
| HP            | EliteBook 840 G3            | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| ASUSTek       | 900                         | [a4dc643c13](https://linux-hardware.org/?probe=a4dc643c13) | May 08, 2022 |
| ASUSTek       | 900                         | [6cbd0391b3](https://linux-hardware.org/?probe=6cbd0391b3) | May 07, 2022 |
| Toshiba       | dynabook R731/37EK          | [10ed6c8741](https://linux-hardware.org/?probe=10ed6c8741) | May 06, 2022 |
| Acer          | Aspire 5740                 | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| ASUSTek       | 900                         | [70b70a4392](https://linux-hardware.org/?probe=70b70a4392) | May 03, 2022 |
| Acer          | Aspire 5740                 | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Acer          | Aspire 5740                 | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | Inspiron 15-3565            | [a26578c0fc](https://linux-hardware.org/?probe=a26578c0fc) | Apr 30, 2022 |
| Dell          | Inspiron 15-3565            | [66d159169f](https://linux-hardware.org/?probe=66d159169f) | Apr 28, 2022 |
| Purism        | Librem 15 v3                | [d2a13c9d0a](https://linux-hardware.org/?probe=d2a13c9d0a) | Apr 27, 2022 |
| MouseCompu... | NH55Dx                      | [0a397dd5e7](https://linux-hardware.org/?probe=0a397dd5e7) | Apr 25, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [9edf97b766](https://linux-hardware.org/?probe=9edf97b766) | Apr 24, 2022 |
| Panasonic     | CF-S10EYADR                 | [efd3e5ce84](https://linux-hardware.org/?probe=efd3e5ce84) | Apr 18, 2022 |
| TUXEDO        | P95_HR                      | [a3996b5033](https://linux-hardware.org/?probe=a3996b5033) | Apr 16, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c6f1d1b99b](https://linux-hardware.org/?probe=c6f1d1b99b) | Apr 16, 2022 |
| Thirdwave     | DX-T7                       | [b03707283b](https://linux-hardware.org/?probe=b03707283b) | Apr 16, 2022 |
| Dell          | Vostro 2520                 | [fd8d5ab56a](https://linux-hardware.org/?probe=fd8d5ab56a) | Apr 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [29c02b0294](https://linux-hardware.org/?probe=29c02b0294) | Apr 12, 2022 |
| Acer          | Swift SF314-54              | [c40cfcc7fe](https://linux-hardware.org/?probe=c40cfcc7fe) | Apr 12, 2022 |
| MSI           | GP76 Leopard 11UG           | [aebd373a66](https://linux-hardware.org/?probe=aebd373a66) | Apr 12, 2022 |
| ASUSTek       | 1000H                       | [725f548eab](https://linux-hardware.org/?probe=725f548eab) | Apr 09, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [5a344e20d6](https://linux-hardware.org/?probe=5a344e20d6) | Apr 06, 2022 |
| Toshiba       | dynabook R73/BN             | [af1ad57286](https://linux-hardware.org/?probe=af1ad57286) | Apr 06, 2022 |
| Lenovo        | ThinkPad X61s 7667DB2       | [34ae68d221](https://linux-hardware.org/?probe=34ae68d221) | Apr 05, 2022 |
| Lenovo        | ThinkPad X230 2306CTO       | [188a7794dd](https://linux-hardware.org/?probe=188a7794dd) | Apr 04, 2022 |
| TUXEDO        | P95_HR                      | [41cd5e79c8](https://linux-hardware.org/?probe=41cd5e79c8) | Apr 03, 2022 |
| MouseCompu... | MB-J370                     | [2c72ea9b17](https://linux-hardware.org/?probe=2c72ea9b17) | Apr 02, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [d17d5e5310](https://linux-hardware.org/?probe=d17d5e5310) | Apr 01, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | [04f5858a30](https://linux-hardware.org/?probe=04f5858a30) | Apr 01, 2022 |
| Apple         | MacBookPro15,1              | [0fe3cba205](https://linux-hardware.org/?probe=0fe3cba205) | Mar 23, 2022 |
| System76      | Lemur Pro                   | [cd847b5e6a](https://linux-hardware.org/?probe=cd847b5e6a) | Mar 23, 2022 |
| Apple         | MacBookPro5,5               | [0e17f0194f](https://linux-hardware.org/?probe=0e17f0194f) | Mar 22, 2022 |
| Fujitsu       | FMVA05003                   | [d61a791168](https://linux-hardware.org/?probe=d61a791168) | Mar 19, 2022 |
| HP            | EliteBook 830 G6            | [46f513206b](https://linux-hardware.org/?probe=46f513206b) | Mar 18, 2022 |
| Dell          | G3 3500                     | [9ca3e10f43](https://linux-hardware.org/?probe=9ca3e10f43) | Mar 14, 2022 |
| R.W.C         | RM-A107-SR                  | [ab4bef6a90](https://linux-hardware.org/?probe=ab4bef6a90) | Mar 13, 2022 |
| Dell          | Latitude E5470              | [7fcd9d2c98](https://linux-hardware.org/?probe=7fcd9d2c98) | Mar 11, 2022 |
| Acer          | Aspire 4750                 | [0659469dbe](https://linux-hardware.org/?probe=0659469dbe) | Mar 09, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [2f2d99c83f](https://linux-hardware.org/?probe=2f2d99c83f) | Mar 03, 2022 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [0d0a2bab7a](https://linux-hardware.org/?probe=0d0a2bab7a) | Mar 03, 2022 |
| HP            | Notebook                    | [c8cd62d913](https://linux-hardware.org/?probe=c8cd62d913) | Feb 28, 2022 |
| Fujitsu       | FMVA05007                   | [21c7863329](https://linux-hardware.org/?probe=21c7863329) | Feb 27, 2022 |
| Fujitsu       | FMVA33LB2                   | [2dc30249b7](https://linux-hardware.org/?probe=2dc30249b7) | Feb 26, 2022 |
| Lenovo        | ThinkPad X220 4290LG4       | [bfb13999b0](https://linux-hardware.org/?probe=bfb13999b0) | Feb 26, 2022 |
| Fujitsu       | FMVA42CW                    | [ec10edeb39](https://linux-hardware.org/?probe=ec10edeb39) | Feb 22, 2022 |
| Panasonic     | CFSV9-1                     | [fa3b39bca1](https://linux-hardware.org/?probe=fa3b39bca1) | Feb 21, 2022 |
| Dell          | Vostro 3405                 | [f869338cb0](https://linux-hardware.org/?probe=f869338cb0) | Feb 20, 2022 |
| Apple         | MacBookAir3,2               | [2e812a8de9](https://linux-hardware.org/?probe=2e812a8de9) | Feb 17, 2022 |
| Fujitsu       | FARQ02010                   | [04fbabcfd2](https://linux-hardware.org/?probe=04fbabcfd2) | Feb 15, 2022 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [681aa0b345](https://linux-hardware.org/?probe=681aa0b345) | Feb 13, 2022 |
| Lenovo        | G570 4334                   | [f5cef9fe9b](https://linux-hardware.org/?probe=f5cef9fe9b) | Feb 13, 2022 |
| ASUSTek       | U24A                        | [47e8fc096a](https://linux-hardware.org/?probe=47e8fc096a) | Feb 10, 2022 |
| Dell          | XPS L401X                   | [1db7a71e79](https://linux-hardware.org/?probe=1db7a71e79) | Feb 09, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [76a7934681](https://linux-hardware.org/?probe=76a7934681) | Feb 09, 2022 |
| Lenovo        | G505 20240                  | [ed806edbbb](https://linux-hardware.org/?probe=ed806edbbb) | Feb 09, 2022 |
| Lenovo        | ThinkPad X240 20ALCTO1WW    | [1620a85467](https://linux-hardware.org/?probe=1620a85467) | Feb 08, 2022 |
| ASUSTek       | X541SA                      | [afafec99f9](https://linux-hardware.org/?probe=afafec99f9) | Feb 08, 2022 |
| Toshiba       | dynabook Satellite B453/... | [279ff9b0f0](https://linux-hardware.org/?probe=279ff9b0f0) | Feb 08, 2022 |
| ASUSTek       | S101                        | [a850549e73](https://linux-hardware.org/?probe=a850549e73) | Feb 04, 2022 |
| ASUSTek       | U24A                        | [c49e4b9513](https://linux-hardware.org/?probe=c49e4b9513) | Jan 31, 2022 |
| AMI           | Intel                       | [33011a4745](https://linux-hardware.org/?probe=33011a4745) | Jan 31, 2022 |
| AMI           | Intel                       | [f749123fdd](https://linux-hardware.org/?probe=f749123fdd) | Jan 31, 2022 |
| ASUSTek       | U24A                        | [cc19cff1a9](https://linux-hardware.org/?probe=cc19cff1a9) | Jan 30, 2022 |
| Fujitsu       | FMVA42CW                    | [ee9b2f44e9](https://linux-hardware.org/?probe=ee9b2f44e9) | Jan 29, 2022 |
| ASUSTek       | UX303LA                     | [b5e498daf0](https://linux-hardware.org/?probe=b5e498daf0) | Jan 28, 2022 |
| Acer          | Aspire V3-571               | [3d4087dc2a](https://linux-hardware.org/?probe=3d4087dc2a) | Jan 28, 2022 |
| Razer         | Blade Stealth               | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Fujitsu       | FMVA42CW                    | [4ba92ab5ea](https://linux-hardware.org/?probe=4ba92ab5ea) | Jan 23, 2022 |
| Dell          | Latitude 3540               | [28339307b2](https://linux-hardware.org/?probe=28339307b2) | Jan 21, 2022 |
| ASUSTek       | 1000H                       | [f88ac2dd3e](https://linux-hardware.org/?probe=f88ac2dd3e) | Jan 19, 2022 |
| ASUSTek       | 1000H                       | [6c56c2c8b3](https://linux-hardware.org/?probe=6c56c2c8b3) | Jan 19, 2022 |
| KOUZIRO       | KOUZIRONB                   | [56b639daeb](https://linux-hardware.org/?probe=56b639daeb) | Jan 14, 2022 |
| Dynabook      | P1-C7MP-BL                  | [268f94787e](https://linux-hardware.org/?probe=268f94787e) | Jan 14, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [8f0b1342b0](https://linux-hardware.org/?probe=8f0b1342b0) | Jan 10, 2022 |
| Lenovo        | ThinkPad X61 76753BJ        | [73ff2bcb33](https://linux-hardware.org/?probe=73ff2bcb33) | Jan 10, 2022 |
| Acer          | Predator PH315-53           | [7f928f794b](https://linux-hardware.org/?probe=7f928f794b) | Jan 04, 2022 |
| NEC Comput... | PC-LL550RG                  | [43435578b7](https://linux-hardware.org/?probe=43435578b7) | Jan 04, 2022 |
| Dell          | Inspiron 5557               | [53d769eaf7](https://linux-hardware.org/?probe=53d769eaf7) | Dec 31, 2021 |
| System76      | Lemur Pro                   | [287aa601fe](https://linux-hardware.org/?probe=287aa601fe) | Dec 29, 2021 |
| Toshiba       | dynabook RX3 SN240Y/3HD     | [0b20db823c](https://linux-hardware.org/?probe=0b20db823c) | Dec 29, 2021 |
| Dell          | Latitude 12 Rugged Table... | [13cc8e2abf](https://linux-hardware.org/?probe=13cc8e2abf) | Dec 25, 2021 |
| MSI           | Delta 15 A5EFK              | [68010a3af5](https://linux-hardware.org/?probe=68010a3af5) | Dec 23, 2021 |
| MSI           | Delta 15 A5EFK              | [2d4a0a1823](https://linux-hardware.org/?probe=2d4a0a1823) | Dec 23, 2021 |
| ASUSTek       | ASUS EXPERTBOOK B9450FA_... | [ded54cb08c](https://linux-hardware.org/?probe=ded54cb08c) | Dec 19, 2021 |
| Dell          | Inspiron 13 5310            | [bdad2f1618](https://linux-hardware.org/?probe=bdad2f1618) | Dec 14, 2021 |
| ASUSTek       | X510UQ                      | [1b14f17a6e](https://linux-hardware.org/?probe=1b14f17a6e) | Dec 11, 2021 |
| Apple         | MacBookPro12,1              | [a6e257304d](https://linux-hardware.org/?probe=a6e257304d) | Dec 05, 2021 |
| Toshiba       | dynabook Satellite B552/... | [b3c78d548b](https://linux-hardware.org/?probe=b3c78d548b) | Dec 03, 2021 |
| Apple         | MacBookPro13,2              | [d5c66e036d](https://linux-hardware.org/?probe=d5c66e036d) | Dec 02, 2021 |
| Notebook      | N13_N140ZU                  | [d63f7874c8](https://linux-hardware.org/?probe=d63f7874c8) | Nov 29, 2021 |
| Dell          | G3 3779                     | [cd6dace549](https://linux-hardware.org/?probe=cd6dace549) | Nov 26, 2021 |
| Notebook      | N13_N140ZU                  | [dca6d021bb](https://linux-hardware.org/?probe=dca6d021bb) | Nov 23, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [fdb480d5f4](https://linux-hardware.org/?probe=fdb480d5f4) | Nov 12, 2021 |
| Lenovo        | G580 26897JJ                | [dc2120663a](https://linux-hardware.org/?probe=dc2120663a) | Nov 10, 2021 |
| Dell          | Inspiron M5110              | [4a6d42444c](https://linux-hardware.org/?probe=4a6d42444c) | Nov 10, 2021 |
| System76      | Lemur Pro                   | [92a5e9c183](https://linux-hardware.org/?probe=92a5e9c183) | Nov 09, 2021 |
| Dell          | Inspiron 16 7610            | [34e330ff50](https://linux-hardware.org/?probe=34e330ff50) | Nov 07, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [0193f0b7a0](https://linux-hardware.org/?probe=0193f0b7a0) | Nov 06, 2021 |
| Timi          | RedmiBook Pro 14S           | [470204d924](https://linux-hardware.org/?probe=470204d924) | Nov 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [f7309ef31a](https://linux-hardware.org/?probe=f7309ef31a) | Oct 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [26adc81160](https://linux-hardware.org/?probe=26adc81160) | Oct 30, 2021 |
| Toshiba       | PORTEGE Z20t-C              | [ed1722174a](https://linux-hardware.org/?probe=ed1722174a) | Oct 27, 2021 |
| Dell          | G5 5500                     | [cf10cd5b99](https://linux-hardware.org/?probe=cf10cd5b99) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | [1f26867986](https://linux-hardware.org/?probe=1f26867986) | Oct 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6aa4ae0da5](https://linux-hardware.org/?probe=6aa4ae0da5) | Oct 23, 2021 |
| HP            | ProBook 6550b               | [4db59c8489](https://linux-hardware.org/?probe=4db59c8489) | Oct 23, 2021 |
| Dell          | G3 3779                     | [a84248c5d5](https://linux-hardware.org/?probe=a84248c5d5) | Oct 21, 2021 |
| Jumper        | Ezbook X3                   | [fe510b821a](https://linux-hardware.org/?probe=fe510b821a) | Oct 17, 2021 |
| UNITCOM       | W55xEU                      | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| NEC Comput... | PC-LL550VG6R                | [5879ce1d61](https://linux-hardware.org/?probe=5879ce1d61) | Oct 13, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [f2690f5ec4](https://linux-hardware.org/?probe=f2690f5ec4) | Oct 13, 2021 |
| Toshiba       | dynabook R634/K             | [f0e385cbfb](https://linux-hardware.org/?probe=f0e385cbfb) | Oct 08, 2021 |
| Acer          | Nitro AN515-45              | [6918b927d0](https://linux-hardware.org/?probe=6918b927d0) | Oct 07, 2021 |
| Dell          | XPS 13 9380                 | [0b768f6fac](https://linux-hardware.org/?probe=0b768f6fac) | Oct 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c920ce007](https://linux-hardware.org/?probe=1c920ce007) | Oct 03, 2021 |
| Fujitsu       | U9311                       | [a76f2fbbe3](https://linux-hardware.org/?probe=a76f2fbbe3) | Sep 30, 2021 |
| Panasonic     | CFSV9-2                     | [05b8edc925](https://linux-hardware.org/?probe=05b8edc925) | Sep 29, 2021 |
| NEC Comput... | PC-GN15B79AA                | [a1046b626e](https://linux-hardware.org/?probe=a1046b626e) | Sep 23, 2021 |
| NEC Comput... | PC-GN15B79AA                | [a1b9f1dc30](https://linux-hardware.org/?probe=a1b9f1dc30) | Sep 23, 2021 |
| Toshiba       | dynabook QOSMIO V65/86LY... | [b0289ef67d](https://linux-hardware.org/?probe=b0289ef67d) | Sep 22, 2021 |
| Apple         | MacBook7,1                  | [5164ba24f6](https://linux-hardware.org/?probe=5164ba24f6) | Sep 21, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6f52a2ebed](https://linux-hardware.org/?probe=6f52a2ebed) | Sep 18, 2021 |
| Apple         | MacBookPro5,5               | [d7ee29aac3](https://linux-hardware.org/?probe=d7ee29aac3) | Sep 15, 2021 |
| Panasonic     | CF-S10EYTDR                 | [a90d037dcf](https://linux-hardware.org/?probe=a90d037dcf) | Sep 10, 2021 |
| ASUSTek       | G551JM                      | [9f323164cd](https://linux-hardware.org/?probe=9f323164cd) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| ASUSTek       | ZenBook UX425IA_U4700IA     | [fa970f7a80](https://linux-hardware.org/?probe=fa970f7a80) | Sep 08, 2021 |
| TUXEDO        | P95_HR                      | [f5d32061ec](https://linux-hardware.org/?probe=f5d32061ec) | Sep 08, 2021 |
| Toshiba       | dynabook T55/PW             | [1ce1b25ad5](https://linux-hardware.org/?probe=1ce1b25ad5) | Sep 04, 2021 |
| Lenovo        | ThinkPad X230 2306A44       | [8f97e284a7](https://linux-hardware.org/?probe=8f97e284a7) | Sep 03, 2021 |
| Toshiba       | dynabook R73/A              | [deb0351e19](https://linux-hardware.org/?probe=deb0351e19) | Sep 03, 2021 |
| Acer          | Aspire V5-571G              | [919b7c1304](https://linux-hardware.org/?probe=919b7c1304) | Sep 01, 2021 |
| Acer          | Aspire V5-471               | [469dc0f2ef](https://linux-hardware.org/?probe=469dc0f2ef) | Aug 31, 2021 |
| Acer          | Aspire V5-471               | [47f44e561f](https://linux-hardware.org/?probe=47f44e561f) | Aug 31, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Apple         | MacBookPro11,5              | [814f16635c](https://linux-hardware.org/?probe=814f16635c) | Aug 22, 2021 |
| Sony          | VGN-S55B_S                  | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| HP            | Laptop 15s-eq1xxx           | [90446b95e6](https://linux-hardware.org/?probe=90446b95e6) | Aug 21, 2021 |
| HP            | ProBook 6470b               | [4d338e7f16](https://linux-hardware.org/?probe=4d338e7f16) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [9b9cd9a995](https://linux-hardware.org/?probe=9b9cd9a995) | Aug 10, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | [32e6ec699f](https://linux-hardware.org/?probe=32e6ec699f) | Aug 09, 2021 |
| HP            | EliteBook Folio 1020 G1 ... | [7facd0568b](https://linux-hardware.org/?probe=7facd0568b) | Aug 09, 2021 |
| Lenovo        | ThinkPad X250 20CLS8E700    | [467f177df6](https://linux-hardware.org/?probe=467f177df6) | Aug 09, 2021 |
| NEC Comput... | PC-GN246W3A5                | [dfc05750e3](https://linux-hardware.org/?probe=dfc05750e3) | Aug 09, 2021 |
| Panasonic     | CF-S10EYTDR                 | [b965812f09](https://linux-hardware.org/?probe=b965812f09) | Aug 06, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [ff5bee5ff8](https://linux-hardware.org/?probe=ff5bee5ff8) | Aug 01, 2021 |
| Chuwi         | GemiBook Pro                | [a4ecebc31b](https://linux-hardware.org/?probe=a4ecebc31b) | Jul 27, 2021 |
| Chuwi         | GemiBook Pro                | [63b014e84e](https://linux-hardware.org/?probe=63b014e84e) | Jul 26, 2021 |
| Chuwi         | GemiBook Pro                | [478d06f2df](https://linux-hardware.org/?probe=478d06f2df) | Jul 26, 2021 |
| Acer          | Nitro AN515-45              | [fbf1f240f4](https://linux-hardware.org/?probe=fbf1f240f4) | Jul 24, 2021 |
| Fujitsu       | FMVS03004                   | [0182178989](https://linux-hardware.org/?probe=0182178989) | Jul 24, 2021 |
| HP            | 14                          | [29af89c91b](https://linux-hardware.org/?probe=29af89c91b) | Jul 23, 2021 |
| HP            | 14                          | [345be169ae](https://linux-hardware.org/?probe=345be169ae) | Jul 20, 2021 |
| Fujitsu       | FMVS54CD1                   | [7e6aa1f514](https://linux-hardware.org/?probe=7e6aa1f514) | Jul 18, 2021 |
| Dell          | Inspiron N5110              | [80b10e8187](https://linux-hardware.org/?probe=80b10e8187) | Jul 18, 2021 |
| Fujitsu       | FMVS54CD1                   | [ad9e144c6a](https://linux-hardware.org/?probe=ad9e144c6a) | Jul 15, 2021 |
| Dell          | Latitude E5510              | [2ab8a16c55](https://linux-hardware.org/?probe=2ab8a16c55) | Jul 12, 2021 |
| Toshiba       | dynabook T954/89L           | [176e4906db](https://linux-hardware.org/?probe=176e4906db) | Jul 12, 2021 |
| Dell          | Inspiron 1526               | [515fc96089](https://linux-hardware.org/?probe=515fc96089) | Jul 11, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [c0af3fd295](https://linux-hardware.org/?probe=c0af3fd295) | Jul 05, 2021 |
| Google        | Helios                      | [644f9f9062](https://linux-hardware.org/?probe=644f9f9062) | Jul 02, 2021 |
| Dell          | XPS 15 9500                 | [db7536f5a7](https://linux-hardware.org/?probe=db7536f5a7) | Jun 29, 2021 |
| Dell          | Inspiron 5583               | [a1f0396c8e](https://linux-hardware.org/?probe=a1f0396c8e) | Jun 29, 2021 |
| Lenovo        | ThinkPad X61s 7667DB2       | [32d294ba2a](https://linux-hardware.org/?probe=32d294ba2a) | Jun 23, 2021 |
| Toshiba       | dynabook T954/89L           | [c4b1b8aabb](https://linux-hardware.org/?probe=c4b1b8aabb) | Jun 21, 2021 |
| Toshiba       | dynabook T954/89L           | [b6a5d80f8a](https://linux-hardware.org/?probe=b6a5d80f8a) | Jun 21, 2021 |
| Lenovo        | S10-3                       | [eb48df4717](https://linux-hardware.org/?probe=eb48df4717) | Jun 20, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [2da9390d91](https://linux-hardware.org/?probe=2da9390d91) | Jun 11, 2021 |
| HP            | Pavilion Laptop 13-an0xx... | [c33921449f](https://linux-hardware.org/?probe=c33921449f) | Jun 10, 2021 |
| Toshiba       | dynabook R73/BN             | [c9cdf2bc57](https://linux-hardware.org/?probe=c9cdf2bc57) | Jun 06, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [0860242147](https://linux-hardware.org/?probe=0860242147) | Jun 04, 2021 |
| Lenovo        | ThinkPad T420s 4170CTO      | [74057c8385](https://linux-hardware.org/?probe=74057c8385) | May 30, 2021 |
| Lenovo        | S10-3                       | [8dfadf5edb](https://linux-hardware.org/?probe=8dfadf5edb) | May 27, 2021 |
| NEC Comput... | PC-LL730TG                  | [e4172892e9](https://linux-hardware.org/?probe=e4172892e9) | May 26, 2021 |
| Notebook      | N13_N140ZU                  | [4d1d4e61c3](https://linux-hardware.org/?probe=4d1d4e61c3) | May 25, 2021 |
| NEC Comput... | PC-VK22TGGCN                | [b6a2893c7e](https://linux-hardware.org/?probe=b6a2893c7e) | May 25, 2021 |
| Dell          | Latitude E6420              | [4ef6253092](https://linux-hardware.org/?probe=4ef6253092) | May 22, 2021 |
| Dell          | XPS 13 9360                 | [4ea4747cbf](https://linux-hardware.org/?probe=4ea4747cbf) | May 18, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [5d215fafdd](https://linux-hardware.org/?probe=5d215fafdd) | May 15, 2021 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [fdc8841fca](https://linux-hardware.org/?probe=fdc8841fca) | May 14, 2021 |
| Fujitsu       | FMVWE3AB11                  | [6c767dc0df](https://linux-hardware.org/?probe=6c767dc0df) | May 13, 2021 |
| Fujitsu       | FMVWE3AB11                  | [5ed8fb5a9f](https://linux-hardware.org/?probe=5ed8fb5a9f) | May 13, 2021 |
| Lenovo        | ThinkPad X230 2330A17       | [02280704ba](https://linux-hardware.org/?probe=02280704ba) | May 11, 2021 |
| Dell          | Inspiron 1545               | [c796c57372](https://linux-hardware.org/?probe=c796c57372) | May 10, 2021 |
| Fujitsu       | FMVWE3AB11                  | [e7238c107c](https://linux-hardware.org/?probe=e7238c107c) | May 09, 2021 |
| Fujitsu       | FMVNF40UK                   | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| MouseCompu... | W150ERQ                     | [1ccfec5c8f](https://linux-hardware.org/?probe=1ccfec5c8f) | May 07, 2021 |
| Dell          | XPS 13 9360                 | [f001bddea6](https://linux-hardware.org/?probe=f001bddea6) | May 04, 2021 |
| Fujitsu       | FMVWE3AB11                  | [65dce9cf99](https://linux-hardware.org/?probe=65dce9cf99) | May 03, 2021 |
| Dynabook      | P1-T6NP-EG                  | [887c9157d0](https://linux-hardware.org/?probe=887c9157d0) | May 03, 2021 |
| Toshiba       | dynabook Satellite J61 1... | [0b4c4a93f1](https://linux-hardware.org/?probe=0b4c4a93f1) | Apr 29, 2021 |
| Maibenben     | S431                        | [a4db49a83f](https://linux-hardware.org/?probe=a4db49a83f) | Apr 29, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| KOUZIRO       | KOUZIRONB                   | [c64bf46d8b](https://linux-hardware.org/?probe=c64bf46d8b) | Apr 24, 2021 |
| HP            | Laptop 15-db0xxx            | [7a4d236e06](https://linux-hardware.org/?probe=7a4d236e06) | Apr 24, 2021 |
| Dell          | XPS 13 9360                 | [dae1fdda5f](https://linux-hardware.org/?probe=dae1fdda5f) | Apr 23, 2021 |
| Lenovo        | ThinkBook 15p 20V3          | [fff82cb538](https://linux-hardware.org/?probe=fff82cb538) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| TUXEDO        | P95_HR                      | [4afc76cdbe](https://linux-hardware.org/?probe=4afc76cdbe) | Apr 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [3ee0cc7c18](https://linux-hardware.org/?probe=3ee0cc7c18) | Apr 13, 2021 |
| Dell          | Precision M4800             | [7a2924ab2a](https://linux-hardware.org/?probe=7a2924ab2a) | Apr 13, 2021 |
| HP            | Pavilion dv4                | [c5ed691eb7](https://linux-hardware.org/?probe=c5ed691eb7) | Apr 13, 2021 |
| KOUZIRO       | KOUZIRONB                   | [18adf344fe](https://linux-hardware.org/?probe=18adf344fe) | Apr 11, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | [122641cd7e](https://linux-hardware.org/?probe=122641cd7e) | Apr 08, 2021 |
| NEC Comput... | PC-VK25TXZCE                | [e6acc84298](https://linux-hardware.org/?probe=e6acc84298) | Apr 07, 2021 |
| Toshiba       | dynabook BX/33M             | [06580ff422](https://linux-hardware.org/?probe=06580ff422) | Apr 06, 2021 |
| Lenovo        | ThinkPad X230 23245Y1       | [83430b3adf](https://linux-hardware.org/?probe=83430b3adf) | Apr 06, 2021 |
| Dynabook      | P1-T6NP-EG                  | [3f0b2d7c1d](https://linux-hardware.org/?probe=3f0b2d7c1d) | Apr 05, 2021 |
| Toshiba       | dynabook CX/48F             | [d32bf9dced](https://linux-hardware.org/?probe=d32bf9dced) | Apr 02, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [a82050e3ae](https://linux-hardware.org/?probe=a82050e3ae) | Apr 01, 2021 |
| Toshiba       | dynabook Satellite B552/... | [0a547ba59a](https://linux-hardware.org/?probe=0a547ba59a) | Mar 31, 2021 |
| Dell          | Latitude E6320              | [2c01829c5b](https://linux-hardware.org/?probe=2c01829c5b) | Mar 28, 2021 |
| Dell          | G3 3500                     | [83f2a24875](https://linux-hardware.org/?probe=83f2a24875) | Mar 27, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [22b865b40a](https://linux-hardware.org/?probe=22b865b40a) | Mar 26, 2021 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [43c49d259d](https://linux-hardware.org/?probe=43c49d259d) | Mar 26, 2021 |
| HP            | G60                         | [a97ca105eb](https://linux-hardware.org/?probe=a97ca105eb) | Mar 25, 2021 |
| HP            | G60                         | [e8cc7247c7](https://linux-hardware.org/?probe=e8cc7247c7) | Mar 23, 2021 |
| TUXEDO        | P95_HR                      | [22b092fe80](https://linux-hardware.org/?probe=22b092fe80) | Mar 23, 2021 |
| Unknown       | Unknown                     | [a4b57558c3](https://linux-hardware.org/?probe=a4b57558c3) | Mar 22, 2021 |
| HP            | ProBook 430 G7              | [fbf317133b](https://linux-hardware.org/?probe=fbf317133b) | Mar 21, 2021 |
| Toshiba       | dynabook Satellite B552/... | [56a39af725](https://linux-hardware.org/?probe=56a39af725) | Mar 20, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [2d9b9381bd](https://linux-hardware.org/?probe=2d9b9381bd) | Mar 16, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [aac20e8dce](https://linux-hardware.org/?probe=aac20e8dce) | Mar 15, 2021 |
| Fujitsu       | FMVA05007                   | [707f6a3ea5](https://linux-hardware.org/?probe=707f6a3ea5) | Mar 14, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20T3C... | [7cda624782](https://linux-hardware.org/?probe=7cda624782) | Mar 12, 2021 |
| Dynabook      | GCX83/PLE                   | [2ef2ac3448](https://linux-hardware.org/?probe=2ef2ac3448) | Mar 12, 2021 |
| Fujitsu       | FMVS54EB                    | [f01ca3644f](https://linux-hardware.org/?probe=f01ca3644f) | Mar 11, 2021 |
| Dell          | Inspiron N5110              | [3feff6616d](https://linux-hardware.org/?probe=3feff6616d) | Mar 07, 2021 |
| Dell          | Latitude 7280               | [64e390d0d6](https://linux-hardware.org/?probe=64e390d0d6) | Mar 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [24088afc25](https://linux-hardware.org/?probe=24088afc25) | Mar 06, 2021 |
| Timi          | RedmiBook 16                | [7139d19a98](https://linux-hardware.org/?probe=7139d19a98) | Mar 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e840817785](https://linux-hardware.org/?probe=e840817785) | Mar 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [5f5d47e737](https://linux-hardware.org/?probe=5f5d47e737) | Feb 26, 2021 |
| Lenovo        | Yoga 3 14 80JH              | [b1a878b7d0](https://linux-hardware.org/?probe=b1a878b7d0) | Feb 26, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [55b2402c28](https://linux-hardware.org/?probe=55b2402c28) | Feb 25, 2021 |
| Apple         | MacBookPro9,2               | [3e009dec2f](https://linux-hardware.org/?probe=3e009dec2f) | Feb 23, 2021 |
| NEC Comput... | PC-LL750FS6R                | [2708ba9972](https://linux-hardware.org/?probe=2708ba9972) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | [fa1eb2a97a](https://linux-hardware.org/?probe=fa1eb2a97a) | Feb 23, 2021 |
| NEC Comput... | PC-VY22GXZ7A                | [cf754cecc4](https://linux-hardware.org/?probe=cf754cecc4) | Feb 23, 2021 |
| Toshiba       | dynabook Satellite TXW/6... | [51128d9716](https://linux-hardware.org/?probe=51128d9716) | Feb 19, 2021 |
| Toshiba       | dynabook EX/35KWH           | [c52a95f06c](https://linux-hardware.org/?probe=c52a95f06c) | Feb 18, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [e8e114704d](https://linux-hardware.org/?probe=e8e114704d) | Feb 16, 2021 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [977e293baa](https://linux-hardware.org/?probe=977e293baa) | Feb 16, 2021 |
| Fujitsu       | FMVNFB40J                   | [8a3d6bcc89](https://linux-hardware.org/?probe=8a3d6bcc89) | Feb 15, 2021 |
| Fujitsu       | FMVA05002                   | [a758e3201d](https://linux-hardware.org/?probe=a758e3201d) | Feb 14, 2021 |
| Lenovo        | ThinkPad T61 7659D92        | [8d9f56460d](https://linux-hardware.org/?probe=8d9f56460d) | Feb 13, 2021 |
| Fujitsu       | FMVA56GBX                   | [bdc337bd04](https://linux-hardware.org/?probe=bdc337bd04) | Feb 13, 2021 |
| HP            | Pavilion g6                 | [a45a89930f](https://linux-hardware.org/?probe=a45a89930f) | Feb 13, 2021 |
| Fujitsu       | FMVA05002                   | [db95456803](https://linux-hardware.org/?probe=db95456803) | Feb 12, 2021 |
| Panasonic     | CF-SX3EDHCS                 | [3f7a156241](https://linux-hardware.org/?probe=3f7a156241) | Feb 11, 2021 |
| NEC Comput... | PC-VK19SGZDF                | [624a2eee47](https://linux-hardware.org/?probe=624a2eee47) | Feb 10, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [e507fdbcf5](https://linux-hardware.org/?probe=e507fdbcf5) | Feb 08, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| Unknown       | Unknown                     | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| NEC Comput... | PC-LL750SG6R                | [7c9081a73a](https://linux-hardware.org/?probe=7c9081a73a) | Jan 16, 2021 |
| Sony          | VGN-TZ73B                   | [735d00e026](https://linux-hardware.org/?probe=735d00e026) | Jan 13, 2021 |
| Sony          | VGN-TZ73B                   | [5df5433a1c](https://linux-hardware.org/?probe=5df5433a1c) | Jan 13, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [1d6691dffe](https://linux-hardware.org/?probe=1d6691dffe) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [d033697e79](https://linux-hardware.org/?probe=d033697e79) | Jan 12, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [6173e9c6e9](https://linux-hardware.org/?probe=6173e9c6e9) | Jan 12, 2021 |
| UNITCOM       | W55xEU                      | [8c2793a502](https://linux-hardware.org/?probe=8c2793a502) | Jan 10, 2021 |
| UNITCOM       | W55xEU                      | [44b1f16e92](https://linux-hardware.org/?probe=44b1f16e92) | Jan 10, 2021 |
| HUAWEI        | MRC-WX0                     | [f650998a3d](https://linux-hardware.org/?probe=f650998a3d) | Jan 02, 2021 |
| Fujitsu       | FMVLCE50B                   | [03569af3cb](https://linux-hardware.org/?probe=03569af3cb) | Dec 31, 2020 |
| MSI           | Modern 14 B4MW              | [ec110ae347](https://linux-hardware.org/?probe=ec110ae347) | Dec 28, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | [fbc4b89320](https://linux-hardware.org/?probe=fbc4b89320) | Dec 28, 2020 |
| Dell          | Inspiron 5490               | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | [84b2b1cba7](https://linux-hardware.org/?probe=84b2b1cba7) | Dec 26, 2020 |
| Thirdwave     | Diginnos PC                 | [4573bf9eeb](https://linux-hardware.org/?probe=4573bf9eeb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | [f4fe782260](https://linux-hardware.org/?probe=f4fe782260) | Dec 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [fcc97d1fdb](https://linux-hardware.org/?probe=fcc97d1fdb) | Dec 25, 2020 |
| Toshiba       | dynabook Satellite TXW/6... | [21e571b40f](https://linux-hardware.org/?probe=21e571b40f) | Dec 25, 2020 |
| Dynabook      | P1-T6NP-EG                  | [9f6b496aaf](https://linux-hardware.org/?probe=9f6b496aaf) | Dec 25, 2020 |
| Fujitsu       | FMVNFA50                    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| Dell          | Inspiron 13-5378            | [d236c778e1](https://linux-hardware.org/?probe=d236c778e1) | Dec 21, 2020 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | [6a74695399](https://linux-hardware.org/?probe=6a74695399) | Dec 21, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| Dell          | Latitude E6230              | [c0f67befa0](https://linux-hardware.org/?probe=c0f67befa0) | Dec 18, 2020 |
| Dell          | Latitude E6230              | [9dd587de7a](https://linux-hardware.org/?probe=9dd587de7a) | Dec 18, 2020 |
| Dell          | Inspiron 13-5378            | [52b0b77ef7](https://linux-hardware.org/?probe=52b0b77ef7) | Dec 17, 2020 |
| NEC Comput... | PC-LL750SG6R                | [867c1b37b1](https://linux-hardware.org/?probe=867c1b37b1) | Dec 14, 2020 |
| Dell          | Inspiron 5370               | [9cf5fbfe60](https://linux-hardware.org/?probe=9cf5fbfe60) | Dec 09, 2020 |
| Toshiba       | dynabook Satellite B552/... | [575c848b52](https://linux-hardware.org/?probe=575c848b52) | Dec 07, 2020 |
| Toshiba       | dynabook Satellite B552/... | [58cf889053](https://linux-hardware.org/?probe=58cf889053) | Dec 07, 2020 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [1190e2392c](https://linux-hardware.org/?probe=1190e2392c) | Dec 02, 2020 |
| HP            | G7000                       | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Lenovo        | ThinkPad X230 23069FJ       | [e8e9e6770b](https://linux-hardware.org/?probe=e8e9e6770b) | Nov 29, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [5fd1f62125](https://linux-hardware.org/?probe=5fd1f62125) | Nov 21, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [593013a504](https://linux-hardware.org/?probe=593013a504) | Nov 20, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | [f34c508c5a](https://linux-hardware.org/?probe=f34c508c5a) | Nov 19, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [8d4468ec71](https://linux-hardware.org/?probe=8d4468ec71) | Nov 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS0QM00    | [f827ecc142](https://linux-hardware.org/?probe=f827ecc142) | Nov 16, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [adbf017e43](https://linux-hardware.org/?probe=adbf017e43) | Nov 13, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [3d8a88a6dd](https://linux-hardware.org/?probe=3d8a88a6dd) | Nov 08, 2020 |
| SLIMBOOK      | PROX14-AMD                  | [d746af6cfd](https://linux-hardware.org/?probe=d746af6cfd) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | [32a742ccd5](https://linux-hardware.org/?probe=32a742ccd5) | Nov 07, 2020 |
| MouseCompu... | N252JU                      | [497c61e3d1](https://linux-hardware.org/?probe=497c61e3d1) | Nov 07, 2020 |
| Panasonic     | CF-SX1GDHYS                 | [e8f3a6867e](https://linux-hardware.org/?probe=e8f3a6867e) | Nov 06, 2020 |
| Fujitsu       | FMVNF70W                    | [aedfc24e7e](https://linux-hardware.org/?probe=aedfc24e7e) | Nov 05, 2020 |
| Fujitsu       | FMVNF70W                    | [6039056d5c](https://linux-hardware.org/?probe=6039056d5c) | Nov 05, 2020 |
| Apple         | MacBookAir6,1               | [102aa409db](https://linux-hardware.org/?probe=102aa409db) | Nov 03, 2020 |
| MSI           | GS66 Stealth 10SF           | [c885924d12](https://linux-hardware.org/?probe=c885924d12) | Nov 02, 2020 |
| Lenovo        | ThinkPad X250 20CLA3TPJP    | [51449a174d](https://linux-hardware.org/?probe=51449a174d) | Nov 01, 2020 |
| HUAWEI        | MRC-WX0                     | [57608acdc4](https://linux-hardware.org/?probe=57608acdc4) | Oct 31, 2020 |
| Dell          | Vostro 2520                 | [196d3c6a8d](https://linux-hardware.org/?probe=196d3c6a8d) | Oct 30, 2020 |
| HP            | ENVY 15                     | [7e0fd3abbc](https://linux-hardware.org/?probe=7e0fd3abbc) | Oct 28, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [d4b681e245](https://linux-hardware.org/?probe=d4b681e245) | Oct 28, 2020 |
| Dell          | Vostro 2520                 | [b660b39908](https://linux-hardware.org/?probe=b660b39908) | Oct 25, 2020 |
| HP            | ProBook 4525s               | [157a86205d](https://linux-hardware.org/?probe=157a86205d) | Oct 24, 2020 |
| Unknown       | Unknown                     | [046bfed81f](https://linux-hardware.org/?probe=046bfed81f) | Oct 23, 2020 |
| Sony          | VPCEB49FJ                   | [a7b30aea08](https://linux-hardware.org/?probe=a7b30aea08) | Oct 21, 2020 |
| EPSON DIRE... | Endeavor NJ7000E            | [fd0992fec0](https://linux-hardware.org/?probe=fd0992fec0) | Oct 21, 2020 |
| MouseCompu... | NG-N-i5730                  | [7748ae5522](https://linux-hardware.org/?probe=7748ae5522) | Oct 19, 2020 |
| ASUSTek       | E200HA                      | [01f02e3868](https://linux-hardware.org/?probe=01f02e3868) | Oct 19, 2020 |
| Fujitsu       | FMVNF70W                    | [af9ba22806](https://linux-hardware.org/?probe=af9ba22806) | Oct 17, 2020 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [d7c4496b69](https://linux-hardware.org/?probe=d7c4496b69) | Oct 17, 2020 |
| HP            | ProBook 4525s               | [67efc6e80a](https://linux-hardware.org/?probe=67efc6e80a) | Oct 16, 2020 |
| UNITCOM       | W35_37ET                    | [13ddafa560](https://linux-hardware.org/?probe=13ddafa560) | Oct 16, 2020 |
| NEC Comput... | PC-LL750F26C                | [7b9dc13b94](https://linux-hardware.org/?probe=7b9dc13b94) | Oct 10, 2020 |
| NEC Comput... | PC-LL750F26C                | [eb148db6e7](https://linux-hardware.org/?probe=eb148db6e7) | Oct 09, 2020 |
| Sony          | VPCS129FJ                   | [ababc3caff](https://linux-hardware.org/?probe=ababc3caff) | Oct 07, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [e4b06fc3af](https://linux-hardware.org/?probe=e4b06fc3af) | Oct 07, 2020 |
| HP            | ENVY 15                     | [096683ec03](https://linux-hardware.org/?probe=096683ec03) | Oct 06, 2020 |
| Fujitsu       | FMVWW11W                    | [e1a03b47aa](https://linux-hardware.org/?probe=e1a03b47aa) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [ebe29c2e8c](https://linux-hardware.org/?probe=ebe29c2e8c) | Oct 06, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [4c90a49a16](https://linux-hardware.org/?probe=4c90a49a16) | Oct 05, 2020 |
| HP            | ProBook 6560b               | [4f60a7aca9](https://linux-hardware.org/?probe=4f60a7aca9) | Oct 05, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [117567ed8a](https://linux-hardware.org/?probe=117567ed8a) | Oct 02, 2020 |
| Lenovo        | ThinkPad X61 76753BJ        | [c1729c7402](https://linux-hardware.org/?probe=c1729c7402) | Oct 02, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [51fb8f3cad](https://linux-hardware.org/?probe=51fb8f3cad) | Oct 02, 2020 |
| Lenovo        | M4450 20302                 | [0614174763](https://linux-hardware.org/?probe=0614174763) | Sep 29, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2ebce35736](https://linux-hardware.org/?probe=2ebce35736) | Sep 29, 2020 |
| ASUSTek       | VivoBook E14 E402YA_E402... | [84913584dc](https://linux-hardware.org/?probe=84913584dc) | Sep 27, 2020 |
| Sharp         | PC-WE/WT Series             | [91e9663e3a](https://linux-hardware.org/?probe=91e9663e3a) | Sep 22, 2020 |
| HP            | ProBook 6550b               | [58aeb4c973](https://linux-hardware.org/?probe=58aeb4c973) | Sep 19, 2020 |
| Lenovo        | ThinkPad X230 2325SSF       | [087fa4f531](https://linux-hardware.org/?probe=087fa4f531) | Sep 17, 2020 |
| HP            | ProBook 6570b               | [db08cfd499](https://linux-hardware.org/?probe=db08cfd499) | Sep 17, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | [d58a689a0b](https://linux-hardware.org/?probe=d58a689a0b) | Sep 13, 2020 |
| Sony          | VGN-NW50JB                  | [f5115778c1](https://linux-hardware.org/?probe=f5115778c1) | Sep 11, 2020 |
| HP            | EliteBook 820 G2            | [37e43e92e5](https://linux-hardware.org/?probe=37e43e92e5) | Sep 07, 2020 |
| HP            | ENVY Notebook               | [4da75a6d49](https://linux-hardware.org/?probe=4da75a6d49) | Sep 07, 2020 |
| Toshiba       | dynabook T554/56KW          | [03f3e6b816](https://linux-hardware.org/?probe=03f3e6b816) | Sep 04, 2020 |
| Samsung       | 940X3G/930X3G               | [d63abb12ee](https://linux-hardware.org/?probe=d63abb12ee) | Sep 03, 2020 |
| Toshiba       | dynabook SS MX/25AE         | [8d195475bf](https://linux-hardware.org/?probe=8d195475bf) | Sep 02, 2020 |
| Fujitsu       | FMVNF70W                    | [b782fe1564](https://linux-hardware.org/?probe=b782fe1564) | Aug 31, 2020 |
| Fujitsu       | FMVNF70W                    | [7451d691b9](https://linux-hardware.org/?probe=7451d691b9) | Aug 31, 2020 |
| Lenovo        | ThinkPad X200s 74664SJ      | [efd7cd5751](https://linux-hardware.org/?probe=efd7cd5751) | Aug 29, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [a2c94f7fdd](https://linux-hardware.org/?probe=a2c94f7fdd) | Aug 29, 2020 |
| Acer          | Aspire V3-571               | [8b32c068dc](https://linux-hardware.org/?probe=8b32c068dc) | Aug 24, 2020 |
| UNITCOM       | W35_37ET                    | [221322a11d](https://linux-hardware.org/?probe=221322a11d) | Aug 18, 2020 |
| Lenovo        | G500 20236                  | [28aacac404](https://linux-hardware.org/?probe=28aacac404) | Aug 16, 2020 |
| Fujitsu       | FMVNF70W                    | [ea2752e5b3](https://linux-hardware.org/?probe=ea2752e5b3) | Aug 14, 2020 |
| Sony          | SVE14A18FJW                 | [0868a90d93](https://linux-hardware.org/?probe=0868a90d93) | Aug 11, 2020 |
| Sony          | SVE14A18FJW                 | [dcd00b5fdc](https://linux-hardware.org/?probe=dcd00b5fdc) | Aug 11, 2020 |
| Lenovo        | ThinkPad T400 6475F99       | [83366b7e92](https://linux-hardware.org/?probe=83366b7e92) | Aug 10, 2020 |
| Dell          | XPS 15 9570                 | [7b17868903](https://linux-hardware.org/?probe=7b17868903) | Aug 07, 2020 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1ae67d880c](https://linux-hardware.org/?probe=1ae67d880c) | Aug 02, 2020 |
| Thirdwave     | Diginnos PC                 | [edad55d12d](https://linux-hardware.org/?probe=edad55d12d) | Aug 02, 2020 |
| Thirdwave     | Diginnos PC                 | [e1fd71a4b1](https://linux-hardware.org/?probe=e1fd71a4b1) | Aug 02, 2020 |
| Panasonic     | CF-N9LYDKDS                 | [8f3337d6ad](https://linux-hardware.org/?probe=8f3337d6ad) | Jul 31, 2020 |
| Fujitsu       | FMVU2400AD                  | [3353544fa3](https://linux-hardware.org/?probe=3353544fa3) | Jul 31, 2020 |
| HP            | ProBook 430 G3              | [7d3e5091ef](https://linux-hardware.org/?probe=7d3e5091ef) | Jul 29, 2020 |
| Sony          | VGN-S55B_S                  | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| Toshiba       | dynabook T554/56KW          | [a6edb6db3c](https://linux-hardware.org/?probe=a6edb6db3c) | Jul 23, 2020 |
| Lenovo        | ThinkPad E520 1143RD9       | [8947a114a1](https://linux-hardware.org/?probe=8947a114a1) | Jul 20, 2020 |
| NEC Comput... | PC-GN246W3A5                | [b95df976ea](https://linux-hardware.org/?probe=b95df976ea) | Jul 19, 2020 |
| Fujitsu       | FMVA705BW                   | [0985e32752](https://linux-hardware.org/?probe=0985e32752) | Jul 18, 2020 |
| Toshiba       | dynabook EX/66MRD           | [e3a6da6bcc](https://linux-hardware.org/?probe=e3a6da6bcc) | Jul 16, 2020 |
| ASUSTek       | TUF Gaming FA506IU_TUF50... | [51c975b932](https://linux-hardware.org/?probe=51c975b932) | Jul 12, 2020 |
| NEC Comput... | PC-VJ19SGHDWLTF             | [b99df50393](https://linux-hardware.org/?probe=b99df50393) | Jul 12, 2020 |
| Acer          | Aspire 3810T                | [bc217e9435](https://linux-hardware.org/?probe=bc217e9435) | Jul 12, 2020 |
| Acer          | Aspire 3810T                | [9b2e49ccd8](https://linux-hardware.org/?probe=9b2e49ccd8) | Jul 12, 2020 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [7cf0424b3b](https://linux-hardware.org/?probe=7cf0424b3b) | Jul 10, 2020 |
| Lenovo        | ThinkPad T450 20BUS0G500    | [439f2ff831](https://linux-hardware.org/?probe=439f2ff831) | Jul 07, 2020 |
| Lenovo        | ThinkPad T450 20BUS0G500    | [770f2f3b0b](https://linux-hardware.org/?probe=770f2f3b0b) | Jul 07, 2020 |
| HP            | ProBook 470 G1              | [7e2ba71d87](https://linux-hardware.org/?probe=7e2ba71d87) | Jul 06, 2020 |
| Fujitsu       | FMVNF70W                    | [5b28cc735f](https://linux-hardware.org/?probe=5b28cc735f) | Jul 02, 2020 |
| Fujitsu       | FMVNF70W                    | [28307d3d6c](https://linux-hardware.org/?probe=28307d3d6c) | Jul 02, 2020 |
| ASUSTek       | K53SK                       | [2003676ccf](https://linux-hardware.org/?probe=2003676ccf) | Jul 01, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [6457099b06](https://linux-hardware.org/?probe=6457099b06) | Jun 27, 2020 |
| Apple         | MacBookPro11,1              | [8754b0ae46](https://linux-hardware.org/?probe=8754b0ae46) | Jun 27, 2020 |
| MSI           | GS63 7RE                    | [31dfc658d7](https://linux-hardware.org/?probe=31dfc658d7) | Jun 26, 2020 |
| Apple         | MacBookPro11,1              | [2a32b846c5](https://linux-hardware.org/?probe=2a32b846c5) | Jun 24, 2020 |
| Lenovo        | ThinkPad T500 208843J       | [a12d551827](https://linux-hardware.org/?probe=a12d551827) | Jun 21, 2020 |
| Sony          | VGN-S55B_S                  | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| Lenovo        | IdeaPad U300s 1080          | [dca0b5baa2](https://linux-hardware.org/?probe=dca0b5baa2) | Jun 21, 2020 |
| Lenovo        | IdeaPad U300s 1080          | [198cec29f3](https://linux-hardware.org/?probe=198cec29f3) | Jun 21, 2020 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [acbdac722c](https://linux-hardware.org/?probe=acbdac722c) | Jun 19, 2020 |
| Dell          | Inspiron 15-3565            | [696dea86af](https://linux-hardware.org/?probe=696dea86af) | Jun 15, 2020 |
| Apple         | MacBookPro16,1              | [8b4c1f4506](https://linux-hardware.org/?probe=8b4c1f4506) | Jun 15, 2020 |
| Apple         | MacBookPro9,2               | [5cedae8b83](https://linux-hardware.org/?probe=5cedae8b83) | Jun 12, 2020 |
| Gateway       | NE56R                       | [45934f9b2c](https://linux-hardware.org/?probe=45934f9b2c) | Jun 12, 2020 |
| ASUSTek       | K53SK                       | [ec6ff61a8c](https://linux-hardware.org/?probe=ec6ff61a8c) | Jun 12, 2020 |
| Fujitsu       | FMVNFG60TC                  | [b6bad717fa](https://linux-hardware.org/?probe=b6bad717fa) | Jun 10, 2020 |
| Fujitsu       | FMVNFG60TC                  | [1b3a040711](https://linux-hardware.org/?probe=1b3a040711) | Jun 10, 2020 |
| Fujitsu       | FMVA77JW                    | [ce5b1dbbcb](https://linux-hardware.org/?probe=ce5b1dbbcb) | Jun 10, 2020 |
| Dell          | Inspiron 15-3565            | [91540b6b55](https://linux-hardware.org/?probe=91540b6b55) | Jun 10, 2020 |
| Lenovo        | ThinkPad X230 232425J       | [2ebe6149b7](https://linux-hardware.org/?probe=2ebe6149b7) | Jun 06, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [c4d2595650](https://linux-hardware.org/?probe=c4d2595650) | Jun 04, 2020 |
| HUAWEI        | HN-WX9X                     | [7c56c01092](https://linux-hardware.org/?probe=7c56c01092) | May 30, 2020 |
| Dell          | Inspiron 7590               | [18895b4469](https://linux-hardware.org/?probe=18895b4469) | May 27, 2020 |
| Panasonic     | CF-195W1ACS                 | [5ee3c1d71e](https://linux-hardware.org/?probe=5ee3c1d71e) | May 27, 2020 |
| Dell          | Inspiron 7590               | [e219e1df90](https://linux-hardware.org/?probe=e219e1df90) | May 25, 2020 |
| Dell          | Inspiron 7590               | [46683fd696](https://linux-hardware.org/?probe=46683fd696) | May 25, 2020 |
| Dell          | Inspiron 7590               | [208561b660](https://linux-hardware.org/?probe=208561b660) | May 25, 2020 |
| Lenovo        | Z51-70 80K6                 | [7b25fce04c](https://linux-hardware.org/?probe=7b25fce04c) | May 24, 2020 |
| Acer          | Aspire 8940G                | [186821b722](https://linux-hardware.org/?probe=186821b722) | May 23, 2020 |
| Unknown       | Unknown                     | [d163d86dcb](https://linux-hardware.org/?probe=d163d86dcb) | May 19, 2020 |
| Toshiba       | dynabook T45/VRS            | [ddae801625](https://linux-hardware.org/?probe=ddae801625) | May 18, 2020 |
| Toshiba       | dynabook T45/VRS            | [efafbf544b](https://linux-hardware.org/?probe=efafbf544b) | May 18, 2020 |
| Panasonic     | CFSX4-1L                    | [54b56291de](https://linux-hardware.org/?probe=54b56291de) | May 18, 2020 |
| HP            | ProBook 6560b               | [72808d19a6](https://linux-hardware.org/?probe=72808d19a6) | May 15, 2020 |
| HP            | ProBook 6560b               | [f88ec1bc1d](https://linux-hardware.org/?probe=f88ec1bc1d) | May 15, 2020 |
| Lenovo        | G570 4334                   | [54ff12939f](https://linux-hardware.org/?probe=54ff12939f) | May 11, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Japan/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 92        | 10.99%  |
| Ubuntu 18.04                 | 47        | 5.62%   |
| Ubuntu 22.04                 | 42        | 5.02%   |
| OpenMandriva 23.03           | 31        | 3.7%    |
| OpenMandriva 4.3             | 29        | 3.46%   |
| Arch Rolling                 | 28        | 3.35%   |
| OpenMandriva 4.90            | 26        | 3.11%   |
| OpenMandriva 4.2             | 21        | 2.51%   |
| OpenMandriva 23.08           | 15        | 1.79%   |
| Debian 11                    | 15        | 1.79%   |
| Zorin 16                     | 14        | 1.67%   |
| OpenMandriva 23.01           | 14        | 1.67%   |
| Manjaro                      | 12        | 1.43%   |
| OpenMandriva 5.0             | 11        | 1.31%   |
| BlackPanther 18.1            | 11        | 1.31%   |
| Arch                         | 11        | 1.31%   |
| Pop!_OS 22.04                | 9         | 1.08%   |
| Linux Mint 22                | 9         | 1.08%   |
| Zorin 15                     | 8         | 0.96%   |
| Xubuntu 20.04                | 8         | 0.96%   |
| openSUSE Tumbleweed-XXXXXXXX | 8         | 0.96%   |
| Fedora 37                    | 8         | 0.96%   |
| Zorin 17                     | 7         | 0.84%   |
| Xubuntu 18.04                | 7         | 0.84%   |
| Ubuntu 24.04                 | 7         | 0.84%   |
| Ubuntu 23.04                 | 7         | 0.84%   |
| Ubuntu 21.04                 | 7         | 0.84%   |
| Pop!_OS 20.10                | 7         | 0.84%   |
| OpenMandriva 24.07           | 7         | 0.84%   |
| Linux Mint 19.3              | 7         | 0.84%   |
| Fedora 39                    | 7         | 0.84%   |
| Fedora 38                    | 7         | 0.84%   |
| Fedora 35                    | 7         | 0.84%   |
| Xubuntu 22.04                | 6         | 0.72%   |
| Fedora 40                    | 6         | 0.72%   |
| Ubuntu 19.10                 | 5         | 0.6%    |
| OpenMandriva 4.50            | 5         | 0.6%    |
| OpenMandriva 24.12           | 5         | 0.6%    |
| Linux Mint 21.2              | 5         | 0.6%    |
| Linux Mint 21.1              | 5         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 227       | 28.2%   |
| OpenMandriva  | 168       | 20.87%  |
| Fedora        | 52        | 6.46%   |
| Linux Mint    | 44        | 5.47%   |
| Arch          | 39        | 4.84%   |
| Debian        | 30        | 3.73%   |
| Zorin         | 29        | 3.6%    |
| Pop!_OS       | 23        | 2.86%   |
| Manjaro       | 22        | 2.73%   |
| Xubuntu       | 20        | 2.48%   |
| Kubuntu       | 12        | 1.49%   |
| openSUSE      | 11        | 1.37%   |
| BlackPanther  | 11        | 1.37%   |
| Kali          | 10        | 1.24%   |
| Ubuntu Unity  | 7         | 0.87%   |
| SteamOS       | 7         | 0.87%   |
| NixOS         | 7         | 0.87%   |
| Lubuntu       | 7         | 0.87%   |
| Gentoo        | 7         | 0.87%   |
| Slackware     | 5         | 0.62%   |
| LMDE          | 5         | 0.62%   |
| ArcoLinux     | 5         | 0.62%   |
| Ubuntu MATE   | 4         | 0.5%    |
| KDE neon      | 4         | 0.5%    |
| antiX         | 4         | 0.5%    |
| Ubuntu Budgie | 3         | 0.37%   |
| ROSA          | 3         | 0.37%   |
| Peppermint    | 3         | 0.37%   |
| Guix          | 3         | 0.37%   |
| Elementary    | 3         | 0.37%   |
| Deepin        | 3         | 0.37%   |
| CentOS        | 3         | 0.37%   |
| RHEL          | 2         | 0.25%   |
| Parrot        | 2         | 0.25%   |
| MX            | 2         | 0.25%   |
| Garuda Linux  | 2         | 0.25%   |
| Endless       | 2         | 0.25%   |
| SystemRescue  | 1         | 0.12%   |
| Sparky        | 1         | 0.12%   |
| SolydXK       | 1         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.2.6-desktop-1omv2390   | 30        | 3.28%   |
| 5.16.7-desktop-1omv4003  | 27        | 2.95%   |
| 5.10.14-desktop-1omv4002 | 20        | 2.19%   |
| 6.1.1-desktop-1omv2290   | 15        | 1.64%   |
| 6.4.11-desktop-1omv2390  | 14        | 1.53%   |
| 6.0.2-desktop-1omv4090   | 14        | 1.53%   |
| 6.6.2-desktop-1omv2390   | 13        | 1.42%   |
| 5.4.0-42-generic         | 13        | 1.42%   |
| 5.4.0-52-generic         | 11        | 1.2%    |
| 5.4.0-58-generic         | 8         | 0.87%   |
| 4.18.16-desktop-1bP      | 8         | 0.87%   |
| 6.8.0-45-generic         | 7         | 0.77%   |
| 6.10.0-desktop-1omv2490  | 7         | 0.77%   |
| 5.4.0-48-generic         | 7         | 0.77%   |
| 5.15.0-58-generic        | 6         | 0.66%   |
| 5.0.0-37-generic         | 6         | 0.66%   |
| 6.12.1-desktop-1omv2490  | 5         | 0.55%   |
| 5.8.0-7642-generic       | 5         | 0.55%   |
| 5.8.0-50-generic         | 5         | 0.55%   |
| 5.8.0-48-generic         | 5         | 0.55%   |
| 5.8.0-43-generic         | 5         | 0.55%   |
| 5.3.0-40-generic         | 5         | 0.55%   |
| 5.19.1-desktop-1omv4090  | 5         | 0.55%   |
| 5.13.0-27-generic        | 5         | 0.55%   |
| 6.8.0-31-generic         | 4         | 0.44%   |
| 6.5.0-28-generic         | 4         | 0.44%   |
| 6.2.0-33-generic         | 4         | 0.44%   |
| 5.6.14-desktop-2bP       | 4         | 0.44%   |
| 5.4.0-40-generic         | 4         | 0.44%   |
| 5.18.12-desktop-3omv4090 | 4         | 0.44%   |
| 5.16.13-desktop-1omv4003 | 4         | 0.44%   |
| 5.15.0-56-generic        | 4         | 0.44%   |
| 5.12.4-desktop-1omv4050  | 4         | 0.44%   |
| 5.11.0-37-generic        | 4         | 0.44%   |
| 5.11.0-27-generic        | 4         | 0.44%   |
| 5.10.0-21-amd64          | 4         | 0.44%   |
| 4.18.0-25-generic        | 4         | 0.44%   |
| 6.8.0-47-generic         | 3         | 0.33%   |
| 6.5.0-35-generic         | 3         | 0.33%   |
| 6.4.12-arch1-1           | 3         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 96        | 10.95%  |
| 5.15.0  | 47        | 5.36%   |
| 4.15.0  | 36        | 4.1%    |
| 5.8.0   | 34        | 3.88%   |
| 6.2.6   | 31        | 3.53%   |
| 6.5.0   | 28        | 3.19%   |
| 5.16.7  | 28        | 3.19%   |
| 5.13.0  | 27        | 3.08%   |
| 5.11.0  | 27        | 3.08%   |
| 6.8.0   | 23        | 2.62%   |
| 5.10.0  | 22        | 2.51%   |
| 5.3.0   | 20        | 2.28%   |
| 5.10.14 | 20        | 2.28%   |
| 6.2.0   | 18        | 2.05%   |
| 5.19.0  | 18        | 2.05%   |
| 5.0.0   | 17        | 1.94%   |
| 6.1.1   | 16        | 1.82%   |
| 6.4.11  | 15        | 1.71%   |
| 6.1.0   | 14        | 1.6%    |
| 6.0.2   | 14        | 1.6%    |
| 6.6.2   | 13        | 1.48%   |
| 6.12.1  | 9         | 1.03%   |
| 6.10.0  | 9         | 1.03%   |
| 4.18.0  | 9         | 1.03%   |
| 4.18.16 | 8         | 0.91%   |
| 5.19.1  | 6         | 0.68%   |
| 6.4.0   | 5         | 0.57%   |
| 6.11.0  | 5         | 0.57%   |
| 4.4.0   | 5         | 0.57%   |
| 6.4.12  | 4         | 0.46%   |
| 6.0.12  | 4         | 0.46%   |
| 6.0.0   | 4         | 0.46%   |
| 5.6.14  | 4         | 0.46%   |
| 5.19.11 | 4         | 0.46%   |
| 5.18.12 | 4         | 0.46%   |
| 5.16.13 | 4         | 0.46%   |
| 5.16.11 | 4         | 0.46%   |
| 5.12.4  | 4         | 0.46%   |
| 4.19.0  | 4         | 0.46%   |
| 6.6.8   | 3         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 103       | 11.88%  |
| 5.15    | 56        | 6.46%   |
| 6.2     | 55        | 6.34%   |
| 5.10    | 52        | 6%      |
| 6.1     | 44        | 5.07%   |
| 5.8     | 41        | 4.73%   |
| 5.16    | 40        | 4.61%   |
| 6.5     | 37        | 4.27%   |
| 4.15    | 36        | 4.15%   |
| 5.19    | 35        | 4.04%   |
| 5.13    | 34        | 3.92%   |
| 5.11    | 30        | 3.46%   |
| 6.8     | 29        | 3.34%   |
| 6.4     | 28        | 3.23%   |
| 6.0     | 26        | 3%      |
| 6.6     | 23        | 2.65%   |
| 6.10    | 21        | 2.42%   |
| 5.3     | 21        | 2.42%   |
| 5.0     | 18        | 2.08%   |
| 5.18    | 17        | 1.96%   |
| 4.18    | 17        | 1.96%   |
| 6.12    | 13        | 1.5%    |
| 6.3     | 12        | 1.38%   |
| 6.11    | 11        | 1.27%   |
| 5.14    | 11        | 1.27%   |
| 5.6     | 8         | 0.92%   |
| 5.12    | 8         | 0.92%   |
| 6.9     | 7         | 0.81%   |
| 6.7     | 6         | 0.69%   |
| 5.17    | 5         | 0.58%   |
| 4.4     | 5         | 0.58%   |
| 4.19    | 5         | 0.58%   |
| 5.9     | 4         | 0.46%   |
| 4.9     | 4         | 0.46%   |
| 5.7     | 2         | 0.23%   |
| 3.10    | 2         | 0.23%   |
| 6.13    | 1         | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 754       | 96.3%   |
| i686   | 29        | 3.7%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 317       | 39.67%  |
| KDE5          | 201       | 25.16%  |
| Unknown       | 75        | 9.39%   |
| XFCE          | 61        | 7.63%   |
| X-Cinnamon    | 35        | 4.38%   |
| LXQt          | 17        | 2.13%   |
| MATE          | 14        | 1.75%   |
| sway          | 11        | 1.38%   |
| KDE           | 9         | 1.13%   |
| Cinnamon      | 8         | 1%      |
| Unity         | 7         | 0.88%   |
| LXDE          | 6         | 0.75%   |
| KDE6          | 6         | 0.75%   |
| i3            | 6         | 0.75%   |
| Hyprland      | 4         | 0.5%    |
| Budgie        | 4         | 0.5%    |
| Pantheon      | 3         | 0.38%   |
| Deepin        | 3         | 0.38%   |
| icewm         | 2         | 0.25%   |
| GNOME Classic | 2         | 0.25%   |
| awesome       | 2         | 0.25%   |
| XSession      | 1         | 0.13%   |
| xmonad        | 1         | 0.13%   |
| Trinity       | 1         | 0.13%   |
| KDE4          | 1         | 0.13%   |
| JWM           | 1         | 0.13%   |
| dwm           | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 555       | 69.03%  |
| Wayland | 199       | 24.75%  |
| Unknown | 34        | 4.23%   |
| Tty     | 16        | 1.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 302       | 37.47%  |
| SDDM    | 222       | 27.54%  |
| GDM     | 95        | 11.79%  |
| GDM3    | 91        | 11.29%  |
| LightDM | 67        | 8.31%   |
| TDM     | 15        | 1.86%   |
| XDM     | 5         | 0.62%   |
| GREETD  | 4         | 0.5%    |
| LXDM    | 2         | 0.25%   |
| SLIMSKI | 1         | 0.12%   |
| KDM     | 1         | 0.12%   |
| EMPTTY  | 1         | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Notebooks | Percent |
|------------|-----------|---------|
| en_US      | 345       | 42.86%  |
| ja_JP      | 283       | 35.16%  |
| Unknown    | 63        | 7.83%   |
| zh_CN      | 25        | 3.11%   |
| en_GB      | 22        | 2.73%   |
| pt_BR      | 16        | 1.99%   |
| C          | 13        | 1.61%   |
| fr_FR      | 11        | 1.37%   |
| es_ES      | 3         | 0.37%   |
| zh_TW      | 2         | 0.25%   |
| UTF-8      | 2         | 0.25%   |
| ru_RU      | 2         | 0.25%   |
| en_AU      | 2         | 0.25%   |
| sv_SE      | 1         | 0.12%   |
| sr_RS      | 1         | 0.12%   |
| sk_SK      | 1         | 0.12%   |
| pl_PL      | 1         | 0.12%   |
| nb_NO      | 1         | 0.12%   |
| ja_JP.UTF8 | 1         | 0.12%   |
| fi_FI      | 1         | 0.12%   |
| es_GT      | 1         | 0.12%   |
| en_SG      | 1         | 0.12%   |
| en_PH      | 1         | 0.12%   |
| en_NL      | 1         | 0.12%   |
| en_IN      | 1         | 0.12%   |
| en_DK      | 1         | 0.12%   |
| en_CA      | 1         | 0.12%   |
| en_AG      | 1         | 0.12%   |
| el_GR      | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 428       | 53.7%   |
| BIOS | 369       | 46.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 565       | 70.45%  |
| Overlay | 90        | 11.22%  |
| Btrfs   | 90        | 11.22%  |
| Tmpfs   | 30        | 3.74%   |
| Xfs     | 11        | 1.37%   |
| Unknown | 9         | 1.12%   |
| Zfs     | 3         | 0.37%   |
| F2fs    | 2         | 0.25%   |
| Ntfs    | 1         | 0.12%   |
| Ext2    | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 412       | 50.99%  |
| Unknown | 309       | 38.24%  |
| MBR     | 87        | 10.77%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 627       | 78.28%  |
| Yes       | 174       | 21.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 577       | 72.85%  |
| Yes       | 215       | 27.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Lenovo                     | 152       | 19.41%  |
| Toshiba                    | 85        | 10.86%  |
| Dell                       | 85        | 10.86%  |
| Hewlett-Packard            | 66        | 8.43%   |
| ASUSTek Computer           | 56        | 7.15%   |
| Fujitsu                    | 54        | 6.9%    |
| NEC Computers              | 44        | 5.62%   |
| Apple                      | 43        | 5.49%   |
| Panasonic                  | 22        | 2.81%   |
| Sony                       | 20        | 2.55%   |
| Acer                       | 20        | 2.55%   |
| MSI                        | 14        | 1.79%   |
| MouseComputer              | 12        | 1.53%   |
| HUAWEI                     | 11        | 1.4%    |
| Valve                      | 8         | 1.02%   |
| Unknown                    | 7         | 0.89%   |
| Dynabook                   | 6         | 0.77%   |
| Alienware                  | 6         | 0.77%   |
| Timi                       | 5         | 0.64%   |
| Google                     | 5         | 0.64%   |
| Novastar                   | 4         | 0.51%   |
| Gateway                    | 4         | 0.51%   |
| Thirdwave                  | 3         | 0.38%   |
| System76                   | 3         | 0.38%   |
| Samsung Electronics        | 3         | 0.38%   |
| Notebook                   | 3         | 0.38%   |
| EPSON DIRECT               | 3         | 0.38%   |
| UNITCOM                    | 2         | 0.26%   |
| SLIMBOOK                   | 2         | 0.26%   |
| KOUZIRO                    | 2         | 0.26%   |
| Intel Client Systems       | 2         | 0.26%   |
| Intel                      | 2         | 0.26%   |
| HONOR                      | 2         | 0.26%   |
| Hampoo                     | 2         | 0.26%   |
| Framework                  | 2         | 0.26%   |
| Chuwi                      | 2         | 0.26%   |
| UNICOMPUTE                 | 1         | 0.13%   |
| TUXEDO                     | 1         | 0.13%   |
| Teclast                    | 1         | 0.13%   |
| ShenZhen ZhiWei Technology | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Toshiba dynabook T653/46JR                  | 24        | 3.07%   |
| Valve Jupiter                               | 8         | 1.02%   |
| Apple MacBookAir9,1                         | 8         | 1.02%   |
| Unknown                                     | 7         | 0.89%   |
| Toshiba dynabook Satellite B552/G           | 5         | 0.64%   |
| Apple MacBookPro9,2                         | 5         | 0.64%   |
| Novastar KL55                               | 4         | 0.51%   |
| Lenovo G570 4334                            | 4         | 0.51%   |
| Toshiba dynabook Satellite B552/H           | 3         | 0.38%   |
| Lenovo G550 2958                            | 3         | 0.38%   |
| HP Notebook                                 | 3         | 0.38%   |
| Dell Inspiron 1545                          | 3         | 0.38%   |
| Dell Inspiron 14 5420                       | 3         | 0.38%   |
| Apple MacBookPro15,1                        | 3         | 0.38%   |
| Apple MacBookPro11,5                        | 3         | 0.38%   |
| Toshiba dynabook R732/G                     | 2         | 0.26%   |
| Toshiba dynabook R73/BN                     | 2         | 0.26%   |
| Timi RedmiBook Pro 14S                      | 2         | 0.26%   |
| System76 Lemur Pro                          | 2         | 0.26%   |
| Panasonic CFSZ6-2                           | 2         | 0.26%   |
| Panasonic CFSZ5-3                           | 2         | 0.26%   |
| Panasonic CF-S10EYADR                       | 2         | 0.26%   |
| MSI Prestige 13 AI+ Evo A2VMG               | 2         | 0.26%   |
| Lenovo ThinkPad X230 2330A17                | 2         | 0.26%   |
| Lenovo ThinkPad X230 2325SSF                | 2         | 0.26%   |
| Lenovo ThinkPad X1 Carbon Gen 12 21KCCTO1WW | 2         | 0.26%   |
| Lenovo IdeaPad 300-15IBR 80M3               | 2         | 0.26%   |
| Lenovo G500 20236                           | 2         | 0.26%   |
| Lenovo G50-70 20351                         | 2         | 0.26%   |
| KOUZIRO KOUZIRONB                           | 2         | 0.26%   |
| HP ProBook 6570b                            | 2         | 0.26%   |
| HP ProBook 6560b                            | 2         | 0.26%   |
| HP ProBook 6550b                            | 2         | 0.26%   |
| HP ProBook 4525s                            | 2         | 0.26%   |
| HP Pavilion Laptop 15-eh1xxx                | 2         | 0.26%   |
| HP Pavilion Gaming Laptop 15-ec2xxx         | 2         | 0.26%   |
| HP Pavilion dv7                             | 2         | 0.26%   |
| HP Pavilion dv6                             | 2         | 0.26%   |
| HP Pavilion dv4                             | 2         | 0.26%   |
| HP Laptop 15-db0xxx                         | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 104       | 13.28%  |
| Toshiba dynabook      | 82        | 10.47%  |
| Dell Inspiron         | 42        | 5.36%   |
| Dell Latitude         | 18        | 2.3%    |
| HP ProBook            | 17        | 2.17%   |
| HP Pavilion           | 14        | 1.79%   |
| Acer Aspire           | 13        | 1.66%   |
| Dell XPS              | 12        | 1.53%   |
| Lenovo IdeaPad        | 10        | 1.28%   |
| ASUS VivoBook         | 10        | 1.28%   |
| HP EliteBook          | 9         | 1.15%   |
| ASUS ROG              | 9         | 1.15%   |
| Valve Jupiter         | 8         | 1.02%   |
| HP Laptop             | 8         | 1.02%   |
| Apple MacBookAir9     | 8         | 1.02%   |
| Lenovo ThinkBook      | 7         | 0.89%   |
| Unknown               | 7         | 0.89%   |
| Apple MacBookPro11    | 6         | 0.77%   |
| ASUS Zenbook          | 5         | 0.64%   |
| ASUS ASUS             | 5         | 0.64%   |
| Apple MacBookPro9     | 5         | 0.64%   |
| Apple MacBookPro15    | 5         | 0.64%   |
| Novastar KL55         | 4         | 0.51%   |
| Lenovo Yoga           | 4         | 0.51%   |
| Lenovo G570           | 4         | 0.51%   |
| HP ENVY               | 4         | 0.51%   |
| Timi RedmiBook        | 3         | 0.38%   |
| MSI Prestige          | 3         | 0.38%   |
| Lenovo Legion         | 3         | 0.38%   |
| Lenovo G550           | 3         | 0.38%   |
| HP Notebook           | 3         | 0.38%   |
| EPSON DIRECT Endeavor | 3         | 0.38%   |
| Dell Vostro           | 3         | 0.38%   |
| Dell G3               | 3         | 0.38%   |
| Apple MacBookPro16    | 3         | 0.38%   |
| Alienware 17          | 3         | 0.38%   |
| Acer Predator         | 3         | 0.38%   |
| Toshiba PORTEGE       | 2         | 0.26%   |
| System76 Lemur        | 2         | 0.26%   |
| Panasonic CFSZ6-2     | 2         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2013    | 73        | 9.32%   |
| 2018    | 69        | 8.81%   |
| 2012    | 64        | 8.17%   |
| 2021    | 63        | 8.05%   |
| 2011    | 60        | 7.66%   |
| 2020    | 52        | 6.64%   |
| 2019    | 50        | 6.39%   |
| 2010    | 41        | 5.24%   |
| 2008    | 40        | 5.11%   |
| 2016    | 35        | 4.47%   |
| 2023    | 34        | 4.34%   |
| 2017    | 34        | 4.34%   |
| 2022    | 31        | 3.96%   |
| 2015    | 31        | 3.96%   |
| 2009    | 31        | 3.96%   |
| 2007    | 28        | 3.58%   |
| 2014    | 23        | 2.94%   |
| 2024    | 13        | 1.66%   |
| 2006    | 8         | 1.02%   |
| 2005    | 1         | 0.13%   |
| 2004    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 783       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 713       | 89.91%  |
| Enabled  | 80        | 10.09%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 774       | 98.85%  |
| Yes  | 9         | 1.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 221       | 27.97%  |
| 3.01-4.0    | 191       | 24.18%  |
| 8.01-16.0   | 131       | 16.58%  |
| 16.01-24.0  | 112       | 14.18%  |
| 32.01-64.0  | 48        | 6.08%   |
| 1.01-2.0    | 38        | 4.81%   |
| 24.01-32.0  | 18        | 2.28%   |
| 64.01-256.0 | 14        | 1.77%   |
| 2.01-3.0    | 11        | 1.39%   |
| 0.51-1.0    | 6         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 341       | 40.4%   |
| 2.01-3.0   | 183       | 21.68%  |
| 4.01-8.0   | 104       | 12.32%  |
| 3.01-4.0   | 97        | 11.49%  |
| 0.51-1.0   | 78        | 9.24%   |
| 8.01-16.0  | 25        | 2.96%   |
| 0.01-0.5   | 12        | 1.42%   |
| 16.01-24.0 | 4         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 592       | 74%     |
| 2      | 178       | 22.25%  |
| 3      | 17        | 2.13%   |
| 0      | 8         | 1%      |
| 4      | 5         | 0.63%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 469       | 59.59%  |
| Yes       | 318       | 40.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 627       | 79.97%  |
| No        | 157       | 20.03%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 752       | 96.04%  |
| No        | 31        | 3.96%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 518       | 65.57%  |
| No        | 272       | 34.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Japan   | 783       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City        | Notebooks | Percent |
|-------------|-----------|---------|
| Tokyo       | 141       | 16.63%  |
| Yokohama    | 47        | 5.54%   |
| Osaka       | 38        | 4.48%   |
| Minato-ku   | 24        | 2.83%   |
| Chiyoda     | 21        | 2.48%   |
| Nagoya      | 15        | 1.77%   |
| Niigata     | 14        | 1.65%   |
| Kyoto       | 14        | 1.65%   |
| Shinjuku    | 12        | 1.42%   |
| Setagaya-ku | 12        | 1.42%   |
| Saitama     | 12        | 1.42%   |
| Shibuya     | 11        | 1.3%    |
| Honcho      | 11        | 1.3%    |
| Shinagawa   | 8         | 0.94%   |
| Miura       | 8         | 0.94%   |
| Sapporo     | 7         | 0.83%   |
| Kobe        | 7         | 0.83%   |
| Adachi      | 7         | 0.83%   |
| Takasago    | 6         | 0.71%   |
| Ōtsu       | 6         | 0.71%   |
| Tsukuba     | 5         | 0.59%   |
| Takamatsu   | 5         | 0.59%   |
| Nakano      | 5         | 0.59%   |
| Machiya     | 5         | 0.59%   |
| Kagoshima   | 5         | 0.59%   |
| Ichikawa    | 5         | 0.59%   |
| Hiratsuka   | 5         | 0.59%   |
| Himeji      | 5         | 0.59%   |
| Umeda       | 4         | 0.47%   |
| Shizuoka    | 4         | 0.47%   |
| Nagasaki    | 4         | 0.47%   |
| Mito        | 4         | 0.47%   |
| Kitakyushu  | 4         | 0.47%   |
| Kawaguchi   | 4         | 0.47%   |
| Hitachi     | 4         | 0.47%   |
| Chiyoda-ku  | 4         | 0.47%   |
| Bunkyo-ku   | 4         | 0.47%   |
| Yamanashi   | 3         | 0.35%   |
| Yamaguchi   | 3         | 0.35%   |
| Yamagata    | 3         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 124       | 163    | 12.89%  |
| Toshiba                     | 115       | 127    | 11.95%  |
| WDC                         | 85        | 95     | 8.84%   |
| Unknown                     | 63        | 80     | 6.55%   |
| Seagate                     | 57        | 79     | 5.93%   |
| SanDisk                     | 51        | 62     | 5.3%    |
| Crucial                     | 39        | 48     | 4.05%   |
| Hitachi                     | 33        | 36     | 3.43%   |
| Micron Technology           | 32        | 47     | 3.33%   |
| Apple                       | 32        | 37     | 3.33%   |
| SK hynix                    | 27        | 29     | 2.81%   |
| Kingston                    | 24        | 26     | 2.49%   |
| Intel                       | 20        | 22     | 2.08%   |
| A-DATA Technology           | 18        | 23     | 1.87%   |
| KIOXIA                      | 17        | 19     | 1.77%   |
| HGST                        | 16        | 18     | 1.66%   |
| SPCC                        | 15        | 19     | 1.56%   |
| Unknown                     | 13        | 14     | 1.35%   |
| SUNEAST                     | 12        | 13     | 1.25%   |
| Fujitsu                     | 9         | 11     | 0.94%   |
| Transcend                   | 8         | 11     | 0.83%   |
| Micron/Crucial Technology   | 7         | 7      | 0.73%   |
| China                       | 7         | 11     | 0.73%   |
| Plextor                     | 6         | 8      | 0.62%   |
| Silicon Motion              | 5         | 5      | 0.52%   |
| JMicron Technology          | 5         | 5      | 0.52%   |
| BUFFALO                     | 5         | 5      | 0.52%   |
| Zheino                      | 4         | 5      | 0.42%   |
| Teclast                     | 4         | 4      | 0.42%   |
| Phison Electronics          | 4         | 6      | 0.42%   |
| MAXIO Technology (Hangzhou) | 4         | 4      | 0.42%   |
| Kingston Technology Company | 4         | 5      | 0.42%   |
| Union Memory (Shenzhen)     | 3         | 3      | 0.31%   |
| SSK                         | 3         | 3      | 0.31%   |
| PNY                         | 3         | 3      | 0.31%   |
| Phison                      | 3         | 3      | 0.31%   |
| Patriot                     | 3         | 4      | 0.31%   |
| Lexar                       | 3         | 4      | 0.31%   |
| KIOXIA-EXCERIA              | 3         | 4      | 0.31%   |
| Green House                 | 3         | 5      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD075 752GB                             | 25        | 2.51%   |
| Unknown MMC Card  64GB                               | 14        | 1.41%   |
| Unknown                                              | 13        | 1.31%   |
| Toshiba MQ01ABD100 1TB                               | 10        | 1%      |
| Crucial CT500MX500SSD1 500GB                         | 10        | 1%      |
| Toshiba MQ01ABF050 500GB                             | 8         | 0.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 8         | 0.8%    |
| Apple SSD AP0256N 256GB                              | 8         | 0.8%    |
| Unknown MMC Card  128GB                              | 7         | 0.7%    |
| Seagate ST1000LM035-1RK172 1TB                       | 7         | 0.7%    |
| Unknown MMC Card  32GB                               | 6         | 0.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 6         | 0.6%    |
| Crucial CT240BX500SSD1 240GB                         | 6         | 0.6%    |
| SPCC Solid State Disk 256GB                          | 5         | 0.5%    |
| Seagate ST9500325AS 500GB                            | 5         | 0.5%    |
| Seagate ST500LT012-1DG142 500GB                      | 5         | 0.5%    |
| Samsung NVMe SSD Drive 256GB                         | 5         | 0.5%    |
| Unknown SD/MMC/MS PRO 128GB                          | 4         | 0.4%    |
| Toshiba MQ01ABD100H 1TB                              | 4         | 0.4%    |
| SanDisk NVMe SSD Drive 1TB                           | 4         | 0.4%    |
| Samsung SSD 860 EVO 500GB                            | 4         | 0.4%    |
| Samsung NVMe SSD Drive 1TB                           | 4         | 0.4%    |
| Phison PS5013 E13 NVMe Controller 512GB              | 4         | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                | 4         | 0.4%    |
| Micron 3400_MTFDKBA1T0TFH 1TB                        | 4         | 0.4%    |
| Kingston RBUSNS4180S3256GJ 256GB SSD                 | 4         | 0.4%    |
| WDC WDS500G2B0B-00YS70 500GB SSD                     | 3         | 0.3%    |
| WDC WD5000LPVX-08V0TT5 500GB                         | 3         | 0.3%    |
| WDC WD1600BEVT-22ZCT0 160GB                          | 3         | 0.3%    |
| Unknown NVMe SSD Drive 512GB                         | 3         | 0.3%    |
| Unknown ASP550SS7-240GM-MI-B 240GB SSD               | 3         | 0.3%    |
| Toshiba THNSNJ128GCSU 128GB SSD                      | 3         | 0.3%    |
| Toshiba MQ01ABF032 320GB                             | 3         | 0.3%    |
| Toshiba MQ01ABD050 500GB                             | 3         | 0.3%    |
| Toshiba MK7575GSX 752GB                              | 3         | 0.3%    |
| SUNEAST SSD SE800 512GB                              | 3         | 0.3%    |
| SSK Disk 1TB                                         | 3         | 0.3%    |
| SPCC Solid State Disk 128GB                          | 3         | 0.3%    |
| SK hynix HFM001TD3JX013N 1024GB                      | 3         | 0.3%    |
| Seagate ST500LM012 HN-M500MBB 500GB                  | 3         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 88        | 93     | 32.12%  |
| WDC                 | 61        | 67     | 22.26%  |
| Seagate             | 54        | 76     | 19.71%  |
| Hitachi             | 31        | 34     | 11.31%  |
| HGST                | 16        | 18     | 5.84%   |
| Fujitsu             | 9         | 11     | 3.28%   |
| Unknown             | 4         | 6      | 1.46%   |
| JMicron Technology  | 3         | 3      | 1.09%   |
| QC-FT-D             | 2         | 2      | 0.73%   |
| USB                 | 1         | 1      | 0.36%   |
| Samsung Electronics | 1         | 3      | 0.36%   |
| SABRENT             | 1         | 1      | 0.36%   |
| MARSHAL             | 1         | 2      | 0.36%   |
| ASMT                | 1         | 1      | 0.36%   |
| Apple               | 1         | 1      | 0.36%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 49        | 68     | 14.85%  |
| Crucial             | 38        | 47     | 11.52%  |
| SanDisk             | 24        | 31     | 7.27%   |
| A-DATA Technology   | 17        | 22     | 5.15%   |
| WDC                 | 16        | 18     | 4.85%   |
| Toshiba             | 16        | 20     | 4.85%   |
| Kingston            | 16        | 17     | 4.85%   |
| SPCC                | 13        | 16     | 3.94%   |
| SUNEAST             | 11        | 12     | 3.33%   |
| Apple               | 11        | 11     | 3.33%   |
| Micron Technology   | 9         | 11     | 2.73%   |
| Intel               | 8         | 8      | 2.42%   |
| Transcend           | 7         | 10     | 2.12%   |
| China               | 7         | 11     | 2.12%   |
| Plextor             | 6         | 8      | 1.82%   |
| Unknown             | 6         | 6      | 1.82%   |
| Unknown             | 5         | 5      | 1.52%   |
| BUFFALO             | 5         | 5      | 1.52%   |
| SK hynix            | 4         | 4      | 1.21%   |
| Teclast             | 3         | 3      | 0.91%   |
| Seagate             | 3         | 3      | 0.91%   |
| PNY                 | 3         | 3      | 0.91%   |
| Lexar               | 3         | 4      | 0.91%   |
| Green House         | 3         | 5      | 0.91%   |
| Dogfish             | 3         | 4      | 0.91%   |
| Zheino              | 2         | 2      | 0.61%   |
| Team                | 2         | 3      | 0.61%   |
| Patriot             | 2         | 3      | 0.61%   |
| OCZ                 | 2         | 2      | 0.61%   |
| Netac               | 2         | 2      | 0.61%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.61%   |
| Hitachi             | 2         | 2      | 0.61%   |
| CFD                 | 2         | 2      | 0.61%   |
| Apacer              | 2         | 4      | 0.61%   |
| TCSUNBOW            | 1         | 1      | 0.3%    |
| StoreJet            | 1         | 1      | 0.3%    |
| SC-M280             | 1         | 1      | 0.3%    |
| RX7                 | 1         | 1      | 0.3%    |
| Ramaxel Technology  | 1         | 1      | 0.3%    |
| OASDX               | 1         | 2      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 301       | 406    | 33.52%  |
| HDD     | 264       | 319    | 29.4%   |
| NVMe    | 257       | 337    | 28.62%  |
| MMC     | 58        | 76     | 6.46%   |
| Unknown | 18        | 18     | 2%      |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 520       | 691    | 58.89%  |
| NVMe | 255       | 332    | 28.88%  |
| MMC  | 58        | 76     | 6.57%   |
| SAS  | 50        | 57     | 5.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 418       | 552    | 75.18%  |
| 0.51-1.0   | 122       | 155    | 21.94%  |
| 1.01-2.0   | 14        | 16     | 2.52%   |
| 3.01-4.0   | 1         | 1      | 0.18%   |
| 10.01-20.0 | 1         | 1      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 280       | 33.9%   |
| 251-500        | 149       | 18.04%  |
| 501-1000       | 107       | 12.95%  |
| 1-20           | 83        | 10.05%  |
| 51-100         | 73        | 8.84%   |
| 21-50          | 39        | 4.72%   |
| 1001-2000      | 37        | 4.48%   |
| Unknown        | 27        | 3.27%   |
| More than 3000 | 17        | 2.06%   |
| 2001-3000      | 14        | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 404       | 47.87%  |
| 21-50          | 141       | 16.71%  |
| 51-100         | 87        | 10.31%  |
| 101-250        | 83        | 9.83%   |
| 251-500        | 55        | 6.52%   |
| 501-1000       | 31        | 3.67%   |
| Unknown        | 27        | 3.2%    |
| 1001-2000      | 8         | 0.95%   |
| 2001-3000      | 5         | 0.59%   |
| More than 3000 | 3         | 0.36%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABD075 752GB                         | 24        | 24     | 33.8%   |
| Seagate ST9500325AS 500GB                        | 3         | 3      | 4.23%   |
| Seagate ST9160314AS 160GB                        | 2         | 2      | 2.82%   |
| HGST HTS541075A9E680 752GB                       | 2         | 3      | 2.82%   |
| WDC WD5000BEVT-55A0RT0 500GB                     | 1         | 1      | 1.41%   |
| WDC WD3200BEVT-08A23T1 320GB                     | 1         | 1      | 1.41%   |
| WDC WD1600BEVS-26RST0 160GB                      | 1         | 1      | 1.41%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 1.41%   |
| Toshiba MK5055GSX 500GB                          | 1         | 1      | 1.41%   |
| Toshiba MK2561GSYN 250GB                         | 1         | 1      | 1.41%   |
| Toshiba MK2555GSX 250GB                          | 1         | 1      | 1.41%   |
| Toshiba MK2552GSX 250GB                          | 1         | 1      | 1.41%   |
| Toshiba MK1652GSX 160GB                          | 1         | 1      | 1.41%   |
| Toshiba MK1255GSX H 120GB                        | 1         | 1      | 1.41%   |
| Teclast 240GB SSD                                | 1         | 1      | 1.41%   |
| Teclast 128GB SSD                                | 1         | 1      | 1.41%   |
| SSSTC CL1-4D128 128GB                            | 1         | 1      | 1.41%   |
| Seagate ST9120817AS 120GB                        | 1         | 1      | 1.41%   |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 1.41%   |
| Seagate ST500LM021-1KJ152 500GB                  | 1         | 1      | 1.41%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 1.41%   |
| SanDisk SSD PLUS 1000GB                          | 1         | 2      | 1.41%   |
| SanDisk SSD P4 64GB                              | 1         | 1      | 1.41%   |
| SanDisk SSD P4 32GB                              | 1         | 1      | 1.41%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.41%   |
| Samsung Electronics HM641JI 640GB                | 1         | 2      | 1.41%   |
| Netac SSD 240GB                                  | 1         | 1      | 1.41%   |
| Micron Technology MTFDDAK128MAM-1J1 128GB SSD    | 1         | 1      | 1.41%   |
| MARSHAL MAL2020SA 80 20GB                        | 1         | 1      | 1.41%   |
| LITEON CV8-8E128-HP 128GB SSD                    | 1         | 4      | 1.41%   |
| Lite-On PH3-CE240 240GB SSD                      | 1         | 1      | 1.41%   |
| Kingston RBUSNS4180DS3128GH 128GB SSD            | 1         | 1      | 1.41%   |
| Intel SSDSA1M160G2HP 160GB                       | 1         | 1      | 1.41%   |
| Hitachi HTS723232L9A360 320GB                    | 1         | 1      | 1.41%   |
| Hitachi HTS723232A7A364 320GB                    | 1         | 1      | 1.41%   |
| Hitachi HTS545050B9A300 500GB                    | 1         | 1      | 1.41%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 1.41%   |
| Hitachi HTS545025B9SA02 250GB                    | 1         | 1      | 1.41%   |
| HGST HTS545050A7E380 500GB                       | 1         | 1      | 1.41%   |
| Crucial M4-CT256M4SSD2 256GB                     | 1         | 1      | 1.41%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 31        | 31     | 43.66%  |
| Seagate             | 9         | 9      | 12.68%  |
| Hitachi             | 5         | 5      | 7.04%   |
| Crucial             | 4         | 6      | 5.63%   |
| WDC                 | 3         | 3      | 4.23%   |
| SanDisk             | 3         | 4      | 4.23%   |
| HGST                | 3         | 4      | 4.23%   |
| Teclast             | 2         | 2      | 2.82%   |
| Samsung Electronics | 2         | 3      | 2.82%   |
| SSSTC               | 1         | 1      | 1.41%   |
| Netac               | 1         | 1      | 1.41%   |
| Micron Technology   | 1         | 1      | 1.41%   |
| MARSHAL             | 1         | 1      | 1.41%   |
| LITEON              | 1         | 4      | 1.41%   |
| Lite-On             | 1         | 1      | 1.41%   |
| Kingston            | 1         | 1      | 1.41%   |
| Intel               | 1         | 1      | 1.41%   |
| A-DATA Technology   | 1         | 1      | 1.41%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 31        | 31     | 58.49%  |
| Seagate             | 9         | 9      | 16.98%  |
| Hitachi             | 5         | 5      | 9.43%   |
| WDC                 | 3         | 3      | 5.66%   |
| HGST                | 3         | 4      | 5.66%   |
| Samsung Electronics | 1         | 2      | 1.89%   |
| MARSHAL             | 1         | 1      | 1.89%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 53        | 55     | 74.65%  |
| SSD  | 17        | 23     | 23.94%  |
| NVMe | 1         | 1      | 1.41%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 408       | 588    | 48.17%  |
| Works    | 368       | 488    | 43.45%  |
| Malfunc  | 70        | 79     | 8.26%   |
| Failed   | 1         | 1      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 533       | 60.57%  |
| Samsung Electronics                     | 86        | 9.77%   |
| AMD                                     | 65        | 7.39%   |
| SanDisk                                 | 32        | 3.64%   |
| SK hynix                                | 24        | 2.73%   |
| Micron Technology                       | 24        | 2.73%   |
| Apple                                   | 20        | 2.27%   |
| KIOXIA                                  | 19        | 2.16%   |
| Kingston Technology Company             | 12        | 1.36%   |
| Toshiba America Info Systems            | 10        | 1.14%   |
| Silicon Motion                          | 9         | 1.02%   |
| Phison Electronics                      | 9         | 1.02%   |
| Micron/Crucial Technology               | 7         | 0.8%    |
| MAXIO Technology (Hangzhou)             | 7         | 0.8%    |
| Nvidia                                  | 4         | 0.45%   |
| Solid State Storage Technology          | 3         | 0.34%   |
| Shenzhen Unionmemory Information System | 3         | 0.34%   |
| ADATA Technology                        | 3         | 0.34%   |
| Yangtze Memory Technologies             | 2         | 0.23%   |
| VIA Technologies                        | 1         | 0.11%   |
| Shenzhen Longsys Electronics            | 1         | 0.11%   |
| Seagate Technology                      | 1         | 0.11%   |
| Realtek Semiconductor                   | 1         | 0.11%   |
| O2 Micro                                | 1         | 0.11%   |
| Marvell Technology Group                | 1         | 0.11%   |
| INNOGRIT                                | 1         | 0.11%   |
| Unknown                                 | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 106       | 11.24%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 58        | 6.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 58        | 6.15%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 49        | 5.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 35        | 3.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 29        | 3.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 29        | 3.08%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 26        | 2.76%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 23        | 2.44%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 22        | 2.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 21        | 2.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 19        | 2.01%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17        | 1.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 1.8%    |
| Apple ANS2 NVMe Controller                                                       | 17        | 1.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 1.7%    |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 1.59%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 13        | 1.38%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 13        | 1.38%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 12        | 1.27%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 12        | 1.27%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 10        | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 9         | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                            | 8         | 0.85%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                       | 7         | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 7         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 0.74%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 7         | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 6         | 0.64%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD          | 6         | 0.64%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 6         | 0.64%   |
| Micron 3400 NVMe SSD [Hendrix]                                                   | 6         | 0.64%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation            | 6         | 0.64%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 5         | 0.53%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 5         | 0.53%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                         | 5         | 0.53%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 5         | 0.53%   |
| Intel SSD 660P Series                                                            | 5         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 527       | 58.75%  |
| NVMe | 256       | 28.54%  |
| IDE  | 65        | 7.25%   |
| RAID | 49        | 5.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 660       | 84.29%  |
| AMD          | 122       | 15.58%  |
| CentaurHauls | 1         | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Celeron CPU 847 @ 1.10GHz         | 24        | 3.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 20        | 2.55%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 13        | 1.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 10        | 1.28%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 10        | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 10        | 1.28%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 10        | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 10        | 1.28%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 9         | 1.15%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 1.15%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 9         | 1.15%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 9         | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 8         | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 8         | 1.02%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 8         | 1.02%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 8         | 1.02%   |
| Intel Core i3-1000NG4 CPU @ 1.10GHz     | 8         | 1.02%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz    | 8         | 1.02%   |
| AMD Custom APU 0405                     | 8         | 1.02%   |
| Intel Core i5-2410M CPU @ 2.30GHz       | 7         | 0.89%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 7         | 0.89%   |
| Intel Core i7-3520M CPU @ 2.90GHz       | 6         | 0.77%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 6         | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 6         | 0.77%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 6         | 0.77%   |
| Intel Core i5-2540M CPU @ 2.60GHz       | 6         | 0.77%   |
| Intel Core i5-2430M CPU @ 2.40GHz       | 6         | 0.77%   |
| Intel Core i5 CPU M 560 @ 2.67GHz       | 6         | 0.77%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 6         | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 6         | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 5         | 0.64%   |
| Intel Core i7-5500U CPU @ 2.40GHz       | 5         | 0.64%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 5         | 0.64%   |
| Intel Core i3-4000M CPU @ 2.40GHz       | 5         | 0.64%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 5         | 0.64%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 5         | 0.64%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 5         | 0.64%   |
| Intel Atom CPU N270 @ 1.60GHz           | 5         | 0.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 5         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 222       | 28.35%  |
| Intel Core i7           | 124       | 15.84%  |
| Intel Celeron           | 86        | 10.98%  |
| Other                   | 67        | 8.56%   |
| Intel Core i3           | 60        | 7.66%   |
| Intel Core 2 Duo        | 45        | 5.75%   |
| AMD Ryzen 7             | 30        | 3.83%   |
| AMD Ryzen 5             | 26        | 3.32%   |
| Intel Atom              | 19        | 2.43%   |
| Intel Core              | 8         | 1.02%   |
| AMD Ryzen 7 PRO         | 8         | 1.02%   |
| Intel Pentium           | 7         | 0.89%   |
| Intel Core 2            | 7         | 0.89%   |
| AMD Ryzen 9             | 6         | 0.77%   |
| AMD Ryzen 3             | 6         | 0.77%   |
| Intel Celeron M         | 5         | 0.64%   |
| AMD E2                  | 5         | 0.64%   |
| Intel Core i9           | 4         | 0.51%   |
| Intel Celeron Dual-Core | 4         | 0.51%   |
| AMD A6                  | 4         | 0.51%   |
| Intel Genuine           | 3         | 0.38%   |
| AMD E1                  | 3         | 0.38%   |
| AMD Athlon              | 3         | 0.38%   |
| Intel Pentium M         | 2         | 0.26%   |
| Intel Pentium Dual-Core | 2         | 0.26%   |
| Intel Core M            | 2         | 0.26%   |
| AMD Turion 64 X2 Mobile | 2         | 0.26%   |
| AMD Ryzen 5 PRO         | 2         | 0.26%   |
| AMD Mobile Sempron      | 2         | 0.26%   |
| AMD Athlon II           | 2         | 0.26%   |
| Intel Core m5           | 1         | 0.13%   |
| Intel Core m3           | 1         | 0.13%   |
| Intel Core 2 Extreme    | 1         | 0.13%   |
| CentaurHauls VIA C7     | 1         | 0.13%   |
| AMD V140                | 1         | 0.13%   |
| AMD V120                | 1         | 0.13%   |
| AMD Turion Neo X2       | 1         | 0.13%   |
| AMD Sempron             | 1         | 0.13%   |
| AMD Ryzen 3 PRO         | 1         | 0.13%   |
| AMD Quad-Core           | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 442       | 56.45%  |
| 4      | 176       | 22.48%  |
| 8      | 53        | 6.77%   |
| 6      | 48        | 6.13%   |
| 1      | 29        | 3.7%    |
| 12     | 11        | 1.4%    |
| 14     | 10        | 1.28%   |
| 10     | 7         | 0.89%   |
| 16     | 5         | 0.64%   |
| 24     | 2         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 783       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 559       | 71.39%  |
| 1      | 224       | 28.61%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 761       | 97.19%  |
| 32-bit         | 16        | 2.04%   |
| Unknown        | 6         | 0.77%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 315       | 38.89%  |
| 0x206a7    | 68        | 8.4%    |
| 0x306a9    | 52        | 6.42%   |
| 0x1067a    | 25        | 3.09%   |
| 0x306d4    | 21        | 2.59%   |
| 0x20655    | 20        | 2.47%   |
| 0x806ec    | 19        | 2.35%   |
| 0x806ea    | 16        | 1.98%   |
| 0x306c3    | 15        | 1.85%   |
| 0x806e9    | 13        | 1.6%    |
| 0x40651    | 13        | 1.6%    |
| 0x0a50000c | 12        | 1.48%   |
| 0xa0652    | 11        | 1.36%   |
| 0x806c1    | 11        | 1.36%   |
| 0x10676    | 11        | 1.36%   |
| 0x406e3    | 10        | 1.23%   |
| 0x20652    | 10        | 1.23%   |
| 0x406c4    | 8         | 0.99%   |
| 0x906ea    | 7         | 0.86%   |
| 0x806eb    | 7         | 0.86%   |
| 0x106c2    | 7         | 0.86%   |
| 0x08600106 | 7         | 0.86%   |
| 0x08108102 | 7         | 0.86%   |
| 0x906a3    | 6         | 0.74%   |
| 0x6f6      | 6         | 0.74%   |
| 0x406c3    | 6         | 0.74%   |
| 0x08108109 | 6         | 0.74%   |
| 0x506c9    | 5         | 0.62%   |
| 0x30678    | 5         | 0.62%   |
| 0x08608103 | 5         | 0.62%   |
| 0x010000c8 | 5         | 0.62%   |
| 0x6fd      | 4         | 0.49%   |
| 0x6e8      | 4         | 0.49%   |
| 0x506e3    | 4         | 0.49%   |
| 0x0a50000d | 4         | 0.49%   |
| 0x906e9    | 3         | 0.37%   |
| 0x806d1    | 3         | 0.37%   |
| 0x706a8    | 3         | 0.37%   |
| 0x6d8      | 3         | 0.37%   |
| 0x40661    | 3         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 119       | 15.18%  |
| SandyBridge       | 95        | 12.12%  |
| IvyBridge         | 77        | 9.82%   |
| Haswell           | 54        | 6.89%   |
| Penryn            | 49        | 6.25%   |
| Unknown           | 45        | 5.74%   |
| Westmere          | 40        | 5.1%    |
| Skylake           | 30        | 3.83%   |
| Broadwell         | 27        | 3.44%   |
| Zen 3             | 26        | 3.32%   |
| Silvermont        | 24        | 3.06%   |
| TigerLake         | 22        | 2.81%   |
| Alderlake Hybrid  | 21        | 2.68%   |
| Core              | 19        | 2.42%   |
| Zen+              | 16        | 2.04%   |
| Zen 2             | 16        | 2.04%   |
| CometLake         | 16        | 2.04%   |
| Icelake           | 15        | 1.91%   |
| Bonnell           | 9         | 1.15%   |
| P6                | 8         | 1.02%   |
| Goldmont          | 7         | 0.89%   |
| K8 Hammer         | 6         | 0.77%   |
| Goldmont plus     | 6         | 0.77%   |
| Puma              | 5         | 0.64%   |
| Meteorlake Hybrid | 5         | 0.64%   |
| K10               | 5         | 0.64%   |
| Zen               | 4         | 0.51%   |
| Jaguar            | 3         | 0.38%   |
| Bobcat            | 3         | 0.38%   |
| Piledriver        | 2         | 0.26%   |
| Nehalem           | 2         | 0.26%   |
| K8 & K10 hybrid   | 2         | 0.26%   |
| K10 Llano         | 2         | 0.26%   |
| Excavator         | 2         | 0.26%   |
| Lunarlake Hybrid  | 1         | 0.13%   |
| Gracemont         | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 637       | 71.25%  |
| AMD              | 144       | 16.11%  |
| Nvidia           | 112       | 12.53%  |
| VIA Technologies | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 94        | 10.03%  |
| Intel 3rd Gen Core processor Graphics Controller                                         | 77        | 8.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 4.16%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 38        | 4.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 2.56%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 2.56%   |
| Intel HD Graphics 620                                                                    | 23        | 2.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 2.45%   |
| Intel UHD Graphics 620                                                                   | 22        | 2.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 2.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 2.03%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 18        | 1.92%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 18        | 1.92%   |
| Intel HD Graphics 5500                                                                   | 17        | 1.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 1.81%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 15        | 1.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 15        | 1.6%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 1.6%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 15        | 1.6%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 13        | 1.39%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 12        | 1.28%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 12        | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.07%   |
| AMD Lucienne                                                                             | 10        | 1.07%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 8         | 0.85%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 8         | 0.85%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 7         | 0.75%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 7         | 0.75%   |
| Intel HD Graphics 500                                                                    | 7         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 0.75%   |
| AMD Barcelo                                                                              | 7         | 0.75%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 6         | 0.64%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.64%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.64%   |
| AMD Rembrandt [Radeon 680M]                                                              | 6         | 0.64%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.53%   |
| Nvidia GP108M [GeForce MX150]                                                            | 5         | 0.53%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 5         | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 528       | 67.18%  |
| 1 x AMD        | 108       | 13.74%  |
| Intel + Nvidia | 81        | 10.31%  |
| 1 x Nvidia     | 17        | 2.16%   |
| 2 x Intel      | 14        | 1.78%   |
| AMD + Nvidia   | 14        | 1.78%   |
| Intel + AMD    | 13        | 1.65%   |
| 2 x AMD        | 8         | 1.02%   |
| Other          | 2         | 0.25%   |
| 1 x VIA        | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 691       | 88.14%  |
| Proprietary | 61        | 7.78%   |
| Unknown     | 32        | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 597       | 75.38%  |
| 0.01-0.5   | 73        | 9.22%   |
| 1.01-2.0   | 56        | 7.07%   |
| 3.01-4.0   | 27        | 3.41%   |
| 0.51-1.0   | 22        | 2.78%   |
| 7.01-8.0   | 7         | 0.88%   |
| 5.01-6.0   | 7         | 0.88%   |
| 8.01-16.0  | 3         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 154       | 19.95%  |
| AU Optronics            | 127       | 16.45%  |
| Samsung Electronics     | 77        | 9.97%   |
| BOE                     | 72        | 9.33%   |
| Chimei Innolux          | 71        | 9.2%    |
| Apple                   | 40        | 5.18%   |
| Sharp                   | 36        | 4.66%   |
| Chi Mei Optoelectronics | 26        | 3.37%   |
| Lenovo                  | 21        | 2.72%   |
| PANDA                   | 13        | 1.68%   |
| Dell                    | 13        | 1.68%   |
| Goldstar                | 9         | 1.17%   |
| Valve                   | 8         | 1.04%   |
| Panasonic               | 8         | 1.04%   |
| InfoVision              | 7         | 0.91%   |
| Toshiba                 | 5         | 0.65%   |
| Philips                 | 5         | 0.65%   |
| CSO                     | 5         | 0.65%   |
| CPT                     | 5         | 0.65%   |
| Acer                    | 5         | 0.65%   |
| Sony                    | 4         | 0.52%   |
| NOV                     | 4         | 0.52%   |
| Mitsubishi              | 4         | 0.52%   |
| Hewlett-Packard         | 4         | 0.52%   |
| BenQ                    | 4         | 0.52%   |
| ASUSTek Computer        | 4         | 0.52%   |
| Ancor Communications    | 4         | 0.52%   |
| LG Philips              | 3         | 0.39%   |
| Iiyama                  | 3         | 0.39%   |
| TMX                     | 2         | 0.26%   |
| RTK                     | 2         | 0.26%   |
| OOO                     | 2         | 0.26%   |
| IOD                     | 2         | 0.26%   |
| AOC                     | 2         | 0.26%   |
| Unknown                 | 2         | 0.26%   |
| Yamaha                  | 1         | 0.13%   |
| SLD                     | 1         | 0.13%   |
| Sceptre Tech            | 1         | 0.13%   |
| SAC                     | 1         | 0.13%   |
| Roku                    | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 24        | 3.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 10        | 1.28%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 9         | 1.15%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 8         | 1.03%   |
| Apple Color LCD APPA041 2560x1600 286x179mm 13.3-inch                    | 8         | 1.03%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.77%   |
| Apple Cinema HD APP9223 1920x1200 495x310mm 23.0-inch                    | 6         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 4         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 0.51%   |
| NOV NOVA HD CARD NOV0405 1920x1080 459x296mm 21.5-inch                   | 4         | 0.51%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 4         | 0.51%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 4         | 0.51%   |
| LG Display LCD Monitor LGD02CB 1366x768 344x194mm 15.5-inch              | 4         | 0.51%   |
| LG Display LCD Monitor LGD01DA 1366x768 294x166mm 13.3-inch              | 4         | 0.51%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                  | 4         | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.51%   |
| AU Optronics LCD Monitor AUO1068 1920x1200 264x166mm 12.3-inch           | 4         | 0.51%   |
| Apple Color LCD APPA02E 2880x1800 331x207mm 15.4-inch                    | 4         | 0.51%   |
| Sharp LCD Monitor SHP14D5 1920x1080 294x165mm 13.3-inch                  | 3         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 3         | 0.38%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD032E 1366x768 345x194mm 15.6-inch              | 3         | 0.38%   |
| LG Display LCD Monitor LGD0171 1366x768 344x194mm 15.5-inch              | 3         | 0.38%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 3         | 0.38%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                  | 3         | 0.38%   |
| Chimei Innolux LCD Monitor CMN1364 1366x768 293x164mm 13.2-inch          | 3         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1680 1366x768 344x193mm 15.5-inch | 3         | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 350x190mm 15.7-inch | 3         | 0.38%   |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                     | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO623D 1920x1080 309x174mm 14.0-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 3         | 0.38%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.38%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch                    | 3         | 0.38%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                     | 3         | 0.38%   |
| Toshiba TV TSB0209 1920x1080 1594x900mm 72.1-inch                        | 2         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 257       | 34.13%  |
| 1920x1080 (FHD)    | 244       | 32.4%   |
| 1280x800 (WXGA)    | 36        | 4.78%   |
| 3840x2160 (4K)     | 32        | 4.25%   |
| 1920x1200 (WUXGA)  | 32        | 4.25%   |
| 2560x1600          | 26        | 3.45%   |
| 1600x900 (HD+)     | 18        | 2.39%   |
| 2880x1800          | 17        | 2.26%   |
| 2560x1440 (QHD)    | 14        | 1.86%   |
| 1440x900 (WXGA+)   | 11        | 1.46%   |
| 800x1280           | 8         | 1.06%   |
| 3840x2400          | 6         | 0.8%    |
| 3072x1920          | 5         | 0.66%   |
| 1920x540           | 5         | 0.66%   |
| 1280x1024 (SXGA)   | 5         | 0.66%   |
| 2560x1080          | 4         | 0.53%   |
| 3200x1800 (QHD+)   | 3         | 0.4%    |
| 2160x1440          | 3         | 0.4%    |
| 1360x768           | 3         | 0.4%    |
| 1024x768 (XGA)     | 3         | 0.4%    |
| 1024x600           | 3         | 0.4%    |
| 3456x2160          | 2         | 0.27%   |
| 2880x1620          | 2         | 0.27%   |
| 2520x1680          | 2         | 0.27%   |
| 2304x1440          | 2         | 0.27%   |
| 1680x1050 (WSXGA+) | 2         | 0.27%   |
| 1024x576           | 2         | 0.27%   |
| 3000x2000          | 1         | 0.13%   |
| 2880x1920          | 1         | 0.13%   |
| 2256x1504          | 1         | 0.13%   |
| 2240x1400          | 1         | 0.13%   |
| 1920x1280          | 1         | 0.13%   |
| 1400x1050          | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 307       | 39.46%  |
| 13      | 142       | 18.25%  |
| 14      | 83        | 10.67%  |
| 12      | 50        | 6.43%   |
| 17      | 26        | 3.34%   |
| 23      | 20        | 2.57%   |
| 11      | 20        | 2.57%   |
| 16      | 18        | 2.31%   |
| 24      | 16        | 2.06%   |
| 31      | 14        | 1.8%    |
| 21      | 13        | 1.67%   |
| 27      | 11        | 1.41%   |
| 10      | 9         | 1.16%   |
| 7       | 8         | 1.03%   |
| Unknown | 8         | 1.03%   |
| 18      | 7         | 0.9%    |
| 72      | 5         | 0.64%   |
| 19      | 4         | 0.51%   |
| 37      | 3         | 0.39%   |
| 34      | 3         | 0.39%   |
| 32      | 3         | 0.39%   |
| 84      | 1         | 0.13%   |
| 52      | 1         | 0.13%   |
| 39      | 1         | 0.13%   |
| 38      | 1         | 0.13%   |
| 29      | 1         | 0.13%   |
| 26      | 1         | 0.13%   |
| 25      | 1         | 0.13%   |
| 20      | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 424       | 54.78%  |
| 201-300     | 190       | 24.55%  |
| 501-600     | 43        | 5.56%   |
| 351-400     | 41        | 5.3%    |
| 401-500     | 27        | 3.49%   |
| 601-700     | 15        | 1.94%   |
| 1-100       | 8         | 1.03%   |
| Unknown     | 8         | 1.03%   |
| 701-800     | 6         | 0.78%   |
| 1501-2000   | 6         | 0.78%   |
| 801-900     | 5         | 0.65%   |
| 1001-1500   | 1         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 539       | 75.7%   |
| 16/10   | 135       | 18.96%  |
| 3/2     | 13        | 1.83%   |
| 0.67    | 8         | 1.12%   |
| 5/4     | 5         | 0.7%    |
| 21/9    | 4         | 0.56%   |
| Unknown | 4         | 0.56%   |
| 4/3     | 3         | 0.42%   |
| 32/9    | 1         | 0.14%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 310       | 39.85%  |
| 81-90          | 130       | 16.71%  |
| 71-80          | 90        | 11.57%  |
| 61-70          | 49        | 6.3%    |
| 201-250        | 43        | 5.53%   |
| 121-130        | 21        | 2.7%    |
| 51-60          | 20        | 2.57%   |
| 351-500        | 20        | 2.57%   |
| 111-120        | 14        | 1.8%    |
| 301-350        | 13        | 1.67%   |
| 41-50          | 9         | 1.16%   |
| 151-200        | 9         | 1.16%   |
| 141-150        | 9         | 1.16%   |
| 1-40           | 8         | 1.03%   |
| Unknown        | 8         | 1.03%   |
| More than 1000 | 7         | 0.9%    |
| 91-100         | 7         | 0.9%    |
| 501-1000       | 5         | 0.64%   |
| 251-300        | 4         | 0.51%   |
| 131-140        | 2         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 234       | 30.51%  |
| 101-120       | 197       | 25.68%  |
| 51-100        | 147       | 19.17%  |
| 161-240       | 136       | 17.73%  |
| More than 240 | 37        | 4.82%   |
| 1-50          | 8         | 1.04%   |
| Unknown       | 8         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 669       | 84.68%  |
| 2     | 83        | 10.51%  |
| 0     | 33        | 4.18%   |
| 3     | 5         | 0.63%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 414       | 34.39%  |
| Realtek Semiconductor                  | 319       | 26.5%   |
| Qualcomm Atheros                       | 194       | 16.11%  |
| Broadcom                               | 101       | 8.39%   |
| Marvell Technology Group               | 26        | 2.16%   |
| MediaTek                               | 24        | 1.99%   |
| ASIX Electronics                       | 22        | 1.83%   |
| Broadcom Limited                       | 17        | 1.41%   |
| Apple                                  | 9         | 0.75%   |
| Ralink                                 | 8         | 0.66%   |
| TP-Link                                | 6         | 0.5%    |
| Sierra Wireless                        | 6         | 0.5%    |
| BUFFALO                                | 6         | 0.5%    |
| Qualcomm                               | 5         | 0.42%   |
| PLANEX                                 | 4         | 0.33%   |
| Huawei Technologies                    | 4         | 0.33%   |
| Ralink Technology                      | 3         | 0.25%   |
| Nvidia                                 | 3         | 0.25%   |
| Lenovo                                 | 3         | 0.25%   |
| Elecom                                 | 3         | 0.25%   |
| Xiaomi                                 | 2         | 0.17%   |
| U-Blox                                 | 2         | 0.17%   |
| Qualcomm Atheros Communications        | 2         | 0.17%   |
| Google                                 | 2         | 0.17%   |
| DisplayLink                            | 2         | 0.17%   |
| D-Link                                 | 2         | 0.17%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Samsung Electronics                    | 1         | 0.08%   |
| Quectel Wireless Solutions             | 1         | 0.08%   |
| Qualcomm Technologies                  | 1         | 0.08%   |
| QNAP System                            | 1         | 0.08%   |
| OPPO Electronics                       | 1         | 0.08%   |
| NetGear                                | 1         | 0.08%   |
| NEC Computers                          | 1         | 0.08%   |
| Logitec                                | 1         | 0.08%   |
| JMicron Technology                     | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| I-O Data Device                        | 1         | 0.08%   |
| Gemtek                                 | 1         | 0.08%   |
| Dell                                   | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 174       | 11.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 45        | 3.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 41        | 2.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 2.21%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 30        | 2.01%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 29        | 1.94%   |
| Intel Wireless 8265 / 8275                                              | 26        | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 25        | 1.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.61%   |
| Intel Wireless 7265                                                     | 24        | 1.61%   |
| Intel Wireless 7260                                                     | 23        | 1.54%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 1.54%   |
| Intel 82579V Gigabit Network Connection                                 | 23        | 1.54%   |
| Intel Wireless 8260                                                     | 19        | 1.27%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 1.21%   |
| ASIX AX88179 Gigabit Ethernet                                           | 18        | 1.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 1.07%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 1.07%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 15        | 1.01%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.01%   |
| Intel Wireless 3165                                                     | 15        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 0.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 13        | 0.87%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 12        | 0.8%    |
| Intel Wireless 3160                                                     | 12        | 0.8%    |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 12        | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 11        | 0.74%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 11        | 0.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 0.67%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 0.67%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 0.67%   |
| Intel Ethernet Connection (4) I219-V                                    | 10        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 9         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 368       | 46.52%  |
| Qualcomm Atheros                | 158       | 19.97%  |
| Realtek Semiconductor           | 107       | 13.53%  |
| Broadcom                        | 75        | 9.48%   |
| MediaTek                        | 20        | 2.53%   |
| Broadcom Limited                | 12        | 1.52%   |
| Ralink                          | 8         | 1.01%   |
| TP-Link                         | 6         | 0.76%   |
| Sierra Wireless                 | 6         | 0.76%   |
| BUFFALO                         | 6         | 0.76%   |
| Qualcomm                        | 5         | 0.63%   |
| PLANEX                          | 4         | 0.51%   |
| Ralink Technology               | 3         | 0.38%   |
| Elecom                          | 3         | 0.38%   |
| Qualcomm Atheros Communications | 2         | 0.25%   |
| D-Link                          | 2         | 0.25%   |
| Quectel Wireless Solutions      | 1         | 0.13%   |
| Qualcomm Technologies           | 1         | 0.13%   |
| NetGear                         | 1         | 0.13%   |
| Logitec                         | 1         | 0.13%   |
| I-O Data Device                 | 1         | 0.13%   |
| Dell                            | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 4.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 29        | 3.65%   |
| Intel Wireless 8265 / 8275                                              | 26        | 3.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 25        | 3.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 24        | 3.02%   |
| Intel Wireless 7265                                                     | 24        | 3.02%   |
| Intel Wireless 7260                                                     | 23        | 2.89%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 2.89%   |
| Intel Wireless 8260                                                     | 19        | 2.39%   |
| Intel Wi-Fi 6 AX201                                                     | 18        | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 16        | 2.01%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 15        | 1.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 15        | 1.89%   |
| Intel Wireless 3165                                                     | 15        | 1.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 1.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 13        | 1.64%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 12        | 1.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 12        | 1.51%   |
| Intel Wireless 3160                                                     | 12        | 1.51%   |
| Intel Centrino Advanced-N + WiMAX 6250 [Kilmer Peak]                    | 12        | 1.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 11        | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.26%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                        | 10        | 1.26%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 10        | 1.26%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.26%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.26%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 1.13%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 9         | 1.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.13%   |
| Intel WiFi Link 5100                                                    | 8         | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.01%   |
| Broadcom BCM4377b Wireless Network Adapter                              | 8         | 1.01%   |
| Broadcom BCM4364 802.11ac Wireless Network Adapter                      | 8         | 1.01%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 7         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 7         | 0.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 7         | 0.88%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 263       | 39.25%  |
| Intel                                  | 203       | 30.3%   |
| Qualcomm Atheros                       | 75        | 11.19%  |
| Broadcom                               | 39        | 5.82%   |
| Marvell Technology Group               | 26        | 3.88%   |
| ASIX Electronics                       | 22        | 3.28%   |
| Apple                                  | 9         | 1.34%   |
| Broadcom Limited                       | 5         | 0.75%   |
| MediaTek                               | 4         | 0.6%    |
| Huawei Technologies                    | 4         | 0.6%    |
| Nvidia                                 | 3         | 0.45%   |
| Lenovo                                 | 3         | 0.45%   |
| Xiaomi                                 | 2         | 0.3%    |
| Google                                 | 2         | 0.3%    |
| DisplayLink                            | 2         | 0.3%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.15%   |
| Samsung Electronics                    | 1         | 0.15%   |
| QNAP System                            | 1         | 0.15%   |
| OPPO Electronics                       | 1         | 0.15%   |
| JMicron Technology                     | 1         | 0.15%   |
| ICS Advent                             | 1         | 0.15%   |
| Gemtek                                 | 1         | 0.15%   |
| Aquantia                               | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 174       | 25.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 45        | 6.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 41        | 5.99%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 30        | 4.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 25        | 3.65%   |
| Intel 82579V Gigabit Network Connection                                        | 23        | 3.36%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 18        | 2.63%   |
| Intel Ethernet Connection (4) I219-V                                           | 10        | 1.46%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 9         | 1.31%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 1.31%   |
| Apple iBridge                                                                  | 9         | 1.31%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 1.17%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 8         | 1.17%   |
| Intel WiMAX Connection 2400m                                                   | 8         | 1.17%   |
| Intel Ethernet Connection (10) I219-V                                          | 8         | 1.17%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 7         | 1.02%   |
| Intel Ethernet Connection I219-V                                               | 7         | 1.02%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 1.02%   |
| Intel Ethernet Connection (4) I219-LM                                          | 7         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                                          | 7         | 1.02%   |
| Intel 82577LC Gigabit Network Connection                                       | 7         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 7         | 1.02%   |
| Intel Ethernet Connection I217-V                                               | 6         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 0.88%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 0.88%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 6         | 0.88%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 6         | 0.88%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 5         | 0.73%   |
| Realtek RTL8125 2.5GbE Controller                                              | 5         | 0.73%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 5         | 0.73%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 5         | 0.73%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 0.58%   |
| Realtek Killer E2600 GbE Controller                                            | 4         | 0.58%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 4         | 0.58%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 4         | 0.58%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 4         | 0.58%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 0.58%   |
| Intel Ethernet Connection I218-LM                                              | 4         | 0.58%   |
| Intel Ethernet Connection I217-LM                                              | 4         | 0.58%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 754       | 54.09%  |
| Ethernet | 628       | 45.05%  |
| Unknown  | 9         | 0.65%   |
| Modem    | 3         | 0.22%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 567       | 68.98%  |
| Ethernet | 255       | 31.02%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 555       | 70.79%  |
| 1     | 212       | 27.04%  |
| 0     | 11        | 1.4%    |
| 3     | 6         | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 569       | 71.04%  |
| Yes  | 232       | 28.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 267       | 50.86%  |
| Realtek Semiconductor           | 40        | 7.62%   |
| IMC Networks                    | 35        | 6.67%   |
| Qualcomm Atheros Communications | 32        | 6.1%    |
| Broadcom                        | 31        | 5.9%    |
| Foxconn / Hon Hai               | 23        | 4.38%   |
| Apple                           | 22        | 4.19%   |
| Cambridge Silicon Radio         | 19        | 3.62%   |
| Fujitsu                         | 9         | 1.71%   |
| Alps Electric                   | 7         | 1.33%   |
| Realtek                         | 6         | 1.14%   |
| Lite-On Technology              | 6         | 1.14%   |
| Toshiba                         | 5         | 0.95%   |
| Hewlett-Packard                 | 4         | 0.76%   |
| ASUSTek Computer                | 4         | 0.76%   |
| USI                             | 3         | 0.57%   |
| Ralink                          | 2         | 0.38%   |
| Opticis                         | 2         | 0.38%   |
| MediaTek                        | 2         | 0.38%   |
| TP-Link                         | 1         | 0.19%   |
| Taiyo Yuden                     | 1         | 0.19%   |
| Ralink Technology               | 1         | 0.19%   |
| Dell                            | 1         | 0.19%   |
| Askey Computer                  | 1         | 0.19%   |
| 8BitDo                          | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 114       | 21.71%  |
| Intel AX201 Bluetooth                                                               | 49        | 9.33%   |
| Realtek Bluetooth Radio                                                             | 27        | 5.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 27        | 5.14%   |
| Intel AX211 Bluetooth                                                               | 23        | 4.38%   |
| Intel AX200 Bluetooth                                                               | 23        | 4.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 19        | 3.62%   |
| IMC Networks Bluetooth Radio                                                        | 15        | 2.86%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 2.67%   |
| Apple Bluetooth Host Controller                                                     | 12        | 2.29%   |
| IMC Networks Wireless_Device                                                        | 11        | 2.1%    |
| Intel AX210 Bluetooth                                                               | 10        | 1.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 10        | 1.9%    |
| Fujitsu Bluetooth Device                                                            | 8         | 1.52%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 1.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.33%   |
| Realtek Bluetooth Radio                                                             | 6         | 1.14%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 1.14%   |
| IMC Networks Bluetooth Device                                                       | 6         | 1.14%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 5         | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.95%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 4         | 0.76%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 0.76%   |
| Realtek 802.11ac WLAN Adapter                                                       | 4         | 0.76%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 0.76%   |
| Intel Bluetooth Device                                                              | 4         | 0.76%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 4         | 0.76%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.76%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.76%   |
| USI Bluetooth Device                                                                | 3         | 0.57%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.57%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.57%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.57%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.57%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.57%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 3         | 0.57%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.57%   |
| ASUS Broadcom Bluetooth 2.1                                                         | 3         | 0.57%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 640       | 70.72%  |
| AMD                                          | 135       | 14.92%  |
| Nvidia                                       | 73        | 8.07%   |
| Apple                                        | 17        | 1.88%   |
| C-Media Electronics                          | 10        | 1.1%    |
| Creative Technology                          | 4         | 0.44%   |
| Lenovo                                       | 3         | 0.33%   |
| Yamaha                                       | 2         | 0.22%   |
| VIA Technologies                             | 2         | 0.22%   |
| Elitegroup Computer Systems (ECS)            | 2         | 0.22%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.11%   |
| Xiaomi                                       | 1         | 0.11%   |
| Texas Instruments                            | 1         | 0.11%   |
| Sony                                         | 1         | 0.11%   |
| Roland                                       | 1         | 0.11%   |
| Realtek Semiconductor                        | 1         | 0.11%   |
| M2Tech                                       | 1         | 0.11%   |
| M-Audio                                      | 1         | 0.11%   |
| JMTek                                        | 1         | 0.11%   |
| iCreate Technologies                         | 1         | 0.11%   |
| ESI Audiotechnik                             | 1         | 0.11%   |
| Corsair                                      | 1         | 0.11%   |
| CMX Systems                                  | 1         | 0.11%   |
| Cambridge Silicon Radio                      | 1         | 0.11%   |
| BY EDIFIER                                   | 1         | 0.11%   |
| Arturia                                      | 1         | 0.11%   |
| Unknown                                      | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 111       | 10.23%  |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 84        | 7.74%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 79        | 7.28%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 61        | 5.62%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 47        | 4.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 42        | 3.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 38        | 3.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 31        | 2.86%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 27        | 2.49%   |
| Intel Broadwell-U Audio Controller                                                                | 27        | 2.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 23        | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 23        | 2.12%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 22        | 2.03%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 21        | 1.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 1.84%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 20        | 1.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 1.75%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 17        | 1.57%   |
| Apple Audio Device                                                                                | 17        | 1.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 16        | 1.47%   |
| Intel Comet Lake PCH cAVS                                                                         | 15        | 1.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 1.38%   |
| AMD FCH Azalia Controller                                                                         | 14        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 13        | 1.2%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 13        | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 1.01%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 0.92%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 8         | 0.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 0.74%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 7         | 0.65%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 7         | 0.65%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 7         | 0.65%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 7         | 0.65%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 6         | 0.55%   |
| Intel Meteor Lake-P HD Audio Controller                                                           | 6         | 0.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.55%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 6         | 0.55%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 4         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 174       | 31.07%  |
| SK hynix            | 112       | 20%     |
| Micron Technology   | 82        | 14.64%  |
| Unknown             | 55        | 9.82%   |
| Kingston            | 20        | 3.57%   |
| Crucial             | 18        | 3.21%   |
| Elpida              | 11        | 1.96%   |
| A-DATA Technology   | 9         | 1.61%   |
| Unknown             | 9         | 1.61%   |
| Ramaxel Technology  | 8         | 1.43%   |
| Nanya Technology    | 8         | 1.43%   |
| Unknown (ABCD)      | 7         | 1.25%   |
| Team                | 5         | 0.89%   |
| Silicon Power       | 5         | 0.89%   |
| SanMax              | 5         | 0.89%   |
| Transcend           | 4         | 0.71%   |
| Patriot             | 3         | 0.54%   |
| CFD                 | 3         | 0.54%   |
| Toshiba             | 2         | 0.36%   |
| Corsair             | 2         | 0.36%   |
| ASint Technology    | 2         | 0.36%   |
| Unknown (0xD306)    | 1         | 0.18%   |
| Unknown (08C8)      | 1         | 0.18%   |
| SHARETRONIC         | 1         | 0.18%   |
| Neo Forza           | 1         | 0.18%   |
| Melco               | 1         | 0.18%   |
| Lexar               | 1         | 0.18%   |
| KLEVV               | 1         | 0.18%   |
| Goldkey             | 1         | 0.18%   |
| G.Skill             | 1         | 0.18%   |
| EUDAR               | 1         | 0.18%   |
| Essencore           | 1         | 0.18%   |
| CUSO                | 1         | 0.18%   |
| ChangXin Memory     | 1         | 0.18%   |
| BUFFALO             | 1         | 0.18%   |
| Advantech           | 1         | 0.18%   |
| 0DEC000080CE        | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 25        | 4.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 1.69%   |
| Unknown                                                          | 9         | 1.52%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 1.35%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 1.35%   |
| Micron RAM MT53E512M64D4NW-053 4GB Row Of Chips LPDDR4 3733MT/s  | 8         | 1.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 7         | 1.18%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 5         | 0.84%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.84%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.84%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.84%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM DDR3 2400MT/s     | 4         | 0.67%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.67%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 4         | 0.67%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.67%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.67%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.67%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.67%   |
| Unknown RAM Module 4GB SODIMM DDR3 1600MT/s                      | 3         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                       | 3         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 0.51%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.51%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 3         | 0.51%   |
| Team RAM TEAMGROUP-SD3-1600 8GB SODIMM DDR3 1600MT/s             | 3         | 0.51%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.51%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 3         | 0.51%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.51%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 3         | 0.51%   |
| Samsung RAM M471B5673EH1-CF8 2GB SODIMM 4199MT/s                 | 3         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 3         | 0.51%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 3         | 0.51%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 185       | 38.14%  |
| DDR4    | 156       | 32.16%  |
| LPDDR3  | 32        | 6.6%    |
| LPDDR4  | 28        | 5.77%   |
| DDR2    | 28        | 5.77%   |
| LPDDR5  | 23        | 4.74%   |
| DDR5    | 13        | 2.68%   |
| SDRAM   | 11        | 2.27%   |
| Unknown | 7         | 1.44%   |
| DRAM    | 1         | 0.21%   |
| DDR     | 1         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 400       | 82.64%  |
| Row Of Chips | 70        | 14.46%  |
| DIMM         | 5         | 1.03%   |
| Unknown      | 5         | 1.03%   |
| Chip         | 4         | 0.83%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 192       | 36.29%  |
| 8192  | 174       | 32.89%  |
| 2048  | 76        | 14.37%  |
| 16384 | 59        | 11.15%  |
| 1024  | 14        | 2.65%   |
| 32768 | 12        | 2.27%   |
| 512   | 1         | 0.19%   |
| 256   | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 142       | 27.41%  |
| 3200    | 78        | 15.06%  |
| 2667    | 61        | 11.78%  |
| 2400    | 32        | 6.18%   |
| 1334    | 28        | 5.41%   |
| 2133    | 26        | 5.02%   |
| 1067    | 16        | 3.09%   |
| 6400    | 13        | 2.51%   |
| 1333    | 12        | 2.32%   |
| 4800    | 10        | 1.93%   |
| 4199    | 10        | 1.93%   |
| 3733    | 10        | 1.93%   |
| Unknown | 10        | 1.93%   |
| 1867    | 8         | 1.54%   |
| 667     | 8         | 1.54%   |
| 1066    | 7         | 1.35%   |
| 7500    | 6         | 1.16%   |
| 5600    | 6         | 1.16%   |
| 4267    | 6         | 1.16%   |
| 800     | 4         | 0.77%   |
| 975     | 3         | 0.58%   |
| 533     | 3         | 0.58%   |
| 333     | 3         | 0.58%   |
| 8533    | 2         | 0.39%   |
| 7467    | 2         | 0.39%   |
| 4266    | 2         | 0.39%   |
| 3266    | 2         | 0.39%   |
| 1866    | 2         | 0.39%   |
| 400     | 2         | 0.39%   |
| 266     | 2         | 0.39%   |
| 2933    | 1         | 0.19%   |
| 100     | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 25%     |
| Samsung Electronics | 1         | 25%     |
| Canon               | 1         | 25%     |
| Brother Industries  | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| Seiko Epson WF-2010 Series | 1         | 25%     |
| Samsung SCX-3200 Series    | 1         | 25%     |
| Canon PIXMA MG3600 Series  | 1         | 25%     |
| Brother HL-2130 series     | 1         | 25%     |

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
| Chicony Electronics                    | 129       | 24.95%  |
| Bison Electronics                      | 54        | 10.44%  |
| IMC Networks                           | 51        | 9.86%   |
| Microdia                               | 40        | 7.74%   |
| Realtek Semiconductor                  | 33        | 6.38%   |
| Sunplus Innovation Technology          | 31        | 6%      |
| Apple                                  | 23        | 4.45%   |
| Quanta                                 | 20        | 3.87%   |
| Suyin                                  | 17        | 3.29%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 3.09%   |
| Luxvisions Innotech Limited            | 13        | 2.51%   |
| Acer                                   | 13        | 2.51%   |
| Syntek                                 | 9         | 1.74%   |
| Lite-On Technology                     | 7         | 1.35%   |
| Alcor Micro                            | 7         | 1.35%   |
| Ricoh                                  | 6         | 1.16%   |
| Importek                               | 6         | 1.16%   |
| Sonix Technology                       | 5         | 0.97%   |
| Silicon Motion                         | 5         | 0.97%   |
| BUFFALO                                | 5         | 0.97%   |
| Logitech                               | 4         | 0.77%   |
| SunplusIT                              | 3         | 0.58%   |
| Genesys Logic                          | 3         | 0.58%   |
| Samsung Electronics                    | 2         | 0.39%   |
| Lenovo                                 | 2         | 0.39%   |
| Z-Star Microelectronics                | 1         | 0.19%   |
| Sunplus Technology                     | 1         | 0.19%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.19%   |
| Shine-optics                           | 1         | 0.19%   |
| Qtech                                  | 1         | 0.19%   |
| Primax Electronics                     | 1         | 0.19%   |
| Omnivision                             | 1         | 0.19%   |
| Oculus VR                              | 1         | 0.19%   |
| Intel                                  | 1         | 0.19%   |
| Framework                              | 1         | 0.19%   |
| Etron Technology                       | 1         | 0.19%   |
| Cubeternet                             | 1         | 0.19%   |
| 2M UVC CAMERA                          | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 25        | 4.81%   |
| Microdia Integrated_Webcam_HD                           | 20        | 3.85%   |
| IMC Networks Integrated Camera                          | 18        | 3.46%   |
| Chicony FJ Camera                                       | 17        | 3.27%   |
| Realtek Integrated_Webcam_HD                            | 15        | 2.88%   |
| Bison Integrated Camera                                 | 12        | 2.31%   |
| Chicony USB2.0 Camera                                   | 10        | 1.92%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 9         | 1.73%   |
| Apple FaceTime HD Camera (Built-in)                     | 9         | 1.73%   |
| Chicony TOSHIBA Web Camera - HD                         | 8         | 1.54%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 7         | 1.35%   |
| Apple FaceTime HD Camera                                | 7         | 1.35%   |
| Acer USB HD Webcam                                      | 7         | 1.35%   |
| Lite-On Integrated Camera                               | 6         | 1.15%   |
| Bison BisonCam, NB Pro                                  | 6         | 1.15%   |
| Sunplus Integrated_Webcam_HD                            | 5         | 0.96%   |
| BUFFALO USB 2.0 Camera                                  | 5         | 0.96%   |
| Bison USB HD Webcam                                     | 5         | 0.96%   |
| Bison ThinkPad Integrated Camera                        | 5         | 0.96%   |
| Sunplus Integrated_Webcam_FHD                           | 4         | 0.77%   |
| Sunplus HD WebCam                                       | 4         | 0.77%   |
| Quanta HD User Facing                                   | 4         | 0.77%   |
| Microdia USB 2.0 Camera                                 | 4         | 0.77%   |
| Luxvisions Innotech Limited Integrated RGB Camera       | 4         | 0.77%   |
| Luxvisions Innotech Limited Integrated Camera           | 4         | 0.77%   |
| IMC Networks ov9734_azurewave_camera                    | 4         | 0.77%   |
| Chicony NEC HD WebCam                                   | 4         | 0.77%   |
| Chicony Lenovo EasyCamera                               | 4         | 0.77%   |
| Chicony HP HD Camera                                    | 4         | 0.77%   |
| Chicony HD WebCam                                       | 4         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 4         | 0.77%   |
| Bison Lenovo EasyCamera                                 | 4         | 0.77%   |
| Bison HD Webcam                                         | 4         | 0.77%   |
| Syntek Lenovo EasyCamera                                | 3         | 0.58%   |
| Syntek Integrated Camera                                | 3         | 0.58%   |
| Suyin HP Webcam                                         | 3         | 0.58%   |
| Sunplus Dell HD Webcam                                  | 3         | 0.58%   |
| Sonix USB2.0 FHD UVC WebCam                             | 3         | 0.58%   |
| Realtek Lenovo EasyCamera                               | 3         | 0.58%   |
| Quanta HP TrueVision HD Camera                          | 3         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 38        | 27.94%  |
| Synaptics                          | 27        | 19.85%  |
| Shenzhen Goodix Technology         | 19        | 13.97%  |
| AuthenTec                          | 18        | 13.24%  |
| Upek                               | 11        | 8.09%   |
| Elan Microelectronics              | 9         | 6.62%   |
| STMicroelectronics                 | 5         | 3.68%   |
| LighTuning Technology              | 5         | 3.68%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.21%   |
| Focal-systems.Corp                 | 1         | 0.74%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 12        | 8.82%   |
| Shenzhen Goodix  Fingerprint Device                             | 10        | 7.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 8         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 7         | 5.15%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 7         | 5.15%   |
| Shenzhen Goodix Fingerprint Reader                              | 7         | 5.15%   |
| AuthenTec Fingerprint Sensor                                    | 6         | 4.41%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 5         | 3.68%   |
| STMicroelectronics Fingerprint Reader                           | 5         | 3.68%   |
| Elan ELAN:ARM-M4                                                | 5         | 3.68%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 4         | 2.94%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 4         | 2.94%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 4         | 2.94%   |
| Validity Sensors VFS491                                         | 3         | 2.21%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 2.21%   |
| Upek TCS5B Fingerprint sensor                                   | 3         | 2.21%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 3         | 2.21%   |
| Elan ELAN:Fingerprint                                           | 3         | 2.21%   |
| AuthenTec AES2810                                               | 3         | 2.21%   |
| AuthenTec AES1600                                               | 3         | 2.21%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor               | 2         | 1.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 2         | 1.47%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 1.47%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 2         | 1.47%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 1.47%   |
| Synaptics UWP WBDI Device                                       | 2         | 1.47%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 1.47%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 2         | 1.47%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 1.47%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 0.74%   |
| Validity Sensors Fingerprint scanner                            | 1         | 0.74%   |
| Synaptics WBDI Device                                           | 1         | 0.74%   |
| Synaptics WBDI                                                  | 1         | 0.74%   |
| Synaptics Prometheus Fingerprint Reader                         | 1         | 0.74%   |
| LighTuning Fingerprint Reader                                   | 1         | 0.74%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                       | 1         | 0.74%   |
| Elan fingerprint sensor [FeinTech FPS00200]                     | 1         | 0.74%   |
| AuthenTec AES2660 Fingerprint Sensor                            | 1         | 0.74%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 0.74%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 12        | 36.36%  |
| Upek        | 9         | 27.27%  |
| Alcor Micro | 8         | 24.24%  |
| O2 Micro    | 4         | 12.12%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 27.27%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 8         | 24.24%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 18.18%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 12.12%  |
| Broadcom 58200                                                               | 3         | 9.09%   |
| Broadcom 5880                                                                | 2         | 6.06%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 498       | 62.48%  |
| 1     | 242       | 30.36%  |
| 2     | 44        | 5.52%   |
| 3     | 10        | 1.25%   |
| 6     | 2         | 0.25%   |
| 4     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 134       | 36.51%  |
| Graphics card            | 71        | 19.35%  |
| Multimedia controller    | 33        | 8.99%   |
| Chipcard                 | 32        | 8.72%   |
| Net/wireless             | 30        | 8.17%   |
| Storage                  | 18        | 4.9%    |
| Communication controller | 12        | 3.27%   |
| Sound                    | 9         | 2.45%   |
| Camera                   | 9         | 2.45%   |
| Bluetooth                | 7         | 1.91%   |
| Net/ethernet             | 4         | 1.09%   |
| Network                  | 3         | 0.82%   |
| Storage/ata              | 2         | 0.54%   |
| Modem                    | 2         | 0.54%   |
| Tv card                  | 1         | 0.27%   |

