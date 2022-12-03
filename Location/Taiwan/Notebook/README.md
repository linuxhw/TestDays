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

Total: 287

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 38        | 18.63%  |
| Ubuntu 18.04       | 19        | 9.31%   |
| Ubuntu 22.04       | 15        | 7.35%   |
| Arch Rolling       | 8         | 3.92%   |
| Pop!_OS 20.04      | 5         | 2.45%   |
| OpenMandriva 4.2   | 5         | 2.45%   |
| Debian 11          | 5         | 2.45%   |
| Ubuntu 19.04       | 4         | 1.96%   |
| KDE neon 20.04     | 4         | 1.96%   |
| Fedora 36          | 4         | 1.96%   |
| Ubuntu 21.04       | 3         | 1.47%   |
| Ubuntu 19.10       | 3         | 1.47%   |
| Pop!_OS 21.04      | 3         | 1.47%   |
| OpenMandriva 4.3   | 3         | 1.47%   |
| Fedora 34          | 3         | 1.47%   |
| Debian Testing     | 3         | 1.47%   |
| Arch               | 3         | 1.47%   |
| Ubuntu 22.10       | 2         | 0.98%   |
| Ubuntu 20.10       | 2         | 0.98%   |
| Ubuntu 18.10       | 2         | 0.98%   |
| Ubuntu 16.04       | 2         | 0.98%   |
| Pop!_OS 21.10      | 2         | 0.98%   |
| OpenMandriva 4.50  | 2         | 0.98%   |
| Manjaro 21.2.2     | 2         | 0.98%   |
| Manjaro 21.1.3     | 2         | 0.98%   |
| Manjaro 21.1.0     | 2         | 0.98%   |
| Manjaro 20.1       | 2         | 0.98%   |
| Manjaro 20.0       | 2         | 0.98%   |
| Manjaro 18.0.0     | 2         | 0.98%   |
| Manjaro            | 2         | 0.98%   |
| Linux Mint 20.3    | 2         | 0.98%   |
| Linux Mint 20.1    | 2         | 0.98%   |
| Gentoo 2.7         | 2         | 0.98%   |
| Fedora 37          | 2         | 0.98%   |
| Fedora 35          | 2         | 0.98%   |
| Zorin 16           | 1         | 0.49%   |
| Zorin 15           | 1         | 0.49%   |
| Xubuntu 17.10      | 1         | 0.49%   |
| Xubuntu 16.04      | 1         | 0.49%   |
| Ubuntu Unity 16.04 | 1         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 87        | 45.31%  |
| Manjaro          | 19        | 9.9%    |
| Fedora           | 13        | 6.77%   |
| Arch             | 11        | 5.73%   |
| Pop!_OS          | 10        | 5.21%   |
| OpenMandriva     | 10        | 5.21%   |
| Debian           | 9         | 4.69%   |
| Linux Mint       | 6         | 3.13%   |
| KDE neon         | 4         | 2.08%   |
| Zorin            | 2         | 1.04%   |
| Xubuntu          | 2         | 1.04%   |
| Ubuntu MATE      | 2         | 1.04%   |
| Lubuntu          | 2         | 1.04%   |
| Kubuntu          | 2         | 1.04%   |
| Gentoo           | 2         | 1.04%   |
| Endless          | 2         | 1.04%   |
| Ubuntu Unity     | 1         | 0.52%   |
| Ubuntu Studio    | 1         | 0.52%   |
| Ubuntu Budgie    | 1         | 0.52%   |
| org.kde.Platform | 1         | 0.52%   |
| Nobara           | 1         | 0.52%   |
| Kali             | 1         | 0.52%   |
| EndeavourOS      | 1         | 0.52%   |
| Elementary       | 1         | 0.52%   |
| CentOS           | 1         | 0.52%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                     | Notebooks | Percent |
|-----------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002    | 5         | 2.35%   |
| 5.8.0-7630-generic          | 3         | 1.41%   |
| 5.4.0-42-generic            | 3         | 1.41%   |
| 5.3.0-46-generic            | 3         | 1.41%   |
| 5.3.0-40-generic            | 3         | 1.41%   |
| 5.16.7-desktop-1omv4003     | 3         | 1.41%   |
| 5.15.0-40-generic           | 3         | 1.41%   |
| 5.11.0-25-generic           | 3         | 1.41%   |
| 5.8.10-arch1-1              | 2         | 0.94%   |
| 5.8.0-53-generic            | 2         | 0.94%   |
| 5.8.0-43-generic            | 2         | 0.94%   |
| 5.4.64-1-MANJARO            | 2         | 0.94%   |
| 5.4.0-52-generic            | 2         | 0.94%   |
| 5.4.0-26-generic            | 2         | 0.94%   |
| 5.16.11-2-MANJARO           | 2         | 0.94%   |
| 5.13.15-1-MANJARO           | 2         | 0.94%   |
| 5.13.0-30-generic           | 2         | 0.94%   |
| 5.11.0-7620-generic         | 2         | 0.94%   |
| 5.11.0-43-generic           | 2         | 0.94%   |
| 5.11.0-41-generic           | 2         | 0.94%   |
| 5.11.0-27-generic           | 2         | 0.94%   |
| 5.10.0-8-amd64              | 2         | 0.94%   |
| 5.10.0-16-amd64             | 2         | 0.94%   |
| 4.18.0-17-generic           | 2         | 0.94%   |
| 4.18.0-15-generic           | 2         | 0.94%   |
| 4.15.0-47-generic           | 2         | 0.94%   |
| 4.15.0-43-generic           | 2         | 0.94%   |
| 6.0.8-300.fc37.x86_64       | 1         | 0.47%   |
| 6.0.7-201.fsync.fc36.x86_64 | 1         | 0.47%   |
| 6.0.2-301.fc36.x86_64       | 1         | 0.47%   |
| 6.0.0-2-amd64               | 1         | 0.47%   |
| 6.0.0-1-MANJARO             | 1         | 0.47%   |
| 5.9.16-200.fc33.x86_64      | 1         | 0.47%   |
| 5.9.0-4-amd64               | 1         | 0.47%   |
| 5.8.3-2-MANJARO             | 1         | 0.47%   |
| 5.8.18-1-MANJARO            | 1         | 0.47%   |
| 5.8.16-2-MANJARO            | 1         | 0.47%   |
| 5.8.0-59-generic            | 1         | 0.47%   |
| 5.8.0-49-generic            | 1         | 0.47%   |
| 5.8.0-44-generic            | 1         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 22        | 10.58%  |
| 5.8.0   | 13        | 6.25%   |
| 5.11.0  | 13        | 6.25%   |
| 5.15.0  | 12        | 5.77%   |
| 5.13.0  | 11        | 5.29%   |
| 4.18.0  | 9         | 4.33%   |
| 4.15.0  | 9         | 4.33%   |
| 5.10.0  | 8         | 3.85%   |
| 5.3.0   | 7         | 3.37%   |
| 5.0.0   | 7         | 3.37%   |
| 5.10.14 | 5         | 2.4%    |
| 5.19.0  | 4         | 1.92%   |
| 5.14.0  | 4         | 1.92%   |
| 5.16.7  | 3         | 1.44%   |
| 5.16.11 | 3         | 1.44%   |
| 6.0.0   | 2         | 0.96%   |
| 5.8.10  | 2         | 0.96%   |
| 5.7.1   | 2         | 0.96%   |
| 5.7.0   | 2         | 0.96%   |
| 5.4.64  | 2         | 0.96%   |
| 5.18.7  | 2         | 0.96%   |
| 5.17.5  | 2         | 0.96%   |
| 5.16.18 | 2         | 0.96%   |
| 5.15.21 | 2         | 0.96%   |
| 5.15.16 | 2         | 0.96%   |
| 5.13.15 | 2         | 0.96%   |
| 6.0.8   | 1         | 0.48%   |
| 6.0.7   | 1         | 0.48%   |
| 6.0.2   | 1         | 0.48%   |
| 5.9.16  | 1         | 0.48%   |
| 5.9.0   | 1         | 0.48%   |
| 5.8.3   | 1         | 0.48%   |
| 5.8.18  | 1         | 0.48%   |
| 5.8.16  | 1         | 0.48%   |
| 5.7.8   | 1         | 0.48%   |
| 5.7.4   | 1         | 0.48%   |
| 5.7.11  | 1         | 0.48%   |
| 5.6.7   | 1         | 0.48%   |
| 5.6.3   | 1         | 0.48%   |
| 5.6.15  | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 25        | 12.14%  |
| 5.15    | 24        | 11.65%  |
| 5.8     | 18        | 8.74%   |
| 5.10    | 18        | 8.74%   |
| 5.13    | 16        | 7.77%   |
| 5.11    | 15        | 7.28%   |
| 5.16    | 9         | 4.37%   |
| 4.18    | 9         | 4.37%   |
| 4.15    | 9         | 4.37%   |
| 5.0     | 8         | 3.88%   |
| 5.7     | 7         | 3.4%    |
| 5.3     | 7         | 3.4%    |
| 5.19    | 7         | 3.4%    |
| 5.14    | 6         | 2.91%   |
| 6.0     | 5         | 2.43%   |
| 5.6     | 4         | 1.94%   |
| 5.17    | 4         | 1.94%   |
| 5.18    | 3         | 1.46%   |
| 5.12    | 3         | 1.46%   |
| 5.9     | 2         | 0.97%   |
| 5.2     | 1         | 0.49%   |
| 4.4     | 1         | 0.49%   |
| 4.19    | 1         | 0.49%   |
| 4.14    | 1         | 0.49%   |
| 4.13    | 1         | 0.49%   |
| 4.10    | 1         | 0.49%   |
| 3.10    | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 181       | 97.84%  |
| i686   | 4         | 2.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 95        | 48.47%  |
| Unknown         | 35        | 17.86%  |
| KDE5            | 27        | 13.78%  |
| XFCE            | 8         | 4.08%   |
| X-Cinnamon      | 5         | 2.55%   |
| MATE            | 5         | 2.55%   |
| KDE             | 5         | 2.55%   |
| Openbox         | 2         | 1.02%   |
| LXQt            | 2         | 1.02%   |
| LXDE            | 2         | 1.02%   |
| i3              | 2         | 1.02%   |
| GNOME Flashback | 2         | 1.02%   |
| Deepin          | 2         | 1.02%   |
| Unity           | 1         | 0.51%   |
| sway            | 1         | 0.51%   |
| Pantheon        | 1         | 0.51%   |
| Budgie          | 1         | 0.51%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 141       | 74.6%   |
| Wayland | 26        | 13.76%  |
| Unknown | 18        | 9.52%   |
| Tty     | 4         | 2.12%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 84        | 43.3%   |
| GDM     | 37        | 19.07%  |
| SDDM    | 30        | 15.46%  |
| GDM3    | 22        | 11.34%  |
| LightDM | 14        | 7.22%   |
| TDM     | 4         | 2.06%   |
| SLiM    | 2         | 1.03%   |
| LXDM    | 1         | 0.52%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 91        | 47.64%  |
| zh_TW   | 54        | 28.27%  |
| Unknown | 27        | 14.14%  |
| zh_CN   | 4         | 2.09%   |
| ru_RU   | 3         | 1.57%   |
| en_GB   | 3         | 1.57%   |
| C       | 2         | 1.05%   |
| zh_SG   | 1         | 0.52%   |
| lzh_TW  | 1         | 0.52%   |
| ja_JP   | 1         | 0.52%   |
| en_SG   | 1         | 0.52%   |
| en_IE   | 1         | 0.52%   |
| de_DE   | 1         | 0.52%   |
| C.UTF8  | 1         | 0.52%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 116       | 61.7%   |
| BIOS | 72        | 38.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 157       | 83.96%  |
| Overlay | 10        | 5.35%   |
| Btrfs   | 7         | 3.74%   |
| Xfs     | 5         | 2.67%   |
| Unknown | 4         | 2.14%   |
| Ext2    | 2         | 1.07%   |
| Tmpfs   | 1         | 0.53%   |
| F2fs    | 1         | 0.53%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 90        | 48.13%  |
| GPT     | 82        | 43.85%  |
| MBR     | 15        | 8.02%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 164       | 87.7%   |
| Yes       | 23        | 12.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 108       | 57.75%  |
| Yes       | 79        | 42.25%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Acer                 | 38        | 20.54%  |
| ASUSTek Computer     | 35        | 18.92%  |
| Lenovo               | 24        | 12.97%  |
| Hewlett-Packard      | 24        | 12.97%  |
| Dell                 | 20        | 10.81%  |
| MSI                  | 16        | 8.65%   |
| Sony                 | 3         | 1.62%   |
| Unknown              | 3         | 1.62%   |
| Toshiba              | 2         | 1.08%   |
| LG Electronics       | 2         | 1.08%   |
| Lex                  | 2         | 1.08%   |
| Intel Client Systems | 2         | 1.08%   |
| Gigabyte Technology  | 2         | 1.08%   |
| Apple                | 2         | 1.08%   |
| win element          | 1         | 0.54%   |
| Vizio                | 1         | 0.54%   |
| Samsung Electronics  | 1         | 0.54%   |
| NEXCOM               | 1         | 0.54%   |
| Intel                | 1         | 0.54%   |
| HUAWEI               | 1         | 0.54%   |
| CJSCOPE              | 1         | 0.54%   |
| AVITA                | 1         | 0.54%   |
| AMI                  | 1         | 0.54%   |
| AMD                  | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 2.7%    |
| MSI GS63 7RE                             | 2         | 1.08%   |
| Lex 3I610DW                              | 2         | 1.08%   |
| Lenovo IdeaPad 5 14ALC05 82LM            | 2         | 1.08%   |
| HP Pavilion dv7                          | 2         | 1.08%   |
| Dell XPS 13 9380                         | 2         | 1.08%   |
| Acer Swift SF514-52T                     | 2         | 1.08%   |
| Acer Aspire 4755                         | 2         | 1.08%   |
| win element MBOX                         | 1         | 0.54%   |
| Vizio CT14                               | 1         | 0.54%   |
| Toshiba Satellite L850                   | 1         | 0.54%   |
| Toshiba PORTEGE R830                     | 1         | 0.54%   |
| Sony VPCCB15FW                           | 1         | 0.54%   |
| Sony SVS15115FWB                         | 1         | 0.54%   |
| Sony SVP13229PWB                         | 1         | 0.54%   |
| Samsung 700Z3A/700Z4A/700Z5A/700Z5B      | 1         | 0.54%   |
| NEXCOM B537-I                            | 1         | 0.54%   |
| MSI U270DX                               | 1         | 0.54%   |
| MSI PE72 8RD                             | 1         | 0.54%   |
| MSI PE62 8RD                             | 1         | 0.54%   |
| MSI PE60 6QE                             | 1         | 0.54%   |
| MSI P65 Creator 9SD                      | 1         | 0.54%   |
| MSI Modern 14 B11M                       | 1         | 0.54%   |
| MSI GV72 8RC                             | 1         | 0.54%   |
| MSI GT63 Titan 9SG                       | 1         | 0.54%   |
| MSI GS76 Stealth 11UH                    | 1         | 0.54%   |
| MSI GL65 9SD                             | 1         | 0.54%   |
| MSI GE70 2PE                             | 1         | 0.54%   |
| MSI GE70 0NC/GE70 0ND                    | 1         | 0.54%   |
| MSI GE62 6QD                             | 1         | 0.54%   |
| MSI CX62 6QD                             | 1         | 0.54%   |
| LG LE50-5BC6H1                           | 1         | 0.54%   |
| LG 16Z90P-G.AA78C                        | 1         | 0.54%   |
| Lenovo Z50-70 20354                      | 1         | 0.54%   |
| Lenovo XiaoXinAir 15ARE 2021 82GL        | 1         | 0.54%   |
| Lenovo V330-15IGM                        | 1         | 0.54%   |
| Lenovo ThinkPad X230 2324CD1             | 1         | 0.54%   |
| Lenovo ThinkPad X13 Gen 1 20UFS0BA00     | 1         | 0.54%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS0L800 | 1         | 0.54%   |
| Lenovo ThinkPad T510 4384CJ7             | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Acer Aspire       | 24        | 12.97%  |
| Lenovo ThinkPad   | 15        | 8.11%   |
| Dell Inspiron     | 8         | 4.32%   |
| HP Pavilion       | 7         | 3.78%   |
| Acer Swift        | 7         | 3.78%   |
| HP ProBook        | 6         | 3.24%   |
| ASUS VivoBook     | 6         | 3.24%   |
| ASUS ROG          | 6         | 3.24%   |
| Lenovo IdeaPad    | 5         | 2.7%    |
| Unknown           | 5         | 2.7%    |
| Dell Vostro       | 4         | 2.16%   |
| ASUS ZenBook      | 4         | 2.16%   |
| Acer TravelMate   | 4         | 2.16%   |
| HP EliteBook      | 3         | 1.62%   |
| Dell XPS          | 3         | 1.62%   |
| Dell Latitude     | 3         | 1.62%   |
| MSI GS63          | 2         | 1.08%   |
| MSI GE70          | 2         | 1.08%   |
| Lex 3I610DW       | 2         | 1.08%   |
| ASUS ASUS         | 2         | 1.08%   |
| win element MBOX  | 1         | 0.54%   |
| Vizio CT14        | 1         | 0.54%   |
| Toshiba Satellite | 1         | 0.54%   |
| Toshiba PORTEGE   | 1         | 0.54%   |
| Sony VPCCB15FW    | 1         | 0.54%   |
| Sony SVS15115FWB  | 1         | 0.54%   |
| Sony SVP13229PWB  | 1         | 0.54%   |
| Samsung 700Z3A    | 1         | 0.54%   |
| NEXCOM B537-I     | 1         | 0.54%   |
| MSI U270DX        | 1         | 0.54%   |
| MSI PE72          | 1         | 0.54%   |
| MSI PE62          | 1         | 0.54%   |
| MSI PE60          | 1         | 0.54%   |
| MSI P65           | 1         | 0.54%   |
| MSI Modern        | 1         | 0.54%   |
| MSI GV72          | 1         | 0.54%   |
| MSI GT63          | 1         | 0.54%   |
| MSI GS76          | 1         | 0.54%   |
| MSI GL65          | 1         | 0.54%   |
| MSI GE62          | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 23        | 12.43%  |
| 2019 | 19        | 10.27%  |
| 2020 | 18        | 9.73%   |
| 2017 | 18        | 9.73%   |
| 2018 | 16        | 8.65%   |
| 2012 | 12        | 6.49%   |
| 2016 | 11        | 5.95%   |
| 2014 | 11        | 5.95%   |
| 2011 | 11        | 5.95%   |
| 2015 | 10        | 5.41%   |
| 2022 | 9         | 4.86%   |
| 2013 | 7         | 3.78%   |
| 2009 | 7         | 3.78%   |
| 2010 | 6         | 3.24%   |
| 2008 | 4         | 2.16%   |
| 2007 | 1         | 0.54%   |
| 2006 | 1         | 0.54%   |
| 2004 | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 185       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 163       | 87.17%  |
| Enabled  | 24        | 12.83%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 185       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 57        | 30.16%  |
| 16.01-24.0  | 49        | 25.93%  |
| 8.01-16.0   | 33        | 17.46%  |
| 3.01-4.0    | 25        | 13.23%  |
| 32.01-64.0  | 11        | 5.82%   |
| 64.01-256.0 | 6         | 3.17%   |
| 24.01-32.0  | 3         | 1.59%   |
| 2.01-3.0    | 2         | 1.06%   |
| 1.01-2.0    | 2         | 1.06%   |
| 0.51-1.0    | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 62        | 30.39%  |
| 2.01-3.0   | 56        | 27.45%  |
| 4.01-8.0   | 34        | 16.67%  |
| 3.01-4.0   | 31        | 15.2%   |
| 8.01-16.0  | 9         | 4.41%   |
| 0.51-1.0   | 7         | 3.43%   |
| 24.01-32.0 | 2         | 0.98%   |
| 0.01-0.5   | 2         | 0.98%   |
| 32.01-64.0 | 1         | 0.49%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 118       | 61.78%  |
| 2      | 57        | 29.84%  |
| 3      | 9         | 4.71%   |
| 0      | 4         | 2.09%   |
| 4      | 2         | 1.05%   |
| 5      | 1         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 74.59%  |
| Yes       | 47        | 25.41%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 78.49%  |
| No        | 40        | 21.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 177       | 95.68%  |
| No        | 8         | 4.32%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 88.17%  |
| No        | 22        | 11.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Taiwan  | 185       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Taipei           | 62        | 31.16%  |
| New Taipei       | 31        | 15.58%  |
| Taoyuan District | 21        | 10.55%  |
| Hsinchu          | 19        | 9.55%   |
| Taichung         | 15        | 7.54%   |
| Kaohsiung City   | 11        | 5.53%   |
| Tainan City      | 7         | 3.52%   |
| Hsinchu County   | 4         | 2.01%   |
| Chang-hua        | 4         | 2.01%   |
| Zhudong          | 3         | 1.51%   |
| Yunlin           | 3         | 1.51%   |
| Pingtung City    | 3         | 1.51%   |
| Shulin District  | 2         | 1.01%   |
| Nantou City      | 2         | 1.01%   |
| Keelung          | 2         | 1.01%   |
| Zhubei           | 1         | 0.5%    |
| Yilan            | 1         | 0.5%    |
| Taichung City    | 1         | 0.5%    |
| Penghu County    | 1         | 0.5%    |
| Neihu            | 1         | 0.5%    |
| Miaoli           | 1         | 0.5%    |
| Fenjihu          | 1         | 0.5%    |
| Chenggong        | 1         | 0.5%    |
| Buxin            | 1         | 0.5%    |
| Bao'an           | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 28        | 37     | 10.94%  |
| Samsung Electronics            | 26        | 37     | 10.16%  |
| Crucial                        | 21        | 26     | 8.2%    |
| Seagate                        | 19        | 21     | 7.42%   |
| SK hynix                       | 17        | 20     | 6.64%   |
| SanDisk                        | 17        | 21     | 6.64%   |
| Kingston                       | 17        | 23     | 6.64%   |
| HGST                           | 16        | 17     | 6.25%   |
| Toshiba                        | 14        | 15     | 5.47%   |
| Unknown                        | 9         | 10     | 3.52%   |
| Micron Technology              | 9         | 9      | 3.52%   |
| Intel                          | 8         | 9      | 3.13%   |
| Hitachi                        | 7         | 8      | 2.73%   |
| ASMT                           | 4         | 4      | 1.56%   |
| Transcend                      | 3         | 3      | 1.17%   |
| JMicron Technology             | 3         | 6      | 1.17%   |
| AGI                            | 3         | 3      | 1.17%   |
| A-DATA Technology              | 3         | 3      | 1.17%   |
| Unknown                        | 3         | 3      | 1.17%   |
| SPCC                           | 2         | 3      | 0.78%   |
| Micron/Crucial Technology      | 2         | 2      | 0.78%   |
| ZHITAI                         | 1         | 1      | 0.39%   |
| Yangtze Memory Technologies    | 1         | 1      | 0.39%   |
| XPG                            | 1         | 1      | 0.39%   |
| USB3.2                         | 1         | 1      | 0.39%   |
| Union Memory                   | 1         | 1      | 0.39%   |
| Toshiba America Info Systems   | 1         | 2      | 0.39%   |
| StoreJet                       | 1         | 2      | 0.39%   |
| Solid State Storage Technology | 1         | 1      | 0.39%   |
| Silicon Motion                 | 1         | 1      | 0.39%   |
| Plextor                        | 1         | 1      | 0.39%   |
| Pioneer                        | 1         | 1      | 0.39%   |
| Phison                         | 1         | 1      | 0.39%   |
| OCZ                            | 1         | 1      | 0.39%   |
| NeoTech                        | 1         | 1      | 0.39%   |
| MyDigitalSSD                   | 1         | 1      | 0.39%   |
| MX                             | 1         | 1      | 0.39%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.39%   |
| LITEONIT                       | 1         | 1      | 0.39%   |
| LITEON                         | 1         | 1      | 0.39%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB               | 8         | 2.97%   |
| Crucial CT500MX500SSD1 500GB           | 7         | 2.6%    |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 1.86%   |
| Seagate ST1000LM049-2GH172 1TB         | 4         | 1.49%   |
| Unknown MMC Card  64GB                 | 3         | 1.12%   |
| Toshiba MQ01ABD100 1TB                 | 3         | 1.12%   |
| SanDisk NVMe SSD Drive 512GB           | 3         | 1.12%   |
| SanDisk NVMe SSD Drive 256GB           | 3         | 1.12%   |
| SanDisk NVMe SSD Drive 1TB             | 3         | 1.12%   |
| Crucial CT500MX500SSD4 500GB           | 3         | 1.12%   |
| Crucial CT240BX500SSD1 240GB           | 3         | 1.12%   |
| Crucial CT1000MX500SSD1 1TB            | 3         | 1.12%   |
| Unknown                                | 3         | 1.12%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 2         | 0.74%   |
| WDC WD10JPVX-22JC3T0 1TB               | 2         | 0.74%   |
| Unknown MMC Card  32GB                 | 2         | 0.74%   |
| Toshiba MQ04ABF100 1TB                 | 2         | 0.74%   |
| SPCC Solid State Disk 240GB            | 2         | 0.74%   |
| SK hynix NVMe SSD Drive 512GB          | 2         | 0.74%   |
| SK hynix HFM512GD3JX016N 512GB         | 2         | 0.74%   |
| SK hynix HFM512GD3JX013N 512GB         | 2         | 0.74%   |
| SK hynix BC711 NVMe 512GB              | 2         | 0.74%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.74%   |
| Samsung NVMe SSD Drive 1024GB          | 2         | 0.74%   |
| Samsung MZVLW256HEHP-00000 256GB       | 2         | 0.74%   |
| Micron 1100_MTFDDAV512TBN 512GB SSD    | 2         | 0.74%   |
| Kingston SA400S37240G 240GB SSD        | 2         | 0.74%   |
| Kingston SA400S37120G 120GB SSD        | 2         | 0.74%   |
| Kingston SA2000M8500G 500GB            | 2         | 0.74%   |
| Kingston RBUSNS8154P3512GJ1 512GB      | 2         | 0.74%   |
| Kingston NVMe SSD Drive 512GB          | 2         | 0.74%   |
| HGST HTS541010B7E610 1TB               | 2         | 0.74%   |
| HGST HTS541010A9E680 1TB               | 2         | 0.74%   |
| ASMT 2115 16GB                         | 2         | 0.74%   |
| ZHITAI TiPro7000 1TB                   | 1         | 0.37%   |
| Yangtze Memory NVMe SSD Drive 1TB      | 1         | 0.37%   |
| XPG NVMe SSD Drive 1024GB              | 1         | 0.37%   |
| WDC WDS500G3X0C-00SJG0 500GB           | 1         | 0.37%   |
| WDC WDS500G2B0B 500GB SSD              | 1         | 0.37%   |
| WDC WDS500G2B0A 500GB SSD              | 1         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| Seagate            | 19        | 20     | 27.94%  |
| HGST               | 16        | 17     | 23.53%  |
| WDC                | 11        | 13     | 16.18%  |
| Toshiba            | 9         | 10     | 13.24%  |
| Hitachi            | 7         | 8      | 10.29%  |
| ASMT               | 3         | 3      | 4.41%   |
| StoreJet           | 1         | 2      | 1.47%   |
| NeoTech            | 1         | 1      | 1.47%   |
| JMicron Technology | 1         | 3      | 1.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 19        | 23     | 22.62%  |
| Kingston            | 9         | 10     | 10.71%  |
| SanDisk             | 7         | 9      | 8.33%   |
| Samsung Electronics | 7         | 9      | 8.33%   |
| WDC                 | 5         | 7      | 5.95%   |
| Micron Technology   | 4         | 4      | 4.76%   |
| Intel               | 4         | 5      | 4.76%   |
| Transcend           | 3         | 3      | 3.57%   |
| Toshiba             | 3         | 3      | 3.57%   |
| SK hynix            | 3         | 3      | 3.57%   |
| A-DATA Technology   | 3         | 3      | 3.57%   |
| Unknown             | 3         | 3      | 3.57%   |
| SPCC                | 2         | 3      | 2.38%   |
| Plextor             | 1         | 1      | 1.19%   |
| OCZ                 | 1         | 1      | 1.19%   |
| MyDigitalSSD        | 1         | 1      | 1.19%   |
| MX                  | 1         | 1      | 1.19%   |
| LITEONIT            | 1         | 1      | 1.19%   |
| LITEON              | 1         | 1      | 1.19%   |
| JMicron Technology  | 1         | 1      | 1.19%   |
| Aura                | 1         | 1      | 1.19%   |
| ASMT                | 1         | 1      | 1.19%   |
| Apple               | 1         | 1      | 1.19%   |
| Apacer              | 1         | 1      | 1.19%   |
| AGI                 | 1         | 1      | 1.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 81        | 115    | 33.89%  |
| SSD     | 78        | 97     | 32.64%  |
| HDD     | 64        | 77     | 26.78%  |
| MMC     | 8         | 9      | 3.35%   |
| Unknown | 8         | 9      | 3.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 123       | 165    | 54.67%  |
| NVMe | 81        | 115    | 36%     |
| SAS  | 13        | 18     | 5.78%   |
| MMC  | 8         | 9      | 3.56%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 86        | 104    | 59.72%  |
| 0.51-1.0   | 51        | 61     | 35.42%  |
| 1.01-2.0   | 4         | 5      | 2.78%   |
| 10.01-20.0 | 2         | 2      | 1.39%   |
| 4.01-10.0  | 1         | 2      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 59        | 30.41%  |
| 101-250        | 57        | 29.38%  |
| 501-1000       | 23        | 11.86%  |
| 1-20           | 15        | 7.73%   |
| 1001-2000      | 12        | 6.19%   |
| 21-50          | 11        | 5.67%   |
| 51-100         | 11        | 5.67%   |
| 2001-3000      | 3         | 1.55%   |
| Unknown        | 2         | 1.03%   |
| More than 3000 | 1         | 0.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 88        | 44.9%   |
| 21-50          | 27        | 13.78%  |
| 51-100         | 25        | 12.76%  |
| 101-250        | 24        | 12.24%  |
| 251-500        | 19        | 9.69%   |
| 501-1000       | 10        | 5.1%    |
| Unknown        | 2         | 1.02%   |
| More than 3000 | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS512GDE9X073N 512GB           | 1         | 1      | 16.67%  |
| SK hynix HFS128G39MNC-2300A 128GB SSD          | 1         | 1      | 16.67%  |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 16.67%  |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 16.67%  |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 16.67%  |
| ASMT 2115 16GB                                 | 1         | 1      | 16.67%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| SK hynix          | 2         | 2      | 33.33%  |
| Micron Technology | 1         | 1      | 16.67%  |
| Hitachi           | 1         | 1      | 16.67%  |
| HGST              | 1         | 1      | 16.67%  |
| ASMT              | 1         | 1      | 16.67%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 33.33%  |
| HGST    | 1         | 1      | 33.33%  |
| ASMT    | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 50%     |
| SSD  | 2         | 2      | 33.33%  |
| NVMe | 1         | 1      | 16.67%  |

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
| Detected | 101       | 160    | 51.79%  |
| Works    | 88        | 141    | 45.13%  |
| Malfunc  | 6         | 6      | 3.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 133       | 55.19%  |
| Samsung Electronics            | 23        | 9.54%   |
| SanDisk                        | 20        | 8.3%    |
| AMD                            | 20        | 8.3%    |
| SK hynix                       | 14        | 5.81%   |
| Kingston Technology Company    | 8         | 3.32%   |
| Micron Technology              | 6         | 2.49%   |
| Toshiba America Info Systems   | 4         | 1.66%   |
| Micron/Crucial Technology      | 4         | 1.66%   |
| Yangtze Memory Technologies    | 1         | 0.41%   |
| Union Memory (Shenzhen)        | 1         | 0.41%   |
| Solid State Storage Technology | 1         | 0.41%   |
| Silicon Motion                 | 1         | 0.41%   |
| Phison Electronics             | 1         | 0.41%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.41%   |
| Marvell Technology Group       | 1         | 0.41%   |
| Lite-On Technology             | 1         | 0.41%   |
| ADATA Technology               | 1         | 0.41%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 7.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 18        | 7.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 14        | 5.6%    |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 4.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 12        | 4.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 11        | 4.4%    |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 9         | 3.6%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 3.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 3.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.2%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 3.2%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 8         | 3.2%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.8%    |
| Micron Non-Volatile memory controller                                          | 6         | 2.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 6         | 2.4%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 2%      |
| Samsung NVMe SSD Controller 980                                                | 5         | 2%      |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 4         | 1.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 1.6%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 1.2%    |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.2%    |
| Kingston Company A2000 NVMe SSD                                                | 3         | 1.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.2%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 3         | 1.2%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 3         | 1.2%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 1.2%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.8%    |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.8%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.8%    |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.8%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.8%    |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 2         | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.8%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 2         | 0.8%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.8%    |
| Yangtze Memory ZHITAI TiPro7000                                                | 1         | 0.4%    |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.4%    |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 1         | 0.4%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 134       | 55.83%  |
| NVMe | 82        | 34.17%  |
| RAID | 20        | 8.33%   |
| IDE  | 4         | 1.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 155       | 83.78%  |
| AMD    | 30        | 16.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz         | 6         | 3.24%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 6         | 3.24%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 6         | 3.24%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 5         | 2.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz          | 4         | 2.16%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 4         | 2.16%   |
| Intel Core i7-4500U CPU @ 1.80GHz          | 4         | 2.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 4         | 2.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 3         | 1.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz          | 3         | 1.62%   |
| Intel Core i5-3230M CPU @ 2.60GHz          | 3         | 1.62%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 3         | 1.62%   |
| AMD Ryzen 7 4800HS with Radeon Graphics    | 3         | 1.62%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 2         | 1.08%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 2         | 1.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 2         | 1.08%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 2         | 1.08%   |
| Intel Core i7-2670QM CPU @ 2.20GHz         | 2         | 1.08%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 2         | 1.08%   |
| Intel Core i5-8300H CPU @ 2.30GHz          | 2         | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 2         | 1.08%   |
| Intel Core i5-4210U CPU @ 1.70GHz          | 2         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz          | 2         | 1.08%   |
| Intel Core i5-2450M CPU @ 2.50GHz          | 2         | 1.08%   |
| Intel Core i5-2410M CPU @ 2.30GHz          | 2         | 1.08%   |
| Intel Core i5-1035G4 CPU @ 1.10GHz         | 2         | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 2         | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz          | 2         | 1.08%   |
| Intel Core i5 CPU M 460 @ 2.53GHz          | 2         | 1.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz          | 2         | 1.08%   |
| Intel Celeron CPU 3955U @ 2.00GHz          | 2         | 1.08%   |
| Intel 12th Gen Core i7-1260P               | 2         | 1.08%   |
| Intel 12th Gen Core i5-12500H              | 2         | 1.08%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz    | 2         | 1.08%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 2         | 1.08%   |
| AMD Ryzen 7 5800U with Radeon Graphics     | 2         | 1.08%   |
| AMD Ryzen 7 5700U with Radeon Graphics     | 2         | 1.08%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 2         | 1.08%   |
| AMD Ryzen 5 5625U with Radeon Graphics     | 2         | 1.08%   |
| AMD Ryzen 5 5500U with Radeon Graphics     | 2         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i7      | 51        | 27.57%  |
| Intel Core i5      | 50        | 27.03%  |
| Other              | 22        | 11.89%  |
| AMD Ryzen 7        | 12        | 6.49%   |
| Intel Core i3      | 7         | 3.78%   |
| Intel Celeron      | 7         | 3.78%   |
| Intel Pentium      | 6         | 3.24%   |
| AMD Ryzen 5        | 6         | 3.24%   |
| Intel Genuine      | 3         | 1.62%   |
| Intel Core 2 Duo   | 3         | 1.62%   |
| Intel Atom         | 3         | 1.62%   |
| AMD Ryzen 9        | 3         | 1.62%   |
| AMD Ryzen 7 PRO    | 3         | 1.62%   |
| AMD Ryzen 3        | 2         | 1.08%   |
| Intel Xeon         | 1         | 0.54%   |
| Intel Pentium M    | 1         | 0.54%   |
| Intel Pentium Dual | 1         | 0.54%   |
| Intel Core 2 Solo  | 1         | 0.54%   |
| AMD FX             | 1         | 0.54%   |
| AMD Embedded       | 1         | 0.54%   |
| AMD E2             | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 72        | 38.92%  |
| 2      | 68        | 36.76%  |
| 8      | 21        | 11.35%  |
| 6      | 12        | 6.49%   |
| 1      | 5         | 2.7%    |
| 12     | 4         | 2.16%   |
| 10     | 2         | 1.08%   |
| 14     | 1         | 0.54%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 185       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 151       | 81.62%  |
| 1      | 34        | 18.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 182       | 98.38%  |
| 32-bit         | 2         | 1.08%   |
| Unknown        | 1         | 0.54%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 36        | 18.95%  |
| 0x306a9    | 11        | 5.79%   |
| 0x806c1    | 10        | 5.26%   |
| 0x40651    | 10        | 5.26%   |
| 0x206a7    | 10        | 5.26%   |
| 0x806ea    | 8         | 4.21%   |
| 0x906e9    | 7         | 3.68%   |
| 0x806eb    | 6         | 3.16%   |
| 0x806e9    | 6         | 3.16%   |
| 0x20655    | 6         | 3.16%   |
| 0x0a50000c | 6         | 3.16%   |
| 0x906ea    | 5         | 2.63%   |
| 0x506e3    | 5         | 2.63%   |
| 0x406e3    | 5         | 2.63%   |
| 0x306d4    | 5         | 2.63%   |
| 0x706e5    | 4         | 2.11%   |
| 0x08600106 | 4         | 2.11%   |
| 0x906a3    | 3         | 1.58%   |
| 0x806ec    | 3         | 1.58%   |
| 0x1067a    | 3         | 1.58%   |
| 0x08608103 | 3         | 1.58%   |
| 0x906ed    | 2         | 1.05%   |
| 0x906a4    | 2         | 1.05%   |
| 0x706a8    | 2         | 1.05%   |
| 0x6fd      | 2         | 1.05%   |
| 0x406c4    | 2         | 1.05%   |
| 0x306c3    | 2         | 1.05%   |
| 0x806d1    | 1         | 0.53%   |
| 0x706a1    | 1         | 0.53%   |
| 0x506c9    | 1         | 0.53%   |
| 0x406c3    | 1         | 0.53%   |
| 0x40661    | 1         | 0.53%   |
| 0x306a8    | 1         | 0.53%   |
| 0x30678    | 1         | 0.53%   |
| 0x20652    | 1         | 0.53%   |
| 0x106e5    | 1         | 0.53%   |
| 0x106c2    | 1         | 0.53%   |
| 0x10676    | 1         | 0.53%   |
| 0x0a404101 | 1         | 0.53%   |
| 0x08608102 | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 24.32%  |
| Haswell          | 14        | 7.57%   |
| Skylake          | 13        | 7.03%   |
| IvyBridge        | 13        | 7.03%   |
| SandyBridge      | 12        | 6.49%   |
| TigerLake        | 11        | 5.95%   |
| Westmere         | 10        | 5.41%   |
| Zen 3            | 9         | 4.86%   |
| Zen 2            | 9         | 4.86%   |
| Unknown          | 9         | 4.86%   |
| Penryn           | 5         | 2.7%    |
| IceLake          | 5         | 2.7%    |
| Broadwell        | 5         | 2.7%    |
| Alderlake Hybrid | 5         | 2.7%    |
| Silvermont       | 4         | 2.16%   |
| Goldmont plus    | 3         | 1.62%   |
| Excavator        | 3         | 1.62%   |
| Zen+             | 2         | 1.08%   |
| Core             | 2         | 1.08%   |
| Zen              | 1         | 0.54%   |
| P6               | 1         | 0.54%   |
| Nehalem          | 1         | 0.54%   |
| Goldmont         | 1         | 0.54%   |
| Bonnell          | 1         | 0.54%   |
| Bobcat           | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 145       | 54.72%  |
| Nvidia | 73        | 27.55%  |
| AMD    | 47        | 17.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 4.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 4.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 4.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 3.36%   |
| Intel UHD Graphics 620                                                                   | 9         | 3.36%   |
| AMD Renoir                                                                               | 9         | 3.36%   |
| Intel HD Graphics 630                                                                    | 8         | 2.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 8         | 2.99%   |
| Intel HD Graphics 530                                                                    | 7         | 2.61%   |
| Intel HD Graphics 620                                                                    | 6         | 2.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.24%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 5         | 1.87%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.87%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.87%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 5         | 1.87%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.49%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 4         | 1.49%   |
| AMD Lucienne                                                                             | 4         | 1.49%   |
| Nvidia GP107M [GeForce MX350]                                                            | 3         | 1.12%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 1.12%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 3         | 1.12%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 1.12%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 3         | 1.12%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.12%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.12%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.12%   |
| Intel HD Graphics 510                                                                    | 3         | 1.12%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.12%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.12%   |
| AMD Madison [Mobility Radeon HD 5650/5750 / 6530M/6550M]                                 | 3         | 1.12%   |
| AMD Barcelo                                                                              | 3         | 1.12%   |
| Nvidia GP108M [GeForce MX330]                                                            | 2         | 0.75%   |
| Nvidia GP108M [GeForce MX230]                                                            | 2         | 0.75%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.75%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 2         | 0.75%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 2         | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 2         | 0.75%   |
| Intel Iris Plus Graphics G7                                                              | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 70        | 37.84%  |
| Intel + Nvidia | 63        | 34.05%  |
| 1 x AMD        | 29        | 15.68%  |
| Intel + AMD    | 12        | 6.49%   |
| 1 x Nvidia     | 5         | 2.7%    |
| AMD + Nvidia   | 5         | 2.7%    |
| 2 x AMD        | 1         | 0.54%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 148       | 78.31%  |
| Proprietary | 37        | 19.58%  |
| Unknown     | 4         | 2.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 105       | 55.26%  |
| 1.01-2.0   | 31        | 16.32%  |
| 0.01-0.5   | 27        | 14.21%  |
| 3.01-4.0   | 12        | 6.32%   |
| 0.51-1.0   | 8         | 4.21%   |
| 5.01-6.0   | 6         | 3.16%   |
| 7.01-8.0   | 1         | 0.53%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 54        | 25.84%  |
| BOE                     | 30        | 14.35%  |
| Chimei Innolux          | 29        | 13.88%  |
| LG Display              | 28        | 13.4%   |
| Samsung Electronics     | 11        | 5.26%   |
| Ancor Communications    | 7         | 3.35%   |
| BenQ                    | 6         | 2.87%   |
| Sharp                   | 5         | 2.39%   |
| Dell                    | 5         | 2.39%   |
| PANDA                   | 3         | 1.44%   |
| Lenovo                  | 3         | 1.44%   |
| ASUSTek Computer        | 3         | 1.44%   |
| Acer                    | 3         | 1.44%   |
| ViewSonic               | 2         | 0.96%   |
| Philips                 | 2         | 0.96%   |
| Eizo                    | 2         | 0.96%   |
| TMX                     | 1         | 0.48%   |
| Sony                    | 1         | 0.48%   |
| Panasonic               | 1         | 0.48%   |
| Olevia                  | 1         | 0.48%   |
| NEX                     | 1         | 0.48%   |
| MStar                   | 1         | 0.48%   |
| LG Philips              | 1         | 0.48%   |
| InfoVision              | 1         | 0.48%   |
| Goldstar                | 1         | 0.48%   |
| CHR                     | 1         | 0.48%   |
| Chi Mei Optoelectronics | 1         | 0.48%   |
| BOE Technology Group    | 1         | 0.48%   |
| AVX                     | 1         | 0.48%   |
| Apple                   | 1         | 0.48%   |
| AOC                     | 1         | 0.48%   |
| AGT                     | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 1.9%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 3         | 1.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 1.42%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 3         | 1.42%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 1.42%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.42%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch         | 3         | 1.42%   |
| Philips PHL 288P6L PHL08F2 3840x2160 621x341mm 27.9-inch              | 2         | 0.95%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 0.95%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch          | 2         | 0.95%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 2         | 0.95%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                 | 2         | 0.95%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 2         | 0.95%   |
| BOE LCD Monitor BOE08A6 1920x1080 294x165mm 13.3-inch                 | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO332C 1366x768 293x164mm 13.2-inch         | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO323D 1920x1080 309x174mm 14.0-inch        | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 2         | 0.95%   |
| AU Optronics LCD Monitor AUO253D 1920x1080 309x174mm 14.0-inch        | 2         | 0.95%   |
| ASUSTek Computer VA24E AUS24D1 1920x1080 527x296mm 23.8-inch          | 2         | 0.95%   |
| Ancor Communications ASUS VP247 ACI24C7 1920x1080 521x293mm 23.5-inch | 2         | 0.95%   |
| ViewSonic VX2376 Series VSC3B32 1920x1080 509x286mm 23.0-inch         | 1         | 0.47%   |
| ViewSonic VA2732-FHD VSC0D3A 1920x1080 598x336mm 27.0-inch            | 1         | 0.47%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 1         | 0.47%   |
| Sony TV SNY8200 1920x1080 560x420mm 27.6-inch                         | 1         | 0.47%   |
| Sharp LQ140M1JW46 SHP14F1 1920x1080 309x174mm 14.0-inch               | 1         | 0.47%   |
| Sharp LQ133M1JW07 SHP1435 1920x1080 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14AE 1920x1080 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM041F 2048x1152 510x287mm 23.0-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC554E 1024x600 223x125mm 10.1-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC314B 1600x900 344x194mm 15.5-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 309x174mm 14.0-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 105       | 56.15%  |
| 1366x768 (WXGA)    | 42        | 22.46%  |
| 3840x2160 (4K)     | 8         | 4.28%   |
| 2560x1440 (QHD)    | 4         | 2.14%   |
| 1600x900 (HD+)     | 4         | 2.14%   |
| 2560x1600          | 3         | 1.6%    |
| 1920x1200 (WUXGA)  | 3         | 1.6%    |
| 2880x1800          | 2         | 1.07%   |
| 1680x1050 (WSXGA+) | 2         | 1.07%   |
| 1280x800 (WXGA)    | 2         | 1.07%   |
| 3840x1080          | 1         | 0.53%   |
| 3200x1800 (QHD+)   | 1         | 0.53%   |
| 2560x1080          | 1         | 0.53%   |
| 2288x1287          | 1         | 0.53%   |
| 2256x1504          | 1         | 0.53%   |
| 2048x1152          | 1         | 0.53%   |
| 1680x945           | 1         | 0.53%   |
| 1440x900 (WXGA+)   | 1         | 0.53%   |
| 1280x720 (HD)      | 1         | 0.53%   |
| 1280x1024 (SXGA)   | 1         | 0.53%   |
| 1024x600           | 1         | 0.53%   |
| Unknown            | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 69        | 33.17%  |
| 14      | 38        | 18.27%  |
| 13      | 35        | 16.83%  |
| 24      | 12        | 5.77%   |
| 23      | 10        | 4.81%   |
| 17      | 8         | 3.85%   |
| 27      | 7         | 3.37%   |
| 11      | 6         | 2.88%   |
| 21      | 4         | 1.92%   |
| 12      | 4         | 1.92%   |
| 22      | 3         | 1.44%   |
| 16      | 3         | 1.44%   |
| 18      | 2         | 0.96%   |
| Unknown | 2         | 0.96%   |
| 55      | 1         | 0.48%   |
| 52      | 1         | 0.48%   |
| 34      | 1         | 0.48%   |
| 31      | 1         | 0.48%   |
| 10      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 124       | 59.9%   |
| 201-300     | 30        | 14.49%  |
| 501-600     | 26        | 12.56%  |
| 351-400     | 10        | 4.83%   |
| 401-500     | 9         | 4.35%   |
| 601-700     | 3         | 1.45%   |
| 1001-1500   | 2         | 0.97%   |
| Unknown     | 2         | 0.97%   |
| 701-800     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 160       | 88.89%  |
| 16/10   | 17        | 9.44%   |
| 3/2     | 1         | 0.56%   |
| 21/9    | 1         | 0.56%   |
| Unknown | 1         | 0.56%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 69        | 33.33%  |
| 81-90          | 55        | 26.57%  |
| 201-250        | 26        | 12.56%  |
| 71-80          | 19        | 9.18%   |
| 121-130        | 8         | 3.86%   |
| 301-350        | 7         | 3.38%   |
| 51-60          | 6         | 2.9%    |
| 61-70          | 3         | 1.45%   |
| 111-120        | 3         | 1.45%   |
| More than 1000 | 2         | 0.97%   |
| 351-500        | 2         | 0.97%   |
| 251-300        | 2         | 0.97%   |
| 141-150        | 2         | 0.97%   |
| Unknown        | 2         | 0.97%   |
| 41-50          | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 99        | 48.06%  |
| 101-120       | 44        | 21.36%  |
| 51-100        | 31        | 15.05%  |
| 161-240       | 21        | 10.19%  |
| More than 240 | 7         | 3.4%    |
| 1-50          | 2         | 0.97%   |
| Unknown       | 2         | 0.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 151       | 80.75%  |
| 2     | 30        | 16.04%  |
| 0     | 4         | 2.14%   |
| 3     | 2         | 1.07%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Intel                    | 112       | 36.6%   |
| Realtek Semiconductor    | 93        | 30.39%  |
| Qualcomm Atheros         | 50        | 16.34%  |
| Broadcom                 | 18        | 5.88%   |
| MediaTek                 | 9         | 2.94%   |
| Broadcom Limited         | 5         | 1.63%   |
| ASIX Electronics         | 4         | 1.31%   |
| Ralink                   | 3         | 0.98%   |
| TP-Link                  | 2         | 0.65%   |
| OPPO Electronics         | 2         | 0.65%   |
| Marvell Technology Group | 2         | 0.65%   |
| Edimax Technology        | 2         | 0.65%   |
| U-Blox                   | 1         | 0.33%   |
| Lenovo                   | 1         | 0.33%   |
| D-Link                   | 1         | 0.33%   |
| ASUSTek Computer         | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65        | 18.84%  |
| Intel Wi-Fi 6 AX200                                               | 16        | 4.64%   |
| Intel Wireless 8265 / 8275                                        | 12        | 3.48%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 3.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 2.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 7         | 2.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 2.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 2.03%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 1.74%   |
| Intel Wireless 7260                                               | 6         | 1.74%   |
| Intel Wireless 3165                                               | 6         | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 5         | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.45%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.45%   |
| Intel Wireless 7265                                               | 5         | 1.45%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.16%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 4         | 1.16%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 1.16%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.16%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 1.16%   |
| Broadcom BCM43225 802.11b/g/n                                     | 4         | 1.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 0.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.87%   |
| Intel Wireless 8260                                               | 3         | 0.87%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.87%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.87%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.87%   |
| Intel Centrino Advanced-N 6235                                    | 3         | 0.87%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.87%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 106       | 58.24%  |
| Qualcomm Atheros      | 34        | 18.68%  |
| Broadcom              | 12        | 6.59%   |
| Realtek Semiconductor | 10        | 5.49%   |
| MediaTek              | 9         | 4.95%   |
| Ralink                | 3         | 1.65%   |
| Broadcom Limited      | 3         | 1.65%   |
| Edimax Technology     | 2         | 1.1%    |
| TP-Link               | 1         | 0.55%   |
| D-Link                | 1         | 0.55%   |
| ASUSTek Computer      | 1         | 0.55%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 16        | 8.79%   |
| Intel Wireless 8265 / 8275                                              | 12        | 6.59%   |
| Intel Wi-Fi 6 AX201                                                     | 11        | 6.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 7         | 3.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 3.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 3.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 3.85%   |
| Intel Wireless 7260                                                     | 6         | 3.3%    |
| Intel Wireless 3165                                                     | 6         | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 2.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 5         | 2.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.75%   |
| Intel Wireless 7265                                                     | 5         | 2.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 2.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 2.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 2.2%    |
| Broadcom BCM43225 802.11b/g/n                                           | 4         | 2.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.65%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.65%   |
| Intel Wireless 8260                                                     | 3         | 1.65%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 1.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 2         | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 1.1%    |
| Intel Wireless-AC 9260                                                  | 2         | 1.1%    |
| Intel Wireless 3160                                                     | 2         | 1.1%    |
| Intel WiFi Link 5100                                                    | 2         | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.1%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2         | 1.1%    |
| Intel Centrino Advanced-N 6200                                          | 2         | 1.1%    |
| TP-Link Archer T4U ver.3                                                | 1         | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.55%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 1         | 0.55%   |
| Ralink RT3091 Wireless 802.11n 1T/2R PCIe                               | 1         | 0.55%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.55%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 1         | 0.55%   |
| MediaTek MT7612U 802.11a/b/g/n/ac Wireless Adapter                      | 1         | 0.55%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 88        | 56.05%  |
| Qualcomm Atheros         | 25        | 15.92%  |
| Intel                    | 25        | 15.92%  |
| Broadcom                 | 7         | 4.46%   |
| ASIX Electronics         | 4         | 2.55%   |
| OPPO Electronics         | 2         | 1.27%   |
| Marvell Technology Group | 2         | 1.27%   |
| Broadcom Limited         | 2         | 1.27%   |
| TP-Link                  | 1         | 0.64%   |
| Lenovo                   | 1         | 0.64%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65        | 40.12%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 6.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 10        | 6.17%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 3.7%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 2.47%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 4         | 2.47%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 2.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 1.85%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.85%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.85%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.85%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.85%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.23%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.23%   |
| OPPO SDM665-IDP _SN:18689828                                      | 2         | 1.23%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.23%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                 | 2         | 1.23%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.62%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.62%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.62%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.62%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.62%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.62%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.62%   |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 1         | 0.62%   |
| Lenovo USB-C Hub                                                  | 1         | 0.62%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.62%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.62%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.62%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.62%   |
| Intel Centrino Advanced-N + WiMAX 6250                            | 1         | 0.62%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 0.62%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 177       | 54.63%  |
| Ethernet | 146       | 45.06%  |
| Modem    | 1         | 0.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 73.47%  |
| Ethernet | 52        | 26.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 133       | 71.89%  |
| 1     | 51        | 27.57%  |
| 5     | 1         | 0.54%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 170       | 91.89%  |
| Yes  | 15        | 8.11%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 95        | 57.93%  |
| Foxconn / Hon Hai               | 12        | 7.32%   |
| Broadcom                        | 12        | 7.32%   |
| Qualcomm Atheros Communications | 11        | 6.71%   |
| Lite-On Technology              | 9         | 5.49%   |
| IMC Networks                    | 9         | 5.49%   |
| Realtek Semiconductor           | 5         | 3.05%   |
| Realtek                         | 2         | 1.22%   |
| Ralink                          | 2         | 1.22%   |
| Hewlett-Packard                 | 2         | 1.22%   |
| ASUSTek Computer                | 2         | 1.22%   |
| Apple                           | 2         | 1.22%   |
| Toshiba                         | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 36        | 21.95%  |
| Intel AX201 Bluetooth                                                               | 18        | 10.98%  |
| Intel AX200 Bluetooth                                                               | 16        | 9.76%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 6.71%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 3.05%   |
| Intel Bluetooth Device                                                              | 5         | 3.05%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 3.05%   |
| Realtek Bluetooth Radio                                                             | 4         | 2.44%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.44%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.83%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 1.83%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.83%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 1.83%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 1.83%   |
| Realtek Bluetooth Radio                                                             | 2         | 1.22%   |
| Ralink RT3290 Bluetooth                                                             | 2         | 1.22%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 2         | 1.22%   |
| Lite-On Bluetooth Device                                                            | 2         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 2         | 1.22%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 1.22%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.22%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.22%   |
| Foxconn / Hon Hai Acer Bluetooth module                                             | 2         | 1.22%   |
| Broadcom Bluetooth                                                                  | 2         | 1.22%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 1.22%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.22%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.61%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.61%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.61%   |
| Lite-On Wireless_Device                                                             | 1         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.61%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.61%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.61%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.61%   |
| IMC Networks Bluetooth                                                              | 1         | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.61%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.61%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 152       | 67.56%  |
| AMD                     | 37        | 16.44%  |
| Nvidia                  | 29        | 12.89%  |
| Realtek Semiconductor   | 1         | 0.44%   |
| GN Netcom               | 1         | 0.44%   |
| ESS Technology          | 1         | 0.44%   |
| Dell                    | 1         | 0.44%   |
| Cambridge Silicon Radio | 1         | 0.44%   |
| C-Media Electronics     | 1         | 0.44%   |
| ASUSTek Computer        | 1         | 0.44%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 26        | 9.42%   |
| Intel Sunrise Point-LP HD Audio                                            | 22        | 7.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 22        | 7.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 4.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12        | 4.35%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 3.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 3.99%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 3.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 11        | 3.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 10        | 3.62%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 2.9%    |
| Intel CM238 HD Audio Controller                                            | 7         | 2.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 7         | 2.54%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 6         | 2.17%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 1.81%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.81%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.81%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.45%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 4         | 1.45%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 3         | 1.09%   |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.09%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.09%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.09%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.09%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 3         | 1.09%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                             | 3         | 1.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.09%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 0.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 0.72%   |
| Intel USB PnP Sound Device                                                 | 2         | 0.72%   |
| Intel Comet Lake PCH-LP cAVS                                               | 2         | 0.72%   |
| AMD Kabini HDMI/DP Audio                                                   | 2         | 0.72%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.36%   |
| Nvidia TU106 High Definition Audio Controller                              | 1         | 0.36%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.36%   |
| Nvidia High Definition Audio Controller                                    | 1         | 0.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.36%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 37        | 25.34%  |
| Samsung Electronics | 32        | 21.92%  |
| Micron Technology   | 20        | 13.7%   |
| Kingston            | 16        | 10.96%  |
| Crucial             | 12        | 8.22%   |
| Unknown             | 5         | 3.42%   |
| Transcend           | 5         | 3.42%   |
| Apacer              | 3         | 2.05%   |
| Ramaxel Technology  | 2         | 1.37%   |
| G-Alantic           | 2         | 1.37%   |
| A-DATA Technology   | 2         | 1.37%   |
| Unknown (ABCD)      | 1         | 0.68%   |
| Unknown (08AE)      | 1         | 0.68%   |
| Patriot             | 1         | 0.68%   |
| Nanya Technology    | 1         | 0.68%   |
| Goldkey             | 1         | 0.68%   |
| G.Skill             | 1         | 0.68%   |
| Elpida              | 1         | 0.68%   |
| Avant               | 1         | 0.68%   |
| ASint Technology    | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.89%   |
| Kingston RAM 9905624-033.A00G 8GB SODIMM DDR4 2400MT/s           | 3         | 1.89%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.26%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 1.26%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 1.26%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 1.26%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 1.26%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.26%   |
| Samsung RAM M471A1K43CB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.26%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.26%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.26%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.26%   |
| Kingston RAM MSI24D4S7S8MB-8 8GB SODIMM DDR4 2400MT/s            | 2         | 1.26%   |
| G-Alantic RAM D4SS12161SH26A-C 4GB SODIMM DDR4 2133MT/s          | 2         | 1.26%   |
| Crucial RAM CT8G4SFS632A.C4FE 8GB SODIMM DDR4 3200MT/s           | 2         | 1.26%   |
| Crucial RAM CT16G4SFD832A.M16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 1.26%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 8192MB SODIMM LPDDR4 4266MT/s                 | 1         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.63%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.63%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                    | 1         | 0.63%   |
| Unknown RAM Module 1024MB SODIMM DDR2 800MT/s                    | 1         | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.63%   |
| Unknown (08AE) RAM Module 4GB SODIMM DDR3 1600MT/s               | 1         | 0.63%   |
| Transcend RAM TS512MSK64V6N 4096MB SODIMM DDR3 1600MT/s          | 1         | 0.63%   |
| Transcend RAM Module 16GB SODIMM DDR4 3200MT/s                   | 1         | 0.63%   |
| Transcend RAM JM3200HSE-16G 16384MB SODIMM DDR4 3200MT/s         | 1         | 0.63%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 0.63%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.63%   |
| SK hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 0.63%   |
| SK hynix RAM Module 4GB SODIMM LPDDR3 1600MT/s                   | 1         | 0.63%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.63%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.63%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 3200MT/s                 | 1         | 0.63%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 0.63%   |
| SK hynix RAM Module 1024MB SODIMM DDR2 533MT/s                   | 1         | 0.63%   |
| SK hynix RAM HMT851S6AMR6A-PB 4GB Chip DDR3 1600MT/s             | 1         | 0.63%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.63%   |
| SK hynix RAM HMT451S6AFR6A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.63%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 1         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 65        | 56.03%  |
| DDR3    | 26        | 22.41%  |
| LPDDR4  | 12        | 10.34%  |
| LPDDR3  | 8         | 6.9%    |
| DDR2    | 2         | 1.72%   |
| LPDDR5  | 1         | 0.86%   |
| DDR5    | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 95        | 81.9%   |
| Row Of Chips | 19        | 16.38%  |
| DIMM         | 1         | 0.86%   |
| Chip         | 1         | 0.86%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 53        | 41.73%  |
| 4096  | 37        | 29.13%  |
| 16384 | 21        | 16.54%  |
| 32768 | 7         | 5.51%   |
| 2048  | 7         | 5.51%   |
| 1024  | 2         | 1.57%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 33        | 27.05%  |
| 2667  | 22        | 18.03%  |
| 1600  | 20        | 16.39%  |
| 2400  | 11        | 9.02%   |
| 2133  | 9         | 7.38%   |
| 4267  | 4         | 3.28%   |
| 1334  | 4         | 3.28%   |
| 4266  | 3         | 2.46%   |
| 1867  | 3         | 2.46%   |
| 6400  | 2         | 1.64%   |
| 4800  | 2         | 1.64%   |
| 800   | 2         | 1.64%   |
| 8400  | 1         | 0.82%   |
| 3733  | 1         | 0.82%   |
| 3266  | 1         | 0.82%   |
| 2000  | 1         | 0.82%   |
| 1067  | 1         | 0.82%   |
| 1066  | 1         | 0.82%   |
| 533   | 1         | 0.82%   |

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
| Chicony Electronics                    | 45        | 29.22%  |
| IMC Networks                           | 21        | 13.64%  |
| Realtek Semiconductor                  | 18        | 11.69%  |
| Quanta                                 | 10        | 6.49%   |
| Sunplus Innovation Technology          | 9         | 5.84%   |
| Microdia                               | 9         | 5.84%   |
| Acer                                   | 9         | 5.84%   |
| Suyin                                  | 5         | 3.25%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.25%   |
| ALi                                    | 3         | 1.95%   |
| Syntek                                 | 2         | 1.3%    |
| Sunplus Technology                     | 2         | 1.3%    |
| Ricoh                                  | 2         | 1.3%    |
| Lite-On Technology                     | 2         | 1.3%    |
| Lenovo                                 | 2         | 1.3%    |
| Apple                                  | 2         | 1.3%    |
| Sonix Technology                       | 1         | 0.65%   |
| Silicon Motion                         | 1         | 0.65%   |
| Samsung Electronics                    | 1         | 0.65%   |
| Luxvisions Innotech Limited            | 1         | 0.65%   |
| Logitech                               | 1         | 0.65%   |
| Google                                 | 1         | 0.65%   |
| Generalplus Technology                 | 1         | 0.65%   |
| Foxconn / Hon Hai                      | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                                          | 9         | 5.81%   |
| Chicony Integrated Camera                                                  | 8         | 5.16%   |
| Chicony HD WebCam                                                          | 8         | 5.16%   |
| Realtek Integrated_Webcam_HD                                               | 5         | 3.23%   |
| Chicony HP HD Camera                                                       | 5         | 3.23%   |
| Sunplus HD WebCam                                                          | 4         | 2.58%   |
| Quanta HD User Facing                                                      | 4         | 2.58%   |
| Microdia Integrated_Webcam_HD                                              | 4         | 2.58%   |
| IMC Networks Integrated Camera                                             | 4         | 2.58%   |
| Realtek USB Camera                                                         | 3         | 1.94%   |
| Realtek HD WebCam                                                          | 3         | 1.94%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 1.94%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 1.94%   |
| Chicony USB2.0 HD UVC WebCam                                               | 3         | 1.94%   |
| Chicony Lenovo EasyCamera                                                  | 3         | 1.94%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 1.94%   |
| ALi Gateway Webcam                                                         | 3         | 1.94%   |
| Acer HD Webcam                                                             | 3         | 1.94%   |
| Sunplus 1.3M HD WebCam                                                     | 2         | 1.29%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 1.29%   |
| Realtek USB2.0 HD UVC WebCam                                               | 2         | 1.29%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 1.29%   |
| IMC Networks UVC VGA Webcam                                                | 2         | 1.29%   |
| Chicony Webcam                                                             | 2         | 1.29%   |
| Chicony USB2.0 VGA UVC WebCam                                              | 2         | 1.29%   |
| Chicony USB 2.0 Webcam Device                                              | 2         | 1.29%   |
| Chicony HD User Facing                                                     | 2         | 1.29%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 2         | 1.29%   |
| Acer BisonCam, NB Pro                                                      | 2         | 1.29%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.65%   |
| Syntek HP TrueVision HD                                                    | 1         | 0.65%   |
| Suyin UVC 1.3MPixel WebCam                                                 | 1         | 0.65%   |
| Suyin Acer/Lenovo Webcam [CN0316]                                          | 1         | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 1         | 0.65%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 0.65%   |
| Suyin 1.3M HD WebCam                                                       | 1         | 0.65%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.65%   |
| Sunplus HP Truevision HD                                                   | 1         | 0.65%   |
| Sunplus HD User Facing                                                     | 1         | 0.65%   |
| Sonix USB2.0 HD UVC WebCam                                                 | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 26.83%  |
| Validity Sensors           | 8         | 19.51%  |
| LighTuning Technology      | 8         | 19.51%  |
| Upek                       | 4         | 9.76%   |
| Shenzhen Goodix Technology | 4         | 9.76%   |
| Elan Microelectronics      | 4         | 9.76%   |
| AuthenTec                  | 2         | 4.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 4         | 9.76%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 4         | 9.76%   |
| Unknown                                                    | 4         | 9.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                | 3         | 7.32%   |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 7.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                  | 3         | 7.32%   |
| Elan ELAN:Fingerprint                                      | 3         | 7.32%   |
| Validity Sensors VFS Fingerprint sensor                    | 2         | 4.88%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 4.88%   |
| Synaptics Metallica MIS Touch Fingerprint Reader           | 2         | 4.88%   |
| Validity Sensors VFS495 Fingerprint Reader                 | 1         | 2.44%   |
| Validity Sensors VFS301 Fingerprint Reader                 | 1         | 2.44%   |
| Validity Sensors Fingerprint scanner                       | 1         | 2.44%   |
| Synaptics  WBDI Fingerprint Reader - USB 052               | 1         | 2.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 1         | 2.44%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader          | 1         | 2.44%   |
| Shenzhen Goodix Fingerprint Reader                         | 1         | 2.44%   |
| LighTuning Fingerprint Reader                              | 1         | 2.44%   |
| Elan fingerprint sensor [FeinTech FPS00200]                | 1         | 2.44%   |
| AuthenTec AES2810                                          | 1         | 2.44%   |
| AuthenTec AES1660 Fingerprint Sensor                       | 1         | 2.44%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 3         | 37.5%   |
| Alcor Micro           | 3         | 37.5%   |
| Upek                  | 1         | 12.5%   |
| Gemalto (was Gemplus) | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 2         | 25%     |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 12.5%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 111       | 58.12%  |
| 1     | 63        | 32.98%  |
| 2     | 15        | 7.85%   |
| 4     | 1         | 0.52%   |
| 3     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 41        | 45.05%  |
| Graphics card            | 20        | 21.98%  |
| Chipcard                 | 7         | 7.69%   |
| Camera                   | 5         | 5.49%   |
| Multimedia controller    | 4         | 4.4%    |
| Net/wireless             | 3         | 3.3%    |
| Card reader              | 3         | 3.3%    |
| Bluetooth                | 3         | 3.3%    |
| Net/ethernet             | 2         | 2.2%    |
| Storage/nvme             | 1         | 1.1%    |
| Sound                    | 1         | 1.1%    |
| Communication controller | 1         | 1.1%    |

