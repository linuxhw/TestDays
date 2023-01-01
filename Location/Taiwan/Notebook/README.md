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

Total: 302

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 38        | 17.84%  |
| Ubuntu 18.04        | 19        | 8.92%   |
| Ubuntu 22.04        | 16        | 7.51%   |
| Arch Rolling        | 8         | 3.76%   |
| Debian 11           | 6         | 2.82%   |
| Pop!_OS 20.04       | 5         | 2.35%   |
| OpenMandriva 4.2    | 5         | 2.35%   |
| Fedora 37           | 5         | 2.35%   |
| Ubuntu 19.04        | 4         | 1.88%   |
| KDE neon 20.04      | 4         | 1.88%   |
| Fedora 36           | 4         | 1.88%   |
| Ubuntu 21.04        | 3         | 1.41%   |
| Ubuntu 19.10        | 3         | 1.41%   |
| Pop!_OS 21.04       | 3         | 1.41%   |
| OpenMandriva 4.3    | 3         | 1.41%   |
| Fedora 34           | 3         | 1.41%   |
| Debian Testing      | 3         | 1.41%   |
| Arch                | 3         | 1.41%   |
| Ubuntu 22.10        | 2         | 0.94%   |
| Ubuntu 20.10        | 2         | 0.94%   |
| Ubuntu 18.10        | 2         | 0.94%   |
| Ubuntu 16.04        | 2         | 0.94%   |
| Pop!_OS 21.10       | 2         | 0.94%   |
| OpenMandriva 4.50   | 2         | 0.94%   |
| Manjaro 21.2.2      | 2         | 0.94%   |
| Manjaro 21.1.3      | 2         | 0.94%   |
| Manjaro 21.1.0      | 2         | 0.94%   |
| Manjaro 20.1        | 2         | 0.94%   |
| Manjaro 20.0        | 2         | 0.94%   |
| Manjaro 18.0.0      | 2         | 0.94%   |
| Manjaro             | 2         | 0.94%   |
| Linux Mint 20.3     | 2         | 0.94%   |
| Linux Mint 20.1     | 2         | 0.94%   |
| Kubuntu 22.04       | 2         | 0.94%   |
| Gentoo 2.7          | 2         | 0.94%   |
| Fedora 35           | 2         | 0.94%   |
| EndeavourOS Rolling | 2         | 0.94%   |
| Debian              | 2         | 0.94%   |
| Zorin 16            | 1         | 0.47%   |
| Zorin 15            | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 89        | 44.5%   |
| Manjaro          | 19        | 9.5%    |
| Fedora           | 16        | 8%      |
| Arch             | 11        | 5.5%    |
| Pop!_OS          | 10        | 5%      |
| OpenMandriva     | 10        | 5%      |
| Debian           | 10        | 5%      |
| Linux Mint       | 6         | 3%      |
| KDE neon         | 4         | 2%      |
| Kubuntu          | 3         | 1.5%    |
| Zorin            | 2         | 1%      |
| Xubuntu          | 2         | 1%      |
| Ubuntu MATE      | 2         | 1%      |
| Lubuntu          | 2         | 1%      |
| Gentoo           | 2         | 1%      |
| Endless          | 2         | 1%      |
| EndeavourOS      | 2         | 1%      |
| Ubuntu Unity     | 1         | 0.5%    |
| Ubuntu Studio    | 1         | 0.5%    |
| Ubuntu Budgie    | 1         | 0.5%    |
| org.kde.Platform | 1         | 0.5%    |
| Nobara           | 1         | 0.5%    |
| Kali             | 1         | 0.5%    |
| Elementary       | 1         | 0.5%    |
| CentOS           | 1         | 0.5%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 5         | 2.25%   |
| 5.8.0-7630-generic          | 3         | 1.35%   |
| 5.4.0-42-generic            | 3         | 1.35%   |
| 5.3.0-46-generic            | 3         | 1.35%   |
| 5.3.0-40-generic            | 3         | 1.35%   |
| 5.16.7-desktop-1omv4003     | 3         | 1.35%   |
| 5.15.0-40-generic           | 3         | 1.35%   |
| 5.11.0-25-generic           | 3         | 1.35%   |
| 6.0.8-300.fc37.x86_64       | 2         | 0.9%    |
| 5.8.10-arch1-1              | 2         | 0.9%    |
| 5.8.0-53-generic            | 2         | 0.9%    |
| 5.8.0-43-generic            | 2         | 0.9%    |
| 5.4.64-1-MANJARO            | 2         | 0.9%    |
| 5.4.0-52-generic            | 2         | 0.9%    |
| 5.4.0-26-generic            | 2         | 0.9%    |
| 5.16.11-2-MANJARO           | 2         | 0.9%    |
| 5.15.0-56-generic           | 2         | 0.9%    |
| 5.15.0-53-generic           | 2         | 0.9%    |
| 5.13.15-1-MANJARO           | 2         | 0.9%    |
| 5.13.0-30-generic           | 2         | 0.9%    |
| 5.11.0-7620-generic         | 2         | 0.9%    |
| 5.11.0-43-generic           | 2         | 0.9%    |
| 5.11.0-41-generic           | 2         | 0.9%    |
| 5.11.0-27-generic           | 2         | 0.9%    |
| 5.10.0-8-amd64              | 2         | 0.9%    |
| 5.10.0-16-amd64             | 2         | 0.9%    |
| 4.18.0-17-generic           | 2         | 0.9%    |
| 4.18.0-15-generic           | 2         | 0.9%    |
| 4.15.0-47-generic           | 2         | 0.9%    |
| 4.15.0-43-generic           | 2         | 0.9%    |
| 6.1.1-arch1-1               | 1         | 0.45%   |
| 6.0.7-201.fsync.fc36.x86_64 | 1         | 0.45%   |
| 6.0.2-301.fc36.x86_64       | 1         | 0.45%   |
| 6.0.12-300.fc37.x86_64      | 1         | 0.45%   |
| 6.0.11-300.fc37.x86_64      | 1         | 0.45%   |
| 6.0.0-4-amd64               | 1         | 0.45%   |
| 6.0.0-2-amd64               | 1         | 0.45%   |
| 6.0.0-1-MANJARO             | 1         | 0.45%   |
| 5.9.16-200.fc33.x86_64      | 1         | 0.45%   |
| 5.9.0-4-amd64               | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 10.14%  |
| 5.15.0  | 15        | 6.91%   |
| 5.8.0   | 13        | 5.99%   |
| 5.11.0  | 13        | 5.99%   |
| 5.13.0  | 11        | 5.07%   |
| 5.10.0  | 9         | 4.15%   |
| 4.18.0  | 9         | 4.15%   |
| 4.15.0  | 9         | 4.15%   |
| 5.3.0   | 7         | 3.23%   |
| 5.0.0   | 7         | 3.23%   |
| 5.10.14 | 5         | 2.3%    |
| 5.19.0  | 4         | 1.84%   |
| 5.14.0  | 4         | 1.84%   |
| 6.0.0   | 3         | 1.38%   |
| 5.16.7  | 3         | 1.38%   |
| 5.16.11 | 3         | 1.38%   |
| 6.0.8   | 2         | 0.92%   |
| 5.8.10  | 2         | 0.92%   |
| 5.7.1   | 2         | 0.92%   |
| 5.7.0   | 2         | 0.92%   |
| 5.4.64  | 2         | 0.92%   |
| 5.18.7  | 2         | 0.92%   |
| 5.17.5  | 2         | 0.92%   |
| 5.16.18 | 2         | 0.92%   |
| 5.15.21 | 2         | 0.92%   |
| 5.15.16 | 2         | 0.92%   |
| 5.13.15 | 2         | 0.92%   |
| 6.1.1   | 1         | 0.46%   |
| 6.0.7   | 1         | 0.46%   |
| 6.0.2   | 1         | 0.46%   |
| 6.0.12  | 1         | 0.46%   |
| 6.0.11  | 1         | 0.46%   |
| 5.9.16  | 1         | 0.46%   |
| 5.9.0   | 1         | 0.46%   |
| 5.8.3   | 1         | 0.46%   |
| 5.8.18  | 1         | 0.46%   |
| 5.8.16  | 1         | 0.46%   |
| 5.7.8   | 1         | 0.46%   |
| 5.7.4   | 1         | 0.46%   |
| 5.7.11  | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 27        | 12.56%  |
| 5.4     | 25        | 11.63%  |
| 5.10    | 19        | 8.84%   |
| 5.8     | 18        | 8.37%   |
| 5.13    | 16        | 7.44%   |
| 5.11    | 15        | 6.98%   |
| 6.0     | 9         | 4.19%   |
| 5.16    | 9         | 4.19%   |
| 4.18    | 9         | 4.19%   |
| 4.15    | 9         | 4.19%   |
| 5.0     | 8         | 3.72%   |
| 5.7     | 7         | 3.26%   |
| 5.3     | 7         | 3.26%   |
| 5.19    | 7         | 3.26%   |
| 5.14    | 6         | 2.79%   |
| 5.6     | 4         | 1.86%   |
| 5.17    | 4         | 1.86%   |
| 5.18    | 3         | 1.4%    |
| 5.12    | 3         | 1.4%    |
| 5.9     | 2         | 0.93%   |
| 6.1     | 1         | 0.47%   |
| 5.2     | 1         | 0.47%   |
| 4.4     | 1         | 0.47%   |
| 4.19    | 1         | 0.47%   |
| 4.14    | 1         | 0.47%   |
| 4.13    | 1         | 0.47%   |
| 4.10    | 1         | 0.47%   |
| 3.10    | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 189       | 97.93%  |
| i686   | 4         | 2.07%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 100       | 49.02%  |
| Unknown         | 36        | 17.65%  |
| KDE5            | 29        | 14.22%  |
| XFCE            | 8         | 3.92%   |
| X-Cinnamon      | 5         | 2.45%   |
| MATE            | 5         | 2.45%   |
| KDE             | 5         | 2.45%   |
| Openbox         | 2         | 0.98%   |
| LXQt            | 2         | 0.98%   |
| LXDE            | 2         | 0.98%   |
| i3              | 2         | 0.98%   |
| GNOME Flashback | 2         | 0.98%   |
| Deepin          | 2         | 0.98%   |
| Unity           | 1         | 0.49%   |
| sway            | 1         | 0.49%   |
| Pantheon        | 1         | 0.49%   |
| Budgie          | 1         | 0.49%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 144       | 73.1%   |
| Wayland | 30        | 15.23%  |
| Unknown | 19        | 9.64%   |
| Tty     | 4         | 2.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 86        | 42.57%  |
| GDM     | 39        | 19.31%  |
| SDDM    | 31        | 15.35%  |
| GDM3    | 24        | 11.88%  |
| LightDM | 15        | 7.43%   |
| TDM     | 4         | 1.98%   |
| SLiM    | 2         | 0.99%   |
| LXDM    | 1         | 0.5%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 95        | 47.74%  |
| zh_TW   | 57        | 28.64%  |
| Unknown | 28        | 14.07%  |
| zh_CN   | 4         | 2.01%   |
| ru_RU   | 3         | 1.51%   |
| en_GB   | 3         | 1.51%   |
| C       | 2         | 1.01%   |
| zh_SG   | 1         | 0.5%    |
| lzh_TW  | 1         | 0.5%    |
| ja_JP   | 1         | 0.5%    |
| en_SG   | 1         | 0.5%    |
| en_IE   | 1         | 0.5%    |
| de_DE   | 1         | 0.5%    |
| C.UTF8  | 1         | 0.5%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 121       | 61.73%  |
| BIOS | 75        | 38.27%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 162       | 83.08%  |
| Overlay | 10        | 5.13%   |
| Btrfs   | 10        | 5.13%   |
| Xfs     | 5         | 2.56%   |
| Unknown | 4         | 2.05%   |
| Ext2    | 2         | 1.03%   |
| Tmpfs   | 1         | 0.51%   |
| F2fs    | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 91        | 46.67%  |
| GPT     | 87        | 44.62%  |
| MBR     | 17        | 8.72%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 172       | 88.21%  |
| Yes       | 23        | 11.79%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 114       | 58.46%  |
| Yes       | 81        | 41.54%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer                 | 39        | 20.21%  |
| ASUSTek Computer     | 37        | 19.17%  |
| Lenovo               | 26        | 13.47%  |
| Hewlett-Packard      | 24        | 12.44%  |
| Dell                 | 21        | 10.88%  |
| MSI                  | 17        | 8.81%   |
| Sony                 | 3         | 1.55%   |
| Unknown              | 3         | 1.55%   |
| Toshiba              | 2         | 1.04%   |
| LG Electronics       | 2         | 1.04%   |
| Lex                  | 2         | 1.04%   |
| Intel Client Systems | 2         | 1.04%   |
| HUAWEI               | 2         | 1.04%   |
| Gigabyte Technology  | 2         | 1.04%   |
| Apple                | 2         | 1.04%   |
| win element          | 1         | 0.52%   |
| Vizio                | 1         | 0.52%   |
| Samsung Electronics  | 1         | 0.52%   |
| NEXCOM               | 1         | 0.52%   |
| Intel                | 1         | 0.52%   |
| CJSCOPE              | 1         | 0.52%   |
| AVITA                | 1         | 0.52%   |
| AMI                  | 1         | 0.52%   |
| AMD                  | 1         | 0.52%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 5         | 2.59%   |
| MSI GS63 7RE                         | 2         | 1.04%   |
| Lex 3I610DW                          | 2         | 1.04%   |
| Lenovo IdeaPad 5 14ALC05 82LM        | 2         | 1.04%   |
| HP Pavilion dv7                      | 2         | 1.04%   |
| Dell XPS 13 9380                     | 2         | 1.04%   |
| Acer Swift SF514-52T                 | 2         | 1.04%   |
| Acer Aspire 4755                     | 2         | 1.04%   |
| Acer Aspire 4750                     | 2         | 1.04%   |
| win element MBOX                     | 1         | 0.52%   |
| Vizio CT14                           | 1         | 0.52%   |
| Toshiba Satellite L850               | 1         | 0.52%   |
| Toshiba PORTEGE R830                 | 1         | 0.52%   |
| Sony VPCCB15FW                       | 1         | 0.52%   |
| Sony SVS15115FWB                     | 1         | 0.52%   |
| Sony SVP13229PWB                     | 1         | 0.52%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B  | 1         | 0.52%   |
| NEXCOM B537-I                        | 1         | 0.52%   |
| MSI U270DX                           | 1         | 0.52%   |
| MSI PE72 8RD                         | 1         | 0.52%   |
| MSI PE62 8RD                         | 1         | 0.52%   |
| MSI PE60 6QE                         | 1         | 0.52%   |
| MSI P65 Creator 9SD                  | 1         | 0.52%   |
| MSI Modern 15 A5M                    | 1         | 0.52%   |
| MSI Modern 14 B11M                   | 1         | 0.52%   |
| MSI GV72 8RC                         | 1         | 0.52%   |
| MSI GT63 Titan 9SG                   | 1         | 0.52%   |
| MSI GS76 Stealth 11UH                | 1         | 0.52%   |
| MSI GL65 9SD                         | 1         | 0.52%   |
| MSI GE70 2PE                         | 1         | 0.52%   |
| MSI GE70 0NC/GE70 0ND                | 1         | 0.52%   |
| MSI GE62 6QD                         | 1         | 0.52%   |
| MSI CX62 6QD                         | 1         | 0.52%   |
| LG LE50-5BC6H1                       | 1         | 0.52%   |
| LG 16Z90P-G.AA78C                    | 1         | 0.52%   |
| Lenovo Z50-70 20354                  | 1         | 0.52%   |
| Lenovo XiaoXinAir 15ARE 2021 82GL    | 1         | 0.52%   |
| Lenovo V330-15IGM                    | 1         | 0.52%   |
| Lenovo ThinkPad X230 2324CD1         | 1         | 0.52%   |
| Lenovo ThinkPad X13 Gen 1 20UFS0BA00 | 1         | 0.52%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 25        | 12.95%  |
| Lenovo ThinkPad   | 17        | 8.81%   |
| Dell Inspiron     | 8         | 4.15%   |
| HP Pavilion       | 7         | 3.63%   |
| ASUS VivoBook     | 7         | 3.63%   |
| Acer Swift        | 7         | 3.63%   |
| HP ProBook        | 6         | 3.11%   |
| ASUS ROG          | 6         | 3.11%   |
| Lenovo IdeaPad    | 5         | 2.59%   |
| Dell Vostro       | 5         | 2.59%   |
| Unknown           | 5         | 2.59%   |
| ASUS ZenBook      | 4         | 2.07%   |
| Acer TravelMate   | 4         | 2.07%   |
| HP EliteBook      | 3         | 1.55%   |
| Dell XPS          | 3         | 1.55%   |
| Dell Latitude     | 3         | 1.55%   |
| MSI Modern        | 2         | 1.04%   |
| MSI GS63          | 2         | 1.04%   |
| MSI GE70          | 2         | 1.04%   |
| Lex 3I610DW       | 2         | 1.04%   |
| ASUS ASUSPRO      | 2         | 1.04%   |
| ASUS ASUS         | 2         | 1.04%   |
| win element MBOX  | 1         | 0.52%   |
| Vizio CT14        | 1         | 0.52%   |
| Toshiba Satellite | 1         | 0.52%   |
| Toshiba PORTEGE   | 1         | 0.52%   |
| Sony VPCCB15FW    | 1         | 0.52%   |
| Sony SVS15115FWB  | 1         | 0.52%   |
| Sony SVP13229PWB  | 1         | 0.52%   |
| Samsung 700Z3A    | 1         | 0.52%   |
| NEXCOM B537-I     | 1         | 0.52%   |
| MSI U270DX        | 1         | 0.52%   |
| MSI PE72          | 1         | 0.52%   |
| MSI PE62          | 1         | 0.52%   |
| MSI PE60          | 1         | 0.52%   |
| MSI P65           | 1         | 0.52%   |
| MSI GV72          | 1         | 0.52%   |
| MSI GT63          | 1         | 0.52%   |
| MSI GS76          | 1         | 0.52%   |
| MSI GL65          | 1         | 0.52%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 25        | 12.95%  |
| 2019 | 20        | 10.36%  |
| 2020 | 19        | 9.84%   |
| 2017 | 18        | 9.33%   |
| 2018 | 17        | 8.81%   |
| 2012 | 13        | 6.74%   |
| 2011 | 12        | 6.22%   |
| 2016 | 11        | 5.7%    |
| 2014 | 11        | 5.7%    |
| 2022 | 10        | 5.18%   |
| 2015 | 10        | 5.18%   |
| 2013 | 7         | 3.63%   |
| 2009 | 7         | 3.63%   |
| 2010 | 6         | 3.11%   |
| 2008 | 4         | 2.07%   |
| 2007 | 1         | 0.52%   |
| 2006 | 1         | 0.52%   |
| 2004 | 1         | 0.52%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 193       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 171       | 87.69%  |
| Enabled  | 24        | 12.31%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 193       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 59        | 29.95%  |
| 16.01-24.0  | 51        | 25.89%  |
| 8.01-16.0   | 36        | 18.27%  |
| 3.01-4.0    | 25        | 12.69%  |
| 32.01-64.0  | 12        | 6.09%   |
| 64.01-256.0 | 6         | 3.05%   |
| 24.01-32.0  | 3         | 1.52%   |
| 2.01-3.0    | 2         | 1.02%   |
| 1.01-2.0    | 2         | 1.02%   |
| 0.51-1.0    | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 63        | 29.72%  |
| 2.01-3.0   | 57        | 26.89%  |
| 4.01-8.0   | 36        | 16.98%  |
| 3.01-4.0   | 33        | 15.57%  |
| 8.01-16.0  | 11        | 5.19%   |
| 0.51-1.0   | 7         | 3.3%    |
| 24.01-32.0 | 2         | 0.94%   |
| 0.01-0.5   | 2         | 0.94%   |
| 32.01-64.0 | 1         | 0.47%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 122       | 61.31%  |
| 2      | 61        | 30.65%  |
| 3      | 9         | 4.52%   |
| 0      | 4         | 2.01%   |
| 4      | 2         | 1.01%   |
| 5      | 1         | 0.5%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 74.61%  |
| Yes       | 49        | 25.39%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 150       | 77.32%  |
| No        | 44        | 22.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 95.85%  |
| No        | 8         | 4.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 172       | 88.66%  |
| No        | 22        | 11.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Taiwan  | 193       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Taipei           | 64        | 30.77%  |
| New Taipei       | 34        | 16.35%  |
| Taoyuan District | 21        | 10.1%   |
| Hsinchu          | 19        | 9.13%   |
| Taichung         | 16        | 7.69%   |
| Kaohsiung City   | 11        | 5.29%   |
| Tainan City      | 7         | 3.37%   |
| Hsinchu County   | 4         | 1.92%   |
| Chang-hua        | 4         | 1.92%   |
| Zhudong          | 3         | 1.44%   |
| Yunlin           | 3         | 1.44%   |
| Pingtung City    | 3         | 1.44%   |
| Shulin District  | 2         | 0.96%   |
| Nantou City      | 2         | 0.96%   |
| Keelung          | 2         | 0.96%   |
| Zhubei           | 1         | 0.48%   |
| Zhongli District | 1         | 0.48%   |
| Yilan            | 1         | 0.48%   |
| Xiawanzi         | 1         | 0.48%   |
| Tuniugou         | 1         | 0.48%   |
| Taichung City    | 1         | 0.48%   |
| Penghu County    | 1         | 0.48%   |
| Neihu            | 1         | 0.48%   |
| Miaoli           | 1         | 0.48%   |
| Fenjihu          | 1         | 0.48%   |
| Chenggong        | 1         | 0.48%   |
| Buxin            | 1         | 0.48%   |
| Bao'an           | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 29        | 38     | 10.78%  |
| Samsung Electronics            | 26        | 37     | 9.67%   |
| Crucial                        | 22        | 28     | 8.18%   |
| Seagate                        | 20        | 22     | 7.43%   |
| SanDisk                        | 20        | 24     | 7.43%   |
| SK hynix                       | 18        | 21     | 6.69%   |
| Kingston                       | 18        | 24     | 6.69%   |
| HGST                           | 17        | 18     | 6.32%   |
| Toshiba                        | 15        | 16     | 5.58%   |
| Unknown                        | 9         | 10     | 3.35%   |
| Micron Technology              | 9         | 9      | 3.35%   |
| Intel                          | 9         | 10     | 3.35%   |
| Hitachi                        | 7         | 8      | 2.6%    |
| ASMT                           | 4         | 4      | 1.49%   |
| Unknown                        | 4         | 4      | 1.49%   |
| Transcend                      | 3         | 3      | 1.12%   |
| JMicron Technology             | 3         | 6      | 1.12%   |
| AGI                            | 3         | 3      | 1.12%   |
| A-DATA Technology              | 3         | 3      | 1.12%   |
| SPCC                           | 2         | 3      | 0.74%   |
| Micron/Crucial Technology      | 2         | 2      | 0.74%   |
| ZHITAI                         | 1         | 1      | 0.37%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.37%   |
| XPG                            | 1         | 1      | 0.37%   |
| USB3.2                         | 1         | 1      | 0.37%   |
| Union Memory                   | 1         | 1      | 0.37%   |
| Toshiba America Info Systems   | 1         | 2      | 0.37%   |
| StoreJet                       | 1         | 2      | 0.37%   |
| Solid State Storage Technology | 1         | 1      | 0.37%   |
| Silicon Motion                 | 1         | 1      | 0.37%   |
| Plextor                        | 1         | 1      | 0.37%   |
| Pioneer                        | 1         | 1      | 0.37%   |
| Phison                         | 1         | 1      | 0.37%   |
| Patriot                        | 1         | 1      | 0.37%   |
| OCZ                            | 1         | 1      | 0.37%   |
| NeoTech                        | 1         | 1      | 0.37%   |
| MyDigitalSSD                   | 1         | 1      | 0.37%   |
| MX                             | 1         | 1      | 0.37%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.37%   |
| LITEONIT                       | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                         | 8         | 2.84%   |
| Crucial CT500MX500SSD1 500GB                     | 7         | 2.48%   |
| Seagate ST1000LM035-1RK172 1TB                   | 5         | 1.77%   |
| Seagate ST1000LM049-2GH172 1TB                   | 4         | 1.42%   |
| Crucial CT1000MX500SSD1 1TB                      | 4         | 1.42%   |
| Unknown                                          | 4         | 1.42%   |
| Unknown MMC Card  64GB                           | 3         | 1.06%   |
| Toshiba MQ04ABF100 1TB                           | 3         | 1.06%   |
| Toshiba MQ01ABD100 1TB                           | 3         | 1.06%   |
| SanDisk NVMe SSD Drive 512GB                     | 3         | 1.06%   |
| SanDisk NVMe SSD Drive 256GB                     | 3         | 1.06%   |
| SanDisk NVMe SSD Drive 1TB                       | 3         | 1.06%   |
| HGST HTS541010B7E610 1TB                         | 3         | 1.06%   |
| Crucial CT500MX500SSD4 500GB                     | 3         | 1.06%   |
| Crucial CT240BX500SSD1 240GB                     | 3         | 1.06%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                 | 2         | 0.71%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 2         | 0.71%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB             | 2         | 0.71%   |
| Unknown MMC Card  32GB                           | 2         | 0.71%   |
| SPCC Solid State Disk 240GB                      | 2         | 0.71%   |
| SK hynix NVMe SSD Drive 512GB                    | 2         | 0.71%   |
| SK hynix HFM512GD3JX016N 512GB                   | 2         | 0.71%   |
| SK hynix HFM512GD3JX013N 512GB                   | 2         | 0.71%   |
| SK hynix BC711 NVMe 512GB                        | 2         | 0.71%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB | 2         | 0.71%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB           | 2         | 0.71%   |
| Samsung NVMe SSD Drive 1024GB                    | 2         | 0.71%   |
| Samsung MZVLW256HEHP-00000 256GB                 | 2         | 0.71%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD              | 2         | 0.71%   |
| Kingston SA400S37240G 240GB SSD                  | 2         | 0.71%   |
| Kingston SA400S37120G 120GB SSD                  | 2         | 0.71%   |
| Kingston SA2000M8500G 500GB                      | 2         | 0.71%   |
| Kingston RBUSNS8154P3512GJ1 512GB                | 2         | 0.71%   |
| Kingston OM8PCP3512F-AI1 512GB                   | 2         | 0.71%   |
| Kingston NVMe SSD Drive 512GB                    | 2         | 0.71%   |
| Intel SSDPEKNU512GZ 512GB                        | 2         | 0.71%   |
| HGST HTS541010A9E680 1TB                         | 2         | 0.71%   |
| ASMT 2115 320GB                                  | 2         | 0.71%   |
| ZHITAI TiPro7000 1TB                             | 1         | 0.35%   |
| Yangtze Memory NVMe SSD Drive 1TB                | 1         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 20        | 21     | 28.17%  |
| HGST               | 17        | 18     | 23.94%  |
| WDC                | 11        | 13     | 15.49%  |
| Toshiba            | 10        | 11     | 14.08%  |
| Hitachi            | 7         | 8      | 9.86%   |
| ASMT               | 3         | 3      | 4.23%   |
| StoreJet           | 1         | 2      | 1.41%   |
| NeoTech            | 1         | 1      | 1.41%   |
| JMicron Technology | 1         | 3      | 1.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 20        | 25     | 23.26%  |
| Kingston            | 9         | 10     | 10.47%  |
| SanDisk             | 7         | 9      | 8.14%   |
| Samsung Electronics | 7         | 9      | 8.14%   |
| WDC                 | 5         | 7      | 5.81%   |
| Micron Technology   | 4         | 4      | 4.65%   |
| Intel               | 4         | 5      | 4.65%   |
| Transcend           | 3         | 3      | 3.49%   |
| Toshiba             | 3         | 3      | 3.49%   |
| SK hynix            | 3         | 3      | 3.49%   |
| A-DATA Technology   | 3         | 3      | 3.49%   |
| Unknown             | 3         | 3      | 3.49%   |
| SPCC                | 2         | 3      | 2.33%   |
| Plextor             | 1         | 1      | 1.16%   |
| Patriot             | 1         | 1      | 1.16%   |
| OCZ                 | 1         | 1      | 1.16%   |
| MyDigitalSSD        | 1         | 1      | 1.16%   |
| MX                  | 1         | 1      | 1.16%   |
| LITEONIT            | 1         | 1      | 1.16%   |
| LITEON              | 1         | 1      | 1.16%   |
| JMicron Technology  | 1         | 1      | 1.16%   |
| Aura                | 1         | 1      | 1.16%   |
| ASMT                | 1         | 1      | 1.16%   |
| Apple               | 1         | 1      | 1.16%   |
| Apacer              | 1         | 1      | 1.16%   |
| AGI                 | 1         | 1      | 1.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 87        | 122    | 34.66%  |
| SSD     | 80        | 100    | 31.87%  |
| HDD     | 67        | 80     | 26.69%  |
| MMC     | 9         | 10     | 3.59%   |
| Unknown | 8         | 9      | 3.19%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 127       | 171    | 53.81%  |
| NVMe | 87        | 122    | 36.86%  |
| SAS  | 13        | 18     | 5.51%   |
| MMC  | 9         | 10     | 3.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 88        | 107    | 59.46%  |
| 0.51-1.0   | 54        | 65     | 36.49%  |
| 1.01-2.0   | 4         | 5      | 2.7%    |
| 3.01-4.0   | 1         | 2      | 0.68%   |
| 10.01-20.0 | 1         | 1      | 0.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 61        | 30.2%   |
| 101-250        | 57        | 28.22%  |
| 501-1000       | 27        | 13.37%  |
| 1-20           | 15        | 7.43%   |
| 1001-2000      | 13        | 6.44%   |
| 21-50          | 11        | 5.45%   |
| 51-100         | 11        | 5.45%   |
| 2001-3000      | 3         | 1.49%   |
| Unknown        | 3         | 1.49%   |
| More than 3000 | 1         | 0.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 90        | 44.12%  |
| 21-50          | 29        | 14.22%  |
| 101-250        | 26        | 12.75%  |
| 51-100         | 25        | 12.25%  |
| 251-500        | 20        | 9.8%    |
| 501-1000       | 10        | 4.9%    |
| Unknown        | 3         | 1.47%   |
| More than 3000 | 1         | 0.49%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 14.29%  |
| SK hynix HFS128G39MNC-2300A 128GB SSD          | 1         | 1      | 14.29%  |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 14.29%  |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 14.29%  |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 14.29%  |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 14.29%  |
| ASMT 2115 320GB                                | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| SK hynix          | 2         | 2      | 28.57%  |
| Seagate           | 1         | 1      | 14.29%  |
| Micron Technology | 1         | 1      | 14.29%  |
| Hitachi           | 1         | 1      | 14.29%  |
| HGST              | 1         | 1      | 14.29%  |
| ASMT              | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 25%     |
| Hitachi | 1         | 1      | 25%     |
| HGST    | 1         | 1      | 25%     |
| ASMT    | 1         | 1      | 25%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 4      | 57.14%  |
| SSD  | 2         | 2      | 28.57%  |
| NVMe | 1         | 1      | 14.29%  |

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
| Detected | 104       | 164    | 50.73%  |
| Works    | 94        | 150    | 45.85%  |
| Malfunc  | 7         | 7      | 3.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 138       | 54.98%  |
| SanDisk                        | 23        | 9.16%   |
| Samsung Electronics            | 23        | 9.16%   |
| AMD                            | 20        | 7.97%   |
| SK hynix                       | 15        | 5.98%   |
| Kingston Technology Company    | 9         | 3.59%   |
| Micron Technology              | 6         | 2.39%   |
| Toshiba America Info Systems   | 4         | 1.59%   |
| Micron/Crucial Technology      | 4         | 1.59%   |
| Yangtze Memory Technologies    | 1         | 0.4%    |
| Union Memory (Shenzhen)        | 1         | 0.4%    |
| Solid State Storage Technology | 1         | 0.4%    |
| Silicon Motion                 | 1         | 0.4%    |
| Phison Electronics             | 1         | 0.4%    |
| MAXIO Technology (Hangzhou)    | 1         | 0.4%    |
| Marvell Technology Group       | 1         | 0.4%    |
| Lite-On Technology             | 1         | 0.4%    |
| ADATA Technology               | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 7.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 6.9%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 14        | 5.36%   |
| Intel Volume Management Device NVMe RAID Controller                            | 13        | 4.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 4.98%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 4.6%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 9         | 3.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 3.45%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 3.45%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 3.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.07%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.68%   |
| Micron Non-Volatile memory controller                                          | 6         | 2.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 2.3%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 5         | 1.92%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 1.92%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 1.92%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.53%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 1.53%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.15%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.15%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.15%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.15%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.77%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.77%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 2         | 0.77%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.77%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.77%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 0.77%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.77%   |
| Intel Non-Volatile memory controller                                           | 2         | 0.77%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 0.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.77%   |
| Yangtze Memory ZHITAI TiPro7000                                                | 1         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 138       | 54.98%  |
| NVMe | 88        | 35.06%  |
| RAID | 21        | 8.37%   |
| IDE  | 4         | 1.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 161       | 83.42%  |
| AMD    | 32        | 16.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz          | 7         | 3.63%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 6         | 3.11%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 6         | 3.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 5         | 2.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 4         | 2.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 2.07%   |
| Intel Core i7-4500U CPU @ 1.80GHz          | 4         | 2.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 4         | 2.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 4         | 2.07%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 3         | 1.55%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 3         | 1.55%   |
| Intel Core i5-3230M CPU @ 2.60GHz          | 3         | 1.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 3         | 1.55%   |
| Intel 12th Gen Core i5-12500H              | 3         | 1.55%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 3         | 1.55%   |
| AMD Ryzen 7 4800HS with Radeon Graphics    | 3         | 1.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.04%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 2         | 1.04%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.04%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 2         | 1.04%   |
| Intel Core i7-2670QM CPU @ 2.20GHz         | 2         | 1.04%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 2         | 1.04%   |
| Intel Core i5-8300H CPU @ 2.30GHz          | 2         | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 2         | 1.04%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 2         | 1.04%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 2         | 1.04%   |
| Intel Core i5-2450M CPU @ 2.50GHz          | 2         | 1.04%   |
| Intel Core i5-2410M CPU @ 2.30GHz          | 2         | 1.04%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz         | 2         | 1.04%   |
| Intel Core i5 CPU M 520 @ 2.40GHz          | 2         | 1.04%   |
| Intel Core i5 CPU M 460 @ 2.53GHz          | 2         | 1.04%   |
| Intel Core i3-2330M CPU @ 2.20GHz          | 2         | 1.04%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 2         | 1.04%   |
| Intel Celeron CPU 3955U @ 2.00GHz          | 2         | 1.04%   |
| Intel 12th Gen Core i7-1260P               | 2         | 1.04%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz    | 2         | 1.04%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 1.04%   |
| AMD Ryzen 7 5800U with Radeon Graphics     | 2         | 1.04%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 2         | 1.04%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 2         | 1.04%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 52        | 26.94%  |
| Intel Core i5      | 52        | 26.94%  |
| Other              | 24        | 12.44%  |
| AMD Ryzen 7        | 13        | 6.74%   |
| Intel Core i3      | 8         | 4.15%   |
| Intel Celeron      | 7         | 3.63%   |
| AMD Ryzen 5        | 7         | 3.63%   |
| Intel Pentium      | 6         | 3.11%   |
| Intel Genuine      | 3         | 1.55%   |
| Intel Core 2 Duo   | 3         | 1.55%   |
| Intel Atom         | 3         | 1.55%   |
| AMD Ryzen 9        | 3         | 1.55%   |
| AMD Ryzen 7 PRO    | 3         | 1.55%   |
| AMD Ryzen 3        | 2         | 1.04%   |
| Intel Xeon         | 1         | 0.52%   |
| Intel Pentium M    | 1         | 0.52%   |
| Intel Pentium Dual | 1         | 0.52%   |
| Intel Core 2 Solo  | 1         | 0.52%   |
| AMD FX             | 1         | 0.52%   |
| AMD Embedded       | 1         | 0.52%   |
| AMD E2             | 1         | 0.52%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 76        | 39.38%  |
| 2      | 69        | 35.75%  |
| 8      | 22        | 11.4%   |
| 6      | 13        | 6.74%   |
| 12     | 5         | 2.59%   |
| 1      | 5         | 2.59%   |
| 10     | 2         | 1.04%   |
| 14     | 1         | 0.52%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 193       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 158       | 81.87%  |
| 1      | 35        | 18.13%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 190       | 98.45%  |
| 32-bit         | 2         | 1.04%   |
| Unknown        | 1         | 0.52%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 38        | 19.19%  |
| 0x306a9    | 12        | 6.06%   |
| 0x806c1    | 11        | 5.56%   |
| 0x40651    | 10        | 5.05%   |
| 0x206a7    | 10        | 5.05%   |
| 0x806ea    | 8         | 4.04%   |
| 0x906e9    | 7         | 3.54%   |
| 0x806eb    | 7         | 3.54%   |
| 0x806e9    | 6         | 3.03%   |
| 0x20655    | 6         | 3.03%   |
| 0x0a50000c | 6         | 3.03%   |
| 0x906ea    | 5         | 2.53%   |
| 0x506e3    | 5         | 2.53%   |
| 0x406e3    | 5         | 2.53%   |
| 0x306d4    | 5         | 2.53%   |
| 0x806ec    | 4         | 2.02%   |
| 0x706e5    | 4         | 2.02%   |
| 0x08608103 | 4         | 2.02%   |
| 0x08600106 | 4         | 2.02%   |
| 0x906a3    | 3         | 1.52%   |
| 0x1067a    | 3         | 1.52%   |
| 0x906ed    | 2         | 1.01%   |
| 0x906a4    | 2         | 1.01%   |
| 0x706a8    | 2         | 1.01%   |
| 0x6fd      | 2         | 1.01%   |
| 0x406c4    | 2         | 1.01%   |
| 0x306c3    | 2         | 1.01%   |
| 0x08600104 | 2         | 1.01%   |
| 0x806d1    | 1         | 0.51%   |
| 0x706a1    | 1         | 0.51%   |
| 0x506c9    | 1         | 0.51%   |
| 0x406c3    | 1         | 0.51%   |
| 0x40661    | 1         | 0.51%   |
| 0x306a8    | 1         | 0.51%   |
| 0x30678    | 1         | 0.51%   |
| 0x20652    | 1         | 0.51%   |
| 0x106e5    | 1         | 0.51%   |
| 0x106c2    | 1         | 0.51%   |
| 0x10676    | 1         | 0.51%   |
| 0x0a404101 | 1         | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 47        | 24.35%  |
| IvyBridge        | 14        | 7.25%   |
| Haswell          | 14        | 7.25%   |
| Skylake          | 13        | 6.74%   |
| SandyBridge      | 13        | 6.74%   |
| TigerLake        | 12        | 6.22%   |
| Unknown          | 11        | 5.7%    |
| Zen 2            | 10        | 5.18%   |
| Westmere         | 10        | 5.18%   |
| Zen 3            | 9         | 4.66%   |
| Penryn           | 5         | 2.59%   |
| IceLake          | 5         | 2.59%   |
| Broadwell        | 5         | 2.59%   |
| Alderlake Hybrid | 5         | 2.59%   |
| Silvermont       | 4         | 2.07%   |
| Goldmont plus    | 3         | 1.55%   |
| Excavator        | 3         | 1.55%   |
| Zen+             | 2         | 1.04%   |
| Core             | 2         | 1.04%   |
| Zen              | 1         | 0.52%   |
| P6               | 1         | 0.52%   |
| Nehalem          | 1         | 0.52%   |
| Goldmont         | 1         | 0.52%   |
| Bonnell          | 1         | 0.52%   |
| Bobcat           | 1         | 0.52%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 151       | 54.51%  |
| Nvidia | 77        | 27.8%   |
| AMD    | 49        | 17.69%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 13        | 4.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 13        | 4.64%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 12        | 4.29%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 3.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 10        | 3.57%   |
| AMD Renoir                                                                               | 10        | 3.57%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.21%   |
| Intel HD Graphics 630                                                                    | 8         | 2.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.86%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.86%   |
| Intel HD Graphics 530                                                                    | 7         | 2.5%    |
| Intel HD Graphics 620                                                                    | 6         | 2.14%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 6         | 2.14%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.14%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.79%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.79%   |
| AMD Lucienne                                                                             | 5         | 1.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.43%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 1.43%   |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 1.07%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.07%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 1.07%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 1.07%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 1.07%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.07%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.07%   |
| Intel HD Graphics 510                                                                    | 3         | 1.07%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.07%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.07%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.07%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.07%   |
| AMD Barcelo                                                                              | 3         | 1.07%   |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.71%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.71%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.71%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.71%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 37.31%  |
| Intel + Nvidia | 67        | 34.72%  |
| 1 x AMD        | 31        | 16.06%  |
| Intel + AMD    | 12        | 6.22%   |
| 1 x Nvidia     | 5         | 2.59%   |
| AMD + Nvidia   | 5         | 2.59%   |
| 2 x AMD        | 1         | 0.52%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 154       | 78.17%  |
| Proprietary | 39        | 19.8%   |
| Unknown     | 4         | 2.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 110       | 55.56%  |
| 1.01-2.0   | 32        | 16.16%  |
| 0.01-0.5   | 29        | 14.65%  |
| 3.01-4.0   | 12        | 6.06%   |
| 0.51-1.0   | 8         | 4.04%   |
| 5.01-6.0   | 6         | 3.03%   |
| 7.01-8.0   | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 57        | 26.15%  |
| Chimei Innolux          | 32        | 14.68%  |
| BOE                     | 31        | 14.22%  |
| LG Display              | 28        | 12.84%  |
| Samsung Electronics     | 12        | 5.5%    |
| Ancor Communications    | 8         | 3.67%   |
| BenQ                    | 6         | 2.75%   |
| Sharp                   | 5         | 2.29%   |
| Dell                    | 5         | 2.29%   |
| PANDA                   | 3         | 1.38%   |
| Lenovo                  | 3         | 1.38%   |
| ASUSTek Computer        | 3         | 1.38%   |
| Acer                    | 3         | 1.38%   |
| ViewSonic               | 2         | 0.92%   |
| Philips                 | 2         | 0.92%   |
| Eizo                    | 2         | 0.92%   |
| TMX                     | 1         | 0.46%   |
| Sony                    | 1         | 0.46%   |
| Panasonic               | 1         | 0.46%   |
| Olevia                  | 1         | 0.46%   |
| NEX                     | 1         | 0.46%   |
| MStar                   | 1         | 0.46%   |
| LG Philips              | 1         | 0.46%   |
| InfoVision              | 1         | 0.46%   |
| Goldstar                | 1         | 0.46%   |
| CHR                     | 1         | 0.46%   |
| Chi Mei Optoelectronics | 1         | 0.46%   |
| BOE Technology Group    | 1         | 0.46%   |
| AVX                     | 1         | 0.46%   |
| Apple                   | 1         | 0.46%   |
| AOC                     | 1         | 0.46%   |
| AGT                     | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 2.27%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 4         | 1.82%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 3         | 1.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 1.36%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 1.36%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 1.36%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.36%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.91%   |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch              | 2         | 0.91%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.91%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 0.91%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.91%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.91%   |
| BOE LCD Monitor BOE08A6 1920x1080 294x165mm 13.3-inch                 | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO332C 1366x768 293x164mm 13.2-inch         | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.91%   |
| AU Optronics LCD Monitor AUO253D 1920x1080 309x174mm 14.0-inch        | 2         | 0.91%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 530x300mm 24.0-inch          | 2         | 0.91%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 2         | 0.91%   |
| ViewSonic VX2376 Series VSC3B32 1920x1080 509x286mm 23.0-inch         | 1         | 0.45%   |
| ViewSonic VA2732-FHD VSC0D3A 1920x1080 598x336mm 27.0-inch            | 1         | 0.45%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.45%   |
| Sony TV SNY8200 1920x1080 560x420mm 27.6-inch                         | 1         | 0.45%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 1         | 0.45%   |
| Sharp LQ133M1JW07 SHP1435 1920x1080 294x165mm 13.3-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.45%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3052 1024x600 223x125mm 10.1-inch  | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 111       | 56.63%  |
| 1366x768 (WXGA)    | 43        | 21.94%  |
| 3840x2160 (4K)     | 8         | 4.08%   |
| 2560x1440 (QHD)    | 4         | 2.04%   |
| 1600x900 (HD+)     | 4         | 2.04%   |
| 2880x1800          | 3         | 1.53%   |
| 2560x1600          | 3         | 1.53%   |
| 1920x1200 (WUXGA)  | 3         | 1.53%   |
| 1680x1050 (WSXGA+) | 2         | 1.02%   |
| 1280x800 (WXGA)    | 2         | 1.02%   |
| 3840x1080          | 1         | 0.51%   |
| 3200x1800 (QHD+)   | 1         | 0.51%   |
| 2560x1080          | 1         | 0.51%   |
| 2288x1287          | 1         | 0.51%   |
| 2256x1504          | 1         | 0.51%   |
| 2160x1440          | 1         | 0.51%   |
| 2048x1152          | 1         | 0.51%   |
| 1680x945           | 1         | 0.51%   |
| 1440x900 (WXGA+)   | 1         | 0.51%   |
| 1280x720 (HD)      | 1         | 0.51%   |
| 1280x1024 (SXGA)   | 1         | 0.51%   |
| 1024x600           | 1         | 0.51%   |
| Unknown            | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 71        | 32.72%  |
| 14      | 40        | 18.43%  |
| 13      | 39        | 17.97%  |
| 24      | 12        | 5.53%   |
| 23      | 10        | 4.61%   |
| 27      | 8         | 3.69%   |
| 17      | 8         | 3.69%   |
| 11      | 6         | 2.76%   |
| 21      | 4         | 1.84%   |
| 12      | 4         | 1.84%   |
| 22      | 3         | 1.38%   |
| 16      | 3         | 1.38%   |
| 18      | 2         | 0.92%   |
| Unknown | 2         | 0.92%   |
| 55      | 1         | 0.46%   |
| 52      | 1         | 0.46%   |
| 34      | 1         | 0.46%   |
| 31      | 1         | 0.46%   |
| 10      | 1         | 0.46%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 131       | 60.65%  |
| 201-300     | 31        | 14.35%  |
| 501-600     | 27        | 12.5%   |
| 351-400     | 10        | 4.63%   |
| 401-500     | 9         | 4.17%   |
| 601-700     | 3         | 1.39%   |
| 1001-1500   | 2         | 0.93%   |
| Unknown     | 2         | 0.93%   |
| 701-800     | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 166       | 88.3%   |
| 16/10   | 18        | 9.57%   |
| 3/2     | 2         | 1.06%   |
| 21/9    | 1         | 0.53%   |
| Unknown | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 71        | 32.87%  |
| 81-90          | 62        | 28.7%   |
| 201-250        | 26        | 12.04%  |
| 71-80          | 18        | 8.33%   |
| 301-350        | 8         | 3.7%    |
| 121-130        | 8         | 3.7%    |
| 51-60          | 6         | 2.78%   |
| 61-70          | 3         | 1.39%   |
| 111-120        | 3         | 1.39%   |
| More than 1000 | 2         | 0.93%   |
| 351-500        | 2         | 0.93%   |
| 251-300        | 2         | 0.93%   |
| 141-150        | 2         | 0.93%   |
| Unknown        | 2         | 0.93%   |
| 41-50          | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 104       | 48.37%  |
| 101-120       | 45        | 20.93%  |
| 51-100        | 32        | 14.88%  |
| 161-240       | 22        | 10.23%  |
| More than 240 | 8         | 3.72%   |
| 1-50          | 2         | 0.93%   |
| Unknown       | 2         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 159       | 81.12%  |
| 2     | 31        | 15.82%  |
| 0     | 4         | 2.04%   |
| 3     | 2         | 1.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 117       | 36.68%  |
| Realtek Semiconductor    | 97        | 30.41%  |
| Qualcomm Atheros         | 51        | 15.99%  |
| Broadcom                 | 19        | 5.96%   |
| MediaTek                 | 10        | 3.13%   |
| Broadcom Limited         | 5         | 1.57%   |
| ASIX Electronics         | 4         | 1.25%   |
| Ralink                   | 3         | 0.94%   |
| TP-Link                  | 2         | 0.63%   |
| OPPO Electronics         | 2         | 0.63%   |
| Marvell Technology Group | 2         | 0.63%   |
| Edimax Technology        | 2         | 0.63%   |
| U-Blox                   | 1         | 0.31%   |
| Lenovo                   | 1         | 0.31%   |
| Google                   | 1         | 0.31%   |
| D-Link                   | 1         | 0.31%   |
| ASUSTek Computer         | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 18.66%  |
| Intel Wi-Fi 6 AX200                                               | 16        | 4.46%   |
| Intel Wireless 8265 / 8275                                        | 12        | 3.34%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 3.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 2.79%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 2.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 2.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 1.95%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 1.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 1.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 1.67%   |
| Intel Wireless 7260                                               | 6         | 1.67%   |
| Intel Wireless 3165                                               | 6         | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 1.39%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.39%   |
| Intel Wireless 7265                                               | 5         | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 1.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 1.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 1.11%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.11%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.11%   |
| Broadcom BCM43225 802.11b/g/n                                     | 4         | 1.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.84%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.84%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.84%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.84%   |
| Intel Wireless 8260                                               | 3         | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.84%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.84%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.84%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.84%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 111       | 58.12%  |
| Qualcomm Atheros      | 35        | 18.32%  |
| Realtek Semiconductor | 12        | 6.28%   |
| Broadcom              | 12        | 6.28%   |
| MediaTek              | 10        | 5.24%   |
| Ralink                | 3         | 1.57%   |
| Broadcom Limited      | 3         | 1.57%   |
| Edimax Technology     | 2         | 1.05%   |
| TP-Link               | 1         | 0.52%   |
| D-Link                | 1         | 0.52%   |
| ASUSTek Computer      | 1         | 0.52%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 16        | 8.38%   |
| Intel Wireless 8265 / 8275                                     | 12        | 6.28%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 5.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 4.19%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 3.66%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 7         | 3.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 7         | 3.66%   |
| Intel Wireless 7260                                            | 6         | 3.14%   |
| Intel Wireless 3165                                            | 6         | 3.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 2.62%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 2.62%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 2.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 2.62%   |
| Intel Wireless 7265                                            | 5         | 2.62%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 2.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 2.09%   |
| Broadcom BCM43225 802.11b/g/n                                  | 4         | 2.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.57%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 1.57%   |
| Intel Wireless 8260                                            | 3         | 1.57%   |
| Intel Centrino Advanced-N 6235                                 | 3         | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 1.57%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.05%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.05%   |
| Intel Wireless-AC 9260                                         | 2         | 1.05%   |
| Intel Wireless 3160                                            | 2         | 1.05%   |
| Intel WiFi Link 5100                                           | 2         | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.05%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.05%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.05%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.05%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.05%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.52%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.52%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.52%   |
| Realtek 802.11ac NIC                                           | 1         | 0.52%   |
| Ralink RT3091 Wireless 802.11n 1T/2R PCIe                      | 1         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 90        | 55.56%  |
| Intel                    | 26        | 16.05%  |
| Qualcomm Atheros         | 25        | 15.43%  |
| Broadcom                 | 8         | 4.94%   |
| ASIX Electronics         | 4         | 2.47%   |
| OPPO Electronics         | 2         | 1.23%   |
| Marvell Technology Group | 2         | 1.23%   |
| Broadcom Limited         | 2         | 1.23%   |
| TP-Link                  | 1         | 0.62%   |
| Lenovo                   | 1         | 0.62%   |
| Google                   | 1         | 0.62%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 67        | 40.12%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 5.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 5.99%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 3.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 2.99%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 2.4%    |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 2.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.8%    |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.8%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.8%    |
| Intel I211 Gigabit Network Connection                             | 3         | 1.8%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.8%    |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.8%    |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.8%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.2%    |
| OPPO RMX3263                                                      | 2         | 1.2%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.2%    |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 1.2%    |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.6%    |
| Realtek Realtek Ethernet controller                               | 1         | 0.6%    |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.6%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.6%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.6%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.6%    |
| Lenovo USB-C Hub                                                  | 1         | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 1         | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.6%    |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.6%    |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.6%    |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.6%    |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 185       | 55.06%  |
| Ethernet | 150       | 44.64%  |
| Modem    | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 151       | 74.02%  |
| Ethernet | 53        | 25.98%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 137       | 70.98%  |
| 1     | 55        | 28.5%   |
| 5     | 1         | 0.52%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 177       | 91.71%  |
| Yes  | 16        | 8.29%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 99        | 57.56%  |
| Broadcom                        | 13        | 7.56%   |
| Qualcomm Atheros Communications | 12        | 6.98%   |
| Foxconn / Hon Hai               | 12        | 6.98%   |
| Lite-On Technology              | 9         | 5.23%   |
| IMC Networks                    | 9         | 5.23%   |
| Realtek Semiconductor           | 5         | 2.91%   |
| Realtek                         | 3         | 1.74%   |
| Ralink                          | 2         | 1.16%   |
| Hewlett-Packard                 | 2         | 1.16%   |
| ASUSTek Computer                | 2         | 1.16%   |
| Apple                           | 2         | 1.16%   |
| Toshiba                         | 1         | 0.58%   |
| MediaTek                        | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 36        | 20.93%  |
| Intel AX201 Bluetooth                             | 18        | 10.47%  |
| Intel AX200 Bluetooth                             | 16        | 9.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 13        | 7.56%   |
| Intel Bluetooth Device                            | 6         | 3.49%   |
| Qualcomm Atheros AR3011 Bluetooth                 | 5         | 2.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 5         | 2.91%   |
| Foxconn / Hon Hai Wireless_Device                 | 5         | 2.91%   |
| Realtek Bluetooth Radio                           | 4         | 2.33%   |
| Realtek Bluetooth Radio                           | 3         | 1.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 3         | 1.74%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 3         | 1.74%   |
| IMC Networks Bluetooth Device                     | 3         | 1.74%   |
| Foxconn / Hon Hai Bluetooth Device                | 3         | 1.74%   |
| Broadcom BCM2045B (BDC-2.1)                       | 3         | 1.74%   |
| Ralink RT3290 Bluetooth                           | 2         | 1.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 2         | 1.16%   |
| Lite-On Bluetooth Device                          | 2         | 1.16%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 1.16%   |
| Intel Wireless-AC 3168 Bluetooth                  | 2         | 1.16%   |
| Intel AX210 Bluetooth                             | 2         | 1.16%   |
| IMC Networks Wireless_Device                      | 2         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 1.16%   |
| Foxconn / Hon Hai Acer Bluetooth module           | 2         | 1.16%   |
| Broadcom Bluetooth                                | 2         | 1.16%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]        | 2         | 1.16%   |
| Broadcom BCM2045 Bluetooth                        | 2         | 1.16%   |
| Apple Bluetooth Host Controller                   | 2         | 1.16%   |
| Toshiba Bluetooth USB Host Controller             | 1         | 0.58%   |
| Realtek RTL8723B Bluetooth                        | 1         | 0.58%   |
| Qualcomm Atheros  Bluetooth Device                | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.58%   |
| MediaTek Wireless_Device                          | 1         | 0.58%   |
| Lite-On Wireless_Device                           | 1         | 0.58%   |
| Lite-On Atheros AR3012 Bluetooth                  | 1         | 0.58%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.58%   |
| IMC Networks Bluetooth USB Host Controller        | 1         | 0.58%   |
| IMC Networks Bluetooth Radio                      | 1         | 0.58%   |
| IMC Networks Bluetooth                            | 1         | 0.58%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 158       | 67.23%  |
| AMD                     | 39        | 16.6%   |
| Nvidia                  | 31        | 13.19%  |
| Realtek Semiconductor   | 1         | 0.43%   |
| GN Netcom               | 1         | 0.43%   |
| ESS Technology          | 1         | 0.43%   |
| Dell                    | 1         | 0.43%   |
| Cambridge Silicon Radio | 1         | 0.43%   |
| C-Media Electronics     | 1         | 0.43%   |
| ASUSTek Computer        | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 28        | 9.72%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 24        | 8.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 22        | 7.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 4.51%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 12        | 4.17%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 3.82%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 3.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 3.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 10        | 3.47%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 3.47%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 2.78%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 2.78%   |
| Intel CM238 HD Audio Controller                                            | 7         | 2.43%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 2.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 1.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.74%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.74%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 1.39%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.39%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.39%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.39%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 1.04%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.04%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.69%   |
| Intel USB PnP Sound Device                                                 | 2         | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.69%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.35%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.35%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.35%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.35%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.35%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 39        | 25.32%  |
| Samsung Electronics | 33        | 21.43%  |
| Micron Technology   | 21        | 13.64%  |
| Kingston            | 17        | 11.04%  |
| Crucial             | 14        | 9.09%   |
| Transcend           | 6         | 3.9%    |
| Unknown             | 5         | 3.25%   |
| Apacer              | 3         | 1.95%   |
| Ramaxel Technology  | 2         | 1.3%    |
| G-Alantic           | 2         | 1.3%    |
| A-DATA Technology   | 2         | 1.3%    |
| Unknown (ABCD)      | 1         | 0.65%   |
| Unknown (08AE)      | 1         | 0.65%   |
| Patriot             | 1         | 0.65%   |
| Nanya Technology    | 1         | 0.65%   |
| Goldkey             | 1         | 0.65%   |
| G.Skill             | 1         | 0.65%   |
| Elpida              | 1         | 0.65%   |
| Avant               | 1         | 0.65%   |
| ASint Technology    | 1         | 0.65%   |
| Unknown             | 1         | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.79%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 1.79%   |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s           | 3         | 1.79%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 1.19%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.19%   |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 2         | 1.19%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.19%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 1.19%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.19%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.19%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.19%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.19%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.19%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.19%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.19%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 2         | 1.19%   |
| G-Alantic RAM D4SS12161SH26A-C 4GB SODIMM DDR4 2133MT/s          | 2         | 1.19%   |
| Crucial RAM CT8G4SFS8266.M8FE 8GB SODIMM DDR4 2667MT/s           | 2         | 1.19%   |
| Crucial RAM CT8G4SFS632A.C4FE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.19%   |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 1.19%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.6%    |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.6%    |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.6%    |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.6%    |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.6%    |
| Unknown RAM Module 1024MB SODIMM DDR2 800MT/s                    | 1         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.6%    |
| Unknown (08AE) RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.6%    |
| Transcend RAM TS512MSK64W6H 4GB SODIMM DDR3 1600MT/s             | 1         | 0.6%    |
| Transcend RAM TS512MSK64V6N 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.6%    |
| Transcend RAM Module 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.6%    |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.6%    |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 0.6%    |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.6%    |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.6%    |
| SK hynix RAM Module 4GB SODIMM LPDDR3 1600MT/s                   | 1         | 0.6%    |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.6%    |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.6%    |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                 | 1         | 0.6%    |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 69        | 56.56%  |
| DDR3    | 28        | 22.95%  |
| LPDDR4  | 12        | 9.84%   |
| LPDDR3  | 8         | 6.56%   |
| DDR2    | 2         | 1.64%   |
| LPDDR5  | 1         | 0.82%   |
| DDR5    | 1         | 0.82%   |
| Unknown | 1         | 0.82%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 100       | 81.97%  |
| Row Of Chips | 20        | 16.39%  |
| DIMM         | 1         | 0.82%   |
| Chip         | 1         | 0.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 58        | 43.61%  |
| 4096  | 37        | 27.82%  |
| 16384 | 22        | 16.54%  |
| 32768 | 7         | 5.26%   |
| 2048  | 7         | 5.26%   |
| 1024  | 2         | 1.5%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 36        | 28.13%  |
| 2667  | 23        | 17.97%  |
| 1600  | 22        | 17.19%  |
| 2400  | 11        | 8.59%   |
| 2133  | 9         | 7.03%   |
| 4267  | 4         | 3.13%   |
| 1334  | 4         | 3.13%   |
| 4266  | 3         | 2.34%   |
| 1867  | 3         | 2.34%   |
| 6400  | 2         | 1.56%   |
| 4800  | 2         | 1.56%   |
| 800   | 2         | 1.56%   |
| 8400  | 1         | 0.78%   |
| 3733  | 1         | 0.78%   |
| 3266  | 1         | 0.78%   |
| 2000  | 1         | 0.78%   |
| 1067  | 1         | 0.78%   |
| 1066  | 1         | 0.78%   |
| 533   | 1         | 0.78%   |

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
| Chicony Electronics                    | 46        | 28.4%   |
| IMC Networks                           | 24        | 14.81%  |
| Realtek Semiconductor                  | 19        | 11.73%  |
| Acer                                   | 11        | 6.79%   |
| Quanta                                 | 10        | 6.17%   |
| Sunplus Innovation Technology          | 9         | 5.56%   |
| Microdia                               | 9         | 5.56%   |
| Suyin                                  | 6         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.09%   |
| ALi                                    | 3         | 1.85%   |
| Syntek                                 | 2         | 1.23%   |
| Sunplus Technology                     | 2         | 1.23%   |
| Ricoh                                  | 2         | 1.23%   |
| Lite-On Technology                     | 2         | 1.23%   |
| Lenovo                                 | 2         | 1.23%   |
| Apple                                  | 2         | 1.23%   |
| Sonix Technology                       | 1         | 0.62%   |
| Silicon Motion                         | 1         | 0.62%   |
| Samsung Electronics                    | 1         | 0.62%   |
| Luxvisions Innotech Limited            | 1         | 0.62%   |
| Logitech                               | 1         | 0.62%   |
| Google                                 | 1         | 0.62%   |
| Generalplus Technology                 | 1         | 0.62%   |
| Foxconn / Hon Hai                      | 1         | 0.62%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 11        | 6.75%   |
| Chicony Integrated Camera                                                  | 9         | 5.52%   |
| Chicony HD WebCam                                                          | 8         | 4.91%   |
| Realtek Integrated_Webcam_HD                                               | 6         | 3.68%   |
| Chicony HP HD Camera                                                       | 5         | 3.07%   |
| Sunplus HD WebCam                                                          | 4         | 2.45%   |
| Quanta HD User Facing                                                      | 4         | 2.45%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 2.45%   |
| IMC Networks Integrated Camera                                             | 4         | 2.45%   |
| Acer HD Webcam                                                             | 4         | 2.45%   |
| Realtek HD WebCam                                                          | 3         | 1.84%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 1.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.84%   |
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 1.84%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.84%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.84%   |
| ALi Gateway Webcam                                                         | 3         | 1.84%   |
| Suyin 1.3M Front                                                           | 2         | 1.23%   |
| Sunplus 1.3M HD WebCam                                                     | 2         | 1.23%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.23%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.23%   |
| Realtek USB Camera                                                         | 2         | 1.23%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 1.23%   |
| IMC Networks UVC VGA Webcam                                                | 2         | 1.23%   |
| Chicony Webcam                                                             | 2         | 1.23%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 1.23%   |
| Chicony USB 2.0 Webcam Device                                              | 2         | 1.23%   |
| Chicony HD User Facing                                                     | 2         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.23%   |
| Acer Integrated Camera                                                     | 2         | 1.23%   |
| Acer BisonCam, NB Pro                                                      | 2         | 1.23%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.61%   |
| Syntek HP TrueVision HD                                                    | 1         | 0.61%   |
| Suyin UVC 1.3MPixel WebCam                                                 | 1         | 0.61%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 0.61%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 0.61%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 0.61%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.61%   |
| Sunplus HP Truevision HD                                                   | 1         | 0.61%   |
| Sunplus HD User Facing                                                     | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 11        | 25%     |
| Validity Sensors                   | 8         | 18.18%  |
| LighTuning Technology              | 8         | 18.18%  |
| Shenzhen Goodix Technology         | 6         | 13.64%  |
| Upek                               | 4         | 9.09%   |
| Elan Microelectronics              | 4         | 9.09%   |
| AuthenTec                          | 2         | 4.55%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                             | 4         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 4         | 9.09%   |
| Unknown                                                         | 4         | 9.09%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 3         | 6.82%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 3         | 6.82%   |
| Elan ELAN:Fingerprint                                           | 3         | 6.82%   |
| Validity Sensors VFS Fingerprint sensor                         | 2         | 4.55%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 2         | 4.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4.55%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4.55%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 2.27%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 2.27%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.27%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                    | 1         | 2.27%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 2.27%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 2.27%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.27%   |
| LighTuning Fingerprint Reader                                   | 1         | 2.27%   |
| Elan fingerprint sensor [FeinTech FPS00200]                     | 1         | 2.27%   |
| AuthenTec AES2810                                               | 1         | 2.27%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 1         | 2.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 36.36%  |
| Broadcom              | 3         | 27.27%  |
| Upek                  | 2         | 18.18%  |
| Lenovo                | 1         | 9.09%   |
| Gemalto (was Gemplus) | 1         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 27.27%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 18.18%  |
| Broadcom 58200                                                               | 2         | 18.18%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 9.09%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 9.09%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 9.09%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 9.09%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 114       | 57.29%  |
| 1     | 67        | 33.67%  |
| 2     | 16        | 8.04%   |
| 4     | 1         | 0.5%    |
| 3     | 1         | 0.5%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 44        | 45.36%  |
| Graphics card            | 21        | 21.65%  |
| Chipcard                 | 9         | 9.28%   |
| Camera                   | 5         | 5.15%   |
| Multimedia controller    | 4         | 4.12%   |
| Net/wireless             | 3         | 3.09%   |
| Card reader              | 3         | 3.09%   |
| Bluetooth                | 3         | 3.09%   |
| Net/ethernet             | 2         | 2.06%   |
| Storage/nvme             | 1         | 1.03%   |
| Sound                    | 1         | 1.03%   |
| Communication controller | 1         | 1.03%   |

